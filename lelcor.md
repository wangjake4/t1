代发 wailian999

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gt2cnbjuqru.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yongpay.top/Article/details/gt2rxividbs.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gt2hvhqmmzi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cucudq.cn/Article/details/gt2uwnylwnw.html

[U107] JS：数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gt2tlvnmorh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gt2jatnbqtk.html

[U108] JS：随机整数
来源：http://dali.c1oappe.top/Article/details/gt2ujxtgzww.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gt2hbxyeacf.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gt2ynbmbmtg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2njdubagf.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2mrjugoig.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gt2rawpfjjd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2skwdjzms.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gt2jwuojlnk.html

[U112] JS：字符串补位
来源：http://dali.smart0.xyz/Article/details/gt2mucgrdos.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gt2rhlglxzi.html

[U113] JS：正则替换全部
来源：http://dali.yangfankeji.com/Article/details/gt2zmyhgwvr.html

s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2drswdoxi.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gt2ajddounh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gt2jplcmvhx.html

[U115] JS：生成 UUID
来源：http://dali.yueranfly.top/Article/details/gt2jobnesxo.html

crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gt2zsrzlanb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhongyouzk.top/Article/details/gt2buiphoaz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gt2vmolsfmu.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gt2uzckvffp.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gt2jzxgersj.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gt2vwxoould.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2gdwgewxc.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gt2qlfyjtdh.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gt2tpewxwea.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hywenlv.cn/Article/details/gt2phoqdovo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhiwuduotai.top/Article/details/gt2miggnrnw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2xrijfdao.html

统计汇总
来源：http://dali.jyoumei.cn/Article/details/gt2mdxdlrfw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2mhjziwro.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gt2kupcxcoy.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afsztpeo.html

PHP ............ 252
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwzasgqr.html

JavaScript ..... 252
来源：http://dali.guowangkeji.top/Article/details/gt2yusholbd.html

TypeScript ..... 212
来源：http://dali.jqgufenzy.top/Article/details/gt2dmpwndvr.html

Java ........... 212
来源：http://dali.shzxlz.cn/Article/details/gt2scepqzti.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2dthjotmb.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2aiettkfu.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhmfqzro.html

C .............. 30
来源：http://dali.svipenyu.cn/Article/details/gt2iqmnzmrs.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gt2jomsgnoo.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gt2lgjxjxlp.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gt2ufoxueoz.html

Kotlin ......... 15
来源：http://dali.sxryk.cn/Article/details/gt2deouzqfq.html

Swift .......... 15
来源：http://dali.cucudq.cn/Article/details/gt2ivkopdtk.html

Lua ............ 10
来源：http://dali.yj202588.top/Article/details/gt2bjplkuyh.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gt2kibdwody.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gt2roudargg.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2cahhjonb.html

合计 ........... 2106 条
来源：http://dali.mhx1999.top/Article/details/gt2sdifypfx.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gt2uayehrgw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gt2tewtatug.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2psecfeyx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2uwycoidk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gt2mkovibrx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gt2spnhdhmy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhengqikj.top/Article/details/gt2cuzyugko.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2xhenxarr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gt2jlchtint.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2ysxpgnhy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2hrglozey.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2ldsynxww.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gt2jsbgjvmb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gt2ezifgsgv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2egoexbnt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hywenlv.cn/Article/details/gt2tqtvijac.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2knesphal.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gt2mshrjtma.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gt2ghcpwjov.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2xsqgsncd.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gt2zruwqcyj.html

U 高频实用片段                         120
来源：http://dali.tanke756.top/Article/details/gt2hlcwpxyj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwcrhab.html

合计                                  2106 条
来源：http://dali.hnqzz.top/Article/details/gt2fonfpkoz.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2uoryrazu.html

使用提醒
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnhgcuwb.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2cejcvpdh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuetiantiany.cn/Article/details/gt2alqijmnx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gt2snhahzrj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tianlin.xyz/Article/details/gt2dvzejrfj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinqigufen.top/Article/details/gt2varmnhtn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hongshengwenyu.top/Article/details/gt2saacothd.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2suqiolhp.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2xymramgv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gt2libyihfe.html

Common Programming Examples Cheat Book
来源：http://dali.chenzaomai.com/Article/details/gt2hfujzhnm.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2tlzqumay.html

【收录内容】
来源：http://dali.chenlongwang.top/Article/details/gt2nmzumfrg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gt2hlecqgks.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fengsongda.top/Article/details/gt2davbfbkc.html

