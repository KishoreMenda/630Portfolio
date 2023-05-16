# Sprint 1 - Weeks 6-7 (Feb 28 - March 20) 
  - Participated in Scrum meeting to understand the Pantry Node Project. Had discussion regarding the libraries to be used in the project. <br>
  [Update UI dependencies](https://github.com/ChicoState/PantryNode/issues/24)

# Sprint 2 -  Weeks 8-9 (March 21 - April 3)
  - Discussed development of the project and Frontend dependecies understanding and started to work with the frontend team on Sales and Expiry pages.

  [Frontend README](https://github.com/ChicoState/PantryNode/issues/67)

# Sprint 3 - Weeks 10-11 (April 4 - 17) 

 - Worked in frontend team to work on Sales Page, to dynamically render the sales data on the UI. Then there was no backend apis ready so had to revert changes - that were made assuming test data.

1. [Dynamic rendering of sales data - main ](https://github.com/ChicoState/PantryNode/pull/125) <br>
 The idea is to dynamically update and display only the products that belong to the selected category.
2. [Dynamic rendering of sales data - feature branch](https://github.com/ChicoState/PantryNode/pull/133) <br>
3. [Commit for the Expiry table](https://github.com/ChicoState/PantryNode/pull/133/commits/88271f6123e00bda2d07829060e4d62e94453a55)


# Sprint 4 - Weeks 12-13 (April 18 - May 1) 

- Worked on adding new functionality in Expiry Page - added sort functionality for all the tables in the Expiry page.

1. [Added sort funtionality in Expiry page taking 2 fields into consideration](https://github.com/ChicoState/PantryNode/pull/212) <br>Sorting functionality is implemented based on two different field of the Expiry object: "Item" and "Expiry Date". 
2. [File changes](https://github.com/ChicoState/PantryNode/pull/212/commits/e089cb33c66bdee42f7f2a566b4632d1ce64b802) <br>
3. [Resolved bugs for the Expiry page sort](https://github.com/ChicoState/PantryNode/pull/213) <br>
There are 2 separate event handlers for each field but the same is being used. Used the appropriate handler which is already there.
4. [File changes](https://github.com/ChicoState/PantryNode/pull/213/commits/9c91297a28b293ca049983c084a578fe2c3d9f6b)


## Review

[Styling](https://github.com/ChicoState/PantryNode/pull/190)

 # Sprint 5 - Weeks 14-15 (May 2 - 15)

 1. [Added test cases in for the Expiry page's table](https://github.com/ChicoState/PantryNode/pull/248) <br>
 This test checks if the component renders the expected table with the provided mock data and rendering a message when no items are present in the expiry page.
 2. [File changes](https://github.com/ChicoState/PantryNode/pull/248/commits/e417ac6a7c888b628ec52a873635322c05cdc4f8) <br>
 3. [Added text fields to view stock count in Expiry page](https://github.com/ChicoState/PantryNode/pull/252) <br>
 Renders total quantity of expired items and nearly expired items from the feedList.
 4. [File changes](https://github.com/ChicoState/PantryNode/pull/252/commits) <br>

 ## Issue

 [Test case - expiry page](https://github.com/ChicoState/PantryNode/issues/238)

## Reviews

1. Reviewed code changes in Expiry page 

 [Reviewed Quantity sorting feature](https://github.com/ChicoState/PantryNode/pull/250) <br>
 [Reviewed couting stock feature in expiry page](https://github.com/ChicoState/PantryNode/pull/252)


 # Highlights

Introduced sorting filter dropdowns on the Expiry Page, facilitating easy sorting of data based on the selected field in the grid header. Users now have the flexibility to sort by Item name or Expiry Date. 

[Reference](https://github.com/ChicoState/PantryNode/pull/212)

# 630Portfolio
