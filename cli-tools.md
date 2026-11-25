# CLI Tools / أدوات سطر الأوامر

## English

### dumpcap — Capture Packets
```bash
# List available interfaces
dumpcap -D

# Capture on a specific interface
dumpcap -i eth0 -w capture.pcapng

# Capture with a maximum file size limit
dumpcap -i eth0 -w capture.pcapng -b filesize:10240

# Capture with a filter
dumpcap -i eth0 -f "port 80" -w http.pcapng
