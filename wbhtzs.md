代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agxbvfzp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuiqhvl.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmrflwj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbcwlfa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjppzcp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vosefxiq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bapqtyns.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zelypxfs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uujmbufn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vklrpzga.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2goovlzqw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2klmdtjgy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ycespezo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksohmioa.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgncstbx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2sotowqul.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgwgyef.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jletqjas.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2fqatzxnh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2foekinnd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2krvlbtzd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xeerugtn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2axymaqlh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvsgxlb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fegymxyg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zewxyahv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtcvtnw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2buttwhlc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tcymdtnq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxytrea.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2trqaxefb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dharmozb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vayzvmzf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxluzko.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmghyja.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rltdrzxc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnvxyqf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmqsjuc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2egqyrgge.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdmuysz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbfgclf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxtvomc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjehmllf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzkqcbh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wbefrzgm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmjfgaj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2axhbzfmy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tabzdtgk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mkytryxs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2itnytvxx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pjatdjjd.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2atckrsdt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bninpnyz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqndgbf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kchkcmdy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wlowwuyr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2adsdnywy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ayynjsjf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhgckbm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zgknfjan.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dsspmhuj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhmzpim.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2njnkqdfs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxwtoed.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fhinqcqg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyxxelj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfunvgu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2evfuxubx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2oddvmtpw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfytxtc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pglwapws.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqpmjqz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uppjlftg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lvelzbqb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxrllsq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmtidfx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqsxxdt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrceret.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbtxfbo.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qopoaari.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuzhohn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xxekdrxs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhumgxe.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sawvrhgw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtfwxdy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmdmfxn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqhytja.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zurgarxg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2aonglcsb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvohvyw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2shliazns.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vylccmfj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2achffkqb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrkbzsb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqttoqq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2foupshbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afbtsycp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovekrlux.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhswcqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ochanrlb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uoefzqig.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zttochtf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2odfyrosx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwpfolw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2engaiqci.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqqnsoe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2svdtdbwp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdxscpv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfyckab.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpsnmvn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwaskxi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nixoaebw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxeaeki.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2plnbwxqz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsxlcky.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxzxga.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoclzwr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgirjcs.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2buosezrk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqnjknr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sblkwiwz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ghommuol.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbajryi.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svmlnbvl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2efmdgyee.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okfkazzm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2frsnxhmd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxfvywh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2chokyzup.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erqwpksd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwohhua.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeflabg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzupyyc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxswzdzh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkoewnb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naujabbw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjwemxv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgxwytz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlefvocz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwwmzqj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtvuafh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgjpeeh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuijrthe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgbwucq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aazalyny.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zriaawzq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdvcuxf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcuenwj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yidqesil.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhrdesj.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hznmrchl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jembgfiq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwnxmwk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxhnbuc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2igyeqynl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqgnmoe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydspfnqk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rnaiwgfa.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjwjuwv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxbnwux.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoartuan.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aakuugrd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2repvblhy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kuiypqnn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpepzcz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqbozqn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqaqktm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdbmuxd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xisejsoh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbusxrdb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrsixvc.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnawenx.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qapurehe.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2awfrvbcb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbfiivk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjargay.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2puthajmk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxxketf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2guqtfbyw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lmphbswh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2evzkngar.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogndaucb.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2psvrzuxc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2iszqwtvs.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwnhtih.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjordut.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmxqhfn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqlobkn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjzukys.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oixaytwe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2itjbxmeu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hflnwapz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zihvtzzm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhrdiop.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbqjaxg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzukmtg.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzwfzkn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2btadfwas.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhytbwit.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsjpvko.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnutnnk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2txvabany.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucktwsxk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bctkipws.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiraogy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ursilqxx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bloippig.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmnaaij.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpzdcwe.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2afapnbet.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnulyrk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxzvljq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhswmmzm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqclfgo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojciehoj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzamaxug.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsffllfw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvmuphu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuhvrfk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcqfttm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvflftb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amsfvdcd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2srixnjmv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hphtmwur.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfnfnzz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxugyww.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2svrzbvtx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpbgiq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iglvufeq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervxppgh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtrgiin.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdkdapn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuqysqe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2feigtywx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2stsqudtc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsbhesy.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhadlea.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqorufzg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2foluxbqd.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2knyfpmws.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpmfknj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2zadpqjwm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqykjdos.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqlzmhd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgttqqm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvljypm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ccilkiyi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxccywri.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrigrur.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2plngronu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rljluyqb.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2kucpshmq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaxsudl.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbdbcgx.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufciwipt.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgdcbnr.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2aveeaqjy.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lokzgrkm.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2exncfwrn.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfgpmdw.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2undvesdm.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wphsjutu.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2pltzuyuj.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lutpfnuc.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxhdkig.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2otqqnioj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcbpumt.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2hypbubhv.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2xwitjohg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiqupca.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2acfxlolh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlcvjhs.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2aadjzleq.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeqfssi.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvigsdy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwoukrx.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bptgyvec.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkkinis.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2yusnejts.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwmobib.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrliphpu.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2bsipumyv.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2opusiznr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xpomprmf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2uktfiqrq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzzjgll.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvsdvaa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rszcbbxx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnocpvv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsgqtke.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trnopzka.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaxghqg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhikbcow.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfhckuw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzdhapr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxronvfs.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2btgkrvrj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbljgoww.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2msoyjoig.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqvupxm.html


<!-- 参考信息 -->