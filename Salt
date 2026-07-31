<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>دليل صرف العلاجات | مستشفى الحسين السلط الجديد</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;500;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0c4a60;
            --primary-accent: #008080;
            --secondary-color: #f4a261;
            --sub-pharmacy: #10b981;
            --main-pharmacy: #3b82f6;
            --card-bg: #ffffff;
            --text-main: #1f2937;
            --text-muted: #6b7280;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Tajawal', sans-serif;
        }

        body {
            background: #f3f4f6;
            color: var(--text-main);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
        }

        .app-container {
            width: 100%;
            max-width: 550px;
            background: var(--card-bg);
            border-radius: 24px;
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            margin-top: 10px;
            border: 1px solid rgba(229, 231, 235, 0.8);
        }

        .header {
            background: linear-gradient(135deg, #0c4a60 0%, #1d7074 100%);
            color: white;
            padding: 30px 20px 22px 20px;
            text-align: center;
            position: relative;
        }

        .header-icon {
            font-size: 42px;
            margin-bottom: 12px;
            color: #6ee7b7;
        }

        .header h1 {
            font-size: 1.5rem;
            font-weight: 800;
            margin-bottom: 6px;
        }

        .header h2 {
            font-size: 1rem;
            font-weight: 500;
            opacity: 0.9;
            color: #e0f2fe;
        }

        /* رسالة الترحيب والكلمات الطيبة للمرضى */
        .patient-welcome-card {
            background: linear-gradient(135deg, #f0fdf4 0%, #e0f2fe 100%);
            border-bottom: 1px solid #e5e7eb;
            padding: 16px 20px;
            text-align: center;
            position: relative;
        }

        .patient-welcome-card p {
            font-size: 0.95rem;
            color: #065f46;
            font-weight: 700;
            line-height: 1.6;
        }

        .patient-welcome-card span {
            display: block;
            font-size: 0.85rem;
            color: #0c4a60;
            font-weight: 500;
            margin-top: 4px;
        }

        .search-section {
            padding: 22px 20px 15px 20px;
        }

        .search-title {
            font-size: 0.95rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .search-wrapper {
            position: relative;
            margin-bottom: 15px;
        }

        .search-input {
            width: 100%;
            padding: 16px 48px 16px 18px;
            border: 2px solid #e5e7eb;
            border-radius: 16px;
            font-size: 1.05rem;
            outline: none;
            transition: all 0.3s ease;
            background: #f9fafb;
        }

        .search-input:focus {
            border-color: var(--primary-accent);
            background: #ffffff;
            box-shadow: 0 0 0 4px rgba(0, 128, 128, 0.1);
        }

        .search-icon {
            position: absolute;
            right: 18px;
            top: 50%;
            transform: translateY(-50%);
            color: #9ca3af;
            font-size: 1.2rem;
        }

        .quick-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            margin-bottom: 20px;
        }

        .tag {
            background: #f3f4f6;
            border: 1px solid #e5e7eb;
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.85rem;
            color: #4b5563;
            cursor: pointer;
            transition: all 0.2s ease;
            font-weight: 500;
        }

        .tag:hover {
            background: var(--primary-color);
            color: white;
            border-color: var(--primary-color);
        }

        .results-container {
            padding: 0 20px 25px 20px;
        }

        .result-card {
            border-radius: 18px;
            padding: 20px;
            display: none;
            animation: fadeIn 0.3s ease-in-out;
            position: relative;
            overflow: hidden;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(8px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .result-card.sub {
            background: #ecfdf5;
            border: 2px solid #a7f3d0;
        }

        .result-card.main {
            background: #eff6ff;
            border: 2px solid #bfdbfe;
        }

        .result-card.not-found {
            background: #fff1f2;
            border: 2px solid #fecdd3;
            text-align: center;
        }

        .badge {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            padding: 6px 12px;
            border-radius: 10px;
            font-size: 0.85rem;
            font-weight: 700;
            margin-bottom: 12px;
        }

        .badge.sub {
            background: #10b981;
            color: white;
        }

        .badge.main {
            background: #3b82f6;
            color: white;
        }

        .badge.not-found {
            background: #f43f5e;
            color: white;
        }

        .clinic-name-title {
            font-size: 1.25rem;
            font-weight: 800;
            color: #111827;
            margin-bottom: 10px;
        }

        .pharmacy-location {
            font-size: 1.05rem;
            font-weight: 700;
            color: #1f2937;
            margin-bottom: 8px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .location-detail {
            font-size: 0.95rem;
            color: #4b5563;
            display: flex;
            align-items: center;
            gap: 8px;
            background: rgba(255, 255, 255, 0.6);
            padding: 10px;
            border-radius: 10px;
        }

        .pharmacy-list-section {
            padding: 0 20px 25px 20px;
        }

        .section-header {
            font-size: 1rem;
            font-weight: 700;
            color: var(--primary-color);
            margin-bottom: 12px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .clinic-item {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 12px 14px;
            border-bottom: 1px solid #f3f4f6;
            font-size: 0.95rem;
        }

        .clinic-item:last-child {
            border-bottom: none;
        }

        .clinic-tag {
            font-size: 0.8rem;
            padding: 3px 8px;
            border-radius: 6px;
            font-weight: 700;
        }

        .clinic-tag.sub {
            background: #d1fae5;
            color: #065f46;
        }

        .clinic-tag.main {
            background: #dbeafe;
            color: #1e40af;
        }

        .footer {
            text-align: center;
            padding: 22px 15px;
            font-size: 0.88rem;
            color: var(--text-muted);
            border-top: 1px solid #e5e7eb;
            background: #fafafa;
        }

        .footer-signature {
            font-weight: 700;
            color: var(--primary-color);
            font-size: 0.95rem;
            margin-bottom: 6px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: 4px;
        }

        .footer-signature span {
            display: inline-flex;
            align-items: center;
            gap: 6px;
        }

        .live-status {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            font-size: 0.75rem;
            color: #10b981;
            background: #ecfdf5;
            padding: 4px 10px;
            border-radius: 20px;
            margin-top: 8px;
        }

        .dot {
            width: 8px;
            height: 8px;
            background-color: #10b981;
            border-radius: 50%;
            display: inline-block;
            animation: pulse 1.5s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(16, 185, 129, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 6px rgba(16, 185, 129, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(16, 185, 129, 0); }
        }
    </style>
</head>
<body>

    <div class="app-container">
        <!-- الهيدر الرئيسي الرسمية والمنظمة بدون مبالغة -->
        <div class="header">
            <div class="header-icon">
                <i class="fa-solid fa-prescription-bottle-medical"></i>
            </div>
            <h1>مستشفى الحسين السلط الجديد</h1>
            <h2>دليل صرف العلاجات - قسم الصيدلة</h2>
            <div>
                <div class="live-status">
                    <span class="dot"></span> الخدمة متوفرة ومحدثة
                </div>
            </div>
        </div>

        <!-- بطاقات الترحيب بالمرضى ودعوات العافية -->
        <div class="patient-welcome-card">
            <p><i class="fa-solid fa-heart-pulse" style="color: #10b981; margin-left: 6px;"></i> أهلاً بكم.. نتمنى لكم دوام الصحة والعافية والشفاء العاجل</p>
            <span>نحن هنا لخدمتكم وإرشادكم لأسهل وأسرع طريق لصرف علاجاتكم</span>
        </div>

        <!-- قسم البحث -->
        <div class="search-section">
            <div class="search-title">
                <i class="fa-solid fa-magnifying-glass"></i>
                ابحث عن عيادتك لمعرفة صيدلية الصرف:
            </div>
            <div class="search-wrapper">
                <input type="text" id="clinicInput" class="search-input" placeholder="أدخل اسم العيادة (مثال: باطنية، أطفال...)" oninput="searchClinic()">
                <i class="fa-solid fa-search search-icon"></i>
            </div>

            <!-- اختصارات سريعة -->
            <div class="quick-tags">
                <span class="tag" onclick="quickSearch('باطنية')">الباطنية</span>
                <span class="tag" onclick="quickSearch('أعصاب')">الأعصاب</span>
                <span class="tag" onclick="quickSearch('جلدية')">الجلدية</span>
                <span class="tag" onclick="quickSearch('أطفال')">الأطفال</span>
                <span class="tag" onclick="quickSearch('عظام')">العظام</span>
            </div>
        </div>

        <!-- بطاقة ظهور النتيجة -->
        <div class="results-container">
            <div id="resultCard" class="result-card">
                <div id="badgeStatus" class="badge"></div>
                <div id="clinicTitle" class="clinic-name-title"></div>
                <div id="pharmacyName" class="pharmacy-location"></div>
                <div id="locationDetail" class="location-detail"></div>
            </div>
        </div>

        <!-- قائمة العيادات الشاملة -->
        <div class="pharmacy-list-section">
            <div class="section-header">
                <span>دليل العيادات الشامل</span>
                <small style="color: var(--text-muted); font-weight: normal;">اضغط للبحث السريع</small>
            </div>
            <div id="fullClinicsList"></div>
        </div>

        <!-- الفوتر البسيط مع إدراج الإشراف والإعداد بالأسفل بأسلوب راقٍ -->
        <div class="footer">
            <div class="footer-signature">
                <span><i class="fa-solid fa-user-doctor" style="color: var(--primary-accent);"></i> بإشراف رئيس قسم الصيدلة د. اروى العدوان</span>
                <span><i class="fa-solid fa-laptop-code" style="color: var(--primary-accent);"></i> اعداد وتصميم : د. عزالدين الخرابشه</span>
            </div>
            <p style="margin-top: 8px;">قسم الصيدلة - مستشفى الحسين السلط الجديد © 2026</p>
        </div>
    </div>

    <script>
        // رابط CSV الخاص بقاعدة البيانات
        const sheetCsvUrl = 'https://docs.google.com/spreadsheets/d/1f63I0wyTLIxfI4vE1uO8SqiIMgwNOWizdQFZwfaHFtQ/export?format=csv';

        let clinicsData = [
            { name: "عيادة الباطنية", pharmacy: "الصيدلية الفرعية", location: "الطابق الأرضي - المبنى الرئيسي" },
            { name: "عيادة الأعصاب", pharmacy: "الصيدلية الفرعية", location: "الطابق الأرضي - المبنى الرئيسي" },
            { name: "عيادة الجلدية", pharmacy: "الصيدلية الفرعية", location: "الطابق الأرضي - المبنى الرئيسي" },
            { name: "عيادة الأطفال", pharmacy: "الصيدلية الرئيسية", location: "مبنى العيادات الخارجية" },
            { name: "عيادة العظام", pharmacy: "الصيدلية الرئيسية", location: "مبنى العيادات الخارجية" },
            { name: "عيادة الجراحة", pharmacy: "الصيدلية الرئيسية", location: "مبنى العيادات الخارجية" }
        ];

        async function fetchLiveSheetData() {
            try {
                const response = await fetch(sheetCsvUrl);
                if (response.ok) {
                    const csvText = await response.text();
                    const rows = csvText.split('\n').slice(1);
                    const loadedData = rows.map(row => {
                        const cols = row.split(',');
                        return {
                            name: cols[0]?.trim().replace(/^"|"$/g, ''),
                            pharmacy: cols[1]?.trim().replace(/^"|"$/g, ''),
                            location: cols[2]?.trim().replace(/^"|"$/g, '')
                        };
                    }).filter(item => item.name && item.pharmacy);
                    
                    if(loadedData.length > 0) {
                        clinicsData = loadedData;
                        renderFullList();
                    }
                }
            } catch (error) {
                console.log("تطبيق البيانات الافتراضية.");
            }
        }

        function renderFullList() {
            const listContainer = document.getElementById("fullClinicsList");
            listContainer.innerHTML = "";
            clinicsData.forEach(item => {
                const isSub = item.pharmacy.includes("الفرعية");
                const div = document.createElement("div");
                div.className = "clinic-item";
                div.onclick = () => quickSearch(item.name);
                div.style.cursor = "pointer";
                div.innerHTML = `
                    <span style="font-weight: 600;"><i class="fa-solid fa-stethoscope" style="color: var(--primary-accent); margin-left: 8px;"></i>${item.name}</span>
                    <span class="clinic-tag ${isSub ? 'sub' : 'main'}">${item.pharmacy}</span>
                `;
                listContainer.appendChild(div);
            });
        }

        function searchClinic() {
            const input = document.getElementById("clinicInput").value.trim().toLowerCase();
            const resultCard = document.getElementById("resultCard");
            const badgeStatus = document.getElementById("badgeStatus");
            const clinicTitle = document.getElementById("clinicTitle");
            const pharmacyName = document.getElementById("pharmacyName");
            const locationDetail = document.getElementById("locationDetail");

            if (input === "") {
                resultCard.style.display = "none";
                return;
            }

            const match = clinicsData.find(item => item.name.toLowerCase().includes(input));

            if (match) {
                const isSub = match.pharmacy.includes("الفرعية");
                
                resultCard.className = `result-card ${isSub ? 'sub' : 'main'}`;
                badgeStatus.className = `badge ${isSub ? 'sub' : 'main'}`;
                badgeStatus.innerHTML = isSub ? '<i class="fa-solid fa-circle-check"></i> الصيدلية الفرعية' : '<i class="fa-solid fa-hospital"></i> الصيدلية الرئيسية';
                
                clinicTitle.textContent = match.name;
                pharmacyName.innerHTML = `<i class="fa-solid fa-pills" style="color: ${isSub ? '#10b981' : '#3b82f6'}"></i> يصرف الدواء من: ${match.pharmacy}`;
                locationDetail.innerHTML = `<i class="fa-solid fa-location-dot" style="color: #ef4444"></i> <strong>الموقع:</strong> ${match.location || 'يرجى التوجه إلى القسم المخصص'}`;
                
                resultCard.style.display = "block";
            } else {
                resultCard.className = "result-card not-found";
                badgeStatus.className = "badge not-found";
                badgeStatus.innerHTML = '<i class="fa-solid fa-circle-exclamation"></i> عيادة غير مدرجة';
                
                clinicTitle.textContent = "لم نجد هذه العيادة في القائمة السريعة";
                pharmacyName.innerHTML = "";
                locationDetail.innerHTML = `<i class="fa-solid fa-info-circle"></i> يرجى التوجه إلى <strong>الصيدلية الرئيسية</strong> للاستفسار وصرف العلاج.`;
                
                resultCard.style.display = "block";
            }
        }

        function quickSearch(name) {
            document.getElementById("clinicInput").value = name;
            searchClinic();
            window.scrollTo({ top: 180, behavior: 'smooth' });
        }

        window.onload = () => {
            renderFullList();
            fetchLiveSheetData();
        };
    </script>
</body>
</html>
