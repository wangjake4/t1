代发 wailian999

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gtcdajtioi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinghuilouyu.cn/Article/details/gthvysyosg.html

[U104] JS：防抖
来源：http://dali.chenjidiqi.icu/Article/details/gttxyvmwfj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gtvnqkcmsk.html

[U105] JS：节流
来源：http://dali.gaohongyu789.top/Article/details/gtjymxjaxc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.birdmap.top/Article/details/gtmnprvxcl.html

[U106] JS：日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gtyyowpuev.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtdzjvtowo.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gttzldbpts.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtjfykblno.html

[U108] JS：随机整数
来源：http://dali.yuanzhike.top/Article/details/gtojqdzedl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtadmefcls.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjeqztva.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdcmbjcp.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtdckrclni.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtssaemodu.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtoojctimd.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgjmqwgl.html

[U112] JS：字符串补位
来源：http://dali.hysaishi.cn/Article/details/gtgxzlurpk.html

"7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtpjiiwsio.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxlmedukj.html

s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtfbtbjceh.html

[U114] JS：JSON 深比较
来源：http://dali.zhongyouzk.top/Article/details/gtxvfibdyq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnxiangtu.top/Article/details/gtqjgyutmc.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtcetcchsz.html

crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gtysnrdlhf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gttzsxgpid.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtucpmwjea.html

[U117] JS：单元测试
来源：http://dali.sysykeji.top/Article/details/gthkrssobf.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gthgncvmca.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtdqvjvotx.html

npm i -D vite;  npx vite
来源：http://dali.nanxuanxn.top/Article/details/gtnzszqzbl.html

[U119] JS：生产构建
来源：http://dali.sxryk.cn/Article/details/gtnretpbtz.html

npx vite build
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkeuoaph.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtnwqokbgw.html

import.meta.env.VITE_API_URL
来源：http://dali.daxiang520.top/Article/details/gtqavbiivo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtptmnmsqb.html

统计汇总
来源：http://dali.ehwqpu.com/Article/details/gtopejxqpo.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrjsjqcjc.html

按语言统计（条）：
来源：http://dali.guannengcc.top/Article/details/gtslahkwwa.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtcqcxobnw.html

PHP ............ 252
来源：http://dali.yvedp.cn/Article/details/gtzythaucc.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gtotxbufid.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtkgqzbcyk.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtprezgeqa.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gtwmgjzfyj.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtciigcrgc.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtgolbogyr.html

C .............. 30
来源：http://dali.yj202588.top/Article/details/gtztwqmczl.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gthuqukpch.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gtazcxfirr.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gtpzpnrkpq.html

Kotlin ......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtxlkyfvgc.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtvstiyyrm.html

Lua ............ 10
来源：http://dali.hongshengwenyu.top/Article/details/gtfljlucqp.html

Perl ........... 10
来源：http://dali.redwolf501.top/Article/details/gtuybvktdt.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtbvlhkwia.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzphvronj.html

合计 ........... 2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtwowrhxrr.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtzjolwmjm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtqkhfkrfy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtpfvrolfs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtesjomvvb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtenpeqyog.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fzhhl.top/Article/details/gtzzgzylqd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtasmzwsym.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtbcxufkqz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtvhsktlmj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtawlpxbxx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yonumen.top/Article/details/gttzszhtxu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtjaamlxeh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gthcuqsfdd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gtisffqtmh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gtbiizuhuo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtzofcqrpb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtxsmtpjwx.html

Q SQL 专题                              90
来源：http://dali.yuxming.cn/Article/details/gtznsojagj.html

R Bash 专题                             80
来源：http://dali.xinyue.icu/Article/details/gtzamitaxq.html

S C / C++ 专题                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtutnlbwnn.html

T 其他语言补充                          60
来源：http://dali.andypj.xyz/Article/details/gtigkfekwp.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gthhylkcip.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtbpxdpdug.html

合计                                  2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtaeglxhbn.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtyemlkeiv.html

使用提醒
来源：http://dali.jinqigfzy.top/Article/details/gtxqgnsobq.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtuuoakpfh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cqqwz.cn/Article/details/gtrnxvmszc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gtiqrvwdlt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aibaodan.cn/Article/details/gtivmzkhax.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gtckrbvybx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gaohongyu789.top/Article/details/gtyrppuhnh.html

—— 文件结束 ——
来源：http://dali.vqdsnc.cn/Article/details/gtunlxigkk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjtjhmyuh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gtaxlbdttr.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gtbgmknsfj.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtqmrzpamb.html

