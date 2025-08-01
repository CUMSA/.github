# Cambridge University Malaysia and Singapore Association (CUMSA)

This is where CUMSA writes software!

## Why Open Source?
As a society, we handle lots of sensitive data, and it's important that we do so responsibly. We also need our members to trust us with their data, which means being transparent about how we handle it.

In 2023-24, the committee revamped several membership administration systems. However, the code for these systems was never committed to a version control system, because API credentials were hardcoded. This made software engineering best practices like code review and continuous integration impossible. Our AWS resources were also being called directly from the frontend, which poses a security risk and increases our attack surface.

An [API gateway](https://github.com/CUMSA/api-gateway) to centralize access to APIs, with a long-term view of a microservices architecture. This is deployed on Vercel, allowing us to manage API credentials in a single place and configure policies such as CORS and rate limiting globally.

We are strong advocates for open source for several reasons:

- **Transparency**: Members can see how their data is handled, and contribute to improving our systems if they wish.
- **Security**: More eyes on the code means more eyes to spot vulnerabilities.
- **Sustainability**: If I get hit by a bus, the next database officer can pick up where I left off.
- **Community**: As a society, we are solving problems that are faced commonly by other societies. If we do a good job, hopefully others can benefit from our work.

---

*Xavier, Database Officer 2025-26*
