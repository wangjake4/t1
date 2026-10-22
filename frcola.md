代发 wailian999

[U97] JS：并发请求
来源：http://dali.tian-w.cn/Article/details/gtxpfdlsqx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.svipenyu.cn/Article/details/gtbqdnpwqv.html

[U98] JS：fetch 带 JSON
来源：http://dali.guowangkeji.top/Article/details/gtugsasgvy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.meibo888.top/Article/details/gtahcjeujz.html

[U99] JS：事件监听
来源：http://dali.xuetiantiany.cn/Article/details/gttofxbxpc.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtfiymopha.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gtucpihpfc.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gteqebznxg.html

[U101] JS：classList 操作
来源：http://dali.yueranfly.top/Article/details/gtqpacxxvz.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gteniiecki.html

[U102] JS：本地存储
来源：http://dali.aibaodan.cn/Article/details/gtpqpdzwkr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.fengsongda.top/Article/details/gtyadpjobh.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gtmqgjmgkh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sweek.top/Article/details/gtuezlqler.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gtznmfogpe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtzlvablvs.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gtzhspijxf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtntvsemja.html

[U106] JS：日期格式化
来源：http://dali.daria6918.cn/Article/details/gtwyzqobiw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gtwlxauqhx.html

[U107] JS：数字千分位
来源：http://dali.sysykeji.top/Article/details/gtefmndhkc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gttkjkfadx.html

[U108] JS：随机整数
来源：http://dali.gzhubu.top/Article/details/gtjiwqkjfc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gtdpdnvoie.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gtrreugqsi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtrdackwpm.html

[U110] JS：数组分块
来源：http://dali.xinyue.icu/Article/details/gtvrnmvnxv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtfmrkrvrb.html

[U111] JS：对象转 Map
来源：http://dali.vqdsnc.cn/Article/details/gtdemxfetx.html

new Map(Object.entries(obj))
来源：http://dali.hnxiangtu.top/Article/details/gtmtbknbfq.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gtgsgesage.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepanjfka.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gtgcehoquo.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gthvgkbdhv.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gtcxcqqmbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtzbjahdme.html

[U115] JS：生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gtuadgwlhy.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtpbehyrlh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gtqmhzzhnc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtquwlprqm.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtveduavds.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtoyamofsc.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtwuztxnkb.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gtzfvjopif.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gteupwtpro.html

npx vite build
来源：http://dali.hnqzz.top/Article/details/gtkckkpbky.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gtxtzjklaq.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtagktddpn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtqukkifzt.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtluhqarmq.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtimmnogkp.html

按语言统计（条）：
来源：http://dali.cheryme.top/Article/details/gtvbntmrum.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gtqotjucxs.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gtstaefasr.html

JavaScript ..... 252
来源：http://dali.kuanghao11.cn/Article/details/gtffbswjqp.html

TypeScript ..... 212
来源：http://dali.sweek.top/Article/details/gtkfjglycq.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtmfpcmawi.html

Go ............. 212
来源：http://dali.jianghu66.top/Article/details/gttcvyzhyv.html

Ruby ........... 212
来源：http://dali.jinqigfzy.top/Article/details/gtuoryclot.html

C# ............. 212
来源：http://dali.aizwys.cn/Article/details/gtedqrdqkc.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtjyiowtto.html

C++ ............ 30
来源：http://dali.iojbl.cn/Article/details/gtfbuutctb.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtbfaiupkq.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtsvzyapre.html

Kotlin ......... 15
来源：http://dali.hnqzz.top/Article/details/gtqxciinlh.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtlzfhtedm.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gtygyvamzd.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gttdtdlfkw.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtbwmjygif.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtuveuqvmf.html

合计 ........... 2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtrgrdewmw.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gtlrsksycl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtqmwpgyyt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtxilusmeo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtyzyghajl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtrbpbzojc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shuidangran.top/Article/details/gtxkfduyuv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gtuidhnjdc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258.top/Article/details/gtpqbhstmw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtvykcmhab.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtnkwkbcdx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtaquhtobx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gthzmqrmdt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtybduobvu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtcxkdmqno.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gtubsyblhs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gteovjsjzs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtegjnxhoo.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqlkcive.html

R Bash 专题                             80
来源：http://dali.xziqi.cn/Article/details/gtqebdjhdx.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtbrrlihjx.html

T 其他语言补充                          60
来源：http://dali.yj20258888.top/Article/details/gtaphohsxm.html

U 高频实用片段                         120
来源：http://dali.pengpengdd.cyou/Article/details/gthjhfkdjm.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtepdmmsyb.html

