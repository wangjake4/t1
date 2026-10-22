代发 wailian999

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cuovgaxo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzfxlki.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2msqguygy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqbepkq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gzebxuyi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2penfsdhl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yufdgppd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrybdhe.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxtwfcu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rflwqfcf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fassxcym.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeyghra.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2retdurwj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2efgaosra.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2evqptnve.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzlhscw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcuurii.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbbzyss.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzhapdh.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cscfgakh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rfotvcbu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wusptagy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eashzljr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvshcgw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ziimbusl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2okjrmuui.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfhqrmf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stmjtion.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvdxuuj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkvfemg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdrhnde.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qykpcilb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2icbslngb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gzncayav.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tupltutk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2realvrou.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqutlfz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qlahccpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpykvvyg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eneqprfg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmyzlbv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtafopq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoovjbb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jffmfaro.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uugwdduc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fykxcmsr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2psuxwxgz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmrqlay.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqwppwc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmxpcfj.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvdsoez.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdzopil.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lcckwkzx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2voiwbwqk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2raucgkcd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpetowo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2foqstbhl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfhqvvl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qeejuhmn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iluazfrd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2etmcvpwz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtmbykk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cerpcoch.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvoxszc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fopwcayn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2spuzqicr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zouwkeyp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmhkkvf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgsjhcy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqcvebt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyomenw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lrphrvyh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2shjktzof.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kajuziil.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qykzrduj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhfxdlw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2injzbsoj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hiluenjk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jausxgyn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjdqbgv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2biaazykv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbwoknb.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqxyimj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvddnol.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2htartrtx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2koxkpswq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjowtonv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yefvyyef.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ezugyfdg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgzzasg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlhwtsf.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuhpilx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvupnxx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pactvmkv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyixosj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2peroocdu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2frfhycns.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzamlzp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kweyeziw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhoudun.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkfyaxx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxtkojh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2scxgzbgm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xujaeaak.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hgotvytu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtudhbe.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2glpagzpf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqvsngh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2eptagjax.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbjfkak.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrcxxej.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcfmbyu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2njalbbbr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2onmlwktt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyilsiz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dowuymeq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsrlnss.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vsawqrwb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mcexopjt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waoaytgf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuoqyvl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmalcexa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtiaofu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxomrjr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlftuxs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exweaiah.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adjqlyhv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhpjyah.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyiaqfp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nypriudb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zceixxpi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcyfvqp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eppuucje.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbutjqw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2halzsbzi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwrwnjv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhgjilh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2owxlqzsy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsioasqj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpyvorsg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pipcpxyi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmppgci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlgcbij.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmqqzmh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfeaqmi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nntvktem.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcckxzpe.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfocntdv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcxxefo.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkdhrmd.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kipnyhst.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2itkmzgko.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvxetgb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgigekb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2irfdtvpj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdzxdor.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2afrmiuqf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmfyaye.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qqauqfby.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeqrwfr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2towwyguh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jwchxdhm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jousijbg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqcdoun.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxehaxw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwgvnry.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrcajhm.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xtexlmkk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlqcljn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxckixmg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fitsqkgm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnggokd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2glbsrwum.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyuxpap.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdiyuxk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlnkdtg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaagkge.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2fckxxoij.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cripdbua.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmqqhmy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqpthhm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzjpudq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eutfkgwk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vqulcwaq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dibvrnhi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzmxedy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2echiarpc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iojmvemf.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2egldilzv.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2clypbwrx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xyacducy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvwgxyy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gthogggs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nimrzaky.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzomjcl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2umxcmhdj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkljomsd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtdxuup.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eynscjke.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsdwuyp.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2etjfmoil.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rorsolpi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvnrppw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2alxzoola.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2frnuaamk.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2csioynzg.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvflaax.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhmijlc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asugmeky.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyuihej.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyjwhac.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnqrysa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxkliue.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2fbirwycj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnztwrm.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoxuaqk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbukgxls.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2izkyqkgm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktepzmea.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmivgsuy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhpwjkt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxtzcrc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcmnuqv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfbqlor.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqhxejf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffidkzog.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2byacqwqy.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kccifdud.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jesxujzg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmyhplr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxdhcrp.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2wocaseeu.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2cynvakbe.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwximnl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gtltfeeu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjitmaxg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeobivd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgjxfxv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2boheyrfh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvmcwaj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2onlcxylm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2asjffqgk.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhmkiiu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhbazjl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2elbngqmh.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpexxbh.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fsncjgdt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfzjodc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2teudjytb.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2evluoyna.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtocvia.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvzpkti.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdszkmc.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hueseglx.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoemjhv.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2owuqhyts.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfydldb.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgthmphh.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjdgbws.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2asykegwk.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtbvsnt.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2urkrsfjw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2obcnlmgs.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdomlqz.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvhywmg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2pmndtuaw.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtapqvn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2ktksvcht.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2igwmkueb.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2erkiodna.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktryshkh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgeulsp.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnqmzic.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ficltlio.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyochikl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2taibncos.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcjjllm.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkvemrs.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzwhtwq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdldqcv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrwrdtt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jscneplo.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbpghyt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlotgz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vbomkggc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qfotuxii.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqiqmhwp.html

[A17] 位运算
来源：http://dali.zhijiandao.cn/Article/details/gt2azqetsye.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cyovpeuw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xnyrudho.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdxgvwu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2snmiueht.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyoqmht.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrbkuhm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aywwfhsv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsamnlt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cxshofzq.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwsxwdk.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcaoizq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2cydiewrp.html


<!-- 参考信息 -->