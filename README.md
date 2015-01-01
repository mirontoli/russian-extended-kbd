russian-extended-kbd
====================

Extended keyboard layout for Russian and all languages that use Cyrillic letters (mostly languages of Russian federation)

Add this to base.xml and evdev.xml under ru node:

```xml
<variant>
  <configItem>
    <name>rux</name>
    <description>Russian Extended</description>
    <languageList>
      <iso639Id>rux</iso639Id>
    </languageList>
  </configItem>
</variant>
```
