# Product Scraping and Data Comparison Project

## Overview

This project is a Python-based solution for web scraping, data comparison, and exporting results to Excel files. Developed for specific work-related tasks, it involves extracting information from websites, comparing scraped data, and exporting findings in an Excel format. The script uses proxies and user agents to fetch data efficiently while minimizing the risk of bans.

## Features

- **Web Scraping**: Extracts data from specified URLs using BeautifulSoup.
- **Proxy and User-Agent Rotation**: Reduces the chance of being flagged as a bot.
- **Data Comparison**: Compares extracted data from different sources.
- **Excel Export**: Outputs comparison results into an Excel file with clear formatting.

## Installation

To set up this project, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/matemcodes/casp.git
    cd casp
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the script, use the following command in the project directory:

```bash
python main.py
```

Ensure the resources directory contains user_agents.txt, proxies.txt, base_pages.txt, and compare_pages.txt files with the necessary data.
Make sure to use the correct format in the base and compare pages. If you don't want to use proxies, leave the file empty.

## Contributing

This project is open for contributions. If you have suggestions for improvement or encounter any issues, please feel free to open an issue or submit a pull request.

## Disclaimer

This script was created for my specific work-related projects. If you plan to use or adapt this script for your purposes, please ensure it aligns with the terms of service of the websites you are scraping and complies with legal requirements. The author is not responsible for any misuse of this tool or any violations of web scraping policies.

## License
Distributed under the MIT License. See LICENSE for more information.

## Contact
If you're interested in this or you'd like a specific solution for your need, feel free to contact me at: github@matem.hu
