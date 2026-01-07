[index (1).html](https://github.com/user-attachments/files/24464164/index.1.html)
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>家メンテ | おうちの健康診断で安心の住まいづくり</title>
    <meta name="description" content="その家、本当に安心ですか？見えない欠陥を見逃さず、後悔しない選択を。不動産会社だから安心できる住宅診断サービス。">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700;800&family=Noto+Sans+JP:wght@400;500;700;900&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        :root {
            --primary-blue: #4A90E2;
            --primary-orange: #FF8C42;
            --light-blue: #E8F4FF;
            --light-orange: #FFF4EC;
            --dark-blue: #2C5F8D;
            --dark-orange: #E67A2E;
            --text-dark: #2c3e50;
            --text-light: #5a6c7d;
            --white: #ffffff;
            --shadow: 0 10px 40px rgba(74, 144, 226, 0.1);
            --shadow-hover: 0 15px 50px rgba(74, 144, 226, 0.15);
        }

        body {
            font-family: 'Noto Sans JP', sans-serif;
            color: var(--text-dark);
            line-height: 1.8;
            overflow-x: hidden;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--dark-blue) 100%);
            color: var(--white);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
        }

        .header-content {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 1rem;
        }

        .logo-text h1 {
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 2rem;
            font-weight: 800;
            margin-bottom: 0.2rem;
            letter-spacing: 1px;
        }

        .logo-subtitle {
            font-size: 0.75rem;
            opacity: 0.9;
            font-weight: 400;
            letter-spacing: 0.5px;
        }

        .header-phone {
            display: flex;
            align-items: center;
            gap: 0.5rem;
            background: var(--primary-orange);
            padding: 0.8rem 1.5rem;
            border-radius: 50px;
            font-weight: 700;
            font-size: 1.2rem;
            text-decoration: none;
            color: var(--white);
            transition: transform 0.3s;
        }

        .header-phone:hover {
            transform: scale(1.05);
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 2rem;
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s;
            font-size: 0.9rem;
        }

        nav a:hover {
            color: var(--primary-orange);
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--light-blue) 0%, var(--white) 100%);
            padding: 5rem 2rem 4rem;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -10%;
            width: 600px;
            height: 600px;
            background: radial-gradient(circle, rgba(255, 140, 66, 0.1) 0%, transparent 70%);
            border-radius: 50%;
        }

        .hero-content {
            max-width: 900px;
            margin: 0 auto;
            position: relative;
            z-index: 1;
        }

        .hero-badge {
            display: inline-block;
            background: linear-gradient(135deg, var(--primary-orange) 0%, var(--dark-orange) 100%);
            color: var(--white);
            padding: 0.5rem 1.5rem;
            border-radius: 30px;
            font-weight: 700;
            font-size: 0.9rem;
            margin-bottom: 2rem;
            box-shadow: 0 5px 20px rgba(255, 140, 66, 0.3);
        }

        .hero-icon {
            font-size: 5rem;
            margin-bottom: 1.5rem;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }

        .hero h2 {
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 2.8rem;
            font-weight: 800;
            color: var(--primary-blue);
            margin-bottom: 1.5rem;
            line-height: 1.4;
        }

        .hero-highlight {
            color: var(--primary-orange);
            position: relative;
            display: inline-block;
        }

        .hero-description {
            font-size: 1.15rem;
            color: var(--text-light);
            margin-bottom: 2.5rem;
            line-height: 2;
        }

        .hero-cta {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
            margin-bottom: 2rem;
        }

        .hero-note {
            font-size: 0.9rem;
            color: var(--text-light);
            font-weight: 500;
        }

        /* Buttons */
        .btn {
            padding: 1.2rem 3rem;
            border: none;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.3s;
            text-decoration: none;
            display: inline-block;
            font-family: 'Noto Sans JP', sans-serif;
        }

        .btn-primary {
            background: linear-gradient(135deg, var(--primary-orange) 0%, var(--dark-orange) 100%);
            color: var(--white);
            box-shadow: 0 8px 25px rgba(255, 140, 66, 0.3);
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 12px 35px rgba(255, 140, 66, 0.4);
        }

        .btn-secondary {
            background: var(--white);
            color: var(--primary-blue);
            border: 3px solid var(--primary-blue);
        }

        .btn-secondary:hover {
            background: var(--primary-blue);
            color: var(--white);
            transform: translateY(-3px);
        }

        /* Trust Badges */
        .trust-section {
            padding: 3rem 2rem;
            background: var(--white);
            border-top: 3px solid var(--primary-orange);
        }

        .trust-badges {
            max-width: 1000px;
            margin: 0 auto;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 3rem;
            flex-wrap: wrap;
        }

        .trust-badge {
            text-align: center;
        }

        .trust-badge-icon {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        .trust-badge-text {
            font-weight: 600;
            color: var(--primary-blue);
            font-size: 0.95rem;
        }

        /* Main Selection Section */
        .selection-section {
            padding: 5rem 2rem;
            background: linear-gradient(135deg, var(--light-blue) 0%, var(--light-orange) 5%, var(--white) 100%);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        .section-title {
            text-align: center;
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 2.3rem;
            font-weight: 800;
            color: var(--primary-blue);
            margin-bottom: 1rem;
        }

        .section-subtitle {
            text-align: center;
            font-size: 1.05rem;
            color: var(--text-light);
            margin-bottom: 4rem;
        }

        .selection-category {
            margin-bottom: 4rem;
        }

        .category-title {
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 1.7rem;
            font-weight: 700;
            color: var(--dark-blue);
            margin-bottom: 2rem;
            padding-left: 1rem;
            border-left: 5px solid var(--primary-orange);
        }

        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
        }

        .card {
            background: var(--white);
            border-radius: 20px;
            padding: 2.5rem;
            box-shadow: var(--shadow);
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            cursor: pointer;
            position: relative;
            overflow: hidden;
            border: 3px solid transparent;
        }

        .card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: linear-gradient(90deg, var(--primary-blue), var(--primary-orange));
            transform: scaleX(0);
            transition: transform 0.4s;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: var(--shadow-hover);
            border-color: var(--primary-orange);
        }

        .card:hover::before {
            transform: scaleX(1);
        }

        .card-icon {
            font-size: 3.5rem;
            margin-bottom: 1.5rem;
        }

        .card-title {
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 1rem;
        }

        .card-description {
            color: var(--text-light);
            margin-bottom: 1.5rem;
            line-height: 1.8;
        }

        .card-link {
            display: inline-flex;
            align-items: center;
            color: var(--primary-orange);
            font-weight: 600;
            text-decoration: none;
            transition: transform 0.3s;
        }

        .card-link:hover {
            transform: translateX(5px);
        }

        .card-link::after {
            content: '→';
            margin-left: 0.5rem;
            font-size: 1.2rem;
        }

        .star-badge {
            position: absolute;
            top: 1rem;
            right: 1rem;
            background: var(--primary-orange);
            color: var(--white);
            padding: 0.4rem 1rem;
            border-radius: 20px;
            font-weight: 700;
            font-size: 0.85rem;
        }

        /* Why Section */
        .why-section {
            padding: 5rem 2rem;
            background: var(--white);
        }

        .why-intro {
            text-align: center;
            max-width: 800px;
            margin: 0 auto 3rem;
            font-size: 1.1rem;
            color: var(--text-light);
            line-height: 2;
        }

        .why-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2.5rem;
            margin-top: 3rem;
        }

        .why-card {
            background: linear-gradient(135deg, var(--light-blue) 0%, var(--white) 100%);
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
            border-left: 5px solid var(--primary-orange);
        }

        .why-card:hover {
            transform: translateY(-5px);
        }

        .why-number {
            font-family: 'Poppins', sans-serif;
            font-size: 2.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, var(--primary-blue), var(--primary-orange));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: 1rem;
        }

        .why-title {
            font-size: 1.4rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 1rem;
        }

        .why-description {
            color: var(--text-dark);
            line-height: 1.9;
        }

        /* Feature Section */
        .feature-section {
            padding: 5rem 2rem;
            background: linear-gradient(135deg, var(--light-orange) 0%, var(--light-blue) 100%);
        }

        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
            margin-top: 3rem;
        }

        .feature-card {
            background: var(--white);
            padding: 2rem;
            border-radius: 20px;
            text-align: center;
            box-shadow: var(--shadow);
            transition: transform 0.3s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        .feature-title {
            font-size: 1.2rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 0.8rem;
        }

        .feature-description {
            color: var(--text-light);
            font-size: 0.95rem;
            line-height: 1.7;
        }

        /* Steps Section */
        .steps-section {
            padding: 5rem 2rem;
            background: var(--white);
        }

        .steps-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            gap: 2rem;
            margin-top: 3rem;
            flex-wrap: wrap;
        }

        .step {
            flex: 1;
            min-width: 250px;
            text-align: center;
            position: relative;
        }

        .step:not(:last-child)::after {
            content: '→';
            position: absolute;
            right: -2rem;
            top: 3rem;
            font-size: 2rem;
            color: var(--primary-orange);
            font-weight: 700;
        }

        .step-badge {
            display: inline-block;
            background: linear-gradient(135deg, var(--primary-orange) 0%, var(--dark-orange) 100%);
            color: var(--white);
            padding: 0.5rem 1.5rem;
            border-radius: 20px;
            font-weight: 700;
            margin-bottom: 1.5rem;
            font-family: 'Poppins', sans-serif;
        }

        .step-icon {
            font-size: 4rem;
            margin-bottom: 1rem;
        }

        .step-title {
            font-size: 1.3rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 1rem;
        }

        .step-description {
            color: var(--text-light);
            line-height: 1.8;
        }

        /* Cases Section */
        .cases-section {
            padding: 5rem 2rem;
            background: linear-gradient(135deg, var(--light-blue) 0%, var(--light-orange) 100%);
        }

        .cases-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2.5rem;
            margin-top: 3rem;
        }

        .case-card {
            background: var(--white);
            border-radius: 20px;
            padding: 2.5rem;
            box-shadow: var(--shadow);
            position: relative;
            overflow: hidden;
        }

        .case-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(90deg, var(--primary-blue), var(--primary-orange));
        }

        .case-number {
            font-family: 'Poppins', sans-serif;
            font-size: 1.1rem;
            font-weight: 700;
            color: var(--primary-orange);
            margin-bottom: 1rem;
        }

        .case-title {
            font-size: 1.3rem;
            font-weight: 700;
            color: var(--primary-blue);
            margin-bottom: 1rem;
        }

        .case-description {
            color: var(--text-dark);
            line-height: 1.8;
            margin-bottom: 1rem;
        }

        .case-result {
            background: var(--light-blue);
            padding: 1rem;
            border-radius: 10px;
            color: var(--primary-blue);
            font-weight: 600;
        }

        /* Final CTA Section */
        .final-cta {
            padding: 5rem 2rem;
            background: linear-gradient(135deg, var(--primary-blue) 0%, var(--dark-blue) 100%);
            color: var(--white);
            text-align: center;
        }

        .final-cta h2 {
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 2.3rem;
            font-weight: 800;
            margin-bottom: 1.5rem;
        }

        .final-cta p {
            font-size: 1.15rem;
            margin-bottom: 3rem;
            line-height: 2;
            opacity: 0.95;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }

        .final-cta-buttons {
            display: flex;
            gap: 1.5rem;
            justify-content: center;
            flex-wrap: wrap;
            margin-bottom: 3rem;
        }

        .contact-info {
            margin-top: 3rem;
            padding-top: 3rem;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
        }

        .phone-number {
            font-family: 'Poppins', sans-serif;
            font-size: 2.5rem;
            font-weight: 700;
            color: var(--primary-orange);
            margin-bottom: 0.5rem;
        }

        .phone-link {
            color: var(--primary-orange);
            text-decoration: none;
            transition: opacity 0.3s;
        }

        .phone-link:hover {
            opacity: 0.8;
        }

        .business-hours {
            opacity: 0.9;
            margin-top: 0.5rem;
        }

        /* Footer */
        footer {
            background: var(--dark-blue);
            color: var(--white);
            padding: 3rem 2rem;
        }

        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
        }

        .footer-main {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 3rem;
            margin-bottom: 2rem;
        }

        .footer-logo {
            font-family: 'Poppins', 'Noto Sans JP', sans-serif;
            font-size: 1.8rem;
            font-weight: 800;
            margin-bottom: 1rem;
        }

        .footer-company {
            font-size: 0.95rem;
            opacity: 0.9;
            line-height: 1.8;
        }

        .footer-section h3 {
            font-size: 1.1rem;
            font-weight: 700;
            margin-bottom: 1rem;
            color: var(--primary-orange);
        }

        .footer-links {
            list-style: none;
        }

        .footer-links li {
            margin-bottom: 0.5rem;
        }

        .footer-links a {
            color: var(--white);
            text-decoration: none;
            transition: color 0.3s;
            font-size: 0.9rem;
        }

        .footer-links a:hover {
            color: var(--primary-orange);
        }

        .footer-bottom {
            text-align: center;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
        }

        .copyright {
            opacity: 0.7;
            font-size: 0.9rem;
        }

        /* Mobile Menu */
        .mobile-menu-toggle {
            display: none;
            background: none;
            border: none;
            color: var(--white);
            font-size: 1.5rem;
            cursor: pointer;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h2 {
                font-size: 1.8rem;
            }

            .hero-description {
                font-size: 1rem;
            }

            .section-title {
                font-size: 1.8rem;
            }

            nav ul {
                display: none;
            }

            .mobile-menu-toggle {
                display: block;
            }

            .header-phone {
                font-size: 1rem;
                padding: 0.6rem 1rem;
            }

            .cards-grid {
                grid-template-columns: 1fr;
            }

            .step:not(:last-child)::after {
                content: '↓';
                position: static;
                display: block;
                margin: 1rem 0;
            }

            .hero-cta {
                flex-direction: column;
            }

            .btn {
                width: 100%;
            }

            .final-cta-buttons {
                flex-direction: column;
            }

            .trust-badges {
                gap: 2rem;
            }

            .phone-number {
                font-size: 1.8rem;
            }
        }

        /* Animations */
        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .animate-on-scroll {
            opacity: 0;
            animation: fadeInUp 0.8s ease forwards;
        }

        .animate-delay-1 { animation-delay: 0.2s; }
        .animate-delay-2 { animation-delay: 0.4s; }
        .animate-delay-3 { animation-delay: 0.6s; }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="header-content">
            <div class="logo">
                <div class="logo-text">
                    <h1>家メンテ</h1>
                    <div class="logo-subtitle">おうちの健康診断</div>
                </div>
            </div>
            <a href="tel:0120-688-822" class="header-phone">
                📞 0120-688-822
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <div class="hero-badge">不動産会社だから安心できる住宅診断</div>
            <div class="hero-icon">🏠💚</div>
            <h2>その家、<br><span class="hero-highlight">本当に安心ですか?</span></h2>
            <p class="hero-description">
                長く暮らしてきたお家には、目には見えない小さな傷みややがみが溜まっていることがあります。<br>
                見えない欠陥を見逃さず、後悔しない選択を。<br>
                まずは1分でできる無料診断で、あなたの家の状態をチェックしてみましょう。
            </p>
            <div class="hero-cta">
                <a href="https://iemente-shindan.com/" target="_blank" class="btn btn-primary">今すぐ無料診断を始める</a>
                <a href="#why" class="btn btn-secondary">診断が必要な理由を知る</a>
            </div>
            <p class="hero-note">✨ 診断は約1分で完了 | 完全無料 | 登録不要</p>
        </div>
    </section>

    <!-- Trust Badges -->
    <section class="trust-section">
        <div class="trust-badges">
            <div class="trust-badge">
                <div class="trust-badge-icon">🏢</div>
                <div class="trust-badge-text">不動産会社運営</div>
            </div>
            <div class="trust-badge">
                <div class="trust-badge-icon">👨‍🔧</div>
                <div class="trust-badge-text">住宅メンテナンス<br>診断士認定</div>
            </div>
            <div class="trust-badge">
                <div class="trust-badge-icon">📊</div>
                <div class="trust-badge-text">満足度98%</div>
            </div>
            <div class="trust-badge">
                <div class="trust-badge-icon">📝</div>
                <div class="trust-badge-text">写真付き<br>詳細レポート</div>
            </div>
        </div>
    </section>

    <!-- Selection Section -->
    <section id="selection" class="selection-section">
        <div class="container">
            <h2 class="section-title">あなたの状況に合った診断をお選びください</h2>
            <p class="section-subtitle">3つの選択肢から、あなたにぴったりの診断をお選びいただけます</p>

            <!-- 築年数で選ぶ -->
            <div class="selection-category animate-on-scroll">
                <h3 class="category-title">🏗️ 築年数で選ぶ</h3>
                <div class="cards-grid">
                    <div class="card">
                        <div class="card-icon">📅</div>
                        <h4 class="card-title">築10年以上の方</h4>
                        <p class="card-description">
                            劣化の加速期、見えない傷みを早期に知り、将来の大出費を防ぐ診断
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                </div>
            </div>

            <!-- お悩みで選ぶ -->
            <div class="selection-category animate-on-scroll animate-delay-1">
                <h3 class="category-title">💧 お悩みで選ぶ</h3>
                <div class="cards-grid">
                    <div class="card">
                        <div class="card-icon">🌧️</div>
                        <h4 class="card-title">雨漏りが心配</h4>
                        <p class="card-description">
                            雨漏りは起きる前に止められる。Web診断で分かる前兆をチェック
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                    <div class="card">
                        <div class="card-icon">💨</div>
                        <h4 class="card-title">床下・湿気が心配</h4>
                        <p class="card-description">
                            床下は家の盲点。湿気・カビ・白蟻は気づかないうちに進行
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                    <div class="card">
                        <div class="card-icon">🛡️</div>
                        <h4 class="card-title">ベランダ防水が心配</h4>
                        <p class="card-description">
                            ベランダ防水は寿命10年。劣化放置は雨漏りへの最短ルート
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                </div>
            </div>

            <!-- タイプで選ぶ -->
            <div class="selection-category animate-on-scroll animate-delay-2">
                <h3 class="category-title">👥 あなたのタイプで選ぶ</h3>
                <div class="cards-grid">
                    <div class="card">
                        <div class="card-icon">👩‍🍳</div>
                        <h4 class="card-title">主婦・主夫の方</h4>
                        <p class="card-description">
                            不具合の早期発見が家事も家計も守る。今日からできる住まいチェック
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                    <div class="card">
                        <span class="star-badge">おすすめ</span>
                        <div class="card-icon">🏘️</div>
                        <h4 class="card-title">中古住宅購入検討中の方</h4>
                        <p class="card-description">
                            買う前に家の価値を見極める。後悔しない住宅診断
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                    <div class="card">
                        <div class="card-icon">👴</div>
                        <h4 class="card-title">シニア世帯の方</h4>
                        <p class="card-description">
                            老後の住まいを安全に。転倒・漏水・老朽トラブルを防ぐ診断
                        </p>
                        <a href="https://iemente-shindan.com/" target="_blank" class="card-link">診断を始める</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Section -->
    <section id="why" class="why-section">
        <div class="container">
            <h2 class="section-title">なぜ今、住宅診断が必要なのか?</h2>
            <p class="why-intro">
                普段は見えない構造部分や設備の劣化状況など、住まいの「健康状態」を専門家が客観的に診断します。<br>
                大切な資産である住まいを守り、安心して暮らすための必須のステップです。
            </p>
            <div class="why-grid">
                <div class="why-card animate-on-scroll">
                    <div class="why-number">01</div>
                    <h3 class="why-title">資産価値の維持と向上<br>劣化進行抑止が期待できる</h3>
                    <p class="why-description">
                        築10年を超えた家はゆっくり確実に劣化が始まります。早期発見・早期対応により、修繕費を大幅に抑えることができます。
                    </p>
                </div>
                <div class="why-card animate-on-scroll animate-delay-1">
                    <div class="why-number">02</div>
                    <h3 class="why-title">診断から始まる<br>安心がずっと続く<br>パートナーシップ</h3>
                    <p class="why-description">
                        ホームインスペクションはゴールではなく、安心な暮らしのスタートライン。診断結果に基づき、必要な修繕計画や維持管理までサポートします。
                    </p>
                </div>
                <div class="why-card animate-on-scroll animate-delay-2">
                    <div class="why-number">03</div>
                    <h3 class="why-title">不動産会社が診るから<br>後悔しない選択ができる</h3>
                    <p class="why-description">
                        建物の隠れたリスクや将来必要なメンテナンスを、専門家の目で客観的に明らかに。資産価値や暮らしにどう影響するかまでアドバイスします。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Feature Section -->
    <section class="feature-section">
        <div class="container">
            <h2 class="section-title">家メンテの診断メニュー</h2>
            <div class="feature-grid">
                <div class="feature-card animate-on-scroll">
                    <div class="feature-icon">🏗️</div>
                    <h3 class="feature-title">基礎診断</h3>
                    <p class="feature-description">
                        家の重みを支え、地震から守る基礎。ひび割れのパターンや幅、傾斜、鉄筋の錆などをチェックし、耐震性の低下を防ぎます。
                    </p>
                </div>
                <div class="feature-card animate-on-scroll animate-delay-1">
                    <div class="feature-icon">🏠</div>
                    <h3 class="feature-title">屋根診断</h3>
                    <p class="feature-description">
                        雨風から家を守る屋根は、劣化が見えにくい要注意箇所。屋根材の状態、棟や谷、雨樋まで詳細に診断します。
                    </p>
                </div>
                <div class="feature-card animate-on-scroll animate-delay-2">
                    <div class="feature-icon">🧱</div>
                    <h3 class="feature-title">外壁診断</h3>
                    <p class="feature-description">
                        外壁は雨水の侵入を防ぐ重要なバリア。ひび割れやシーリングの劣化、特に雨漏りの原因となる窓周りを徹底チェックします。
                    </p>
                </div>
                <div class="feature-card animate-on-scroll animate-delay-3">
                    <div class="feature-icon">🛡️</div>
                    <h3 class="feature-title">ベランダ診断</h3>
                    <p class="feature-description">
                        床防水層のひび割れや水たまり、排水口の状態、手すりのぐらつきなどをチェック。階下への雨漏りを未然に防ぎます。
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Steps Section -->
    <section id="steps" class="steps-section">
        <div class="container">
            <h2 class="section-title">簡単3ステップで診断完了!</h2>
            <div class="steps-container">
                <div class="step animate-on-scroll">
                    <div class="step-badge">STEP 1</div>
                    <div class="step-icon">📝</div>
                    <h3 class="step-title">いざテスト</h3>
                    <p class="step-description">
                        診断結果を正確に知るためにお家の現状を素直な気持ちで回答しましょう。
                    </p>
                </div>
                <div class="step animate-on-scroll animate-delay-1">
                    <div class="step-badge">STEP 2</div>
                    <div class="step-icon">📊</div>
                    <h3 class="step-title">テスト結果を見る</h3>
                    <p class="step-description">
                        住宅診断の結果からご家庭からのメンテナンスやリフォームのヒントを見つけましょう
                    </p>
                </div>
                <div class="step animate-on-scroll animate-delay-2">
                    <div class="step-badge">STEP 3</div>
                    <div class="step-icon">👨‍🔧</div>
                    <h3 class="step-title">より詳しいプロ診断をしよう</h3>
                    <p class="step-description">
                        お家の現状をチェックしたら、専門家による詳しい診断で"本当の状態"を見てみましょう
                    </p>
                </div>
            </div>
            <div style="text-align: center; margin-top: 3rem;">
                <a href="https://iemente-shindan.com/" target="_blank" class="btn btn-primary">今すぐ無料診断を始める</a>
            </div>
        </div>
    </section>

    <!-- Cases Section -->
    <section id="cases" class="cases-section">
        <div class="container">
            <h2 class="section-title">おうちの健康診断で自宅の価値が変わる</h2>
            <div class="cases-grid">
                <div class="case-card animate-on-scroll">
                    <div class="case-number">事例 01 | 川崎市</div>
                    <h3 class="case-title">築15年が新築同様の20年持つメンテナンスの少ないおうちへ</h3>
                    <p class="case-description">
                        外壁や屋根の傷みを気にされていたお客様。将来を見据えた長持ちする施工方法をご提案しました。
                    </p>
                    <div class="case-result">
                        → 「まるで新築のようにキレイになった」とご近所から好評
                    </div>
                </div>
                <div class="case-card animate-on-scroll animate-delay-1">
                    <div class="case-number">事例 02 | 横浜市</div>
                    <h3 class="case-title">中古住宅の不安を解消　診断とメンテナンスで住まいの価値向上</h3>
                    <p class="case-description">
                        中古でご購入されたご自宅について、「どこから手を入れたら良いかわからない」とのお悩みから診断をご依頼。
                    </p>
                    <div class="case-result">
                        → 計画的にメンテナンスし、将来の売却時にもプラスに
                    </div>
                </div>
                <div class="case-card animate-on-scroll animate-delay-2">
                    <div class="case-number">事例 03 | 横浜市</div>
                    <h3 class="case-title">診断履歴が評価される住まいづくり―マンションへの住み替えを見据えて</h3>
                    <p class="case-description">
                        新築に30年以上お住まいのお客様より、将来の売却に備えて診断のご相談。
                    </p>
                    <div class="case-result">
                        → 「診断履歴がある」という点が評価され、査定額がアップ
                    </div>
                </div>
            </div>
            <div style="text-align: center; margin-top: 3rem;">
                <p style="font-size: 1.15rem; font-weight: 600; color: var(--primary-blue);">
                    📝 報告書で安心の履歴管理<br>
                    住まいにも信頼できる「履歴書」を。確かな履歴管理で、住まいの価値と安心を守りましょう。
                </p>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section id="contact" class="final-cta">
        <div class="container">
            <h2>まずは1分の無料診断から<br>始めませんか?</h2>
            <p>
                長く暮らしてきたお家には、目には見えない小さな傷みややがみが溜まっていることがあります。<br>
                プロによる住宅診断を受けることで、お家の健康状態をしっかり把握し、<br>
                将来のトラブルを防ぐことができます。
            </p>
            <div class="final-cta-buttons">
                <a href="https://iemente-shindan.com/" target="_blank" class="btn btn-primary">今すぐ無料診断を始める</a>
                <a href="https://iemente.com/entry/inspection-fromapp/" target="_blank" class="btn btn-secondary">プロの訪問診断を申し込む</a>
            </div>
            <div class="contact-info">
                <p style="font-size: 1.1rem; margin-bottom: 1rem;">お電話でのご相談はこちら</p>
                <div class="phone-number">
                    <a href="tel:0120-688-822" class="phone-link">📞 0120-688-822</a>
                </div>
                <p class="business-hours">受付時間: 平日 9:00-18:00</p>
                <p style="margin-top: 1rem; font-size: 0.95rem; opacity: 0.9;">
                    ※お電話が一番最短で承れます
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-main">
                <div>
                    <div class="footer-logo">家メンテ</div>
                    <div class="footer-company">
                        株式会社サンアソシエーション<br>
                        東京都港区麻布十番2-19-8<br>
                        ボヌール麻布十番7F<br>
                        <a href="https://sunassociation.jp/" target="_blank" style="color: var(--primary-orange);">https://sunassociation.jp/</a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>サービス</h3>
                    <ul class="footer-links">
                        <li><a href="https://iemente.com/service/inspection">住宅診断とは</a></li>
                        <li><a href="https://iemente.com/service/foundation">基礎診断</a></li>
                        <li><a href="https://iemente.com/service/wall">外壁診断</a></li>
                        <li><a href="https://iemente.com/service/roof">屋根診断</a></li>
                        <li><a href="https://iemente.com/service/balcony">ベランダ診断</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>情報</h3>
                    <ul class="footer-links">
                        <li><a href="https://iemente.com/case">診断事例</a></li>
                        <li><a href="https://iemente.com/specialist">専門家の紹介</a></li>
                        <li><a href="https://iemente.com/area">対応エリア</a></li>
                        <li><a href="https://iemente.com/faq">よくある質問</a></li>
                        <li><a href="https://iemente.com/privacy-policy">プライバシーポリシー</a></li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>お問い合わせ</h3>
                    <ul class="footer-links">
                        <li><a href="https://iemente-shindan.com/" target="_blank">オンライン診断</a></li>
                        <li><a href="https://iemente.com/trial">お試し診断</a></li>
                        <li><a href="tel:0120-688-822">電話: 0120-688-822</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <div class="copyright">
                    © 2025 家メンテ（株式会社サンアソシエーション）. All rights reserved.
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Smooth scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Scroll animations
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = '1';
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, observerOptions);

        document.querySelectorAll('.animate-on-scroll').forEach(el => {
            observer.observe(el);
        });
    </script>
</body>
</html>
