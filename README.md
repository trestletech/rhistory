Analysis of Public .Rhistory Files
==================================

The scripts in this repo are used to analyze public .Rhistory files to see which packages and functions are most commonly used, among other things.

The analysis can be seen online at http://trestletechnology.net/2013/02/analysis-of-public-rhistory-files/ .

Identification and Download of Candidate Files
----------------------------------------------

We can use GitHub's Advanced Search abilities to identify files ending in .Rhistory, then use [ghrabber](https://github.com/cortesi/ghrabber) to download them using the command:

    ./ghrabber.py "extension:Rhistory"
    
Be sure to check out the original post that inspired this analysis and wrote the above Python script: http://corte.si/posts/hacks/github-shhistory/index.html 