【收录内容】
来源：http://dali.xziqi.cn/Article/details/gtobbzxkei.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.mhx1999.top/Article/details/gtprapeiom.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.quarkkingdee.top/Article/details/gthdmgubws.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gtqgwvhjus.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nwbrower.top/Article/details/gtjmjucoff.html

【使用说明】
来源：http://dali.cqqwz.cn/Article/details/gtvhfmsveq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhixingplan.top/Article/details/gtofchlkkp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.svipenyu.cn/Article/details/gteeoxvlvl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jinqigfzy.top/Article/details/gtyqkzzkbf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtvmkmydmz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gtwyccgfui.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daria6918.cn/Article/details/gtgkfphfvy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xuetiantiany.cn/Article/details/gtdgakaces.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.quarkkingdee.top/Article/details/gtqjczvsmw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gtcxdwslgt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.quarkkingdee.top/Article/details/gtlemdpmnp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gtpfpewdsk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtxwhijihy.html

【文件统计】
来源：http://dali.cheryme.top/Article/details/gtveuomjsx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gtfudysjbt.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtndmfaawk.html

目  录
来源：http://dali.iojbl.cn/Article/details/gtworezbbn.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtxuylwthd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jyoumei.cn/Article/details/gtpmmisivx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gtcvoguzxx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gtbwnyljse.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttoevctmj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssjzaffe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gtgpvhlmcp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtztasbort.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtkqgahwjq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtmpexqxas.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.tianlin.xyz/Article/details/gteytwlxkv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtfrnbajhl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtmzuaklme.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gtecjsquyj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtvmrticpi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gtirustpyz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtmwpjzvdw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gtqvlmeinl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.birdmap.top/Article/details/gtfnqntqxs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shzxlz.cn/Article/details/gtsfdrdbhe.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dashuyun.cn/Article/details/gtdhiwecuz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sxryk.cn/Article/details/gtkxjwrpra.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtwgidxslo.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmxzfjei.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtbdpnhsbe.html

[A01] Hello World
来源：http://dali.daxiang520.top/Article/details/gtlngewukb.html

