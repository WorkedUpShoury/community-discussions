## ✅ Milestone 1 – Jul 15 to Jul 17, 2025 (First Commit – 3-Day Setup Sprint)

🎯 **Goal**: Ship a functional foundation:
- Project setup (frontend, backend, db)
- One working `/internships` page with dummy data
- Docs initialized
- Design references ready
- Basic style guide + deploy scaffold

---

### 🏗️ Project Setup & Structure

- [ ] **Jayant**: Create the frontend app with Next.js + TypeScript + Tailwind CSS  
  - Add base layout (`layout.tsx`), `_app.tsx`, and `/internships` route  
- [ ] **Shoury**: Initialize backend API structure in `pages/api/` (or Express if external)  
  - Add a sample GET endpoint at `/api/internships` with mock JSON  

- [ ] **Aayush**: Set up Prisma + PostgreSQL schema for internship resources  
  - Add seed script with 3 sample entries  
  - Run and test `prisma generate` & `prisma migrate dev`  

---

### 🧱 UI & Page Implementation

- [ ] **Utkarsh**: Build `/internships` page with a resource list using mock data  
  - Style cards using Tailwind  
  - Fetch from static JSON or Shoury’s endpoint  

- [ ] **Manoj**: Create basic layout with navbar + footer using shadcn/ui  
  - Design in Figma and implement with Tailwind  

---

### 📚 Data & Content Prep

- [ ] **Pankaj**: Collect and write short descriptions for 5–10 internship platforms  
- [ ] **Kayum**: Create a `data/internships.json` file with sample structure and tags  
  - Format: `{ name, url, tags, description }`  

- [ ] **Akash**: Assist Aayush in syncing mock JSON with database seed format  

---

### 🧾 Docs & Developer Essentials

- [ ] **Abhiran**: Draft the UVP and MVP in `docs/UVP.md` and `docs/MVP.md`  
- [ ] **Tushar**: Create `README.md` with install/run instructions + tech stack list  
- [ ] **Asad**: Add ESLint + Prettier + pnpm setup with base config  
- [ ] **Atindra**: Write initial `SITEMAP.md` + update team task table in docs  

---

### 🌐 Deployment (Optional if ready)

- [ ] **Vishal**: Set up Clerk and test with a simple “login” button (placeholder UI)  
- [ ] **Abhijeet**: Deploy to Vercel from GitHub main branch and confirm it's live  

---

## 🏁 Deliverables by Day 3:
- `/internships` page rendering real/fake data via component
- Live demo or local run-ready code
- Committed docs: MVP, UVP, SITEMAP
- Linting, formatting, and base project scaffold complete

---

## 📝 Commit Naming Standard
