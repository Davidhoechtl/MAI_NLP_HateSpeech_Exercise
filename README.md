# MAI_NLP_HateSpeech_Exercise
Exercise for the Master Ai Engineering - Natural Language Processing - Class

# Setup
conda env create -f environment_GPU.yml for systems with cuda device.
conda env create -f environment_CPU.yml for all other systems

(We also create a requirement_CPU.txt for non conda users. This is experimental due to the fact that we extract the packages from an conda enviroment via pip list --format=freeze > requirements.txt
-> not tested)

# Credit for pretrained Models
-> https://huggingface.co/distilbert/distilbert-base-uncased
-> https://huggingface.co/Hate-speech-CNERG/dehatebert-mono-english
