# 🌊 Vibe System Builder

The ultimate AI Skill for "vibe coders" using Claude Code, Cursor, Windsurf, or Antigravity. 

Stop settling for generic, centered, purple-gradient "AI slop." This skill transforms your AI agent into an opinionated frontend design engineer that extracts real design systems, enforces exact component semantics, and layers on premium Framer Motion animations.

## ✨ Features

- **Live Design System Extraction**: Feed it a URL or a screenshot, and it will extract the exact color palette, typography, spacing, and motion principles into a reusable design token document.
- **Canonical Component Naming**: Forces the AI to stop inventing HTML and start using precise `shadcn/ui` and `Radix` primitives (e.g., `<Dialog>`, `<Accordion>`, `<InputOTP>`) based on `component.gallery` standards.
- **Built-in Boilerplate**: Includes instant templates for complex components, including Recharts (Line, Bar, Area, Pie) and Forms.
- **Premium Motion Design**: Built-in `framer-motion` variants (springs, staggers, and fade-ins) to give your UI a polished, interactive feel.
- **Strict Anti-Slop Rules**: Hardcoded instructions to prevent symmetric layouts, raw divs for interactive elements, and default generic styling.

## 📦 Installation

We've included automated scripts to install the skill directly into your local AI agent environments.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/vibe-system-builder.git
   cd vibe-system-builder
   ```

2. Run the install script for your environment:

### For Claude Code / Cursor / Windsurf:

```bash
npm run install:claude
```

### For Antigravity:

```bash
npm run install:antigravity
```

> **Note:** These scripts will create the necessary `.skills` folders in your home directory and copy the `SKILL.md` and `references/` folder over.

## 🚀 Usage

Once installed, restart your AI IDE or agent. You can now prompt it with highly specific vibe requests:

### Example 1: URL Extraction & Generation

```
"Extract the design system from linear.app. Using that exact vibe, build me a settings dashboard using our local shadcn templates and staggered Framer Motion entrances."
```

### Example 2: Using Built-in Vibes

```
"Build a pricing page using our pre-defined 'bento-modern' vibe definitions. Ensure all interactive cards use the springHover motion variant."
```

### Example 3: Screenshot Fallback

```
(Upload an image) "Use the Vibe System Builder to infer the design tokens from this screenshot, then build me a sleek login form with Radix primitives."
```

## 📁 Repository Architecture

- **SKILL.md** – The core brain and system prompt for the AI agent.
- **VIBE_CHECKLIST.md** – A quick-reference guide to ensure your generated UIs pass the "anti-slop" test.
- **references/vibe-definitions.json** – Custom, pre-defined CSS rules and motion specs for specific aesthetics (e.g., linear-clean, bento-modern).
- **references/components.json** – The canonical vocabulary list from component.gallery to prevent AI hallucinations.
- **references/shadcn-radix-templates.json** – Copy-paste ready code for complex frontend patterns.
- **references/framer-motion-variants.json** – Standardized, smooth animation physics.
