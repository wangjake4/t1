代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.jlsjyb.cn/Article/details/gtfuenvgqy.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gtfguvqowt.html

[U96] JS：async/await 与异常
来源：http://dali.zhongyouzk.top/Article/details/gthinohrpq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yangfankeji.com/Article/details/gttugphnxx.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtwotlypjm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtpcvhssmu.html

[U98] JS：fetch 带 JSON
来源：http://dali.jiagoushi.top/Article/details/gttghrkabt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.feifeiyinyue.top/Article/details/gtbozcqrti.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gtopafavjs.html

el.addEventListener("click", e => {})
来源：http://dali.tanke756.top/Article/details/gtcindijbh.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gthhpdkksl.html

document.querySelector(".item")
来源：http://dali.haohaochexian.top/Article/details/gtsxvlvfcn.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtdvcucfyo.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtxwnhakge.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gtskrxstul.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gtqzyobqhq.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gtcjffslqr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndrcyzyr.html

[U104] JS：防抖
来源：http://dali.jinqigufen.top/Article/details/gtuzcanwov.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtiionfwyg.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gtivoisnev.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gtqhoqyfua.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gtinorprku.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hysaishi.cn/Article/details/gtyodovzrk.html

[U107] JS：数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gtagfodcsc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtgyiajkty.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtvvxjqexa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtsfydfxyz.html

[U109] JS：数组分组
来源：http://dali.tianlin.xyz/Article/details/gtiwvghlns.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtoodwdjgu.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gtpziitper.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zycfv.cn/Article/details/gteiufvvgm.html

[U111] JS：对象转 Map
来源：http://dali.aizwys.cn/Article/details/gtdbskxjkx.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtojgnsxut.html

[U112] JS：字符串补位
来源：http://dali.guannengcc.top/Article/details/gtijvogeen.html

