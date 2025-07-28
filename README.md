# Developer Workspace Platform

## Problem

Supporting 300+ developers across multiple teams with local dev environments is causing:
- 3-5 day onboarding times
- "Works on my machine" issues 
- Inconsistent tooling versions
- High local CPU/memory usage
- No reproducibility

## Solution

Build a platform that provides on-demand, ephemeral dev environments that are:
- Branch/PR specific
- Pre-loaded with correct tools and deps
- Accessible via browser VS Code or CLI
- Integrated with GitHub and K8s dev clusters
- Scalable to 500+ concurrent sessions

## Architecture

See [architecture.md](./architecture.md) for the technical design and implementation details.