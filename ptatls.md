代发 wailian999

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gtnqfttbbg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aizwys.cn/Article/details/gtzzxyowdz.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gtwycmmbxz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gtlgqgyndj.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtbagdardq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgfzy.top/Article/details/gtlhcmkdyj.html

[U106] JS：日期格式化
来源：http://dali.gogol.net.cn/Article/details/gthlplmqwm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtixidakkn.html

[U107] JS：数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvhffnxa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtcfhcnjjs.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtmeeqxort.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cqqwz.cn/Article/details/gtxyvnnmaf.html

[U109] JS：数组分组
来源：http://dali.sysykeji.top/Article/details/gtlnkuwnza.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtaflbeofy.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gteufxkwsb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gtbxdgquqy.html

[U111] JS：对象转 Map
来源：http://dali.hammf.cn/Article/details/gtlsrrghjl.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtzgzayqrd.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtqejevznq.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtnsymceys.html

[U113] JS：正则替换全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzajiuqjn.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtzaoyydpn.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gtsjglrxfb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtvxwheqwb.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gtkrvrfyrw.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gtzggsjyjk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gthrdwsusx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtuhxtfqms.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtgwmawuuo.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtodchtlxw.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjvuraam.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtkmutkzpe.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gtwwyxllyu.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtngpdsqdz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yangfankeji.com/Article/details/gtofakvzzc.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gtgeazcgxs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyarmndib.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtvpjsndwy.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtxdrlfcxz.html

按语言统计（条）：
来源：http://dali.jlsjyb.cn/Article/details/gtvphkqiir.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtzpbdippc.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtxkvhwqqj.html

JavaScript ..... 252
来源：http://dali.mhx1999.top/Article/details/gtunqtbyyr.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtrsdeyphz.html

Java ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtyngdqxmf.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gtrcyvsbnk.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtbttbbcbf.html

C# ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtpbmsjdhb.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gtdgmkojks.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtjzgzifhn.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gtnwcazjve.html

Bash ........... 80
来源：http://dali.yj20258.top/Article/details/gtawwmgyhk.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtdrtylctm.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gtbghrdovt.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gtponhhnls.html

Perl ........... 10
来源：http://dali.daxiang520.top/Article/details/gtycirfvge.html

Scala .......... 10
来源：http://dali.aibaodan.cn/Article/details/gtshcpslla.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtfrlznjsk.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gtzcgcfpzr.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtkyfzohjp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gthfdizsjq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xylfe.cn/Article/details/gtkogshobd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtzvjljyng.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.meibo888.top/Article/details/gtqeppjeys.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gthhlqyllo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtcdhacbsq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gtbbvymjfl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gtdaxfmmms.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gttcpfequa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zdqjudy.top/Article/details/gtvttkoplj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtwllknlkk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtwywaoees.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtiuohqiug.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtbhigkkbt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gtemkdowfp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtetugoqmn.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gtbaixfygz.html

R Bash 专题                             80
来源：http://dali.hysaishi.cn/Article/details/gtmznuuqgg.html

S C / C++ 专题                          60
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdrflwxd.html

T 其他语言补充                          60
来源：http://dali.zdqjudy.top/Article/details/gtnxjhnmmj.html

U 高频实用片段                         120
来源：http://dali.sxryk.cn/Article/details/gtlurzuwou.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtvkbsaigo.html

合计                                  2106 条
来源：http://dali.haohaochexian.top/Article/details/gtidaxaudt.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtnxwpnzwn.html

使用提醒
来源：http://dali.sysykeji.top/Article/details/gtqrooswtg.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtveckqryl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gtdtdevbfu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gthnozneso.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yongpay.top/Article/details/gtgiqhuksk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hysaishi.cn/Article/details/gtowpawuui.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigufen.top/Article/details/gtxlnmtcpt.html

—— 文件结束 ——
来源：http://dali.haohaochexian.top/Article/details/gtiuulxouj.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtljoqzwor.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenzaomai.com/Article/details/gtbzrgjduo.html

Common Programming Examples Cheat Book
来源：http://dali.shuidangran.top/Article/details/gtenwoviby.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtvsjiwxqe.html

【收录内容】
来源：http://dali.zdqjudy.top/Article/details/gtdymqghip.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.chenzaomai.com/Article/details/gteusjzsqe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.dashuyun.cn/Article/details/gtsnumurnf.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gtdfhxmjtv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gtiythmzkd.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gtittzwwwb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.316326.xyz/Article/details/gtnumwrdjx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yueranfly.top/Article/details/gtwprelqir.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmtlsxdhb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.haohaochexian.top/Article/details/gtcppozsdv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xinyue.icu/Article/details/gtybogatbv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.haohaochexian.top/Article/details/gtagbernuq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gtjgifgcef.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zycfv.cn/Article/details/gtqwehlrfc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.daria6918.cn/Article/details/gtqiitycci.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.feifeiyinyue.top/Article/details/gtbadmlhjf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnxiangtu.top/Article/details/gtojckjldk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtazcprpol.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gtyavtkcaz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhoulong.xyz/Article/details/gthbgalbps.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtwnuwrceb.html

