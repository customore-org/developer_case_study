# Junior Developer Case Study

Welcome to the Junior Developer Case Study repository! This project is designed to assess the skills and abilities of junior developers by implementing a web scraper in Python to gather product reviews from an ecommerce website. Before you start, please read the following instructions carefully.
Project Overview

The goal of this case study is to create a simple web scraper that extracts product reviews from a specified ecommerce website. The scraper should be written in Python and adhere to best practices in terms of code structure, readability, and maintainability.

-----
## 1. Setup

Clone this repository to your local machine.
```
git clone https://github.com/customore-org/developer_case_study.git
cd developer_case_study
```

Create a virtual environment (optional but recommended).
```
python -m venv venv
```

Activate the virtual environment.
        
On Windows:
```
venv\Scripts\activate
```

On Unix or MacOS:
```
source venv/bin/activate
```
Install the required dependencies.
```
pip install -r requirements.txt
```

------
## 2. Task

Your task is to implement a web scraper using Python to extract product reviews from the Lazada ecommerce platform, considering different countries such as Vietnam, Singapore, and Thailand. Utilize the Celery framework for task automation. The scraper should take a list of product identifiers as input and produce a CSV or JSON file with the following columns: product, review_id, review_content, review_rating, and review_timestamp (in UTC).
Instructions:

### Choose Lazada Platform: </br>
Target Lazada websites in different countries such as Vietnam, Singapore, and Thailand. Ensure that your scraper is capable of extracting reviews from Lazada's product pages in these regions.

### Input/Output Specification:
- The scraper should accept a list of product identifiers as input.
- Output a CSV or JSON file with the following columns for each review:
    - product: the product identifier.
    - review_id: unique identifier for each review.
    - review_content: the textual content of the review.
    - review_rating: the rating given by the user.
    - review_timestamp: the timestamp of the review in UTC.

    This file could be stored locally, or sent to a cloud service like dropbox, GCS or S3.

### Use Celery for Automation:
- Integrate the Celery framework to automate the execution of tasks related to scraping. This includes distributing tasks, handling retries, and managing the asynchronous processing of product reviews.

### Code Structure and Modularity:
- Organize your code into modular components for improved readability and maintainability.
- Implement error handling for cases like network errors or unexpected page structures.

### Documentation:
- Provide clear comments within your code explaining the purpose of each function and any critical logic.
Include a brief overview in the README on how to set up and run the Celery tasks.


-----
## 3. Submission

- Create a new branch for your work.

- Write your scraper code in a Python file within the src/ directory.

- Provide clear comments, documentation and commits within your code.

- Update the README.md file with any necessary instructions for running your code.

- Once you are finished, create a pull request for your branch.

-----
## 4. Evaluation Criteria

Your submission will be evaluated based on the following criteria
- Code quality: adherence to PEP 8, clean code principles, unit tests and best practices.
- Functionality: the scraper should successfully extract product reviews from the chosen ecommerce website.
- Readability and documentation: clear comments and documentation explaining the code.

-----
## Additional Notes

Remember to respect the terms of service of the chosen ecommerce website. Do not attempt to scrape sensitive or private information.

Feel free to reach out if you have any questions or need clarification on the instructions.

Happy coding!