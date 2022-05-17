# Email Unprepared Students
This script will create a CSV file that you can upload to Google Sheets to email each student in your Canvas class a list of the Canvas resources they still need to access for the upcoming assignment.

&nbsp;

## There might be a better way for you
Depending on the limitations your institution puts on you and on Canvas, you might have a more elegant way to do this. I wrote this because I had very limited access to the Canvas API. In particular, I could not access the message functions.

&nbsp;    


### Prerequisites
- You will need to know how to download an activity CSV file from Canvas. Mine have files names in the format MM-DD-YYYY.csv. The menu for downloading the files was recently changed to "New Analytics," which I suspect will change again and may be different for you.

- One of the columns in that CSV file needs to be the USERID (or evan the entire email address) of the student.

- You need a Gmail account. The university I worked for used Gmail, so this was easy. If your school does not, you should make sure that it is acceptable to email students about their academic work from an external account.

- You'll need to know how to Create a mail merge with Gmail & Google Sheets. I followed [these instructions](https://developers.google.com/apps-script/samples/automations/mail-merge).

- The Python module, which should come with your Python installation.

- The Pandas library. If you don't have it, follow [these instructions](https://pandas.pydata.org).

&nbsp;

### Instructions

I give step-by-step instructions in the Jupyter Notebook.


