# Birthday Present Website

This folder is ready for GitHub Pages.

## Edit in VS Code

Open this folder in VS Code:

```powershell
code .
```

The website file for GitHub Pages is:

```text
docs/index.html
```

The copy in `outputs/index.html` is the Codex output copy.

## Publish With GitHub Pages

1. Create a new GitHub repository.
2. Upload this project folder or push it with Git.
3. In the repository, go to `Settings`.
4. Go to `Pages`.
5. Set `Source` to `Deploy from a branch`.
6. Set the branch to `main`.
7. Set the folder to `/docs`.
8. Save.

GitHub will give you a public website link after it finishes publishing.

## Birthday Lock

The site is locked until:

```text
July 16, 2026 at 12:00 AM
```

To change that later, edit this line in `docs/index.html`:

```js
const unlockDate = new Date("2026-07-16T00:00:00");
```
