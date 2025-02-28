---
marp: true
theme: default
paginate: true
backgroundColor: white
style: |
  section {
    font-family: 'Inter', 'Arial', sans-serif;
    font-size: 16px;
    padding: 40px;
    background-color: white;
    color: #1B1B3D;
  }
  .columns {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 24px;
    margin-top: 1em;
  }
  .tool-card {
    background: #F5F5F5;
    padding: 16px;
    border-radius: 8px;
    font-size: 14px;
    box-shadow: 0 2px 4px rgba(107, 45, 127, 0.05);
    transition: all 0.2s ease;
    border: 1px solid #1B1B3D10;
  }
  .tool-card:hover {
    transform: translateY(-2px);
    box-shadow: 0 4px 8px rgba(107, 45, 127, 0.1);
    background: white;
  }
  .tool-card h3 {
    color: #6B2D7F;
    font-size: 20px;
    margin: 0 0 8px 0;
    font-weight: 600;
  }
  .tool-card em {
    font-size: 12px;
    display: block;
    margin-bottom: 12px;
    background: none;
    padding: 0;
  }
  .tool-card ul {
    margin: 0;
    padding-left: 1em;
  }
  .tool-card li {
    margin: 0.2em 0;
    font-size: 14px;
    line-height: 1.4;
  }
  .price-tag {
    border-top: 1px solid #1B1B3D20;
    font-size: 12px;
    color: #6B2D7F;
    font-weight: 500;
    background: #6B2D7F10;
    margin: 12px -16px -16px;
    padding: 8px 16px;
    border-radius: 0 0 8px 8px;
  }
  h1 {
    color: #6B2D7F;
    font-size: 32px;
    margin: 0 0 0.5em;
    font-weight: 600;
  }
  h2 {
    color: #1B1B3D;
    font-size: 24px;
    margin: 0.3em 0;
    font-weight: 500;
  }
  ul, ol {
    margin: 0.5em 0;
    padding-left: 1.2em;
  }
  li {
    margin: 0.3em 0;
    font-size: 16px;
    line-height: 1.5;
  }
  li > ul, li > ol {
    margin: 0.2em 0;
    padding-left: 1em;
    color: #1B1B3D99;
  }
  code {
    font-size: 14px;
    background-color: #F5F5F5;
    padding: 0.2em 0.4em;
    border-radius: 4px;
  }
  p {
    font-size: 16px;
    margin: 0.5em 0;
    line-height: 1.5;
  }
  a {
    color: #6B2D7F;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  strong {
    color: #6B2D7F;
    font-weight: 600;
  }
  em {
    color: #1B1B3D;
    font-style: normal;
    background-color: #F5F5F5;
    padding: 0.1em 0.3em;
    border-radius: 3px;
    font-size: 0.9em;
  }
  section::after {
    color: #6B2D7F80;
    font-size: 12px;
  }
  img {
    border-radius: 4px;
  }
---

# Agentic workflows: the case of Junie
## A hands-on session on modern development workflows

- Understanding AI-powered development
- Practical workshops with Magnolia and Sanity
- 50 minutes of hands-on experience

---

# What are Agentic Workflows?

- AI agents that understand context and goals
- Autonomous problem-solving capabilities
- Integration with development tools
- **Junie**: A specialized agent for development workflows

---

# AI Tools for Developers Today

Modern AI-powered assistants that enhance developer productivity and code quality.

<div class="columns">
<div class="tool-card">

### JetBrains Junie
*The intelligent companion for JetBrains IDEs*

- Project structure analysis
- Workflow optimization
- Smart code completion
- Code review assistance
- Documentation help

<div class="price-tag">
Free during Early Access
</div>
</div>

<div class="tool-card">

### Tabnine
*Privacy-focused AI assistant*

- Local-first processing
- Offline capabilities
- Multi-line completion
- Team learning
- IDE integration

<div class="price-tag">
Free Basic | Pro: $12/mo
</div>
</div>

<div class="tool-card">

### Codeium
*Ultra-fast coding assistant*

- Fast completions
- Natural language to code
- Code explanations
- Refactoring help
- Multi-language support

<div class="price-tag">
Free Personal | Team: $12/mo
</div>
</div>

<div class="tool-card">

### CodeGPT
*GPT-powered companion*

- Code generation
- Documentation
- Bug detection
- Test generation
- Code optimization

<div class="price-tag">
Free Tier | Pro: $10/mo
</div>
</div>
</div>

---

# Magnolia Light Dev Workshop (20')

## What we'll build
- Setting up a light development environment
- Creating a new Magnolia project
- Building custom components
- Integration with modern frontend tools

## Learning outcomes
- Understanding Magnolia's architecture
- Best practices for component development
- Efficient development workflow
- Real-time preview capabilities

---

# Sanity Workshop (20')

## Hands-on Experience
- Setting up Sanity Studio
- Creating content models
- Writing and testing GROQ queries
- Real-time content management

## Key Takeaways
- Modern content modeling approaches
- Headless CMS best practices
- Integration with frontend frameworks
- Collaborative content workflows

---

# Workshop Flow

## Time Distribution
- 10' Introduction to Agentic Workflows
- 20' Hands-on Magnolia Development
  - Setup: 5'
  - Development: 15'
- 20' Hands-on Sanity
  - Setup: 5'
  - Development: 15'

## Get Ready!
- Clone the workshop repository
- Have Node.js installed
- Docker for Magnolia
- Code editor of choice

---

# Resources & Next Steps

## Workshop Materials
- Repository: github.com/tea-agentic-workshops
- Documentation: [Magnolia](https://docs.magnolia-cms.com)
- Documentation: [Sanity](https://www.sanity.io/docs)

## Stay Connected
- Follow updates on Junie
- Join our developer community
- Share your feedback and experiences

Thank you! 🚀
