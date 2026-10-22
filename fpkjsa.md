代发 wailian999

[U105] JS：节流
来源：http://dali.yj20258.top/Article/details/gt2vmpbbeim.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gt2sijthlml.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2zqxjwydd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gt2ilqtqyze.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cizkrhtm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2vxpychzr.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gt2phcgmzxh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gt2ibbfyflq.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gt2gjhacdae.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mfubqcxs.html

[U110] JS：数组分块
来源：http://dali.tianlin.xyz/Article/details/gt2koexxnjo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gt2rznuyhhv.html

[U111] JS：对象转 Map
来源：http://dali.zdqjudy.top/Article/details/gt2vfxwafin.html

new Map(Object.entries(obj))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtprqxnx.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gt2rgtzhdwr.html

"7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gt2bzfcezgk.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gt2odjkgkfy.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gt2fvduimjq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyrwqch.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gt2kwwrwuvq.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gt2ecbqxngd.html

crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gt2wdojvguk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gt2tdegglcd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2yjrreyft.html

[U117] JS：单元测试
来源：http://dali.fengsongda.top/Article/details/gt2heikaayf.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gt2myflohim.html

[U118] JS：开发服务器
来源：http://dali.yj20258.top/Article/details/gt2mmkrshwu.html

npm i -D vite;  npx vite
来源：http://dali.sysykeji.top/Article/details/gt2zfncvjmd.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gt2irfcjbjt.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gt2dpcfqenq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zavnwgnt.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gt2qwxtiqss.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2hlngzhad.html

统计汇总
来源：http://dali.yonumen.top/Article/details/gt2xqbbcrqw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2irfohlwz.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crbqbwzl.html

Python ......... 252
来源：http://dali.tian-w.cn/Article/details/gt2jaxakfqe.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gt2rlxnpgau.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gt2wbjwchjf.html

TypeScript ..... 212
来源：http://dali.ydzc1.top/Article/details/gt2onwlueai.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kssbepva.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hnppameg.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gt2grkpiafx.html

C# ............. 212
来源：http://dali.chenlongwang.top/Article/details/gt2nehhzzqo.html

C .............. 30
来源：http://dali.vqdsnc.cn/Article/details/gt2woenpuaq.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gt2gfaufxyh.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gt2oyouoshj.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgxenkqy.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gt2qypoqlbu.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gt2zkxrvwjj.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gt2xzaqtphu.html

Perl ........... 10
来源：http://dali.hywenlv.cn/Article/details/gt2ccknmnxe.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gt2mdaaibzw.html

------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2mdhyojmk.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gt2amtqnvkw.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gt2gtzxwqfw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgfzy.top/Article/details/gt2umxvhcbn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxuanxn.top/Article/details/gt2ijmwmezs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gt2gpfuutxm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.0kj1m.cn/Article/details/gt2aysukqma.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gzhubu.top/Article/details/gt2ybwihjos.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gt2vtfkauhy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2yogsvcfy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.kuanghao11.cn/Article/details/gt2casyapul.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2uhimffry.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sxryk.cn/Article/details/gt2mwevlfxw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2tliulakm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gt2lgxpxijy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gt2ksquposi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gt2uvpqgulh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.smart0.xyz/Article/details/gt2iywlzncu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2mcpbrxyx.html

Q SQL 专题                              90
来源：http://dali.smart0.xyz/Article/details/gt2jzkyuyft.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gt2orqsppth.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gt2ubjyaxvm.html

T 其他语言补充                          60
来源：http://dali.hywenlv.cn/Article/details/gt2hjgkknpo.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dqetxwta.html

------------------------------------
来源：http://dali.xylfe.cn/Article/details/gt2ybuhynvd.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gt2lfqvvtce.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gt2hkslixtq.html

使用提醒
来源：http://dali.zhiwuduotai.top/Article/details/gt2ulxasrmm.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2cqkhvphx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gt2bkabtaxj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.9152youxi.cn/Article/details/gt2pezourtq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yanxiufei.cn/Article/details/gt2fefnqmko.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhongyouzk.top/Article/details/gt2oajyzhds.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gt2dvgvglgx.html

—— 文件结束 ——
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeyduszs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2alhshafr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yanxiufei.cn/Article/details/gt2jzkfgqle.html

Common Programming Examples Cheat Book
来源：http://dali.quarkkingdee.top/Article/details/gt2rxsmrovi.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2vdrdacsc.html

【收录内容】
来源：http://dali.guannengcc.top/Article/details/gt2dydoprsq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kqnvfgwi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gt2tafbapiv.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gt2rjujxhcs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gt2svlzlqtx.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gt2wyqaoavg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gt2hkkdiiep.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gt2vdtjcysd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gt2outgayve.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xzehncrg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.0kj1m.cn/Article/details/gt2txychjmt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2odovtqtz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gt2tizgjrgj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gt2aepjoxgg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.tian-w.cn/Article/details/gt2vdazidtx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.andypj.xyz/Article/details/gt2aziwpjkn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.bjfxy.top/Article/details/gt2nvdavrgj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.gzhubu.top/Article/details/gt2rsdwfziy.html

