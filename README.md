# ghost
A spooky, vibe-coded CLI tool to run Go tests.
Uses fzf, rg, fd, and gotestsum to interactively select and run Go tests.

## Installation
```bash
git clone https://github.com/cdkini/ghost.git
cd ghost
chmod +x ghost
mv ghost ~/bin/  # or anywhere in your PATH
```

## Usage
```bash
ghost                    # Interactive test picker
ghost ./...              # Run all tests
ghost TestSomething      # Run tests matching pattern
ghost path/to/pkg        # Run tests in directory
```

- `Tab` to select tests
- `Ctrl-A` to select all
- `Enter` to run

