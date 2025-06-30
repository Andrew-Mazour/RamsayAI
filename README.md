# 🍳 Ramsay AI - AI-Powered Smart Meal Planner

> *"There's nothing to eat"* - We've all been there. Staring at a packed fridge or pantry and still thinking there's nothing to cook. Ramsay AI eliminates this everyday problem using AI to transform your kitchen inventory into delicious meal possibilities.

## 🌟 What We Built

Ramsay AI is a smart, AI-powered meal planner that revolutionizes how you think about cooking. Users can:

- **📸 Snap & Scan**: Take a photo of their pantry or fridge
- **🤖 AI Detection**: Let AI detect ingredients and count what's available
- **🍽️ Recipe Generation**: Get personalized recipe ideas based on current inventory
- **⚖️ Nutrition Focus**: Specify calorie and macronutrient targets (protein, carbs, fat)
- **📋 Complete Recipes**: Full instructions, cook time, and ingredient lists
- **📅 Meal Planning**: Receive full weekly meal prep plans (3 meals/day) based on what's on hand
- **🔍 Smart Search**: Find recipes by ingredients, macros, or dietary preferences

## Demo
https://github.com/user-attachments/assets/3e755779-555c-4d45-93b1-2077aad89501

## ✨ Key Features

### 🖼️ **Image Upload & Food Detection**
- **Drag & Drop Interface**: Easy image upload with visual feedback
- **Camera Integration**: Direct camera access for mobile users
- **AI-Powered Recognition**: Detects 50+ common food items across 8 categories:
  - 🥬 Vegetables (tomato, onion, garlic, bell pepper, etc.)
  - 🍎 Fruits (apple, banana, orange, lemon, etc.)
  - 🥩 Meat (chicken breast, ground beef, salmon, bacon, etc.)
  - 🥛 Dairy (milk, cheese, butter, yogurt, eggs, etc.)
  - 🌾 Grains (rice, pasta, bread, etc.)
  - 🌿 Herbs (basil, parsley, cilantro, rosemary, etc.)
  - 🧂 Pantry (olive oil, salt, pepper, flour, sugar, etc.)
  - 🥫 Condiments (ketchup, mustard, mayonnaise, soy sauce, etc.)

### 📊 **Smart Ingredient Management**
- **Automatic Counting**: AI estimates quantities of detected items
- **Manual Adjustment**: Fine-tune counts with +/- controls
- **Confidence Scoring**: See detection accuracy for each item
- **Category Classification**: Organized by food type for easy browsing

### 🎯 **Nutrition & Macro Tracking**
- **Custom Macros**: Set protein, carbs, fat, and calorie targets
- **Dietary Preferences**: Filter recipes by dietary restrictions
- **Nutritional Analysis**: Complete nutritional breakdown for each recipe
- **Health-Focused**: Prioritize recipes that meet your nutritional goals

### 🔍 **Advanced Recipe Search**
- **Ingredient-Based**: Find recipes using available ingredients
- **Macro-Based**: Search by nutritional requirements
- **AI-Powered**: Natural language search with intelligent suggestions
- **Favorites System**: Save and organize your favorite recipes

## 🛠️ How We Built It

### **Frontend Stack**
- **React 18** - Modern UI library with hooks and functional components
- **TypeScript** - Type-safe development for better code quality
- **Vite** - Lightning-fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework for rapid styling
- **Shadcn/ui** - Beautiful, accessible component library
- **Radix UI** - Low-level, accessible component primitives
- **React Router** - Client-side routing for seamless navigation
- **React Hook Form** - Performant forms with validation
- **Lucide React** - Beautiful, customizable icons

### **Backend & AI Integration**
- **Node.js** - Server-side JavaScript runtime
- **OpenAI APIs** - Advanced AI for:
  - Image analysis and food recognition
  - Recipe generation and meal suggestions
  - Natural language processing for search
- **MongoDB** - NoSQL database for storing:
  - User preferences and meal history
  - Recipe data and nutritional information
  - Ingredient database and categories

### **Development Tools**
- **ESLint** - Code linting and quality assurance
- **PostCSS** - CSS processing and optimization
- **Hot Module Replacement** - Instant development feedback

