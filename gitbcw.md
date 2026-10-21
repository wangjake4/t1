代发 wailian999

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gtnskwqpif.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtcvwnzbwg.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gtqpbefopa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtejdblblt.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gtdzskyssi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sweek.top/Article/details/gttqbuojrx.html

[U106] JS：日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtgbqacagc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cheryme.top/Article/details/gttdrmibfj.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtoodkupcj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nanxuanxn.top/Article/details/gtebtiexaa.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtzzwurfgz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gtzhzzrtbq.html

[U109] JS：数组分组
来源：http://dali.jianghu66.top/Article/details/gteixvdcll.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shangyingyoupin.top/Article/details/gtroebigco.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gtodbydmmc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shangyingyoupin.top/Article/details/gtgssziydo.html

[U111] JS：对象转 Map
来源：http://dali.wangdashe.top/Article/details/gtrpnzhqye.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gtxtwrvxih.html

[U112] JS：字符串补位
来源：http://dali.daxiang520.top/Article/details/gthboosdwf.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtkugquoxg.html

[U113] JS：正则替换全部
来源：http://dali.sxryk.cn/Article/details/gtrxdaqtdm.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtssqowjnv.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtnnsypowh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtqahcjaty.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtojmokege.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtqnpsyxkq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtvqtsfrka.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pycfn.com/Article/details/gtykbdiuyo.html

[U117] JS：单元测试
来源：http://dali.jianghu66.top/Article/details/gtsbplxkmv.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gtrmcpryxf.html

[U118] JS：开发服务器
来源：http://dali.tian-w.cn/Article/details/gtfvridoly.html

npm i -D vite;  npx vite
来源：http://dali.jqgfzy.top/Article/details/gtjyczawcx.html

[U119] JS：生产构建
来源：http://dali.sysykeji.top/Article/details/gtfburjmal.html

npx vite build
来源：http://dali.smart0.xyz/Article/details/gtppbrkfiw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtyzlwsrsn.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gtwqvrzrbh.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvatxtcnw.html

统计汇总
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzqphvsmn.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcwpwfds.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtbutnhbdo.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gthuzhgwxv.html

PHP ............ 252
来源：http://dali.cucudq.cn/Article/details/gtduxzlxbr.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtssmjohzp.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtaaeenugi.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtpnpynylp.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gtlumkgfni.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gttihgewzh.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gtxbshmaks.html

C .............. 30
来源：http://dali.bjfxy.top/Article/details/gtabxtpqak.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtpsrgqpml.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtzlpqkhbg.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxddyflyf.html

Kotlin ......... 15
来源：http://dali.yj202588.top/Article/details/gttnwigynz.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gttoxxhgfm.html

Lua ............ 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvbwblcrx.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtdmfythpc.html

Scala .......... 10
来源：http://dali.ybcxt.top/Article/details/gtoijvnnav.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtspbwhzoa.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtzmbpxenx.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtguihqtra.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtougkjrhb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtytrcrubp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtuvugiabm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtluqjcydk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hywenlv.cn/Article/details/gtfmrmnhdg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gtqltmrswn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gteohbmesm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtlcpssrso.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtnxhijtoa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtprxmeboj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gttgctyzyd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtnzzfflju.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtywjkkjja.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtfcdobdxo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xziqi.cn/Article/details/gtdpjbeadb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtlgjhjvbc.html

Q SQL 专题                              90
来源：http://dali.cdnleiting.top/Article/details/gtitlrzjva.html

R Bash 专题                             80
来源：http://dali.mhx1999.top/Article/details/gtthjqmagy.html

S C / C++ 专题                          60
来源：http://dali.svipenyu.cn/Article/details/gtoeeynkyy.html

T 其他语言补充                          60
来源：http://dali.jinqigufen.top/Article/details/gtlptwaumz.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtxssrjifi.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtyvkbduft.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gtphcfdgbz.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtrdcfqdkr.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gttfxfsrje.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtjvilanin.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuetiantiany.cn/Article/details/gtkmqbgkju.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.pycfn.com/Article/details/gteiahoaat.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yonumen.top/Article/details/gtcjlewenz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtlzdrygzl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shzxlz.cn/Article/details/gtanvumqci.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gtsgmpdlqg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvtiqsgxn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yvedp.cn/Article/details/gtfowvsgcm.html

Common Programming Examples Cheat Book
来源：http://dali.guannengcc.top/Article/details/gtrhfufbll.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxworhhru.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gtfonmaebn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gthuayjefp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.iojbl.cn/Article/details/gtyqgplrch.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gtcczxjipi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.daria6918.cn/Article/details/gtbeukdwhs.html

