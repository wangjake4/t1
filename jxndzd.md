代发 wailian999

[U97] JS：并发请求
来源：http://dali.cdnleiting.top/Article/details/gtcfavnstt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtjllygavr.html

[U98] JS：fetch 带 JSON
来源：http://dali.snrcjt.cn/Article/details/gtgseoidgo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gtgbwsdxug.html

[U99] JS：事件监听
来源：http://dali.wangdashe.top/Article/details/gttdfjemle.html

el.addEventListener("click", e => {})
来源：http://dali.kuanghao11.cn/Article/details/gthticbpgw.html

[U100] JS：DOM 查询
来源：http://dali.pycfn.com/Article/details/gtsqzxfmcj.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtkraerxic.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtbkcgmgfg.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gtwxakzwdm.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gtwcowmkrd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yonumen.top/Article/details/gtrxzujdga.html

[U103] JS：定时器
来源：http://dali.jinghuilouyu.cn/Article/details/gtxybfgmaw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fengsongda.top/Article/details/gtwgiikdoj.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gtngyqsflr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtnyrrhxtw.html

[U105] JS：节流
来源：http://dali.guowangkeji.top/Article/details/gtwlessqtd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gtkhtsdaby.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtpulhyywe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ppjwa.cn/Article/details/gteaorgtjz.html

[U107] JS：数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtteixfuin.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtlmcbxfac.html

[U108] JS：随机整数
来源：http://dali.yuxming.cn/Article/details/gtxcglyfif.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtydweisny.html

[U109] JS：数组分组
来源：http://dali.ivvv.top/Article/details/gtdnthonsr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenzaomai.com/Article/details/gtclmfdrht.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtfueexbjw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daxiang520.top/Article/details/gtqmpykwoc.html

[U111] JS：对象转 Map
来源：http://dali.xylfe.cn/Article/details/gtikmopxpf.html

