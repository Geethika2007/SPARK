# RainShield – Income Protection for Delivery Workers

Problem

Delivery workers lose income during heavy rain because they cannot work.

Solution

We are building an insurance system that automatically pays workers when rain stops them from working.

Weekly Premium

Workers pay ₹49 per week for coverage.

Trigger Condition

If rainfall is very high for more than 3 hours, the system triggers payout.

Payout

Worker receives ₹500 for lost working hours.

---
# Adversarial Defense & Anti-Spoofing Strategy
1. Real vs Fake Worker Detection

Real workers show continuous movement and delivery activity. Fake users may show sudden GPS jumps and no delivery activity.

2. Data Used

* GPS location
* Movement pattern
* Order activity
* Login time
* Device ID

3. Handling Suspicious Cases

If a user is suspicious:

* Payout is paused
* Data is checked
* Genuine users are paid
* Fraud users are blocked
