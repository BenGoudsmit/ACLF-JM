# ACLF-JM

Here, you can find example testing data for the ACLF-JM application (https://predictionmodels.shinyapps.io/aclf-jm/).

You can use the column names and data properties as template for your own longitudinal data.

Instructions:
- In the ID column: enter a random ID number (e.g. 1).
- In the time_of_measurement column: set the day of measurement, e.g. if you followed a patient from day 0 (start measurements) to day 50 (current date). 
If your measurements are taken on a specific date, please visit the following link to calculate the date difference in days: https://support.microsoft.com/en-us/office/calculate-the-difference-between-two-dates-8235e7c9-b430-44ca-9425-46100a162f38
- In the meldna column: enter the repeated measured MELD-Na scores of your patient.
- In the time_of_last_measurement column: enter the last time (in days) your patient was measured. Typically, it is the date difference between the current date and start of follow-up, e.g. 51 days.
- In the death column: enter 1 if your patient died at the time_of_last_measurement, if not: enter 0.
- In the age column: enter the age of your patient in years.
- In the femalesex column: enter 1 if your patient is female, if not: enter 0.
- In the aclf_grade column: enter the CLIF-C OF score, which can be calculated at: https://www.efclif.com/scientific-activity/score-calculators/clif-c-aclf
The possible levels are: "No ACLF", "ACLF-1","ACLF-2" or "ACLF-3".
- In the sbp_present column: enter 1 if your patient has bacterial peritonitis, if not: enter 0.
- In the life_support_dependent colum: enter 1 if your patient is on life support, if not: enter 0.

Save the file (as .csv).

Then upload in the online application and predict survival for you patient.
