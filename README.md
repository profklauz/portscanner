# Port Scanner

A simple Python-based port scanner that checks for open ports on specified target IP addresses.

## Features

- Scan single or multiple target IP addresses
- Specify the number of ports to scan
- Simple command-line interface
- Color-coded output for better visibility

## Requirements

- Python 3.x
- `termcolor` package (for colored output)

## Installation

1. Clone the repository or download the `portscanner.py` file
2. Install the required package:
   ```
   pip install termcolor
   ```

## Usage

Run the script using Python:
```
python3 portscanner.py
```

### Input Options:
1. **Single Target**: Enter a single IP address (e.g., `192.168.1.1`)
2. **Multiple Targets**: Enter multiple IP addresses separated by commas (e.g., `192.168.1.1, 192.168.1.2`)
3. **Port Range**: Specify how many ports you want to scan (starting from port 1)

## Example

```
[*] Enter Targets To Scan(split them by ,): 192.168.1.1, 192.168.1.2
[*] Enter How Many Ports You Want To Scan: 100
[*] Scanning Multiple Targets

Starting Scan For 192.168.1.1
[+] Port Opened 80
[+] Port Opened 443

Starting Scan For 192.168.1.2
[+] Port Opened 22
[+] Port Opened 80
```

## Note

This is a basic port scanner for educational purposes only. Always ensure you have proper authorization before scanning any network or system.

