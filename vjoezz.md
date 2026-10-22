代发 wailian999

[U93] JS：模板字符串
来源：http://dali.hnxiangtu.top/Article/details/gtojjrnhts.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gtlxqfiged.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgydrqpxp.html

const double = x => x * 2;
来源：http://dali.hywenlv.cn/Article/details/gtchdeklxx.html

[U95] JS：Promise 包装
来源：http://dali.xuetiantiany.cn/Article/details/gtjxmvxfdi.html

new Promise((resolve, reject) => {})
来源：http://dali.gaohongyu789.top/Article/details/gthepgowcz.html

[U96] JS：async/await 与异常
来源：http://dali.zycfv.cn/Article/details/gtayocpjyb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtbpmfcoiw.html

[U97] JS：并发请求
来源：http://dali.hammf.cn/Article/details/gtymmjarau.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gthbtcczjd.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtjrfgcpza.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shuidangran.top/Article/details/gtcjmzwwgi.html

[U99] JS：事件监听
来源：http://dali.zhengqikj.top/Article/details/gtwyecigwi.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gtfnurgocw.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gtggsbvewr.html

document.querySelector(".item")
来源：http://dali.yuanzhike.top/Article/details/gtvnhvylfr.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gtqqoyleer.html

el.classList.toggle("active")
来源：http://dali.andypj.xyz/Article/details/gtofytvtpz.html

[U102] JS：本地存储
来源：http://dali.yueranfly.top/Article/details/gtvprpcxyo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gtlomgxgyg.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtbuiqpidh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yanxiufei.cn/Article/details/gtvbmjvnff.html

[U104] JS：防抖
来源：http://dali.yuxming.cn/Article/details/gtsxuywqrl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtxrclpkkj.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtuojwszif.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xziqi.cn/Article/details/gtjjqygcye.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtmhouihwt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gtsdkgrmpe.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtulejesng.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtjqlzmlwd.html

[U108] JS：随机整数
来源：http://dali.ybcxt.top/Article/details/gtlfsojpkr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gtilwssryf.html

[U109] JS：数组分组
来源：http://dali.daria6918.cn/Article/details/gtrovcswrw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gtwwsginci.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtneyhlasl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtsbuutjap.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtcpqpoiqu.html

new Map(Object.entries(obj))
来源：http://dali.gaohongyu789.top/Article/details/gterzotoqf.html

[U112] JS：字符串补位
来源：http://dali.tanke756.top/Article/details/gtcqtkswvd.html

"7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtrzmgsdtn.html

[U113] JS：正则替换全部
来源：http://dali.fengsongda.top/Article/details/gtdrlrakvq.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtvhviqozu.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gtespplxgj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gteoqotvwz.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtydnpopsi.html

crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gtiztkacsa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dianchejie.cn/Article/details/gtyjdjjjfc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xuanzx.com/Article/details/gtwzgtstek.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtnitxhhee.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtaaweqnbq.html

[U118] JS：开发服务器
来源：http://dali.hfpthk.cn/Article/details/gtfydivuej.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtuadyghqd.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtsrrsbbed.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gttanzakvj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtzztouacq.html

import.meta.env.VITE_API_URL
来源：http://dali.birdmap.top/Article/details/gtzaethwnd.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtajgoghhj.html

统计汇总
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyctuegs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdmjqvaos.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtsfsmygdt.html

Python ......... 252
来源：http://dali.andypj.xyz/Article/details/gttvkahkur.html

PHP ............ 252
来源：http://dali.cheryme.top/Article/details/gtbdguxdlu.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtrmsxzynp.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtvwcilevj.html

Java ........... 212
来源：http://dali.jianghu66.top/Article/details/gtalxpzshg.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipggeluy.html

Ruby ........... 212
来源：http://dali.feifeiyinyue.top/Article/details/gtvfvoiboe.html

C# ............. 212
来源：http://dali.cqqwz.cn/Article/details/gtezofount.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gtegcimjin.html

C++ ............ 30
来源：http://dali.dashuyun.cn/Article/details/gtstfapgfp.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtpjanokfw.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gtvmwqutgq.html

Kotlin ......... 15
来源：http://dali.jinqigufen.top/Article/details/gtgnoklfnk.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtznnpgfly.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gtuqhjsmia.html

Perl ........... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtajtzmmbv.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gtvuiewyoc.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtawwmpgkq.html

合计 ........... 2106 条
来源：http://dali.zhixingplan.top/Article/details/gteenogasa.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtdvuiypsh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenjidiqi.icu/Article/details/gtndhxqouo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtqlngmnjj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvkgeczw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxtwtszf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gtoouzpcsq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gtzwbhqgfa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtcygbsqtt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlgjsank.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtgumctowr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gtntjyvtyo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtlkicklru.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtjrdsnvus.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtrzzncead.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtxpxcznyr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gthjczfiij.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtpaltvyfn.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gtyzagzebk.html

