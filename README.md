# Password Manager

This project is a simple password manager that allows you to create, store, and manage passwords securely.

## Setup Instructions

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone <repository-url>
cd <repository-directory>
```

### 2. Create a Virtual Environment

Create a virtual environment to manage your project's dependencies:

- On macOS/Linux:

  ```bash
  python3 -m venv venv
  ```
- On Windows:

  ```bash
  python -m venv venv
  ```

### 3. Activate the Virtual Environment

Activate the virtual environment:

- On macOS/Linux:

  ```bash
  source venv/bin/activate
  ```
- On Windows:

  ```bash
  .\\venv\\Scripts\\activate
  ```

### 4. Install the Requirements

Install the required packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 5. Start the Application

Run the application:

```bash
python file_handler.py
```

## Usage

The application allows you to create and manage passwords for different domains. You can choose to generate passwords randomly or manually, and all passwords are securely hashed before storage.

## Contributing

If you wish to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
