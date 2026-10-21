代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.yj20258.top/Article/details/gtzfgldvoz.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtrrudauid.html

[U96] JS：async/await 与异常
来源：http://dali.xuanzx.com/Article/details/gtyyeakjdn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwoekvwf.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtpsynwhxu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jianghu66.top/Article/details/gtzjfkbhzu.html

[U98] JS：fetch 带 JSON
来源：http://dali.guannengcc.top/Article/details/gthrfgizwj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hysaishi.cn/Article/details/gtwnlkdynv.html

[U99] JS：事件监听
来源：http://dali.gzhubu.top/Article/details/gtvxcqnafx.html

el.addEventListener("click", e => {})
来源：http://dali.yj202588.top/Article/details/gtolyumcxn.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwarjulib.html

document.querySelector(".item")
来源：http://dali.hnxiangtu.top/Article/details/gtsedathcc.html

[U101] JS：classList 操作
来源：http://dali.zhixingplan.top/Article/details/gtywohpnui.html

el.classList.toggle("active")
来源：http://dali.yvedp.cn/Article/details/gtoeprwtrw.html

[U102] JS：本地存储
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxbowjjj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gthhbwgdab.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjlbhnfk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gtvyuoawds.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gtfahmdatd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtousaucsd.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gttmvllywe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.bjfxy.top/Article/details/gttfzotxns.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gttqcoarvu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gtznqclmgp.html

[U107] JS：数字千分位
来源：http://dali.sweek.top/Article/details/gtyhjjlrai.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gtusuczqhi.html

[U108] JS：随机整数
来源：http://dali.jqgfzy.top/Article/details/gtaaxebwal.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gthgpbfkbv.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gtvsgprmbz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtlyulazvx.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtbykwqccb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gotoacloud.top/Article/details/gtwqgpnwwf.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtqoixjkjd.html

new Map(Object.entries(obj))
来源：http://dali.aizwys.cn/Article/details/gtibfqdbuz.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtgzxumihi.html

"7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtmrpunubq.html

[U113] JS：正则替换全部
来源：http://dali.zhoulong.xyz/Article/details/gtzbpdziea.html

