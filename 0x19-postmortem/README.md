**Issue Summary:**
- Duration: The outage occurred from May 10th, 2024, at 10:00 PM to May 11th, 2024, at 2:00 AM (UTC).
- Impact: The outage affected the availability of our primary web application, leading to a complete service disruption for approximately 20% of our users. Users experienced slow response times and intermittent errors during this period.

**Timeline:**
- 10:00 PM (UTC): Issue detected through monitoring alerts indicating increased latency and error rates.
- 10:05 PM: Engineering team notified of the issue.
- 10:10 PM: Investigation initiated, focusing on backend services and database connectivity.
- 11:00 PM: Initial assumption made that the issue was related to database performance degradation.
- 12:00 AM: Misleading investigation path taken, focusing on optimizing database queries.
- 1:00 AM: Incident escalated to senior engineering team for further assistance.
- 2:00 AM: Root cause identified and resolution implemented.

**Root Cause and Resolution:**
- Root Cause: The outage was caused by a distributed denial-of-service (DDoS) attack targeting our network infrastructure. The attack overwhelmed our servers, leading to degraded performance and eventual service unavailability.
- Resolution: The DDoS attack was mitigated through the implementation of rate-limiting measures at the network perimeter. Additionally, cloud-based DDoS protection services were activated to provide ongoing defense against similar attacks.

**Corrective and Preventative Measures:**
- Improvement Opportunities:
  - Enhance network monitoring capabilities to detect and mitigate DDoS attacks more effectively.
  - Implement redundant network infrastructure to ensure high availability and fault tolerance.
- Tasks:
  - Patch network devices and servers to address potential vulnerabilities exploited in the attack.
  - Conduct a thorough review of incident response procedures and update documentation accordingly.
  - Schedule regular security audits and penetration testing to proactively identify and address security weaknesses.

**Conclusion:**
The recent outage was a challenging experience for our team, but it highlighted areas for improvement in our network security and incident response capabilities. By implementing the corrective measures outlined above and remaining vigilant against emerging threats, we aim to minimize the risk of future disruptions and ensure the continued reliability of our services.
![image](https://github.com/shreen-youssif/alx-system_engineering-devops/assets/138828741/2f0771a1-37e6-4b05-bd0c-7a7c8133b0d3)
