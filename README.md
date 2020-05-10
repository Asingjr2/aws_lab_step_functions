# AWS_LAB_STEP_FUNCTIONS

### Purpose
- Purpose of repo is to demonstrate use of AWS step functions to handle lambda activity using conditional logic

### Description
- Application pushes sample text file to s3 for use by AWS state machine.  Cloudformation is used to create a state machine and required lambda functions that will read the uploaded s3 file, perform some simple processing, and upload a new file to s3 (information on a Super Mario brother)

### Requirements
- AWS account
- AWS console access
- Permission to use cloudformation to create aws resources
- Access to terminal to run script (optional)

### Implementation
- Deploy cloudformation templates in AWS console in following order:
    1. s3
    2. lambda
    3. step_function
- Uploaded either the `mario.txt` or the `luigi.txt` to your s3 bucket once created
- Use AWS console to start new execution for state machine or use `start.sh` or `start.bat` scripts"# aws_lab_step_functions" 
