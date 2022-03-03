## da_lego_evolution_analysis
## Title
#### Analysing Evolution for Lego

## Problem Statement
#### You are a Data Analyst at Lego working with the Sales/Customer Success teams. The Accout Executive responsible for the Star Wars partnership has asked for specific information in preparation for their meeting with the Star Wars team. Although Star Wars _was_ critical to the survival of the brand, Lego has since introduced a wide variety of licensed sets over subsequent years.
-   ##### What percentage of all licensed sets ever released were Star Wars themed ?
-   ##### In which year was Star Wars _not_ the most popular licensed theme (in terms of number of sets released that year) ?

## Datasets
-   #### lego_sets.csv
    -   **set_num**: code unique to each set.
    -   **set_name**
    -   **year**: year of release of that set
    -   **num_parts**: number of parts contained in the set.
    -   **theme_name**: name of _sub\_theme_ of set.
    -   **parent_theme**: name of parent theme set belong to.
-   #### parent_themes.csv
    -   **id**: unique code for theme.
    -   **name**: name of parent theme.
    -   **is_licensed**: (boolean) specifying whether theme is licensed