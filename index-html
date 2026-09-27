```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English for Libya - Unit 1 Lesson 2 (Workbook Page 5)</title>
    <!-- Google Fonts & Font Awesome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&family=Cairo:wght@600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        :root {
            --wb-grey-dark: #3a3f47;
            --wb-grey-mid: #5a626e;
            --wb-grey-light: #e8ecef;
            --wb-bg: #f2f4f7;
            --wb-paper: #ffffff;
            --wb-accent: #2563eb;
            --wb-success: #16a34a;
            --text-dark: #1e293b;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Roboto', 'Cairo', sans-serif;
        }

        body {
            background-color: #1e293b;
            color: var(--text-dark);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
        }

        /* Top Toolbar Controls */
        .top-nav {
            width: 100%;
            max-width: 1000px;
            background: #0f172a;
            color: white;
            padding: 12px 20px;
            border-radius: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 15px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.3);
            flex-wrap: wrap;
            gap: 10px;
        }

        .nav-title {
            font-size: 16px;
            font-weight: 700;
            color: #38bdf8;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .mode-switch {
            display: flex;
            gap: 8px;
        }

        .nav-btn {
            background: #334155;
            color: white;
            border: none;
            padding: 8px 14px;
            border-radius: 8px;
            cursor: pointer;
            font-weight: 600;
            font-size: 13px;
            transition: all 0.2s ease;
            display: flex;
            align-items: center;
            gap: 6px;
        }

        .nav-btn:hover, .nav-btn.active {
            background: #0284c7;
            color: white;
        }

        /* Presentation Container (Page Layout / Slide Layout) */
        .page-container {
            width: 100%;
            max-width: 1000px;
            background: var(--wb-paper);
            border-radius: 12px;
            padding: 35px 45px;
            box-shadow: 0 15px 35px rgba(0,0,0,0.4);
            position: relative;
            min-height: 800px;
            display: none;
            animation: fadeIn 0.3s ease-in-out;
        }

        .page-container.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Original Workbook Section Headers */
        .wb-header-banner {
            background: var(--wb-grey-dark);
            color: white;
            padding: 10px 18px;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 700;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .wb-header-banner .letter-badge {
            background: white;
            color: var(--wb-grey-dark);
            width: 26px;
            height: 26px;
            border-radius: 4px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-weight: 900;
        }

        /* Writing Box (Exercise D Area) */
        .writing-tip-box {
            background: #f8fafc;
            border: 2px solid var(--wb-grey-light);
            border-radius: 10px;
            padding: 15px 20px;
            margin-bottom: 25px;
        }

        .writing-tip-box h4 {
            color: var(--wb-grey-dark);
            font-size: 15px;
            margin-bottom: 8px;
        }

        .tip-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px;
            font-size: 14px;
            color: #475569;
        }

        .tip-item {
            background: white;
            padding: 6px 12px;
            border-radius: 6px;
            border: 1px solid #e2e8f0;
        }

        /* Lesson Title */
        .lesson-title-main {
            font-size: 28px;
            font-weight: 900;
            color: var(--text-dark);
            margin: 20px 0 15px 0;
            border-bottom: 2px solid #cbd5e1;
            padding-bottom: 8px;
        }

        /* Exercises List Item (Authentic Workbook Layout) */
        .exercise-block {
            margin-bottom: 30px;
        }

        .wb-exercise-title {
            background: var(--wb-grey-mid);
            color: white;
            padding: 8px 15px;
            border-radius: 6px;
            font-weight: 700;
            font-size: 15px;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .exercise-item {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px dashed #e2e8f0;
            font-size: 16px;
            font-weight: 600;
        }

        .item-label {
            display: flex;
            align-items: center;
            gap: 12px;
            color: #334155;
            flex: 1;
        }

        .item-num {
            font-weight: 800;
            color: var(--wb-grey-dark);
            width: 20px;
        }

        /* Interactive Blank Fill */
        .blank-field {
            min-width: 280px;
            background: #f1f5f9;
            border: 2px dashed #94a3b8;
            border-radius: 8px;
            padding: 6px 14px;
            display: inline-flex;
            align-items: center;
            justify-content: space-between;
            cursor: pointer;
            transition: all 0.2s ease;
        }

        .blank-field:hover {
            border-color: var(--wb-accent);
            background: #eff6ff;
        }

        .blank-field.revealed {
            border-style: solid;
            border-color: var(--wb-success);
            background: #f0fdf4;
            animation: popIn 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .blank-answer {
            font-weight: 800;
            font-size: 16px;
            color: #15803d;
            display: none;
        }

        .blank-field.revealed .blank-answer {
            display: inline;
        }

        .reveal-btn-mini {
            background: var(--wb-grey-dark);
            color: white;
            border: none;
            padding: 4px 10px;
            border-radius: 5px;
            font-size: 12px;
            font-weight: 700;
            cursor: pointer;
            transition: all 0.2s;
        }

        .blank-field.revealed .reveal-btn-mini {
            background: #cbd5e1;
            color: #64748b;
        }

        /* Image Tooltip / Visual Icon Button */
        .img-trigger-btn {
            background: #e0f2fe;
            color: #0369a1;
            border: 1px solid #bae6fd;
            border-radius: 50%;
            width: 32px;
            height: 32px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            margin-left: 8px;
            transition: all 0.2s;
        }

        .img-trigger-btn:hover {
            background: #0284c7;
            color: white;
            transform: scale(1.1);
        }

        /* Infographic Slide Cards (Mode 2) */
        .cards-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 15px;
        }

        .info-card {
            background: #ffffff;
            border: 2px solid #e2e8f0;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 4px 6px -1px rgba(0,0,0,0.05);
            transition: all 0.3s ease;
            display: flex;
            flex-direction: column;
        }

        .info-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.1);
            border-color: #38bdf8;
        }

        .card-img-container {
            height: 160px;
            width: 100%;
            overflow: hidden;
            position: relative;
            background: #cbd5e1;
        }

        .card-img-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .card-body {
            padding: 15px;
            flex: 1;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .card-title {
            font-size: 17px;
            font-weight: 800;
            color: #0f172a;
            margin-bottom: 4px;
        }

        .card-sub {
            font-size: 13px;
            color: #64748b;
            margin-bottom: 12px;
        }

        .card-fact-box {
            background: #f8fafc;
            padding: 8px 12px;
            border-radius: 6px;
            border-left: 3px solid var(--wb-accent);
            font-size: 13px;
            color: #334155;
            margin-top: 8px;
        }

        /* Modal Image Viewer */
        .modal-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: rgba(15, 23, 42, 0.85);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 999;
            backdrop-filter: blur(4px);
        }

        .modal-overlay.active {
            display: flex;
        }

        .modal-content {
            background: white;
            border-radius: 16px;
            max-width: 500px;
            width: 90%;
            padding: 20px;
            text-align: center;
            position: relative;
            animation: zoomIn 0.25s ease-out;
        }

        @keyframes zoomIn {
            from { transform: scale(0.85); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }

        .modal-img {
            width: 100%;
            height: 250px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 12px;
        }

        .modal-close {
            position: absolute;
            top: 10px;
            right: 15px;
            font-size: 24px;
            background: none;
            border: none;
            cursor: pointer;
            color: #64748b;
        }

        /* Footer Page Mark */
        .wb-footer-mark {
            margin-top: 40px;
            border-top: 2px solid var(--wb-grey-dark);
            padding-top: 10px;
            display: flex;
            justify-content: space-between;
            color: #64748b;
            font-size: 13px;
            font-weight: 700;
        }

        /* Canvas Confetti */
        #confetti-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            pointer-events: none;
            z-index: 9999;
        }

        @media (max-width: 768px) {
            .page-container {
                padding: 20px;
            }
            .exercise-item {
                flex-direction: column;
                align-items: flex-start;
                gap: 8px;
            }
            .blank-field {
                width: 100%;
            }
            .tip-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>

    <canvas id="confetti-canvas"></canvas>

    <!-- Navigation Header -->
    <div class="top-nav">
        <div class="nav-title">
            <i class="fa-solid fa-book-open"></i> English for Libya - Grade 7 Workbook Page 5
        </div>
        <div class="mode-switch">
            <button class="nav-btn active" onclick="switchSlide(0)">
                <i class="fa-solid fa-file-lines"></i> شكل الصفحة الأصلي
            </button>
            <button class="nav-btn" onclick="switchSlide(1)">
                <i class="fa-solid fa-image"></i> صور المعالم (Exercise A)
            </button>
            <button class="nav-btn" onclick="switchSlide(2)">
                <i class="fa-solid fa-lightbulb"></i> الحقائق (Exercise B)
            </button>
            <button class="nav-btn" onclick="switchSlide(3)">
                <i class="fa-solid fa-spell-check"></i> المعاني (Exercise C)
            </button>
        </div>
    </div>

    <!-- SLIDE 1: Authentic Workbook Page Layout -->
    <div class="page-container active" id="slide-0">
        
        <!-- Writing Tip Header (Top section of Page 5) -->
        <div class="wb-header-banner">
            <span class="letter-badge">D</span> Write a paragraph about your holidays in your notebook.
        </div>

        <div class="writing-tip-box">
            <h4><i class="fa-solid fa-pen-nib"></i> Writing tip: Improving your writing</h4>
            <p style="font-size: 13px; color: #64748b; margin-bottom: 8px;">Make your writing better. Read and check these things:</p>
            <div class="tip-grid">
                <div class="tip-item">• <strong>spelling:</strong> التدقيق الإملائي</div>
                <div class="tip-item">• <strong>wrong words:</strong> تصحيح الكلمات الخطأ</div>
                <div class="tip-item">• <strong>punctuation:</strong> علامات الترقيم</div>
                <div class="tip-item">• <strong>missing words:</strong> الكلمات الناقصة</div>
            </div>
        </div>

        <!-- Lesson Header -->
        <div class="lesson-title-main">Lesson 2: Joe's Holiday Album</div>

        <!-- Exercise A -->
        <div class="exercise-block">
            <div class="wb-exercise-title">
                <span class="letter-badge">A</span> 
                <span><i class="fa-solid fa-headphones"></i> Listen to Joe talking about his photos again. Write one word he uses to describe each thing.</span>
            </div>

            <!-- Item 1 -->
            <div class="exercise-item">
                <div class="item-label">
                    <span class="item-num">1</span> Park Güell
                    <button class="img-trigger-btn" onclick="openModal('Park Güell', 'Barcelona, Spain', 'https://images.unsplash.com/photo-1583422409516-2895a77efded?auto=format&fit=crop&w=600&q=80', 'amazing')" title="عرض صورة المعلم"><i class="fa-regular fa-image"></i></button>
                </div>
                <div class="blank-field" id="ex-a-1" onclick="revealAnswer('ex-a-1')">
                    <span class="blank-answer">amazing</span>
                    <button class="reveal-btn-mini">كشف الإجابة</button>
                </div>
            </div>

            <!-- Item 2 -->
            <div class="exercise-item">
                <div class="item-label">
                    <span class="item-num">2</span> Leaning Tower of Pisa
                    <button class="img-trigger-btn" onclick="openModal('Leaning Tower of Pisa', 'Pisa, Italy', 'https://images.unsplash.com/photo-1543429776-2782fc8e1acd?auto=format&fit=crop&w=600&q=80', 'famous')" title="عرض صورة المعلم"><i class="fa-regular fa-image"></i></button>
                </div>
                <div class="blank-field" id="ex-a-2" onclick="revealAnswer('ex-a-2')">
                    <span class="blank-answer">famous</span>
                    <button class="reveal-btn-mini">كشف الإجابة</button>
                </div>
            </div>

            <!-- Item 3 -->
            <div class="exercise-item">
                <div class="item-label">
                    <span class="item-num">3</span> Leptis Magna
                    <button class="img-trigger-btn" onclick="openModal('Leptis Magna', 'Al-Khums, Libya', 'https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/Leptis_Magna_Theater_01.jpg/800px-Leptis_Magna_Theater_01.jpg', 'beautiful')" title="عرض صورة المعلم"><i class="fa-regular fa-image"></i></button>
                </div>
                <div class="blank-field" id="ex-a-3" onclick="revealAnswer('ex-a-3')">
                    <span class="blank-answer">beautiful</span>
                    <button class="reveal-btn-mini">كشف الإجابة</button>
                </div>
            </div>

            <!-- Item 4 -->
            <div class="exercise-item">
                <div class="item-label">
                    <span class="item-num">4</span> Big Ben
                    <button class="img-trigger-btn" onclick="openModal('Big Ben', 'London, UK', 'https://images.unsplash.com/photo-1529655683826-aba9b3e77383?auto=format&fit=crop&w=600&q=80', 'interesting')" title="عرض صورة المعلم"><i class="fa-regular fa-image"></i></button>
                </div>
                <div class="blank-field" id="ex-a-4" onclick="revealAnswer('ex-a-4')">
                    <span class="blank-answer">interesting</span>
                    <button class="reveal-btn-mini">كشف الإجابة</button>
                </div>
            </div>

            <!-- Item 5 -->
            <div class="exercise-item">
                <div class="item-label">
                    <span class="item-num">5</span> The Pyramids
                    <button class="img-trigger-btn" onclick="openModal('The Pyramids', 'Giza, Egypt', 'https://images.unsplash.com/photo-1503177119275-0aa32b3a9368?auto=format&fit=crop&w=600&q=80', 'fantastic')" title="عرض صورة المعلم"><i class="fa-regular fa-image"></i></button>
                </div>
                <div class="blank-field" id="ex-a-5" onclick="revealAnswer('ex-a-5')">
                    <span class="blank-answer">fantastic</span>
                    <button class="reveal-btn-mini">كشف الإجابة</button>
                </div>
            </div>

            <!-- Item 6 -->
            <div class="exercise-item">
                <div class="item-label">
                    <span class="item-num">6</span> Victoria Falls
                    <button class="img-trigger-btn" onclick="openModal('Victoria Falls', 'Zimbabwe / Zambia', 'https://images.unsplash.com/photo-1603201236596-eb1a63eb0f51?auto=format&fit=crop&w=600&q=80', 'exciting')" title="عرض صورة المعلم"><i class="fa-regular fa-image"></i></button>
                </div>
                <div class="blank-field" id="ex-a-6" onclick="revealAnswer('ex-a-6')">
                    <span class="blank-answer">exciting</span>
                    <button class="reveal-btn-mini">كشف الإجابة</button>
                </div>
            </div>
        </div>

        <!-- Exercise B Banner -->
        <div class="exercise-block">
            <div class="wb-exercise-title">
                <span class="letter-badge">B</span> 
                <span>Listen again. This time, note down any facts you hear.</span>
            </div>
            <p style="font-size: 14px; color: #64748b; margin-left: 10px;">(راجع الشريحة المخصصة للحقائق لرؤية جميع المعلومات المذكورة لكل معلم).</p>
        </div>

        <!-- Exercise C -->
        <div class="exercise-block">
            <div class="wb-exercise-title">
                <span class="letter-badge">C</span> 
                <span><i class="fa-solid fa-users"></i> Wha
