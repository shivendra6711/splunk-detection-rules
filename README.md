# splunk-detection-rules


Collection of Splunk SPL detection queries focused on SOC monitoring, threat hunting, and incident investigation.

## Included Rules

- Brute Force Detection
- Suspicious PowerShell
- Encoded Command Detection
- Beaconing Activity
- Account Lockouts

## MITRE ATT&CK Mapping

| Rule | MITRE Technique |
|------|----------------|
| Brute Force | T1110 |
| PowerShell Abuse | T1059.001 |
| Obfuscated Commands | T1027 |
| Beaconing | T1071 |
| Impossible Travel Login | T1078 |
| Credential Dumping Detection | T1003 |
| DNS Tunneling Detection | T1071.004 |
| USB Device Detection | T1091 |

## Notes

- Detection rules are created for learning and portfolio purposes.
- No sensitive or production data included.
