Spreadsheet Data Quality & QA – Practice 1

Project Overview

This project demonstrates how spreadsheets can be used to review, organize, and maintain the quality of AI annotation datasets.

Learning Objectives

* Understand spreadsheet filtering.
* Use COUNTIF to count specific labels.
* Identify incorrect annotations.
* Detect missing labels and duplicate records.
* Understand the importance of data quality.

Exercise 1: Annotation Error Detection

I reviewed a dataset containing eight customer reviews.

Errors identified

ID	Original Label	Correct Label	Reason
002	Positive	Negative	Delivery was three days late.
005	Negative	Neutral	No clear positive or negative sentiment.

Result: Successfully identified both deliberate annotation errors.

Exercise 2: Spreadsheet Filtering

Question: Which feature displays only records matching a selected condition?

Answer: Filter.

Explanation: Filtering allows an annotator to display only selected records, such as customer reviews labelled Negative, without deleting the other records.

Exercise 3: COUNTIF Formula

Formula:

=COUNTIF(B2:B7,"Positive")

Purpose: Counts the number of cells containing the word Positive within the selected range.

Result: 3 positive labels.

Exercise 4: Data Quality Assessment

A dataset contained:

* 5 missing sentiment labels.
* 3 incorrect sentiment labels.
* 2 duplicate customer reviews.

Why these problems matter

* Missing labels create incomplete records.
* Incorrect labels introduce misleading information.
* Duplicate entries can distort the dataset and overrepresent repeated examples.

These issues should be corrected before submission to maintain reliable and consistent data.

Quality Assurance Checklist

1. Check for missing labels.
2. Verify sentiment classifications.
3. Identify duplicate records.
4. Apply consistent annotation guidelines.
5. Confirm that formulas and filters work correctly.

Skills Demonstrated

* Spreadsheet data organization
* Data filtering
* COUNTIF formulas
* Annotation quality assurance
* Error detection
* Data validation concepts
* Critical thinking

Final Assessment

Successfully completed spreadsheet QA exercises involving annotation error detection, filtering, formula interpretation, and data quality assessment.

This is a beginner practice project, not professional work experience.
