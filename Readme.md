# `Open in vscode` option for Nemo

![Preview picture of context menu](test.png)

Nemo, the cinnamon DE (Desktop Environment) file manager, supports adding actions and scripts easily by adding a config file in `~/.local/share/nemo`.

So, for adding the `open in vscode` option, you just need to place the file `vscode.nemo_action` in the `actions` folder in the mentioned directory.

# Installation


```shell
sudo wget https://raw.githubusercontent.com/Justwouter/nemo-open-in-vscode-insiders/master/vscodeinsider.nemo_action -O ~/.local/share/nemo/actions/vscodeinsider.nemo_action
```

Or, clone this repository and run:

```shell
sudo cp nemo-open-in-vscode-insiders/vscodeinsider.nemo_action ~/.local/share/nemo/actions
```
