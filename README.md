# Py Static Server

Py Static Server is a simple and fast Python CLI tool to spin up a local server to serve static files. It features an intuitive setup process, error handling, and a beautiful ASCII art banner. You can input the path manually or use a file explorer to select your desired directory. This server automatically detects `index.html` and serves your project files, including subfolders and resources.

## Features
- 🖼️ ASCII art banner to enhance the CLI experience.
- 📂 Option to manually input the path or choose via a file explorer.
- 🔍 Automatically detects and serves `index.html` and its dependencies.
- 🌐 Error handling for missing files or invalid paths.
- ⚡ Lightweight and quick to use — no dependencies other than Python's standard library!

## Installation
Clone the repository and navigate into the folder:
```bash
git clone https://github.com/yourusername/quick-python-static-server.git
cd quick-python-static-server
```

## Usage
Run the script using Python:
```bash
python server.py
```

### Steps:
1. **Choose a directory**: 
   - Enter the path manually.
   - Or, select a folder using the file explorer (default option for ease).
2. **Start the server**: 
   - The server will automatically find the `index.html` in the chosen directory and serve it on a local port (default: `8000`).
3. **Access your server**:
   - Open your browser and navigate to `http://localhost:8000`.

## Example Output
When you run the script, you'll see something like this:
```
*************************************************
  QUICK PYTHON STATIC SERVER
*************************************************
🎉 Server started at http://localhost:8000 🎉
Serving files from: /your/selected/path
Press CTRL+C to stop the server.
```

## Dependencies
- Python 3.6+ (no external libraries required).

## Notes
- Make sure your selected folder contains an `index.html` file.
- The script handles errors gracefully and will inform you if any required file is missing.

## Contributing
Feel free to fork this repository, make improvements, and open pull requests!

## License
MIT License
