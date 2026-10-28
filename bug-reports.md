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

##### Attachment: [https://drive.google.com/drive/folders/1URvMZ942VfnibVnyboB0liYWb4xSIPPq?usp=sharing]

##### Fix Version/s: (not specified in the documentation)

######  Reporter: OlgaOcean27

---



