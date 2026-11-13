
## 1. ps aux

**Purpose:**  
The `ps aux` command displays all running processes in Linux, including their Process ID (PID), CPU usage and memory usage.

**Example:**
```bash
ps aux
```

## 2. top

**Purpose:**  
The `top` command displays real-time information about running processes, CPU usage and memory consumption.

**Example:**
```bash
top
```

## 3. free -h

**Purpose:**  
The `free -h` command displays total, used and available RAM and swap memory in a human-readable format.

**Example:**
```bash
free -h
```

## 4. df -h

**Purpose:**  
The `df -h` command displays used and available disk space for mounted file systems in a human-readable format.

**Example:**
```bash
df -h
```

## 5. pgrep

**Purpose:**  
The `pgrep` command searches for running processes by name and displays their Process IDs (PID).

**Example:**
```bash
pgrep -a java
```

## 6. systemctl

**Purpose:**  
The `systemctl` command is used to check and manage Linux services, such as starting, stopping and restarting services.

**Example:**
```bash
systemctl status cron
```

## 7. journalctl

**Purpose:**  
The `journalctl` command displays system and service logs to investigate errors and troubleshoot problems.

**Example:**
```bash
journalctl -u cron -n 20
```
