# SyntheticPassportsGenerateScript

This program allows to generate a dataset of RF passports for machine learning.

## Installation

    1) Create virtual environment:
        conda create -n <your_virtual_environment_name> python=3.7 -y
        conda activate <your_virtual_environment_name>
        
    2) Build virtual environment:
        pip install -r requirements.txt
        
## Prerequisites

* Installed [Python](https://www.python.org/downloads/) >= 3.6 or [Anaconda](https://www.anaconda.com/products/individual) >= 4.10.1
* Web Browser: [Google Chrome](https://www.google.com/chrome) or [Mozilla Firefox](https://www.mozilla.org/en/firefox/new/)
* Dowload web driver to work path (see [ChromeDriver](https://chromedriver.chromium.org/downloads) or [mozilla/geckodriver](https://github.com/mozilla/geckodriver/releases) for more information)

## Generation

    1) Run script:
    python main.py --output_path <output path> --number_images <number of augmented images>
For more information launch `python generate_passports.py -h`. 

