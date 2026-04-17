# Wireshark Network Traffic Analysis

## Objective
To capture live network packets using Wireshark and analyze different protocols and traffic types.

## Tools Used
- Wireshark (Free Network Protocol Analyzer)

## Steps Performed

1. Installed Wireshark on my system.
2. Selected the active network interface (Wi-Fi).
3. Started packet capture.
4. Generated traffic by:
   - Browsing websites (google.com)
   - Using ping command
5. Stopped capture after ~1 minute.
6. Applied filters to analyze protocols.
7. Exported the capture as a `.pcap` file.

## Protocols Identified

### 1. DNS (Domain Name System)
- Used to resolve domain names to IP addresses.
- Example: Query for `google.com`

### 2. TCP (Transmission Control Protocol)
- Reliable, connection-based communication.
- Observed handshake (SYN, SYN-ACK, ACK)

### 3. HTTP (HyperText Transfer Protocol)
- Used for web communication.
- Observed GET requests and responses.

## Key Observations

- DNS queries happen before accessing websites.
- TCP ensures reliable data transfer.
- HTTP carries actual webpage data.
- Multiple packets are exchanged for a single request.

## Conclusion

This task helped me understand:
- Packet-level communication
- Protocol behavior
- Real-time traffic monitoring

## Files Included

- `capture.pcap` → Packet capture file
- `report.txt` → Detailed analysis
- `screenshots/` → Proof of work

