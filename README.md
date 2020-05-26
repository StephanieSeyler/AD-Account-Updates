# AD Provisioning
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://choosealicense.com/licenses/mit/)
[![Dev](https://img.shields.io/badge/Version-Dev-blue)]()
[![Mainteneance](https://img.shields.io/maintenance/yes/2020?style=plastic)]()
[![Powershell](https://img.shields.io/badge/Powershell-v%205.1-orange)](https://www.microsoft.com/en-us/download/details.aspx?id=54616)

AD Provisioning is a collection of Powershell Scripts that are ran against Active Directory on a scheduled time frame
to make sure all data is up to date and formatted correctly.

## Installation

Download the Repository contains all scripts and supporting files.

## Features

#### Location Verify:
Updates office location and associated attributes in Active Directory based on Provided Data

#### Phone Verify:
Reformats Phone Numbers taken from the field "msrtcsip-line" Attribute and updates all phone fields.

#### Account Disablement:
Takes a list of UPN's provided by the user and performs the final steps of the Account Terimination / Data Deletion process

## Usage

Within each Individual Program there is a sub file structure with the script that will need to be ran within the Scripts folder.

## RoadMap

### Account Disablement Roadmap:
Automate the trigger condition of the script to remove the need for a Technician to begin the process. 

### Modules
All SCripts within this project will run of a single module for all functions to ensure consistancy and portability. 

### Phone Verify
V 0.2.0 Initial Release 2020-01-07
V 0.3.0 Revised to fix Swedish Numbers 2020-01-14

### Location Verify
V 1.1.0 Code completed waiting for Data Source
Initial Release pending official data source determination

### Account Disablement
V 1.0.0 Initial Release 2020-03-17


## Authors
Stephanie Seyler 

## Project Status
Overall Project is still in development

## license 
[MIT](https://choosealicense.com/licenses/mit/)
