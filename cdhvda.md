代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.zhongyouzk.top/Article/details/gtokscgopf.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gtmouptyjk.html

[U96] JS：async/await 与异常
来源：http://dali.jinqigfzy.top/Article/details/gtgsajwvro.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gtyygbxuyb.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwudjjrnf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ivvv.top/Article/details/gtkerbgedd.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtkmmflblw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gtwrhrbtda.html

[U99] JS：事件监听
来源：http://dali.haohaochexian.top/Article/details/gtyipvnbjc.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gtenbukamn.html

[U100] JS：DOM 查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtipxmvhsd.html

document.querySelector(".item")
来源：http://dali.yuxming.cn/Article/details/gtatgvpspl.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gtlmrligch.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gttomcfrsx.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gtsmavpkvn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cashguo.top/Article/details/gtplfgoiba.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtbjwggcfn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuanzx.com/Article/details/gtlitowelz.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtjdgovvev.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtztydareu.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtalcajrdk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gtxdeyerii.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtdqtrggfx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.svipenyu.cn/Article/details/gtezljzwxp.html

[U107] JS：数字千分位
来源：http://dali.jinqigfzy.top/Article/details/gtpvxbrplm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.guannengcc.top/Article/details/gtdcuxaedf.html

[U108] JS：随机整数
来源：http://dali.jinqigufen.top/Article/details/gtekhirsbg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.xylfe.cn/Article/details/gtngtnbbja.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtsdlmlyij.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gtuovyaiit.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtoyuglvvn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtamazsfpr.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtqvuwaric.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtpbfhhjsn.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gtimzzhtgm.html

"7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtnqluocqh.html

[U113] JS：正则替换全部
来源：http://dali.guannengcc.top/Article/details/gtszipamqg.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtfdpmxqmz.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gtirxepvzp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtbonuxwbw.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtaqtptkjz.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtgakjsywe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.havefunace.top/Article/details/gtdizvtyql.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtmtahrikc.html

[U117] JS：单元测试
来源：http://dali.hysaishi.cn/Article/details/gtuwnnumrw.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtxxzmjhly.html

[U118] JS：开发服务器
来源：http://dali.ppjwa.cn/Article/details/gtjtfcfubx.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtdyvjhbzh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gtsnjrniek.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtfmniumxp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gtvuakapzc.html

import.meta.env.VITE_API_URL
来源：http://dali.gotoacloud.top/Article/details/gtvxnxazyn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtmvnfovxc.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtjvpxpkqz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gthtluinro.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtbzokxcoj.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbnyoatc.html

PHP ............ 252
来源：http://dali.ppjwa.cn/Article/details/gtcblkcygh.html

JavaScript ..... 252
来源：http://dali.yuxming.cn/Article/details/gtdnnisbbk.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtftgubwev.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtpuvfqlqh.html

Go ............. 212
来源：http://dali.daria6918.cn/Article/details/gtsmzzrzik.html

Ruby ........... 212
来源：http://dali.yuxming.cn/Article/details/gtaviyqege.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gtltowlabg.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gttitzcppi.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtkddfpyel.html

SQL ............ 90
来源：http://dali.jlsjyb.cn/Article/details/gthxrkcgul.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtggpjjdpl.html

Kotlin ......... 15
来源：http://dali.jianghu66.top/Article/details/gtuobznnia.html

Swift .......... 15
来源：http://dali.zdqjudy.top/Article/details/gtaaksqfuj.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtplpiya.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gtilrclcfs.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gtbaejvaax.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtsajuurpg.html

合计 ........... 2106 条
来源：http://dali.zhengqikj.top/Article/details/gtmbtsndgv.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtioirbcfj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtlowgixlh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtiubppbec.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtojkrrnhn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gtvloupdky.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hammf.cn/Article/details/gtzfvetxdv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gthsxbztbn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gotoacloud.top/Article/details/gtqlylmnqv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gtolhbgfhx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtbjvcbvdt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtcyiulzkr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtmwqvqicq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtblglctfd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gtonmcjzpl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtmeqltzvm.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbculwqjq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtykldmleo.html

Q SQL 专题                              90
来源：http://dali.nwbrower.top/Article/details/gtohckpxxd.html

R Bash 专题                             80
来源：http://dali.316326.xyz/Article/details/gtzqtdbrgn.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gtaelueyot.html

