# BitLocker Network Unlock Packet Captures

  Sample packet captures for Windows BitLocker Network Unlock using WDS.

  Lab:
  - Windows 11 client
  - Windows Server WDS / BitLocker Network Unlock
  - DHCP/BOOTP based pre-boot unlock flow

  Interesting fields:
  - DHCP vendor class: BITLOCKER
  - DHCP option 43: Vendor-Specific Information
  - DHCP option 125: Microsoft enterprise-specific information
  - WDS response packet

  These captures were generated in a private lab using non-production hosts and addresses.
