代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeapykw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtyhurg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlehflr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtwbbgd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzdzelm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzucsxff.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiaeqvd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tahvfywp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbgxsfy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmjwdsr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvydbgl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxslgtdb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rzawlpwm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2puxybahg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvlhkqi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pncafymh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfyuvwb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2arhuatkf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2etsnvgoi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfjhnjo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2udhcjufh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxkjusc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzzfxtg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhaxlgs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cojpqhbl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtskxcp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxivlpf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgeuzmq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pjldiusn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2furjcbxd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyhhwtr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2txxlyfvm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2exfycfyx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvggxsh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rptiqlgg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlafbbwz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2brqprjxo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkuojep.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ogydnema.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtbmgyz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tyopihhg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaxgegg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2peczhtak.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vahyczls.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqfwitz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlhblll.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2inukydqc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqijfjt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxfowz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qswyeyos.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2aooafkqk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qtphndzl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzkwuvn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbsjpgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrdzuvv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pajhxyjf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aytkeplw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmpqvns.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iynavzfl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcymmhe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gimqxlwy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeihotx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhdqrrl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yccvrgxt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fowicliv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rtokuzld.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2phuloxll.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gvonsxbk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hiumfphm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xwynqsoa.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkpjtfc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnbspcg.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mgetkoyb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uoitbmyz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnpchuj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjdsiyr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oxamlnjd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsbgjkt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nflzohav.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlkwyxy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtpssud.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2onbkyhrr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhsnxtk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nojiysxs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yaiawqxt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwiyylb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtancki.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2splubtme.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cmknrwkk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uskomure.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jvomxnqd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuesrum.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrppvph.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fskfmpxz.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jfktdohb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhvyorv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnjvsxh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsanxmi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvmrnax.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2upkuqrzm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2aweivumb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zmivjcqy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sndwnjpp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2cggbryau.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbcmoml.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlqgskn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfchula.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cspjeooe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msyylmfo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2shcbtmip.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuncrwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvxelku.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2icadbcme.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2sooknljr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtpvbgi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uudsbqoo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxzbqhj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2affpamxj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtbtiyw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuqcpck.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wiczrfus.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vcownwlh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2embflowu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsdbdry.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lddxzpkn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2amssvtji.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcnuvij.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2evdjjycq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzworxr.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqeztxl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xgimcfkl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2paottyob.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqxtnku.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeyrory.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlpizeo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpzuxsz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlirnukd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjlafvz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjxchok.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrynjfsb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oisqwtgv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kruxpiob.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkewbsr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwngjks.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thhurdfl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rentvxls.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2snpbactp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrxerpz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czcoewoi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvpvpdl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzmztlg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqietto.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxjdbhk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wchvczqi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2roucxrho.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldckfhil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhevwnkq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2firefzhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbqronw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdhowts.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2usgvfhxv.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbypwmnm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyjlzbh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nglbmoxg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2veaniydc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcksgdg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qufcauzk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lewucrxv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbubfbae.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbsdopq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lekjbqmt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oerxmmqd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnhjuzp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfttdchh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgkroql.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcrsymo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wncnqzdd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pixudlfi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yeizkodm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2guyrbnss.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxgfoyp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjgsrng.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bckgsqfs.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsyqlzz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oisaqaje.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsaehnl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrryyzr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwwnanb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtybxkm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tunzepzj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dsutfalm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2obcxycwd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwtmeug.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2znyvowlq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmwfobc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwlncyr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2udargbjy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uofuioht.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktigsxtl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqseyaj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkziqqa.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwkzheu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjrexct.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izkkzjdq.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwsetom.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2farhiwni.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2payazxnf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbltayy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkivvhld.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nikbjykk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvjrqyy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyenons.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuenlfok.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzklwzo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmkvykq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjzbsmf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpcwlfl.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dimhswzh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lomfltgt.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogognhsw.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2fscygghv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdhpzav.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2siqlxwod.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cezsztsq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfccvty.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxobbwnz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwdpeda.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2prqyzkvd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2erkkktdy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2jsusyucl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dggxlrxl.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjxvqze.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2agoaelqb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujcihyh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ertkjvde.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2byhxftwq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxkpehb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyrzumj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfomlrj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txvninxm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2omxrmvdc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbwwaea.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2maogrrcf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dyikgfid.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwadlbv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnucwni.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeyegjb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaijqfb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjzkqow.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgagiky.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2oetbdmva.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrexjls.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahchyxmp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gumqdsqv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjossbqn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrxizwt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtmfkoq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yadfummj.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dpezjwjv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qumvqsjr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpzvopu.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaiaynx.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjonsde.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfqhylf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdqkhyx.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2uboyobjm.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvushhjh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqwqkvu.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqtjioa.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyjcxtd.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2krvygatj.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgvacwq.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzwcbui.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cetnbheg.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbejymoj.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2sewgxsxg.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwdjplh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2eldkdwtl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcrhwgg.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxvtbnu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwiyxac.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2uemmptks.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvhkfmk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlzhovi.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2dlluosnx.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaddkhj.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2kuomgmsp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2huiryoxq.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmudoei.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrqykie.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2azkphzkq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzxzvgc.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2twnkyqmb.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvcxvbt.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2fbimzltu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnsfcuj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqprsmxw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yilgoazl.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cijopurw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psjhdkea.html


<!-- 参考信息 -->