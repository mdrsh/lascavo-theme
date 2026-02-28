# Lascavo Theme for VS Code

A carefully crafted, neutral dark theme designed for long coding sessions. Lascavo balances calm, low-contrast backgrounds with logical, highly specific syntax highlighting to help you read code faster and reduce eye strain.

Whether you prefer warm accents, cool tones, or high-contrast syntax, Lascavo has a variant tailored for your workspace.

## 🎨 Three Distinct Variants

Lascavo comes in three flavors to match your environment and mood:

- **Lascavo Classic:** The original experience. A neutral dark grey background with elegant burgundy/red UI accents. Syntax colors are muted and perfectly balanced to keep you focused without overwhelming your eyes.

- **Lascavo Classic Contrast:** The layout of the Classic theme, but with hyper-vibrant, high-contrast syntax highlighting. Perfect for working in bright environments, presenting code on screens, or developers who prefer maximum color distinction.

- **Lascavo Cold:** A cooler, blue-tinted approach. It features a deep blue-grey background with sharp blue UI accents.

<img src="https://raw.githubusercontent.com/mdrsh/lascavo-theme/main/images/ui-classic-preview.png" alt="Lascavo Cold Preview" width="500">
<img src="https://raw.githubusercontent.com/mdrsh/lascavo-theme/main/images/classic-preview.png" alt="Lascavo Classic Preview" width="500">
<img src="https://raw.githubusercontent.com/mdrsh/lascavo-theme/main/images/contrast-preview.png" alt="Lascavo Contrast Preview" width="500">

<img src="https://raw.githubusercontent.com/mdrsh/lascavo-theme/main/images/ui-cold-preview.png" alt="Lascavo Cold Preview" width="500">
<img src="https://raw.githubusercontent.com/mdrsh/lascavo-theme/main/images/cold-preview.png" alt="Lascavo Cold Preview" width="500">

## ✨ Key Features & Advantages

Lascavo isn't just a color palette; it's built with an obsessive attention to TextMate scopes and VS Code's modern semantic highlighting engine.

- **Pristine HTML & JSX:** Structural tags (`div`, `header`, `form`) are visually separated from inline tags (`span`, `a`), helping you grasp the DOM tree at a glance. Classes, IDs, and standard attributes all have distinct, logical colors.
- **Full Semantic Highlighting:** Native support for TypeScript and JavaScript semantic tokens. Variables, properties, classes, and types cascade perfectly, providing incredibly accurate coloring that standard regex parsers miss.
- **Master-Level Regular Expressions:** Complex Regex is finally readable. Lascavo features ultra-detailed, custom highlighting for anchors (`^$`), quantifiers (`*+?`), character classes, and lookahead assertions.
- **Beautiful Markdown:** Writing documentation is a joy. Headings, bold/italic text, quotes, and fenced code blocks are meticulously styled to look like a fully formatted document right in your editor.
- **Clean JSON:** JSON keys remain clean and straight, while distinct colors make nested data structures easy to scan.
- **Unobtrusive Punctuation:** Brackets, commas, and equal signs are dimmed using semi-transparent colors, pushing the structural noise to the background and bringing your actual code to the forefront.

## ⚙️ Recommended Settings

For the best experience, ensure Semantic Highlighting is enabled in your `settings.json`, and pair the theme with a good coding font with ligatures (like Fira Code or JetBrains Mono):

```json
{
  "editor.semanticHighlighting.enabled": true,
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', Consolas, monospace",
  "editor.fontLigatures": true,
  "editor.bracketPairColorization.enabled": true
}
```
