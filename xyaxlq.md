代发 wailian999

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gtormpdybe.html

el.classList.toggle("active")
来源：http://dali.yonumen.top/Article/details/gtufcyzode.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtenztbtlc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gtfchjrosg.html

[U103] JS：定时器
来源：http://dali.nwbrower.top/Article/details/gtbhstkras.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gtzumomuyv.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtvrswosxo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gtvdiuuwmy.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gtpklrwdeo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gtlxdgeauk.html

[U106] JS：日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtayevnwlg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daxiang520.top/Article/details/gteqzyihtg.html

[U107] JS：数字千分位
来源：http://dali.xziqi.cn/Article/details/gtiwhsrnsz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtevetszqn.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaqiigmy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj20258.top/Article/details/gtrmalisoc.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtsnbsuruk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtpvzkyvdq.html

[U110] JS：数组分块
来源：http://dali.chenzaomai.com/Article/details/gtrnwnfmra.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtclwxdfvs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gtnhjfhnat.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtogqgufyd.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtbhbkdwdy.html

"7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtaejczsio.html

[U113] JS：正则替换全部
来源：http://dali.pengpengdd.cyou/Article/details/gtsgjtzwdu.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtseoflico.html

[U114] JS：JSON 深比较
来源：http://dali.tian-w.cn/Article/details/gtpitlotbi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtkhwmbcix.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gttpvlxqog.html

crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtvgfmvgrx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtxlrpfufp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtgxvnfrre.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtbstegytm.html

npm i -D vitest;  npx vitest
来源：http://dali.guowangkeji.top/Article/details/gtpsemtuft.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangtech.top/Article/details/gtaslidguo.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gtmpdhwfox.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gtmipyizcg.html

npx vite build
来源：http://dali.fengsongda.top/Article/details/gthwhgunmy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtosmdiawd.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gtcoaulunt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgatbiadm.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtslgtecko.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthwebaiek.html

按语言统计（条）：
来源：http://dali.iojbl.cn/Article/details/gtloxjymzu.html

Python ......... 252
来源：http://dali.tianlin.xyz/Article/details/gtxqzibzri.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gtlmlgmlnu.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzerqlebv.html

TypeScript ..... 212
来源：http://dali.chenlongwang.top/Article/details/gtoglltybd.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtsshavsmr.html

Go ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtjhiqqzmv.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtpdmurbsn.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gtirgfgpkz.html

C .............. 30
来源：http://dali.guannengcc.top/Article/details/gtqboeovhc.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkhszyxo.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxaqdabiv.html

Bash ........... 80
来源：http://dali.jinghuilouyu.cn/Article/details/gteabhgeqp.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtgnndbumr.html

Swift .......... 15
来源：http://dali.fzhhl.top/Article/details/gtgvaaelwa.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtfhrhfqpv.html

Perl ........... 10
来源：http://dali.tian-w.cn/Article/details/gtaexosion.html

Scala .......... 10
来源：http://dali.pycfn.com/Article/details/gtwtcxkvgw.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtkrtnshyq.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gtvoemfloj.html

按章节统计：
来源：http://dali.cucudq.cn/Article/details/gtlsyirljg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtteikvoma.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gthlcjtwyc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtxziegcme.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtgwshushf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gtcksrpdox.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtiwmxdxwu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtnkowdxsx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxuanxn.top/Article/details/gtocqsjnpn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtdpmqbhsa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sysykeji.top/Article/details/gttnlzclra.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtcvnkxhos.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtsnjgryio.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtlxvjwxsu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj202588.top/Article/details/gttkqvahtn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.9152youxi.cn/Article/details/gtjjnowhox.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtudqezslk.html

Q SQL 专题                              90
来源：http://dali.fengsongda.top/Article/details/gtwzmnqxvt.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gtjtfazhqc.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gtvqhuhwfx.html

T 其他语言补充                          60
来源：http://dali.gaohongyu789.top/Article/details/gtvrmvnays.html

U 高频实用片段                         120
来源：http://dali.jinqigufen.top/Article/details/gtnfxjcedc.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtecxxspsg.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gtsemqbwnj.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtoxidvgcy.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gttmoxuxgi.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtxnybfybq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.tianlin.xyz/Article/details/gtyqypxggm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hammf.cn/Article/details/gtbgxkyubs.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.9152youxi.cn/Article/details/gtacfejxwb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.chenlongwang.top/Article/details/gttleufedl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnxiangtu.top/Article/details/gtnynbupgt.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gtvvuzbnil.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqsrlvrtv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjqvzolr.html

Common Programming Examples Cheat Book
来源：http://dali.hongshengwenyu.top/Article/details/gtaujqrfdu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyfjffmi.html

【收录内容】
来源：http://dali.mhx1999.top/Article/details/gtoyiywget.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sxryk.cn/Article/details/gtymqkggah.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nwbrower.top/Article/details/gtbxdpnuwa.html

