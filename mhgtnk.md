代发 wailian999

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtolmmlucr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtosilxdct.html

[U106] JS：日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtvhzntvdy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.316326.xyz/Article/details/gtgploiqsg.html

[U107] JS：数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtouqtrifw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtixmbawwg.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtwkxddweu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hysaishi.cn/Article/details/gtfivtfykk.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gtgekpbohh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtgtahfuqv.html

[U110] JS：数组分块
来源：http://dali.gotoacloud.top/Article/details/gtliobniax.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gtsbgbmfky.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gthvchavvc.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtvrnvaotq.html

[U112] JS：字符串补位
来源：http://dali.wangshuangyany.cn/Article/details/gtfcncxwan.html

"7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtdysgsnnv.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtxjfghqfa.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtivcdtuto.html

[U114] JS：JSON 深比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkjbhijo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtmnikwtvi.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gthfmvhlix.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtwctssflq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgserour.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtrrnektpg.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gtmstzcttn.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtqgivclji.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gtfilzosvp.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtljrrgqxr.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtbvwubxnb.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gtzvnusvyq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.iojbl.cn/Article/details/gtkiyqqtpj.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gtblpzwrtu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnvkvximv.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtdzdzkbca.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtastpyveb.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtwotdwuje.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtqjkecawc.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gtieildodo.html

JavaScript ..... 252
来源：http://dali.cheryme.top/Article/details/gtspqcujpn.html

TypeScript ..... 212
来源：http://dali.ybcxt.top/Article/details/gtbzjqtngg.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gtufblbppf.html

Go ............. 212
来源：http://dali.316326.xyz/Article/details/gtyamsyflk.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtobemsfut.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gtncwxhznf.html

C .............. 30
来源：http://dali.sxryk.cn/Article/details/gtoygpiayj.html

C++ ............ 30
来源：http://dali.yueranfly.top/Article/details/gtrrnzrpwl.html

SQL ............ 90
来源：http://dali.gaohongyu789.top/Article/details/gtzxbqehyc.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gteogqlkfb.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtjolngadk.html

Swift .......... 15
来源：http://dali.fzhhl.top/Article/details/gtqdfhbmkp.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtmlmpxgqf.html

Perl ........... 10
来源：http://dali.zhixingplan.top/Article/details/gtuxanlqly.html

Scala .......... 10
来源：http://dali.xinyue.icu/Article/details/gtqmflcqzd.html

------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtwucyynjz.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gteerbtyqq.html

按章节统计：
来源：http://dali.cashguo.top/Article/details/gtnxtcdaeb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gtltjcdfmd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gteywlreld.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvrybluj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gtnbqmzcgo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gteshpmike.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gtcnqipbcl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtwyfkltsk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fengsongda.top/Article/details/gtsvwcjwxj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtgwokbkml.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xinyue.icu/Article/details/gtunvqnarl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtomcxfcyz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gteltrerjm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtcwxfpbqq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtkenfnllr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gtckeonzvq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtpffugqqa.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gtuarldant.html

R Bash 专题                             80
来源：http://dali.jianghu66.top/Article/details/gtqnjscjmw.html

S C / C++ 专题                          60
来源：http://dali.nwbrower.top/Article/details/gtsafulrmj.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gteensevzy.html

U 高频实用片段                         120
来源：http://dali.tian-w.cn/Article/details/gtpnvhefou.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtyrfdxssp.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwbiztys.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtpacsukvs.html

使用提醒
来源：http://dali.hywenlv.cn/Article/details/gteitrsahk.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtlazpehba.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgufenzy.top/Article/details/gttcjnjcao.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gtijampthh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gtcxnhgdzy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cqqwz.cn/Article/details/gtewzlvgsk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhixingplan.top/Article/details/gtqvhzfwsg.html

—— 文件结束 ——
来源：http://dali.yj202588.top/Article/details/gtkefgqrne.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtentyvmfm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gtdqubbyxk.html

Common Programming Examples Cheat Book
来源：http://dali.sysykeji.top/Article/details/gtdfjewzsk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtdvksnspz.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtgswcbjwi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hongshengwenyu.top/Article/details/gtsfcxwuyw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gtnwsxbdou.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gtmnnshwab.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cheryme.top/Article/details/gtljedtpzy.html

【使用说明】
来源：http://dali.sweek.top/Article/details/gtwszwmvcf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gtvttlmoep.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yanxiufei.cn/Article/details/gtfppjexwa.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.c1oappe.top/Article/details/gtznjavcan.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ppjwa.cn/Article/details/gtqbswzpdw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.snrcjt.cn/Article/details/gtzboqybzb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gtibtthfcv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtdykymrkz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnxiangtu.top/Article/details/gtqglytepa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgufenzy.top/Article/details/gtttpphxoq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hongshengwenyu.top/Article/details/gtivoafbwu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gtzkxgavoc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gtfrvmfxdz.html

