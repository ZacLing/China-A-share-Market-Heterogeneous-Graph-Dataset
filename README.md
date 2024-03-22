### Indicator Dataset Documentation

The `indicator.csv` dataset contains financial indicators for stocks listed on the stock exchange. Below is a summary of its structure and the meaning of its columns:

- `Unnamed: 0`: An auto-generated index column.
- `id`: Unique identifier for each record.
- `code`: Stock code, which includes the stock symbol and its exchange identifier (e.g., `000001.XSHE`).
- `pubDate`: Publication date of the financial indicators.
- `pe_ratio`: Price-to-earnings ratio, indicating how much investors are paying for each dollar of earnings.
- `turnover_ratio`: A measure of stock liquidity, indicating the percentage of a company's shares that were traded over a given period.
- `pb_ratio`: Price-to-book ratio, reflecting the market's valuation of a company relative to its book value.
- `ps_ratio`: Price-to-sales ratio, indicating the value that investors are willing to pay for a dollar of sales.
- `pcf_ratio`: Price-to-cash-flow ratio, measuring the market's valuation of a company’s cash flow.
- `capitalization`: The total value of a company's outstanding shares of stock.
- `market_cap`: Market capitalization, representing the total market value of a company's equity.
- `circulating_cap`: Circulating capital, referring to the portion of a company's shares that are in the hands of public investors and available for trading.
- `circulating_market_cap`: Market capitalization based on circulating capital.
- `day`: The specific day to which the financial indicators apply.
- `pe_ratio_lyr`: Last year's price-to-earnings ratio, providing historical context for valuation.

This dataset offers a detailed snapshot of various financial metrics that are crucial for analyzing and understanding the market value and performance of listed companies.

---

### Financial Statement Dataset Documentation

The `financial_statementexe.csv` dataset encompasses comprehensive financial statement data for companies listed on the stock exchange. Given its extensive breadth, only a selection of key columns are highlighted below:

- `Unnamed: 0`: An automatically generated index.
- `id`: Unique identifier for the record.
- `code`: The stock symbol with its exchange identifier (e.g., `300692.XSHE`).
- `statDate`: The date the financial statistics were recorded.
- `pubDate`: The publication date of the financial data.
- `total_operating_revenue`: Total revenue generated from the company's operations.
- `operating_revenue`: Revenue from the primary activities of the company.
- `interest_income`: Income earned from interest.
- `premiums_earned`: Earnings from premiums, relevant for insurance companies.
- `...`: The dataset contains numerous other columns, covering a wide range of financial metrics such as expenses, profits, cash flow activities, assets, liabilities, and equity items, among others.

This dataset is pivotal for financial analysis, offering a detailed view of a company's financial health, performance, and cash flow, which are essential for making informed investment decisions.

---

### Financial Statement Dataset Documentation

The `financial_statementexe.csv` dataset encompasses comprehensive financial statement data for companies listed on the stock exchange. Given its extensive breadth, only a selection of key columns are highlighted below:

- `Unnamed: 0`: An automatically generated index.
- `id`: Unique identifier for the record.
- `code`: The stock symbol with its exchange identifier (e.g., `300692.XSHE`).
- `statDate`: The date the financial statistics were recorded.
- `pubDate`: The publication date of the financial data.
- `total_operating_revenue`: Total revenue generated from the company's operations.
- `operating_revenue`: Revenue from the primary activities of the company.
- `interest_income`: Income earned from interest.
- `premiums_earned`: Earnings from premiums, relevant for insurance companies.
- `...`: The dataset contains numerous other columns, covering a wide range of financial metrics such as expenses, profits, cash flow activities, assets, liabilities, and equity items, among others.

This dataset is pivotal for financial analysis, offering a detailed view of a company's financial health, performance, and cash flow, which are essential for making informed investment decisions.

---

### Historical Price Dataset Documentation

The `his_price.csv` dataset contains historical price data for stocks, including trading volumes and the amount of money involved in transactions. Here is a breakdown of its columns:

- `time`: The date of the trading data.
- `code`: The stock code, combining the stock symbol and its exchange identifier (e.g., `000001.XSHE`).
- `open`: The opening price of the stock on the given day.
- `close`: The closing price of the stock on the given day.
- `high`: The highest price at which the stock traded during the given day.
- `low`: The lowest price at which the stock traded during the given day.
- `volume`: The total number of shares that were traded during the day.
- `money`: The total monetary value of all shares traded during the day.

