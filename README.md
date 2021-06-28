<!-- TODO: Utilize same structure as the vscode-theme repo with icon on top and descriptive steps -->
<h1 align="center">
  <br>
  <img src="assets/img/icon.png" alt="404 theme" width="100">
  <br>
  404 theme for <a href="https://www.microsoft.com/pt-br/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab">Windows Terminal</a>
  <br>
</h1>

<p align="center">
  <strong>Neon colors inspired theme with strong variants</strong>
</p>

<p align="center">
  <a href="#install">Install</a> •
  <a href="#license">License</a>
</p>

<p align="center">
  <img alt="Purple Daze Preview Screenshot" src="assets/img/purple-daze-terminal.png">
</p>

## Install

All instructions can be found at [INSTALL.md](./INSTALL.md).

## License

[MIT License](./LICENSE.md)

## Override this theme

To quickly test something, you can also override this (or any other) theme in your personal config file. Please follow the guide in the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation.

## Publish (internal)

> Note: Publishing a new version of this theme is only meant for maintainers.

**Prerequisite**: Please follow this [guide](https://code.visualstudio.com/api/working-with-extensions/publishing-extension) to install and login to `vsce`. Ask an existing maintainer how to get the "Personal Access Token".

1. Merge any PR that is ready to be published into `main`.
2. Perform all the necessary changes following code structure and folder organization.
3. Update [CHANGELOG.md](https://github.com/404-theme/visual-studio-code/blob/master/CHANGELOG.md) + commit the changes.
4. Run `vsce publish [version]`. Follow the [SemVer](https://semver.org) convention and replace `[version]` with one of the following options:
   - `patch` for bug fixes
   - `minor` for improvements
   - `major` for breaking or bigger changes
5. Push the commits and make a [new release](https://github.com/404-theme/visual-studio-code/releases/new).
