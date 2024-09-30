[![orcid](https://img.shields.io/badge/ORCID-0000--0002--3929--788X-green?style=plastic&logo=orcid&url=https://orcid.org/0000-0002-3929-788X)](https://orcid.org/0000-0002-3929-788X)

# Analysis and Detection of Differences in Spoken User Behaviors between Autonomous and Wizard-of-Oz Systems
This repository contains the data and code for "Analysis and Detection of Differences in Spoken User Behaviors between Autonomous and Wizard-of-Oz Systems" by Mikey Elmers, Koji Inoue, Divesh Lala, Keiko Ochi, and Tatsuya Kawahara for the 27th International Conference of the Oriental COCOSDA (O-COCOSDA '24), Hsinchu, Taiwan, October 17-19. This study examined users' behavioral differences in a large corpus of Japanese human-robot interactions, comparing interactions with a tele-operated robot to those with an autonomous dialogue system.


## Table Of Contents

- [Instructions](#instructions)
- [Directory information](#directory-information)
    * [data](#data)
    * [docs](#docs)
    * [output](#output)
    * [scripts](#scripts)
- [Issues/comments/suggestions](#issuescommentssuggestions)
- [License](#license)

## Instructions
You can view the .html result files in the `output/` directory. If you would like to re-run part or all of the analysis please do the following:

1. Clone repository.
   ```bash
   git clone https://github.com/MikeyElmers/paper_ococosda24.git
   cd paper_ococosda24/
   ```
2. Open the `paper_ococosda24.Rproj` file.
3. Open and run the `scripts/renvRestore.R` file or use the following code in the terminal to install project dependencies.
   ```bash
   Rscript scripts/00_renvRestore.R 
   ```
4. Open the individual .`Rmd` files in the scripts directory.

## Directory Information
### `data`
- `data.csv`: cleaned data with participant information removed

### `docs`
- `elmers_ococosda24_poster.pdf`: O-COCOSDA '24 poster submission

### `output`
- `plots`: Directory with modeling correlation plots
- `01_analysis.html`: Output of 01_analysis.Rmd file
- `02_model_acoustics.html`: Output of 02_model_acoustics.Rmd file
- `02_model_full.html`: Output of 02_model_full.Rmd file
- `02_model_linguistics.html`: Output of 02_model_linguistics.Rmd file
- `sessionInfo.txt`: R session info

### `scripts`
- `00_renvRestore.R`: Restores project dependencies
- `01_analysis.Rmd`: Descriptive and inferential data analysis
- `02_model_acoustics.Rmd`: Modeling using only acoustic features
- `02_model_full.Rmd`: Modeling using all features
- `02_model_linguistics.Rmd`: Modeling using only linguistic features

## Issues/Comments/Suggestions
Please use the [issue tracker](https://github.com/MikeyElmers/paper_ococosda24/issues). 

## License
This code is licensed under the terms of the MIT license. See [LICENSE.md](https://github.com/MikeyElmers/paper_ococosda24/blob/master/LICENSE.md) 
