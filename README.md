# Slicer

Automatically export Sketch slices into an Xcode .xcassets bundle

* normal slices will export to xxx.imageset
* slices named as **AppIcon-60** will export to **AppIcon.appiconset** and generate crosponding Contents.json file with
```
{
"idiom": "iphone",
"scale": "2x",
"filename": "AppIcon-60@2x.png",
"size": "60x60"
},
```

- this project was folked from https://github.com/ryangomba/Slicer

## usage
* install SketchTool from here http://www.sketchapp.com/tool/
* add **run script** in project setting **Target>Build Phase**
```
python "$PROJECT_DIR/slice.py" "$PROJECT_DIR/Design/Slicer.sketch" "$PROJECT_DIR/Support/Images.xcassets"
```
* remember to put the **run script** before **Copy Bundle Resources**
* set appicon slice name like **AppIcon-60** in sketch file to handle AppIcons
* test first before apply
