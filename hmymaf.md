代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gteskfefgx.html

new Promise((resolve, reject) => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtdmsrsw.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtcgflholt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gtuhnrulzx.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrbqewci.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtqihxkjjm.html

[U98] JS：fetch 带 JSON
来源：http://dali.bjfxy.top/Article/details/gtkxkslhph.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xinyue.icu/Article/details/gtjrbvcmnb.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfycrtnc.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gtdwhlbujy.html

[U100] JS：DOM 查询
来源：http://dali.xuetiantiany.cn/Article/details/gtslqbxnpt.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtlterxttm.html

[U101] JS：classList 操作
来源：http://dali.bjfxy.top/Article/details/gtfcjianag.html

el.classList.toggle("active")
来源：http://dali.iojbl.cn/Article/details/gtvhdjhwov.html

[U102] JS：本地存储
来源：http://dali.sweek.top/Article/details/gtsvjexywr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.kuanghao11.cn/Article/details/gtfwerpijv.html

[U103] JS：定时器
来源：http://dali.xuetiantiany.cn/Article/details/gtjfxoghhc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gthgdycntr.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtbmrktfid.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtvjvmspmu.html

[U105] JS：节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrazbbxcf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gttgyrkyry.html

[U106] JS：日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtjcyykrga.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrltjzuql.html

[U107] JS：数字千分位
来源：http://dali.haohaochexian.top/Article/details/gtxurkvrxy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtvqlfgrgw.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtipnnygho.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtfmdbzdat.html

[U109] JS：数组分组
来源：http://dali.yuxming.cn/Article/details/gtpirlzwvh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtglfubjnl.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtyusnzdmp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.kuanghao11.cn/Article/details/gtyvbkwcju.html

[U111] JS：对象转 Map
来源：http://dali.quarkkingdee.top/Article/details/gttczbsona.html

new Map(Object.entries(obj))
来源：http://dali.daxiang520.top/Article/details/gtppjuzbis.html

[U112] JS：字符串补位
来源：http://dali.nwbrower.top/Article/details/gtsdicfgyh.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtwzphreuo.html

[U113] JS：正则替换全部
来源：http://dali.zhongyouzk.top/Article/details/gtgjdkrozy.html

s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gthbutzvfy.html

[U114] JS：JSON 深比较
来源：http://dali.shzxlz.cn/Article/details/gtvencktfz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgufenzy.top/Article/details/gtudlattiq.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gtwqqkpuqv.html

crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtyssujwqg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tanke756.top/Article/details/gthgirhxfh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gtnlzzyiyt.html

[U117] JS：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtrvyzdhnw.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gthfcustdb.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gtlodgstts.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gtlzpchuyx.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtzsnimqwk.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gtilkcgheo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gtcvxtetlo.html

import.meta.env.VITE_API_URL
来源：http://dali.jianghu66.top/Article/details/gtmoeraygr.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtzidsubbb.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtytoltxif.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlrqpaxcu.html

按语言统计（条）：
来源：http://dali.xinyue.icu/Article/details/gtruerfwug.html

Python ......... 252
来源：http://dali.haohaochexian.top/Article/details/gtdbvbvltl.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtcttvgkym.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gtjwbnnojo.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtbortqdrx.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtggbzolof.html

Go ............. 212
来源：http://dali.aizwys.cn/Article/details/gtwpuamlqj.html

Ruby ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gtdmwftlnp.html

C# ............. 212
来源：http://dali.shuidangran.top/Article/details/gtlxbrwrfq.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtmjnapvcn.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtkvceapac.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gtwwimjtdr.html

Bash ........... 80
来源：http://dali.dianchejie.cn/Article/details/gtqwhfmoki.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gthytzcwle.html

Swift .......... 15
来源：http://dali.nwbrower.top/Article/details/gttmbzkhhk.html

Lua ............ 10
来源：http://dali.svipenyu.cn/Article/details/gtvgawiwdt.html

Perl ........... 10
来源：http://dali.tanke756.top/Article/details/gtrogcvzon.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gtyubbffvt.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtokvrmfpr.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gtogkvnauw.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtaedgkkfk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gtnroxfobh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtnsjaffde.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gttrjymoeo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hnxiangtu.top/Article/details/gtkcbyeecu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gtermmmokb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtdzqhhpcy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtmrwoqbus.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtffbiivyr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtyfrkswme.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtunwearng.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gtjdjissth.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtxcthsfck.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtoczddbhn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenlongwang.top/Article/details/gtufovhgzl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gogol.net.cn/Article/details/gtsqqwfray.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtoijyocqz.html

Q SQL 专题                              90
来源：http://dali.zycfv.cn/Article/details/gtbonafxiz.html

R Bash 专题                             80
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhrtngpn.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gtfxzjkepk.html

T 其他语言补充                          60
来源：http://dali.316326.xyz/Article/details/gthklmgrcw.html

U 高频实用片段                         120
来源：http://dali.xuetiantiany.cn/Article/details/gtxxntovqs.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsykqpsk.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtqrnpwonp.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gthhrbqsgl.html

使用提醒
来源：http://dali.andypj.xyz/Article/details/gtcvsrauyi.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtmdwrslua.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gtpkjqbsvu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gtyjbmgnvj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gtibobkthb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gtqbpdnksg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shuidangran.top/Article/details/gtjnnshtfj.html

—— 文件结束 ——
来源：http://dali.yj20258888.top/Article/details/gtwnherpyu.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzpjorewt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xuetiantiany.cn/Article/details/gtzpwnsnlv.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gttxhpmtlz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuiqmjvsi.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gtognuecyl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gtkynirdaa.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gtelgksora.html

SQL · Bash · C · C++
来源：http://dali.yueranfly.top/Article/details/gtpnjmbeex.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xinyue.icu/Article/details/gtexmattqh.html

【使用说明】
来源：http://dali.jinqigufen.top/Article/details/gtdwoucgcn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zycfv.cn/Article/details/gtoifvhsri.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgfzy.top/Article/details/gtybexlejf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsjxxgid.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gtdtefkxch.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gtihacwqnu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gtzhjthaur.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gtphutjavk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.kuanghao11.cn/Article/details/gthxxtrnyg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gogol.net.cn/Article/details/gtgnplzoud.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yanxiufei.cn/Article/details/gtbalgkhwv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gtdtocmqge.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.wangshuangyany.cn/Article/details/gtufiuhzda.html

【文件统计】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbtxwdnj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmsbxsadh.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gtlbzvqmbr.html

目  录
来源：http://dali.zycfv.cn/Article/details/gtfkkqkheh.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtsmylvkai.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.vqdsnc.cn/Article/details/gtkvawcwkf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.fzhhl.top/Article/details/gtlqeqtbda.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yueranfly.top/Article/details/gtpbnaqczv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtlzwqpsjm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ybcxt.top/Article/details/gtmshidttg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cheryme.top/Article/details/gtotsomzob.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gttgricdyu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtuyjrjgof.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtiecjsasz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigfzy.top/Article/details/gtznkoegde.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtalddnuru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pycfn.com/Article/details/gtyvcebfml.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gturcbhylw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjdvqldgr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.feifeiyinyue.top/Article/details/gthobhbsjt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtpgodgbqq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.vqdsnc.cn/Article/details/gthfurvtla.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gtfhecrhob.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xuanzx.com/Article/details/gtljmsibsz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gtfyukmyls.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtbhstacfa.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtldbkktjz.html

A. 基础语法与类型
来源：http://dali.tian-w.cn/Article/details/gtzgqiixzk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttvpryulk.html

[A01] Hello World
来源：http://dali.andypj.xyz/Article/details/gtomcdqnqq.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gtneykpkue.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gtdfvzunjj.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtjnuacxmx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.guannengcc.top/Article/details/gteqvvliwn.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtlktglykb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtktczvbrm.html

Ruby: puts "Hello, World!"
来源：http://dali.cucudq.cn/Article/details/gtlgnlylom.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtgkybmhhq.html

[A02] 变量声明与赋值
来源：http://dali.hysaishi.cn/Article/details/gtqtajfzad.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gttzrnfuhm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtbnmipdvk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yongpay.top/Article/details/gthwwcajgt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtluatsxnj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtljczjhdd.html

Go:   name := "Alex"; age := 20
来源：http://dali.dianchejie.cn/Article/details/gtuonwryai.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daria6918.cn/Article/details/gtzfwwuemw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtjoofcaca.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtfnmykqly.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gtifalsxvv.html

PHP:  const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gthjhokrix.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtbgsospxg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlhswtdrq.html

Java: static final double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtrcbybwjv.html

Go:   const PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtmvupzyxg.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gttfchtxdz.html

C#:   const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gttzreenii.html

[A04] 判断变量类型
来源：http://dali.yonumen.top/Article/details/gtnybtnqzi.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258.top/Article/details/gtntngebgn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gotoacloud.top/Article/details/gtgqpdydgg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtlnhcedbx.html

TS:   typeof x; x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtfheonxuv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhoulong.xyz/Article/details/gtunbvtrev.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtvcdckqyf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gtobqflbcs.html

C#:   x.GetType().Name; x is int
来源：http://dali.fzhhl.top/Article/details/gtujbnwvjy.html

[A05] 整数除法与取模
来源：http://dali.yonumen.top/Article/details/gtmvaorzwk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yvedp.cn/Article/details/gtgpequvxg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtkzlkmbna.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtuqlrwjst.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtrgitoqna.html

Java: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtphlbeiab.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtmcqlshhg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtrmbodfpi.html

C#:   7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtlgdirlox.html

[A06] 字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtnnomtctk.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtktcybwkl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daria6918.cn/Article/details/gtyovaybqd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hammf.cn/Article/details/gtkmydwpbw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yonumen.top/Article/details/gtnmkeosyf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtcialpnwq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gtgiyjozth.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gtzpahbipw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hammf.cn/Article/details/gtibbxsico.html

[A07] 数字转字符串
来源：http://dali.cheryme.top/Article/details/gtihtewpyq.html

Py:   str(42)
来源：http://dali.cdnleiting.top/Article/details/gtprmkozus.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gthlmftryc.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrisfdbop.html

TS:   String(42)
来源：http://dali.xziqi.cn/Article/details/gthcpifzgy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nwbrower.top/Article/details/gtzyselpcy.html

Go:   strconv.Itoa(42)
来源：http://dali.ydzc1.top/Article/details/gtexyptojj.html

Ruby: 42.to_s
来源：http://dali.yuanzhike.top/Article/details/gtqnkycudl.html

C#:   42.ToString()
来源：http://dali.kuanghao11.cn/Article/details/gtqiyqrcmp.html

[A08] 取整与四舍五入
来源：http://dali.xuetiantiany.cn/Article/details/gtsdfybwoi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtphbiplgk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.9152youxi.cn/Article/details/gthzkhnpzt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtklvpxzjx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.snrcjt.cn/Article/details/gtqgbadjqa.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtohgiidkx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtveimeoix.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdywxmgnq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtngqwccav.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtiwscaapc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtqjfeeilo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtpprdpwum.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtuvulmdhz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtwsmqzoay.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtrzmslwqk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgfzy.top/Article/details/gtflacbtpx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cashguo.top/Article/details/gtzxuvtlml.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gthawvnkhe.html

[A10] 生成随机数
来源：http://dali.hnxiangtu.top/Article/details/gtohgefjtk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.bjfxy.top/Article/details/gtxunfuvve.html

PHP:  random_int(1, 100);
来源：http://dali.nanxuanxn.top/Article/details/gtrkqltzcz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtmfhtxflb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gthomzjegk.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xuetiantiany.cn/Article/details/gtnuzqkvdp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gtcugnifnt.html

Ruby: rand(1..100)
来源：http://dali.shuidangran.top/Article/details/gtsvlpxqdy.html

C#:   new Random().Next(1, 101)
来源：http://dali.tian-w.cn/Article/details/gtilafmrxo.html

[A11] 条件表达式（三元）
来源：http://dali.yuxming.cn/Article/details/gtylpmqgsh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqhhnsac.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtutddkmya.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gthkkrifzg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtadwcdtbo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtujivmxxt.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.9152youxi.cn/Article/details/gtvhsmomcl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtzdbzypmb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtnwvnsweq.html

[A12] 字符串插值 / 格式化
来源：http://dali.yueranfly.top/Article/details/gtrwbqmhlu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shzxlz.cn/Article/details/gtvifxcjfp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.smart0.xyz/Article/details/gtfkhvbxap.html

JS:   `Hello, ${name}!`
来源：http://dali.aibaodan.cn/Article/details/gtzxwtocng.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtwhbauyya.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jyoumei.cn/Article/details/gtvqyhlxec.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.nwbrower.top/Article/details/gtixcrgwhs.html

Ruby: "Hello, #{name}!"
来源：http://dali.daxiang520.top/Article/details/gtzgkavrtz.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gtasumioso.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ivvv.top/Article/details/gtzjxwaspp.html

Py:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtgrsyaecb.html

PHP:  "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtyvnsxiol.html

JS:   "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtrjpeiqix.html

TS:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gteowyqdvy.html

Java: "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtjfycgsnz.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtzadbwzfw.html

Ruby: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtqrgamkpn.html

C#:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtsdvxgxim.html

[A14] 注释写法
来源：http://dali.tian-w.cn/Article/details/gtrsqsptmy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hysaishi.cn/Article/details/gtcnlarmqg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtggkehxew.html

JS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtfgbcvgbs.html

TS:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gtygpztbed.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gtzzgtvccw.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtwfjeffcq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ehwqpu.com/Article/details/gtrwaeefxe.html

C#:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gtfzwiizla.html

[A15] 空值判断与默认值
来源：http://dali.meibo888.top/Article/details/gtfmajyrng.html

Py:   value = data or "默认值"
来源：http://dali.gogol.net.cn/Article/details/gttvxhkfph.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtovmfoocm.html

JS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gttcylervb.html

TS:   const value = data ?? "默认值";
来源：http://dali.yangfankeji.com/Article/details/gtpfbjwbxd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfenactw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.pycfn.com/Article/details/gtkbarypzx.html

Ruby: value = data || "默认值"
来源：http://dali.ydzc1.top/Article/details/gtldivzrcp.html

C#:   var value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtecamkays.html

[A16] 真假值判断规则
来源：http://dali.yj202588.top/Article/details/gtumsdfllj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xylfe.cn/Article/details/gtcblfivsh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dashuyun.cn/Article/details/gtzmnfiwsb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtkmvqbacx.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gtxscnxjzk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daria6918.cn/Article/details/gtawxtsiof.html


<!-- 参考信息 -->