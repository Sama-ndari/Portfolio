Act as a Senior Frontend Engineer. I need to refactor my 'index.html' to reflect my transition to a Senior AI Developer.

Please perform the following updates on the current file. Maintain the existing "Pro" design aesthetic.

### PHASE 1: CLEANUP (Remove Legacy Content)
1. **Projects:** Remove the portfolio items for "SimonGame," "Dicee," "NumberToLetters," "App 1," "App 2," "App 3," "Mobile 1," "Mobile 2," "Web 2," and "Web 3."
2. **Certifications:** In the Resume section, DELETE the entries for "Web Development Bootcamp," "Python Bootcamp," "Duolingo," and "Book Review." Leave "Embedded Systems" and "Leadership Training" (or remove if empty).
3. **Services:** Remove the service cards for "WebSites" and "Mobile Apps." Keep "Software Applications" and "AI Apps" (rename/repurpose if needed based on the Data Source).
4. **Resume Experience:** In the "Software Developer Engineer" entry, DELETE the line: "Developed numerous games SimonGame, Dicee..." and DELETE the line regarding "Registers and Books for Election."

### PHASE 2: CONTENT UPDATE (Strict Adherence to Data Source)
1. **Hero Section:**
   - Update the `<span class="typed">` data items to: "AI Developer, Software Engineer, Backend Architect, Open Source Lead".
   - Ensure the name is **Jules Cesar Junior Ndayisenga**.

2. **About Section:**
   - Replace the main paragraph and the "Software Engineer | AI Data Architect..." sub-headline with the "About Me" and "Title" from the DATA SOURCE below.
   - Update the "Fun Facts" or "Interests" (if present) to include the "Former Nurse" fact.

3. **Skills Section (UI Refactor):**
   - **Action:** Remove the "Percentage" numbers (e.g., `<i class="val">65%</i>`) and the Progress Bars (`.progress-bar-wrap`).
   - **New UI:** Convert the lists inside the `data-typed-items` attributes into **static, visible pill-shaped badges** (e.g., `<span class="badge bg-secondary">NestJS</span>`) so all skills are visible at once, OR keep the `Typed.js` animation but remove the progress bar context so it looks like a dynamic list.
   - **Tech Stack:** Ensure the skills match the "Tech Stack" in the DATA SOURCE (e.g., add CrewAI, OpenAI, Docker where appropriate).

4. **Projects Section (Update Content):**
   - Keep the "Kirundi AI Ecosystem" as the Flagship.
   - Update/Replace the remaining slots with these specific projects from the DATA SOURCE:
     1. **Dev Swarm: Autonomous Software Agency** (Use a placeholder image or existing app image if none exists).
     2. **Enterprise RAG ChatBot**.
     3. **Kirundi Contribution App**.
     4. **Burundian Language Identifier**.
     5. **SamandariApp**.
   - Update links and descriptions to match the DATA SOURCE.

---

### DATA SOURCE (Use this text exactly):

**Name:** Jules Cesar Junior Ndayisenga
**Title:** AI Developer & Software Engineer
**Company:** Asyst Resources LTD

**About Me:**
I'm a passionate AI Developer & Backend Engineer specializing in Agentic AI, Multi-Agent Systems, and Scalable Microservices. I live for the intersection of clean architecture and intelligent automation. Currently, I am focused on engineering Autonomous Agents, RAG systems, and bridging the gap between raw LLM logic and production-ready applications.

**Founder Role (Add to About or Experience):**
Founder & Lead at Ijwi ry'Ikirundi AI. An open-source organization dedicated to digitizing the Kirundi language.

**Fun Facts (Add to About or Bio):**
- Former Nurse turned Engineer — I treat production bugs like medical emergencies.
- Music producer & late-night coder.

**Featured Projects (Update Portfolio Grid):**
1. **Kirundi Open Speech & Text Dataset:** First large-scale open-source dataset for Kirundi.
2. **Dev Swarm: Autonomous Software Agency:** Multi-agent system where autonomous agents collaborate to build software. Features Dockerized code execution.
3. **Enterprise RAG ChatBot:** A fully containerized production-ready, framework-free RAG microservice.
4. **Kirundi Contribution App:** Gamified platform for crowdsourcing language data.
5. **Burundian Language Identifier:** Custom-trained NLP model.