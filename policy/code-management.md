<!-- Migrated from OSF szch3, wiki page "Code Management Practices". Original: https://osf.io/szch3/wiki/Code%20Management%20Practices/ · last edited 2019-09-11. -->

# Code Management Practices

The lab maintains a [Github organization][1] that houses public, general shared code. This includes experimental control tools developed and extended in the lab, spike train and local field potential analysis tools and novel methods, and manuscript repos.  

You will be expected to maintain your own repo (if you are developing or using any of this code), and follow [git best practices][2]. Or at minimum, some git practice...here is a good [git basics][3] guide to keep handy. If you develop some code in your own repo that we'd like to make a lab tool, we'll fork it and maintain it in the Denman Lab organization.  


The lab maintains a shared codebase, dlab, which contains a python package of analysis and plotting functions, example .ipynbs, and project folders for dashboards and other software packages. Changes to this shared resource can and should be made by all lab members via pull requests, which are reviewd at qaurterly code review meetings. Instructions for making your changes into a pull request are on [elab here](https://elabftw.denmanlab.org/database.php?mode=view&id=876).

The package can be found here: https://github.com/denmanlab/dlab
It can also be pip installed `pip install denmanlab` [from pypi](https://pypi.org/project/denmanlab/). Releases are approximately quarterly, with code reviews.



  [1]: https://github.com/denmanlab
  [2]: https://www.git-tower.com/learn/git/ebook/en/command-line/appendix/best-practices
  [3]: http://rogerdudler.github.io/git-guide/
