# Submission Reminder App

## Description
The Submission Reminder App sets up a directory structure for managing student submission status. It includes scripts and configuration files needed to simulate a real-world application environment.

## Prerequisites
- A Unix-like operating system (e.g., Linux, macOS)
- Bash shell

## Files Provided
- `submissions.txt`: Contains sample records of students' submission status.
- `config.env`: Configuration file for the application.
- `reminder.sh`: Script that sends submission reminders.
- `functions.sh`: Script containing helper functions.
- You will also create a `startup.sh` script.

## Directory Structure
When the environment is set up, the directory structure will look like this:

## Setup Instructions
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/submission_reminder_app_githubusername.git
    ```
2. **Navigate to the repository directory**:
    ```sh
    cd submission_reminder_app_githubusername
    ```
3. **Run the environment setup script**:
    ```sh
    ./create_environment.sh
    ```
4. **Enter your name** when prompted. The script will create a directory named `submission_reminder_{yourName}` with the necessary subdirectories and files.

## Scripts Description
- **create_environment.sh**: Creates the directory structure and populates the files.
- **config.env**: Contains environment variables for the app.
- **reminder.sh**: Script that sends reminders to students.
- **functions.sh**: Contains helper functions used by the other scripts.
- **startup.sh**: Script to start the reminder application. (You will create this script.)

## Running the Application
1. **Navigate to the `scripts` directory** inside the created `submission_reminder_{yourName}` directory:
    ```sh
    cd submission_reminder_{yourName}/scripts
    ```
2. **Run the `startup.sh` script to start the app**:
    ```sh
    ./startup.sh
    ```

Enjoy using the Submission Reminder App!

