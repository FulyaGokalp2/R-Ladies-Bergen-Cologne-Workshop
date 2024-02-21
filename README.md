This repository contains materials for a workshop (Bookclub) that I recently taught. The workshop organized by R-Ladies Cologne and R-Ladies Bergen (https://www.meetup.com/rladies-cologne/events/299176858/). It includes notes and resources used during the workshop delves into Chapter 9 of the book “Building Reproducible Analytical Pipelines with R” by Bruno Rodrigues. This chapter marks the beginning of Part 2: "Write IT down," within the book.

The workshop aims to provide participants with a comprehensive understanding of the concepts outlined in Chapter 9, focusing on practical implementation. All workshop materials are housed within this designated folder.

Here are the two R files previously generated in the book and utilized again in Chapter 9: 

save_data.R: https://is.gd/7PhUjd
analysis.R: https://is.gd/X7XXJg

Please save them and add them to a folder, you may name it "housing". Instead of saving manually, you can also automize it in Terminal by using the following codes:

mkdir Housing  # Create the folder
cd Housing     # Go into that folder
wget --content-disposition https://is.gd/7PhUjd  # Download the first script
wget --content-disposition https://is.gd/X7XXJg  # Download the second script

Reading recommendations at the end of Chapter 9:

Programming with dplyr: https://dplyr.tidyverse.org/articles/programming.html
http://modern-rstats.eu/defining-your-own-functions.html#functions-that-take-columns-of-data-as-arguments
