# 🛡️ Raices Cyber Interactive Labs

This repository hosts the source code for interactive cybersecurity simulations and lab environments embedded within **CourseStack** lessons for Raices Cyber Org. 

## 🏗️ Repository Architecture
We use a **Monorepo** structure to manage multiple labs while maintaining a consistent design language.

* **/common**: Contains global assets, including the `null-sector.css` master theme.
* **/assets**: Global media, Raices logos, icons, and branding assets.
* **/lab-[name]**: Individual, self-contained interactive labs.

## 🚀 Deployment Workflow
This repository is deployed via **GitHub Pages**. 

1.  **Develop Locally**: Create a new folder (e.g., `/lab-nullbot`) and build your `index.html`.
2.  **Theme Integration**: Link to the shared styles to maintain the Null_Sector aesthetic:
    `<link rel="stylesheet" href="../common/null-sector.css">`.
3.  **Push to Main**: Once pushed to the `main` branch, GitHub Actions will automatically deploy the update.
4.  **Embed in CourseStack**: Use the following URL format in the CourseStack Embed Block:
    `https://Raices-Cyber-Org.github.io/coursestack-labs/lab-[name]/`

## 💻 Local Preview
To preview a lab locally before pushing to production:
1. Navigate to the specific lab folder.
2. Start a local HTTP server (e.g., `python3 -m http.server 8000`).
3. View in browser at: `http://localhost:8000`.

## 📝 Lab Inventory
| Lab Slug | Description | Primary Vulnerability |
| :--- | :--- | :--- |
| `lab-nullbot` | Social engineering via an AI terminal bypass. | Human Element / Social Engineering |

---
**Maintainer:** Raices Course Development
