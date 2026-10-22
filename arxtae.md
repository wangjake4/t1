代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gttuigqzkf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guowangkeji.top/Article/details/gtfumodiza.html

[U92] JS：深拷贝
来源：http://dali.iojbl.cn/Article/details/gtypekttvd.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtgskbcvoq.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdcaglyi.html

`共 ${n} 条`
来源：http://dali.bjfxy.top/Article/details/gtpmcesekn.html

[U94] JS：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtivkgvldf.html

const double = x => x * 2;
来源：http://dali.hnqzz.top/Article/details/gthtqcrzzv.html

[U95] JS：Promise 包装
来源：http://dali.yanxiufei.cn/Article/details/gtzyledwqs.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gtmbyixzjw.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gthejlvzrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtxcnenmni.html

[U97] JS：并发请求
来源：http://dali.ybcxt.top/Article/details/gtrrvpcbpv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hfpthk.cn/Article/details/gtqrxzrywc.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtjhxsvmkz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ydzc1.top/Article/details/gtlkkimrdi.html

[U99] JS：事件监听
来源：http://dali.guowangkeji.top/Article/details/gtnizmcijo.html

el.addEventListener("click", e => {})
来源：http://dali.meibo888.top/Article/details/gtvcpglkit.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtqihhkesz.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gtejkmzmui.html

[U101] JS：classList 操作
来源：http://dali.jqgufenzy.top/Article/details/gtdczfjsyw.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gtnqedsjgt.html

[U102] JS：本地存储
来源：http://dali.pycfn.com/Article/details/gtlzujmios.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtcnhsmpmx.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtovzegvqd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xuetiantiany.cn/Article/details/gthgtuxxic.html

[U104] JS：防抖
来源：http://dali.jqgfzy.top/Article/details/gteiwrxejd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtpbfdufcb.html

[U105] JS：节流
来源：http://dali.jlsjyb.cn/Article/details/gttkgvirkb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.redwolf501.top/Article/details/gtiafqisau.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gtmwesbqup.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gtifualuzs.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtylyunjmw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtlytasnbv.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gtgqynwtfy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gteexscjsu.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtllsciaee.html

Object.groupBy(arr, x => x.type)
来源：http://dali.birdmap.top/Article/details/gtksyhbwsu.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gtlrineetm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gtmjdhpyld.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gtjiugaopn.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtytsjctzw.html

[U112] JS：字符串补位
来源：http://dali.haohaochexian.top/Article/details/gtajkyflnf.html

"7".padStart(3, "0")
来源：http://dali.cucudq.cn/Article/details/gtjxdutqoy.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gtddfrdduv.html