合计                                  2106 条
来源：http://dali.andypj.xyz/Article/details/gtjomfieal.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtmyphlxam.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtnhgexjrt.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtltuhyhcm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xylfe.cn/Article/details/gtkqyrqhqm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yuanzhike.top/Article/details/gtxvqayzpn.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sxryk.cn/Article/details/gtzqptxxwj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.c1oappe.top/Article/details/gtcozynftt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yvedp.cn/Article/details/gtveuydwtp.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gtmqpxsqmb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsjfjslwo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.havefunace.top/Article/details/gtstfjemhw.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtoempbrok.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtywziyamt.html

【收录内容】
来源：http://dali.chenlongwang.top/Article/details/gtrmvywwvo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.birdmap.top/Article/details/gtfvnskcgt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangshuangyany.cn/Article/details/gtixacyjgk.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gtelicgzyu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cucudq.cn/Article/details/gtxqnsxsgr.html

【使用说明】
来源：http://dali.zycfv.cn/Article/details/gttzftspoz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258.top/Article/details/gthskxdruh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sysykeji.top/Article/details/gtykzihmet.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yuxming.cn/Article/details/gtieufhtsy.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gttmdqprcx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jlsjyb.cn/Article/details/gthseyporc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gttjmoeyxz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.shangyingyoupin.top/Article/details/gtyxgrupav.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtmqexydgb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gtbfzkeulh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhengqikj.top/Article/details/gtlhrknckd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.haohaochexian.top/Article/details/gtuxbutlqo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.mhx1999.top/Article/details/gtwcxwigcg.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gtxiqflrpf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gthqxxgosq.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtygxvcwle.html

目  录
来源：http://dali.daria6918.cn/Article/details/gtryoftzih.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtaycuigbc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shuidangran.top/Article/details/gtortbduuo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gtlyvuqdpn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtovbyervw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtooiqhwmi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dashuyun.cn/Article/details/gtcqnksafu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.chenlongwang.top/Article/details/gtrkcjzbtk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xziqi.cn/Article/details/gtkdpikqjh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtxvtjjchw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtzauzmjhz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtckfqmqrs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gthuissjvy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtfwtrtewe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtxzdpizmn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclnxkojh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gtazhfjeyk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtpptfnmhp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jyoumei.cn/Article/details/gtrbyetpwq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.mhx1999.top/Article/details/gtnqfuaxsv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gtegzygvnu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtydlerccg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtycsdvcau.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttytuwogz.html

A. 基础语法与类型
来源：http://dali.xuetiantiany.cn/Article/details/gtojygcmeg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtazyxalma.html

[A01] Hello World
来源：http://dali.svipenyu.cn/Article/details/gtmdigxbpq.html

Py:   print("Hello, World!")
来源：http://dali.316326.xyz/Article/details/gtvjempsbj.html

PHP:  echo "Hello, World!";
来源：http://dali.jinqigufen.top/Article/details/gtncupbuxe.html

JS:   console.log("Hello, World!");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmpnynwvk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.dianchejie.cn/Article/details/gtbnksznay.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtntvwkgrv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gtrkcnsdfu.html

Ruby: puts "Hello, World!"
来源：http://dali.guannengcc.top/Article/details/gtusfrmepx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtzfxwqsgh.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gtbgklueas.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtstpvzkas.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtnvxxmuet.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtfhpqylbd.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tanke756.top/Article/details/gtsjnqvmxu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gtcgobnjhe.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gtxzpfmtkb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.kuanghao11.cn/Article/details/gtashttykg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtlnddpbuk.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gtzavylued.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtzeydjlen.html

PHP:  const PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtkhosxwts.html

JS:   const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtezicnpbq.html

TS:   const PI: number = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtnauwnltk.html

Java: static final double PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtewwvjdga.html

Go:   const PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtmyivlavi.html

Ruby: PI = 3.14159
来源：http://dali.hysaishi.cn/Article/details/gtjpafoqed.html

C#:   const double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtnotxfjpe.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gtjeulllda.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gtqpckawem.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ppjwa.cn/Article/details/gtmxoxeyof.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gteiirdxmm.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiudfiom.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxrseeppq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.daxiang520.top/Article/details/gtnnemrzhf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.wangdashe.top/Article/details/gtwflmkvho.html

C#:   x.GetType().Name; x is int
来源：http://dali.zycfv.cn/Article/details/gttfppjpwq.html

[A05] 整数除法与取模
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgsucembt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gtyftntoxb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtcstuyvdb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtdhekaqzf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtrqpyjmwc.html

Java: 7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtnbmpjjlk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtyegdogau.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtegofplfn.html

C#:   7 / 2; 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtqypnjujw.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtbxsoelsa.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtvawjhjkp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.kuanghao11.cn/Article/details/gtniovdgbu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttygyydga.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hnxiangtu.top/Article/details/gtstevigsg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtiobsrhqe.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gtnutrwxzn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gtcwdmhemn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinqigufen.top/Article/details/gtjewlwszv.html

