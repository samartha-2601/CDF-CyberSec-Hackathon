
# CDF CyberSec Hackathon

## Intelligent Code Security Challenge

### AI that sees what your code is hiding.

Welcome to the CDF CyberSec Hackathon!

In this two-day, code-first hackathon, you will build
an AI-powered security code review tool that analyzes
application source code, identifies potential security
vulnerabilities, recommends secure code fixes, and
generates a comprehensive security assessment report.

The challenge is designed to be beginner-friendly.
Advanced cybersecurity expertise is not required.

## The Challenge: Find. Fix. Fortify.

### FIND — Identify Security Issues

Build a tool that uses AI to analyze source code and
identify potential vulnerabilities.

Examples include:
- Hardcoded secrets
- Missing authorization
- Unsafe input handling
- SQL injection
- Cross-site scripting (XSS)
- Insecure configurations
- Database access control weaknesses

### FIX — Recommend Secure Code

For each finding, your tool should explain:
- What is wrong
- Why it matters
- Where the issue exists
- How to remediate it

Include a secure code snippet wherever possible.

### FORTIFY — Generate a Security Report

Generate a comprehensive report containing:
- An executive summary
- Identified vulnerabilities
- Severity classifications
- Affected file paths and code locations
- Technical explanations
- Recommended fixes
- An overall security assessment

## Challenge Format

- Duration: 2 days
- Difficulty: Beginner-friendly
- Focus: Technical implementation
- AI usage: Required
- Development tools: Flexible
- Submission: Working tool, public repository,
  demo video, and sample security report

Participants may use LLM APIs, AI development tools,
existing libraries, and open-source security utilities.

Your solution must meaningfully use AI for security
analysis, explanation, or remediation.

## Sample Application

A small intentionally vulnerable application,
CDF TaskFlow, is provided for this challenge.

It includes a React/TypeScript frontend, representative
backend source files, and database access policies.

Participants can use it to develop and demonstrate
their security analysis tools.

**[Access CDF TaskFlow](vulnerable-app/README.md)**

The application is intentionally vulnerable.
Do not deploy it to public or production systems.

## Getting Started

1. Read the [Hackathon Instructions](docs/INSTRUCTIONS.md).
2. Review the [FAQ](docs/FAQ.md).
3. Download the [Sample Application](vulnerable-app/).
4. Build your AI-powered security reviewer.
5. Review the [Judging Criteria](docs/JUDGING-CRITERIA.md).
6. Prepare your [Submission](docs/SUBMISSION.md).

## Expected Deliverables

Each participating team must submit:

1. A working AI-powered security code review tool
2. A public GitHub repository containing source code
3. A README explaining setup and usage
4. A demo video showing the tool in action
5. A sample security assessment report

See the submission guidelines for further details.

## Evaluation

Solutions will be judged on:

| Criteria | Weight |
|---|---:|
| Vulnerability detection accuracy | 35% |
| Quality of recommended fixes | 25% |
| Security report quality | 20% |
| Ease of use | 10% |
| Effective use of AI | 10% |
| **Total** | **100%** |

The organizers may use an additional unseen
application to evaluate submitted tools.

## Repository Contents

| Location | Description |
|---|---|
| `vulnerable-app/` | Sample application |
| `docs/INSTRUCTIONS.md` | Challenge instructions |
| `docs/FAQ.md` | Frequently asked questions |
| `docs/SUBMISSION.md` | Submission requirements |
| `docs/JUDGING-CRITERIA.md` | Evaluation criteria |
| `templates/SAMPLE-REPORT.md` | Example report structure |
| `presentation/` | Kickoff materials |

## Responsible Use

All challenge work must be limited to authorized
educational codebases.

Do not upload confidential client code, real
credentials, or sensitive organizational data
to external AI services.

Do not deploy the intentionally vulnerable sample
backend to publicly accessible infrastructure.

## Recognition

Participants will gain:
- Practical experience building AI security tools
- Hands-on exposure to secure coding practices
- A portfolio-ready project
- Recognition for accurate and useful solutions

## Questions

Refer to the [FAQ](docs/FAQ.md) or contact the
hackathon organizers through the official event
communication channel.

---

**CDF CyberSec Hackathon**

*AI that sees what your code is hiding.*
