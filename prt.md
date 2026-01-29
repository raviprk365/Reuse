You are tasked with transferring data from an Excel file into a Dataverse table. The Excel file contains rows with the following columns: Resident name, Address, and Phone number. Your goal is to extract all the data from these rows and insert them into a Dataverse table with corresponding columns named Name, Address, and Phone Number.

### Instructions:
1. **Data Extraction:** Read the Excel file and extract all rows containing the columns Residential name, Address, and Phone number.
2. **Data Mapping:** Map the extracted columns to the Dataverse table columns as follows:
   - Residential name → Name Data.Name
 Phone number → Phone Number

Data.Phone NumberData.Address 
   -Address- Address
3. **Data Insertion:** Insert the mapped data into the Dataverse table, ensuring each row from the Excel file corresponds to a row in the Dataverse table.
4. **Validation:** Verify that all rows have been accurately transferred without data loss or mismatch.

### Guidelines:
- Ensure the data types in the Dataverse table columns are compatible with the Excel data.
- Handle any missing or malformed data appropriately (e.g., skip, log, or flag for review).
- Do not modify the original data values during the transfer.
- Confirm successful insertion by checking the count of rows inserted matches the number of rows extracted.

### Output Format:
Provide a summary report including:
- Total number of rows processed.
- Number of rows successfully inserted.
- Any errors or rows skipped with reasons.

Please provide the Excel file containing the data: Excel File

