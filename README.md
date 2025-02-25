# Linux Log Monitoring and Analysis

## Who
This project is designed for anyone interested in monitoring system activity to detect unauthorized access and suspicious behavior. I have been using these scripts for my own purposes and they are quite useful.

## What
A log monitoring and analysis system that extracts and processes authentication, sudo, and command history logs from a Linux system. It consists of a Bash script to retrieve log entries and Python scripts to parse and analyze the data.

## When
This system can be used at any time to monitor and analyze system activity. I have been using it as part of routine security checks, but it can be used for monitoring in other situations as well.

## Where
This project is designed for Linux environments where security monitoring is necessary. It can be deployed on personal machines or servers.

## Why
Monitoring logs is important for maintaining system security and integrity. This project provides visibility into authentication attempts, administrative actions, and user activity. This helps to identify security threats before they escalate.

## How
To set up and run the project:

1. Clone the repository.
2. Ensure you have Python and Bash installed on your Linux system.
3. Install required Python dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install pandas scikit-learn matplotlib
   ```
4. Grant execution permissions to the Bash script:
   ```bash
   chmod +x monitor_logs.sh
   ```
5. Run the Bash script to extract logs:
   ```bash
   ./monitor_logs.sh
   ```
6. Run the Python scripts to analyze logs:
   ```bash
   python3 parse_logs.py
   python3 fraud_detection.py
   python3 email_alert.py
   ```

## Future
-Integrate SMS Alerts (Twilio API)
-Automate Execution of the scripts

