### 运行问题
```
An application bundle was not found at the provided path.
Provide a valid path to the desired application bundle.
Print: Entry, ":CFBundleIdentifier", Does Not Exist

Command failed: /usr/libexec/PlistBuddy -c Print:CFBundleIdentifier build/Build/Products/Debug-iphonesimulator/react_native_starter.app/Info.plist
Print: Entry, ":CFBundleIdentifier", Does Not Exist
```
### 解决方案

```
在根目录 将.rncache文件夹及里面的全部内容替换

```


