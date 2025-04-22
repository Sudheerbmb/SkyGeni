

## 🗂️ Dataset Summaries

### 1. `finanical_information.csv`
This dataset contains economic indicators that may influence client behavior or subscriptions.
- `start_date`: The beginning of the time period
- `end_date`: The end of the time period
- `inflation_rate`: The rate of inflation during the period
- `gdp_growth_rate`: The rate of GDP growth during the period

---

### 2. `industry_client_details.csv`
This dataset provides information about the clients, their industries, and company characteristics.
- `client_id`: Unique identifier for each client
- `company_size`: Size category of the company (e.g., Small, Medium, Large)
- `industry`: Industry in which the client operates (e.g., Finance Lending, Blockchain)
- `location`: Client’s geographical location

---

### 3. `payment_information.csv`
This dataset logs payment activity by clients.
- `client_id`: Identifier for the paying client
- `payment_date`: Date when the payment was made
- `amount_paid`: Total amount paid
- `payment_method`: Method of payment used (e.g., Credit Card, Bank Transfer)

---

### 4. `subscription_information.csv`
Tracks subscription details and renewal patterns of clients.
- `client_id`: Identifier linking to a client
- `subscription_type`: Plan type subscribed to (e.g., Basic, Premium)
- `start_date`: Subscription start date
- `end_date`: Subscription end date
- `renewed`: Boolean indicating if the subscription was renewed

- - -

