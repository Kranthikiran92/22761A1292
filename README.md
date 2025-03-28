22761A1292
Average Calculator HTTP
This project is a Node.js-based Express API that fetches random numbers, categorizes them, maintains a sliding window, and calculates their average.

## Features
- Fetches 10 random numbers from an external API.
- Categorizes numbers as:
  - **p** (Prime)
  - **f** (Fibonacci)
  - **e** (Even)
  - **r** (Random/Other)
- Maintains a sliding window of the last 10 numbers.
- Computes and returns the average of the current window.
- Handles API failures with default fallback values.

## Prerequisites
- Node.js installed on your system.
- npm installed (comes with Node.js).

## Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/Kranthikiran92/22761A1292.git
   cd 22761A1292
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

## Usage
1. Start the server:
   ```sh
   node server.js
   ```
2. Access the API endpoint:
   ```sh
   http://localhost:9876/numbers
   ```

## API Response Example
```json
{
  "windowPrevState": [2, 4, 6, 8],
  "windowCurrState": [3, 5, 10, 15],
  "categorizedNumbers": [
    { "number": 3, "category": "p" },
    { "number": 5, "category": "p" },
    { "number": 10, "category": "e" },
    { "number": 15, "category": "r" }
  ],
  "Avg": "8.25"
}
```

## Screenshots
![image](https://github.com/user-attachments/assets/df1c1295-ba74-4c87-85c0-6fd6cf4a5ba7)
![image](https://github.com/user-attachments/assets/5f1bd717-2006-4cdb-93e5-f6fbc88edd42)
![image](https://github.com/user-attachments/assets/74f45bb0-8fbc-4d45-ac37-f2f3618de739)




