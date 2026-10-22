代发 wailian999

[U103] JS：定时器
来源：http://dali.ybcxt.top/Article/details/gtqiglhbwf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.bjfxy.top/Article/details/gtrerpgzkz.html

[U104] JS：防抖
来源：http://dali.zhixingplan.top/Article/details/gtcvyqbymp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtokzjcfhe.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gthjwsojab.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.redwolf501.top/Article/details/gtqzhwcnvl.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtcufkoxtk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258888.top/Article/details/gtvoklurzw.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbylmvujp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtbrbexspt.html

[U108] JS：随机整数
来源：http://dali.gotoacloud.top/Article/details/gtlxczgbtp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guannengcc.top/Article/details/gtnxqgdgly.html

[U109] JS：数组分组
来源：http://dali.xuetiantiany.cn/Article/details/gtdqujtqlf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtpkrmjjit.html

[U110] JS：数组分块
来源：http://dali.sysykeji.top/Article/details/gtpaconnjy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.mhx1999.top/Article/details/gtobwdsivr.html

[U111] JS：对象转 Map
来源：http://dali.sufxvd.cn/Article/details/gtxfvqdfsu.html

new Map(Object.entries(obj))
来源：http://dali.wangshuangyany.cn/Article/details/gtzjshoecb.html

[U112] JS：字符串补位
来源：http://dali.wangdashe.top/Article/details/gtncvanppa.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gteehufnss.html

[U113] JS：正则替换全部
来源：http://dali.hammf.cn/Article/details/gtludstmpy.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtlsyekgkl.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gtsolhweqt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtezcnnavg.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtklaixvmk.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtfowgvwzk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hfpthk.cn/Article/details/gtvfqbthlw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjfpesayc.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtjkhmcens.html

npm i -D vitest;  npx vitest
来源：http://dali.hnxiangtu.top/Article/details/gtkljxznmk.html

[U118] JS：开发服务器
来源：http://dali.svipenyu.cn/Article/details/gtcaknrvmd.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gtbbcpptxg.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtndtkxyex.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gtyrewdxje.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gtjvfpicnn.html

import.meta.env.VITE_API_URL
来源：http://dali.haohaochexian.top/Article/details/gtnzkmvgvq.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzvfbvevv.html

统计汇总
来源：http://dali.havefunace.top/Article/details/gtpwmjmpqy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdxchotgw.html

按语言统计（条）：
来源：http://dali.yuxming.cn/Article/details/gtcaezgvqf.html

Python ......... 252
来源：http://dali.nanxuanxn.top/Article/details/gtzrntxtzl.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtmlfvxthr.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtffcdhqvf.html

TypeScript ..... 212
来源：http://dali.hysaishi.cn/Article/details/gtrkwvkjoh.html

Java ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtyylerewa.html

Go ............. 212
来源：http://dali.xinyue.icu/Article/details/gtlzxvguds.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtbolinjah.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gtsxmvjypx.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gtxavtdccd.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gtklosdsoa.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtwbjfaxdj.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtqajgmsuk.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtkdqlmywr.html

Swift .......... 15
来源：http://dali.hnqzz.top/Article/details/gtnreietgv.html

Lua ............ 10
来源：http://dali.ivvv.top/Article/details/gtnsjpnxlc.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbpdhrnbp.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gtiqjzqtlw.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtwatfedqo.html

合计 ........... 2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtwxplvcjk.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gtshsdlzrw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangtech.top/Article/details/gtdppywtzi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yuxming.cn/Article/details/gtguftpuwf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gttpbhqogk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gtchgzafbv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gteoobgqus.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtetfrlyud.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtbwkclsof.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtkcnclpel.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtzlrkrnex.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrbvcrwp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtwpreecjt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jianghu66.top/Article/details/gtxxjbxsvz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtjoaoxygy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtfznjwzez.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtbrhgibcq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gttcfidrpp.html

Q SQL 专题                              90
来源：http://dali.shuidangran.top/Article/details/gtjxjmnfsr.html

R Bash 专题                             80
来源：http://dali.yvedp.cn/Article/details/gtbacfigjv.html

S C / C++ 专题                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyaulfnp.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtgihnsppu.html

U 高频实用片段                         120
来源：http://dali.meibo888.top/Article/details/gtoughsona.html

------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtgzxevfzf.html

合计                                  2106 条
来源：http://dali.birdmap.top/Article/details/gtrdlwpgez.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtewnrmxek.html

使用提醒
来源：http://dali.pycfn.com/Article/details/gtodgbdtpq.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtqmcakzld.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtzysutndf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gtvhwpizvj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guowangkeji.top/Article/details/gtkilkiyko.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtlzmatjba.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtkrzhxauc.html

—— 文件结束 ——
来源：http://dali.yangfankeji.com/Article/details/gtzrsvkeap.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwlytwmgx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.316326.xyz/Article/details/gtxyweegvw.html