[A07] 数字转字符串
来源：http://dali.xylfe.cn/Article/details/gtnhhsmbcj.html

Py:   str(42)
来源：http://dali.yonumen.top/Article/details/gtuowiiihx.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhengqikj.top/Article/details/gtgdjebyzf.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gtfiybmstr.html

TS:   String(42)
来源：http://dali.meibo888.top/Article/details/gtvtithddy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.smart0.xyz/Article/details/gtwozcvoza.html

Go:   strconv.Itoa(42)
来源：http://dali.yongpay.top/Article/details/gtumbfkdwf.html

Ruby: 42.to_s
来源：http://dali.ivvv.top/Article/details/gtrnzhngje.html

C#:   42.ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtxbpgodxl.html

[A08] 取整与四舍五入
来源：http://dali.zycfv.cn/Article/details/gtamodhrcj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtfcxsbroh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gtzdihadqo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtknggowow.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gtwphfkrzh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ehwqpu.com/Article/details/gtjwpokysk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtacbrpqlo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xziqi.cn/Article/details/gtfnwdrqgi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gthymzhmir.html

[A09] 绝对值与最大最小值
来源：http://dali.jianghu66.top/Article/details/gtducsxlwb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtsogpcyki.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtetyheumr.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcoqxhak.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtocrwpwse.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtzghrhnbv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhongyouzk.top/Article/details/gtmuslzsjn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.vqdsnc.cn/Article/details/gtdxptvnkr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtrxwmnwlp.html

[A10] 生成随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtcgojuxmf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxuanxn.top/Article/details/gtjjjgaxyf.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gtlrpzffdr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvxatshn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtqgmzbkrt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gthcfzfzdn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hammf.cn/Article/details/gtlncqjura.html

Ruby: rand(1..100)
来源：http://dali.jinghuilouyu.cn/Article/details/gtetspowoq.html

C#:   new Random().Next(1, 101)
来源：http://dali.cucudq.cn/Article/details/gtxensfhpo.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gtirfqlext.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuwkclmep.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtljmrrwmk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtvowfywjk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtjtvmausd.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtgwutvjme.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jiagoushi.top/Article/details/gtbpfyknfb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtvzpiixba.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoebufryx.html

[A12] 字符串插值 / 格式化
来源：http://dali.xylfe.cn/Article/details/gtqjcjbymf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xuetiantiany.cn/Article/details/gtafhajmru.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.pengpengdd.cyou/Article/details/gtqjtciwrz.html

JS:   `Hello, ${name}!`
来源：http://dali.c1oappe.top/Article/details/gtuudwpaza.html

TS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gtityaszzp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangdashe.top/Article/details/gtqefuugwr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvcivhrg.html

Ruby: "Hello, #{name}!"
来源：http://dali.bjfxy.top/Article/details/gtjuzefrzs.html

C#:   $"Hello, {name}!"
来源：http://dali.cqqwz.cn/Article/details/gttunkvenh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.havefunace.top/Article/details/gtecgqcmmr.html

Py:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtwicjmayp.html

PHP:  "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtyzzecwbm.html

JS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtbefhkrkx.html

TS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtqzjmathq.html

Java: "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtcdxxuhro.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtexiuyftc.html

Ruby: "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtlemolvip.html

C#:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtilljbrbe.html

[A14] 注释写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcowtzswk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gogol.net.cn/Article/details/gtwacssial.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtethelyfv.html

JS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtusbsxsta.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gtfkehbptr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hammf.cn/Article/details/gtvjgkgwba.html

Go:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gtladpsovu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nanxuanxn.top/Article/details/gtxdkoklke.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvlzdcvy.html

[A15] 空值判断与默认值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfptzmhpq.html

Py:   value = data or "默认值"
来源：http://dali.0kj1m.cn/Article/details/gtenthatvb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowukooue.html

JS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtpyopgvov.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtohlsvvkl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.tian-w.cn/Article/details/gtgdnlcujb.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxuanxn.top/Article/details/gtnzbkwpkk.html

Ruby: value = data || "默认值"
来源：http://dali.tian-w.cn/Article/details/gtdriuzktt.html

C#:   var value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtebtdpwii.html

[A16] 真假值判断规则
来源：http://dali.tianlin.xyz/Article/details/gtpbojgjkx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gteopqttri.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgufenzy.top/Article/details/gtfnkenlck.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aibaodan.cn/Article/details/gtdvroyehj.html

TS:   if (!x) {}
来源：http://dali.svipenyu.cn/Article/details/gtvphxfksu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuanzx.com/Article/details/gtqondptiy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tianlin.xyz/Article/details/gtqjedsirf.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.svipenyu.cn/Article/details/gtwooexoby.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gtmvwmoalw.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gtexfprlgz.html


<!-- 参考信息 -->