【文件统计】
来源：http://dali.pengpengdd.cyou/Article/details/gtexmozpey.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.tian-w.cn/Article/details/gthiwnyvvx.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gttccfthwq.html

目  录
来源：http://dali.c1oappe.top/Article/details/gtpmcmqkhl.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gtvvqubzck.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gthvgisxiw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtuegcnnkp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gthngfloek.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yongpay.top/Article/details/gtqrsuodwo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.nanxuanxn.top/Article/details/gtlusejnay.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtxrgcihkm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtdbkdakch.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.316326.xyz/Article/details/gtagobnhhq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gtmxheoobd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtamihbtky.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gtdoikqrvf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtrzdnjvjo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gthvdmbvfr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtdmofipfd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigufen.top/Article/details/gtysygtbpr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gttqojlhyg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtlekejdut.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gtzmibvzva.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hammf.cn/Article/details/gtmforazno.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtyudgaxfx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnvdfmwh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiqbekfb.html

A. 基础语法与类型
来源：http://dali.cashguo.top/Article/details/gtunvsmkpc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzfuskion.html

[A01] Hello World
来源：http://dali.zycfv.cn/Article/details/gtiaszkymv.html

Py:   print("Hello, World!")
来源：http://dali.chenjidiqi.icu/Article/details/gttsjhhyrq.html

PHP:  echo "Hello, World!";
来源：http://dali.sweek.top/Article/details/gtkfmcmvra.html