This dataset is critical for performing historical price analysis, allowing investors and analysts to track price movements, analyze trends, and make predictions based on past performance.

---

### Edge Symbol Dataset Documentation

The `edge_symbool.csv` dataset appears to contain a collection of stock codes organized by different stock indexes or categories, as indicated by the column headers. Each column represents a specific index or category, and the rows list the stock codes included in that index/category. Here is a brief overview of its structure:

- Columns: Each column name seems to represent a stock index or a specific category (e.g., `000300.XSHG`, `000001.XSHG`, `399001.XSHE`, etc.).
- Rows: Under each column, the rows list the stock codes (e.g., `000625.XSHE`, `000703.XSHE`, `002841.XSHE`, etc.) that are part of the index or category the column represents.

This dataset could be useful for analyzing the composition of different stock indexes or categories, studying the characteristics of stocks within each group, and comparing the performance of stocks across different segments of the market.

---

### Edge Industry Dataset (June 2018) Documentation

The `edge_industry_2018_6.csv` dataset lists stock codes grouped by industry categories as of June 2018. Each column represents a specific industry category, identified by a numerical code, and contains the stock codes of companies classified within that industry. Here is a general overview:

- `Unnamed: 0`: An automatically generated index.
- Columns (e.g., `801740`, `801020`, `801110`, etc.): Each column header seems to be an industry code, which categorizes stocks into different industries.
- Rows: Under each column, the rows list the stock codes (e.g., `600435.XSHG`, `300159.XSHE`, `000519.XSHE`, etc.) associated with the respective industry category.

This dataset facilitates industry-specific analysis, allowing investors and researchers to examine and compare the performance of stocks within the same industry category or across different industries.

---

### Edge Symbol Dataset (June 2018) Documentation

The `edge_symbool_2018_6.csv` dataset is structured similarly to the previously discussed `edge_symbool.csv`, but it specifically represents stock code groupings as of June 2018. Each column is labeled with an index or category identifier, and the rows under each column list the stock codes included within that particular index/category at that time. Key details include:

- `Unnamed: 0`: A system-generated index column.
- Columns (`000300.XSHG`, `000001.XSHG`, `399001.XSHE`, etc.): Represent different stock indexes or categories. Each column header is an identifier for the index/category.
- Rows: Contain stock codes (e.g., `600498.XSHG`, `601099.XSHG`, `000100.XSHE`, etc.) classified under the respective index/category denoted by the column headers.

This dataset allows for a historical comparison and analysis of the composition of various stock indexes or categories as of June 2018, providing insights into market trends and stock classifications at that time.

---

### Edge Industry Dataset Documentation

The `edge_industry.csv` dataset lists stock codes grouped by their respective industry categories. Each column represents an industry category, identified by a numerical code, and contains the stock codes of companies that fall within that industry. Here's a quick summary:

- Columns: Industry codes such as `801740`, `801110`, `801160`, etc., serve as headers. Each represents a different industry category.
- Rows: Each row under a column lists stock codes (`688776.XSHG`, `300114.XSHE`, `603267.XSHG`, etc.) that are classified within the corresponding industry.

This dataset is invaluable for conducting industry-based analyses, allowing for a detailed examination of sectors and comparisons within or across industries based on stock performance and other metrics.

---

### Edge Concept Dataset Documentation

The `edge_concept.csv` dataset organizes stock codes according to various concept categories, indicated by each column's label. Similar to the industry datasets, this dataset groups stocks but focuses on thematic or conceptual groupings rather than industry sectors. Here's a concise description:

- `Unnamed: 0`: An automatically generated index column.
- Columns (e.g., `SC0001`, `SC0002`, `SC0003`, etc.): Each represents a specific concept category, identified by a unique code. The concepts may cover various themes or trends relevant to the stock market.
- Rows: Lists of stock codes under each column, indicating which stocks are associated with the respective concept category.

This dataset is particularly useful for tracking the performance of stocks within niche markets or those benefiting from specific trends, offering insights into how certain themes or concepts are performing in the broader market.

---