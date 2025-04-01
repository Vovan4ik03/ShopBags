# ShopBags
This is an online store where you can buy bags of various brands and styles.

### 🚀 Technologies  
- 🎨 **Frontend:** HTML, CSS, JavaScript  
- 🖥 **Backend:** PHP  
- 🗄 **Database:** MySQL 
- 🔄 **Version Control:** Git, GitHub  
- 📦 **Package Manager:** Composer  
### Installation
```bash
composer install
php artisan migrate
php artisan serve
```
### Autor 
- Done by student Makarov Volodymyr
- [License](https://github.com/vovan4ik1/ShopBags?tab=MIT-1-ov-file)

# License
- **License:** MIT
- **Result:** [📜 License Report](license-report.txt)

# Cookie Popup (GDPR)
- **Tool:** `cookieconsent`

**Example `index.php`:**
```php
<?php
session_start();
?>

<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cookie Popup</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div id="cookie-popup" class="cookie-popup">
        <p>Ми використовуємо файли cookie для покращення вашого досвіду на сайті. Продовжуючи користуватися сайтом, ви погоджуєтесь на їх використання.</p>
        <button id="accept-cookies">Прийняти</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
```

```js
document.addEventListener("DOMContentLoaded", function () {
    const popup = document.getElementById("cookie-popup");
    const acceptBtn = document.getElementById("accept-cookies");

    if (!localStorage.getItem("cookiesAccepted")) {
        popup.style.display = "block";
    }

    acceptBtn.addEventListener("click", function () {
        localStorage.setItem("cookiesAccepted", "true");
        popup.style.display = "none";
    });
}); 
```

# Privacy policy
[📜 User Guide](Privacy-policy.txt)

# API (POSTMAN)
- [Docs](https://documenter.getpostman.com/view/34437124/2sAYdbNYHN)
