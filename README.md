# Python Manager 🐍

![Python Manager](https://img.shields.io/badge/Python_Manager-v1.0-blue.svg)
![Flask](https://img.shields.io/badge/Flask-v2.0-orange.svg)
![Monitoring](https://img.shields.io/badge/Monitoring-Enabled-green.svg)

Welcome to the **Python Manager** repository! This project offers a web-based interface for managing Python scripts with real-time monitoring, logging, and control. Whether you're running a simple script or managing multiple processes, Python Manager provides a seamless experience.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Real-time Monitoring**: Keep track of your scripts and processes as they run.
- **Logging**: Access detailed logs for each script execution to troubleshoot issues.
- **Control**: Start, stop, and manage your Python scripts directly from the web interface.
- **Dashboard**: A user-friendly dashboard displays all running scripts and their statuses.
- **WebSocket Support**: Enables real-time updates without needing to refresh the page.

## Technologies Used

This project uses several key technologies:

- **Flask**: A lightweight web framework for Python.
- **WebSockets**: For real-time communication between the client and server.
- **JavaScript**: Enhances the user interface and interactivity.
- **HTML/CSS**: For building the front-end layout and design.
- **SQLite**: A lightweight database for logging and monitoring data.

## Installation

To get started with Python Manager, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/valeitn1/python-manager.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd python-manager
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   python app.py
   ```

5. **Access the dashboard**: Open your web browser and go to `http://localhost:5000`.

To download the latest version of the application, visit the [Releases](https://github.com/valeitn1/python-manager/releases) section. Download the appropriate file, execute it, and follow the installation steps above.

## Usage

Once you have installed Python Manager, you can start using it to manage your Python scripts. Here’s how:

1. **Access the Dashboard**: Open your web browser and navigate to `http://localhost:5000`.
2. **Add a New Script**: Use the "Add Script" button to upload a Python script.
3. **Monitor Running Scripts**: The dashboard displays all running scripts, their status, and logs.
4. **Control Scripts**: Start or stop scripts directly from the dashboard.

### Example Script

Here’s a simple example of a Python script you can manage with Python Manager:

```python
import time

while True:
    print("Running...")
    time.sleep(5)
```

Add this script to Python Manager and observe its output in real-time.

## Contributing

We welcome contributions to Python Manager! If you want to contribute, please follow these steps:

1. **Fork the repository**.
2. **Create a new branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make your changes** and commit them:
   ```bash
   git commit -m "Add your message here"
   ```
4. **Push to your branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Create a Pull Request**.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [valeitn1](https://github.com/valeitn1)

To download the latest version of the application, visit the [Releases](https://github.com/valeitn1/python-manager/releases) section. Download the appropriate file, execute it, and follow the installation steps above.

---

Thank you for checking out Python Manager! We hope you find it useful for managing your Python scripts. Happy coding!