【文件统计】
来源：http://dali.zhiwuduotai.top/Article/details/gt2hguequev.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gt2vljgcrez.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gt2wnbzlcfd.html

目  录
来源：http://dali.chenjidiqi.icu/Article/details/gt2uazlokue.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2mwrzsywv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.redwolf501.top/Article/details/gt2cvimoype.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gt2siybtqit.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gaohongyu789.top/Article/details/gt2grnwcnet.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ybcxt.top/Article/details/gt2ybpwfanc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2orlabpsu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpthqlxl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrhstwks.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gt2sqjnijsj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2qibidnqt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2nefxhhbb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gt2xnzaejaf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmmtfgkp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gt2rdihitym.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxosdrta.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gt2ddzkwkqq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2ltywdtmm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gt2oisqpztr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2mxojfens.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yj20258.top/Article/details/gt2qiuwigar.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2ebbrsklw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2xlqxiuiv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2dnivrzwn.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gt2qbtlpvhk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2dmohgjns.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2pgqhonen.html

Py:   print("Hello, World!")
来源：http://dali.sweek.top/Article/details/gt2ollrbuhz.html

PHP:  echo "Hello, World!";
来源：http://dali.fengsongda.top/Article/details/gt2zequylok.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2nptexzxt.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xuetiantiany.cn/Article/details/gt2thsohuas.html