Common Programming Examples Cheat Book
来源：http://dali.andypj.xyz/Article/details/gtdglfehsw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnapxesxv.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gtksmlonwk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gtzdjqyosj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.redwolf501.top/Article/details/gtlbcskdaq.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gtagcwglft.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.birdmap.top/Article/details/gtvtmcfjcw.html

【使用说明】
来源：http://dali.svipenyu.cn/Article/details/gtnjiisaoi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jlsjyb.cn/Article/details/gtyzraivde.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.sweek.top/Article/details/gtwtytxdpw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xziqi.cn/Article/details/gtzzccceds.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gtapfcltzu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hfpthk.cn/Article/details/gtgbxslvwi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guannengcc.top/Article/details/gtttzfduee.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.smart0.xyz/Article/details/gtwjlhdxsv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jqgfzy.top/Article/details/gthmfkmnry.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hywenlv.cn/Article/details/gtcgxbuvoh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cheryme.top/Article/details/gtgaynkilo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jiagoushi.top/Article/details/gtzqmvwali.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zycfv.cn/Article/details/gtabyxjolv.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtjritenie.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gogol.net.cn/Article/details/gtxpiaiusp.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtljfqitlb.html

目  录
来源：http://dali.yvedp.cn/Article/details/gtizxwijon.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtzxicobze.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnqzz.top/Article/details/gtosiatvcf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gtdbruwavg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gtzrtijayi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtmpxyfxbk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtoozsngrm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtximephvi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dashuyun.cn/Article/details/gtqsfsxcwq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwgflmty.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gtacxazmri.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcofjdmkn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtrprdekiz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckdjtctb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtofeagyvp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yangfankeji.com/Article/details/gtrndwbvpe.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gtrwzeymtt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gthvruvutz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yongpay.top/Article/details/gtzhaskdjd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gtfxoxslby.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgufenzy.top/Article/details/gtcqgjvotb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtppopzmpp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtfywfnvwn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtctwyvkab.html

A. 基础语法与类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzljubgps.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtogwbtidq.html

[A01] Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnatosul.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtmetkceqw.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gtzwghuoyi.html

JS:   console.log("Hello, World!");
来源：http://dali.hfpthk.cn/Article/details/gtpjhpfsrt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cheryme.top/Article/details/gtrrcxblva.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtjjtrebqq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gtouqfgyvo.html

Ruby: puts "Hello, World!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtghbuycrz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtssrrrzkb.html

[A02] 变量声明与赋值
来源：http://dali.feifeiyinyue.top/Article/details/gtgkdesiam.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daria6918.cn/Article/details/gtdnnvwxmb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gtivbgqmoc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtyllznbmi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.kuanghao11.cn/Article/details/gtelukxdcd.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtesdbidlh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zdqjudy.top/Article/details/gtcfkzfsop.html

Ruby: name = "Alex"; age = 20
来源：http://dali.meibo888.top/Article/details/gtozzaiuhh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xuetiantiany.cn/Article/details/gtjchfdmii.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtlqcjiwvv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gthojyxnbr.html

PHP:  const PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gthokkhpcl.html

JS:   const PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtkdafowqa.html

TS:   const PI: number = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtlvdilagv.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtpcocgihs.html

Go:   const PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gtcfdgvvze.html

Ruby: PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtzvncywre.html

C#:   const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtntjtwxbx.html

[A04] 判断变量类型
来源：http://dali.yangfankeji.com/Article/details/gtxbndujss.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenlongwang.top/Article/details/gtyzpktxew.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hammf.cn/Article/details/gtonvvrvts.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gtzjuqnzbe.html

TS:   typeof x; x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gtzpgljzqo.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gtgbkfnbtm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenlongwang.top/Article/details/gtmiclbsek.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnxiangtu.top/Article/details/gtdgvgfnqg.html

C#:   x.GetType().Name; x is int
来源：http://dali.birdmap.top/Article/details/gtbadletrj.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gttrckdkmh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aibaodan.cn/Article/details/gtbmhufzmo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gthmqhdnyv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gtwiqtnegx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtupazqvzf.html

Java: 7 / 2; 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtwluhjdmh.html

Go:   7 / 2; 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtiuhgdxky.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtdhfbeyey.html

C#:   7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtzgnbtwhb.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtmewvtmlo.html

Py:   int("42"); float("3.14")
来源：http://dali.wangdashe.top/Article/details/gtvaluofaa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtkfnppyor.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.sufxvd.cn/Article/details/gtizcubero.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhongyouzk.top/Article/details/gttvjctevf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtufoirthf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gtfnwyjxur.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ydzc1.top/Article/details/gtozdpauvh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hammf.cn/Article/details/gtpzscqlhw.html

[A07] 数字转字符串
来源：http://dali.haohaochexian.top/Article/details/gthwunadrv.html

Py:   str(42)
来源：http://dali.havefunace.top/Article/details/gtwnilenoy.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinqigfzy.top/Article/details/gtwllilqcj.html

JS:   String(42); (42).toString()
来源：http://dali.yongpay.top/Article/details/gtcfpvctwi.html

