![](https://i.gyazo.com/1a901f779b244c3c236f15cb9c3e616e.jpg)

Digits is an application that allows users to:

- Register an account.
- Create and manage a set of contacts.
- Add a set of timestamped notes regarding their interactions with each contact.

## Installation

First, install node.js. Then download a copy of Digits. Note that Digits is a private repo and so you will need to request permission from the author to gain access to the repo.

Then, cd into the app directory and install the required libraries with:

```

$ npm install

```

Run the application by invoking:

```

npm run dev

```

If all goes well, the template application will appear at http://localhost:3000. You can login using the credentials in settings.development.json, or else register a new account.

Lastly, you can run ESLint over the code in the imports/ directory with:

```

npm run lint

```

## Walkthrough

### Landing Page

When you first bring up the application, you will see the landing page that provides a brief introduction to the capabilities of Digits:

![](https://i.gyazo.com/1a901f779b244c3c236f15cb9c3e616e.jpg)

### Register

If you do not yet have an account on the system, you can register by clicking on “Login”, then “Sign Up”:

![](https://i.gyazo.com/b48d4926eea2531290930328c7c50241.jpg)

### Sign Up

Click on the Login link, then click on the Signin link to bring up the Sign In page which allows you to login:

![](https://i.gyazo.com/046e02c9cc3a6497cbfb3b4653f85a06.jpg)

### User home page
After successfully logging in, the system takes you to your home page. It is just like the landing page, but the NavBar contains links to list contact and add new contacts:

![](https://i.gyazo.com/ef4e5b439cd7d430aea5def2702460f2.jpg)

### List Contacts
Clicking on the List Contacts link brings up a page that lists all of the contacts associated with the logged in user:

![](https://i.gyazo.com/5e4a0a9597f2471c4d65d58a4b4f6704.jpg)

### Edit Contacts
From the List Contacts page, the user can click the “Edit” link associated with any Contact to bring up a page that allows that Contact information to be edited:

![](https://i.gyazo.com/e7cd070680467976db96f38e09fd1dd8.jpg)

### Admin mode
It is possible to designate one or more users as “Admins” through the settings file. When a user has the Admin role, they get access to a special NavBar link that retrieves a page listing all Contacts associated with all users:

![](https://i.gyazo.com/2415523499dcd07da9016a4363873dff.png)
