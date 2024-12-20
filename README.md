# IMDB Degrees of Separation AI

This project explores the concept of "Degrees of Separation" between actors using the IMDB dataset. The AI algorithm identifies the shortest connection path between two actors based on their shared movie appearances.

## Features

- **Shortest Path Algorithm**: Determines the minimum number of connections (degrees of separation) between two actors.
- **IMDB Dataset Analysis**: Processes and analyzes actor and movie data from IMDB.
- **Efficient Search**: Utilizes graph traversal algorithms for optimal performance.

## File Structure

```
.
├── .idea              # Project configuration files
├── large              # Large dataset for the IMDB actors and movies
├── small              # Small dataset for testing and debugging
├── degrees.py         # Main script for computing degrees of separation
├── util.py            # Utility functions for data processing and graph traversal
```

## How It Works

1. **Dataset**:
   - The `large` folder contains a comprehensive dataset of actors and movies.
   - The `small` folder is a simplified dataset for quick testing.

2. **Algorithm**:
   - Constructs a graph where actors are nodes and movies represent edges.
   - Implements a graph traversal algorithm (e.g., Breadth-First Search) to find the shortest path between two actors.

## Prerequisites

- Python 3.x

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Vishvendra07/IMDB_Degrees_of_Seperation_AI.git
   cd IMDB_Degrees_of_Seperation_AI
   ```

2. **Run the Script**:
   Execute the `degrees.py` file to start the program:
   ```bash
   python degrees.py
   ```

## Usage

- The program will prompt you to enter the names of two actors.
- It will compute and display the shortest path connecting the two actors.
- If no connection exists, the program will indicate this.

## Future Enhancements

- Expand functionality to handle larger datasets more efficiently.
- Add a graphical interface for interactive visualization of actor connections.
- Integrate additional data sources for richer insights.

## Contributions

Contributions are welcome! Feel free to open an issue or submit a pull request to improve the project.

---

Explore the fascinating connections in the world of cinema with the IMDB Degrees of Separation AI!
