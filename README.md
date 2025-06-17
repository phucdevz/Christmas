# 🎄 Christmas Terminal Animation (C++)

A festive terminal-based animation written in C++ to celebrate the Christmas spirit. This project creates a colorful and lively ASCII art-based animation in your terminal featuring falling snowflakes, dynamic text effects, and a warm holiday greeting.

## ✨ Features

- ❄️ Falling snowflake animation in terminal
- 🎨 Colored ASCII art using ANSI escape codes
- 🎅 Display of a Christmas message: "Merry Christmas and Happy New Year"
- 🧵 Multi-threaded animation for smooth rendering
- ⏱️ Customizable delay and display duration

## 🛠️ Built With

- **C++**
- **ANSI Escape Codes** for colored output
- **`<thread>`** and **`<chrono>`** for timing control

## 🚀 Getting Started

### Prerequisites

- A C++17 compatible compiler (e.g., `g++`, `clang++`)
- A terminal that supports ANSI escape sequences

### Build & Run

```bash
# Clone the repository
git clone https://github.com/phucdevz/Christmas.git
cd Christmas

# Compile the source code
g++ -std=c++17 -pthread -o christmas main.cpp

# Run the program
./christmas
