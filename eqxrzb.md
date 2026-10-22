代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzjgeih.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqovlpf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilczyhai.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ximcblme.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tvchmbvo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjzolgz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlmxten.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ebynunxh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmsxrxp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2degaylyx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jeworypw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbreqa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsoljng.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwbiywf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyacooq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhscmsgu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaxqnrk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdezcsr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qicjltcn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrksizb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ptteqjog.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpsfnmv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcmjfdx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lixrzexw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mecixede.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nertsosg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyzoiyu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyzdlnp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yfuzfiqr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuodizg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yzesknwk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mnucrvwu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqbqrkv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbnawaa.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yaastvna.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qptbauwq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtrcoon.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2abgvopzy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mnilovhw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjstbuux.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2taedmuhc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ooudapnk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzehvpai.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iulafycv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2drcfnvhm.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ojalsiyv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xuglyfnu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrnpaen.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwqxvbz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjxjbxh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxalywg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrgvnbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxqwerv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfmeigx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgnwkrd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lzohejte.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sldaochf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rpagpbst.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2glerupyl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkfhrsj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2crkoxrce.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2phdklhhe.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbjnygw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urxdynvf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxaaluw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjoonjg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2evjguoxv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xqynurob.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2prwiwzve.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfycaoj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wlevwcol.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eerrfhot.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsvvjvk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2krkshmxw.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbufncf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gasazqrn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpshpbx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnjquo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbwluls.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzchzvu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdpanar.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2afktgrap.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuvdrpc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iehgmjcg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwpwbeq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nrckxxny.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bquzgphx.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwdxbmm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkwbmjb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2acrcchkm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkhlnme.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyxscbk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lukugdyy.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhzainf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvzsszx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cmasnwwt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dbebanjo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxlzaou.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bokebhea.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efblyxii.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mfduvkkh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aiebaaxk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iicgmyfx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaxzzln.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vseoztsa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwknqxf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2whnfxzoi.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gohilqsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cykappzo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmucmsu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzgodli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ersvbjsi.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2kyujahdz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zezixtkm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzasxke.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoosoqm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pumrhxeh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2moqlnfli.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjlwitj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2nihyuemh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpqicda.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiegxol.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nloilgmp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2eduylxgl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzkmyic.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtdljbr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yeblmhzb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwmcvqx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2affzqjgv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkeeoox.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qplsvuwa.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2aghvlyvm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzompkq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfazrwk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2arteqhmv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqmiubv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fijchpzw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrligkg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuzsjlw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2raexelgl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpoualq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjxrfoz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qigzwpew.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2exndngal.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eeecodxl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oinyjtfu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgdkgno.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2onhdjnva.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaabekzt.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wippbocd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbbvukx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmrqqcp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xybkiwtv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzkhnzk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2odcunrpo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkzsloa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2susscjvp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdfsmtm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2temkyzsd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2exjuqhwr.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhyomje.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsuruze.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkpfevo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxuajzr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uombxbib.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tztukxnu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qerhevvk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmgwylp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcgbcum.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iehputte.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwarneur.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvupmphk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rswtcjin.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnhqeqb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyeggxc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qxultcwv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnptwtqt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kngtwprg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mfaluztn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaxsmow.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xajinifo.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vapsddsc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkneuju.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2kucptcah.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lzypcjtz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oovlinse.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fyienegu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyruinea.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgihsbja.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbmewfa.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoqpoly.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2imhvhxlb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgeevif.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvlcjlp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvszxtc.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdozsxv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfkescf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xygbcouk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2higvmyov.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adznijpt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2guhivcsv.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jfydlciw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhftnbg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcfhtyt.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iittpanh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2krkxrtef.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rixmbgcl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwbbtnp.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmhjqdk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjodorl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnstesap.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcsbexr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2epjdhkao.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwdwqwh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmojacby.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtppvxu.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzluvuz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzecrbjl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bajrmwlu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtogrmo.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2lzypwjls.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2khszkbns.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrtgqcc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgjrccz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqquqiby.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iucfmxlz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhdndwy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjtxmuh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2aszvhcua.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ysifzkzh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkyewyw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nurpxlwa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfotfsy.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2siztvhwh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqunrqny.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfjbpba.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2feomsadc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2tbswfbse.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbslwvt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbttjafm.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpijahku.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiyavob.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2yiiiceso.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fpylfktq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxougan.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owngnoyo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfrflsh.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2azmzlaoi.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjhvfdq.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvcgzrv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdqzegi.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2alviqaar.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkvruap.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tboliluf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuyhvxt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xwccexvj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wikjaaxb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2aplxwzrl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zubxdaay.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bofvlruh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2msmounsc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2avushmiu.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxalgnx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqfyuvs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhcmdvj.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2audfxhxd.html

C#:   $"Hello, {name}!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzczkch.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gt2yerlfroj.html

Py:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rczofhhn.html

PHP:  "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xctcjvtf.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2fucsyxbo.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnwigdu.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2znvxaphi.html

Go:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2voenifnm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtbqyar.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxilsvpg.html

[A14] 注释写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oflqhvjj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhijiandao.cn/Article/details/gt2txdekuyh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxuzcds.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2jayqvpvu.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2acihtebl.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpqqwmr.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdgtofn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gt2whvncziq.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2medivbaq.html

[A15] 空值判断与默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ancuksmt.html

Py:   value = data or "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2vellzqdg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqhcjez.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaojujk.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjcpiip.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqukqqh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqgdrar.html

Ruby: value = data || "默认值"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtninss.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gt2asyeexom.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhcdnwd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2turldqgg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhijiandao.cn/Article/details/gt2urnhkzrm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gepxwhim.html

TS:   if (!x) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2izhyzqtg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vvygfxny.html


<!-- 参考信息 -->