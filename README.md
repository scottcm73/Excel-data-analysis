# Data Analysis with Excel

## Background
The emensely successful crowdfunding service, Kickstarter has raise nearly $2 billion, but not every project has found success. Only one-third of the more than 300,000 projects launched on Kickstarter achieve a positive outcome from funding process in terms of making more than what they initially sought.

Excel is employed to examine and analyze the data of 4,000 past Kickstarter projects.

One portion of the spreadsheet uses conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Conditional formatting fills each cell in the `Percent Funded` column using a three-color scale starting with 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

The column P called `Average Donation`uses a formula to discover how much each project backer paid on average.

A sheet with a pivot table that draws data from the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live in their category.

A stacked column pivot chart can be filtered by country based on the table.

A new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category**.

The created table was the basis for a stacked column pivot chart that can be filtered by country and parent-category.

The dates stored within the `deadline` and `launched_at` columns freature Unix timestamps. A formula (https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) can employed to convert these timestamps to a normal date.

Columns named `Date Created Conversion` and `Date Ended Conversion` that uses [this formula](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) to convert the informationcontained within the `launched_at` column into Excel's date format.

A pivot table has a of `state` and rows of `Date Created Conversion`, values based on the count of `state`, and filters based on `parent category` and `Years`.

One line graph from a pivot chart visualizes the table.