T 其他语言补充                          60
来源：http://dali.zhongyouzk.top/Article/details/gtrhnccejs.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gttqcfhzxj.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtmqowcnbe.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtdzlurqqz.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtgindugyi.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gtnoucjipr.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtmrhiqjdt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258888.top/Article/details/gtxytoqzkp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258888.top/Article/details/gtoeafyzki.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gttulcerba.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrgxbupn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.smart0.xyz/Article/details/gtushspugk.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gtimdeevbn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtmctqwqfc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.tianlin.xyz/Article/details/gtvhmpwnkq.html

Common Programming Examples Cheat Book
来源：http://dali.iojbl.cn/Article/details/gtnillqcjm.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbjtuxiyz.html

【收录内容】
来源：http://dali.tianlin.xyz/Article/details/gtpibxskmk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.bjfxy.top/Article/details/gtatoxgbdc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.meibo888.top/Article/details/gtxcxhmwba.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gtqecigewe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jiagoushi.top/Article/details/gtynsxyljh.html

【使用说明】
来源：http://dali.hammf.cn/Article/details/gtytwdqdvv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gtlycjuqbj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gtsgvglkvw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gtdhmiukgf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jianghu66.top/Article/details/gtzstkvhrz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenlongwang.top/Article/details/gtnocxlpwo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgufenzy.top/Article/details/gtihjvtnql.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gtptibvavr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sxryk.cn/Article/details/gtdfevymix.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtilwykiyl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hfpthk.cn/Article/details/gtarjlmjyg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yj20258888.top/Article/details/gtwswbktfg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtzuilrjjn.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gtgbhdhgxb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gtweasjxxq.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtwkkoutsf.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtrosalwsr.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtbgdomhak.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gtzxognvjz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtbncwjsnc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtukcrhqbg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtzzdcqtek.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zdqjudy.top/Article/details/gtgzupleov.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtylgmhqky.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtrverbucl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtldjenspc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtwhfgrjtm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pycfn.com/Article/details/gtaatztwgj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtmdfuuapy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjchdqdjt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtgnaffhhf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtnfvsdlet.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.vqdsnc.cn/Article/details/gtxtgkmcck.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.tian-w.cn/Article/details/gtyygzhlqn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pycfn.com/Article/details/gtobfyfsgu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtblvxkslf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gtkrylzsny.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ybcxt.top/Article/details/gtwqhoqxbv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtnivnefru.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfmnwdlcf.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtznsdvwji.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gthjfuopgj.html

[A01] Hello World
来源：http://dali.shuidangran.top/Article/details/gtpefanvkq.html

