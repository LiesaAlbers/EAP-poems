# Edgar Allen Poe Poems Corpus
This repository contains a small corpus of poem titles by The American writer and poet Edgar Allen Poe. It is a collection of 17 poem titles and their years of publishing spanning Poe's career from 1829 to 1850.

### Data Collection process
The poem titles and publishing years were scraped from [poestories.com](https://poestories.com/poetry.php) using web scraping techniques with the BeautifulSoup library.

### Cleaning and Preprocessing
Both the poem titles and years of publishing were cleaned of any punctuation. Trailing whitespaces were also removed from the years of publishing.

### File Formats
#### Notebook (.ipynb)
- ⁠The file ⁠`code.ipynb` ⁠ contains all code used to realise this corpus.
  
#### CSV files (.csv)
- ⁠The file ⁠`EAP_poems.csv`⁠ contains the corpus:

    **Rows:** each row contains data on a poem.

    **Columns** (variables):

  | Header | Description |
  | ------ | ----------- |
  | ⁠`Poem Title` | The title of the poem |
  | ⁠`Publishing Year` | The year the poem was first published |


### Terms of Use
No explicit terms and conditions were stated on [poestories.com](https://poestories.com/poetry.php), nor was there a robots.txt file. 

This corpus is provided for non-commercial, research purposes only. All Rights Reserved.
