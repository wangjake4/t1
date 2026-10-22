代发 wailian999

[U103] JS：定时器
来源：http://dali.hnxiangtu.top/Article/details/gt2naznhbrh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mffrcqmo.html

[U104] JS：防抖
来源：http://dali.smart0.xyz/Article/details/gt2jivoeukk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daria6918.cn/Article/details/gt2afjfpvhq.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gt2shsgvltz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gt2cznclvzf.html

[U106] JS：日期格式化
来源：http://dali.0kj1m.cn/Article/details/gt2sormwxqg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2juunnmsi.html

[U107] JS：数字千分位
来源：http://dali.xinyue.icu/Article/details/gt2mzwvydwz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gt2wckzmamt.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gt2flvbkbos.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sysykeji.top/Article/details/gt2lytfdfab.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpmeixhx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gt2pwvtjgbv.html

[U110] JS：数组分块
来源：http://dali.ybcxt.top/Article/details/gt2jsfgyako.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hysaishi.cn/Article/details/gt2rgrabddg.html

[U111] JS：对象转 Map
来源：http://dali.xuanzx.com/Article/details/gt2ddrqcwus.html

new Map(Object.entries(obj))
来源：http://dali.aibaodan.cn/Article/details/gt2lhhmmicj.html

[U112] JS：字符串补位
来源：http://dali.jyoumei.cn/Article/details/gt2gcouglbo.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2skqzwirs.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gt2gxymaiuk.html

s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gt2ogpngjlm.html

[U114] JS：JSON 深比较
来源：http://dali.316326.xyz/Article/details/gt2ibzscdok.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjxpeyun.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyavqcts.html

crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2nnppqdfm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.9152youxi.cn/Article/details/gt2poxiitxp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fengsongda.top/Article/details/gt2xwyeaayv.html

[U117] JS：单元测试
来源：http://dali.yuanzhike.top/Article/details/gt2vmeoansn.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gt2rxsrpnrf.html

[U118] JS：开发服务器
来源：http://dali.vqdsnc.cn/Article/details/gt2vmsenyak.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gt2qroiahhr.html

[U119] JS：生产构建
来源：http://dali.cashguo.top/Article/details/gt2gckyjqgu.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gt2gvkbhbbp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gt2ggprvivk.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gt2eyoyqjei.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bhbcrlhd.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gt2nldoisog.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2jefhfzcp.html

按语言统计（条）：
来源：http://dali.ybcxt.top/Article/details/gt2rwvbxwzq.html

Python ......... 252
来源：http://dali.yj20258888.top/Article/details/gt2qnykiyne.html

PHP ............ 252
来源：http://dali.fzhhl.top/Article/details/gt2exwrkplt.html

JavaScript ..... 252
来源：http://dali.jqgufenzy.top/Article/details/gt2cptxedax.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gt2slmtfmrv.html

Java ........... 212
来源：http://dali.zhengqikj.top/Article/details/gt2kbuljmfw.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gt2suzqftsd.html

Ruby ........... 212
来源：http://dali.hysaishi.cn/Article/details/gt2naljlbpz.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2jfdtczoa.html

C .............. 30
来源：http://dali.daxiang520.top/Article/details/gt2nbcsbgva.html

C++ ............ 30
来源：http://dali.zycfv.cn/Article/details/gt2adzrpysq.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gt2oatjkoax.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gt2eqgeqoge.html

Kotlin ......... 15
来源：http://dali.hammf.cn/Article/details/gt2swlyjcjb.html

Swift .......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nowcmaio.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gt2vvmcrxlt.html

Perl ........... 10
来源：http://dali.jiagoushi.top/Article/details/gt2mcddnugl.html

