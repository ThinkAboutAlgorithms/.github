# Security Policy

At **Think About Algorithms**, we take security concerns seriously and are committed to maintaining a safe, trustworthy, and responsible open-source environment. Although the organization primarily publishes educational algorithm implementations rather than production software, we recognize that developers, students, and organizations may still rely on these repositories for learning, experimentation, or integration. For this reason, all security-related concerns are treated with care, professionalism, and timely attention.

This policy explains which projects are covered, what qualifies as a security issue, how to report vulnerabilities responsibly, and how disclosures are handled by maintainers.

---

## Supported Projects

This security policy applies to all repositories maintained under the **Think About Algorithms** organization unless a specific repository defines its own `SECURITY.md` with alternative instructions.

Repositories within the organization primarily contain reference implementations of algorithms across multiple programming languages. While these implementations are educational in nature and not intended for direct production deployment, vulnerabilities or unsafe patterns in educational code can still propagate into real-world usage. As such, reported security concerns are reviewed and addressed with the same diligence expected in professional software projects.

---

## What to Report

We encourage responsible reporting of any issue that may pose a security risk to users who read, clone, study, adapt, or execute code from Think About Algorithms repositories.

This includes, but is not limited to, vulnerabilities in algorithm implementations, logic flaws that could cause unsafe or undefined behavior, dependency-related vulnerabilities where applicable, malicious or unauthorized code injection, unsafe or dangerous use of language features (such as buffer overflows, unsafe memory access, unchecked pointer arithmetic, or insecure input handling), and any condition that could negatively affect users interacting with the repository content.

If there is uncertainty about whether an issue qualifies as a security concern, it is always appropriate to report it. Maintainers will evaluate the report and determine classification.

---

## What Not to Report

Certain issues are generally outside the scope of security reporting and should instead be submitted as standard GitHub issues. These include incorrect algorithm outputs that do not create exploitable conditions, performance limitations, formatting or stylistic concerns, feature or algorithm requests, and general educational or documentation improvements.

Keeping non-security matters out of the security channel helps ensure that genuine vulnerabilities receive timely attention and appropriate handling.

---

## How to Report a Vulnerability

Security vulnerabilities should never be disclosed publicly before maintainers have had an opportunity to investigate and remediate the issue. Public disclosure prior to a fix may expose users to unnecessary risk or enable misuse.

The preferred reporting method is to open a private security advisory through GitHub, if the feature is enabled for the repository. If a private advisory channel is not available, reporters should contact maintainers directly using the organization’s published security or contact email address, where provided. As a last resort, if no private channel exists, a public issue may be opened only if it is clearly marked in the title with the prefix `SECURITY:` followed by a brief description, and sensitive technical details should be minimized until maintainers respond.

A high-quality vulnerability report should include the affected repository name, a clear description of the issue, steps required to reproduce the problem, a proof of concept if applicable, an explanation of potential impact, and—if available—a suggested mitigation or fix. Detailed reports significantly accelerate investigation and resolution.

---

## Response Timeline

Think About Algorithms is maintained by volunteers; however, security reports are prioritized appropriately. Maintainers aim to acknowledge receipt of a valid vulnerability report within seventy-two hours, provide a status update within seven days, and prepare and release a fix as soon as reasonably possible given the complexity of the issue and contributor availability.

Timelines may vary depending on technical scope, cross-language implications, and maintainer capacity, but transparent communication is maintained throughout the process whenever feasible.

---

## Responsible Disclosure

We request that reporters follow responsible disclosure practices to protect users and the integrity of the project. This includes refraining from public disclosure of the vulnerability until a fix or mitigation is available, allowing maintainers reasonable time to investigate and remediate the issue, and avoiding exploitation beyond what is strictly necessary to demonstrate proof of concept.

Responsible disclosure enables coordinated fixes and prevents accidental harm or misuse. We deeply appreciate ethical reporting conducted in good faith.

---

## Recognition

Individuals who responsibly disclose valid and impactful security issues may be acknowledged in release notes, repository documentation, or project communications as a token of appreciation for strengthening the project’s safety and reliability. Recognition is entirely optional, and anonymity will always be respected if requested by the reporter.

---

## Scope

This policy applies exclusively to repositories owned and maintained by the **Think About Algorithms** organization. It does not extend to third-party forks, external dependencies, downstream adaptations, or unofficial mirrors of the repositories.

Issues originating from external projects should be reported to their respective maintainers according to their own security policies.

---

Security and trust are essential—even in educational software.

Thank you for helping maintain a safe, responsible, and professional open-source ecosystem within Think About Algorithms.
