# Part 2. Removing Duplicates

We will be working on the first column `record_id`

## 1. Check if Duplicates Exist

- Under the column `record_id`, `Facet` - `Customized facets` - `Duplicates facets`

![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/06.png)

- Click on `true` to view the duplicate values
- `sort` the values can give you a clearer view



## 2. Remove Duplicates

Please note that you cannot directly remove the values classified as `true` unless you want to delete all the records that appear more than once.

- You can follow the steps below to **keep the first record of each set of duplicates**.

  - **Sort the values**

    - `sort` the values under the column `record_id` if you have not do so. (Simply keep the default setting).

      

  - **Change the row indexes**

    - Under the column `record_id`, `Sort` - `Reorder rows permanently`

    ![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/07.png)

    
  
- **Blank down extra values**
  
  - This will set the duplicate values (except the first record) to blank
    - Under the column `record_id`, `Edit Cells` - `Blank down`
  
  ![img](https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/08.png)
  
  
  
  - **Remove the duplicates**
  
    - Now only the **blanked-down** records should be classified as `true` under the duplicate facets.
    - Simply remove all rows under `true` to remove the duplicates.
    - After remove the `Duplicates facet`, you should see 940 rows.
  
    <img src="https://libapps-au.s3-ap-southeast-2.amazonaws.com/accounts/118911/images/09.png" width="399px"/>