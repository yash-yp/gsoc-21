# Coding Period- Week 8

The weekly meeting was a whirlwind of activity. We discussed the translations automation system's approach. We had intended to develop separate systems for English and translations at first. Georg recommended that we combine them into a single entity. We also chose to build a dynamic model that would allow us to simply add translations in new languages.

The week started with the restructuring of MARS. This made it simple to accommodate translations.

For the files that are used as input to the automation system, we established some naming conventions:

```
<language>_working-groups-config.yml
<language>_cover.tex
```

We also introduced three checks to the script for translations:

1. Check that the given language's YAML file exists.
2. Check that the language's cover file exists.
3. Check that the table templates are available in the desired language.

Since we're dynamically creating the tables it is necessary for the templates to exist in the chosen language.

A small issue that I find worth mentioning was that earlier we used the colon (`:`) as a delimiter. The Chinese translations use another colon (`：`). These have different ASCII values due to which we faced some trouble in extracting the goal and question from the markdowns. We now employ a list of possible delimiters for this purpose.

Once the scripts were ready, Ritik containerized the new MARS structure on Docker.

The system works in the following way:

- Ask for user input -> English or Translations
- Clone the required repositories depending on the input
- Detect the available languages
- Search for appropriate YAML and cover file
- Begin the conversion process

We have added support for the Chinese translations, we will to further extend it to Spanish translations after their standardization and discussion with the mentors.

I also had a very fruitful discussion about the metrics translation process in the Asia Pacific call. We were able to iron out all the process's kinks. After a final review from the community, I plan to add it to the handbook in the following week.
