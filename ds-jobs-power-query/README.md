## Data Careers Insights

### [Dashboard (PDF)](https://github.com/TienNguyen93/excel-project/blob/main/ds-jobs-power-query/jobs-report.pdf)

### Dataset Description
This dataset found through Mo Chen's exercise, containing 672 instances with 14 attributes,

Features | Index | Job Title | Salary Estimate | Job Description |	Rating	| Company Name | Location | Headquarters	| Size | Founded | Type of ownership |	Industry	| Sector	Revenue	| Competitors |
| -------- | -------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- | ------- |------- | ------- |
Data Type | Integer  | String | String | String |	Float	| String | String | String	| String | Integer | String |	String	| String | String |

* No duplicates existed

### Objectives
* Practice data-cleaning techniques
* Identify Average Min and Max Salary by different criteria


### Steps applied
* Remove unnecessary wording in `Salary Estimate` field: `$137K-$171K (Glassdoor est.)` -> `$137K-$171K`
* Determine maximum and minimum salary from `Salary Estimate` for each entry
* Add new column with more concentrated titles in `Job Title`
* Filter out rows contain `-1` and `Unknown` in `Size` columns
* Correct state names in `Location` column
* Utilize legitimate `states` dataset to map existed `state` column and filter out rows containing `null` values


### Results
Average Min and Max Salary by `Role Type`:

<img width="488" alt="sal-role" src="https://github.com/user-attachments/assets/49578a6e-9d08-44f3-bf73-ce80ce6a052c" />
<br></br>

Average Min and Max Salary by `Company's Size`:

<img width="400" alt="sal-size" src="https://github.com/user-attachments/assets/4a517bb3-6411-4152-81ba-2882b14540a3" />
<br></br>

Average Min and Max Salary by `State`:

<img width="398" alt="sal-state" src="https://github.com/user-attachments/assets/6a5e4b9a-90fa-47e5-b01b-7f14addb866b" />
<br></br>

Average Min and Max Salary by `Company's Size and Role Type`:

<img width="600" alt="sal-role-size" src="https://github.com/user-attachments/assets/32fe3fd6-d17d-4f09-9388-6e14e0198423" />

### Future Objectives
* Explore skills required in job descriptions
* Identify the top companies hiring for data science positions
* Determine the most common job locations for data science roles
* Explore the relationship between job level and required skills
* Explore the prevalence of certain skills or technologies within different industries
