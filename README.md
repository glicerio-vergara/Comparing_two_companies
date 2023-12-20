# Comparing_two_companies
Introduction

The script, titled "Company Comparison Tool," is designed to facilitate a comprehensive analysis of the financial performance of two companies. Its primary purpose is to offer users a user-friendly interface for comparing key performance indicators (KPIs) side-by-side. Leveraging the Dash framework and Yahoo Finance API, the tool retrieves financial data, converts currencies to USD, and presents the information in a visually appealing manner. This documentation outlines the data sources, methodology, results, and discussions regarding the script.

Data

The script utilizes the Yahoo Finance API to gather financial information for specified companies. The collected data includes company name, ticker symbol, sector, dividend yield, market capitalization, revenue, earnings growth, profit margins, EBITDA margins, and P/E ratio. The tool also fetches company logos from Clearbit for visual identification. All financial values are converted to USD for consistency in comparison.

Methodology

The script follows a systematic approach to achieve its objective. It starts by retrieving financial information for the specified companies through the Yahoo Finance API. The data is then processed and converted to USD using currency exchange rates obtained through the CurrencyRates class. The tool employs the Dash framework to create an interactive web-based interface, with elements for displaying company logos and various financial metrics. The interface allows users to input a list of stock tickers for comparison.

Results

The script generates a web-based dashboard displaying a side-by-side comparison of the specified companies. Key financial metrics, including market capitalization, revenue, earnings growth, dividend yield, profit margins, EBITDA margins, and P/E ratio, are presented in a visually appealing format. The tool also formats large numbers for market capitalization and revenue, providing a clearer representation. Company logos are displayed for easy visual identification.

Discussions

The tool facilitates discussions by visually highlighting the performance differences between the two companies. Users can quickly assess how each company compares in terms of market capitalization, revenue, and various financial ratios. The tool's design encourages a holistic understanding of the financial health of the companies and prompts further analysis and discussions.

Conclusion

In conclusion, the "Company Comparison Tool" offers a convenient and visually engaging platform for comparing the financial performance of two companies. The integration of Dash, Yahoo Finance API, and Clearbit logos ensures a comprehensive and user-friendly experience. Users can leverage this tool for quick assessments and in-depth discussions about the financial strengths and weaknesses of the specified companies in a chosen market or industry.

Example of output:

![Screenshot 2023-12-20 at 11 50 40](https://github.com/glicerio-vergara/Comparing_two_companies/assets/79378133/af813f1c-fbc8-4a17-bafc-dd17b5bcefad)



