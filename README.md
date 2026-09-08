Bank Security System 
A robust, enterprise-grade backend security and authentication system built with Spring Boot, featuring advanced threat mitigation, multi-factor authentication, and strict traffic control.
Key Features
JWT Authentication: Secure stateless user sessions and token-based authorization.
TOTP 2FA: Time-based One-Time Password multi-factor authentication for high-security accounts.
Redis Rate-Limiting: High-performance request and login throttling to prevent brute-force and DDoS attacks.
VPN & Proxy Blocking: Advanced network guard service using IP intelligence and CIDR blocklists to filter out malicious connections and proxies.
Automated Maintenance: Scheduled background tasks for efficient refresh token cleanup and database optimization.
Tech Stack
Java / Spring Boot
Spring Security & JWT
Redis (Rate-limiting & Caching)
Maven
