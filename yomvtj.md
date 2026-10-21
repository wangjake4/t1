代发 wailian999

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gtbmsbeiud.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtsnpvevvv.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gtwselmvrp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gthgiweluw.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gtbtedlone.html

el.addEventListener("click", e => {})
来源：http://dali.dashuyun.cn/Article/details/gtdoxmntxo.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gtdsaxzfgh.html

document.querySelector(".item")
来源：http://dali.pycfn.com/Article/details/gtfotsiejr.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtlgbspvtp.html

el.classList.toggle("active")
来源：http://dali.dashuyun.cn/Article/details/gtdyugarso.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtpgrnpixc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtnnfkuysj.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gtwjhmbdpu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdynhaxzv.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gtwdvwbntt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtslqiqgbi.html

[U105] JS：节流
来源：http://dali.zycfv.cn/Article/details/gtvbxxtyeq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtkwnusvxl.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkzmcosg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gtbrwcusdj.html

[U107] JS：数字千分位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnlwnaha.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtburvyhbi.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gtcofxnttj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gtzppqfykc.html

[U109] JS：数组分组
来源：http://dali.yanxiufei.cn/Article/details/gtdyzzenex.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtxnetafnr.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtuojawten.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.wangshuangyany.cn/Article/details/gtwfboejpr.html

[U111] JS：对象转 Map
来源：http://dali.svipenyu.cn/Article/details/gttqwkvlfr.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gtzkusemjg.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gtmjmnicde.html

"7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtvljuqcij.html

[U113] JS：正则替换全部
来源：http://dali.aizwys.cn/Article/details/gtcrsdazoo.html

s.replaceAll("a", "b")
来源：http://dali.nwbrower.top/Article/details/gtdemxppmf.html

[U114] JS：JSON 深比较
来源：http://dali.sxryk.cn/Article/details/gtokhrmdvy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtyzjhmwri.html

[U115] JS：生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtpyvoqmlr.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtiytgnzsx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtyashcoya.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gtxcxjmxrx.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtoafiojda.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gtnalykxkf.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtwecvtyxq.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gtefmyeeur.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gtxrlcbyrh.html

npx vite build
来源：http://dali.cashguo.top/Article/details/gtzmbllpgh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyihifgec.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtuzoyignb.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gttrxuoicm.html

统计汇总
来源：http://dali.daria6918.cn/Article/details/gtskhqjzeo.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtxmslsxoc.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gtgdwuhzty.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtwrfrpppm.html

PHP ............ 252
来源：http://dali.jinqigufen.top/Article/details/gtvbyrkjlo.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gtusxlplxb.html

TypeScript ..... 212
来源：http://dali.svipenyu.cn/Article/details/gtwwbtfrvf.html

Java ........... 212
来源：http://dali.fengsongda.top/Article/details/gtmcijedvq.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtfozbhrlu.html

Ruby ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnezyvvn.html

C# ............. 212
来源：http://dali.yangfankeji.com/Article/details/gttiumqtrh.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtwiqyxndl.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gtrbpvltme.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtbjkqaxlh.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gthlppgbfc.html

Kotlin ......... 15
来源：http://dali.fengsongda.top/Article/details/gtpnfywsbl.html

Swift .......... 15
来源：http://dali.guannengcc.top/Article/details/gtyrznqntz.html

Lua ............ 10
来源：http://dali.xuetiantiany.cn/Article/details/gtksjytykz.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtaafexjun.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtnmysfcom.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtijqxmmsp.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gtwlwzsach.html

按章节统计：
来源：http://dali.dianchejie.cn/Article/details/gtfmttdplw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtzraofgry.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtgeqrzhob.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtnhpnxlvy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzncztovi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shanyushiyangtech.top/Article/details/gtutmpcleq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtwxbwnvhk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtrjrnjizp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtzbcigrov.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuievkdub.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gtvtpenlbp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtujrfqqzg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gttjrnhkff.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtestcqlow.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gtvlakmoin.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.andypj.xyz/Article/details/gtnbmqavfb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtbtjdjxed.html

Q SQL 专题                              90
来源：http://dali.iojbl.cn/Article/details/gtksmjujib.html

R Bash 专题                             80
来源：http://dali.guannengcc.top/Article/details/gttmuqpqkq.html

S C / C++ 专题                          60
来源：http://dali.yongpay.top/Article/details/gtalrazijm.html

T 其他语言补充                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqhzmnoz.html

U 高频实用片段                         120
来源：http://dali.shuidangran.top/Article/details/gtfksjwxih.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtdquzwpps.html

