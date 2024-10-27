# International Debt Statistics - PPG Bilateral Debt

## Objective

If you have been following the news recently, you may have come across various headlines like "South Asia in Chinese Debt Trap", "Economic crisis in Sri Lanka", "Failing economy of Pakistan", etc. These news articles made me curious to look into bilateral lendings between two countries. Using Python, I developed a script to download PPG Bilateral Debt data between two countries using the World Bank API.

My project collects data of PPG bilateral lending between India and its neighbouring countries, which include Bangladesh, Bhutan, Sri Lanka, Nepal, Maldives, and Myanmar. I have wrangled and analyzed data from the last 20 years of each country individually and visualized the data in the form of an Excel dashboard for easy understanding of lending trends.  
Check out the [project report](#).

## About the dataset

The dataset includes details of PPG Bilateral debt data between India & Bangladesh/Bhutan/Sri Lanka/Maldives/Myanmar/Nepal obtained using the World Bank API. Each dataset contains 4 columns: 
- `Year`: Year of debt
- `Debtor`: Debtor country code
- `Debt in US$`: Amount of debt in US$
- `YoY Growth %`: Year on year growth percentage of bilateral debt.

All 6 datasets are combined, cleaned, wrangled, and analyzed. The data is gathered from the World Bank website and considered as primary data. The detailed analysis can be found [here](#).

## Conclusion of project

1. Total PPG Bilateral Lending has increased from less than 500 million $ in 2000 to about 45 billion $ in 2020.
2. Bhutan has been the biggest debtor country, receiving almost 18 billion $ over the period of 20 years.
3. Nepal has received the least bilateral lending, amounting to less than 1 billion $.
4. Total bilateral lending shows a positive growth rate since the last 20 years.
5. Total bilateral lending to neighbouring countries is approximately 1.2% of the overall GDP of India.
6. In the event of default by any neighboring country in the future, its impact on India’s financial sector will be minimal (considering only the above data).
