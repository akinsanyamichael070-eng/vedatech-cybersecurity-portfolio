## Summary of the Shared Responsibility Model
- The Shared Responsibility Model splits cloud security between the provider and the customer. Security OF the cloud is the provider’s job, covering physical data centers, hardware, and core infrastructure. Security IN the cloud is the customer’s job, covering data encryption, user access controls, and proper configuration settings.
## 3 cloud security risks with one-sentence explanations
- Misconfiguration: Leaving cloud settings improperly configured, such as making storage buckets public, which accidentally exposes sensitive data.
- Account Hijacking: Attackers stealing user credentials through phishing to take over and control cloud accounts.
- Lack of Visibility and Logging: Failing to enable monitoring tools like CloudTrail, leaving teams blind to unauthorized activity.
## One real-world breach example and the lesson learned
- In the 2019 Capital One breach, an attacker exploited a misconfigured firewall and overly permissive IAM role to steal over 100 million customer records from AWS S3. Capital One should have enforced least-privilege IAM permissions and properly hardened its Web Application Firewall settings.
