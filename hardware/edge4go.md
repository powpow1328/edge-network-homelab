# Edge4Go Firewall

## Why this device?
- x86 architecture
- 4x 1 Gbit/s NICs
- Low power consumption
- Full control over OS

## Alternatives considered
- ISP router (rejected: limited control)
- Consumer router (rejected: poor firewalling)

## OS Choice
OPNsense was chosen over OpenWrt because:
- Better x86 support
- Strong firewall tooling
- Easier maintenance

## Risks & Limitations
- Limited to 1 Gbit/s per interface
- No PoE support
