# hyperForest Snippets

Optional CSS snippets to enhance your hyperForest theme experience.

## Installation

1. Copy the desired `.css` file to your vault's snippets folder:
   ```
   YourVault/.obsidian/snippets/
   ```

2. In Obsidian, go to **Settings → Appearance → CSS snippets**

3. Toggle on the snippet you want to use

## Available Snippets

| Snippet | Description |
|---------|-------------|
| `math-hyperforest.css` | MathJax theming — bold pink base, H1 deep pink operators, fraction/sqrt lines |
| `daily-hide-comments.css` | Hides HTML comments in daily notes |
| `font-recursive-*.css` | Recursive font variants for different contexts |

More snippets coming soon! Feel free to contribute your own.

## Sync Notice

Snippets in this directory are **repo copies**. Obsidian loads snippets from the vault's global snippets folder:

```
<vault>/.obsidian/snippets/
```

**Both locations must stay in sync.** When editing any snippet, update both:

| Location | Purpose |
|----------|---------|
| `<vault>/.obsidian/snippets/<file>.css` | **Live** — loaded by Obsidian |
| `<vault>/.obsidian/themes/hyperForest/snippets/<file>.css` | **Repo** — tracked in git |
