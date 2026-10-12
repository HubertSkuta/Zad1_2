---
name: Imported Java environments
description: Diagnosing missing Java tools when an imported project already selects a Java module.
---

Legacy Nix dependency evaluation can block the entire environment, making Java and Maven appear missing even when the Java module is selected.

**Why:** This import's legacy Java/editor dependencies prevented environment construction. Removing the redundant dependencies through the package-management tools restored the existing module's tools.

**How to apply:** When configured Java tools are missing, check environment evaluation errors before adding another toolchain. Keep the existing stack and remove obsolete duplicate dependencies rather than migrating the project.
