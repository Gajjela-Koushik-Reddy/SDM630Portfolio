[Portfolio Website](https://gajjela-koushik-reddy.github.io/SDM630Portfolio/)  
Timeline:  
Sprint 1. Weeks 6-7 (February 28 - March 20)  
(including Spring Break)  
Sprint 2. Weeks 8-9 (March 21 - April 3)  
Sprint 3. Weeks 10-11 (April 4 - 17)  
Sprint 4. Weeks 12-13 (April 18 - May 1)  
Sprint 5. Weeks 14-15 (May 2 - 15)  

# Pantrynode Contribution

# Sprint 1

Discussed on the UI libraries that are a viable option for the project and assigned into the issue - [Update UI dependencies (#24)](https://github.com/ChicoState/PantryNode/issues/24)

Research:
1. [Resource 1](https://www.wearedevelopers.com/magazine/best-free-react-ui-libraries)
2. [Resource 2](https://www.turing.com/blog/react-ui-frameworks-for-developers/#:~:text=Which%20UI%20is%20best%20for,Evergreen%20are%20also%20popular%20UIs)

# Sprint 2

Discussed on the developement of the project and assigned into the issue - [Create Documentation Of Dependencies For Frontend Update Readme.md with how to start and dependencies](https://github.com/ChicoState/PantryNode/issues/67)

# Sprint 3

## Issues Created
1. [Improve sales page by tabulating sales data](https://github.com/ChicoState/PantryNode/issues/129)  

## Commits
1. [Adding dummy table to describe item's data](https://github.com/ChicoState/PantryNode/pull/125/commits/582c0661d0874edcd0a4c15602a30dab17a84109)  
- Created Table to render Sales Data
- Added Dummy Sales Data as the end point was not ready yet

## Reviews
1. [Updated README.md file with latest technology stack](https://github.com/ChicoState/PantryNode/pull/122) [(comment)](https://github.com/ChicoState/PantryNode/pull/122#pullrequestreview-1379846800)  
- Reviewed the README.md and made some suggestions to improve it further.

# Sprint 4

## Issues Created
1. [Implement Expiry Page - Frontend](https://github.com/ChicoState/PantryNode/issues/143)

Note: During our team discussion, we focused on determining the key features to implement on the expiry page.

2. [Format the sales table to be consistent with the layout of the summary and expiry tables.](https://github.com/ChicoState/PantryNode/issues/189)

I noticed that the table formatting in the sales table was inconsistent with the overall design of the pantry node project. To address this issue, I have created a task to resolve the formatting inconsistencies.

## Reviews  
1. [Frontend linter*](https://github.com/ChicoState/PantryNode/pull/134)  
After carefully reviewing the functionality and implementation of the linter, I have confirmed that it is working as intended and approved the pull request.
2. [Adding Category Filter to the Expiry Page (#188)](https://github.com/ChicoState/PantryNode/pull/188)  
After conducting a thorough examination of the category filter's functionality and testing its working nature, I am pleased to confirm that it is working as expected. Consequently, I have approved the pull request to be merged into the expiryPage. 
3. [Added Sort functionality in Expiry Page (#212)](https://github.com/ChicoState/PantryNode/pull/212)  
Upon testing the sorting functionality, I encountered a bug and promptly reported it to [Kishore](https://github.com/KishoreMenda) during our call. Despite the bug not being critical, I proceeded with the merge, considering it as a non-blocking issue.
4. [Resolving bug in expiry page sort functionality (#213)](https://github.com/ChicoState/PantryNode/pull/213)  
After the bug in the sorting functionality was fixed, I thoroughly rechecked its functionality and confirmed that it is now working correctly. Consequently, I proceeded to merge the updated code into the expiryPage branch.
5. [Expiry Page Cleanup (#218)](https://github.com/ChicoState/PantryNode/pull/218)  
By this point, we had successfully implemented all the required functionalities. However, we had to make the decision to remove the category filter feature from the implementation. This was necessary because the backend endpoint was not returning the required category data, making it unfeasible to support the feature. Reviewed if everything was removed along with the redundant code and merged it into the expiryPage branch.

## Pull Requests
1. [changing the style of the sales table to maintain consistency across all the pages](https://github.com/ChicoState/PantryNode/pull/190)  
The pull request was closed due to a change in the contribution branch strategy. Initially, it was decided to push frontend changes into the frontend branch and merge the code into the main branch as a single large update. However, the strategy was later revised, and it was decided to merge the code into the main branch in smaller batches. As a result of this change, the pull request was closed.

2. [Connecting backend to frontend and changing the view of the frontend](https://github.com/ChicoState/PantryNode/pull/211)  
To establish a connection between the expiry page endpoint and the expiry page frontend, we integrated the necessary components. Instead of a single large table displaying both expired and nearly expired items with color codings, we made design decisions to split the tables into distinct sections. This approach allows for better organization and improves the user experience by providing clear visibility and differentiation between expired and nearly expired items.
3. [Adding Dummy Data to test the sorting filters](https://github.com/ChicoState/PantryNode/pull/214)  
Due to the insufficient data being returned from the backend endpoint, we had to generate our own test data in order to evaluate the functionality of the features. By creating our own data, we were able to thoroughly assess how the features were working and ensure their effectiveness. 
4. [Sorting the data by expiry date by default](https://github.com/ChicoState/PantryNode/pull/215)  
Previously, the default sorting for the data was based on the item name. However, we made a decision to change this default sorting behavior to prioritize sorting by the expiry date. By implementing this change, the data will now be presented in a more relevant and meaningful way, making it easier for users to identify items that are nearing their expiration dates.
5. [Setting the default value on sort by filter to expiry date](https://github.com/ChicoState/PantryNode/pull/216)  
Changed the display order of the filter items 
6. [Moving Category Filter to a New Bar](https://github.com/ChicoState/PantryNode/pull/196)  
In order to improve the design and reduce clutter on the page, I relocated the filter functionality to a new area. By doing so, we were able to create a cleaner and more organized layout for the expiry page.

## Discussions
1. [here](https://github.com/ChicoState/PantryNode/pull/134#issuecomment-1505817344) - I have discussed on how to run the linter with the fellow reviewer.
2. Discussed on the end point return data with the backend team in scrum meeting.

## Commits [Merged To Main]
1. [Adding Expiry Table](https://github.com/ChicoState/PantryNode/pull/224/commits/56331dc6907d013700fbde1c3eafcbf68825f131)  
Created a table as per the [issue](https://github.com/ChicoState/PantryNode/issues/143) specifications
2. [sorting data by date and adding the table](https://github.com/ChicoState/PantryNode/pull/224/commits/9022d33edb23471b33fe5357cbb50c0f4d4ba0d1)  
3. [Moving Category Filter to a New Bar (#196)](https://github.com/ChicoState/PantryNode/commit/bb9ff6423ccd71082c7effb4fabe154bdb698356)  
4. [Connecting backend to frontend and changing the view of the frontend](https://github.com/ChicoState/PantryNode/commit/8cab82ec5ce1faee5d3a59b7925381c76e27a96e)
5. [Adding Dummy Data to test the sorting filters(#214)](https://github.com/ChicoState/PantryNode/pull/224/commits/fcb2a66c71703754ea0dbc1f5c0609502b2ac83a)
6. [Sorting the data by expiry date by default (#215)](https://github.com/ChicoState/PantryNode/commit/79e39535179e4f07f4194fbdc3a0efeec08cdd10)
7. [Setting the default value on sort by filter to expiry date (#216)](https://github.com/ChicoState/PantryNode/commit/e2fcdfdd70e9f543de4f95ca28a94cf1ddd1da83)

## Pull Requests [Merged To Main]
1. [Expiry page (#224)*](https://github.com/ChicoState/PantryNode/pull/224) 

# Sprint 5

## Issues  
1. [Add Sort by Quantity Feature into expiry page](https://github.com/ChicoState/PantryNode/issues/249)  
A subsequent proposal recommended the addition of an expiry page, which would offer the advantage of easily identifying the bulk quantity of expired items for efficient disposal.

## Commits [Merged to Main]
1. [Added nearly expired count to the page](https://github.com/ChicoState/PantryNode/pull/252/commits/0d00818c9990c456e68a060c2d6186d5aa314f15)   
A new feature has been introduced to showcase the overall quantity of soon-to-expire items present in the pantry.

## Reviews
1. [Reviewed](https://github.com/ChicoState/PantryNode/pull/250#pullrequestreview-1427567735) - [PR(#250)](https://github.com/ChicoState/PantryNode/pull/250)  
The implementation of sorting the items on the expiry page based on quantity was successful and well-received. Consequently, the proposed changes were approved.

# Highlights
During sprint 4, I collaborated with my teammates to develop the expiry page, incorporating various functional features. As a team, we collectively contributed to the overall development of the page. I am extremely proud to have taken a leadership role in guiding the group through the creation of this page.

Commits accepted into **main** branch  
- [Commits into main branch of pantrynode](https://github.com/ChicoState/PantryNode/commits?author=Gajjela-Koushik-Reddy)  

Pull Requests Accepted into **Main** branch  
- [Expiry page (#224)](https://github.com/ChicoState/PantryNode/pull/224)