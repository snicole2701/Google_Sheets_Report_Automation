# Automated Report Generation - Google Sheets

## Overview
This project aims to automate the process of generating management reports by extracting and compiling information from two separate Google Sheets. Due to a large amount of staff members working remote they make use of Google Sheets for real-time colaboration.

Financial Records: Used by the finance team to record payments received per file per client in different sub-sheets in the Google Sheet.

Administrative Records: Used for the administration of files.

Previously, the team leader spent hours every week manually compiling reports on:

Monies available for clients as collected per team member.

Team performance per team member in the current month.

Information on overdue amounts on files.

By automating this process, the time required to generate the reports has been reduced to just 5 minutes on reporting day, allowing the team leader to focus on cosmetic changes before submitting the reports to management.

## Steps Taken
### 1. Extraction of Information from Google Sheets
We created a Google Apps Script to:

Extract relevant information from both Google Sheets.

Compile the data into a new sheet named Stats.

in the different layouts as required for the reporting management wants to see

### 2. Custom Button for Quick Update
A custom button was created on the Google Sheet to allow for quick updates of reporting information on reporting day. This button can be accessed from the custom menu and triggers the report generation script.

### 3. Language Used
The language used in the scripts is JavaScript, specifically tailored for Google Apps Script.

### 4. Financial Records Sheet 
Script Purpose and Goals:
The script processes each sheet individually.

It gathers data for each team member per client and calculates subtotals and grand totals.

It then populates the Stats sheet accordingly.

### 5. Administrative Records Sheet
Script Purpose and Goals:
The script fetches data from a single large spreadsheet multiple columns and a fast amount of rows.

It groups data by user and calculates subtotals and grand totals per KPI that needs to be reported on.

It populates a new Stats sheet, ensuring efficient data handling.

## Conclusion
By automating the data extraction and report generation process, I have significantly reduced the time required for team leaders to compile reports. The process is now streamlined and efficient, allowing for more focus on strategic tasks rather than manual data compilation.
