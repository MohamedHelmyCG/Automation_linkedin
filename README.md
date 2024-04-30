LinkedIn Job Application Automation

This repository contains a Python script for automating job applications on LinkedIn using Selenium.

Overview

This script automates the process of applying for jobs on LinkedIn. It logs in to your LinkedIn account, navigates to the job search page, applies filters based on your preferences, and then applies to each job listing automatically.

Prerequisites

Before running the script, make sure you have the following:

- Python installed on your machine
- Chrome browser installed
- Chrome WebDriver installed and added to your system PATH

Installation

1. Clone this repository to your local machine:

   git clone https://github.com/your-username/linkedin-job-application-automation.git

2. Install the required Python packages:

   pip install -r requirements.txt

3. Download the Chrome WebDriver and add it to your system PATH. Alternatively, you can use the ChromeDriverManager to automatically download and manage the WebDriver.

Usage

1. Open the config.py file and fill in your LinkedIn login email, password, phone number, and Chrome WebDriver path.

2. Run the script:

   python apply_jobs.py

3. Follow the instructions to manually solve the CAPTCHA if prompted.

Important Notes

- This script interacts with the LinkedIn website, so it may break if LinkedIn changes its layout or security measures.
- Use this script responsibly and ethically. Automated job applications should be used judiciously and not to spam employers.
- Make sure to review the code and adjust it according to your needs and preferences.

Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

