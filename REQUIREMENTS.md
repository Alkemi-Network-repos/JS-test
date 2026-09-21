# JavaScript Screening - 5 Minutes

Short check, not a take-home. Budget about 5 minutes.

Nothing to install - no packages. Just Node, VS Code, and access to the GitLab repo you were sent.

## 1. Set up your branch

1. In GitLab, click **Code → Open with → Visual Studio Code (HTTPS)**, then pick a local folder - VS Code will clone the repo and open it.
2. In VS Code's status bar, click `main` → **Create new branch...** → name it `submission/firstname-lastname` (your real name, lowercase and hyphenated).
3. Open the terminal (**Ctrl+`** / **Cmd+`**) and run `node --version` - Node 18+ required.

**`main` is read-only.** Work only on your branch - never commit, merge, or open a merge request against `main`.

## 2. Write the code

Open `solution.js`. Three functions have a `// TODO` in the body - implement all
three. The comment above each one gives you the expected behaviour.

Edit only the function bodies. Leave everything below the `do not edit` line alone,
and don't change `REQUIREMENTS.md`.

## 3. Submit

**Commit and push using the Source Control panel - no terminal needed for this part.**

1. Open the **Source Control** panel (the branch icon in the left sidebar).
2. Hover over `solution.js` under "Changes" and click the **+** to stage it (or click **+** next to "Changes" to stage everything).
3. Type your commit message in the message box at the top: `solution: firstname lastname`
4. Click the checkmark **✓ Commit** button.
5. Click **Publish Branch** (first push) or **Sync Changes** (if shown) to push to `origin` and set the upstream for `submission/firstname-lastname`.

Then reply to the email with your branch name. That's it.

If your output doesn't fully match in the time you've given it, push anyway -
partial work is fine and we still want to see it.

## Rules

- Standard JavaScript only. Any built-in method is fair game.
- Your branch only. Don't read other candidates' branches.