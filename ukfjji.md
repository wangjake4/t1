代发 wailian999

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtpnjkqmel.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtfummizxh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhixingplan.top/Article/details/gtnhzbzbvf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gtbdweazwz.html

[U99] JS：事件监听
来源：http://dali.nanxuanxn.top/Article/details/gtdyawwbps.html

el.addEventListener("click", e => {})
来源：http://dali.hammf.cn/Article/details/gtbgkfemsp.html

[U100] JS：DOM 查询
来源：http://dali.smart0.xyz/Article/details/gtflbtzlan.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gtvrmcmxjb.html

[U101] JS：classList 操作
来源：http://dali.gaohongyu789.top/Article/details/gtpfkukzcw.html

el.classList.toggle("active")
来源：http://dali.ybcxt.top/Article/details/gtpzcdgobl.html

[U102] JS：本地存储
来源：http://dali.tanke756.top/Article/details/gtlcmzbbnm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yvedp.cn/Article/details/gtlbftmwkr.html

[U103] JS：定时器
来源：http://dali.vqdsnc.cn/Article/details/gtlmyzihpa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtprkdlvhz.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtmurrdans.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtbdtvsnsv.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gtvnuucnzi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jlsjyb.cn/Article/details/gttfvgwggr.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gtmoajpuel.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtagujtgyj.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gthzlmayje.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtittonoch.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlesvzwx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cdnleiting.top/Article/details/gtwpffamsd.html

[U109] JS：数组分组
来源：http://dali.pycfn.com/Article/details/gtsqxnetip.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ydzc1.top/Article/details/gtzzouerrl.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgtsugtz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ydzc1.top/Article/details/gtdentenfk.html

[U111] JS：对象转 Map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawcnnwro.html

new Map(Object.entries(obj))
来源：http://dali.cashguo.top/Article/details/gtimisnnqw.html

[U112] JS：字符串补位
来源：http://dali.redwolf501.top/Article/details/gtblkcwnki.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gtqrhnuhtm.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gtkpaldskj.html

s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtjdxrnsvm.html

[U114] JS：JSON 深比较
来源：http://dali.hnqzz.top/Article/details/gtmfxdlukx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtrpoxaqqa.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gthdmoerxu.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtrbdsomla.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtfqyvlvkw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtxvlpwnbq.html

[U117] JS：单元测试
来源：http://dali.shuidangran.top/Article/details/gtfacuwmjh.html

npm i -D vitest;  npx vitest
来源：http://dali.gotoacloud.top/Article/details/gtwwpvdgqp.html

[U118] JS：开发服务器
来源：http://dali.sweek.top/Article/details/gtwodlajnz.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gtqhrtoald.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gthnllckhb.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtickvszxa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtmxiluyoh.html

import.meta.env.VITE_API_URL
来源：http://dali.gzhubu.top/Article/details/gtbxlrelwe.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkwylhuwr.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtfhiimjpn.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjrnvexnq.html

按语言统计（条）：
来源：http://dali.daria6918.cn/Article/details/gtaryueruo.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gthxdjpgfu.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gtqegxxjog.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtumdbnpgm.html

TypeScript ..... 212
来源：http://dali.xinyue.icu/Article/details/gtwuwtfgow.html

Java ........... 212
来源：http://dali.tanke756.top/Article/details/gtcxfweila.html

Go ............. 212
来源：http://dali.nanxinkj.top/Article/details/gtdshyfgmg.html

Ruby ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gthauhlryf.html

C# ............. 212
来源：http://dali.jianghu66.top/Article/details/gtajeitzpv.html

C .............. 30
来源：http://dali.shanyushiyangtech.top/Article/details/gtuplnplxv.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gtlenrsiqh.html

SQL ............ 90
来源：http://dali.wangshuangyany.cn/Article/details/gtvdsaswkp.html

Bash ........... 80
来源：http://dali.hywenlv.cn/Article/details/gtnrrmylpx.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gtktrpczqu.html

