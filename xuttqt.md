代发 wailian999

[U105] JS：节流
来源：http://dali.ydzc1.top/Article/details/gt2wtqorvqr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenzaomai.com/Article/details/gt2osrepzni.html

[U106] JS：日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2kfsvpekf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gt2uiazxvph.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2fhtrzxlj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2gxdkpdcj.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gt2kfwfppaj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gt2tpswmqpq.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2btnxxfuc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gt2ukghjcos.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gt2utassdty.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cqqwz.cn/Article/details/gt2avdxpeap.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gt2nnporviw.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gt2kehpncja.html

[U112] JS：字符串补位
来源：http://dali.ehwqpu.com/Article/details/gt2xwynttat.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2yvfogsir.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gt2edfqcujj.html

s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2fihhexpg.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gt2ejrfojeb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gt2qaktvjrm.html

[U115] JS：生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2ekkgerhr.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2nnudhmto.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gt2wxxebped.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gt2muayvvzv.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2lglkwioc.html

npm i -D vitest;  npx vitest
来源：http://dali.dashuyun.cn/Article/details/gt2oezuakix.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gt2wcamhizi.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gt2txzdxvdb.html

[U119] JS：生产构建
来源：http://dali.nanxinkj.top/Article/details/gt2cbfjvyfg.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gt2ervvifvr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gt2tfbzhmvr.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gt2rjguhlug.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jcdatomo.html

统计汇总
来源：http://dali.haohaochexian.top/Article/details/gt2szelojdh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2csjychek.html

按语言统计（条）：
来源：http://dali.zhoulong.xyz/Article/details/gt2wfusjmqt.html

Python ......... 252
来源：http://dali.xinyue.icu/Article/details/gt2dsbjcjse.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gt2cldyrlmh.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gt2sgbfikhw.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gt2sxsxvxpx.html

Java ........... 212
来源：http://dali.yongpay.top/Article/details/gt2tbxvbbto.html

Go ............. 212
来源：http://dali.yongpay.top/Article/details/gt2elyurjjj.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gt2gyicytyk.html

C# ............. 212
来源：http://dali.c1oappe.top/Article/details/gt2sxrftfai.html

C .............. 30
来源：http://dali.tianlin.xyz/Article/details/gt2tglmbcbh.html

C++ ............ 30
来源：http://dali.shuidangran.top/Article/details/gt2oifkchbf.html

SQL ............ 90
来源：http://dali.redwolf501.top/Article/details/gt2ytjtwygy.html

Bash ........... 80
来源：http://dali.xinyue.icu/Article/details/gt2ffkuviwd.html

Kotlin ......... 15
来源：http://dali.316326.xyz/Article/details/gt2rpradjae.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gt2gjbimjqb.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gt2thbrsxht.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gt2flzjyrin.html

Scala .......... 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2myragxjv.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2emgosomy.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gt2yeppdujj.html

按章节统计：
来源：http://dali.pycfn.com/Article/details/gt2spkjmsdh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gt2slgatnmc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gt2qzzbveuh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gt2wugmgooo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pengpengdd.cyou/Article/details/gt2whfoboss.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gt2hyvtdeeg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cheryme.top/Article/details/gt2xtgnsdfd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gt2rqfbinlc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gt2aqatlndr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2zrynwcph.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.feifeiyinyue.top/Article/details/gt2owscjlns.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2qsgydzvq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gt2ckdrhbxo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssvfgfkc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gt2elauzxmv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gt2etazfhxq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2sysoqeyn.html

Q SQL 专题                              90
来源：http://dali.guannengcc.top/Article/details/gt2fjpssamr.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gt2sgudmvxu.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gt2xvpedsje.html

T 其他语言补充                          60
来源：http://dali.snrcjt.cn/Article/details/gt2kdvnzbxg.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gt2ksovhfti.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2llqrtrir.html

合计                                  2106 条
来源：http://dali.hnxiangtu.top/Article/details/gt2jpxffqdt.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2igyvxecc.html

使用提醒
来源：http://dali.yuxming.cn/Article/details/gt2ekpmowmx.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gt2hznoprah.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gt2oasoagjz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.chenlongwang.top/Article/details/gt2cweagano.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuanzx.com/Article/details/gt2xuuuikqz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhengqikj.top/Article/details/gt2jdireejr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gt2vstuwrvy.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gt2mtgbqptp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2boshrwnv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.haohaochexian.top/Article/details/gt2wcdradpr.html

Common Programming Examples Cheat Book
来源：http://dali.yueranfly.top/Article/details/gt2shxgfcqj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2poivwlst.html

【收录内容】
来源：http://dali.meibo888.top/Article/details/gt2yprqwlte.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gt2gmmsodez.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gogol.net.cn/Article/details/gt2fpygwlkr.html

SQL · Bash · C · C++
来源：http://dali.zhixingplan.top/Article/details/gt2jmtkfnfk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgjdmhmk.html

