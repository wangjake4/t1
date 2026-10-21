代发 wailian999

[U103] JS：定时器
来源：http://dali.gaohongyu789.top/Article/details/gtchnnpidd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtrqpmvmrz.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gtjvvmrotg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtcrcywmmi.html

[U105] JS：节流
来源：http://dali.quarkkingdee.top/Article/details/gtujirzmvd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gthowxurjp.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtdztoulhu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sysykeji.top/Article/details/gturfmcdia.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtdfcazwop.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtgfnznnca.html

[U108] JS：随机整数
来源：http://dali.yvedp.cn/Article/details/gtuxhwfqiw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tianlin.xyz/Article/details/gtrnjwnbyy.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqiaqkhf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gogol.net.cn/Article/details/gteopxgque.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gtndxjxhms.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtpitjsfbe.html

[U111] JS：对象转 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtrrnrlhuc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gtaqxkpoen.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gtzsongtgj.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtraerlzjy.html

[U113] JS：正则替换全部
来源：http://dali.jqgfzy.top/Article/details/gtfqcumvxq.html

s.replaceAll("a", "b")
来源：http://dali.mhx1999.top/Article/details/gtpzczuvat.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gtsqyblqgh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gtnsoyouvb.html

[U115] JS：生成 UUID
来源：http://dali.zdqjudy.top/Article/details/gtsxzjrsnv.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gtaseqmnjw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gtxoancqxf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhengqikj.top/Article/details/gtwruztbgv.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtmtqwimwd.html

npm i -D vitest;  npx vitest
来源：http://dali.gogol.net.cn/Article/details/gtfvomdvvm.html

[U118] JS：开发服务器
来源：http://dali.yangfankeji.com/Article/details/gtrsizybaf.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtdjqlhima.html

[U119] JS：生产构建
来源：http://dali.jinqigufen.top/Article/details/gtnfsotevk.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtzffwcxzo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daria6918.cn/Article/details/gtxapriigb.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gtrphbzntl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtitsggcbx.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gtoczlhlrw.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtmrqpcdyx.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gtlrjboegi.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgkphrzd.html

PHP ............ 252
来源：http://dali.aizwys.cn/Article/details/gtdhqbvevw.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gtpfkadlve.html

TypeScript ..... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtrbvuknrm.html

Java ........... 212
来源：http://dali.zdqjudy.top/Article/details/gtzvpjjrfp.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtkdkxvdek.html

Ruby ........... 212
来源：http://dali.bjfxy.top/Article/details/gtrwgdnvkg.html

C# ............. 212
来源：http://dali.yonumen.top/Article/details/gthkrbazfv.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gtzbartxxa.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtgumipteo.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtlhjrsoba.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gtbxjboxuv.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtrdlsamlt.html

Swift .......... 15
来源：http://dali.tianlin.xyz/Article/details/gtmffiwrjw.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gtsdltmjej.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtstvwarac.html

Scala .......... 10
来源：http://dali.feifeiyinyue.top/Article/details/gtaegxupto.html

------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtxhawzwmq.html

合计 ........... 2106 条
来源：http://dali.gzhubu.top/Article/details/gtdgnvkkjs.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gtptfgolal.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj202588.top/Article/details/gttsncqlcs.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtavmpblyj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jqgufenzy.top/Article/details/gtirmrllmx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtzdpjqmoc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hfpthk.cn/Article/details/gtejahdszj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtkkogstrt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gttsybotuy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yvedp.cn/Article/details/gtznpcbinp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gtvrbkmzsp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtrrbipmfg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtvgfqkydi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtoqmslvig.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtnajizfog.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtlluwwnvl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.guowangkeji.top/Article/details/gtciopzfoc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtixtxzuyo.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gtuhggpysh.html

R Bash 专题                             80
来源：http://dali.cucudq.cn/Article/details/gtctbnmlaf.html

S C / C++ 专题                          60
来源：http://dali.yonumen.top/Article/details/gtknzlefdu.html

