# String_Translations_Master
Multilingual Machine Translation is a computer system that translates text from one language to another. Machine learning can help to learn from large amounts of data, adapt to new languages and domains, and generate fluent and natural translations.

<!--  This site was created by Dinusha Salith Perera  -->

# String Translations

This repository contains scripts to automatically generate string translations for an iOS, Android and web application.

## Adding a New Translation

Translations for all applications can be found in the excel file Translations.xlsx. 

To add a new translation please add the phrase in all languages and a key for each required platform to this file and run one of the generation scripts to create new localized files for each application. 

Final output for use in each application can be found organized for each platform within the output directory.


## Getting Started

Install dependencies
``` bash
npm i
```

Generate translations for all applications
``` bash
npm run generate
```


## Scripts

Generate translations for iOS
``` bash
npm run generate:ios
```

Generate translations for Android
``` bash
npm run generate:android
```

Generate translations for Web
``` bash
npm run generate:web
```
