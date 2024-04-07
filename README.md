# Phishing Link Detection

This Python script is designed to detect potential phishing links by comparing URLs against a list of legitimate domains and identifying misspelled domain names. It utilizes techniques such as extracting domain parts and calculating string similarity to determine the likelihood of a URL being associated with phishing activities.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)

## Installation

To use this script, you need to have Python installed on your system. Follow these steps to set up the project:

1. Clone the repository to your local machine:
git clone git@github.com:sjarancio/phishing_link_scanner.git

2. Navigate to the project directory:
cd phishing_link_scanner

3. Install the required dependencies:
pip install tldextract
pip install python-Levenshtein

## Usage

Once you have installed the necessary dependencies, you can run the script to detect potential phishing links. Modify the `test_urls` and `legitimate_domains` variables in the script according to your requirements. Then execute the script using the following command:
python main.py

The script will analyze each URL in the `test_urls` list and print potential phishing links if detected.

## Customization

You can customize the script according to your specific needs. Here are a few suggestions:

- **Adjust Threshold**: Modify the `threshold` parameter in the `is_mispelled_domain()` function to change the similarity threshold for detecting misspelled domains.
- **Add Additional Checks**: Enhance the phishing detection logic by adding more checks, such as examining suspicious subdomains or analyzing URL structure.


