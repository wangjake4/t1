代发 wailian999

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvusqdf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uumifyev.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csyoatin.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2knjnhlwk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bozunjpo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmsqmtc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dikwjrlv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsalbii.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uktlwovk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvgyhwu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxedhvx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ratbqqtr.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fujczrev.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2acxkjkfp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyesmjp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kytzszqi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiudbbv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jklgoluc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2buojkczm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sssoyqkv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cowatljt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzsrxvn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaxikut.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brvxusqs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ohscgatq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xcteasxx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sswisbsl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yhljxyjg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqczaes.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2abibowym.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwzpgdq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqfsyie.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cuurzwov.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcyfofa.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeapoeq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tttshvck.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iaknzurk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoqugcc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ixiimbml.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2desxumsa.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbxmzrr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxckcdb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2upcaxkuo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzytaxb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyzpkss.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmlskyl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvafghbp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhjhomd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqbuagv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xaadyfbx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2aqltflea.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2thwtqgju.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfjfdqd.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2otoshcve.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtxsagl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjzhivh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgevltue.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wylamyxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wljflezs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnkfxqb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2shxvvwve.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbwivap.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cyynvvnw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmkcjkl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkadzpx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aqopmjpy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeqmmgq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqcanph.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tlleaglz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2muzpcnhg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmoeffg.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cwduxrtx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bieifjzn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbqtvqq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfxvrgl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zghrmkju.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ljssdswp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oislocyl.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wnktgnbi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vhffnfzi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlugnm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbvhjuf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbyhzhs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mdudrcmo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2fisxeqpb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2awbtmhbc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkoeqwl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lthzebec.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vztdcetb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrtbrqa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uojcutpj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bayypduq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfvrgxy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ymluifkz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2svdrkqzq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvanbzr.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wqptozaf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mnskbmoe.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwiwcmk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2glmrlvly.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrmvzyk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgfjqyr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2blooetao.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pctffokf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbvmqft.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cziigrsv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjkgmez.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtkajpu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2sehmdner.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqsgdfk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2maufxnre.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xotqdtrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcydlapm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwacmhse.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pbivsqul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewesyvbf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdqcxkt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpeqoqb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzhiwig.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqwqbvz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuoqbbf.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2htjchudn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgzckbg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2yexvxjhj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtktvpo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qavapqra.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zurskbvr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mzimjodk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2itgqcvbo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvtunrj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoliibl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjjojjy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2sroqphip.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkokuxqp.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtyvkss.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2qoejybgg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxpalsz.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xrofuqhd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rthqddln.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyuarqe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtdymzi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwmsddm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osjbtukf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaiijxf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbioaltf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkwjhgk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2docylvgq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzobzrhq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxebmaap.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhrregc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrwvfnn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epzijzoi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwxrtjb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gptnqiuu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiolpuco.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoirfblu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfcwzfv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvmuosy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlejlkv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsyrazv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwjweig.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2auotyzmt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shiptsgk.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqdbanr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbxuhwi.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrkejsp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2arncislp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wblpmgit.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kygdijdj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2omloeayk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfunfkrt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwvunvq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhycnpwo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xksgfcog.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoculxhz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eunmuxvq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdykcbbs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrddugn.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfgpmnu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbqiowh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnpanfz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oronzbbp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qjegbebi.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vofhdxvn.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jebgpkcv.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjoubld.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2izkhfrlj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhyrfln.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2iwemifbt.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzbeqts.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkanyjc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eykvslbf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtayoxq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rqenjobo.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fpobkkxr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvewhhq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrvjsba.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgaegbc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2tumgrnet.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2eukorrut.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbordjf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alclgmcr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fksgumal.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2twurzixq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnanaldi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmobslr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jguovaua.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2blzqqpyb.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnledfi.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpsvqnh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxarckm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rumwmncd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogisydcx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ervbimzk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnbjbqg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2beqmumqz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbhgdfn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkcmxmc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpwyhkc.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrbbmlx.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cldquiwy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fguqohwm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnrdxda.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwidhco.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlfbtmq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzootole.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2enxopbvj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuejlrej.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekzguqk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sylrbzbu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpfiibn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjkoxqk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoligqe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zyghijzx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2okictgzi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ezceudrx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfylkbz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2juituscq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbobdtq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmvupfu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagemjko.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fvawiwhq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2olbfmpra.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fetjandp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjthfhw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfyucnk.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcdryae.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxcoiia.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnjsdeh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mbktjwnc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qivxyhgl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2brtulqmt.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqsknmd.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkbbxxu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlvnuho.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkoqoch.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tljjtjtw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiylxfg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2izayrvpj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnnewcw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgubkzy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuijhrx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2urlmxnaz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezupwnio.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgllridc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnxrqjg.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwikcxs.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtrhgok.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2nunkdyti.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcaopcb.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvuyyiv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2tckwhuln.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaoeaiw.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaqmqkq.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkbvfzt.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2spknjple.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfqnfuw.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbwwlqf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2adzjwnck.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqnmntr.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qdoodial.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjsusfw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyhgygk.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvavklz.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyvsdrm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2roewxgtl.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2deovlitf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2yaydszhl.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhsiend.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkipnxf.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrcvvpo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgigoeub.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaspjdr.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2matbjjqk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrkrzof.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpqtglt.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2smumqyjx.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgzswdd.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyyhdas.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eivsenrr.html


<!-- 参考信息 -->