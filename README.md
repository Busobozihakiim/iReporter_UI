# iReporter
iReporter, an online backed solution that is meant to reduce on the corruption level on the continent. With this method any citizen with an internet access can present any form of corruption to the right authorities.
iReporter also enables users to report any other discovery or situation that needs government intervention.

## Online Website.
Website accessed through https://busobozihakiim.github.io/iReporter_UI/UI

## For an offline version  
```
git clone -b gh-pages https://github.com/Busobozihakiim/iReporter_UI.git
```

## Built with 
- HTML
- CSS
- Javascript

## How to use it
- Visit the online website and you'll receive a page with signin or signup options, for the offline version, click on the index page to have the same options.
- At the moment, no authentication is set up so you can login with no account.

### The user
- After login, you are to meet a page that has a navigation bar with four tabs.
- By default the first tab 'report' is open and it contains a form where a user should be able to make a report.
- The form contains fields for selecting the type of report, writing a comment or description, and uploading images or videos.
- After filling in the form the user should be able to submit the report by clicking on the report button.
- The second tab 'My Reports' contains user submited reports that are pending meaning the user should be able to edit and delete reports.
- Click on the grey button with a report id, which will be dropped down to reveal a table with one row containing details of a report. The type, comment fields are editable and when you are done making changes you can click on the Update button to save your changes.
- The third tab 'Records' contains all reports that have been resolved, rejected or under unvestigation. They can be accessed the same way you accessed them in the My reports tab.
- Currently, the right most tab contains a drop down that logs you out of the page and links you to the admin page.

### The admin
- The admin page contains a table with all reports,the admin should be able to edit the status of a report by changing it in the status column by selecting a different status in the drop down, and finally clicking the update button.