# Sorting Visualizer

**Sorting Visualizer** is a web-based application that demonstrates the step-by-step execution of popular sorting algorithms through dynamic visualizations. The application is designed with a clear **client-server architecture**, separating the backend logic from the frontend interface for scalability, maintainability, and clarity.



## Overview

This project allows users to visually understand how different sorting algorithms operate. It supports several algorithms including:

- Bubble Sort
- Merge Sort
- Heap Sort
- Quick Sort

Each algorithm is handled on the server side and the results are sent to the client for real-time visualization.

## Features

- Real-time visualization of sorting steps
- Clean and responsive user interface
- Modular backend with separate logic for each sorting algorithm
- RESTful API architecture for interaction between client and server
- Easy to extend with additional algorithms

## Technologies Used

### Frontend
- HTML
- CSS
- JavaScript (Canvas or DOM manipulation)

### Backend
- Node.js
- Express.js

### Architecture
- Client-server model
- Modular Node.js structure with reusable components

## Project Structure

```

sorting-visualizer/
│
├── client/                  # Frontend code
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── server/                  # Backend code
│   ├── algorithms/          # Sorting logic modules
│   │   ├── bubbleSort.js
│   │   ├── mergeSort.js
│   │   ├── heapSort.js
│   │   └── quickSort.js
│   ├── routes/
│   │   └── sort.js          # API routes
│   ├── app.js               # Express server setup
│   └── package.json
│
└── README.md

````

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sorting-visualizer.git
   cd sorting-visualizer
````

2. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

3. (Optional) If you use a bundler or frontend framework, set it up inside the `client` folder.



