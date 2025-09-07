# Teeshirtate Store

Next.js (App Router) + Tailwind v4 + Supabase. جاهز للنشر على Bolt (v0.app).

## الإعداد محليًا
1. انسخ `.env.example` إلى `.env.local` واملأ القيم (`NEXT_PUBLIC_SUPABASE_URL`, `NEXT_PUBLIC_SUPABASE_ANON_KEY`, `SUPABASE_URL`, `SUPABASE_SERVICE_ROLE_KEY` إذا لزم).
2. ثبّت الحِزم: `npm i`
3. شغّل التطوير: `npm run dev`

## البناء والتشغيل للإنتاج
- `npm run build`
- `npm run start`

## النشر على Bolt
- ارفع المشروع من GitHub.
- أضف نفس متغيرات البيئة في Project → Settings → Environment (Preview + Production).
- اعمل Deploy.

> Tailwind v4 مستخدم عبر `@import "tailwindcss";` في `app/globals.css` ولا يحتاج إعداد إضافي.
