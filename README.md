# Retail Grocery Price Comparison Across China, the US, and Indonesia

## 1. Problem & User
Grocery prices are difficult to compare across countries due to differences in currency and product sizes, therefore Python is needed to compare prices across China, the US, and Indonesia. It is intended for students, travellers, and price-conscious consumers who want a better understand living costs  before moving or travelling to these countries.

## 2. Data
The data was collected manually from Walmart (US), Hypermart (Indonesia), and Sam’s Club (China) using their official platforms in 15 April 2026. I focused on common everyday products such as dairy, grains, protein, beverages, and household items. The dataset includes market, retailer, product name, category, package size, unit type, and price, which were later used to calculate unit price in USD.

## 3. Methods
The dataset was cleaned using pandas by removing empty rows and standardising column names. All package sizes were standardized into kilograms and litres, and prices were converted into USD for consistency. Unit prices were calculated to allow fair comparison. Groupby and pivot tables were used to compare prices across countries, and matplotlib was used to visualise the results.

## 4. Key Findings
- Indonesia has the lowest average unit price overall.
- China is slightly higher than Indonesia.
- The US has the highest average unit price overall.
- No single market is the cheapest for all products.
- Dairy products, such as milk and yogurt, are cheaper in the US, while basic needs such as rice and bottled water are cheaper in Indonesia.

## 5. How to run
Download this repository and open the Jupyter Notebook (.ipynb) using Jupyter Notebook or JupyterLab. Make sure required libraries such as pandas and matplotlib are installed. Then run all cells from top to bottom to reproduce the full workflow, including data cleaning, standardisation, analysis, and visualisation.

## 6. Product link / Demo
(https://video.xjtlu.edu.cn/Mediasite/Play/eafb1190d1a6422db7c42bb40065dab91d)

## 7. Limitations & next steps
There are several limitations in this project. First, the products compared are not exactly the same across countries, as different brands and variations are available. Second, some items are sold in bulk while others are sold individually, which makes comparison less accurate even after standardisation. In addition, some products were sold at discounted prices, which may not reflect their usual price. Lastly, prices were converted using fixed exchange rates, so any changes in currency values could affect the accuracy of the results. In the future, this analysis could be improved by including more products and more retailers, as well as collecting data over a longer period. Using real-time exchange rates and focusing on more similar brands would also make the comparison more accurate.
