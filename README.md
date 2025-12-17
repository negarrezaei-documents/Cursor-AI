
# Cursor AI + Angular 🚀

راهنمای جامع استفاده حرفه‌ای از **Cursor AI** در پروژه‌های **Angular**

---

<h2 dir="rtl">Cursor AI چیست؟</h2>

<div dir="rtl">Cursor یک ویرایشگر کد مبتنی بر هوش مصنوعی است که روی هسته VS Code ساخته شده اما AI را به‌صورت عمیق درکد، ساختار پروژه و Context قرار می‌دهد.</div>

برخلاف ابزارهایی مثل Copilot که بیشتر autocomplete هستند، Cursor نقش یک **هم‌تیمی Senior** را دارد که کل پروژه را می‌فهمد.

---

## چرا Cursor برای Angular عالی است؟

* درک Component / Service / Pipe / Directive
* فهم Dependency Injection
* پشتیبانی از RxJS و Angular Signals
* Refactor هوشمند بدون شکستن پروژه
* تولید Unit Test استاندارد

---

<h2 dir="rtl"> Workflow حرفه‌ای استفاده از Cursor در Angular </h2>

### 1️⃣ فهم پروژه (Project Understanding)

اولین قدم بعد از باز کردن پروژه:

**Prompt پیشنهادی:**

```
Analyze this Angular project structure and explain its architecture
```

نتیجه:

* ساختار کلی پروژه
* نقش ماژول‌ها یا standalone componentها
* الگوی معماری (Smart/Dumb, Feature-based, ...)

---

### 2️⃣ فهم Component یا Service قدیمی

قبل از تغییر کد:

```
Explain this Angular component, its responsibilities and dependencies
```

یا:

```
Explain how this service is used across the project
```

---

### 3️⃣ Refactor امن و مرحله‌ای

#### مثال‌ها:

**تبدیل به OnPush:**

```
Refactor this component to use OnPush change detection
```

**کوچک‌سازی کامپوننت بزرگ:**

```
Split this large Angular component into smaller reusable components
```

**تبدیل RxJS به Signals:**

```
Refactor this RxJS logic to Angular signals
```

---

### 4️⃣ تولید Feature جدید

```
Create a standalone Angular component for a reusable modal with inputs and outputs
```

```
Generate an Angular Pipe to format numbers with Persian separators
```

Cursor فایل‌ها، decoratorها و typeها را درست ایجاد می‌کند.

---

### 5️⃣ Unit Test نویسی حرفه‌ای

```
Write unit tests for this Angular component using TestBed
```

```
Add unit tests for this service and mock HttpClient
```

ویژگی‌ها:

* Mock استاندارد
* تست edge case
* خوانایی بالا

---

### 6️⃣ دیباگ و بهینه‌سازی

```
Find potential memory leaks in this Angular component and fix them
```

```
Improve performance of this table component
```

---

<h2 dir="rtl">Promptهای آماده مخصوص Angular 🧠 </h2>

### 🔹 Component

```
Explain this Angular component and suggest improvements
```

```
Refactor this component for better readability and maintainability
```

---

### 🔹 Service

```
Extract this logic into a reusable Angular service
```

```
Refactor this service to follow best practices
```

---

### 🔹 Pipe

```
Create a pure Angular Pipe for formatting numeric values
```

---

### 🔹 Refactor کلی

```
Rename variables and methods in this file with better semantic names
```

---

### 🔹 Architecture

```
Review this Angular feature and suggest architectural improvements
```

---

## Cursor vs Copilot (خلاصه)

| ویژگی                 | Cursor | Copilot |
| --------------------- | ------ | ------- |
| فهم کل پروژه          | ✅      | ❌       |
| Refactor واقعی        | ✅      | ❌       |
| Chat مبتنی بر Context | ✅      | محدود   |
| Unit Test حرفه‌ای     | ✅      | متوسط   |

---

## Best Practices ⭐

* پرامپت دقیق بنویس
* تغییرات بزرگ را مرحله‌ای انجام بده
* همیشه خروجی را Review کن
* Cursor را جایگزین فکر نکن، تقویت‌کننده بدان

---

## مناسب چه کسانی است؟

* Front-end Developer
* Angular Developer (Mid / Senior)
* پروژه‌های بزرگ و Legacy
* Refactor و توسعه Feature جدید

---

## مراحل نصب Cursor (ویندوز):

## 1️⃣ دانلود Cursor

برو به سایت رسمی:

🔗 https://cursor.sh

سپس روی دکمه **Download for Windows** کلیک کن.

## 2️⃣ نصب برنامه

## 3️⃣ اولین اجرا

وقتی Cursor باز می‌شه:

- محیطش دقیقاً شبیه **VS Code** هست
- اگه قبلاً VS Code داشتی، خیلی سریع باهاش عادت می‌کنی

---

## 4️⃣ لاگین کردن (خیلی مهم)

برای استفاده از قابلیت‌های **AI** باید لاگین کنی:

- بالای صفحه یا سمت راست → **Sign in**
- لاگین با یکی از این گزینه‌ها:
  - GitHub
  - Google

بعد از لاگین، هوش مصنوعی Cursor فعال می‌شه 🤖✨
وقتی هم که این قسمت رسیدین با زدن این دکمه همه تنظیمات vs code  که داشتین میاد این سمت
<img width="954" height="521" alt="image" src="https://github.com/user-attachments/assets/32680c5a-63bb-4adb-8437-bd9253531fc5" />



## 5️⃣ باز کردن پروژه (Angular یا هر پروژه دیگه)

برای باز کردن پروژه:
<div dir="rtl">
- از منو:
</br>
  - File → Open Folder
  </br>
- فولدر پروژه رو انتخاب کن
  </br>
  </br>
بعد از این کار:
</br>
- Cursor کل پروژه رو می‌خونه
</br>
- Context کامل از کدها می‌گیره
</div>
</br>
</br>



🔹 **اینجاست که Cursor از VS Code قوی‌تر می‌شه**
<div dir="rtl">به صورت پیش فرض Activity Bar به صورت این صورت</div>

<img width="442" height="661" alt="image" src="https://github.com/user-attachments/assets/70e81e8d-d1e5-4c71-9d99-6e672c1c3c42" />

برای تغییر و تنظیمش مثل  vs code باید مراحل زیر انجام بدین : 
## 1️⃣ باز کردن Settings

- برای باز کردن تنظیمات:
```ts
  Ctrl + ,

 ```

## 2️⃣ جستجو در تنظیمات

- داخل قسمت Search بنویس:
```ts
  Activity Bar
 ```


<img width="1406" height="714" alt="image" src="https://github.com/user-attachments/assets/04ece62c-2a0b-4996-9054-d06d1756da9e" />

