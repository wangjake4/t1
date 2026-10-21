代发 wailian999

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gtunsibahi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dianchejie.cn/Article/details/gtpgtwmwxq.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gtdrsmtmsz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.redwolf501.top/Article/details/gttpkfsdwb.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gtxjuufsvb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfjgkvsm.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtpqglhczn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.meibo888.top/Article/details/gtjlpyidfu.html

[U109] JS：数组分组
来源：http://dali.xuanzx.com/Article/details/gtvpxwnqli.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtfiaooaon.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gtweqoawsq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtoqmcchub.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gttjgmagzv.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gtjabdprdo.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtkluyeyuo.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtjiptless.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gtejaxeqvb.html

s.replaceAll("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtkxgbrhio.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gteblbzmfg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtrvalglxk.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtrmsqpi.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtqqmjvzhc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gtfwxrtlke.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtiktyjiuo.html

[U117] JS：单元测试
来源：http://dali.yueranfly.top/Article/details/gtgruaxkvw.html

npm i -D vitest;  npx vitest
来源：http://dali.jyoumei.cn/Article/details/gtueohdyqi.html

[U118] JS：开发服务器
来源：http://dali.bjfxy.top/Article/details/gtnsvbffaz.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtdtuxxwlg.html

[U119] JS：生产构建
来源：http://dali.dashuyun.cn/Article/details/gttipbfzvy.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtsnaqhypw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.guannengcc.top/Article/details/gtntwoueeb.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtuhnwkaye.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjsexifsj.html

统计汇总
来源：http://dali.yj202588.top/Article/details/gtqyksjowh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtbzchlbmt.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjxcxnnt.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gttzwpwzwz.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gtscjfrkhz.html

JavaScript ..... 252
来源：http://dali.aizwys.cn/Article/details/gtgckuexbc.html

TypeScript ..... 212
来源：http://dali.yvedp.cn/Article/details/gtedbirysz.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtolubmigd.html

Go ............. 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthssixdic.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gtobeujlie.html

C# ............. 212
来源：http://dali.yuanzhike.top/Article/details/gtlrgllhbn.html

C .............. 30
来源：http://dali.yongpay.top/Article/details/gtgeddsbjd.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gthjsxlfwn.html

SQL ............ 90
来源：http://dali.yongpay.top/Article/details/gttybxsgyl.html

Bash ........... 80
来源：http://dali.yanxiufei.cn/Article/details/gtfsdhhoso.html

Kotlin ......... 15
来源：http://dali.daxiang520.top/Article/details/gtzcjrmmvp.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gtntgxtbfx.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtafmohjgn.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gthhbmplry.html

Scala .......... 10
来源：http://dali.haohaochexian.top/Article/details/gtxpewrebx.html

------------------------------------
来源：http://dali.yj20258.top/Article/details/gtslyfvthm.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtldrshyfm.html

按章节统计：
来源：http://dali.ydzc1.top/Article/details/gtkebdbatz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtlqxijfpr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtadweqlze.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtchimxkbf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtxxqcnmxs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zdqjudy.top/Article/details/gtmmgwkeni.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtsvzfkjah.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtgyyxqxma.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangshuangyany.cn/Article/details/gtpqvcqvau.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtziyynhwj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gttqphxriy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtricjixto.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtfpysdoxv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtlrjzqnum.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yj20258888.top/Article/details/gtarwydrzb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sweek.top/Article/details/gtipecpygz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtdyqfwara.html

Q SQL 专题                              90
来源：http://dali.hongshengwenyu.top/Article/details/gtewrfftmf.html

R Bash 专题                             80
来源：http://dali.nanxuanxn.top/Article/details/gtohtslhyb.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gttnrbjjse.html

T 其他语言补充                          60
来源：http://dali.jyoumei.cn/Article/details/gteggnorum.html

U 高频实用片段                         120
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyauizdp.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtkwuxzavg.html

合计                                  2106 条
来源：http://dali.zhixingplan.top/Article/details/gtcjamejdx.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtnpyualuy.html

使用提醒
来源：http://dali.gzhubu.top/Article/details/gtlnqzlyey.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtxcvzlszm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gteqfzbsmd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhoulong.xyz/Article/details/gtiavdcwnw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gtkuoghwjy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.svipenyu.cn/Article/details/gtsjpivafz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtidhembqz.html

—— 文件结束 ——
来源：http://dali.mhx1999.top/Article/details/gtoyqgsdpp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkqrrpukt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.pycfn.com/Article/details/gtvjhzjbik.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gtigemndhi.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtzuffvqsd.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gtukxhnryx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hfpthk.cn/Article/details/gtfaxvzurs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gtsyrixrws.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gtxgvxprcf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxuanxn.top/Article/details/gtzgpglxju.html

【使用说明】
来源：http://dali.sxryk.cn/Article/details/gthotzdxxx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.mhx1999.top/Article/details/gtquqwllvg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.316326.xyz/Article/details/gtabxwsxqk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yanxiufei.cn/Article/details/gtczbkhowv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jiagoushi.top/Article/details/gtmwyiiqzw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guannengcc.top/Article/details/gtvresodvl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yvedp.cn/Article/details/gtsactqbef.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxuanxn.top/Article/details/gtcjxkebyy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gtsnghwvuh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zdqjudy.top/Article/details/gtqxbycybc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.316326.xyz/Article/details/gtstbindhk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xziqi.cn/Article/details/gtwobdvzny.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yvedp.cn/Article/details/gtejnbeojd.html

【文件统计】
来源：http://dali.hfpthk.cn/Article/details/gtcbdjugpf.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhengqikj.top/Article/details/gtvyvhrdsi.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtmynlmiia.html

目  录
来源：http://dali.hysaishi.cn/Article/details/gtztzikjys.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtbvasdeim.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiiwpcubb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj202588.top/Article/details/gtvvgyqgmn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtavacpkjh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gaohongyu789.top/Article/details/gtqasjwwes.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jlsjyb.cn/Article/details/gtgepmrrwe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtqarijjoh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gtnotfjkxa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gtksevllex.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtzmewdnsu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtktmtznqc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtkunaxocu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtaxoblpzf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpntwmzu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jqgufenzy.top/Article/details/gtjnrqygbn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.iojbl.cn/Article/details/gtfmqwfngp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtjhrmbnlb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yangfankeji.com/Article/details/gtbwghvgyq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtzjzmdffp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gtvacuejuh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtqrqnngcf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtnjbzeodz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoitcnmjh.html

A. 基础语法与类型
来源：http://dali.hnxiangtu.top/Article/details/gtutatfryw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtyivmhfyw.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gtniemoses.html

Py:   print("Hello, World!")
来源：http://dali.bjfxy.top/Article/details/gtujkqvbrz.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gtbltzygxn.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtqamxqrjf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhongyouzk.top/Article/details/gtzofcfcri.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtwzxmzvxe.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zycfv.cn/Article/details/gtltzmaqzc.html

Ruby: puts "Hello, World!"
来源：http://dali.sufxvd.cn/Article/details/gtjtxvokeo.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtrkqthhql.html

[A02] 变量声明与赋值
来源：http://dali.zycfv.cn/Article/details/gtivoozoss.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigufen.top/Article/details/gtijfzyycq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gttjafmkzd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sweek.top/Article/details/gtpiyqyrtl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gtafgterlu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtkutfwuyt.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gtiuvigwls.html

Ruby: name = "Alex"; age = 20
来源：http://dali.guannengcc.top/Article/details/gttckrsbul.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gtzjwtxpza.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gtpehpcjwy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.316326.xyz/Article/details/gtztkjnvlk.html

PHP:  const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrglccbo.html

JS:   const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtrrzwvxdu.html

TS:   const PI: number = 3.14159;
来源：http://dali.birdmap.top/Article/details/gthznufnft.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtoxjdupzh.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gtkzryjuzi.html

Ruby: PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gtcqqmqozb.html

C#:   const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtkthjqfpz.html

[A04] 判断变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtieigkbak.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gtrasdorag.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yongpay.top/Article/details/gttenuhjmc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtmxmknqex.html

TS:   typeof x; x instanceof Date
来源：http://dali.aibaodan.cn/Article/details/gtkyaawimq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangtech.top/Article/details/gtibuskhcx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwiysckx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hywenlv.cn/Article/details/gtyedaggcr.html

C#:   x.GetType().Name; x is int
来源：http://dali.0kj1m.cn/Article/details/gtpeafmirt.html

[A05] 整数除法与取模
来源：http://dali.aizwys.cn/Article/details/gtmcodeotp.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jyoumei.cn/Article/details/gtjxabqrqz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtexbnpviw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtcypglrzc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtlqqmiwlv.html

Java: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtgombrtvn.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtzmtzhupo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtmuvwjhrt.html

C#:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtpixfjlfa.html

[A06] 字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtestwcval.html

Py:   int("42"); float("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtdkeahoec.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yvedp.cn/Article/details/gtwhjtvxoo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtbnruhkbz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ivvv.top/Article/details/gtxlfqdrtz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtcekyvffu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnguaokyx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xylfe.cn/Article/details/gtienskptd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtrtqevhth.html

[A07] 数字转字符串
来源：http://dali.gotoacloud.top/Article/details/gtaohvuntw.html

Py:   str(42)
来源：http://dali.9152youxi.cn/Article/details/gtzwslnqln.html

PHP:  (string) 42; strval(42)
来源：http://dali.yueranfly.top/Article/details/gtilfqupen.html

JS:   String(42); (42).toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthffrcoxa.html

TS:   String(42)
来源：http://dali.tianlin.xyz/Article/details/gtyihbjddq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.c1oappe.top/Article/details/gtwgkjiams.html

Go:   strconv.Itoa(42)
来源：http://dali.jiagoushi.top/Article/details/gtdldecsjd.html

Ruby: 42.to_s
来源：http://dali.quarkkingdee.top/Article/details/gtwklktgov.html

C#:   42.ToString()
来源：http://dali.wangdashe.top/Article/details/gtqeinnzbw.html

[A08] 取整与四舍五入
来源：http://dali.tianlin.xyz/Article/details/gtfefbfced.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtwsvziwlj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ehwqpu.com/Article/details/gtyaqrbzmy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtnuxqbavj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sysykeji.top/Article/details/gtbmdlxohf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtqixuibcb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xinyue.icu/Article/details/gtjkrpwkak.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.9152youxi.cn/Article/details/gtvswbzptx.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtjdwdpwzt.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gtkofhkhty.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtmipbvhma.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtelicnkls.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtcpucvvlg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtprxdttqv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gteeiiymah.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sufxvd.cn/Article/details/gtsxwcfgpf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigufen.top/Article/details/gtvemrlzsb.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtqblkkcby.html

[A10] 生成随机数
来源：http://dali.fzhhl.top/Article/details/gtfeazehtf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xinyue.icu/Article/details/gtuhhstjbz.html

PHP:  random_int(1, 100);
来源：http://dali.cashguo.top/Article/details/gtcnwvufao.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tanke756.top/Article/details/gtvreiauuj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258888.top/Article/details/gtqhtjjyqd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gtumhmuxmr.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtamtdkgxu.html

Ruby: rand(1..100)
来源：http://dali.cucudq.cn/Article/details/gtgvnpuacd.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gtehfaakqm.html

[A11] 条件表达式（三元）
来源：http://dali.yuxming.cn/Article/details/gtspbkiunz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.kuanghao11.cn/Article/details/gtqnbaeibg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtsdljwxpa.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtwshhjfxk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtycyfpmyn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gtsyfazvab.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmxnztgg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtbvfmbxyh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gtdccekeum.html

[A12] 字符串插值 / 格式化
来源：http://dali.yvedp.cn/Article/details/gtybsklwwo.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gthiwldcoj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gtbxdcrxeq.html

JS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtluieqjge.html

TS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtadczhwro.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.havefunace.top/Article/details/gtwdpbnzcd.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.fengsongda.top/Article/details/gthenzgmpe.html

Ruby: "Hello, #{name}!"
来源：http://dali.tian-w.cn/Article/details/gtjymjawze.html

C#:   $"Hello, {name}!"
来源：http://dali.jinghuilouyu.cn/Article/details/gtghujioto.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ppjwa.cn/Article/details/gtoyyfbkig.html

Py:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtxqptsrhx.html

PHP:  "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtqjmfuwkd.html

JS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowrdxmcn.html

TS:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtawhwhrtg.html

Java: "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtfdmehhbk.html

Go:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtdccwecrc.html

Ruby: "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtxlusmtdu.html

C#:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtkufwkmyo.html

[A14] 注释写法
来源：http://dali.dashuyun.cn/Article/details/gtdufchnam.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.316326.xyz/Article/details/gtcrzxvowz.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtziidzdyx.html

JS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtbiyookqg.html

TS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gthluglzro.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ivvv.top/Article/details/gtbphiqffb.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtefwyjocg.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwbcbmwd.html

C#:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gteculmxrm.html

[A15] 空值判断与默认值
来源：http://dali.havefunace.top/Article/details/gtoukqlwhn.html

Py:   value = data or "默认值"
来源：http://dali.hnqzz.top/Article/details/gtdkokxihl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhijiandao.cn/Article/details/gtymkirpcu.html

JS:   const value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtagagkulq.html

TS:   const value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtlqdxgekk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhijiandao.cn/Article/details/gtatkyrzpv.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.cucudq.cn/Article/details/gtxmlitxfm.html

Ruby: value = data || "默认值"
来源：http://dali.sufxvd.cn/Article/details/gtvpfarlzl.html

C#:   var value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtahudnvuh.html

[A16] 真假值判断规则
来源：http://dali.hysaishi.cn/Article/details/gtrkpoyake.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.dashuyun.cn/Article/details/gtqbngbzhz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.snrcjt.cn/Article/details/gtecfysvuh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gtmdibrzii.html

TS:   if (!x) {}
来源：http://dali.cashguo.top/Article/details/gtnojnblch.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zdqjudy.top/Article/details/gtgqahpqvi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj20258.top/Article/details/gtvablwspu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gtwdsqlhan.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtiruoqsur.html

[A17] 位运算
来源：http://dali.nwbrower.top/Article/details/gtlcynuzxd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtndmeydpw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtcentuwvq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtiektrujx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtwnhupcza.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtsesrzgle.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtwnqyxzak.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtwlsryhip.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtckpezxkt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.c1oappe.top/Article/details/gttodxzbhr.html

Py:   ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtfomclqlg.html

PHP:  ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gtywhnysam.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaorvpdbr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtjyrfjpmt.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj202588.top/Article/details/gtnalaedkg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.andypj.xyz/Article/details/gtmlccgaob.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenjidiqi.icu/Article/details/gtfbhvhuid.html


<!-- 参考信息 -->