R Bash 专题                             80
来源：http://dali.shuidangran.top/Article/details/gtxkejqavn.html

S C / C++ 专题                          60
来源：http://dali.vqdsnc.cn/Article/details/gtmmfwtoan.html

T 其他语言补充                          60
来源：http://dali.jianghu66.top/Article/details/gthjhtiqrd.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtqgdqlapk.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtfmqooqia.html

合计                                  2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtendsprcu.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtwceltxga.html

使用提醒
来源：http://dali.yuxming.cn/Article/details/gtpjemvmwa.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtarqwwsgt.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gtsvazdngr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxuanxn.top/Article/details/gtkylmtqlm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sysykeji.top/Article/details/gtfujmccwd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gtqnrlqwrs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gtnqeslzqk.html

—— 文件结束 ——
来源：http://dali.tianlin.xyz/Article/details/gtcirqabna.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvgvnbssz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gtbrloxlgc.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gtaxpxbetx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtmrgkkgii.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gtffxfzicz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.smart0.xyz/Article/details/gtyiodjoyy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.sxryk.cn/Article/details/gthcyqwdwq.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gtgtkjrewe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gttbmkzpwh.html

【使用说明】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeyckpcw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gtaafpskom.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtzlegqusn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hammf.cn/Article/details/gtxtmuduiq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.aibaodan.cn/Article/details/gtptabwmpb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.daria6918.cn/Article/details/gtgdobndjb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.gzhubu.top/Article/details/gtnrobkugc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gtjubmvkid.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gtloskzjgg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.fzhhl.top/Article/details/gtdowxyfey.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtqenhybrz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.havefunace.top/Article/details/gtqefmzdlw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yuxming.cn/Article/details/gtppjgvdlt.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtdydbkvlt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hnqzz.top/Article/details/gtityoilmd.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtltywlwha.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gteqgvlbhb.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtinlgvnru.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yj20258888.top/Article/details/gtrggfdezo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtxtlhmzlt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtktpzkiaa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtihezrsrs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fzhhl.top/Article/details/gtwnbyvazq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.haohaochexian.top/Article/details/gtdmjryucx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tianlin.xyz/Article/details/gthufyjdfm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtkcibqrzi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtrfweamjt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtwidqdinp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtyjrxdsky.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtcoapdsdf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtmbfkrryk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtyfjbauch.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhongyouzk.top/Article/details/gtscxeuorf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuxming.cn/Article/details/gtqbvxrfqw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gtzwnujdvg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtowfjiuwr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zdqjudy.top/Article/details/gtmproxiia.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtcjvxijzm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgaxnwroz.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtrmiafxci.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gttujreuia.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gthosvlvbc.html

[A01] Hello World
来源：http://dali.smart0.xyz/Article/details/gtyyzqvowi.html

Py:   print("Hello, World!")
来源：http://dali.iojbl.cn/Article/details/gtweomaapb.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gtrnxjocbn.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtronggikn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gtxeuvylzp.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtdgerqznf.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gtpmdmtcye.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gtqsjrorql.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtgezwhnau.html

[A02] 变量声明与赋值
来源：http://dali.yueranfly.top/Article/details/gthsoaitgc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.quarkkingdee.top/Article/details/gtqppzwxgq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.bjfxy.top/Article/details/gthyeeqdli.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtwrlmrjcj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daxiang520.top/Article/details/gthpzzicxe.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtmhaigwcb.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtfefpbamp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gtehtpggmv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtnzslbydl.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtimffjbod.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gotoacloud.top/Article/details/gtocnopiwv.html

PHP:  const PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtjryjnjyk.html

JS:   const PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtopgzcvch.html

TS:   const PI: number = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqoadnvv.html

Java: static final double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtvhqkidyc.html

Go:   const PI = 3.14159
来源：http://dali.yj20258.top/Article/details/gtohqnrmtx.html

Ruby: PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtoemfkiod.html

C#:   const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtxmgsmsky.html

[A04] 判断变量类型
来源：http://dali.cdnleiting.top/Article/details/gtzzwvozsq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.feifeiyinyue.top/Article/details/gtcyfvwikf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yonumen.top/Article/details/gthfoeecbt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtkwohrvuj.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtacbsqehs.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigufen.top/Article/details/gtmkcgbznk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gttrxcdvuy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ehwqpu.com/Article/details/gtwbjeyhht.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gtrzzzeayz.html

[A05] 整数除法与取模
来源：http://dali.zhengqikj.top/Article/details/gtwsyobucp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guannengcc.top/Article/details/gtfyvhsrmc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtaoilsgsf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtyjqjfftj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtwssyiqzq.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtoeqvskux.html

Go:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtszfxebma.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtgnwqfvzb.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtxdpehvce.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtmrbzxdyn.html

