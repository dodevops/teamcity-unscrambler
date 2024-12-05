# Teamcity unscrambler

Unscrambles passwords used in Teamcity and scrambled with [default strategy](https://www.jetbrains.com/help/teamcity/teamcity-configuration-and-maintenance.html#encryption-settings)

## Requirements

* Current Python3 implementation

## Preparations

Create a virtual environment by issuing:

   python3 -m venv venv

Activate it (e.g. for bash):

   . venv/bin/activate

Install the required packages

    pip3 install -f requirements.txt

## Usage

    python3 unscramble.py <scrambled password>


