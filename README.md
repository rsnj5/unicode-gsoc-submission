# GSoC 2024 Project Report | Unicode
## Linux command line (sh/Perl/Python) interface to Google groups
Contributor: Sanju Raj
Mentors: Rick McGowan

Project Size : Small (~60 hours)
Project repo: [project-submission](https://github.com/unicode-org/kr-tools/tree/main/lgl-group-tools)
Project Proposal: [Proposal](Linux command line (sh_Perl_Python) interface to Google groups GSOC PROPSAL SANJU RAJ - Google Docs.pdf)

## Project abstract
This project aims to develop a suite of command-line interface (CLI) modules tailored for Linux environments, enabling automation of common Google Groups operations. These modules, predominantly in sh, Perl, and Python, will leverage various Google APIs to facilitate tasks seamlessly. Primarily, the tool will serve as a bridge between Little Green Light (LGL), the unicode's central contact management system, and Google Groups. By integrating with LG's daily reports, the tool will enable automatic updates to Google Groups based on constituent data changes. This ensures that Google Groups remain synchronised with the single source of truth provided by LGL.
Expected outcomes encompass a robust CLI toolset capable of:
Adding members to groups.
Removing members from groups.
Modifying member roles within groups.
Validating membership status based on email addresses.
Efficiently removing members from all groups.
Listing groups in the organisation linked to specific individuals.
By automating these tasks, the project aims to save significant time and effort previously spent on manual group management processes. The tool's modular design will facilitate easy integration into existing workflows, enabling seamless execution via cron jobs and shell scripts.

## Project Goals
This project simplifies the management of Google Groups by automating common tasks. It uses LGL reports as the primary data source to ensure accuracy. Through a user-friendly console interface, the tool efficiently synchronises groups, reducing manual effort.

## Project Results
Adding members to groups.
Removing members from groups.
Modifying member roles within groups.
Validating membership status based on email addresses.
Efficiently removing members from all groups.
Listing groups in the organisation linked to specific individuals.

|Commits| |Description|
|-------| |------|
|[Commits:5d4f1f7](5d4f1f765b5add0d3745337c228264f3092c94e9)| |Added script for managing group members using Google Admin SDK|
|[Commits:3383f08](3383f08f6c5afb20dd28153c7a4fc3015b2d0631)| |Added .gitignore file|



