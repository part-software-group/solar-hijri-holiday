مقدمه
====

لیست تطیلات رسمی تقویم شمسی به همراه توضیح مناسبت هرروز


این لیست از تاریخ `13000101` تا `14101229` می‌باشد


ساختار
=====

نام جدول: `events`

| Column         | Type    | Description                  |
| -------------- |:-------:| ----------------------------:|
| date           | int     | تاریخ شمسی به فرمت `YYYYMMDD  |
| holiday        | boolean | پرچم برای تعطیلی رسمی در تقویم  |
| sh_holiday     | boolean | پرچم برای تعطیلی در تاریخ شمسی  |
| sh_description | text    | توضیحات برای تاریخ شمسی        |
| ic_holiday     | boolean | پرچم برای تعطیلی در تاریخ قمری    |
| ic_description | text    | توضیحات برای تاریخ قمری         |
| wc_holiday     | boolean | پرچم برای تعطیلی در تاریخ میلادی   |
| wc_description | text    | توضیحات برای تاریخ میلادی         |

* هجری شمسی (SH = Solar Hijri Calendar)
* هجری قمری (IC = Islamic Calendar)
* میلادی (WC = World Calendar)