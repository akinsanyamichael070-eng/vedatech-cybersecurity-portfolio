# Week 13: Introduction to Cloud Security
## What I Learned
- What cloud computing is and why organisations are moving to the cloud
- What the Shared Responsibility Model and why it is the foundation of cloud security
- Describing the three cloud service models (IaaS, PaaS, SaaS) and their security boundaries
## Key Takeaways
- Cloud computing means using someone else's computers over the internet and it is a rented infrastructure.
- The Shared Responsibility Model is the foundation of cloud security. The provider secures the cloud. You secure what you put in it.
- Misconfiguration is the #1 cloud security risk. Not hackers with advanced tools. Just people leaving settings wrong.
## AWS vs Azure
- Both AWS and Azure operate under the Shared Responsibility Model and offer direct equivalents for every core cloud function
- They organize and scope permissions differently:AWS uses IAM as a global service inside a single AWS Account using JSON-based policies, whereas Azure separates user identities (Microsoft Entra ID) from resource permissions (Azure RBAC), which are assigned hierarchically across Subscriptions and Resource Groups
## Screenshots
- aws-iam-dashboard.png
- ec2-dashboard.png
- security-groups.png
- cloudtrail.png
## Reflection
- Completing this assignment strengthened my understanding of cloud computing fundamentals and real-world cloud security. My biggest takeaway was seeing how the Shared Responsibility Model divides duties across IaaS, PaaS, and SaaS. While providers like AWS and Azure secure the physical infrastructure, customers remain responsible for protecting their data, configurations, and user identities. Working through the NexaShield scenarios showed why Identity and Access Management (IAM), Multi-Factor Authentication (MFA), least privilege, and logging tools like CloudTrail are vital for preventing breaches. Comparing AWS and Azure also helped me connect cloud theory with practical security steps.
