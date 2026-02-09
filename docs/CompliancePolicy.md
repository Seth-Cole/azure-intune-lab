# Compliance Policy

## Task-Overview
Created a Windows device compliance policy for all members of TestDevices group, which include minimum device configurations allowed for devices to access company network.

## Purpose
Establishes baseline security posture for all Windows devices accessing network resources, reducing attack surface through automated compliance assesment. If devices are out of compliance an automated message is sent to user which includes compliance issues montiored and inform them of expected remediation time prior to next action.

## Monitored Security Controls
- Password requirements: Enforces strong authentication hygiene
- Minimum OS version (10.0.19041): Prevents use of EOL versions with unpatched vulnerabilities
- Microsoft Defender: Ensures real-time malware protection is active
- BitLocker encryption: Protects data if device is lost or stolen
- Secure Boot: Validates OS integrity, prevents boot-level tampering

## Outcome
![Compliance Policy Creation](./images/CompliancePolicyCreation1.png)
![](./images/CompliancePolicyCreation2.png)
![](./images/CompliancePolicyCreation3.png)