# collectionbuilder-sample-data

This repository contains demo metadata for various CollectionBuilder templates. 

- "psychiana_cbdemo_csv.csv" is prepped to work with CollectionBuilder-CSV. 
    - 67 items, mix of formats (image, pdf, audio, video)
    - All items are links hosted at University of Idaho Library, so you do not need any objects!
    - place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
    - Items from the [Psychiana Digital Collection](https://www.lib.uidaho.edu/digital/psychiana/)
- "psychiana_cbdemo_gh.csv" is prepped to work with CollectionBuilder-GH or Sheets. 
    - 67 items, mix of formats (image, pdf, audio, video)
    - All items are links hosted at University of Idaho Library, so you do not need any objects!
    - On GH, place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
    - On Sheets, configure the `metadata-csv` value in your "_config.yml" to `https://raw.githubusercontent.com/CollectionBuilder/collectionbuilder-sample-data/main/psychiana_cbdemo_gh.csv`.
    - Items from the [Psychiana Digital Collection](https://www.lib.uidaho.edu/digital/psychiana/)
- "watkins_cbdemo_gh.csv" is prepped to work with CollectionBuilder-GH or Sheets. 
    - 80 items, images only
    - All items are links hosted at University of Idaho Library, so you do not need any objects!
    - On GH, place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
    - On Sheets, configure the `metadata-csv` value in your "_config.yml" to `https://raw.githubusercontent.com/CollectionBuilder/collectionbuilder-sample-data/main/watkins_cbdemo_gh.csv`.
    - Items from the [Carleton Watkins Mine Interiors Collection](https://www.lib.uidaho.edu/digital/watkins/)
- "idaho_cities_cbdemo_urls.csv" is prepped to work with CollectionBuilder-GH, -Sheets, or -CSV.
    - 371 items, images only
    - All items are links hosted at University of Idaho Library, so you do not need any objects! 
    - On GH or CSV, place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
    - On Sheets, configure the `metadata-csv` value in your "_config.yml" to `https://raw.githubusercontent.com/CollectionBuilder/collectionbuilder-sample-data/main/idaho_cities_cbdemo_urls.csv`.
    - Items from [Idaho Cities and Towns Collection](https://www.lib.uidaho.edu/digital/cities/)
- "nwpostcards_cbdemo_urls.csv" is prepped to work with CollectionBuilder-GH or -CSV. 
    - 192 items, mix of image and multiple types
    - All items are links hosted at University of Idaho Library, so you do not need any objects! 
    - On GH or CSV, place the demo csv in your project's "_data" folder, and configure the `metadata` value in your "_config.yml".
    - On Sheets, configure the `metadata-csv` value in your "_config.yml" to `https://raw.githubusercontent.com/CollectionBuilder/collectionbuilder-sample-data/main/nwpostcards_cbdemo_urls.csv`.
    - Items from [Northwest Historical Postcards Collection](https://www.lib.uidaho.edu/digital/postcards/)

*Note:* CB-Sheets uses the "psychiana_cbdemo_gh.csv", "watkins_cbdemo_gh.csv", and "idaho_cities_cbdemo_urls.csv" files from this repository as demo options.
