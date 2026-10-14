<img width="2940" height="1912" alt="2454122C-C733-46B5-A9AF-4965174E020F" src="https://github.com/user-attachments/assets/4a6ac5b7-2411-4b5e-b9c5-1cbe6bd850ca" />
<img width="2940" height="1912" alt="8D7AB713-B7A0-4E57-8E69-B5E0FA9C7D88" src="https://github.com/user-attachments/assets/53414543-d374-46e1-875e-f3eee4b5edd3" />
<img width="2940" height="1912" alt="1B3510F6-55C4-4D8E-A395-E25C6C75F9FA" src="https://github.com/user-attachments/assets/0748f66f-dbdc-4818-a99a-64551cc90979" />
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
