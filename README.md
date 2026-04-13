# Riftmap-Open-Source — Change Impact Engine for multi-repo systems

> "If I change repo X, what else breaks?"

I have created Riftmap, https://riftmap.dev. A cross repo dependency mapper. Once the SaaS has had time to mature and proved stability, I plan on sharing helpfull code and learnings from it.

Riftmap scans a GitLab or GitHub organization, automatically discovers how repositories depend on each other across ecosystems (Terraform, Docker, Python, CI/CD pipelines, Ansible, Helm, Go modules, npm, Kustomize, Kubernetes), and builds a queryable dependency graph with visual impact analysis.

**Zero per-repo configuration.** No manually maintained YAML. Install once at the org level with a read-only access token, and Riftmap discovers everything from the actual code.
