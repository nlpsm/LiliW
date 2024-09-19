LiLiW (Windows) # NLPSM - Natural Language Processing System Manager

## Overview
NLPSM is an innovative project designed to enable non-technical users to interact with their computer systems through natural language commands, leveraging OpenAI's GPT technology. This application provides a user-friendly API setup using FastAPI to execute system-level commands securely.

## Features
- **Command Execution**: Execute system commands via a secure API interface.
- **GPT Integration**: Utilizes GPT to understand and process natural language commands.
- **FastAPI Framework**: Built on FastAPI for robust, scalable, and fast web services.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Installation

1. **Clone the repository**:

   git clone https://github.com/nlpsm/lili.git
   
2. **Navigate to the project directory**:

   cd NLPSM-master

3. **Install required Python packages**:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Application
Execute the following command to run the FastAPI server:

   uvicorn app.nlpsm:app --reload

This will start the FastAPI server on `http://127.0.0.1:8000`. The server will automatically reload for code changes.

## Usage
You can interact with the system by sending HTTP requests to `http://127.0.0.1:8000`. Example commands include:
- **Fetch System Date**: `GET /date`
- **List Directory Contents**: `GET /list-dir?path=<path>`

## Contributing
Contributions are welcome! Please fork the repository and submit pull requests with your proposed changes.

## Security
For security concerns, please refer to the SECURITY.md file.

## License
This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.
