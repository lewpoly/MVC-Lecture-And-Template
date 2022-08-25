Included in this repository is a project template using MVC.

### MVC - Model View Controller.

#### A lecture outline for the methodology and organisation of modern websites.

---

### What is MVC exactly?

- Not a framework.
- Just a way of thinking.
- Way to structure web applications.
- The structure of MVC is used by most frameworks.
- Frameworks implement a structure(MVC), MVC is not a framework.
- Keep solid structure throughout applications.
- Client is the browser, processing information..

### What are the Advantages of using MVC?

- An easier way to keep a separation of

---

![MVC](https://www.ma-no.org/cache/galleries/contents-2002/router-mvc-db.svg.png "MVC")

MVC order doesn't matter, just this flow...

#### User :arrow_right: Route processing :arrow_right: Controller :arrow_right: Model :arrow_right: Controller :arrow_right: View :arrow_right: User

---

A great video explaining MVC and how it is used can be found [here](https://youtu.be/1IsL6g2ixak).

### Browser

- User makes request to router
- Router hands request off to controller
- Controller sends request to the view, which sends request back to client.

---

### Model (Database)

- Interacts with data.
- Add and retrieve items from DB
- Process data from or to the database
- Speaks only with the controller (Server)

---

### View (Client Side)

- The only thing the client ever sees
- U.I.
- Only listens
- Follows instruction form the controller (server)
- Makes no decisions for itself

---

### Controller (Server)

- Receives requests from the user
- All server side logic
- Middle man between user and database
- Processes info and talks to the DB if needed
- Receives info from db- Speaks to View to explain presentation to the viewer
- Can be handled by things like EJS, Handlebars, PUG, and React.
- Processes GET/POST/PUT/DELETE requests. (CRUD)

Takes info from user ➡️ Processes info and talks to the DB if needed ➡️ receives info from the database ➡️ speaks to View to explain presentation to viewer.