Swift .......... 15
来源：http://dali.yvedp.cn/Article/details/gtxjcwkmjf.html

Lua ............ 10
来源：http://dali.snrcjt.cn/Article/details/gtudhnlbpd.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gtqmfrctwr.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtbbumukis.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtvlwbvyzg.html

合计 ........... 2106 条
来源：http://dali.yuxming.cn/Article/details/gtdjiamuky.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gtudarjqdj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtwiwygign.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtukgxrbup.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtoxukptdq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtkhkhddvb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinghuilouyu.cn/Article/details/gtygcszdzv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtdnphimrf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlwqftwf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gtdcuczrdp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtmmhdbwmb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gthsnqoxce.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtbhyatvla.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtlzpoiovx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gttudjcohq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtbkxxakcc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinqigfzy.top/Article/details/gttfpoayjf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtkangxude.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gttnzjwfdr.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gtobcbrsiq.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtsvwidazb.html

T 其他语言补充                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtsfzigbvo.html

U 高频实用片段                         120
来源：http://dali.shangyingyoupin.top/Article/details/gtmvzqnnsl.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjoahdelj.html

合计                                  2106 条
来源：http://dali.aizwys.cn/Article/details/gtwktubhrk.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtiqzvetnz.html

使用提醒
来源：http://dali.smart0.xyz/Article/details/gtrjzqfzvv.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtvlkgmseq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sweek.top/Article/details/gtkymrlmzf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gtkzhmqkbp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sxryk.cn/Article/details/gtbvtdewpo.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.sweek.top/Article/details/gtwjzvjcpv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gtmkdxtcfy.html

—— 文件结束 ——
来源：http://dali.xylfe.cn/Article/details/gtbmynfwso.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gteprrndxg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtnuzeqoyn.html

Common Programming Examples Cheat Book
来源：http://dali.hywenlv.cn/Article/details/gthelyulqf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtktvzsjof.html

【收录内容】
来源：http://dali.vqdsnc.cn/Article/details/gtpocrzeik.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gtcklpbicx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.andypj.xyz/Article/details/gtlxxtoakg.html

SQL · Bash · C · C++
来源：http://dali.chenlongwang.top/Article/details/gtulzaygvp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuanzhike.top/Article/details/gtizqrduex.html

【使用说明】
来源：http://dali.zhongyouzk.top/Article/details/gtgsotarbp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhiwuduotai.top/Article/details/gtzryohgoc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gtrxqjthok.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.316326.xyz/Article/details/gtejcvzhlc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daxiang520.top/Article/details/gtnafjkrde.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jianghu66.top/Article/details/gtqryhomao.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hammf.cn/Article/details/gttmdxcnvb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gtyntitaxn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.guowangkeji.top/Article/details/gtovdulhsc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.dianchejie.cn/Article/details/gtmcynehvy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenjidiqi.icu/Article/details/gtpfecvpux.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fengsongda.top/Article/details/gtsfttxpim.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aizwys.cn/Article/details/gtecwupzha.html

【文件统计】
来源：http://dali.sweek.top/Article/details/gtovpiayxi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gtaxpsgssv.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtenmidjqx.html

目  录
来源：http://dali.birdmap.top/Article/details/gtquohuwbp.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtbejwigam.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xylfe.cn/Article/details/gtikekizba.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtgwiuxodj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtztinbjmh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtcxhmxxcc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gtarfompdj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gthfazlstz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gthqmvzfhj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtwxfrwmfa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtaextvnig.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtllqrsznx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtoueaannb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtfqslcstw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtgrfzsvul.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gtrajbqsre.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gtuvuznsfh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtwhsqwrpv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtvtnowges.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtbibyqfiv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yanxiufei.cn/Article/details/gtnvyeyoxm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtoqeepftj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtfdtuqavz.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmxtheofx.html

A. 基础语法与类型
来源：http://dali.jinqigufen.top/Article/details/gtgooomxui.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtmbkmvssr.html

