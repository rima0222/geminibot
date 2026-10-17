# ربات ترید هوشمند و خودآموز (AI Real Live Trading Bot)

این یک ربات ترید هوشمند و خودآموز به زبان پایتون است که داده‌های لایو بازار (BTC، TOTAL2 و USDT.D) را دریافت کرده، هم‌بستگی شاخص‌ها را تحلیل می‌کند، پوزیشن‌های لایو مجازی (Paper Trading) باز کرده و تمام اطلاعات را در دیتابیس SQLite و پنل وب نمایش می‌دهد.

---

## 🚀 دستور نصب تک‌خطی (Ubuntu VPS)

برای نصب و اجرای سریع تمام پیش‌نیازها و پروژه روی سرور اوبونتو، این دستور را اجرا کنید:

```bash
git clone [https://github.com/rima0222/geminibot.git](https://github.com/rima0222/geminibot.git) && cd geminibot && pip3 install -r requirements.txt && python3 trading_robot.py
