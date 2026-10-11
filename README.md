# AnuragPatil-cloud.github.io

Personal portfolio website of **Anurag Patil** — DevOps Engineer | Multi-Cloud Infrastructure, CI/CD Automation & SRE.

DevOps Engineer with 3.8+ years of experience building the CI/CD, Kubernetes and cloud platforms that help software teams ship faster and safer. Cut developer deployment wait time from 4 hours to under 10 minutes with ArgoCD, kept a 99.8% pipeline success rate across 15+ microservices with Jenkins and GitHub Actions, and reduced MTTR by 45% with Prometheus, Grafana and the ELK Stack. Works across AWS, Azure and GCP using Terraform, Docker, Kubernetes (Amazon EKS), Python and Bash, and has built AI-powered DevOps automation with LangChain and LangGraph.

Built with plain HTML, CSS and JavaScript in a single file. No frameworks and no build step.

## 🔗 Live Site

[https://AnuragPatil-cloud.github.io](https://AnuragPatil-cloud.github.io)

## 📌 Sections

- **Hero** — Name, role, an animated (replayable) view of the CI/CD pipeline from my Student Registration project, and four headline results: 3.8+ years, 99.8% pipeline success, 4h to 10min deployment wait, 45% lower MTTR
- **About** — Summary, location, contact details and availability
- **Technical Skills** — Grouped by Cloud platforms (AWS, Azure, GCP), Platform & delivery (Containers & Kubernetes, CI/CD & GitOps, IaC), Reliability & security (Monitoring, SRE, DevSecOps) and Foundations (Scripting, Databases & Networking, Operating Systems, AI & Automation, Tools & collaboration)
- **Experience** — Pentagram Infotech Private Limited: DevOps Engineer, Platform Engineering Team (Sep 2023 – Present) and DevOps Engineer Intern (Mar 2023 – Aug 2023)
- **Projects**
  - *Featured:* [Multi-Cloud Flight Reservation Platform](https://github.com/AnuragPatil-cloud/flightreservation-multicloud) · [AI Agent Projects](https://github.com/AnuragPatil-cloud/Ai_Agent_Projects)
  - *More projects:* [Multi-Cloud Student Registration Platform](https://github.com/AnuragPatil-cloud/multicloud-student-registration) · [Full-Stack Blogging App on AWS EKS](https://github.com/AnuragPatil-cloud/Full-Stack-Blogging-Application-CI-CD-Pipeline-on-AWS-EKS) · [Deploying an App to AKS using Azure DevOps & Azure Cloud Shell](https://github.com/AnuragPatil-cloud/Deploying-an-App-to-AKS-using-Azure-DevOps-Azure-Cloud-Shell)
- **Education & Certifications** — DBATU University (B.Tech, Computer Science Engineering, CGPA 7.6), AWS SAA-C03 and CKA in progress, plus completed AWS, Azure and Linux Foundation courses
- **Contact** — Email, phone (with copy buttons), LinkedIn, GitHub

## 🛠️ Tech Stack

- HTML5 and semantic landmarks
- CSS3 (Custom Properties, Grid, Flexbox)
- Vanilla JavaScript (IntersectionObserver, requestAnimationFrame, Clipboard API)
- Three.js r128 for the optional 3D background — lazy-loaded from cdnjs after the page is ready
- Google Fonts (Space Mono, Syne)

## ♿ Accessibility & Performance

- Skip link, visible keyboard focus, labelled landmarks and an accessible mobile menu
- `prefers-reduced-motion` respected: no pipeline animation, no 3D background, no custom cursor
- Works without JavaScript (the pipeline shows its final state) and without the CDN (the 3D background is simply skipped)
- The 3D background and custom cursor are disabled on touch devices, small screens and Save-Data connections
- Contact links open mail and dialer apps as expected; copying is a separate button

## 🚀 Deployment

This site is hosted via **GitHub Pages**.

To deploy your own copy:
1. Fork this repository
2. Go to `Settings` → `Pages`
3. Set source to `main` branch / `root`
4. Your site will be live at `https://<your-username>.github.io`

## 📁 Project Structure

```
AnuragPatil-cloud.github.io/
├── index.html               # Single file — all HTML, CSS and JS included
├── AnuragPatil_resume.pdf   # Linked from the "Download resume" button
├── preview.png              # 1200×630 social preview (Open Graph / Twitter card)
└── README.md
```

## ✏️ Updating the Content

Everything lives in `index.html`:

| To change | Look for |
|---|---|
| Headline results | `<div class="results">` |
| About text and contact facts | `<section ... id="about">` |
| Skills | `<section ... id="skills">` — one `.sk-row` per category, one `.tag` per skill |
| Jobs | `<article class="job">` inside `#experience` |
| Add a project | Copy an `<article class="proj">` into `.proj-grid.feature` or `.proj-grid.more` |
| Colours and fonts | `:root { ... }` at the top of the `<style>` block |
| Hero pipeline stages | `<aside class="pipe">` |

After changing your resume, replace `AnuragPatil_resume.pdf` with the new file under the same name.

## 📬 Contact

- **Email:** patilanurag1703@gmail.com
- **Phone:** +91-9226521573
- **LinkedIn:** [linkedin.com/in/anuragpatil17](https://www.linkedin.com/in/anuragpatil17)
- **GitHub:** [github.com/AnuragPatil-cloud](https://github.com/AnuragPatil-cloud)