[A01] Hello World
来源：http://dali.jinqigufen.top/Article/details/gttxbzmsvl.html

Py:   print("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gtbmgjzdcz.html

PHP:  echo "Hello, World!";
来源：http://dali.cheryme.top/Article/details/gtpcobveyz.html

JS:   console.log("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gtpzbuutbg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ehwqpu.com/Article/details/gtxujnvxuc.html

Java: System.out.println("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtwlvgqnsg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenlongwang.top/Article/details/gtlymibwri.html

Ruby: puts "Hello, World!"
来源：http://dali.ppjwa.cn/Article/details/gtkrwcamah.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtrkxihcqk.html

[A02] 变量声明与赋值
来源：http://dali.zhixingplan.top/Article/details/gtlacwcymx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnxiangtu.top/Article/details/gtznbkazan.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtmucnuahr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.daria6918.cn/Article/details/gtaashpqfc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sweek.top/Article/details/gtoeiohkmc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.daxiang520.top/Article/details/gtqsygqfwt.html

Go:   name := "Alex"; age := 20
来源：http://dali.ehwqpu.com/Article/details/gthnhkdfld.html

Ruby: name = "Alex"; age = 20
来源：http://dali.vqdsnc.cn/Article/details/gtyrhyolah.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.birdmap.top/Article/details/gtivxewtxv.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbguwjwuh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuetiantiany.cn/Article/details/gtcyvqhxwi.html

PHP:  const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gthjrcmrrh.html

JS:   const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtsnesznyu.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtxcptlmsd.html

Java: static final double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtkslskcsh.html

Go:   const PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gtqztlbgtc.html

Ruby: PI = 3.14159
来源：http://dali.yj202588.top/Article/details/gtrzksqylg.html

C#:   const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtjzijqfmk.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gtgxgutmsy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258888.top/Article/details/gthxzffksp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmjpuiil.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ivvv.top/Article/details/gtotjcdplr.html

TS:   typeof x; x instanceof Date
来源：http://dali.ybcxt.top/Article/details/gtpwzcpxig.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.iojbl.cn/Article/details/gtunwylwkd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.kuanghao11.cn/Article/details/gtndssqlca.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jlsjyb.cn/Article/details/gtfkfonelk.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gttfqxyifa.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtephnusbw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yueranfly.top/Article/details/gtlaxaclmw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtifuxwbbw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtmoshcjvd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnfzrkud.html

Java: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtkpbavphm.html

Go:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtbqryfjwh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtoengucjo.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtjkubbnik.html

[A06] 字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtqoriiwpg.html

Py:   int("42"); float("3.14")
来源：http://dali.ydzc1.top/Article/details/gtlmgthysu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.c1oappe.top/Article/details/gthwhgpthm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sweek.top/Article/details/gtxttpymtf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtfhahxtdw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtjpkdtnsi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhongyouzk.top/Article/details/gtotlxpchd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gtsrikkbvc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtxuauzbyb.html

[A07] 数字转字符串
来源：http://dali.gotoacloud.top/Article/details/gtosyexzxe.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtokpvkjdx.html

PHP:  (string) 42; strval(42)
来源：http://dali.nwbrower.top/Article/details/gteazvrvwz.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gttlmtwbpe.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtyrovuzeg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hammf.cn/Article/details/gtkggctrqd.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gtnadnupmq.html

Ruby: 42.to_s
来源：http://dali.gzhubu.top/Article/details/gtyqgqrlrj.html

C#:   42.ToString()
来源：http://dali.guannengcc.top/Article/details/gtlyodcrdo.html

[A08] 取整与四舍五入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkoyfhdz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtsfpqtzna.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sysykeji.top/Article/details/gtmelojrog.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtexxwyodd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.chenlongwang.top/Article/details/gtormhnoxg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtbtvsyffn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtramessli.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenjidiqi.icu/Article/details/gtmzuoaebj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtlnaldkvh.html

[A09] 绝对值与最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtfauxoqqe.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.andypj.xyz/Article/details/gtyffvhxbz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtfrfqhlya.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ivvv.top/Article/details/gtstyxcapa.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdgtvqjmw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtkwhwamnj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cucudq.cn/Article/details/gtcyxligry.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cucudq.cn/Article/details/gtsmpecxfh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtwsrgooob.html

[A10] 生成随机数
来源：http://dali.yangfankeji.com/Article/details/gttfwwufax.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tanke756.top/Article/details/gttubbzazi.html

PHP:  random_int(1, 100);
来源：http://dali.ppjwa.cn/Article/details/gtefcwpgpq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gtyakhukya.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gtjpbqcjnd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cqqwz.cn/Article/details/gtspradmfr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yonumen.top/Article/details/gthbqhticl.html

Ruby: rand(1..100)
来源：http://dali.tian-w.cn/Article/details/gtvwkpfonc.html

C#:   new Random().Next(1, 101)
来源：http://dali.0kj1m.cn/Article/details/gtrviknlfs.html

[A11] 条件表达式（三元）
来源：http://dali.pengpengdd.cyou/Article/details/gtrsxlmmly.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shzxlz.cn/Article/details/gtjhlvsdis.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtleefzsix.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtybqlafwu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtxlblmwrs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtschbnpzj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hysaishi.cn/Article/details/gtwtpyoqjz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtgjaqxfux.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtwaymhmlu.html

[A12] 字符串插值 / 格式化
来源：http://dali.ppjwa.cn/Article/details/gtfeloxhib.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonxkhsuj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.quarkkingdee.top/Article/details/gtkfrubiyv.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gtwczlfejm.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gtnepvzirm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cdnleiting.top/Article/details/gtggrtdpnm.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jlsjyb.cn/Article/details/gtvkwffljl.html

Ruby: "Hello, #{name}!"
来源：http://dali.tian-w.cn/Article/details/gtxjrorrjf.html

C#:   $"Hello, {name}!"
来源：http://dali.guowangkeji.top/Article/details/gtkdnlnbty.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tianlin.xyz/Article/details/gtforhimqy.html

Py:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtpfsqfhnr.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtmwxuwyio.html

JS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtwfexrgxt.html

TS:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gthcehzhub.html

Java: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtetlsfhli.html

Go:   "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gtuhbnwdyi.html

Ruby: "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtrpcoglil.html

C#:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtjbtvitin.html

[A14] 注释写法
来源：http://dali.vqdsnc.cn/Article/details/gtlxxforky.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.snrcjt.cn/Article/details/gtsyiaulnz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtwbxbnjcj.html

JS:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gtmhwrbajr.html

TS:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtneyfsgdp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.vqdsnc.cn/Article/details/gttxictqmi.html

Go:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtualqttcx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guowangkeji.top/Article/details/gthqnxqgbw.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtgupzpcli.html

[A15] 空值判断与默认值
来源：http://dali.guannengcc.top/Article/details/gtbtqlbdrc.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gtnfzqfnch.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gteobjkewq.html

JS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gtetdprmow.html

TS:   const value = data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtzhxnujlv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jqgfzy.top/Article/details/gtdcwspurj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.pengpengdd.cyou/Article/details/gtbjolrsoz.html

Ruby: value = data || "默认值"
来源：http://dali.0kj1m.cn/Article/details/gtsxklqszw.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtawouxuhg.html

[A16] 真假值判断规则
来源：http://dali.ppjwa.cn/Article/details/gtpeabekxy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhijiandao.cn/Article/details/gtxcgtjaxf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xziqi.cn/Article/details/gtooxujevq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtpxnbywzy.html

TS:   if (!x) {}
来源：http://dali.yangfankeji.com/Article/details/gtfkvviezo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtldsyaims.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuanzhike.top/Article/details/gtrfjudrbs.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jyoumei.cn/Article/details/gtihgmlldt.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxcsdqvyb.html

[A17] 位运算
来源：http://dali.gotoacloud.top/Article/details/gtsibcvsgl.html


<!-- 参考信息 -->