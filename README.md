# WordPress Restaurant Website

This is a **WordPress restaurant website** built using **Elementor** and **Astra Child Theme**. Fully responsive and mobile-friendly.

---

## Project Contents

- **wp-content/themes/your-child-theme/**  
  Contains the custom Astra child theme with all your customizations.

- **Plugins (separate zip files)**  
  - **Elementor**  
  - **WPForms**  
  - **Elementor Header & Footer**  
  Upload these plugins via WordPress dashboard before using the theme.

- **wp-config.php**  
  WordPress configuration file. Replace database credentials (`DB_NAME`, `DB_USER`, `DB_PASSWORD`, `DB_HOST`) before use.

- **database.sql**  
  Exported database file containing website content.

---

## Usage Instructions

1. Upload the child theme to `wp-content/themes/`.
2. Upload and activate each plugin via WordPress dashboard.
3. Import `database.sql` into your MySQL database.
4. Update `wp-config.php` with your database credentials.
5. Install WordPress core separately if not already installed.
6. Activate the child theme from WordPress dashboard.

---

## Notes

- Only the **custom theme** and selected plugins are included; WordPress core files are not part of this repository.
- Make sure to replace database credentials in `wp-config.php` before running the website.
