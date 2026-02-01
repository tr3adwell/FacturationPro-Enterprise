# Contributing to FacturationPro Enterprise

Thanks for your interest in FacturationPro Enterprise. Since this is a **proprietary project**, contributions work a bit differently than open-source repos.

---

## Can I contribute?

Not directly — there's no public branch to push to. The full source code isn't available in this repository, only selected code snippets and documentation.

However, there are ways to get involved:

### Bug reports & feedback
If you spot something in the documentation or screenshots that looks off, or if you have feedback on the architecture decisions, feel free to open a GitHub **Issue**. I genuinely appreciate it — outside perspective is useful.

### Collaboration or licensing
If you're interested in using FacturationPro, building on top of it, or partnering on development, reach out directly. I'm open to conversations about that.

### Questions about the code
The code snippets in `code-snippets/` are intentionally partial. If something is unclear about the architecture or the patterns used, open an Issue with your question and I'll do my best to explain.

---

## If we do work together

Here's how I'd expect things to go, just so we're on the same page:

**Code style** — The project uses consistent formatting across all C++ files. Braces on the same line for control flow, explicit comments on non-obvious logic, and clear separation between declaration (`.h`) and implementation (`.cpp`).

**Database changes** — Any schema modification needs to be backward-compatible or come with a migration script. The app uses soft deletes everywhere, so we never actually drop data.

**Testing** — New features should come with at least a manual test checklist. Automated testing infrastructure isn't in place yet, but that's on the roadmap.

**Communication** — Keep it simple. If you're working on something, a quick note on what you're doing and why is all that's needed. No need for formal PRs or design docs for small changes.

---

Thanks for reading. If you have any questions, just open an Issue.
