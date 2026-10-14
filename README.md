# PHP Project

A simple signup form project built with HTML and PHP. The user fills in the signup form, and the data is processed by `submit.php`.

## Files
- `signup.html` - signup form (frontend)
- `submit.php` - receives and processes the form data (backend)

## Requirements
- Apache (httpd)
- PHP 8.x
- MariaDB / MySQL (if the data is saved to a database)

## Installation
```bash
git clone https://github.com/Vishal32-stack/php_project.git
sudo cp php_project/* /var/www/html/
```

## Usage
1. Start Apache:
```bash
   sudo systemctl start httpd
```
2. Open in your browser: `http://your-server-ip/signup.html`
3. Fill in the form and submit it.

## Output
After submitting, the result from `submit.php` is shown on the page.

## Author
Vishal
