# Slicer

Automatically export Sketch slices into an Xcode .xcassets bundle

this project was folked from https://github.com/ryangomba/Slicer

## usage
* add **run script** in project setting **Target>Build Phase**
```
python "$PROJECT_DIR/slice.py" "$PROJECT_DIR/Design/Slicer.sketch" "$PROJECT_DIR/Support/Images.xcassets"
```
* remember to put the **run script** before **Copy Bundle Resources**
* set appicon slice name like **AppIcon-60** in sketch file
* test first before apply
