
# Frequently Asked Questions

## CDF CyberSec Hackathon

### 1. Do I need cybersecurity experience?

No. The hackathon is beginner-friendly.

You are encouraged to learn about security
vulnerabilities while building your solution.

### 2. Is using AI mandatory?

Yes.

Your tool must meaningfully use AI for security
analysis, vulnerability explanation, or remediation.

You may combine AI with traditional rules and
existing security scanning tools.

### 3. Which AI model should I use?

You may use an available LLM API or local model,
subject to your organization's approved tools
and applicable terms.

No specific AI provider is required.

### 4. Can I use Lovable to build my tool?

Yes.

You may use Lovable or other AI-assisted
development environments.

However, your final submission must be a working
security code review tool, not just a prototype
design or presentation.

### 5. Do I need to build a scanner from scratch?

No.

You may use existing libraries, static analyzers,
and open-source components.

You must document what your project uses and
demonstrate meaningful AI-powered functionality.

### 6. Must my tool have a graphical interface?

No.

A working command-line interface is acceptable.

A simple web interface is also acceptable.

### 7. What source code must my tool support?

At minimum, it should review the provided
CDF TaskFlow codebase.

This includes relevant React/TypeScript,
backend TypeScript, and SQL files.

Additional language support is optional.

### 8. Must I detect every vulnerability?

No.

Detection accuracy and quality matter more than
the number of alerts generated.

False positives and duplicate findings may
reduce your evaluation score.

### 9. Are secure code suggestions mandatory?

Yes.

For each reported security issue, provide a
recommended fix and a secure code snippet where
a code-level remediation is applicable.

### 10. Is automatic code modification required?

No.

Your tool only needs to recommend fixes.

Automatically editing the original code is optional.

### 11. Do I need to run the vulnerable backend?

No.

The backend functions and SQL migrations are
provided for static analysis.

The frontend can run using local sample data.

Do not deploy the vulnerable backend.

### 12. Can I use GitHub repositories as input?

Yes.

Your tool may support GitHub URLs, local folders,
or ZIP uploads.

The minimum requirement is to support one practical
way of supplying the sample codebase.

### 13. What format should the report use?

PDF, HTML, or Markdown is acceptable.

The report must be downloadable or saved as a file
and must contain the required security information.

### 14. Can I use external AI APIs?

Yes, subject to approved services, API terms,
cost limits, and data-handling restrictions.

Use only the synthetic hackathon materials or
other code you are authorized to share.

### 15. Will the organizers provide an answer key?

No.

The locations and number of intended security
issues will not be disclosed during the challenge.

### 16. Will my tool be tested on other code?

It may be.

Organizers may use an unseen evaluation application
to assess detection accuracy and generalization.

### 17. What counts as a false positive?

A false positive is a reported vulnerability that
is not supported by the available code and context.

For example, reporting a fabricated demonstration
value as a confirmed leaked production credential
would be an overstatement.

### 18. How detailed should explanations be?

Explanations should be understandable to a developer
without specialist security knowledge.

Describe the problem, its impact, and the fix.

### 19. Can I submit a project created before the event?

Existing tools and libraries may be reused.

Your submission must clearly identify reused
components and work developed during the hackathon.

The organizers may request clarification about
third-party code or pre-existing functionality.

### 20. What must I submit?

A working tool, public repository, project README,
demo video, and sample security report.

See [Submission Guidelines](SUBMISSION.md).

### 21. Can I publish my project publicly?

Yes.

The challenge expects a public repository.

Do not publish real credentials, confidential
information, or private organizer evaluation data.

### 22. What if my tool produces an incorrect finding?

That is acceptable as part of the learning process.

Judges will assess detection accuracy, false
positives, explanations, and recommended fixes.

### 23. Will an attractive UI receive extra marks?

Usability is part of the evaluation, but security
accuracy and remediation quality carry more weight.

A simple tool that works reliably is preferable
to an attractive tool with unreliable findings.

### 24. Where do I ask questions?

Use the official hackathon communication channel
announced by the organizers.
