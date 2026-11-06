<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;height=220&amp;section=header&amp;color=0:1E1B4B,55:4338CA,100:7C3AED&amp;text=Shruti%20Talikoti&amp;fontSize=52&amp;fontColor=F5F3FF&amp;fontAlignY=38&amp;animation=fadeIn" alt="Shruti Talikoti" />
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&amp;weight=500&amp;size=19&amp;pause=1400&amp;color=A78BFA&amp;center=true&amp;vCenter=true&amp;width=680&amp;height=48&amp;lines=Full-Stack+Developer;Applied+AI+%26+Data+Science;Software+Engineering+%26+Product+Development" alt="Full-Stack Developer · Applied AI and Data Science · Software Engineering and Product Development" />

  <p>
    <img src="https://img.shields.io/badge/B.E.-CSE%20%28Data%20Science%29-4338CA?style=flat-square&amp;labelColor=1E1B4B" alt="B.E. in CSE (Data Science)" />
    <img src="https://img.shields.io/badge/Dayananda%20Sagar%20Institutions-Class%20of%202029-5B21B6?style=flat-square&amp;labelColor=1E1B4B" alt="Dayananda Sagar Institutions, expected graduation 2029" />
    <img src="https://img.shields.io/badge/CGPA-9.58-6D28D9?style=flat-square&amp;labelColor=1E1B4B" alt="CGPA 9.58" />
    <img src="https://img.shields.io/badge/Bengaluru-India-4338CA?style=flat-square&amp;labelColor=1E1B4B" alt="Bengaluru, India" />
  </p>

  <p>
    <a href="#featured-projects"><img src="https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge" alt="Portfolio and featured projects" /></a>
    <a href="https://www.linkedin.com/in/shruti-talikoti-420001386/"><img src="https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge" alt="LinkedIn" /></a>
    <a href="mailto:shrutitalikoti2007@gmail.com"><img src="https://img.shields.io/badge/Email-5B21B6?style=for-the-badge&amp;logo=gmail&amp;logoColor=FFFFFF" alt="Email Shruti" /></a>
    <a href="https://github.com/itsmeshruti1"><img src="https://img.shields.io/badge/GitHub-312E81?style=for-the-badge&amp;logo=github&amp;logoColor=FFFFFF" alt="GitHub profile" /></a>
  </p>


</div>

---

## About

I’m a **Computer Science and Engineering (Data Science) undergraduate** at Dayananda Sagar Institutions and a **full-stack developer** based in Bengaluru. I build software across interfaces, APIs, and persistence layers, with an interest in how design decisions affect the people using and maintaining it.

At AITurf, I contributed to a feature deployed on its live site and supported it through testing and documentation. My project work spans a recoverable local study timer, geospatial clustering for road-safety analysis, and a recruitment platform that uses AI for résumé matching and candidate ranking. I’ve also contributed to few open source repositories.

### Open To

Software engineering and full-stack internships · Applied AI and data science projects · Open-source collaboration

---

## Tech Stack

### Languages

