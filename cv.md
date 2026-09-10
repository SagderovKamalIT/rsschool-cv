<p align="center">
  <img src="https://vercel.app" />
</p>

# Kamal Sagderov
## Frontend Developer / React

<div align="center">

🚀 **Frontend Developer Intern**, focused on the **React** ecosystem  
Developing in the **React + TypeScript** direction, paying close attention to component architecture, code quality, and modern UI solutions.

</div> 

---

## Contact Information

- **GitHub:** [SagderovKamalIT](https://github.com)
- **Telegram:** [@kamal_sagderov](https://t.me)
- **Discoed:** [@kamal_sagderov]
- **Email:** sagderovkamal.it@gmail.com
- **Location:** Moscow, Russia

---

## About Me

I am a passionate 22-year-old Frontend Developer Intern with a strong focus on building responsive and interactive web applications using React and TypeScript. Currently studying Digital Design and Web Development at RUDN University, I actively combine my academic knowledge with practical experience, ranging from production-level automation systems to modern SPA development. I am highly motivated to write clean, type-safe code, optimize performance, and continuously elevate my technical skills through the RS School ecosystem.

---

## Technical Skills

- **Programming Languages:** JavaScript (ES6+), TypeScript, HTML5, CSS3, SQL
- **Frameworks & Libraries:** React 19, React Router, TanStack Query, Material UI (MUI), Framer Motion
- **Tools & Workflow:** Git, GitHub, Vite, npm, Docker, Bash, BEM Methodology, SCSS/SASS Modules
- **AI & Engineering Tools:** Prompt Engineering, Claude Code, LLM integration
- **Design:** Figma (Pixel-perfect layout translation)
- **Languages:** Russian (Native), English (A2 - Elementary)

---

## Professional Experience

### Sber — Intern (Software Engineer)
*June 2026 – July 2026 (2 months)*
* Designed and built a multi-agent system powered by a Telegram bot for automated business meeting management (knowledge base maintenance, meeting minutes, LLM & external services integration).
* Migrated a production-grade application for event and warehouse management from demo mode to actual server infrastructure, implementing user roles, request approvals, and notifications (delivered 100% stable MVP).
* **Stack:** Node.js, TypeScript, React, PostgreSQL, Docker, LLM (Claude Code).

### Freelance / Independent Projects — Frontend Developer
*August 2025 – Present*
* Developing single-page applications (SPAs) and highly interactive landing pages using modern frontend stacks.
* Focus areas: component-driven architecture, custom hooks, complex routing, data persistence (localStorage), and smooth UI animations.

### RUDN Higher School of Management — Frontend Intern
*June 2025 – July 2025 (2 months)*
* Developed responsive and cross-browser semantic layouts from detailed Figma UI designs.
* Implemented core interface interactivity using vanilla JavaScript DOM manipulation.

---

## Education

### RUDN University (Peoples' Friendship University of Russia)
* **Degree:** Bachelor's Degree in Digital Design and Web Development (Higher School of Management)
* **Period:** 2022 — 2027 (Expected graduation)

### Additional Courses & Certifications
* **Full Stack Open** — University of Helsinki (2027)
* **The Odin Project** — Open-source Full Stack Web Development (2027)
* **JavaScript: Step by Step** — Yandex Lyceum, Frontend (2026)
* **Artificial Intelligence in Python** — RUDN Institute of Training and Retraining (2026)
* **IT Project Management** — Innopolis University (2024)

---

## Featured Projects

### ⚛️ School 21 × RUDN University
* **Description:** A landing page for a joint educational project focused on AI and digital technologies training.
* **Tech Stack:** React, Vite, SCSS, Framer Motion
* **Deployment:** [Live Demo](https://github.io)

### 🌐 Digital Business Transformation Conference
* **Description:** Official website for the international scientific and practical conference of the RUDN Higher School of Management, deployed to the university's official domain.
* **Tech Stack:** React 19, Vite, SASS, ESLint
* **Deployment:** [Live Demo](https://github.io)

### 🎂 Sweet Chest (Сладкий сундук)
* **Description:** Single-page cake ordering landing page built with atomic component decomposition, live price counters, and pixel-perfect design.
* **Tech Stack:** React 19, TypeScript, Vite, SCSS Modules
* **Deployment:** [Live Demo](https://github.io)

### 📋 Kanban Board for Task Management
* **Description:** Feature-rich Kanban application with CRUD capabilities, state caching, custom hooks, and external API data synchronization.
* **Tech Stack:** React 19, TypeScript, Material UI, React Router, TanStack Query
* **Deployment:** [Live Demo](https://github.io2/)

---

## Code Example

Here is a clean snippet showing a typed React custom hook designed for managing task status updates in a Kanban architecture:

```typescript
import { useState, useCallback } from 'react';

interface Task {
  id: string;
  title: string;
  status: 'todo' | 'in-progress' | 'done';
}

export const useTaskManager = (initialTasks: Task[]) => {
  const [tasks, setTasks] = useState<Task[]>(initialTasks);

  const updateTaskStatus = useCallback((taskId: string, newStatus: Task['status']) => {
    setTasks((prevTasks) =>
      prevTasks.map((task) =>
        task.id === taskId ? { ...task, status: newStatus } : task
      )
    );
  }, []);

  return { tasks, updateTaskStatus };
};
```
---

## 🎯 Professional Goals

* Deepen understanding of advanced React state-management and architectural patterns.
* Elevate TypeScript implementation to advanced strict guidelines.
* Build fully secure and heavily optimized full-stack applications.
* Actively collaborate in open-source tasks and tech hackathons.