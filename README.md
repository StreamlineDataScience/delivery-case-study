
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Case Study

Streamline builds custom data pipelines to organize data for our
clients. This code runs on a schedule whenever the data is updated. For
many clients, the data is in Excel spreadsheets with varied structures.
Many of these structures are not rectangular and one of our first tasks
is to reformat the data.

To get an idea about how you think about writing data cleaning code, we
would like you to work on this example data reformatting problem.

The data is from [Enron](https://en.wikipedia.org/wiki/Enron), which was
a gas pipeline company. After a scandal, a number of their spreadsheets
were released to the public, so this example represents a real format
that analysts have in practice. The spreadsheet is located at
<https://github.com/StreamlineDataScience/delivery-case-study/blob/master/andrea_ring_000_1_1.pst.0.xls>.
The original spreadsheet was downloaded from
<https://github.com/SheetJS/enron_xls>, which has information on the
provenance of the data.

The data contains deliveries and receipts for a number of
locations/facilities (e.g. ACADIAN, BRIDGELINE). We would like the data
to be reformatted into the following data columns: location, date,
deliveries, receipts, where date is a date object, which should go from
2001-09-01 to 2002-02-05. Prior month averages and the month averages
can be removed.

Please provide a script/Notebook in your language of choice and an
output CSV of the reformatted data. The things we are looking for are:

-   Self-contained code that runs and processes the data with only the
    spreadsheet as input
-   Comments describing the code and steps you take
-   A script that checks common potential issues or notify if there are
    changes to the data structure
-   A script that could be run on a regular basis if we sent you a new
    spreadsheet with similar formatting.

We hope the project will take you \< 2 hours but you may spend as much
time as you prefer.
