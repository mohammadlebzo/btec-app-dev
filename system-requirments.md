# System Requirments
## Stage 1, task 1

### Task 1.1:
**Problem definition statement**: nowadays there are many similar products that are competing to get the customer's money, but these products differ in quality, because of that the client asked for a web application where users can review products, to highlight their pros and cons, and judge their quality, so that customers can refer to before buying the product.

The **client** asked for a **web application** that is a review site that contains many **different categories**, and they asked for the ***following requirments*** to be in the site:

 1. **Registration System**.
 2. **Categories** of **games**, **movies** and **anime**, and the **ability to add more** placed horizontally.
 3. ***Save for later*** system, to save and remove reviews.
 4. **Commenting** system for the users.
 5. **Feedback** form to data collection.
 6. **Search functionality**.
 7. **Interesting colorful design** that is **appealing** to look at.

### Task 1.2
Any *starting project* in the world will always be **associated** with **risks**, as for this project there were actually many **risks associated with it** such as:

 1. **Timeframe**: the time frame for this project consisted of 4 total days, meaning it is a very short window for the client's requirements.
 2. **Feature creeping**: the client might look at other products features and want to have some of them in the project, which would be out of scope.
 3. **Lake of continuous feedback**:  i might not be able to get a stable stream of feedback from the client on all features.
 4. **Poor code optimization**: because of the short window of time, i might not be able to properly obtimize the code, which may result in moments of confusion where i don't understand where am i exactly.
 5. **Lake of an appealing design**: i might not be able to give the time for the design as there are many functions that i need to work on.
 6. **File corruption**: everyone is vulnerable to such a thing, anything can happen at any moment.
 7. **hardware failure**: it isn't very common but it might happen, you don't know when your hardware just decides to stop working.
 8. **Costs**: softwares costs money, and i might not have the right budget for that.

 ### Task 1.3

 1. **List of requirments**:
    - The *user* **must** be able to ***create an account***, or ***sign in to their account*** on the site.
    - The **categories** should be, **games**, **movies** and **anime**, with the **ability to add more** later down the line.
    - The site must provide the *users* with a ***save button***, so that *users* can **save** the reviews that they want to read leater or if they liked the review.
    - In the home page the user should be able to ***slide left or right*** to see all the items of a specific **category**.
    - The *users* should be able to **remove** reviews from their **saved reviews tab**.
    - The *users* should be **notified** if they **tried to save an already saved review**. 
    - The *users* should be able to **view all comments** on the **reviews pages**.
    - The *users* should be able to **comment** on any of the reviews so they can share their opinion with other *users*.
    - The *user* should be able to send **feedback** if they have any *concerns*.
    - The *user* should be able to **search** for **product specific reviews**.
    - The *users* should be able to see the **ratings and likes** of each of the reviews and 
    - The *users* should be welcomed with **appealing** colors and animations in the site.
    - The *users* should be able to **view the other** *users* **profiles**.

2. **Local storage and wireframe**:
    For the **local storage** *objects* i used a **constructor** to make the *objects* so there are **21 objects in total**, but they all share the same *attributes*, these *attributes* are:
    - ***oName***: refers to the **name** or the **title** of the product.
    - ***oDis***: refers to the **description** of the product.
    - ***oLink***: refers to the **link** were the product will be generated(**review page**).
    - ***oImage***: refers to the **main image** path for the product.
    - ***oHero***: refers to the **hero image** path that will be showen when the product is generated(**review page**).
    - ***category***: refers to the **category** of the product(**games, movies or anime**);
    - ***trailer***: refers to the **trailer link** for the product.
    - ***commentsA***: refers to the **products comments**.

    **The wireframe is in the wireframe file that is in the repository**.

3. **The Activity diagram is in the file that is in the repository**.
    Users will first access the home page, then they will be asked to sign in or creat an account, after they do that they can:
    - Search for any item to access the review page of that item to be able to comment, view other comments or watch the trailer.
    - See all the items by category, choose any of them to access the the review page of that item to be able to comment, view other comments or watch the trailer.
    - Save any of the items and have it in the saved reviews page to access them at a later point.
    - Send feedback by going to the feedback page and filling the form.
    
4. **The coding and implementation technique is agile**.
5. ***Used Testing technique***:
    - **Acceptance Testing**: it is the test made by the client(s), where the client(s) gives their opinion and if they accept the product/system or not.
    - **Black Box Testing**: it is the kind of testing where the functionalities and behavior is tested, to make sure that everything is working as intended.
    - **Graphical User Interface (GUI) Testing**: it is the kind of testing that tests the GUI elements, such as menus, buttons, input fields, text, data tables and screen sizes.
    - **Unit Testing**: it is the kind of testing where each function is tested to see if it's working as intended.
    - **Usability Testing**: it is the kind of testing where we test if the systen is user friendly or not.

**Resources**:
- Software testing types: [https://www.softwaretestinghelp.com/types-of-software-testing/](https://www.softwaretestinghelp.com/types-of-software-testing/)