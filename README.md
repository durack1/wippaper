Thsi is the git repo for the WIP paper to be submitted to GMD special issue on CMIP6.

To create your own copy, go to your working directory of choice.

  git clone https://github.com/balaji-gfdl/wippaper.git

then your files are in the subdirectory wippaper. You don't need a github account to download the paper, but you do need it to submit changes. Please send me the github id to add as a collaborator.

Please edit wippaper.tex (don't touch wippaper.tex.save... I use it as the reference for 'track changes' and will update it when I want to 'accept changes').

Please make changes to this file, and submit the changes in the usual manner.

git commit -m "message" -a
git push

If the push fails, it's because someone else has committed changes. You will have to 'git pull' the changes, merge and resolve any conflicts, and commit+push the updated version.

There is only the master branch (trunk) and every collaborator will have commit privileges. (Don't worry... the real master copy is in my private clone on my laptop!)

If adding figures, please send it to me separately and I'll add it. Remember to preface the includegraphics with "images/..." such as

      \includegraphics[width=175mm]{images/esgf-map-2017.png}





