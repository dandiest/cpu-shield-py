# CPU-Shield 🛡️

**CPU-Shield** is a powerful, lightweight Python utility designed to monitor system resources, alert the user about CPU spikes, and provide an automated defense mechanism against runaway processes.

## 🚀 Key Features
- **Real-time Monitoring**: Analyzes CPU usage at randomized intervals to detect anomalies.
- **Active Defense**: Automatically terminates non-whitelisted processes that exceed 90% CPU usage.
- **Detailed Logging**: Records all alerts, including timestamps and the top 3 offending processes (PID, Name, CPU%).
- **Cross-Platform Notifications**: Native desktop alerts for **Windows, macOS, and Linux**.
- **Safety Whitelist**: Built-in protection for critical system processes.

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/leumascripts/cpu-shield-py.git](https://github.com/leumascripts/cpu-shield-py.git)
   cd cpu-shield-py
