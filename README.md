# leaf-trait-responses-to-climate-change
Analysis for responses of Australian plant leaf trait changes to changes in climate metrics

This analysis is for the mansucript entitled: Leaf morphological traits show greater responses to changes in climate than leaf physiological traits and gas exchange variables

Data will be made freely available upon publication

There are 5 datasets (available on dryad) and 3 analysis scripts available

The 1st Rmarkdown file: "reshaping data for leaf analysis" takes all the raw data of measured leaf traits and creates a dataframe (and csv file) with all trait responses (calculated as the log odds response ratio of means) and all variances for trait changes with all changes in climate metrics (calculated as the difference between years for temperature metrics and the log odds repsonse ratio of means for precipitation metrics)

The 2nd and 3rd Rmarkdown file: 
"leaf analyses - two way leaf morphs"
"leaf analyses - photosynthesis"

Both files are for the analysis of change in mean temperature and change in mean precipitation with change in leaf traits (morphological and photosynthetic)

THe 4th Rmarkdown file:"PCA for leaf economics" analyses the photosynthetic data, LMA data and nitrogen data to determine a principal component for 'leaf economy'

The 5th Rmarkdown file: "leaf economics analysis" analyses the principal component of leaf economy against mean temperature and mean precipitation

The 6th Rmarkdown file: "meta analysis all leaf traits and all climate variables" analyses all the measured leaf traits in a meta-analytic multi model selction model framework with variable inference to determine if there are any relationships between all cliamte change metrics and all leaf trait changes.

The 7th Rmarkdown file: "Analysis of growth form and leaf traits.Rmd" analyses the absolute average trait change across all leaf traits for each species against the categorical predictor of growth form
