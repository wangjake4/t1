代发 wailian999

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gt2tsrejihq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gt2yegjglfk.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gt2sszvhaue.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gt2oteboubn.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2jzgnjnlx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bghynpus.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gt2jseittxr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.mhx1999.top/Article/details/gt2satycesm.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gt2fdruawae.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yanxiufei.cn/Article/details/gt2tsrktwmn.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gt2poshamyr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sxryk.cn/Article/details/gt2obwzsatk.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2folxjnkx.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gt2pdgrymgx.html

[U112] JS：字符串补位
来源：http://dali.shuidangran.top/Article/details/gt2cjqvupjg.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2donrizqg.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gt2tlszdoch.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2nphpqyqx.html

[U114] JS：JSON 深比较
来源：http://dali.yuxming.cn/Article/details/gt2anssxbzd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gt2bateauks.html

[U115] JS：生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2rtggxags.html

crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2stbarhtu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.snrcjt.cn/Article/details/gt2pkymepxe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gt2wvlplcaq.html

[U117] JS：单元测试
来源：http://dali.jiagoushi.top/Article/details/gt2sperdapq.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gt2chhglqpw.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gt2wxkxycbo.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gt2ukndfhdc.html

[U119] JS：生产构建
来源：http://dali.yj202588.top/Article/details/gt2fmgoagrq.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gt2fjiuexbd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.haohaochexian.top/Article/details/gt2otmhxqcr.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gt2pobmwrjy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2wcrqzazx.html

统计汇总
来源：http://dali.zdqjudy.top/Article/details/gt2sbtdgioo.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hlnlikxl.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzochvqs.html

Python ......... 252
来源：http://dali.xylfe.cn/Article/details/gt2qdseaawi.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gt2swmecayi.html

JavaScript ..... 252
来源：http://dali.yonumen.top/Article/details/gt2owiaxqyp.html

TypeScript ..... 212
来源：http://dali.yongpay.top/Article/details/gt2bckodima.html

Java ........... 212
来源：http://dali.xylfe.cn/Article/details/gt2dfshrwxi.html

Go ............. 212
来源：http://dali.zhiwuduotai.top/Article/details/gt2katvppha.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2syntkeuf.html

C# ............. 212
来源：http://dali.xuanzx.com/Article/details/gt2javajfbq.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gt2mupevgca.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gt2ozjtfctk.html

SQL ............ 90
来源：http://dali.zhengqikj.top/Article/details/gt2mmuftrpo.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gt2lxpymyuw.html

Kotlin ......... 15
来源：http://dali.pycfn.com/Article/details/gt2iypktiam.html

Swift .......... 15
来源：http://dali.yuanzhike.top/Article/details/gt2uzdduvdx.html

Lua ............ 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2chtxbhwz.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2ejpotwyp.html

Scala .......... 10
来源：http://dali.yvedp.cn/Article/details/gt2vhpgtjvr.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2ffobefll.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gt2ofrhumqv.html

按章节统计：
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnjiquik.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gt2pdwxqefr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gt2ibpbwyaz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2kvntyodw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gt2urzgxyax.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinqigfzy.top/Article/details/gt2cyaqbjkf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gt2yoprayow.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2cpunavaa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gt2bqowoqyl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gt2srlxzvmk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2jxieakto.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gt2vcefmfqy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2pdxgxzpi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfbgzgq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubjgamjy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tanke756.top/Article/details/gt2dastqrlf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2vtlwpppt.html

Q SQL 专题                              90
来源：http://dali.guowangkeji.top/Article/details/gt2umnhznod.html

R Bash 专题                             80
来源：http://dali.quarkkingdee.top/Article/details/gt2zzdcjcdd.html

S C / C++ 专题                          60
来源：http://dali.pengpengdd.cyou/Article/details/gt2yeneahwd.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsgokujn.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gt2ztrjvrqp.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gt2yjqxwuki.html

合计                                  2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2rbfvwkim.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gt2coibrrdw.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gt2gywhldaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2iunpkois.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ydzc1.top/Article/details/gt2ofetcppd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jiagoushi.top/Article/details/gt2zfzvnwdu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.quarkkingdee.top/Article/details/gt2aqavgdmj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cypqmicu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yueranfly.top/Article/details/gt2qtcnrhdb.html

—— 文件结束 ——
来源：http://dali.yonumen.top/Article/details/gt2xczboljv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2hcthcylb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shangyingyoupin.top/Article/details/gt2uirpujdf.html

Common Programming Examples Cheat Book
来源：http://dali.pycfn.com/Article/details/gt2etasusvs.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2leveeejy.html

【收录内容】
来源：http://dali.daxiang520.top/Article/details/gt2wdpupwru.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gt2kqntbmiw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gt2xijrfhhp.html

SQL · Bash · C · C++
来源：http://dali.sweek.top/Article/details/gt2orvmwdth.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.mhx1999.top/Article/details/gt2bcalnoyj.html

