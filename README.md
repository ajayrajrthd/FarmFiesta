# 🌾 FarmFiesta - Smart Agriculture Solution

An innovative smart agriculture system that leverages AI and ML to optimize farming practices, improve crop yield, and provide real-time insights to farmers. The "FarmFiesta" is a soil and crop recommendation and plant disease prevention project that integrates advanced technologies to modernize farming practices.
This system serves two main purposes:

Soil and Crop Recommendation - Utilizing machine learning to offer personalized guidance on soil preparation, fertilization, and crop selection.

Plant Disease Detection - Employing image recognition and deep learning to swiftly identify diseases, nutrient deficiencies, or pest infestations.

By providing early disease detection, this system reduces reliance on chemical treatments, enhances agricultural sustainability, and ensures food security. 

---

## 📌 Features
- Enhance Crop Yield - Provide data-driven recommendations for improved productivity.
- Resource Efficiency - Optimize fertilizers, water, and land usage.
- Sustainable Farming - Promote eco-friendly agricultural practices.
- Timely Disease Detection - Detect diseases early to prevent crop loss.
- Farmer Empowerment - Provide farmers with intuitive tools for better decision-making.
- Food Security - Improve crop resilience to ensure a stable food supply.
- Data-Driven Decisions - Utilize modern technologies for better insights.
- Scalability - Develop a system adaptable to various agricultural regions.

---

## 🏗️ System Architecture
FarmFiesta consists of:
- Crop Recommendation: Uses Naive Bayes and Random Forest Algorithm trained on a dataset containing: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall.
- Location-based live weather data from OpenWeather API
- Plant Disease Detection: Uses image processing and deep learning to diagnose plant health issues based on an image dataset.
- Web & Mobile Dashboard: Visualize farm data and control irrigation remotely.

---

## 🚀 Installation & Usage

### 📥 Install Dependencies
```bash
# Clone the repository
git clone https://github.com/yourusername/farmfiesta.git
cd farmfiesta

# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 🔧 Run the Application
```bash
# Start backend server
cd backend
npm start

# Start frontend application
cd ../frontend
npm start
```

## 🌱 Scopes

- Machine Learning Models: Enhance predictive accuracy for diseases and recommendations.
- Image Recognition: Improve the ability to identify plant diseases, pests, and deficiencies.
- Collaboration with Experts: Ensure recommendations align with agricultural research.
- E-commerce Module: Provide an online store for fertilizers, pesticides, and farming tools
