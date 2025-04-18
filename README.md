# TermuXify

Terminal customization tool for Termux

## Installation

> [!NOTE]\
> Method 1 is recommended for better experience and easier updates.

### Method 1: Using apt/pkg (Recommended)
```bash
# Add the apt repository
echo "deb [trusted=yes] https://ayanrajpoot10.github.io/termuxify/ stable main" >> $PREFIX/etc/apt/sources.list

# Install termuxify
pkg install termuxify
```

### Method 2: Quick install
```bash
curl -sL https://raw.githubusercontent.com/Ayanrajpoot10/termuxify/main/install.sh | bash
```

After installation, you can run termuxify from anywhere by typing:
```bash
termuxify
```

## Features

### Appearance
- **Font Customization**: Size and style options
- **Color Schemes**: Professional presets including Dark, Light, Solarized themes
- **Cursor Styling**: Choose from block, underline, or bar

### Configuration
- **MOTD**: Customize your Message of the Day

### Management
- **Alias System**: Create and manage terminal shortcuts
