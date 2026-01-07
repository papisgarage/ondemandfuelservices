# Running On Demand Fuel Services Locally

Choose one of the following methods to run the website on your local machine:

## Method 1: Python (Easiest - Recommended)

### Option A: Using the Python script (auto-opens browser)
```bash
python start-server.py
```

### Option B: Using Python's built-in server
```bash
python -m http.server 8000
```
Then open: http://localhost:8000

### Option C: Using the batch file (Windows)
Double-click `start-server.bat` or run:
```bash
start-server.bat
```

## Method 2: Node.js

1. Install Node.js if you don't have it: https://nodejs.org/

2. Run the server:
```bash
node start-server.js
```

Or if you prefer using npm:
```bash
npm start
```

## Method 3: Using PHP (if installed)

```bash
php -S localhost:8000
```

## Method 4: Using Live Server (VS Code Extension)

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Access the Website

Once the server is running, open your browser and go to:
- **http://localhost:8000**

The Python script (`start-server.py`) will automatically open your browser.

## Stopping the Server

Press `Ctrl+C` in the terminal/command prompt to stop the server.

## Troubleshooting

- **Port 8000 already in use?** Change the PORT number in the script to 8001, 8080, or any other available port.
- **Python not found?** Make sure Python is installed and added to your PATH.
- **Node.js not found?** Install Node.js from https://nodejs.org/