Scala .......... 10
来源：http://dali.yueranfly.top/Article/details/gt2nbkdmlzu.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2evemtfti.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gt2ccjldcki.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gt2wtjzqmqh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gt2mjobprxr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.9152youxi.cn/Article/details/gt2ilpqrmzr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gt2bzzstfzl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2xpfbfmkm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gt2vmuckbae.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gt2plnguhwa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2dfomwxvu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yuanzhike.top/Article/details/gt2qcnhcwur.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2txpqkcqn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2uvfrknjw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2yozqyayo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gt2gpoocyhh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2ryhtbrtq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gt2qighnpsb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.redwolf501.top/Article/details/gt2gvkrikfh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2tprmoroj.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gt2gaudejgz.html

R Bash 专题                             80
来源：http://dali.zdqjudy.top/Article/details/gt2pvcoaecf.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gt2dskrttle.html

T 其他语言补充                          60
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvfuetgk.html

U 高频实用片段                         120
来源：http://dali.hywenlv.cn/Article/details/gt2noovwmbv.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2zkihncca.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gt2thlmdezp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzdcser.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gt2ewmbdvvb.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gt2vdlzissj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.guannengcc.top/Article/details/gt2dtbduwoe.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.vqdsnc.cn/Article/details/gt2dbslinoa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gt2zksjhueb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gt2giximftn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysfaymel.html

—— 文件结束 ——
来源：http://dali.yuanzhike.top/Article/details/gt2gaysgfeq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2cwgwfqxs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.0kj1m.cn/Article/details/gt2wgncmqpf.html

Common Programming Examples Cheat Book
来源：http://dali.bjfxy.top/Article/details/gt2ydjfxmgf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dvkwuylk.html

【收录内容】
来源：http://dali.pycfn.com/Article/details/gt2vbuictkg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigfzy.top/Article/details/gt2humjbijm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hywenlv.cn/Article/details/gt2qqhxseex.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gt2hywqwmkp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dashuyun.cn/Article/details/gt2ylqnyilx.html

【使用说明】
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxjknayt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gt2llqvlumu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gogol.net.cn/Article/details/gt2nmbxlnxy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2fxeheiiu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gt2avegwqcn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yongpay.top/Article/details/gt2eqlcqbpp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xziqi.cn/Article/details/gt2huywpmjr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ivvotcko.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gt2pmffxrnf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangdashe.top/Article/details/gt2nfxsizuo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gt2oqzmnntq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hfpthk.cn/Article/details/gt2grfoxcbw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oejjkccb.html

【文件统计】
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngaxiznv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shzxlz.cn/Article/details/gt2aidjcruv.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2ntmioevy.html

目  录
来源：http://dali.yangfankeji.com/Article/details/gt2ehregwyj.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2wcpgdyhx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.guannengcc.top/Article/details/gt2pcnddwky.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yongpay.top/Article/details/gt2szkijowb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2gxuymyoc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hysaishi.cn/Article/details/gt2yacbvxnn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2whmutfhr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.meibo888.top/Article/details/gt2bwngzsyz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hysaishi.cn/Article/details/gt2wcbilnnd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinqigufen.top/Article/details/gt2yydxpahy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2wsteffvz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2nootmmwd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2uhmqicey.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ehwqpu.com/Article/details/gt2nfyhtvgy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2dmhmdhzv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gt2qogyzqej.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.0kj1m.cn/Article/details/gt2yavbzrii.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gt2rpehdlqq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cheryme.top/Article/details/gt2zjxpbowb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.9152youxi.cn/Article/details/gt2ldsppcim.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yonumen.top/Article/details/gt2haabxrpg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2meojyhma.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gt2wvyevqyl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2cyehaviq.html

A. 基础语法与类型
来源：http://dali.jiagoushi.top/Article/details/gt2uackzpvj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2iaccrzmt.html

[A01] Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2xijzgfyy.html

Py:   print("Hello, World!")
来源：http://dali.svipenyu.cn/Article/details/gt2qedmmedp.html

PHP:  echo "Hello, World!";
来源：http://dali.aizwys.cn/Article/details/gt2rlwkyeay.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2jmryqhms.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gt2duvkscsy.html

