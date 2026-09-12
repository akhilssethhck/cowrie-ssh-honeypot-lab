# Cowrie Honeypot Findings

## SSH Connection Analysis

A controlled SSH connection was initiated from Kali Linux
against the Cowrie SSH honeypot in a virtualized laboratory
environment.

The connection demonstrated how Cowrie emulates an SSH service
and records interaction with the honeypot.

### Observed Activity

- SSH connection established
- SSH authentication interaction
- User session created
- Commands entered during the session
- Session termination recorded

The activity demonstrates the type of telemetry that can be
collected from an exposed SSH service.

## 2. Authentication Activity

Cowrie successfully captured the authentication attempt
and recorded the associated SSH session.

## 3. Command Activity

Commands executed during the SSH session were recorded
by Cowrie.

## 4. Log Analysis

The collected logs provide information about:

- Connection timestamps
- Source IP addresses
- Authentication attempts
- Usernames
- Commands executed
- Session activity
- Session termination

## 5. Detection Opportunities

The collected telemetry could be used to detect:

- Repeated authentication failures
- SSH brute-force activity
- Password attacks
- Suspicious commands
- Repeated connections
- Abnormal SSH sessions

## 6. Security Lessons

This experiment demonstrated how a honeypot can provide
valuable telemetry for security monitoring and incident
analysis.

## 7. Conclusion

The Cowrie honeypot successfully captured controlled SSH
activity from Kali Linux and generated logs that can be
used for security analysis.
