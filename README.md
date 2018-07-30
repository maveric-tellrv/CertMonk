# Project: CertMonk

Project is based on comparing tempest test with certification policy file


Create a python Flask app to display tempest test and rhcert supported tests in web UI.

## Objective:
 
	To find the difference in certification supported tests and  tempest test added in every new version of rhosp.
        Input:
	Policy.py file [file where all the tempest test regx are mentioned]
	Cert test run [Test logs to match the test run per feature based]

## Output: [UI]
	Tabular display of list of test executed from rhcert and missing test in policy regex file w.r.t tempest.

Project structure:

    |
    |
    |--------Template
    |                    -----HTML/js pages
    |
    |--------Src
    |               ------Source code
    |
    |--------Practice
    |          ----- sample practice codes
    |
    |--------README.md


UI:

![alt text](https://github.com/vikasmulaje/CertMonk/blob/master/UI.png)


## Author
	Certifcation QE
