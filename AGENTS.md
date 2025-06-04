# Codex Guide

This repository contains the Request Tracker (RT) application written in Perl.
Key areas of the codebase:
- `lib/RT` – core modules
- `bin/` and `sbin/` – command line tools
- `t/` – tests
- `docs/` – project documentation

## Workflow
Codex should limit itself to static analysis. Do not attempt to configure, build,
or run the test suite. Formatting with `perltidy` and other Perl lint tools is
acceptable, but avoid commands that require a full RT installation.

## Style
Follow the conventions described in `lib/RT/StyleGuide.pod`. Format any changed
Perl files with `perltidy` using the repository's `.perltidyrc`.

## Commit Messages
Begin commit messages with a concise summary line (under 80 characters), followed
by a blank line and any additional detail.
