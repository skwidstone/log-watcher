# log-watcher

LogWatcher is a simple and lightweight Bash script designed to monitor Linux log files in real-time and alert you when suspicious activity is detected.



🚀 Features

1. Monitors log files for suspicious patterns.

2. Default log file: /var/log/auth.log.

3. Default patterns:
   a) Failed password
   b) Invalid user
   c) authentication failure
   
4. Outputs a notification directly to the terminal.

5. Lightweight, no dependencies beyond Bash.




⚙️ Usage

chmod +x log-watcher.sh
./log-watcher.sh

You can edit the script to change:

1. The log file to monitor.

2. The suspicious keywords to search for.




💡 Example Output

[ALERT] Suspicious activity detected:
Apr 15 14:33:45 server sshd[1234]: Failed password for invalid user admin from 192.168.1.100 port 43210 ssh2



📌 Planned Features

1. Email or Telegram notifications.

2. Config file support.

3. Multi-logfile monitoring.

4. Log rotation handling.
