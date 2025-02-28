# Updating Magnolia CLI to Version 5

To update your Magnolia CLI from version 4 to version 5, follow these steps:

1. First, uninstall the old version of Magnolia CLI:

If you installed via npm:
```bash
npm uninstall -g magnolia-cli
```

If you installed via Homebrew:
```bash
brew uninstall magnolia-cli
```

2. Install the new Magnolia CLI v5:
```bash
npm install -g @magnolia/cli
```

3. Verify the installation:
```bash
mgnl -v
```

You should now see that you're running Magnolia CLI version 5.x.x

## Note
- The new Magnolia CLI v5 is published under the package name `@magnolia/cli` instead of the old `magnolia-cli`
- Make sure you have Node.js installed on your system
- You might need to use `sudo` on Unix-based systems if you encounter permission errors
- If you previously used Homebrew, note that we're switching to npm as the package manager for Magnolia CLI v5