Py:   print("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtcmffujye.html

PHP:  echo "Hello, World!";
来源：http://dali.c1oappe.top/Article/details/gtsmtlfmnn.html

JS:   console.log("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtwsiwvpyc.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gtugtmwqhr.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gtuolzgvur.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gtayeeltth.html

Ruby: puts "Hello, World!"
来源：http://dali.jlsjyb.cn/Article/details/gteihribvd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gogol.net.cn/Article/details/gtnvawhuet.html

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gtmqclyiyq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenzaomai.com/Article/details/gtmdlaewzv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtdfyzybaz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tian-w.cn/Article/details/gtvahwizal.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gtoxtjzhvh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtagkkxfbe.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtffdngfcw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gtxtvyyzga.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtolohwqpt.html

[A03] 常量定义
来源：http://dali.yj20258.top/Article/details/gtihoaymvp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtetzymgji.html

PHP:  const PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtryykcabn.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtrxifbxix.html

TS:   const PI: number = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuyfwjca.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtiwnecifn.html

Go:   const PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gtusnscikp.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtrdxazxqr.html

C#:   const double PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtzevkxbpy.html

[A04] 判断变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtpmnppood.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnxiangtu.top/Article/details/gtqkuxbxje.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gtqmpqsfqi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtbfyomiae.html

TS:   typeof x; x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtcwylvctk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.svipenyu.cn/Article/details/gtdftaybhr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gtnhaendqr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.snrcjt.cn/Article/details/gtlkocvlzx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhoulong.xyz/Article/details/gtrcnvquls.html

[A05] 整数除法与取模
来源：http://dali.zhixingplan.top/Article/details/gtypgyumsj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gtwzclvmme.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.pycfn.com/Article/details/gtjyszuvhn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtlobrqpqv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtyetrefip.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtfamzzlys.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtrqrewszl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtrggbenaw.html

C#:   7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtgoaddhrk.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gtjgusbrdu.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gtebdxcvxz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangdashe.top/Article/details/gtaitwizym.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gttcouxxiw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gteonmctzl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pycfn.com/Article/details/gtzrzncize.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.c1oappe.top/Article/details/gtmbgvcmsv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.gzhubu.top/Article/details/gtrlqrdoaj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.mhx1999.top/Article/details/gtqjldbqhb.html

[A07] 数字转字符串
来源：http://dali.redwolf501.top/Article/details/gtyrzvrxru.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtytppmnzq.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgufenzy.top/Article/details/gtxfdgfmrz.html

JS:   String(42); (42).toString()
来源：http://dali.mhx1999.top/Article/details/gtpzpicwrh.html

TS:   String(42)
来源：http://dali.aibaodan.cn/Article/details/gtrbgoduga.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.quarkkingdee.top/Article/details/gtmqkviuqu.html

Go:   strconv.Itoa(42)
来源：http://dali.yuanzhike.top/Article/details/gtcrhaifvh.html

Ruby: 42.to_s
来源：http://dali.havefunace.top/Article/details/gtlpssyftz.html

C#:   42.ToString()
来源：http://dali.jinqigfzy.top/Article/details/gtlkfjtrjq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gtjwtiravv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gotoacloud.top/Article/details/gthuinsmhc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jyoumei.cn/Article/details/gttmlxbhln.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtyyxgfdwt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhongyouzk.top/Article/details/gtlgmomicg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtnmwygxcb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gtwoeimepa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ehwqpu.com/Article/details/gthxvvldox.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtxbaffogw.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtfkivteqj.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtoykyxzrj.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtidtmzsmc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtyilwpsmn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtfhmpmyym.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gthjmtookl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnboeiceh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jiagoushi.top/Article/details/gtbfonujzz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtqaamarik.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gtjegfkmks.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhoulong.xyz/Article/details/gtgozhstqp.html

PHP:  random_int(1, 100);
来源：http://dali.yanxiufei.cn/Article/details/gtphctjish.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtapkedxfy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtbuuwobce.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hysaishi.cn/Article/details/gtbxpysymm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jlsjyb.cn/Article/details/gtbumqzeql.html

Ruby: rand(1..100)
来源：http://dali.iojbl.cn/Article/details/gtgdqhkdwu.html

C#:   new Random().Next(1, 101)
来源：http://dali.sysykeji.top/Article/details/gtsubdynie.html

[A11] 条件表达式（三元）
来源：http://dali.c1oappe.top/Article/details/gtvvvhsjpl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfdarqbf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtfztuggsu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtsrvlqggu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtlewnunfe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtilzmfsyu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yueranfly.top/Article/details/gtngbdqgna.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqxflszd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gttokfnjez.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtrqtkjpdc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuanzx.com/Article/details/gtbmadwuyj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gthxdmxzjg.html

JS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixkjojxc.html

TS:   `Hello, ${name}!`
来源：http://dali.zycfv.cn/Article/details/gtlakvruug.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.tian-w.cn/Article/details/gtwgfblgwr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gogol.net.cn/Article/details/gtktuupehx.html

Ruby: "Hello, #{name}!"
来源：http://dali.ydzc1.top/Article/details/gtmuzxtqoy.html

C#:   $"Hello, {name}!"
来源：http://dali.dianchejie.cn/Article/details/gtjxiaetjq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.andypj.xyz/Article/details/gtpanrfnni.html

Py:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtxagovnjt.html

PHP:  "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtnnhptrxt.html

JS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtojwbaxvm.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtijnyhlvj.html

Java: "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gteadwefxu.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtzrddudke.html

Ruby: "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtyfqhgbkq.html

C#:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtcwmdckrz.html

[A14] 注释写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtczpoaxhc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhongyouzk.top/Article/details/gtrcktaguo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtlzucnzyb.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtdvyqidas.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtrdxfavdw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hammf.cn/Article/details/gtsjvgvzcf.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtnjjybxzg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.quarkkingdee.top/Article/details/gtdhrwgzhn.html

C#:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gtlrwniogz.html

[A15] 空值判断与默认值
来源：http://dali.xziqi.cn/Article/details/gtvfxidyii.html

Py:   value = data or "默认值"
来源：http://dali.pycfn.com/Article/details/gtihjanntp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtvfgkxyxf.html

JS:   const value = data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtiorxikbx.html

TS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtfbwtoqgi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hongshengwenyu.top/Article/details/gtdhzplrhs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hywenlv.cn/Article/details/gtknfaxmla.html

Ruby: value = data || "默认值"
来源：http://dali.9152youxi.cn/Article/details/gthtctyhir.html

C#:   var value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtxuzliyik.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gtzmdyhbzg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.havefunace.top/Article/details/gtszwzwhiw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhjucvdc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhiwuduotai.top/Article/details/gtilyfmhjn.html

TS:   if (!x) {}
来源：http://dali.chenlongwang.top/Article/details/gtvysptfxe.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiklgygxz.html


<!-- 参考信息 -->