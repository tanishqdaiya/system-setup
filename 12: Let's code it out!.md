# [Visual Studio Code](https://code.visualstudio.com/)

> ## Code editing.
>
> ## Redefined.

# Installation

## Via Snap

```bash
$ sudo snap install code --classic # To Install via Snap
```

## Via Flatpak

```bash
$ sudo pacman -S flatpak # To install flatpak
$ flatpak install flathub com.visualstudio.code # To install Visual Studio Code
```



# Configuration

## Install these packages

- `stevencl.adddoccomments`

- `mikael.angular-beastcode`

- `angular.ng-template`

- `coenraads.bracket-pair-colorizer-2`

- `naumovs.color-highlight`

- `ms-azuretools.vscode-docker`

- `dsznajder.es7-react-js-snippets`

- `dbaeumer.vscode-eslint`

- `codezombiech.gitignore`

- `graphql.vscode-graphql*Preview*`

- `kumar-harsh.graphql-for-vscode`

- `ms-vscode.vscode-typescript-next`

- `vintharas.learn-vim` IF YOU WANT TO LEARN VIM

- `ms-vsliveshare.vsliveshare`

- `pkief.material-icon-theme` or `vscode-icons-team.vscode-icons`

- `nrwl.angular-console`

- `esbenp.prettier-vscode`

- `vscodevim.vim`

  These all are my personal preferences to get started

## Fonts

1. Go to settings <kbd>Ctrl</kbd> + <kbd>,</kbd>
2. Change the `Editor: Font Size` to 16 atleast
3. Change the Editor: Font Family to `Menlo, Monaco, 'Courier New', monospace` and yes, you have to install some of these fonts
4. Search `zoom` and you will see an option `Editor: Mouse Wheel Zoom` and enable it.

## Prettier Configuration

1. Go to settings <kbd>Ctrl</kbd> + <kbd>,</kbd>
2. Search `formatonsave` and enable it
3. Search `default formatter` and choose `Prettier`
4. I prefer single quotes everywhere, do whatever you please.

# Wanna speed things up?

Take my `settings.json` and paste it in your `settings.json` in vs code

[In case you don't know how to do it](https://www.google.com/search?q=how+to+open+settings.json+in+vscode)

```json
{
	"workbench.iconTheme": "material-icon-theme",
	"editor.fontSize": 16,
	"editor.fontFamily": "Menlo, Monaco, 'Courier New', monospace",
	"files.exclude": {
		"**/node_modules": true
	},
	"terminal.integrated.fontFamily": "'NotoSansMono Nerd Font'",
	"editor.mouseWheelZoom": true,
	"editor.formatOnSave": true,
	"javascript.updateImportsOnFileMove.enabled": "always",
	"prettier.arrowParens": "avoid",
	"prettier.jsxSingleQuote": true,
	"prettier.singleQuote": true,
	"prettier.useTabs": true,
	"[html]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"[javascript]": {
		"editor.defaultFormatter": "esbenp.prettier-vscode"
	},
	"eslint.format.enable": true,
	"prettier.documentSelectors": [".ts", ".html"],
	"editor.defaultFormatter": "esbenp.prettier-vscode",
	"typescript.updateImportsOnFileMove.enabled": "always",
	"vim.hlsearch": true,
	"vim.handleKeys": {
		"<C-c>": false,
		"<C-v>": false
	},
	"material-icon-theme.activeIconPack": "react_redux",
	"window.zoomLevel": 2
}
```

