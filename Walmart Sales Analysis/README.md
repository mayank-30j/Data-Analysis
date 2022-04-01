
# Walmart Sales Anlaysis

-- Walmart is an American multinational retail corporation that operates a chain of hypermarkets (also called supercenters), discount department stores, and grocery stores from the United States.

-- This project aims to share some of the interesting findings. 

-- Any one interested can also share what else can be extracted from the data.

-- We will be taking a look at the walmart data and try to get some insights from it.

### About the dataset: 
- Each row in the dataset represents Weekly Sales.
- The sales is recored on Friday each week and so the dates in each row also differ by 7 days.

### Columns: 
- Store : Every store of walmart is assigned a number (at least in the data set) ranging from 1-45.
- Date: This date represents Friday of each week (that is when the sales total sales is recorded).
- weekly_Sales: Sales for the given store
- Holiday_Flag: 1 represents Special holiday week and 0 represents no holiday week
- Temperature: temprature on the day of sales.
- Fuel_Price: Fuel price in the region.
- CPI : Prevailing consumer price index
- Unemployment : Prevailing unemployment rate 

### Holidays
- Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
- Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
- Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
- Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

## Run Locally

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```

