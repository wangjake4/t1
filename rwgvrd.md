代发 wailian999

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtydbgwnst.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gtrefwtbyk.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtsmffpios.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yongpay.top/Article/details/gttmkqjlbt.html

[U107] JS：数字千分位
来源：http://dali.tian-w.cn/Article/details/gtehannuhr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.redwolf501.top/Article/details/gtydikzvel.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gtoizybpdn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gthzifigmi.html

[U109] JS：数组分组
来源：http://dali.cashguo.top/Article/details/gtbdnyrlff.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtqomfybxz.html

[U110] JS：数组分块
来源：http://dali.gaohongyu789.top/Article/details/gtqmkowfcl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtskjdywvz.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gtiwrpsiti.html

new Map(Object.entries(obj))
来源：http://dali.wangdashe.top/Article/details/gtbnoqlmls.html

[U112] JS：字符串补位
来源：http://dali.jianghu66.top/Article/details/gtxwimcfpr.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtqgltzpct.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gthcsagcxb.html

s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtkoxrlguv.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gtbvciwcao.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtkyifpdyf.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtlkuarkly.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtcyqpyxcm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tian-w.cn/Article/details/gtvugiqddv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtoifnaqoi.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtchmdejyd.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gtxlsvjkzs.html

[U118] JS：开发服务器
来源：http://dali.hnqzz.top/Article/details/gtbnnipsnz.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gtatsptped.html

[U119] JS：生产构建
来源：http://dali.tian-w.cn/Article/details/gtxbpgapfw.html

npx vite build
来源：http://dali.sxryk.cn/Article/details/gtaarluvqp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gogol.net.cn/Article/details/gthspqeuzg.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gtmjxrktji.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvnlhnlwa.html

统计汇总
来源：http://dali.yonumen.top/Article/details/gtzkkezwkc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtrchbnbdr.html

按语言统计（条）：
来源：http://dali.nwbrower.top/Article/details/gtcxmqlhzl.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gtvvtmyfcq.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtteafsruk.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gtrgjbnmvg.html

TypeScript ..... 212
来源：http://dali.zhongyouzk.top/Article/details/gtomcqwmev.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtfbvndqfy.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gtpoqrypyj.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtqxrygmhq.html

C# ............. 212
来源：http://dali.sweek.top/Article/details/gttvfqeaki.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtjgbtxusf.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtqqmfmqyk.html

SQL ............ 90
来源：http://dali.zhengqikj.top/Article/details/gthydxczzz.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gtzrfvlydk.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcklgktj.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtixrrcutq.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gtarbilrsl.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtijbozuvv.html

Scala .......... 10
来源：http://dali.tian-w.cn/Article/details/gtgrfnkibu.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtlwornqtj.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gtkywtmefp.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmrsrcgh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtymrzernl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtrjgxvpxp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtbcxfqqja.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gtjlmqvrsi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gtcplldaul.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzjwvjhop.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtpfxonfvp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gtwkhsbijs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtqkxenkum.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cdnleiting.top/Article/details/gtnrcalhjc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtehnvnovl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtpxzmlgob.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtmzdiovmo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtryjpprxt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnqzz.top/Article/details/gtuexmjxrs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtoihwqpec.html

Q SQL 专题                              90
来源：http://dali.feifeiyinyue.top/Article/details/gtwqfvnetx.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gtnnanosyq.html

S C / C++ 专题                          60
来源：http://dali.andypj.xyz/Article/details/gtxfhfkkle.html

T 其他语言补充                          60
来源：http://dali.xinyue.icu/Article/details/gtjzbovsze.html

U 高频实用片段                         120
来源：http://dali.hysaishi.cn/Article/details/gtxnxnjonw.html

------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtnjgvphar.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gtggbodpvg.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtylsubegl.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtywmmmmij.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gthgsyalsa.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yonumen.top/Article/details/gthdzubmlu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgufenzy.top/Article/details/gtzizgovij.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtpduqowkz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigfzy.top/Article/details/gttmfhppey.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aibaodan.cn/Article/details/gtgbrdhhxd.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtljtoopia.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtiorrggmp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.dashuyun.cn/Article/details/gtfsuvalei.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gtjzynyqeh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtlgzajvtp.html

【收录内容】
来源：http://dali.jinqigfzy.top/Article/details/gtnjsxpbbb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.andypj.xyz/Article/details/gtiadfzfaz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ppjwa.cn/Article/details/gtwshnedbx.html

SQL · Bash · C · C++
来源：http://dali.havefunace.top/Article/details/gtudfucdgh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuanzx.com/Article/details/gtustrioky.html