Py:   print("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtdmcthadr.html

PHP:  echo "Hello, World!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtggmlqxra.html

JS:   console.log("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gtgoaqwijr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnxiangtu.top/Article/details/gtedpdxzpz.html

Java: System.out.println("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtjzwojdxy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtnsvriofm.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gtzrmlisul.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gtnfjtxqcc.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtauwbqgrf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtsyrymopg.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtzlheljkz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtpjmkxnpe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gtwbzkzrlo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtdoefcgfb.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gtibzknifq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cheryme.top/Article/details/gthgutveiq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtgyvdjrvb.html

[A03] 常量定义
来源：http://dali.vqdsnc.cn/Article/details/gtfeqgazpf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.andypj.xyz/Article/details/gtxladeclt.html

PHP:  const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gttmrhmihe.html

JS:   const PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gtwaeyirki.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtifoidfdg.html

Java: static final double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtcizzdqsl.html

Go:   const PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gtzvinnain.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtwaezycuk.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmvrvxdy.html

[A04] 判断变量类型
来源：http://dali.cheryme.top/Article/details/gtvzlqdblf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.fzhhl.top/Article/details/gtlgpiwhdu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.fzhhl.top/Article/details/gtoblsujke.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gthmzzjakh.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gtissjwddk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dianchejie.cn/Article/details/gthismrbux.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.guowangkeji.top/Article/details/gtlfvdklej.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.fengsongda.top/Article/details/gtdbelzkqu.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gtlupreqvf.html

[A05] 整数除法与取模
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcahzeqxi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtnakvqsvy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtbxkoazxm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtlvnrfmop.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtfiffztdb.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtuspyatzp.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtfqdrfpjf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtsdvywcbz.html

C#:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gthqdjhjvy.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtlrvcatdm.html

Py:   int("42"); float("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuoeeopd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shuidangran.top/Article/details/gtggigxawe.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtwlhuxcaz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtvpqjkefr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.snrcjt.cn/Article/details/gtwqyivqul.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtnrtdrwpq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.pycfn.com/Article/details/gtoczgqocp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xuanzx.com/Article/details/gthzwxnkxz.html

[A07] 数字转字符串
来源：http://dali.yangfankeji.com/Article/details/gtlaaxrdjs.html

Py:   str(42)
来源：http://dali.wangdashe.top/Article/details/gtsbmuhtzf.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqjstgxc.html

JS:   String(42); (42).toString()
来源：http://dali.jianghu66.top/Article/details/gtbptzzbhv.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gtwktnsdxx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangdashe.top/Article/details/gtpmsgbmmw.html

Go:   strconv.Itoa(42)
来源：http://dali.guowangkeji.top/Article/details/gtwnagouoz.html

Ruby: 42.to_s
来源：http://dali.jinqigfzy.top/Article/details/gtiakhjxzo.html

C#:   42.ToString()
来源：http://dali.pycfn.com/Article/details/gtxtnilneg.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gtyuzdrwgf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtswstacuj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shzxlz.cn/Article/details/gtwgupgjlo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtftuegtco.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxourzhop.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtrczajrdj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtbqnclnjf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenlongwang.top/Article/details/gtclrndzca.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtwifobwcb.html

[A09] 绝对值与最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gtutockcnv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtojvlqdyo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtivpficec.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtztpkovib.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shuidangran.top/Article/details/gtwhmpozbw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtfxtphlsy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.svipenyu.cn/Article/details/gtifzcugbv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtdoznhscv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtclrwbqrl.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gtxlbfdzkm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gtuouczidq.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gtulvhuuap.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.sysykeji.top/Article/details/gtshfuppzg.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gtpqhgxpmn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gtcvyfaqfj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gtgadbwffj.html

Ruby: rand(1..100)
来源：http://dali.cdnleiting.top/Article/details/gtttfldlvy.html

C#:   new Random().Next(1, 101)
来源：http://dali.smart0.xyz/Article/details/gtcmffwhmy.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gtkrbwoxlz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenzaomai.com/Article/details/gtbwtrwlye.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtmbhxcxvw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtqosqwiky.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtvcpeygih.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtbgcjrfld.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fzhhl.top/Article/details/gtmluklciw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtidwpokks.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtrzzftxpp.html

[A12] 字符串插值 / 格式化
来源：http://dali.gzhubu.top/Article/details/gtlzjrxfqe.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yongpay.top/Article/details/gtexzfnjvh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ehwqpu.com/Article/details/gtncdshvfu.html

JS:   `Hello, ${name}!`
来源：http://dali.gogol.net.cn/Article/details/gtdwbgxykr.html

TS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gtospndsdd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gtlmcahkzq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shuidangran.top/Article/details/gtuvksrgtr.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gtacgbvqbw.html

C#:   $"Hello, {name}!"
来源：http://dali.cheryme.top/Article/details/gtkhjscqye.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.quarkkingdee.top/Article/details/gtubgvcqao.html

Py:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gthrdlevpk.html

PHP:  "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtreufvgwv.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtyvbzbvwa.html

TS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtgflnxwda.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtdejgrzut.html

Go:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtisfhsusn.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtmrnnuows.html

C#:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtwjpyvukf.html

[A14] 注释写法
来源：http://dali.gaohongyu789.top/Article/details/gtxfmlvazx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gtkmufujfm.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtvnwdulbs.html

JS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtkapwhkwo.html

TS:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gthenjjkfd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cdnleiting.top/Article/details/gtzzwshzts.html

Go:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtqxxrqhwy.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.316326.xyz/Article/details/gtydzgfzsd.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtldtjgdxf.html

[A15] 空值判断与默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtxmywdtci.html

Py:   value = data or "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gtxlvwpxdu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtedbozudj.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtmcnjmhsb.html

TS:   const value = data ?? "默认值";
来源：http://dali.hongshengwenyu.top/Article/details/gtmaqrkimx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ehwqpu.com/Article/details/gtkkkyzqdf.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthflqicae.html

Ruby: value = data || "默认值"
来源：http://dali.ybcxt.top/Article/details/gtjxhhbqni.html

C#:   var value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtwhspazxc.html

[A16] 真假值判断规则
来源：http://dali.fengsongda.top/Article/details/gtrdaogphz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sufxvd.cn/Article/details/gtgadrvjln.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cdnleiting.top/Article/details/gtmxalmzqq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnqzz.top/Article/details/gtymymniip.html

TS:   if (!x) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvorqsuos.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtnvaaalai.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.316326.xyz/Article/details/gtbqswluvd.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pycfn.com/Article/details/gtsoxlmdry.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtfnrnqoqx.html

[A17] 位运算
来源：http://dali.jyoumei.cn/Article/details/gtkwfrmbdp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgtebkcl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.fengsongda.top/Article/details/gtutlacoqx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gtxxggcafi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtwagpribx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtqmhhbghk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtahzjxwqv.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtwxfulyik.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtqsajarsg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgufenzy.top/Article/details/gtuviypmfy.html

Py:   ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gtivyxibqa.html

PHP:  ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gtvmotbaow.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxpptjlf.html


<!-- 参考信息 -->