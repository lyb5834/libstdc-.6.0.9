## libstdc-.6.0.9

Help people download the libstdc-6.0.9 library file.


 # 真机   
 终端输入：  `open /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib`
 后把 iPhoneOS 下libstdc++.6.0.9.tbd 文件 放入即可
 
 # 模拟器
 终端输入：  `open /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib`
 后把 iPhoneSimulator 下libstdc++.6.0.9.tbd 文件 放入即可
 
 模拟器还要放入动态库 终端输入 `open /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/`
 后把 iPhoneSimulator 下libstdc++.6.dylib、 libstdc++.dylib 文件 放入即可
