# Install

You can install the package from github instruction below - or you can simply use Autodesk Dynamo package installer :)

<img src="/pics/adskPublisher.png" width="300"/>

## Github step by step install

### First steps

- Turn off your Civil 3D app
- Find Roaming folder C:\Users\ {your USER}\AppData\Roaming\
- Find Dynamo packages folder ...\Roaming\Autodesk\C3D {some version}\Dynamo\ {some version}\packages
- Copy the package inside package folder ...\packages\yourC3DFeeder
- Add a path to this custom package inside DynamoSettings.xml

  - find ...\Roaming\Autodesk\C3D {some version}\Dynamo\ {some version}\DynamoSettings.xml
  - find CustomPackageFolder section in XML and add path to your package - checkout the picture below

    <img src="/pics/customPackage.png" width="300"/>

- Hey, you are done ✅

### After install ...

- Start Civil 3D
- Start Dynamo
- Feeder package will be available
- Continue to [samples section](../samples/corridor)

## Version

Let me know if working elsewhere :)

| C3D version | Working |
| ----------- | ------- |
| 2024        | ✅      |
| 2025        | ❗ be aware that [C3D Toolkit does not work here](https://forum.dynamobim.com/t/future-of-civil-3d-toolkit-and-camber-packages/98700/45)         |
| 2026        |  ...      |
