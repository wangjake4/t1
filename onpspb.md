代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtwqwyysic.html

new Promise((resolve, reject) => {})
来源：http://dali.yj20258.top/Article/details/gtbwemyqvm.html

[U96] JS：async/await 与异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnwivbscm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtnssbbpmb.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtruhgeyvt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtpbdicnym.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhengqikj.top/Article/details/gtxjsezvgb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gtajrbkglp.html

[U99] JS：事件监听
来源：http://dali.vqdsnc.cn/Article/details/gtyhufcxhc.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtbhcdpbbv.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gtgxufqojn.html

document.querySelector(".item")
来源：http://dali.zdqjudy.top/Article/details/gttsxezrze.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gtsnmhpdai.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gtzqvxtnce.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gtjpzjyero.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhongyouzk.top/Article/details/gtrpqlskih.html

[U103] JS：定时器
来源：http://dali.tanke756.top/Article/details/gtlqmlvxqh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daria6918.cn/Article/details/gttraeljow.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gtaxnlklht.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gthvgqwmpd.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtewykcyjs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.316326.xyz/Article/details/gtdphgbfen.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtajvloatq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gteijjppee.html

[U107] JS：数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtywvyfkxe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gttybwuupy.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gtutmmehqb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.svipenyu.cn/Article/details/gttmyyuvqh.html

[U109] JS：数组分组
来源：http://dali.jyoumei.cn/Article/details/gtnwzkvhag.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtdbiqhfit.html

[U110] JS：数组分块
来源：http://dali.guannengcc.top/Article/details/gtykvjfoqw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gtdimplwkg.html

[U111] JS：对象转 Map
来源：http://dali.dianchejie.cn/Article/details/gtatqyyvjj.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gtjjlcnbje.html

[U112] JS：字符串补位
来源：http://dali.andypj.xyz/Article/details/gtztsedvca.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtoaspbggo.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gtzcvpsxuf.html

s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtfeuggtdk.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtmnjyngfy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtrneqvhfe.html

[U115] JS：生成 UUID
来源：http://dali.cashguo.top/Article/details/gtvpiotbej.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtgiywkisg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shuidangran.top/Article/details/gtdarxxaiq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ppjwa.cn/Article/details/gtnvagjnfz.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtcipjwrsp.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtjdihcdjs.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtagvlkuya.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtxkcntpkl.html

[U119] JS：生产构建
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugvjhvva.html

npx vite build
来源：http://dali.wangshuangyany.cn/Article/details/gtumrjtacp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sxryk.cn/Article/details/gtgwfvxrgn.html

import.meta.env.VITE_API_URL
来源：http://dali.sxryk.cn/Article/details/gtjqhmzsbt.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnzhvsppd.html

统计汇总
来源：http://dali.svipenyu.cn/Article/details/gtftcimrvr.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttdevkqxl.html

按语言统计（条）：
来源：http://dali.shanyushiyangkeji.top/Article/details/gttmzkixzu.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gtaxpfbfvz.html

PHP ............ 252
来源：http://dali.svipenyu.cn/Article/details/gtpkumhrfz.html

JavaScript ..... 252
来源：http://dali.sysykeji.top/Article/details/gtqfjxadkg.html

TypeScript ..... 212
来源：http://dali.sysykeji.top/Article/details/gtgfbzhqsi.html

Java ........... 212
来源：http://dali.cashguo.top/Article/details/gtahacteuc.html

Go ............. 212
来源：http://dali.sysykeji.top/Article/details/gtvzraxzga.html

Ruby ........... 212
来源：http://dali.hnqzz.top/Article/details/gtxdkamddc.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtaybzkpuy.html

C .............. 30
来源：http://dali.svipenyu.cn/Article/details/gtpemsrnea.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtrcztgscb.html

SQL ............ 90
来源：http://dali.xylfe.cn/Article/details/gttqtmvcsd.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gtnrbgicnb.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gtbwmjcdgw.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gtptjhswzi.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gttoequsds.html

Perl ........... 10
来源：http://dali.pycfn.com/Article/details/gtplcxgkks.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtcsfozbns.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhglwiwm.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtprnxziwt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gtvtemrsnc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gthcppqimi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtrppllydh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtzuunxgge.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtgypvmcxf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.c1oappe.top/Article/details/gtnlxivwtz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtimyddmux.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtdbqasoff.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtvmozbcma.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtwovgqrou.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgofbtgx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtcfcfminy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvozhfsr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtevvtttkj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gtxtuzocvf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtctlfqyvl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gteeberpcs.html

Q SQL 专题                              90
来源：http://dali.jqgufenzy.top/Article/details/gtzvolmkbi.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gtmhqgzffz.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtklipnjcj.html

T 其他语言补充                          60
来源：http://dali.fengsongda.top/Article/details/gtinlrpoez.html

U 高频实用片段                         120
来源：http://dali.svipenyu.cn/Article/details/gtwnjwsjhw.html