[![Python, C++, C, Java, JavaScript, and TypeScript](https://skillicons.dev/icons?i=py,cpp,c,java,js,ts&theme=dark)](https://skillicons.dev)

### Frontend

[![React, Next.js, HTML, CSS, Bootstrap, jQuery, and Vite](https://skillicons.dev/icons?i=react,nextjs,html,css,bootstrap,jquery,vite&theme=dark)](https://skillicons.dev)

### Backend & Databases

[![Node.js, Express.js, FastAPI, Flask, and SQLite](https://skillicons.dev/icons?i=nodejs,express,fastapi,flask,sqlite&theme=dark)](https://skillicons.dev)

`SQL` · `Firestore` · `IndexedDB`

### Cloud, DevOps & Tooling

[![Firebase, Git, GitHub, and GitHub Actions](https://skillicons.dev/icons?i=firebase,git,github,githubactions&theme=dark)](https://skillicons.dev)

---

## AI / ML Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| Geospatial machine learning | Applied in projects | Used geographic DBSCAN with haversine distances to group synthetic road incidents into hotspots. |
| Explainable risk scoring | Applied in projects | Ranked hotspot clusters and let users inspect the observations behind each score. |
| AI-assisted screening | In development | Built résumé matching and candidate ranking into a recruitment workflow. |
| AI workflow orchestration | In development | Used LangGraph to support a recruitment platform covering screening, assessments, and interview scheduling. |
| Data analytics | Applied in projects | Built daily and weekly reporting for study streaks and planned versus actual study time. |

---

## Featured Projects

<details>
<summary><strong>Kinetic Scholar</strong> · Local study planning and focus analytics</summary>

<br />

A local study workspace that turns subject priorities and a fixed time budget into a plan, records focus sessions, and shows how actual study time compares with the plan.

| Area | Details |
| :--- | :--- |
| **Stack** | Python, Flask, Waitress, SQLite, JavaScript |
| **Scale** | Single-user workspace with up to 20 active subjects and retained session history |
| **Performance** | Deadline-based timer recovery after reloads and retry-safe session writes |
| **Security** | Loopback-only server, local storage of study data, and CSV formula protection |
| **Impact** | Gives learners a daily and weekly view of study time, focus ratings, and progress against their plan |
| **Repository** | [itsmeshruti1/kinetic-scholar](https://github.com/itsmeshruti1/kinetic-scholar) |

The app keeps an unfinished timer draft in the browser and uses SQLite for durable session records. Request IDs prevent retries from recording duplicate sessions. Planning and reporting use the same subject and session data, so users can follow a study goal from allocation through completion.

</details>

<details>
<summary><strong>Tracify</strong> · Road incident mapping and hotspot analysis</summary>

<br />

A geospatial dashboard for exploring road incidents, filtering them by date and severity, and inspecting clusters on an interactive map.

| Area | Details |
| :--- | :--- |
| **Stack** | React, TypeScript, Vite, Leaflet, IndexedDB, Firebase Auth, Firestore, Firebase Storage |
| **Scale** | 175 synthetic Bengaluru observations in the demo and up to 2,000 records per workspace |
| **Performance** | Geographic DBSCAN with a bounded dataset and shared filters across maps and analysis |
| **Security** | Authenticated per-user cloud storage, validated CSV imports, and formula-safe CSV exports |
| **Impact** | Makes hotspot rankings traceable to individual observations and supports incident reporting with media attachments |
| **Repository** | [itsmeshruti1/Tracify](https://github.com/itsmeshruti1/Tracify) |

Tracify uses haversine distances for density-based clustering. The map connects each hotspot to its source incidents and shows the factors behind its risk score. The workspace supports local persistence and an optional Firebase-backed mode for signed-in users.

</details>

<details>
<summary><strong>AI-Powered Talent Acquisition Platform</strong> · Recruitment workflows in development</summary>

<br />

A recruitment platform that brings candidate screening, assessments, interview scheduling, and applicant tracking into one workflow.

| Area | Details |
| :--- | :--- |
| **Stack** | LangGraph, FastAPI, React, Next.js |
| **Scale** | Covers intake, screening, assessments, and interview scheduling |
| **Performance** | Automates résumé matching and candidate ranking for recruiter review |
| **Security** | Role-based access for the recruiter dashboard |
| **Impact** | Brings candidate progress, scheduling, and hiring analytics into a single recruiter view |
| **Repository** | In development |

LangGraph supports AI-assisted steps, FastAPI exposes the backend, and the React and Next.js dashboard gives recruiters a view of candidates and hiring activity. The platform is in development.

</details>

---

## Experience

### Intern · AITurf

**July 2026 – August 2026** · Remote, India

Supported feature development and release preparation for DigiVitalz at AITurf.

- Contributed to development of the DigiVitalz feature that went live on AITurf’s website.
- Tested the feature before client release to verify expected behavior and identify issues.
- Wrote documentation for feature usage and ongoing maintenance.

![Feature Development](https://img.shields.io/badge/Feature%20Development-4338CA?style=flat-square)
![Functional Testing](https://img.shields.io/badge/Functional%20Testing-5B21B6?style=flat-square)
![Technical Documentation](https://img.shields.io/badge/Technical%20Documentation-6D28D9?style=flat-square)

---

## Achievements

<div align="center">

| Recognition | Details |
| :---: | :--- |
| **PyQuest** | First place in PyQuest, a coding challenge. |
| **Smart India Hackathon 2026** | Qualified through the internal round. |
| **National-Level Hackathon** | Our team placed among the top 70 out of 876 competing teams. |

</div>

---

## Coding Profiles

<div align="center">
  <a href="https://leetcode.com/u/itsmeshruti/"><img src="https://img.shields.io/badge/LeetCode-5B21B6?style=for-the-badge&amp;logo=leetcode&amp;logoColor=FFFFFF" alt="LeetCode profile" /></a>
  <a href="https://www.hackerrank.com/profile/shrutitalikoti21"><img src="https://img.shields.io/badge/HackerRank-4338CA?style=for-the-badge&amp;logo=hackerrank&amp;logoColor=FFFFFF" alt="HackerRank profile" /></a>
  <a href="https://www.codechef.com/users/itsmeshruti"><img src="https://img.shields.io/badge/CodeChef-6D28D9?style=for-the-badge&amp;logo=codechef&amp;logoColor=FFFFFF" alt="CodeChef profile" /></a>
</div>

---

## GitHub Analytics

<div align="center">
  <a href="https://github.com/itsmeshruti1"><img width="48%" src="https://github-stats-extended.vercel.app/api?username=itsmeshruti1&amp;show_icons=true&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=C4B5FD&amp;text_color=EDE9FE&amp;icon_color=8B5CF6" alt="GitHub profile statistics" /></a>
  <a href="https://github.com/itsmeshruti1#contribution-activity"><img width="48%" src="https://streak-stats.demolab.com/?user=itsmeshruti1&amp;hide_border=true&amp;background=0D1117&amp;stroke=312E81&amp;ring=8B5CF6&amp;fire=C4B5FD&amp;currStreakNum=EDE9FE&amp;sideNums=EDE9FE&amp;currStreakLabel=C4B5FD&amp;sideLabels=C4B5FD&amp;dates=A5B4FC" alt="GitHub contribution streak" /></a>
  <br />
  <a href="https://github.com/itsmeshruti1?tab=repositories"><img width="48%" src="https://github-stats-extended.vercel.app/api/top-langs?username=itsmeshruti1&amp;layout=compact&amp;langs_count=8&amp;hide_border=true&amp;bg_color=0D1117&amp;title_color=C4B5FD&amp;text_color=EDE9FE" alt="Most-used languages in public GitHub repositories" /></a>
</div>

---

## GitHub Trophies

<div align="center">
  <a href="https://github.com/itsmeshruti1"><img width="100%" src="https://trophy.benkou.dev/?username=itsmeshruti1&amp;theme=tokyonight&amp;no-frame=true&amp;no-bg=true&amp;column=4&amp;margin-w=12&amp;margin-h=12" alt="GitHub profile trophies" /></a>
</div>

---

## Contribution Activity

<div align="center">
  <a href="https://github.com/itsmeshruti1#contribution-activity"><img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=itsmeshruti1&amp;bg_color=0D1117&amp;color=C4B5FD&amp;line=8B5CF6&amp;point=DDD6FE&amp;area=true&amp;area_color=4C1D95&amp;hide_border=true&amp;custom_title=GitHub%20Contribution%20Activity" alt="GitHub contribution activity over the past 31 days" /></a>
</div>

---

## Contribution Snake

<div align="center">
  <a href="https://github.com/itsmeshruti1#contribution-activity">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itsmeshruti1/itsmeshruti1/output/github-contribution-grid-snake-dark.svg" />
      <img width="100%" src="https://raw.githubusercontent.com/itsmeshruti1/itsmeshruti1/output/github-contribution-grid-snake.svg" alt="Animated snake tracing Shruti's GitHub contributions" />
    </picture>
  </a>
</div>

---

## Current Focus

```yaml
Learning:
  - Data structures and algorithms
  - Operating systems
  - Applied machine learning
Building:
  - AI-powered talent acquisition workflows
  - A supply chain disruption simulator that finds the lowest-cost recovery plan for a given on-time delivery target
Exploring:
  - Open-source software
  - Agentic AI workflows
"Open To":
  - Software engineering and full-stack internships
  - Applied AI projects
  - Open-source collaboration
```

---

## Connect

<div align="center">
  <a href="mailto:shrutitalikoti2007@gmail.com"><img src="https://img.shields.io/badge/Gmail-5B21B6?style=for-the-badge&amp;logo=gmail&amp;logoColor=FFFFFF" alt="Gmail" /></a>
  <a href="https://www.linkedin.com/in/shruti-talikoti-420001386/"><img src="https://img.shields.io/badge/LinkedIn-4338CA?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://github.com/itsmeshruti1"><img src="https://img.shields.io/badge/GitHub-312E81?style=for-the-badge&amp;logo=github&amp;logoColor=FFFFFF" alt="GitHub" /></a>
  <a href="#featured-projects"><img src="https://img.shields.io/badge/Portfolio-6D28D9?style=for-the-badge" alt="Portfolio and featured projects" /></a>
</div>

---

<div align="center">
  <p><em>Build for the people who use it and the engineers who maintain it.</em></p>
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&amp;height=120&amp;section=footer&amp;color=0:1E1B4B,55:4338CA,100:7C3AED" alt="" />
</div>

