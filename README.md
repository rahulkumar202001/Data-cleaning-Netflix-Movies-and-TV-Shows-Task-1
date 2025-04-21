Netflix Data Cleaning – Task 1 (Data Analytics Internship)
Summary of Data Cleaning Steps:
Eliminated Duplicate Records: Removed all duplicate rows to maintain data integrity and ensure accurate analysis.
Addressed Missing Values: Carefully handled null values by either imputing appropriate data or dropping irrelevant entries based on context.
Standardized Column Names: Renamed all column headers to lowercase with underscores for consistency and better code readability.
Converted ‘date_added’ to Datetime Format: Transformed string-based dates into proper datetime objects to enable efficient time-based operations and filtering.
Cleaned Text Fields (Country, Director, Cast): Removed inconsistencies such as extra spaces, null placeholders, and unified formatting for cleaner categorical data.
Validated and Updated Data Types: Ensured all columns had appropriate data types (e.g., integers for release_year, strings for categorical values) to support accurate analysis and visualization.

Tools & Technologies Used:
Python (Pandas): Utilized for efficient data manipulation, transformation, and cleaning processes throughout the project.
