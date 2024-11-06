# FastAPI Starter

FastAPI Starter provides a streamlined foundation for quickly launching FastAPI projects. With a modular project structure, essential configurations, and common utilities, this template accelerates project initialization, allowing you to focus on core functionality.

## Project Structure

```plaintext
fastapi-starter/
├── app/
│   ├── main.py          # Entry point of the FastAPI application
│   ├── routers/         # API route definitions
│   ├── models/          # Database models
│   ├── utils/           # Common utilities and helper functions
│   └── core/            # Core configurations and settings
├── tests/               # Test cases
├── requirements.txt     # List of dependencies
├── README.md            # Project documentation
├── .env.example         # Environment variable template
└── LICENSE              # License information
```

## Features

- **Modular Architecture**: Organized folder structure for easy scalability and maintainability.
- **CRUD-Ready Setup**: Pre-configured for basic CRUD operations to accelerate API development.

*(More features will be added over time)*

## Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sanikamal/fastapi-starter.git
   cd fastapi-starter
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Set Up Environment Variables**:
   - Copy `.env.example` to `.env` and configure as needed.

4. **Run the Application**:
   ```bash
   uvicorn app.main:app --reload
   ```

5. **Access the API**:
   - Open [http://127.0.0.1:8000](http://127.0.0.1:8000) to view the interactive API documentation.

## Contribution Guidelines

We welcome contributions to enhance this starter template. Please submit pull requests or open issues for any feature suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.