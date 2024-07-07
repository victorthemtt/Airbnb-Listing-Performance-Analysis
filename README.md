# Airbnb Listing Performance Analysis
Ivy Zhang, Mrimon “Nemo” Guha, and Tiantong "Victor" Mao

This repository hosts the project on Airbnb Listing Performance Analysis in Seattle, conducted as a machine learning assignment by a small group of people. The primary goal of this project is to use various machine learning techniques to predict the performance of Airbnb listings based on a myriad of attributes and to provide actionable insights for property hosts.

## Project Overview

Utilizing a comprehensive dataset from Kaggle, this project explores key factors influencing Airbnb listing performances in Seattle. Through detailed exploratory data analysis and regression modeling, we investigate how variables such as location, price, and amenities affect the likelihood of listings being booked.

## Files

- `Airbnb Listing Performance Analysis_FINAL.ipynb`: A Jupyter notebook containing the data analysis, feature engineering, and machine learning modeling.

## Technologies Used

- **Python**: Programming language for analysis.
- **Pandas** and **NumPy**: For data manipulation.
- **Matplotlib** and **Seaborn**: For visualizing data.
- **Scikit-Learn**: For implementing machine learning models.
- **Tableau**: Dashboard visualizations to enhance understanding of the data (link to dashboard if public).

## Feature Engineering

We enhanced the dataset by:
- **Creating new features**: Such as calculating the ratio of positive reviews to total reviews and categorizing properties based on size and location attributes. Creating a new feature called 'distance_to_space_needle' as an important contributor to Seattle's Airbnb listing
-   price.
- **Transforming categorical variables**: Applied one-hot encoding to make categorical data suitable for modeling.
- **Handling missing data**: Imputed or removed missing values based on the impact assessment on the dataset’s integrity.

## Setup

To run this project locally:
```bash
pip install -r requirements.txt  # Install the required Python packages
jupyter notebook  # Run Jupyter notebook in the project directory
```

## Results and Conclusion

Key outcomes of the analysis include:
- **Location Impact**: Proximity to the Space Needle significantly affects listing availability, overshadowing even price factors.
- **Pricing Strategy**: Weekly price adjustments were crucial in predicting listing performance, indicating the importance of competitive pricing.
- **Optimal Model Settings**: Fine-tuning model parameters enhanced predictive accuracy, highlighting the need for model-specific adjustments.

### Interpretation

The results suggest that hosts can optimize their listing visibility and profitability by focusing on strategic pricing and capitalizing on location advantages. Furthermore, model insights can help in crafting targeted marketing strategies for Airbnb properties in tourist-heavy zones.

## Future Work

Suggestions for extending this project:
1. **Dynamic Pricing Models**: Integrate dynamic pricing tools to adjust listing prices based on real-time demand and supply metrics.
2. **User Feedback Analysis**: Incorporate natural language processing to analyze guest reviews for deeper insights into guest satisfaction.
3. **Predictive Maintenance**: Develop predictive models to suggest maintenance and upgrades based on usage patterns and guest feedback.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgements

Thanks to Ivy Zhang, Mrimon “Nemo” Guha for their collaboration. Special thanks to Kaggle for providing the dataset that made this analysis possible.

---

This README provides a comprehensive overview of your project, the methodologies employed, and future directions. Adjust as necessary to align with your specific project details or personal preferences. If there's anything else you'd like to modify or add, feel free to let me know!
