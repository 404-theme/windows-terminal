### [Windows Terminal](https://www.microsoft.com/pt-br/p/windows-terminal/9n0dx20hk701)

#### Install using Git

If you are a git user, you can install the theme by cloning the repo:

    $ git clone https://github.com/404-theme/windows-terminal.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/404-theme/windows-terminal/archive/refs/heads/main.zip) option and unzip them.

#### Activating theme

1. Start Windows Terminal.
2. Click on the down arrow icon and select "Settings" option or ctrl+shift+, keyboard shortcut
3. In the settings.json file, find the section called "Schemes" and paste the content of [purple_daze.json](./purple_daze.json) inside of [].
4. Find the profiles section and set a "colorScheme" value on the default profile as the example

```json
"profiles": {
    "defaults": {
        "colorScheme" : "Purple Daze"
    }
}
```
