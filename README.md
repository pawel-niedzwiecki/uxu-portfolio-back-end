# UXU ( PORTFOLIO BACK END - API )

[DEMO](https://www.uxu.pl).

# Description

It is project my protfolio. This project use :

- Strapi.js
- AWS
- REST API: Node.js + MongoDB ( [repositorie API ](https://github.com/pawel-niedzwiecki/uxu-portfolio-back-end). )

# How to run this project?

1. Download this project on your computer
2. Make sure you have node.js installed [Link to Node.js ](https://nodejs.org) and database MongoDB
3. After making sure that you have installed node.js, run the terminal and in the directory of this project run the command `yarn install`
4. Create `.env` in main and add parametr:

- `ADMIN_JWT_SECRET`
- `AWS_ACCESS_KEY_ID`
- `AWS_ACCESS_SECRET`
- `AWS_BUCKET`
- `AWS_REGION`
- `DATABASE_HOST`
- `DATABASE_NAME`
- `DATABASE_PASSWORD`
- `DATABASE_PORT`
- `DATABASE_SRV`
- `DATABASE_USERNAME`
- `HOST`
- `JWT_SECRET`
- `PORT`

5. Then select one of the options:

### `yarn develop`

Runs the app in the development mode.\
Open [http://localhost:1337/admin](http://localhost:1337/admin) to view it in the browser.

### `yarn start`

Builds the app for production.
It correctly bundles Strapi in production mode and optimizes the build for the best performance.

## Learn More

Thanks for your interest and I invite you to cooperation :)
