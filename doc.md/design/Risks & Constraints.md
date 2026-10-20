# Risks & Constraints
## Context
This section outlines the potential technical, operational, and resource risks associated with the project, along with the key constraints guiding our development decisions.
### Project Risks
* **Technical Risk:** API rate limits or downtime from third-party services could impact feature availability.
  * *Mitigation:* Implement client-side caching and graceful error handling.
* **Schedule Risk:** Delays in pull request reviews may push back milestone deliverables.
  * *Mitigation:* Establish a strict 24-hour SLA for team code reviews.

### Project Constraints
* **Tech Stack:** Development is restricted to HTML, CSS, JavaScript, and Node.js.
* **Timeline:** Final submission and live demo must be completed by Week 12.
* **Budget:** All tools, hosting services, and APIs must utilize free-tier options.
## Decisions
* **Use GitHub Actions for CI/CD** — Team Lead, Oct 2026
## Next Steps
- [ ] Conduct security audit on third-party dependencies (Student 4, due next week)
- [ ] Define emergency fallback behaviour for offline mode (Student 4, due in 2 weeks)
