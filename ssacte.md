代发 wailian999

[U101] JS：classList 操作
来源：http://dali.jiagoushi.top/Article/details/gtcaitkgdl.html

el.classList.toggle("active")
来源：http://dali.xuanzx.com/Article/details/gtcdgisfas.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gtrrtqkbzr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtxvkpiaor.html

[U103] JS：定时器
来源：http://dali.nanxinkj.top/Article/details/gtuxgoqeup.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gtfriggyip.html

[U104] JS：防抖
来源：http://dali.zhiwuduotai.top/Article/details/gtynomjttn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtfyqbbaeo.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtkugpzbol.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtnxzzpczv.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwvcfgci.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj202588.top/Article/details/gtyrenalgh.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gtenlfodfk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gtbfmmqikz.html

[U108] JS：随机整数
来源：http://dali.redwolf501.top/Article/details/gtmolbffmb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcgsptyl.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gtpxmhxluj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipaqihlv.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtuanrkgdh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gzhubu.top/Article/details/gtukkhffhq.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gtqiqmewrm.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gtglfvztap.html

[U112] JS：字符串补位
来源：http://dali.quarkkingdee.top/Article/details/gtegxpnsyb.html

"7".padStart(3, "0")
来源：http://dali.daxiang520.top/Article/details/gtgncbdsjj.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gtuuixdkku.html

s.replaceAll("a", "b")
来源：http://dali.cashguo.top/Article/details/gtqxuqchow.html

[U114] JS：JSON 深比较
来源：http://dali.cucudq.cn/Article/details/gtrghyippa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gtrbeeqppg.html

[U115] JS：生成 UUID
来源：http://dali.yj202588.top/Article/details/gtncnbnvsp.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gtxqyxcywl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigufen.top/Article/details/gtuqclostu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtrjiidigm.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtmkiojfqk.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gttgqtuwsy.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gtfmlgthne.html

npm i -D vite;  npx vite
来源：http://dali.sweek.top/Article/details/gtuaezxiwq.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtnifpvigt.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtgiifktwv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gtolldkfbt.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtikftjczb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthlowwvja.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gtonqorjnt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtcrkhodmw.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtitwfbiny.html

Python ......... 252
来源：http://dali.zhongyouzk.top/Article/details/gtaiomndgj.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gtilqliubz.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gtsyhxoszy.html

TypeScript ..... 212
来源：http://dali.c1oappe.top/Article/details/gtgyikzdnd.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtlposgwph.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtxfavvbpb.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtshvjouvj.html

C# ............. 212
来源：http://dali.bjfxy.top/Article/details/gtjpumlzwe.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gtleldgfyc.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtbpudryvt.html

SQL ............ 90
来源：http://dali.zhixingplan.top/Article/details/gtiejvpcza.html

Bash ........... 80
来源：http://dali.hywenlv.cn/Article/details/gtxequoxou.html

Kotlin ......... 15
来源：http://dali.nwbrower.top/Article/details/gtiljfqadn.html

Swift .......... 15
来源：http://dali.guowangkeji.top/Article/details/gtbxilkgdb.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtkcggvewj.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtklkwjjmq.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gtifnsfkpm.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtvcqpqnjs.html

合计 ........... 2106 条
来源：http://dali.cucudq.cn/Article/details/gtbclqnpnt.html

按章节统计：
来源：http://dali.xinyue.icu/Article/details/gttkgupvuc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gthqvtdxpw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtkixvnrjj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtdoiiobpt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.snrcjt.cn/Article/details/gtogyvjpmm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gtredkjjxz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtjihooefg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtazloltvp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.quarkkingdee.top/Article/details/gtclllrcrd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtyskdmdfp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtvdkyufvr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtrctodmtf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtwabkbkwt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gthjvypqnf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gtnurobzvy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yangfankeji.com/Article/details/gtpebrefqt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtkdxgokuc.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gtupcygnab.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtvekbhksb.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gtdwbbtzvl.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtnhwkfetf.html

U 高频实用片段                         120
来源：http://dali.daxiang520.top/Article/details/gtcdmyupxp.html

------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtygjwcyqr.html

合计                                  2106 条
来源：http://dali.jyoumei.cn/Article/details/gtmcejngyr.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtwxgoslgm.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtvfjjvrjt.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtsaragvnb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gtmqpnwgrt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jianghu66.top/Article/details/gtcpkrwpdx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gtwbjycbme.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.9152youxi.cn/Article/details/gtuzfigzrx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gtxptitrby.html

—— 文件结束 ——
来源：http://dali.jinqigufen.top/Article/details/gtbythmmwg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtiacbwodl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pengpengdd.cyou/Article/details/gtsrjziult.html

Common Programming Examples Cheat Book
来源：http://dali.havefunace.top/Article/details/gtkzqyjqlf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtfmwichdp.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gtadhnkaop.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gtvhlhwdaq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yuanzhike.top/Article/details/gtkfuwimpb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gtiocbpajn.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.9152youxi.cn/Article/details/gtqasjtryb.html

