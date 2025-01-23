# PeopleOps
PeopleOps is a modern, comprehensive employee management system designed to streamline and enhance the way organizations manage their workforce. With an intuitive interface and robust features, PeopleOps empowers HR teams and managers to handle key aspects of employee lifecycle management effortlessly.

## Prerequisites

### System Requirements
- Python 3.8+
- pip
- pipenv

### Required Software
- Git
- Code Editor (VS Code, PyCharm, etc.)

### Installation Steps for Prerequisites

#### Windows
1. Download Python from [python.org](https://www.python.org/downloads/)
2. Install Python, ensuring "Add Python to PATH" is checked
3. Install pipenv:
   ```bash
   pip install pipenv
   ```

#### macOS
1. Install Homebrew:
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```
2. Install Python:
   ```bash
   brew install python
   ```
3. Install pipenv:
   ```bash
   pip3 install pipenv
   ```

#### Linux (Ubuntu/Debian)
1. Update package list:
   ```bash
   sudo apt update
   ```
2. Install Python and pip:
   ```bash
   sudo apt install python3 python3-pip
   ```
3. Install pipenv:
   ```bash
   pip3 install pipenv
   ```

## Project Setup

1. **Clone Repository**
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```

2. **Install Project Dependencies**
   ```bash
   pipenv install
   ```

3. **Activate Virtual Environment**
   ```bash
   pipenv shell
   ```

4. **Configure Environment**
   - Copy `.env.example` to `.env`
   - Update configuration values

5. **Run Database Migrations**
   ```bash
   python manage.py migrate
   ```

6. **Create Superuser**
   ```bash
   python manage.py createsuperuser
   ```

7. **Run Development Server**
   ```bash
   python manage.py runserver
   ```

## Troubleshooting
- Ensure all prerequisites are installed
- Check Python version compatibility
- Verify virtual environment activation

## Additional Resources
- Django Documentation: [docs.djangoproject.com](https://docs.djangoproject.com/)
- Pipenv Documentation: [pipenv.pypa.io](https://pipenv.pypa.io/)