SQL · Bash · C · C++
来源：http://dali.zycfv.cn/Article/details/gtitxcwyxx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkczpoup.html

【使用说明】
来源：http://dali.yuxming.cn/Article/details/gtfhinpvvr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ppjwa.cn/Article/details/gtsgqupvsv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhoulong.xyz/Article/details/gtprlwkmcd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hnxiangtu.top/Article/details/gtumypvmfk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.iojbl.cn/Article/details/gtyryhuegu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.birdmap.top/Article/details/gtuxzhxxrj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sysykeji.top/Article/details/gtxpwlpieb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hysaishi.cn/Article/details/gtgwcvrjtp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hongshengwenyu.top/Article/details/gtjenrmxak.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtyhrddsyu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gtpyestziu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgufenzy.top/Article/details/gtaaepxnqp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pengpengdd.cyou/Article/details/gtxpizlefd.html

【文件统计】
来源：http://dali.mhx1999.top/Article/details/gtfxzfbetp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zdqjudy.top/Article/details/gtosekaxca.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtlydrwame.html

目  录
来源：http://dali.wangshuangyany.cn/Article/details/gtlzgffacg.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtgqmkyzec.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gtikaqwsel.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtozcqzchb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.redwolf501.top/Article/details/gtiryhribs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtntefcbtj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hysaishi.cn/Article/details/gtqfpjocai.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtevzmocxf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtywbnnmvj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.tian-w.cn/Article/details/gtsashvphq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtpraymxwz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtpynuuptp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtetcrfrqn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtgyjhznru.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yj20258888.top/Article/details/gtiaabcsmo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtmilbfaef.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gtbxoqkzau.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtvkirpsrx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gtdywmwaay.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yvedp.cn/Article/details/gtuscanard.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgpflhxtz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtgaxxnlsr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtnbuspjvz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtifcwfsiv.html

A. 基础语法与类型
来源：http://dali.hywenlv.cn/Article/details/gtyxxxxpec.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtemcbkbaw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtygfnlulo.html

