# RTBF Auvio
Kodi plugin to stream content from the RTBF Auvio website (public broadcasting organization of the French Community of Belgium)
For feature requests / issues:
https://github.com/rickybiscus/plugin.video.auvio/issues
Contributions are welcome:
https://github.com/rickybiscus/plugin.video.auvio

## Features
* Main menu : 'En direct', 'Accueil', 'Chaînes', 'Catégories', 'Mon Auvio'
* Stream live videos and radios, video replays and audio podcasts

## Installation
* Navigate to your `.kodi/addons/` folder
* Clone this repository: `git clone https://github.com/rickybiscus/plugin.video.auvio.git`
* Install the dependencies
```
wget -q https://mirrors.kodi.tv/addons/krypton/script.module.dateutil/script.module.dateutil-2.7.3.zip
wget -q https://mirrors.kodi.tv/addons/krypton/script.module.unidecode/script.module.unidecode-0.4.16.zip
wget -q https://mirrors.kodi.tv/addons/krypton/script.module.six/script.module.six-1.11.0.zip
for z in *.zip; do unzip $z; rm $z; done
```
* (Re)start Kodi.

## TODO

## License
See the `LICENSE` file.

Additional copyright notices:
* [SimplePlugin](https://github.com/romanvm/script.module.simpleplugin/stargazers) by romanvm
* [Python Slugify](https://github.com/un33k/python-slugify) by un33k