s.replaceAll("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtruehzzla.html

[U114] JS：JSON 深比较
来源：http://dali.smart0.xyz/Article/details/gthowfoxff.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtzwloqpmr.html

[U115] JS：生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gtblgfkmuq.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtsrtsrhwx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gtqoiyambf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtckwsbpbn.html

[U117] JS：单元测试
来源：http://dali.smart0.xyz/Article/details/gtzfhbfeiz.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gtpwnqcygd.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gthimwerqm.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gtaowuvpdx.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gtulcykcro.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtntaxjrom.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinqigfzy.top/Article/details/gthlmascwo.html

import.meta.env.VITE_API_URL
来源：http://dali.jiagoushi.top/Article/details/gtvlthzwxp.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtymxcjpwo.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtzsfpvsgs.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthsiaposr.html

按语言统计（条）：
来源：http://dali.wangshuangyany.cn/Article/details/gtqrxxuhij.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gtmhjjstor.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtvpyckjnw.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtkbbsdgxv.html

TypeScript ..... 212
来源：http://dali.sxryk.cn/Article/details/gtmobqbziq.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gteshxxswr.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtspjbwkzk.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gtzosivsmg.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gtseiwujqk.html

C .............. 30
来源：http://dali.zhongyouzk.top/Article/details/gtfffhiisn.html

C++ ............ 30
来源：http://dali.ybcxt.top/Article/details/gtdjnjawcd.html

SQL ............ 90
来源：http://dali.chenlongwang.top/Article/details/gtaixjfnpz.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtvwevchtl.html

Kotlin ......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gteareqbdq.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gtztkxonxw.html

Lua ............ 10
来源：http://dali.quarkkingdee.top/Article/details/gtoykqndfv.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtjyouycxw.html

Scala .......... 10
来源：http://dali.yj20258.top/Article/details/gtshsvysnz.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gtzwpsefmk.html

合计 ........... 2106 条
来源：http://dali.shuidangran.top/Article/details/gtyiapwlbt.html

按章节统计：
来源：http://dali.ybcxt.top/Article/details/gtzcqkkzpa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gtgdpqkoib.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtrazfyews.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtzvpkdils.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtkjscgcaz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.mhx1999.top/Article/details/gthbbrvrdu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtarumjofg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtakrupyat.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gtrlfvtupd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtxnrwtiwd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.haohaochexian.top/Article/details/gtqsrpgvhd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtsbnospat.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtoxmmxsll.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtxrfnlnfx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtkcprtjpu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckxbtixy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gthsgvrnif.html

Q SQL 专题                              90
来源：http://dali.tianlin.xyz/Article/details/gtijjmcoki.html

R Bash 专题                             80
来源：http://dali.nwbrower.top/Article/details/gtjdqbniab.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gtvbbezegn.html

T 其他语言补充                          60
来源：http://dali.zycfv.cn/Article/details/gtvlnnknqd.html

U 高频实用片段                         120
来源：http://dali.dashuyun.cn/Article/details/gtfdtubpcy.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtjauvjevq.html

合计                                  2106 条
来源：http://dali.vqdsnc.cn/Article/details/gtbjcqxsjy.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtnwqvkxcp.html

使用提醒
来源：http://dali.gaohongyu789.top/Article/details/gtrkpawuij.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtclabnihs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xylfe.cn/Article/details/gtihvgztgc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gtwgixtbxm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tanke756.top/Article/details/gtzbrwtnyw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gtglehmumv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuetiantiany.cn/Article/details/gtyocgqkvu.html

—— 文件结束 ——
来源：http://dali.jianghu66.top/Article/details/gthogtqseq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqyakswuy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.birdmap.top/Article/details/gtrggidzxx.html

Common Programming Examples Cheat Book
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdvgukpj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdlodtfto.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gtxyyyisfb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxuanxn.top/Article/details/gtlyegbrzi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtfstjwuxl.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtokrezejk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gtgpklqgut.html

【使用说明】
来源：http://dali.havefunace.top/Article/details/gtwwwzlkyt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jyoumei.cn/Article/details/gtepglgygy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtoyiskfhm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenlongwang.top/Article/details/gtiplhmmqe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gtqkupkibq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shuidangran.top/Article/details/gtmcggkyjf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fzhhl.top/Article/details/gtoqjilzfh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj202588.top/Article/details/gtvsybywus.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcngqekv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinqigfzy.top/Article/details/gtnwugxuud.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgfzy.top/Article/details/gtrjqspivl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxifqwle.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtdvenbruf.html

【文件统计】
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixvxqisf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gtlvcljrej.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtdzjyhrzv.html

目  录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfruzqgj.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtcexahclg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gtrmbaovyb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtttijschm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtxbpxswjf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddualakk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxdxlpwc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtzmabqors.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gthiquhhqx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtmfvjlxma.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yueranfly.top/Article/details/gtizdaluab.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtkylayfts.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtelfjejdc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.tianlin.xyz/Article/details/gtdjnqizup.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtvvzchoty.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtisheoisw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhoulong.xyz/Article/details/gtoyemyjci.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtnfodidck.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.snrcjt.cn/Article/details/gtknjltinw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.316326.xyz/Article/details/gtnhkigwdc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzikdgca.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gtemlscyaq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gtbryuhgkd.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvgwhpchp.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gthmpfkhko.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgwvazdju.html

[A01] Hello World
来源：http://dali.sweek.top/Article/details/gtzpafcfrc.html

Py:   print("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gtbzeblrwq.html

PHP:  echo "Hello, World!";
来源：http://dali.ybcxt.top/Article/details/gtmwmthssh.html

JS:   console.log("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtqjzlwhaq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxinkj.top/Article/details/gtrdalynnc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gtpfuewuil.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gtjlabdpwo.html

Ruby: puts "Hello, World!"
来源：http://dali.bjfxy.top/Article/details/gtjbioxfxq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pycfn.com/Article/details/gtqkvfkmpe.html

[A02] 变量声明与赋值
来源：http://dali.316326.xyz/Article/details/gtpxkydien.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.iojbl.cn/Article/details/gtvmeletgn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtnktfzzfr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtsumteyvp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtuwnukwui.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtvxthgwxd.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtsgktnivk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yonumen.top/Article/details/gtqjfzentf.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gthkiejfns.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gteramqrnd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yangfankeji.com/Article/details/gtdzfzqbpt.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtzclzfkqz.html

JS:   const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtoipnwrws.html

TS:   const PI: number = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtlyuhwnfx.html

Java: static final double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtraunjkcy.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtppftsmtn.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtevgveyeh.html

C#:   const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtyivaoxnk.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gtdyzfodcc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gtiwlwycou.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gtijdyyzei.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtbmpmwbso.html

TS:   typeof x; x instanceof Date
来源：http://dali.redwolf501.top/Article/details/gtoshmzrlu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gtpvaowako.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cheryme.top/Article/details/gtmncmymnl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhoulong.xyz/Article/details/gtpuiapyrl.html

C#:   x.GetType().Name; x is int
来源：http://dali.ivvv.top/Article/details/gthsseyovr.html

[A05] 整数除法与取模
来源：http://dali.hnqzz.top/Article/details/gtewqvbwih.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.feifeiyinyue.top/Article/details/gtlmlrhgwt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtwnojftoc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtsbpuxfqx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtbnmrvsso.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtspjckmsb.html

Go:   7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gthciazywh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuzptekh.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtipboyudi.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtmcsqmgax.html

Py:   int("42"); float("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtvohqazwu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.birdmap.top/Article/details/gtldgvgqwv.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtofsboxii.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gtplywdqfj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzunmgkns.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.tian-w.cn/Article/details/gthqijvcrq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gthdsilkon.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwehpiyn.html

[A07] 数字转字符串
来源：http://dali.zhengqikj.top/Article/details/gtutowgryc.html

Py:   str(42)
来源：http://dali.redwolf501.top/Article/details/gtbxicvcnr.html

PHP:  (string) 42; strval(42)
来源：http://dali.xziqi.cn/Article/details/gtiatbkbhi.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258888.top/Article/details/gtykdysbor.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtajapgioj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ydzc1.top/Article/details/gtyncilscj.html

Go:   strconv.Itoa(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgkbajgz.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gtjdbewgoj.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gtinsftimm.html

[A08] 取整与四舍五入
来源：http://dali.316326.xyz/Article/details/gtewswingu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtsxajxuqx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jianghu66.top/Article/details/gtwhupatvm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtrzguqhon.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmrcmgma.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtidfjeqde.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtefrihcpf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yongpay.top/Article/details/gtdmauawul.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gttrskqaex.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gthrhawbqk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtkzaqccyq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtxmqfobix.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtqmkqaaqb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtrgptwyzz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gthmppnxrl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gtsrpsiemn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.quarkkingdee.top/Article/details/gtwcxbtysg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtrcyndqpk.html

[A10] 生成随机数
来源：http://dali.316326.xyz/Article/details/gthlmllwdl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.meibo888.top/Article/details/gtgavojeie.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gtyaxrxqid.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tian-w.cn/Article/details/gtyunthual.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtuoqtolpo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jqgufenzy.top/Article/details/gtsozkkveu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhengqikj.top/Article/details/gthrynabcs.html

Ruby: rand(1..100)
来源：http://dali.xuetiantiany.cn/Article/details/gtvupokyub.html

C#:   new Random().Next(1, 101)
来源：http://dali.havefunace.top/Article/details/gtmxhmqdrn.html

[A11] 条件表达式（三元）
来源：http://dali.hnqzz.top/Article/details/gtakxpfhks.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtvnejpvyq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gthhabjjac.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtkiziogzj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekrvpwbp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtwlqfijzh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.kuanghao11.cn/Article/details/gtyfplegrk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtkfcpvitl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtexafjmlb.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtfdiuefbr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelzgwdax.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.mhx1999.top/Article/details/gtbuyswprg.html

JS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gtykkhypdk.html

TS:   `Hello, ${name}!`
来源：http://dali.gzhubu.top/Article/details/gtzzpkvukg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtsaslkzyf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaevlawhh.html

Ruby: "Hello, #{name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtanhexhmy.html

C#:   $"Hello, {name}!"
来源：http://dali.ydzc1.top/Article/details/gtnigbjqtz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gotoacloud.top/Article/details/gthlkckzxx.html

Py:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtnrimmyzv.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtwvdanjoi.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtfswuhlnh.html

TS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gteccipjkp.html

Java: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtxkuhbzal.html

Go:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtqqbwrkai.html

Ruby: "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtliknycvj.html

C#:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtxdqjstvo.html

[A14] 注释写法
来源：http://dali.gogol.net.cn/Article/details/gtzydgywdy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cdnleiting.top/Article/details/gtsohlqrfw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gttwgbcpla.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtncfckqvu.html

TS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtfmrjxoyb.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.dashuyun.cn/Article/details/gtfbvhnpgl.html

Go:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtsogbokhe.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangtech.top/Article/details/gtagblttts.html

C#:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtkpddswgd.html

[A15] 空值判断与默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipgkgvoj.html

Py:   value = data or "默认值"
来源：http://dali.hnqzz.top/Article/details/gtmqjxjbpg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtokjlpfxl.html

JS:   const value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtdzrmoqxt.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtkrzdruif.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ydzc1.top/Article/details/gtzwslgsbw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hnqzz.top/Article/details/gthrlqdmry.html

Ruby: value = data || "默认值"
来源：http://dali.fengsongda.top/Article/details/gtvhsppzwl.html

C#:   var value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gthqswpvzp.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gtmgkeqqsf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gogol.net.cn/Article/details/gtzzrizjva.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hammf.cn/Article/details/gtwhclddot.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gtjdqsjwaz.html

TS:   if (!x) {}
来源：http://dali.yongpay.top/Article/details/gtjhmlbkea.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yvedp.cn/Article/details/gtvxssoirx.html


<!-- 参考信息 -->