# Configuration Settings Baseline

## Task-Overview
Baseline configuration standards created with a settings catalog. Applied to TestDevices group to automate configurations for each device in group.

## Purpose
Ensures that features such as disk encryption or other, are configured automatically for each device joined to assigned groups. This enforces compliance with policies set through settings catalog.

## Monitored Settings
- Required Device Encryption – Ensures BitLocker is enabled and deployed for attached disks to implement full disk encryption for each device, this includes OS, removable, and fixed data drives. This hardens the security posture by protecting data stored on disk in case of loss of equipment, or stolen disks.
- Password Settings – ensures password complexity and hygiene, reduces vulnerability caused by simple, short, or reused passwords by enforcing max password age, length, complexity, and history.
- Account Lock out – set maximum logon attempts to 3, this reduces the attack surface by disabling the chance of brute force attempts or rainbow table attacks
- Windows Update – configured settings for automatically updating windows systems weekly, giving the user a 30 minute warning before automatically downloading, installing, and restarting the device. The user is allowed to snooze the updates for up to 7 days at which point the system will force the updates to install and system to restart


## Outcome
![Configuration Policy Creation](./images/ConfigurationComplianceCreation1.png)
![](./images/ConfigurationComplianceCreation2.png)
![](./images/ConfigurationComplianceCreation3.png)
![](./images/ConfigurationComplianceCreation4.png)
![](./images/ConfigurationComplianceCreation5.png)