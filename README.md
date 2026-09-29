# audit-prep-assistant

Prepares codebases for security review using Trail of Bits' checklist. Helps set review goals, runs static analysis tools, increases test coverage, removes dead code, ensures accessibility, and generates documentation (flowcharts, user stories, inline comments). Use when preparing your own codebase to be audited by someone else, getting a repository review-ready before an external security review, deciding what to fix before auditors start, or asking what assessors need from a project. For understanding unfamiliar code you are about to audit, use audit-context-building instead.

## Overview

This directory contains the operational guidance for the `audit-prep-assistant` skill. Start with [SKILL.md](SKILL.md), which defines when to use it and the workflow it provides.

## Usage

Install or reference this directory through your agent's skill-discovery mechanism, then invoke `audit-prep-assistant` when the task matches the description above. Review linked resources in `SKILL.md` only when that workflow calls for them.

## Included resources

- `agents` — supporting material for this skill.
- `assets` — supporting material for this skill.
