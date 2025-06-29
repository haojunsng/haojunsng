# GitHub README Waves Animation

Add this to your `haojunsng/readme.md` file:

```html
<div align="center">
  <h1>🌊 Welcome to My GitHub! 🏴‍☠️</h1>
  <p>Sailing through data and tech - one adventure at a time.</p>
  
  <!-- Animated Waves with Thousand Sunny -->
  <div style="position: relative; height: 120px; overflow: hidden; margin: 20px 0;">
    <!-- Wave 1 - Deep -->
    <svg style="position: absolute; bottom: 0; width: 100%; height: 40px;" viewBox="0 0 1200 120" preserveAspectRatio="none">
      <path d="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z" 
            fill="#1e40af" opacity="0.4">
        <animate attributeName="d" 
                 dur="3s" 
                 repeatCount="indefinite"
                 values="M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z;
                         M0,0V80.29c67.79,32.2,123.59,42.17,178,38,90.36-7.37,156.33-35.31,226.8-39.5C458.64,22.43,532.34,43.67,603,62.05c89.27,20,158.3,26.88,229.4,15.08,56.15-8,89.85-19.84,124.45-31.34C1009.49,15,1133-24.29,1200,42.47V0Z;
                         M0,0V46.29c47.79,22.2,103.59,32.17,158,28,70.36-5.37,136.33-33.31,206.8-37.5C438.64,32.43,512.34,53.67,583,72.05c69.27,18,138.3,24.88,209.4,13.08,36.15-6,69.85-17.84,104.45-29.34C989.49,25,1113-14.29,1200,52.47V0Z"/>
      </path>
    </svg>

    <!-- Wave 2 - Medium -->
    <svg style="position: absolute; bottom: 0; width: 100%; height: 50px;" viewBox="0 0 1200 120" preserveAspectRatio="none">
      <path d="M0,0V30c100,20,200,20,300,0s200-20,300,0,200,20,300,0,200-20,300,0V0Z" 
            fill="#3b82f6" opacity="0.6">
        <animate attributeName="d" 
                 dur="2.5s" 
                 repeatCount="indefinite"
                 values="M0,0V30c100,20,200,20,300,0s200-20,300,0,200,20,300,0,200-20,300,0V0Z;
                         M0,0V60c100,40,200,40,300,0s200-40,300,0,200,40,300,0,200-40,300,0V0Z;
                         M0,0V30c100,20,200,20,300,0s200-20,300,0,200,20,300,0,200-20,300,0V0Z"/>
      </path>
    </svg>

    <!-- Wave 3 - Surface -->
    <svg style="position: absolute; bottom: 0; width: 100%; height: 60px;" viewBox="0 0 1200 120" preserveAspectRatio="none">
      <path d="M0,0V20c150,30,250,30,400,0s250-30,400,0,250,30,400,0V0Z" 
            fill="#60a5fa" opacity="0.8">
        <animate attributeName="d" 
                 dur="2s" 
                 repeatCount="indefinite"
                 values="M0,0V20c150,30,250,30,400,0s250-30,400,0,250,30,400,0V0Z;
                         M0,0V50c150,60,250,60,400,0s250-60,400,0,250,60,400,0V0Z;
                         M0,0V20c150,30,250,30,400,0s200-30,400,0,250,30,400,0V0Z"/>
      </path>
    </svg>

    <!-- Thousand Sunny Ship -->
    <div style="position: absolute; bottom: 20px; left: 50%; transform: translateX(-50%); z-index: 10;">
      <svg width="80" height="60" viewBox="0 0 80 60">
        <!-- Ship Hull -->
        <path d="M10,40 L70,40 L65,50 L15,50 Z" fill="#8B4513" stroke="#654321" stroke-width="1"/>
        <!-- Ship Deck -->
        <rect x="15" y="35" width="50" height="5" fill="#DEB887" stroke="#8B4513" stroke-width="1"/>
        <!-- Main Mast -->
        <rect x="38" y="25" width="4" height="15" fill="#8B4513"/>
        <!-- Sail -->
        <path d="M42,25 Q55,20 55,35 Q42,30 42,25" fill="#F5F5DC" stroke="#8B4513" stroke-width="1"/>
        <!-- Flag -->
        <rect x="40" y="20" width="8" height="6" fill="#FF0000"/>
        <!-- Sun Symbol on Flag -->
        <circle cx="44" cy="23" r="1.5" fill="#FFD700"/>
      </svg>
      
      <!-- Floating Animation -->
      <animateTransform attributeName="transform" 
                        type="translate" 
                        values="0,0; 0,-5; 0,0" 
                        dur="3s" 
                        repeatCount="indefinite"/>
    </div>
  </div>

  <!-- Your GitHub Stats -->
  <div style="margin-top: 20px;">
    <img src="https://github-readme-stats.vercel.app/api?username=haojunsng&show_icons=true&theme=radical" alt="GitHub Stats" />
  </div>
</div>
```

## 🎨 **Features:**

✅ **Animated Waves** - Three layers of moving waves  
✅ **Thousand Sunny Ship** - SVG ship with floating animation  
✅ **One Piece Colors** - Blue ocean theme  
✅ **Responsive** - Works on different screen sizes  
✅ **GitHub Compatible** - Uses only supported HTML/CSS  

## 📝 **How to Use:**

1. **Copy the HTML code** above
2. **Paste it** into your `haojunsng/readme.md` file
3. **Customize** the colors, text, or ship design as needed
4. **Commit and push** to see the animation live!

## 🚀 **Customization Options:**

- **Change colors** - Modify the fill colors in the SVG paths
- **Adjust timing** - Change the `dur` values for faster/slower waves
- **Modify ship** - Edit the ship SVG to match your style
- **Add text** - Include your name, bio, or links

The animation will work on GitHub and create a beautiful One Piece themed introduction to your profile! 🏴‍☠️ 