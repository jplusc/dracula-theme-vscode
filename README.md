### This is a personal clone of https://github.com/dracula/visual-studio-code/

The comments didn't quite have enough contrast for me -- probably due to my protan issue.
Otherwise, this is the same as dracula, just with a comment color tweak.


#### installing in VScode (windows):
```shell
git clone https://github.com/jplusc/dracula-theme-vscode.git %HOMEDRIVE%%HOMEPATH%\.vscode\extensions\theme-dracula
cd /d %HOMEDRIVE%%HOMEPATH%\.vscode\extensions\theme-dracula
npm install
npm run build
```

#### installing in VScode (linux):
```shell
$ git clone https://github.com/jplusc/dracula-theme-vscode.git ~/.vscode/extensions/theme-dracula
$ cd ~/.vscode/extensions/theme-dracula
$ npm install
$ npm run build
```

after the `npm build` you will have dracula.json under \theme\
and it can be selected from File -> Preferences -> Color Theme.  (Dracula and Dracula Soft)


#### missing git and/or npm for windows?
```shell
choco upgrade git -y
choco upgrade nodejs -y
```

#### missing choco?
Seriously, if you have to use windows, use a package manager to make it less painfull. https://chocolatey.org/

from powershell:
```shell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```



#### misc notes:
update your local copy:
```shell
cd /d %HOMEDRIVE%%HOMEPATH%\.vscode\extensions\theme-dracula
git pull
```
or if needed:
```shell
cd /d %HOMEDRIVE%%HOMEPATH%\.vscode\extensions\theme-dracula
git reset --hard
git pull
```
not showing up in vscode?
do you have one of the other clones of dracula installed? or even `Dracula Official`?
you'll have to uninstall it first since this uses the same name.
after uninstall, exist vscode and rebuild it so vscode sees it as new.





---

*original README.md follows:*

---



# Dracula for [Visual Studio Code](http://code.visualstudio.com)

> A dark theme for [Visual Studio Code](http://code.visualstudio.com).

![Screenshot](https://raw.githubusercontent.com/dracula/visual-studio-code/master/screenshot.png)

## Install

All instructions can be found at [draculatheme.com/visual-studio-code](https://draculatheme.com/visual-studio-code).

## Team

This theme is maintained by the following person(s) and a bunch of [awesome contributors](https://github.com/dracula/visual-studio-code/graphs/contributors).

[![Derek S.](https://avatars3.githubusercontent.com/u/5240018?v=3&s=70)](https://github.com/dsifford) |
:---: |
[Derek S.](https://github.com/dsifford) |

## Community

* [Twitter](https://twitter.com/draculatheme) - Best for getting updates about themes and new stuff.
* [GitHub](https://github.com/dracula/dracula-theme/discussions) - Best for asking questions and discussing issues.
* [Discord](https://draculatheme.com/discord-invite) - Best for hanging out with the community.

## Contributing

If you'd like to contribute to this theme, please read the [contributing guidelines](./.github/CONTRIBUTING.md).

## Dracula PRO

[![Dracula PRO](./dracula-pro.png)](https://draculatheme.com/pro)

## License

[MIT License](./LICENSE)