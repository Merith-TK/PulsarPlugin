# Personal PluginHub

A personal collection of plugins for [Pulsar](https://github.com/SpaceGT/Pulsar).

## Adding Plugins

To add a plugin to your personal hub:

1. Create an XML file in the `Plugins` folder for GitHub-based plugins
2. For Steam Workshop mods, create an XML file in the `Plugins/Mods` folder
3. Use the sample templates as reference:
   - `sample-github` for GitHub repositories
   - `sample-mod` for Steam Workshop mods

## Validation

Run the validation script to check your plugin XML files:

```bash
python test.py Plugins
```

## Converting to JSON

Generate a JSON file from your plugins:

```bash
python Json/tojson.py Plugins output.json
```
