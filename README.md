 PickSmart-choose-smartly-spend-wisely.
A smart product analysis tool that helps buyers identify the best value-for-money items on e-commerce platforms like Amazon. By comparing product ratings with prices, it ranks products using a custom value score and visualizes the top picks through insightful charts and graphs. 

---

 Features

- Web Scraping with BeautifulSoup:  
  Extracts product data (title, price, and rating) from an Amazon search results page.

- Data Structuring with Pandas:  
  Cleans and organizes the extracted information into a structured DataFrame.

- Visualization with Matplotlib:  
  Plots the top 20 most expensive earrings using a horizontal bar chart for quick price comparison.

- Insightful Seaborn Box Plot:  
  Creates a box plot of price ranges by rating group to identify overpriced items at a glance.

- Value-for-Money Analysis:  
  Calculates a value score (rating ÷ price) to surface the top 10 best-value products.

---

 Usage

1. Run the notebook in Google Colab or locally with Jupyter.
2. Enter a valid Amazon search/category URL when prompted.
3. View structured data in tabular format.
4. Explore plots that assist in making smarter buying decisions.

---

 Example Output

- Horizontal bar chart showing the most expensive earrings
- Box plot revealing price variations within rating groups
- Table of top 10 earrings with the best value score

---

 Dependencies

- `BeautifulSoup4`
- `requests`
- `pandas`
- `matplotlib`
- `seaborn`

Install all using:
```bash
pip install beautifulsoup4 requests pandas matplotlib seaborn
