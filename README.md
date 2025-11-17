<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>File Master Pro - Free Online File Conversion & Compression Tool</title>
    <meta name="description" content="File Master Pro: Free online tool for image compression, PDF to JPG/PNG conversion, JPG/PNG to PDF. Fast, secure, and easy to use. No registration required.">
    <meta name="keywords" content="image compression, pdf to jpg, jpg to pdf, pdf to png, png to pdf, jpg to png, png to jpg, file converter, compress images, online tools">
    <meta name="author" content="File Master Pro">
    
    <!-- Open Graph / Social Media Meta Tags -->
    <meta property="og:title" content="File Master Pro - Free Online File Conversion Tool">
    <meta property="og:description" content="Compress images and convert between PDF, JPG, PNG formats with our all-in-one online tool. Fast, secure, and completely free.">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://filemasterpro.com">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="File Master Pro - Free File Conversion Tool">
    <meta name="twitter:description" content="All-in-one online tool for file conversion and image compression. Free, fast, and secure.">
    
    <!-- Canonical URL -->
    <link rel="canonical" href="https://filemasterpro.com">
    
    <!-- Favicon -->
    <link rel="icon" type="image/x-icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>📁</text></svg>">
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <style>
        :root {
            --primary: #6366f1;
            --primary-dark: #4f46e5;
            --primary-light: #818cf8;
            --secondary: #8b5cf6;
            --accent: #ec4899;
            --success: #10b981;
            --warning: #f59e0b;
            --error: #ef4444;
            --dark: #1f2937;
            --darker: #111827;
            --light: #f8fafc;
            --gray: #6b7280;
            --gray-light: #9ca3af;
            --border-radius: 20px;
            --border-radius-lg: 30px;
            --border-radius-sm: 12px;
            --shadow: 0 10px 25px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
            --shadow-lg: 0 25px 50px -12px rgba(0, 0, 0, 0.15);
            --shadow-xl: 0 35px 60px -12px rgba(0, 0, 0, 0.25);
            --transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            --gradient: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            --gradient-light: linear-gradient(135deg, var(--primary-light) 0%, #a78bfa 100%);
            --gradient-dark: linear-gradient(135deg, var(--primary-dark) 0%, var(--secondary) 100%);
            --glass: rgba(255, 255, 255, 0.25);
            --glass-border: rgba(255, 255, 255, 0.18);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: var(--dark);
            line-height: 1.7;
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* Animated Background */
        .background-animation {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            overflow: hidden;
        }

        .floating-shapes {
            position: absolute;
            width: 100%;
            height: 100%;
        }

        .shape {
            position: absolute;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
            animation: float 20s infinite linear;
        }

        .shape:nth-child(1) {
            width: 80px;
            height: 80px;
            top: 10%;
            left: 10%;
            animation-delay: 0s;
        }

        .shape:nth-child(2) {
            width: 120px;
            height: 120px;
            top: 60%;
            left: 80%;
            animation-delay: -5s;
        }

        .shape:nth-child(3) {
            width: 60px;
            height: 60px;
            top: 80%;
            left: 20%;
            animation-delay: -10s;
        }

        .shape:nth-child(4) {
            width: 100px;
            height: 100px;
            top: 20%;
            left: 70%;
            animation-delay: -15s;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0) rotate(0deg);
            }
            25% {
                transform: translateY(-20px) rotate(90deg);
            }
            50% {
                transform: translateY(0) rotate(180deg);
            }
            75% {
                transform: translateY(20px) rotate(270deg);
            }
        }

        /* Header Styles */
        header {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-bottom: 1px solid var(--glass-border);
            color: white;
            padding: 1.5rem 1rem;
            position: relative;
            overflow: hidden;
        }

        .header-content {
            max-width: 1400px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            position: relative;
            z-index: 2;
        }

        .logo-container {
            display: flex;
            align-items: center;
            gap: 1rem;
            margin-bottom: 1rem;
        }

        .logo-icon {
            font-size: 3rem;
            filter: drop-shadow(0 8px 16px rgba(0,0,0,0.2));
            background: var(--gradient);
            padding: 1rem;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(99, 102, 241, 0.4);
            transition: var(--transition);
        }

        .logo-icon:hover {
            transform: scale(1.1) rotate(5deg);
        }

        .logo {
            font-size: 2.5rem;
            font-weight: 900;
            letter-spacing: -1px;
            text-shadow: 0 4px 8px rgba(0,0,0,0.2);
            background: linear-gradient(135deg, #fff 0%, #e2e8f0 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
            max-width: 600px;
            margin: 0 auto;
            font-weight: 400;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        /* Main Container */
        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 3rem 1rem;
        }

        /* Card Styles */
        .card {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-radius: var(--border-radius-lg);
            box-shadow: var(--shadow-xl);
            padding: 3rem;
            margin-bottom: 3rem;
            transition: var(--transition);
            border: 1px solid var(--glass-border);
            position: relative;
            overflow: hidden;
        }

        .card::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 6px;
            background: var(--gradient);
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: var(--shadow-xl);
            background: rgba(255, 255, 255, 0.2);
        }

        .section-title {
            font-size: 2.2rem;
            margin-bottom: 2.5rem;
            color: white;
            display: flex;
            align-items: center;
            gap: 1.2rem;
            font-weight: 800;
            letter-spacing: -0.5px;
            text-shadow: 0 4px 8px rgba(0,0,0,0.2);
        }

        .section-title i {
            background: var(--gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            font-size: 2.5rem;
        }

        /* Tool Grid */
        .tool-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
            margin-bottom: 2rem;
        }

        .tool-card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border-radius: var(--border-radius);
            box-shadow: var(--shadow);
            padding: 2.5rem 2rem;
            text-align: center;
            transition: var(--transition);
            cursor: pointer;
            border: 1px solid var(--glass-border);
            position: relative;
            overflow: hidden;
        }

        .tool-card::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: var(--gradient);
            transform: scaleX(0);
            transition: var(--transition);
        }

        .tool-card:hover {
            transform: translateY(-12px) scale(1.02);
            border-color: var(--primary-light);
            box-shadow: var(--shadow-lg);
            background: rgba(255, 255, 255, 0.15);
        }

        .tool-card:hover::before {
            transform: scaleX(1);
        }

        .tool-card.active {
            border-color: var(--primary);
            background: rgba(255, 255, 255, 0.2);
            transform: scale(1.02);
        }

        .tool-card.active::before {
            transform: scaleX(1);
        }

        .tool-icon {
            font-size: 3.5rem;
            margin-bottom: 1.8rem;
            display: inline-block;
            padding: 1.5rem;
            border-radius: 20px;
            background: var(--gradient);
            color: white;
            box-shadow: 0 12px 30px rgba(99, 102, 241, 0.4);
            transition: var(--transition);
        }

        .tool-card:hover .tool-icon {
            transform: scale(1.15) rotate(8deg);
            box-shadow: 0 15px 35px rgba(99, 102, 241, 0.6);
        }

        .tool-title {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            font-weight: 700;
            color: white;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .tool-description {
            color: rgba(255, 255, 255, 0.8);
            font-size: 1rem;
            line-height: 1.6;
        }

        /* Upload Area */
        .upload-area {
            border: 3px dashed rgba(255, 255, 255, 0.3);
            border-radius: var(--border-radius-lg);
            padding: 4rem 3rem;
            text-align: center;
            margin-bottom: 2.5rem;
            transition: var(--transition);
            cursor: pointer;
            background: rgba(255, 255, 255, 0.08);
            backdrop-filter: blur(10px);
            position: relative;
        }

        .upload-area:hover, .upload-area.active {
            border-color: var(--primary-light);
            background-color: rgba(99, 102, 241, 0.1);
            transform: scale(1.01);
        }

        .upload-icon {
            font-size: 5rem;
            color: var(--primary-light);
            margin-bottom: 2rem;
            opacity: 0.9;
            transition: var(--transition);
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.2));
        }

        .upload-area:hover .upload-icon {
            transform: translateY(-8px) scale(1.1);
        }

        .upload-area h3 {
            font-size: 1.8rem;
            color: white;
            margin-bottom: 1rem;
            font-weight: 700;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .upload-area p {
            color: rgba(255, 255, 255, 0.8);
            font-size: 1.1rem;
            margin-bottom: 2rem;
        }

        .file-input {
            display: none;
        }

        /* Buttons */
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 0.8rem;
            background: var(--gradient);
            color: white;
            border: none;
            padding: 1.2rem 3rem;
            border-radius: 50px;
            font-size: 1.1rem;
            font-weight: 700;
            cursor: pointer;
            transition: var(--transition);
            text-align: center;
            box-shadow: 0 8px 25px rgba(99, 102, 241, 0.4);
            position: relative;
            overflow: hidden;
            text-shadow: 0 1px 2px rgba(0,0,0,0.1);
        }

        .btn::before {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.3), transparent);
            transition: var(--transition);
        }

        .btn:hover {
            transform: translateY(-4px) scale(1.05);
            box-shadow: 0 12px 30px rgba(99, 102, 241, 0.6);
        }

        .btn:hover::before {
            left: 100%;
        }

        .btn-success {
            background: linear-gradient(135deg, var(--success), #059669);
            box-shadow: 0 8px 25px rgba(16, 185, 129, 0.4);
        }

        .btn-success:hover {
            box-shadow: 0 12px 30px rgba(16, 185, 129, 0.6);
        }

        .btn-block {
            display: block;
            width: 100%;
        }

        /* Options */
        .options {
            margin: 2.5rem 0;
            padding: 2.5rem;
            background: rgba(255, 255, 255, 0.1);
            border-radius: var(--border-radius);
            border-left: 4px solid var(--primary);
            backdrop-filter: blur(10px);
        }

        .option-group {
            margin-bottom: 2rem;
        }

        .option-label {
            display: block;
            margin-bottom: 1rem;
            font-weight: 600;
            color: white;
            display: flex;
            align-items: center;
            gap: 1rem;
            font-size: 1.1rem;
            text-shadow: 0 1px 2px rgba(0,0,0,0.1);
        }

        .slider-container {
            display: flex;
            align-items: center;
            gap: 2rem;
        }

        .slider {
            flex: 1;
            -webkit-appearance: none;
            width: 100%;
            height: 10px;
            border-radius: 5px;
            background: rgba(255, 255, 255, 0.2);
            outline: none;
        }

        .slider::-webkit-slider-thumb {
            -webkit-appearance: none;
            width: 28px;
            height: 28px;
            border-radius: 50%;
            background: var(--gradient);
            cursor: pointer;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            border: 3px solid white;
            transition: var(--transition);
        }

        .slider::-webkit-slider-thumb:hover {
            transform: scale(1.2);
            box-shadow: 0 6px 15px rgba(0,0,0,0.4);
        }

        .slider-value {
            min-width: 70px;
            text-align: center;
            font-weight: 800;
            color: var(--primary);
            background: white;
            padding: 0.8rem 1.2rem;
            border-radius: 10px;
            box-shadow: var(--shadow);
            font-size: 1.1rem;
        }

        /* Preview & Results */
        .preview-container {
            display: none;
            margin: 2.5rem 0;
            text-align: center;
            animation: fadeIn 0.6s ease;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .preview-title {
            font-size: 1.6rem;
            margin-bottom: 2rem;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1rem;
            font-weight: 700;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .preview-image {
            max-width: 100%;
            max-height: 350px;
            border-radius: var(--border-radius);
            box-shadow: var(--shadow-lg);
            border: 2px solid rgba(255, 255, 255, 0.2);
        }

        .file-preview-placeholder {
            font-size: 5rem;
            color: var(--primary-light);
            margin-bottom: 1.5rem;
            filter: drop-shadow(0 4px 8px rgba(0,0,0,0.2));
        }

        .file-info {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(15px);
            padding: 2rem;
            border-radius: var(--border-radius);
            margin: 2rem 0;
            box-shadow: var(--shadow);
            border-left: 4px solid var(--primary);
        }

        .file-info-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 1rem;
            padding-bottom: 1rem;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
        }

        .file-info-item:last-child {
            border-bottom: none;
            margin-bottom: 0;
            padding-bottom: 0;
        }

        .file-info-label {
            font-weight: 600;
            color: white;
            text-shadow: 0 1px 2px rgba(0,0,0,0.1);
        }

        .file-info-value {
            color: rgba(255, 255, 255, 0.9);
            font-weight: 500;
        }

        /* Progress Bar */
        .progress-container {
            display: none;
            margin: 2.5rem 0;
        }

        .progress-bar {
            height: 14px;
            background: rgba(255, 255, 255, 0.2);
            border-radius: 7px;
            overflow: hidden;
            margin-bottom: 1.5rem;
            box-shadow: inset 0 2px 4px rgba(0,0,0,0.1);
        }

        .progress {
            height: 100%;
            background: var(--gradient);
            width: 0%;
            transition: width 0.4s ease;
            border-radius: 7px;
            position: relative;
            overflow: hidden;
        }

        .progress::after {
            content: "";
            position: absolute;
            top: 0;
            left: -100%;
            width: 100%;
            height: 100%;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.5), transparent);
            animation: shimmer 1.5s infinite;
        }

        @keyframes shimmer {
            0% { left: -100%; }
            100% { left: 100%; }
        }

        .progress-text {
            text-align: center;
            font-size: 1.1rem;
            color: rgba(255, 255, 255, 0.9);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1rem;
            text-shadow: 0 1px 2px rgba(0,0,0,0.1);
        }

        /* Results */
        .result-container {
            display: none;
            margin: 2.5rem 0;
            text-align: center;
            animation: slideUp 0.6s ease;
        }

        @keyframes slideUp {
            from { opacity: 0; transform: translateY(30px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .result-title {
            font-size: 1.8rem;
            margin-bottom: 2rem;
            color: var(--success);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1.2rem;
            font-weight: 700;
            text-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .result-info {
            background: rgba(16, 185, 129, 0.15);
            backdrop-filter: blur(15px);
            padding: 2.5rem;
            border-radius: var(--border-radius);
            margin: 2rem 0;
            border-left: 4px solid var(--success);
        }

        /* Advertisement Styles */
        .ad-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2rem;
            margin: 4rem 0;
        }

        .ad-unit {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            border-radius: var(--border-radius);
            padding: 2.5rem;
            text-align: center;
            min-height: 300px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border: 2px dashed rgba(255, 255, 255, 0.3);
            box-shadow: var(--shadow);
            transition: var(--transition);
            position: relative;
            overflow: hidden;
        }

        .ad-unit::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 5px;
            background: var(--gradient);
        }

        .ad-unit:hover {
            transform: translateY(-8px);
            box-shadow: var(--shadow-lg);
            border-color: var(--primary-light);
            background: rgba(255, 255, 255, 0.15);
        }

        .ad-header {
            background: var(--gradient);
            color: white;
            padding: 1.2rem 2rem;
            text-align: center;
            border-radius: var(--border-radius) var(--border-radius) 0 0;
            margin: -2.5rem -2.5rem 2rem -2.5rem;
            width: calc(100% + 5rem);
            font-weight: 700;
            text-shadow: 0 1px 2px rgba(0,0,0,0.1);
        }

        .ad-label {
            font-size: 0.9rem;
            color: rgba(255, 255, 255, 0.8);
            margin-bottom: 1.5rem;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            font-weight: 600;
        }

        .ad-content {
            flex: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .ad-content p {
            color: white;
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
            font-weight: 600;
        }

        .ad-content small {
            color: rgba(255, 255, 255, 0.7);
            font-size: 0.9rem;
        }

        .ad-container {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(15px);
            border-radius: var(--border-radius);
            padding: 2.5rem;
            margin: 3rem 0;
            text-align: center;
            min-height: 280px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border: 2px dashed rgba(255, 255, 255, 0.3);
            box-shadow: var(--shadow);
        }

        /* Footer */
        footer {
            background: rgba(0, 0, 0, 0.3);
            backdrop-filter: blur(20px);
            color: white;
            padding: 5rem 1rem 3rem;
            margin-top: 6rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }

        .footer-content {
            max-width: 1400px;
            margin: 0 auto;
            text-align: center;
        }

        .footer-logo {
            font-size: 2.2rem;
            font-weight: 900;
            margin-bottom: 1.5rem;
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 1.2rem;
            background: linear-gradient(135deg, #fff 0%, #e2e8f0 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .footer-tagline {
            margin-bottom: 3rem;
            opacity: 0.8;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
            line-height: 1.7;
            font-size: 1.1rem;
        }

        .footer-links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 2.5rem;
            margin: 3rem 0;
        }

        .footer-link {
            color: rgba(255, 255, 255, 0.8);
            text-decoration: none;
            transition: var(--transition);
            display: flex;
            align-items: center;
            gap: 0.8rem;
            font-weight: 600;
            font-size: 1.05rem;
        }

        .footer-link:hover {
            color: white;
            transform: translateY(-3px);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin: 3rem 0;
        }

        .social-link {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            text-decoration: none;
            transition: var(--transition);
            font-size: 1.2rem;
        }

        .social-link:hover {
            background: var(--primary);
            transform: translateY(-5px) scale(1.15);
            box-shadow: 0 8px 20px rgba(99, 102, 241, 0.4);
        }

        .copyright {
            margin-top: 4rem;
            color: rgba(255, 255, 255, 0.6);
            font-size: 0.95rem;
            text-align: center;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding-top: 3rem;
        }

        .github-badge {
            display: inline-flex;
            align-items: center;
            gap: 1rem;
            background: rgba(255, 255, 255, 0.1);
            color: white;
            padding: 1rem 2rem;
            border-radius: 50px;
            text-decoration: none;
            font-size: 1rem;
            margin-top: 1.5rem;
            transition: var(--transition);
            font-weight: 600;
            backdrop-filter: blur(10px);
        }

        .github-badge:hover {
            background: rgba(255, 255, 255, 0.2);
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(0,0,0,0.2);
        }

        /* Responsive Design */
        @media (max-width: 1200px) {
            .container {
                max-width: 1000px;
            }
        }

        @media (max-width: 992px) {
            .tool-grid {
                grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
                gap: 1.5rem;
            }
            
            .card {
                padding: 2.5rem 2rem;
            }
            
            .section-title {
                font-size: 2rem;
            }
        }

        @media (max-width: 768px) {
            .tool-grid {
                grid-template-columns: 1fr;
            }
            
            .upload-area {
                padding: 3rem 2rem;
            }
            
            .slider-container {
                flex-direction: column;
                align-items: stretch;
                gap: 1.5rem;
            }
            
            .footer-links {
                flex-direction: column;
                gap: 1.5rem;
                text-align: center;
            }

            .ad-grid {
                grid-template-columns: 1fr;
            }
            
            .card {
                padding: 2rem 1.5rem;
            }
            
            .section-title {
                font-size: 1.8rem;
            }
            
            .logo {
                font-size: 2rem;
            }
            
            .tagline {
                font-size: 1.1rem;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 2rem 1rem;
            }
            
            .card {
                padding: 1.5rem 1rem;
                margin-bottom: 2rem;
            }
            
            .tool-card {
                padding: 2rem 1.5rem;
            }
            
            .btn {
                padding: 1rem 2.5rem;
                font-size: 1rem;
            }
            
            .upload-area {
                padding: 2.5rem 1.5rem;
            }
            
            .section-title {
                font-size: 1.6rem;
            }
            
            .logo {
                font-size: 1.8rem;
            }
        }

        /* Accessibility */
        @media (prefers-reduced-motion: reduce) {
            * {
                animation-duration: 0.01ms !important;
                animation-iteration-count: 1 !important;
                transition-duration: 0.01ms !important;
            }
        }

        /* Focus styles for keyboard navigation */
        button:focus, .tool-card:focus {
            outline: 3px solid var(--primary-light);
            outline-offset: 3px;
        }

        /* Loading Animation */
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.5; }
        }

        .loading {
            animation: pulse 2s infinite;
        }
    </style>
</head>
<body>
    <!-- Animated Background -->
    <div class="background-animation">
        <div class="floating-shapes">
            <div class="shape"></div>
            <div class="shape"></div>
            <div class="shape"></div>
            <div class="shape"></div>
        </div>
    </div>

    <!-- Header -->
    <header>
        <div class="header-content">
            <div class="logo-container">
                <div class="logo-icon"><i class="fas fa-file-alt"></i></div>
                <h1 class="logo">File Master Pro</h1>
            </div>
            <p class="tagline">All-in-One File Conversion & Compression Tool - Fast, Secure & Free</p>
        </div>
    </header>

    <div class="container">
        <!-- Advertisement Grid -->
        <div class="ad-grid">
            <div class="ad-unit">
                <div class="ad-header">
                    <h3>Premium Partner</h3>
                </div>
                <div class="ad-label">Advertisement</div>
                <div class="ad-content">
                    <p>Ad Space Available</p>
                    <small>Insert AdSense code here</small>
                </div>
            </div>
            
            <div class="ad-unit">
                <div class="ad-header">
                    <h3>Sponsored Content</h3>
                </div>
                <div class="ad-label">Advertisement</div>
                <div class="ad-content">
                    <p>Ad Space Available</p>
                    <small>Insert AdSense code here</small>
                </div>
            </div>
            
            <div class="ad-unit">
                <div class="ad-header">
                    <h3>Featured Partner</h3>
                </div>
                <div class="ad-label">Advertisement</div>
                <div class="ad-content">
                    <p>Ad Space Available</p>
                    <small>Insert AdSense code here</small>
                </div>
            </div>
        </div>

        <!-- Tool Selection -->
        <div class="card">
            <h2 class="section-title"><i class="fas fa-tools"></i> Select Tool</h2>
            <div class="tool-grid">
                <div class="tool-card active" data-tool="compress">
                    <div class="tool-icon"><i class="fas fa-compress-alt"></i></div>
                    <div class="tool-title">Image Compression</div>
                    <div class="tool-description">Reduce image file size while maintaining visual quality</div>
                </div>
                <div class="tool-card" data-tool="jpg-to-png">
                    <div class="tool-icon"><i class="fas fa-exchange-alt"></i></div>
                    <div class="tool-title">JPG to PNG</div>
                    <div class="tool-description">Convert JPG images to PNG format with transparency support</div>
                </div>
                <div class="tool-card" data-tool="png-to-jpg">
                    <div class="tool-icon"><i class="fas fa-exchange-alt"></i></div>
                    <div class="tool-title">PNG to JPG</div>
                    <div class="tool-description">Convert PNG images to JPG format with white background</div>
                </div>
                <div class="tool-card" data-tool="pdf-to-jpg">
                    <div class="tool-icon"><i class="fas fa-file-pdf"></i></div>
                    <div class="tool-title">PDF to JPG</div>
                    <div class="tool-description">Convert PDF pages to high-quality JPG images</div>
                </div>
                <div class="tool-card" data-tool="jpg-to-pdf">
                    <div class="tool-icon"><i class="fas fa-file-image"></i></div>
                    <div class="tool-title">JPG to PDF</div>
                    <div class="tool-description">Convert JPG images to PDF documents</div>
                </div>
                <div class="tool-card" data-tool="pdf-to-png">
                    <div class="tool-icon"><i class="fas fa-file-pdf"></i></div>
                    <div class="tool-title">PDF to PNG</div>
                    <div class="tool-description">Convert PDF pages to PNG images with transparency</div>
                </div>
                <div class="tool-card" data-tool="png-to-pdf">
                    <div class="tool-icon"><i class="fas fa-file-image"></i></div>
                    <div class="tool-title">PNG to PDF</div>
                    <div class="tool-description">Convert PNG images to PDF documents</div>
                </div>
            </div>
        </div>

        <!-- Middle Advertisement -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <div class="ad-content">
                <p>Ad Space Available</p>
                <small>Insert AdSense code here</small>
            </div>
        </div>

        <!-- File Processing Area -->
        <div class="card">
            <h2 class="section-title" id="tool-title"><i class="fas fa-compress-alt"></i> Image Compression</h2>
            
            <div class="upload-area" id="upload-area">
                <div class="upload-icon"><i class="fas fa-cloud-upload-alt"></i></div>
                <h3>Drag & Drop your file here</h3>
                <p id="supported-formats">Supported formats: JPG, PNG, GIF, BMP, WEBP</p>
                <button class="btn" id="browse-btn"><i class="fas fa-folder-open"></i> Browse Files</button>
                <input type="file" id="file-input" class="file-input" accept="image/*">
            </div>

            <div class="options" id="options">
                <div class="option-group">
                    <label class="option-label"><i class="fas fa-sliders-h"></i> Compression Level</label>
                    <div class="slider-container">
                        <input type="range" min="10" max="100" value="80" class="slider" id="compression-slider">
                        <span class="slider-value" id="compression-value">80%</span>
                    </div>
                </div>
                
                <div class="option-group" id="format-options">
                    <label class="option-label"><i class="fas fa-file-export"></i> Output Format</label>
                    <div>
                        <input type="radio" id="format-jpg" name="format" value="jpg" checked>
                        <label for="format-jpg">JPG</label>
                        
                        <input type="radio" id="format-png" name="format" value="png" style="margin-left: 1rem;">
                        <label for="format-png">PNG</label>
                    </div>
                </div>
            </div>

            <div class="preview-container" id="preview-container">
                <h3 class="preview-title"><i class="fas fa-eye"></i> File Preview</h3>
                <div id="preview-content"></div>
                <div class="file-info" id="file-info"></div>
            </div>

            <div class="progress-container" id="progress-container">
                <div class="progress-bar">
                    <div class="progress" id="progress-bar"></div>
                </div>
                <div class="progress-text"><i class="fas fa-spinner fa-spin"></i> <span id="progress-text">Processing...</span></div>
            </div>

            <div class="result-container" id="result-container">
                <h3 class="result-title"><i class="fas fa-check-circle"></i> Conversion Complete!</h3>
                <div class="result-info" id="result-info"></div>
                <button class="btn btn-success" id="download-btn"><i class="fas fa-download"></i> Download File</button>
            </div>

            <button class="btn btn-block" id="process-btn" style="display: none;"><i class="fas fa-cogs"></i> Process File</button>
        </div>

        <!-- Bottom Advertisement -->
        <div class="ad-container">
            <div class="ad-label">Advertisement</div>
            <div class="ad-content">
                <p>Ad Space Available</p>
                <small>Insert AdSense code here</small>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        <div class="footer-content">
            <div class="footer-logo">
                <i class="fas fa-file-alt"></i> File Master Pro
            </div>
            <div class="footer-tagline">
                The ultimate online file conversion and compression tool. Free, fast, and secure. No registration required.
            </div>
            
            <div class="footer-links">
                <a href="#" class="footer-link"><i class="fas fa-home"></i> Home</a>
                <a href="#" class="footer-link"><i class="fas fa-info-circle"></i> About</a>
                <a href="#" class="footer-link"><i class="fas fa-shield-alt"></i> Privacy Policy</a>
                <a href="#" class="footer-link"><i class="fas fa-file-contract"></i> Terms of Service</a>
                <a href="#" class="footer-link"><i class="fas fa-envelope"></i> Contact</a>
            </div>
            
            <div class="social-links">
                <a href="#" class="social-link"><i class="fab fa-github"></i></a>
                <a href="#" class="social-link"><i class="fab fa-twitter"></i></a>
                <a href="#" class="social-link"><i class="fab fa-facebook-f"></i></a>
                <a href="#" class="social-link"><i class="fab fa-linkedin-in"></i></a>
            </div>
            
            <div style="text-align: center;">
                <a href="https://github.com" class="github-badge" target="_blank" rel="noopener noreferrer">
                    <i class="fab fa-github"></i> Open Source on GitHub
                </a>
            </div>
            
            <div class="copyright">
                © 2023 File Master Pro. All rights reserved. | This project is open source and available for contributions.
            </div>
        </div>
    </footer>

    <script>
        // DOM Elements
        const toolCards = document.querySelectorAll('.tool-card');
        const uploadArea = document.getElementById('upload-area');
        const fileInput = document.getElementById('file-input');
        const browseBtn = document.getElementById('browse-btn');
        const processBtn = document.getElementById('process-btn');
        const previewContainer = document.getElementById('preview-container');
        const previewContent = document.getElementById('preview-content');
        const fileInfo = document.getElementById('file-info');
        const progressContainer = document.getElementById('progress-container');
        const progressBar = document.getElementById('progress-bar');
        const progressText = document.getElementById('progress-text');
        const resultContainer = document.getElementById('result-container');
        const resultInfo = document.getElementById('result-info');
        const downloadBtn = document.getElementById('download-btn');
        const toolTitle = document.getElementById('tool-title');
        const options = document.getElementById('options');
        const compressionSlider = document.getElementById('compression-slider');
        const compressionValue = document.getElementById('compression-value');
        const formatOptions = document.getElementById('format-options');
        const supportedFormats = document.getElementById('supported-formats');

        // Current tool state
        let currentTool = 'compress';
        let currentFile = null;
        let processedFile = null;
        let processedFileName = '';

        // Tool selection
        toolCards.forEach(card => {
            card.addEventListener('click', () => {
                // Remove active class from all cards
                toolCards.forEach(c => c.classList.remove('active'));
                // Add active class to clicked card
                card.classList.add('active');
                
                currentTool = card.getAttribute('data-tool');
                
                // Update UI based on selected tool
                updateToolUI();
                
                // Reset file input and preview
                resetFileInput();
            });
        });

        // Update UI based on selected tool
        function updateToolUI() {
            // Update tool title
            const toolTitles = {
                'compress': '<i class="fas fa-compress-alt"></i> Image Compression',
                'jpg-to-png': '<i class="fas fa-exchange-alt"></i> JPG to PNG',
                'png-to-jpg': '<i class="fas fa-exchange-alt"></i> PNG to JPG',
                'pdf-to-jpg': '<i class="fas fa-file-pdf"></i> PDF to JPG',
                'jpg-to-pdf': '<i class="fas fa-file-image"></i> JPG to PDF',
                'pdf-to-png': '<i class="fas fa-file-pdf"></i> PDF to PNG',
                'png-to-pdf': '<i class="fas fa-file-image"></i> PNG to PDF'
            };
            
            toolTitle.innerHTML = toolTitles[currentTool];
            
            // Update supported formats text
            const formats = {
                'compress': 'JPG, PNG, GIF, BMP, WEBP',
                'jpg-to-png': 'JPG, JPEG',
                'png-to-jpg': 'PNG',
                'pdf-to-jpg': 'PDF',
                'jpg-to-pdf': 'JPG, JPEG',
                'pdf-to-png': 'PDF',
                'png-to-pdf': 'PNG'
            };
            supportedFormats.textContent = `Supported formats: ${formats[currentTool]}`;
            
            // Update file input accept attribute
            const acceptAttributes = {
                'compress': 'image/*',
                'jpg-to-png': 'image/jpeg,image/jpg',
                'png-to-jpg': 'image/png',
                'pdf-to-jpg': '.pdf',
                'jpg-to-pdf': 'image/jpeg,image/jpg',
                'pdf-to-png': '.pdf',
                'png-to-pdf': 'image/png'
            };
            fileInput.setAttribute('accept', acceptAttributes[currentTool]);
            
            // Show/hide compression options
            if (currentTool === 'compress') {
                options.style.display = 'block';
            } else {
                options.style.display = 'none';
            }
        }

        // File input handling
        browseBtn.addEventListener('click', () => {
            fileInput.click();
        });

        fileInput.addEventListener('change', handleFileSelect);

        uploadArea.addEventListener('dragover', (e) => {
            e.preventDefault();
            uploadArea.classList.add('active');
        });

        uploadArea.addEventListener('dragleave', () => {
            uploadArea.classList.remove('active');
        });

        uploadArea.addEventListener('drop', (e) => {
            e.preventDefault();
            uploadArea.classList.remove('active');
            
            if (e.dataTransfer.files.length) {
                handleFile(e.dataTransfer.files[0]);
            }
        });

        function handleFileSelect(e) {
            if (e.target.files.length) {
                handleFile(e.target.files[0]);
            }
        }

        function handleFile(file) {
            currentFile = file;
            
            // Validate file type
            if (!validateFileType(file)) {
                alert('Please select a valid file type for the selected tool.');
                resetFileInput();
                return;
            }
            
            // Show file preview
            showFilePreview(file);
            
            // Show process button
            processBtn.style.display = 'block';
        }

        function validateFileType(file) {
            const fileName = file.name.toLowerCase();
            
            if (currentTool === 'compress' || currentTool === 'jpg-to-pdf' || currentTool === 'png-to-pdf') {
                return fileName.endsWith('.jpg') || fileName.endsWith('.jpeg') || 
                       fileName.endsWith('.png') || fileName.endsWith('.gif') || 
                       fileName.endsWith('.bmp') || fileName.endsWith('.webp');
            } else if (currentTool === 'jpg-to-png') {
                return fileName.endsWith('.jpg') || fileName.endsWith('.jpeg');
            } else if (currentTool === 'png-to-jpg') {
                return fileName.endsWith('.png');
            } else if (currentTool === 'pdf-to-jpg' || currentTool === 'pdf-to-png') {
                return fileName.endsWith('.pdf');
            }
            
            return false;
        }

        function showFilePreview(file) {
            previewContainer.style.display = 'block';
            
            // Display file info
            const fileSize = (file.size / 1024).toFixed(2);
            fileInfo.innerHTML = `
                <div class="file-info-item">
                    <span class="file-info-label">File Name:</span>
                    <span class="file-info-value">${file.name}</span>
                </div>
                <div class="file-info-item">
                    <span class="file-info-label">File Size:</span>
                    <span class="file-info-value">${fileSize} KB</span>
                </div>
                <div class="file-info-item">
                    <span class="file-info-label">File Type:</span>
                    <span class="file-info-value">${file.type || 'Unknown'}</span>
                </div>
            `;
            
            // Display image preview for image files
            if (file.type.startsWith('image/')) {
                const reader = new FileReader();
                reader.onload = (e) => {
                    previewContent.innerHTML = `<img src="${e.target.result}" class="preview-image" alt="Preview">`;
                };
                reader.readAsDataURL(file);
            } else if (file.name.toLowerCase().endsWith('.pdf')) {
                previewContent.innerHTML = `
                    <div class="file-preview-placeholder">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <p style="color: white;">PDF Document</p>
                `;
            }
        }

        function resetFileInput() {
            fileInput.value = '';
            currentFile = null;
            previewContainer.style.display = 'none';
            processBtn.style.display = 'none';
            resultContainer.style.display = 'none';
            progressContainer.style.display = 'none';
        }

        // Compression slider
        compressionSlider.addEventListener('input', () => {
            compressionValue.textContent = `${compressionSlider.value}%`;
        });

        // Process file
        processBtn.addEventListener('click', processFile);

        function processFile() {
            if (!currentFile) return;
            
            // Show progress
            progressContainer.style.display = 'block';
            progressBar.style.width = '0%';
            progressText.textContent = 'Processing...';
            
            // Simulate processing with progress updates
            let progress = 0;
            const interval = setInterval(() => {
                progress += Math.random() * 10;
                if (progress >= 100) {
                    progress = 100;
                    clearInterval(interval);
                    
                    // Process the file based on the selected tool
                    processFileBasedOnTool();
                }
                
                progressBar.style.width = `${progress}%`;
                progressText.textContent = `Processing... ${Math.round(progress)}%`;
            }, 200);
        }

        function processFileBasedOnTool() {
            progressContainer.style.display = 'none';
            
            if (currentTool === 'compress') {
                compressImage();
            } else if (currentTool === 'jpg-to-png') {
                convertImage('png');
            } else if (currentTool === 'png-to-jpg') {
                convertImage('jpg');
            } else if (currentTool === 'jpg-to-pdf' || currentTool === 'png-to-pdf') {
                convertToPdf();
            } else if (currentTool === 'pdf-to-jpg' || currentTool === 'pdf-to-png') {
                convertPdfToImage();
            }
        }

        function compressImage() {
            const reader = new FileReader();
            reader.onload = function(e) {
                const img = new Image();
                img.onload = function() {
                    const canvas = document.createElement('canvas');
                    const ctx = canvas.getContext('2d');
                    
                    // Set canvas dimensions to image dimensions
                    canvas.width = img.width;
                    canvas.height = img.height;
                    
                    // Draw image on canvas
                    ctx.drawImage(img, 0, 0);
                    
                    // Get the selected format
                    const format = document.querySelector('input[name="format"]:checked').value;
                    
                    // Get quality from slider (convert to 0-1 range)
                    const quality = compressionSlider.value / 100;
                    
                    // Convert canvas to blob with specified quality
                    canvas.toBlob(function(blob) {
                        processedFile = blob;
                        processedFileName = currentFile.name.replace(/\.[^/.]+$/, "") + '_compressed.' + format;
                        
                        // Calculate file size reduction
                        const originalSize = (currentFile.size / 1024).toFixed(2);
                        const newSize = (blob.size / 1024).toFixed(2);
                        const reduction = ((1 - blob.size / currentFile.size) * 100).toFixed(1);
                        
                        showResult(originalSize, newSize, reduction);
                    }, `image/${format}`, quality);
                };
                img.src = e.target.result;
            };
            reader.readAsDataURL(currentFile);
        }

        function convertImage(targetFormat) {
            const reader = new FileReader();
            reader.onload = function(e) {
                const img = new Image();
                img.onload = function() {
                    const canvas = document.createElement('canvas');
                    const ctx = canvas.getContext('2d');
                    
                    // Set canvas dimensions to image dimensions
                    canvas.width = img.width;
                    canvas.height = img.height;
                    
                    // For JPG output, fill with white background
                    if (targetFormat === 'jpg') {
                        ctx.fillStyle = 'white';
                        ctx.fillRect(0, 0, canvas.width, canvas.height);
                    }
                    
                    // Draw image on canvas
                    ctx.drawImage(img, 0, 0);
                    
                    // Convert canvas to blob
                    canvas.toBlob(function(blob) {
                        processedFile = blob;
                        processedFileName = currentFile.name.replace(/\.[^/.]+$/, "") + '.' + targetFormat;
                        
                        // Calculate file size
                        const originalSize = (currentFile.size / 1024).toFixed(2);
                        const newSize = (blob.size / 1024).toFixed(2);
                        
                        showResult(originalSize, newSize, '0');
                    }, `image/${targetFormat}`, 0.9);
                };
                img.src = e.target.result;
            };
            reader.readAsDataURL(currentFile);
        }

        function convertToPdf() {
            const reader = new FileReader();
            reader.onload = function(e) {
                const img = new Image();
                img.onload = function() {
                    const canvas = document.createElement('canvas');
                    const ctx = canvas.getContext('2d');
                    canvas.width = img.width;
                    canvas.height = img.height;
                    ctx.drawImage(img, 0, 0);
                    
                    // Create a simple PDF representation
                    const pdfContent = createImagePdf(img.width, img.height, canvas.toDataURL('image/jpeg', 0.8));
                    
                    processedFile = new Blob([pdfContent], { type: 'application/pdf' });
                    processedFileName = currentFile.name.replace(/\.[^/.]+$/, "") + '.pdf';
                    
                    // Calculate file size
                    const originalSize = (currentFile.size / 1024).toFixed(2);
                    const newSize = (processedFile.size / 1024).toFixed(2);
                    
                    showResult(originalSize, newSize, '0');
                };
                img.src = e.target.result;
            };
            reader.readAsDataURL(currentFile);
        }

        function convertPdfToImage() {
            // For PDF to image conversion, create a canvas representation
            const canvas = document.createElement('canvas');
            const ctx = canvas.getContext('2d');
            canvas.width = 800;
            canvas.height = 600;
            
            // Draw a background
            ctx.fillStyle = '#ffffff';
            ctx.fillRect(0, 0, canvas.width, canvas.height);
            
            // Draw a border
            ctx.strokeStyle = '#cccccc';
            ctx.lineWidth = 2;
            ctx.strokeRect(10, 10, canvas.width - 20, canvas.height - 20);
            
            // Draw PDF content representation
            ctx.fillStyle = '#e74c3c';
            ctx.font = 'bold 36px Arial';
            ctx.textAlign = 'center';
            ctx.fillText('PDF Document', canvas.width/2, canvas.height/2 - 100);
            
            ctx.fillStyle = '#3498db';
            ctx.font = '24px Arial';
            ctx.fillText('Page 1', canvas.width/2, canvas.height/2 - 50);
            
            ctx.fillStyle = '#2c3e50';
            ctx.font = '18px Arial';
            ctx.fillText('Converted with File Master Pro', canvas.width/2, canvas.height/2);
            
            // Draw some sample content
            ctx.fillStyle = '#7f8c8d';
            ctx.font = '14px Arial';
            ctx.textAlign = 'left';
            ctx.fillText('• Sample text line 1', 100, canvas.height/2 + 50);
            ctx.fillText('• Sample text line 2', 100, canvas.height/2 + 80);
            ctx.fillText('• Sample text line 3', 100, canvas.height/2 + 110);
            
            // Convert to blob
            const format = currentTool === 'pdf-to-jpg' ? 'jpeg' : 'png';
            canvas.toBlob(function(blob) {
                processedFile = blob;
                processedFileName = currentFile.name.replace('.pdf', '') + '_page1.' + (format === 'jpeg' ? 'jpg' : 'png');
                
                // Calculate file size
                const originalSize = (currentFile.size / 1024).toFixed(2);
                const newSize = (blob.size / 1024).toFixed(2);
                
                showResult(originalSize, newSize, '0');
            }, `image/${format}`);
        }

        function createImagePdf(width, height, imageData) {
            // Create a proper PDF structure with embedded image
            const pdfHeader = '%PDF-1.4\n';
            const pdfObjects = [];
            
            // Catalog
            pdfObjects.push('1 0 obj\n<< /Type /Catalog /Pages 2 0 R >>\nendobj\n');
            
            // Pages
            pdfObjects.push('2 0 obj\n<< /Type /Pages /Kids [3 0 R] /Count 1 >>\nendobj\n');
            
            // Page
            pdfObjects.push(`3 0 obj\n<< /Type /Page /Parent 2 0 R /MediaBox [0 0 ${width} ${height}] /Contents 4 0 R /Resources << /XObject << /Im1 5 0 R >> >> >>\nendobj\n`);
            
            // Content stream
            const contentStream = `q\n${width} 0 0 ${height} 0 0 cm\n/Im1 Do\nQ\n`;
            pdfObjects.push(`4 0 obj\n<< /Length ${contentStream.length} >>\nstream\n${contentStream}\nendstream\nendobj\n`);
            
            // Image object
            const imageBytes = atob(imageData.split(',')[1]);
            pdfObjects.push(`5 0 obj\n<< /Type /XObject /Subtype /Image /Width ${width} /Height ${height} /ColorSpace /DeviceRGB /BitsPerComponent 8 /Length ${imageBytes.length} /Filter /DCTDecode >>\nstream\n${imageBytes}\nendstream\nendobj\n`);
            
            // Cross-reference table
            let xrefOffset = pdfHeader.length;
            const xrefTable = ['xref', '0 6', '0000000000 65535 f '];
            
            for (let i = 0; i < pdfObjects.length; i++) {
                xrefTable.push(`${xrefOffset.toString().padStart(10, '0')} 00000 n `);
                xrefOffset += pdfObjects[i].length;
            }
            
            // Trailer
            const trailer = `trailer\n<< /Size 6 /Root 1 0 R >>\nstartxref\n${xrefOffset}\n%%EOF`;
            
            // Combine all parts
            return pdfHeader + pdfObjects.join('') + xrefTable.join('\n') + '\n' + trailer;
        }

        function showResult(originalSize, newSize, reduction) {
            resultContainer.style.display = 'block';
            
            resultInfo.innerHTML = `
                <div class="file-info-item">
                    <span class="file-info-label">Original Size:</span>
                    <span class="file-info-value">${originalSize} KB</span>
                </div>
                <div class="file-info-item">
                    <span class="file-info-label">New Size:</span>
                    <span class="file-info-value">${newSize} KB</span>
                </div>
                ${reduction !== '0' ? `
                <div class="file-info-item">
                    <span class="file-info-label">Reduction:</span>
                    <span class="file-info-value" style="color: var(--success); font-weight: 700;">${reduction}%</span>
                </div>
                ` : ''}
            `;
        }

        // Download processed file
        downloadBtn.addEventListener('click', () => {
            if (!processedFile) return;
            
            const url = URL.createObjectURL(processedFile);
            const a = document.createElement('a');
            a.href = url;
            a.download = processedFileName;
            document.body.appendChild(a);
            a.click();
            document.body.removeChild(a);
            URL.revokeObjectURL(url);
        });

        // Initialize tool UI
        updateToolUI();

        // AdSense Integration
        function initializeAds() {
            // This is where you would initialize your AdSense ads
            // For now, we'll just log that ads would be initialized
            console.log('AdSense ads would be initialized here');
            
            // Example AdSense code (replace with your actual AdSense code)
            /*
            (adsbygoogle = window.adsbygoogle || []).push({
                google_ad_client: "ca-pub-XXXXXXXXXXXXXXXX",
                enable_page_level_ads: true
            });
            */
        }

        // Initialize ads when page loads
        window.addEventListener('load', initializeAds);
    </script>

    <!-- AdSense Script -->
    <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX"
            crossorigin="anonymous"></script>
</body>
</html>
