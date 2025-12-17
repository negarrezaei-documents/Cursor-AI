
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


 ----

 ## 🧠 Prompt
 
1. Feature Development Prompt
  
  ```ts
You are a Senior Angular Developer working on a Cloud Infrastructure Management Panel (PishgamRayan Cloud Panel). 

Project Context:
- Angular 20 with TypeScript strict mode
- State management: Angular Signals (mandatory, prefer Signals over RxJS)
- Styling: Tailwind CSS only (no prefix, no inline styles)
- Architecture: Thin Components pattern - components are UI-only, all business logic in Services
- Use @if/@for instead of *ngIf/*ngFor
- Default ChangeDetectionStrategy: OnPush
- Never use detectChanges in lifecycle hooks

Task: [Describe your feature here]

Requirements:
1. Follow the existing project structure (core/, pages/, shared/)
2. Extend appropriate base classes (BaseComponent, BasePageComponent, BaseIndexPageComponent, etc.)
3. Use signal inputs/outputs for component communication
4. Place business logic in services (core/services/ or feature-specific services)
5. Use the auto-generated API services from core/api/services/
6. Follow Clean Code principles (single responsibility, DRY, clear naming)
7. Ensure ESLint passes with zero errors
8. Use Tailwind CSS for all styling

Please:
- Analyze the existing codebase patterns before implementing
- Ask for clarification if requirements are ambiguous
- Generate production-ready code following Angular 20 best practices
  ```

2. Refactoring Prompt

```ts
Refactor the following code in this Angular 20 Cloud Panel project to follow modern Angular patterns:

[Paste code here]

Project Rules:
- Convert @Input() to signal inputs using input<T>()
- Convert @Output() to signal outputs using output<T>()
- Replace RxJS state management with Angular Signals where appropriate
- Move business logic from components to services
- Use @if/@for instead of *ngIf/*ngFor in templates
- Ensure ChangeDetectionStrategy.OnPush
- Use Tailwind CSS classes only
- Follow the existing base class inheritance pattern (BaseComponent → BasePageComponent → specific base classes)

Please:
1. Identify all violations of project rules
2. Refactor step by step with explanations
3. Ensure backward compatibility where needed
4. Update all related files (component, template, service)
5. Verify ESLint compliance
```

3. Bug Fixing Prompt
   
```ts
Debug and fix the following issue in this Angular 20 Cloud Panel application:

[Describe the bug/error]

Project Architecture:
- Angular 20, TypeScript strict
- Signals for state management
- Thin Components (UI only), business logic in Services
- Base classes: BaseComponent, BasePageComponent, BaseIndexPageComponent, BaseFormPageComponent, BaseDetailsPageComponent
- API layer: Auto-generated services in core/api/services/
- State: AppStateService (core/services/state.service.ts) uses Signals
- Routing: Claim-based guards (CheckClaimGuard)

Please:
1. Analyze the error/issue in context of the project architecture
2. Check related base classes and services
3. Verify signal usage and reactivity
4. Ensure proper error handling
5. Test the fix doesn't break existing functionality
6. Follow project coding standards
```

4. Component Creation Prompt

 ```ts
Create a new [component type: index/form/details] component for [feature name] in this Angular 20 Cloud Panel project.

Project Structure:
- Components extend: BaseComponent → BasePageComponent → [BaseIndexPageComponent/BaseFormPageComponent/BaseDetailsPageComponent]
- Location: src/app/pages/[feature-name]/
- Services: src/app/core/services/ or feature-specific services
- Shared components: src/app/shared/components/
- API: Use auto-generated services from core/api/services/

Requirements:
1. Extend the appropriate base class
2. Use signal inputs/outputs: input<T>() and output<T>()
3. Place business logic in a service (create if needed)
4. Use Tailwind CSS for styling
5. Implement proper error handling
6. Use @if/@for in template
7. Set ChangeDetectionStrategy.OnPush
8. Follow existing naming conventions
9. Add proper TypeScript types (no 'any')
10. Ensure ESLint compliance

Please provide:
- Component class file
- Template file with Tailwind styling
- Service file (if new service needed)
- Route configuration (if needed)
- Any necessary guards or resolvers
 ```


