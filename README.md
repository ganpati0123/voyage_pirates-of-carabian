# Voyage Hackathon - 3D Pirate Adventure

A stunning 3D pirate-themed hackathon website with immersive 3D graphics, smooth animations, and continuous background music.

## 🚀 Deployment to Vercel

This project is a static site ready for Vercel deployment.

### Prerequisites
- Vercel account (free at vercel.com)
- Git repository (GitHub, GitLab, or Bitbucket)

### Deployment Steps

1. **Initialize Git Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Voyage Hackathon 3D Experience"
   ```

2. **Push to GitHub**
   - Create a new repository on GitHub
   - Push your code:
   ```bash
   git remote add origin https://github.com/your-username/voyage-hackathon.git
   git branch -M main
   git push -u origin main
   ```

3. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "Add New Project"
   - Import your GitHub repository
   - Click "Deploy"

   Vercel will automatically detect the static files and deploy them.

## 📁 Project Structure

- `index.html` - Main 3D experience (default)
- `index-2d.html` - 2D alternative version
- `pirate.mp3` - Background music (loops continuously)
- `*.glb` - 3D model files (sands_location, captain_jack_sparrow, etc.)
- `README.md` - Project documentation
- `.gitignore` - Git ignore rules

## 🎮 Features

- **3D Experience**: Interactive 3D scene with Three.js
- **Continuous Music**: Pirate-themed background music
- **Smooth Animations**: Natural character movements
- **Responsive Design**: Works on desktop and mobile
- **2D/3D Toggle**: Switch between 2D and 3D versions
- **Camera Movement**: Subtle cinematic camera shifts

## 🎨 Key Components

- **Camera**: Fixed position with subtle shifts after Z=-55 depth
- **Captain Jack Sparrow**: Animated around fixed position
- **Main GLB**: Fixed position with breathing scale effect
- **Flying Birds**: Owls and macaws with synchronized movement
- **Pirate Characters**: Octopus, Barbossa, and coin with subtle animations

## 📝 Notes

- GLB files are large (some >40MB) - ensure Vercel's 100MB file limit is respected
- Music is set to 40% volume for comfortable background listening
- All 3D elements have fixed positions with subtle animations
- Camera moves only forward/backward with subtle cinematic shifts
- This is a pure static site - no configuration files or build process required
- Vercel automatically detects and deploys static HTML sites

Generated with [Devin](https://devin.ai)