【使用说明】
来源：http://dali.jinqigufen.top/Article/details/gt2cpqbsvob.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jlsjyb.cn/Article/details/gt2azgjbdqv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gt2oeemfwyz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shzxlz.cn/Article/details/gt2nzekskja.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gt2qaqimzaf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hywenlv.cn/Article/details/gt2fwaduzlo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj202588.top/Article/details/gt2qekftolr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gt2bwjcvhji.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cdnleiting.top/Article/details/gt2zyecrwts.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yueranfly.top/Article/details/gt2xdypkkre.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hammf.cn/Article/details/gt2oytkekjx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jqgfzy.top/Article/details/gt2ssjxuhfh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pengpengdd.cyou/Article/details/gt2uaogydlw.html

【文件统计】
来源：http://dali.shzxlz.cn/Article/details/gt2kdapmewe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258888.top/Article/details/gt2ldkqqcgb.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2xokyakig.html

目  录
来源：http://dali.feifeiyinyue.top/Article/details/gt2zodhqhcw.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gt2zcfhurcb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gt2pwpakotp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gt2zdojrsol.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gt2ucbdpqcy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2rulfyutr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yltdsabo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zycfv.cn/Article/details/gt2lxnmajjg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gt2qzbbtqzv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ybcxt.top/Article/details/gt2gndizrnn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2eypggspx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gt2cvghghak.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsdbumcw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2emjonuxw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfzpcexy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gt2hqxsoufy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.bjfxy.top/Article/details/gt2djbymcim.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2rysyjtqd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.0kj1m.cn/Article/details/gt2wcesexot.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shuidangran.top/Article/details/gt2npvsozkr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.birdmap.top/Article/details/gt2jzrouboa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gt2ujwnavwa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2cohdbfww.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2psvkwfgm.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gt2jtkuivtc.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2lescoplo.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2gcptfjpo.html

