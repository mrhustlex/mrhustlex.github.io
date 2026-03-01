# Open Claw Bot - Agent Recipes Repository

A collection of agent recipes for the Open Claw Bot automation system.

## About

This repository serves as a central hub for Open Claw Bot recipes - step-by-step instructions that agents can read and execute. Each recipe provides clear prompts, dependencies, code examples, and expected outputs.

## Structure

```
/
├── index.html                      # Homepage
├── recipes.html                    # Recipes listing page
├── recipes/                        # Individual recipe pages
│   ├── ai-cv-generator.html       # Interactive tool
│   └── yahoo-finance-downloader.html  # Step-by-step recipe
├── about.html                      # About the creator
└── README.md
```

## Adding New Recipes

1. Create a new HTML file in the `recipes/` directory
2. Use `recipes/yahoo-finance-downloader.html` as a template for instruction-based recipes
3. Add a recipe card to `recipes.html`
4. Include:
   - Clear bot prompt example
   - Required dependencies
   - Step-by-step instructions with code
   - Expected output
   - Error handling guidance

## Recipe Format

Each recipe should include:
- **Bot Prompt**: Example of what user would say to trigger this recipe
- **Dependencies**: Required packages/tools
- **Step-by-Step Instructions**: Clear, executable code blocks
- **Complete Example**: Full working script
- **Expected Output**: What the result should look like
- **Error Handling**: Common issues and solutions

## Local Development

Simply open `index.html` in your browser. No build process required!

## Deployment

This site is automatically deployed via GitHub Pages.

## License

MIT License - See individual recipe repositories for their licenses.
