<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تاریخ جهان - دایرةالمعارف تاریخ</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; }
        :root { --primary: #2c3e50; --secondary: #3498db; --accent: #e74c3c; --light: #ecf0f1; --dark: #2c3e50; }
        body { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: #333; line-height: 1.6; min-height: 100vh; }
        .container { max-width: 1400px; margin: 0 auto; padding: 20px; }
        header { background: rgba(255, 255, 255, 0.95); padding: 2rem 0; text-align: center; border-radius: 20px; margin-bottom: 2rem; box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1); position: relative; overflow: hidden; }
        header::before { content: ''; position: absolute; top: 0; right: 0; width: 100%; height: 5px; background: linear-gradient(90deg, var(--accent), var(--secondary)); }
        h1 { color: var(--primary); font-size: 3.5rem; margin-bottom: 0.5rem; text-shadow: 2px 2px 4px rgba(0,0,0,0.1); }
        .subtitle { color: #7f8c8d; font-size: 1.3rem; margin-bottom: 1rem; }
        .creator { color: var(--accent); font-weight: bold; font-size: 1.1rem; }
        .search-container { background: rgba(255, 255, 255, 0.9); padding: 1.5rem; border-radius: 15px; margin-bottom: 2rem; text-align: center; }
        .search-box { display: flex; max-width: 600px; margin: 0 auto; }
        .search-box input { flex: 1; padding: 15px 20px; border: 2px solid var(--secondary); border-radius: 50px 0 0 50px; font-size: 1.1rem; outline: none; }
        .search-box button { background: var(--secondary); color: white; border: none; padding: 0 30px; border-radius: 0 50px 50px 0; cursor: pointer; font-size: 1.2rem; transition: all 0.3s ease; }
        .search-box button:hover { background: #2980b9; }
        .nav { background: rgba(255, 255, 255, 0.9); padding: 1rem; border-radius: 15px; margin-bottom: 2rem; }
        .nav-list { list-style: none; display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap; }
        .nav-list a { text-decoration: none; color: var(--dark); font-weight: bold; padding: 0.8rem 1.5rem; border-radius: 25px; transition: all 0.3s ease; background: var(--light); display: flex; align-items: center; gap: 0.5rem; }
        .nav-list a:hover { background: var(--secondary); color: white; transform: translateY(-3px); box-shadow: 0 5px 15px rgba(52, 152, 219, 0.4); }
        .main-content { display: grid; grid-template-columns: repeat(auto-fit, minmax(400px, 1fr)); gap: 2rem; margin-bottom: 2rem; }
        .section { background: rgba(255, 255, 255, 0.95); padding: 2rem; border-radius: 20px; box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1); transition: all 0.3s ease; position: relative; overflow: hidden; }
        .section::before { content: ''; position: absolute; top: 0; right: 0; width: 100%; height: 4px; background: linear-gradient(90deg, var(--accent), var(--secondary)); }
        .section:hover { transform: translateY(-10px); box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15); }
        .section h2 { color: var(--primary); margin-bottom: 1.5rem; border-bottom: 3px solid var(--secondary); padding-bottom: 0.5rem; font-size: 1.8rem; display: flex; align-items: center; gap: 0.5rem; }
        .timeline { margin-top: 1rem; }
        .timeline-item { margin-bottom: 1.5rem; padding-right: 1.5rem; border-right: 3px solid var(--secondary); position: relative; }
        .timeline-item::before { content: ''; position: absolute; right: -8px; top: 0; width: 14px; height: 14px; background: var(--accent); border-radius: 50%; }
        .year { font-weight: bold; color: var(--accent); font-size: 1.1rem; display: inline-block; margin-bottom: 0.3rem; }
        footer { text-align: center; background: rgba(255, 255, 255, 0.9); padding: 2.5rem; border-radius: 20px; margin-top: 3rem; }
        .quote { font-style: italic; color: var(--primary); font-size: 1.2rem; margin-bottom: 1rem; }
        @media (max-width: 768px) {
            .nav-list { flex-direction: column; gap: 0.8rem; }
            h1 { font-size: 2.5rem; }
            .main-content { grid-template-columns: 1fr; }
            .search-box { flex-direction: column; gap: 1rem; }
            .search-box input, .search-box button { border-radius: 50px; width: 100%; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>📚 دایرةالمعارف تاریخ جهان</h1>
            <p class="subtitle">کشف اسرار گذشته، درک حال، ساختن آینده</p>
            <p class="creator">طراحی و توسعه: کیارش سهولی</p>
        </header>

        <div class="search-container">
            <div class="search-box">
                <input type="text" id="searchInput" placeholder="جستجو در تاریخ... (مثال: هخامنشی، ماه، جنگ)">
                <button onclick="searchHistory()"><i class="fas fa-search"></i> جستجو</button>
            </div>
        </div>

        <nav class="nav">
            <ul class="nav-list">
                <li><a href="#iran"><i class="fas fa-crown"></i> ایران باستان</a></li>
                <li><a href="#space"><i class="fas fa-star"></i> ستاره‌ها و فضا</a></li>
                <li><a href="#world"><i class="fas fa-globe"></i> تاریخ جهان</a></li>
                <li><a href="#science"><i class="fas fa-flask"></i> تاریخ علم</a></li>
                <li><a href="#art"><i class="fas fa-palette"></i> تاریخ هنر</a></li>
                <li><a href="#war"><i class="fas fa-shield-alt"></i> جنگ‌های بزرگ</a></li>
            </ul>
        </nav>

        <main class="main-content">
            <section id="iran" class="section">
                <h2><i class="fas fa-crown"></i> تمدن ایران باستان</h2>
                <p>یکی از کهن‌ترین و درخشان‌ترین تمدن‌های جهان با قدمتی بیش از ۷۰۰۰ سال</p>
                <div class="timeline">
                    <div class="timeline-item"><span class="year">۵۵۰ پیش از میلاد:</span><p>تأسیس شاهنشاهی هخامنشی به دست کوروش بزرگ - انتشار منشور حقوق بشر</p></div>
                    <div class="timeline-item"><span class="year">۵۲۱ پیش از میلاد:</span><p>پادشاهی داریوش بزرگ - ساخت تخت جمشید و راه‌شاهی</p></div>
                    <div class="timeline-item"><span class="year">۳۳۰ پیش از میلاد:</span><p>پایان امپراتوری هخامنشی با حمله اسکندر مقدونی</p></div>
                    <div class="timeline-item"><span class="year">۲۲۴ پس از میلاد:</span><p>شکل‌گیری امپراتوری ساسانی توسط اردشیر بابکان</p></div>
                    <div class="timeline-item"><span class="year">۶۵۱ پس از میلاد:</span><p>سقوط امپراتوری ساسانی و آغاز دوره اسلامی در ایران</p></div>
                </div>
            </section>

            <section id="space" class="section">
                <h2><i class="fas fa-star"></i> اکتشافات فضایی</h2>
                <p>سفر بشر به فراسوی زمین و کشف اسرار کیهان</p>
                <div class="timeline">
                    <div class="timeline-item"><span class="year">۱۵۴۳ میلادی:</span><p>نیکلاس کوپرنیک نظریه مرکزیت خورشید را منتشر کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۶۰۹ میلادی:</span><p>گالیله اولین تلسکوپ نجومی را ساخت و قمرهای مشتری را کشف کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۹۵۷ میلادی:</span><p>شوروی اسپوتنیک-۱، اولین ماهواره مصنوعی را به فضا پرتاب کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۹۶۱ میلادی:</span><p>یوری گاگارین اولین انسانی شد که به فضا سفر کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۹۶۹ میلادی:</span><p>نیل آرمسترانگ و باز آلدرین اولین انسان‌هایی شدند که روی ماه قدم گذاشتند</p></div>
                </div>
            </section>

            <section id="world" class="section">
                <h2><i class="fas fa-globe"></i> نقاط عطف تاریخ جهان</h2>
                <p>رویدادهای سرنوشت‌ساز که مسیر تاریخ بشر را تغییر دادند</p>
                <div class="timeline">
                    <div class="timeline-item"><span class="year">۳۲۰۰ پیش از میلاد:</span><p>اختراع خط در میان‌رودان - آغاز تاریخ مکتوب</p></div>
                    <div class="timeline-item"><span class="year">۴۷۶ میلادی:</span><p>سقوط امپراتوری روم غربی - آغاز قرون وسطی</p></div>
                    <div class="timeline-item"><span class="year">۱۴۹۲ میلادی:</span><p>کشف قاره آمریکا توسط کریستف کلمب</p></div>
                    <div class="timeline-item"><span class="year">۱۷۸۹ میلادی:</span><p>انقلاب فرانسه - آغاز عصر دموکراسی‌های مدرن</p></div>
                    <div class="timeline-item"><span class="year">۱۹۴۵ میلادی:</span><p>پایان جنگ جهانی دوم و تأسیس سازمان ملل متحد</p></div>
                </div>
            </section>

            <section id="science" class="section">
                <h2><i class="fas fa-flask"></i> انقلاب‌های علمی</h2>
                <p>دستاوردهای شگفت‌انگیز که درک ما از جهان را متحول کردند</p>
                <div class="timeline">
                    <div class="timeline-item"><span class="year">۱۶۸۷ میلادی:</span><p>ایزاک نیوتن قوانین حرکت و گرانش را در کتاب "اصول" منتشر کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۸۵۹ میلادی:</span><p>چارلز داروین نظریه تکامل را در "منشأ گونه‌ها" ارائه داد</p></div>
                    <div class="timeline-item"><span class="year">۱۹۰۵ میلادی:</span><p>آلبرت اینشتین نظریه نسبیت خاص را مطرح کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۹۵۳ میلادی:</span><p>کشف ساختار DNA توسط واتسون، کریک و فرانکلین</p></div>
                    <div class="timeline-item"><span class="year">۱۹۹۰ میلادی:</span><p>پرتاب تلسکوپ فضایی هابل به فضا</p></div>
                </div>
            </section>

            <section id="art" class="section">
                <h2><i class="fas fa-palette"></i> تاریخ هنر جهان</h2>
                <p>تکامل بیان هنری از غارنگاره‌ها تا هنر دیجیتال</p>
                <div class="timeline">
                    <div class="timeline-item"><span class="year">۱۵۰۰۰ پیش از میلاد:</span><p>نقاشی‌های غار لاسکو در فرانسه</p></div>
                    <div class="timeline-item"><span class="year">۱۵۰۴ میلادی:</span><p>میكلانژ تندیس داوود را تکمیل کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۸۸۸ میلادی:</span><p>ون گوگ تابلوی "شب پرستاره" را خلق کرد</p></div>
                    <div class="timeline-item"><span class="year">۱۹۰۷ میلادی:</span><p>پابلو پیکاسو سبک کوبیسم را با تابلوی "دوشیزگان آوینیون" بنیان گذاشت</p></div>
                </div>
            </section>

            <section id="war" class="section">
                <h2><i class="fas fa-shield-alt"></i> جنگ‌های بزرگ تاریخ</h2>
                <p>نبردهایی که مرزهای جهان را تغییر دادند</p>
                <div class="timeline">
                    <div class="timeline-item"><span class="year">۴۹۰ پیش از میلاد:</span><p>نبرد ماراتون - یونان باستان در برابر امپراتوری پارس</p></div>
                    <div class="timeline-item"><span class="year">۱۰۶۶ میلادی:</span><p>نبرد هستینگز - نورمن‌ها انگلستان را فتح کردند</p></div>
                    <div class="timeline-item"><span class="year">۱۸۱۵ میلادی:</span><p>نبرد واترلو - پایان امپراتوری ناپلئون</p></div>
                    <div class="timeline-item"><span class="year">۱۹۱۴-۱۹۱۸ میلادی:</span><p>جنگ جهانی اول - اولین جنگ بزرگ جهانی</p></div>
                    <div class="timeline-item"><span class="year">۱۹۳۹-۱۹۴۵ میلادی:</span><p>جنگ جهانی دوم - مرگبارترین جنگ تاریخ</p></div>
                </div>
            </section>
        </main>

        <footer>
            <div class="quote">"تاریخ، فلسفه‌ای است با مثال‌هایی از فضیلت و رذیلت"</div>
            <p>~ لرد بولینگ بروک ~</p>
            <div style="margin-top: 2rem;">
                <p><strong>© ۲۰۲۴ دایرةالمعارف تاریخ جهان</strong></p>
                <p>طراحی و توسعه توسط کیارش سهولی</p>
                <p style="margin-top: 1rem; color: var(--accent);"><i class="fas fa-heart"></i> ساخته شده با عشق به تاریخ و دانش</p>
            </div>
        </footer>
    </div>

    <script>
        function searchHistory() {
            const searchTerm = document.getElementById('searchInput').value.toLowerCase();
            if (searchTerm.trim() === '') {
                alert('لطفاً عبارت مورد نظر برای جستجو را وارد کنید');
                return;
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
            alert('جستجو برای: ' + searchTerm + '\n\nاین قابلیت در نسخه‌های بعدی کامل خواهد شد. برای حالا می‌توانید از منوی بالا استفاده کنید.');
        }
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({ behavior: 'smooth', block: 'start' });
                }
            });
        });
        document.getElementById('searchInput').addEventListener('keypress', function(e) {
            if (e.key === 'Enter') { searchHistory(); }
        });
    </script>
</body>
</html>
