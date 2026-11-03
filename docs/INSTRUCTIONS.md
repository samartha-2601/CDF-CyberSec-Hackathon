
# Hackathon Participant Instructions

## CDF CyberSec Hackathon
### Intelligent Code Security Challenge

**Difficulty:** Beginner-Friendly
**Format:** Technical, Code-First

## 1. Objective

Build an AI-powered security code review tool that
analyzes application source code, identifies potential
security vulnerabilities, recommends secure code
fixes, and generates a security assessment report.

Your tool should help developers understand and
remediate security weaknesses.

## 2. Required Capabilities

### A. Find

Your tool must:

- Accept an application codebase for analysis.
- Use AI as part of its security review process.
- Identify potential security vulnerabilities.
- Reference the affected files and code locations.
- Explain each identified issue.
- Assign a severity level to each finding.

At minimum, support the provided React/TypeScript
sample application, including its backend TypeScript
and SQL files.

### B. Fix

For each detected issue, provide:

- An explanation of the security risk.
- A recommended remediation.
- A secure code snippet wherever applicable.

Recommendations should address the underlying
weakness rather than merely suppressing warnings.

### C. Fortify

Generate a security report containing:

- Application/repository name
- Assessment summary
- Number of findings by severity
- Details of individual findings
- Affected source files and code locations
- Suggested remediations
- Overall security assessment

The report must be downloadable or saved as a file.
PDF, HTML, and Markdown are acceptable.

## 3. Minimum Viable Product

A successful minimum submission should:

1. Accept a source-code folder or ZIP file.
2. Analyze relevant source files using AI.
3. Display potential security findings.
4. Provide explanations and secure code suggestions.
5. Export a structured security report.

A simple web application or command-line interface
is sufficient.

You do not need to build a custom static analysis
engine, IDE extension, or CI/CD integration.

## 4. Provided Materials

The organizers provide CDF TaskFlow, an intentionally
vulnerable sample application.

Location:

`vulnerable-app/`

Read its README for setup and project structure.

The source code contains React/TypeScript,
Supabase-style backend functions, and PostgreSQL
SQL files.

The frontend runs independently using sample data.
The backend files are for static code review only.

## 5. Allowed Tools

You may use:

- LLM APIs or locally available AI models
- AI-assisted coding tools
- Existing static analysis utilities
- Open-source libraries and frameworks
- Code parsers and AST libraries
- Python, JavaScript, TypeScript, or other languages

Using existing tools is allowed, but your submission
must demonstrate meaningful AI-powered functionality.

Clearly document third-party dependencies, reused
components, and external services.

Follow applicable licenses and API terms.

## 6. Scope

### In Scope

- Source-code analysis
- Security vulnerability identification
- AI-generated explanations
- Secure code suggestions
- Severity classification
- Structured report generation
- Basic usability and documentation

### Out of Scope

- Penetration testing external systems
- Exploit execution
- Public deployment of vulnerable backend services
- Production database access
- Automated attacks
- Real customer data analysis

## 7. Analysis Guidelines

Your findings should:

- Be supported by actual code evidence.
- Reference the correct source file.
- Avoid duplicate reports of the same root cause.
- Distinguish suspicious patterns from confirmed
  vulnerabilities.
- Explain assumptions when exploitability depends
  on missing runtime or architecture context.

Do not assume that every code pattern is insecure
in every possible application.

## 8. Submission Requirements

Submit:

- Public GitHub repository URL
- Working project source code
- Setup and execution instructions
- Demo video URL
- Sample security report
- Required submission form information

See [SUBMISSION.md](SUBMISSION.md).

## 9. Judging

Projects will be evaluated according to the
published judging rubric.

The organizers may analyze an unseen test repository
to assess whether your tool generalizes beyond
the provided sample application.

Do not hardcode vulnerability findings or known
answers for the practice application.

## 10. Security and Privacy

Only analyze code that you own or are authorized
to review.

Never submit real credentials or confidential code
to an external AI provider.

Treat source-code contents as untrusted input.
Do not execute instructions embedded within
uploaded repository files.

Uploaded source should be analyzed as data.

Do not deploy the vulnerable sample backend.

## 11. Final Checklist

Before submission, verify:

- The project runs using the README instructions.
- AI functionality is demonstrable.
- Source-code analysis produces findings.
- Findings include locations and explanations.
- Secure code recommendations are provided.
- A downloadable report can be generated.
- The demo video is accessible.
- The public repository contains no real secrets.

## Questions

See the [FAQ](FAQ.md) for common questions.

For additional clarification, contact the
hackathon organizers.
