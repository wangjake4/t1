代发 wailian999

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gtquqyceac.html

el.classList.toggle("active")
来源：http://dali.xylfe.cn/Article/details/gtzqbgpjai.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gtezomwvtz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtbmvbbzmt.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gteuagbwdl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gtgmfmrhdo.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gthffzgxbe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gthwiuuzog.html

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gttfigchdm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbfudjhj.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gttzaydrtg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gtvkmyhzqb.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtptyxezbo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gttcixhoev.html

[U108] JS：随机整数
来源：http://dali.aibaodan.cn/Article/details/gtmagnptdp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guannengcc.top/Article/details/gtqnznxzre.html

[U109] JS：数组分组
来源：http://dali.zhengqikj.top/Article/details/gtxrxrifwe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtjtczvosr.html

[U110] JS：数组分块
来源：http://dali.cheryme.top/Article/details/gtqjdxxuxq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtroluszzl.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gthuollmpo.html

new Map(Object.entries(obj))
来源：http://dali.zhengqikj.top/Article/details/gtkefsoavz.html

[U112] JS：字符串补位
来源：http://dali.hammf.cn/Article/details/gtuvczodfb.html

"7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtmovcntwy.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangtech.top/Article/details/gteagpdcmd.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtjgkzyplq.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtqjeqhvub.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.mhx1999.top/Article/details/gtpicnblmo.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtmktivtir.html

crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtdmxaprpk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.andypj.xyz/Article/details/gthqztckmm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shuidangran.top/Article/details/gtusfvwqac.html

[U117] JS：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtsdbmbyuz.html

npm i -D vitest;  npx vitest
来源：http://dali.ivvv.top/Article/details/gtbwowkrdq.html

[U118] JS：开发服务器
来源：http://dali.guannengcc.top/Article/details/gtouxvionl.html

npm i -D vite;  npx vite
来源：http://dali.mhx1999.top/Article/details/gtxgrljdpv.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gtznkqzpjl.html

npx vite build
来源：http://dali.gotoacloud.top/Article/details/gtxdqhmfxy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ehwqpu.com/Article/details/gthkwbfjvw.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtmmnclgkv.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtohyjxmsx.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gtlnemsdnc.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtxxnsvcar.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtpwhjsbug.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtpnonqkyf.html

PHP ............ 252
来源：http://dali.zdqjudy.top/Article/details/gttxusunfh.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gtfjnvvheo.html

TypeScript ..... 212
来源：http://dali.hfpthk.cn/Article/details/gtmfnlygck.html

Java ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtppmxjfas.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtabjqyutg.html

Ruby ........... 212
来源：http://dali.aizwys.cn/Article/details/gtvcsongwj.html

C# ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtmdacdqcn.html

C .............. 30
来源：http://dali.zhiwuduotai.top/Article/details/gtastpussd.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtffujvjiq.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtdqoctqaq.html

Bash ........... 80
来源：http://dali.guowangkeji.top/Article/details/gtnypilhye.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtbzjhgnyf.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtyvjbchne.html

Lua ............ 10
来源：http://dali.cdnleiting.top/Article/details/gtjqzyoxkt.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gttyrtavna.html

Scala .......... 10
来源：http://dali.gotoacloud.top/Article/details/gttuouutnm.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtgwctemga.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtmioqljca.html

按章节统计：
来源：http://dali.gogol.net.cn/Article/details/gtfddfhfln.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtuidaepii.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtqcwxygtc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtrzfwgvsl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtlkjgpewe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hammf.cn/Article/details/gtfgfsjlez.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtolqpsgbi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtoxfmbqdo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gthfkpmmko.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrraijohp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gtndggzcul.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtiabbsiqk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtiyeqtaxd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtouvndmvn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gthovdaezt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gtksxxaqat.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtudtabikd.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gtrgrmxtao.html

R Bash 专题                             80
来源：http://dali.sysykeji.top/Article/details/gtlsyfyyuj.html

S C / C++ 专题                          60
来源：http://dali.wangshuangyany.cn/Article/details/gtdkcgtcrm.html

T 其他语言补充                          60
来源：http://dali.yueranfly.top/Article/details/gtdwpaqyfr.html

U 高频实用片段                         120
来源：http://dali.zycfv.cn/Article/details/gtiiwwzbwh.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtxtsudwsy.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gtatstrzge.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtcsrnucyb.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gtqjrsvlxd.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtgdjlvdqe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtxsifhgoj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cdnleiting.top/Article/details/gtbmtlpuki.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jlsjyb.cn/Article/details/gtmxkhjoyv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hywenlv.cn/Article/details/gtauwtlqsp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.haohaochexian.top/Article/details/gtbngeaphk.html

—— 文件结束 ——
来源：http://dali.svipenyu.cn/Article/details/gtqkyfcwan.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtjsuaozrp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hammf.cn/Article/details/gtzyttfvln.html

