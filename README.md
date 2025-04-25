[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pooriazohrabii/Pooria-/blob/main/News_Analysis.ipynb)
# تحلیل اخبار

این پروژه با استفاده از زبان پایتون، عناوین اخبار را از یک وب‌سایت خبری جمع‌آوری کرده و آن‌ها را تحلیل می‌کند. هدف پروژه، تمرین کار با داده‌های متنی، تحلیل ساده، مصورسازی و ایجاد یک نمونه‌کار قابل ارائه در گیت‌هاب و رزومه است.

## ویژگی‌ها

- جمع‌آوری داده‌های خبری و ذخیره در فرمت‌های CSV و JSON
- تحلیل فراوانی کلمات در عناوین خبر
- رسم نمودار زمانی بر اساس تاریخ جمع‌آوری خبرها
- مصورسازی داده‌ها با Matplotlib
- قابل اجرا در Google Colab

## اجرای سریع در Google Colab

برای مشاهده و اجرای کامل کدها، فایل [notebook.ipynb](https://github.com/pooriazohrabii/Pooria-/blob/main/notebook.ipynb) را در Google Colab باز کنید.

نمونه‌ای از کد پروژه:

```python
import pandas as pd
df = pd.read_csv('news_data.csv')
df['تاریخ _جمع آوری'] = pd.to_datetime(df['تاریخ _جمع آوری'])
## فایل خروجی تحلیل احساسات

فایل `analyzed_news_data.csv` شامل عناوین اخبار به‌همراه تحلیل احساسات آن‌هاست.  
این فایل پس از اجرای مراحل پیش‌پردازش و تحلیل احساسات با استفاده از پکیج‌های فارسی تولید شده است.

[مشاهده فایل در گیت‌هاب](https://github.com/pooriazohrabii/Pooria-/blob/main/analyzed_news_data.csv)
