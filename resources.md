## On managing a data analysis project

https://rajlaboratory.blogspot.com/2017/08/figure-scripting-and-how-we-organize.html

Following this, how one should organize a data analysis project:

- paper
    - extractionScripts: 
        * contains scripts to pull out numbers from data and store them for plot making
        * Has a master script `extractAll.py` to run before submission to make sure everything works.
    - extractedData: 
        * *.csv files
    - plotScripts
    - graphs
    - finalFigures: 
        * contains the illustrator files.
        * along with each figure (e.g. fig1.ai) there is a (fig1readme.txt) says exactly what eps or pdf files from the graphs folders ended up in e.g. fig1f

- data
    (For this part I would follow what *Neuroblueprint* did, at least for a system neuroscience project)