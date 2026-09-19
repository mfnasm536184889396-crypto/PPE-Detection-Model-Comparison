# تشخیص تجهیزات حفاظت فردی با ارزیابی و مقایسه معماری‌های نوین یادگیری عمیق

## معرفی پروژه

این پروژه با هدف تشخیص تجهیزات حفاظت فردی کارکنان در محیط‌های کاری و بررسی و مقایسه عملکرد معماری‌های مختلف یادگیری عمیق انجام شده است.

در این پروژه چند معماری نوین تشخیص شیء شامل YOLOv10، YOLOv11، YOLOv12، YOLO-World و RT-DETR مورد بررسی و ارزیابی قرار گرفته‌اند.

## دیتاست

برای آموزش و ارزیابی مدل‌ها از مجموعه‌داده Construction Site Safety استفاده شده است.

این دیتاست شامل ۱۰ کلاس زیر است:

* Hardhat
* Mask
* NO-Hardhat
* NO-Mask
* NO-Safety Vest
* Person
* Safety Cone
* Safety Vest
* machinery
* vehicle

## مدل‌های مورد بررسی

مدل‌های مورد استفاده در این پروژه:

* YOLOv10
* YOLOv11
* YOLOv12
* YOLO-World
* RT-DETR

## معیارهای ارزیابی

عملکرد مدل‌ها با استفاده از معیارهای زیر بررسی و مقایسه می‌شود:

* Precision
* Recall
* mAP@50
* mAP@50:95
* F1-Score
* FPS / Inference Time
* تعداد پارامترها
* FLOPs
* حجم مدل
* زمان آموزش

همچنین Confusion Matrix و Learning Curves برای بررسی نتایج مدل‌ها استفاده شده است.

## ساختار پروژه

```text
PPE-Detection-Model-Comparison/
│
├── README.md
├── requirements.txt
├── data/
├── models/
├── results/
├── notebooks/
├── src/
└── docs/
```

## وضعیت پروژه

این پروژه در حال توسعه و تکمیل است.

## نویسنده

Naser Shahin
