# Computer-Application-and-Security-Task-Part-2

# Mutillidae Setup and SQL Injection Attack Guide

This guide provides step-by-step instructions for setting up Mutillidae, performing a SQL injection attack, and capturing screenshots.

## Setup Mutillidae

1. **Download and Install Mutillidae:**
   - Download the latest version of Mutillidae from the official repository: [https://github.com/webpwnized/mutillidae](https://github.com/webpwnized/mutillidae)
   - Follow the installation instructions provided in the repository.

2. **Launch Mutillidae:**
   - Start the Mutillidae server according to the installation instructions.
   - Access Mutillidae through your web browser by navigating to the configured address (usually `http://localhost/mutillidae/`).

## SQL Injection Attack

1. **Insert Apostrophe in Name Field:**
   - Navigate to the appropriate page in Mutillidae where a form with a "Name" field exists.
   - Enter any value into the "Name" field.
   - Insert an apostrophe (`'`) into the "Name" field and click on "View Account Details".

2. **Capture Screenshot:**
   - Use your operating system's built-in screenshot tool or a third-party screenshot tool to capture the outcome of the query.
   - Save the screenshot in a suitable location.

3. **Perform SQL Injection Attack to Retrieve User Accounts:**
   - Navigate to the login page of Mutillidae.
   - Enter your username along with an apostrophe (`'`) in the Username field.
   - Click on the login button.

4. **Capture Screenshot:**
   - Capture a screenshot of the resulting page that shows ALL of the user accounts from the table.
   - Save the screenshot in a suitable location.

## Viewing SQL Queries

1. **Check SQL Queries:**
   - Depending on the setup of Mutillidae, you may be able to view the SQL queries being executed directly within the application.
   - Explore the application interface or settings to locate a feature that allows viewing SQL queries.

## Screenshots

### Insert Apostrophe in Name Field

![Apostrophe in Name Field](screenshots/apostrophe_name_field.png)

### SQL Injection Attack - Retrieving User Accounts

![SQL Injection Attack](screenshots/sql_injection_attack.png)

## Disclaimer

This guide is for educational purposes only. Ensure that you have proper authorization before performing any security testing or exploiting vulnerabilities.