【使用说明】
来源：http://dali.smart0.xyz/Article/details/gtrnpkyyle.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.sxryk.cn/Article/details/gtjqeayvim.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuetiantiany.cn/Article/details/gtehuzrebx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhiwuduotai.top/Article/details/gtguzhxpix.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jyoumei.cn/Article/details/gtsjgvhghy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigfzy.top/Article/details/gtaeaikwhy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgfzy.top/Article/details/gtijpdxnar.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.bjfxy.top/Article/details/gtdmyaudcn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jlsjyb.cn/Article/details/gtovmhrvqo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yongpay.top/Article/details/gtyztihtxg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cashguo.top/Article/details/gtozwkhsfu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.chenzaomai.com/Article/details/gtuijhopnc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj20258.top/Article/details/gtodmnkejl.html

【文件统计】
来源：http://dali.xuanzx.com/Article/details/gtruyaervt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gaohongyu789.top/Article/details/gtsizoyfto.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtmdoadexm.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gtzfgvqpcd.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtxfmmxnhb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ydzc1.top/Article/details/gtgkhjrqsj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllmatmcw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtportmzfs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtfajjmmpc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.guannengcc.top/Article/details/gtxrwlgkys.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.316326.xyz/Article/details/gtonufncgf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gtrvltpiml.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtbbndbtre.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtgbipnuqe.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fengsongda.top/Article/details/gtrgvkbzor.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gthcpmbqek.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gteekeuqpe.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtnccxdimo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiteyxwn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.andypj.xyz/Article/details/gtesorsenj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtyuznzubv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.c1oappe.top/Article/details/gtmulzfhfo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tian-w.cn/Article/details/gtbynojftj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ydzc1.top/Article/details/gtbemqlzxm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gthgicviys.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzttmzhdp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtshiotrtd.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gttigiataz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjlxjtybe.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtdirjsqyw.html