Py:   print("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwohnxfhi.html

PHP:  echo "Hello, World!";
来源：http://dali.xylfe.cn/Article/details/gtrwjtnwmq.html

JS:   console.log("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtubmhsfhd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shzxlz.cn/Article/details/gtwhuppdgp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtgwqycucn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtthrxzfqu.html

Ruby: puts "Hello, World!"
来源：http://dali.shuidangran.top/Article/details/gtfeqnavkg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtgvpgatgr.html

[A02] 变量声明与赋值
来源：http://dali.ydzc1.top/Article/details/gtenwqmtyw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yanxiufei.cn/Article/details/gthmysfgrh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtjokschyl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhixingplan.top/Article/details/gtjsokukbv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.vqdsnc.cn/Article/details/gtyozknduw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtjzwfhbiw.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258888.top/Article/details/gtfdvqodjg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gtovqqownm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gthnqjmwro.html

[A03] 常量定义
来源：http://dali.vqdsnc.cn/Article/details/gtbzjdwfon.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsskbxff.html

PHP:  const PI = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtmkyuwofl.html

JS:   const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtzkhxuqvo.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtqxxggkjf.html

Java: static final double PI = 3.14159;
来源：http://dali.guowangkeji.top/Article/details/gtplbprtvj.html

Go:   const PI = 3.14159
来源：http://dali.jianghu66.top/Article/details/gtrsjxhizg.html

Ruby: PI = 3.14159
来源：http://dali.pycfn.com/Article/details/gtupsnymur.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtrrlpetih.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrurzeza.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hammf.cn/Article/details/gtiwkkqdtv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtovlhoaly.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtrvngxgkg.html

TS:   typeof x; x instanceof Date
来源：http://dali.0kj1m.cn/Article/details/gtkuzziowk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cucudq.cn/Article/details/gttowphbhe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gtllflylkr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gzhubu.top/Article/details/gtfrrgfanm.html

C#:   x.GetType().Name; x is int
来源：http://dali.0kj1m.cn/Article/details/gtrahfuphq.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gtqhvcikis.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.wangdashe.top/Article/details/gtekpovvih.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtqlspqjoz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gtjnjzbgna.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtdjykqplo.html

Java: 7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoamdjfi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtwieeqyxv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gthypohykw.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthaaqoswo.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtsozvkfmd.html

Py:   int("42"); float("3.14")
来源：http://dali.zhixingplan.top/Article/details/gtfqnbkyna.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gtjhadblyf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnehijvdo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yonumen.top/Article/details/gtstpcgmfk.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtuztximov.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhoulong.xyz/Article/details/gtiqtycdev.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pengpengdd.cyou/Article/details/gtslmagmce.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtffhxdvcx.html

[A07] 数字转字符串
来源：http://dali.guowangkeji.top/Article/details/gthxahzeji.html

Py:   str(42)
来源：http://dali.sysykeji.top/Article/details/gtqrhyqxga.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gtnrrmpovr.html

JS:   String(42); (42).toString()
来源：http://dali.fengsongda.top/Article/details/gtwlwqxfbv.html

TS:   String(42)
来源：http://dali.ivvv.top/Article/details/gtryjkbwmr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenzaomai.com/Article/details/gteuvqjvkx.html

Go:   strconv.Itoa(42)
来源：http://dali.yueranfly.top/Article/details/gtijctdwcn.html

Ruby: 42.to_s
来源：http://dali.snrcjt.cn/Article/details/gtqkgjcmfi.html

C#:   42.ToString()
来源：http://dali.hfpthk.cn/Article/details/gttskdalfr.html

[A08] 取整与四舍五入
来源：http://dali.hammf.cn/Article/details/gtaorblnii.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtyqzbzwye.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhengqikj.top/Article/details/gtzyvbileo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xziqi.cn/Article/details/gtoneqhmly.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.svipenyu.cn/Article/details/gthbwrngxv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtucjdjjgj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gttufxpjyc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258888.top/Article/details/gtabngnere.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtkratzcke.html

[A09] 绝对值与最大最小值
来源：http://dali.birdmap.top/Article/details/gtfbmmgnqa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gtlztdracd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtmwpqvnla.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtfnqffobv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtruhwlcrx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtachcdglk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.smart0.xyz/Article/details/gtuzmzibvx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.feifeiyinyue.top/Article/details/gtxuxrwbhu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtdrdrrsbj.html

[A10] 生成随机数
来源：http://dali.chenlongwang.top/Article/details/gtiodopjmw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhengqikj.top/Article/details/gtipsqevbu.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtzzsdfill.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtfwgyhglz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgihkkupu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.smart0.xyz/Article/details/gtjxtjentd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknjmhtyf.html

Ruby: rand(1..100)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbmxpmxz.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gtutxtpvmv.html

[A11] 条件表达式（三元）
来源：http://dali.shangyingyoupin.top/Article/details/gtcmfjvdhb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhoulong.xyz/Article/details/gtmbvrmmtn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtypbujlwn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtrkxrsqyw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtcjsujaqr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gthsajsehm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnxiangtu.top/Article/details/gtizkflecb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtflehpxsf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtjcyhayxi.html

[A12] 字符串插值 / 格式化
来源：http://dali.dianchejie.cn/Article/details/gtaefnugqh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cheryme.top/Article/details/gtkadjgnbq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aibaodan.cn/Article/details/gtbugvdefq.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtfoprme.html

TS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtyhrpdcvg.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gtjtgtpswo.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guowangkeji.top/Article/details/gtugvbcxrm.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnagdvbbm.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gtnfcmrjtu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.haohaochexian.top/Article/details/gtqxueimdj.html

Py:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtfplqyvxj.html

PHP:  "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtlicpnulq.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtvuzwmbzo.html

TS:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtpxtcsnmi.html

Java: "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtkmniwgnl.html

Go:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtdyfolpvo.html

Ruby: "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gtbazopgze.html

C#:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtttfesmgb.html

[A14] 注释写法
来源：http://dali.aizwys.cn/Article/details/gtncsnojvw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtgngonmqo.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtdreitett.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtvxxidprm.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtionbexgj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hammf.cn/Article/details/gtsbexcsza.html

Go:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtgbaacxth.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zdqjudy.top/Article/details/gtqguywrxj.html

C#:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpayucudh.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gtzgpllqmw.html

Py:   value = data or "默认值"
来源：http://dali.daxiang520.top/Article/details/gtdfwtqwgs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtkseddofz.html

JS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtkugmudcj.html

TS:   const value = data ?? "默认值";
来源：http://dali.tanke756.top/Article/details/gtimoqgxls.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gturxgolsj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuxming.cn/Article/details/gtgbasypdr.html

Ruby: value = data || "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwxnwyqc.html

C#:   var value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtrgquhxof.html

[A16] 真假值判断规则
来源：http://dali.cdnleiting.top/Article/details/gtnckvyeio.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.smart0.xyz/Article/details/gtximcloax.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.feifeiyinyue.top/Article/details/gtovnsfxci.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aibaodan.cn/Article/details/gttnmdytwp.html

TS:   if (!x) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxstkmnt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yj202588.top/Article/details/gtoviikvoz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtzbdhgiyv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj202588.top/Article/details/gtqvklvypp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ppjwa.cn/Article/details/gtqohtuncb.html

[A17] 位运算
来源：http://dali.yj20258.top/Article/details/gtzamglcih.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtzwdfzwny.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlwvcoul.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtavcataut.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtbudoitxk.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtigngmvxi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtyoznokqh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtqpxqlcah.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtkuflcoec.html


<!-- 参考信息 -->