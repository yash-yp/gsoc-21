# August 2, 2021

Attendees (please add yourself to this list and tell us one good thing going on in your life recently)

- Ritik Malik -
- Kevin Lumbard
- Yash Prakash
- Georg Link - 

## Agenda/Notes:

- New MARS model -
    - Merging English and translation system into 1
    - New naming convention for yml file and coverpage
        - https://github.com/chaoss/MARS/tree/main/automation-english/active_user_input
    - New language selection menu
    - New scripts for english and translation counterparts
    - Auto-detect language and auto-select yml file and coverpage
    - Error handling + sanitized user inputs
- For Chinese Lang -
    - Needed a new LaTeX package - xeCJK ~ 842 MBs
    - New Docker image uploaded with latest tag on Docker Hub
    - https://hub.docker.com/r/ritikmalik/mars-image
    - Image size doubled up from 440 MB to 842 MB - Download size
    - Uncompressed/actual image size - 2.2 GB
- For Spanish Lang -
    - Need standardization of translations -
        - https://github.com/chaoss/translations/pull/46
        - https://github.com/chaoss/translations/pull/47
- Automation system requirements
    - YAML file in the form ⇒ `<language>_working-groups-config.yml`
    - Cover Page in the form ⇒ `<language>_cover.tex`
    - Language class to exist in table_templates.py 
- Enough theory, show a Demo!
- Satisfied? Mind a user testing?
- Translations Doc
    - Worked out answers to all questions
        - https://docs.google.com/document/d/10bJvsZZ7A25fsLIZbX_2P2oWyCpGBs5oTi9GKvUMKdk/edit#
        - Doubt regarding too many checks
    - Add the questions to the handbook page under the heading FAQ?
- CHAOSScast 

### TODO:

- Update MARS documentation
    - Add GIF for the process
- Standardizing translation repo
    - Add in translation repo README a section about requirements for adding a new language (what standard does it need to follow?)
- Flowchart for translation guidelines
- Adding translations to community handbook
- Changes to release document:
    - Only latest release notes
    - Add board members to release notes: These are the CHAOSS Governing Board members at the time of release
    - Move contributors to back, before license
- Add section to MARS Readme about how to add support for a new language