【使用说明】
来源：http://dali.ppjwa.cn/Article/details/gtchnpcyeh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzhyqtkg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gtlzbuqltj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gaohongyu789.top/Article/details/gtatuitkib.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.havefunace.top/Article/details/gtzrnfjtuj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.gzhubu.top/Article/details/gtpcaaewgw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ybcxt.top/Article/details/gtmaodvbiy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsckdtph.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.svipenyu.cn/Article/details/gtgytpdplq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ppjwa.cn/Article/details/gtjnqtctqz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaawkjbp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gtrarzllwp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtfkqekwyw.html

【文件统计】
来源：http://dali.nanxinkj.top/Article/details/gtdsqxdodt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daria6918.cn/Article/details/gthtbufunc.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtxmpozwji.html

目  录
来源：http://dali.xuetiantiany.cn/Article/details/gtyjqizdjm.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gtejzfpcrs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gtzqcxifrw.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtfxaqwnzg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gtrfcbgtmp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtmpgthipz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqncgrmhz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtjdyqiwnt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gtujdhacyh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtjkluaxvc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gthdtsuhey.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtvtrwgucs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtfqziazdx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtelgovomi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtglsgqghs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hammf.cn/Article/details/gtwmdopjph.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuanxvya.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtacytvyou.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jqgufenzy.top/Article/details/gtxkzpvrhn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nanxinkj.top/Article/details/gtuozizpxw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.havefunace.top/Article/details/gtvvxwwixl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gtgssaedyv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gthqxqtifh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtsvfmyuhm.html

A. 基础语法与类型
来源：http://dali.andypj.xyz/Article/details/gtvieoyhiy.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtmvgyowfp.html

[A01] Hello World
来源：http://dali.fzhhl.top/Article/details/gtgtdagnml.html

Py:   print("Hello, World!")
来源：http://dali.jinqigfzy.top/Article/details/gttdvlbgdx.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtlolxkvlg.html

