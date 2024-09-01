**Cosmetic Product Analysis: Exploring the Impact of Ingredients, Brands, and Categories on Pricing**
=====================================================================================================

**Table of Contents**
---------------------

1.  [Project Description](#project-description)
    
2.  [Data](#data)
    
3.  [Methodology](#methodology)
    
4.  [Results](#results)
    
5.  [Contributing](#contributing)
    
6.  [License](#license)
    
7.  [Acknowledgments](#acknowledgments)
    

**Project Description**
-----------------------

This project explores the pricing dynamics of cosmetic products by analyzing their ingredients, brand influence, and customer ratings. Leveraging a dataset sourced from Sephora, the project uses ingredient scoring, brand analysis, and data visualization to uncover key insights that can guide consumers and businesses in making informed decisions within the beauty industry.

**Data**
--------

The dataset, sourced from the [Comparing Cosmetics by Ingredients GitHub repository](https://github.com/satyam9090/Comparing-Cosmetics-by-Ingredients/blob/master/datasets/cosmetics.csv), contains over 1,400 cosmetic products with details on ingredients, prices, customer ratings, and skin type suitability.

### **Common Ingredients**

The 20 most common ingredients found in the dataset include:

1.  **Water** - 944 occurrences
    
2.  **Glycerin** - 901 occurrences
    
3.  **Phenoxyethanol** - 728 occurrences
    
4.  **Butylene Glycol** - 693 occurrences
    
5.  **Sodium Hyaluronate** - 402 occurrences
    
6.  **Caprylyl Glycol** - 401 occurrences
    
7.  **Dimethicone** - 382 occurrences
    
8.  **Xanthan Gum** - 378 occurrences
    
9.  **Ethylhexylglycerin** - 375 occurrences
    
10.  **Tocopheryl Acetate** - 351 occurrences
    
11.  **Citric Acid** - 322 occurrences
    
12.  **Tocopherol** - 310 occurrences
    
13.  **Caprylic/Capric Triglyceride** - 288 occurrences
    
14.  **Potassium Sorbate** - 276 occurrences
    
15.  **Disodium EDTA** - 266 occurrences
    
16.  **Carbomer** - 264 occurrences
    
17.  **Fragrance** - 256 occurrences
    
18.  **Sodium Hydroxide** - 255 occurrences
    
19.  **Limonene** - 248 occurrences
    
20.  **Sodium Benzoate** - 247 occurrences
    

**Methodology**
---------------

The analysis involved several key steps:

1.  **Ingredient Scoring**: Each ingredient was researched and scored based on its effectiveness and safety, leading to a metric for ingredient quality. For instance:
    
    *   **High Quality**: Sodium Hyaluronate, Tocopherol (+3)
        
    *   **Moderate Quality**: Glycerin, Citric Acid (+2)
        
    *   **Low Quality**: Phenoxyethanol, Fragrance (+1)
        
2.  **Visualization of Ingredient Quality vs. Price**
    
    *   A scatter plot was created to visually explore the relationship between ingredient quality and product pricing. This allowed us to see if there was any observable trend between higher-quality ingredients and product prices.
        
    *   **Observation**: The scatter plot indicates that there is no strong visual trend suggesting that higher ingredient scores directly correlate with higher product prices. The data points are scattered, showing that factors other than ingredient quality might play a significant role in determining prices.
        
3.  **Exploring Other Factors**: Various factors such as brand influence, product category, and customer ratings were analyzed to understand their impact on pricing.
    
    *   **Brand Influence**: Analyzed the average prices across different brands.
        
    *   **Product Category Impact**: Examined how different product types (e.g., moisturizers, treatments) affect pricing.
        
    *   **Customer Ratings**: Investigated the correlation between customer ratings and product prices.
        

**Results**
-----------

*   **Ingredient Quality vs. Price**: The scatter plot showed that there isn't a strong relationship between ingredient scores and product prices, suggesting that other factors might be more influential.
    
*   **Brand Influence**: Luxury brands like LA MER and SK-II command higher prices, often independent of ingredient quality, emphasizing the impact of brand reputation.
    
*   **Product Category Impact**: Treatment products are the most expensive on average, reflecting their specialized nature.
    
*   **Customer Ratings**: There is a very weak correlation between product prices and customer ratings, indicating that customer satisfaction is not a primary driver of pricing.
    

**Contributing**
----------------

Contributions are welcome! Please fork this repository and submit a pull request with your enhancements. Ensure that your contributions align with the project's goals and include relevant tests.

**License**
-----------

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Acknowledgments**
-------------------

*   Data sourced from [Sephora](https://www.sephora.com/).
    
*   Visualization libraries: Matplotlib, Seaborn.
    
*   Special thanks to [Satyam9090](https://github.com/satyam9090) for their help with data preprocessing.
