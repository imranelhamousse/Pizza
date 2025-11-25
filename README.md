# Pizza
Pizza morocco
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مطعم المغرب الأصيل</title>
    <style>
        body {
            font-family: "Arial", sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8f0;
            color: #333;
        }
        header {
            background-color: #d84315;
            color: white;
            padding: 30px 0;
            text-align: center;
            font-size: 32px;
            font-weight: bold;
        }
        nav {
            background-color: #ff7043;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .section {
            padding: 50px 20px;
            text-align: center;
        }
        .section h2 {
            color: #d84315;
            font-size: 28px;
        }
        .cards {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        .card {
            background-color: #fff3e0;
            padding: 20px;
            border-radius: 15px;
            width: 250px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .card img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            background-color: #d84315;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 50px;
        }
    </style>
</head>
<body>

<header>مطعم المغرب الأصيل</header>

<nav>
    <a href="#about">عن المطعم</a>
    <a href="#menu">قائمة الطعام</a>
    <a href="#contact">اتصل بنا</a>
</nav>

<section id="about" class="section">
    <h2>عن المطعم</h2>
    <p>مرحبا بكم في مطعم المغرب الأصيل، حيث نقدم أشهى الأكلات المغربية التقليدية بنكهات أصيلة وجودة عالية.</p>
</section>

<section id="menu" class="section">
    <h2>قائمة الطعام</h2>
    <div class="cards">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1601050690986-238e61c77c77?auto=format&fit=crop&w=400&q=80" alt="طاجين الدجاج">
            <h3>طاجين الدجاج</h3>
            <p>طاجين مغربي شهي بالدجاج والخضار والتوابل المغربية الأصيلة.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1586190848861-99aa4a171e90?auto=format&fit=crop&w=400&q=80" alt="الكسكس">
            <h3>الكسكس المغربي</h3>
            <p>كسكس مغربي بالتوابل والخضار الطازجة واللحم اللذيذ.</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092?auto=format&fit=crop&w=400&q=80" alt="الحريرة">
            <h3>الحريرة</h3>
            <p>شوربة مغربية تقليدية غنية بالمكونات الطازجة.</p>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <h2>اتصل بنا</h2>
    <p>📞 0123-456-789 | 📧 info@moroccanrestaurant.com</p>
    <p>🏠 شارع المغرب، الدار البيضاء، المغرب</p>
</section>

<footer>
    جميع الحقوق محفوظة &copy; 2025 مطعم المغرب الأصيل
</footer>

</body>
</html>
<div class="moroccan-logo">
  <div class="circle"></div>
  <div class="circle inner"></div>
  <div class="text">المغرب الأصيل</div>
</div>

<style>
.moroccan-logo {
  position: relative;
  width: 150px;
  height: 150px;
  margin: 20px auto;
  text-align: center;
  font-family: "Arial", sans-serif;
}
.moroccan-logo .circle {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  background: linear-gradient(135deg, #d84315, #ff7043);
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1;
}
.moroccan-logo .circle.inner {
  width: 100px;
  height: 100px;
  background: #fff8f0;
  top: 25px;
  left: 25px;
  z-index: 2;
}
.moroccan-logo .text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  z-index: 3;
  font-size: 18px;
  font-weight: bold;
  color: #d84315;
}
</style>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>موقع البيتزا الخاص بي</title>

    <!-- طريقة 1: favicon باستخدام صورة PNG -->
    <!-- ضع صورة شعار البيتزا في نفس المجلد باسم pizza.png -->
    <link rel="icon" href="pizza.png" type="image/png">

    <!-- طريقة 2: favicon باستخدام إيموجي (عمله عبر بيانات Base64) -->
    <link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🍕</text></svg>">
</head>
<body>
    <h1>مرحبا بك في موقع البيتزا الخاص بي 🍕</h1>
    <p>هنا تجد أشهى أنواع البيتزا!</p>
</body>
</html/>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>موقع البيتزا الخاص بي</title>

    <!-- favicon باستخدام صورة PNG -->
    <!-- ضع الصورة التي أرسلتها باسم pizza-cartoon.png في نفس مجلد الموقع -->
    <link rel="icon" href="pizza-cartoon.png" type="image/png">
</head>
<body>
    <h1>مرحبا بك في موقع البيتزا الخاص بي 🍕</h1>
    <p>استمتع بألذ أنواع البيتزا!</p>
</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>موقع البيتزا الخاص بي</title>

    <!-- favicon باستخدام صورة PNG -->
    <!-- ضع الصورة التي أرسلتها باسم pizza-cartoon.png في نفس مجلد الموقع -->
    <link rel="icon" href="pizza-cartoon.png" type="image/png">
</head>
<body>
    <h1>مرحبا بك في موقع البيتزا الخاص بي 🍕</h1>
    <p>استمتع بألذ أنواع البيتزا!</p>
</body>
</html>
