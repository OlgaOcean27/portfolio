Collection of the testcases for the project ➤ (https://practicesoftwaretesting.com/)

### TTC-001 
(positive)

Tittle: Verify that a user can search for an existing product.

Preconditions:
➤ The website is accessible.
➤ The product catalog is loaded.
➤ Browser (Version): Chrome 155.0.8059.40 
➤ Environment: macOS 14.6, 2020

Test Data: "Hammer"

Test Steps:
  1. Open the website https://practicesoftwaretesting.com/.
  2. Click on the Search field.
  3. Enter "Hammer" in the Search field.
  4. Press the Search button.
  5. Review the displayed search results.

Expected Result:
➤ The search is performed successfully.
➤ The results contain products matching the search query.
➤ Each displayed product has its corresponding name and other product information.

---

### TTC-002 
(negative)

Tittle: Verify that a user can search for a non-existent product.

Preconditions:
➤ The website is accessible.
➤ The product catalog is loaded.
➤ Browser (Version): Chrome 155.0.8059.40 
➤ Environment: macOS 14.6, 2020

Test Data: j8tj58tj58jt85jtj5t8

Test Steps:
  1. Open the website https://practicesoftwaretesting.com/.
  2. Click on the Search field.
  3.  Enter "j8tj58tj58jt85jtj5t8" in the Search field.
  4. Press the Search button.
  5. Review the displayed search results.

Expected Result:
➤ The search is not performed successfully.
➤ No products were found for your search query.
➤ The system's behavior has not changed and still conforms to the specification.

---

### TTC-003 
(positive)

Tittle: Verify that products can be filtered by category.

Preconditions:
➤ The website is accessible.
➤ The product catalog is loaded.
➤ Browser (Version): Chrome 155.0.8059.40 
➤ Environment: macOS 14.6, 2020

Test Data: "Hand Tools"

Test Steps:
  1. Open the website https://practicesoftwaretesting.com/.
  2. Select the "Hand tools" category by checking the box.
  3. Review the displayed filtering result.  

Expected Result:
➤ The selected category filter is applied
➤ Only products belonging to the "Hand Tools" category are displayed. 

---

### TTC-004 
(positive)

Tittle: Verify that products can be sorted alphabetically from A to Z

Preconditions:
➤ The website is accessible.
➤ The product catalog is loaded.
➤ Browser (Version): Chrome 155.0.8059.40 
➤ Environment: macOS 14.6, 2020

Test Data: -

Test Steps:
  1. Open the website https://practicesoftwaretesting.com/.
  2. Click on the "Sort" field 
  3. Select the "Name A-Z" option from the list.
  4. Pay attention to the filtered result.  

Expected Result:
➤ All tools on the main page are sorted in alphabetical order.
➤ The system's behavior has not changed and still conforms to the specification.

---

### TTC-005 
(positive)

Tittle: Verify that products can be sorted by rating from lowest to highest

Preconditions:
➤ The website is accessible.
➤ The product catalog is loaded.
➤ Browser (Version): Chrome 155.0.8059.40 
➤ Environment: macOS 14.6, 2020

Test Data: -

Test Steps:
  1. Open the website https://practicesoftwaretesting.com/.
  2. Click on the "Sort" field 
  3. Select the "Rating A-E" option from the list.
  4. Pay attention to the filtered result.  

Expected Result:
➤ All tools on the main page are sorted by rating - from highest to lowest.
➤ The system's behavior has not changed and still conforms to the specification.

---


