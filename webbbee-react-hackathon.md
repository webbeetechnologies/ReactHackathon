# Webbee React Hackathon

*Questions are always welcome.*


### Problem statement:
The company Construction Machine Management Inc. manages a fleet of diverse building machines and rents them out to building companies. The director Mr. Chechnik manages those with multiple paper staple folders. He would like to digitize his inventory and ask you to develop an application for that purpose.
1. The client has a diverse inventory (excavators, chainsaws, bulldozers) and other machines.
1. For each of those machines he needs to store different information, to be able to provide the information to his customers, when they want to rent out his machines
1. He constantly expands his inventory so he needs to be able to add new items to his inventory as well as new inventory types with different properties. The properties of existing inventory types should also be editable.

  

## Goal

My goal with this test is to give you the ability to show off your skills under close to real world circumstances. In the real world there is almost never unlimited time. Because of that, we as engineers need to find a balance between writing good code and producing results. Therefore I do not expect perfect code but a good balance, that allows you to finish the project in the given deadline.

When evaluating your code, I will look at the architecture of your code base, check if you handle edge cases well and follow best practices.
- starting from the date of receiving the test, you have **12 hours** to submit it.
- set yourself a timer for 11 hours and plan 1 hour as a margin to test and push a working project
- use ES6
- use React
- use Redux for state management
- use create-react-app ([https://github.com/facebook/create-react-app](https://github.com/facebook/create-react-app))
- use any other library that you consider helpful
- use google
- use git to make useful commits during the development of the app
- divide the projects into stages and commit working intermediate results to the repository
- push the project to Github after completion and send me the repo link

  

## Demo

**Please watch the following demonstration video: [test_inventory_manager.mp4](https://drive.google.com/open?id=1fQnDIv8Q-JL5mKf9qaT7ajrMA2ACfYJU)

  

## User story:

#### Interface
1. As a user, I want to see a navbar.
2. As a user, I want to use the application from my mobile browser.
3. As a user, I want to use the application from the desktop browser.
4. As a user, I want to use the application from a tablet.
5. As a user, I want a way to manage the Inventory Types
6. As a user, I want a way to see all the inventory items at once.
7. As a user, I want a way to filter Inventory Type.


#### Inventory Type Editor
**![](https://lh3.googleusercontent.com/4NfnQMJBqPi0mbJtELZMNZwobRbJffrlNe9iV-r1-wEGK3x-0VwEqDZJsLWgegpo0qJcZZCwO00T1b98NlWeX2iLEJr2ulxjd4K_vOT7cfKeMUDHkb2ZWvk3eoksF2L7RDlbDm778_71VrOuzg)**
1. As a user, I want to be able Manage Inventory Types
2. As a user, I want to be able to delete an Inventory Type.
3. As a user, I want to be able to add new Inventory Type
4. As a user, I want to be able to set a title for an Inventory Type.
5. As a user, I want to be able to select a Title attribute from the available attributes.
6. As a user, I want to be able to add/manage attributes to a particular Inventory Type
7. As a user, I want to be able to add following type of attributes to the Inventory Type.
	- Text
	- Number
	- Date
	- LongText
8. As a user, I want to be able to delete an attribute.
9. As a user, I want to be able to add a new attribute of x type
10. As a user, I want to be able to change the type of an existing attribute.


#### Inventory Manager
**![](https://lh5.googleusercontent.com/ybnndBcBAZHAVIpkUHVGqvyRozL9JG3aWE5VfkYCRM0fFgi3gUHNtz0PMtdsX90FR0XDlERD5oXVI39vK7rwvZqd1HYGDDkTzOkwRA3Ae5he51YI_lg5yoSIrARfZ8Zf81C3QrVn1yn4hV1hHg)**
1. As a user, I want to be able to list all the inventory at once.
2. As a user, I want to be able to list inventory item of a particular Inventory Type.
3. As a user, I want to be able to navigate to a particular Inventory Type just using the URL.
4. As a user, I want to able to create an inventory item from the Inventory Manager for a particular Inventory Type.


#### Inventory Item
1. As a user, I want to be able to add inventory items to an Inventory Type.
2. As a user, I want to be able to edit an inventory item.
3. As a user, I want to be able to remove an inventory item.


## Acceptance Criteria:
1. Inventory data is persisted between page reloads.
2. Browser navigation should work.
3. Every page should have a unique url.
4. On reload the page, the application should be at the page where you have been before
5. The application should work well on mobile devices.
6. On changes to the Inventory Type, the changes are reflected in its items.
7. Create a good UX whilst keeping the deadline in mind.


### Good Luck