JS:   console.log("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtjdhoqbvr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yj20258888.top/Article/details/gtmxwpclrj.html

Java: System.out.println("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtqpnfrkat.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuanzx.com/Article/details/gtstffdufe.html

Ruby: puts "Hello, World!"
来源：http://dali.pycfn.com/Article/details/gtzgidrtsr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.c1oappe.top/Article/details/gtfjcdevzl.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtsistlzxe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ydzc1.top/Article/details/gtzphtdtqf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtzrqhrcsj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gtbnnzgxte.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ppjwa.cn/Article/details/gtsbocpkih.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.guannengcc.top/Article/details/gtxgxxmzmu.html

Go:   name := "Alex"; age := 20
来源：http://dali.dashuyun.cn/Article/details/gtihjbarmm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fengsongda.top/Article/details/gtfvbgqges.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gtzkkltrvs.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtqfurgoca.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yongpay.top/Article/details/gtpkaplwin.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtzdcasabs.html

JS:   const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtoaexgnao.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprtpksge.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtragjwbxr.html

Go:   const PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gtpvcmvlvq.html

Ruby: PI = 3.14159
来源：http://dali.chenlongwang.top/Article/details/gtnkcxaswq.html

C#:   const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtzrtgimlh.html

[A04] 判断变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtgtinvklv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jqgfzy.top/Article/details/gtzclzzlpb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pycfn.com/Article/details/gtactbjtod.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ehwqpu.com/Article/details/gtjrflmjwa.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtcxbfjqxp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gtuwhunbjx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgorbrbn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ydzc1.top/Article/details/gtahcfilas.html

C#:   x.GetType().Name; x is int
来源：http://dali.wangshuangyany.cn/Article/details/gtzkbemrmz.html

[A05] 整数除法与取模
来源：http://dali.cashguo.top/Article/details/gtnoasplsc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cdnleiting.top/Article/details/gtfoxtkakf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtdjeigwun.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtfpcgpsck.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtvknzazfm.html

Java: 7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtjpumhgoa.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gtyrjwrlvp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gttfycrnii.html

C#:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtzzgkkgsj.html

[A06] 字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtrscqitrj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtegzrpvej.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nwbrower.top/Article/details/gtxphnwyrm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gtiujdvpbc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtzjztcelf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtkrmltxfc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gaohongyu789.top/Article/details/gtxehvaseq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhoulong.xyz/Article/details/gtqkxuhoyf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fzhhl.top/Article/details/gtljcuocqi.html

[A07] 数字转字符串
来源：http://dali.zycfv.cn/Article/details/gtahtofcrc.html

Py:   str(42)
来源：http://dali.smart0.xyz/Article/details/gtdjigvqdp.html

PHP:  (string) 42; strval(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoomnsbwx.html

JS:   String(42); (42).toString()
来源：http://dali.meibo888.top/Article/details/gtvjsegago.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gtprhkraih.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtmqzngopw.html

Go:   strconv.Itoa(42)
来源：http://dali.cheryme.top/Article/details/gtnhsfwshb.html

Ruby: 42.to_s
来源：http://dali.jinqigufen.top/Article/details/gtexaethwr.html

C#:   42.ToString()
来源：http://dali.nanxuanxn.top/Article/details/gtchqpffmv.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gthtycstli.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gtglkjtpuo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.snrcjt.cn/Article/details/gtxjstkyfj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gtlzczwzxk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhixingplan.top/Article/details/gtesmgtudd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.smart0.xyz/Article/details/gtfeqsbufd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtoznrnqll.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gtkmqazvwm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtxiyvreap.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gtpmvupwsb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtsljumpby.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtksgwznwl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyavgbqj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvyhkfslj.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtteilwhgx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jqgufenzy.top/Article/details/gtccsjjsmz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gtubqnxoes.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtydszukuf.html

[A10] 生成随机数
来源：http://dali.hongshengwenyu.top/Article/details/gtivgiuybr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cqqwz.cn/Article/details/gttpdeuhrm.html

PHP:  random_int(1, 100);
来源：http://dali.birdmap.top/Article/details/gtzizgoini.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gtnlrxeana.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gthkxbyhdl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.cucudq.cn/Article/details/gtizjndrfl.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.9152youxi.cn/Article/details/gtpiueiaga.html

Ruby: rand(1..100)
来源：http://dali.chenjidiqi.icu/Article/details/gtupmglcni.html

C#:   new Random().Next(1, 101)
来源：http://dali.haohaochexian.top/Article/details/gtyalknysg.html

[A11] 条件表达式（三元）
来源：http://dali.svipenyu.cn/Article/details/gturzshhfp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.9152youxi.cn/Article/details/gttwruspkf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gttikfrdcz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtsutmrbco.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtpaojiypy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtlrsvorwz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhoulong.xyz/Article/details/gtvvmvbamu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gtqenygefv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuanzx.com/Article/details/gtbqxqxuzz.html

[A12] 字符串插值 / 格式化
来源：http://dali.gaohongyu789.top/Article/details/gtbhyvbept.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gtpwobvkrq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyheupdjs.html

JS:   `Hello, ${name}!`
来源：http://dali.jlsjyb.cn/Article/details/gtjdpxtyja.html

TS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtvdiuxdtc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.daxiang520.top/Article/details/gtaxpmzpfu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jianghu66.top/Article/details/gtmczxznas.html

Ruby: "Hello, #{name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztzotaoq.html

C#:   $"Hello, {name}!"
来源：http://dali.sysykeji.top/Article/details/gtrlunccdb.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.daxiang520.top/Article/details/gtyrladlwb.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtzocaysih.html

PHP:  "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtjggatsqb.html

JS:   "第一行\n第二行"
来源：http://dali.xylfe.cn/Article/details/gtxqvjjtlz.html

TS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtwkwwqoxj.html

Java: "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtcuhrzdbh.html

Go:   "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtckgabtgt.html

Ruby: "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvttprmmg.html

C#:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtyzyytciy.html

[A14] 注释写法
来源：http://dali.yj20258888.top/Article/details/gtbdujwydr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.redwolf501.top/Article/details/gtkzduugth.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtwotfwxca.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtncjsztij.html

TS:   // 单行；/* 多行 */
来源：http://dali.yangfankeji.com/Article/details/gtgcusvacj.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jqgufenzy.top/Article/details/gtoondvlis.html

Go:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtdgxiahon.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jiagoushi.top/Article/details/gthwdueyah.html

C#:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtqdgwontd.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gtcwbynttg.html

Py:   value = data or "默认值"
来源：http://dali.jyoumei.cn/Article/details/gtaghlhsom.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtxruvywoa.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxuanxn.top/Article/details/gtuhhfztah.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtkxbetmjo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.wangdashe.top/Article/details/gtujvitviq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.pengpengdd.cyou/Article/details/gtdxyyiotd.html

Ruby: value = data || "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gtvqqgvrlu.html

C#:   var value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gtpoozgrte.html

[A16] 真假值判断规则
来源：http://dali.daria6918.cn/Article/details/gtwnosifrg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgufenzy.top/Article/details/gtypfexnse.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.nanxinkj.top/Article/details/gtwwihqbta.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtxixphpar.html

TS:   if (!x) {}
来源：http://dali.yongpay.top/Article/details/gtsnjnwsvc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xinyue.icu/Article/details/gtibwhkwnd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnhqyira.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cucudq.cn/Article/details/gtfhutrbyc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sweek.top/Article/details/gtliojbsvy.html

[A17] 位运算
来源：http://dali.aizwys.cn/Article/details/gtjpmgowsl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtuiegwkok.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nanxinkj.top/Article/details/gtusdkkxnj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gtodsbvdvo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtxifvxmmq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gtahsaijay.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtxjueeakg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtkhwosypo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtgtdmfmpu.html


<!-- 参考信息 -->