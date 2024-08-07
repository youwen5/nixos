# liminalOS

This is a repository that implements liminalOS, my personal Linux distribution based on [NixOS](https://nixos.org/).

## Installation guide

TBD. May use `deploy-rs` or the in-house [dartgun](https://github.com/youwen5/dartgun) tool for easy deployment.

## FAQ

### This looks like a collection of NixOS configuration files and modules. What makes it a distinct distribution?

Most Linux[^1] users will agree that any self-respecting distribution must include at least the following: installer, package manager, and some set of default packages. Therefore, anything that implements the aforementioned items must also be a Linux distribution.

liminalOS comes with the Nix package manager (nothing says you need _a unique_ package manager. Ubuntu and Debian are distinct distributions yet both use `apt`), the Hyprland desktop environment as well as various applications installed by default, and [the means to generate an installer](https://nixos.wiki/wiki/Creating_a_NixOS_live_CD). Therefore, liminalOS is a Linux distribution. QED.[^2]

### Should I actually install this?

No.

[^1]: also known as GNU/Linux, GNU+Linux, Freedesktop/systemd/musl/busybox Linux, Linux+friends, etc

[^2]: disclaimer: this is unfortunately not actually how the converse works. $A \implies B$ does not necessarily imply $B \implies A$. I hope this satiates the rigor-hungry mathematicians reading.

## Keybinds

| Shortcut                                                                                                 | Action                           |
| -------------------------------------------------------------------------------------------------------- | -------------------------------- |
| <kbd>Super</kbd> + <kbd>W</kbd>                                                                          | Toggle floating                  |
| <kbd>Super</kbd> + <kbd>J</kbd>                                                                          | Toggle layout                    |
| <kbd>Super</kbd> + <kbd>E</kbd>                                                                          | Open Dolphin                     |
| <kbd>Super</kbd> + <kbd>T</kbd>                                                                          | Open kitty                       |
| <kbd>Super</kbd> + <kbd>F</kbd>                                                                          | Open librewolf                   |
| <kbd>Super</kbd> + <kbd>R</kbd>                                                                          | Open pavucontrol                 |
| <kbd>Super</kbd> + <kbd>Space</kbd>                                                                      | Open rofi                        |
| <kbd>Super</kbd> + <kbd>Backspace</kbd>                                                                  | Open logout menu                 |
| <kbd>Super</kbd> + <kbd>P</kbd>                                                                          | Screenshot region                |
| <kbd>Super</kbd> + <kbd>Y</kbd><kbd>U</kbd><kbd>I</kbd><kbd>O</kbd>                                      | Move around                      |
| <kbd>Super</kbd> + <kbd>Ctrl</kbd> + <kbd>Y</kbd><kbd>O</kbd>                                            | Move workspaces                  |
| <kbd>Super</kbd> + <kbd>Alt</kbd> + <kbd>Ctrl</kbd> + <kbd>Y</kbd><kbd>U</kbd><kbd>I</kbd><kbd>O</kbd>   | Move windows around workspaces   |
| <kbd>Super</kbd> + <kbd>Shift</kbd> + <kbd>Ctrl</kbd> + <kbd>Y</kbd><kbd>U</kbd><kbd>I</kbd><kbd>O</kbd> | Move windows around              |
| <kbd>Super</kbd> + <kbd>S</kbd>                                                                          | Open Special Workspace           |
| <kbd>Super</kbd> + <kbd>Enter</kbd>                                                                      | Fullscreen Window                |
| <kbd>Super</kbd> + <kbd>Alt</kbd> + <kbd>S</kbd>                                                         | Move Window to Special Workspace |
