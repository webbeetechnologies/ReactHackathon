
# Webbee React Hackathon

*Questions are always welcome.*


## Problem statement:
The company Construction Machine Management Inc. manages a fleet of diverse building machines and rents them out to building companies. The director Mr. Chechnik manages those with multiple paper staple folders. He would like to digitize his inventory and ask you to develop an application for that purpose.
1. The client has a diverse inventory (excavators, chainsaws, bulldozers) and other machines.
2. For each of those machines he needs to store different information, to be able to provide the information to his customers, when they want to rent out his machines
3. He constantly expands his inventory so he needs to be able to add new items to his inventory as well as new inventory types with different properties. The properties of existing inventory types should also be editable.

  

## Goal
My goal with this test is to give you the ability to show off your skills under close to real world circumstances. In the real world there is almost never unlimited time. Because of that, we as engineers need to find a balance between writing good code and producing results. Therefore I do not expect perfect code but a good balance, that allows you to finish the project in the given deadline.
  

## Demo

**Please watch the following demonstration video: [test_inventory_manager.mp4](https://drive.google.com/open?id=1fQnDIv8Q-JL5mKf9qaT7ajrMA2ACfYJU)

  

## User story:

#### Interface
1. As a user, I want a way to manage the Inventory Types.
2. As a user, I want to be able to see all the inventory items at once.
3. As a user, I want to be able to filter Inventory Type.

#### Inventory Category Editor
1. As a user, I want to be able manage inventory categories
2. As a user, I want to be able to add a new category
3. As a user, I want to be able to delete an existing category.
4. As a user, I want to be able to set a title for a category.
5. As a user, I want to be able to pick a title field from the available category fields for the items.
6. As a user, I want to be able to add/manage fields to a category
7. As a user, I want to be able to add following type of fields to the category.
	- Text
	- Number
	- Date
	- LongText
8. As a user, I want to be able to add a new field.
9. As a user, I want to be able to change the type of an existing field.
10. As a user, I want to be able to delete a field.
11. As a user, I should have access to the category items with a unique URL

#### Inventory Manager
**![](https://lh5.googleusercontent.com/ybnndBcBAZHAVIpkUHVGqvyRozL9JG3aWE5VfkYCRM0fFgi3gUHNtz0PMtdsX90FR0XDlERD5oXVI39vK7rwvZqd1HYGDDkTzOkwRA3Ae5he51YI_lg5yoSIrARfZ8Zf81C3QrVn1yn4hV1hHg)**
1. As a user, I want to see all the items available in the store.
3. As a user, I want to see filtered items of a selected inventory category.
4. As a user, I want to able to create, delete, update an inventory item from the Inventory Manager.

#### Inventory Item
1. As a user, I want to manage inventory items from the Inventory Manager.
2. As a user, I want to be able to add inventory items to an Inventory Category.
3. As a user, I want to see all the fields of the inventory category.
4. As a user, I want to be able to edit the fields an inventory item.
5. As a user, I want to be able to remove an inventory item.


## Acceptance Criteria:
1. Inventory data is persisted between page reloads.
2. Browser navigation should work.
3. Every page should have a unique url.
4. On reload the page, the application should be at the page where you have been before.
5. Ability to add/ update, delete a inventory category
6. On adding a new field to an inventory category, the field should be added to all the items of the category.
7. On deleting a field from an inventory category, the field should be deleted from all the items belonging to the category.
8. On updating the type of a field, the field type change should reflect in the inventory manager as well for this category.
9. On updating the label of a field, the change should also be updated for all items of the category.
10. On deleting an inventory category, the items belonging to the category will also be deleted.
11. Application should be adapted to Mobile, Tablet and Desktop browsers
12. UX should be good; you do not have to make a clone of the UI from the demo


## Evaluation
When evaluating your code, I will look at the architecture of your code base, check if you handle edge cases well and follow best practices.


## Do's
- use a library of your choice for the UI.
- use any other library that you consider helpful
- use ES6
- use React
- use Redux for state management
- use create-react-app ([https://github.com/facebook/create-react-app])
- preferably, write function components.

## Dont's
- create an API to store the data to a server.


## Best Practices
- use git to make useful commits during the development of the app
- divide the projects into stages and commit working intermediate results to the repository


## Code Quality
-   Write decent not perfect code, finish in 12 hours but don't just finish the job quick & dirty
-   if I cant easily read your code it will not pass
-   add comments to make your code more understandable


## Bonus tasks
Bonus tasks will give extra points but cannot affect your score negatively. If you have time left, you should do them.
- use Typescript
- create PWA


## Due Date  
- starting from the date of receiving the test, you have **12 hours** to submit it.
- set yourself a timer for 11 hours and plan 1 hour as a margin to test and push a working project
- At most until the midnight it needs to be submitted otherwise it does not pass.


## Submission
- Push the project to Github after completion and [send me](mailto:shashank@veranstaltungsbutler.de) the repo link
- [Schedule code review](https://tinyurl.com/react-code-review)

### Good Luck