------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtwvsexthd.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtgluwdnzs.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtswqpixmy.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtnjpjjjzj.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtngjekais.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenlongwang.top/Article/details/gtqvnfffvc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenlongwang.top/Article/details/gtokegxcbj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hnxiangtu.top/Article/details/gtkzacolhr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtbuqkzokr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gtjdxllosd.html

—— 文件结束 ——
来源：http://dali.dianchejie.cn/Article/details/gtswdfdwaq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnzwcuwyq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtxduggx.html

Common Programming Examples Cheat Book
来源：http://dali.wangdashe.top/Article/details/gtghrmcbiw.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtkuzgqpqh.html

【收录内容】
来源：http://dali.tianlin.xyz/Article/details/gtpxvqkcxf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yanxiufei.cn/Article/details/gtaetfmgml.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigfzy.top/Article/details/gtxdlydbdf.html

SQL · Bash · C · C++
来源：http://dali.aibaodan.cn/Article/details/gtoewfbuxd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.mhx1999.top/Article/details/gtmoqwcmeu.html

【使用说明】
来源：http://dali.chenjidiqi.icu/Article/details/gtxypjlgbc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gtoazwxwoc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.feifeiyinyue.top/Article/details/gtvrxagtva.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jyoumei.cn/Article/details/gtvvcvvbfv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nwbrower.top/Article/details/gtgkltuady.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gotoacloud.top/Article/details/gtohsnmmiq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jlsjyb.cn/Article/details/gtsmegfbog.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gtaltlmvhx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxggasags.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.meibo888.top/Article/details/gtdlgcuicn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tanke756.top/Article/details/gtvdzkbhmz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hysaishi.cn/Article/details/gtutsmkxby.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hnqzz.top/Article/details/gtdbbievlo.html

【文件统计】
来源：http://dali.bjfxy.top/Article/details/gtondgehyg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hysaishi.cn/Article/details/gtiwindmmf.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtmkccmnyv.html

目  录
来源：http://dali.hongshengwenyu.top/Article/details/gtmdgozpen.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtfhxjwcpz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhengqikj.top/Article/details/gthhsvvwiw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gtmypapvqa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jqgfzy.top/Article/details/gtzmktpqis.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gtkciqvcbs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gtfduufokl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtdhkqmjqk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtrmzfmkmx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gttdvgtiea.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtowgmdzwq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtbythlizx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtksshxuay.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtljdfobhg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtuhqklkpx.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtgpxnizoz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hysaishi.cn/Article/details/gtmdlietif.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtercgpkll.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gtqdareqob.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gtsktcuqmu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gtjnxmxvnk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gthphyfavw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtkdecrkhm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtqhnssfmy.html

A. 基础语法与类型
来源：http://dali.nwbrower.top/Article/details/gtduqhdxli.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtltgymieb.html

[A01] Hello World
来源：http://dali.ppjwa.cn/Article/details/gtbbrttzwr.html

Py:   print("Hello, World!")
来源：http://dali.cqqwz.cn/Article/details/gtwoucpqiy.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gtyqzpzbwq.html

