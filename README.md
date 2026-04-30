##SkillMap
AI-Powered Learning Roadmap Platform
An intelligent full-stack web application that helps students and developers follow structured, goal-oriented learning paths with AI-driven recommendations.
learning platform with role/skill-based roadmaps, quizzes, projects, resources, docs, AI-assisted learning, and a SaaS-grade admin dashboard.

##Overview
Learning new technologies can be overwhelming due to scattered resources and lack of direction. This platform solves that problem by generating clear, structured roadmaps for any domain such as Full Stack Development, Cloud Computing, or Data Analytics.

Each roadmap provides:-
- Step-by-step progression
- Concepts and explanations
- Curated resources and documentation
- AI-based learning suggestions

##Stack
- Backend: Spring Boot 3.2, Java 17, Spring Security + JWT, Spring Data MongoDB
- Frontend: React 18 + Vite + Tailwind + shadcn/ui + @dnd-kit + Recharts
- DB: MongoDB 7

- Frontend → http://localhost:5173
- Backend  → http://localhost:8080/api
- Swagger  → http://localhost:8080/swagger-ui.html
- Admin    → `admin@skillmap.dev` / `Admin@123`

##Architecture
RESTful APIs built using Spring Boot
Modular backend design for scalability
React-based dynamic UI
AI integration for smart suggestions

##Features
- AI-generated learning roadmaps
- Topic-wise concepts and resources
- Structured step-by-step guidance
- Personalized recommendations
- Responsive and modern UI
- Scalable backend architecture
- Role-based + skill-based roadmaps with phases & topics
- Drag-and-drop phase / topic / question reordering (admin) + personal learning queue (user)
- Quizzes: MCQ + long-form interview-prep questions with model answers & AI evaluation
- Projects, Resources, Documentation, Skill Guidance pages
- AI Suggestions + Concept Explainer
- Admin dashboard with Recharts analytics, CRUD for all entities, user management
- JWT auth with `ROLE_USER` / `ROLE_ADMIN`
- Seeded sample data on first boot
