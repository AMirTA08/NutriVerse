# 🌱 Nutriverse

**Nutriverse** is a smart nutrition and diet assistance platform powered by machine learning. It delivers personalized diet recommendations, detects nutritional deficiencies, classifies food items, and even predicts surplus food to reduce waste. Designed to serve individuals, nutritionists, and volunteers, Nutriverse promotes health, sustainability, and food distribution efficiency.

## 🔍 Features

**🥗 Diet Recommendation**  
Suggests personalized, regionally valid diet plans based on user input.

**💊 Nutrition Deficiency Guidance**  
Recommends food items to overcome specific nutrient deficiencies.

**🍱 Food Classification**  
Classifies food items using a machine learning model trained on a food dataset.

**📍 Volunteer & Map Integration**  
Assists in food delivery and logistics using location tracking.

**📈 Surplus Prediction**  
Uses past data to predict potential surplus food for better planning and donation.

## 🤖 Machine Learning Models

- `diet_model.pkl`: Suggests region-specific balanced diets.
- `food_classifier.pkl`: Classifies input food items into nutritional categories.
- `nutrition_model.pkl`: Recommends diet changes based on deficiencies.
- `vectorizer.pkl`: Used for text preprocessing (e.g., TF-IDF).
- `ml_model/model.pkl`: Predicts restaurant surplus food based on historical data.

## 📊 Datasets Used

- `deficiency_recommendation_dataset.csv`
- `regionally_valid_diet_meal_plan (1).csv`
- `food_classification_dataset.csv`
- `restaurant_surplus_data_2000.csv`

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/nutriverse.git
cd nutriverse