JS:   console.log("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtoikspaeh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhixingplan.top/Article/details/gttafjwybr.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gtrrgobmie.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daxiang520.top/Article/details/gtbsheprxy.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gtzhavmmex.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtwavkcgkk.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gtihearzty.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gtdhhkpwvs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gtgedtbkiz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtdhcpyrwl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.guannengcc.top/Article/details/gtbmvafkml.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtxvwybyfg.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakcvniyt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gttjyoxigr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj202588.top/Article/details/gtspsmcrlj.html

[A03] 常量定义
来源：http://dali.chenzaomai.com/Article/details/gtiasinfoc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtlpdomshz.html

PHP:  const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtrslgtxqi.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gthjwhbwmq.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtxbuyekyu.html

Java: static final double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtfqcmmmtd.html

Go:   const PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtginkcxrl.html

Ruby: PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtlednqrpl.html

C#:   const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gthrboxhur.html

[A04] 判断变量类型
来源：http://dali.dianchejie.cn/Article/details/gtnorxwrds.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.bjfxy.top/Article/details/gtryvaeobz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.haohaochexian.top/Article/details/gtlaphxotr.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtkfdldlui.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtgepomtln.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnqzz.top/Article/details/gtzpreenrb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gzhubu.top/Article/details/gtpzwvfhcm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.pengpengdd.cyou/Article/details/gtpliyetfy.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gtqqtsbhxw.html

[A05] 整数除法与取模
来源：http://dali.yanxiufei.cn/Article/details/gtudtgyfms.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ehwqpu.com/Article/details/gtezrelozf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtlfrkambz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtplhbfkjt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvtxensq.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gteqlcsigt.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtybwufqpa.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtoldmmkmn.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtdtwtxkhf.html

[A06] 字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtdakaqpaw.html

Py:   int("42"); float("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtgqavbnyu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.iojbl.cn/Article/details/gtlwtagbqn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gtpvikxbth.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtpjeydods.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtdkpjfdxt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.birdmap.top/Article/details/gtzbjmikvz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.dashuyun.cn/Article/details/gtgzcprtad.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hysaishi.cn/Article/details/gtsqltdgcl.html

[A07] 数字转字符串
来源：http://dali.hfpthk.cn/Article/details/gtcdpdillf.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gttnwgnndt.html

PHP:  (string) 42; strval(42)
来源：http://dali.tian-w.cn/Article/details/gtaqfhxohg.html

JS:   String(42); (42).toString()
来源：http://dali.jlsjyb.cn/Article/details/gtwryhdzvw.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gtczjvdwga.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sxryk.cn/Article/details/gthygvfuge.html

Go:   strconv.Itoa(42)
来源：http://dali.gogol.net.cn/Article/details/gtxdthjrcv.html

Ruby: 42.to_s
来源：http://dali.yuanzhike.top/Article/details/gtfvyhtrwm.html

C#:   42.ToString()
来源：http://dali.zhongyouzk.top/Article/details/gtxlqpitfp.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gtrahsbzrm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtcrholtfm.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hysaishi.cn/Article/details/gtsrbrugvc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtjlsujqnk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangshuangyany.cn/Article/details/gtkcgfjpem.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gtoaowovgw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinghuilouyu.cn/Article/details/gtncbkggqa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.meibo888.top/Article/details/gtvgunrffc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtoiktdlpe.html

[A09] 绝对值与最大最小值
来源：http://dali.316326.xyz/Article/details/gtjwjgtblv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtzignstvz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtrrprjykn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkkqfuigd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtsyjemfud.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtchkekovm.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jiagoushi.top/Article/details/gtexmjibjh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gtbegkljao.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aizwys.cn/Article/details/gtvysaqmaq.html

[A10] 生成随机数
来源：http://dali.shuidangran.top/Article/details/gttwvdsztc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ehwqpu.com/Article/details/gtysinqwyy.html

PHP:  random_int(1, 100);
来源：http://dali.yuanzhike.top/Article/details/gtqrdrznrn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtuqnsyctj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gthnstzqtx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtgbhyspwq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.nanxuanxn.top/Article/details/gtmghfhwyp.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gtrmztvrpv.html

C#:   new Random().Next(1, 101)
来源：http://dali.kuanghao11.cn/Article/details/gtpgrwgvcu.html

[A11] 条件表达式（三元）
来源：http://dali.birdmap.top/Article/details/gtlidacjhp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.dianchejie.cn/Article/details/gtvsodumyx.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtexceyyrg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtqwyxwchf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekcowibq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gtfkjgnokd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gtlfsjsyoa.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtoijlnlht.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtepuigihl.html

[A12] 字符串插值 / 格式化
来源：http://dali.nwbrower.top/Article/details/gtzhshbsef.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jiagoushi.top/Article/details/gtvxbuscqq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.316326.xyz/Article/details/gthffygiah.html

JS:   `Hello, ${name}!`
来源：http://dali.wangshuangyany.cn/Article/details/gtvgwvjlzh.html

TS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gtyrlcbznp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtzoyzibbv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gtlslqtvws.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhoulong.xyz/Article/details/gthqqiyfpk.html

C#:   $"Hello, {name}!"
来源：http://dali.ydzc1.top/Article/details/gtvniipedq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtcvqiunzr.html

Py:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtazlioaou.html

PHP:  "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtwhmtazdm.html

JS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtqsxpyzrs.html

TS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgsdycgo.html

Java: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtnojzwpvj.html

Go:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtbrtcdxye.html

Ruby: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtsnajleac.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtabiwbolb.html

[A14] 注释写法
来源：http://dali.cdnleiting.top/Article/details/gtapxuosgx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jlsjyb.cn/Article/details/gtktvtijpo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gthwuxfkvg.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtgcolybao.html

TS:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gthicefwue.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhiwuduotai.top/Article/details/gtbehzztvi.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtikffybgc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtczopznuu.html

C#:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtlawvcfoe.html

[A15] 空值判断与默认值
来源：http://dali.birdmap.top/Article/details/gtvwtznxzq.html

Py:   value = data or "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtynragyju.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtydbptwgv.html

JS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gthtkoixyz.html

TS:   const value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtmkptgxss.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.bjfxy.top/Article/details/gtwpspherr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtucvecbwt.html

Ruby: value = data || "默认值"
来源：http://dali.sweek.top/Article/details/gtvfcgzyls.html

C#:   var value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtbgaavacw.html

[A16] 真假值判断规则
来源：http://dali.zhoulong.xyz/Article/details/gtjgfafmol.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jlsjyb.cn/Article/details/gtvdobmpag.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhixingplan.top/Article/details/gtqhbsfprm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.meibo888.top/Article/details/gtkbutyxjn.html

TS:   if (!x) {}
来源：http://dali.jyoumei.cn/Article/details/gtwmyzeqvt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtetcataib.html


<!-- 参考信息 -->