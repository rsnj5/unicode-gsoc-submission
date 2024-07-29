# GSoC 2024 Project Report | Unicode

## Linux Command Line (sh/Perl/Python) Interface to Google Groups

**Contributor:** Sanju Raj  
**Mentor:** Rick McGowan  

**Project Size:** Small (~60 hours)  
**Project Repository:** [project-submission](https://github.com/unicode-org/kr-tools/tree/main/lgl-group-tools)  
**Project Proposal:** [Proposal](https://docs.google.com/document/d/1cNtDYlnaWF_yIpUVlObSJfvxk9uik1TFT7dyax8H0A4)

## Project Abstract

This project aims to develop a suite of command-line interface (CLI) modules tailored for Linux environments, enabling automation of common Google Groups operations. These modules, predominantly in sh, Perl, and Python, will leverage various Google APIs to facilitate tasks seamlessly. Primarily, the tool will serve as a bridge between Little Green Light (LGL), Unicode's central contact management system, and Google Groups. By integrating with LGL's daily reports, the tool will enable automatic updates to Google Groups based on constituent data changes, ensuring that Google Groups remain synchronized with the single source of truth provided by LGL.

Expected outcomes encompass a robust CLI toolset capable of:
- Adding members to groups.
- Removing members from groups.
- Modifying member roles within groups.
- Validating membership status based on email addresses.
- Efficiently removing members from all groups.
- Listing groups in the organization linked to specific individuals.

By automating these tasks, the project aims to save significant time and effort previously spent on manual group management processes. The tool's modular design will facilitate easy integration into existing workflows, enabling seamless execution via cron jobs and shell scripts.

## Project Goals

This project simplifies the management of Google Groups by automating common tasks. It uses LGL reports as the primary data source to ensure accuracy. Through a user-friendly console interface, the tool efficiently synchronizes groups, reducing manual effort.

## Project Results

1. Adding members to groups.
2. Removing members from groups.
3. Modifying member roles within groups.
4. Validating membership status based on email addresses.
5. Efficiently removing members from all groups.
6. Listing groups in the organization linked to specific individuals.

## Contributions

| Commit | Description |
|--------|-------------|
| [5d4f1f7](https://github.com/unicode-org/kr-tools/commit/5d4f1f765b5add0d3745337c228264f3092c94e9) | Added script for managing group members using Google Admin SDK |
| [3383f08](https://github.com/unicode-org/kr-tools/commit/3383f08f6c5afb20dd28153c7a4fc3015b2d0631) | Added .gitignore file |
| [2abc7c0](https://github.com/unicode-org/kr-tools/commit/2abc7c086f63c6c3103a1a7e24941748362d298e) | Added scripts for adding members to group, Removing members from group,modifying member roles within groups,validating membership status.|
| [6da428e](https://github.com/unicode-org/kr-tools/commit/6da428e5f7953374b904b45137739783bc4781ac) | Updated files |
| [e50a471](https://github.com/unicode-org/kr-tools/commit/e50a471436752d2be8d8b7708d7ecbff45b94b9d) | Updated files |
| [7eddb48](https://github.com/unicode-org/kr-tools/commit/7eddb48ea21278ee30cf7bcc3404fc7062e4ca65) | Added unittest script |
| [70fd514](https://github.com/unicode-org/kr-tools/commit/70fd51464419d48f7f41671dbaf5145871d7824b) | Updated Readme |

## Concluding remarks

I have completed almost all the goals we decided on during the community bonding period. I thoroughly enjoyed the work and would be thrilled to keep contributing. I tried getting into open source a few times before and hit a dead end. Participating in GSoC gave me the right confidence and skill to make meaningful contributions. Now, instead of feeling overwhelmed by a big codebase, I have the skills to handle it.


## Acknowledgments

Thanks to Google, Unicode, and my mentor for this opportunity. I will be forever indebted to my mentor and Unicode community for their constant support and guidance.
