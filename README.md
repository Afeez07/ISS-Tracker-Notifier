# ISS-Tracker-Notifier

This script uses real-time Open Notify and Sunrise Sunset API data to track the ISS. The script sends you an email notification when the ISS is within a 5-degree radius of your location and it's nighttime.

## Getting Started

### Prerequisites

* Python 3.12
* `requests` library (install with `pip install requests`)
* An email account with less secure apps enabled.

### Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/Afeez07/ISS-Tracker-Notifier]
    ```

2.  Navigate to the project directory:

    ```bash
    cd ISSTrackerNotifier
    ```

3. Install the required dependencies:
  
    ```pip
    install requests
    ```

4.  Update the following variables in the Python script:

    * `MY_EMAIL`: Your email address.
    * `MY_PASSWORD`: Your email password.
    * `__YOUR_SMTP_ADDRESS_HERE___`: Your email provider's SMTP server address (e.g., `smtp.gmail.com`).
    * `MY_LAT`: Your latitude.
    * `MY_LONG`: Your longitude.

5.  Run the program:

    ```bash
    python main.py
    ```

### Important Notes:

* You might need to enable "less secure app access" or generate an "app password" in your email account settings for the script to work.
* The script runs continuously, so you might want to run it in the background or as a scheduled task.

### Contributing

Feel free to contribute to ISSTrackerNotifier by:

* Adding a GUI.
* Implementing a more precise ISS tracking algorithm.
* Adding support for other notification methods (e.g., SMS).
* Adding a feature that sends a map of the ISS location.