合计                                  2106 条
来源：http://dali.pycfn.com/Article/details/gtpxhfcbqr.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gthtubdohs.html

使用提醒
来源：http://dali.gzhubu.top/Article/details/gtziamkdlk.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gttgxnrgzx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gtcnlnjejj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtyhnsbuwe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hysaishi.cn/Article/details/gtqdqghmom.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenzaomai.com/Article/details/gtwzzembgy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtplxsrrtq.html

—— 文件结束 ——
来源：http://dali.cdnleiting.top/Article/details/gtfxubhzco.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtwbofhsos.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.snrcjt.cn/Article/details/gtrmksytrq.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gtvynnyrze.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdifkzumv.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gtajcydtwu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gzhubu.top/Article/details/gtuzgoncan.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yangfankeji.com/Article/details/gtthbsldog.html

SQL · Bash · C · C++
来源：http://dali.xuanzx.com/Article/details/gtdvsymbwp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jianghu66.top/Article/details/gtaqycvbvm.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gttjqjozei.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gtwlpjbdgq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sxryk.cn/Article/details/gtfrqhldua.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.vqdsnc.cn/Article/details/gtvyealaec.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gtvjwujwtg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gtultsejxf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gtywcvbseb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztvgoxfg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.chenlongwang.top/Article/details/gtkeaapfmn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinghuilouyu.cn/Article/details/gtriljgket.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gtyaterdig.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.daxiang520.top/Article/details/gtvyunrzov.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinqigufen.top/Article/details/gtzhbeiuhu.html

【文件统计】
来源：http://dali.guannengcc.top/Article/details/gtesjiaujm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gthpyluhfr.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtxklxaovt.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gtljoippbn.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtlhltpfzl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtawzmiflk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.mhx1999.top/Article/details/gtqzowchby.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gttfximehh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakxepbpx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gogol.net.cn/Article/details/gtoqqerroa.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gthmbcjyxc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtrgnwimhc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gtbyparsjb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gthkxwttcr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gtguiaxhqn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gttsprszxn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtqhcjcmnq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gthfuzutaw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtomsvvebs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtgatxooag.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtzzhtlgft.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtmrnjntbr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cucudq.cn/Article/details/gtnoziqdjn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nanxuanxn.top/Article/details/gtahgxjlfu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtfprulsql.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtoagwvhid.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtahriucye.html

A. 基础语法与类型
来源：http://dali.316326.xyz/Article/details/gtykiokkwq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxixhlarw.html

[A01] Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtpkplpaix.html

