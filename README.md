# Postman API Automation Integration with Github Action #

This repository is a demonstration for POC for integrating test with github actions. The tests are written in Postman and they are executed on the VM with the help of newman and newman-reporter-htmlextra
Github Action will trigger the project exegution on every push to the main branch. You can also execute the project manually using workflow_dispatch. The Projects runs on a scheduled time with the help of the cron job.

The HTML report is archived and kept in the artifact section for the team to download it. Along with that they can view the report directly from the github page : https://sb-karthik.github.io/Phoenix-Inwarranty-flow/
The latest report is mailed to the team members using GMAIL SMTP.


## Tech Stack ##
1. Postman
2. Nodejs
3. Newman
4. Newman-Reporter-htmlextra
5. Github Action
6. Gmail SMPT
7. Github Pages
8. CSV for Data Driven Testing
9. AWS-EC2_Instances for self hosted github runner.


## Github Pages ##
You can directly view the latest test report of the Postman Test of the Github page Link : https://sb-karthik.github.io/Phoenix-Inwarranty-flow/

# How to run the project #
You can run the project manually
