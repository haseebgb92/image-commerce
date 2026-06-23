# Image Commerce Plugin

This repository contains the **Image Commerce Realism Skill**, a globally installable Antigravity/Codex plugin designed to act as an expert Amazon, Etsy, Shopify, KDP, and A+ Content image planning and prompt-generation assistant.

It reverse-engineers product specifications and creates highly realistic, conversion-focused product image plans and prompts. The plugin operates using an isolated subagent so that it seamlessly triggers only when you are working on product image generation.

## Features

- **Product Reverse Engineering**: Analyzes and extracts detailed dimensions, materials, and features from product references.
- **Universal Category Support**: Custom logic for cosmetics, home goods, food packaging, electronics, apparel, and more.
- **Marketplace Safety Compliance**: Enforces safe padding, Amazon's pure white background rules, Etsy's lifestyle standards, and A+ content specifications.
- **Subagent Architecture**: Isolates the specialized skill logic, activating automatically via the `image-commerce-agent` when needed.

## Installation

To install this plugin locally for your Antigravity Agent, clone this repository directly into your agent's plugins folder.

### macOS / Linux
```bash
git clone https://github.com/haseebgb92/image-commerce.git ~/.gemini/config/plugins/image-commerce-plugin
```

### Windows
```powershell
git clone https://github.com/haseebgb92/image-commerce.git "$env:USERPROFILE\.gemini\config\plugins\image-commerce-plugin"
```

## Usage

Once installed, there's no manual setup required. 
Simply open your agent and use prompts like:

- *"I need an image plan for a new skincare product. Can you trigger the image commerce subagent?"*
- *"Help me create some highly realistic Etsy lifestyle images for this ceramic vase set."*
- *"Generate A+ content image prompts based on this product's dimensions."*

The main agent will detect the plugin and invoke the specialized **Image Commerce Agent** to handle your request.

## Author

Created by Muhammad Haseeb.
