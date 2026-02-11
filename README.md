# SOC Project – SSH Brute Force Detection

Simulated and analyzed an SSH brute-force attack against a Windows host.

### Tools
- Kali Linux
- Windows 11
- OpenSSH
- PowerShell

### Skills Demonstrated
- Log analysis
- Detection of brute-force attacks
- Incident response thinking

## Attack Scenario

A simulated SSH brute-force attack was launched from Kali Linux 
against a Windows 11 machine running OpenSSH Server.

Multiple failed login attempts were generated to trigger security logs.

## Detection Steps

1. Enabled OpenSSH Server on Windows
2. Generated failed SSH login attempts from Kali
3. Collected Windows Security logs
4. Identified Event ID 4625 (Failed Logon)
5. Confirmed brute-force behavior

## Key Log Evidence

Event ID 4625 – An account failed to log on
Multiple failed attempts from same IP within short time window.
## Screenshots

### Failed Login Attempts
<img width="1915" height="1977" alt="failed_login" src="https://github.com/user-attachments/assets/7d8eafc0-a3b9-4497-8d73-58397c75fd65" />


### Windows Event Log
<img width="1910" height="617" alt="event_log" src="https://github.com/user-attachments/assets/3cef68e8-188e-4180-b44f-2a3e549fae4c" />