Py:   print("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gt2tgbeqftd.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gt2mfpxpahm.html

JS:   console.log("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gt2tvdmvpyg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2xsyzotmz.html

Java: System.out.println("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2mtkogxjx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2opfqcnul.html

Ruby: puts "Hello, World!"
来源：http://dali.jqgufenzy.top/Article/details/gt2aedpteyj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eistizax.html

[A02] 变量声明与赋值
来源：http://dali.nanxuanxn.top/Article/details/gt2tyvgkdyv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agyjnfut.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tojpdapl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2qlixjpxi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzzrprlg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2hbzxffsc.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gt2azgehisq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqahvjwr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkqrbzvl.html

[A03] 常量定义
来源：http://dali.nanxuanxn.top/Article/details/gt2taxfknma.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.sufxvd.cn/Article/details/gt2qciketcf.html

PHP:  const PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2ysbddwht.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2dnhlxasm.html

TS:   const PI: number = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2ywdqefgq.html

Java: static final double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gt2rvxxinnt.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gt2lusqvezl.html

Ruby: PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gt2ooiamvoz.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2exkyfagf.html

[A04] 判断变量类型
来源：http://dali.zycfv.cn/Article/details/gt2mbuhizkn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nwbrower.top/Article/details/gt2akabfbtj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jianghu66.top/Article/details/gt2uobzmdeb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmsugdet.html

TS:   typeof x; x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gt2rylysvkp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yvedp.cn/Article/details/gt2ylrnpyfx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gt2cisfyanb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gogol.net.cn/Article/details/gt2szjlfgmg.html

C#:   x.GetType().Name; x is int
来源：http://dali.yuxming.cn/Article/details/gt2pwscuiyd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrdbpqq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.svipenyu.cn/Article/details/gt2tqkpcrks.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqmzkwah.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gt2repqncum.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2yqsiuuay.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2wczknrbu.html

Go:   7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2ofdflgzt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gt2guzhmckt.html

C#:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2cmkwbzkq.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2jfoiwyhq.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxinkj.top/Article/details/gt2kmqfhwpc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.daxiang520.top/Article/details/gt2udyezqny.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gt2dwiaipqa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinqigufen.top/Article/details/gt2jblzqvek.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gt2qmddewef.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yueranfly.top/Article/details/gt2qvkicqwu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guannengcc.top/Article/details/gt2cyjwefvw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gt2xmxyghtz.html

[A07] 数字转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2ixpzjpiv.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qflhvcuv.html

PHP:  (string) 42; strval(42)
来源：http://dali.xylfe.cn/Article/details/gt2olfcscna.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gt2zxrksylw.html

TS:   String(42)
来源：http://dali.andypj.xyz/Article/details/gt2ikdpzsrx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tian-w.cn/Article/details/gt2kjcjemwf.html

Go:   strconv.Itoa(42)
来源：http://dali.svipenyu.cn/Article/details/gt2rjwiahkh.html

Ruby: 42.to_s
来源：http://dali.quarkkingdee.top/Article/details/gt2hugqhxwk.html

C#:   42.ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzonlloe.html

[A08] 取整与四舍五入
来源：http://dali.dianchejie.cn/Article/details/gt2ldwkneif.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gt2hxlocdqo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gt2hseveamv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2kgtvjuqf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.wangdashe.top/Article/details/gt2kcyuxxiz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2aryybwmq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gt2nnlpjgqb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuxming.cn/Article/details/gt2taqdutst.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2eihycxzf.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gt2faqlzkqh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gt2etvyixmi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2blzwegqa.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtycmlzq.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2dqcxssiq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2naqyzfaj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sufxvd.cn/Article/details/gt2gjvjibjd.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gt2pdsrkmyp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cashguo.top/Article/details/gt2mhwuwost.html

[A10] 生成随机数
来源：http://dali.ppjwa.cn/Article/details/gt2liacinkn.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jyoumei.cn/Article/details/gt2jofxgzii.html

PHP:  random_int(1, 100);
来源：http://dali.svipenyu.cn/Article/details/gt2qlrgcixt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2huxzpikj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2avbjhqng.html

Java: new Random().nextInt(100) + 1
来源：http://dali.bjfxy.top/Article/details/gt2qnwycoat.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.316326.xyz/Article/details/gt2mvjnjndv.html

Ruby: rand(1..100)
来源：http://dali.yj202588.top/Article/details/gt2zkijczag.html

C#:   new Random().Next(1, 101)
来源：http://dali.guowangkeji.top/Article/details/gt2qqdekdfl.html

[A11] 条件表达式（三元）
来源：http://dali.birdmap.top/Article/details/gt2hjaevllk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gt2zbjrlttg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gt2zkgooxan.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxczpitx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gt2mfwuxbif.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2fallovyi.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.c1oappe.top/Article/details/gt2atypncgp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2kssiqzxs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gt2zozayknd.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigufen.top/Article/details/gt2zbzxyakf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.birdmap.top/Article/details/gt2zfdvrtmn.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daxiang520.top/Article/details/gt2wvfxagkj.html

JS:   `Hello, ${name}!`
来源：http://dali.shuidangran.top/Article/details/gt2qbizxelv.html

TS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gt2gldjlqcw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yvedp.cn/Article/details/gt2rlqekclj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dashuyun.cn/Article/details/gt2njcptjfl.html

Ruby: "Hello, #{name}!"
来源：http://dali.ybcxt.top/Article/details/gt2imnetxpd.html

C#:   $"Hello, {name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmjpfyhh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gt2rglibvep.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2nbihaxjr.html

PHP:  "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2ggdsmrja.html

JS:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2izorvqgu.html

TS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2qoepwnbm.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2xjzmmqrb.html

Go:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2zakoqxno.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2btbaidzo.html

C#:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2sfgjbaym.html

[A14] 注释写法
来源：http://dali.jlsjyb.cn/Article/details/gt2yamoaxuh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.aizwys.cn/Article/details/gt2ooyiwuzk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2jtvmkrai.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzjamyhi.html

TS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gt2udcapdom.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxuanxn.top/Article/details/gt2dphharok.html

Go:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2cffphtax.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tianlin.xyz/Article/details/gt2pkprqljo.html

C#:   // 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gt2olkivadv.html

[A15] 空值判断与默认值
来源：http://dali.ydzc1.top/Article/details/gt2kvxbjnep.html

Py:   value = data or "默认值"
来源：http://dali.hammf.cn/Article/details/gt2vadfsjhv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2lhrwbopg.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxejbigx.html

TS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gt2dsbnjpjd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258.top/Article/details/gt2lhavnejd.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgufenzy.top/Article/details/gt2qfthscbd.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2foptmhql.html

C#:   var value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gt2mjlfeutb.html

[A16] 真假值判断规则
来源：http://dali.gogol.net.cn/Article/details/gt2aeouvojm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yuxming.cn/Article/details/gt2avinxtgy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jinqigfzy.top/Article/details/gt2sbflatrt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhengqikj.top/Article/details/gt2ieyfhril.html

TS:   if (!x) {}
来源：http://dali.smart0.xyz/Article/details/gt2myabzurv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzfajfjp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gt2jaqvmelj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gt2kjjjferb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2zbroojxl.html

[A17] 位运算
来源：http://dali.xziqi.cn/Article/details/gt2uwqpnglk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2wdszmcix.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2jlsedeon.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2aunuiajp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2tpwxigjy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gt2grmogmva.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2exakntyp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2mxrgmylj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2dofmxlal.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yangfankeji.com/Article/details/gt2octrttyf.html

Py:   ord("A"); chr(65)
来源：http://dali.fengsongda.top/Article/details/gt2gromthff.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gt2tbalwlvt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gt2sigegpxz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gt2tcaolxqe.html

Java: (int) 'A'; (char) 65
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bynjkgim.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yongpay.top/Article/details/gt2tlmytafm.html

Ruby: "A".ord; 65.chr
来源：http://dali.birdmap.top/Article/details/gt2erjoyxku.html


<!-- 参考信息 -->