
## Commit to GitHub 
# --> navigate to SHH directory 
git init
git add .
git commit -am "message"
git remote add origin "https://github.com/keeya-beausoleil/repo_name"
git push -u "https://github.com/keeya-beausoleil/link.git"  branch_name 


## Running MedSpec Program 
nohup python -u med_spec_loop.py med_spec_WOLV.par WOLVERINE WOLN HHZ> WOLN_medspec.log &
nohup python -u plot_med_spec.py > WOLN_plot_medspec.log &

