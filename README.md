

```md
# 🌐 PHP URL Shortener with AdSense & Interactive Game 🎮  

![Project Screenshot](https://tools.licfree.com/link/images/ss1.png)  

🚀 **A powerful PHP-based URL shortener with AdSense monetization and an engaging interactive game to maximize user engagement and earnings.**  

---

## 🔗 **Live Demo**
- 🟢 **Shorten URL Page:** [Try It Now](https://tools.licfree.com/link)  
- 🟢 **Ad Waiting Page with Game:** [View Example](https://tools.licfree.com/link/e3e610)  

---

## **🛠 Features**
✅ **Instant URL Shortening** – Converts long URLs into short, trackable links 📏  
✅ **AdSense Monetization** – Smart ad placement for **high CPC revenue** 💰  
✅ **Interactive Game** – "Catch the Falling Stars" mini-game to keep users engaged 🎮  
✅ **Custom Short Links** – Users can generate **random or custom** short URLs 🔗  
✅ **SEO Optimized** – Structured data and metadata for better search visibility 📈  
✅ **Fast Redirection** – Lightning-speed redirection with security checks ⚡  
✅ **Database-Driven** – Uses **MySQL** for efficient link management 🗃  
✅ **User-Friendly Design** – Simple, modern UI with **copy button for easy sharing** 🔘  
✅ **Analytics Ready** – Future support for tracking click counts & referrers 📊  
✅ **Responsive Design** – Works on desktop & mobile seamlessly 📱  

---

## **📸 Screenshots**
| **Shorten URL Page** | **Ad Waiting Page with Game** |
|----------------------|-----------------------------|
| ![Shorten](https://tools.licfree.com/link/images/ss1.png) | ![Ads Page](https://tools.licfree.com/link/images/ss2.png) |

---

## **📜 Installation Guide**
Follow these steps to set up your **PHP URL Shortener**:

### **🔹 Step 1: Clone the Repository**
```bash
git clone https://github.com/iammaksudul/URL-Shortener-With-Adsense.git
cd URL-Shortener-With-Adsense
```

### **🔹 Step 2: Set Up Your Database**
1. **Create a MySQL database** from your hosting panel.
2. **Import `database.sql`** (included in the project folder) into your database.
3. **Update `db.php`** with your database credentials:
```php
$servername = "your_database_host";  // Usually 'localhost'
$username = "your_database_username";
$password = "your_database_password";
$dbname = "your_database_name";
$conn = new mysqli($servername, $username, $password, $dbname);
```

### **🔹 Step 3: Configure AdSense for Maximum Earnings**
1. Open `adsense_config.php` in your editor.
2. Replace the existing AdSense script with **your own** AdSense code:
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-4452711820150477"
     crossorigin="anonymous"></script>
```
3. Ensure your **AdSense account is active** and ads are approved.

### **🔹 Step 4: Upload to Hosting Server**
1. **Upload all project files** to your **public_html** or **root directory**.
2. Enable **mod_rewrite** for cleaner short URLs.
3. Set **file permissions correctly** (if needed).

---

## **💰 How the Monetization Works**
This URL shortener is optimized to **earn AdSense revenue** by keeping users engaged **before redirecting them to their final destination.**  

1️⃣ User **enters a long URL** and clicks **Shorten**  
2️⃣ A **short link** is generated  
3️⃣ When the user **clicks the short link**, they land on a **waiting page** where:  
   - **AdSense ads load for high CPC earnings**  
   - A **mini-game keeps them engaged**  
   - A **countdown timer runs** to ensure ads get displayed  
4️⃣ After the countdown, they are **redirected to their destination**  

✅ **This strategy helps maximize revenue by increasing ad impressions and reducing bounce rates.**  

---

## **🎮 Interactive Game (User Engagement)**
To keep users engaged while ads load, we have added a **mini-game**:  
🎯 **Catch the Falling Stars** – Users can play while waiting for redirection, ensuring higher ad visibility.  

🎨 **Want a different game?** You can replace it with any other **HTML5/JavaScript game**.

---

## **🔧 Customization Options**
You can **easily modify** the following:
- **Waiting Page:** Edit `redirect.php` to change the waiting time, text, or animations.
- **Mini-Game:** Modify `game.js` to replace or tweak the existing game.
- **AdSense Optimization:** Test different **ad placements** for higher CPC revenue.
- **Short URL Design:** Customize `styles.css` for a unique look.

---

## **🛠 Upcoming Features**
✅ **Analytics Dashboard** – Track **click counts, referrers, and revenue** 📊  
✅ **Admin Panel** – Manage links, earnings, and user activity 🚀  
✅ **User Accounts** – Let users register & track their shortened links 🔐  
✅ **QR Code Generator** – Users can generate **QR codes** for their links 📱  
✅ **Link Expiry & Password Protection** – Additional security features 🔒  

🚀 **Want a feature?** Open an issue or contribute to the project!  

---

## **🔗 Contribute & Support**
💡 Found a bug? Have a great idea?  
✅ Feel free to **fork this repository** and improve it!  

🔗 **GitHub:** [URL Shortener Repo](https://github.com/iammaksudul/URL-Shortener-With-Adsense)  

If you like this project, **consider giving it a star ⭐ on GitHub!**  

---

## **📜 License**
📄 This project is **open-source** under the **MIT License**.  
**Use, modify, and distribute freely.**  

---

🌟 **Like this project?** Help spread the word by sharing it on social media!  
🚀 **Happy Coding!**  
```

---

## **🔹 What’s Improved in this Version?**
✅ **More Professional & Engaging Look**  
✅ **Clearer Installation Guide**  
✅ **Detailed AdSense Optimization Tips**  
✅ **Game Integration Highlights**  
✅ **Customization Options for Developers**  
✅ **SEO Optimized Structure for GitHub**  

