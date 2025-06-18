## Background
This web app was created with Next.js, a React framework. This demos the use of AG Grid to display an Excel like table whose cells can be edited/updated. As cells are updated, the values within that updated row are sent to a JSON Rules Engine, which calculates the Price column based on pre-defined rules.

The Last JSON Rule which was applied based on the latest user update in the table can be seen in the area at the bottom of the page for your reference.

This demo is meant to show how one would build an Excel like table for a website, in which various combinations of user selections are used to calculate a price.

The column names and values used are examples of Cloud Infrastructure selections which one would make to determine a total price for their cloud infrastructure.

## Demo
[▶️ Watch Demo Video](./demodaytech-react-ag-grid-json-rules-demo.mov)


## Running Locally

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to view the web app.


## Technologies Used

- Next.js bootstrapped with [`create-next-app`](https://nextjs.org/docs/pages/api-reference/create-next-app)
- React.js
- AG Grid
- A simple JSON Rules Engine