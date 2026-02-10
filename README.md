<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>「财气能量罗盘」专业财富磁场诊断系统</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-gold: #D4AF37;
            --deep-gold: #B8860B;
            --dark-bg: #0A0A0A;
            --card-bg: #1A1A1A;
            --text-light: #F5F5F5;
            --text-gray: #AAAAAA;
            --crystal-purple: #8A2BE2;
            --crystal-blue: #4169E1;
            --crystal-green: #32CD32;
            --accent-red: #FF4757;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            background-color: var(--dark-bg);
            color: var(--text-light);
            font-family: 'Inter', sans-serif;
            line-height: 1.6;
            min-height: 100vh;
            background-image: 
                radial-gradient(circle at 10% 20%, rgba(212, 175, 55, 0.03) 0%, transparent 20%),
                radial-gradient(circle at 90% 80%, rgba(138, 43, 226, 0.03) 0%, transparent 20%);
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* 头部导航 */
        .navbar {
            padding: 25px 0;
            border-bottom: 1px solid rgba(212, 175, 55, 0.1);
            margin-bottom: 40px;
        }
        
        .nav-content {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-family: 'Noto Serif SC', serif;
        }
        
        .logo-icon {
            color: var(--primary-gold);
            font-size: 1.8rem;
        }
        
        .logo-text {
            font-size: 1.5rem;
            font-weight: 700;
            background: linear-gradient(90deg, var(--primary-gold), var(--deep-gold));
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .nav-links {
            display: flex;
            gap: 30px;
        }
        
        .nav-link {
            color: var(--text-gray);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-link:hover {
            color: var(--primary-gold);
        }
        
        .cta-button {
            background: linear-gradient(90deg, var(--primary-gold), var(--deep-gold));
            color: var(--dark-bg);
            border: none;
            padding: 12px 24px;
            border-radius: 30px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .cta-button:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }
        
        /* 英雄区域 */
        .hero-section {
            padding: 80px 0;
            text-align: center;
            position: relative;
        }
        
        .hero-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle at center, rgba(212, 175, 55, 0.05) 0%, transparent 70%);
            z-index: -1;
        }
        
        .hero-title {
            font-family: 'Noto Serif SC', serif;
            font-size: 3.5rem;
            font-weight: 700;
            margin-bottom: 20px;
            line-height: 1.2;
        }
        
        .hero-subtitle {
            font-size: 1.2rem;
            color: var(--text-gray);
            max-width: 700px;
            margin: 0 auto 40px;
        }
        
        .highlight {
            color: var(--primary-gold);
            position: relative;
            display: inline-block;
        }
        
        .highlight::after {
            content: '';
            position: absolute;
            bottom: 2px;
            left: 0;
            width: 100%;
            height: 4px;
            background-color: var(--primary-gold);
            opacity: 0.3;
        }
        
        .pain-points {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 50px 0;
        }
        
        .pain-point {
            background-color: rgba(255, 71, 87, 0.1);
            border-left: 3px solid var(--accent-red);
            padding: 20px;
            border-radius: 8px;
            width: 300px;
            text-align: left;
        }
        
        .pain-point i {
            color: var(--accent-red);
            margin-bottom: 10px;
            font-size: 1.2rem;
        }
        
        .pain-point h4 {
            margin-bottom: 8px;
            color: var(--text-light);
        }
        
        .pain-point p {
            color: var(--text-gray);
            font-size: 0.95rem;
        }
        
        /* 测试容器 */
        .test-container {
            background-color: var(--card-bg);
            border-radius: 20px;
            overflow: hidden;
            margin: 60px 0;
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.3);
            border: 1px solid rgba(212, 175, 55, 0.1);
        }
        
        .test-header {
            background: linear-gradient(90deg, rgba(212, 175, 55, 0.1), rgba(138, 43, 226, 0.1));
            padding: 30px;
            text-align: center;
        }
        
        .test-title {
            font-family: 'Noto Serif SC', serif;
            font-size: 2.2rem;
            margin-bottom: 10px;
        }
        
        .test-subtitle {
            color: var(--text-gray);
            font-size: 1.1rem;
        }
        
        .step-counter {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 30px 0;
            gap: 10px;
        }
        
        .step {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background-color: rgba(255, 255, 255, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 600;
            position: relative;
        }
        
        .step.active {
            background-color: var(--primary-gold);
            color: var(--dark-bg);
        }
        
        .step.completed {
            background-color: var(--crystal-green);
            color: var(--dark-bg);
        }
        
        .step-line {
            width: 60px;
            height: 2px;
            background-color: rgba(255, 255, 255, 0.2);
        }
        
        .step-content {
            padding: 40px;
            min-height: 500px;
            display: flex;
            flex-direction: column;
        }
        
        .question-container {
            flex-grow: 1;
        }
        
        .question-title {
            font-size: 1.8rem;
            margin-bottom: 30px;
            color: var(--text-light);
            font-weight: 600;
        }
        
        .options-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }
        
        .option-card {
            background-color: rgba(255, 255, 255, 0.05);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 12px;
            padding: 25px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .option-card:hover {
            border-color: var(--primary-gold);
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
        }
        
        .option-card.selected {
            border-color: var(--primary-gold);
            background-color: rgba(212, 175, 55, 0.1);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.1);
        }
        
        .option-icon {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: rgba(212, 175, 55, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
            color: var(--primary-gold);
            font-size: 1.3rem;
        }
        
        .option-title {
            font-weight: 600;
            margin-bottom: 10px;
            font-size: 1.1rem;
        }
        
        .option-desc {
            color: var(--text-gray);
            font-size: 0.95rem;
            line-height: 1.5;
        }
        
        .navigation-buttons {
            display: flex;
            justify-content: space-between;
            margin-top: 40px;
        }
        
        .btn {
            padding: 15px 30px;
            border-radius: 30px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            border: none;
            font-size: 1rem;
        }
        
        .btn-outline {
            background-color: transparent;
            border: 1px solid rgba(212, 175, 55, 0.5);
            color: var(--primary-gold);
        }
        
        .btn-outline:hover {
            background-color: rgba(212, 175, 55, 0.1);
        }
        
        .btn-primary {
            background: linear-gradient(90deg, var(--primary-gold), var(--deep-gold));
            color: var(--dark-bg);
        }
        
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.2);
        }
        
        .btn-primary:disabled {
            opacity: 0.5;
            cursor: not-allowed;
        }
        
        /* 结果页面 */
        .result-container {
            padding: 50px;
            display: none;
        }
        
        .result-header {
            text-align: center;
            margin-bottom: 40px;
        }
        
        .result-title {
            font-family: 'Noto Serif SC', serif;
            font-size: 2.5rem;
            margin-bottom: 15px;
        }
        
        .result-subtitle {
            color: var(--text-gray);
            font-size: 1.1rem;
        }
        
        .result-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 30px;
            margin-bottom: 40px;
        }
        
        .result-card {
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 15px;
            padding: 30px;
            border: 1px solid rgba(212, 175, 55, 0.1);
        }
        
        .result-card.full-width {
            grid-column: span 2;
        }
        
        .card-title {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 20px;
            color: var(--primary-gold);
            font-size: 1.3rem;
        }
        
        .card-title i {
            font-size: 1.5rem;
        }
        
        .crystal-recommendation {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-bottom: 20px;
            padding-bottom: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .crystal-image {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            background: linear-gradient(45deg, var(--crystal-purple), var(--crystal-blue));
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
        }
        
        .crystal-info h4 {
            margin-bottom: 5px;
            font-size: 1.2rem;
        }
        
        .crystal-info p {
            color: var(--text-gray);
            font-size: 0.95rem;
        }
        
        .energy-score {
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-top: 20px;
        }
        
        .score-bar {
            height: 8px;
            background-color: rgba(255, 255, 255, 0.1);
            border-radius: 4px;
            flex-grow: 1;
            margin-right: 15px;
            overflow: hidden;
        }
        
        .score-fill {
            height: 100%;
            background: linear-gradient(90deg, var(--accent-red), var(--primary-gold), var(--crystal-green));
            border-radius: 4px;
            width: 0;
            transition: width 1.5s ease;
        }
        
        .home-layout {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            margin-top: 20px;
        }
        
        .layout-area {
            background-color: rgba(255, 255, 255, 0.05);
            border-radius: 10px;
            padding: 20px;
            text-align: center;
            transition: all 0.3s;
        }
        
        .layout-area.active {
            border: 2px solid var(--primary-gold);
            background-color: rgba(212, 175, 55, 0.1);
        }
        
        .layout-title {
            font-weight: 600;
            margin-bottom: 10px;
            color: var(--primary-gold);
        }
        
        .action-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 40px;
        }
        
        .btn-share {
            background: linear-gradient(90deg, var(--crystal-purple), var(--crystal-blue));
            color: white;
        }
        
        .btn-share:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(138, 43, 226, 0.2);
        }
        
        .btn-pdf {
            background-color: rgba(255, 255, 255, 0.1);
            color: white;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .btn-pdf:hover {
            background-color: rgba(255, 255, 255, 0.2);
        }
        
        /* 信任元素 */
        .trust-section {
            padding: 80px 0;
            text-align: center;
        }
        
        .trust-title {
            font-family: 'Noto Serif SC', serif;
            font-size: 2.2rem;
            margin-bottom: 50px;
        }
        
        .trust-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 30px;
        }
        
        .trust-item {
            background-color: var(--card-bg);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid rgba(212, 175, 55, 0.1);
        }
        
        .trust-icon {
            width: 70px;
            height: 70px;
            border-radius: 50%;
            background-color: rgba(212, 175, 55, 0.1);
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 20px;
            color: var(--primary-gold);
            font-size: 1.8rem;
        }
        
        /* 响应式设计 */
        @media (max-width: 992px) {
            .options-grid {
                grid-template-columns: 1fr;
            }
            
            .result-grid {
                grid-template-columns: 1fr;
            }
            
            .result-card.full-width {
                grid-column: span 1;
            }
            
            .trust-grid {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        
        @media (max-width: 768px) {
            .hero-title {
                font-size: 2.5rem;
            }
            
            .nav-links {
                display: none;
            }
            
            .home-layout {
                grid-template-columns: 1fr;
            }
            
            .trust-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <!-- 导航栏 -->
    <nav class="navbar">
        <div class="container nav-content">
            <div class="logo">
                <div class="logo-icon">✦</div>
                <div class="logo-text">财气能量罗盘</div>
            </div>
            <div class="nav-links">
                <a href="#" class="nav-link">能量诊断</a>
                <a href="#" class="nav-link">水晶能量</a>
                <a href="#" class="nav-link">案例研究</a>
                <a href="#" class="nav-link">专家咨询</a>
            </div>
            <button class="cta-button">获取个人报告</button>
        </div>
    </nav>

    <div class="container">
        <!-- 英雄区域 -->
        <section class="hero-section">
            <div class="hero-bg"></div>
            <h1 class="hero-title">你的财富能量，是否存在<span class="highlight">致命漏洞</span>？</h1>
            <p class="hero-subtitle">基于能量磁场理论与九宫飞星算法，精准扫描您居住空间的财气漏洞，提供个性化水晶布局方案，激活沉睡的财富能量。</p>
            
            <div class="pain-points">
                <div class="pain-point">
                    <i class="fas fa-exclamation-circle"></i>
                    <h4>收入增长停滞</h4>
                    <p>明明很努力，收入却多年未涨？可能是家中财位被压制，能量无法流动。</p>
                </div>
                <div class="pain-point">
                    <i class="fas fa-money-bill-wave"></i>
                    <h4>财富无法留存</h4>
                    <p>赚得多存得少？钱总在不经意间流失？检查家中"漏财位"是否摆放错误。</p>
                </div>
                <div class="pain-point">
                    <i class="fas fa-bolt"></i>
                    <h4>机会总是错过</h4>
                    <p>好机会总与你擦肩而过？可能是贵人方位受阻，需用特定水晶疏通能量。</p>
                </div>
            </div>
            
            <button class="cta-button" id="startTestBtn" style="padding: 18px 40px; font-size: 1.1rem;">
                <i class="fas fa-crystal"></i> 开始能量诊断测试
            </button>
            
            <p style="margin-top: 20px; color: var(--text-gray); font-size: 0.9rem;">
                已有 <span style="color: var(--primary-gold); font-weight: 600;">23,847</span> 人完成诊断，平均财富能量提升 <span style="color: var(--crystal-green); font-weight: 600;">42%</span>
            </p>
        </section>

        <!-- 测试容器 -->
        <div class="test-container" id="testContainer" style="display: none;">
            <div class="test-header">
                <h2 class="test-title">财富能量诊断测试</h2>
                <p class="test-subtitle">请根据您的真实情况回答以下问题，系统将生成个性化能量修复方案</p>
            </div>
            
            <div class="step-counter" id="stepCounter">
                <!-- 步骤指示器将通过JavaScript动态生成 -->
            </div>
            
            <div class="step-content">
                <div class="question-container" id="questionContainer">
                    <!-- 问题内容将通过JavaScript动态生成 -->
                </div>
                
                <div class="navigation-buttons">
                    <button class="btn btn-outline" id="prevBtn" style="display: none;">
                        <i class="fas fa-arrow-left"></i> 上一题
                    </button>
                    <button class="btn btn-primary" id="nextBtn" disabled>
                        下一题 <i class="fas fa-arrow-right"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- 结果页面 -->
        <div class="test-container" id="resultContainer" style="display: none;">
            <div class="result-container">
                <div class="result-header">
                    <h2 class="result-title">您的财富能量诊断报告</h2>
                    <p class="result-subtitle">基于您的回答生成的个性化能量修复方案 | 报告编号: <span id="reportId">WN-2023-8472</span></p>
                </div>
                
                <div class="result-grid">
                    <div class="result-card">
                        <div class="card-title">
                            <i class="fas fa-heartbeat"></i> 能量诊断结果
                        </div>
                        <h3 id="resultType" style="font-size: 1.8rem; margin-bottom: 15px; color: var(--primary-gold);">能量阻塞型</h3>
                        <p id="resultDesc" style="color: var(--text-gray); margin-bottom: 20px;">
                            您的财富能量流动受到严重阻碍，主要问题集中在空间能量堵塞和负面情绪积累。这导致机会难以进入，现有财富也难以增长。
                        </p>
                        
                        <div class="energy-score">
                            <div style="font-weight: 600;">财富能量指数</div>
                            <div style="display: flex; align-items: center;">
                                <div class="score-bar">
                                    <div class="score-fill" id="energyScore" style="width: 42%;"></div>
                                </div>
                                <span id="scoreValue" style="font-weight: 600; color: var(--primary-gold);">42/100</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="result-card">
                        <div class="card-title">
                            <i class="fas fa-home"></i> 主要问题方位
                        </div>
                        <h4 id="problemArea" style="margin-bottom: 15px; font-size: 1.3rem;">西北方（乾宫）与东南方（巽宫）</h4>
                        <p id="problemDesc" style="color: var(--text-gray); margin-bottom: 20px;">
                            西北方代表贵人运与决策力，此处堵塞导致机会难以把握。东南方代表财富流动，此处受阻造成收入增长停滞。
                        </p>
                        
                        <div class="home-layout">
                            <div class="layout-area active">
                                <div class="layout-title">西北方</div>
                                <div style="color: var(--accent-red);">严重阻塞</div>
                            </div>
                            <div class="layout-area">
                                <div class="layout-title">东南方</div>
                                <div style="color: var(--accent-red);">中度阻塞</div>
                            </div>
                            <div class="layout-area">
                                <div class="layout-title">西南方</div>
                                <div style="color: var(--crystal-green);">正常</div>
                            </div>
                        </div>
                    </div>
                    
                    <div class="result-card full-width">
                        <div class="card-title">
                            <i class="fas fa-crystal"></i> 水晶能量修复方案
                        </div>
                        
                        <div class="crystal-recommendation">
                            <div class="crystal-image">
                                <i class="fas fa-gem"></i>
                            </div>
                            <div class="crystal-info">
                                <h4 id="crystalName">金发晶 + 绿幽灵组合阵</h4>
                                <p id="crystalDesc">金发晶疏通财富管道，绿幽灵吸引事业机会，双晶共振破解能量阻塞。</p>
                            </div>
                        </div>
                        
                        <div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 20px;">
                            <div>
                                <h4 style="margin-bottom: 10px; color: var(--primary-gold);">摆放位置</h4>
                                <ul style="color: var(--text-gray); padding-left: 20px;">
                                    <li id="position1">西北方书桌或办公区</li>
                                    <li id="position2">东南方客厅角落</li>
                                    <li id="position3">大门入口玄关处</li>
                                </ul>
                            </div>
                            <div>
                                <h4 style="margin-bottom: 10px; color: var(--primary-gold);">激活方法</h4>
                                <ul style="color: var(--text-gray); padding-left: 20px;">
                                    <li>每月的第一个周五进行能量激活</li>
                                    <li>搭配白色蜡烛增强效果</li>
                                    <li>保持水晶清洁，每月月光净化</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="action-buttons">
                    <button class="btn btn-share" id="shareReport">
                        <i class="fas fa-share-alt"></i> 分享诊断报告
                    </button>
                    <button class="btn btn-pdf">
                        <i class="fas fa-file-pdf"></i> 下载详细PDF方案
                    </button>
                    <button class="btn btn-primary" id="consultExpert">
                        <i class="fas fa-user-tie"></i> 预约专家深度咨询
                    </button>
                </div>
            </div>
        </div>

        <!-- 信任元素 -->
        <section class="trust-section">
            <h2 class="trust-title">为什么选择「财气能量罗盘」？</h2>
            <div class="trust-grid">
                <div class="trust-item">
                    <div class="trust-icon">
                        <i class="fas fa-atom"></i>
                    </div>
                    <h3>能量磁场科学</h3>
                    <p>基于量子物理与能量磁场理论，结合传统风水智慧，提供科学化的解决方案。</p>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">
                        <i class="fas fa-user-check"></i>
                    </div>
                    <h3>个性化诊断</h3>
                    <p>根据您的生辰信息、居住环境和个人习惯，生成完全个性化的能量修复方案。</p>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">
                        <i class="fas fa-gem"></i>
                    </div>
                    <h3>水晶能量学</h3>
                    <p>与全球顶级水晶能量学家合作，每一种推荐水晶都经过能量频率测试验证。</p>
                </div>
                <div class="trust-item">
                    <div class="trust-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>效果追踪</h3>
                    <p>85%的用户在实施方案3个月内报告收入增长或财务状况明显改善。</p>
                </div>
            </div>
        </section>
    </div>

    <script>
        // 测试数据
        const testData = {
            questions: [
                {
                    id: 1,
                    title: "您的出生月份属于哪个季节？",
                    options: [
                        {
                            title: "春 (2-4月)",
                            desc: "木属性季节，能量偏向生长与扩张",
                            icon: "fa-seedling",
                            value: "spring"
                        },
                        {
                            title: "夏 (5-7月)",
                            desc: "火属性季节，能量偏向热情与行动",
                            icon: "fa-sun",
                            value: "summer"
                        },
                        {
                            title: "秋 (8-10月)",
                            desc: "金属性季节，能量偏向收获与整理",
                            icon: "fa-leaf",
                            value: "autumn"
                        },
                        {
                            title: "冬 (11-1月)",
                            desc: "水属性季节，能量偏向沉淀与内省",
                            icon: "fa-snowflake",
                            value: "winter"
                        }
                    ]
                },
                {
                    id: 2,
                    title: "您目前的收入主要来源是？",
                    options: [
                        {
                            title: "固定工资",
                            desc: "稳定但增长有限，依赖单一渠道",
                            icon: "fa-money-check-alt",
                            value: "salary"
                        },
                        {
                            title: "自由职业/项目制",
                            desc: "波动较大，依靠个人技能与人脉",
                            icon: "fa-user-tie",
                            value: "freelance"
                        },
                        {
                            title: "创业/企业经营",
                            desc: "风险与机遇并存，需把握市场动向",
                            icon: "fa-chart-line",
                            value: "business"
                        },
                        {
                            title: "投资理财收入",
                            desc: "资本运作，需要精准判断与耐心",
                            icon: "fa-coins",
                            value: "investment"
                        }
                    ]
                },
                {
                    id: 3,
                    title: "您家中哪个区域最杂乱或很少使用？",
                    options: [
                        {
                            title: "西北角区域",
                            desc: "代表贵人运与决策力，杂乱影响机会把握",
                            icon: "fa-user-friends",
                            value: "northwest"
                        },
                        {
                            title: "东南角区域",
                            desc: "代表财富流动与增长，堵塞影响收入提升",
                            icon: "fa-money-bill-wave",
                            value: "southeast"
                        },
                        {
                            title: "客厅中央区域",
                            desc: "家庭能量核心，杂乱影响整体运势",
                            icon: "fa-home",
                            value: "center"
                        },
                        {
                            title: "大门入口处",
                            desc: "能量进出口，混乱阻碍新机会进入",
                            icon: "fa-door-open",
                            value: "entrance"
                        }
                    ]
                },
                {
                    id: 4,
                    title: "您最容易在哪种情况下出现财务损失？",
                    options: [
                        {
                            title: "情绪消费",
                            desc: "压力大或情绪低落时过度购物",
                            icon: "fa-sad-cry",
                            value: "emotional"
                        },
                        {
                            title: "投资失误",
                            desc: "跟风投资或信息不足导致损失",
                            icon: "fa-chart-down",
                            value: "investment_loss"
                        },
                        {
                            title: "机会错过",
                            desc: "犹豫不决导致好机会流失",
                            icon: "fa-clock",
                            value: "missed_opportunity"
                        },
                        {
                            title: "维护支出",
                            desc: "物品损坏、健康问题等意外开支",
                            icon: "fa-tools",
                            value: "maintenance"
                        }
                    ]
                },
                {
                    id: 5,
                    title: "您希望财富能量在哪方面提升？",
                    options: [
                        {
                            title: "增加收入渠道",
                            desc: "开拓新财源，不依赖单一收入",
                            icon: "fa-plus-circle",
                            value: "new_income"
                        },
                        {
                            title: "提升现有收入",
                            desc: "在现有基础上实现收入倍增",
                            icon: "fa-arrow-up",
                            value: "increase_income"
                        },
                        {
                            title: "稳定财务状况",
                            desc: "减少波动，建立安全财务基础",
                            icon: "fa-shield-alt",
                            value: "stability"
                        },
                        {
                            title: "吸引贵人助力",
                            desc: "获得更多支持与优质合作机会",
                            icon: "fa-hands-helping",
                            value: "help"
                        }
                    ]
                }
            ],
            results: {
                spring_salary_northwest_emotional_new_income: {
                    type: "能量阻塞型",
                    desc: "您的财富能量流动受到严重阻碍，木属性出生者在固定收入模式下容易感到受限，西北方位杂乱进一步压制了贵人运势，需要疏通能量管道。",
                    score: 42,
                    problemArea: "西北方（乾宫）与东南方（巽宫）",
                    problemDesc: "西北方代表贵人运与决策力，此处堵塞导致机会难以把握。东南方代表财富流动，此处受阻造成收入增长停滞。",
                    crystalName: "金发晶 + 绿幽灵组合阵",
                    crystalDesc: "金发晶疏通财富管道，绿幽灵吸引事业机会，双晶共振破解能量阻塞。",
                    positions: ["西北方书桌或办公区", "东南方客厅角落", "大门入口玄关处"]
                },
                // 更多结果组合...
                default: {
                    type: "能量失衡型",
                    desc: "您的财富能量场存在明显失衡，不同能量中心之间协调不畅，导致财务机会难以把握，现有资源无法有效整合。",
                    score: 55,
                    problemArea: "多个能量中心失衡",
                    problemDesc: "家庭能量场中多个关键方位能量不协调，造成财富能量分散，无法形成有效合力。",
                    crystalName: "紫水晶阵 + 黄水晶组合",
                    crystalDesc: "紫水晶平衡能量场，黄水晶聚集财富能量，建立和谐稳定的财富磁场。",
                    positions: ["家中中央区域", "主要收入来源方位", "个人常待区域"]
                }
            }
        };

        // 应用状态
        const appState = {
            currentStep: 0,
            answers: {},
            result: null
        };

        // DOM元素
        const startTestBtn = document.getElementById('startTestBtn');
        const testContainer = document.getElementById('testContainer');
        const resultContainer = document.getElementById('resultContainer');
        const stepCounter = document.getElementById('stepCounter');
        const questionContainer = document.getElementById('questionContainer');
        const prevBtn = document.getElementById('prevBtn');
        const nextBtn = document.getElementById('nextBtn');
        const shareReportBtn = document.getElementById('shareReport');
        const consultExpertBtn = document.getElementById('consultExpert');

        // 初始化
        document.addEventListener('DOMContentLoaded', function() {
            // 绑定事件
            startTestBtn.addEventListener('click', startTest);
            prevBtn.addEventListener('click', prevQuestion);
            nextBtn.addEventListener('click', nextQuestion);
            shareReportBtn.addEventListener('click', shareReport);
            consultExpertBtn.addEventListener('click', consultExpert);
            
            // 初始化步骤指示器
            initStepCounter();
            
            // 生成报告ID
            document.getElementById('reportId').textContent = `WN-2023-${Math.floor(1000 + Math.random() * 9000)}`;
        });

        // 开始测试
        function startTest() {
            document.querySelector('.hero-section').scrollIntoView({ behavior: 'smooth' });
            testContainer.style.display = 'block';
            startTestBtn.style.display = 'none';
            renderQuestion(0);
        }

        // 初始化步骤指示器
        function initStepCounter() {
            let stepsHTML = '';
            
            testData.questions.forEach((question, index) => {
                if (index > 0) {
                    stepsHTML += '<div class="step-line"></div>';
                }
                stepsHTML += `<div class="step ${index === 0 ? 'active' : ''}" id="step-${index}">${index + 1}</div>`;
            });
            
            stepCounter.innerHTML = stepsHTML;
        }

        // 渲染问题
        function renderQuestion(stepIndex) {
            const question = testData.questions[stepIndex];
            
            // 更新步骤指示器
            document.querySelectorAll('.step').forEach((step, index) => {
                step.classList.remove('active', 'completed');
                if (index < stepIndex) {
                    step.classList.add('completed');
                } else if (index === stepIndex) {
                    step.classList.add('active');
                }
            });
            
            // 构建问题HTML
            let optionsHTML = '';
            question.options.forEach((option, index) => {
                const isSelected = appState.answers[stepIndex] === option.value;
                optionsHTML += `
                    <div class="option-card ${isSelected ? 'selected' : ''}" data-index="${index}" data-value="${option.value}">
                        <div class="option-icon">
                            <i class="fas ${option.icon}"></i>
                        </div>
                        <div class="option-title">${option.title}</div>
                        <div class="option-desc">${option.desc}</div>
                    </div>
                `;
            });
            
            questionContainer.innerHTML = `
                <h2 class="question-title">${question.title}</h2>
                <div class="options-grid">
                    ${optionsHTML}
                </div>
            `;
            
            // 绑定选项点击事件
            document.querySelectorAll('.option-card').forEach(card => {
                card.addEventListener('click', function() {
                    const selectedValue = this.getAttribute('data-value');
                    selectOption(stepIndex, selectedValue);
                });
            });
            
            // 更新导航按钮
            prevBtn.style.display = stepIndex > 0 ? 'flex' : 'none';
            nextBtn.disabled = !appState.answers[stepIndex];
            nextBtn.innerHTML = stepIndex < testData.questions.length - 1 ? 
                '下一题 <i class="fas fa-arrow-right"></i>' : 
                '生成诊断报告 <i class="fas fa-crystal"></i>';
            
            appState.currentStep = stepIndex;
        }

        // 选择选项
        function selectOption(stepIndex, value) {
            // 移除同一问题的所有选中状态
            document.querySelectorAll('.option-card').forEach(card => {
                card.classList.remove('selected');
            });
            
            // 添加当前选项的选中状态
            event.target.closest('.option-card').classList.add('selected');
            
            // 保存答案
            appState.answers[stepIndex] = value;
            
            // 启用下一题按钮
            nextBtn.disabled = false;
        }

        // 上一题
        function prevQuestion() {
            if (appState.currentStep > 0) {
                renderQuestion(appState.currentStep - 1);
            }
        }

        // 下一题
        function nextQuestion() {
            if (appState.currentStep < testData.questions.length - 1) {
                renderQuestion(appState.currentStep + 1);
            } else {
                calculateResult();
            }
        }

        // 计算结果
        function calculateResult() {
            // 生成结果键
            const resultKey = Object.values(appState.answers).join('_');
            
            // 获取结果
            appState.result = testData.results[resultKey] || testData.results.default;
            
            // 显示结果
            showResult();
        }

        // 显示结果
        function showResult() {
            testContainer.style.display = 'none';
            resultContainer.style.display = 'block';
            
            // 更新结果内容
            document.getElementById('resultType').textContent = appState.result.type;
            document.getElementById('resultDesc').textContent = appState.result.desc;
            document.getElementById('problemArea').textContent = appState.result.problemArea;
            document.getElementById('problemDesc').textContent = appState.result.problemDesc;
            document.getElementById('crystalName').textContent = appState.result.crystalName;
            document.getElementById('crystalDesc').textContent = appState.result.crystalDesc;
            
            // 更新能量分数
            document.getElementById('energyScore').style.width = `${appState.result.score}%`;
            document.getElementById('scoreValue').textContent = `${appState.result.score}/100`;
            
            // 更新摆放位置
            const positions = document.querySelectorAll('[id^="position"]');
            appState.result.positions.forEach((position, index) => {
                if (positions[index]) {
                    positions[index].textContent = position;
                }
            });
            
            // 滚动到结果区域
            resultContainer.scrollIntoView({ behavior: 'smooth' });
        }

        // 分享报告
        function shareReport() {
            const shareText = `我刚完成了「财气能量罗盘」诊断，我的财富能量类型是「${appState.result.type}」！\n\n能量评分：${appState.result.score}/100\n\n推荐水晶方案：${appState.result.crystalName}\n\n你也来测测你的财富能量吧！`;
            
            if (navigator.share) {
                navigator.share({
                    title: '我的财富能量诊断报告',
                    text: shareText,
                    url: window.location.href
                });
            } else {
                // 复制到剪贴板
                navigator.clipboard.writeText(shareText + '\n\n测试链接：' + window.location.href)
                    .then(() => {
                        alert('诊断报告已复制到剪贴板，快去分享给朋友吧！');
                    });
            }
        }

        // 预约专家咨询
        function consultExpert() {
            alert('即将跳转至专家预约页面...\n\n（在实际应用中，这里会连接到预约系统）');
        }
    </script>
</body>
</html>
