# Route-optimizer-Visualizer

An interactive web application that demonstrates and compares different pathfinding algorithms including A*, Dijkstra's, BFS, and DFS with real-time visualization.

## 🚀 Live Demo

[View the live demo here](https://route-optimizer-visualizer.vercel.app/)

## ✨ Features

- **Multiple Algorithms**: A*, Dijkstra's, Breadth-First Search, Depth-First Search


## ✨ Features

- **Multiple Algorithms**: A*, Dijkstra's, Breadth-First Search, Depth-First Search
- **Real-time Animation**: Watch algorithms find paths step-by-step
- **Terrain Types**: Grass, Road, Water, Mountain with different movement costs
- **Grid Customization**: 10×10 to 30×30 grid sizes
- **Save/Load Routes**: Persist your custom routes locally
- **Statistics Dashboard**: Real-time metrics and performance data
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Deployment Options

### Option 1: GitHub Pages (Recommended - Free)
1. Create a GitHub account at [github.com](https://github.com)
2. Create a new repository named `pathfinding-visualizer`
3. Upload the `index.html` file to the repository
4. Go to Settings → Pages → Source → Deploy from branch
5. Select `main` branch and save
6. Your site will be available at: `https://yourusername.github.io/pathfinding-visualizer`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com) and sign up
2. Click "New site from Git" or drag `index.html` to the deploy area
3. If using Git: Connect your GitHub repository
4. Your site will be available at: `https://your-site-name.netlify.app`

### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "New Project" → Import Git Repository
3. Select your repository and deploy
4. Your site will be available at: `https://your-project.vercel.app`

### Option 4: Surge.sh (Free)
1. Install Node.js from [nodejs.org](https://nodejs.org)
2. Open terminal/command prompt
3. Run: `npm install -g surge`
4. Navigate to your project folder
5. Run: `surge`
6. Follow the prompts to create an account and deploy
7. Your site will be available at: `https://your-site-name.surge.sh`

## 📱 LinkedIn Sharing

Once deployed, you can share your project on LinkedIn:

1. **Post the link** with a description like:
   ```
   🚀 Just built an interactive Pathfinding Algorithms Visualizer!
   
   Explore A*, Dijkstra's, BFS, and DFS algorithms with real-time visualization. 
   Perfect for learning computer science concepts or demonstrating algorithm efficiency.
   
   Try it out: [Your Deployed URL]
   
   #ComputerScience #Algorithms #WebDevelopment #JavaScript #Pathfinding
   ```

2. **Add to your portfolio** by including it in your LinkedIn profile's featured section

3. **Share with your network** to showcase your technical skills

## 🎯 How to Use

1. **Set Start Point**: Click "🎯 Start" mode and click a cell
2. **Set End Point**: Click "🎯 End" mode and click another cell  
3. **Add Obstacles**: Click "🧱 Wall" mode and click cells to add/remove walls
4. **Add Terrain**: Click "🗺️ Terrain" mode, select terrain type, and click cells
5. **Choose Algorithm**: Select from the dropdown menu
6. **Find Path**: Click "▶️ Find Path" to see the algorithm in action
7. **Save/Load**: Use the save and load buttons to persist your routes

## 🛠️ Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling, animations, and responsive design
- **JavaScript (ES6+)**: Algorithm implementation and interactivity
- **Local Storage**: Route persistence
- **CSS Grid**: Layout and grid system

## 📊 Algorithm Comparison

| Algorithm | Optimal Path | Speed | Use Case |
|-----------|-------------|-------|----------|
| A* | ✅ Yes | Fast | General purpose, most efficient |
| Dijkstra | ✅ Yes | Medium | Guaranteed shortest path |
| BFS | ✅ Yes | Fast | Unweighted graphs, level exploration |
| DFS | ❌ No | Fast | Quick path finding, not optimal |

## 🤝 Contributing

Feel free to fork this project and add new features like:
- Additional algorithms (Bellman-Ford, Floyd-Warshall)
- Diagonal movement
- Weighted edges
- Algorithm comparison mode
- Export/import functionality

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for learning and sharing computer science concepts** 
