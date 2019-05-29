# SC2Layout schema

XML Schema of SC2Layout document from StarCraft II.

Used in:

* [VSC SC2Layout Extension](https://marketplace.visualstudio.com/items?itemName=talv.sc2layouts)

It will soon also be connected to documentation at https://mapster.talv.space/layouts/frame.

## Contribution guide

Validate your changes before commiting using `xmllint`:

```sh
xmllint --noout --schema dev/sc2layout-map.xsd sc2layout/*.xml
```

### Recommended tools

* Visual Studio Code
* https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml
* https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
