# aido

> Stop opening AI chatbots, Google, or SO just to remember one command

aido is your one-shot CLI tool. Describe what you need. Instant help. Stay in flow.

```
$ aido what listens on port 8080
$ aido extract archive.tgz
$ aido clear logs in cwd
```

Without it, you'd open a browser, a chat, or Stack Overflow just to remember the exact syntax.

```
$ lsof -i :8080
$ tar xzf archive.tar.gz
$ find . -name "*.log" -delete
```

That context switch costs you. And getting back into flow costs you again.

The same task looks different depending on where you are:

```
  $ find . -name "*.log" -delete
  > del /s /q *.log
PS> Get-ChildItem -Recurse -Filter *.log | Remove-Item
```

aido works on macOS, Linux, and Windows — one command, any shell.

## Install aido

1. Download the binary from [https://github.com/secondfry/aido/releases](https://github.com/secondfry/aido/releases)

2. **macOS users only:** Remove quarantine attribute:
   ```bash
   xattr -d com.apple.quarantine ./aido_*_darwin_*
   ```

3. Run it in your CLI.

4. Get your API key from [https://aido.secondfry.com](https://aido.secondfry.com) (sign in via GitHub)

## Issues

Found a bug or have a feature request? Open an issue.
