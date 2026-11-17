# The College-Town Market

An interactive comparison of completed home sales in college towns.

## What this site is for

The College-Town Market helps students, families, and other readers compare typical home sale prices across university areas in the dataset. It answers: **How do sale prices vary across these college towns?** The comparison uses each city's median sale price so a small number of unusually high or low sales have less influence than they would on an average.

## Live site

[Open The College-Town Market](https://yyeqw.github.io/college-town-home-sales/)

## Data notes

The site reads the provided data/college_town_home_sales.csv file. It excludes sales below $10,000 because the data description identifies implausibly low sale prices; 40 rows fall below this threshold, leaving 35,402 eligible sales. The page reports each city's median sale price and eligible sale count, plus the median across all eligible sales in the selected view. University and city search controls filter the displayed cities and recalculate the summary statistics.

The dataset represents completed sales collected in March 2026. It is not a feed of current listings or appraisals. The data description also warns that home_type is unreliable, street addresses are not unique identifiers, and blank days-on-market values must not be treated as zero. This site does not use those fields. Values are based on the supplied dataset and have not been independently verified.

## Tools we used

OpenAI Codex assisted with reading the project instructions and data description, writing the HTML, CSS, and JavaScript page, and documenting the work. The site uses plain HTML, CSS, and JavaScript with no external libraries; it parses the supplied CSV in the browser. GitHub Pages publishes the site through the repository's Actions workflow.

## Citation

College-town home sales dataset, version 1.0 (2026). University of Illinois-Deloitte Foundation Center for Business Emerging Technologies. Data collected March 2026.

## Who did what

Daiming Ye set the project direction and reviewed the finished site. OpenAI Codex assisted with implementation and documentation.
