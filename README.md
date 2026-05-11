# Next Level — Gaming Social MVP

> A mobile-first social network for gamers — taken from problem definition through user research to a functional Next.js MVP, in 9 documented phases.

[![Next.js](https://img.shields.io/badge/Next.js-16-black?style=flat&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9-3178C6?style=flat&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind](https://img.shields.io/badge/Tailwind-4.1-06B6D4?style=flat&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-47A248?style=flat&logo=mongodb&logoColor=white)](https://www.mongodb.com/)

## What it is

**Next Level** is a mobile-first social network that lets gamers share clips and screenshots, interact with the community, and **find teammates filtered by game + skill rank**. The project is structured as a full **product design process** — from problem statement to user research, personas, wireframes, prototype, user testing, and finally an MVP build.

## The product process (9 phases)

```
01_research        →  Problem statement · objectives · benchmark · interviews
02_personas        →  Casual gamer · Competitive player · Parents supervisor
03_user_journey    →  Mapping the core flows
04_wireframes      →  Low-fi screens
05_mockups         →  Hi-fi visuals
06_prototype       →  Interactive Figma
07_feedback        →  User testing protocol + results
08_prioritization  →  MoSCoW matrix · MVP definition
09_pitch           →  Final stakeholder pitch
mvp/yowl/          →  Functional Next.js MVP
```

## MVP stack

| Layer            | Technology                                                     |
| ---------------- | -------------------------------------------------------------- |
| **Framework**    | Next.js 16 + React 19                                          |
| **Language**     | TypeScript                                                     |
| **Styling**      | Tailwind CSS 4                                                 |
| **Backend**      | Express (in-app API routes) + Mongoose                         |
| **Database**     | MongoDB Atlas                                                  |
| **Media**        | Cloudinary (image/video uploads)                               |
| **Moderation**   | `leo-profanity` + `bad-words` for community content filtering  |
| **Theming**      | `next-themes` for light/dark mode                              |

## MVP features

- **Auth** : login system
- **Feed** : community posts with image/clip uploads via Cloudinary
- **Interactions** : likes and comments
- **Game search** : browse games to find content
- **Teammate finder** : match other players by game + rank
- **Profile page** : user identity & posts
- **Content moderation** : profanity filter on user-generated content

## What I learned

- **End-to-end product design** — going from "people need X" to a shippable MVP is a different beast than just coding features. Each phase fed the next.
- **User research with real interviews** — turning qualitative input into 3 distinct personas with quantified pain points
- **Prioritization that holds up** — MoSCoW + impact matrix forced honest scope decisions
- **Next.js 16 + React 19** on a non-trivial backend (Mongoose models, Cloudinary upload pipeline, content moderation middleware)
- **Mobile-first execution** — designing for thumbs first, desktop second

## Project context

- **Year** : 2025–2026
- **School** : Epitech Bachelor, Mulhouse
- **Team** : group project
- **Course** : Tech Business Methodology (B-TBM-100)

## Note

This is a portfolio summary. The full source code, documentation, and MVP are private per Epitech academic policy. Available on request for recruiters.

---

[Imran Nogueira](https://github.com/imrannnn30) · MMXXVI
