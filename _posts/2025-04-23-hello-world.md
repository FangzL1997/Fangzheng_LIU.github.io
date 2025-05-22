---
title: "Hello World"
categories: [随笔]
tags: [第一次发文, GitHub Pages]
---

<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>志愿者经历 - 张三</title>
    <style>
        /* 基础样式 */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, sans-serif;
        }

        body {
            background-color: #f5f7fa;
            line-height: 1.6;
            color: #333;
            padding: 2rem 1rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        /* 标题样式 */
        .page-title {
            text-align: center;
            color: #2c3e50;
            margin-bottom: 2rem;
            font-size: 2.5rem;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }

        /* 活动卡片 */
        .activity-card {
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            padding: 2rem;
            margin-bottom: 2rem;
            transition: transform 0.2s;
        }

        .activity-card:hover {
            transform: translateY(-3px);
        }

        /* 信息区块样式 */
        .info-section {
            margin-bottom: 1.5rem;
        }

        .section-title {
            color: #3498db;
            border-bottom: 2px solid #3498db;
            padding-bottom: 0.5rem;
            margin-bottom: 1rem;
            font-size: 1.3rem;
        }

        /* 细节列表 */
        .detail-list {
            list-style: none;
            padding-left: 1rem;
        }

        .detail-list li {
            margin-bottom: 0.8rem;
            padding-left: 1.2rem;
            position: relative;
        }

        .detail-list li::before {
            content: "•";
            color: #3498db;
            position: absolute;
            left: 0;
        }

        /* 证明人区块 */
        .reference-contact {
            background: #f8f9fa;
            border-radius: 8px;
            padding: 1rem;
            margin-top: 1.5rem;
        }

        /* 按钮样式 */
        .proof-btn {
            display: inline-block;
            background: #3498db;
            color: white!important;
            padding: 0.5rem 1rem;
            border-radius: 6px;
            text-decoration: none;
            margin-top: 1rem;
            transition: background 0.3s;
        }

        .proof-btn:hover {
            background: #2980b9;
        }

        /* 响应式设计 */
        @media (max-width: 768px) {
            .activity-card {
                padding: 1.5rem;
            }
            
            .page-title {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="page-title">志愿者经历记录</h1>
        
        <!-- 活动1 -->
        <div class="activity-card">
            <div class="info-section">
                <h2 class="section-title">自闭症儿童画展筹款活动</h2>
                <ul class="detail-list">
                    <li><strong>日期：</strong>2023年9月10日</li>
                    <li><strong>主办方：</strong>星空公益基金会</li>
                    <li><strong>担任角色：</strong>活动执行组长</li>
                </ul>
            </div>

            <div class="info-section">
                <h3 class="section-title">主要成果</h3>
                <ul class="detail-list">
                    <li>策划执行3场社区展览</li>
                    <li>募集善款12,000元</li>
                    <li>服务参与家庭20组</li>
                </ul>
            </div>

            <div class="info-section">
                <h3 class="section-title">能力提升</h3>
                <ul class="detail-list">
                    <li>活动策划与执行</li>
                    <li>跨部门协调沟通</li>
                    <li>紧急情况处理</li>
                </ul>
            </div>

            <div class="reference-contact">
                <h3 class="section-title">证明人信息</h3>
                <ul class="detail-list">
                    <li><strong>姓名：</strong>李华</li>
                    <li><strong>职位：</strong>项目经理</li>
                    <li><strong>联系：</strong>lihua@xingkong.org</li>
                </ul>
            </div>

            <a href="#" class="proof-btn">查看活动照片</a>
            <a href="#" class="proof-btn">媒体报道链接</a>
        </div>

        <!-- 活动2 -->
        <div class="activity-card">
            <!-- 结构同上，复制修改内容即可 -->
        </div>
    </div>
</body>
</html>
