# jwt-bch-frontend

This repository is forked from [jwt-bch-frontend in the PSF repository](https://github.com/Permissionless-Software-Foundation/jwt-bch-frontend). It was forked so the Developer Services team can play with the code and evaluate if it's a good fit for our product plan.

This is a front end user interface based on Gatsby and React. It is forked from
[this template](https://github.com/christroutner/gatsby-login). It is intended
to be run with [this back end](https://github.com/Permissionless-Software-Foundation/jwt-bch-api).

This single page app (SPA) allows users to:
- Create an account.
- Fund their account with BCH and receive credit.
- Recieve a JWT token to access a REST API or other web service.

## Installation and Usage
- Install and run the [the back end](https://github.com/Permissionless-Software-Foundation/jwt-bch-api)
- Clone this repository `git clone https://github.com/Permissionless-Software-Foundation/jwt-bch-frontend`
- Install dependencies: `npm install`
- Run development server: `npm run develop`
- Build for production: `npm run build`

This is a simple demo. The homepage is a login form. And a profile page is accessible
only if the user is logged in. The profile page displays the username and JWT of
the logged in user.
- Click on the _Profile_ link in the nav bar. You will be redirected back to the
home page, and can not access the private _Profile_ page unless logged in.
- Add a username and password then click the _Create_ button to create a new user.
- You will be logged in and taken to the _Profile_ page.
- Log Out. You will be redirected to the Homepage with the login screen.
- Log In. You will be redirected to the _Profile_ page.

minor change
