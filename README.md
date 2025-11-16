<!DOCTYPE html>
<html lang="ru" itemscope itemtype="https://schema.org/EducationalOrganization">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    
    <!-- Критичные мета-теги для виральности -->
    <title>Медоеду ВСЁ — Личное наставничество в ИИ | @eugizus</title>
    <meta name="description" content="Максимум 10 человек. Личный коач @eugizus. Видеосессии + реальные проекты. 7777 руб/неделя интенсива. Или фристарт в сообществе. Начни сейчас.">
    <meta name="keywords" content="ИИ наставничество, ChatGPT, Midjourney, личный коач, курс ИИ, медоеду все, eugizus">
    <meta name="author" content="@eugizus (PostoFilya)">
    
    <!-- Open Graph для виральности в соцсетях -->
    <meta property="og:title" content="Максимум 10 человек. Интенсив ИИ с личным коачем.">
    <meta property="og:description" content="Видеокоч сессии + личный аудит + 7 дней результата. 7777 руб/неделя. Или бесплатный фристарт в @MedoeduZ">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://demodaygit.github.io/MedoEDUz/">
    <meta property="og:image" content="https://demodaygit.github.io/MedoEDUz/og-preview.jpg">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:locale" content="ru_RU">
    
    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Медоеду ВСЁ — Интенсив ИИ с личным коачем">
    <meta name="twitter:description" content="Максимум 10 мест. Видеосессии + результат за 7 дней. 7777 руб.">
    <meta name="twitter:image" content="https://demodaygit.github.io/MedoEDUz/twitter-preview.jpg">
    
    <!-- Schema.org JSON-LD -->
    <script type="application/ld+json">
    {
        "@context": "https://schema.org",
        "@type": "EducationalOrganization",
        "name": "Медоеду ВСЁ",
        "founder": {
            "@type": "Person",
            "name": "@eugizus",
            "url": "https://t.me/eugizus"
        },
        "url": "https://demodaygit.github.io/MedoEDUz/",
        "contactPoint": {
            "@type": "ContactPoint",
            "contactType": "Telegram",
            "url": "https://t.me/eugizus"
        },
        "description": "Личное наставничество в ИИ. Максимум 10 человек. Видеокоч + реальные проекты + жесткий фидбек.",
        "courses": [
            {
                "@type": "Course",
                "name": "ИИ интенсив за 7 дней",
                "description": "Личный коачинг + видеосессии + демонстрация реальных работ",
                "timeToComplete": "P7D"
            }
        ]
    }
    </script>
    
    <!-- Предзагрузка критических ресурсов -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700;900&family=Inter:wght@400;600;700;800;900&display=swap" rel="stylesheet" media="print" onload="this.media='all'">
    
    <style>
        /* CSS Variables — современный подход */
        :root {
            --color-primary: #FFB800;
            --color-primary-dark: #e5a500;
            --color-accent: #FF6B35;
            --color-bg: #0a0a0a;
            --color-bg-2: #141414;
            --color-text: #f0f0f0;
            --color-text-muted: #888;
            --color-border: rgba(255, 184, 0, 0.15);
            --color-border-hover: rgba(255, 184, 0, 0.4);
            --shadow-primary: 0 12px 32px rgba(255, 184, 0, 0.25);
            --shadow-primary-hover: 0 20px 48px rgba(255, 184, 0, 0.35);
            --gradient-hero: radial-gradient(ellipse at 75% 25%, rgba(255, 184, 0, 0.12), transparent 70%);
            --gradient-card: linear-gradient(135deg, rgba(255, 184, 0, 0.05), rgba(255, 107, 53, 0.05));
            --font-sans: 'Inter', -apple-system, BlinkMacSystemFont, system-ui, sans-serif;
            --font-mono: 'JetBrains Mono', 'Courier New', monospace;
        }

        /* Reset и базовые стили */
        *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; scroll-padding-top: 100px; }
        body {
            font-family: var(--font-sans);
            background: var(--color-bg);
            color: var(--color-text);
            line-height: 1.6;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
            -moz-osx-font-smoothing: grayscale;
        }

        /* Скрытый контент для скринридеров */
        .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0,0,0,0);
            white-space: nowrap;
            border: 0;
        }

        /* Критичные стили для CLS */
        .container { 
            width: min(100% - 48px, 1240px); 
            margin-inline: auto; 
            padding: 0 24px;
        }

        /* Header с backdrop-filter */
        header {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            background: rgba(10, 10, 10, 0.95);
            backdrop-filter: blur(20px) saturate(180%);
            -webkit-backdrop-filter: blur(20px) saturate(180%);
            border-bottom: 1px solid var(--color-border);
        }

        .header-inner {
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 80px;
            gap: 24px;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
            font-size: 28px;
            font-weight: 900;
            color: var(--color-primary);
            text-decoration: none;
            transition: transform 0.3s ease;
        }

        .logo:hover { transform: translateY(-2px); }
        .logo span { font-size: 36px; filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3)); }

        .nav-buttons {
            display: flex;
            gap: 16px;
            flex-wrap: wrap;
            justify-content: flex-end;
        }

        /* Кнопки с micro-interactions */
        .btn {
            padding: 14px 32px;
            border: none;
            border-radius: 12px;
            font-weight: 700;
            font-size: 15px;
            text-transform: uppercase;
            letter-spacing: 0.8px;
            text-decoration: none;
            color: inherit;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
            overflow: hidden;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            isolation: isolate;
        }

        .btn::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.2), transparent);
            transform: translateX(-100%);
            transition: transform 0.6s ease;
            z-index: -1;
        }

        .btn:hover::before { transform: translateX(100%); }

        .btn-primary {
            background: var(--color-primary);
            color: var(--color-bg);
            box-shadow: var(--shadow-primary);
        }

        .btn-primary:hover {
            background: #FFD700;
            transform: translateY(-4px) scale(1.02);
            box-shadow: var(--shadow-primary-hover);
        }

        .btn-secondary {
            background: transparent;
            color: var(--color-primary);
            border: 2px solid var(--color-primary);
        }

        .btn-secondary:hover {
            background: var(--color-primary);
            color: var(--color-bg);
            transform: translateY(-4px) scale(1.02);
        }

        .btn-large { padding: 22px 56px; font-size: 17px; }

        /* Hero section с продвинутыми эффектами */
        .hero {
            padding: 180px 0 80px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .hero::before {
            content: '';
            position: absolute;
            inset: 0;
            background: var(--gradient-hero);
            pointer-events: none;
            animation: pulse 8s ease-in-out infinite;
        }

        @keyframes pulse {
            0%, 100% { opacity: 0.6; }
            50% { opacity: 0.9; }
        }

        .hero-badge {
            display: inline-block;
            background: rgba(255, 184, 0, 0.15);
            border: 1px solid var(--color-primary);
            color: var(--color-primary);
            padding: 12px 32px;
            border-radius: 50px;
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1.2px;
            margin-bottom: 24px;
            backdrop-filter: blur(10px);
        }

        .hero h1 {
            font-size: clamp(48px, 8vw, 80px);
            font-weight: 900;
            line-height: 1.05;
            margin: 32px 0;
            letter-spacing: -1.5px;
        }

        .hero-highlight {
            color: var(--color-primary);
            text-shadow: 0 0 40px rgba(255, 184, 0, 0.3);
        }

        .hero p {
            font-size: 22px;
            max-width: 900px;
            margin: 0 auto 48px;
            opacity: 0.92;
            line-height: 1.4;
        }

        .hero-cta {
            display: flex;
            gap: 24px;
            justify-content: center;
            flex-wrap: wrap;
            margin: 60px 0 40px;
        }

        .hero-subtext {
            font-size: 14px;
            color: var(--color-text-muted);
            text-align: center;
            margin-bottom: 60px;
        }

        /* Stats с hover-эффектом */
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 32px;
            margin-top: 80px;
        }

        .stat {
            background: rgba(255, 184, 0, 0.07);
            border: 1px solid var(--color-border);
            padding: 36px 24px;
            border-radius: 16px;
            text-align: center;
            transition: all 0.4s ease;
            position: relative;
            overflow: hidden;
        }

        .stat::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, rgba(255, 184, 0, 0.1), transparent);
            opacity: 0;
            transition: opacity 0.4s ease;
        }

        .stat:hover::before { opacity: 1; }

        .stat-number {
            font-size: 56px;
            font-weight: 900;
            color: var(--color-primary);
            line-height: 1;
            margin-bottom: 8px;
        }

        .stat-text {
            font-size: 15px;
            text-transform: uppercase;
            letter-spacing: 1.2px;
            color: var(--color-text-muted);
        }

        /* Section стандарты */
        section {
            padding: 120px 0;
            position: relative;
        }

        .section-title {
            font-size: clamp(44px, 7vw, 72px);
            font-weight: 900;
            text-align: center;
            margin-bottom: 32px;
            line-height: 1.1;
        }

        .section-subtitle {
            font-size: 20px;
            text-align: center;
            max-width: 820px;
            margin: 0 auto 80px;
            opacity: 0.88;
            color: var(--color-text-muted);
        }

        /* Pricing Clarity */
        .pricing-clarity {
            background: rgba(255, 184, 0, 0.08);
            padding: 80px 0 !important;
            border-top: 1px solid var(--color-border);
            border-bottom: 1px solid var(--color-border);
        }

        .pricing-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 40px;
            max-width: 1000px;
            margin: 0 auto;
        }

        .pricing-box {
            padding: 36px;
            border-radius: 16px;
        }

        .pricing-box-free {
            background: transparent;
            border: 1px solid var(--color-border);
        }

        .pricing-box-paid {
            background: rgba(255, 184, 0, 0.12);
            border: 2px solid var(--color-primary);
            position: relative;
        }

        .pricing-box-paid::before {
            content: '🔥 ПОПУЛЯРНО';
            position: absolute;
            top: -12px;
            left: 50%;
            transform: translateX(-50%);
            background: var(--color-primary);
            color: var(--color-bg);
            padding: 6px 16px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 700;
            letter-spacing: 1px;
        }

        .pricing-title {
            font-size: 24px;
            font-weight: 800;
            color: var(--color-primary);
            margin-bottom: 24px;
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .pricing-list {
            list-style: none;
            font-size: 16px;
            line-height: 2;
            margin-bottom: 24px;
        }

        .pricing-list li {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .pricing-list li::before {
            content: '✓';
            color: var(--color-primary);
            font-weight: 900;
            font-size: 18px;
            flex-shrink: 0;
        }

        .pricing-price {
            font-size: 28px;
            font-weight: 900;
            color: var(--color-primary);
            margin: 24px 0 12px;
        }

        .pricing-subtitle {
            font-size: 13px;
            color: var(--color-text-muted);
            font-weight: 600;
        }

        /* Grid система */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(340px, 1fr));
            gap: 36px;
            align-items: start;
        }

        .card {
            background: var(--gradient-card);
            border: 1px solid var(--color-border);
            padding: 44px 36px;
            border-radius: 20px;
            transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            height: fit-content;
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: '';
            position: absolute;
            inset: 0;
            background: linear-gradient(135deg, rgba(255, 184, 0, 0.1), transparent);
            opacity: 0;
            transition: opacity 0.4s ease;
        }

        .card:hover::before { opacity: 1; }

        .card:hover {
            transform: translateY(-12px);
            border-color: var(--color-primary);
            box-shadow: 0 24px 48px rgba(255, 184, 0, 0.15);
        }

        .card-emoji {
            font-size: 48px;
            margin-bottom: 16px;
            display: block;
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.3));
        }

        .card h3 {
            font-size: 24px;
            margin: 20px 0 16px;
            color: var(--color-primary);
            font-weight: 800;
        }

        .card p {
            font-size: 16px;
            line-height: 1.6;
            color: var(--color-text-muted);
        }

        /* Philosophy section */
        .philosophy {
            background: linear-gradient(180deg, var(--color-bg-2), var(--color-bg));
        }

        .philosophy-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 80px;
            align-items: start;
        }

        .philosophy-text h3 {
            font-size: 36px;
            margin-bottom: 32px;
            color: var(--color-primary);
            font-weight: 900;
        }

        .philosophy-text p {
            font-size: 18px;
            margin-bottom: 24px;
            line-height: 1.6;
        }

        .philosophy-list {
            list-style: none;
            margin-top: 40px;
        }

        .philosophy-list li {
            padding: 20px 0 20px 60px;
            position: relative;
            border-bottom: 1px solid var(--color-border);
            font-size: 17px;
        }

        .philosophy-list li:last-child { border-bottom: none; }

        .philosophy-list li::before {
            content: '🦡';
            position: absolute;
            left: 0;
            font-size: 32px;
            filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3));
        }

        .philosophy-image {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            background: rgba(255, 184, 0, 0.08);
            border: 2px solid var(--color-primary);
            border-radius: 20px;
            padding: 60px 40px;
            text-align: center;
            min-height: 500px;
            position: relative;
        }

        /* Пчелиный контейнер и орбита */
        .bee-container {
            position: absolute;
            width: 280px;
            height: 280px;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            pointer-events: none;
        }

        .bee {
            position: absolute;
            font-size: 24px;
            cursor: pointer;
            transition: all 0.1s ease-out;
            font-weight: bold;
            filter: drop-shadow(0 2px 4px rgba(0, 0, 0, 0.3));
        }

        /* Орбиты для каждой пчелы */
        @keyframes orbit-1 {
            0% { transform: translate(140px, 0) rotateZ(0deg) scale(1); }
            50% { filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3)); }
            100% { transform: translate(140px, 0) rotateZ(360deg) scale(1); }
        }
        @keyframes orbit-2 {
            0% { transform: translate(0px, 140px) rotateZ(0deg) scale(1); }
            50% { filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3)); }
            100% { transform: translate(0px, 140px) rotateZ(360deg) scale(1); }
        }
        @keyframes orbit-3 {
            0% { transform: translate(-140px, 0px) rotateZ(0deg) scale(1); }
            50% { filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3)); }
            100% { transform: translate(-140px, 0px) rotateZ(360deg) scale(1); }
        }
        @keyframes orbit-4 {
            0% { transform: translate(0px, -140px) rotateZ(0deg) scale(1); }
            50% { filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3)); }
            100% { transform: translate(0px, -140px) rotateZ(360deg) scale(1); }
        }
        @keyframes orbit-5 {
            0% { transform: translate(100px, 100px) rotateZ(0deg) scale(1); }
            50% { filter: drop-shadow(0 4px 8px rgba(255, 184, 0, 0.3)); }
            100% { transform: translate(100px, 100px) rotateZ(360deg) scale(1); }
        }

        .bee-1 { animation: orbit-1 8s linear infinite; }
        .bee-2 { animation: orbit-2 7s linear infinite reverse; }
        .bee-3 { animation: orbit-3 9s linear infinite; }
        .bee-4 { animation: orbit-4 6.5s linear infinite reverse; }
        .bee-5 { animation: orbit-5 7.5s linear infinite; }

        .bee.fleeing {
            animation: none !important;
            transition: all 0.3s ease-out;
        }

        /* Honest section */
        .honest-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(360px, 1fr));
            gap: 32px;
        }

        .honest-card {
            background: rgba(255, 184, 0, 0.06);
            border-left: 5px solid var(--color-primary);
            padding: 36px;
            border-radius: 0 20px 20px 0;
            transition: transform 0.3s ease;
        }

        .honest-card:hover {
            transform: translateX(8px);
        }

        .honest-card h3 {
            font-size: 20px;
            font-weight: 700;
            margin-bottom: 16px;
            color: var(--color-primary);
        }

        .honest-card p {
            font-size: 16px;
            line-height: 1.6;
        }

        .honest-card a {
            color: var(--color-primary);
            text-decoration: underline;
            text-underline-offset: 4px;
        }

        /* CTA sections */
        .final-cta {
            background: linear-gradient(135deg, var(--color-bg-2), var(--color-bg));
            padding: 160px 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .final-cta::before {
            content: '';
            position: absolute;
            inset: 0;
            background: radial-gradient(circle at center, rgba(255, 184, 0, 0.1), transparent 70%);
            animation: pulse 6s ease-in-out infinite;
        }

        .final-cta h2 {
            font-size: clamp(48px, 8vw, 88px);
            margin-bottom: 40px;
            position: relative;
            z-index: 2;
        }

        .final-cta p {
            font-size: 24px;
            max-width: 900px;
            margin: 0 auto 60px;
            opacity: 0.9;
            position: relative;
            z-index: 2;
        }

        /* Footer */
        footer {
            padding: 80px 0 40px;
            border-top: 1px solid var(--color-border);
            text-align: center;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            gap: 48px;
            flex-wrap: wrap;
            margin-bottom: 32px;
        }

        .footer-links a {
            color: var(--color-text-muted);
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
            font-size: 16px;
        }

        .footer-links a:hover {
            color: var(--color-primary);
        }

        .footer-badge {
            color: var(--color-primary);
            margin-top: 20px;
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Анимации */
        .fade-up {
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.9s cubic-bezier(0.16, 1, 0.3, 1);
            will-change: transform, opacity;
        }

        .fade-up.visible {
            opacity: 1;
            transform: translateY(0);
        }

        .fade-in {
            animation: fadeIn 0.8s ease-in both;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Parallax эффект */
        .parallax {
            transform: translateY(var(--parallax-offset, 0));
            transition: transform 0.1s linear;
        }

        /* Кастомный курсор (прогрессивное улучшение) */
        @media (hover: hover) and (pointer: fine) {
            .cursor {
                width: 24px;
                height: 24px;
                border: 2px solid var(--color-primary);
                border-radius: 50%;
                position: fixed;
                pointer-events: none;
                z-index: 9999;
                transform: translate(-50%, -50%);
                transition: transform 0.1s ease;
                mix-blend-mode: difference;
            }
            .cursor-hover { transform: translate(-50%, -50%) scale(1.8); background: rgba(255, 184, 0, 0.3); }
        }

        /* Responsive - Tablet (768px) */
        @media (max-width: 768px) {
            .hero { padding: 120px 0 50px; }
            .hero h1 { font-size: clamp(32px, 9vw, 48px); }
            .hero p { font-size: 18px; }
            .hero-cta { flex-direction: column; align-items: center; gap: 16px; }
            .btn-large { width: 100%; max-width: 100%; }
            .hero-subtext { font-size: 12px; margin-bottom: 40px; }
            
            section { padding: 80px 0; }
            .section-title { font-size: clamp(32px, 8vw, 48px); }
            .section-subtitle { font-size: 16px; margin: 0 auto 50px; }
            
            .philosophy-grid { grid-template-columns: 1fr; gap: 40px; }
            .pricing-grid { grid-template-columns: 1fr; gap: 24px; }
            .grid { grid-template-columns: 1fr; gap: 20px; }
            
            .header-inner { height: 60px; gap: 8px; }
            .logo { font-size: 20px; }
            .logo span { font-size: 28px; }
            .nav-buttons { gap: 6px; }
            .btn { padding: 10px 14px; font-size: 12px; letter-spacing: 0.3px; white-space: nowrap; }
            .btn-large { padding: 16px 32px; font-size: 15px; }
            
            .card { padding: 28px 24px; }
            .card h3 { font-size: 20px; margin: 16px 0 12px; }
            .card p { font-size: 15px; }
            .card-emoji { font-size: 40px; }
            
            .stats { gap: 20px; margin-top: 60px; }
            .stat { padding: 24px 16px; }
            .stat-number { font-size: 44px; margin-bottom: 6px; }
            .stat-text { font-size: 13px; }
            
            .pricing-box { padding: 24px; }
            .pricing-title { font-size: 20px; margin-bottom: 16px; }
            .pricing-list { font-size: 14px; line-height: 1.8; margin-bottom: 16px; }
            .pricing-price { font-size: 24px; margin: 16px 0 8px; }
            .pricing-subtitle { font-size: 12px; }
            
            .philosophy-text h3 { font-size: 28px; margin-bottom: 20px; }
            .philosophy-text p { font-size: 16px; margin-bottom: 16px; }
            .honest-card { padding: 24px; border-left-width: 4px; }
            .honest-card h3 { font-size: 18px; margin-bottom: 12px; }
            .honest-card p { font-size: 15px; }
            
            .final-cta h2 { font-size: clamp(36px, 8vw, 64px); margin-bottom: 24px; }
            .final-cta p { font-size: 18px; margin: 0 auto 40px; }
            
            .footer-links { gap: 24px; flex-wrap: wrap; }
            .footer-links a { font-size: 14px; }
        }

        /* Responsive - Small Phone (600px) */
        @media (max-width: 600px) {
            .container { 
                width: min(100% - 32px, 100%); 
                padding: 0 16px;
            }
            
            .hero { padding: 100px 0 40px; }
            .hero h1 { font-size: clamp(28px, 8vw, 40px); line-height: 1.1; }
            .hero p { font-size: 16px; margin: 0 auto 32px; }
            .hero-badge { padding: 10px 24px; font-size: 12px; margin-bottom: 16px; }
            .hero-cta { gap: 12px; margin: 40px 0 24px; }
            .hero-subtext { font-size: 11px; margin-bottom: 32px; }
            
            section { padding: 60px 0; }
            .section-title { font-size: clamp(28px, 7vw, 40px); margin-bottom: 20px; }
            .section-subtitle { font-size: 15px; margin: 0 auto 40px; }
            
            .pricing-clarity { padding: 50px 0; }
            .pricing-grid { gap: 16px; }
            .pricing-box { padding: 20px; border-radius: 12px; }
            .pricing-box-paid::before { top: -10px; font-size: 11px; padding: 4px 12px; }
            .pricing-title { font-size: 18px; margin-bottom: 12px; }
            .pricing-list { font-size: 13px; line-height: 1.7; margin-bottom: 12px; }
            .pricing-list li { gap: 8px; }
            .pricing-price { font-size: 22px; margin: 12px 0 6px; }
            .pricing-subtitle { font-size: 11px; }
            
            .card { padding: 20px; border-radius: 16px; }
            .card h3 { font-size: 18px; margin: 12px 0 10px; }
            .card p { font-size: 14px; line-height: 1.5; }
            .card-emoji { font-size: 36px; margin-bottom: 12px; }
            
            .grid { gap: 16px; }
            
            .stats { grid-template-columns: repeat(2, 1fr); gap: 12px; margin-top: 40px; }
            .stat { padding: 16px 12px; border-radius: 12px; }
            .stat-number { font-size: 36px; margin-bottom: 4px; }
            .stat-text { font-size: 11px; letter-spacing: 0.8px; }
            
            .header-inner { height: 56px; }
            .logo { font-size: 18px; gap: 8px; }
            .logo span { font-size: 24px; }
            .nav-buttons { gap: 6px; }
            .btn { padding: 10px 18px; font-size: 12px; letter-spacing: 0.4px; border-radius: 10px; }
            .btn-large { padding: 14px 28px; font-size: 14px; }
            
            .philosophy-grid { gap: 32px; }
            .philosophy-text h3 { font-size: 24px; margin-bottom: 16px; }
            .philosophy-text p { font-size: 15px; margin-bottom: 12px; }
            .philosophy-list li { padding: 12px 0 12px 40px; font-size: 14px; }
            .philosophy-list li::before { font-size: 20px; left: 0; }
            .philosophy-image { min-height: 300px; padding: 32px 24px; }
            .philosophy-image > div:first-child { font-size: 80px; margin-bottom: 12px; }
            .philosophy-image > p { font-size: 15px; }
            
            .honest-grid { gap: 16px; }
            .honest-card { padding: 20px; border-left-width: 4px; border-radius: 0 12px 12px 0; }
            .honest-card h3 { font-size: 16px; margin-bottom: 10px; }
            .honest-card p { font-size: 14px; line-height: 1.5; }
            
            .final-cta { padding: 100px 0; }
            .final-cta h2 { font-size: clamp(28px, 7vw, 48px); margin-bottom: 20px; }
            .final-cta p { font-size: 16px; margin: 0 auto 32px; }
            
            footer { padding: 50px 0 24px; }
            .footer-links { gap: 16px; flex-wrap: wrap; }
            .footer-links a { font-size: 13px; }
        }

        /* Responsive - Extra Small (400px) */
        @media (max-width: 400px) {
            .container { padding: 0 12px; }
            
            .hero { padding: 80px 0 32px; }
            .hero h1 { font-size: clamp(24px, 7vw, 36px); }
            .hero p { font-size: 15px; margin: 0 auto 24px; }
            .hero-badge { padding: 8px 20px; font-size: 11px; }
            .hero-cta { gap: 10px; margin: 32px 0 16px; }
            .hero-subtext { font-size: 10px; }
            
            section { padding: 50px 0; }
            .section-title { font-size: clamp(24px, 6vw, 32px); }
            .section-subtitle { font-size: 14px; margin: 0 auto 32px; }
            
            .pricing-grid { gap: 12px; }
            .pricing-box { padding: 16px; }
            .pricing-title { font-size: 16px; margin-bottom: 10px; }
            .pricing-list { font-size: 12px; line-height: 1.6; margin-bottom: 10px; }
            .pricing-price { font-size: 20px; margin: 10px 0 4px; }
            
            .card { padding: 16px; }
            .card h3 { font-size: 16px; margin: 10px 0 8px; }
            .card p { font-size: 13px; }
            .card-emoji { font-size: 32px; }
            
            .stats { grid-template-columns: repeat(2, 1fr); gap: 10px; margin-top: 32px; }
            .stat { padding: 12px 10px; }
            .stat-number { font-size: 32px; }
            .stat-text { font-size: 10px; }
            
            .header-inner { height: 52px; }
            .logo { font-size: 16px; }
            .logo span { font-size: 20px; }
            .btn { padding: 9px 16px; font-size: 11px; }
            .btn-large { padding: 12px 24px; font-size: 13px; }
            
            .philosophy-text h3 { font-size: 20px; margin-bottom: 12px; }
            .philosophy-text p { font-size: 14px; }
            .philosophy-list li { padding: 10px 0 10px 36px; font-size: 13px; }
            .philosophy-list li::before { font-size: 18px; }
            .philosophy-image { min-height: 250px; padding: 24px 16px; }
            .philosophy-image > div:first-child { font-size: 64px; margin-bottom: 8px; }
            
            .honest-card { padding: 16px; }
            .honest-card h3 { font-size: 15px; margin-bottom: 8px; }
            .honest-card p { font-size: 13px; }
            
            .final-cta { padding: 80px 0; }
            .final-cta h2 { font-size: clamp(22px, 6vw, 36px); margin-bottom: 16px; }
            .final-cta p { font-size: 14px; margin: 0 auto 24px; }
        }
    </style>
<base target="_blank">
</head>
<body>

    <!-- Кастомный курсор -->
    <div class="cursor" aria-hidden="true"></div>

    <!-- Header -->
    <header>
        <div class="container">
            <div class="header-inner">
                <a href="/" class="logo" aria-label="Медоеду ВСЁ — главная">
                    <span role="img" aria-label="Honey badger">🦡</span>
                    <span>МЕДОЕДУ ВСЁ</span>
                </a>
                <nav class="nav-buttons" role="navigation" aria-label="Основная навигация">
                    <a href="https://t.me/MedoeduZ" target="_blank" rel="noopener noreferrer" class="btn btn-secondary">
                        @MedoeduZ
                    </a>
                    <a href="https://t.me/eugizus" target="_blank" rel="noopener noreferrer" class="btn btn-primary">
                        Интенсив 7777 ₽
                    </a>
                </nav>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero" aria-labelledby="hero-title">
        <div class="container">
            <div class="hero-badge fade-up" role="banner">
                🔥 МАКСИМУМ 10 ЧЕЛОВЕК • ЛИЧНЫЙ КОАЧ • ВИДЕОСЕССИИ
            </div>
            <h1 class="hero-title fade-up" id="hero-title">
                Не учебный центр.<br>
                <span class="hero-highlight">Личное наставничество в ИИ.</span>
            </h1>
            <p class="fade-up">
                Один преподаватель (@eugizus). Видеокоч сессии. Реальные проекты.<br>
                Демонстрация как я это делаю в боевых условиях.<br>
                <strong>7777 руб за неделю интенсива</strong> или фристарт в сообществе прямо сейчас.
            </p>
            
            <div class="hero-cta fade-up" role="group" aria-label="Призыв к действию">
                <a href="https://t.me/eugizus" target="_blank" rel="noopener noreferrer" class="btn btn-primary btn-large">
                    📧 Записаться на интенсив
                </a>
                <a href="https://t.me/MedoeduZ" target="_blank" rel="noopener noreferrer" class="btn btn-secondary btn-large">
                    🦡 Начать с фристарта
                </a>
            </div>

            <p class="hero-subtext">
                ⚠️ Максимум 10 мест на группу. Сейчас ~6 свободных. Первых там не будет.
            </p>

            <div class="stats" role="list" aria-label="Статистика проекта">
                <div class="stat fade-up" role="listitem">
                    <div class="stat-number">1</div>
                    <div class="stat-text">Преподаватель</div>
                </div>
                <div class="stat fade-up" role="listitem">
                    <div class="stat-number">10</div>
                    <div class="stat-text">Максимум учеников</div>
                </div>
                <div class="stat fade-up" role="listitem">
                    <div class="stat-number">7</div>
                    <div class="stat-text">Дней интенсива</div>
                </div>
                <div class="stat fade-up" role="listitem">
                    <div class="stat-number">3–4</div>
                    <div class="stat-text">Часов видеосессий/неделю</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Как это работает -->
    <section class="pricing-clarity" aria-labelledby="pricing-title">
        <div class="container">
            <h2 class="section-title fade-up" id="pricing-title">
                Как это работает? <span class="hero-highlight">Честно.</span>
            </h2>
            
            <div class="pricing-grid">
                <!-- УРОВЕНЬ 1: Фристарт -->
                <div class="pricing-box pricing-box-free fade-up">
                    <h3 class="pricing-title">📱 Уровень 1: Фристарт</h3>
                    <ul class="pricing-list">
                        <li>Сообщество @MedoeduZ (400+ человек)</li>
                        <li>Я показываю инструменты, которые юзаю</li>
                        <li>Демонстрация реальных работ</li>
                        <li>Как добывать ИИ-знания самостоятельно</li>
                        <li>Бот @Medo_cyberbot бесплатный</li>
                    </ul>
                    <div class="pricing-price">0 ₽</div>
                    <p class="pricing-subtitle">Неограниченно. Начни прямо сейчас.</p>
                    <a href="https://t.me/MedoeduZ" class="btn btn-secondary" style="width: 100%; margin-top: 24px;">
                        Вступить в @MedoeduZ
                    </a>
                </div>

                <!-- УРОВЕНЬ 2: Интенсив -->
                <div class="pricing-box pricing-box-paid fade-up">
                    <h3 class="pricing-title">🚀 Уровень 2: Интенсив</h3>
                    <ul class="pricing-list">
                        <li>Личное наставничество (макс 10 мест)</li>
                        <li>Видеокоч сессии 3–4 часа/неделю</li>
                        <li>Личный аудит твоих инструментов</li>
                        <li>Жесткий фидбек по результатам</li>
                        <li>Демонстрация моих боевых работ</li>
                        <li>Как я добываю информацию в открытых источниках</li>
                    </ul>
                    <div class="pricing-price">7777 ₽</div>
                    <p class="pricing-subtitle">За неделю интенсива. Оплата: ТГ Stars или TON.</p>
                    <a href="https://t.me/eugizus" class="btn btn-primary" style="width: 100%; margin-top: 24px;">
                        Записаться сейчас
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="section problem" id="problem" aria-labelledby="problem-title">
        <div class="container">
            <h2 class="section-title fade-up" id="problem-title">
                Ты уже отстаёшь.<br>
                Это не паника — это <span class="hero-highlight">факт</span>.
            </h2>
            <div class="grid">
                <article class="card fade-up">
                    <span class="card-emoji">⏰</span>
                    <h3>Время уходит впустую</h3>
                    <p>Пока ты «изучаешь», другие уже зарабатывают на ИИ в 3–10× быстрее. Каждый день — это упущенная тысяча.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">😵</span>
                    <h3>Информационный хаос</h3>
                    <p>Тысячи курсов, видео, туториалов — и ни одного рабочего пути. Только воды и ложных обещаний.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">💸</span>
                    <h3>Деньги на ветер</h3>
                    <p>Платил за «премиум-курсы» по 100k, а в итоге всё равно делаешь вручную. Потому что не было практики.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">🌀</span>
                    <h3>Паралич выбора</h3>
                    <p>ChatGPT, Claude, Midjourney, Runway, Copilot… С чего начать? Что реально работает? Кто скажет правду?</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">😞</span>
                    <h3>Чувство отсталости</h3>
                    <p>Все вокруг уже используют ИИ, а ты всё ещё «потом разберусь». Завтра будет поздно.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">💼</span>
                    <h3>Работодатель требует</h3>
                    <p>«ИИ-навыки обязательны» — уже не привилегия, а requirement. Без этого твоё CV идёт в корзину.</p>
                </article>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section class="section solution" id="solution" aria-labelledby="solution-title">
        <div class="container">
            <h2 class="section-title fade-up" id="solution-title">
                Решение одно — <span class="hero-highlight">боевая подготовка</span>
            </h2>
            <div class="grid">
                <article class="card fade-up">
                    <span class="card-emoji">🎯</span>
                    <h3>Только практика</h3>
                    <p>Никакой воды. С первого дня — реальные проекты, которые можно показать клиенту или работодателю.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">👤</span>
                    <h3>Персональный подход</h3>
                    <p>Я @eugizus лично отвечаю каждому. Максимум 10 человек. Никаких менеджеров, только прямой контакт.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">🔥</span>
                    <h3>Честность 100%</h3>
                    <p>Нет фейковых отзывов. Лучше меньше людей, но с реальным результатом.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">💻</span>
                    <h3>Мои реальные работы</h3>
                    <p>GitHub репозиторий с кодом, примеры моих проектов. Вот как это делается в реальности, копай код сам.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">🦡</span>
                    <h3>Комьюнити медоедов</h3>
                    <p>Люди, которые не боятся быть первыми. Взаимопомощь, совместные проекты, рост вместе.</p>
                </article>
                <article class="card fade-up">
                    <span class="card-emoji">🚀</span>
                    <h3>Система, которая растёт</h3>
                    <p>Сейчас — курс + бот. Скоро — персональные агенты и новые боевые инструменты. Ты инвестируешь в живой проект.</p>
                </article>
            </div>
        </div>
    </section>

    <!-- Фришные инструменты - краткий список -->
    <section class="section" id="free-tools" style="background: rgba(255, 184, 0, 0.06);">
        <div class="container">
            <h2 class="section-title fade-up">
                Начинаешь с нуля?<br>
                <span class="hero-highlight">Всё что нужно — бесплатное</span>
            </h2>
            <p class="section-subtitle fade-up">
                Не нужно платить за подписки. Всё для результата уже есть. Бесплатно.
            </p>
            
            <div style="max-width: 900px; margin: 0 auto; background: rgba(255, 184, 0, 0.08); border: 1px solid var(--color-border); border-radius: 16px; padding: 40px; text-align: center;">
                <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 24px; margin-bottom: 32px;">
                    <div class="fade-up" style="padding: 20px;">
                        <div style="font-size: 32px; margin-bottom: 12px;">💬</div>
                        <p style="font-weight: 700; color: var(--color-primary); margin-bottom: 6px;">ChatGPT</p>
                        <p style="font-size: 13px; color: var(--color-text-muted);">Текст, код, идеи</p>
                    </div>
                    <div class="fade-up" style="padding: 20px;">
                        <div style="font-size: 32px; margin-bottom: 12px;">🎨</div>
                        <p style="font-weight: 700; color: var(--color-primary); margin-bottom: 6px;">Midjourney</p>
                        <p style="font-size: 13px; color: var(--color-text-muted);">Генерация визуала</p>
                    </div>
                    <div class="fade-up" style="padding: 20px;">
                        <div style="font-size: 32px; margin-bottom: 12px;">⚙️</div>
                        <p style="font-weight: 700; color: var(--color-primary); margin-bottom: 6px;">ComfyUI</p>
                        <p style="font-size: 13px; color: var(--color-text-muted);">Локальная генерация</p>
                    </div>
                    <div class="fade-up" style="padding: 20px;">
                        <div style="font-size: 32px; margin-bottom: 12px;">🎥</div>
                        <p style="font-weight: 700; color: var(--color-primary); margin-bottom: 6px;">CapCut</p>
                        <p style="font-size: 13px; color: var(--color-text-muted);">Видеомонтаж + AI</p>
                    </div>
                    <div class="fade-up" style="padding: 20px;">
                        <div style="font-size: 32px; margin-bottom: 12px;">📊</div>
                        <p style="font-weight: 700; color: var(--color-primary); margin-bottom: 6px;">Sheets + Python</p>
                        <p style="font-size: 13px; color: var(--color-text-muted);">Аналитика</p>
                    </div>
                    <div class="fade-up" style="padding: 20px;">
                        <div style="font-size: 32px; margin-bottom: 12px;">💻</div>
                        <p style="font-weight: 700; color: var(--color-primary); margin-bottom: 6px;">GitHub + Claude</p>
                        <p style="font-size: 13px; color: var(--color-text-muted);">Код & разработка</p>
                    </div>
                </div>
                
                <p style="font-size: 18px; color: var(--color-primary); font-weight: 700; margin-top: 24px;">
                    Итого: 0 ₽. Платишь только за время и внимание.
                </p>
            </div>
        </div>
    </section>

    <!-- Philosophy Section -->
    <section class="section philosophy" id="philosophy" aria-labelledby="philosophy-title">
        <div class="container">
            <div class="philosophy-grid">
                <div class="philosophy-text fade-up">
                    <h3 id="philosophy-title">Философия медоеда</h3>
                    <p>Медоед не жалуется на обстоятельства. У него 30 килограммов веса и он не боится львов. Почему? Потому что <strong>не думает — действует</strong>.</p>
                    <p>Один преподаватель, один проект, одна идея: научить людей работать с ИИ честно, без маркетинговой лжи и фейковых отзывов.</p>
                    <p>ИИ — это не опция. Это дефолт. И если ты это понимаешь, ты уже впереди 90% людей. Теперь нужно только сделать следующий шаг.</p>
                </div>
                <div class="philosophy-image fade-up" aria-hidden="true" style="position: relative;">
                    <!-- Пчелы вокруг медоеда -->
                    <div class="bee-container">
                        <div class="bee bee-1">🐝</div>
                        <div class="bee bee-2">🐝</div>
                        <div class="bee bee-3">🐝</div>
                        <div class="bee bee-4">🐝</div>
                        <div class="bee bee-5">🐝</div>
                    </div>

                    <!-- Медоед в центре -->
                    <div style="font-size: 120px; margin-bottom: 20px;" role="img" aria-label="Медоед">🦡</div>
                    <p style="color: var(--color-primary); font-weight: 900; font-size: 20px; margin-bottom: 8px;">
                        МЕДОЕДУ ВСЁ
                    </p>
                    <p style="color: var(--color-text-muted); font-weight: 700; font-size: 16px;">
                        = тебе всё, если ты готов действовать
                    </p>
                </div>
            </div>
        </div>
    </section>
    <section class="section" id="courses" aria-labelledby="courses-title" style="background: rgba(255, 184, 0, 0.04);">
        <div class="container">
            <h2 class="section-title fade-up" id="courses-title">
                Шесть боевых дисциплин
            </h2>
            <p class="section-subtitle fade-up">
                Выбираешь своё направление — за 7 дней результат + готовый для продажи артефакт
            </p>
            <div class="grid">
                <article class="card fade-up" style="position: relative; overflow: visible;">
                    <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px;">
                        <span class="card-emoji">🎨</span>
                        <span style="background: rgba(255, 107, 53, 0.8); color: white; padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.8px;">НАЧИНАЮЩИЙ</span>
                    </div>
                    <h3>Визуал-гиперболоид</h3>
                    <p style="margin-bottom: 16px;">Midjourney • Firefly • ComfyUI • Runway</p>
                    <p style="color: var(--color-primary); font-weight: 700; font-size: 14px;">✓ Портфолио изображений</p>
                </article>
                <article class="card fade-up" style="position: relative; overflow: visible;">
                    <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px;">
                        <span class="card-emoji">✍️</span>
                        <span style="background: rgba(255, 107, 53, 0.8); color: white; padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.8px;">НАЧИНАЮЩИЙ</span>
                    </div>
                    <h3>Копирайтер-ассасин</h3>
                    <p style="margin-bottom: 16px;">Claude • ChatGPT • Perplexity • NotebookLM</p>
                    <p style="color: var(--color-primary); font-weight: 700; font-size: 14px;">✓ Тексты, которые продают</p>
                </article>
                <article class="card fade-up" style="position: relative; overflow: visible;">
                    <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px;">
                        <span class="card-emoji">💻</span>
                        <span style="background: #FF3333; color: white; padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.8px;">ПРОДВИНУТЫЙ</span>
                    </div>
                    <h3>Кодер-киборг</h3>
                    <p style="margin-bottom: 16px;">GitHub Copilot • Claude • Cursor • v0</p>
                    <p style="color: var(--color-primary); font-weight: 700; font-size: 14px;">✓ MVP за часы</p>
                </article>
                <article class="card fade-up" style="position: relative; overflow: visible;">
                    <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px;">
                        <span class="card-emoji">🎬</span>
                        <span style="background: rgba(255, 107, 53, 0.8); color: white; padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.8px;">НАЧИНАЮЩИЙ</span>
                    </div>
                    <h3>Видеомонтажник+</h3>
                    <p style="margin-bottom: 16px;">Runway • CapCut • DaVinci + AI</p>
                    <p style="color: var(--color-primary); font-weight: 700; font-size: 14px;">✓ Видео за часы</p>
                </article>
                <article class="card fade-up" style="position: relative; overflow: visible;">
                    <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px;">
                        <span class="card-emoji">📊</span>
                        <span style="background: var(--color-primary); color: var(--color-bg); padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.8px;">СРЕДНИЙ</span>
                    </div>
                    <h3>Аналитик-магистр</h3>
                    <p style="margin-bottom: 16px;">Claude Projects • Python • Sheets</p>
                    <p style="color: var(--color-primary); font-weight: 700; font-size: 14px;">✓ Аналитика 10×</p>
                </article>
                <article class="card fade-up" style="position: relative; overflow: visible;">
                    <div style="display: flex; justify-content: space-between; align-items: flex-start; margin-bottom: 8px;">
                        <span class="card-emoji">🚀</span>
                        <span style="background: #FF3333; color: white; padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: 700; letter-spacing: 0.8px;">ПРОДВИНУТЫЙ</span>
                    </div>
                    <h3>Супер-инженер ИИ</h3>
                    <p style="margin-bottom: 16px;">RAG • Fine-tuning • Agents • API</p>
                    <p style="color: var(--color-primary); font-weight: 700; font-size: 14px;">✓ Свой ИИ-продукт</p>
                </article>
            </div>
        </div>
    </section>

    <!-- Honest Section -->
    <section class="section honest" id="honest" aria-labelledby="honest-title" style="background: rgba(255, 184, 0, 0.04);">
        <div class="container">
            <h2 class="section-title fade-up" id="honest-title">
                Честно про проект<br>
                <span style="font-size: 60%; opacity: 0.8;">(без маркетинговой лжи)</span>
            </h2>
            <div class="honest-grid">
                <article class="honest-card fade-up">
                    <h3>🚨 Максимум 10 человек. Точка.</h3>
                    <p>Это не маркетинговый трюк. Я физически не могу дать качественное внимание больше чем 10 ученикам одновременно. Видеокоч, аудит, фидбек — это требует часов. Лучше 10 с результатом, чем 1000 без.</p>
                </article>
                <article class="honest-card fade-up">
                    <h3>💸 Я не даю гарантий. Вот почему.</h3>
                    <p>Если я обещаю результат — я лгу. Я даю вектор, инструменты, демонстрацию, фидбек. Результат — твое. Медоед не передает ответственность. Ты — хозяин своего обучения.</p>
                </article>
                <article class="honest-card fade-up">
                    <h3>👤 Кто преподаёт?</h3>
                    <p>Один человек — <strong>@eugizus</strong> (PostoFilya). Физик по образованию, ИИ-маньяк по жизни. Никаких «команд опытных преподов». Только я и 100% ответственности.</p>
                </article>
                <article class="honest-card fade-up">
                    <h3>📊 Метрика успеха</h3>
                    <p>Не количество учеников, не доход. Метрика одна: <strong>продуктивное использование ИИ инструментов в разных областях твоей жизни</strong>. Расширение кругозора и видение новых возможностей.</p>
                </article>
                <article class="honest-card fade-up">
                    <h3>🚀 Что будет дальше?</h3>
                    <p>Специальные образовательные агенты. Персональные боты-наставники. Расширение спектра. <strong>Ты инвестируешь в проект, который растёт</strong> на твоих глазах. Это не финальный продукт — это начало.</p>
                </article>
                <article class="honest-card fade-up">
                    <h3>🤝 Донаты — поддержка проекта</h3>
                    <p>Если тебе помогло — кинь на развитие. Это поддерживает мою мотивацию создавать дальше. Я могу принять через ТГ Stars или TON. Это инвестиция в будущее проекта.</p>
                </article>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="final-cta" aria-labelledby="final-cta-title">
        <div class="container">
            <h2 class="fade-up" id="final-cta-title">
                Медоед не ждёт завтра.<br>
                Он берёт <span class="hero-highlight">всё сегодня</span>.
            </h2>
            <p class="fade-up">
                Твой конкурент уже в чате.<br>
                Первыми будут только те, кто не боится.<br>
                Мест осталось немного.
            </p>
            <div class="hero-cta fade-up">
                <a href="https://t.me/eugizus" target="_blank" rel="noopener noreferrer" class="btn btn-primary btn-large">
                    Записаться на интенсив прямо сейчас 🦡
                </a>
                <a href="https://t.me/MedoeduZ" target="_blank" rel="noopener noreferrer" class="btn btn-secondary btn-large">
                    Или начать с фристарта в сообществе
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer role="contentinfo">
        <div class="container">
            <nav class="footer-links" aria-label="Ссылки проекта">
                <a href="https://t.me/eugizus" target="_blank" rel="noopener noreferrer">💌 Личное сообщение</a>
                <a href="https://t.me/MedoeduZ" target="_blank" rel="noopener noreferrer">📱 Сообщество</a>
                <a href="https://t.me/Medo_cyberbot" target="_blank" rel="noopener noreferrer">🤖 Бот @Medo_cyberbot</a>
                <a href="https://github.com/DemoDaygit" target="_blank" rel="noopener noreferrer">💻 GitHub</a>
            </nav>
            <p class="footer-badge">Проект одного человека и кучи ИИ инструментов. Сделано агрессивно и с верой в лучшее 🦡⚡</p>
        </div>
    </footer>

    <!-- JavaScript -->
    <script>
        // Intersection Observer для анимаций
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, {
            threshold: 0.1,
            rootMargin: '0px 0px -80px 0px'
        });

        document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));

        // Smooth scroll для якорей
        if (window.matchMedia('(hover: hover) and (pointer: fine)').matches) {
            const cursor = document.querySelector('.cursor');
            let mouseX = 0, mouseY = 0;
            let cursorX = 0, cursorY = 0;

            document.addEventListener('mousemove', (e) => {
                mouseX = e.clientX;
                mouseY = e.clientY;

                // Интерактивность пчел - они пугаются от курсора
                const bees = document.querySelectorAll('.bee');
                bees.forEach(bee => {
                    const beeRect = bee.getBoundingClientRect();
                    const beeX = beeRect.left + beeRect.width / 2;
                    const beeY = beeRect.top + beeRect.height / 2;
                    
                    const distance = Math.sqrt((mouseX - beeX) ** 2 + (mouseY - beeY) ** 2);
                    
                    if (distance < 150) {
                        // Пчела пугается - летит от курсора
                        bee.classList.add('fleeing');
                        
                        const angle = Math.atan2(beeY - mouseY, beeX - mouseX);
                        const speed = 120;
                        const newX = Math.cos(angle) * speed;
                        const newY = Math.sin(angle) * speed;
                        
                        bee.style.transform = `translate(${newX}px, ${newY}px) scale(1.15)`;
                    } else if (distance < 300) {
                        // На промежуточном расстоянии пчела колеблется
                        bee.classList.add('fleeing');
                        const angle = Math.atan2(beeY - mouseY, beeX - mouseX);
                        const speed = 40;
                        const newX = Math.cos(angle) * speed;
                        const newY = Math.sin(angle) * speed;
                        bee.style.transform = `translate(${newX}px, ${newY}px) scale(1.05)`;
                    } else {
                        // Пчела возвращается на орбиту
                        bee.classList.remove('fleeing');
                        bee.style.transform = '';
                    }
                });
            });

            function animateCursor() {
                cursorX += (mouseX - cursorX) * 0.15;
                cursorY += (mouseY - cursorY) * 0.15;
                cursor.style.left = cursorX + 'px';
                cursor.style.top = cursorY + 'px';
                requestAnimationFrame(animateCursor);
            }
            animateCursor();

            document.querySelectorAll('a, button').forEach(el => {
                el.addEventListener('mouseenter', () => cursor.classList.add('cursor-hover'));
                el.addEventListener('mouseleave', () => cursor.classList.remove('cursor-hover'));
            });
        }

        // Поддержка мобильных устройств - пчелы реагируют на касание
        const bees = document.querySelectorAll('.bee');
        bees.forEach(bee => {
            bee.addEventListener('touchstart', (e) => {
                bee.style.transform = `translate(${Math.random() * 100 - 50}px, ${Math.random() * 100 - 50}px) scale(1.15)`;
                bee.classList.add('fleeing');
            });
            
            bee.addEventListener('touchend', () => {
                setTimeout(() => {
                    bee.classList.remove('fleeing');
                    bee.style.transform = '';
                }, 500);
            });
        });

        // Smooth scroll для якорей
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

        // Предотвращение CLS при загрузке
        window.addEventListener('load', () => {
            document.body.classList.add('loaded');
        });

        // Консоль-лог для тех, кто смотрит код
        console.log('%c🦡 Медоеду ВСЁ', 'color: #FFB800; font-size: 24px; font-weight: bold;');
        console.log('%c@eugizus | @MedoeduZ | Личное наставничество в ИИ', 'color: #FF6B35; font-size: 16px;');
        console.log('%cМаксимум 10 человек. Только качество.', 'color: #888; font-size: 14px;');
    </script>

</body>
</html>

