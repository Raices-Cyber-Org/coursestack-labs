# Raices Cyber Interactive Labs

This repository hosts the source code for interactive cybersecurity simulations and lab environments embedded within **CourseStack** lessons for Raices Cyber Org. 

## Repository Architecture
We use a **Monorepo** structure to manage multiple labs while maintaining a consistent design language.

* **/common**: Global assets and the `null-sector.css` master theme.
* **/lab-[name]**: Individual, self-contained interactive labs.

## Deployment Workflow
This repository is deployed via **GitHub Pages**. 

1. **Develop**: Create a new folder (e.g., `/lab-name`) and build the `index.html`.
2. **Style**: Link to shared styles: `<link rel="stylesheet" href="../common/null-sector.css">`.
3. **Deploy**: Push to the `main` branch to trigger the automatic update.
4. **Embed**: Use the following URL format in CourseStack: 
   `https://Raices-Cyber-Org.github.io/coursestack-labs/lab-[name]/`.

## Lab Inventory
| Lab Name | Description | Link |
| :--- | :--- | :--- |
| **NullBot v3.0** | AI Social Engineering Simulation | [Launch Lab](https://Raices-Cyber-Org.github.io/coursestack-labs/lab-nullbot/) |
| **The Mindfall Protocol** | PR Grid Recovery CTF | [Launch Lab](https://Raices-Cyber-Org.github.io/coursestack-labs/lab-mindfall/) |

---
**Maintainer:** Raices Course Development