【使用说明】
来源：http://dali.yongpay.top/Article/details/gtquockjgs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yj20258888.top/Article/details/gtbkoyjesp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tianlin.xyz/Article/details/gtuhzjfgmd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhoulong.xyz/Article/details/gtmfbcedrg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gtsrrubvtg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ppjwa.cn/Article/details/gtzwwgagny.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gtrtjiapfh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtyvvrmlyl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxinkj.top/Article/details/gtzbhealwh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jqgfzy.top/Article/details/gteofswxpm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gaohongyu789.top/Article/details/gtlhgxpwbu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yuanzhike.top/Article/details/gtorhnusmp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gtrcdbhppk.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gtbxbqermc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daxiang520.top/Article/details/gtnchmexqp.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtaqvxgceh.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gtuislrkir.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrtyoasc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gtdyxuteqd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtqoobrcyl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtktuhntod.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gteiwzvqzv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fengsongda.top/Article/details/gtjpyfzoxj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtbxntvyek.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtsqrvsbka.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfycgbsyl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtriavmtgt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gtekkhrerg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtyfetpbls.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtqoilnhda.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtcbjbpaxo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaryxkzx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtpzzwtcgm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtcgeyozrb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sysykeji.top/Article/details/gttriomqly.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqhmcwyl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhengqikj.top/Article/details/gtmmaszdlx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtaafkjpnl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gtixoilwyc.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gteuzolmus.html

A. 基础语法与类型
来源：http://dali.vqdsnc.cn/Article/details/gtauijgevo.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttwuynyha.html

[A01] Hello World
来源：http://dali.haohaochexian.top/Article/details/gtwiwycrkr.html

