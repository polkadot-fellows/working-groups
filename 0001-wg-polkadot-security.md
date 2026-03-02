# WG-0001: Polkadot Security

|                         |                                         |
| ----------------------- | --------------------------------------- |
| **Start Date**          | 2026/02/23                              |
| **Initial leader(s)**   | @xlc, @bkchr                            |


## Description

The Polkadot Security Working Group focuses on improving runtime security through automated testing and analysis. This is achieved by leveraging cutting-edge security tools including fuzzing, static analysis, and AI-powered review systems.

Our mission aligns with the Manifesto's goal of maintaining a secure and reliable Polkadot network. We undertake the following tasks:

1. **Continuous Blackbox Testing**: Running 24/7 fuzzers with randomly generated data, integrity assertions (e.g., `try_state` checks), and AI-powered log analysis to detect runtime violations automatically.

2. **Whitebox Testing & Code Analysis**: Source code inspection for edge cases and attack surfaces, targeted test generation, and maintaining regression test suites.

3. **AI-Powered Review Tools**: Developing specialized agents for PR review, release diff analysis, and focused reviewers for weight files, pallets, test cases, parameters, and migrations.

4. **Invariant Analysis**: AI-generated invariants from runtime behavior, state verification function generation, and integration with fuzzers for state validation.

We measure impact through:
- Number of runtime vulnerabilities discovered before production
- Test coverage improvements across runtime codebases
- Reduction in security-related incidents
- Automated triage and resolution rate of security findings

We are looking to onboard participants with expertise in:
- Runtime development and FRAME
- Fuzzing and security testing
- AI/LLM tool usage and prompt engineering
- Security research and vulnerability analysis


## Resources & Links

### Core Projects

- **Runtime Fuzzer**: https://github.com/polkadot-fellows/runtimes-fuzzer - Continuous fuzzing engine using pluggable test case generators
- **Goal Document**: https://github.com/polkadot-fellows/runtimes-fuzzer/blob/main/docs/GOAL.md

### Planned Components

1. **Runtime Fuzzer**: Continuous fuzzing engine that executes test cases 24/7 against runtimes
2. **Static Analyzer & Test Generator**: Source code inspection tool for edge cases and attack surfaces
3. **Failure Investigator**: Root cause analysis for failed assertions with automated issue creation
4. **Review Agents Suite**:
   - PR Reviewer (CI/CD integration)
   - Release Reviewer (diff analysis)
   - Specialized agents for weights, pallets, parameters, and migrations


## Public channels

**Note**: As this is a security initiative, the main repository and discussion channels are kept private to facilitate responsible disclosure and coordinated vulnerability management.

For general inquiries about the working group's mission (not specific security findings), please reach out through [Polkadot Technical Fellowship - Open Channel](https://matrix.to/#/#fellowship-open-channel:parity.io).

**For security vulnerability disclosures**, please report to Parity Bug Bounty program: https://www.parity.io/bug-bounty

