# LifeLine-HealthServices-text-classification

## Problem Statement
LifeLine HealthServices is a top ranked Health care provider in USA with stellar credentials and provides high quality-care with 
focus on end-to-end Health care services. The Heath Care Services range from basic medical diagnostics to critical emergency 
services.

The provider follows a ticketing system for all the telephonic calls received across all the departments.

Calls to the provider can be for New Appointment, Cancellation, Lab Queries, Medical Refills, Insurance Related, General Doctor 
Advise etc. The Tickets have the details of Summary of the call and description of the calls written by various staff members with 
no standard text guidelines.

The challenge is, based on the Text in the Summary and Description of the call written in “converse” Column, the ticket is to be 
classified to Appropriate Category (out of 21 Categories)

## Data Description
### Train data:
contains the converstation in text form with its labels

### Teset data:
Test data only contains of converstation in text form we are expected to predict the correct ticket out of 21 tickets for each
conversation

## Evaluation Metric
The evaluation metric used here was Accuracy
