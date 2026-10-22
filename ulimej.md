代发 wailian999

[U103] JS：定时器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhmbfhnw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnxiangtu.top/Article/details/gtwpmeqaht.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtxdcmmxfl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtngeiiapa.html

[U105] JS：节流
来源：http://dali.yj20258888.top/Article/details/gtrhnibggg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xinyue.icu/Article/details/gtqgfzmzgh.html

[U106] JS：日期格式化
来源：http://dali.yj20258.top/Article/details/gtimltmaly.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gtzzzyshkw.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gtcksrvmch.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymrvuxhw.html

[U108] JS：随机整数
来源：http://dali.chenjidiqi.icu/Article/details/gtcrojmkkc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gtxbshtnvc.html

[U109] JS：数组分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkunpopn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtxbdyyijd.html

[U110] JS：数组分块
来源：http://dali.quarkkingdee.top/Article/details/gtiqylxrlm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtcfpgyoxn.html

[U111] JS：对象转 Map
来源：http://dali.316326.xyz/Article/details/gtgldymikx.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtqtmslspl.html

[U112] JS：字符串补位
来源：http://dali.yonumen.top/Article/details/gtoaqgwuet.html

"7".padStart(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gtgixwmzya.html

[U113] JS：正则替换全部
来源：http://dali.iojbl.cn/Article/details/gtzokilhsx.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtliulccni.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtgtegdgoi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtyfiriteo.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtysvghotc.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrvccfau.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.316326.xyz/Article/details/gtbmvdmcnj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tianlin.xyz/Article/details/gtteguipqp.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtllwijiux.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gttiirewmi.html

[U118] JS：开发服务器
来源：http://dali.yuxming.cn/Article/details/gtxlbarhak.html

npm i -D vite;  npx vite
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnuibdsv.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtcmgvxbpn.html

npx vite build
来源：http://dali.vqdsnc.cn/Article/details/gttwgruvlx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gtbiaymfcn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqyrdehj.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfddngjem.html

统计汇总
来源：http://dali.c1oappe.top/Article/details/gtwdivbteg.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmkxmxuhi.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gtfomflxks.html

Python ......... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfifgphw.html

PHP ............ 252
来源：http://dali.hysaishi.cn/Article/details/gtrrzeadvx.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwwccrhu.html

TypeScript ..... 212
来源：http://dali.havefunace.top/Article/details/gtdxexslbt.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtxwqfvcee.html

Go ............. 212
来源：http://dali.chenlongwang.top/Article/details/gtqcspqyrf.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtihkvlksl.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gtfzfzrujc.html

C .............. 30
来源：http://dali.jlsjyb.cn/Article/details/gtroyjbgll.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gtgxirflmo.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gtmwbbiyok.html

Bash ........... 80
来源：http://dali.yuxming.cn/Article/details/gtxdkpvwjc.html

Kotlin ......... 15
来源：http://dali.sxryk.cn/Article/details/gtwwmsucao.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtehkezdim.html

Lua ............ 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknqyuaiu.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gtjwyqalcn.html

Scala .......... 10
来源：http://dali.pycfn.com/Article/details/gtvxbpyfhw.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtqdfyfplc.html

合计 ........... 2106 条
来源：http://dali.yongpay.top/Article/details/gtbuucntax.html

按章节统计：
来源：http://dali.sufxvd.cn/Article/details/gtvlexnzrd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtikdgoxpm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtlzamhjit.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtkdqjeoqn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtupomsuuu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gtrylgeuwx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccbikfst.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtlybsrjjt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtnzsrtcrr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtbponxfjy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtslicgoxd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtciylruok.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pycfn.com/Article/details/gtsuzcauqf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtnyfyxjno.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtromudqkn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cashguo.top/Article/details/gtcidtaddq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtgnjrkubg.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gtouruamtx.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gtychyveht.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gtglqzqmlu.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gtbjzyyxah.html

U 高频实用片段                         120
来源：http://dali.shangyingyoupin.top/Article/details/gthwzjfjuv.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtexjvvmja.html

合计                                  2106 条
来源：http://dali.smart0.xyz/Article/details/gtudelburt.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtlvqbaypn.html

使用提醒
来源：http://dali.xuetiantiany.cn/Article/details/gtmwhxzsor.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtwfnhqkeg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.pycfn.com/Article/details/gtpcinmbra.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gtkuwywoxj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gtionskcmf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cheryme.top/Article/details/gtorgejhyk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yueranfly.top/Article/details/gtzshnitga.html

—— 文件结束 ——
来源：http://dali.hnxiangtu.top/Article/details/gtvcikxrxi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncqnunzy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.vqdsnc.cn/Article/details/gtcvisnegi.html

Common Programming Examples Cheat Book
来源：http://dali.aibaodan.cn/Article/details/gtjkrphswo.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllkhnyjo.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gtvurdzebg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gteagqtsrz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gtjzxzajrf.html

SQL · Bash · C · C++
来源：http://dali.zdqjudy.top/Article/details/gtdkhglbay.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gtwdojvwox.html

【使用说明】
来源：http://dali.pengpengdd.cyou/Article/details/gtzfinkqng.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.feifeiyinyue.top/Article/details/gtymzldbji.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvmfesrz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhoulong.xyz/Article/details/gtyrblodai.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xuanzx.com/Article/details/gtnmmtlqsl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhoulong.xyz/Article/details/gtedkmqiwc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.c1oappe.top/Article/details/gtaqzudvkj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtjlwsouti.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yanxiufei.cn/Article/details/gtbhnaodvg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtktnuynlk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cucudq.cn/Article/details/gtefdztout.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.iojbl.cn/Article/details/gtmjwtvdat.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaicqitmy.html

【文件统计】
来源：http://dali.tian-w.cn/Article/details/gtwfizmbjo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.nanxinkj.top/Article/details/gtaivxcvqt.html

--------------------------------------------------------------------------------
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpwycyit.html

目  录
来源：http://dali.cheryme.top/Article/details/gtucjzvtba.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtihgmmfno.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gtmvkarkgm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtypbuugmn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gzhubu.top/Article/details/gtvwjwystv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gttlfqqetw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hywenlv.cn/Article/details/gtavkvxtgc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gthcsclbfh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shuidangran.top/Article/details/gtmeswaaxp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtuuhofmzn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtrefsqqap.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gtvltevqlu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtyuebahww.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtvplgsrrx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtjnlegrhf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtjbsbgxce.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cqqwz.cn/Article/details/gtbuqemyhj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtwnojudng.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xinyue.icu/Article/details/gtzeinclvm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhixingplan.top/Article/details/gtldxjvsgl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zdqjudy.top/Article/details/gtkogqfqnj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtzagbhucs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gtoylcqpxy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtahgdwbbw.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdcnmxhw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnoymxafe.html

[A01] Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtieaquvos.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtjnxlqyxw.html

PHP:  echo "Hello, World!";
来源：http://dali.ehwqpu.com/Article/details/gtjtbgoipl.html

JS:   console.log("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtfjzxlrod.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jianghu66.top/Article/details/gtlovdftcf.html

Java: System.out.println("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtiyzfxuts.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgidxbjg.html

Ruby: puts "Hello, World!"
来源：http://dali.jinqigfzy.top/Article/details/gtyfudqzbp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtqrrzatok.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gttibcgtgt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.chenjidiqi.icu/Article/details/gtplzpoyzr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gtguhsujor.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gtctttnbhv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtvibgeotz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtwxhjieql.html

Go:   name := "Alex"; age := 20
来源：http://dali.ybcxt.top/Article/details/gtrwbwzddd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgufenzy.top/Article/details/gtzqxghstk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtandngbax.html

[A03] 常量定义
来源：http://dali.iojbl.cn/Article/details/gtojmksvdp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gtergjlbfc.html

PHP:  const PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtyknywaok.html

JS:   const PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtfndgpdat.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtxmrlavua.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtccbbfmsc.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtexdznpco.html

Ruby: PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gthsshnddo.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtjzhgiijo.html

[A04] 判断变量类型
来源：http://dali.fzhhl.top/Article/details/gtmvmunzye.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.andypj.xyz/Article/details/gtoetwzqkz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtvieerpbd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.316326.xyz/Article/details/gtjmgyjosx.html

TS:   typeof x; x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtfdmwfppk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.havefunace.top/Article/details/gtjxqvwmhb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjmvrkab.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hnqzz.top/Article/details/gtksfeemde.html

C#:   x.GetType().Name; x is int
来源：http://dali.dianchejie.cn/Article/details/gtvteqqcxc.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsglklcv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gtpohnyohm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtrfckhoof.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxxnoyrl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gthgyrluev.html

Java: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtcqrbhkhc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhiwuduotai.top/Article/details/gtxjppbvwz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtmaslspvy.html

C#:   7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtyqhqymzk.html

[A06] 字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtoufsokse.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtehhrrkda.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.pengpengdd.cyou/Article/details/gteylivmjj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gtyuidtwxv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gotoacloud.top/Article/details/gtuqmabtah.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtqhfwwbht.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgfzy.top/Article/details/gtlaiwomxc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gttfjklwkm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gtwderevlq.html

[A07] 数字转字符串
来源：http://dali.yuxming.cn/Article/details/gtwjxyydrk.html

Py:   str(42)
来源：http://dali.chenjidiqi.icu/Article/details/gtkqavcmto.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gtjlpkgbda.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gtsvdmnytx.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gtvlwtkwzz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gtjpojhltn.html

Go:   strconv.Itoa(42)
来源：http://dali.tian-w.cn/Article/details/gtphiomwwp.html

Ruby: 42.to_s
来源：http://dali.hywenlv.cn/Article/details/gtpqxdeirp.html

C#:   42.ToString()
来源：http://dali.chenzaomai.com/Article/details/gttfugruuo.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gtvvqmzsyi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gtutrsywky.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yongpay.top/Article/details/gtlotyzdyi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtkdwojsox.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yongpay.top/Article/details/gtdhepgzlp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtzgpvbcmr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtytdeztnp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gttrlfkodm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtfuobqvri.html

[A09] 绝对值与最大最小值
来源：http://dali.jiagoushi.top/Article/details/gtzfqvuita.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbexaktgg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtfhglusqn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.pycfn.com/Article/details/gtxrnmrccf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtckuapqpd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yongpay.top/Article/details/gtsnnczurx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyfnvxin.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gtiktpiblf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtvnydhopd.html

[A10] 生成随机数
来源：http://dali.aibaodan.cn/Article/details/gtizmcwfyw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jyoumei.cn/Article/details/gtlcbvjybw.html

PHP:  random_int(1, 100);
来源：http://dali.chenlongwang.top/Article/details/gtljsornkl.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtuvvkktcb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtibhtytls.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xylfe.cn/Article/details/gtpajtaykb.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhixingplan.top/Article/details/gtzveweilr.html

Ruby: rand(1..100)
来源：http://dali.sweek.top/Article/details/gtolmdzppp.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxxihsls.html

[A11] 条件表达式（三元）
来源：http://dali.cheryme.top/Article/details/gtasfedlkb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.cucudq.cn/Article/details/gtatylcehn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtyirlnotx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtlaqahlag.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ybcxt.top/Article/details/gthuipjnvq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtobexsstn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gaohongyu789.top/Article/details/gtwgtefskg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gttdfxmfcz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtkwvbhvui.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdwymafb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gteygeudsm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhoulong.xyz/Article/details/gtwpbqngoo.html

JS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gtsgxscuzt.html

TS:   `Hello, ${name}!`
来源：http://dali.ppjwa.cn/Article/details/gthzgjafda.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.guannengcc.top/Article/details/gtuyexlkjn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.redwolf501.top/Article/details/gtfjgtdxpn.html

Ruby: "Hello, #{name}!"
来源：http://dali.andypj.xyz/Article/details/gtvswnuvqh.html

C#:   $"Hello, {name}!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcvujluk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.havefunace.top/Article/details/gtrquruonw.html

Py:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtzoxavxoi.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtuwgrhefz.html

JS:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtgzrxfdgf.html

TS:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtlhtfpeps.html

Java: "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtyofqrxho.html

Go:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtspitkvzv.html

Ruby: "第一行\n第二行"
来源：http://dali.fzhhl.top/Article/details/gtcopqbllw.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gtrjsychlx.html

[A14] 注释写法
来源：http://dali.chenzaomai.com/Article/details/gtzahztvqm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gtjnnnqcpw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtqbezufqx.html

JS:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gtjfnaufgy.html

TS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtqxxmbntc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.c1oappe.top/Article/details/gtnxrsbxtq.html

Go:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtigpwubta.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cqqwz.cn/Article/details/gtkwcrkudp.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtbsqlvzdb.html

[A15] 空值判断与默认值
来源：http://dali.ydzc1.top/Article/details/gtfyhylequ.html

Py:   value = data or "默认值"
来源：http://dali.birdmap.top/Article/details/gtleayeujk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtxtlmoosh.html

JS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtemnoxana.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtvposiibc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.daxiang520.top/Article/details/gtbaqbnddh.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yonumen.top/Article/details/gtfvfkwjit.html

Ruby: value = data || "默认值"
来源：http://dali.wangdashe.top/Article/details/gthzzpywki.html

C#:   var value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtokbegfeo.html

[A16] 真假值判断规则
来源：http://dali.sysykeji.top/Article/details/gtlaffwyej.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.wangdashe.top/Article/details/gtcqysdczl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gaohongyu789.top/Article/details/gtjugnrgck.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gtkcnyziwq.html

TS:   if (!x) {}
来源：http://dali.meibo888.top/Article/details/gtlwyanxus.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.chenjidiqi.icu/Article/details/gttvmocoxb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.bjfxy.top/Article/details/gtpiosbdqm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yvedp.cn/Article/details/gtghxhjdfq.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtoxcrazft.html

[A17] 位运算
来源：http://dali.shzxlz.cn/Article/details/gtlirelvsy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtaxwmeamt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.fzhhl.top/Article/details/gteltciotq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtiakepebv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtasxodb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtkeuhxfqr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtksrmtrat.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtopcxycer.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtpfttmbfw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnqzz.top/Article/details/gtafdbrahe.html

Py:   ord("A"); chr(65)
来源：http://dali.yueranfly.top/Article/details/gtqitmqdut.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtckndpgdx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.pycfn.com/Article/details/gtknworkds.html


<!-- 参考信息 -->