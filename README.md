# وب‌سایت تعاونی مسکن نخبگان استان تهران

قالب کامل MkDocs با پوسته Material، محتوای فارسی، راست‌به‌چپ، دو پوسته روشن و تیره و هویت بصری اختصاصی.

## اجرای محلی

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# Linux/macOS: source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

سپس نشانی `http://127.0.0.1:8000` را باز کنید.

## ساخت نسخه انتشار

```bash
mkdocs build --strict
```

خروجی در پوشه `site/` ایجاد می‌شود.

## نکات مهم

- تمام اسامی اشخاص، شماره‌ها، نشانی‌ها، پروژه‌ها و آمارهای این بسته **نمونه** هستند و باید پیش از انتشار جایگزین شوند.
- فونت رابط با خانواده `Vazirmatn / Vazir` تنظیم شده و از Google Fonts بارگذاری می‌شود؛ فایل فونت در بسته قرار ندارد.
- برای GitHub Pages، فایل workflow در `.github/workflows/deploy.yml` آماده است.
- فایل `docs/assets/images/logo-emblem.png` نمونه تصویری لوگو و `logo.svg` نسخه سبک و مناسب هدر سایت است.
