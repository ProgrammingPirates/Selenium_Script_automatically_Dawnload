# PDF Downloader

This Python script automates the process of downloading PDF files from an ArXiv webpage using Selenium and threading.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Dependencies](#dependencies)
- [Disclaimer](#disclaimer)

## Overview

The script utilizes Selenium, a web automation tool, to navigate through an ArXiv webpage and extract links to PDF files. Threading is employed to speed up the download process by processing multiple links concurrently. The downloaded PDF files are saved in the same directory as the script.

## Installation

1. **Python and Libraries**: Make sure you have Python installed on your system. Install the required libraries listed in `requirements.txt` by running the following command:
    ```
    pip install -r requirements.txt
    ```

2. **WebDriver**: Download the appropriate WebDriver for your browser. This script uses Chrome WebDriver, so ensure you have it downloaded and placed in your system PATH or specify its location in the script.

## Usage

1. **Run the Script**: Execute the script by running `python pdf_downloader.py` in your terminal or command prompt. Replace `pdf_downloader.py` with the actual name of your script.

2. **Follow Instructions**: The script will open a Chrome browser window and navigate to the specified ArXiv webpage. It will then start downloading PDF files automatically.

3. **Monitor Progress**: You can monitor the progress of the script in the terminal or command prompt. It will display messages indicating the status of the download process.

4. **Completion**: Once all PDF files have been downloaded, the script will automatically close the browser window.

## Customization

- **URL**: You can customize the `url` variable in the script to target a different ArXiv webpage.
- **Chunk Size**: Adjust the `chunk_size` variable to control the number of links processed by each thread.

## Dependencies

- **Selenium**: For web automation.
- **Requests**: For making HTTP requests.
- **Threading**: For concurrent processing of links.