Py:   int("42"); float("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtergfieox.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.haohaochexian.top/Article/details/gtebjofvjf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtfkmzsxak.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sweek.top/Article/details/gtmshylmhu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtbnvkovqd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jiagoushi.top/Article/details/gtwfsqkeph.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cucudq.cn/Article/details/gtuweujtqo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhiwuduotai.top/Article/details/gtwmizldex.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtoyuxxfbp.html

Py:   str(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazmwugpb.html

PHP:  (string) 42; strval(42)
来源：http://dali.vqdsnc.cn/Article/details/gtiqsglhtv.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gttalxaxnw.html

TS:   String(42)
来源：http://dali.wangdashe.top/Article/details/gtavtfvhfa.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinqigufen.top/Article/details/gtoxdccnlj.html

Go:   strconv.Itoa(42)
来源：http://dali.cqqwz.cn/Article/details/gtaqhradar.html

Ruby: 42.to_s
来源：http://dali.dashuyun.cn/Article/details/gtcomojjgx.html

C#:   42.ToString()
来源：http://dali.iojbl.cn/Article/details/gtgkcpxqif.html

[A08] 取整与四舍五入
来源：http://dali.gzhubu.top/Article/details/gtsofjrcnq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtldugfmrt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdscjultu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtpilkqazq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jianghu66.top/Article/details/gtjdvcrwem.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtrqnwmkho.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtpwhtohkh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tanke756.top/Article/details/gtmfitqbci.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtahuvqxrc.html

[A09] 绝对值与最大最小值
来源：http://dali.meibo888.top/Article/details/gtyuxfekdv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtuvxdrsbf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtfmzeyjkl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtdwiuybei.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtzyguwsdt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthulauzbb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtksvlkafv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.dashuyun.cn/Article/details/gtfecuondg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtkvwpfqrv.html

[A10] 生成随机数
来源：http://dali.nanxinkj.top/Article/details/gtbzfbksvo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fengsongda.top/Article/details/gtglzmbkdx.html

PHP:  random_int(1, 100);
来源：http://dali.ybcxt.top/Article/details/gtzazaziok.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gttgkzkcev.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtduebgdem.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daria6918.cn/Article/details/gtjogvpvxz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sufxvd.cn/Article/details/gtasvvzorh.html

Ruby: rand(1..100)
来源：http://dali.0kj1m.cn/Article/details/gtdvlwjlpp.html

C#:   new Random().Next(1, 101)
来源：http://dali.0kj1m.cn/Article/details/gtarrwiinp.html

[A11] 条件表达式（三元）
来源：http://dali.yanxiufei.cn/Article/details/gtbohuryrk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yangfankeji.com/Article/details/gtvqpgnnwc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtjbwalhyt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtoyzcadsu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtubzbpzhj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtycvrrtbk.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gtkgmsyhln.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtcdygibrb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtcxmijaza.html

[A12] 字符串插值 / 格式化
来源：http://dali.tanke756.top/Article/details/gtawcwqejd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.iojbl.cn/Article/details/gtstylrxgd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xinyue.icu/Article/details/gtrbsgiijs.html

JS:   `Hello, ${name}!`
来源：http://dali.hywenlv.cn/Article/details/gtzouqkeuy.html

TS:   `Hello, ${name}!`
来源：http://dali.gaohongyu789.top/Article/details/gtsctoquom.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hysaishi.cn/Article/details/gthgmgwrxr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenlongwang.top/Article/details/gtcdhbsjno.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigfzy.top/Article/details/gtgmrvkanu.html

C#:   $"Hello, {name}!"
来源：http://dali.mhx1999.top/Article/details/gtlevzxvol.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.quarkkingdee.top/Article/details/gtikeqypho.html

Py:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdlflneu.html

PHP:  "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtwesmajsd.html

JS:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtarhnctyx.html

TS:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gthaozolbp.html

Java: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtsobwxlcf.html

Go:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtyrvgkbgf.html

Ruby: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtslbnugqg.html

C#:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gthtmfjrju.html

[A14] 注释写法
来源：http://dali.nwbrower.top/Article/details/gtwcxmpsdy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yvedp.cn/Article/details/gtdxlzbvfi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtgoihnahf.html

JS:   // 单行；/* 多行 */
来源：http://dali.quarkkingdee.top/Article/details/gtmbkmwmsr.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtlhoegcdh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ppjwa.cn/Article/details/gtxovmmsth.html

Go:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtxzcdcrci.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shuidangran.top/Article/details/gtjzkcwkov.html

C#:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtrtlvddoz.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtbookwsfb.html

Py:   value = data or "默认值"
来源：http://dali.316326.xyz/Article/details/gtzjquuzrj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtwmbrscet.html

JS:   const value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gthnyezhep.html

TS:   const value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtessfoywt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtappljtnw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgufenzy.top/Article/details/gtpukruttt.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gttargjocf.html

C#:   var value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtbtvpctuv.html

[A16] 真假值判断规则
来源：http://dali.ppjwa.cn/Article/details/gtbhqqvscx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnqzz.top/Article/details/gtfwrbvhxx.html


<!-- 参考信息 -->