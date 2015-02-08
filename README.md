开发资源总结 (持续整理中)
===============

> *就像开发一样, 这篇文档如果没有人关心和维护, 里面的内容就会变得老旧, 过时而不再具有参考价值. 所以, 我希望所有看到并喜欢这篇文档的人都来一起维护它. 放心大胆的提交 Pull Request 和 Issue 吧!!*

这是对自己这几年开发的一个总结，各种项目、资源、书籍、博客等

喜欢么？或者对您有用？那就 Star 一下吧 ^_^

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Web 前端](#web-前端)
    - [Javascript](#javascript)
        - [HTML5 相关](#html5-相关)
        - [AngularJS](#angularjs)
    - [CSS](#css)
    - [ICON](#icon)
- [Web 后端](#web-后端)
    - [Ruby](#ruby)
    - [Python](#python)
    - [Node.js](#node.js)
        - [Express](#express)
    - [Erlang](#erlang)
    - [Java](#java)
    - [C/C++](#cc)
    - [Go](#go)
- [IOS 或 OSX](#ios-或-osx)
- [Android](#android)
- [代码效率](#代码效率)
    - [CoffeeScript](#coffeescript)
    - [TypeScript](#typescript)
    - [Sublime Text](#sublime-text)
- [云计算](#云计算)
    - [Docker](#docker)
    - [OS](#os)
- [开源产品(论坛、在线教育、项目管理等)](#开源产品论坛、在线教育、项目管理等)
- [Awesome 系列](#awesome-系列)
- [代码规范&设计模式](#代码规范&设计模式)
    - [Ruby](#ruby-1)
        - [Rails](#rails)
    - [Java](#java-1)
    - [Bash](#bash)
    - [Objective-C](#objective-c)
    - [Swift](#swift)
- [数据库](#数据库)
- [博客 / 网站](#博客--网站)
    - [设计](#设计)
    - [技术](#技术)
- [书籍 / 阅读](#书籍--阅读)
    - [前端](#前端)
        - [Web](#web)
        - [IOS](#ios)
    - [后端](#后端)
        - [Node.js](#nodejs)
        - [Ruby](#ruby-2)
        - [Go](#go-1)
        - [接口](#接口)
    - [其他](#其他)
- [科学上网](#科学上网)
- [Git 相关](#git-相关)
- [其他](#其他-1)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Web 前端

#### Javascript

+ [parallel.js](https://github.com/adambom/parallel.js): 前后端通用的一个并行库
+ [zepto](https://github.com/madrobby/zepto): 用于现代浏览器的兼容 jQuery 的库
+ [totoro](https://github.com/totorojs/totoro): 稳定的跨浏览器测试工具
+ [TheaterJS](https://github.com/Zhouzi/TheaterJS): 一个用于模拟人输入状态的 JS 库
+ [stellar.js](https://github.com/markdalgleish/stellar.js): 前端用于实现异步滚动效果的库，现已不再维护
+ [skrollr](https://github.com/Prinzhorn/skrollr): 另一款实现一步滚动的开源库，使用人数众多，可实现各种狂拽酷炫掉渣天的前端效果，[看真相](http://prinzhorn.github.io/skrollr/)
+ [Framework7](https://github.com/nolimits4web/Framework7): 前端框架，是开发人员可以基于 web 技术构建 IOS7 程序
+ [regulex](https://github.com/JexCheng/regulex): 用于生成 正则表达式 的可视化流程图
+ [markdown-it](https://github.com/markdown-it/markdown-it): 新型 Markdown 解析器，快速，支持插件
+ [multiline](https://github.com/sindresorhus/multiline): 用于 Javascript 中的多行文本，类似于 Ruby 的 HERE Doc
+ [screenfull.js](https://github.com/sindresorhus/screenfull.js): 全屏插件，支持各大浏览器
+ [lunr.js](https://github.com/olivernn/lunr.js): 类似于 Solr, 但是用于浏览器上的全文搜索引擎，可以为 JSON 创建索引，离线也可以使用
+ [jquery.hotkeys](https://github.com/jeresig/jquery.hotkeys): jQuery 插件，用于绑定热键
+ [breach_core](https://github.com/breach/breach_core): Javascript 编写的 Browser (浏览器)
+ [octocard](https://github.com/zmmbreeze/octocard): 用于生成 Github 信息卡片的库
+ [github-cards](https://github.com/lepture/github-cards): 用于生成 Github 信息卡片的库
+ [money.js](https://github.com/openexchangerates/money.js): 轻量级货币转换库，web 和 node 皆可用
+ [accounting.js](https://github.com/openexchangerates/accounting.js): 轻量级的数字、货币转换库
+ [javascript-algorithms](https://github.com/mgechev/javascript-algorithms): Javascript 实现的各种算法集合
+ [lazy.js](https://github.com/dtao/lazy.js): 类似于 underscore, 但是会延迟执行，某些场景下，性能会有很大的提升
+ [seajs](https://github.com/seajs/seajs): 前端模块加载器，解决模块化、依赖等问题
+ [jQuery-One-Page-Nav](https://github.com/davist11/jQuery-One-Page-Nav): 单页应用中一个用于处理导航栏的库
+ [js.js](https://github.com/js-js/js.js): Javascript 实现的 javascript JIT
+ [jquery-ui](https://github.com/jquery/jquery-ui): jQuery 团队开发的 UI 相关的前端库，功能强大
+ [todomvc](https://github.com/tastejs/todomvc): 分别基于 AngularJS/EmberJS/Backbone等实现的 TODO List, 帮助开发者选择前端 MVC 库
+ [localForage](https://github.com/mozilla/localForage): Mozilla 出品，用于离线存储，基于IndexedDB, WebSQL 或者 localStorage, 提供一致的接口
+ [EventEmitter](https://github.com/Wolfy87/EventEmitter): 浏览器版的 EventEmitter
+ [jquery.serializeJSON](https://github.com/marioizquierdo/jquery.serializeJSON): jQuery 插件，用于将 form 表单序列化成 JSON 数据
+ [knockout](https://github.com/knockout/knockout): 前端 MVVM 框架，用于开发富前端应用
+ [mermaid](https://github.com/knsv/mermaid): 可以根据文本生成流程图，类似于 Markdown 的语法
+ [js-sequence-diagrams](https://github.com/bramp/js-sequence-diagrams): 另一款可以根据文本生成流程图的库，类似于 Markdown 的语法
+ [flow](https://github.com/facebook/flow): 一个用来检测 Javascript 语法错误的库， Facebook 出品
+ [zoomooz](https://github.com/jaukia/zoomooz): jQuery 插件，用来处理浏览器缩放
+ [fancyBox](https://github.com/fancyapps/fancyBox): 一个用于放大缩小图片、Web 内容或者多媒体元素的库，优雅大方
+ [mithril.js](https://github.com/lhorie/mithril.js): 轻量型前端 MVC 框架，部分使用场景下性能优于 Angular.js 和 React
+ [backbone](https://github.com/jashkenas/backbone): 强大的前端 MVC 库，鼻祖级前端库，最初为了配合 Rails 来模块化前端应用，兼容性良好 (兼容到 IE6)，插件丰富，性能良好
+ [jquery.smartbanner](https://github.com/jasny/jquery.smartbanner): [smartbanner](http://developer.apple.com/library/ios/#documentation/AppleApplications/Reference/SafariWebContent/PromotingAppswithAppBanners/PromotingAppswithAppBanners.html) 是从 IOS6 开始支持的一个新特性, 这个插件提供了对早期 IOS4/5 和 Android 的支持
+ [jquery.scrollTo](https://github.com/flesler/jquery.scrollTo): 在页面上以一个元素为起始以动画的方式移动(ScrollTo)到另一个元素， 支持回退等
+ [jScrollPane](https://github.com/vitch/jScrollPane): 自定义的滚动条，让所有浏览器都显示一样的滚动条
+ [onepage-scroll](https://github.com/peachananr/onepage-scroll): 提供类似于 iPhone6 展示页类似的效果，适用于单页应用，兼容到 IE8
+ [scrollMonitor](https://github.com/sakabako/scrollMonitor): 前端插件用来监控元素的滚动事件(进入、退出等)，性能很好
+ [ScrollMagic](https://github.com/janpaepke/ScrollMagic): 神奇的滚动交互效果插件，可以在滚动的过程中设置各种各样的动态效果
+ [infinite-scroll](https://github.com/paulirish/infinite-scroll): 滚动加载，滚动到最下到自动加载， Paul Irish 大神之作
+ [animatable](https://github.com/LeaVerou/animatable): 仅仅依靠 `border-width` 和 `background-position` 实现的各种动态效果，[看真相](http://leaverou.github.io/animatable/)
+ [Fluidbox](https://github.com/terrymun/Fluidbox): 页面上内嵌图片的放大缩小效果，类似于 [Medium](http://medium.com) 中的效果
+ [jquery-validation](https://github.com/jzaefferer/jquery-validation): jQuery 的一个插件，用于校验 Form 表单
+ [BigVideo.js](https://github.com/dfcb/BigVideo.js): jQuery 的一个插件, 用于实现大背景(视频、图片)效果
+ [emscripten](https://github.com/kripken/emscripten): 一款基于 LLVM, 可以将 C/C++ 转换成 Javascript 的工具，使得 Javascript 可以近乎 Native 的速度
+ [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator): 各种语言的二维码生成工具
+ [device.js](https://github.com/matthewhudson/device.js): 一个可以检测设备类型的工具，可以让我们根据不同的设备来为其定制响应的 Javascript 和 CSS
+ [jquery-qrcode](https://github.com/jeromeetienne/jquery-qrcode): jQuery 插件，用来生成二维码
+ [Wookmark-jQuery](https://github.com/GBKS/Wookmark-jQuery): jQuery 的一个插件，可以用来实现瀑布流的效果
+ [isotope](https://github.com/metafizzy/isotope): 可以用来过滤、排列布局，实现美观的动态布局切换效果，[Demo](http://isotope.metafizzy.co/)
+ [lazysizes](https://github.com/aFarkas/lazysizes): 功能强大的图片延迟加载工具，可以首先加载一个低质量的图片，然后再加载高质量的图片
+ [progressbar.js](https://github.com/kimmobrunfeldt/progressbar.js): 简洁美观的进度条，扁平化
+ [pigshell](https://github.com/pigshell/pigshell): 一个由 Javascript 实现的Shell, 将互联网当做一个大的文件系统, 通过 cd/ls/cat.....等命令, 可以访问 Facebook
/Twitter/Google Drive 等网络服务

###### HTML5 相关

+ [sensor.js](https://github.com/branding-fe/sensor): 在智能移动设备浏览器上，通过HTML5的api使用移动设备的功能。定位、运动、倾斜等
+ [hyhyhy](https://github.com/maciejczyzewski/hyhyhy): 用于创建 基于 HTML5 的 演示文稿
+ [swipebox](https://github.com/brutaldesign/swipebox): jQuery 插件，用于处理移动端的触摸事件
+ [FileAPI](https://github.com/mailru/FileAPI): 前端用户处理文件（拖放、多文件上传等）
+ [Sortable](https://github.com/RubaXa/Sortable): 现代浏览器上用于实现元素拖拽排序的功能，支持 Meteor, AngularJS, React，不依赖 jQuery
+ [Swiper](https://github.com/nolimits4web/Swiper): 用于实现浏览器上的滑动切换效果，支持硬件加速
+ [matter-js](https://github.com/liabru/matter-js): 2D 物理效果引擎，碰撞、弹跳等
+ [jQTouch](https://github.com/senchalabs/jQTouch): 用于辅助创建手机端的 Web 应用，支持主题、Zepto.js 等
+ [snabbt.js](https://github.com/daniel-lundin/snabbt.js): 一个利用 Javascript 和 CSS transform 的 animation 库
+ [c3](https://github.com/masayuki0812/c3): 基于 D3 的图表库
+ [echarts](https://github.com/ecomfe/echarts): 企业级图表库，百度开发
+ [parallax.js](https://github.com/wagerfield/parallax): 一个用于响应智能手机 orientation 的库
+ [jQuery-Animate-Enhanced](https://github.com/benbarnett/jQuery-Animate-Enhanced): jQuery 动画库的一个增强，用于现代浏览器
+ [wysihtml](https://github.com/Voog/wysihtml): 富文本编辑器，适用于现代浏览器
+ [slip](https://github.com/pornel/slip): 一个通过滑动或者拖拽来操控列表的库
+ [evil-icons](https://github.com/outpunk/evil-icons): 一个矢量图库，提供 Ruby/Node 等支持
+ [PhotoSwipe](https://github.com/dimsemenov/PhotoSwipe): JS 的一个图片展示库
+ [focusable](https://github.com/zzarcon/focusable): 是页面上一个元素高亮的库，[有图有真相](http://zzarcon.github.io/focusable/)
+ [firefox.html](https://github.com/paulrouget/firefox.html): Firefox 在浏览器端的实现 —— HTML 版的 Firefox
+ [jquery-mobile](https://github.com/jquery/jquery-mobile): jQuery 团队开发的用于辅助手机端 web app 开发的库，基于 HTML5
+ [interact.js](https://github.com/taye/interact.js): 一个适用于现代浏览器的，用于处理 手势、拖放、缩放等的库
+ [rebound-js](https://github.com/facebook/rebound-js): 实现部分物理效果，Facebook 出品
+ [basket.js](https://github.com/addyosmani/basket.js): 基于 LocalStorage 的资源加载器，可以用来缓存 script 和 css, 手机端使用速度快于浏览器直接缓存
+ [iscroll](https://github.com/cubiq/iscroll): 高性能的滚动(scroll)处理库，功能强大，支持各种事件，不依赖任何的库，且插件丰富, 大众点评的手机端列表滚动就是用这个库处理的
+ [metrics-graphics](https://github.com/mozilla/metrics-graphics): 基于 D3 的图表库，简洁、高效，Mozilla 出品
+ [Placeholders.js](https://github.com/jamesallardice/Placeholders.js): 为不支持的 HTML5 的浏览器提供 Placeholder 支持
+ [prefixfree](https://github.com/LeaVerou/prefixfree): 自动为 CSS 添加 Vender Prefix，把你从不停添加浏览器前缀的噩梦中解放出来
+ [accessible-html5-video-player](https://github.com/paypal/accessible-html5-video-player): Paypal 出品的 Video 播放器
+ [loading](https://github.com/jxnblk/loading): 几种 Loading 效果，基于 SVG
+ [flippant.js](https://github.com/mintchaos/flippant.js): 一款能够漂亮的网页元素翻转效果库，代码许久不更新，不过作为源码学习还是不错的
+ [move.js](https://github.com/visionmedia/move.js): 基于 CSS3 的前端动画框架
+ [scrollReveal.js](https://github.com/julianlloyd/scrollReveal.js): 使元素以非常酷帅的方式进入画布 (Viewpoint)，看 [Demo](http://scrollrevealjs.org/)
+ [Modernizr](https://github.com/Modernizr/Modernizr): 一个用来检测 HTML5 和 CSS3 支持情况的库
+ [foundation](https://github.com/zurb/foundation): 另一款前端模版框架，类似于 Bootstrap
+ [Flat-UI](https://github.com/designmodo/Flat-UI): Bootstrap 的一款主题，简洁美观
+ [iCheck](https://github.com/fronteed/iCheck): 一款漂亮的 Checkbox 插件
+ [Swipe](https://github.com/lyfeyaj/Swipe): 非常轻量级的一个图片滑动切换效果库, 性能良好, 尤其是对手机的支持, 压缩后的大小约 5kb
+ [slick](https://github.com/kenwheeler/slick): 功能异常强大的一个图片滑动切换效果库
+ [SocialButtons](https://github.com/t4t5/SocialButtons): 漂亮的社交按钮
+ [sweetalert](https://github.com/t4t5/sweetalert): 一个非常美观的用于替换浏览器默认 alert 的库

###### AngularJS

+ [angular-masonry](https://github.com/passy/angular-masonry): Masonry 的 AngularJS 插件，用于瀑布流
+ [angular-schema-form](https://github.com/Textalk/angular-schema-form): 根据 JSON 生成响应的 Form 表单
+ [restangular](https://github.com/mgonto/restangular): Angular 中用来处理 RESTful API 的插件，可替代 $resource
+ [ng-cordova](https://github.com/driftyco/ng-cordova): Cordova 常用组件的 Angular 版本
+ [angular-translate](https://github.com/angular-translate/angular-translate): Angular 的国际化 (I18n)
+ [ng-inspector](https://github.com/rev087/ng-inspector): Chrome 插件，用于调试 Angular
+ [angularjs-style-guide](https://github.com/mgechev/angularjs-style-guide): AngularJS 代码风格
+ [ngReact](https://github.com/davidchang/ngReact): React 的 Angular 插件，可以在 Angular 中使用 React Components
+ [material](https://github.com/angular/material): Google Material Design 效果的 Angular 实现
+ [angular-local-storage](https://github.com/grevory/angular-local-storage): Angular 插件, 提供了对 localStorage 的友好支持, 并对不支持的浏览器使用 cookie 优雅降级
+ [angular-filter](https://github.com/a8m/angular-filter): 一组有用的 Angular Filters

#### CSS

+ [Hover](https://github.com/IanLunn/Hover): 基于 CSS3 的各种 鼠标悬停(hover)特效, [点击查看效果](http://ianlunn.github.io/Hover/)
+ [normalize.css](https://github.com/necolas/normalize.css): 一个用于重置浏览器内置样式的库
+ [Skeleton](https://github.com/dhg/Skeleton): 一个 CSS 相关的库，用于构建对手机友好的网站

#### ICON

+ [icono](https://github.com/saeedalipoor/icono): 一款用纯 CSS 实现的图标库
+ [material-design-icons](https://github.com/google/material-design-icons): Google 为 Material Design 出品的 ICON

## Web 后端

#### Ruby

+ [ruby](https://github.com/ruby/ruby): Ruby 源代码
+ [spyke](https://github.com/balvig/spyke): 像使用 ActiveRecord 一样使用 RESTful API 
+ [reactive_record](https://github.com/twopoint718/reactive_record): 根据 ActiveRecord 的 数据库 Schema 来反向生成 Model
+ [eventmachine](https://github.com/eventmachine/eventmachine): Ruby 中著名的事件驱动库
+ [faker](https://github.com/stympy/faker): Perl 的 Data::Faker 库的一个 Ruby 实现，用于虚拟各种类型的数据
+ [amqp](https://github.com/ruby-amqp/amqp): RabbitMQ 的 Ruby 客户端，基于 EventMachine
+ [bunny](https://github.com/ruby-amqp/bunny): 另一个 RabbitMQ 的 Ruby 客户端
+ [thinking-sphinx](https://github.com/pat/thinking-sphinx): Sphinx 全文搜索的 ActiveRecord 插件
+ [ruby-vips](https://github.com/jcupitt/ruby-vips): Ruby 的一款图像处理库, 基于 libvips
+ [statesman](https://github.com/gocardless/statesman): Ruby 的一个状态机
+ [aasm](https://github.com/aasm/aasm): 另一款 Ruby 状态机
+ [paper_trail](https://github.com/airblade/paper_trail): 一款强大的用于记录 Model 变更的库，非常适合于 创建记录的版本和审查变更
+ [timers](https://github.com/celluloid/timers): Ruby 的一个 Timer 库，适合于配合事件使用
+ [gitlab-shell](https://github.com/gitlabhq/gitlab-shell): gitlab 的命令行工具，用于替换 gitolite
+ [money](https://github.com/RubyMoney/money): Ruby 的一个数字、货币转换库
+ [money-rails](https://github.com/RubyMoney/money-rails): Rails 的一个数字、货币转换库
+ [houston](https://github.com/nomad/houston): APN 的 Ruby 库
+ [devise_invitable](https://github.com/scambra/devise_invitable): Devise 的一个插件，用于邀请用户
+ [mail](https://github.com/mikel/mail): Ruby 的处理邮件的库
+ [commander](https://github.com/tj/commander): Ruby 的命令行辅助库
+ [helios](https://github.com/helios-framework/helios): 一个为 IOS 提供后端支撑的库
+ [middleman](https://github.com/middleman/middleman): 一个辅助制作静态网站的工具
+ [pundit](https://github.com/elabs/pundit): 一个处理认证的库
+ [refile](https://github.com/elabs/refile): 一个处理图片上传的库
+ [sharedrop](https://github.com/cowbell/sharedrop): Airdrop 的 HTTP5 实现，基于 WebRTC
+ [mailman](https://github.com/titanous/mailman): 处理接收邮件的库
+ [mruby](https://github.com/mruby/mruby): mini-ruby (light-weight ruby) 轻量级 Ruby 源代码
+ [sidekiq-status](https://github.com/utgarda/sidekiq-status): Sidekiq 插件，用来监控任务状态
+ [postgres_ext](https://github.com/dockyard/postgres_ext): ActiveRecord 的插件，扩展了 PostgreSQL 相关的一些功能
+ [prawn](https://github.com/prawnpdf/prawn): Ruby 的 PDF 编辑工具
+ [spring](https://github.com/rails/spring): Rails 的加载器，可以加速 Rails 开发
+ [rails](https://github.com/rails/rails): Rails 源代码
+ [newrelic-grape](https://github.com/xinminlabs/newrelic-grape): Grape 的 Newrelic 插件
+ [newrelic_moped](https://github.com/stevebartholomew/newrelic_moped): Moped 的 Newrelic 插件
+ [rack-attack](https://github.com/kickstarter/rack-attack): 基于 Rack 的防攻击中间件
+ [rack-utf8_sanitizer](https://github.com/whitequark/rack-utf8_sanitizer): Rack 的 UTF8 序列化中间件
+ [redis-stat](https://github.com/junegunn/redis-stat): Redis 监控工具
+ [rack-mini-profiler](https://github.com/MiniProfiler/rack-mini-profiler): Rack 中间件，用于分析各个性能指标，如 SQL, View渲染等
+ [memory_profiler](https://github.com/SamSaffron/memory_profiler): 用于分析内存占用
+ [gctools](https://github.com/tmm1/gctools): 用于分析和优化 Ruby GC，可以配合 Unicorn 使用
+ [wicked_pdf](https://github.com/mileszs/wicked_pdf): Rails 插件，用于生成 PDF
+ [request_store](https://github.com/steveklabnik/request_store): Rack 中间件，用于保存仅单次请求有效的的全局变量，线程安全
+ [slim](https://github.com/slim-template/slim): 基于 Ruby 的前端模板引擎，类似于 Haml, 语法更简洁，据说相比于 Haml 会更快一些
+ [simplecov](https://github.com/colszowka/simplecov): Ruby 测试代码的覆盖率分析
+ [sass](https://github.com/sass/sass): CSS 框架，使得编写 CSS 更加容易和有趣，支持模块化、变量、运算、Mixin等
+ [slate](https://github.com/tripit/slate): 静态的 API 接口文档生成工具，干净、整洁、对手持设备友好、单页应用、代码高亮
+ [ruby-destroyed_at](https://github.com/dockyard/ruby-destroyed_at): ActiveRecord 扩展，支持安全删除
+ [taps](https://github.com/ricardochimal/taps): 支持数据库导入导出 -> 原理是，对导出目标数据库建立一个服务器提供数据接口，然后对目标导入数据库进行数据导入，依赖 Sinatra 启动数据库接口服务
+ [meta-tags](https://github.com/kpumuk/meta-tags): 为 Rails 应用提供 SEO 优化支持
+ [logstash](https://github.com/elasticsearch/logstash): 日志、时间管理工具
+ [rspec-rails](https://github.com/rspec/rspec-rails): Rspec 的 Rails 插件
+ [nokogiri](https://github.com/sparklemotion/nokogiri): 一个功能强大，性能良好的用于解析 HTML, XML 的工具，支持 XPath 和 CSS 选择器
+ [vcr](https://github.com/vcr/vcr): 一个测试辅助库，纪录一组 HTTP 请求交互，并作为测试重现
+ [factory_girl](https://github.com/thoughtbot/factory_girl): 一个用来准备测试数据的库
+ [mongoid_paranoia](https://github.com/simi/mongoid_paranoia): Mongoid 软删除功能, 通过添加一个 destroyed_at
+ [treat](https://github.com/louismullie/treat): Ruby的自然语言处理
+ [MacGap1](https://github.com/MacGapProject/MacGap1): 一款工具可以将 HTML/CSS/JS 网络应用打包成 Mac App
+ [ffi](https://github.com/ffi/ffi): 可以帮助 Rubyer 开发基于 C 的 ruby 库, 提供了一套接口
+ [api_cache](https://github.com/mloughran/api_cache): 可以为外部接口添加缓存的工具
+ [ckeditor](https://github.com/galetahub/ckeditor): Rails 的 Ckeditor 插件
+ [mailboxer](https://github.com/mailboxer/mailboxer): Rails 插件, 可以发送消息/邮件

#### Python

+ [django](https://github.com/django/django): 一个全栈式的 web 框架, 类似于 Rails
+ [wifiphisher](https://github.com/sophron/wifiphisher): WIFI 中间人钓鱼攻击工具，获取用户名密码
+ [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit): Python 的交互命令行工具，提供代码补全、高亮等
+ [redis-rdb-tools](https://github.com/sripathikrishnan/redis-rdb-tools): Redis 的 dump.rdb 文件解析器，用于分析内存使用、导出 JSON 以及 比较不同 rdb 文件差异
+ [supervisor](https://github.com/Supervisor/supervisor): 类UNIX下用于控制进程的一个开源库，通过配置可以监控、自动重启各种服务
+ [pyenv](https://github.com/yyuu/pyenv): Python 版本管理工具，类似于 RVM
+ [pyspider](https://github.com/binux/pyspider): 一个爬虫系统

#### Node.js

+ [Node-Webkit.js](https://github.com/nwjs/nw.js): Node-Webkit 是基于Chromium 和 node.js的运行环境，可以用来创建桌面应用程序
+ [request](https://github.com/request/request): 基于 Node.js 的用于网络请求的库，使用简单，功能强大
+ [hapi](https://github.com/hapijs/hapi): 一个配置优先的 web 框架，[hapijs.com](http://hapijs.com/)
+ [psi](https://github.com/addyosmani/psi): 用于分析页面速度的工具，支持命令行
+ [gulp](https://github.com/gulpjs/gulp): 基于 Node.js 的流式构建系统
+ [orchestrator](https://github.com/orchestrator/orchestrator): 一个可以并行执行任务和依赖的库
+ [johnny-five](https://github.com/rwaldron/johnny-five): 用 Javascript 控制机器人
+ [popcorn-js](https://github.com/mozilla/popcorn-js): Mozilla 的一个开源项目，允许开发者基于 HTML5 音视频的时间线添加互动元素，比如注释，字幕，甚至动画
+ [connect](https://github.com/senchalabs/connect): Node 中间件支持，注：Express 4 以下依赖此库，从 4 开始支持全新的 Router，类似于 Rails Engine
+ [faker.js](https://github.com/Marak/faker.js): Faker 的 Node 实现，用于生成假数据
+ [chart](https://github.com/jstrace/chart): 用于终端生成 ASCII 图表
+ [drawille](https://github.com/asciimoo/drawille): 用于终端生成 ASCII 图形
+ [sparkly](https://github.com/sindresorhus/sparkly): spark.sh 的一个 Javascript 实现，终端生成 sparklines
+ [node-inspector](https://github.com/node-inspector/node-inspector): Node 的调试神器，使用方法，用 `node-debug` 代替 `node` 启动服务，并在你想调试的地方输入 `debugger`
+ [NodeOS](https://github.com/NodeOS/NodeOS): 基于 Node 的操作系统
+ [pdfkit](https://github.com/devongovett/pdfkit): Node 和 浏览器均可以使用的，用于生成 PDF 的库
+ [empty-trash](https://github.com/sindresorhus/empty-trash): 清空垃圾桶
+ [trash](https://github.com/sindresorhus/trash): 安全删除文件 -> 将文件放入垃圾桶
+ [rabbit.js](https://github.com/squaremo/rabbit.js): RabbitMQ 的 Node 客户端
+ [htmlbars](https://github.com/tildeio/htmlbars): 基于 Handlebars 的一个变种，可以编写直接操作 DOM 的辅助方法
+ [sharp](https://github.com/lovell/sharp): Node 的一个图像处理的库，基于 libvips
+ [debug](https://github.com/visionmedia/debug): 一个用于在 console 或者 浏览器输出日志，方便与 Debug 的工具
+ [github-contributions](https://github.com/IonicaBizau/github-contributions): 一个好玩的库，用于在 github 的 contribution calendar 上输出你想要的文字或者图案
+ [hexo](https://github.com/hexojs/hexo): 基于 Node 的静态博客，类似于 Octopress
+ [GhostScroll](https://github.com/grmmph/GhostScroll): Ghost 的一个主题
+ [ghost-themes](https://github.com/haydenbleasel/ghost-themes): 多个 Ghost 主题
+ [TermKit](https://github.com/unconed/TermKit): 一个基于 Chrome 和 Node 的终端应用
+ [h5ai](https://github.com/lrsjng/h5ai): 配置简单，美观的 http 静态目录，支持 Nginx、Apache 等
+ [http-server](https://github.com/nodeapps/http-server): Http 静态服务器，基于 Node, 配置简单
+ [node-apn](https://github.com/argon/node-apn): Node 的 APN (Apple Push Notification) 模块
+ [chai](https://github.com/chaijs/chai): Node 的 TDD/BDD 测试框架
+ [io.js](https://github.com/iojs/io.js): Node 的一个分支，更加活跃，开发更激进，最终的目的是合并入 Node.js
+ [immutable-js](https://github.com/facebook/immutable-js): 不可改变的集合, 前后端通用
+ [node-migrate](https://github.com/tj/node-migrate): Node 的数据库迁移框架
+ [pomelo](https://github.com/NetEase/pomelo): Node 游戏服务器框架，网易开发
+ [blessed-contrib](https://github.com/yaronn/blessed-contrib): 构建终端信息板 (Dashboard) 利器
+ [node-notifier](https://github.com/mikaelbr/node-notifier): Node 模块，可以发送本地通知，支持 Mac/Windows/Linux
+ [prerender](https://github.com/prerender/prerender): 用于预解析网站，主要解决单页应用(angular.js ember.js backbone.js 等)的搜索引擎 SEO 支持
+ [spider](https://github.com/alongubkin/spider): 一种新语言，目标是编译成 Javascript
+ [jsdoc](https://github.com/jsdoc3/jsdoc): 用来生成 Javascript API 文档的库
+ [browser-sync](https://github.com/shakyShane/browser-sync): 多浏览器(多设备)同步库，监控 CSS/Javascript/HTML 的变更并通知到浏览器；监控浏览器的操作，如滚动、点击等事件，同步到所有的开发设备。前端开发利器！
+ [tmi](https://github.com/addyosmani/tmi): 基于 Node 的命令行工具, 用于计算网站图片的权重，以及那些图片可以进一步优化
+ [6to5](https://github.com/6to5/6to5): 转换 ES6 代码为 ES5，提前使用 ES6 语法带来的各种畅快！
+ [js-xss](https://github.com/leizongmin/js-xss): 根据白名单过滤HTML(防止XSS攻击)
+ [PM2](https://github.com/Unitech/PM2): Node 进程管理，内置负载均衡，提供自动重启，热启动等功能，适合在生产环境下使用
+ [sinopia](https://github.com/rlidwka/sinopia): 私有 NPM 服务器
+ [validator.js](https://github.com/chriso/validator.js): 校验工具(url，邮箱，整数等), 内置几十种校验方法，前后端通用
+ [wechat](https://github.com/node-webot/wechat): 微信公共平台消息接口服务中间件
+ [superagent](https://github.com/visionmedia/superagent): 更 NB 的 Ajax 请求库，号称比 jQuery 更好用，前后端通用
+ [cheerio](https://github.com/cheeriojs/cheerio): Server 端的 jQuery, 相同的 API，支持 DOM 操作等
+ [node-restify](https://github.com/mcavage/node-restify): Node.js 的 REST API 框架，从 Express 中借鉴了很多，并去除了 render 等方法
+ [ejs](https://github.com/tj/ejs): Node.js 的前端模板引擎, 使用 <%=  %> 直接在 HTML中嵌入，简单易学
+ [Bluebird](https://github.com/petkaantonov/bluebird): 另一款实现 Promises/A+ 的库，相比于 Q，性能卓越
+ [node-amqp](https://github.com/postwait/node-amqp): RabbitMQ 的 Node 客户端
+ [Knex](https://github.com/tgriesser/knex): SQL 生成器，支持 PostgreSQL, MySQL 和 SQLite3， 用于和 Bookshelf 配合使用
+ [node_redis](https://github.com/mranney/node_redis): Node 的 Redis 客户端
+ [elasticsearch-js](https://github.com/elasticsearch/elasticsearch-js): ElasticSearch 的 Node 客户端
+ [Passport](http://passportjs.org/): Node 的认证中间件，支持 Express, 组件丰富, 支持多种认证策略，OAuth
+ [everyauth](https://github.com/bnoguchi/everyauth): 认证库，支持多种策略，OAuth，支持 Express
+ [node-oauth](https://github.com/ciaranj/node-oauth): Node 的 OAuth 支持
+ [restler](https://github.com/danwrong/restler): 一个 Node REST 客户端
+ [oauth2orize](https://github.com/jaredhanson/oauth2orize): Node 的服务端 OAuth支持
+ [Mocha](http://mochajs.org/): Node 的 TDD/BDD 测试框架
+ [nodemon](https://github.com/remy/nodemon): 开发时使用, 自动检测文件变更, 并重启服务

###### Express

+ [express-admin](https://github.com/simov/express-admin): Express 的后端，支持(MySQL, MariaDB, SQLite, PostgreSQL)
+ [grant](https://github.com/simov/grant): Express 认证中间件(middleware)

#### Erlang

+ [kerl](https://github.com/yrashk/kerl): 版本管理器, 用于管理 Erlang/OTP 实例, 类似于 RVM
+ [rabbitmq-server](https://github.com/rabbitmq/rabbitmq-server): RabbitMQ 消息队列 源码
+ [rabbitmq-tutorials](https://github.com/rabbitmq/rabbitmq-tutorials): RabbitMQ 教程
+ [ejabberd](https://github.com/processone/ejabberd): XMPP 协议的开源实现，用于及时聊天软件，Whatsapp 的聊天核心就是这个软件
+ [elixir](https://github.com/elixir-lang/elixir): 基于 Erlang VM 的一个语言，语法类似于 Ruby
+ [phoenix](https://github.com/phoenixframework/phoenix): 基于 Elixir 语言的 web 框架

#### Java

+ [elasticsearch](https://github.com/elasticsearch/elasticsearch): 开源的分布式搜索引擎，社区活跃，支持强大

#### C/C++

+ [json](https://github.com/nlohmann/json): C++ 的 JSON 库
+ [simple-rtmp-server](https://github.com/winlinvip/simple-rtmp-server): 运营级的互联网直播服务器集群
+ [mozjpeg](https://github.com/mozilla/mozjpeg): JPEG 图片解码压缩，Mozilla 出品
+ [libsass](https://github.com/sass/libsass): SASS 的 C++ 实现
+ [QQStars](https://github.com/AfterTheRainOfStars/QQStars): 基于 WebQQ 协议和 QT 开发的 QQ 客户端
+ [caffe](https://github.com/BVLC/caffe): 一个关于数据挖掘的库
+ [fastsocket](https://github.com/fastos/fastsocket): 一个高扩展性的 Socket 库，在多核设备上有良好的表现，新浪出品

#### Go

+ [delve](https://github.com/derekparker/delve): Go 调试器
+ [go](https://github.com/golang/go): Go 源码
+ [beego](https://github.com/astaxie/beego): 国内大牛开发的 Web 框架
+ [revel](https://github.com/revel/revel): 全栈 Web 框架
+ [martini](https://github.com/go-martini/martini): 另一款 Web 框架
+ [pgweb](https://github.com/sosedoff/pgweb): PostgreSQL 的 Web 数据库浏览器

#### Lua

+ [lua-nginx-module](https://github.com/openresty/lua-nginx-module): 一个 Nginx 组件包, 可以使用 Lua 来开发 Nginx 插件, 将之变成一个全功能的 Web 应用服务器

## IOS 或 OSX

+ [Harpy](https://github.com/ArtSabintsev/Harpy): 用于检测应用更新
+ [CRToast](https://github.com/cruffenach/CRToast): 现代、时髦的 IOS 通知提醒库
+ [Ono](https://github.com/mattt/Ono): IOS 或者 OSX 中用于处理 XML & HTML 的库
+ [CocoaMarkdown](https://github.com/indragiek/CocoaMarkdown): IOS 或者 OSX 中用于解析或者渲染 Markdown 的库
+ [Haneke](https://github.com/Haneke/Haneke): 一个用于缓存图片的 IOS 库，无需配置
+ [HanekeSwift](https://github.com/Haneke/HanekeSwift): Haneke 的 swift 版本
+ [RFQuiltLayout](https://github.com/bryceredd/RFQuiltLayout): 一个用于实现 IOS 端瀑布流的库
+ [kxmenu](https://github.com/kolyvan/kxmenu): 用于 IOS 上实现垂直菜单，支持上下左右等方向
+ [peertalk](https://github.com/rsms/peertalk): IOS 或者 OSX 中用于处理 USB 通信
+ [REMenu](https://github.com/romaonthego/REMenu): IOS 中用于实现下拉菜单效果
+ [RESideMenu](https://github.com/romaonthego/RESideMenu): IOS 中侧边栏的异步效果实现，类似于 QQ 中的侧边栏
+ [AwesomeMenu](https://github.com/levey/AwesomeMenu): IOS 中用于实现类似于 Path 应用菜单的效果，各种酷炫
+ [Alamofire](https://github.com/Alamofire/Alamofire): NFNetworking 的 Swift 版本
+ [Alcatraz](https://github.com/supermarin/Alcatraz): Xcode 的包管理工具
+ [JBChartView](https://github.com/Jawbone/JBChartView): IOS 的图表库
+ [PNChart](https://github.com/kevinzhow/PNChart): 基于 IOS 的强大图表库
+ [GPUImage](https://github.com/BradLarson/GPUImage): 基于 GPU 图片、视频处理库
+ [shenzhen](https://github.com/nomad/shenzhen): 一个用于构架和发布 IOS 的命令行工具
+ [ZXingObjC](https://github.com/TheLevelUp/ZXingObjC): ZXing(二维码、条形码扫描库) 的 Objective-C 实现
+ [PKRevealController](https://github.com/pkluz/PKRevealController): IOS 上一个非常优秀的，用于实现侧边栏的库
+ [KIF](https://github.com/kif-framework/KIF): IOS 功能测试框架
+ [Bolts-iOS](https://github.com/BoltsFramework/Bolts-iOS): 为了加快开发速度的相对低层级的库集合， Parse 和 Facebook 出品
+ [MaterialKit](https://github.com/nghialv/MaterialKit): 基于 Swift 实现的 Google Material Design 效果
+ [Carthage](https://github.com/Carthage/Carthage): 一个简单的、去中心化的 Cocoa 依赖管理库, Swift 编写，仅用于 IOS8.0 及 以后的系统
+ [JSONModel](https://github.com/icanzilb/JSONModel): 智能化的数据模型，有了它，再也不用手动解析JSON数据啦
+ [KZPlayground](https://github.com/krzysztofzablocki/KZPlayground): 提供对 Objective-C 的 Playground 支持，比 Swift 更快
+ [RMStore](https://github.com/robotmedia/RMStore): 轻量级应用内购买库，集成方便，使用简单，方便项目中快速支持应用内购买
+ [pop](https://github.com/facebook/pop): Facebook开源出来的动画扩展库
+ [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController): 一个优美大方的即时聊天 UI 库
+ [realm-cocoa](https://github.com/realm/realm-cocoa): 一个移动端数据库，提供了丰富的数据支持，快速，且不依赖 SQLite
+ [Surge](https://github.com/mattt/Surge): Swift 的高效数学运算库，基于 [Accelerate](https://developer.apple.com/library/mac/documentation/Accelerate/Reference/AccelerateFWRef/_index.html)
+ [Masonry](https://github.com/Masonry/Masonry): OSX 和 IOS 上用来简化 Autolayout 约束的一个库
+ [Side-Menu.iOS](https://github.com/Yalantis/Side-Menu.iOS): 一款精美的侧边栏实现
+ [AsyncDisplayKit](https://github.com/facebook/AsyncDisplayKit): IOS 上的一款异步界面引擎, 非常流畅, Facebook 出品
+ [Kiwi](https://github.com/kiwi-bdd/Kiwi): IOS 的 BDD 测试框架
+ [PonyDebugger](https://github.com/square/PonyDebugger): IOS 的远程调试工具, 允许开发者在 Chrome Developer Tool 中调试 IOS 应用
+ [ObjectiveSugar](https://github.com/supermarin/ObjectiveSugar): 提供一些 Objective-C 的语法糖, 类似于 Ruby 的语法

## Android

+ [Slidr](https://github.com/r0adkll/Slidr): 一个用于给 Activity 添加滑动消隐效果的库
+ [material_design_zh](https://github.com/1sters/material_design_zh): Material Design 的中文协同翻译
+ [galgo](https://github.com/inaka/galgo): Android 的日志工具，可以将日志显示在 Activity 的最上端，方便调试
+ [sweet-alert-dialog](https://github.com/pedant/sweet-alert-dialog): Sweet Alert Android 版本，用于应用内通知和提示
+ [Side-Menu.Android](https://github.com/Yalantis/Side-Menu.Android): 一款精美的侧边栏实现
+ [dagger](https://github.com/square/dagger): Android 和 Java 的依赖注入库
+ [picasso](https://github.com/square/picasso): 一款用于下载并缓存图片的库

## 代码效率

#### CoffeeScript

+ [coffeescript](https://github.com/jashkenas/coffeescript): Coffeescript 源码

#### TypeScript

+ [DefinitelyTyped](https://github.com/borisyankov/DefinitelyTyped): 高质量的 TypeScript 资源汇总

#### Sublime Text

+ [SublimeCodeIntel](https://github.com/SublimeCodeIntel/SublimeCodeIntel): Sublime Text 的代码补全工具，支持多种语言
+ [Emmet](https://github.com/emmetio/emmet)：一个用于提高开发效率的编辑器插件，前身是Zen coding
+ [SublimeLinter](https://github.com/SublimeLinter/SublimeLinter3): 一个提供代码质量检测的插件
+ [SublimeTmpl](https://github.com/kairyou/SublimeTmpl)：快速新建指定的模版文件
+ [Syntax-highlighting-for-Sass](https://github.com/P233/Syntax-highlighting-for-Sass)：sass代码高亮插件
+ [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing): Sublime Text 强大的 Markdown 扩展, 提供快捷键, 主题等
+ [ApplySyntax](https://github.com/facelessuser/ApplySyntax/): 辅助检测语法插件
+ [CTags](https://github.com/SublimeText/CTags/): Sublime Text Ctags 支持插件, 需要安装 ctags

## 云计算

#### Docker

+ [kubernetes](https://github.com/GoogleCloudPlatform/kubernetes): Google 开源的 Docker 集中管控系统
+ [weave](https://github.com/zettio/weave): 用于为基于不同主机的 Docker Containers 创建一个虚拟网络

#### OS

+ [linux](https://github.com/torvalds/linux): linux 源码，Linus 大神之作，只能膜拜了
+ [smartos-live](https://github.com/joyent/smartos-live): Joyent 出品的用于云平台的智能 OS

## 开源产品(论坛、在线教育、项目管理等)

+ [Edx](https://github.com/edx/edx-platform): 在线教育平台源代码，Edx
+ [alchemy_cms](https://github.com/AlchemyCMS/alchemy_cms): 开源 CMS 系统，基于 Rails
+ [flynn](https://github.com/flynn/flynn): 下一代 PAAS 服务产品，用于管理主机或者 AWS 实例
+ [jsgen](https://github.com/zensh/jsgen): 开源论坛、博客系统, 基于 Node.js, AngularJS, MongoDB
+ [libreboard](http://git.libreboard.com/libreboard/libreboard): [开源看板系统](https://github.com/libreboard/libreboard)，除了配色，长得几乎和 [Trello](https://trello.com) 一模一样
+ [paperwork](https://github.com/twostairs/paperwork): 开源笔记系统，类似于Evernote, Microsoft OneNote & Google Keep
+ [cabot](https://github.com/arachnys/cabot): 开源服务器监控服务
+ [firefox-ios](https://github.com/mozilla/firefox-ios): IOS 版 Firefox 源代码
+ [gogs](https://github.com/gogits/gogs): 一款开源 Git 托管服务，基于 GO 语言开发，类似于 Gitlab
+ [huginn](https://github.com/cantino/huginn): 个人代理监控，可以监控天气、Twitter、网站等等，并按照预设的条件发送通知给自己，功能强大！
+ [nodeclub](https://github.com/cnodejs/nodeclub): 社区系统，基于Node.js 和 MongoDB 开发
+ [keystone](https://github.com/keystonejs/keystone): 基于 Node.js 的 CMS 系统
+ [apostrophe](https://github.com/punkave/apostrophe): 基于 Node.js 的 CMS 系统
+ [reddit](https://github.com/reddit/reddit): Reddit 的源代码

## Awesome 系列

+ [awesome](https://github.com/sindresorhus/awesome): awesome 汇总
+ [iOS 学习资料整理](https://github.com/Aufree/trip-to-iOS): IOS 的各种学习资料整理，初学者必备
+ [awesome-android-libraries](https://github.com/wasabeef/awesome-android-libraries): Android 各种开源库的一个汇总
+ [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui): Android 各种开源UI/UX库的一个汇总
+ [awesome-courses](https://github.com/prakhar1989/awesome-courses): 关于计算机科学的各种大学教学课程
+ [awesome-ruby](https://github.com/markets/awesome-ruby): Ruby 资源集合
+ [awesome-go](https://github.com/avelino/awesome-go): Go 资源集合
+ [awesome-cpp](https://github.com/fffaraz/awesome-cpp): C++ 的资源集合
+ [awesome-elixir](https://github.com/h4cc/awesome-elixir): Elixir 资源集合
+ [awesome-emacs](https://github.com/emacs-tw/awesome-emacs): Emacs 资源整合
+ [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks): 前端开发资源的集合, 内容极多

## 代码规范&设计模式

#### Ruby

+ [Airbnb 的 ruby 代码编写规范](https://github.com/airbnb/ruby): Airbnb 的 ruby 代码编写规范

###### Rails

+ [Rails 代码编写规范](https://github.com/bbatsov/rails-style-guide): Rails 代码编写规范

#### Java

+ [java-design-patterns](https://github.com/iluwatar/java-design-patterns): Java 设计模式

###### Android

+ [android-best-practices](https://github.com/futurice/android-best-practices): Android 开发最佳实践

#### Bash

+ [bashstyle](https://github.com/progrium/bashstyle): Bash 代码编写规范

#### Objective-C

+ [objective-c-style-guide](https://github.com/NYTimes/objective-c-style-guide): Objective-C 代码编写规范，New York Times 出品

###### IOS

+ [ios-good-practices](https://github.com/futurice/ios-good-practices): IOS 开发最佳实践

#### Swift

+ [swift-style-guide](https://github.com/raywenderlich/swift-style-guide): Swift 代码编写规范

## 数据库

+ [postgrest](https://github.com/begriffs/postgrest): PostgreSQL 的 RESTful API
+ [pgcli](https://github.com/amjith/pgcli): PostgreSQL 命令行工具，提供高亮和自动补全
+ [mongo](https://github.com/mongodb/mongo): MongoDB 源代码
+ [nedb](https://github.com/louischatriot/nedb): 纯 Javascript 实现，类 MongoDB 的内存型数据库，API 基本和 MongoDB相同，可选同步写入磁盘，小项目数据不太多时性能很强乃至超过MongoDB
+ [TokuMX MongoDB](https://github.com/Tokutek/mongo): TokuMX 版的 MongoDB, MongoDB 的一个分支，支持更快的写速度，完整的事务支持等

## 博客 / 网站

#### 设计

+ [Dribble](https://dribbble.com/): 设计师必上的网站，各种设计资源、创意、分享等
+ [Design Museum](https://designmuseum.org/): 当代前沿设计，涉及设计的各个领域
+ [Behance](https://www.behance.net/): 创意&设计资源集合，Adobe 旗下网站(应用)
+ [Awwwards](http://www.awwwards.com/): 一家筛选评比互联网上最佳网站设计开发的网站
+ [gooood](http://www.gooood.hk/): 建筑，景观，设计，艺术在线杂志
+ [ui4app](http://ui4app.com/): 专注于 IOS UI 的一个网站，提供各种设计资源
+ [wookmark](http://www.wookmark.com/): 这上面有分享的各种各样的美图、设计等

#### 技术

+ [code4app](http://code4app.com/): 专注于IOS 代码的一个网站，提供各种功能实现 Demo
+ [CSS Tricks](http://css-tricks.com/): 各种 CSS 技巧
+ [html5rocks](http://www.html5rocks.com/en/): 提供各种各样关于 HTML5 的资讯
+ [html5weekly](http://html5weekly.com/): 提供各种各样关于 HTML5 的资讯和技巧
+ [rubyweekly](http://rubyweekly.com/): 提供各种各样关于 Ruby 的资讯和技巧
+ [javascriptweekly](http://javascriptweekly.com/): 提供各种各样关于 Javascript 的资讯和技巧
+ [ng-newsletter](http://www.ng-newsletter.com/): 提供各种各样关于 Angular 的资讯和技巧
+ [cnodejs](https://cnodejs.org/): 国内最大最火 Node.js 社区
+ [ruby-china](https://ruby-china.org/): 国内最大最火 Ruby 社区
+ [angularjs](http://angularjs.cn/): Angularjs 的国内中文社区

## 书籍 / 阅读

#### 前端

###### Web
+ [Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions): 各种前端面试问题
+ [what-happens-when](https://github.com/alex/what-happens-when): 一篇文章，详细解释了从在浏览器中输入网址之后发生的一切
+ [backbone-fundamentals](https://github.com/addyosmani/backbone-fundamentals): 关于 Backbone 的一本书，初学和高级都适用
+ [http2-spec](https://github.com/http2/http2-spec): HTTP 2 草案
+ [grid](https://github.com/aekaplan/grid): 响应式布局指南
+ [fks](https://github.com/JacksonTian/fks): 前端技能汇总
+ [AngularJS-Learning](https://github.com/jmcunningham/AngularJS-Learning): AngularJS 的各种学习资源
+ [You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS): 一个 Javascript 系列图书，主要讲述 JS 的核心概念和机制
+ [JavaScript-Garden](https://github.com/BonsaiDen/JavaScript-Garden): 一个关于 Javascript 的诡异特性集合
+ [在控制台中调试 AngularJS 应用](http://lyfeyaj.com/2015/01/07/debugging-angularjs-apps-from-the-console/): 在控制台中调试 AngularJS 应用的几种方法
+ [Learning JavaScript Design Patterns](http://addyosmani.com/resources/essentialjsdesignpatterns/book/): 学习 Javascript 设计模式

###### IOS
+ [30min_guides](https://github.com/qinjx/30min_guides): 覃健祥的学习笔记，若干个几十分钟入门的文档
+ [The Swift Programming Language 中文版](http://numbbbbb.gitbooks.io/-the-swift-programming-language-/content/): The Swift Programming Language 中文版, 苹果官方教程的中文翻译
+ [cocoacontrols](https://www.cocoacontrols.com/): 包含各种 OSX 或者 IOS 的开源 UI 库或者 商业库

#### 后端

###### Node.js

+ [node-lessons](https://github.com/alsotang/node-lessons): Node.js 包教不包会
+ [node-books](https://github.com/pana/node-books): 关于 Node.js 的一些书籍
+ [art-of-node](https://github.com/maxogden/art-of-node): Node的艺术, 一本简短的书，旨在介绍 Node
+ [Node.js 实战](http://nodejs.ucdok.com/): 以实战开发中的应用为例的讲解
+ [http://nodeschool.io/](http://nodeschool.io/): 基于 Node.js 打造的、跑在终端上的开源教学课程。

###### Ruby

+ [fast-ruby](https://github.com/JuanitoFatas/fast-ruby): 怎样写出更快的 Ruby

###### Go

+ [build-web-application-with-golang](https://github.com/astaxie/build-web-application-with-golang): beego 作者写的关于怎么使用 Go 语言开发 web 应用的书

###### 接口

+ [http-api-design](https://github.com/interagent/http-api-design): 从 Heroku 接口总结出的，如何更好地设计 API 接口

#### 算法 & 论文

+ [The-Art-Of-Programming-By-July](https://github.com/julycoding/The-Art-Of-Programming-By-July): 程序员编程艺术：面试和算法心得
+ [papers-we-love](https://github.com/papers-we-love/papers-we-love): 计算机科学学术论文的一个集合，内容丰富有深度

#### 其他

+ [til](https://github.com/thoughtbot/til): 今天我们学了什么，thoughtbot 出品，建议 watch
+ [tenant-point](https://github.com/soulteary/tenant-point): 租房要点，适用于北上广深杭
+ [linux-insides](https://github.com/0xAX/linux-insides): 关于 Linux 内核的一些知识
+ [慕课网](http://www.imooc.com/): 在线学习平台，各种编程学习资源
+ [alternative-internet](https://github.com/redecentralize/alternative-internet): 一些有趣的新型互联网和技术,主要目的是去中心化
+ [cocktails_for_programmers](https://github.com/the-teacher/cocktails_for_programmers): 程序员鸡尾酒, 一个特意为专业节日“程序员日”而建立的鸡尾酒项目！“程序员日”在每年的第256天。

## 科学上网

+ [ShadowVPN](https://github.com/clowwindy/ShadowVPN): 科学上网之 VPN
+ [shadowsocks](https://github.com/shadowsocks/shadowsocks): 科学上网利器(服务器端) ~ 墙外的世界丰富多彩
+ [gfwlist2pac](https://github.com/clowwindy/gfwlist2pac): 科学上网之 GFWlist to Pac
+ [7-days-nodejs](https://github.com/nqdeng/7-days-nodejs): 七天学会 Node.js
+ [PPTP VPN 搭建](https://edgepeek.com/articles/144-ubuntu-12-dot-04-shang-pptp-vpn-da-jian): PPTP VPN 搭建教程

## Git 相关

+ [gitolite](https://github.com/sitaramc/gitolite): 用于构建 Git 服务器 
+ [lolcommits](https://github.com/mroth/lolcommits): 给自己的 git commit 
+ [scm_breeze](https://github.com/ndbroadbent/scm_breeze): Git 流程的辅助简化工具
+ [gitlet](https://github.com/maryrosecook/gitlet): Javascript 实现的 Git
+ [js-git](https://github.com/creationix/js-git): Git 的 Javascript 实现

## 其他

+ [retter](https://github.com/maciejczyzewski/retter): 密码学相关的算法库
+ [uBlock](https://github.com/gorhill/uBlock): Chrome, Firefox, Safari 插件用来屏蔽内容（如广告等），可自定义
+ [rust](https://github.com/rust-lang/rust): Rust 语言源码
+ [font-spider](https://github.com/aui/font-spider): 中文 WebFont 自动化压缩工具
加一张杀马特的照片
+ [github-awesome-autocomplete](https://github.com/algolia/github-awesome-autocomplete): Github 的浏览器插件, 用于辅助搜索, 更加人性化的搜索结果
