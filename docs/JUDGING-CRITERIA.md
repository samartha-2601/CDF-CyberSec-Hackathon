
# Judging Criteria

## CDF CyberSec Hackathon
### Intelligent Code Security Challenge

Projects will be evaluated using five criteria.

## Scoring Summary

| Category | Weight |
|---|---:|
| Vulnerability Detection Accuracy | 35% |
| Quality of Recommended Fixes | 25% |
| Security Report Quality | 20% |
| Ease of Use | 10% |
| Effective Use of AI | 10% |
| **Total** | **100%** |

## 1. Vulnerability Detection Accuracy — 35 Points

Judges will assess whether the tool:

- Identifies genuine security weaknesses
- References relevant files and code locations
- Provides evidence supporting each finding
- Avoids unsupported or speculative alerts
- Minimizes duplicate findings
- Performs on unseen evaluation code

Both missed vulnerabilities and false positives
may affect the score.

## 2. Quality of Recommended Fixes — 25 Points

Judges will assess whether the tool:

- Explains why each issue is dangerous
- Recommends a technically appropriate fix
- Includes secure code snippets where applicable
- Addresses the underlying cause of the issue
- Avoids introducing obvious new vulnerabilities
- Provides developer-friendly guidance

## 3. Security Report Quality — 20 Points

Judges will assess whether the report includes:

- Executive summary
- Findings grouped or classified by severity
- Affected files and code locations
- Clear descriptions and supporting evidence
- Remediation recommendations
- Overall security assessment

The report should be understandable and actionable.

PDF, HTML, or Markdown exports are acceptable.

## 4. Ease of Use — 10 Points

Judges will assess:

- Ease of installation and setup
- Clarity of instructions
- Simplicity of the analysis workflow
- Readability of findings
- Reliability of normal tool operation

A command-line tool and a web interface are
equally eligible.

## 5. Effective Use of AI — 10 Points

Judges will assess:

- Meaningful integration of an AI model
- AI contribution to analysis or remediation
- Quality of generated explanations
- Reliability and consistency of AI output
- Appropriate handling of uncertainty

Merely displaying generic AI-generated text
without meaningful security functionality
will not receive full credit.

## Evaluation Process

Judges may:

1. Review each submission repository.
2. Watch the submitted demo.
3. Examine the sample security report.
4. Run the tool against an unseen test codebase.
5. Evaluate the quality of generated findings.
6. Assign scores using the rubric above.

The same evaluation codebase and procedures
will be used consistently where practical.

## Important Notes

- More reported vulnerabilities do not
  automatically mean a better solution.
- Correctness is more important than alert volume.
- Unsupported high-severity claims may reduce
  confidence in the report.
- Appropriate security recommendations matter.
- A sophisticated UI is not required.
- An incomplete tool may still receive partial credit.

The organizers reserve the right to resolve
ambiguous results consistently and document
their scoring rationale.