【使用说明】
来源：http://dali.xinyue.icu/Article/details/gt2ooslrovw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xziqi.cn/Article/details/gt2kqulipww.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gt2uzyilezt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgufenzy.top/Article/details/gt2llebpyxd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhixingplan.top/Article/details/gt2dzqrkteh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gt2uwgrdwni.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gt2lftclfau.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gt2vkaomdyw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gt2thboykrj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sxryk.cn/Article/details/gt2uyipctxp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.haohaochexian.top/Article/details/gt2ccfuzuma.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xziqi.cn/Article/details/gt2vbxovufz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ppjwa.cn/Article/details/gt2mwyugarx.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snazerzh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gt2egmzwqnm.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2pnvhevne.html

目  录
来源：http://dali.chenzaomai.com/Article/details/gt2qjlkktug.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2rolsmqfc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gt2ixvnckfe.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gt2osblgvys.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gt2nwychino.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhixingplan.top/Article/details/gt2ljueuyur.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.daxiang520.top/Article/details/gt2fdqyqrtb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xziqi.cn/Article/details/gt2eisdszrm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gt2ythjraex.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2urhpijjt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gt2vcudsuhn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gt2vuzkkzxj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gt2ysmravwh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2ztotnsdi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gt2coymtcik.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daxiang520.top/Article/details/gt2hwwjoxba.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlxonoll.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tkumaxsg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.pycfn.com/Article/details/gt2inhxvnqk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gt2afbsgedd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.meibo888.top/Article/details/gt2ddiofcbc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.c1oappe.top/Article/details/gt2ezlrctlt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gt2ealfkgjp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2ybiipwus.html

A. 基础语法与类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmukdyih.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2kyjljiah.html

[A01] Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2zhbznxcb.html

