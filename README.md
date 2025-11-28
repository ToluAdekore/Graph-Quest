# 🎮 Graph Quest - Master Algorithms Through Play

<div align="center">

![Graph Quest Logo](docs/images/logo.png)

**An interactive Unity game that transforms complex algorithms into engaging puzzles**

[![Unity Version](https://img.shields.io/badge/Unity-2021.3%2B-blue.svg)](https://unity.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![GitHub Stars](https://img.shields.io/github/stars/yourusername/graph-quest?style=social)](https://github.com/yourusername/graph-quest/stargazers)

[🎯 Play Demo](https://yourusername.github.io/graph-quest) • [📚 Documentation](docs/README.md) • [🐛 Report Bug](https://github.com/yourusername/graph-quest/issues) • [✨ Request Feature](https://github.com/yourusername/graph-quest/discussions)

</div>

---

## 🌟 Overview

**Graph Quest** is an educational game designed for COMP 359 (Design and Analysis of Algorithms) students at UFV. Instead of just reading about algorithms, you'll solve interactive puzzles that teach you how they work through hands-on gameplay.

### 🎓 Based On
- **Course**: COMP 359 - Design and Analysis of Algorithms
- **Textbook**: "The Design & Analysis of Algorithms" (3rd ed.) by Anany Levitin
- **Institution**: University of the Fraser Valley
- **Instructor**: Dr. Russell Campbell

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🎯 **50+ Levels** | Progressive difficulty from beginner to expert |
| 🧠 **5 Game Modes** | Cover all major algorithm categories |
| ⚡ **Real-time Feedback** | Instant validation with helpful hints |
| 📊 **Visual Learning** | See algorithms execute step-by-step |
| 🏆 **Achievement System** | Track your progress and mastery |
| 🎨 **Beautiful UI** | Clean, modern interface with smooth animations |
| 💾 **Progress Saving** | Never lose your progress |
| 🌐 **Cross-Platform** | Windows, macOS, Linux, and WebGL |

---

## 🎮 Game Modes

### 1. 🌲 Graph Traversal Challenge
**Master the fundamentals of graph exploration**

- **DFS (Depth-First Search)**: Dive deep into tree structures
- **BFS (Breadth-First Search)**: Explore level by level
- **Topological Sort**: Order tasks with dependencies

📚 *Based on Chapter 3: Brute Force and Exhaustive Search*

```
Difficulty: ⭐ Easy to ⭐⭐⭐ Hard
Levels: 1-10
Algorithm Time: O(V + E)
```

---

### 2. 🗺️ Shortest Path Quest
**Find the most efficient routes through networks**

- **Dijkstra's Algorithm**: Weighted shortest paths
- **Floyd-Warshall**: All-pairs shortest paths
- **Network Flow**: Maximize throughput

📚 *Based on Chapters 8 & 10: Dynamic Programming, Iterative Improvement*

```
Difficulty: ⭐⭐ Medium to ⭐⭐⭐⭐ Expert
Levels: 11-20
Algorithm Time: O(V² log V) to O(V³)
```

---

### 3. 📊 Sorting Arena
**Race sorting algorithms and learn their complexities**

- **Merge Sort**: Divide and conquer
- **Quick Sort**: Efficient partitioning
- **Heap Sort**: Priority queue magic

📚 *Based on Chapters 4, 5, 6: Decrease-and-Conquer, Divide-and-Conquer, Transform-and-Conquer*

```
Difficulty: ⭐⭐ Medium
Levels: 21-30
Algorithm Time: O(n log n)
```

---

### 4. 💎 Dynamic Programming Dungeon
**Solve optimization puzzles with clever subproblem solutions**

- **Coin Collection**: Maximize value with constraints
- **Knapsack Problem**: Pack the most valuable items
- **Matrix Chain**: Optimize multiplication order

📚 *Based on Chapter 8: Dynamic Programming*

```
Difficulty: ⭐⭐⭐ Hard to ⭐⭐⭐⭐ Expert
Levels: 31-40
Algorithm Time: O(n²) to O(n³)
```

---

### 5. 💑 Matching Madness
**Create stable pairings and maximum matchings**

- **Bipartite Matching**: Pair elements optimally
- **Stable Marriage**: Find stable partnerships
- **Maximum Flow**: Optimize network capacity

📚 *Based on Chapter 10: Iterative Improvement*

```
Difficulty: ⭐⭐⭐⭐ Expert
Levels: 41-50
Algorithm Time: O(V²E)
```

---

## 🚀 Quick Start

### Prerequisites

- **Unity**: 2021.3 LTS or newer ([Download](https://unity.com/download))
- **Git**: For version control ([Download](https://git-scm.com/))
- **Text Editor**: VS Code, Visual Studio, or Rider (optional)

### Installation

#### Option 1: Clone and Play (Recommended)

```bash
# Clone the repository
git clone https://github.com/yourusername/graph-quest.git
cd graph-quest

# Open in Unity Hub
# 1. Launch Unity Hub
# 2. Click "Open" or "Add"
# 3. Select the graph-quest folder
# 4. Wait for Unity to import assets (~2-5 minutes)

# Play!
# Open Assets/Scenes/MainMenu.unity and press Play ▶️
```

#### Option 2: Download Release Build

1. Go to [Releases](https://github.com/yourusername/graph-quest/releases)
2. Download the build for your platform
3. Extract and run the executable
4. Start learning!

### First Time Setup

```bash
# If contributing, create your own branch
git checkout -b feature/your-feature-name

# Install Unity packages (if needed)
# Window -> Package Manager -> Install required packages
```

---

## 🎯 How to Play

### Basic Controls

| Input | Action |
|-------|--------|
| **Left Click** | Select nodes/UI elements |
| **Right Click** | Deselect or cancel |
| **ESC** | Pause menu |
| **R** | Reset current level |
| **H** | Show hint (-10 points) |
| **Space** | Step through algorithm |

### Gameplay Loop

```
1. Choose Game Mode
   ↓
2. Select Level
   ↓
3. Read Instructions & Objective
   ↓
4. Click Nodes in Correct Order
   ↓
5. Get Real-time Feedback
   ↓
6. Complete Level & Earn Stars ⭐⭐⭐
   ↓
7. Unlock Next Level!
```

### Scoring System

- ✅ **Correct Node**: +10 points
- ❌ **Wrong Node**: -5 points
- 💡 **Hint Used**: -10 points
- ⚡ **Time Bonus**: Up to +50 points
- ⭐ **Perfect Run**: +100 points

### Star Ratings

| Stars | Requirement |
|-------|-------------|
| ⭐ | Complete the level |
| ⭐⭐ | Complete within time limit |
| ⭐⭐⭐ | Perfect run (no mistakes, no hints) |

---

## 📚 Learning Resources

### In-Game Tutorials

Each game mode includes:
- 📖 **Algorithm Explanation**: What it does and why
- 🎯 **Step-by-Step Guide**: How to approach the puzzle
- 💡 **Interactive Hints**: Contextual help when stuck
- 📊 **Complexity Analysis**: Big-O notation explained

### Algorithm Reference

```
┌─────────────────────────┬──────────────┬────────────────┐
│ Algorithm               │ Time         │ Space          │
├─────────────────────────┼──────────────┼────────────────┤
│ DFS / BFS               │ O(V + E)     │ O(V)           │
│ Dijkstra                │ O(V² log V)  │ O(V)           │
│ Floyd-Warshall          │ O(V³)        │ O(V²)          │
│ Merge Sort              │ O(n log n)   │ O(n)           │
│ Quick Sort (avg)        │ O(n log n)   │ O(log n)       │
│ Heap Sort               │ O(n log n)   │ O(1)           │
│ Knapsack (0/1)          │ O(nW)        │ O(nW)          │
│ Max Flow                │ O(V²E)       │ O(V)           │
│ Bipartite Matching      │ O(VE)        │ O(V)           │
└─────────────────────────┴──────────────┴────────────────┘
```

### External Resources

- 📕 [Course Textbook](https://www.pearson.com/en-us/subject-catalog/p/design-and-analysis-of-algorithms-the/P200000003302)
- 🎥 [Algorithm Visualizations](https://visualgo.net/)
- 📝 [Big-O Cheat Sheet](https://www.bigocheatsheet.com/)
- 💻 [LeetCode Practice](https://leetcode.com/)

---

## 🏗️ Project Structure

```
GraphQuest/
├── Assets/
│   ├── Scenes/                    # Unity scenes
│   │   ├── MainMenu.unity         # Main menu scene
│   │   ├── LevelSelect.unity      # Level selection
│   │   └── GameLevel.unity        # Gameplay scene
│   │
│   ├── Scripts/
│   │   ├── Core/                  # Core game systems
│   │   │   ├── GameManager.cs     # Game state management
│   │   │   ├── LevelManager.cs    # Level logic
│   │   │   ├── ScoreManager.cs    # Score tracking
│   │   │   └── AudioManager.cs    # Sound effects & music
│   │   │
│   │   ├── Graph/                 # Graph data structures
│   │   │   ├── Node.cs            # Node class
│   │   │   ├── Edge.cs            # Edge class
│   │   │   ├── Graph.cs           # Graph container
│   │   │   └── GraphVisualizer.cs # Rendering logic
│   │   │
│   │   ├── Algorithms/            # Algorithm implementations
│   │   │   ├── DFS.cs             # Depth-First Search
│   │   │   ├── BFS.cs             # Breadth-First Search
│   │   │   ├── Dijkstra.cs        # Dijkstra's algorithm
│   │   │   ├── FloydWarshall.cs   # Floyd-Warshall
│   │   │   ├── MergeSort.cs       # Merge sort
│   │   │   ├── QuickSort.cs       # Quick sort
│   │   │   ├── HeapSort.cs        # Heap sort
│   │   │   ├── Knapsack.cs        # Knapsack DP
│   │   │   └── MaxFlow.cs         # Maximum flow
│   │   │
│   │   ├── UI/                    # User interface
│   │   │   ├── MenuController.cs  # Menu navigation
│   │   │   ├── LevelSelector.cs   # Level grid
│   │   │   ├── HUDController.cs   # In-game HUD
│   │   │   └── SettingsPanel.cs   # Settings menu
│   │   │
│   │   └── Levels/                # Level-specific scripts
│   │       ├── DFSLevel.cs        # DFS level logic
│   │       ├── BFSLevel.cs        # BFS level logic
│   │       ├── ShortestPathLevel.cs
│   │       └── ...
│   │
│   ├── Prefabs/                   # Reusable game objects
│   │   ├── NodePrefab.prefab      # Node visual
│   │   ├── EdgePrefab.prefab      # Edge visual
│   │   └── UIElements/            # UI prefabs
│   │
│   ├── Materials/                 # Visual materials
│   │   ├── NodeMaterial.mat
│   │   ├── EdgeMaterial.mat
│   │   └── HighlightMaterial.mat
│   │
│   ├── Resources/                 # Runtime resources
│   │   ├── LevelData/             # Level definitions (JSON)
│   │   │   ├── DFS/
│   │   │   │   ├── level_1.json
│   │   │   │   └── ...
│   │   │   ├── BFS/
│   │   │   └── ...
│   │   ├── Sprites/               # 2D graphics
│   │   └── Audio/                 # Sound files
│   │
│   └── Plugins/                   # Third-party assets
│
├── Packages/                      # Unity packages
├── ProjectSettings/               # Unity project settings
├── docs/                          # Documentation
│   ├── README.md                  # Detailed docs
│   ├── ARCHITECTURE.md            # Code structure
│   └── images/                    # Screenshots
│
├── .gitignore                     # Git ignore rules
├── README.md                      # This file
├── LICENSE                        # MIT License
├── CONTRIBUTING.md                # Contribution guide
└── CONTRIBUTORS.md                # Credits
```

---

## 🛠️ Development

### For Students & Learners

Want to understand how it works or add your own levels?

1. **Explore the Code**
   ```csharp
   // Start with simple scripts
   Assets/Scripts/Graph/Node.cs      // See how nodes work
   Assets/Scripts/Algorithms/DFS.cs  // Learn DFS implementation
   ```

2. **Create a Custom Level**
   ```json
   // Copy this to Assets/Resources/LevelData/Custom/my_level.json
   {
     "levelId": 100,
     "gameMode": "DFS",
     "title": "My First Level",
     "description": "Solve this graph!",
     "nodes": [
       { "id": "A", "position": { "x": 0, "y": 2, "z": 0 } },
       { "id": "B", "position": { "x": -2, "y": 0, "z": 0 } }
     ],
     "edges": [
       { "from": "A", "to": "B" }
     ],
     "solution": ["A", "B"],
     "timeLimit": 30,
     "hints": ["Start at node A"]
   }
   ```

3. **Test Your Level**
   - Open Unity
   - Play mode
   - Load your custom level
   - Share with others!

### For Contributors

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

```bash
# Setup development environment
git clone https://github.com/yourusername/graph-quest.git
cd graph-quest
git checkout -b feature/amazing-feature

# Make your changes
# Test thoroughly
# Commit with clear message
git commit -m "Add amazing feature: [description]"

# Push and create PR
git push origin feature/amazing-feature
```

### Code Style

```csharp
// Follow these conventions
public class MyClass          // PascalCase for classes
{
    public int PublicField;   // PascalCase for public
    private int privateField; // camelCase for private
    
    public void DoSomething() // PascalCase for methods
    {
        int localVar = 0;     // camelCase for locals
    }
}
```

---

## 🎯 Roadmap

### Version 1.0 (Current) ✅
- [x] 5 game modes
- [x] 50 levels
- [x] Progress saving
- [x] Achievement system
- [x] Cross-platform builds

### Version 1.1 (Next) 🚧
- [ ] Multiplayer races
- [ ] Level editor (in-game)
- [ ] Community level sharing
- [ ] Mobile support (iOS/Android)
- [ ] More algorithms (Greedy, Backtracking)

### Version 2.0 (Future) 💭
- [ ] Campaign mode with story
- [ ] Algorithm visualization replay
- [ ] Performance profiling tools
- [ ] Integration with online judge platforms
- [ ] AR/VR mode

### Community Requests 🗳️
Vote for features in [Discussions](https://github.com/yourusername/graph-quest/discussions)!

---

## 🏆 Achievements

Unlock achievements as you master algorithms:

| Achievement | Description | Requirement |
|-------------|-------------|-------------|
| 🌱 **First Steps** | Complete your first level | Finish Level 1 |
| 🌲 **Tree Hugger** | Master all DFS levels | 3-star all DFS levels |
| 🌊 **Wave Rider** | Master all BFS levels | 3-star all BFS levels |
| ⚡ **Speed Demon** | Beat par time on 10 levels | Sub-par on 10 levels |
| 🧠 **Big Brain** | Complete without hints | 10 levels without hints |
| 💎 **Perfectionist** | Get 3 stars on all levels | Perfect all 50 levels |
| 🎓 **Algorithm Master** | Complete all game modes | Finish all 5 modes |
| 🏅 **Speedrunner** | Beat game in under 2 hours | Complete all levels fast |

---

## 📊 Statistics

Track your progress:

```
📈 Your Stats
├── Levels Completed: 42/50
├── Total Stars: ⭐⭐⭐ 98/150
├── Time Played: 12h 34m
├── Algorithms Mastered: 7/9
├── Best Streak: 15 levels
└── Global Rank: #247
```

---

## 🤝 Contributing

We love contributions! Whether you're fixing bugs, adding levels, or improving docs.

### Ways to Contribute

| Type | Description | Difficulty |
|------|-------------|------------|
| 🐛 **Bug Reports** | Found something broken? | Easy |
| 📝 **Documentation** | Improve explanations | Easy |
| 🎨 **Level Design** | Create new puzzles | Medium |
| 💻 **Code** | Add features or fixes | Medium-Hard |
| 🌍 **Translation** | Localize the game | Medium |
| 🎬 **Content** | Create tutorials/videos | Medium |

### Quick Contribution

```bash
# Report a bug
https://github.com/yourusername/graph-quest/issues/new?template=bug_report.md

# Suggest a feature
https://github.com/yourusername/graph-quest/discussions/new

# Submit a level
# 1. Create JSON in LevelData/Community/
# 2. Test in Unity
# 3. Submit PR
```

### Recognition

Contributors get:
- 🏆 Name in CONTRIBUTORS.md
- 🎮 Special in-game badge
- 💌 Shoutout in release notes

---

## 📜 License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) for details.

```
Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

**TL;DR**: You can freely use, modify, and distribute this game. Just give credit! 🙏

---

## 🙏 Acknowledgments

### Course Material
- **Dr. Russell Campbell** - COMP 359 Instructor, UFV
- **Anany Levitin** - Textbook author

### Inspiration & Tools
- [VisuAlgo](https://visualgo.net/) - Algorithm visualization
- [Unity](https://unity.com/) - Game engine
- [LeetCode](https://leetcode.com/) - Problem inspiration

### Special Thanks
- All beta testers and students
- Open source contributors
- The amazing Unity community

### Assets Used
- [DOTween](http://dotween.demigiant.com/) - Animation
- [TextMesh Pro](https://unity.com/features/textmeshpro) - Text rendering
- Icons from [Lucide](https://lucide.dev/)

---

## 📧 Contact & Support

### Get Help
- 📖 [Documentation](docs/README.md)
- 💬 [Discord Community](https://discord.gg/your-server)
- 📧 Email: your.email@example.com

### Found a Bug?
1. Check [existing issues](https://github.com/yourusername/graph-quest/issues)
2. Create [new issue](https://github.com/yourusername/graph-quest/issues/new)
3. Include:
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots/videos
   - Unity version & platform

### Feature Request?
Start a [discussion](https://github.com/yourusername/graph-quest/discussions)!

---

## 📱 Social Media

Stay updated on development:

- 🐦 [Twitter](https://twitter.com/yourusername)
- 📺 [YouTube](https://youtube.com/yourchannel) - Devlogs & tutorials
- 💼 [LinkedIn](https://linkedin.com/in/yourprofile)
- 🎮 [Itch.io](https://yourusername.itch.io/graph-quest)

---

## 🌟 Show Your Support

If Graph Quest helped you learn algorithms, please:

⭐ **Star this repo** - It helps others find it!  
🐦 **Share on social media** - Spread the word!  
💖 **Sponsor the project** - Support development!  

[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-❤-red.svg)](https://github.com/sponsors/yourusername)

---

## 📈 Stats

![GitHub Stars](https://img.shields.io/github/stars/yourusername/graph-quest?style=for-the-badge)
![GitHub Forks](https://img.shields.io/github/forks/yourusername/graph-quest?style=for-the-badge)
![GitHub Issues](https://img.shields.io/github/issues/yourusername/graph-quest?style=for-the-badge)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/yourusername/graph-quest?style=for-the-badge)

---

<div align="center">

**Made with ❤️ and lots of ☕ for algorithm learners everywhere**

[🎮 Start Playing](https://yourusername.github.io/graph-quest) | [📚 Read the Docs](docs/README.md) | [🤝 Contribute](CONTRIBUTING.md)

---

*"The best way to learn algorithms is to play with them." - Graph Quest Team*

</div>
