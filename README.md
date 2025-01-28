# Adzuna_Job_Vacancies

## Project Overview

The Adzuna Job Vacancies project is a web scraping application that extracts job listings from the Adzuna website for the field of Artificial Intelligence in India. The tool utilizes Selenium for browser automation to navigate through job listings, gather relevant details, and store them in a structured format for further analysis.

## Requirements

To run this project, you will need the following packages and dependencies:

- Python 3.x
- Selenium (for web automation)
- Pandas (for data manipulation)
- Regular Expressions (re module)

You can install the required packages using pip:
```bash
pip install selenium pandas
```

Additionally, ensure that you have the appropriate WebDriver for your browser (I have used Microsoft Edge) installed on your system.

## Steps to Run the Project

1. **Clone the Repository:**
   Clone this repository to your local machine using:
```bash
https://github.com/PRANAYBHUMAGOUNI/
```

2. **Navigate to Project Directory:**
Change your directory to the project folder:
```bash
https://github.com/PRANAYBHUMAGOUNI/Adzuna_Job_Vacancies/
```

3. **Install Dependencies:**
Ensure all required packages are installed by running:
```bash
pip install -r requirements.txt
```

4. **Set Up WebDriver:**
Download and set up the Microsoft Edge WebDriver. Specify its path in the code where indicated.

5. **Run Adzuna_Job_Vacancies.ipynb:**
Execute the script to start scraping job listings


6. **View Results:**
The job listings will be printed in a DataFrame format in the console, displaying details such as job title, company name, location, job description, and application link.

## Approach

The approach taken in this project includes:

- **Web Scraping:** Utilizing Selenium to automate browser actions such as scrolling and clicking through pages to collect job data.
- **Data Extraction:** Extracting relevant details from each job listing using XPath and CSS selectors.
- **Data Storage:** Storing extracted data in a Pandas DataFrame for easy manipulation and analysis.
- **Error Handling:** Implementing try-except blocks to manage potential errors during scraping and navigation.

## Sample Output

Upon running the Adzuna_Job_Vacancies.ipynb, you should see output similar to the following:

| Job Title                                 | Company Name                          | Location                             | Job Description                                     | Application Link                           |
|-------------------------------------------|--------------------------------------|--------------------------------------|----------------------------------------------------|--------------------------------------------|
| Senior Software Engineer, AI/ML           | VERANTOS                             | PUNE                                 | ... data sources and generates evidence with t...  | [Link](https://www.adzuna.in/details/5026923483?title...) |
| IT Security Analyst                        | NEXUS COGNITIVE TECHNOLOGIES        | MAHARASHTRA, IND                     | , strategic decisions that drive growth and in...  | [Link](https://www.adzuna.in/details/5026923432?title...) |
| ITV System Test Engineer                  | IND APTIV COMPONENTS INDIA PRIVATE   | IND CHENNAI - ENG 2                 | ... and the forefront of solving mobility’s to...  | [Link](https://www.adzuna.in/details/5026923304?title...) |
| Senior Software Engineer                   | THOMSON REUTERS                      | IND-BLR-SALARPURIA SATTVA KNOWLEDGE COURT | ... as Code, CICD Pipelines Excellent and crea...  | [Link](https://www.adzuna.in/details/5026923018?title...) |
| Infrastructure Specialist: Cloud Platforms | IBM                                  | BANGALORE, INDIA                    | ... an early adopter of artificial intelligenc...  | [Link](https://www.adzuna.in/details/5026922972?title...) |

This output provides a clear view of available job vacancies along with their details, making it useful for job seekers or researchers interested in employment trends within specific sectors.






