🏢 سیستم درخواست خرید سازمانی | Organizational Purchase Requisition System

یک سامانه تحت وب امن و کارآمد برای مکانیزه کردن و بهینه‌سازی فرآیندهای ثبت و تایید درخواست خرید در سازمان‌ها.

<br>

🇮🇷 نسخه فارسی
📝 خلاصه
سامانه جامع درخواست خرید، جایگزینی مدرن برای فرآیندهای دستی و کاغذی است که با هدف افزایش شفافیت، کنترل و کارایی در چرخه تدارکات سازمان طراحی شده است. این سیستم یک گردش کار چندسطحی برای تایید درخواست‌ها فراهم کرده و با کنترل دسترسی دقیق، امنیت فرآیند را تضمین می‌کند.

✨ ویژگی‌های کلیدی
گردش کار تایید چندسطحی: پیاده‌سازی یک Workflow کاملاً انعطاف‌پذیر برای مدیریت فرآیند تایید درخواست‌ها توسط نقش‌های مختلف سازمانی (مانند مدیر بخش، مدیر مالی و تدارکات).

کنترل دسترسی مبتنی بر نقش (RBAC): سیستم مجوزدهی دقیق که مشخص می‌کند هر کاربر چه اقداماتی را می‌تواند انجام دهد و به چه داده‌هایی دسترسی دارد.

ثبت و پیگیری درخواست‌ها: امکان ثبت درخواست‌های خرید با جزئیات کامل و افزودن اقلام متعدد به صورت داینامیک، و قابلیت پیگیری وضعیت لحظه‌ای آن‌ها.

سیستم اعلان‌رسانی: آگاه‌سازی کاربران مسئول از طریق نوتیفیکیشن‌های درون‌برنامه‌ای هنگام ثبت یا تغییر وضعیت یک درخواست.

تاریخچه کامل اقدامات (Audit Trail): ثبت و نمایش تمام وقایع، تغییرات و تاییدهای مربوط به هر درخواست برای شفافیت کامل.

اقدامات شرطی و هوشمند: نمایش دکمه‌ها و گزینه‌ها (مانند تایید، رد، ویرایش، لغو) بر اساس نقش کاربر، وضعیت فعلی درخواست و مجوزهای تخصیص‌داده‌شده.

🖼️ تصاویری از پروژه
(نکته: مطمئن شوید نام فایل‌های عکس شما در پوشه images دقیقاً مانند آدرس‌های src زیر باشد.)

صفحه ورود	داشبورد اصلی	صفحه ثبت درخواست
<img src="./images/1-login-page.png" alt="Login Page" width="250"/>	<img src="./images/2-dashboard.png" alt="Dashboard" width="250"/>	<img src="./images/3-new-request-form.png" alt="New Request Page" width="250"/>

Export to Sheets
جزئیات درخواست	تاریخچه اقدامات
<img src="./images/4-request-details.png" alt="Request Details" width="250"/>	<img src="./images/5-action-history.png" alt="Action History" width="250"/>

Export to Sheets
🚀 فناوری‌های استفاده شده
بخش	تکنولوژی
Backend	
Frontend	
Authentication	


🔒 جنبه‌های فنی و امنیتی برجسته
موتور Workflow مبتنی بر وضعیت: طراحی و پیاده‌سازی یک موتور گردش کار قدرتمند برای مدیریت منطق پیچیده تاییدها و انتقال بین وضعیت‌های مختلف.

سیستم RBAC قدرتمند: استفاده از دکوراتورهای سفارشی در فلسک برای کنترل دسترسی دقیق و ریزدانه در سطح مسیرها (routes) و داده‌ها.

فرم‌های داینامیک: مدیریت آسان اقلام درخواست خرید (افزودن/حذف) در فرانت‌اند با استفاده از جاوااسکریپت.

امنیت: تمرکز ویژه بر احراز هویت (Authentication)، کنترل دسترسی (Authorization) و محافظت در برابر حملات CSRF.

<br>


🇬🇧 English Version
📝 Summary
This comprehensive Purchase Requisition System is a modern replacement for manual, paper-based processes. It is designed to enhance transparency, control, and efficiency within the organization's procurement cycle. The system provides a multi-level approval workflow and ensures process security through granular access control.

✨ Key Features
Multi-Level Approval Workflow: Implements a flexible workflow to manage the approval process of requisitions by various organizational roles (e.g., Department Manager, Finance, Procurement).

Role-Based Access Control (RBAC): A granular authorization system that defines what actions each user can perform and what data they can access.

Requisition Submission & Tracking: Allows users to submit detailed purchase requisitions with multiple items dynamically and track their real-time status.

Notification System: In-app notifications to alert relevant users of status changes or new submissions requiring their action.

Complete Audit Trail: Logs and displays the full history of all events, changes, and approvals for each requisition, ensuring full transparency.

Conditional & Smart Actions: Dynamically displays action buttons and options (e.g., Approve, Reject, Edit, Cancel) based on the user's role, the request's current status, and assigned permissions.

🖼️ Project Screenshots
(Note: Ensure your image filenames in the images folder match the src paths below.)

Login Page	Main Dashboard	New Request Form
<img src="./images/1-login-page.png" alt="Login Page" width="250"/>	<img src="./images/2-dashboard.png" alt="Dashboard" width="250"/>	<img src="./images/3-new-request-form.png" alt="New Request Page" width="250"/>


Request Details	Action History / Audit Trail
<img src="./images/4-request-details.png" alt="Request Details" width="250"/>	<img src="./images/5-action-history.png" alt="Action History" width="250"/>



🚀 Technology Stack
Area	Technology
Backend	
Frontend	
Authentication	

Export to Sheets
🔒 Technical & Security Highlights
State-Based Workflow Engine: A custom-built, robust workflow engine to manage the complex logic of approvals and state transitions.

Granular RBAC System: Utilizes custom decorators in Flask to enforce fine-grained access control at the route and data levels.

Dynamic Forms: Seamless management of requisition items (add/remove) on the front-end using JavaScript.

Security: A strong focus on Authentication, Authorization, and CSRF Protection.
