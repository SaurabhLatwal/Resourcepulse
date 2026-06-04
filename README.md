# ResourcePulse – Intelligent System Performance Tracker

ResourcePulse is a Flask-based system monitoring and performance tracking application that provides real-time insights into CPU, memory, disk, network activity, and running processes. The application continuously collects system metrics, stores historical logs, and generates alerts when resource usage crosses predefined thresholds.

## Features

- Real-time CPU usage monitoring
- Memory utilization tracking
- Disk usage analysis
- Network activity monitoring
- Top running processes display
- Automatic resource logging in JSON format
- Alert generation for high resource usage
- Interactive dashboard with live updates
- Historical performance data storage

## Technologies Used

- Python
- Flask
- Psutil
- HTML
- CSS
- JavaScript
- JSON

## Project Structure

```text
ResourcePulse/
│
├── app.py
├── alerts.log
├── resource_log.json
├── static/
├── templates/
├── systemmonitor/
```

## How It Works

1. Collects real-time system statistics using Psutil.
2. Tracks CPU, Memory, Disk, and Network usage.
3. Records system metrics into a JSON log file.
4. Detects abnormal resource usage and creates alerts.
5. Displays live data through a Flask-powered dashboard.

## API Endpoints

| Endpoint | Description |
|-----------|-------------|
| / | Main Dashboard |
| /charts | Performance Charts |
| /data | Returns Live System Data (JSON) |

## Sample Metrics

The application records:

- CPU Usage (%)
- Memory Usage (%)
- Disk Usage (%)
- Network Bytes Sent
- Network Bytes Received
- Top Resource Consuming Processes

## Future Improvements

- Email Notifications
- Database Integration
- User Authentication
- Export Reports (PDF/CSV)
- Advanced Analytics Dashboard

## Author

Saurabh Latwal
