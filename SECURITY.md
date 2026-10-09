# Security Policy for UdyAmPath 🛡️

At **UdyAmPath**, we take the security of our career and placement platform—and the data of our students and recruiters—very seriously. We appreciate the community's help in keeping our platform safe and reliable.

## 📌 Supported Versions

Currently, UdyAmPath is in active development. Security updates are applied directly to the `master` branch and subsequent releases. 

| Version | Supported          |
| ------- | ------------------ |
| v0.1.x  | :white_check_mark: |
| < v0.1  | :x:                |

*(Note: We highly recommend always running the latest version from the `master` branch to benefit from the most recent security patches and dependency updates.)*

## 🚨 Reporting a Vulnerability

If you discover a security vulnerability in UdyAmPath, please **do not** report it publicly via GitHub Issues. 

Instead, please report it to the core team by reaching out directly to the maintainers:
- **Komal Giri** (via GitHub profile)
- **Ankit** (via GitHub profile)

When reporting a vulnerability, please include the following details:
1. **Description**: A clear summary of the vulnerability.
2. **Steps to Reproduce**: Detailed instructions on how to replicate the issue.
3. **Impact**: Potential consequences if the vulnerability is exploited (e.g., data leak, unauthorized access).
4. **Environment**: Any relevant context (e.g., browser, specific dependencies).
5. **(Optional) Mitigation**: Any suggested fixes or temporary workarounds.

### What to expect:
- You will receive an acknowledgment of your report within **48 hours**.
- Our team will thoroughly investigate the issue and provide a timeline for a resolution.
- Once the issue is resolved and a patch is deployed, we will coordinate public disclosure and gladly credit you for your responsible discovery (if desired).

## 🤝 Disclosure Policy

- Please notify us as soon as possible upon the discovery of a potential security issue.
- Please provide us a reasonable amount of time to resolve the issue before disclosing it to the public or a third-party.
- Make a good faith effort to avoid privacy violations, destruction of data, and interruption or degradation of our service (e.g., please do not run automated vulnerability scanners against production instances).

## 🔒 Platform Security Highlights

- **Authentication**: UdyAmPath exclusively utilizes **Firebase Authentication** to manage user identities securely.
- **Data Protection**: All real-time data interactions are governed by strict Firebase Realtime Database Security Rules to ensure that students and recruiters can only access data relevant to their specific roles.
- **Sanitization**: We employ robust sanitization utilities (e.g., `DOMPurify`) to prevent XSS attacks across our platform.

Thank you for helping us keep UdyAmPath secure!