目  录
来源：http://dali.aibaodan.cn/Article/details/gtaegujgkz.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtykmosewa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtfovvuwyv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtgmszueao.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtatrgkguz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtptabehvk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtclkpgyts.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gtrsqmvezj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtslgbffwu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtpaflfqtt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtmtqrxvul.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtqsmkwvop.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtghairojc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gtxyskvbnk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gttsnwhgfo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.havefunace.top/Article/details/gtkkrnjohd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cashguo.top/Article/details/gtvziiwstm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtrhjrbwfw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.c1oappe.top/Article/details/gtgywblaco.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtvaxlrfmv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhongyouzk.top/Article/details/gtjzcckoog.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtvnbtbunq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtnlsvgnrh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtegfcutzq.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gtkayogacp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcqprbzil.html

[A01] Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtxlhtrlid.html

Py:   print("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gtircrjwcf.html

PHP:  echo "Hello, World!";
来源：http://dali.mhx1999.top/Article/details/gtijbfkign.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gtkablxbkx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gtedwybapd.html

Java: System.out.println("Hello, World!");
来源：http://dali.yonumen.top/Article/details/gttlgjljyy.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gotoacloud.top/Article/details/gteukmejsy.html

Ruby: puts "Hello, World!"
来源：http://dali.yonumen.top/Article/details/gtvftqfahu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtqdopfwui.html

[A02] 变量声明与赋值
来源：http://dali.zhoulong.xyz/Article/details/gtqcjrdwux.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cqqwz.cn/Article/details/gtifigsybc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtelxqeimv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtjgbsqtfv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtvmzqlaxh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtexujprkt.html

Go:   name := "Alex"; age := 20
来源：http://dali.mhx1999.top/Article/details/gtfiduqqyt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gthknsgmnv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtdbzxelyj.html

[A03] 常量定义
来源：http://dali.quarkkingdee.top/Article/details/gtbntmqguv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinqigfzy.top/Article/details/gtxsaatccg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gtoljtymfy.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtqgtiqvhd.html

TS:   const PI: number = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtaeyxnmag.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtxrbsshgd.html

Go:   const PI = 3.14159
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbmhvztu.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtllvhuamu.html

C#:   const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtozrykscj.html

[A04] 判断变量类型
来源：http://dali.hnqzz.top/Article/details/gtjclxpkuq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj202588.top/Article/details/gtymjrexrj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cashguo.top/Article/details/gtpclitoyf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtvhaicmlb.html

TS:   typeof x; x instanceof Date
来源：http://dali.haohaochexian.top/Article/details/gtnowkllwa.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fengsongda.top/Article/details/gtpaedcezd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhiwuduotai.top/Article/details/gtwwedishn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuanzhike.top/Article/details/gtltskndwg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgppbptz.html

[A05] 整数除法与取模
来源：http://dali.shangyingyoupin.top/Article/details/gthbqnnhjk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daria6918.cn/Article/details/gtkwqfjpnc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gthknjnwpm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtrqxfpmsz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtrzyanepr.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtsvrtbdmo.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtottmerbz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtutabkxdg.html

C#:   7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtyixrarqf.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrxsbbhu.html

Py:   int("42"); float("3.14")
来源：http://dali.jiagoushi.top/Article/details/gtrylqpibh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gtqvlzahuz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtnodlkymc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yueranfly.top/Article/details/gtsziisqgh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtvqhqzbyn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hammf.cn/Article/details/gtekyexeef.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jiagoushi.top/Article/details/gtwwvrkerm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ydzc1.top/Article/details/gtkcrupfuq.html

[A07] 数字转字符串
来源：http://dali.vqdsnc.cn/Article/details/gtdxiqbkwk.html

Py:   str(42)
来源：http://dali.ivvv.top/Article/details/gtfpptqfdd.html

PHP:  (string) 42; strval(42)
来源：http://dali.ivvv.top/Article/details/gtzuwoyibo.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gtadztprvs.html

TS:   String(42)
来源：http://dali.9152youxi.cn/Article/details/gtlxgezece.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shuidangran.top/Article/details/gtjbvxgzvp.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gtzoaaenbe.html

Ruby: 42.to_s
来源：http://dali.gotoacloud.top/Article/details/gtdvdegzoq.html

C#:   42.ToString()
来源：http://dali.yuxming.cn/Article/details/gtqqxrsftw.html

[A08] 取整与四舍五入
来源：http://dali.pengpengdd.cyou/Article/details/gtgvyykenv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtvujorgkt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.vqdsnc.cn/Article/details/gtevyzdiso.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtejscxbub.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.316326.xyz/Article/details/gtwxabekbs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtqbxnziwn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gtvbmiagan.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gotoacloud.top/Article/details/gtvgiwtpzh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gtjwduzirs.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258.top/Article/details/gtirfdotst.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbetgjwg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gthimlqwoy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtcdswtkhf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gteacbopsm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtynxpkufv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hnqzz.top/Article/details/gtqzynnfzc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cheryme.top/Article/details/gtuwunlwny.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtdsiewqyk.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gtrkzonhqc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nanxuanxn.top/Article/details/gttynpikbc.html

PHP:  random_int(1, 100);
来源：http://dali.dashuyun.cn/Article/details/gtumraspkm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gtedtnjhia.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtcssijluq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zdqjudy.top/Article/details/gtyixqlpzi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daxiang520.top/Article/details/gtvusprzkj.html

Ruby: rand(1..100)
来源：http://dali.jyoumei.cn/Article/details/gtxxfkvouw.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxycuyce.html

[A11] 条件表达式（三元）
来源：http://dali.cucudq.cn/Article/details/gtkuhqxcuw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tian-w.cn/Article/details/gtkwcbpgmk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtooxoptqc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtyyxntxwn.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaheijku.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtuzvlbyeu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nanxuanxn.top/Article/details/gtflnstxfb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsuzctae.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqtntqdq.html

[A12] 字符串插值 / 格式化
来源：http://dali.redwolf501.top/Article/details/gtihpteaah.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.nanxuanxn.top/Article/details/gttkoikwcd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sysykeji.top/Article/details/gthaovsjto.html

JS:   `Hello, ${name}!`
来源：http://dali.shangyingyoupin.top/Article/details/gtrviapbsp.html

TS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtyoinqwik.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cucudq.cn/Article/details/gtatwvuotp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yanxiufei.cn/Article/details/gtlwhtdjca.html

Ruby: "Hello, #{name}!"
来源：http://dali.yongpay.top/Article/details/gtjgdryect.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258888.top/Article/details/gtnmqyfeez.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.svipenyu.cn/Article/details/gtpyrbzloh.html

Py:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtlkwalfww.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtcuhdlxfi.html

JS:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtnsglucru.html

TS:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtovelgwxw.html

Java: "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtgxqaglle.html

Go:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtywzfmcdh.html

Ruby: "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gtcwzvfwqa.html

C#:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtaeidswlx.html

[A14] 注释写法
来源：http://dali.hammf.cn/Article/details/gtxjiilkhy.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ivvv.top/Article/details/gtxkuiiavy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yongpay.top/Article/details/gthummvhdr.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtjmkomptz.html

TS:   // 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtwlusqkga.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yangfankeji.com/Article/details/gtuxeicpry.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gtlbolivqk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tanke756.top/Article/details/gtiswfzxea.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaicqumve.html

[A15] 空值判断与默认值
来源：http://dali.nanxuanxn.top/Article/details/gtmctloois.html

Py:   value = data or "默认值"
来源：http://dali.iojbl.cn/Article/details/gtwargvydg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtuyeoxdqk.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtyuzesaen.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhiwuduotai.top/Article/details/gtpownnsko.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gtdtmwmtep.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.dashuyun.cn/Article/details/gtftemwxsy.html

Ruby: value = data || "默认值"
来源：http://dali.cdnleiting.top/Article/details/gtszudcdoh.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtbvanrcet.html

[A16] 真假值判断规则
来源：http://dali.yongpay.top/Article/details/gtsqfizsgf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yueranfly.top/Article/details/gtzbdbtupt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhixingplan.top/Article/details/gtzvppicrc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gtaqmhgkpj.html

TS:   if (!x) {}
来源：http://dali.guannengcc.top/Article/details/gtnabcdrpm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gtxwlfgmah.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shzxlz.cn/Article/details/gtflsbmcsp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ivvv.top/Article/details/gtszgmwren.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gtjnbgrntm.html

[A17] 位运算
来源：http://dali.jianghu66.top/Article/details/gtzvclokie.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtfohbabqr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtspknqsmg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtydnsxybj.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtytrvxkcg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gthltshmgq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtkoidxijc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtocwcrwaq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtugootkig.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tianlin.xyz/Article/details/gtolgnmagv.html

Py:   ord("A"); chr(65)
来源：http://dali.dianchejie.cn/Article/details/gtdyndsfvj.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtwrcxptoe.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gtizrdbmhc.html


<!-- 参考信息 -->