5. Signal Migration Prompt
 ```ts
Convert the following component/service to use Angular Signals instead of RxJS for state management:

[Paste code here]

Migration Rules:
1. Replace BehaviorSubject/Subject with signal()
2. Replace @Input() with input<T>()
3. Replace @Output() with output<T>()
4. Replace Observable subscriptions with computed() or effect()
5. Use signal.update() for derived state
6. Keep RxJS only for HTTP requests and async operations
7. Update template to use signal() syntax: signalName() instead of signalName
8. Ensure ChangeDetectionStrategy.OnPush
9. Remove unnecessary RxJS imports

Please:
- Show before/after comparison
- Explain signal reactivity flow
- Update all related templates
- Ensure no breaking changes
- Verify ESLint compliance
 ```
6. API Integration Prompt
   
```ts
Integrate a new API endpoint into this Angular 20 Cloud Panel application.

Project API Structure:
- Auto-generated API services: core/api/services/ (generated via ng-openapi-gen)
- Base service pattern: All services extend BaseService
- API configuration: core/api/api-configuration.ts
- HTTP interceptors: core/interceptors/ (token, language, permission, etc.)

Task: [Describe the API integration needed]

Requirements:
1. Use existing auto-generated services if available
2. If new endpoint needed, describe the OpenAPI spec changes required
3. Create service methods following existing patterns
4. Use Signals for state management (not RxJS Subjects)
5. Implement proper error handling using ResponseService
6. Add loading states using AppStateService signals
7. Follow existing API call patterns (basePipeOperators, etc.)
8. Update TypeScript models if needed

Please:
- Identify the appropriate service to extend/use
- Show service method implementation
- Show component usage with Signals
- Handle loading/error states
- Follow existing error handling patterns

```

7. Performance Optimization Prompt
   
```ts
Optimize the following code/component for performance in this Angular 20 Cloud Panel:

[Paste code or describe component]

Optimization Goals:
- Reduce unnecessary change detection cycles
- Improve signal reactivity
- Optimize template rendering
- Reduce bundle size
- Improve lazy loading

Project Constraints:
- Must use ChangeDetectionStrategy.OnPush
- Signals for state (not RxJS for state)
- Tailwind CSS only
- No inline styles
- Follow existing architecture patterns

Please:
1. Identify performance bottlenecks
2. Suggest optimizations with explanations
3. Use OnPush change detection
4. Optimize signal usage (computed, effect)
5. Lazy load heavy components
6. Optimize template bindings
7. Ensure no breaking changes
```

8. Code Review Prompt
   
```ts
Review the following code changes for this Angular 20 Cloud Panel project:

[Paste code or describe changes]

Review Checklist:
- ✅ Follows Angular 20 best practices
- ✅ Uses Signals (not RxJS for state)
- ✅ Thin Components pattern (business logic in services)
- ✅ Uses @if/@for (not *ngIf/*ngFor)
- ✅ ChangeDetectionStrategy.OnPush
- ✅ Tailwind CSS only (no inline styles)
- ✅ Proper TypeScript types (no 'any')
- ✅ ESLint compliance
- ✅ Follows existing project structure
- ✅ Proper error handling
- ✅ Security considerations (claim-based access)

Please:
1. Identify all issues and violations
2. Suggest improvements
3. Check for security concerns
4. Verify consistency with existing codebase
5. Provide specific code fixes
```

9. Testing Prompt

```ts
Write comprehensive tests for [component/service name] in this Angular 20 Cloud Panel project.

Component/Service: [Paste code here]

Testing Requirements:
- Unit tests for component logic
- Service tests with mocked dependencies
- Signal reactivity testing
- Template rendering tests
- Error handling tests
- Edge case coverage

Project Context:
- Angular 20 with Jest/Karma
- Signals-based state management
- Thin Components (test services separately)
- Mock API services from core/api/services/
- Test base class behavior

Please provide:
- Component test file
- Service test file (if applicable)
- Mock implementations
- Test coverage for signals
- Edge case scenarios
```

10. Architecture Analysis Prompt

```ts
Analyze the architecture of this Angular 20 Cloud Panel project and provide recommendations.

Current Architecture:
- Layered: Presentation (pages) → Shared Components → Core (services/API) → Infrastructure
- Base class inheritance: BaseComponent → BasePageComponent → specific base classes
- State: AppStateService with Signals
- API: Auto-generated OpenAPI services
- Routing: Claim-based guards

Focus Areas:
[Specify: performance, scalability, maintainability, etc.]

Please:
1. Analyze current architecture patterns
2. Identify strengths and weaknesses
3. Suggest improvements aligned with Angular 20 best practices
4. Consider migration to standalone components
5. Evaluate signal usage patterns
6. Review service organization
7. Provide actionable recommendations
```
