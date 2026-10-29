## Checklist for a catalog, searching and filtering forms 
###### [project ➤ https://practicesoftwaretesting.com]
### CH-001
Description: Verify that items can be sorted by name in ascending alphabetical order (A–Z).
- ➤ Expected result: Items are displayed in alphabetical order, from A to Z.
### CH-002
Description: Verify that items can be sorted by name in ascending alphabetical order (Z–A).
- ➤ Expected result: Items are displayed in reverse alphabetical order, from Z to A.
### CH-003
Description: Verify that items can be sorted by price in descending order (highest to lowest)
- ➤ Expected result: Items are displayed from the highest price to the lowest price.
### CH-004
Description: Verify that items can be sorted by price in ascending order (lowest to highest).
- ➤ Expected result: Items are displayed from the lowest price to the highest price.
### CH-005
Description: Verify that items can be sorted by rating from highest to lowest. (A-E)
- ➤ Expected result: Items are displayed in ascending rating (A-E)
### CH-006
Description: Verify that items can be sorted by rating from lowest to highest. (E-A)
- ➤ Expected result: Items are displayed in descending order of rating.
### CH-007
Description: Verify that items can be filtered by a price range of 0 to 200.
- ➤ Expected result: Only items within the specified price range are displayed.
### CH-008
Description: Verify the system behavior when the maximum price will be decreased to 0
- ➤ Expected result: The system is not displays any of items on the main page when price is equal to 0. 
### CH-009
Description: Verify that an item can be found by entering its name or a relevant search term.
- ➤ Expected result: The results contain items name matching the search query
### CH-010
Description: Verify that an item can be found by entering its name or a irrelevant search term.
- ➤ Expected result: A no-results message or an empty results list is displayed, according to the application requirements.
### CH-011
Description: Verify the search behavior when the search field is empty.
- ➤ Expected result: The application handles the empty query according to the defined requirements and shows message for user "the field is empty" 
### CH-012
Description: Verify search behavior with a one-character query
- ➤ Expected result: The application handles the query according to the defined requirements
### CH-013
Description: Verify search behavior with a long query
- ➤ Expected result: The application handles the query correctly without error messages or unexpected behavior.
### CH-014
Description: Verify that items can be filtered by the "Hand Tools" category
- ➤ Expected result: Only items belonging to the "Hand Tools" category are displayed.
### CH-015
Description: Verify that items can be filtered by the "Power Tools" category
- ➤ Expected result: Only items belonging to the "Power Tools" category are displayed.
### CH-016
Description: Verify that items can be filtered by the "Other" category
- ➤ Expected result: Only items belonging to the "Other" category are displayed.
