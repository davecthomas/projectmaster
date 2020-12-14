# ProjectMaster Google Sheets Gantt Chart 

## Installation
1. Upload the XLS file to Google Sheets 
1. Open as Google Sheets
1. Copy the Code.gs file contents into your clipboard
1. In your sheet, go to Tools->Script editor 
1. Paste the contents over the default file
1. Save and run the file
1. You should see a new menu ProjectMaster

## Use

## Columns

### Days
Your raw sizing

### Adj Days
Sizing adjusted based on team load and a configurable fudge factor

### Gantt Days
This is auto computed based on whether you want raw or adjusted days in your Gantt

### Dependencies
Can be any one of: 
* SS - task starts the same date as prev
* ES - task starts the same day the last one ends
* SL5, 10, 15 - task starts 5, 10, or 15 business days after the prev
* EL5, 10 20 - task starts 5, 10, or 20 days