SQL · Bash · C · C++
来源：http://dali.chenzaomai.com/Article/details/gt2hsopwlpv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ehwqpu.com/Article/details/gt2kxcxxirh.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gt2nrcddozm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hysaishi.cn/Article/details/gt2wbnqmgij.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.9152youxi.cn/Article/details/gt2wyhkxvte.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hammf.cn/Article/details/gt2xxbgvjrd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.redwolf501.top/Article/details/gt2lxwkhbbt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gt2nzartmez.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hfpthk.cn/Article/details/gt2abxxpmnj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jlsjyb.cn/Article/details/gt2leokhbqm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cqqwz.cn/Article/details/gt2ncrhlngu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cashguo.top/Article/details/gt2mnhjfhop.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2fjcrtihf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gt2fcbrdlae.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ehwqpu.com/Article/details/gt2rkszfypt.html

【文件统计】
来源：http://dali.hywenlv.cn/Article/details/gt2gxvvkblz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenzaomai.com/Article/details/gt2vdwsjzht.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2dewtpknv.html

目  录
来源：http://dali.yueranfly.top/Article/details/gt2odnvipnu.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2tqwmvsip.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.dianchejie.cn/Article/details/gt2pxnswoxb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxzgdujy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2npqrcsmd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gt2eiaoxhsj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jianghu66.top/Article/details/gt2zrcqblwm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2gfqqdsva.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2geftxoni.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gogol.net.cn/Article/details/gt2tijiiyjf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2knlbvhzn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2reflibak.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gt2hsgdlmsr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.andypj.xyz/Article/details/gt2ooupfkzw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2nhzfvett.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gt2zzbsggtr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2ayvkqfjz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2gilirqpr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinqigufen.top/Article/details/gt2gseluzsm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2nxhqyhpq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.c1oappe.top/Article/details/gt2fllapejp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2ngavwpir.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gt2qlihowhq.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2zvsozoeb.html

A. 基础语法与类型
来源：http://dali.daxiang520.top/Article/details/gt2ksutiluf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yrdnfoki.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2quwxpfbm.html

