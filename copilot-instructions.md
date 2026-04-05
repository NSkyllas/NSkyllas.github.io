# Project: Personal Portfolio Website (Nomikos Skyllas)

## Goal
Build a minimal, clean, static portfolio website using plain HTML and CSS.

The website should present:
- who I am
- what I do
- concrete projects (main focus)
- a clear CV

No unnecessary complexity.

---

## Core principles
- Clarity over design
- Structure over creativity
- Evidence over claims
- Minimalism over features

Avoid:
- buzzwords
- vague language
- unnecessary styling
- frameworks

---

## Tech stack
- Plain HTML
- Plain CSS
- No JavaScript unless strictly necessary
- No frameworks (no React, no Tailwind, no Bootstrap)

---

## Project structure

Root:
- index.html
- projects.html
- cv.html
- contact.html

/projects/
- flyway-model.html
- arctic-climate.html
- ecological-modelling.html

/assets/css/
- style.css

/assets/images/
- images for projects

---

## Navigation

Every page must include the same navigation:

Home | Projects | CV | Contact

Navigation must be:
- simple
- consistent across pages
- placed at the top

---

## Layout rules

- Max width: ~800px
- Centered content
- White background
- Black text
- One accent color (orange or red)
- No animations
- No visual clutter

---

## HTML rules

- Use semantic HTML:
  - header
  - main
  - section
  - footer

- Keep structure consistent across all pages
- Avoid unnecessary div nesting
- Keep HTML readable and clean

---

## CSS rules

- Single file: /assets/css/style.css
- Focus on:
  - typography
  - spacing
  - layout
- No external libraries
- No complex styling systems

---

## Content style

- Short paragraphs (max 2–3 sentences)
- Direct and clear language
- No storytelling fluff
- No generic phrases like:
  - "passionate about"
  - "driven individual"

Every section must answer:
- what
- how
- why

---

## Page definitions

### index.html (Home)

Purpose:
Present identity clearly in <10 seconds

Structure:
1. Name + role
2. Short introduction (what I do)
3. Key strengths (2–3 bullets)
4. Selected projects (links)

---

### projects.html

Purpose:
Overview of all projects

Structure:
- Title
- Short intro (1–2 lines)

Project list:
For each project:
- Title
- 1–2 line description
- Link to project page

---

### Project pages (/projects/*.html)

Each project page must follow this exact structure:

1. Context  
What problem is being solved?

2. Approach  
How does the method/model work?

3. Key components  
Breakdown of main elements

4. Results  
What was found?

5. Why it matters  
Scientific or practical relevance

6. Tools  
Technologies used

---

### cv.html

Structure:
- Name
- Current role
- Experience (concise, factual)
- Education
- Skills:
  - programming
  - data
  - modelling
- Publications (if available)

---

### contact.html

Minimal:
- Email
- GitHub
- LinkedIn (optional)

---

## Naming conventions

- lowercase
- hyphen-separated filenames

Examples:
- flyway-model.html
- arctic-climate.html

---

## Expectations for Copilot

- Generate clean, readable HTML
- Keep consistency across all pages
- Prefer simple solutions
- Do NOT introduce frameworks
- Do NOT overengineer

When unsure:
→ choose the simplest possible implementation
