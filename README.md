## Customize Chia Icon File

1. Install [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
2. Download Chia file icon
![chia](images/chia.svg)
```sh
❯ curl https://raw.githubusercontent.com/kimsk/chia-settings/main/images/chia.svg -o chia.svg
```
> This is a smaller version of a file you find in https://github.com/Chia-Network/chia-dev-guides/blob/main/static/img/chia_leaf_green.svg

3. Update User Settings and point to the file location (relative to material-icon-theme extension `icons` folder)

![material-icon-chia](images/material-icon-chia.png)
```json
"workbench.iconTheme": "material-icon-theme",
"material-icon-theme.files.associations": {
    "*.clsp": "../../icons/chia",
    "*.clib": "../../icons/chia",
    "*.clvm": "../../icons/chia",
    "*.clinc": "../../icons/chia"
},
```
4. Material Icon Screenshot
![material-icon](images/material-icon-screenshot.png)