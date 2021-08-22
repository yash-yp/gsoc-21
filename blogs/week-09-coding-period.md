# Coding Period- Week 9

The weekly meeting included discussions primarily about MARS documentation, user testing, and translation guidelines.

We had successfully incorporated the translation workflow into the same model.

The next step was to write instructions on how a user could begin operating MARS and use all of its associated features.

We created a new guide for adding language support to MARS. The mentors decided that the page with the Release Notes and Board Members should be added at the end of the PDF rather than at the beginning. These minor and simple tasks were initially completed.

We asked the mentors to proceed with the user once this was completed.

The script worked flawlessly on Ubuntu, but we ran into some Docker issues on MacOS. However, the mentors provided some solutions, which we were able to implement.

They also suggested some changes that could improve MARS's performance. Among these were to

> Merge “english_release.py” and “translations_release.py” into 1 single file
> 
> Add new “repo-location” parameter in yml config file, to point to the location of “focus-areas” in the repo
> 
> Make a “words.yml” in “passive_user_input” which contains a dictionary for language translations for words — focus-areas, goal, metric, question, TOC, etc.
> 
> Remove “table_templates.py” and make 3 new “.tex” templates in “passive_user_input”
>
> Giving some meaningful names to the sanity checks in scripts
>
> Improve documentation in code and giving files some more descriptive names

This meant that what would have been a free week 10 turned into one of the busiest ones.
