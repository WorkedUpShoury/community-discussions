# Tech Stack

| Layer                   | Teams             | Recommended Stack                               | Notes                                                       |
| ----------------------- | ----------------- | ----------------------------------------------- | ----------------------------------------------------------- |
| **1. Frontend**         | Manoj, Shoury     | Next.js + TypeScript + Tailwind CSS + shadcn/ui | Simple, fast, scalable; modern UI + DX                      |
| **2. Backend**          | Akash, Shoury     | Next.js API Routes or Express.js                | Lightweight serverless or minimal backend as needed         |
| **3. Database**         | Pankaj, Kayum     | PostgreSQL + Prisma ORM                         | Type-safe, fast dev cycle, reliable relational DB           |
| **4. Authentication**   | Vishal, Jayant    | Clerk or Supabase Auth                          | Easy integration; full auth suite out of the box            |
| **5. Hosting & Deploy** | Tushar,  Atindra, | Vercel or Render                                | CI/CD built-in, fast global edge deployments                |
| **6. Dev Tools**        | Asad, Abhiran     | pnpm, ESLint, Prettier, GitHub Actions, Vitest  | Developer productivity + clean code maintained effortlessly |

---
# Resources

⚠️ **Must-Watch for Everyone**  
> ✅ [English: Web Dev basics Full Course](https://youtu.be/zJSY8tbf_ys?si=BxwRxK_6BDVPO4we)  
> or
> ✅ [Hindi: Web Dev basics Full Course ](https://youtube.com/playlist?list=PLfqMhTWNBTe0PY9xunOzsP5kmYIz2Hu7i&si=Yl933sUFg9Y7fLcr)

| **Member**           | **Tools**                                      | **Resources**                                                                                                                                                                                                                                                                                                                                               |
| -------------------- | ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Manoj**            | Tailwind, shadcn/ui                            | Tailwind: [YouTube](https://youtu.be/_9mTJ84uL1Q?si=S6z2LuozRDmoanIu) shadcn/ui: [YouTube](https://youtu.be/O4AjymzpIEg?si=NXvCM5V-7qPGV-Fa)                                                                                                                                                                                                                |
| **Jayant**           | Next.js + TypeScript                           | Next.js: [YouTube](https://youtu.be/ZVnjOPwW4ZA?si=vBPyNNGDw5BbMjvt) TypeScript: [YouTube](https://youtu.be/30LWjhZzg50?si=eTQX5eTkvB3XDq35)                                                                                                                                                                                                                |
| **Shoury**           | Next.js + TypeScript, Next.js API Routes       | Same as Jayant + Backend playlist: [YouTube](https://youtube.com/playlist?list=PLC3y8-rFHvwhIEc4I4YsRz5C7GOBnxSJY&si=Tm7LQQ1FpLTBp4gB)                                                                                                                                                                                                                      |
| **Akash**            | Next.js API Routes                             | Backend playlist: [YouTube](https://youtube.com/playlist?list=PLC3y8-rFHvwhIEc4I4YsRz5C7GOBnxSJY&si=Tm7LQQ1FpLTBp4gB)                                                                                                                                                                                                                                       |
| **Pankaj**           | PostgreSQL + Prisma ORM, Data Ops              | PostgreSQL: [YouTube](https://youtu.be/cnzka7kF5Zk?si=NiA535NDzvQPzUtl) Prisma ORM: [YouTube](https://youtu.be/-_nz4q_Cyr4?si=_EWLUsYjRLrxwKVh) Data Ops: [Playlist](https://youtube.com/playlist?list=PLmHi7ol7EPSD9IuLtelWwnUinCxXh7HhG&si=pbhBKvg3H3jQbbaX)                                                                                              |
| **Kayum**            | Data Ops                                       | Data Ops: [Playlist](https://youtube.com/playlist?list=PLmHi7ol7EPSD9IuLtelWwnUinCxXh7HhG&si=pbhBKvg3H3jQbbaX)                                                                                                                                                                                                                                              |
| **Abhiran**          | Data Ops, Vercel                               | Data Ops: [Playlist](https://youtube.com/playlist?list=PLmHi7ol7EPSD9IuLtelWwnUinCxXh7HhG&si=pbhBKvg3H3jQbbaX) Vercel: [YouTube](https://youtu.be/sPmat30SE4k?si=CSoXXraQy08WTvxy)                                                                                                                                                                          |
| **Vishal, Abhijeet** | Clerk                                          | Clerk 1: [YouTube](https://youtu.be/MzbgCh5L6Cc?si=Pg51sz8Eajtsfq1C) Clerk 2: [YouTube](https://youtu.be/FQCTzomz6bw?si=lN_xLmqxaAo4bSMD)                                                                                                                                                                                                                   |
| **Tushar**           | Vercel                                         | Vercel: [YouTube](https://youtu.be/sPmat30SE4k?si=CSoXXraQy08WTvxy)                                                                                                                                                                                                                                                                                         |
| **Asad, Atindra**    | pnpm, ESLint, Prettier, Vitest, GitHub Actions | pnpm: [YouTube](https://youtu.be/MvbReZDSKHI?si=khyH7cMMS-NFtg-M) ESLint: [YouTube](https://youtu.be/qhuFviJn-es?si=Byp1JNURP0_gXYJA) Prettier: [YouTube](https://youtu.be/DqfQ4DPnRqI?si=OZg7vmLfxH1NssAy) Vitest: [YouTube](https://youtu.be/cM_AeQHzlGg?si=CoCGVPZGg-SCYcr8) GitHub Actions: [YouTube](https://youtu.be/R8_veQiYBjI?si=i8vZBZQVqx_bOP2-) |

---
### 🛠️ For the Backend Team : Next.js API Routes

This path focuses on creating server-side logic, handling data, and building robust APIs that the frontend will consume.

#### **Primary Recommendation: Official Documentation**

- **Official Next.js Docs - Route Handlers:** In the App Router, traditional "API Routes" are now called **Route Handlers**. The official documentation is the source of truth and provides clear, copy-paste-ready examples.
    
    - **Link:** [Next.js Route Handlers Documentation](https://nextjs.org/docs/app/building-your-application/routing/route-handlers)
        

#### **In-Depth Guides & Tutorials**

- **Mastering Next.js API Routes (SuperTokens Blog):** A fantastic deep-dive article that goes beyond the basics to cover dynamic routes, middleware, error handling, and security.
    
- **"Effectively Build RESTful APIs using Next.js API Routes" (Egghead.io):** A concise, paid course, but the concepts covered in the syllabus (available for free) provide an excellent roadmap of what to learn.
    
- **YouTube - "Next.js API Routes":** Search for recent videos on this topic. Many tutorials cover creating CRUD (Create, Read, Update, Delete) APIs, which is a practical way to learn.
    

#### **Key Concepts for the Backend Team to Master:**

- **Route Handlers:** Understand how to create `route.ts` (or `.js`) files and export functions for HTTP methods like `GET`, `POST`, `PUT`, and `DELETE`.
    
- **Dynamic API Routes:** Learn how to create routes that accept dynamic segments, like `/api/users/[userId]`.
    
- **Request and Response Objects:** Become proficient in handling incoming requests (`Request`) and crafting responses (`NextResponse`), including setting status codes and JSON bodies.
    
- **Server Actions:** Understand this newer alternative to traditional API routes for handling form submissions and mutations directly from components. It's crucial to know when to use a Server Action vs. a dedicated API endpoint.
    
- **Middleware:** Learn how to run code before a request is completed, which is perfect for authentication, logging, or redirects.
    
- **Connecting to Databases:** Practice fetching and sending data to a database (e.g., Postgres with Prisma, or a serverless DB like Supabase/Firebase) from within your Route Handlers.