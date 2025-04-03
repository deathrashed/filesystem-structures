# Linux-Based File Structure

<div align="center">
  
  [![Platform](https://img.shields.io/badge/Platform-Linux-orange?style=for-the-badge&logo=linux)](https://github.com/username/filesystem-structures)
  [![Standard](https://img.shields.io/badge/Standard-XDG_Base_Directory-blue?style=for-the-badge)](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html)
  [![Target User](https://img.shields.io/badge/For-Linux_Users_&_Developers-green?style=for-the-badge)](https://github.com/username/filesystem-structures)
  [![Complexity](https://img.shields.io/badge/Complexity-Medium-yellow?style=for-the-badge)](https://github.com/username/filesystem-structures)

  **A filesystem organization structure that follows Linux conventions and freedesktop.org standards, providing a clean separation between configuration, applications, and user data.**
</div>

## 🌟 Key Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧰 Structure Highlights</h3>
      <ul>
        <li><b>XDG Compliance</b> - Follows freedesktop.org specifications for base directories</li>
        <li><b>Dotfiles Organization</b> - Clean management of configuration files</li>
        <li><b>Hidden/Visible Separation</b> - Proper use of hidden directories for configs</li>
        <li><b>Linux Conventions</b> - Adherence to Linux filesystem standards</li>
        <li><b>Development-Ready</b> - Organized for programming and system administration</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🎯 Perfect For</h3>
      <ul>
        <li>Linux desktop and server users</li>
        <li>Developers and system administrators</li>
        <li>Open source contributors</li>
        <li>Multi-user systems with separate home directories</li>
        <li>Users who value Linux filesystem standards</li>
        <li>DevOps professionals working with containerization</li>
        <li>Rice enthusiasts customizing their Linux environment</li>
      </ul>
    </td>
  </tr>
</table>

## 📂 Directory Structure

<details>
<summary><b>Visible Directories</b> - User content and projects</summary>
<ul>
  <li><b>dev/</b> - Development and programming projects
    <ul>
      <li>Organized by project or language</li>
      <li>Perfect for git repositories</li>
      <li>Separate from configuration files</li>
    </ul>
  </li>
  <li><b>documents/</b> - Text documents, spreadsheets, and other files
    <ul>
      <li>Personal and work documents</li>
      <li>Reference materials</li>
      <li>Text files and PDFs</li>
    </ul>
  </li>
  <li><b>downloads/</b> - Downloaded files
    <ul>
      <li>Web browser downloads</li>
      <li>Package files</li>
      <li>External content</li>
    </ul>
  </li>
  <li><b>music/</b> - Audio files and music collection
    <ul>
      <li>Music library</li>
      <li>Playlists</li>
      <li>Audio recordings</li>
    </ul>
  </li>
  <li><b>pictures/</b> - Images and photos
    <ul>
      <li>Personal photos</li>
      <li>Screenshots</li>
      <li>Graphic files</li>
    </ul>
  </li>
  <li><b>scripts/</b> - Executable scripts and automation
    <ul>
      <li>Shell scripts</li>
      <li>Utility scripts</li>
      <li>Automation tools</li>
    </ul>
  </li>
  <li><b>videos/</b> - Video files
    <ul>
      <li>Movies</li>
      <li>Recorded videos</li>
      <li>Video projects</li>
    </ul>
  </li>
</ul>
</details>

<details>
<summary><b>Hidden Directories</b> - Configuration and application data</summary>
<ul>
  <li><b>.cache/</b> - Non-essential cached data
    <ul>
      <li>Application caches</li>
      <li>Temporary data that can be regenerated</li>
    </ul>
  </li>
  <li><b>.config/</b> - User configuration files
    <ul>
      <li><b>alacritty/</b> - Terminal emulator configuration</li>
      <li><b>dunst/</b> - Notification daemon configuration</li>
      <li><b>gtk-3.0/</b> - GTK3 theming and configuration</li>
      <li><b>i3/</b> - i3 window manager configuration</li>
      <li><b>mpv/</b> - Media player configuration</li>
      <li><b>nvim/</b> - Neovim editor configuration</li>
      <li><b>picom/</b> - Compositor configuration</li>
      <li><b>polybar/</b> - Status bar configuration</li>
      <li><b>ranger/</b> - File manager configuration</li>
      <li><b>rofi/</b> - Application launcher configuration</li>
    </ul>
  </li>
  <li><b>.local/</b> - User-specific data and applications
    <ul>
      <li><b>bin/</b> - User executables
        <ul>
          <li>Personal scripts</li>
          <li>User-installed binaries</li>
        </ul>
      </li>
      <li><b>share/</b> - User application data
        <ul>
          <li>Application-specific data</li>
          <li>Themes</li>
          <li>Icons</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>
</details>

## 🔄 XDG Base Directory Standard

This structure follows the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html), which defines standard locations for user-specific files:

<table>
  <tr>
    <th>Environment Variable</th>
    <th>Directory</th>
    <th>Purpose</th>
  </tr>
  <tr>
    <td><code>$XDG_CONFIG_HOME</code></td>
    <td><code>~/.config</code></td>
    <td>User-specific configuration files</td>
  </tr>
  <tr>
    <td><code>$XDG_CACHE_HOME</code></td>
    <td><code>~/.cache</code></td>
    <td>User-specific non-essential (cached) data</td>
  </tr>
  <tr>
    <td><code>$XDG_DATA_HOME</code></td>
    <td><code>~/.local/share</code></td>
    <td>User-specific data files</td>
  </tr>
  <tr>
    <td><code>$XDG_STATE_HOME</code></td>
    <td><code>~/.local/state</code></td>
    <td>User-specific state files</td>
  </tr>
  <tr>
    <td><code>$XDG_RUNTIME_DIR</code></td>
    <td>Varies (often <code>/run/user/$UID</code>)</td>
    <td>Runtime files and objects (sockets, etc.)</td>
  </tr>
</table>

## 💡 Implementation Tips

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔧 Getting Started</h3>
      <p>Basic setup commands:</p>
      <pre>
#!/bin/bash
# Create basic Linux directory structure

# Create visible directories
mkdir -p ~/{dev,documents,downloads,music,pictures,scripts,videos}

# Create hidden directories
mkdir -p ~/.config
mkdir -p ~/.local/{bin,share}
mkdir -p ~/.cache

# Ensure ~/.local/bin is in PATH
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc

echo "Basic Linux directory structure created!"
      </pre>
    </td>
    <td width="50%" valign="top">
      <h3>⚙️ Dotfiles Management</h3>
      <p>For configuration management:</p>
      <ul>
        <li><b>GNU Stow</b> - Symlink farm manager for dotfiles</li>
        <li><b>Chezmoi</b> - Securely manage dotfiles across multiple machines</li>
        <li><b>Bare Git Repository</b> - Use git directly for dotfile management</li>
        <li><b>Ansible</b> - For more complex environment setup</li>
        <li><b>Shell Scripts</b> - Custom scripts for setup and synchronization</li>
      </ul>
      <p>Example with GNU Stow:</p>
      <pre>
# Organize configs in ~/dotfiles
mkdir -p ~/dotfiles/{bash,nvim,i3}

# Move configurations
mv ~/.config/nvim ~/dotfiles/nvim/
mv ~/.config/i3 ~/dotfiles/i3/

# Create proper directory structure
mkdir -p ~/dotfiles/nvim/.config
mv ~/dotfiles/nvim/nvim ~/dotfiles/nvim/.config/

# Use stow to create symlinks
cd ~/dotfiles
stow nvim   # Creates ~/.config/nvim symlink
stow i3     # Creates ~/.config/i3 symlink
      </pre>
    </td>
  </tr>
</table>

## 🔍 Linux vs. Other Systems

<details>
<summary><b>Comparison with macOS</b></summary>
<p>Key differences from macOS:</p>
<ul>
  <li><b>Hidden Files</b> - Linux uses dot prefix (.filename) for hidden files</li>
  <li><b>Configuration</b> - macOS uses ~/Library while Linux uses ~/.config</li>
  <li><b>Applications</b> - macOS has /Applications while Linux uses /usr/bin or ~/.local/bin</li>
  <li><b>Case Sensitivity</b> - Linux filesystems are typically case-sensitive</li>
  <li><b>Path Separators</b> - Both use forward slashes but with different root structures</li>
</ul>
</details>

<details>
<summary><b>Comparison with Windows</b></summary>
<p>Key differences from Windows:</p>
<ul>
  <li><b>Path Separators</b> - Linux uses forward slashes (/) instead of backslashes (\\)</li>
  <li><b>Drive Letters</b> - Linux uses mount points instead of drive letters</li>
  <li><b>User Directories</b> - Windows uses C:\\Users\\username vs. Linux's /home/username</li>
  <li><b>Configuration</b> - Windows uses Registry and AppData while Linux uses dotfiles</li>
  <li><b>Extensions</b> - Linux doesn't rely on extensions for file type associations</li>
</ul>
</details>

## ✨ Key Advantages

1. **Clean Configuration** - Well-organized dotfiles and configuration
2. **Standard Compliance** - Follows established Linux conventions
3. **Portability** - Easy to synchronize across different Linux machines
4. **Development Focus** - Optimized for programming and system administration
5. **Customization Friendly** - Perfect for Linux ricing and customization
6. **Multi-User Ready** - Designed for systems with multiple users
7. **Version Control Compatible** - Easily manage configuration with git

## 🔧 Environment Configuration

<details>
<summary><b>Shell Profile Setup</b></summary>
<p>Key files to configure:</p>
<ul>
  <li><b>~/.bashrc</b> - Bash configuration for interactive shells</li>
  <li><b>~/.bash_profile</b> - Executed for login shells</li>
  <li><b>~/.zshrc</b> - Configuration for Zsh shell</li>
  <li><b>~/.profile</b> - Generic shell profile for any shell</li>
</ul>

<p>Recommended environment variables:</p>

```bash
# XDG Base Directory
export XDG_CONFIG_HOME="$HOME/.config"
export XDG_CACHE_HOME="$HOME/.cache"
export XDG_DATA_HOME="$HOME/.local/share"
export XDG_STATE_HOME="$HOME/.local/state"

# Ensure user binaries are in PATH
export PATH="$HOME/.local/bin:$PATH"

# Default applications
export EDITOR="nvim"
export VISUAL="nvim"
export TERMINAL="alacritty"
export BROWSER="firefox"
```
</details>

<details>
<summary><b>Window Manager Configuration</b></summary>
<p>For tiling window managers like i3:</p>

```bash
# Create necessary directories
mkdir -p ~/.config/i3
mkdir -p ~/.config/polybar
mkdir -p ~/.config/dunst
mkdir -p ~/.config/picom

# Create starter configurations
cp /etc/i3/config ~/.config/i3/
touch ~/.config/polybar/config.ini
touch ~/.config/dunst/dunstrc
touch ~/.config/picom/picom.conf

# Configure autostart
mkdir -p ~/.config/autostart
```
</details>

## 📝 Migration Tips

- **Start with Configuration** - Begin by organizing your dotfiles in ~/.config
- **Move Gradually** - Transition one directory at a time rather than all at once
- **Fix Paths** - Update paths in configuration files after moving them
- **Test Startup** - Verify that applications find their configuration in new locations
- **Script It** - Create scripts to automate future machine setup
- **Track in Git** - Use version control for your configuration

## 🛠️ Recommended Tools

- **Stow** - Symlink management for dotfiles
- **Ranger** - File manager that respects XDG directories
- **RipGrep** - Fast file searching that respects .gitignore
- **fd** - Alternative to find that respects .gitignore
- **Neovim** - Modern Vim distribution with good XDG support
- **tmux** - Terminal multiplexer with dotfile configuration
- **Zsh** - Shell with advanced customization options
- **Chezmoi** - Advanced dotfile management across machines

---

<div align="center">
  <p><i>"A home directory is a reflection of its user."</i></p>
  <p><a href="../Structure%2010%20-%20Deep%20Hierarchy">← Deep Hierarchy Structure</a> | <a href="../Structure%201%20-%20Basic">Basic Structure →</a></p>
</div>
