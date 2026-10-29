 This document contains simple bug reports during testing and self-studying


#### BR-001 [All Products Disappear When a Category Filter Is Selected]
---
##### Summary: All products disappear when any category checkbox is selected

##### Preconditions:
- ➤ The website is accessible.
- ➤ The product list is displayed.
- ➤ All category checkboxes are unchecked.

##### Steps to Reproduce:
1. Open the website https://practicesoftwaretesting.com/
2. Verify that all category checkboxes are unchecked and products are displayed.
3. Select the checkbox next to "Hand Tools".
4. Observe  that the product list is dispayed only "Hand tools".
5. Select the checkbox next to "Power Tools" without unchecking "Hand Tools".
6. Observe  that the product list is displayed only "Power tools" and "Hand Tools"
7. Select the checkbox next to "Other" without unchecking the previously selected categories.
8. Observe  that the product list is displayed " Other", "Hand Tools" and "Power Tools"
9. Uncheck all selected category checkboxes.
10. Verify that all products are displayed again. 

##### Expected Result: When one category is selected, products belonging to that category are displayed. When multiple categories are selected, products belonging to the selected categories are displayed according to the filter logic. When all category checkboxes are unchecked, all products are displayed.

##### Actual Result: All products disappear from the product list when any category checkbox is selected. Selecting additional category checkboxes does not display any products. All products reappear only after all category checkboxes are empty.

##### Severity: Major (preliminarily)

##### Priority: High (preliminarily)

##### Environment: 
- ➤ OS: macOS 14.6
- ➤ Browser: Google Chrome 155.0.8059.40
- ➤ URL: https://practicesoftwaretesting.com/

##### Attachment: https://drive.google.com/drive/folders/1xFQtvyiKgmIp6ouIzU_6Q-9OGL1cQl2h?usp=sharing

##### Fix Version/s: (not specified in the documentation)

###### Reporter: OlgaOcean27

---

#### BR-002 — [Sorting Does Not Reset Pagination to the First Page]

##### Summary: [Sorting] Changing the sort order on the last page does not reset pagination to the first page

##### Preconditions:
- ➤ The product catalogue contains multiple pages.
- ➤ The user is on the last page of the catalogue (e.g., page 6).
- ➤ Products are displayed on the current page.

##### Steps to Reproduce:
1. Open https://practicesoftwaretesting.com/
2. Navigate to the last page of the product catalogue (e.g., page 6)
3. Open the **Sort** dropdown.
4. Select **Price (High – Low)**.
5. Observe the current page number and the displayed products.

##### Expected Result: The product catalogue is sorted by price in descending order across all pages, and pagination resets to the first page so that the most expensive products are displayed first.

##### Actual Result: The selected sort order is applied, but the user remains on the last page. The most expensive products are displayed on the last page instead of the first page.

##### Severity: Major (preliminarily)

##### Priority: High (preliminarily)

##### Environment: 
- ➤ OS: macOS 14.6
- ➤ Browser: Google Chrome 155.0.8059.40
- ➤ URL: https://practicesoftwaretesting.com/

##### Attachment: https://drive.google.com/drive/folders/1URvMZ942VfnibVnyboB0liYWb4xSIPPq?usp=sharing

##### Fix Version/s: (not specified in the documentation)

######  Reporter: OlgaOcean27

---

#### BR-003 — [Search Field Is Cleared After Submitting a Query While Results Remain Filtered]

##### Summary: [Search] Search field is cleared after submitting a query, but the results remain filtered by the previous query

##### Preconditions:
- ➤ The product catalogue is available.
- ➤ The website is accessible.

##### Steps to Reproduce:
1. Open https://practicesoftwaretesting.com/
2. Enter "drill" (for example) in the search field.
3. Click the "Search" button.
4. Pay attention and verify to the search field and the displayed products on the main page.
5. Click the "Search" button several times while the search field is empty.
6. Observe the displayed products.
7. Click the "×" button in the search field.
8. Observe the displayed products again.


##### Expected Result: The search interface should consistently indicate whether a search filter is active. If the search field is cleared after submitting a query, the user should have a clear way to identify or reset the active filter. Submitting an empty search should behave consistently with the interface's search-reset behavior.

##### Actual Result: After submitting the query drill, the search field becomes empty, but four products matching the previous query remain displayed. Clicking the Search button with an empty field does not reset the results. Clicking the × button clears the search and restores the full product catalogue.

##### Severity: Minor (preliminarily)

##### Priority: Medium (preliminarily)

##### Environment: 
- ➤ OS: macOS 14.6
- ➤ Browser: Google Chrome 155.0.8059.40
- ➤ URL: https://practicesoftwaretesting.com/

##### Attachment: https://drive.google.com/drive/folders/1O-Q5Mo51fyomfI8fWAoNlgfWwGd-RJ6K?usp=sharing

##### Fix Version/s: (not specified in the documentation)

######  Reporter: OlgaOcean27
