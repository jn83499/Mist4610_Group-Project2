# MIST 4610 Group Project 2 - Group 7

## Group Members:

1. Donovan D'Silva - 	[repo](https://github.com/donmelsil/MIST-4610-Group-Project-2---Group-7)
2. Noah Hammond	-[repo](https://github.com/NoahHammond1/Group-Project2)
3. Chase Lin - [repo](https://github.com/cinnamotz/mist4610gp2)
4. Krithin Lokasani	- [repo]()
5. Jessica Ngo -[repo](https://github.com/jn83499/Mist4610_Group-Project2)

## Dataset and Description
The dataset, titled “NYPD Hate Crimes”, contains records of reported hate crime incidents investigated by the New York Police Department (NYPD). Each row represents a single complaint, including details about the offense, location, bias motivation, and whether an arrest was made.

Dataset was obtained from Data.gov (https://catalog.data.gov/), the U.S. government’s open data portal. It aggregates datasets from federal, state, and local agencies, and this dataset originates from the NYPD as part of New York City’s public data initiatives.

Number of rows: 4,029

Number of columns: 14

Each row corresponds to one reported hate crime complaint.

The dataset contains a mix of numerical and categorical variables, making it suitable for both statistical and categorical analysis. Several fields related to arrests contain missing values, indicating incidents where no arrest was made. The data supports analysis of temporal trends, geographic distribution, and bias motivations behind hate crimes.

Overall, this dataset provides a comprehensive view of hate crime incidents in New York City, including when and where they occurred, the type of offense, and the underlying bias motivation. Its structure makes it well-suited for exploratory data analysis and identifying patterns in hate crime activity.

### Columns and Data Types
1. Full Complaint ID (float64): Unique identifier for each complaint.
2. Complaint Year Number (int64): Year the complaint was filed.
3. Month Number (int64): Month of occurrence (1–12).
4. Record Create Date (string/object): Date the record was entered into the system.
5. Complaint Precinct Code (int64): Numeric code for the NYPD precinct.
6. Patrol Borough Name (string/object): Borough-level patrol division.
7. County (string/object): County where the incident occurred.
8. Law Code Category Description (string/object): Legal classification (e.g., felony, misdemeanor).
9. Offense Description (string/object): General type of crime.
10. PD Code Description (string/object): Specific NYPD classification of the offense.
11. Bias Motive Description (string/object): Motivation behind the hate crime.
12. Offense Category (string/object): Broader grouping of offenses.
13. Arrest Date (float64 / nullable): Date of arrest, if applicable.
14. Arrest Id (string/object): Identifier for associated arrest, if any.