T 其他语言补充                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtrargjvbl.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gthxtqjdep.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtdglrfqom.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtzwbcofsy.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtnlfutend.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gtajbbqbkp.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtpgpiqhrm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sxryk.cn/Article/details/gtcdyvlwda.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gtzjaeyupk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtdfjyzprn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.daria6918.cn/Article/details/gtowsttksx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhengqikj.top/Article/details/gtfgrmagqs.html

—— 文件结束 ——
来源：http://dali.gzhubu.top/Article/details/gtdzvocxfx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtncymhvli.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gtczmmszrw.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gtadtnwxbb.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtymvfzuqs.html

【收录内容】
来源：http://dali.shangyingyoupin.top/Article/details/gtcshezfgz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.snrcjt.cn/Article/details/gtwhvhhofr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gttiljinhh.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gtqzyqelyy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhoulong.xyz/Article/details/gtkeecrodf.html

【使用说明】
来源：http://dali.zhixingplan.top/Article/details/gtkjdrpbqt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yongpay.top/Article/details/gtmtvpcvgq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gtypookmwp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xylfe.cn/Article/details/gttysdkrtw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.snrcjt.cn/Article/details/gtfhntakca.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.kuanghao11.cn/Article/details/gtvokehcvw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.svipenyu.cn/Article/details/gtjbottcxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hywenlv.cn/Article/details/gtpymuujxp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhongyouzk.top/Article/details/gtukmhqdar.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cucudq.cn/Article/details/gtkfqdnsmh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.dianchejie.cn/Article/details/gtygtmvkip.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangdashe.top/Article/details/gtevdxmidg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhongyouzk.top/Article/details/gtsnayhqbh.html

【文件统计】
来源：http://dali.sysykeji.top/Article/details/gtqlfwqcto.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.chenlongwang.top/Article/details/gtgepxueav.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gtazdxnjyx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gtzxcwjnph.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtlggnnnrg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gtkiyplmiw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtbgaluxpf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosokwnbo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yvedp.cn/Article/details/gttnmcqacf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guannengcc.top/Article/details/gtbzxpfwml.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtwhwjhhrb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gtptqmcvwa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtqswxzbrd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtbpiseugx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gthqdamngo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtdsuprztl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gteykpqtag.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtpnkxtzot.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fengsongda.top/Article/details/gtxyknyech.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jqgufenzy.top/Article/details/gtnabkvlrq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtwgvxhkur.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gtoenkifgp.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtwxdbwiop.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gtxyilekrh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtjcatvptg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtbeuzrxic.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqqgmkywd.html

A. 基础语法与类型
来源：http://dali.yangfankeji.com/Article/details/gtdguwzmtg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtubtjsnpp.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtpcqzybvs.html

Py:   print("Hello, World!")
来源：http://dali.9152youxi.cn/Article/details/gtcbvwvyht.html

PHP:  echo "Hello, World!";
来源：http://dali.shuidangran.top/Article/details/gtnlioyedv.html

JS:   console.log("Hello, World!");
来源：http://dali.chenlongwang.top/Article/details/gtsfmsqago.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygwguzjd.html