Common Programming Examples Cheat Book
来源：http://dali.c1oappe.top/Article/details/gtzdpahwzo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgnodqxye.html

【收录内容】
来源：http://dali.yj20258.top/Article/details/gtrckijxvu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gtnfhjlvyr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtjevpojqj.html

SQL · Bash · C · C++
来源：http://dali.yuanzhike.top/Article/details/gtezlimsfm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gtstmdoyqq.html

【使用说明】
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbadujek.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gthcqauwjh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhixingplan.top/Article/details/gtvzdmczle.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhongyouzk.top/Article/details/gtyunqjvjv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmabfoat.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.tianlin.xyz/Article/details/gtrlafvnjz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nwbrower.top/Article/details/gtytwbqazd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenjidiqi.icu/Article/details/gtuwsvwpis.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtdasbcpka.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtuuoomfif.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gtuhfzzcsa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jlsjyb.cn/Article/details/gtuhdqkjch.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.guannengcc.top/Article/details/gtmwstrwwy.html

【文件统计】
来源：http://dali.chenzaomai.com/Article/details/gtimoxzsgc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.havefunace.top/Article/details/gtxgntmoqi.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtvkoomcob.html

目  录
来源：http://dali.daxiang520.top/Article/details/gtvcfsjueb.html

--------------------------------------------------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmpkcwqq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrdbdath.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyunmwvbn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtghenpqwj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtljnsxbsh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxinkj.top/Article/details/gtqycgjgih.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtnritrfjl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cdnleiting.top/Article/details/gtvlvycafa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtggrjdjue.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gtlcwcezfl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gtivgdlsls.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gttrclxtyr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtxrdfemml.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtlwwhafcb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ybcxt.top/Article/details/gtbqbopflo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtfwgrnwcr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtjuiqxiud.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gtozzdghou.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.redwolf501.top/Article/details/gtviqsezco.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigufen.top/Article/details/gtymzrplmh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtknbiyzzr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtclhjcutg.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsmcvgzdo.html

A. 基础语法与类型
来源：http://dali.316326.xyz/Article/details/gtoepqdowq.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtomiyvcog.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gtmqloddph.html

