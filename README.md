## Hi there 👋

I'm **Sherline**, a **Full-Stack Developer** who builds and validates web applications with **Ruby on Rails**, **Python**, and **PostgreSQL**, and integrates AI into real products.

🎓 **Le Wagon AI Software Development Bootcamp**
🌍 **Based in Montreal | Open to local & remote opportunities in backend and full-stack development**

---

## ⚙️ Tech Stack

**Backend:** Ruby on Rails, Python, FastAPI, SQLAlchemy, Pydantic

**Databases:** PostgreSQL, SQL, SQLite, Supabase

**Frontend:** JavaScript, TypeScript, HTML, CSS, Bootstrap, Hotwire (Turbo / Stimulus), React

**Testing:** Minitest, pytest, unit testing, business rule validation, debugging

**AI & LLMs:** LLM integration, RAG, prompt engineering, context engineering, Claude API, Gemini API, OpenAI GPT-4o, Claude Code

**Cloud & Tools:** Docker, Kamal, AWS EC2, Heroku, Vercel, Git, GitHub

**Realtime:** WebSockets, Action Cable

---

## 🚀 Projects

### **Present** *(Primary Project · In Progress)*

A full-stack attendance and financial management app for community organizations: churches, social clubs, sports teams, and similar groups.

* Implemented business rules that automatically generate charges for late and no-show attendance
* Added validation logic to prevent duplicate charges and keep member balances accurate
* Wrote backend unit tests with Minitest and tested edge cases across attendance, billing, payment, and balance workflows
* Deployed to AWS EC2 with Kamal, Docker, and PostgreSQL

`Rails 8.1` `PostgreSQL` `Minitest` `Hotwire` `Devise` `Solid Queue` `Docker` `Kamal` `AWS EC2`

### **Review** *(In Progress)*

A full-stack web app where users share and rate experiences they've tried, like hiking or kayaking.

* Built a REST API with FastAPI providing full CRUD (create, read, update, delete) for users and reviews
* Modelled a one-to-many user → reviews relationship with SQLAlchemy, including cascade deletion
* Converted the database layer to async SQLAlchemy, using eager loading to avoid N+1 queries
* Validated data with Pydantic schemas (1–5 rating limits, email validation, partial updates)
* Rendered server-side pages with Jinja2 and Bootstrap
* Built custom error handling: JSON for API clients, friendly HTML pages for visitors

`Python` `FastAPI` `SQLAlchemy` `SQLite` `Pydantic` `Jinja2` `Bootstrap`

### **ChairHop** *(Team Project · Le Wagon)*

A two-sided salon booking marketplace connecting clients with independent hair stylists.

My main contribution was **HOPPS**, an AI assistant that helps clients find appointments and guides stylists through the platform.

* Built the chat's backend and frontend with Rails, PostgreSQL, and Hotwire
* Built real-time features with Action Cable and WebSockets
* Integrated GPT-4o via RubyLLM and applied prompt engineering for appointment discovery
* Worked on booking workflows involving multiple business rules and user roles

`Rails 7.1` `PostgreSQL` `pgvector` `GPT-4o` `RubyLLM` `Action Cable` `Hotwire` `Pundit`

### 🤖 **AI Agents** *(built with Claude Code under my supervision)*

I defined the requirements, directed the work phase by phase, and tested each feature both with Claude and manually in the browser.

* **AI Mock Interview Agent:** resume-aware interviewer that runs a five-phase adaptive mock interview over text or voice, then scores each phase and generates a report. `FastAPI` `React` `Claude API` `ElevenLabs` `Supabase` `pytest` `Playwright`
* **Email Agent:** Gmail reply agent that drafts answers to course inquiries using RAG over a 150-course catalogue. Nothing is sent automatically; every draft is reviewed and approved by a human. `Next.js` `TypeScript` `Supabase pgvector` `Gemini API` `Gmail API` `Google OAuth`

---

## 🧠 Currently Exploring

* AI agents and LLM application development
* Backend architecture
* Testing and validating software behavior
* Real-time systems

---

## 🌐 Languages

French · English · Haitian Creole (fluent) · Spanish (understanding)

---

## 💡 About Me

I'm naturally curious and enjoy understanding how systems work from end to end. I like building backend systems, integrating AI into real applications, and making sure software behaves the way it should, especially around tricky business rules and edge cases. I value maintainable code, continuous learning, and collaborating with others to solve meaningful problems.

---

## 📫 Connect With Me

**Portfolio:** https://shbe12.github.io/profile/

**LinkedIn:** https://www.linkedin.com/in/sherline-bertrand/
