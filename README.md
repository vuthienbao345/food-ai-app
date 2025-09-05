# 🍽️ Plante AI - Smart Meal Analysis App

<div align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/AI-Powered-FF6B6B?style=for-the-badge" alt="AI Powered">
  <img src="https://img.shields.io/badge/Health-Focused-4ECDC4?style=for-the-badge" alt="Health Focused">
</div>

## 📱 Overview

**Plante AI** is an innovative Flutter application that revolutionizes how we understand and improve our eating habits through advanced AI-powered meal analysis. Simply take a photo of your meal, and our intelligent system will provide comprehensive insights, health recommendations, and safety alerts.

## ✨ Key Features

### 🔍 **Intelligent Meal Analysis**
- **Instant Recognition**: Upload a photo and get instant analysis of your meal components
- **Nutritional Breakdown**: Detailed macronutrient and micronutrient analysis
- **Ingredient Detection**: Advanced AI identifies individual food items and ingredients
- **Calorie Estimation**: Accurate calorie counting based on visual analysis

### 🏥 **Health & Wellness Recommendations**
- **Personalized Suggestions**: AI-driven recommendations to improve your meal choices
- **Dietary Goal Alignment**: Customized advice based on your health objectives
- **Nutritional Gaps**: Identify missing nutrients and suggest improvements
- **Meal Optimization**: Tips to make your meals more balanced and nutritious

### ⚠️ **Safety & Health Alerts**
- **Allergen Detection**: Identify potential allergens in your food
- **Dangerous Combinations**: Alert about potentially harmful food combinations
- **Contamination Warnings**: Detect signs of spoiled or unsafe food
- **Dietary Restrictions**: Flag foods that don't align with your dietary needs

### 📊 **Advanced Analytics**
- **Meal History Tracking**: Comprehensive log of your analyzed meals
- **Trend Analysis**: Visualize your eating patterns over time
- **Progress Monitoring**: Track improvements in your dietary choices
- **Health Score**: Get a comprehensive health rating for your meals

### 🎯 **Additional Advantages**
- **Multi-language Support**: Analyze meals in various languages
- **Offline Capability**: Core features work without internet connection
- **Cross-platform**: Seamless experience across iOS, Android, and Web
- **Privacy-Focused**: Your data stays secure with local processing options
- **Educational Content**: Learn about nutrition and healthy eating habits
- **Social Features**: Share healthy meal discoveries with friends and family

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (3.6.0 or higher)
- Dart SDK
- Android Studio / VS Code with Flutter extensions
- iOS Simulator / Android Emulator (for testing)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/vuthienbao345/food-ai-app.git
   cd plante_ai_app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the application**
   ```bash
   flutter run
   ```

### Build for Production

**Android APK:**
```bash
flutter build apk --release
```

**iOS App:**
```bash
flutter build ios --release
```

**Web:**
```bash
flutter build web --release
```

## 🏗️ Project Structure

```
lib/
├── main.dart                 # Application entry point
├── models/                   # Data models
├── services/                 # AI and API services
├── screens/                  # UI screens
├── widgets/                  # Reusable UI components
├── utils/                    # Utility functions
└── constants/                # App constants
```

## 🛠️ Technology Stack

- **Framework**: Flutter 3.6.0+
- **Language**: Dart
- **AI/ML**: TensorFlow Lite, Custom ML Models
- **Image Processing**: Camera, Image Picker
- **State Management**: Provider/Riverpod
- **Local Storage**: Hive/SQLite
- **Networking**: HTTP, Dio

## 📱 Screenshots

<div align="center">
  <img src="assets/screenshots/meal_analysis.png" alt="Meal Analysis" width="200">
  <img src="assets/screenshots/health_recommendations.png" alt="Health Recommendations" width="200">
  <img src="assets/screenshots/nutrition_breakdown.png" alt="Nutrition Breakdown" width="200">
</div>

## 🔧 Configuration

### API Keys
Create a `.env` file in the root directory:
```env
AI_API_KEY=your_ai_api_key_here
NUTRITION_API_KEY=your_nutrition_api_key_here
```

### Permissions
The app requires the following permissions:
- **Camera**: For taking meal photos
- **Storage**: For saving analysis results
- **Internet**: For AI processing and updates

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- TensorFlow team for ML capabilities
- Nutrition databases and APIs
- Open source community