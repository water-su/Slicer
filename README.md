# Slicer

Automatically export Sketch slices into an Xcode .xcassets bundle

this project was folked from https://github.com/ryangomba/Slicer

## usage
1. add run script in project setting **Target>Build Phase**
```
python "$PROJECT_DIR/slice.py" "$PROJECT_DIR/Design/Slicer.sketch" "$PROJECT_DIR/Support/Images.xcassets"
```
Notice! must before ```Copy Bundle Resources```

2. set appicon slice name as ```AppIcon-60``` like naming
3. test first before apply
