# login_and_auth
using login context, "protect" an app by restricting access to various application features based on the users' login 
and capabilities.

### Author: Alistair Blake

Assignment: Refactor the application to use functional components and multiple pages

You will notice that the login system is fundamentally broken
What doesn't work?
Why?
... Fix It before you move on
Convert both the <Login /> and <Auth /> components to be implemented as 'function' components instead of 'class' components
Which hook will you use?
Add a menu/nav to the <App /> with links to 2 routes: / and /content along with the <Login />
Replace the <EditLink /> and <DeleteLink /> components with <Route>s that will show the appropriate content (below)
Add 2 "pages" (implemented as functional components) to the application
<Home /> should respond to the / route
This should always show "Hello World" as an <h1>
<Content /> should respond to the /content route
The link to this page should be hidden if you're not logged in
When visible, this component should render 3 divs conditionally:
One if you're logged in, which says "You are logged in"
One if you're logged in and have edit permissions, which says "You can edit"
One if you're logged in and have delete permissions, which says "You can delete"
Testing
Write unit tests for the Login Context Component
Write unit tests for the Login/Auth components
Hide/Show based on status
You will need to create some mocking interface to fake a server/login to simulate.
To Do Application Refactor
You have been provided, in the starter-code/todo folder, a working To Do list application, written using standard React Component State

Assignment: Implement Login and Authorization into an existing application

Requirements
Hide the entire interface until the user has logged in.
Provide a login and logout option in the header of the app
Implement the following RBAC rules:
Logged In Users with 'read' permissions can see the summary/count
Logged In Users with 'read' permissions can see the list of To Do Items
Logged In Users with 'delete' permissions can click the records to mark them as complete
Logged In Users with 'update' permissions can edit existing items
Logged In Users with 'create' permissions can create new items

### UML
1[]()