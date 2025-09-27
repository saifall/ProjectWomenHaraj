

# Women Haraj Project (مشروع حراج نسائي)

<p align="center">
	<img src="frontend/assets/icon.png" alt="Women Haraj Logo" width="120" />
</p>

<p align="center">
	<b>Women Haraj</b> | <b>مشروع حراج نسائي</b>
</p>

<p align="center">
	<i>This project is a marketplace application specifically for women.<br>
	هذا المشروع عبارة عن تطبيق سوق إلكتروني مخصص للنساء.</i>
</p>

---

**آخر تحديث | Last Updated**: 24 سبتمبر 2025 | September 24, 2025  
**الإصدار | Version**: 4.3  
**Node.js**: 18+  
**pnpm**: 8+  
**المطور | Developer**: SAiF

---

---


## 🚀 Features (الميزات)

- تسجيل دخول وتسجيل مستخدمين جدد (Authentication & Registration)
- عرض الإعلانات والبحث عنها (Browse & Search Ads)
- إضافة إعلان جديد (Add New Ad)
- إدارة الإعلانات الخاصة بالمستخدم (Manage My Ads)
- شاشة الملف الشخصي وتعديل البيانات (Profile Management)
- شاشة حول التطبيق (About Screen)
- تصميم متجاوب وواجهة سهلة الاستخدام (Responsive & User-Friendly UI)
- دعم الوضع الليلي (Dark Mode Support)
- تقارير تطوير مفصلة (Development Reports)

---

## Project Structure (هيكلة المشروع)

The project is divided into two main parts:
ينقسم المشروع إلى جزأين رئيسيين:

- **frontend**: Contains the client-side code (React Native + Expo)
		- يحتوي على كود الواجهة الأمامية (React Native + Expo)
- **backend**: Contains the server-side code (currently empty)
		- يحتوي على كود الواجهة الخلفية (حالياً فارغ)

### Frontend Structure (هيكلة الواجهة الأمامية)

```
frontend/
	app.json           # Expo app configuration
	index.ts           # Entry point
	package.json       # Dependencies and scripts
	tsconfig.json      # TypeScript config
	src/
		App.tsx         # Main App component
		api/            # API logic (empty)
		assets/
			fonts/        # Custom fonts (empty)
			images/       # Images (empty)
		components/
			common/
				AboutModal.tsx
				StyledButton.tsx
				StyledInput.tsx
		context/
			AuthContext.tsx
		hooks/          # Custom hooks (empty)
		navigation/
			AppNavigator.tsx
			AuthNavigator.tsx
			MainStackNavigator.tsx
			RootNavigator.tsx
		screens/
			AboutScreen.tsx
			AdDetailsScreen.tsx
			AddPostScreen.tsx
			HomeScreen.tsx
			MyAdsScreen.tsx
			ProfileScreen.tsx
			SearchScreen.tsx
			auth/
				LoginScreen.tsx
				RegisterScreen.tsx
		store/
			authStore.ts
		theme/
			colors.ts
			navigationStyles.ts
			theme.ts
		utils/          # Utilities (empty)
```

### Backend Structure (هيكلة الواجهة الخلفية)

```
backend/
	(empty)
```

### Reports (تقارير التطوير)

All development reports are in the `report-dev/` folder:
جميع تقارير التطوير موجودة في مجلد `report-dev/`:

- stage-1-report.md
- stage-2.5-report.md
- stage-3.1-report.md
- stage-3.2-report.md
- stage-3.3-report.md
- stage-3.4-report.md
- stage-3.5-report.md
- stage-4.1-report.md


---

<div align="center">
  
	© 2025 SAiF. All rights reserved. | جميع الحقوق محفوظة للمطور سيف
  
</div>

## Development Log (سجل التطوير)

### Stage 1: Base Setup & Configuration (مكتمل)
- **1.1: Development Environment Setup:** Initialized a React Native project with Expo and TypeScript. (مكتمل)
- **1.2: Core Libraries Installation:** Installed NativeBase for UI and React Navigation for routing. (مكتمل)
- **1.3: File & Folder Structure:** Created a clean, scalable source code directory structure. (مكتمل)
- **1.4: Basic Theme Setup:** Defined and applied a custom color palette and theme for the app. (مكتمل)
- **1.5: Basic Common Components:** Created reusable Button and Input components. (مكتمل)
- **Documentation:** A detailed report for this stage is available at `report-dev/stage-1-report.md`.