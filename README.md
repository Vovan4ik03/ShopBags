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
- **Ліцензія:** MIT
- **Результат перевірки:** [📜 License Report](license-report.txt)

# Cookie Popup (GDPR)
- **Функціонал:** Відображення повідомлення про використання файлів cookie
- **Інструменти:** `cookieconsent`

**Приклад у `navigation.php`:**
```php
<script src="cookieconsent.min.js"></script>
<script>
  window.addEventListener("load", function(){
    cookieconsent.run({
      notice_banner_type: "interstitial",
      consent_type: "express"
    });
  });
</script>
