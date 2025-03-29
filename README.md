# MAI_NLP_HateSpeech_Exercise
Exercise for the Master Ai Engineering - Natural Language Processing - Class

# Setup
conda env create -f environment.yml
NOTE: This environment is using a pytorch version that uses cuda. If the system contains no cuda device the pytorch version may needed to be changed

(We also create a requirement.txt for non conda users. This is experimental due to the fact that we extract the packages from an conda enviroment via pip list --format=freeze > requirements.txt
-> not tested)