# Operator Profile — Installation Guide

## 1. Create the special profile repository

Create a **public** GitHub repository whose name is exactly the same as your GitHub username.

Example:

```text
Username: Ichyaboy
Repository: Ichyaboy/Ichyaboy
```

GitHub displays the root `README.md` of that repository on your profile.

## 2. Copy this template

Your repository should look like this:

```text
YOUR_USERNAME/
├── README.md
├── assets/
│   └── operator-console.svg
└── .github/
    └── workflows/
        └── snake.yml
```

Copy the included files into those locations.

## 3. Replace placeholders

Search the whole repository for:

```text
YOUR_USERNAME
YOUR_BLOG_URL
YOUR_LINKEDIN_URL
YOUR_EMAIL
```

Also edit `ICHYABOY` inside:

- `README.md`
- `assets/operator-console.svg`

## 4. Enable the contribution animation

The workflow already requests `contents: write`.

After pushing:

1. Open the repository's **Actions** tab.
2. Open **Generate contribution snake**.
3. Select **Run workflow**.
4. Wait for the workflow to finish.
5. Confirm that a branch named `output` was created.

If GitHub blocks the write operation:

1. Open **Settings → Actions → General**.
2. Find **Workflow permissions**.
3. Select **Read and write permissions**.
4. Save and run the workflow again.

## 5. Pin repositories that support the story

Pin 4–6 repositories that demonstrate:

- one polished security tool,
- one lab or educational environment,
- one documentation or wiki project,
- one unusual specialty such as BLE, firmware, or medical-device security.

A cool README cannot compensate for empty or unclear repositories. Each pinned project should have a screenshot, clear purpose, setup instructions, and a legal-use statement where relevant.

## 6. Keep confidential work out

Do not publish:

- client names,
- internal IP addresses or domains,
- screenshots from customer environments,
- credentials, tokens, private keys or flags,
- proprietary source code,
- unredacted reports,
- exploit code copied from a confidential engagement.

Describe the testing method and lesson, not the customer.

## 7. Test the rendering

Check your profile in:

- GitHub dark mode,
- GitHub light mode,
- desktop,
- mobile,
- another browser.

The banner supports reduced-motion preferences. If an SVG rendering issue appears in a browser, export a GIF fallback and reference that instead.
