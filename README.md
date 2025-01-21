# Test Case: Filtering Hotels by 4 Stars  

This test case demonstrates the process of applying a filter for **4-star hotels** on Skyscanner and validating that all results meet the specified criteria. The automation ensures the functionality of the filtering system and verifies its accuracy.  

---

## Test Case Description  

1. **Objective:**  
   Validate that Skyscanner's hotel filtering feature displays only **4-star hotels** when the filter is applied.  

2. **Process:**  
   - Navigate to the Skyscanner homepage and access the Hotels section.  
   - Search for hotels in London.  
   - Apply the **4-star filter**.  
   - Validate that all displayed results match the 4-star criteria.  

3. **Execution Steps:**  
   - Open the Skyscanner website.  
   - Click on the "Hotels" link to navigate to the hotels search section.  
   - Input "London" into the destination field.  
   - Apply the 4-star filter.  
   - Execute the search to retrieve results.  
   - Validate each hotel result by checking its star rating through the `aria-label` attribute.  

4. **Validation Logic:**  
   - Extract the star rating of each displayed hotel card.  
   - Assert that the rating matches **4 stars**.  
   - If a mismatch is detected, log the error and halt the test.  

---

## Test Results  

The test was **successful**, confirming that the **4-star filter** works as expected. All displayed results matched the filter criteria, and no discrepancies were found. This demonstrates that Skyscanner's filtering functionality provides accurate and reliable results when applied.  

![Test Results Screenshot](https://github.com/woroodfathiassi/Filteringby4Stars-Selenium-IDE-Test-Case/blob/main/fourStars.png?raw=true)  

