# GitHub Profile README — Setup Guide

This folder contains the profile README for GitHub user **`allab2`**. A profile README appears at the top of your GitHub profile page when you create a public repository with the **same name as your username**.

---

## Prerequisites

- A GitHub account with username: **`allab2`**
- Git installed locally
- This folder's `README.md` ready to publish

---

## Step 1: Create the profile repository on GitHub

1. Sign in to [GitHub](https://github.com).
2. Click **+** (top right) → **New repository**.
3. Set the repository name to exactly:

   ```
   allab2
   ```

   > **Important:** The repo name must match your GitHub username exactly. This is what makes it a profile README.

4. Set visibility to **Public**.
5. Check **Add a README file** (optional — you will replace it with the one from this folder).
6. Click **Create repository**.

---

## Step 2: Clone the repository (if you have not already)

```bash
git clone https://github.com/allab2/allab2.git
cd allab2
```

If you already created the repo with a default README, pull it first:

```bash
git pull origin main
```

---

## Step 3: Add the profile README

Copy the `README.md` from this folder into your cloned repository, replacing any existing README:

```bash
cp /path/to/this/folder/README.md ./README.md
```

Or open the repo in your editor and paste the contents of `README.md` manually.

---

## Step 4: Customize before publishing

Update these placeholders in `README.md`:

| Section | What to change |
|---|---|
| **Featured Work** | Replace `[Project Name](project-link-here)` with real repo names and URLs |
| **Connect** | Add your LinkedIn URL, email, and portfolio link |
| **GitHub stats** | Stats load automatically for `allab2`; remove the section if you prefer a cleaner look |

---

## Step 5: Commit and push

```bash
git add README.md
git commit -m "Add professional data engineer profile README"
git push origin main
```

If your default branch is `master`, use `master` instead of `main`.

---

## Step 6: Verify on your profile

1. Open **https://github.com/allab2**
2. Refresh the page if needed.
3. The README content should appear **above** your pinned repositories and contribution graph.

---

## Notes

- **Only one profile README:** GitHub displays the README from the public repo named `allab2/allab2`.
- **No special folder:** The file must be `README.md` at the **root** of the repository — not in a subfolder.
- **Edits are live:** Any push to `README.md` on the default branch updates your profile after a refresh.
- **Private repo:** A profile README repo must be **public** to appear on your profile.

---

## Optional: Pin repositories

After publishing your profile README:

1. Go to your profile → **Customize your pins**
2. Pin 4–6 repositories that best represent your data engineering work
3. This complements the Featured Work section in your README

---

## Troubleshooting

| Issue | Fix |
|---|---|
| README not showing | Confirm repo is public and named exactly `allab2` |
| Old content still visible | Hard refresh (Cmd+Shift+R / Ctrl+Shift+R) or wait a minute |
| Stats badge not loading | Third-party stats service may be slow; remove the section if undesired |
| Wrong branch | Ensure `README.md` is on the repository's **default** branch |

---

## Reference

- [GitHub Docs: Managing your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
