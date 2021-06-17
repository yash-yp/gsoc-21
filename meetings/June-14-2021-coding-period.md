# Meeting June 7, 2021

Attendees (please add yourself to this list and tell us one good thing going on in your life recently)

- Matt Germonprez 
- Kevin Lumbard
- Ritik Malik - mangoes are back
- Georg Link - enjoying summer
- Yash Prakash 
- Jaskirat Singh  

## Agenda/Notes:
- Can we share this doc in our GSoC repo, as a part of the weekly updates
    - Answer: Yes    
- Could we have a separate repo for Automation task or do we continue collaborating in our local repos
    - AI Georg: create new repo: github.com/chaoss/metric-release-automation
- Update on slack channel…
    - Yes, we can have a public Slack channel
    - This has been created
- Use of the “Provide Feedback” column for focus area tables?
    - Each metric has a >30day review period until release; in the “provide feedback” column is a link to an issue; this column should be on the website only
- Show the new workflow photo
    - Can you please add a copy of the photo here?
- Confirm YAML file structure template
    - Link: https://github.com/ritik-malik/Automated-Metrics-Release-CHAOSS/blob/main/active_user_input/WG_conf.yml
    - YML file needs to be updated for each release to include new metrics
    - The YML file is self-explanatory, well done!
- Places that would require updation for each new metric:
    - YML file
    - Focus-area tables 
- Show the focus-areas.tex file & its use (splitting code)
    - LINK: https://github.com/ritik-malik/Automated-Metrics-Release-CHAOSS/blob/main/TESTING/focus_areas.tex
    - The file will be split into one file per focus area
    - Pro: easy to update just a single file
    Requirement: the focus area name needs to match the folder name in the WG repos
    - Requirement: no two working groups may use the same focus area name because the focus area names are used without the context of the WG name
    - Question: Is there a good way to use the same file to also update the website?
    - Either way, the description of the release process needs to describe how the website is updated
    - Maybe build the focus-areas.tex file by parsing the website? 
    - Georg’s concern: adding a dependency on the website structure and template -- adding a point of failure in the automation process
    - NEW PROCESS:
        - Automatically build the focus-area.tex file by parsing the name and questions from the metric.md files
        - Goal: no manual updating of a focus-area.tex file; no duplicating question into the yml file

- Inconsistency in website focus-areas goals and that in the working groups
    - Answer: Website and repository should be the same; changes from the WG repos are the original and should be propagated to website and release PDF
- For YML files instead of listing the metrics we want in the PDF should we list the metrics we do not want?
    - Reason: This would only required updation when we do not want to include a particular metric file
    - Con
        - Reduced flexibility and hardcoding would have to be done 
        - No reorder
    - The value of sorting metrics by explicitly listing them in the YML file outweigh the overhead of updating the file
    - The anticipated overhead of updating the YML file is small and acceptable
- Confirmation on Report Structure
    - Current: https://chaoss.github.io/website/release/release-pdfs/CHAOSS-Metrics-Release-2021-03.pdf
        - WG -1
            - Focus Area-1
            - Focus Area -2  
        - WG -2
            - Focus Area- 1
            - Focus Area-2 
        - WG-1 FA -1 Metrics
        - WG-1 FA-2  Metrics
        - WG-2 FA-1 Metrics
        - WG-2 FA-2 Metrics

    - Proposed for PDF only (sections in PDF): (+1 Georg)
        - Frontmatter with full list of wgs/fas/metrics 
        - WG-1
            - Focus Area-1
                - WG-1 FA -1 Metrics
            - Focus Area-2
                - WG-1 FA-2 Metrics
        - WG-2
            - Focus Area -1
                - WG-2 FA-1 Metrics
            - Focus Area -2
                - WG-2 FA-2 Metrics
        - Backmatter    
- Directly pull the questions for the metrics from the WG, (as defined in yml) & generate the focus_areas.tex file with THAT tabular structure
