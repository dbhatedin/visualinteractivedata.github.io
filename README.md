# Website of the Visual+Interactive Data group at the University of Edinburgh

[visualinteractivedata.github.io](https://visualinteractivedata.github.io/)

## Adding new publications

-   The publications page is located at [visualinteractivedata.github.io/publications](https://visualinteractivedata.github.io/publications).
-   To add a new publication, add it to the CSV file in `_data/publications.csv`. Publications are displayed in the order that they are stored in the file, so add a row at the top (underneath the header row) to have a new publication show up at the top of the list.
-   You can/should provide the following information for each paper:
    -   `title`
    -   `authors`
    -   `journal_conf`: the journal or conference it was published at
    -   `year`: year of publication
    -   `img`: (optional) an image to be displayed alongside the publication. Place the image into the folder `figures/` and add the filename into this field.
    -   `img_alt`: Alt text for the image, i.e., an image description for visually impaired people as well as if the image cannot be rendered for any reason.
    -   `paperlink`: Link to the paper, e.g., on arxiv or the DOI link. Alternatively, place the pdf in the `papers` folder and add `papers/filename.pdf` here.
    -   `weblink`: If there is a companion website for the paper, add the link here.
    -   `videolink`: If there is a recorded talk or other video for the paper, add the link here.
    -   `awards`: If the paper has won any awards, add them here using the text you would like displayed, for example "BEST PAPER HONORABLE MENTION"

## How to work on this site locally

-   Make sure you have [Ruby and Jekyll installed](https://jekyllrb.com/docs/installation/)
-   Clone this repo to your computer
-   Open a command line in that folder, run "bundle update" then "bundle exec jekyll serve"
-   The website should now be available at localhost:4000

_This works on my (Sarah's) Windows setup - cannot vouch for anything else, but this is the general principle of running Jekyll sites locally_
