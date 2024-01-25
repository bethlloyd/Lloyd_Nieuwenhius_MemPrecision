# Code and processed data from: 'The effect of reward-induced arousal on the success and precision of episodic memory retrieval'
ref: Lloyd, B., Nieuwenhuis, S. The effect of reward-induced arousal on the success and precision of episodic memory retrieval. Sci Rep 14, 2105 (2024). https://doi.org/10.1038/s41598-024-52486-6

## Data preprocessing script: 

MemPrecision_process_data.ipynb

- This script feeds in the raw behavioural data, processed pupil data (ran through default setttings in https://github.com/lindvoo/PupCor). 
- Runs further processing on pupil data and carries out all trial/run/sub exclusions
- Prepares the data in format that can be analysed/plotted.

## Data analysis script: 

MemPrecision_analyse_data.Rmd

- This script loads in the processed data
- Fits the mixture model to the behavioural data
- Runs statistics and plot behaviouoral data
- Runs lmes on behavioural + pupil data (and some plots the effects found from these models) 



For any questions, please contact: b.lloyd@fsw.leidenuniv.nl
Also, for access to the raw data please contact: b.lloyd@fsw.leidenuniv.nl


This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
