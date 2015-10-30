# Slicer

Automatically export Sketch slices into an Xcode .xcassets bundle

this project was folked from https://github.com/ryangomba/Slicer

## usage
1. add **run script** in project setting **Target>Build Phase**
```
python "$PROJECT_DIR/slice.py" "$PROJECT_DIR/Design/Slicer.sketch" "$PROJECT_DIR/Support/Images.xcassets"
```
2. remember to put the **run script** before **Copy Bundle Resources**
3. set appicon slice name like **AppIcon-60** in sketch file
4. test first before apply
