# Viewing Marp Presentations

There are several ways to view the Marp presentations in this folder:

## 1. Using Visual Studio Code (Recommended)

1. Install the "Marp for VS Code" extension
2. Open the `.md` presentation file
3. Click on the "Open Preview to the Side" button (or press `Cmd/Ctrl + K V`)
4. For presentation mode, click on the "Open Preview" button in the top-right corner

## 2. Using Marp CLI

1. Install Marp CLI globally:
   ```bash
   npm install -g @marp-team/marp-cli
   ```

2. Generate HTML:
   ```bash
   marp agentic-workflows.md
   ```

3. Start presentation server:
   ```bash
   PORT=3000 marp -s .
   #marp -s agentic-workflows.md
   ```

## 3. Using Marp Web Interface

You can also use the online Marp editor at https://web.marp.app/
Just copy and paste the content of the .md file into the editor.

## Export Options

To export the presentation to PDF or other formats using Marp CLI:

```bash
# Export to PDF
marp agentic-workflows.md --pdf

# Export to PowerPoint
marp agentic-workflows.md --pptx

# Export to HTML
marp agentic-workflows.md --html
```
