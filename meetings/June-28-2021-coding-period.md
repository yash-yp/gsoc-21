# Meeting- June 28, 2021

Attendees (please add yourself to this list and tell us one good thing going on in your life recently)
 
- Ritik Malik
- Kevin Lumbard 
- Yash Prakash

## Agenda/Notes:

- Project Update : Core work of the project is complete.
    - Show the DEMO
    - We’ve updated the main branch with automation system
    PDF link
    - PDF gets generated automatically with the focus area tables and 3 levels of hierarchy in the TOC
    - Focus-Areas README standardization has been discussed, and will be sending PRs this week
    - Will continue to work in dev branch and push it timely
- Added a new README for yml config file -
    - https://github.com/chaoss/MARS/tree/main/automation-english/active_user_input
    - Which directory are we using in website repo to store backup of yml config file before every release?
    NO
- What other elements are required in the PDF? And How do we incorporate them?
  - Contributor List
        - https://github.com/chaoss/website/blob/master/release/contributors.md
  - Release Notes
        - We can pull from website repo - include this in yml file
        - https://github.com/chaoss/website/blob/master/release/release-notes.md
  - What should be the content of WG.tex files? (show in output PDF)
      - Show all the focus-areas (table)
      - Some intro about WG?
      - Table of included focus areas and Goals?
      - Anything else?
- Wg_focus-areas : new name for focus-areas latex file (instead of who.tex, try wg-common_who.tex) since 2 focus-areas can have same name in the future
    - Georg: Great idea! Good solution. +1 👍
- Renaming focus-areas in wg-common
    - https://github.com/chaoss/wg-common/issues/124
    - https://bit.ly/2ROytFz
- Pending PR: https://github.com/chaoss/wg-risk/pull/130
- Can we use docker to resolve cross platform installation issues?
    - Could be used as an easy/alternate method to replicate the automation system
    - Current dependencies that need to be installed manually and also platform dependent -
        - LaTeX
        - Pandoc
        - Git
        - Python
        - Pip packages - gitpython, pypandoc, pyyaml
- WG-Value needs to be given a heads up about removing tables and HTML from social-listening.md 
    - [1] instead of superscripts
- Extra content in focus-area READMEs for wg-evolution
    - We can remove them
- General Mentor Feedback and Suggestions

**Goals for the next week:**

- Create a handbook page describing all steps needed from (WG makes a change to a metric or creates new metric) to (translation of the change is ready in a language)
    - The steps need to describe what everyone involved in the process is expected to do
    - The handbook pages does NOT describe any automation specifics
    - Goal: Handbook page with description of steps and who does which step
- Continue standardizing the WG repos
    - Goal: PRs created for all needed changes; discussion during WG meetings (as available)
- Containerize M.A.R.S. 
    - Goal: Mentor can run M.A.R.S. on their machine
