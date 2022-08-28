# notebook data cleaner

this notebook is dedicated to clean personal data from the results of notebooks before committing them on a public spaces such as github. 

# pain point:

It's possible to push on github sensible information located on the results of Notebook

I quickly coded a prototype that deletes all the results-block of a notebook before puhing to github for data privacy

I wonder if there is functionality using jupyter notebook which already does that (or a CI/CD tool), otherwise,if you manifest your interest, I will develop the idea. 

# technical details:

simple script which empty the output boxes from the ipynb file

#  possible improvements:

- do the same for file-path in the code
- create a web interface to just drag and drop your file
