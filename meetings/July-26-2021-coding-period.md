# July 26, 2021

Attendees (please add yourself to this list and tell us one good thing going on in your life recently)

- Kevin Lumbard
- Ritik Malik: watching Loki
- Yash Prakash
- Matt Germonprez
- Georg Link: First day back from vacation

## Agenda/Notes:

- Sent update on mailing list for MARS user testing of Docker image
    - Review: working fine on Nico’s system (new guy)
    - Mentor reviews: (due)
        - AI Georg: find email about this and do the review of MARS
        - AI Kevin: review MARS
- Another working group standardized! - wg-common
    - Thanks Kevin for this as well as the website migration
    - Focus-areas table accidentally got removed:
    - https://github.com/chaoss/wg-common/pull/134: Done
- PRs for standardization of Chinese Metrics
    - All Accepted 
- Documentation update - (include cover.tex in README) [AI Ritik] - Done
- Need to add newly released metrics to yml file?
- Model for translations MARS
    - User Input language-directory-name, e.g. (chinese, spanish…)
        - To provide input we can either take full language names or options 1,2, etc.
            - Need to create a dynamic structure to detect languages present in translation repository
            - Display them as options - 1,2, etc.
            - Auto-detect the yml file for that particular language - throw warning and exit if no yml found OR not following the correct naming convention
    - User Input YAML filename  
        - Separate yml file for each language
        - Need a naming convention for yml file
    - User Input cover page filename
- Do we want to standardize Spanish metrics and README?
    - Do we have an active community for spanish translations?
    - Yes
- Add Translation updates…. [AI Yash]
    - https://docs.google.com/document/d/10bJvsZZ7A25fsLIZbX_2P2oWyCpGBs5oTi9GKvUMKdk/edit#
- Create checklist of process that should be done by the WG to alert translations community and the 
    - https://github.com/chaoss/metrics/issues/193
 
## TODOs:

- Continue on MARS documentation
- Make structure for translations directory in MARS
- Write scripts for yml, main.py, Docker for translations
- Update chinese translations
- Update spanish translations
