# Part 4. Tackling Inaccurate/Inconsistent Entries

Text facet and Numeric facet are two most commonly used facets to discover values in a column, and hence they can be used to identify inaccurate information or inconsistent formats in the column.

### Numeric Facet

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/14.png" width="750" />

### Text Facet

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/15.png" width="700" />

### Text Length Facet

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/16.png" width="750" />

## 4.1 Identify invalid age information

### 1. Discover the values

- Under the column `age`, `Facet` - `Numeric facet`

- The range is shown as `0.00 — 330.00`

  

### 2. Remove records with invalid age information

- Remove records with age <= 10
- Remove records with age >= 90



## 4.2 Clean up the gender information

There are 52 unique entries under the column `gender`. For better-aggreated results, we will do a simple clean up and classify non-empty values into three types: 1) Female, 2) Male, 3) Others.

### 1. Discover the values

- Under the column `gender`, `Facet` - `Text facet`

  

### 2. Cluster the values

- At the top right corner of the `Text facet`, click on `Cluster` to trigger the clustering window
- Edit the `New Cell Value` - `Select all` - Click on `Merge Selected & Re-Cluster` - `Closed`

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/17.png" width="750" />



## 4.3 Clean up the `country_work`

Values in column `country_work` are not in consistent formats.

- Text cases
- Extra leading and trailing spaces

### 1. Discover the values

- Under the column `country_work`, `Facet` - `Text facet`



### 2. Converting all values to lower cases

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/18.png" width="550px" />

- Under the column `country_work`, `Edit cells` - `Common transform` - `To lowercase` (Feel free to try out `To upper case` and `To titlecase` too)



### 3. Removing Leading and Trailing Spaces

- Under the column `country_work`, `Edit cells` - `Common transform` - `Trim leading and trailing whitespace`

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/19.png" width="550px" />



### 4. Mass replacing

- Replace `united states` with `united states of america`
- Hover `united states` under the `Text facet` until you see the `edit` option - Click on `edit` - Enter the replace in the box - Click on `Apply`

<img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/20.png" width="600px" />

