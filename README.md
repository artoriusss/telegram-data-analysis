# Telegram Propaganda Dataset Analysis 

This repository contains a research project that aims to investigate data collected from russian telegram channels. Here you can find an example codebase that you can use to research your telegram data: unfoutunately, I cannot provide the data I used for this project, but you can use the code to analyze your own data.

## Installation

To install the required packages, I highly recommend using `uv` for managing a virtual environment and dependencies. If you don't have it installed, you can do so by running:

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

After that, feel free to clone the repository and install the dependencies:

```bash
git clone
cd telegram-propaganda-dataset-analysis
```

```bash
uv sync
```

Now you're ready to go! 

## Usage
To use this project's code, you need to have a dataset of telegram messages in a `.csv` format. Please name it as `tg-channels.csv` and place it in the `data` folder. After that, you should be able to run the code in the `notebooks` folder. 