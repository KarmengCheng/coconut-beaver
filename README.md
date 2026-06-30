# Coconut Beaver 🦫

A real-time flood telemetry dashboard for Taman Sri Muda, Klang River Basin (Station 301543).

## Features
- **Real-time Telemetry Dashboard**: Visualizes flood and river levels.
- **Interactive Recharts Graph**: View level history and reference thresholds.
- **Tailwind CSS Styling**: Clean, responsive dashboard design.

## How to Run

Since the application is built as a single-page static HTML file leveraging React and Tailwind CSS through CDNs, you can run it in a few simple ways:

### Option 1: Using a Local HTTP Server (Recommended)
Running through an HTTP server ensures all features load correctly without browser security policy restrictions.

**Using Python:**
If you have Python installed, run the following command in the project directory:
```bash
python3 -m http.server 8000
```
Then, open [http://localhost:8000](http://localhost:8000) in your web browser.

**Using Node.js:**
If you have Node.js installed, run:
```bash
npx serve
```
Then, open the local URL provided by the terminal (typically [http://localhost:3000](http://localhost:3000)).

### Option 2: Directly in Browser
You can open the `index.html` file directly in your browser:
1. Double-click [index.html](index.html) in your file manager (Finder / Explorer).
2. Or drag and drop [index.html](index.html) into an open browser window.