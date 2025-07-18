# releases

## About this repo

This repo is used for hosting public releases of Engram, as well as our community plugins & themes directories.

Engram is not open source software and this repo _does not_ contain the source code of Engram. However, if you wish to contribute to Engram, you can easily do so with our extensive plugin system. A plugin guide can be found here: https://docs.engramapp.com

## Submit your plugin or theme

When opening a pull request, please switch to preview mode and use our submission checklist to review your entry. You can submit your entry by following the convention in the JSON file and your submission will be reviewed by our team.

You can find a detailed explanation for submitting your [theme here](https://docs.engramapp.com/themes/build-a-theme/).

## Community Theme

To add your theme to our theme store, make a pull request to the `community-css-theme.json` file. Please add your theme to the end of the list.

- `name`: a unique name for your theme. Must not collide with other themes.
- `author`: the author's name for display.
- `repo`: the GitHub repository identifier, in the form of `user-name/repo-name`, if your GitHub repo is located at `https://github.com/user-name/repo-name`.
- `screenshot`: path to the screenshot of your theme.
- `modes`: if your theme supports both dark and light mode, put `["dark", "light"]`. Otherwise, put `["dark"]` if your theme only supports dark mode, or  `["light"]` if your theme only supports light mode.

## Policies

All submissions must conform with our [developer policies](https://docs.engramapp.com/developer-policy/)