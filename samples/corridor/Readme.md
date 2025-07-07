# About the sample

This is a corridor sample that shows the most common use case. You usually want to create a corridor, make some changes, change subassemblies, add more regions etc. This is the common task for every construction project. **And it is covered in this sample**

## 💛 Make it run

- select solids in dwg file
- updat object selection in dynamo script
- run script
- check out new property sets in the solids

## 🤷‍♂️ Input

What are our inputs?

### placeholders.json

Defines common phrases that are being replaced in psetsdefs.jsonc. These phrases can be easily changed if you create multiple placeholders files for you project.

### psetsdefs.jsonc

Specify layers of objects and their property sets and values. This is the magic, this is the framework. You specify objects metadata in json = create your company standards and then reuse it on every project.

### sample.dwg

Inside the drawing you find a corridor with extracted solids. Simple, easy to understand, based on C3D subassemblies. No 3rd party tools.

Check out

- the corridor definition
- corridor regions
- assemblies I use in each region
- code shapes of each subassembly

### yourC3DFeeder.dyn

This script will add properties and property sets. Check out its comments and notes. Make sure you installed package properly before RUN the script.

**And here the magic happens.**

## 💨 Output

If you try the running the script in the input folder, you can then easily check the result in output. Output is here just for you to check that you understand the script and that your results are the same as mine.
