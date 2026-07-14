What is My IP
=============
Use this skill as a quick way to get the public IP address of the machine that is running this agent. Useful for 
debugging network issues.

## Usage
Depending on whether this machine is a Windows or Linux platform:

```bash
sh scripts/get-my-ip.sh
```

or 

```bat
.\scripts\get-my-ip.bat
```

## Output
Returns the public IPv4 address (and IPv6 if available) by querying `ifconfig.me`.

Example output:

```
203.0.113.24
```

## When to Use
When user asks "what's my IP?" or "show my public IP".

## Requirements
 - curl (pre-installed on most systems, including Widows)
 - internet access