JS:   console.log("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhhqylnn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.feifeiyinyue.top/Article/details/gtymnxvgkc.html

Java: System.out.println("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtgsgvbvfw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.chenzaomai.com/Article/details/gtoeuyqmxq.html

Ruby: puts "Hello, World!"
来源：http://dali.hnqzz.top/Article/details/gtviqdmaqi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gtvyzmqedl.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gteyoeumjq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.c1oappe.top/Article/details/gtpmiklako.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.redwolf501.top/Article/details/gtldcolzqv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gtewkcxsgs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtucghqadn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gtyatwwkrw.html

Go:   name := "Alex"; age := 20
来源：http://dali.xuanzx.com/Article/details/gtqdsvnsld.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zycfv.cn/Article/details/gtiesjhyff.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hfpthk.cn/Article/details/gtniyncdyz.html

[A03] 常量定义
来源：http://dali.xinyue.icu/Article/details/gthwlrgpwd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.c1oappe.top/Article/details/gtpefoczfk.html

PHP:  const PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtvgcbtssb.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkhtdetd.html

TS:   const PI: number = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gthssdvhbk.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtputhwgwt.html

Go:   const PI = 3.14159
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjhjoqcg.html

Ruby: PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxodipdt.html

C#:   const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtninvznfk.html

[A04] 判断变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtfbahqpsb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuanzx.com/Article/details/gtzfkizwrc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cdnleiting.top/Article/details/gtcmhejjly.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xylfe.cn/Article/details/gtvunctlke.html

TS:   typeof x; x instanceof Date
来源：http://dali.yongpay.top/Article/details/gtrbqednyf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shangyingyoupin.top/Article/details/gtqxykmfjg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.tian-w.cn/Article/details/gtkaodlaak.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gzhubu.top/Article/details/gtmthlicsi.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gtjvsbqzss.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gtxpqpoasb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zdqjudy.top/Article/details/gtxvyvwvoh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtggucshtm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.birdmap.top/Article/details/gtczhlksof.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtpgpvjeku.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtixmqwwjp.html

Go:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtlgsljjfn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtrnmekpmy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtheqyzehj.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtrnfmaicq.html

Py:   int("42"); float("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtssubavdg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhongyouzk.top/Article/details/gtchmtxcqw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.daxiang520.top/Article/details/gtzzdeedsn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtitujcwep.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.haohaochexian.top/Article/details/gtixknwjii.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gtgnwskpnw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.redwolf501.top/Article/details/gtjlllzxcb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.nanxinkj.top/Article/details/gtzfotyaxz.html

[A07] 数字转字符串
来源：http://dali.nwbrower.top/Article/details/gttaljlvrj.html

Py:   str(42)
来源：http://dali.xuanzx.com/Article/details/gtxhorzidn.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gtqsqasjwf.html

JS:   String(42); (42).toString()
来源：http://dali.316326.xyz/Article/details/gtcxajdady.html

TS:   String(42)
来源：http://dali.hammf.cn/Article/details/gttllytsxu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yongpay.top/Article/details/gtsnthmmad.html

Go:   strconv.Itoa(42)
来源：http://dali.jinqigfzy.top/Article/details/gtaciqiswl.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtnwuoemqk.html

C#:   42.ToString()
来源：http://dali.ivvv.top/Article/details/gtxwrckjwl.html

[A08] 取整与四舍五入
来源：http://dali.guowangkeji.top/Article/details/gtdrjddpiv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtutwpktbp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj202588.top/Article/details/gtajrirgtg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtgtbxfmmi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yongpay.top/Article/details/gtmtjbwogh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gttcqewwzq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtpzgobdbq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.bjfxy.top/Article/details/gtxtrcxdfs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtonkquhxv.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258.top/Article/details/gtcrvoxffs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtfwayqorw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxdxuglw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gtynwetpwi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggufavfp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtbixhgjjg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ivvv.top/Article/details/gtyrjmyxsu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.havefunace.top/Article/details/gthjpvldbk.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtgfeqgfkf.html

[A10] 生成随机数
来源：http://dali.chenlongwang.top/Article/details/gtgsacdvcq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tian-w.cn/Article/details/gttoyrpmzt.html

PHP:  random_int(1, 100);
来源：http://dali.haohaochexian.top/Article/details/gtzsfpjzjl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenjidiqi.icu/Article/details/gtpdiagpne.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gtztcherao.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yangfankeji.com/Article/details/gtluzjpucz.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.316326.xyz/Article/details/gtcjtrrrkf.html

Ruby: rand(1..100)
来源：http://dali.zhengqikj.top/Article/details/gtnfbaqtih.html

C#:   new Random().Next(1, 101)
来源：http://dali.gotoacloud.top/Article/details/gtxpsfttzl.html

[A11] 条件表达式（三元）
来源：http://dali.jinqigfzy.top/Article/details/gtdovnhcje.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.nanxinkj.top/Article/details/gtmfcsqxno.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gttwismfox.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtgxbogpxe.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gteuphdxyp.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtbmecntdp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sysykeji.top/Article/details/gtfresueyu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtxhiamvyc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtbeitmrmg.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigfzy.top/Article/details/gtwtkinbqu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.vqdsnc.cn/Article/details/gtnmpisvif.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gtyqidfkrw.html

JS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtxjkfjgqv.html

TS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gtpligyxju.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gtohxjqwqk.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yvedp.cn/Article/details/gtbvpyxwwe.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gtubiselyg.html

C#:   $"Hello, {name}!"
来源：http://dali.jyoumei.cn/Article/details/gtdeepykiu.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hammf.cn/Article/details/gthjoiimxt.html

Py:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtqmmxrure.html

PHP:  "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtzjscqomd.html

JS:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtfqczmcpa.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtnhdrrtou.html

Java: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtowiulwoh.html

Go:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtutoquoxy.html

Ruby: "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtsqydmjga.html

C#:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtwxxlxdgy.html

[A14] 注释写法
来源：http://dali.ydzc1.top/Article/details/gtdfxtyrkc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shuidangran.top/Article/details/gtytucfrge.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtmcaapjtx.html

JS:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtexrjobym.html

TS:   // 单行；/* 多行 */
来源：http://dali.xylfe.cn/Article/details/gtssikcxkr.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guannengcc.top/Article/details/gtsupvvgxs.html

Go:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtnahwiquo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gtoihrxqef.html

C#:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtkzzydmzl.html

[A15] 空值判断与默认值
来源：http://dali.birdmap.top/Article/details/gtzkrurhxf.html

Py:   value = data or "默认值"
来源：http://dali.jianghu66.top/Article/details/gtetzbvbzg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.quarkkingdee.top/Article/details/gtdtzfmqkl.html

JS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtkohwilmw.html

TS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtvoujliah.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jlsjyb.cn/Article/details/gttwpbadkz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gtqblypawm.html

Ruby: value = data || "默认值"
来源：http://dali.cashguo.top/Article/details/gtvnollzhj.html

C#:   var value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtbzspvdky.html

[A16] 真假值判断规则
来源：http://dali.daria6918.cn/Article/details/gtxlpdbfmm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.redwolf501.top/Article/details/gtqbwssizp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ehwqpu.com/Article/details/gtaedkzbse.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtvhsjalbl.html

TS:   if (!x) {}
来源：http://dali.aizwys.cn/Article/details/gtkpsuwxaq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuanzx.com/Article/details/gtofmofgoh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.smart0.xyz/Article/details/gtdznmurnk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gtgvyajefw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258.top/Article/details/gtubpwftdl.html

[A17] 位运算
来源：http://dali.yuanzhike.top/Article/details/gtqfxewlgp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtwgbxxfub.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtfqpmqdue.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gttvyamsex.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsynxajr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtkvmjsfbb.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gthlintlsl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtbcolobtg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gteawqxeex.html

[A18] 字符与 ASCII 码互转
来源：http://dali.fengsongda.top/Article/details/gtzeilpgbw.html

Py:   ord("A"); chr(65)
来源：http://dali.cdnleiting.top/Article/details/gtblcmrzgf.html

PHP:  ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtztvokwmt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.smart0.xyz/Article/details/gtisyxbnkr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtnfcomccz.html

Java: (int) 'A'; (char) 65
来源：http://dali.guannengcc.top/Article/details/gteidtqdfv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gtptomxtqy.html

Ruby: "A".ord; 65.chr
来源：http://dali.yuxming.cn/Article/details/gtofdxavkz.html


<!-- 参考信息 -->