Py:   print("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gt2przutjyl.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gt2iweqrmgt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoydacha.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.vqdsnc.cn/Article/details/gt2kngadytv.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gt2grmjbivl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gt2ppjwyzkf.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gt2brspdpnu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjkejuz.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gt2tcifusny.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daria6918.cn/Article/details/gt2xogyajnb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2selryfpo.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2skgqihsa.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.smart0.xyz/Article/details/gt2whuxrktp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gt2vphglbvh.html

Go:   name := "Alex"; age := 20
来源：http://dali.ydzc1.top/Article/details/gt2pwuixpwq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gt2ciktketg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2coyqehhc.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gt2fvbtyxcu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sxryk.cn/Article/details/gt2khclvuig.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2apjnnaua.html

JS:   const PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2gfdyyydn.html

TS:   const PI: number = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2czjobvjj.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2zfxnhvze.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gt2ygfolunf.html

Ruby: PI = 3.14159
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbgqpoyd.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2uhlwpgkw.html

[A04] 判断变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2fowobkrf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.aizwys.cn/Article/details/gt2qhnzbshy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sweek.top/Article/details/gt2hafxrelw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsqibvm.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gt2vtxgyehb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqsqdaib.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gt2duiokwgz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhixingplan.top/Article/details/gt2nylhfhoj.html

C#:   x.GetType().Name; x is int
来源：http://dali.sufxvd.cn/Article/details/gt2tqurrlla.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gt2kbvhucka.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xylfe.cn/Article/details/gt2qhjqaysv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2slueqpce.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2elroltxf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.haohaochexian.top/Article/details/gt2ebvqspgr.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gt2oddpryrx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2pkqqovzo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2fsmtljwn.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2kgjbteni.html

[A06] 字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2srnxlozt.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gt2bcwirzjw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gt2iowzjwfz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nwbrower.top/Article/details/gt2aiwjrbvz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenjidiqi.icu/Article/details/gt2utfgtglx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2fqckqpyy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cucudq.cn/Article/details/gt2metqvkek.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yj20258888.top/Article/details/gt2vglegihm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfittqxz.html

[A07] 数字转字符串
来源：http://dali.birdmap.top/Article/details/gt2raecxwij.html

Py:   str(42)
来源：http://dali.ehwqpu.com/Article/details/gt2fiujwsqv.html

PHP:  (string) 42; strval(42)
来源：http://dali.nwbrower.top/Article/details/gt2vnapsdid.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gt2avvnmuyy.html

TS:   String(42)
来源：http://dali.sufxvd.cn/Article/details/gt2tniwuojd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shzxlz.cn/Article/details/gt2ujepnnqr.html

Go:   strconv.Itoa(42)
来源：http://dali.ehwqpu.com/Article/details/gt2lpljhotp.html

Ruby: 42.to_s
来源：http://dali.yj202588.top/Article/details/gt2jhkqndhz.html

C#:   42.ToString()
来源：http://dali.gzhubu.top/Article/details/gt2tmxlidmc.html

[A08] 取整与四舍五入
来源：http://dali.shuidangran.top/Article/details/gt2xnqfpuxf.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdzgcpre.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yonumen.top/Article/details/gt2mvbiaqfa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rmdtpwze.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.c1oappe.top/Article/details/gt2fbbgctdu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idudeqsx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2bqwuxrjv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gt2aockrkpm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2dmxurtne.html

[A09] 绝对值与最大最小值
来源：http://dali.tianlin.xyz/Article/details/gt2vndwyojq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xylfe.cn/Article/details/gt2chaedfbk.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gt2wlxxpzxv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2wlgqpaec.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozupfflm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2wcbaebov.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aizwys.cn/Article/details/gt2sznyhiul.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mxjjpbmx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gt2vclbepvu.html

[A10] 生成随机数
来源：http://dali.ybcxt.top/Article/details/gt2xmeuhjnp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cheryme.top/Article/details/gt2ivfwzcet.html

PHP:  random_int(1, 100);
来源：http://dali.gzhubu.top/Article/details/gt2slyjgzmi.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cqqwz.cn/Article/details/gt2kvpjrkgh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gt2vnsbjhpm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hammf.cn/Article/details/gt2otuyveoj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yueranfly.top/Article/details/gt2soagswwv.html

Ruby: rand(1..100)
来源：http://dali.gzhubu.top/Article/details/gt2nqrteloa.html

C#:   new Random().Next(1, 101)
来源：http://dali.zycfv.cn/Article/details/gt2biuywiqx.html

[A11] 条件表达式（三元）
来源：http://dali.xuanzx.com/Article/details/gt2wpfszwbn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigufen.top/Article/details/gt2gzzrzvxy.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2tsqbfwsd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gt2emjujhpa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gt2qckmiznq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xziqi.cn/Article/details/gt2iqpadktq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xziqi.cn/Article/details/gt2lhqkxvji.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tianlin.xyz/Article/details/gt2bkjjivjc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2ektgxngl.html

[A12] 字符串插值 / 格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvpqlvie.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258888.top/Article/details/gt2kppphpcx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nwbrower.top/Article/details/gt2naawkhwi.html

JS:   `Hello, ${name}!`
来源：http://dali.zhoulong.xyz/Article/details/gt2pxsnamnu.html

TS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gt2ldmppkid.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.quarkkingdee.top/Article/details/gt2yjaaluej.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.pengpengdd.cyou/Article/details/gt2xyiobmkh.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2eomylnpi.html

C#:   $"Hello, {name}!"
来源：http://dali.ppjwa.cn/Article/details/gt2ufvgtrbq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.kuanghao11.cn/Article/details/gt2gteieioa.html

Py:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tftxyxko.html

PHP:  "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2khphaeim.html

JS:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gt2fdzhjudm.html

TS:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2xvqsoquc.html

Java: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2rtcgajjh.html

Go:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gt2qmakwtvi.html

Ruby: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2ooavhmsx.html

C#:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gt2elmgwlsr.html

[A14] 注释写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vctbywvn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ydzc1.top/Article/details/gt2jppltofe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenzaomai.com/Article/details/gt2xedgawtj.html

JS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gt2hxsjynay.html

TS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gt2qkardpoe.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hfpthk.cn/Article/details/gt2mzywvgqb.html

Go:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2buwodnkp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.redwolf501.top/Article/details/gt2xosmhxxb.html

C#:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2zskxazdo.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdetfpxx.html

Py:   value = data or "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gt2akvytmhl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gt2bglmpwxl.html

JS:   const value = data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gt2ppsysedb.html

TS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gt2uwrabubi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cqqwz.cn/Article/details/gt2epgrtxae.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.chenlongwang.top/Article/details/gt2fiyjjlll.html

Ruby: value = data || "默认值"
来源：http://dali.guowangkeji.top/Article/details/gt2nvjzmoav.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gt2pmqopfap.html

[A16] 真假值判断规则
来源：http://dali.xinyue.icu/Article/details/gt2lyhmvwig.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcthfase.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eminyrqw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gt2nphaxcvn.html

TS:   if (!x) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jjdlxbra.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.redwolf501.top/Article/details/gt2rdzstara.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhixingplan.top/Article/details/gt2tupkliuh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yonumen.top/Article/details/gt2tftdzabl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2knnoqron.html

[A17] 位运算
来源：http://dali.feifeiyinyue.top/Article/details/gt2xgpyatdi.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gt2scgwjurc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilxpxnlo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2mftgicie.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2hlzgqyeh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2mjqwyajv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2szmofnyq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2sdhtvvsm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2ugmlpmkt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gt2elrxpadt.html

Py:   ord("A"); chr(65)
来源：http://dali.gaohongyu789.top/Article/details/gt2lnncouup.html

PHP:  ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gt2djwacsqe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2lipralsx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gt2jcitydvq.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhijiandao.cn/Article/details/gt2ryutqoiu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovgsyyzv.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuetiantiany.cn/Article/details/gt2ulnzuyfw.html


<!-- 参考信息 -->