## 🚀 Getting Started

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager

### Installation

```bash
# Clone the repository
git clone <YOUR_REPO_URL>
cd spurhacks

# Install dependencies
npm install

# Start development server
npm run dev
```

The application will be available at `http://localhost:8080` (or the next available port).

### Building for Production

```bash
# Build the project
npm run build

# Preview the production build
npm run preview
```

## 🎯 How to Use

### 1. **Upload Your Kitchen Inventory**
   - Navigate to the "Find Your Recipe" section
   - Click the "Upload Image" tab
   - Take a photo or upload an image of your fridge/pantry
   - Let AI detect and count your ingredients

### 2. **Review Detected Items**
   - Check the AI's detection results
   - Adjust counts if needed using +/- buttons
   - Remove any incorrect detections
   - Add missing ingredients manually

### 3. **Set Your Preferences**
   - Specify calorie targets
   - Set macronutrient goals (protein, carbs, fat)
   - Choose dietary restrictions
   - Select meal types (breakfast, lunch, dinner)

### 4. **Discover Recipes**
   - Browse AI-generated recipe suggestions
   - Filter by ingredients, macros, or dietary needs
   - Save favorites for later
   - Get complete cooking instructions

### 5. **Plan Your Week**
   - Generate weekly meal plans
   - Get shopping lists for missing ingredients
   - Track your nutritional goals

## 🧠 What We Learned

- **Computer Vision Challenges**: Working with vision models in real-world conditions (poor lighting, cluttered spaces, reflections)
- **AI Prompt Engineering**: Crafting precise prompts for consistent, structured AI outputs
- **User Experience Design**: Building intuitive interfaces for complex AI interactions
- **System Integration**: Connecting multiple components (frontend, backend, AI, database) into a cohesive system
- **Performance Optimization**: Balancing AI accuracy with real-time user experience

## 🚧 Challenges We Faced

### **Image Quality Issues**
**Problem**: Poor lighting in user photos made ingredient recognition unreliable.
**Solution**: Implemented image preprocessing to improve brightness and contrast before AI analysis.

### **AI Output Consistency**
**Problem**: AI responses varied in format and structure.
**Solution**: Carefully crafted prompts and implemented response validation to ensure clean, structured recipe outputs.

### **Real-time Performance**
**Problem**: AI processing could be slow, affecting user experience.
**Solution**: Implemented loading states, progress indicators, and optimized API calls for better perceived performance.

## 🔮 What's Next

### **Immediate Roadmap**
- 🛒 **Smart Shopping Lists**: Generate grocery lists for missing ingredients
- 🎤 **Voice Commands**: Add voice interface for hands-free operation
- 📱 **Mobile App**: Native mobile application for better camera integration
- 🌍 **Multi-Language**: Support for different languages and regional cuisines

### **Advanced Features**
- 📊 **Nutritional Tracking**: Daily/weekly nutritional goal tracking
- 🏷️ **Barcode Scanning**: Scan product barcodes for instant ingredient addition
- 📅 **Meal Prep Planning**: Advanced meal prep scheduling and reminders
- 👥 **Social Features**: Share recipes and meal plans with friends and family
- 🏪 **Grocery Integration**: Connect with grocery delivery services

### **AI Enhancements**
- 🍎 **Freshness Detection**: Evaluate food freshness from images
- 🏷️ **Brand Recognition**: Identify specific food brands and products
- 📏 **Quantity Estimation**: More accurate quantity and portion detection
- 🧠 **Learning System**: AI learns from user preferences and cooking patterns

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues, feature requests, or pull requests.

### Development Setup
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- **OpenAI** for providing the AI capabilities that power our food detection and recipe generation
- **Spoonacular API** for comprehensive recipe database
- **Shadcn/ui** for the beautiful component library
- **Tailwind CSS** for the utility-first styling approach
- **Vite** for the lightning-fast development experience

---

**Built with ❤️ for everyone who's ever stared at a full fridge and thought "there's nothing to eat"**

*Ramsay AI - Where AI meets your kitchen*
