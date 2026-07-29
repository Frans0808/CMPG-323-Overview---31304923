CMPG-323 — Project Portfolio



This repository indexes a series of projects completed for CMPG-323 (IT Developments) at North-West University, covering the full development lifecycle: GUI fundamentals, REST API design, IoT device management, and data visualization/reporting. It's maintained as a portfolio reference and updated periodically as individual projects are refactored to reflect current industry practice.

Projects
#	Repository	Description	Tech Stack
1	FirstGUI	Introductory GUI application	TBC
2	CMPG-323-Project-2-31304923	IoT Device Management REST API	C#, ASP.NET Core, EF Core
3	CMPG-323-IOT-Device-Management	Reference/demo repository (forked)	CSS
4	CMPG-323-Project-4-31304923	TBC	TBC
5	CMPG-323-Project-5	Power BI reporting/dashboard	Power BI, DAX

Rows marked TBC will be completed as each individual repository is reviewed and its README finalized.

Engineering Practices Applied Across This Portfolio

Repository structure Each project repository is self-contained, with its own README covering setup, architecture, and usage — this index repository exists purely for navigation.

Branching strategy — GitHub Flow

main is always deployable.
Feature work happens on short-lived branches (feature/..., fix/...).
Changes merge back via Pull Request after review, keeping main stable and release-ready at all times.

Source control hygiene Every repository uses a .gitignore scoped to its stack (e.g. bin/, obj/, .vs/ for .NET projects) to keep build artifacts and IDE files out of version control.

Secrets management No credentials, connection strings, or API keys are ever committed. Local secrets are managed via .NET User Secrets or environment variables; production credentials are supplied via environment variables or a secrets manager (e.g. Azure Key Vault), never checked into appsettings.json.

Planning & tracking Work was tracked via Azure DevOps Boards, with GitHub handling source control and CI, and Azure DevOps handling sprint planning and work items.

Roadmap
 Fill in remaining project descriptions (rows marked TBC above)
 Refactor Project 2 (IoT API) into a modern layered architecture with tests and CI
 Add architecture diagrams and screenshots to each individual repo
 Add a GitHub Actions build/test pipeline to applicable repositories
License

This project is licensed under the MIT License — see the LICENSE file for details.
