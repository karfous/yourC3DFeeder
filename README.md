# Dynamo Civil 3D Feeder

Dynamo Feeder is a lightweight framework that allows you to add property sets with property values to any AutoCAD or Civil 3D model space object based on AutoCAD layers.

## 🧩 Samples

You can easily try the framework with some [samples](samples) I have prepared for you.

## Version

Let me know if working elsewhere :)

| C3D version | Working |
| ----------- | ------- |
| 2024        | ✅      |
| 2025        |         |
| 2026        |         |

## 💯 Install

- Civil 2024 with all patches
- Dynamo package: Civil3DToolkit by paolo.serra@autodesk.com
- copy the content from [/package](package) to your dynamo package destination folder for example ...\AppData\Roaming\Autodesk\C3D 2024\Dynamo\2.xx\packages

## ❓ About the workflow

I was wondering how can I easily add metadata to AutoCAD or Civil 3D objects. You can use some 3rd party tools for this task of course but Dynamo seemed to be enough with packages and nodes already provided.

### 🔪 I wanted

- to define corridor
- to use it as data shortcut
- to generate solids (dynamicaly connected)
- to add property sets and values with one button
- to have this possibility on every project

### 🙏 How to start

- define assemblies
- define proper codes for subassemblies shapes
- define property sets and values definition - see [jsonc](https://github.com/karfous/DynamoC3DFeeder/blob/main/samples/corridor/input/psetsdefs.jsonc) in samples
- build your corridor and export solids
- use the script and enjoy

## 🤝 Community

### 🐞 BUG report and cooperation

Create an [issue](https://github.com/karfous/DynamoC3DFeeder/issues) in order to inform others about possible problems and bugs.

### 💡 Suggestions

Create an [issue](https://github.com/karfous/DynamoC3DFeeder/issues) so we can discuss your intentions and coordinate our time. Discuss your thought before pull request please.

### 💪 Be independent

You can easily "fork" the repository and make your edits, improvements or bug fixes for yourself of course.

## 😊 Support

- ⭐ Star the repository
- 🗣️ Share it with others on social media #dynamoC3Dfeeder
- ☕ [Buy me a coffee](https://coff.ee/jakubkares)

<img src="/pics/coffe.png" width="300"/>
