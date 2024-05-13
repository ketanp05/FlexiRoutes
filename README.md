# FlexiRoutes

FlexiRoutes is a dynamic, file-based routing system that leverages Python and Flask to provide a flexible and easily configurable routing mechanism. This project is designed to allow developers to define their application's routes through a simple JSON configuration file, promoting cleaner and more manageable code.

## Features

- **Dynamic Routing**: Routes are configured through a JSON file, allowing changes without altering the source code.
- **Easy Configuration**: Simplify your Flask app management by centralizing route definitions.
- **Extensible**: Supports basic routing out of the box with potential extensions for HTTP methods, middleware, and more.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Flask

### Installation

Clone the repository:

```bash
git clone https://github.com/ketanp05/FlexiRoutes.git
cd FlexiRoutes
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### Setting Up Your Routes

1. Open or create `routes.json` in the project root.
2. Define your routes in the following format:

```json
{
  "/": "home.index",
  "/about": "content.about"
}
```

### Running the Application

Execute the following command to start the Flask server:

```bash
python app.py
```

The server will start, and routes will be available based on the configuration in `routes.json`.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
```
