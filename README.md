# Nonogram Game written in JavaScript

A fully-featured **Nonogram** (also known as Picross or Paint by Numbers) puzzle game implemented as a single HTML file with JavaScript. This browser-based game offers a complete puzzle-solving experience with modern UI features and multilingual support.

[<kbd> <br> ➡️ Play it right now in your browser <br> </kbd>](https://htmlpreview.github.io/?https://github.com/anga83/NonogramJS/blob/main/NonogramJS.html)

## 🎯 Game Overview

Nonogram is a logic puzzle where you fill in cells on a grid to reveal a hidden picture. The numbers on the sides of the grid tell you how many consecutive cells should be filled in each row and column.

## ✨ Features

### 🎮 Core Gameplay
- **Multiple Grid Sizes**: 5x5, 10x10, 15x15, and various rectangular formats (5x10, 10x15, etc.)
- **Random Puzzle Generation**: Automatically generates new puzzles with varying difficulty
- **Predefined Image Puzzles**: Hand-crafted puzzles that reveal recognizable shapes (tree, heart)
- **Three Tool Types**:
  - **Pen Tool**: Fill cells with selected color
  - **Cross Tool**: Mark cells as definitely empty
  - **Note Tool**: Place small markers for uncertain cells

### 🎨 Visual & Interactive Features
- **Color Palette**: 8 different colors for filling cells
- **Smart Auto-Cross**: Automatically crosses out impossible cells when rows/columns are completed
- **Visual Feedback**: Completed rows and columns are highlighted
- **Grid Highlighting**: 5x5 block pattern for better readability
- **Responsive Design**: Adapts to different screen sizes

### 🏆 Scoring System
- **Base Points**: Earned for correctly filled cells
- **Combo System**: Consecutive correct fills increase point multiplier
- **Time Bonus**: Faster completion yields bonus points
- **Efficiency Bonus**: Awarded for clean solving
- **Error-Free Bonus**: Extra points for perfect completion

### 🌐 Multilingual Support
- **German** and **English** interface
- **Automatic Language Detection**: Uses browser language preference
- **URL Parameter Override**: `?lang=de` or `?lang=en`
- **Cookie Persistence**: Remembers language preference
- **Live Language Switching**: Change language without losing game progress

### 💾 Data Persistence
- **High Score Tracking**: Top 5 scores saved locally via cookies
- **Separate Categories**: Different leaderboards for random vs. predefined puzzles
- **Grid Size Specific**: High scores tracked per puzzle size
- **Persistent Settings**: Language and preferences saved between sessions

### ⌨️ Keyboard Controls
- **1-8**: Quick grid size selection
- **T**: Toggle between Pen and Cross tools
- **H/O**: Toggle Note tool
- **A**: Toggle Auto-Cross feature
- **C**: Check grid for errors and auto-correct
- **R**: Reset current puzzle
- **N**: Generate new random puzzle
- **E**: Load next predefined image puzzle

### 🖱️ Mouse Controls
- **Left Click/Drag**: Fill cells with current tool
- **Right Click**: Use alternative tool (Cross when Pen is selected, Pen when Cross is selected)
- **Hover**: Preview tool effect before clicking

## 🎯 How to Play

1. **Understand the Numbers**: Each number represents a group of consecutive filled cells
2. **Use Logic**: If a row shows "3 1", there are groups of 3 and 1 filled cells with at least one empty cell between them
3. **Start with Obvious Rows/Columns**: Look for large numbers or rows that are nearly complete
4. **Use the Cross Tool**: Mark cells you know are empty to avoid mistakes
5. **Auto-Cross Feature**: Enable to automatically mark impossible cells when sections are complete

## 🏁 Win Conditions

Complete the puzzle by correctly filling all required cells according to the number clues. The game automatically detects completion and shows your score breakdown.

## 📱 Technical Details

- **Single File**: Complete game in one HTML file
- **No Dependencies**: Pure JavaScript, HTML, and CSS
- **Local Storage**: Uses cookies for data persistence
- **Modern Browser Support**: Works in all current browsers
- **Version**: 2.1

## 🎨 Customization

The game features a flexible color system allowing players to use different colors for artistic expression, though the core puzzle logic remains the same regardless of color choice.

---

*Perfect for puzzle enthusiasts who enjoy logic-based challenges and want a polished, feature-rich Nonogram experience directly in their browser!*