Py:   print("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gt2jtoqrusa.html

PHP:  echo "Hello, World!";
来源：http://dali.tian-w.cn/Article/details/gt2suxecwbp.html

JS:   console.log("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gt2jeptteyl.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhikbxvu.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gt2hzczynka.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gt2rqmmlxbf.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gt2sdidlrcl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2fghctsex.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gt2yuylxmpg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gt2uliwjznk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gt2vkhxapbi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gt2glugvtdl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhengqikj.top/Article/details/gt2esgzurap.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgypquln.html

Go:   name := "Alex"; age := 20
来源：http://dali.aizwys.cn/Article/details/gt2djzjszwf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuanzhike.top/Article/details/gt2jetxzcjo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2djernbfi.html

[A03] 常量定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2djdrdpaz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gt2xdycssrt.html

PHP:  const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2fbprvzhk.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gt2eevbdvug.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2pxftxciv.html

Java: static final double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2xhwkkpds.html

Go:   const PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gt2cculrque.html

Ruby: PI = 3.14159
来源：http://dali.yangfankeji.com/Article/details/gt2wnzckeqf.html

C#:   const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2zpyclsif.html

[A04] 判断变量类型
来源：http://dali.316326.xyz/Article/details/gt2iyzwqicg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xylfe.cn/Article/details/gt2tckfiwxs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hysaishi.cn/Article/details/gt2dcbzosah.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xuetiantiany.cn/Article/details/gt2hblaahql.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxinkj.top/Article/details/gt2sosdtott.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gt2cplaftaa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhongyouzk.top/Article/details/gt2aylohtag.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmatrsbj.html

C#:   x.GetType().Name; x is int
来源：http://dali.pycfn.com/Article/details/gt2omeicyit.html

[A05] 整数除法与取模
来源：http://dali.yanxiufei.cn/Article/details/gt2iohugqsy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.c1oappe.top/Article/details/gt2jlhoipkd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2oftrwktc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndegisbg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2bawovuoq.html

Java: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2riojkeql.html

Go:   7 / 2; 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ogditfpj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2qgexkbyc.html

C#:   7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gt2trzvfucd.html

[A06] 字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2jabxxtqf.html

Py:   int("42"); float("3.14")
来源：http://dali.dianchejie.cn/Article/details/gt2nzrpsyyp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.sweek.top/Article/details/gt2vdaiiedz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gt2ctfrmguw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nukhimpt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yangfankeji.com/Article/details/gt2xriuxedb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhrxinrx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daria6918.cn/Article/details/gt2kyqxuorw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gt2hxeylauw.html

[A07] 数字转字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2tnrsygex.html

Py:   str(42)
来源：http://dali.jinqigfzy.top/Article/details/gt2zvaqodml.html

PHP:  (string) 42; strval(42)
来源：http://dali.0kj1m.cn/Article/details/gt2rhkspfli.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2zfngnuus.html

TS:   String(42)
来源：http://dali.yanxiufei.cn/Article/details/gt2vezbxkco.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.birdmap.top/Article/details/gt2nobsgcpq.html

Go:   strconv.Itoa(42)
来源：http://dali.hnxiangtu.top/Article/details/gt2flbnzcjg.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gt2xstxehgb.html

C#:   42.ToString()
来源：http://dali.0kj1m.cn/Article/details/gt2exeuiekq.html

[A08] 取整与四舍五入
来源：http://dali.svipenyu.cn/Article/details/gt2ixbevmjj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gt2gudswglp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuxming.cn/Article/details/gt2fydrcjpc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gt2oadeuqtp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yvedp.cn/Article/details/gt2dnsimfub.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gt2dgtasqmj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gt2uezeyjcc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guannengcc.top/Article/details/gt2nlrvbqcy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2dbewbpzw.html

[A09] 绝对值与最大最小值
来源：http://dali.yueranfly.top/Article/details/gt2tiqdbish.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2awooilwl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqahbnqc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2owbtqbun.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2uvvksvvu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2hgxpagfo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnqzz.top/Article/details/gt2rccptbfa.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yangfankeji.com/Article/details/gt2kvizqrzn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2lhhzrauv.html

[A10] 生成随机数
来源：http://dali.nanxinkj.top/Article/details/gt2unqdrlij.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhongyouzk.top/Article/details/gt2wpysqzok.html

PHP:  random_int(1, 100);
来源：http://dali.birdmap.top/Article/details/gt2xudoopvq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2dpbzyeza.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvmmffgm.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkhwksc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhoulong.xyz/Article/details/gt2ohxdljts.html

Ruby: rand(1..100)
来源：http://dali.yj20258.top/Article/details/gt2mbguqunk.html

C#:   new Random().Next(1, 101)
来源：http://dali.dashuyun.cn/Article/details/gt2xqvmuerb.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gt2fidjjtqx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.wangdashe.top/Article/details/gt2whdbntpn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbpesbgq.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2tmguxtye.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2uetkkrew.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gt2nxlzfgrq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.snrcjt.cn/Article/details/gt2xapbgdlj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gt2bbqdpyax.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gt2ndnjymdp.html

[A12] 字符串插值 / 格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2dxmqzkdv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jiagoushi.top/Article/details/gt2qigcvsky.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gt2zjbfvkmm.html

JS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gt2gvhjixkf.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gt2jvmqjmjd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.iojbl.cn/Article/details/gt2fmjlrito.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2yynfhnun.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gt2dkzyugpx.html

C#:   $"Hello, {name}!"
来源：http://dali.sufxvd.cn/Article/details/gt2woucymcw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.0kj1m.cn/Article/details/gt2xhvjmdyb.html

Py:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gt2ocewbzed.html

PHP:  "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2ykpokrlo.html

JS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2uumiojlb.html

TS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2mgxaxlok.html

Java: "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrpnymfm.html

Go:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2gikmgior.html

Ruby: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2phibslsc.html

C#:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2jcilqawt.html

[A14] 注释写法
来源：http://dali.bjfxy.top/Article/details/gt2zhxqxraf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.birdmap.top/Article/details/gt2cxxglxrw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gt2xbcxxmeh.html

JS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gt2csslshrs.html

TS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2fvfwxtuk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yj202588.top/Article/details/gt2opzsvvgc.html

Go:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2gvbnuyvq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jiagoushi.top/Article/details/gt2sdghqwjj.html

C#:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gt2mbrlrjtq.html

[A15] 空值判断与默认值
来源：http://dali.dianchejie.cn/Article/details/gt2guawhria.html

Py:   value = data or "默认值"
来源：http://dali.ybcxt.top/Article/details/gt2gzcizjrp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.snrcjt.cn/Article/details/gt2prilvmdm.html

JS:   const value = data ?? "默认值";
来源：http://dali.tian-w.cn/Article/details/gt2rzwsolqh.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqmrwhkn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangshuangyany.cn/Article/details/gt2iagrvhdj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nwbrower.top/Article/details/gt2ucpdyfxr.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gt2tarwwyjq.html

C#:   var value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gt2ndircfyn.html

[A16] 真假值判断规则
来源：http://dali.hywenlv.cn/Article/details/gt2hqqlxwsd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.c1oappe.top/Article/details/gt2wzizamtz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hfpthk.cn/Article/details/gt2rsugtilc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gt2yunrfdbe.html

TS:   if (!x) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iyjstngt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fzhhl.top/Article/details/gt2xkeunxwc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuanzhike.top/Article/details/gt2uqlnaxlb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tianlin.xyz/Article/details/gt2xiqxmoen.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ijflhivl.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gt2fluvflyz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2fqcuzudw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2labcihyp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2mansgocs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2plhjglnd.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2lzqcrkwj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gt2jcfzuwnd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2uhagcpmi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlgdbbfl.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2musemfpw.html

Py:   ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gt2kgnqubjp.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhongyouzk.top/Article/details/gt2dqnejcbc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2boggarey.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jianghu66.top/Article/details/gt2jycocrzy.html

Java: (int) 'A'; (char) 65
来源：http://dali.haohaochexian.top/Article/details/gt2jntymggx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cdnleiting.top/Article/details/gt2cdvhaqsc.html

Ruby: "A".ord; 65.chr
来源：http://dali.xylfe.cn/Article/details/gt2uhkfajdx.html


<!-- 参考信息 -->