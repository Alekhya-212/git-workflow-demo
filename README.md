# Main Branch – Stable Release

The `main` branch represents the **production-ready code**.  
All tested and approved changes from `dev` are merged here, and this branch is used to mark official versions of the application.

---

## 🔹 Key Highlights
- Integrated updates from `dev` after resolving conflicts.
- Created release tag **v1.0** to mark the first stable version.
- Serves as the baseline for future releases and deployments.

---

## 🔹 Commands Used
```bash
# Switch to main branch
git checkout main

# Merge changes from dev
git merge dev

# Create annotated tag for release
git tag -a v1.0 -m "First stable release"

# Push branch and tag to remote
git push origin main
git push origin v1.0

