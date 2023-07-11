# Introduction
This is a tiny machine learning demo which covers the relavant neccesary steps included: raw dataset loding, data proprocessing, targeting params calculation, etc. In the source code we show the necessary steps for calculating f1-score of Tuesdays datas. The similar mindset is also transferrable if there's few more targets to get. Feel free to take and enjoy!

# Files
- [dataset.psv](dataset.psv): This is the dummy dataset which concludes the necessary fields. Each date's data covered as a single record in the dataset. In following we also have the true value of targeting y and it's estimation of y_hat.
- [main.py](main.py): This file is the main one to run for the overall process. The codes in main.py show the overall processes from higher view. We can see the main steps showing the dataset loading, data proprecessing, f1-score calculation and output results. Nomally there would be more insteresting if some following visualisations involved which supported by library like [matplotlib](https://matplotlib.org/stable/tutorials/index.html) but unfortunatly it's not included in this repository for the moment. Luckily there're fairly enorgh public resources over the internet showing how to achieve these works.
- [solution.py](solution.py): This one covers the detailed implemements of related main steps which running in the `main.py`.

# Dependencies
- python
- numpy
- csv
- datetime
