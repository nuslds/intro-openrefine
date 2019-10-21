# Part 3. Dealing with Incomplete Information
We will be working on the column `countr_work`.

## 1. Check if empty cells exist

We use `Facet by blanks` to check if empty cells exist in the column.

- Under the column `country_work`, `Facet` - `Customized facets` - `Facet by blank (null or empty string)`
- Click on `true` to view the empty cells

![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/10.png)

## 2. Dealing with empty cells

- **Fill the cells by known rules**, for e.g., as long as the `us_state_work` is not empty, the `country_work` should be United States.
- Make sure you click on `true` under the `Facet by blank`
  - Under the column `us_state_work`, `Facet` - `Customized facets` - `Facet by blank (null or empty string)`
- Click on `false` in the facet for `us_state_work` to view non-empty values in the column
  - Please note that **multiple facets can work together**. The matching rows in the example below refer to the records that
- The values under `county_work` are missing, but entries are provided for `us_state_work`

![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/12.png)



  - `Fill the selected empty cells`

![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/13.png)

- **Remove relevant records**

You can also choose to remove relevant records with empty values in particular columns. Simply follow the steps below to remove the remaining records with empty values in `country_work`.
  - Close the `us_state_work` facet so that the display records will not be affected.
  - Ensure you choose `true` under the `Facet by blank` of `country_work` 
  - Under `All`,  `Edit rows` - `Remove all matching rows`

