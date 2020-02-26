===========
Report Generator Project
Jan 06, 2018
Overview

# Reports Generator System For FFA

[FFA](https://www.facilitiesfirst.com.au) Report Generator Project is aimed to provide automatic way to collect raw data, analysis data, generate report for client and manager to review, which can be utilised to find the weaknesses for the next activities to have better performance.

## Install

- Install Office 365 or Excel, Outlook individually to use.
- Currently only compatible under Windows OS.
- You must have Excel and Outlook to run this programme.
- You also can use VM or EC2 on AWS to simulate the funtions.

## Target Audience

- This is only use for FFA internal Administration staff members

## Support

- Monthly KPI Report

  1.  Select the month, or you can select any month of the year.
  2.  Select the Site, you can also select multiple sites at the same time.
  3.  Press Run
  4.  Select the Master file, the first file must be the Master Template file.
  5.  Select the 3x Source files one by one, these 3 files are the raw data retrieved from Templa. It does not matter the order of which file to select. but the file name must be obeied.
  6.  Wait until it pop up a message saying "Done", during the report generating, you can do other jobs at the same time.
  7.  If you encounter errors, please read carefully the error message will lead you to fix the issue.
  8.  When this is done, you will get a Excel file and PDF file of the report.
  9.  You then use the email function to send out the report.

- Prepare Email
  1.  Select which report you want to use
  2.  Select State or Site
  3.  Select the recipient(s). Although the recipients should be automatically select while the programme initiallised by the company compliance. but you can change it as needed.
  4.  Press Attach button to select the file as attachement
  5.  Press Prepare button to save the email and attachement as a draft.
  6.  Press Send button to send the email direclty from the programme, or you can send from the Outlook.

## Features added so far

- Weekly TimeSolutionz Report for every State, including VIC on Thursday
- Monthly TimeSolutionz For VIC Monthly Report - The pivot Table
- Monthly KPI Report for Any Month of the Year as long as Templa Files are ready
- Straight Generate PDF file for Monthly KPI Report
- Change color for Buttons
- Major Bug Fixed
- Warrning message added to enhance User Experience
- Standardise for Failed QA Items, including Font type, size, color, aligment etc.
- Fix bug for open file, check if file is selected, opened, integrated.
- Merge Cell correctly for Long descriptions of Failed QA Items
- Enhance Efficiency for change Font Style by Range Modify
- PMC and DAWR set up the Site Totals and All Ite (All Functioned)
- Faster with Refreshing Shutdown
- Fix TimeSolutionz Weekly Report bug, Yaanma not correct (Range was wrong)
- Log Sheet Function For KPI Report, Site Score, Failed QA Items, and All Items are now can tell which ones are Found/Not Found and setup format for easy reading.
- Weekly TimeSolutionz Report can now Conver to Range automatically
- The Email recipients will auto selected when different report need to be sent.
- Weekly Report can now select any Date Range as the result will be Filtered out by the Date Range(Validation checked)
- Weekly Report can now select any Company / Area individually
- Email attachement KPI use PDF filter, others use Excel Filter to choose Report file
- Weekly Report can now select individule site for timesolutionz report, sometimes they ask for QR report for a specific site
- Generate Template Master File for Next Month Use Automatically.
- Add Feature, Weekly Report you can search Single CSM as additional search criteria
- Send Bulk Email from draft folder, once you draft are ready to send, just click send email button( due to the restriction, every time send a email, need to wait 5 sec, and need confirm to send)
- Weekly Report can now filtered by multiple CSM, you can type in Names of CSM and run report, only that CSM will be shown
- Add Feature, auto select Quarterly Report email recipients and prepare email function
- KPI Report Format function added, now, the report will auto clean up blank rows to save paper and look cle But, will slow down the program
- Bug fixed, for if no result on weekly report, will continue generating other report.
- Bug fixed, if the file name not named as standard, error message will pop up.
- Adding new Site for KPI Report: Zinfra, Jemena Sister Company
- Check Master file saving directory exist before saving the file.
