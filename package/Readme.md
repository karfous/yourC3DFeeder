# Install

Sorry guys, it would be better to use AUTODESK Publish package function, but I do not have time to cover this so only copy paste solution is now available

## Do this ...

- Turn off your Civil 3D app
- Find Roaming folder C:\Users\ {your USER}\AppData\Roaming\
- Find Dynamo packages folder ...\Roaming\Autodesk\C3D {some version}\Dynamo\ {some version}\packages
- Copy the package inside package folder ...\packages\yourC3DFeeder
- Add a path to this custom package inside DynamoSettings.xml

  - find ...\Roaming\Autodesk\C3D {some version}\Dynamo\ {some version}\DynamoSettings.xml
  - find CustomPackageFolder section in XML and add path to your package - checkout the picture below

    <img src="/pics/customPackage.png" width="300"/>

- Hey, you are done ✅

## After install ...

- Start Civil 3D
- Start Dynamo
- Feeder package will be available
- Continue to [samples section](../samples/corridor)

## Version

Let me know if working elsewhere :)

| C3D version | Working |
| ----------- | ------- |
| 2024        | ✅      |
| 2025        |         |
| 2026        |         |