Py:   print("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gtjnrfqhup.html

PHP:  echo "Hello, World!";
来源：http://dali.bjfxy.top/Article/details/gtvfziyfcr.html

JS:   console.log("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gtytyyjbwo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuylgrlxv.html

Java: System.out.println("Hello, World!");
来源：http://dali.bjfxy.top/Article/details/gtwfzuhpwz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtmmtzpflf.html

Ruby: puts "Hello, World!"
来源：http://dali.kuanghao11.cn/Article/details/gtgpkvykqn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gttnntoumr.html

[A02] 变量声明与赋值
来源：http://dali.gotoacloud.top/Article/details/gtfbljdeto.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zdqjudy.top/Article/details/gtbxcwsvqh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.bjfxy.top/Article/details/gtknmfapkj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gtpzuiameg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtmyizfuff.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.pengpengdd.cyou/Article/details/gtxspkzefz.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxnogsnz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cashguo.top/Article/details/gtmkzvedwq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shzxlz.cn/Article/details/gtouuilfrz.html

[A03] 常量定义
来源：http://dali.shzxlz.cn/Article/details/gtokhtatxz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zycfv.cn/Article/details/gtvbdwwdwc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkelpdixl.html

JS:   const PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtweeikzxj.html

TS:   const PI: number = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtpfkjfgad.html

Java: static final double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtvymfytyd.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtyvclcqwl.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtncojkreq.html

C#:   const double PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gtjlhhwula.html

[A04] 判断变量类型
来源：http://dali.gogol.net.cn/Article/details/gtnghmpitg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daxiang520.top/Article/details/gtclfifpun.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.aizwys.cn/Article/details/gtmbtiskvk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yongpay.top/Article/details/gthzfstyfa.html

TS:   typeof x; x instanceof Date
来源：http://dali.nanxuanxn.top/Article/details/gttzurdnmq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtvbzhmjyg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gtiydogcqw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sxryk.cn/Article/details/gtkavpdqdu.html

C#:   x.GetType().Name; x is int
来源：http://dali.shanyushiyangtech.top/Article/details/gttuujhpvo.html

[A05] 整数除法与取模
来源：http://dali.jqgufenzy.top/Article/details/gtwhdikijk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenjidiqi.icu/Article/details/gtsbvsuzhp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtvmkrhewl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gtpdnqdrzu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtaqkiwuvt.html

Java: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtlbtlqhvs.html

Go:   7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtezggebmy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtmrtwfmoc.html

C#:   7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtcihfxkvt.html

[A06] 字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gtsqcccthw.html

Py:   int("42"); float("3.14")
来源：http://dali.pycfn.com/Article/details/gtjirssltz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.quarkkingdee.top/Article/details/gtdwcqkkae.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yuxming.cn/Article/details/gttgpqtpte.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtkwvcjyxv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zycfv.cn/Article/details/gtejvqoocl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.pengpengdd.cyou/Article/details/gtnfvbmjyw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.316326.xyz/Article/details/gtbebktstu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shuidangran.top/Article/details/gtcqbinhum.html

[A07] 数字转字符串
来源：http://dali.andypj.xyz/Article/details/gteezjtqgl.html

Py:   str(42)
来源：http://dali.zhongyouzk.top/Article/details/gttdvqlqmo.html

PHP:  (string) 42; strval(42)
来源：http://dali.jianghu66.top/Article/details/gtyoeiuowl.html

JS:   String(42); (42).toString()
来源：http://dali.yueranfly.top/Article/details/gtqnmugexe.html

TS:   String(42)
来源：http://dali.fengsongda.top/Article/details/gtzqwzkqbr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gtnaqgdxfv.html

Go:   strconv.Itoa(42)
来源：http://dali.andypj.xyz/Article/details/gtolgizhdy.html

Ruby: 42.to_s
来源：http://dali.zhongyouzk.top/Article/details/gtrftvtcsv.html

C#:   42.ToString()
来源：http://dali.nwbrower.top/Article/details/gtzbuxikul.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gtchlyecxt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtmyfktrmh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daria6918.cn/Article/details/gttvdobmfm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gtggtkoull.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ppjwa.cn/Article/details/gtfqmohucf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtedmzrrlu.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtzruqrltd.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.quarkkingdee.top/Article/details/gtoygluhgc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtjemhshau.html

[A09] 绝对值与最大最小值
来源：http://dali.cashguo.top/Article/details/gtubwbanuv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtopkmuoxt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtlmuxkdjv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwxazvsf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtrhelyqvx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtsrgrzeot.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gtaqfnarlu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenzaomai.com/Article/details/gtgfxzhrzg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtkygtyfyd.html

[A10] 生成随机数
来源：http://dali.jianghu66.top/Article/details/gtbgarciue.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hywenlv.cn/Article/details/gtoqnuwfyo.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gtcqyeditw.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gtbdpbcpei.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gttqmiriif.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gtodhglszq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoslewpz.html

Ruby: rand(1..100)
来源：http://dali.zhoulong.xyz/Article/details/gtycmqwwpi.html

C#:   new Random().Next(1, 101)
来源：http://dali.ydzc1.top/Article/details/gtyzvovswb.html

[A11] 条件表达式（三元）
来源：http://dali.yongpay.top/Article/details/gtcrkjhjlx.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guannengcc.top/Article/details/gthffleism.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtlmvpanoj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtniwfmdbc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtketflkjf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jlsjyb.cn/Article/details/gtnzffctnp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yanxiufei.cn/Article/details/gtdrnquzii.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shangyingyoupin.top/Article/details/gttqajbfrq.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtzdenmbea.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gtgqliwgtd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwciwpvhb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gtsvhhvkci.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhohdwfw.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtdgxgasis.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj202588.top/Article/details/gtzfkselau.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gtqdmzncic.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuxming.cn/Article/details/gtjbfebdzt.html

C#:   $"Hello, {name}!"
来源：http://dali.fengsongda.top/Article/details/gtxepbklkr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sufxvd.cn/Article/details/gtauzrzsxv.html

Py:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtwtatchtj.html

PHP:  "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gttslpvluy.html

JS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtjpqltdgh.html

TS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtaifkqdth.html

Java: "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gthkkbvlrl.html

Go:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtbsybfbcx.html

Ruby: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtvegtiwig.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtxzatasvo.html

[A14] 注释写法
来源：http://dali.nanxuanxn.top/Article/details/gtyklfoidd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gtolyridps.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtqmrrbfah.html

JS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gtafcklhcd.html

TS:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gtdgoaqivn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jianghu66.top/Article/details/gtgqdneywc.html

Go:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gttsecfyky.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhijiandao.cn/Article/details/gtlbgawqjl.html

C#:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtdvcsorta.html

[A15] 空值判断与默认值
来源：http://dali.hfpthk.cn/Article/details/gticoapxvr.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtoqfkjjil.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtfpswwmiz.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtzbkkiokw.html

TS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtggapzrzm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ivvv.top/Article/details/gtgssxvors.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gtqejiosnp.html

Ruby: value = data || "默认值"
来源：http://dali.svipenyu.cn/Article/details/gtzlyyetwa.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtfqnbyvlu.html

[A16] 真假值判断规则
来源：http://dali.quarkkingdee.top/Article/details/gtjrnjqrxy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cqqwz.cn/Article/details/gtsetocufr.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gotoacloud.top/Article/details/gtugjmkilk.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.svipenyu.cn/Article/details/gtdfcjlhen.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsapjcpqx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hysaishi.cn/Article/details/gtpjqfvrmv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guannengcc.top/Article/details/gtmncyguqq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.meibo888.top/Article/details/gtcirqpazz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yueranfly.top/Article/details/gtulfelpgg.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gtrqdytezm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtolwrabax.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtdjddjdyg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtjabvxbip.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtzduseedq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gttwtaqzfi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtynnmivrc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gthnjfgxlo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtvfulshri.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jianghu66.top/Article/details/gtxpuuvyps.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtvwithxjx.html

PHP:  ord("A"); chr(65)
来源：http://dali.andypj.xyz/Article/details/gtndcojccf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gtozvopvhr.html


<!-- 参考信息 -->