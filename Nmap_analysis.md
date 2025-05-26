# Network Scan Analysis

## Devices Discovered:
- **3 active hosts** found in 192.168.1.0/24 network
- **Total scan time:** 17.17 seconds

## Device Analysis:

### Device 1: 192.168.1.1 (Router/Gateway)
- **MAC:** F4:27:56:32:D9:2F (Dasan Network Solutions)
- **Device Type:** Network Router/Gateway
- **Open Ports:**
  - 53/tcp (DNS)
  - 80/tcp (HTTP - Web interface)
  - 443/tcp (HTTPS - Secure web interface)
- **Filtered Ports:** FTP, SSH, Telnet, NetBIOS, SNMP
- **Security Risk:** Medium - Web interfaces exposed

### Device 2: 192.168.1.2
- **MAC:** 82:EA:B6:58:95:44 (Unknown manufacturer)
- **Status:** All ports closed/filtered
- **Security Risk:** Low - Well secured

### Device 3: 192.168.1.5 (Windows Machine)
- **Open Ports:**
  - 135/tcp (MS-RPC)
  - 139/tcp (NetBIOS)
  - 445/tcp (SMB file sharing)
  - 2179/tcp (VM Remote Desktop)
  - 2869/tcp (UPnP)
  - 5357/tcp (WS-Discovery)
- **Security Risk:** HIGH - Multiple Windows services exposed
