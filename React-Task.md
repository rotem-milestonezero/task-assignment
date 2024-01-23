This test is an opportunity for you to demonstrate your development skills and for us to be exposed to them. 
Please create a public GitHub repo to post your submission.


**React Frontend** 

- Use `MUI` as your UI components library.
- Dynamic Routing: Implement a multi-page layout with React Router.

***Views***

- Users Table: 
1. users page should show a table of users, which shows data fetched from `https://jsonplaceholder.typicode.com/users`, with the following columns: name, email, company name. 

- Posts List: 
1. posts page should display a list of posts fetched from `https://jsonplaceholder.typicode.com/posts`. 
2. Show also list of posts saved in the localStorage (see below)

- New Post: 
1. Add a "Create post" button to Posts page.
2. Button should open a dialog where the user can enter details to create the post. 
3. Use localStorage to save the new post.
 

***State Managment and API calls***

* All state should be managed using `Redux Toolkit` - don't use internal state (useState)

* All API calls from the components should be handled using `Redux Toolkit Query`.


**Bonus points for:**

* Error handling when fetching data from the API. What should the user get? What do you do as the system in such a case? 

* Loading indicator while fetching data from the API. 

* The application to be responsive and look good on both desktop and mobile. 

* Add a search box which will filter users table by name or email.

* State should be persistence to maintain application state even after browser refresh.
  
* Containerize the React application and add it to the Docker compose


**Recommendations** 

* Create an easy-to-read code, and ensure you do understand your own code. 

* Structure the project in a way that promotes scalability and maintainability. 

* Prevent unnecessary renders.

* Make sure the project is built okay and no debugger and development logs are left in the code and no errors in the console. 

* Use comments in the code to explain the things you do there. 

* Try to produce a professional-looking page. 


**Final thoughts**

What's missing in this application to make it production grade ?
Please refer to any non functional requirements you addressed in applications you developped.

**Important** 

The git project must be complete and work independently. We test the project using the following tools: 

* pnpm (As package manager) 

* Node v18.12.0 (LTS) 

So, I do recommend testing the git locally on a clean server to make sure project dependencies are correct and the project is built and runs okay. 