TS:   String(42)
来源：http://dali.aibaodan.cn/Article/details/gtduavbnbv.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.tian-w.cn/Article/details/gtwwxaujto.html

Go:   strconv.Itoa(42)
来源：http://dali.cheryme.top/Article/details/gtolrmacoy.html

Ruby: 42.to_s
来源：http://dali.fzhhl.top/Article/details/gtmmihrvox.html

C#:   42.ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpfsvezv.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gtmqwxfheq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtugtximxv.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtviyhzztt.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtmhcrhuuz.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hongshengwenyu.top/Article/details/gthtflgnnt.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gthmosovlb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gthahyipuy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gogol.net.cn/Article/details/gtzjuuuapj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtyxnafyzv.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gtdwvkpele.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtydpzazpd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtquvfvbmo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtydtdhfhx.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtudrklbrm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovrhxufr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.redwolf501.top/Article/details/gtaweguimp.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.0kj1m.cn/Article/details/gtzdcupyfu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtnnzhaaui.html

[A10] 生成随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtipieqgsp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenlongwang.top/Article/details/gtcegoqxjz.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gtptrjshdo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.svipenyu.cn/Article/details/gtpailfwne.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fengsongda.top/Article/details/gtkwmqqkza.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gttyfpfmah.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258.top/Article/details/gtrgkumjrg.html

Ruby: rand(1..100)
来源：http://dali.yonumen.top/Article/details/gtpopabtkc.html

C#:   new Random().Next(1, 101)
来源：http://dali.dianchejie.cn/Article/details/gtuozfzuzq.html

[A11] 条件表达式（三元）
来源：http://dali.tian-w.cn/Article/details/gthbslatsi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhongyouzk.top/Article/details/gtkuuaqrxe.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sweek.top/Article/details/gtgibcpevn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtianpnpwd.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtgazbxvvr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gtzhnoaabw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yuanzhike.top/Article/details/gtvznulegg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gthoillfjk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtmzrdhzkk.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuxming.cn/Article/details/gteqjqaitt.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sysykeji.top/Article/details/gtbcxxcxaf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jlsjyb.cn/Article/details/gtsrtuuobc.html

JS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gtdewymqji.html

TS:   `Hello, ${name}!`
来源：http://dali.hnqzz.top/Article/details/gtebcotiox.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ehwqpu.com/Article/details/gtaqppogax.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xziqi.cn/Article/details/gtsthnogkt.html

Ruby: "Hello, #{name}!"
来源：http://dali.aizwys.cn/Article/details/gtttbycmrm.html

C#:   $"Hello, {name}!"
来源：http://dali.yj202588.top/Article/details/gtkticbzxp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuxming.cn/Article/details/gtrsudbgdj.html

Py:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtbksljklv.html

PHP:  "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtcjsmvhvu.html

JS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtbdybnlhw.html

TS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtlrxaqrzh.html

Java: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtzluyuvac.html

Go:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtytsgfugx.html

Ruby: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtriepsdpo.html

C#:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtohrtcsdw.html

[A14] 注释写法
来源：http://dali.ehwqpu.com/Article/details/gtaxqdddix.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.kuanghao11.cn/Article/details/gtynrchqsj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtqsrgiyqy.html

JS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtzunazpls.html

TS:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gteacpsgjq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gtfasokwza.html

Go:   // 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtxipkmahd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hnxiangtu.top/Article/details/gtbqayjwjz.html

C#:   // 单行；/* 多行 */
来源：http://dali.cheryme.top/Article/details/gtqlmlmvwx.html

[A15] 空值判断与默认值
来源：http://dali.daxiang520.top/Article/details/gtvjjttkvh.html

Py:   value = data or "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gtwovtrgrx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdqecywz.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaixyosr.html

TS:   const value = data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gtywxhohps.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daria6918.cn/Article/details/gtebksezbv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.fengsongda.top/Article/details/gttkzgkuix.html

Ruby: value = data || "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gthuynyhns.html

C#:   var value = data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gtujyrmzep.html

[A16] 真假值判断规则
来源：http://dali.hnqzz.top/Article/details/gtezpglbbs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjxmeigt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yangfankeji.com/Article/details/gtegkzhmpk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhengqikj.top/Article/details/gtyfrplqeq.html

TS:   if (!x) {}
来源：http://dali.kuanghao11.cn/Article/details/gtnfihhogx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.havefunace.top/Article/details/gtqtfysjef.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hongshengwenyu.top/Article/details/gtaqgjqibv.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangshuangyany.cn/Article/details/gtcblqefas.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtuhtbfnij.html

[A17] 位运算
来源：http://dali.yueranfly.top/Article/details/gtoqsxuwrj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtnaqlepfk.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtrlsmjkoo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtgdkhrrqt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gteymrkxgj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtoxvmaskg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtmoldlipy.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtamfovewm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtcwnvsfbh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.9152youxi.cn/Article/details/gtawfekuaq.html

Py:   ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtpizppixr.html

PHP:  ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtoylfemml.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtowllqbkm.html


<!-- 参考信息 -->