<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>نظام تتبع الشاحنات الكبيرة</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="assets/logo.png" alt="شعار نظام التتبع">
            <h1>نظام تتبع الشاحنات الكبيرة</h1>
        </div>
        <nav>
            <a href="#features">المميزات</a>
            <a href="#pricing">الأسعار</a>
            <a href="#contact">تواصل معنا</a>
        </nav>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h2>تتبع شاحناتك الكبيرة بكفاءة وأمان</h2>
            <p>نظام متكامل لتتبع وإدارة أسطول الشاحنات الكبيرة الخاص بك. احصل على رؤية كاملة لتحركات شاحناتك، وتحسين الكفاءة التشغيلية، وتوفير الوقت والمال.</p>
            <a href="#contact" class="btn">ابدأ الآن</a>
        </div>
    </section>

    <section id="features" class="features">
        <h2>المميزات الرئيسية</h2>
        <div class="feature-card">
            <img src="assets/icon1.png" alt="تتبع مباشر">
            <h3>تتبع مباشر</h3>
            <p>راقب موقع شاحناتك في الوقت الفعلي على الخريطة.</p>
        </div>
        <div class="feature-card">
            <img src="assets/icon2.png" alt="تحليل البيانات">
            <h3>تحليل البيانات</h3>
            <p>احصل على تقارير مفصلة حول أداء الشاحنات، وكفاءة الوقود، وسلوك القيادة.</p>
        </div>
         <div class="feature-card">
            <img src="assets/icon3.png" alt="تنبيهات فورية">
            <h3>تنبيهات فورية</h3>
            <p>احصل على تنبيهات فورية في حالة حدوث أي مشكلة، مثل تجاوز السرعة أو الخروج عن المسار المحدد.</p>
        </div>
         <div class="feature-card">
            <img src="assets/icon4.png" alt="تكامل كامل">
            <h3>تكامل كامل</h3>
            <p>يتكامل النظام بسهولة مع الأنظمة الأخرى التي تستخدمها.</p>
        </div>
    </section>
    
      <section id="pricing" class="pricing">
        <h2>باقات الأسعار</h2>
          <div class="pricing-card">
                <h3>الباقة الأساسية</h3>
                <p class="price">150$ / شهرياً</p>
                <ul>
                    <li>تتبع مباشر</li>
                    <li>تنبيهات أساسية</li>
                     <li>دعم فني 24/7</li>
                </ul>
                <a href="#contact" class="btn">اشترك الآن</a>
          </div>
            <div class="pricing-card">
                <h3>الباقة الاحترافية</h3>
                <p class="price">300$ / شهرياً</p>
                <ul>
                    <li>تتبع مباشر</li>
                    <li>تنبيهات متقدمة</li>
                    <li>تحليل بيانات</li>
                    <li>دعم فني 24/7</li>
                    
                </ul>
               <a href="#contact" class="btn">اشترك الآن</a>
          </div>
    </section>

    <section id="contact" class="contact">
        <h2>تواصل معنا</h2>
        <form>
            <input type="text" placeholder="اسمك">
            <input type="email" placeholder="بريدك الإلكتروني">
            <textarea placeholder="رسالتك"></textarea>
            <button type="submit" class="btn">إرسال</button>
        </form>
    </section>

    <footer>
        <p>© 2024 نظام تتبع الشاحنات الكبيرة</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    direction: rtl;
    text-align: right;
}

header {
    background-color: #f8f8f8;
    padding: 1rem 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    display: flex;
    align-items: center;
    margin-right: 20px;
}

.logo img {
    height: 50px;
    margin-left: 10px;
}

nav a {
    margin-left: 20px;
    text-decoration: none;
    color: #555;
    font-weight: bold;
}

nav a:hover {
    color: #007bff;
}

.hero {
    background-image: url('assets/truck-bg.jpg');
    background-size: cover;
    background-position: center;
    color: white;
    text-align: center;
    padding: 100px 0;
}

.hero-content {
    max-width: 800px;
    margin: 0 auto;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

.btn {
    display: inline-block;
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    text-decoration: none;
    font-weight: bold;
}

.btn:hover {
    background-color: #0056b3;
}

.features {
    padding: 50px 0;
    text-align: center;
}

.features h2{
    margin-bottom: 40px;
}

.feature-card {
    display: inline-block;
    width: 300px;
    padding: 20px;
    margin: 20px;
    border: 1px solid #eee;
    border-radius: 8px;
     background: #fff;
}

.feature-card img {
    height: 80px;
    margin-bottom: 15px;
}

.feature-card h3 {
    margin-bottom: 10px;
}

.pricing {
    padding: 50px 0;
    text-align: center;
    background-color: #f8f8f8;
}

.pricing h2{
     margin-bottom: 40px;
}
.pricing-card {
    display: inline-block;
    width: 300px;
    padding: 20px;
    margin: 20px;
    border: 1px solid #ddd;
    border-radius: 8px;
    background: #fff;
}

.pricing-card h3{
    margin-bottom: 10px;
    font-size: 1.5rem;
}

.pricing-card ul {
    list-style: none;
    padding: 0;
    margin-bottom: 20px;
}

.pricing-card ul li{
    padding: 5px 0;
    border-bottom: 1px solid #eee;
}


.price {
    font-size: 1.5rem;
    color: #007bff;
    margin-bottom: 20px;
}
.contact {
    padding: 50px 0;
    text-align: center;
    background-color: #f8f8f8;
}

.contact form {
    max-width: 500px;
    margin: 20px auto;
    display: flex;
    flex-direction: column;
}

.contact input, .contact textarea {
    margin-bottom: 15px;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
    text-align: right;
}

footer {
    text-align: center;
    padding: 20px 0;
    background-color: #333;
    color: white;
}
// هنا يمكنك إضافة أي أكواد JavaScript إضافية إذا لزم الأمر
// على سبيل المثال: إضافة تأثيرات على الصفحة، أو التعامل مع نماذج الإدخال.
document.addEventListener('DOMContentLoaded', function() {
    // يمكنك إضافة أوامر JavaScript هنا بعد تحميل الصفحة بالكامل
    
    // مثال: إضافة تأثير تمرير سلس عند النقر على روابط القائمة
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            
            const targetId = this.getAttribute('href').substring(1);
            const targetElement = document.getElementById(targetId);
            
            if (targetElement) {
                window.scrollTo({
                    top: targetElement.offsetTop - 50, // تعويض بسيط لضمان عدم حجب الرأس
                    behavior: 'smooth'
                });
            }
        });
    });

  });