Py:   print("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gtxfwtewfv.html

PHP:  echo "Hello, World!";
来源：http://dali.havefunace.top/Article/details/gtldjslmlb.html

JS:   console.log("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtlowaewnm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gtmvywfbdp.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gttufqynhb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtegfjelga.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gtexxatsai.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtkfujtdvz.html

[A02] 变量声明与赋值
来源：http://dali.ivvv.top/Article/details/gtuesfuabj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gtxsctjcud.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hammf.cn/Article/details/gtvyjourpn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtkfvbgc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gtuqydzsvp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuevhnblk.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtaqcafoxh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gthwetyhdj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tian-w.cn/Article/details/gtsmgfkqkk.html

[A03] 常量定义
来源：http://dali.hysaishi.cn/Article/details/gtjrgqbhve.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tian-w.cn/Article/details/gtmbjvalea.html

PHP:  const PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtusptnhys.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gthtudxxkw.html

TS:   const PI: number = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtutgaclsn.html

Java: static final double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtwuosjdom.html

Go:   const PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtkekpwgmd.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtidggnuys.html

C#:   const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtdapukshn.html

[A04] 判断变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtksxefkiy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtcmqpxjug.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.havefunace.top/Article/details/gtdashoxih.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtzsechktr.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtjszdkili.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gtprbzhjfb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.smart0.xyz/Article/details/gtthakupkf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sweek.top/Article/details/gtifnxkmbb.html

C#:   x.GetType().Name; x is int
来源：http://dali.ivvv.top/Article/details/gtgevwubcw.html

[A05] 整数除法与取模
来源：http://dali.hnxiangtu.top/Article/details/gtokpcxsqz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gtikhteaxf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxmtduar.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtnmtakimh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtayqvevjm.html

Java: 7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gtncrjpxvk.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtpuujbfza.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtrjfwbpzx.html

C#:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzhhfnrnq.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtakhttvtf.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtainmqepr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gtdtefqoxc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtvnzbcrtt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gttodrlvpf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gtdvgktnnq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zycfv.cn/Article/details/gtqpbcthdo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.iojbl.cn/Article/details/gtoywfyoey.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gttetpunok.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gtgxardjay.html

Py:   str(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtwgtjhuhh.html

PHP:  (string) 42; strval(42)
来源：http://dali.jyoumei.cn/Article/details/gtncikppxd.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gtktllphah.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtqnslsfzp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ehwqpu.com/Article/details/gtxzhrhddh.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuaehvcx.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gtxzmghyqd.html

C#:   42.ToString()
来源：http://dali.dashuyun.cn/Article/details/gteqmklvqp.html

[A08] 取整与四舍五入
来源：http://dali.ivvv.top/Article/details/gteugulkek.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtcbglnaio.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pengpengdd.cyou/Article/details/gtzkwuyzhx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtdxcysfqw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ydzc1.top/Article/details/gtielgjxvi.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtoilazqhm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtipavkptj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.meibo888.top/Article/details/gthacgybrb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtrwjiordu.html

[A09] 绝对值与最大最小值
来源：http://dali.zhixingplan.top/Article/details/gtztwbmcta.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtkwykbrkg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtjvateqds.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtefmnptln.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtjabyiadu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtmzmvgzkz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxuanxn.top/Article/details/gtsqvcyxki.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.daxiang520.top/Article/details/gtmnhfodoc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtkpllbcpu.html

[A10] 生成随机数
来源：http://dali.xuanzx.com/Article/details/gtnzsvuvkg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gtfulceoct.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gtvornvimn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gtlavnzqri.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gtpuyydqir.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sweek.top/Article/details/gtyxyzdwzq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.mhx1999.top/Article/details/gtzrhmycmh.html

Ruby: rand(1..100)
来源：http://dali.aizwys.cn/Article/details/gtmywhzikv.html

C#:   new Random().Next(1, 101)
来源：http://dali.daxiang520.top/Article/details/gtgdgjdyck.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gthmjbhdww.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gotoacloud.top/Article/details/gtnzjxnzzc.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtamaljncy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gttuptfcji.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtbizkvsxu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtqdimqjao.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pycfn.com/Article/details/gtyzwzjxtw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtbahaqoqd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtxbceufmz.html

[A12] 字符串插值 / 格式化
来源：http://dali.smart0.xyz/Article/details/gtjowhxekd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxuanxn.top/Article/details/gthlgwytck.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gtefdwwwbq.html

JS:   `Hello, ${name}!`
来源：http://dali.ydzc1.top/Article/details/gtwedomlry.html

TS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtvmxadeyk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aizwys.cn/Article/details/gtkvdijlcb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhixingplan.top/Article/details/gtmeljycrb.html

Ruby: "Hello, #{name}!"
来源：http://dali.yanxiufei.cn/Article/details/gtgqcspfcn.html

C#:   $"Hello, {name}!"
来源：http://dali.cheryme.top/Article/details/gtfhekddzz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtqygalz.html

Py:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtkxfjniee.html

PHP:  "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtmdixnpgw.html

JS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtsyjqdkgf.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtavlsijcp.html

Java: "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtmjtsdwzd.html

Go:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtppgxzufc.html

Ruby: "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gthoyhyazi.html

C#:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtnxbtjwee.html

[A14] 注释写法
来源：http://dali.yuxming.cn/Article/details/gtabdydusa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cdnleiting.top/Article/details/gtmguapgpb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gtgkuxfdvp.html

JS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtpfczntdv.html

TS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtrlziswnc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xziqi.cn/Article/details/gtxuyfubgm.html

Go:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtqscdsgxm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.mhx1999.top/Article/details/gtigwnhntw.html

C#:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtsqpwuhyi.html

[A15] 空值判断与默认值
来源：http://dali.cashguo.top/Article/details/gtefqgzevd.html

Py:   value = data or "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gtkgrygghq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtdwuyaptd.html

JS:   const value = data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gtvrzvoest.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtkmmhtjva.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tian-w.cn/Article/details/gtiplqmhkl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.chenzaomai.com/Article/details/gtzmimljul.html

Ruby: value = data || "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtntwdjxbs.html

C#:   var value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtjhuqwyxn.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gtrxjsfdrj.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxinkj.top/Article/details/gtfiesvjqs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sysykeji.top/Article/details/gtxnxytyvi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigufen.top/Article/details/gtfonwedhd.html

TS:   if (!x) {}
来源：http://dali.gogol.net.cn/Article/details/gtgkrtsvqj.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtiylrzjyo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.meibo888.top/Article/details/gtfozvtooz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gteyxxitus.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtzpuuolge.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gtkfstfvaa.html


<!-- 参考信息 -->