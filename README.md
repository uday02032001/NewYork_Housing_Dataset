# NewYork_Housing_Dataset

This project analyzes the New York house dataset to help users find their perfect home. I started by cleaning the data to ensure accuracy and consistency, and added several new columns to enable deeper analysis of the listings. Using pivot tables, I explored key metrics like price, square footage, and home features across different localities and home types.

To make the insights accessible, I built an interactive dashboard with charts and slicers. You can easily filter and explore the data based on your preferences-such as price range, location, or number of bedrooms-to discover the best house options for your needs. The dashboard provides a user-friendly way to compare listings, visualize trends, and make informed decisions.

Quick Insights:

Average Price: The average house price is $1.638 million.

Listings: There are 4,424 listings in the dataset.

Price per Sqft: The average price per square foot is $723.

Expensive Homes: The top 5 most expensive houses range from approximately $40 million to $52 million.

Cheapest Homes: The top 5 cheapest houses are around $9 million to $12 million.

Price by Locality: The average house price by locality varies significantly, with some areas having much higher prices than others.


Top 10 Expensive Houses
Used pivot charts to identify the top 10 most expensive houses by sorting broker titles and prices in descending order.

Applied a Top 10 filter to highlight the highest-priced listings.

Detected and excluded outliers in beds, baths, and price columns using the Z-score method to ensure data accuracy.

This section helps users quickly spot the most luxurious and premium homes available in the dataset.

Top 10 Cheapest Houses
Used pivot charts to find the top 10 cheapest houses by sorting prices in ascending order.

Applied a Top 10 filter to focus on the most affordable options.

Analysis revealed a diverse range of affordable listings across different locations, making it easier for budget-conscious buyers to find suitable homes.

Average Price by Locality
Calculated the average house price for each locality by grouping prices accordingly.

This comparison helps users identify which neighborhoods are more expensive and which are more budget-friendly, aiding in location-based decision-making.

Average Sqft Price by Locality
Analyzed the average price per square foot for each locality, which is a crucial metric for understanding real estate value.

Localities with higher average sqft prices often indicate premium or highly desirable areas, while lower prices may suggest better value for larger spaces.

This insight helps buyers compare value across different neighborhoods, not just total price.

Average Sqft Price by Home Type
Segmented data by home type (e.g., condo, townhouse, single-family) to compare average price per square foot.

Revealed which home types tend to be more expensive or offer better value, helping buyers choose the right property type for their needs and budget.

Total Listing Homes KPI
Displays the total number of listings in the dataset (4,424), providing an overview of market inventory.

Helps users and stakeholders gauge the size and diversity of available homes.

Average Price KPI
Shows the average price of all listings ($1,638K).

This KPI updates dynamically based on user-selected filters, giving real-time insights into average prices for specific requirements.

Average Beds KPI
Indicates the average number of bedrooms across all listings, helping users understand typical home sizes in the dataset.

Useful for buyers looking for homes that fit their family size or lifestyle.

Average Baths KPI
Shows the average number of bathrooms, which can be an indicator of comfort and luxury in the listings.

Average Sqft Price KPI
Displays the overall average price per square foot ($723).

This metric is essential for comparing value between listings and helps users make informed decisions about which homes offer the best deal for their budget.

Additional Points

The dashboard features interactive charts and slicers, allowing users to filter results by budget, beds, baths, location, and home type for a personalized experience.

All key metrics and visualizations update instantly based on user selections, making the dashboard a powerful tool for both buyers and real estate professionals.

The project demonstrates a full data analysis workflow: from data cleaning and feature engineering to visualization and dashboard creation, ensuring insights are both accurate and actionable.
