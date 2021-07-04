## Coding Period- Week 4

This week's meeting kicked off with a live demo of the automation system. The system worked perfectly and was able to perform the required tasks. We were running into some cross-platform issues as the script had been primarily tested for Linux users. Ritik suggested resolving these issues using [Docker](https://www.docker.com/). In the past 3 weeks, we had mainly focussed on the automation process. This week, we also decided to improve the translations process.

The translations community does not have any existing guidelines, hence it is difficult for them to communicate and work together since most of the discussions take place in the Asia-Pacific Meetings which occurs only twice a month.

 As per the suggestion of mentors, I created a doc that could help the existing community and allow more communities to begin translations in new languages. The document covers the following topics:

- Adding translations in a new language
- Updating translations
- Release of translated metrics

Link to document: <https://docs.google.com/document/d/10bJvsZZ7A25fsLIZbX_2P2oWyCpGBs5oTi9GKvUMKdk/edit?usp=sharing>

The document is being reviewed and still requires feedback. It will be added to the community handbook after finalization 

Additionally, I worked on the standardization process of the working group repositories. The following templates had been recently added/updated according to the project requirements:

- [Metrics](https://github.com/chaoss/metrics/blob/master/resources/metrics-template.md)
- [Focus Area READMEs](https://github.com/chaoss/governance/blob/master/templates/focus-areas.md)

Based on the above templates, I made some PRs in the working group repositories.

- Diversity, Equity, and Inclusion WG
  - Standardize focus area READMEs- [#364](https://github.com/chaoss/wg-diversity-inclusion/pull/364)
  - Rename images and add spaces- [#365](https://github.com/chaoss/wg-diversity-inclusion/pull/365)
- Evolution WG
  - Fix minor issues in metrics for proper display of PDF (MARS)- [#413](https://github.com/chaoss/wg-evolution/pull/413)
  - Standardize & remove extra content from focus-area READMEs- [#414](https://github.com/chaoss/wg-evolution/pull/414)
- Risk WG
  - Modify metrics to follow updated template- [#131](https://github.com/chaoss/wg-risk/pull/131)
- Value WG
  - Replace HTML tags and tables- [#145](https://github.com/chaoss/wg-value/pull/145)

The above PRs are necessary for the proper display of metrics when they are pulled from the remote repositories and incorporated in the release report PDF.

I plan to add some extra elements to the release report and work further on the documentation of the MARS in the next week.

