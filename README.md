# Telegram data analysis

An analysis of personal data downloaded from Telegram

This project is a university project which aim was to practice exploratory data analysis on personal Telegram data.
It uses [telegram-data-collection](https://github.com/SanGreel/telegram-data-collection) for data collection
and [telegram-dialogs-analysis-v2](https://github.com/SanGreel/telegram-dialogs-analysis-v2) for data merging and basic
data analysis.

## How to reuse?

1. Download your Telegram data into a folder named `data` using instructions in [this repo](https://github.com/SanGreel/telegram-data-collection). 
Please note that this will take a while!
2. Fork this repository or make its local clone.
3. Merge data by running all cells in `merge_data.ipynb`.
4. Look at some general stats by running all cells in `data_overview.ipynb`.
Substitute some specific data with your own (like your TG id, or the names of dialogs) where needed
5. Perform a deeper analysis of your data using `analysis.ipynb`.
Again, don't forget to change to your personal specific data when needed.
Some steps will most likely take a substantial amount of time, so be prepared!
6. Add, modify, remove any code you like. Experiment!