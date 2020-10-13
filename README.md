# java-formatter-configuration

Opinionated Java formatter Configuration for Eclipse/STS/VSCode

## How to use

### eclipse/sts

- Download XML : https://raw.githubusercontent.com/rbestardpino/java-formatter-configuration/main/vscode-java-rbestardpino-style.xml
- Open Eclipse > Project Menu > Java Code Style > Formatter > Import > Import Downloaded XML

### vscode

- Update settings.json in Code > Preference

```json
{
  "java.format.settings.url": "https://raw.githubusercontent.com/rbestardpino/java-formatter-configuration/main/vscode-java-rbestardpino-style.xml",
  "java.format.settings.profile": "rbestardpino"
}
```

## Credits

Base configuration is taken from Google's java style guide and mansa's java style guide
