# terminal-personal-website

This is my personal website but as a TUI

You can ssh into this by going to: `ssh terminal.mveilleux`


There you can see my website and some other cool stuff I have planned


# Basic Intitial File Structure
```
myproject/
├── cmd/
│   └── myapp/
│       └── main.go          # Entry point for your application
├── internal/
│   ├── config/              # Application configuration
│   │   └── config.go
│   ├── models/              # Your TUI models
│   │   ├── model.go         # Main application model
│   │   └── components/      # Reusable component models
│   │       ├── input.go
│   │       ├── list.go
│   │       └── status.go
│   ├── styles/              # LipGloss styles
│   │   └── styles.go
│   └── ui/                  # UI logic
│       ├── view.go          # View functions
│       └── update.go        # Update functions
├── pkg/                     # Reusable packages
│   └── util/
│       └── util.go
├── assets/                  # Static assets
│   └── help.txt
├── go.mod                   # Go module file
├── go.sum                   # Go module checksums
├── README.md                # Documentation
└── LICENSE                  # License information
```
# terminal-personal-website
# terminal-personal-website
# terminal-personal-website
