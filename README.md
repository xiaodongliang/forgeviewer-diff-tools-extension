# forgeviewer-diff-tools-extension

DiffTool Extension was introduced at: https://forge.autodesk.com/blog/difference-3d-models-autodeskdifftool-extension
This small demo is based on the repository: https://github.com/yiskang/MultipleModelUtil

1. Prepare two model versions and translate them by Model Derivative service of Forge by other utilities or scripts
2. Input the urn of the two models to the [lines 34-35 in index.html](https://github.com/xiaodongliang/forgeviewer-diff-tools-extension/blob/main/index.html#L34-L35)
3. Get access token by other utilities or scripts, input it to [line 47 of index.html](https://github.com/xiaodongliang/forgeviewer-diff-tools-extension/blob/main/index.html#L47)
4. Open index.html in the browser.
5. After model A and model B are loaded completely. Type `modelDiff()` function in browser console
6. The diffTool will be loaded and model versions will be compared. 
7. By default, the aggregated single view will be displayed.
![thumbnail](/single.png)  
8. Click the split view, the two versions will be displayed side by side.
![thumbnail](/split.png)  