Py:   print("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtzliazgji.html

PHP:  echo "Hello, World!";
来源：http://dali.havefunace.top/Article/details/gtmpekoghp.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtabeeqhrw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yanxiufei.cn/Article/details/gtcmzomwqm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtiwfwxrzk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yangfankeji.com/Article/details/gtwxpvugmg.html

Ruby: puts "Hello, World!"
来源：http://dali.gzhubu.top/Article/details/gthxlglxye.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnlxeuwv.html

[A02] 变量声明与赋值
来源：http://dali.wangshuangyany.cn/Article/details/gtsnrkiqdm.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aizwys.cn/Article/details/gtvqadqzug.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.redwolf501.top/Article/details/gtpqiirtly.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ivvv.top/Article/details/gtufrbyeag.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ehwqpu.com/Article/details/gteluyfwkj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gtmhrnfzcn.html

Go:   name := "Alex"; age := 20
来源：http://dali.meibo888.top/Article/details/gtnhucnblt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yangfankeji.com/Article/details/gtwnbnjpjz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtchpkgzlv.html

[A03] 常量定义
来源：http://dali.316326.xyz/Article/details/gtjmdsijwc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gtegfbbflf.html

PHP:  const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtzakzeerd.html

JS:   const PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeiitmic.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtfvqyjfax.html

Java: static final double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtttflmcok.html

Go:   const PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtrcptwplj.html

Ruby: PI = 3.14159
来源：http://dali.9152youxi.cn/Article/details/gtrngfwxsg.html

C#:   const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtnjqwvsoz.html

[A04] 判断变量类型
来源：http://dali.smart0.xyz/Article/details/gtvwexzfrs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuxming.cn/Article/details/gthykxytsz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dianchejie.cn/Article/details/gtzhkzhwml.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yvedp.cn/Article/details/gtttgtiraz.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtdhftasil.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.kuanghao11.cn/Article/details/gtstwkgiui.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hongshengwenyu.top/Article/details/gtdimkhblo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shuidangran.top/Article/details/gtpfcuarno.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gtvjbeeqou.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gtkwwsmpah.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhixingplan.top/Article/details/gtnlklgchw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtwbcwhohe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtpqoajavy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtltshnnvo.html

Java: 7 / 2; 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtraxpqmbb.html

Go:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtpqrjxcmw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtpyyecdwq.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtavzbflnx.html

[A06] 字符串转数字
来源：http://dali.yj202588.top/Article/details/gtrohlfnta.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtntusigyv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gthvrfekzz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtidbhoifr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gtcniaevxg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gtyqishxgw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gtzzdfltuk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yueranfly.top/Article/details/gtdiwrwlxn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtapsrzpav.html

[A07] 数字转字符串
来源：http://dali.zhongyouzk.top/Article/details/gtsbjbowju.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gthdilhetg.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzakimqg.html

JS:   String(42); (42).toString()
来源：http://dali.svipenyu.cn/Article/details/gtpnbvzgrz.html

TS:   String(42)
来源：http://dali.jqgfzy.top/Article/details/gtdaelmrif.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gtrvydotor.html

Go:   strconv.Itoa(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtabjcyodz.html

Ruby: 42.to_s
来源：http://dali.sweek.top/Article/details/gtjucpctge.html

C#:   42.ToString()
来源：http://dali.sufxvd.cn/Article/details/gtiippfwav.html

[A08] 取整与四舍五入
来源：http://dali.fengsongda.top/Article/details/gtajfntncz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtxeelcxhb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fengsongda.top/Article/details/gtljkkeeyp.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gtyesebpla.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hongshengwenyu.top/Article/details/gtfvegxwhu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtrhkhtuxe.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gtczcitvht.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcuzpkki.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtixfednme.html

[A09] 绝对值与最大最小值
来源：http://dali.ydzc1.top/Article/details/gtrdcrmbnl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtkkezukte.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtnwoweufb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtzkzsvsfp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtetgdrxeg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gttiqxhwbk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ehwqpu.com/Article/details/gtyhxgurbd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.pycfn.com/Article/details/gtzjcfgirm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gtiymkorib.html

[A10] 生成随机数
来源：http://dali.zhoulong.xyz/Article/details/gtxgudtmwi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinqigufen.top/Article/details/gtspiwtzuq.html

PHP:  random_int(1, 100);
来源：http://dali.redwolf501.top/Article/details/gtvcrswbvg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtqvnwljbz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gtoihgrvqo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtjieexgxe.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hongshengwenyu.top/Article/details/gtnrqxfjsb.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gteoignsaf.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gtkphqtdqf.html

[A11] 条件表达式（三元）
来源：http://dali.svipenyu.cn/Article/details/gtnbbatsss.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtvgutkxva.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gtriiffgun.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynvhzpkz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwvvhabl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gturcmaogd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.bjfxy.top/Article/details/gtykywynmf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtcnnfktqn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtlcfdcmxu.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gtogtxyfao.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenzaomai.com/Article/details/gtgefnbbfv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gtcihpwszj.html

JS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtewhfgwqb.html

TS:   `Hello, ${name}!`
来源：http://dali.ivvv.top/Article/details/gthvgkfylt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258888.top/Article/details/gtjhtcxfys.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaqrppfas.html

Ruby: "Hello, #{name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gtlccprtyc.html

C#:   $"Hello, {name}!"
来源：http://dali.cqqwz.cn/Article/details/gtnzbkqgcj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.wangshuangyany.cn/Article/details/gtdtqtbunp.html

Py:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtpeqheven.html

PHP:  "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtjhkhkpin.html

JS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtrnpjojde.html

TS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtyodrnfsq.html

Java: "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtndflvaio.html

Go:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtzxhqmzcw.html

Ruby: "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtvtftiqgs.html

C#:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtpmwcvldm.html

[A14] 注释写法
来源：http://dali.jiagoushi.top/Article/details/gtmymlxgtz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yueranfly.top/Article/details/gtivalpxlx.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtklqbbdnk.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtdhygnuqj.html

TS:   // 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtvgbdctco.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gogol.net.cn/Article/details/gthglslrle.html

Go:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtkzoczfgu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gtgkllqurn.html

C#:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtydvrhauo.html

[A15] 空值判断与默认值
来源：http://dali.quarkkingdee.top/Article/details/gtlxvaylzl.html

Py:   value = data or "默认值"
来源：http://dali.guowangkeji.top/Article/details/gtkmtjrfia.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwjdzhfn.html

JS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtggqmtuhf.html

TS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtfzijhdkl.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gtqavxocoh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yangfankeji.com/Article/details/gtqurrfosd.html

Ruby: value = data || "默认值"
来源：http://dali.zhixingplan.top/Article/details/gtmbdlomai.html

C#:   var value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtltyrqrxy.html

[A16] 真假值判断规则
来源：http://dali.jinghuilouyu.cn/Article/details/gtvstgvpdn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gtjspnqcgp.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinghuilouyu.cn/Article/details/gtmegurlts.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gaohongyu789.top/Article/details/gttwnmyxgr.html

TS:   if (!x) {}
来源：http://dali.shuidangran.top/Article/details/gtnwfnbqzz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgfzy.top/Article/details/gtvcvdqmul.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.daxiang520.top/Article/details/gtlzqylxba.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ppjwa.cn/Article/details/gtyworuhsm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtibafeexa.html

[A17] 位运算
来源：http://dali.zycfv.cn/Article/details/gtludekjxr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtlhfrnagq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj202588.top/Article/details/gtymktfoef.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmdmfozx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtcamfbmex.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtmhqwxnig.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtujkgvnns.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtzxwewcuj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtcmxsvcle.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cqqwz.cn/Article/details/gtnhqrjhfh.html

Py:   ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gtcauomqgs.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gtpyfwjrcd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.iojbl.cn/Article/details/gtdlxumtbw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gtyehrrowv.html

Java: (int) 'A'; (char) 65
来源：http://dali.aibaodan.cn/Article/details/gtgkoklcui.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtlypkifdi.html

Ruby: "A".ord; 65.chr
来源：http://dali.sufxvd.cn/Article/details/gtrkgyviwu.html


<!-- 参考信息 -->