## 收集一些比较常用的Swift第三方库

#### 网络@
* [Alamofire](https://github.com/Alamofire/Alamofire) - 非常赞👍👍👍 Alamofire是AFNetworking的作者mattt新写的网络请求的swift库。[Alamofire 最佳实践](https://github.com/ipader/SwiftGuide/wiki/Alamofire%20%E6%9C%80%E4%BD%B3%E5%AE%9E%E8%B7%B5)
* [Moya](https://github.com/Moya/Moya) - 对Alamofire的封装，使用枚举将网络层实现细节与页面逻辑代码分离，方便单元测试，支持stub测试，配合RxSwift食用更佳，[博客教程](http://www.hmttommy.com/2015/12/15/Moya/)
* [Reachability](https://github.com/ashleymills/Reachability.swift) - 检测网络连通性实用工具库（Reachability 的 Swift 版本）。
* [Tiercel](https://github.com/Danie1s/Tiercel) - 简单易用且功能丰富的纯Swift下载框架，（缺点：不支持后台下载）

#### UI@
* [SnapKit](https://github.com/SnapKit/SnapKit) - A Swift Autolayout DSL for iOS & OS X 
* [Material](https://github.com/CosmicMind/Material) - A UI/UX framework for creating beautiful applications.
* [TextFieldEffects](https://github.com/raulriera/TextFieldEffects) - Custom UITextFields effects inspired by Codrops, built using Swift
* [LoginCritter](https://github.com/cgoldsby/LoginCritter) - An animated avatar that responds to text field interactions
* [WhatsNewKit](https://github.com/SvenTiigi/WhatsNewKit) - 高可定制应用更新特性展示视图。
* [MessageViewController](https://github.com/GitHawkApp/MessageViewController) -  用作极佳、定制的文本输入控制时，自适应文本区域，手势识别、自动填充、多媒体合并，快速drop-in解决方案. [SlackTextViewController] (https://github.com/slackhq/SlackTextViewController) 的 Swift 版本实现，它是 Slack 应用信息输入组件。
* [fluid-slider ](https://github.com/Ramotion/fluid-slider) - 滑动时带气泡指示的滑块组件及演示。顺附了 Ramotion 上架 UI 演示案例集合。
* [SkeletonView](https://github.com/Juanpe/SkeletonView) - 等待加载信息前，预先优雅的显示内容框架。
* [Cards](https://github.com/PaoloCuscela/Cards) - 高仿 App Store 卡片界面风格设计组件及演示。
* [CHIPageControl](https://github.com/ChiliLabs/CHIPageControl) - 酷帅的翻页状态切换动画组件。
* [panelkit](https://github.com/louisdh/panelkit) - 灵活地浮动、磁吸式弹窗 UI 组件框架库。

#### 日历@
* [CalendarKit](https://github.com/richardtop/CalendarKit) - 高可定制日历组件库。

#### 弹出框@
* [SwiftEntryKit](https://github.com/huri000/SwiftEntryKit) - 简洁易用的iOS通知/弹出框的开源库
* [Alerts-Pickers](https://github.com/dillidon/alerts-and-pickers) - 可配置、功能丰富的警示弹窗组件库。
* [BulletinBoard](https://github.com/alexaubry/BulletinBoard) - 在底部卡片式显示公告信息及交互按钮。
* [XLActionController](https://github.com/xmartlabs/XLActionController) - 具有丰富可定制风格及动效的 Action 控制类库。


#### 指示器@
* [Toast-Swift](https://github.com/scalessec/Toast-Swift) - A Swift extension that adds toast notifications to the UIView object class.
* [StatusAlert](https://github.com/LowKostKustomz/StatusAlert) - 类似苹果系统状态自隐信息显示组件（不中断用户作业的信息显示）。
* [NotificationBanner](https://github.com/Daltron/NotificationBanner) - 简单、易用地高可定制通知、状态栏组件。
* [NVActivityIndicatorView](https://github.com/ninjaprox/NVActivityIndicatorView) - 很炫酷的加载动画的集合

#### Json@

* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON) - The better way to deal with JSON data in Swift..  本质上仍然是根据JSON结构去取值，使用起来顺手、清晰；但这种做法没能妥善解决上述的几个问题，因为它不是机遇model的，我们使用的时候，依然必须制定key去获取value，这在一定程度上不是很友好。
* [HandyJSON](https://github.com/alibaba/HandyJSON) - A handy swift json-object serialization/deserialization library.  采用Swift反射+内存赋值的方式来构造Model实例，保持原汁原味的Swift类定义
* [ObjectMapper](https://github.com/Hearst-DD/ObjectMapper) - Simple JSON Object mapping written in Swift.   实现了JSON直接转Model的功能，不过使用起来，代码量会多一点，因为我们必须遵循Mappable协议，制定json内的每一个key和model属性的对应关系。


#### 框架@
* [IBAnimatable](https://github.com/IBAnimatable/IBAnimatable) - 基于 Swift Interface Builder 开发的完整 App，包含高度设计的 UI，动画交互，页面导航等
* [RxSwift](https://github.com/ReactiveX/RxSwift) - Reactive Programming in Swift
* [ReSwift](https://github.com/ReSwift/ReSwift) - 是一个轻量级的框架，能够帮助你很轻松的去构建一个 Redux 架构的app。
* [PromiseKit](https://github.com/mxcl/PromiseKit) - 是iOS/OS X 中一个用来出来异步编程框架。

#### 图像缓存@

* [AlamofireImage](https://github.com/Alamofire/AlamofireImage) - Alamofire的一个图片组件，支持图片序列化，UIImage扩展（压缩、缩放、圆角、核心图像），单个、多个的图片过滤、自动清除内存，队列图片下载、URL鉴定、图片占位和异步远程图片下载、UIImageView过滤和转换等. An image component library for Alamofire.
* [Kingfisher](https://github.com/onevcat/Kingfisher) - A lightweight, pure-Swift library for downloading and caching images from the web.


#### 图像浏览@
* [SKPhotoBrowser](https://github.com/suzuki-0000/SKPhotoBrowser) - 一款好用的Swift版本的图片浏览器
* [ImagePicker](https://github.com/hyperoslo/ImagePicker) - 非常好用的照片选择器

#### 音频@

* [AudioKit](https://github.com/AudioKit/AudioKit) - Swift audio synthesis, processing, & analysis platform for iOS, macOS and tvOS. 音频合成、加工及分析平台（支持 iOS、OS X、tvOS）框架库。

#### 图像识别@

* [SwiftOCR](https://github.com/garnele007/SwiftOCR) - 
Fast and simple OCR library written in Swift

#### 相机@
* [ALCameraViewController](https://github.com/AlexLittlejohn/ALCameraViewController) - 摄像头视图控制器（含可定制照片选择器，图片简单裁切功能）及演示。
* [NextLevel](https://github.com/NextLevel/NextLevel) - 对于相机能力，它几乎满足了你所有需求，且更多一点的组件库。


#### 动画@

* [Spring](https://github.com/MengTo/Spring) - 一个用来简化 iOS 动画 api 的库，支持链式代码和 Storyboard 模式。
* [Advance](https://github.com/timdonnelly/Advance) - 简单易用、功能强大的动画框架库。在手势交互、帧动画、自定义动画及仿真类型将是不错的选择。
* [Koloda](https://github.com/Yalantis/Koloda) - 基于卡片的 Tinder-style 动画效果示例, 通过左右滑动切换卡片和做出不同的选择判断。精细绝人。更赞的是额外附了详细开发教程 How We Built Tinder-Like Koloda Animation in Swift [网页链接](https://yalantis.com/blog/how-we-built-tinder-like-koloda-in-swift/) 。Yalantis 出品动画程序款款精品。
* [ZLSwipeableViewSwift](https://github.com/zhxnlai/ZLSwipeableViewSwift) - swift 卡片堆叠效果的实现
* [DisplaySwitcher.swift](https://github.com/Yalantis/DisplaySwitcher) - 两个集合视图在不同布局（平铺和列表）间平滑切换。[Yalantis](https://github.com/Yalantis) 出品。
* [GuillotineMenu](https://github.com/Yalantis/GuillotineMenu) - 旋转式弹出的顶部导航栏菜单
* [circle-menu.swift](https://github.com/Ramotion/circle-menu) - 动画效率很赞的圆形缩放菜单演示及类库。
* [expanding-collection](https://github.com/Ramotion/expanding-collection) - 一个动态材质设计的卡片选择界面。
* [Hero](https://github.com/lkzhao/Hero) - 是一个构建 iOS 视图控制器之间转场动画的库。通过声明式的方法封装了 UIKit 复杂的 API，支持代码和 Storyboard 方式。 
* [EasyTransitions](https://github.com/marcosgriselli/EasyTransitions) - A simple way to create custom interactive UIViewController transitions. 实现细腻的转场动画效果。
* [paper-onboarding](https://github.com/Ramotion/paper-onboarding) - PaperOnboarding is a material design UI slider. 
* [ViewAnimator](https://github.com/marcosgriselli/ViewAnimator) - 简单的代码实现复杂 UI 布局及动画切换。
* [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) - 上下滚动时自动消隐或显示导航标题栏类库及示例。
* [Advance](https://github.com/timdonnelly/Advance) - 简单易用、功能强大的动画框架库。在手势交互、帧动画、自定义动画及仿真类型将是不错的选择。
* [spruce-ios](https://github.com/willowtreeapps/spruce-ios) - 非常易用的多视图协同编排动画库。
* [elongation-preview](https://github.com/Ramotion/elongation-preview) - 干净、优雅的 push-pop 风格视图控制器。来自 [Ramotion](https://github.com/Ramotion)
* [WCLShineButton](https://github.com/imwcl/WCLShineButton) - 类似太阳动画的按钮。
* [Motion](https://github.com/CosmicMind/Motion) - 来自 CosmicMind 无缝流畅的动画及转场框架库。

#### 侧滑与右滑返回手势@

* [SideMenu](https://github.com/Yalantis/Side-Menu.iOS) - swift实现，一款带动画效果可定制 Slide Menu，可以学习其动画实现思路。

#### TabBar@

* [animated-tab-bar](https://github.com/Ramotion/animated-tab-bar) - 给tabbar item增加动画效果的一个组件.
* [ESTabBarController](https://github.com/eggswift/ESTabBarController) - 一款功能十分强大的自定义TabBarController组件，满足你所有关于TabBar的需求。目前支持Lottie，让你的TabBar动起来吧！


#### 文本@

* [LTMorphingLabel](https://github.com/lexrus/LTMorphingLabel) - swift 能够实现文字变形动画效果的Label，用Swift写的一个能够实现文字变形动画效果的Label，很炫。
* [ActiveLabel](https://github.com/optonaut/ActiveLabel.swift) - 扩展实现 UILabel 触控事件针对 “#, @, 链接” 响应及事件捕获。


#### CollectionView@

* [CollectionKit](https://github.com/SoySauceLab/CollectionKit) - A modern Swift framework for building reusable data-driven collection components.
* [AnimatedCollectionViewLayout](https://github.com/KelvinJin/AnimatedCollectionViewLayout) - 低耦合实现在 CollectionView 内增加漂亮地转场过渡效果。(PS: 有停更的迹象)

#### 列表@

* [folding-cell](https://github.com/Ramotion/folding-cell) - FoldingCell is an expanding content cell with animation inspired by folding paper material design UI.
* [SwipeCellKit](https://github.com/SwipeCellKit/SwipeCellKit) - UITableViewCell 内各种滑动变化及动画效果。

#### 图表@

* [ios-charts](https://github.com/danielgindi/Charts) - 一款优秀 Android 图表开源库 MPAndroidChart 的 Swift 语言实现版（支持 Objective-C 和 Swift 调用）。缺省提供的示例代码为 Objective-C.
* [HSStockChart](https://github.com/zyphs21/HSStockChart) - 股票走势图，包括 K 线图，分时图，并提供横屏展示，手势缩放，拖动

#### 设计模式@

* [Design-Patterns-In-Swift](https://github.com/ochococo/Design-Patterns-In-Swift) 非常👍 Design Patterns implemented in Swift

#### 测试调试@

* [Quick](https://github.com/Quick/Quick) - 非常赞👍👍👍 用于Swift中的单元测试（也可用于Objective-C），与Xcode整合在一起。如果你是Objective-C的粉丝，我建议用Specta代替这个，但是对Swift使用者来说，Quick是最佳选择.

### 轮播图@

* [FSPagerView](https://github.com/WenchaoD/FSPagerView) - 功能性和实用性均佳，应用领域广泛（宣传页、产品展示、指南...）的幻灯片播放库。

### 标签卡@
* [XLPagerTabStrip](https://github.com/xmartlabs/XLPagerTabStrip) - 页面滑动和标签选项卡，非常好用的东东
* [Segmentio](https://github.com/Yalantis/Segmentio) - Animated top/bottom segmented control written in Swift.
* [Persei](https://github.com/Yalantis/Persei) - 非常赞 动画隐藏或显示顶部菜单支持库及示例项目。

#### 二维码@
* [BarcodeScanner](https://github.com/hyperoslo/BarcodeScanner) - 带状态控制的条码扫描库，支持处理相机权限、自定义颜色和提示信息，不依赖其他第三方库).
* [EFQRCode](https://github.com/EyreFree/EFQRCode) - iOS 花式二维码生成库.


#### AR@

* [ARShooter](https://github.com/farice/ARShooter) - A demo Augmented Reality shooter made with ARKit in Swift (iOS 11) http://texnotes.me/post/5/.


#### 服务器@
* [vapor](https://github.com/vapor/vapor) - A server-side Swift web framework. 相比 Perfect，这一款 Web 服务器框架更轻量、小巧型，方便二次开发使用。
* [Perfect](https://github.com/PerfectlySoft/Perfect) - Server-side Swift. The Perfect core toolset and framework for Swift Developers.
* [Kitura](https://github.com/IBM-Swift/Kitura) - A Swift web framework and HTTP server.
* [apollo-ios](https://github.com/apollographql/apollo-ios) - A strongly-typed, caching GraphQL client for iOS, written in Swift 
* [swifter](https://github.com/httpswift/swifter) - 一款极其轻量的 HTTP 服务器引擎

#### 组件化@
* [Crossroad](https://github.com/giginet/Crossroad) - URL route，这款使用貌似挺简单的。
* [URLNavigator](https://github.com/devxoul/URLNavigator) - 可以建立基于 URL 模式匹配的 URL 与 view controllers 映射导航工具类库。

##### 数据存储
* [Disk](https://github.com/saoudrizwan/Disk) -  针对 Swift 数据对象（结构、图像、Codable、Data）文件形式的持久化管理框架库。
* [Locksmith](https://github.com/matthewpalmer/Locksmith) - 功能强大、面向协议便于扩展的 Keychain 类库。
* [GRDB](https://github.com/groue/GRDB.swift) - 让操作 SQLite 再简单一点，方便、实用。
* [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) - Simple Swift wrapper for Keychain that works on iOS, watchOS, tvOS and macOS.

##### 其他@
* [CryptoSwift](https://github.com/krzyzanowskim/CryptoSwift) -  各种加密方式
* [merchantkit](https://github.com/benjaminmayo/merchantkit) - 极简代码应用内购框架。
* [SwiftLint](https://github.com/realm/SwiftLint) - SwiftLint 是一个用于强制检查 Swift 代码风格和规定的一个工具，基本上以 [GitHub's Swift 代码风格指南](https://github.com/github/swift-style-guide)为基础。
* [VisualActivityViewController](https://github.com/naturaln0va/VisualActivityViewController) - 系统分享视图同屏图文预览。
* [Repeat](https://github.com/malcommac/Repeat) - 可替代 NSTimer，基于 GCD，语法简洁、轻量的定时器。
* [AppFolder](https://github.com/dreymonde/AppFolder) - 一套更优雅易用的 App 文件系统访问库。 
* [Files](https://github.com/JohnSundell/Files) - 优雅、健壮的文件系统管理类库。
* [Closures](https://github.com/vhesener/Closures) - 简洁、直观的 UIKit 和 Foundation 封装库。
* [LifetimeTracker](https://github.com/krzysztofzablocki/LifetimeTracker) - 在开发过程中，直观快速的发现应用生命周期内的内存泄漏。
* [FileKit](https://github.com/nvzqz/FileKit) - 使用简单、功能完整的文件管理工具库类。
* [Chatto](https://github.com/badoo/Chatto) - 轻量级聊天应用框架及示例。文字及图片可扩展输入栏，汽泡效果等聊天核心特性，分页及自动布局完善。
* [Localize-Swift](https://github.com/marmelroy/Localize-Swift) - 一款开发者不可或缺的国际化及本地化字符串框架支持类库。同样地，使用简单、直观又方便。
* [FolioReaderKit](https://github.com/FolioReader/FolioReaderKit) - ePub 阅读器及解析框架类库。
* [Zip](https://github.com/marmelroy/Zip) - 套用 Swift 语言写的解、压缩框架库
* [TinyConstraints](https://github.com/roberthein/TinyConstraints) - 自动布局微约束、易理解、高可读语法糖。
* [SwiftMonkey](https://github.com/zalando/SwiftMonkey) - iOS 应用的随机 UI 测试框架。

#### 项目@
* [Quick-Chat](https://github.com/aslanyanhaik/Quick-Chat) - 基于 Firebase 数据服务框架的实时聊天应用。
