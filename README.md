# collectionbuilder-sample-data

This repository contains demo metadata for various CollectionBuilder templates. 

- "psychiana_cbdemo_csv.csv" is prepped to work with CollectionBuilder-CSV. All files links hosted at University of Idaho Library, so you do not need any objects!
    - place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
- "psychiana_cbdemo_gh.csv" is prepped to work with CollectionBuilder-GH or Sheets. All files links hosted at University of Idaho Library, so you do not need any objects!
    - On GH, place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
    - On Sheets, configure the `metadata-csv` value in your "_config.yml" to `https://raw.githubusercontent.com/CollectionBuilder/collectionbuilder-sample-data/master/psychiana_cbdemo_gh.csv`.
- "contentdm/" contains collections each with a metadata CSV, _config.yml, and theme.yml to work with CollectionBuilder-CONTENTdm.
    - place the demo csv in your project's "_data" folder. Use the "_config.yml" and "theme.yml" to replace the template version in your repository.
