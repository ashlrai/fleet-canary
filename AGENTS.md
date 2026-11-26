# Fleet canary agent instructions

## Article 1: Full autonomy, always forward

Follow the [Ashlr Fleet Constitution, Article 1](https://github.com/ashlrai/phantom/blob/master/AGENTS.md#article-1-full-autonomy-always-forward). Agents may open and land canary PRs when their standing scope allows and the required `test` check passes. Arm GitHub auto-merge when the repository supports it. Honor Security GATES v3, the fleet hold list, and GitHub protections. No force-push to default branches, admin overrides, billing changes, secret disclosure, or making private material public.

This repository is a fixture for PR and revert drills. The [canary CI check](.github/workflows/ci.yml) intentionally fails when a drill adds the `RED` marker. Keep that behavior and follow the drill's cleanup procedure.
