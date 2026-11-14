# ZenX School ERP — Production-Ready Multi-Tenant SaaS

Aapka complete **ZenX School ERP** full-stack project ready hai! Isme Public SaaS Website (₹8 & ₹12 pricing), Multi-Role Login (Super Admin, School Admin, Teacher, Student/Parent), Printable School Documents (Fee Receipt, ID Card, TC, Marksheet), aur PostgreSQL Database Schema shamil hain.

---

## Step-by-Step Live Publish Guide (10 Minutes Mein Live Karein)

### Step 1: Supabase Database Setup (Free)
1. [supabase.com](https://supabase.com) par jakar free account banayein aur **New Project** create karein.
2. Left sidebar mein **SQL Editor** kholein, is folder ke andar di gayi `supabase/supabase_schema.sql` file ka poora code paste karke **Run** karein. Isse saari tables aur security policies automatically ban jayengi.
3. **Project Settings -> API** mein jakar apna **Project URL** aur **anon public key** copy kar lein.

### Step 2: Project Run & Configure Karein
1. Apne computer mein Node.js install rakhein aur terminal mein is folder ko kholein:
   ```bash
   npm install
   ```
2. `.env.example` file ko rename karke `.env` banayein aur usme apni Supabase keys dalein:
   ```env
   VITE_SUPABASE_URL=https://aapka-project.supabase.co
   VITE_SUPABASE_ANON_KEY=aapki-anon-key
   ```
3. Local test karne ke liye chalayein:
   ```bash
   npm run dev
   ```

### Step 3: Vercel / Netlify par Free Live Publish Karein
1. Is project folder ko GitHub par upload karein.
2. [vercel.com](https://vercel.com) par jakar apna GitHub repo import karein.
3. Vercel ke **Environment Variables** mein `VITE_SUPABASE_URL` aur `VITE_SUPABASE_ANON_KEY` add karein aur **Deploy** par click karein.
4. Deploy hone ke baad Vercel Settings -> Domains mein jakar apna custom domain (jaise `zenxerp.in`) connect kar lein.

---
**Support & Contact Configured in App:**
- Phone: +91 7060443995 / +91 9760443995
- Email: ipandatprashant@gmail.com
