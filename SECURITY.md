# Security Policy

This repository is an archival package for a published research paper —
"A Taxonomy of Epistemic Failure Modes in Large Language Models"
(<https://doi.org/10.5281/zenodo.19042469>). It ships no runtime software,
no network service, and no production deployment, so there is no
conventional software attack surface to secure here.

The repository does include a small offline convenience script,
`verify.py`, that checks package integrity, citation identity, and the
published PDF's bytes against the checksum manifest. It makes no network
calls, is not a service, and is not designed to process untrusted input;
it exists only to let a reader confirm the archived files have not been
altered.

## Reporting a problem

If you find a problem with the archived materials — a corrupted or
tampered file, a checksum mismatch, an error in the citation or metadata
files, or a concern about how this archive is represented — please report
it by opening a GitHub issue on this repository, or by email to
<roli@hermes-labs.ai>.

This is a solo-maintained research archive. Reports are read and
acknowledged in good faith, but no fixed response time or service-level
agreement is promised.

## Scope

This policy covers only the materials in this repository. It does not
cover the canonical Zenodo deposit, hermes-labs.ai, or any other Hermes
Labs repository.
