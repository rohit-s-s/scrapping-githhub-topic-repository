# Web Scraping GitHub Topics
This is a Python web scraping project that extracts information from the GitHub Topics page (https://github.com/topics). The script retrieves a list of topics and, for each topic, gathers the topic title, topic page URL, and topic description. Additionally, for each topic, it collects the top 25 repositories within the topic from the topic page, and for each repository, it grabs the repository name, username, stars, and repository URL.

## Installation
1.Ensure you have Python 3.x installed on your system.

2.Clone this repository to your local machine:

    git clone https://github.com/rohit-s-s/scrapping-githhub-topic-repository
3.Navigate to the project directory:

    cd scrapping_github_topics_repositories.ipynb
4.Install the required dependencies by running:

    pip install requests
    pip install beautifulsoup4
    pip install pandas
## Usage
run the web scraping script

The script will start scraping the GitHub Topics page and collect the required information for each topic and repository. The data will be stored in CSV files, with one CSV file for each topic. The CSV files will be saved in the data directory within the project folder.

## CSV Format
The CSV files will follow the format as shown below:

    Topic Title,Topic URL,Topic Description,Repository Name,Username,Stars,Repository URL
The CSV files will contain data for the top 25 repositories within each topic, along with their corresponding information.

Note
GitHub's website structure may change over time, which could affect the web scraping process. The script may require adjustments if there are any significant changes to the website's layout or class names.