Java: System.out.println("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gt2qvgkpcft.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gt2iwbtlbfw.html

Ruby: puts "Hello, World!"
来源：http://dali.c1oappe.top/Article/details/gt2lrtsppku.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yvedp.cn/Article/details/gt2ffrlygnu.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gt2dzywhzxe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnqzz.top/Article/details/gt2drvvrxot.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2wrmsoziw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2liwoxvks.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.andypj.xyz/Article/details/gt2lgciafgs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iebtqhms.html

Go:   name := "Alex"; age := 20
来源：http://dali.shuidangran.top/Article/details/gt2gevtiwkt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gt2bhlxrudh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2tlhyxgrl.html

[A03] 常量定义
来源：http://dali.jinqigufen.top/Article/details/gt2gcouxqqi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gt2vgugveuo.html

PHP:  const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2ojuipive.html

JS:   const PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2eosgnmvh.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2citmwrjn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2jrwgojxc.html

Go:   const PI = 3.14159
来源：http://dali.zhiwuduotai.top/Article/details/gt2bncnafjt.html

Ruby: PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gt2iapadpft.html

C#:   const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gt2lrxjmxqt.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gt2rxfonydb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yueranfly.top/Article/details/gt2uarbmlff.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.mhx1999.top/Article/details/gt2yluaqkgw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.havefunace.top/Article/details/gt2jjnhxumb.html

TS:   typeof x; x instanceof Date
来源：http://dali.cashguo.top/Article/details/gt2jxyntwyt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xinyue.icu/Article/details/gt2vdlhrkjt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgtbznlz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qlnfeaia.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgufenzy.top/Article/details/gt2pstogofm.html

[A05] 整数除法与取模
来源：http://dali.sxryk.cn/Article/details/gt2pelibuhy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejhbbgtp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2crfewwfz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gt2evxbkduo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2wtpdzokd.html

Java: 7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2rupaoydj.html

Go:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gt2vbiddnco.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdytluay.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2fretbnij.html

[A06] 字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gt2zurarqlc.html

Py:   int("42"); float("3.14")
来源：http://dali.hammf.cn/Article/details/gt2rmebvyjc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.chenzaomai.com/Article/details/gt2melcdeyl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zycfv.cn/Article/details/gt2hbmdsauq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xinyue.icu/Article/details/gt2xfjjysig.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jlsjyb.cn/Article/details/gt2lpatfugs.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gt2ftvunuor.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gt2eodgelcz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2ozovqgzz.html

[A07] 数字转字符串
来源：http://dali.jiagoushi.top/Article/details/gt2onomqudk.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gt2nvjmqykt.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangdashe.top/Article/details/gt2oomijujh.html

JS:   String(42); (42).toString()
来源：http://dali.xziqi.cn/Article/details/gt2cepyimwn.html

TS:   String(42)
来源：http://dali.gaohongyu789.top/Article/details/gt2pcqayvew.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.meibo888.top/Article/details/gt2acosiwym.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gt2smhczwuc.html

Ruby: 42.to_s
来源：http://dali.havefunace.top/Article/details/gt2mnznqgmv.html

C#:   42.ToString()
来源：http://dali.jinqigfzy.top/Article/details/gt2ydjpstkz.html

[A08] 取整与四舍五入
来源：http://dali.yuanzhike.top/Article/details/gt2zwdbpseo.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2ftvtmwli.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ivvv.top/Article/details/gt2wjpyuyrn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gt2bnkbanli.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.smart0.xyz/Article/details/gt2xwlzhbtm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gt2ekhivtkt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mkqxcnai.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cashguo.top/Article/details/gt2budrhfda.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gt2ozbwhqcv.html

[A09] 绝对值与最大最小值
来源：http://dali.gotoacloud.top/Article/details/gt2xqbbichl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2yudscukl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gt2cktrkkgy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2uubbqlhr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gt2tlkhpusu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2cqjhajrr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gt2rdnqxkgt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tian-w.cn/Article/details/gt2iavpwwjo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gt2dbhgachz.html

[A10] 生成随机数
来源：http://dali.0kj1m.cn/Article/details/gt2pbrnwnbp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhongyouzk.top/Article/details/gt2cyywzfqq.html

PHP:  random_int(1, 100);
来源：http://dali.daxiang520.top/Article/details/gt2ijlvukaj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gt2jcptrzuy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2xthumrpp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fqusqikx.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.snrcjt.cn/Article/details/gt2xkoqirjz.html

Ruby: rand(1..100)
来源：http://dali.zycfv.cn/Article/details/gt2ltxlcowe.html

C#:   new Random().Next(1, 101)
来源：http://dali.gzhubu.top/Article/details/gt2hsfqwnns.html

[A11] 条件表达式（三元）
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzdcrdhy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.smart0.xyz/Article/details/gt2pkzodetm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvcrddln.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2tayyybip.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gt2xnflyazz.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2hyocvxac.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2tvohwsaw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gt2lgwucnsz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2nnqirogz.html

[A12] 字符串插值 / 格式化
来源：http://dali.cashguo.top/Article/details/gt2mplspphu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhixingplan.top/Article/details/gt2yuounayd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.9152youxi.cn/Article/details/gt2ggwkcilf.html

JS:   `Hello, ${name}!`
来源：http://dali.xuetiantiany.cn/Article/details/gt2lzkqkynw.html

TS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gt2ixhiidgz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yangfankeji.com/Article/details/gt2bvznitub.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sufxvd.cn/Article/details/gt2rnqpmihu.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenzaomai.com/Article/details/gt2ymyyszwr.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258888.top/Article/details/gt2vbubfdut.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj20258888.top/Article/details/gt2fghlklax.html

Py:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrncanfd.html

PHP:  "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gt2vzmezzbh.html

JS:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gt2bqkamnlp.html

TS:   "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gt2vlbnngpl.html

Java: "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gt2qtgqghpn.html

Go:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2hzynwshr.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ewghtbkp.html

C#:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gt2zrlgadty.html

[A14] 注释写法
来源：http://dali.hammf.cn/Article/details/gt2pjzgqtxg.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gt2wwngzhuq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.birdmap.top/Article/details/gt2fiifrdwx.html

JS:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2xnyeiokx.html

TS:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gt2rpyzpyjk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.316326.xyz/Article/details/gt2lenysywg.html

Go:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gt2xclobseq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.snrcjt.cn/Article/details/gt2upxuxqyz.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbhldyct.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gt2xrkuibbs.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2emttttbr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gt2yfbgfgrj.html

JS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2lqiunbdj.html

TS:   const value = data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2vspvaois.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jiglxaul.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hfpthk.cn/Article/details/gt2jpzujoyw.html

Ruby: value = data || "默认值"
来源：http://dali.ydzc1.top/Article/details/gt2vpoyyusr.html

C#:   var value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gt2uuwwebuy.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gt2hmgaxugv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hnxiangtu.top/Article/details/gt2btulcjjg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangdashe.top/Article/details/gt2kcvjqxin.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.feifeiyinyue.top/Article/details/gt2kofdbifl.html

TS:   if (!x) {}
来源：http://dali.yuxming.cn/Article/details/gt2qkdnkyxr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gt2whoasgmq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj20258888.top/Article/details/gt2srvqxxlq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhixingplan.top/Article/details/gt2iwshxjcw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2uaybjjla.html

[A17] 位运算
来源：http://dali.cqqwz.cn/Article/details/gt2wejceejp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2sfegeeik.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gt2ittafmtc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2iyukkaul.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2jjynrebv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gt2bhrvtvqk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2uqlgpdnr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2jjylqfig.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gt2zkruroqc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj20258888.top/Article/details/gt2mstbfrgf.html

Py:   ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gt2rdwcqfno.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gt2hyzakupb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.quarkkingdee.top/Article/details/gt2jxuhfwbq.html


<!-- 参考信息 -->