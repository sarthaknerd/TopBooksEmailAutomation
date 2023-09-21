# RPA UiPath Project - Goodreads Data Scraping and Email Automation

## Overview

This UiPath project automates the process of scraping data from Goodreads.com, specifically information about 100 popular books and their respective authors. The scraped data is then exported to a CSV file, and the CSV file is sent via email using the Simple Mail Transfer Protocol (SMTP). This automation streamlines the collection and dissemination of book-related data.

## Prerequisites

Before running this UiPath project, ensure that you have the following:

1. **UiPath Studio**: Install UiPath Studio on your machine.
2. **Goodreads Account**: A Goodreads account is required to access the website.
3. **SMTP Server Credentials**: Obtain the SMTP server details (server address, port, username, and password) for sending emails.
4. **Google Workspace (G Suite) Account**: If using Gmail for sending emails, make sure you have a Google Workspace (formerly G Suite) account.

## Setup

1. Clone or download this UiPath project from the repository.
2. Open UiPath Studio and load the project.
3. Configure the following settings in the project:
   - Goodreads credentials (if required).
   - SMTP server details.
   - Email sender and recipient addresses.

## Workflow

This project consists of the following main steps:

1. **Data Scraping**: The UiPath robot navigates to Goodreads.com and scrapes data from the website, including book titles and authors, for the top 100 popular books. The data is extracted into a structured format.

2. **Data Export**: The scraped data is then processed and exported to a CSV file, ensuring that the data is organized and ready for analysis.

3. **Email Automation**: After exporting the data to the CSV file, the robot composes an email. The CSV file is attached to the email, and it is sent to the specified recipient(s) using SMTP. Ensure that you have configured the SMTP server details and email addresses correctly.

## Running the Project

To run the project, follow these steps:

1. Open UiPath Studio.

2. Load this project.

3. Configure the necessary settings as mentioned in the "Setup" section.

4. Run the project by clicking the "Run" button in UiPath Studio.

5. Monitor the UiPath robot's execution. It will perform data scraping, export data to a CSV file, and send the email automatically.

## Output

Upon successful execution of this UiPath project, you will have:

- A CSV file containing data about 100 popular books and their authors.

- An email sent to the specified recipient(s) with the CSV file attached.

## Note

- This project assumes that Goodreads.com does not have any CAPTCHA or authentication barriers. If there are CAPTCHA challenges, additional configurations may be needed.

- Make sure to handle errors and exceptions appropriately, especially when dealing with web scraping, to ensure the reliability of the automation.

- Ensure that your email provider allows sending emails via SMTP from external applications. Some providers may require additional security settings.

- Regularly check and update the project, especially if the structure of the Goodreads website changes.

---

**Disclaimer**: This project is for educational and informational purposes only. Be respectful of websites' terms of use and scraping policies when implementing similar automation for real-world applications.