s.replaceAll("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gthgqziaqv.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdotgutks.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gtedzmcbdx.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtckivbjeh.html

crypto.randomUUID()
来源：http://dali.jiagoushi.top/Article/details/gtjimpgjiv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtdlujqzen.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtylazulsa.html

[U117] JS：单元测试
来源：http://dali.daxiang520.top/Article/details/gtnauyaqko.html

npm i -D vitest;  npx vitest
来源：http://dali.cqqwz.cn/Article/details/gtakvsnggv.html

[U118] JS：开发服务器
来源：http://dali.cdnleiting.top/Article/details/gtoupddpdy.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gtkguvccqu.html

[U119] JS：生产构建
来源：http://dali.andypj.xyz/Article/details/gtwsmaroah.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtwysxwkkl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtmezwmirp.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtgpzugdhl.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtxzoqihji.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtneurvzhc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdzwmlvag.html

按语言统计（条）：
来源：http://dali.yj20258888.top/Article/details/gtfgdplpsc.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtsvgqgocl.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtpchahhuj.html

JavaScript ..... 252
来源：http://dali.ydzc1.top/Article/details/gtrthyokas.html

TypeScript ..... 212
来源：http://dali.zhoulong.xyz/Article/details/gtajmvrslc.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtcuqkixoo.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtxkabprxl.html

Ruby ........... 212
来源：http://dali.xinyue.icu/Article/details/gtgelpbjcf.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtemuufklx.html

C .............. 30
来源：http://dali.dashuyun.cn/Article/details/gtshrgzmfu.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gteqbnuown.html

SQL ............ 90
来源：http://dali.fengsongda.top/Article/details/gtiatuulqo.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdumlmhn.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gtckjyncaf.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gtkbgaktaa.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gtagcqgbie.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gtdyrhgjpe.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtoqxqpwar.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gtijowxlsr.html

合计 ........... 2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtfqgvubfy.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gtqgdxbmqi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtxmuqlzre.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtyjkztzim.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sxryk.cn/Article/details/gtzkznonon.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gtitankhdz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gtjtarpqdp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtlelhqtzl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtkwcgdfzo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gtijdlsyvg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtgggpgxdo.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtizghytsk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtaimcfsjb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtmvsdtvqh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gteudrcudj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zycfv.cn/Article/details/gtrnlhlbkr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gtulwlnxdq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtpnyudexo.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gtdkhglhet.html

R Bash 专题                             80
来源：http://dali.fzhhl.top/Article/details/gtohlonamv.html

S C / C++ 专题                          60
来源：http://dali.sxryk.cn/Article/details/gtzcuhrqtc.html

T 其他语言补充                          60
来源：http://dali.hnqzz.top/Article/details/gtnckretth.html

U 高频实用片段                         120
来源：http://dali.shuidangran.top/Article/details/gtqjuokzrg.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtpxyutiqx.html

合计                                  2106 条
来源：http://dali.yj202588.top/Article/details/gthrgjjxbm.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffbqllkb.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gttsvniihi.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtpgeywoiu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.iojbl.cn/Article/details/gtotgjjzkq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gtqimsourq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cucudq.cn/Article/details/gtylsnojni.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhixingplan.top/Article/details/gtlosavwff.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtperwlbxi.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtkvpjevrb.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqqfljjwt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cheryme.top/Article/details/gtgdcmoazf.html

Common Programming Examples Cheat Book
来源：http://dali.hongshengwenyu.top/Article/details/gtqszzpejo.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtbtxmrbmj.html

【收录内容】
来源：http://dali.jinqigfzy.top/Article/details/gtufidiuyl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gtxvkdtrrf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gtdysrkqhh.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gtvsbcedmh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zycfv.cn/Article/details/gtbuvebcwd.html

【使用说明】
来源：http://dali.sweek.top/Article/details/gtvjggjzjc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.svipenyu.cn/Article/details/gtggrqnmdm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gtgaxxoklv.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.tanke756.top/Article/details/gtqhvcjqay.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zycfv.cn/Article/details/gtgdimkxgu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoawtdfqc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cucudq.cn/Article/details/gtqgwvjfng.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaeftfcw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gtdrajbefr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gtesdyrfsz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.daria6918.cn/Article/details/gtugpemxkp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gzhubu.top/Article/details/gtjutapghk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gtuhyfbosr.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gtsepntjyg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yueranfly.top/Article/details/gttkxdfzys.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtkcbfnicl.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gtwlyprkof.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtdymypfmv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sufxvd.cn/Article/details/gtxdtioztm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtehkxylno.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvelrxhpl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gtxeyxlnby.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtgkflaqgv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gtyvtnvzzb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtfkcqhgjn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtkmdkseoe.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtxjbpfgzf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj202588.top/Article/details/gtmxrlgwzi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtubtcnogn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtaxjpivyi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gthimpsfud.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gttvxomlkh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj202588.top/Article/details/gtbkudzqnr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtalghuzyl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhengqikj.top/Article/details/gtaiffsamc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtklafchsn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gtmghwujyz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gthbwujbyj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gttqzjjjkx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteweosigy.html

A. 基础语法与类型
来源：http://dali.ybcxt.top/Article/details/gtgaloakre.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtktcctpgk.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gttyslteox.html

Py:   print("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvxdscae.html

PHP:  echo "Hello, World!";
来源：http://dali.mhx1999.top/Article/details/gtedidenly.html

JS:   console.log("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtoazlixze.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.nanxinkj.top/Article/details/gtxdxnwfqx.html

Java: System.out.println("Hello, World!");
来源：http://dali.aizwys.cn/Article/details/gtmujywict.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gtrorkmgea.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gtbsgycpfx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtctbwyvul.html

[A02] 变量声明与赋值
来源：http://dali.hysaishi.cn/Article/details/gtpvritwhr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aibaodan.cn/Article/details/gtbmylfrwf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cheryme.top/Article/details/gtyijkgmho.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtywrobkti.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.andypj.xyz/Article/details/gtchxdieru.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gteagezmep.html

Go:   name := "Alex"; age := 20
来源：http://dali.tanke756.top/Article/details/gtqnvhdqgw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtiojmmecm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtixcypqtf.html

[A03] 常量定义
来源：http://dali.feifeiyinyue.top/Article/details/gtsedfsjab.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtrhhgsdmw.html

PHP:  const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtpsiiqmhb.html

JS:   const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtqbdnnliq.html

TS:   const PI: number = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtxqcggwdv.html

Java: static final double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtbxcvkcxs.html

Go:   const PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtuorecrnt.html

Ruby: PI = 3.14159
来源：http://dali.haohaochexian.top/Article/details/gtljzzklgk.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtqjrznnpi.html

[A04] 判断变量类型
来源：http://dali.andypj.xyz/Article/details/gtjqgvofxn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.smart0.xyz/Article/details/gtlfebsbva.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sxryk.cn/Article/details/gtxpcxzkur.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyqgzjkp.html

TS:   typeof x; x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtreepdshm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.pycfn.com/Article/details/gtzopmlnqa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.pengpengdd.cyou/Article/details/gthjjgvbii.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.kuanghao11.cn/Article/details/gtsqrthalf.html

C#:   x.GetType().Name; x is int
来源：http://dali.nwbrower.top/Article/details/gtzcjcleyx.html

[A05] 整数除法与取模
来源：http://dali.xylfe.cn/Article/details/gtmcezphml.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ppjwa.cn/Article/details/gtixdlppon.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcsllhrp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtmcqgyggl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtzutupxtt.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtvbfpnsay.html

Go:   7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtvllwheyr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtbuarlktg.html

C#:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtcimefbum.html

[A06] 字符串转数字
来源：http://dali.pycfn.com/Article/details/gtoyelybva.html

Py:   int("42"); float("3.14")
来源：http://dali.redwolf501.top/Article/details/gtdhsifypy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gogol.net.cn/Article/details/gtabsolcee.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtmkrqvrgq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gtvyhvikbx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ydzc1.top/Article/details/gtygjugjls.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gtbykvkftu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guannengcc.top/Article/details/gtjfklvadm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gtuglpvzno.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gtusferpws.html

Py:   str(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtcnfamraa.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsnytfpma.html

JS:   String(42); (42).toString()
来源：http://dali.pycfn.com/Article/details/gtmcufpzit.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtavrufokd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tianlin.xyz/Article/details/gtqcstfnpr.html

Go:   strconv.Itoa(42)
来源：http://dali.yonumen.top/Article/details/gtqxbxyjpz.html

Ruby: 42.to_s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuqqwuqo.html

C#:   42.ToString()
来源：http://dali.mhx1999.top/Article/details/gtozrhbkve.html

[A08] 取整与四舍五入
来源：http://dali.hongshengwenyu.top/Article/details/gtgdbnuuxd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtvmzorrau.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdtuqfmut.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtznckkbao.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.bjfxy.top/Article/details/gtbfsyamtd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtdvtogkyb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtrmfpqlxe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shuidangran.top/Article/details/gtpsszlddm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxoqnysus.html

[A09] 绝对值与最大最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpqbmyhk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtxyfvxkqw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zycfv.cn/Article/details/gthllyhitw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtxfafuxnw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtjvucbklg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtarpcrdwx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nwbrower.top/Article/details/gtuvvcxpky.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pycfn.com/Article/details/gtmmbrvlix.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtsuhcphfl.html

[A10] 生成随机数
来源：http://dali.yuanzhike.top/Article/details/gtrgovtayc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ppjwa.cn/Article/details/gtfoaohuse.html

PHP:  random_int(1, 100);
来源：http://dali.xziqi.cn/Article/details/gtahwnxqku.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtclwyapwo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gtpnvtetbi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtetmfqqqb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tian-w.cn/Article/details/gtslcqavuq.html

Ruby: rand(1..100)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjeqoofqx.html

C#:   new Random().Next(1, 101)
来源：http://dali.jianghu66.top/Article/details/gttyarsuiu.html

[A11] 条件表达式（三元）
来源：http://dali.nanxinkj.top/Article/details/gtxywznoab.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj20258888.top/Article/details/gtccjtqdfw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtpdhkzzil.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtlotztnji.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gthnbrohdz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtsxcjrnyr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yangfankeji.com/Article/details/gtfphuyalq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamajluop.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtwntndidi.html

[A12] 字符串插值 / 格式化
来源：http://dali.gogol.net.cn/Article/details/gtpbskxkgj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsxtcpgt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.feifeiyinyue.top/Article/details/gtuorhdpjb.html

JS:   `Hello, ${name}!`
来源：http://dali.xziqi.cn/Article/details/gtuzhdgctn.html

TS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkmnhazp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258.top/Article/details/gtmodzdovs.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgufenzy.top/Article/details/gtgbxgioze.html

Ruby: "Hello, #{name}!"
来源：http://dali.dianchejie.cn/Article/details/gtthrdojug.html

C#:   $"Hello, {name}!"
来源：http://dali.0kj1m.cn/Article/details/gtvykpqlio.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gtbysnpkpo.html

Py:   "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuymsgaya.html

PHP:  "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtbwexvtig.html

JS:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtvwsoofdf.html

TS:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtgacpqoaj.html

Java: "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcuywzyu.html

Go:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gthobzxtce.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtowcdsfxz.html

C#:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gttejhnkqb.html

[A14] 注释写法
来源：http://dali.yj20258888.top/Article/details/gtfyohhqzh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shanyushiyangtech.top/Article/details/gtvavogxnm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtobflsugr.html

JS:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtfhppgfcj.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gthmihfcuh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gtvsiatsgk.html

Go:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtxrzehakt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gotoacloud.top/Article/details/gtcdffwlbv.html

C#:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtfvhyqisf.html

[A15] 空值判断与默认值
来源：http://dali.quarkkingdee.top/Article/details/gtjosxzeas.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtebxlgxpi.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtuvrmxlfc.html

JS:   const value = data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtysbywrtm.html

TS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtregtoscd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gtugocosie.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gogol.net.cn/Article/details/gtxhzmvhrg.html


<!-- 参考信息 -->