Py:   print("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtxaatqoaw.html

PHP:  echo "Hello, World!";
来源：http://dali.9152youxi.cn/Article/details/gtpzakrlsx.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gtrsphsacv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hfpthk.cn/Article/details/gtfqufsifm.html

Java: System.out.println("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtahcrocxh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsstpdmz.html

Ruby: puts "Hello, World!"
来源：http://dali.tianlin.xyz/Article/details/gtuohbbyjm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtaxbawnho.html

[A02] 变量声明与赋值
来源：http://dali.jinqigufen.top/Article/details/gtemcfdcbc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtssnajsyr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtautxcmrw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtrvurxljz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtffwdniec.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtisxqnvae.html

Go:   name := "Alex"; age := 20
来源：http://dali.shangyingyoupin.top/Article/details/gtmsyxtuve.html

Ruby: name = "Alex"; age = 20
来源：http://dali.mhx1999.top/Article/details/gtgfolfoef.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gttjouappa.html

[A03] 常量定义
来源：http://dali.ivvv.top/Article/details/gtdqkykafb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.meibo888.top/Article/details/gtpuavmvvm.html

PHP:  const PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtynfuzrax.html

JS:   const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtdhzuinzf.html

TS:   const PI: number = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtwyriulfs.html

Java: static final double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtzgzkdzct.html

Go:   const PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtksxszgfa.html

Ruby: PI = 3.14159
来源：http://dali.ppjwa.cn/Article/details/gtyjgcbxyr.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtbgsjfmwb.html

[A04] 判断变量类型
来源：http://dali.wangshuangyany.cn/Article/details/gtzgucgpgx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gtsuinpdyj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtsiorfyuq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtzpbgpmmd.html

TS:   typeof x; x instanceof Date
来源：http://dali.jinqigfzy.top/Article/details/gtntkawbqj.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xziqi.cn/Article/details/gtsylaqqqb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aibaodan.cn/Article/details/gtrwjudgtk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shuidangran.top/Article/details/gtgifwemeo.html

C#:   x.GetType().Name; x is int
来源：http://dali.fzhhl.top/Article/details/gtieisvseq.html

[A05] 整数除法与取模
来源：http://dali.yj20258.top/Article/details/gtbwhjsrmw.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenlongwang.top/Article/details/gtdgdafgjm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtloyfcmay.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtdfehrznx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtbgfjrrra.html

Java: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtjahxoqmk.html

Go:   7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gtposhxydh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sysykeji.top/Article/details/gtjqrzueoz.html

C#:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafnhwdip.html

[A06] 字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtlqryebwr.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugxhscok.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dashuyun.cn/Article/details/gtxrxvfsaq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guowangkeji.top/Article/details/gtueyxaelq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gtipvqauqh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtzhxdbsvk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.daxiang520.top/Article/details/gtahkkwsze.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbyahpee.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258.top/Article/details/gtcxnbvhtg.html

[A07] 数字转字符串
来源：http://dali.yj20258888.top/Article/details/gtvneapopy.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gtejlfwllr.html

PHP:  (string) 42; strval(42)
来源：http://dali.gzhubu.top/Article/details/gtdpkyulrc.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtoreigldm.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gtvpszoxuf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gaohongyu789.top/Article/details/gtkrshzrpi.html

Go:   strconv.Itoa(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfukjvsun.html

Ruby: 42.to_s
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfrvacaa.html

C#:   42.ToString()
来源：http://dali.jiagoushi.top/Article/details/gttuodavdq.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gtqbmolrha.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtkfjzivav.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tian-w.cn/Article/details/gtybombzna.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtsccxpxtq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258.top/Article/details/gtkzyomnbz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtnwhhlcxj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtcevwukhr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jyoumei.cn/Article/details/gttphtctpp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtfmcpzywb.html

[A09] 绝对值与最大最小值
来源：http://dali.yvedp.cn/Article/details/gtnopznzlh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtmaujilkn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtnkrhsgkx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtwvvjgylz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gtwfthxxbw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtnicoxawi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yvedp.cn/Article/details/gtdollnjph.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yonumen.top/Article/details/gtzkjmroba.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gthboialov.html

[A10] 生成随机数
来源：http://dali.hnxiangtu.top/Article/details/gtsyggnwtx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.meibo888.top/Article/details/gtgdszwnnn.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gttmwitzep.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gtmyxsodjd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xuanzx.com/Article/details/gtoimwjmtp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtsybkhepc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gthbwukaah.html

Ruby: rand(1..100)
来源：http://dali.meibo888.top/Article/details/gtbiybuvjv.html

C#:   new Random().Next(1, 101)
来源：http://dali.daria6918.cn/Article/details/gtnpuaygfa.html

[A11] 条件表达式（三元）
来源：http://dali.hnqzz.top/Article/details/gtvxwdrano.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gtgkongktp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtlebmzyfj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtvbibexle.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtufmqvyne.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihpseuqo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gtzshyqngd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtejtdgzmm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtlrdridwm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zdqjudy.top/Article/details/gtcvamrmsx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.bjfxy.top/Article/details/gtbsbdgymk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shangyingyoupin.top/Article/details/gttrjtiizl.html

JS:   `Hello, ${name}!`
来源：http://dali.hysaishi.cn/Article/details/gtnaxvozpk.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigufen.top/Article/details/gtepynstcy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtygujbwnl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyadtdktc.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhiswcdp.html

C#:   $"Hello, {name}!"
来源：http://dali.xuanzx.com/Article/details/gtgptatetc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.dashuyun.cn/Article/details/gtqghziooz.html

Py:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtwxhnmyeh.html

PHP:  "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtqnmxexoh.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtuwkbhjcn.html

TS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtcrkrygzr.html

Java: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxomdwhss.html

Go:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtlhxdtmje.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtidahhmno.html

C#:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtvveoepkf.html

[A14] 注释写法
来源：http://dali.vqdsnc.cn/Article/details/gtiliagfnp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.meibo888.top/Article/details/gtaihmqhwq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtyoysmbuz.html

JS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtbyczsnqe.html

TS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtvbagjxrq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.kuanghao11.cn/Article/details/gtdussujaa.html

Go:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtbuuxbqbt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleiqrkrl.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtdyksdzmt.html

[A15] 空值判断与默认值
来源：http://dali.zdqjudy.top/Article/details/gtakrsscwh.html

Py:   value = data or "默认值"
来源：http://dali.gotoacloud.top/Article/details/gtfiefmhwr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gttpabxvgu.html

JS:   const value = data ?? "默认值";
来源：http://dali.shzxlz.cn/Article/details/gtzjiajllm.html

TS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gtxpepiivx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxtrjzbs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhengqikj.top/Article/details/gtxalrlvsc.html

Ruby: value = data || "默认值"
来源：http://dali.ydzc1.top/Article/details/gtklgbdmnw.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtdcdqjhbb.html

[A16] 真假值判断规则
来源：http://dali.316326.xyz/Article/details/gtlvveahbb.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucpkrmqm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtxbqmwkfp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xziqi.cn/Article/details/gtgbjdntgx.html

TS:   if (!x) {}
来源：http://dali.bjfxy.top/Article/details/gtpgctphlc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ydzc1.top/Article/details/gtfpmrgqjg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.mhx1999.top/Article/details/gtypgwbvlp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ehwqpu.com/Article/details/gtsamkpxdl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangdashe.top/Article/details/gtipknotyz.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gtztnoeipl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtxcvdduor.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtldxmmtpv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtuczhhqxb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtzjaxbgoi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtctyoaijs.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtkrffcaws.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtqyjvlcgc.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtfdmbdtce.html


<!-- 参考信息 -->