new Map(Object.entries(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtduvawese.html

[U112] JS：字符串补位
来源：http://dali.ydzc1.top/Article/details/gtpcbrmobz.html

"7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gtczulyuno.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtwsuldfvg.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gthlwohptk.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gtmpvouysr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gtkyhqqylb.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbztxnuk.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtlrqrbctn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtsgwzstco.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsotxnsqw.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtkshneryu.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtrzuykqwk.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtspmkdrqc.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gtaytiqxvi.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gttdbijmku.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gtleaadqrq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtkwdcmmtc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gtcdjejxyp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtyyobnqen.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqytyowr.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtqczjsktz.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtcsbnqilg.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsgpkchl.html

PHP ............ 252
来源：http://dali.jqgufenzy.top/Article/details/gtdsfvtrkv.html

JavaScript ..... 252
来源：http://dali.zhengqikj.top/Article/details/gtwpiwhtof.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gtoyhtxmks.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtplpxiwnd.html

Go ............. 212
来源：http://dali.shuidangran.top/Article/details/gtqbgpikwc.html

Ruby ........... 212
来源：http://dali.cucudq.cn/Article/details/gtrwxhzjuh.html

C# ............. 212
来源：http://dali.316326.xyz/Article/details/gtoxgwqudb.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gtwbgwdbfl.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gtnekivoak.html

SQL ............ 90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylcqtiwe.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gtxxdpryos.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gticgksiku.html

Swift .......... 15
来源：http://dali.haohaochexian.top/Article/details/gtkmefobpl.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtrhhyumyk.html

Perl ........... 10
来源：http://dali.guannengcc.top/Article/details/gteqnynxcc.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gtzncavsex.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuywrigmh.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyikrkow.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevllnxhh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gtdftmdmrz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtwlgurpps.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gtfkfolbye.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gtfwrwlxib.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gtbxuhgxkw.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtjqfvxtui.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gttikbyxmp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gtddifmavg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtvlduldhw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalawezzq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gttrvbdvzq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtduwtgiqm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gtmxysulau.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtyoaqisob.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ybcxt.top/Article/details/gtneelxqlw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfqocmyi.html

Q SQL 专题                              90
来源：http://dali.hongshengwenyu.top/Article/details/gttaznhlhk.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtvyzvvyhw.html

S C / C++ 专题                          60
来源：http://dali.hysaishi.cn/Article/details/gtgxictyao.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtkttijqsu.html

U 高频实用片段                         120
来源：http://dali.hongshengwenyu.top/Article/details/gtkzkrdjsa.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gtigcvgnld.html

合计                                  2106 条
来源：http://dali.yongpay.top/Article/details/gtdccvkkdw.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtmoafsnll.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gtubkhysjo.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtuiccklfm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtmopihvbi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgsjkqje.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.haohaochexian.top/Article/details/gtihjuudbg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daxiang520.top/Article/details/gtaamejzch.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gtaphylmwk.html

—— 文件结束 ——
来源：http://dali.jyoumei.cn/Article/details/gtkncitegh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzkfisdki.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gtdjexwhld.html

Common Programming Examples Cheat Book
来源：http://dali.yvedp.cn/Article/details/gtsetzpcvx.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtuxllramf.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gtlawlypob.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gtoxqgtope.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.aibaodan.cn/Article/details/gttuozpglg.html

SQL · Bash · C · C++
来源：http://dali.tanke756.top/Article/details/gtrhbpcapj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gtvkrnhovu.html

【使用说明】
来源：http://dali.yonumen.top/Article/details/gtbwvqklxm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gtnqkuljmk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.hongshengwenyu.top/Article/details/gtihrajvvk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shuidangran.top/Article/details/gttpmjcywd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cqqwz.cn/Article/details/gtubtbgmbp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hammf.cn/Article/details/gtmjvqvbwe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gtklszixmd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhiwuduotai.top/Article/details/gtwrjkhsfi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.redwolf501.top/Article/details/gtbpuvlble.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.smart0.xyz/Article/details/gtxjwhyqni.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gotoacloud.top/Article/details/gtysjconhu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtbdhepwbj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xuetiantiany.cn/Article/details/gtdnqqgedh.html

【文件统计】
来源：http://dali.gotoacloud.top/Article/details/gtswcrhhpz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gtavtergcf.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gttxofaqwe.html

目  录
来源：http://dali.jyoumei.cn/Article/details/gtfyiocmwf.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtpisvyehs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtazonyrzs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtadvklump.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gtvqgvktqa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtutaqffxs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhxwpjhs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtbudppyln.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.fengsongda.top/Article/details/gtgyiqpueh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtdjjvdnpc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtelskdnxs.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtqtoaytzu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtuykfsrax.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtrjxzctms.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gtqvyxznqn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gtbkyhzlvg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tianlin.xyz/Article/details/gtqvunjald.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtjflonebd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.daxiang520.top/Article/details/gtgrkabmro.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sysykeji.top/Article/details/gtqdprtvww.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daxiang520.top/Article/details/gtkjirvels.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtpxgkecfj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtyzvvgcqd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtugngivcx.html

A. 基础语法与类型
来源：http://dali.mhx1999.top/Article/details/gtrnlhougl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdcdvdsnb.html

[A01] Hello World
来源：http://dali.guannengcc.top/Article/details/gtpjroggbi.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtqzbuyoez.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gtrrqpkfqg.html

JS:   console.log("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtjhooongy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gtgnzquztc.html

Java: System.out.println("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtyhpdjwqb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gtklchhypa.html

Ruby: puts "Hello, World!"
来源：http://dali.316326.xyz/Article/details/gtmbxqqzyy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjoytupw.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtiylqwvyv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlfebkzr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtineyflwh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gtirexnugo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtwazthlbv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gtgqlezlip.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gtjsoggygi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yanxiufei.cn/Article/details/gtawjqonbl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtfnpahkvm.html

[A03] 常量定义
来源：http://dali.kuanghao11.cn/Article/details/gtilyntytd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.dianchejie.cn/Article/details/gtvuxhgczm.html

PHP:  const PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtpnqflpuk.html

JS:   const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtkahesiib.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtfdjljvdr.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gttcdlvcbf.html

Go:   const PI = 3.14159
来源：http://dali.ybcxt.top/Article/details/gtcegyhgoy.html

Ruby: PI = 3.14159
来源：http://dali.hnxiangtu.top/Article/details/gtcpgnohvp.html

C#:   const double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtxciqplrt.html

[A04] 判断变量类型
来源：http://dali.iojbl.cn/Article/details/gtbwxorjuy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gtkaznsxfs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tianlin.xyz/Article/details/gtvlurngge.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtwlslqnjz.html

TS:   typeof x; x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtsseqqjrn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmrmitap.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cdnleiting.top/Article/details/gtaezgcjoa.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gtckfemqhx.html

C#:   x.GetType().Name; x is int
来源：http://dali.nanxuanxn.top/Article/details/gttnuejcbv.html

[A05] 整数除法与取模
来源：http://dali.andypj.xyz/Article/details/gtgrbuymqk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jianghu66.top/Article/details/gtusqzsjfl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtwjxkdwko.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtefbjvtpu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtfozucspf.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtwicrheah.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtamdggugr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtrynrjtiw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtpaahmgnh.html

[A06] 字符串转数字
来源：http://dali.yangfankeji.com/Article/details/gtnqqnxeis.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtpiryshoy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizqssjuu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxinkj.top/Article/details/gthiuynttj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gtmdwfjvrn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtjasktlnm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtqpvpiocq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cashguo.top/Article/details/gtszpxsyge.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtqnvyaqhr.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtnudqijmy.html

Py:   str(42)
来源：http://dali.hfpthk.cn/Article/details/gtmxdcpubm.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtjkemyhas.html

JS:   String(42); (42).toString()
来源：http://dali.nanxuanxn.top/Article/details/gtrscflaev.html

TS:   String(42)
来源：http://dali.redwolf501.top/Article/details/gtdpkzmfri.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnqzz.top/Article/details/gtnjzjbjkr.html

Go:   strconv.Itoa(42)
来源：http://dali.yuanzhike.top/Article/details/gtjpaxexhl.html

Ruby: 42.to_s
来源：http://dali.guannengcc.top/Article/details/gtorgkpzae.html

C#:   42.ToString()
来源：http://dali.yj202588.top/Article/details/gteakjtgsj.html

[A08] 取整与四舍五入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbuigbwoz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtlkihiwne.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdopzmgua.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gttnxvhjsv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sweek.top/Article/details/gttvgthegy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gteqotyino.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtseaxkrbj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.iojbl.cn/Article/details/gtujtvulii.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtvgauesvv.html

[A09] 绝对值与最大最小值
来源：http://dali.andypj.xyz/Article/details/gtyhitrdja.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.316326.xyz/Article/details/gtwtfzeoqi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtimtnmjhz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtvucesaah.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtusqewdwj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gthiwntskk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ivvv.top/Article/details/gtmyznsfjp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jyoumei.cn/Article/details/gtjzhmoces.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.havefunace.top/Article/details/gttbjkrhev.html

[A10] 生成随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtxwsgjlkf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuanzhike.top/Article/details/gtpsenzeue.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtuphoqqbx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtqfocnqzm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tanke756.top/Article/details/gtbcubtjzs.html

Java: new Random().nextInt(100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gtyprqgyby.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cheryme.top/Article/details/gtcozaqpip.html

Ruby: rand(1..100)
来源：http://dali.jianghu66.top/Article/details/gtejkrokio.html

C#:   new Random().Next(1, 101)
来源：http://dali.jlsjyb.cn/Article/details/gtewmwjdqw.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtehhejpja.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yanxiufei.cn/Article/details/gthpwcrnxn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gtpewuhpxw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtmmtrgbky.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtykcmvorj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtctqwmtgx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gtczibpmwl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtrmnpauvq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtagnbxxfh.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gtpbswhbwd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sweek.top/Article/details/gthdppbnbx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.birdmap.top/Article/details/gtadvsqygl.html

JS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gtxefsfznv.html

TS:   `Hello, ${name}!`
来源：http://dali.tianlin.xyz/Article/details/gtlkmbxnrl.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.fzhhl.top/Article/details/gtcmswlfaj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tanke756.top/Article/details/gtdvtmqsqv.html

Ruby: "Hello, #{name}!"
来源：http://dali.aibaodan.cn/Article/details/gtqgaayxjk.html

C#:   $"Hello, {name}!"
来源：http://dali.jlsjyb.cn/Article/details/gtzzyxdkgl.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.feifeiyinyue.top/Article/details/gtsftusndh.html

Py:   "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtzmvrrhum.html

PHP:  "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtnvrojuqi.html

JS:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatskbsgt.html

TS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtlkxspfgy.html

Java: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtskyhixyy.html

Go:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtrmzhbovb.html

Ruby: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtdbsaojkk.html

C#:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtuluotvdq.html

[A14] 注释写法
来源：http://dali.chenjidiqi.icu/Article/details/gtdjmpstso.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xuanzx.com/Article/details/gtghjmzzmu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtpjckzybo.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtklwqgkub.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gtsnpakuzr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zdqjudy.top/Article/details/gtfcfkbrhj.html

Go:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtblqwblnt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yanxiufei.cn/Article/details/gtutcbbmqr.html

C#:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtowhvocyu.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gtftvczrrr.html

Py:   value = data or "默认值"
来源：http://dali.fzhhl.top/Article/details/gtxmtzlxle.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtzocwmidf.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gtktulcaab.html

TS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtjkeuknzl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gtmrfscofn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.quarkkingdee.top/Article/details/gtbnrdjxzd.html

Ruby: value = data || "默认值"
来源：http://dali.cucudq.cn/Article/details/gtqxskopks.html

C#:   var value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gtkctwzhjz.html

[A16] 真假值判断规则
来源：http://dali.hnqzz.top/Article/details/gtssvytphf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinqigufen.top/Article/details/gtmpvsrxbw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.iojbl.cn/Article/details/gtbphnzcij.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzritumsg.html

TS:   if (!x) {}
来源：http://dali.ybcxt.top/Article/details/gtcrwzszev.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxinkj.top/Article/details/gtkdvclaap.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnqzz.top/Article/details/gtoribwnxl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.daria6918.cn/Article/details/gthkkcdmig.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.c1oappe.top/Article/details/gtspshwstb.html

[A17] 位运算
来源：http://dali.meibo888.top/Article/details/gtcajkione.html


<!-- 参考信息 -->