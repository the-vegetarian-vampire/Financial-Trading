# Financial-Trading
Full-stack web application simulating stock purchasing and selling through `IEX's` API. The site uses: `HTML`, `CSS`, and `Bootstrap` for styling and `Flask`, `Python`, `Jinja`, and `SQLite` for the backend.

----

## To Run:
1. Visit `[https://iexcloud.io/cloud-login#/register/](https://iexcloud.io/cloud-login#/register/)`
2. Once API token is confirmed, in terminal, execute: `export API_KEY=value`
3. Run flask via `flask run`

----

<img width="1280" alt="Screen Shot 2022-12-10 at 1 13 58 PM" src="https://user-images.githubusercontent.com/105305546/206869911-f0907c09-5708-450f-95f9-a5ef28fd8e89.png">

1. User registers an account checked against SQL database and creates a unique password.
2. User login and session recorded via cookies.
3. Each account allocated $10,000.
4. User can Quote, Buy, or Sell stocks via NASDAQ.
5. User account balance is updated based on buying and selling stocks.
6. User can check history to view purchases and sales.
