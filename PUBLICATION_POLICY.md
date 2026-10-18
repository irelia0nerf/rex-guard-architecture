# Public disclosure boundaries

## Purpose

This repository makes a selected architecture available for professional
evaluation. Its publication is intentional; its scope is limited to the material
actually included here.

| Suitable for this repository | Keep outside this repository |
|---|---|
| General control topology and trust boundaries | Private source code and implementation internals |
| Failure semantics and architectural trade-offs | Customer names, contracts, environments, or data |
| Synthetic JSON examples and diagrams | Credentials, key identifiers, private endpoints, or tenant identifiers |
| Public standards and provider documentation | Internal findings, readiness status, incident evidence, or legal documents |
| Proposed acceptance scenarios with explicit status | Unsupported test, performance, certification, or compliance claims |

## Claims

Distinguish a design requirement from an implementation, a test result, a
deployment, and an independently verified observation. Adding a measurement
requires its version, environment, method, date, scope, and limitations.

Architecture changes must preserve the distinction between authorization,
dispatch, target commitment, and evidence. A signed record does not by itself
prove the factual correctness of the event it describes.

## Rights and disclosure

The repository's [rights notice](LICENSE) reserves rights in protectable content
without granting a general open-source or open-content license. It does not
create ownership over ideas, standard methods, or mathematics; determine the
ownership of underlying technology; or establish patent protection.

Public content should be treated as disclosed and copyable in practice. A later
deletion or visibility change cannot be relied upon to retrieve existing forks
or local copies. Confidentiality therefore depends on keeping confidential
material outside this repository, not on a notice attached after publication.

## Review before publication

- Confirm that every file is intended for public release.
- Use synthetic examples without live identifiers or sensitive data.
- Check internal references, customer details, secrets, and local paths.
- Preserve source links and distinguish public evidence from design choices.
- Resolve rights and third-party-content questions before incorporating material.
- Keep product commitments and legal agreements outside architecture examples.

These are publication practices for this repository, not a statement that an
automated scan can prove absence of all confidential information.

## Official references

- [GitHub: Licensing a repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository).
- [WIPO: Copyright frequently asked questions](https://www.wipo.int/en/web/copyright/faq-copyright).
