# Community Bonding Phase Summary

I have created a report of the work done and project updates till the end of the community bonding period.

I will be creating a public repository that will house the automation system.

The project discussions will be held on Google Meet every Monday at 9:00 AM CDT / 2:00 PM UTC / 7:30 PM IST.

Other than that, I would be using a public slack channel in the CHAOSS-community workspace to constantly stay in touch with the mentors.

 Further, I'll be creating weekly blogs/reports of the work done during the coding period. 

Note:- This document summarizes the work done till the end of the community bonding period.

## Project Updates

### Standardization of WG repos

  - The working group repositories did not have a standard structure. I particularly focused on [Common Metrics](https://github.com/chaoss/wg-common), [DEI](https://github.com/chaoss/wg-diversity-inclusion), and [Evolution](https://github.com/chaoss/wg-evolution) working groups.
  - Having a standard structure was crucial to the project and would simplify the automation of the metrics release.
  - I changed the structure of the repositories according to the proposed template
  - The incorporation of images was earlier done using HTML, absolute paths, Imgur links, etc. I changed and standardized this to a relative markdown format.  
  - The metric files were classified in their focus areas and images were included by adding a subdirectory for each focus area. The names of images and metric files were changed to follow a set convention.

  - Related PRs: [wg-common/pull/112](https://github.com/chaoss/wg-common/pull/112), [wg-diversity-inclusion/pull/356](https://github.com/chaoss/wg-diversity-inclusion/pull/356), [wg-evolution/pull/406](https://github.com/chaoss/wg-evolution/pull/406), [wg-value/pull/140](https://github.com/chaoss/wg-value/pull/140)

### Organization of translated metrics

  - The translations of metrics are recorded in the translations repository. The metrics currently exist in two translated languages:
    
    - Chinese
    - Spanish
  - The metrics in these directories were not organized and did not follow a naming pattern.
  - Since the project involves the automation of the translations metrics release, it only made sense to restructure the translations in the same manner as the original metrics. 
  - I added the images from the original working group repos and incorporated them in the translated markdowns.
  - In addition, I renamed the metrics and organized them into their respective focus areas for Spanish as well Chinese versions.
  - Related PRs: [translations/pull/18](https://github.com/chaoss/translations/pull/18), [translations/pull/17](https://github.com/chaoss/translations/pull/17)

### Standardization of WG files

  - The working group repositories contain some files that can be standardized. The complete details can be found [here](https://github.com/chaoss/governance/issues/277).
  - The process of file standardization required collecting feedback from each working group.
  - I attended the meetings for each WG and tried to create some templates based on their reviews.
  - This task is not directly related to the GSoC project but it helped me bond well with community members and understand the workflow of each working group.

  - Related PRs: [governance/pull/278](https://github.com/chaoss/governance/pull/278), [wg-common/pull/121](https://github.com/chaoss/wg-common/pull/121)

### Approach for the automation systems

  - I would be working together with [Ritik Malik](https://github.com/ritik-malik) who has been selected for the same project idea. I would primarily be focussing on the automated release of the translated metrics.

  - The project would involve us collaborating to create an efficient automation system as per the requirements.

  - Since we have different approaches to the project, we would be discussing and forming a common approach as per the advice of the mentors.

  - I have also been familiarizing myself with the LaTeX file format since this will be the intermediate file format between the markdowns and the PDF.