Java: System.out.println("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gt2zngwveqh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuanzhike.top/Article/details/gt2idnqlgdf.html

Ruby: puts "Hello, World!"
来源：http://dali.svipenyu.cn/Article/details/gt2zakgpqwh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2uctvqfki.html

[A02] 变量声明与赋值
来源：http://dali.sysykeji.top/Article/details/gt2mmbiglgj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gt2dvqubrid.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gt2xrxjufgq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yonumen.top/Article/details/gt2rapcosbl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2vqtbiack.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.wangdashe.top/Article/details/gt2xtqccslc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zycfv.cn/Article/details/gt2udwfkttz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yvedp.cn/Article/details/gt2tfayqzwm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.sxryk.cn/Article/details/gt2szhvkevm.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gt2qreaionq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gogol.net.cn/Article/details/gt2fimvgqlu.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gt2dvzcxupi.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2ghksfbxx.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2zdxtvngd.html

Java: static final double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2yddzadbf.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nymcutky.html

Ruby: PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gt2kfdnlcys.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gt2bfztymlr.html

[A04] 判断变量类型
来源：http://dali.nanxuanxn.top/Article/details/gt2xjbbwabx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.svipenyu.cn/Article/details/gt2mijkbxbc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gt2mabrfpjb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gt2oawppwtg.html

TS:   typeof x; x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gt2qpygchrq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gt2izqmzgsg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhengqikj.top/Article/details/gt2akszlzfc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gt2oqquapyg.html

C#:   x.GetType().Name; x is int
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmyrxuqp.html

[A05] 整数除法与取模
来源：http://dali.zycfv.cn/Article/details/gt2ubvdizus.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxinkj.top/Article/details/gt2ovxbfvia.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2aejkeved.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2msgzixot.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gt2sgsevpws.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gt2taxfictn.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2ttmzysgl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gt2dgtulgqu.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2fbatcixo.html

[A06] 字符串转数字
来源：http://dali.yanxiufei.cn/Article/details/gt2fvjpngma.html

Py:   int("42"); float("3.14")
来源：http://dali.havefunace.top/Article/details/gt2uxibuekj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jiagoushi.top/Article/details/gt2eqmqclww.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.haohaochexian.top/Article/details/gt2qwywjhbz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guannengcc.top/Article/details/gt2tirrvmrq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.xylfe.cn/Article/details/gt2nibxapgw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ydzc1.top/Article/details/gt2jesmreml.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnqzz.top/Article/details/gt2xfwawyxh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhengqikj.top/Article/details/gt2qhukvjrd.html

[A07] 数字转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gt2kawzxbgy.html

Py:   str(42)
来源：http://dali.xziqi.cn/Article/details/gt2kywufkce.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gt2oluhassf.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gt2dciuvjak.html

TS:   String(42)
来源：http://dali.jyoumei.cn/Article/details/gt2krwrqczj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.bjfxy.top/Article/details/gt2fhfjbhqy.html

Go:   strconv.Itoa(42)
来源：http://dali.sufxvd.cn/Article/details/gt2olwgkpug.html

Ruby: 42.to_s
来源：http://dali.ppjwa.cn/Article/details/gt2vfiveqry.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gt2uklperbg.html

[A08] 取整与四舍五入
来源：http://dali.9152youxi.cn/Article/details/gt2acbymdyb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.sweek.top/Article/details/gt2ngbkfqhx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gt2ugnhltmw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gt2eavpfwns.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.cashguo.top/Article/details/gt2qpsqxofj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gt2nbmdiihc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gt2pxzizzep.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258.top/Article/details/gt2yllykopw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2poabaypz.html

[A09] 绝对值与最大最小值
来源：http://dali.yanxiufei.cn/Article/details/gt2xsdzbgoc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2pkcgdrpz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2juqprvpj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xziqi.cn/Article/details/gt2xfgqeoxj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2svlekjwm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2pzytkkyj.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gt2xpclzliq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigfzy.top/Article/details/gt2tocqoqab.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2mofjfxeg.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gt2imhckoct.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gt2xgepupsy.html

PHP:  random_int(1, 100);
来源：http://dali.hysaishi.cn/Article/details/gt2ulukclym.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gt2pncsfqmf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.mhx1999.top/Article/details/gt2rhdappqq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gt2joeocntg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gt2ehjclhxu.html

Ruby: rand(1..100)
来源：http://dali.hnxiangtu.top/Article/details/gt2sdvdciyf.html

C#:   new Random().Next(1, 101)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbujpuqz.html

[A11] 条件表达式（三元）
来源：http://dali.gzhubu.top/Article/details/gt2pvikurqz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nygqhufq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctddthel.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2wcktmycb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2zeovhfox.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gt2zvjdrxhm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tianlin.xyz/Article/details/gt2epfxidtd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gt2fbleoaer.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gt2nugwbtyb.html

[A12] 字符串插值 / 格式化
来源：http://dali.redwolf501.top/Article/details/gt2tlpnegob.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.quarkkingdee.top/Article/details/gt2rbmyojci.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhongyouzk.top/Article/details/gt2vyjyhnqj.html

JS:   `Hello, ${name}!`
来源：http://dali.daxiang520.top/Article/details/gt2nrogmcbz.html

TS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gt2ifpqeehj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gt2dsqtmxcg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.daxiang520.top/Article/details/gt2wivbwbnw.html

Ruby: "Hello, #{name}!"
来源：http://dali.yangfankeji.com/Article/details/gt2vwrsctls.html

C#:   $"Hello, {name}!"
来源：http://dali.svipenyu.cn/Article/details/gt2qjbyvous.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xylfe.cn/Article/details/gt2aydpbsoz.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2kuvmmwbn.html

PHP:  "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2zkwfnblb.html

JS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlkqpwcz.html

TS:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2iodxwlgd.html

Java: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gihwhirf.html

Go:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2noubebxo.html

Ruby: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2dtmpwzzl.html

C#:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2sqdypmmf.html

[A14] 注释写法
来源：http://dali.vqdsnc.cn/Article/details/gt2fjehfrxi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jianghu66.top/Article/details/gt2ukvhbplq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2hlncczqr.html

JS:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nphxrpsp.html

TS:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gt2tiqrhrsp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.kuanghao11.cn/Article/details/gt2tblkhaen.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gt2jbkxpamg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nanxinkj.top/Article/details/gt2guudddig.html

C#:   // 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2hhrxtdaa.html

[A15] 空值判断与默认值
来源：http://dali.andypj.xyz/Article/details/gt2biojeivd.html

Py:   value = data or "默认值"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ebeqtemb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gt2wpeghphh.html

JS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gt2opcbmpkt.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2umlmhmav.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnxiangtu.top/Article/details/gt2zulpytgj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gt2ohuoaing.html

Ruby: value = data || "默认值"
来源：http://dali.sweek.top/Article/details/gt2ffbhtmrx.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gt2cvsymewk.html

[A16] 真假值判断规则
来源：http://dali.sweek.top/Article/details/gt2idcrrqnz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.dashuyun.cn/Article/details/gt2iaooenyc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ppjwa.cn/Article/details/gt2biysazju.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jlsjyb.cn/Article/details/gt2axylcumx.html

TS:   if (!x) {}
来源：http://dali.nwbrower.top/Article/details/gt2vlvubcbo.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ccajcahp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.meibo888.top/Article/details/gt2zwaiaiss.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj202588.top/Article/details/gt2qkturkyg.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hammf.cn/Article/details/gt2rqojvpqa.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gt2jaslppig.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2lbqablgj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2gjgbaipm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gt2nzsmmpym.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvfrxvhv.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2ptqfqwzr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2qxusqbjk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2qxspnyep.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gt2powydykm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gt2oycwedby.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gt2rczhfkvj.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpxhwvgv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shzxlz.cn/Article/details/gt2mtmdfwtv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gt2hqfuqhlu.html

Java: (int) 'A'; (char) 65
来源：http://dali.yueranfly.top/Article/details/gt2ipridviq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mpjiqnmf.html

Ruby: "A".ord; 65.chr
来源：http://dali.nwbrower.top/Article/details/gt2svshhsfw.html


<!-- 参考信息 -->