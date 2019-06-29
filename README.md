# CodeSnippets

## 使用方式

Xcode 的 Code Snippets 文件存放于 ~/Library/Developer/Xcode/UserData/CodeSnippets 目录，只要直接把 *.codesnippets 文件放到这个目录下（若没有则自己创建），重启 Xcode 即可生效。

## 快捷键汇总

### objc

- `ann`: 属性名注释 和 方法名注释
- `assign--`: 定义一个 assign 的 property
- `checkerror`: 定义一个检查错误的函数
-  `conststring`: 定义一个字符串常亮
-  `copy--`: 定义一个 copy 的 property
-  `copyblock`: 定义一个 block 的 property
-  `debug`: Debug 判断
-  `deprecated`: 忽略方法过期警告
-  `desmethod`: 重写 `- (NSString *)description` 方法
-  `dispatch_async_global_queue`: 异步全局队列
-  `fetchcoredata`: CoreData 查询
-  `fetchresultscontroller`: CoreData 查询结果
-  `initcell`: 重写 `UITableViewCell` 的初始化方法
-  `initparams`: 定义初始化参数方法模板
-  `initviews`: 定义初始化界面方法模板
-  `logcmd`: 打印带方法名的日志
-  `logstack`: 打印运行时调用栈
-  `mark`: 展开一个用于 Xcode 导航的 `#pragma mark -` 宏
-  `mas_make`: 创建 Masonry 约束 block
-  `mas_remake`: 创建 Masonry 约束 block
-  `mas_update`: 创建 Masonry 约束 block
-  `separatorLine`: Cell 分割线
-  `setframe`: 设置 frame 语法糖
-  `singleton`: 创建单例
-  `strong--`: 定义一个 strong 的 property
-  `strongself`: strong self for retainCycle
-  `weak--`: 定义一个 weak 的 property
-  `weakdelegate`: 定义一个 delegate 的 property
- `weakself`: weak self for retainCycle

### swift

- `swift-closureoptionaltypealias`: Optional closure typealiast with arguments and return value snippet for Swift
- `swift-closuretypealias`: Closure typealias with arguments and return value snippet for Swift
- `swift-prop`: Auto-Create property stub
- `swift-dispatchafter`: GCD dispatch_after snippet for Swift
- `swift-dispatchasync`: GCD dispatch_async snippet for Swift
- `swift-dispatchmain`: GCD dispatch_async on main queue snippet for Swift
- `swift-documentdirectory`: Document directory path snippet for Swift
- `swift-forin`: for-in loop that casts objects inline
- `swift-iba`: Create IBAction method stub
- `swift-ibo`: Stub out IBOutlet
- `swift-mail`: MFMailComposeViewController snippet for Swift
- `swift-mark`: Divider label for separating code into sections
- `swift-message`: MFMessageComposeViewController snippet for Swift
- `swift-nslocalizedstring`: NSLocalizedString function snippet for Swift
- `required init`: Swift Required Initializer
- `swift-sortarrayofstrings`: Swift String Array locale-aware sorting
- `swift-uialertcontroller`: Present a UIAlertController
- `swift-uicollectionviewdatasource`: UICollectionViewDataSource snippet for Swift
- `swift-uicollectionviewdelegate`: UICollectionViewDelegate snippet for Swift
- `swift-uiremotenotification`: UIRemoteNotification registration and handling snippet for Swift
- `swift-uitableviewdatasource`: UITableViewDataSource snippet for Swift
- `swift-uitableviewdelegate`: UITableViewDelegate snippet for Swift
- `swift-uiviewcontrollerlifecycle`: Swift UIViewController lifecycle
- `swift-urlsession-datatask`: Swift Simple HTTP Request
- `swift-urlsession-delegate`: Swift HTTP Request With Delegate set
- `swift-weak`: weakify self in closure