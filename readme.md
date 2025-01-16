# Particles Cursor Animation 🌌  

Leveraging WebGL and Three.js, this project brings to life a dynamic particle animation that seamlessly responds to user interactions. Using custom shaders and an image texture, it generates disc particles whose size is directly influenced by the texture’s pixel data. These particles react fluidly to mouse movements, producing an interactive hover effect that delivers an engaging and satisfying experience.

---

## 🌟 Key Features  

### 🎨 Particle Mapping  
- Particles are positioned using an image texture, where the color and size of each particle are determined by the texture's pixel data.  
- Real-time updates to particle positions and effects using custom **vertex** and **fragment shaders**.  

### 🖱️ Interactive Hover Effect  
- A displacement map adds a hover effect when the mouse pointer moves over the particles.  
- Particles ripple and disperse dynamically, creating a fluid, interactive visual.  

### ✨ Shader Effects  
- Custom **vertex shader** controls particle positioning and movement, incorporating noise for a liquid-like effect.  
- Custom **fragment shader** enhances particle appearance with glow and color grading.  

### ⚙️ Responsive Design  
- Automatically adjusts canvas size and resolution on window resize.  
- Optimized for various devices with pixel ratio settings.  

---

## 🚀 Setup  

Download [Node.js](https://nodejs.org/en/download/) and follow these steps:  

```bash
# Clone the repository  
git clone <repository-url>  

# Navigate to the project directory  
cd <project-folder>  

# Install dependencies (only the first time)  
npm install  

# Run the local server at localhost:8080  
npm run dev  

# Build for production in the dist/ directory  
npm run build  
