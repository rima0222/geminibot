# AI Self-Learning Real Live Trading Bot

ربات خودآموز ترید هوشمند با قابلیت دریافت داده لایو از API بایننس، تحلیل هم‌بستگی شاخص‌ها، ذخیره دیتابیس SQLite، پنل وب امن و اطلاع‌رسانی تلگرام.

## نصب و اجرا روی Ubuntu VPS

```bash
# ۱. به‌روزرسانی و نصب Git و Python
sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git screen -y

# ۲. کلون پروژه و نصب پکیج‌ها
git clone [https://github.com/USERNAME/auto-trading-bot.git](https://github.com/USERNAME/auto-trading-bot.git)
cd auto-trading-bot
pip3 install -r requirements.txt

# ۳. باز کردن پورت پنل وب
sudo ufw allow 8000/tcp

# ۴. اجرای ربات در محیط دائمی (Screen)
screen -S trading_bot
python3 trading_robot.py