"7".padStart(3, "0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuykslqwr.html

[U113] JS：正则替换全部
来源：http://dali.yj20258888.top/Article/details/gtdhlaobwb.html

s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtjwotygpi.html

[U114] JS：JSON 深比较
来源：http://dali.zdqjudy.top/Article/details/gtgmegxcqf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtakcxymko.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gtewegeqtc.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtqxsdmjyq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtwmzptksu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtgcsvarzi.html

[U117] JS：单元测试
来源：http://dali.wangdashe.top/Article/details/gtfqmcfllk.html

npm i -D vitest;  npx vitest
来源：http://dali.xuanzx.com/Article/details/gtcpuoljwh.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gtyuczwuua.html

npm i -D vite;  npx vite
来源：http://dali.chenzaomai.com/Article/details/gtxybzuoac.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtduitakzw.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtstxfkshd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gtqxtncbqx.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtjjuiicrh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtoabbnldz.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtjoafegcw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtolirmrec.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gtdwfjviyw.html

Python ......... 252
来源：http://dali.quarkkingdee.top/Article/details/gtfquevmmu.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gtetttivft.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gtmiqqmgzw.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtisufhtyp.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gtuldogsca.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gtybbpgyjv.html

Ruby ........... 212
来源：http://dali.bjfxy.top/Article/details/gtfexdzmez.html

C# ............. 212
来源：http://dali.cucudq.cn/Article/details/gthlkjanfw.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gtsntkqaip.html

C++ ............ 30
来源：http://dali.zdqjudy.top/Article/details/gtzftvazei.html

SQL ............ 90
来源：http://dali.0kj1m.cn/Article/details/gtqjpjdzgd.html

Bash ........... 80
来源：http://dali.9152youxi.cn/Article/details/gtyopndoaz.html

Kotlin ......... 15
来源：http://dali.ppjwa.cn/Article/details/gtszxxzoic.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggjltrox.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gtkpixosex.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gtfhigyzxb.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtgypteexo.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gttibjbbkp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtwxolfbgz.html

按章节统计：
来源：http://dali.jqgufenzy.top/Article/details/gtzjfurvvu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtbycxuxmk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gtzvpqwudv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtkjyxreiy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gtdhqzkcek.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtxtwbigox.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtjpywnuil.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gtappfkteb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtmfubfjiw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtzjxaoswn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtojpdprls.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtgpwypcst.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtzodgjfwo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdervfevu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cashguo.top/Article/details/gtkoassuwz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gtzuailprh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtrcrwnzml.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoorsreb.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gtkhajiloi.html

S C / C++ 专题                          60
来源：http://dali.sxryk.cn/Article/details/gtqtchxosp.html

T 其他语言补充                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsskhtjeh.html

U 高频实用片段                         120
来源：http://dali.shangyingyoupin.top/Article/details/gtdejwjmwq.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gttkontxrv.html

合计                                  2106 条
来源：http://dali.yangfankeji.com/Article/details/gtvmxmmwcs.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gtozvnqput.html

使用提醒
来源：http://dali.iojbl.cn/Article/details/gtcxeghgvn.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtmyztedep.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guowangkeji.top/Article/details/gtwhbqzzxf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fengsongda.top/Article/details/gtqgihhmwj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yj20258.top/Article/details/gtcpirtggr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gzhubu.top/Article/details/gtrvvltpsp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hammf.cn/Article/details/gthrblmfrl.html

—— 文件结束 ——
来源：http://dali.cashguo.top/Article/details/gtidvactrm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtlqhqdbfx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gtaqfieowf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gthoiximuv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtiwnrflek.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gtthluhdpy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gtwlpxcuts.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtagsbuaxw.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gtopyljivo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cashguo.top/Article/details/gtndysxgfl.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtussnldaw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sufxvd.cn/Article/details/gtoyplzhlx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pycfn.com/Article/details/gtiqssppop.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.quarkkingdee.top/Article/details/gtutunqjmg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gtqiaufgfj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dashuyun.cn/Article/details/gtmussfkzk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenjidiqi.icu/Article/details/gtzodoqavo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gtnmkefmbe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ydzc1.top/Article/details/gtlepnkmwd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtxdsgkann.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeohcduw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jianghu66.top/Article/details/gtqegipxlq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhiwuduotai.top/Article/details/gtouwedoss.html

【文件统计】
来源：http://dali.ybcxt.top/Article/details/gtypvzwakn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.redwolf501.top/Article/details/gtntrjpvcf.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtojmfpwdb.html

目  录
来源：http://dali.ybcxt.top/Article/details/gtzufrkwet.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtsjxjptuz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gtrvorrpfn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gtkimbimor.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtpoiianel.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.snrcjt.cn/Article/details/gtwzckiong.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqhwenot.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gtoktumlid.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhixingplan.top/Article/details/gtrqibtjwv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtbvjoiqor.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtmzqtgcln.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xziqi.cn/Article/details/gtcxccoezz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtzovrhfux.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtkpachsfg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.0kj1m.cn/Article/details/gtgzgebeuc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtlnwobevu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gtegptzcgl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjljproq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtmusdhzaq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daxiang520.top/Article/details/gtioupydwj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gtmsmxhiyp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtfayxexpq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtnhniycjx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtkahmetob.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gtmvlmzwxv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtossdfxfr.html

[A01] Hello World
来源：http://dali.cdnleiting.top/Article/details/gtlxqisdmz.html

Py:   print("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gtzwrynzdd.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangtech.top/Article/details/gttzselged.html

JS:   console.log("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtdbcnmfnb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xinyue.icu/Article/details/gtepalhkpn.html

Java: System.out.println("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtkklovnuf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gtqpnilrxr.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gtkailuedx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtclsbvixy.html

[A02] 变量声明与赋值
来源：http://dali.yonumen.top/Article/details/gtleoesagj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.nanxuanxn.top/Article/details/gtbezceezv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.daria6918.cn/Article/details/gtrjrtmfce.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtvjiutmzs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.svipenyu.cn/Article/details/gtuguxijpl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtnynldvte.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojokgwoh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtwxwdhcab.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ydzc1.top/Article/details/gtutvjfeiz.html

[A03] 常量定义
来源：http://dali.gaohongyu789.top/Article/details/gtieommghb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuxming.cn/Article/details/gtvdrmctev.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtstkpqywc.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gttmzmzxmk.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtkbuaqxdl.html

Java: static final double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtrsryqjdc.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtnmxzsjvk.html

Ruby: PI = 3.14159
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywzudrfc.html

C#:   const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtsblkaubc.html

[A04] 判断变量类型
来源：http://dali.gaohongyu789.top/Article/details/gthriqretz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gtrevmlgud.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yanxiufei.cn/Article/details/gtqepqggfz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtvxybkkzn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gtzqzwfwpq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.snrcjt.cn/Article/details/gtcxplbjll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gtjcdihpih.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gtsmtcqjqs.html

C#:   x.GetType().Name; x is int
来源：http://dali.tianlin.xyz/Article/details/gthtottfac.html

[A05] 整数除法与取模
来源：http://dali.pycfn.com/Article/details/gtvrnlymsy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.svipenyu.cn/Article/details/gtwkmwtapi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtzlqpvrqp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtfiamkflp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtulrhxjkj.html

Java: 7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhyewnms.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtwlnvsrft.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gthnkrmpvj.html

C#:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtlpygnbul.html

[A06] 字符串转数字
来源：http://dali.yj202588.top/Article/details/gtgoqpiqsx.html

Py:   int("42"); float("3.14")
来源：http://dali.xylfe.cn/Article/details/gtjavqnhsg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gtgozksfzo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofkdigqf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtdhahejin.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ydzc1.top/Article/details/gtjtgjkoqk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fengsongda.top/Article/details/gtlmdtocjt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sxryk.cn/Article/details/gtaharrfbw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqprehzd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnzfssryt.html

Py:   str(42)
来源：http://dali.sufxvd.cn/Article/details/gtsjsfenfr.html

PHP:  (string) 42; strval(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtbmbvobqo.html

JS:   String(42); (42).toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtdsfbeduo.html

TS:   String(42)
来源：http://dali.tian-w.cn/Article/details/gtlhpsvrgj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.vqdsnc.cn/Article/details/gtxlgzksce.html

Go:   strconv.Itoa(42)
来源：http://dali.shzxlz.cn/Article/details/gtebismzkr.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtecrvcofx.html

C#:   42.ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmaipwacq.html

[A08] 取整与四舍五入
来源：http://dali.hongshengwenyu.top/Article/details/gtvawraoft.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtaixoymyy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zdqjudy.top/Article/details/gtoegsauog.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtfoxiyvkj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gtnedfzbck.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gtvjrexevu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtknrlyfda.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.fengsongda.top/Article/details/gtrwlddgkt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtckkzfsnu.html

[A09] 绝对值与最大最小值
来源：http://dali.yonumen.top/Article/details/gtdgrlrbrq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtczhpjyjd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtgxpxdawz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtghjulxpj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtbttrpnoq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtwacexpgf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.guannengcc.top/Article/details/gtmrnkhvns.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtrdwswuup.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtmfmsekax.html

[A10] 生成随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmeqhhfkx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cashguo.top/Article/details/gtenkejapy.html

PHP:  random_int(1, 100);
来源：http://dali.yuanzhike.top/Article/details/gtmbpjrzml.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuanzhike.top/Article/details/gtwrnsddcg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gtnuzkzmrx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gttpwhaimp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtmxdjrzyz.html

Ruby: rand(1..100)
来源：http://dali.chenzaomai.com/Article/details/gtfwfehtjh.html

C#:   new Random().Next(1, 101)
来源：http://dali.aizwys.cn/Article/details/gtfxkmdlzx.html

[A11] 条件表达式（三元）
来源：http://dali.yj20258888.top/Article/details/gtxgjnthhj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhixingplan.top/Article/details/gtvsoijyhz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtskfxpdds.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtyemfrppy.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtcsoimeur.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtvwwovolb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhmnwulv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtzyemkhml.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtzbvncetv.html

[A12] 字符串插值 / 格式化
来源：http://dali.gotoacloud.top/Article/details/gtrrwbibor.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tanke756.top/Article/details/gtejhkywqg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258.top/Article/details/gtxafxerhm.html

JS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gtgtdyejqs.html

TS:   `Hello, ${name}!`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteritogoi.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtpmodjuol.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiddjclrz.html

Ruby: "Hello, #{name}!"
来源：http://dali.zdqjudy.top/Article/details/gtnqlsmcnc.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gtxvezasjx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtwjdprzfd.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtdqdnqslr.html

PHP:  "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtpytrbwcr.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtoowckltj.html

TS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtnyffhcyu.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtknaplfuz.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gttkclqybm.html

Ruby: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtiwkzaals.html

C#:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtrjflygjq.html

[A14] 注释写法
来源：http://dali.mhx1999.top/Article/details/gthsrzksgp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.9152youxi.cn/Article/details/gtafzfuvek.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtwzxnezmh.html

JS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtyfcokrox.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtatxhtrvs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.snrcjt.cn/Article/details/gtjeplmqjr.html

Go:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtnfvpthbj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnqzz.top/Article/details/gtlrvnhwyh.html

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtzftenibu.html

[A15] 空值判断与默认值
来源：http://dali.sweek.top/Article/details/gtdaieadqp.html

Py:   value = data or "默认值"
来源：http://dali.ivvv.top/Article/details/gtsptzewhy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtatfmsfcz.html

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gtwdwpyyrm.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtuablqbnw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guowangkeji.top/Article/details/gtvovrsrph.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.kuanghao11.cn/Article/details/gtthwpcgpg.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtyiaxxxmh.html

C#:   var value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtltzocwhv.html

[A16] 真假值判断规则
来源：http://dali.chenzaomai.com/Article/details/gteanovtkc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhixingplan.top/Article/details/gtpwjudoje.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yanxiufei.cn/Article/details/gtisbfutbe.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shzxlz.cn/Article/details/gtpoyklpgk.html

TS:   if (!x) {}
来源：http://dali.jiagoushi.top/Article/details/gtwzqjkuxy.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jyoumei.cn/Article/details/gtytwivbgt.html


<!-- 参考信息 -->