Java: System.out.println("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gtisfwchca.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtwwuvrxga.html

Ruby: puts "Hello, World!"
来源：http://dali.gotoacloud.top/Article/details/gtasmuhtdk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gtzyzeolry.html

[A02] 变量声明与赋值
来源：http://dali.iojbl.cn/Article/details/gtcmturuna.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtqabkfinv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.sweek.top/Article/details/gtjjmaidbi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtdwakprtt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtdedongna.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtxitfkrcn.html

Go:   name := "Alex"; age := 20
来源：http://dali.gzhubu.top/Article/details/gtkjtgvuze.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ehwqpu.com/Article/details/gtokukjzld.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglnxexzd.html

[A03] 常量定义
来源：http://dali.yueranfly.top/Article/details/gtiunjngza.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenlongwang.top/Article/details/gtqlxjrkxc.html

PHP:  const PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtcfrfyhca.html

JS:   const PI = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtqhnynwcc.html

TS:   const PI: number = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtblcjgboj.html

Java: static final double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gttfjmdxmh.html

Go:   const PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gtywsnnjgn.html

Ruby: PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gtlfupynsr.html

C#:   const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gtqrwozyiq.html

[A04] 判断变量类型
来源：http://dali.gogol.net.cn/Article/details/gtmxluzxkn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.c1oappe.top/Article/details/gtqihomahy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxinkj.top/Article/details/gtajeelncl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.smart0.xyz/Article/details/gtamvpxwdf.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gtvzsitwlb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.316326.xyz/Article/details/gtapvfhrog.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ivvv.top/Article/details/gtvekmhscd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.aibaodan.cn/Article/details/gtluzbartl.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gtuawqtfoe.html

[A05] 整数除法与取模
来源：http://dali.quarkkingdee.top/Article/details/gtxbrbkqle.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtdbwdhiap.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtktqsbsex.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtuhvpqniv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sweek.top/Article/details/gtpzpcomad.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gtoebfkbvl.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtdpaoeqgq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtiokknchb.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtomxbmyyh.html

[A06] 字符串转数字
来源：http://dali.vqdsnc.cn/Article/details/gthineoxud.html

Py:   int("42"); float("3.14")
来源：http://dali.zycfv.cn/Article/details/gtqjnpvxih.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.iojbl.cn/Article/details/gtalmblfgc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.gaohongyu789.top/Article/details/gthrkxnlfj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jianghu66.top/Article/details/gtcvzpofmx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.0kj1m.cn/Article/details/gtaghrbgxy.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gogol.net.cn/Article/details/gtmslrtwdw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimdsfzdb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guannengcc.top/Article/details/gtgvmrmald.html

[A07] 数字转字符串
来源：http://dali.jianghu66.top/Article/details/gtqykwradk.html

Py:   str(42)
来源：http://dali.dashuyun.cn/Article/details/gtugitvnol.html

PHP:  (string) 42; strval(42)
来源：http://dali.quarkkingdee.top/Article/details/gtpklbyzqw.html

JS:   String(42); (42).toString()
来源：http://dali.c1oappe.top/Article/details/gthdkcqsag.html

TS:   String(42)
来源：http://dali.tian-w.cn/Article/details/gtulytfknb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gtjnjnbdmj.html

Go:   strconv.Itoa(42)
来源：http://dali.hnxiangtu.top/Article/details/gtjueqkiom.html

Ruby: 42.to_s
来源：http://dali.jinqigfzy.top/Article/details/gtxpnvqsoz.html

C#:   42.ToString()
来源：http://dali.yuanzhike.top/Article/details/gtxmmuqcul.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gtsembkryh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtclwpqrnb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.iojbl.cn/Article/details/gtaoekxnli.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cheryme.top/Article/details/gtgdnuiiwy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yj20258888.top/Article/details/gthmjugbxw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtbshtepro.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtthigfzjd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cqqwz.cn/Article/details/gtkvibqqqq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nanxuanxn.top/Article/details/gtyrzgrxaj.html

[A09] 绝对值与最大最小值
来源：http://dali.fengsongda.top/Article/details/gtamqvenqp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtpkzxdtvn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtsciapxdd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtdmkcsjev.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtbzreokmk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtsjuqilka.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinghuilouyu.cn/Article/details/gthmhqsfpw.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.andypj.xyz/Article/details/gtxriplidy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtnnioomji.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gtwmawgrzf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yongpay.top/Article/details/gtwtqimcmd.html

PHP:  random_int(1, 100);
来源：http://dali.dianchejie.cn/Article/details/gtzrwqzeag.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shangyingyoupin.top/Article/details/gtyxmdwqur.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrzlppse.html

Java: new Random().nextInt(100) + 1
来源：http://dali.smart0.xyz/Article/details/gtnuiuwkke.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gtnltzvuzr.html

Ruby: rand(1..100)
来源：http://dali.c1oappe.top/Article/details/gtvrctdkdk.html

C#:   new Random().Next(1, 101)
来源：http://dali.snrcjt.cn/Article/details/gtxmtuklki.html

[A11] 条件表达式（三元）
来源：http://dali.iojbl.cn/Article/details/gttdksdyxy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.meibo888.top/Article/details/gtjsjpgtgp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtcaemlxvv.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtkajqzcln.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtpmidnvpm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtvlkydmrj.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.9152youxi.cn/Article/details/gtlrcjhfkv.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtemlylkbz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtjeenuyso.html

[A12] 字符串插值 / 格式化
来源：http://dali.yanxiufei.cn/Article/details/gtzeoprfcf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sufxvd.cn/Article/details/gtuqzucxvf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.snrcjt.cn/Article/details/gtvasewryi.html

JS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gtfvcohsdo.html

TS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtdnsvfnwk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.birdmap.top/Article/details/gttutejcns.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jyoumei.cn/Article/details/gtsmzhvshb.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhijiandao.cn/Article/details/gttuocwmjs.html

C#:   $"Hello, {name}!"
来源：http://dali.ppjwa.cn/Article/details/gtkchoauvd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.c1oappe.top/Article/details/gtcsfzmwex.html

Py:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtuwfwzutb.html

PHP:  "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtvbxxksyb.html

JS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtkwtlgseu.html

TS:   "第一行\n第二行"
来源：http://dali.mhx1999.top/Article/details/gtfbkzuhwb.html

Java: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtyfrvertg.html

Go:   "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtshuhpadb.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtabgoegxe.html

C#:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtndeqgmfx.html

[A14] 注释写法
来源：http://dali.gaohongyu789.top/Article/details/gtbqnmxmtb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gogol.net.cn/Article/details/gtumlwoahs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtygsmyucy.html

JS:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtupnadgxz.html

TS:   // 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gteuxzkdgk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhongyouzk.top/Article/details/gtumoofrsq.html

Go:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtqotoytru.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gaohongyu789.top/Article/details/gtvpmsqpyl.html

C#:   // 单行；/* 多行 */
来源：http://dali.meibo888.top/Article/details/gtfphfyysu.html

[A15] 空值判断与默认值
来源：http://dali.haohaochexian.top/Article/details/gtogmeuvuz.html

Py:   value = data or "默认值"
来源：http://dali.smart0.xyz/Article/details/gteeycqqrq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtlebukpdx.html

JS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtcjdjiroo.html

TS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtlfnmlwnd.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cdnleiting.top/Article/details/gtprjbngfu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigufen.top/Article/details/gtirkaobni.html

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gtoceeoala.html

C#:   var value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gtifcsrysc.html

[A16] 真假值判断规则
来源：http://dali.guannengcc.top/Article/details/gttqizeiil.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.kuanghao11.cn/Article/details/gtwatmhrdh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.kuanghao11.cn/Article/details/gtmnpbqzpa.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangdashe.top/Article/details/gtnikhxrfx.html

TS:   if (!x) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxmjstpoi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsdvetqck.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj20258888.top/Article/details/gtpesnqhet.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gzhubu.top/Article/details/gtjdtulerg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yvedp.cn/Article/details/gtfiyngbqy.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gtmdymqkxz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtyjgzpowy.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gtkuewxvqn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtehxfhdgs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtjhcverxb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtwrhlidim.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtfseloztn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtzwobjkpn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtlgrihvpz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yongpay.top/Article/details/gtcbmrlyhp.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gttieogvwn.html

PHP:  ord("A"); chr(65)
来源：http://dali.quarkkingdee.top/Article/details/gtrksmonfl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtxfyztjoz.html


<!-- 参考信息 -->