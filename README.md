![Python Logo](https://www.python.org/static/img/python-logo.png)


# UN User Migration Project

## Purpose
The UN User Migration Project aims to migrate users from an old legacy platform to a new information portal. The primary objective is to identify middle managers who have the authority to approve individuals to input information for each country. The project involves several key checkpoints to ensure a smooth migration process:

1. *Old Legacy Platform Registration:* Identify users registered in the old legacy platform.

2. Check for the Correct Number of OMT Chairs: Verify that the number of users in the legacy platform for each country does not exceed two OMT chairs. If there are more than two users in any country, it indicates that the information about the middle manager has not been updated.

3. Registration in the New Platform (UNINFO): Confirm the registration of the middle manager in the new platform, UNINFO.

4. Matching BOS and UNINFO Country: Ensure that when a person is registered in UNINFO, their BOS (basis of selection) and UNINFO country are matched correctly.

## Data
The project relies on two sets of data:

1. Raw Dataset: The project's data is sourced from various platforms, with specific information stored in Sheet 3. This sheet is used for summary purposes.
2. Preprocessed Data: Additional information from the BOS platform, including registered countries and titles from UNINFO, is stored and utilized to perform the necessary checks and validations.
