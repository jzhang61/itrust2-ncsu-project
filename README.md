iTrust2 is an electronics health records system (EHR) that provides patients with a means to maintain their health records and communicate with their health care providers (HCPs).  HCPs can record information about office visits including basic health metrics, diagnoses, prescriptions, eye care, and pregnancy care. iTrust2 follows [HIPAA statue](http://www.hhs.gov/ocr/hipaa/) for ensuring security and privacy of patient records.

## Technical Info
iTrust2 is written with Java EE and JavaScript.  It uses Spring to handle the backend and AngularJS on the frontend (currently AngularJS v1.6; work is underway to migrate to AngularJS v7) and runs with a MySQL/MariaDB database.  Testing is performed using Spring for the API and a combination of [Cucumber](https://cucumber.io/docs) and [Selenium](https://www.seleniumhq.org/) on the frontend.  

Setup instructions are located in the Developer's Guide in the docs.


