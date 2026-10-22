代发 wailian999

[U105] JS：节流
来源：http://dali.xziqi.cn/Article/details/gt2jokctevu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gt2jlitgbfh.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2maznvqfn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gogol.net.cn/Article/details/gt2htwmcalt.html

[U107] JS：数字千分位
来源：http://dali.xylfe.cn/Article/details/gt2ewwslwyu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2sykupzws.html

[U108] JS：随机整数
来源：http://dali.gaohongyu789.top/Article/details/gt2iblqfbet.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjzgduiu.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gt2ocudzbsv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gt2npfhwgzm.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gt2jzqmqyud.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmuwbkrz.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfzgdian.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2lhxfosbr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zbukvjff.html

"7".padStart(3, "0")
来源：http://dali.smart0.xyz/Article/details/gt2ktnbdses.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gt2utnmgiwv.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2bwtjkvtx.html

[U114] JS：JSON 深比较
来源：http://dali.pycfn.com/Article/details/gt2lkfilocx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zycfv.cn/Article/details/gt2kjwekosw.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2sjxeroki.html

crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2wvfvexap.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj202588.top/Article/details/gt2enknanom.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fggknase.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2reskufih.html

npm i -D vitest;  npx vitest
来源：http://dali.zhixingplan.top/Article/details/gt2hevwoxug.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gt2acocqrql.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gt2etsfyubz.html

[U119] JS：生产构建
来源：http://dali.yangfankeji.com/Article/details/gt2xdcjlmzc.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gt2jbxmrbpn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2lgphjmnp.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgecnksd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pyqbglum.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gt2spawcckp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nktugntd.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gt2woxyhrns.html

Python ......... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqqnxusp.html

PHP ............ 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2opnbqqhz.html

JavaScript ..... 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2odwwgexp.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gt2txfiyymx.html

Java ........... 212
来源：http://dali.jiagoushi.top/Article/details/gt2yxwlrjts.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gt2jjleesvd.html

Ruby ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2jnyfatgi.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gt2jetxszhb.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gt2hwjihsyn.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gt2jtyuwvsd.html

SQL ............ 90
来源：http://dali.hammf.cn/Article/details/gt2qyuhchsy.html

Bash ........... 80
来源：http://dali.aibaodan.cn/Article/details/gt2gpjwuapp.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gt2fllancvg.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gt2xomgzquk.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gt2vcaphooh.html

Perl ........... 10
来源：http://dali.hfpthk.cn/Article/details/gt2okarzgko.html

Scala .......... 10
来源：http://dali.daria6918.cn/Article/details/gt2nscpembw.html

------------------------------------
来源：http://dali.jianghu66.top/Article/details/gt2gsphsbrl.html

合计 ........... 2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlcuxzoi.html

按章节统计：
来源：http://dali.gotoacloud.top/Article/details/gt2ipdrjtcx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gt2bzilstdz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhoulong.xyz/Article/details/gt2rozjtjyi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gt2dyvrjopo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuanzx.com/Article/details/gt2ydkujzqq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gt2depcalsu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gt2jifabxpt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gt2eurihwpi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guowangkeji.top/Article/details/gt2czqxkdmj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2crjldejj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.sweek.top/Article/details/gt2huwhhceb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2atglkcdk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2sijfmcqr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2xjualyra.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnqzz.top/Article/details/gt2ranmoylz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sxryk.cn/Article/details/gt2pjhhnbrc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gt2natnvilk.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gt2nhacoync.html

R Bash 专题                             80
来源：http://dali.nanxinkj.top/Article/details/gt2ffuiujsu.html

S C / C++ 专题                          60
来源：http://dali.hnqzz.top/Article/details/gt2jyzxogri.html

T 其他语言补充                          60
来源：http://dali.zhixingplan.top/Article/details/gt2hnnzkkgl.html

U 高频实用片段                         120
来源：http://dali.yueranfly.top/Article/details/gt2petcxfkh.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2mmyrzesz.html

合计                                  2106 条
来源：http://dali.aibaodan.cn/Article/details/gt2sijnyuht.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gt2mhdblffz.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gt2otnlndgg.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2ktrfkmgn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.meibo888.top/Article/details/gt2qmpabscb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.dashuyun.cn/Article/details/gt2wovfogsa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gt2gmkrozek.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gt2dadodomj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gt2oyyeuaap.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gt2rczxcqma.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2ekdkqbid.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gt2cvjikfir.html

Common Programming Examples Cheat Book
来源：http://dali.aibaodan.cn/Article/details/gt2ncwoflfp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mywxmyzq.html

【收录内容】
来源：http://dali.xuanzx.com/Article/details/gt2iofdgctb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2nonyflsr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.havefunace.top/Article/details/gt2oekllopn.html

SQL · Bash · C · C++
来源：http://dali.svipenyu.cn/Article/details/gt2txscpcah.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.nanxinkj.top/Article/details/gt2txyemcol.html

【使用说明】
来源：http://dali.aibaodan.cn/Article/details/gt2jyqhnirp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhoulong.xyz/Article/details/gt2tfywwuwd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jlsjyb.cn/Article/details/gt2qhrtgihn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2prvkqmfh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.316326.xyz/Article/details/gt2htixfidh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pycfn.com/Article/details/gt2olumfelh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgvgekeh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gt2vlxawsxu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gt2rontbymt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ivvv.top/Article/details/gt2wwefiimk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2fxzgffpv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.c1oappe.top/Article/details/gt2jthibhtb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.andypj.xyz/Article/details/gt2rxmfqblv.html

【文件统计】
来源：http://dali.316326.xyz/Article/details/gt2xuhrhaoy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlilqljw.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2lnadojxw.html

目  录
来源：http://dali.guowangkeji.top/Article/details/gt2ubjycgoi.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gt2ugmpifxe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gt2heelwhqi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2xetdsdtb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sufxvd.cn/Article/details/gt2edkojsws.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.chenlongwang.top/Article/details/gt2auwumuuv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tian-w.cn/Article/details/gt2xyhgribx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gt2izabeoak.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zdqjudy.top/Article/details/gt2gryejkvb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gt2csuwdiok.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.birdmap.top/Article/details/gt2iaqrnqha.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2iltkuash.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gt2tmffpbry.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2xnqodlgo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gt2goafozoz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.daria6918.cn/Article/details/gt2emkktvkb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.c1oappe.top/Article/details/gt2nsxxvfev.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btuxgidn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybbzhghx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cheryme.top/Article/details/gt2nixfrbcj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwnyoeml.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gt2pniwsztd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gt2mpktdytt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2pdrulirz.html

A. 基础语法与类型
来源：http://dali.jinqigfzy.top/Article/details/gt2xpdofhir.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsgpidqk.html

[A01] Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2vkvwoobg.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yqjuvkrx.html

PHP:  echo "Hello, World!";
来源：http://dali.hysaishi.cn/Article/details/gt2rkrkdwwe.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwbzetgi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ivvv.top/Article/details/gt2oekpllsz.html

Java: System.out.println("Hello, World!");
来源：http://dali.meibo888.top/Article/details/gt2xckagfta.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.daria6918.cn/Article/details/gt2xvcecqca.html

Ruby: puts "Hello, World!"
来源：http://dali.zhoulong.xyz/Article/details/gt2mmpmckmq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.chenzaomai.com/Article/details/gt2qghxqhgw.html

[A02] 变量声明与赋值
来源：http://dali.ybcxt.top/Article/details/gt2gbcaqhvo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yvedp.cn/Article/details/gt2uaexrmyt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2ukgnlbfl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cashguo.top/Article/details/gt2xnarrtkt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sufxvd.cn/Article/details/gt2kkbfbopv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gt2mbpvpxky.html

Go:   name := "Alex"; age := 20
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djqsmctm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gt2ykodbouu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhkjnpfi.html

[A03] 常量定义
来源：http://dali.hysaishi.cn/Article/details/gt2uxxqjroa.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zdqjudy.top/Article/details/gt2shavfyef.html

PHP:  const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gt2wfvgjhhc.html

JS:   const PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2yvakbiia.html

TS:   const PI: number = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gt2qgjnoplh.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2tuhqqdai.html

Go:   const PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gt2lrekstjn.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gt2jrvmmnqh.html

C#:   const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gt2jzmvvhoj.html

[A04] 判断变量类型
来源：http://dali.havefunace.top/Article/details/gt2cpjqdjqw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgumtbqk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jiagoushi.top/Article/details/gt2huieronl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gt2tkuxhcbs.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2njubrvte.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.nwbrower.top/Article/details/gt2ueocdqtq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigufen.top/Article/details/gt2uxqegcun.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gt2grtvlrtk.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gt2ienqqjeq.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gt2jhhufihz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gt2yotyvjto.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2ehxqhqnc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lndhjpvg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2hqvbpsub.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2rrmkiizy.html

Go:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2kuyzsqpg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gt2wcrnccuk.html

C#:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2lmtljneh.html

[A06] 字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2xmozqepa.html

Py:   int("42"); float("3.14")
来源：http://dali.yuanzhike.top/Article/details/gt2vaukxiwm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhixingplan.top/Article/details/gt2irknivps.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cheryme.top/Article/details/gt2lefxsvpd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fengsongda.top/Article/details/gt2ehvggvrz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tian-w.cn/Article/details/gt2fgctsoxa.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yuxming.cn/Article/details/gt2erzwjupj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guannengcc.top/Article/details/gt2izeulybc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sufxvd.cn/Article/details/gt2towarlec.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gt2mcxlgtgl.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gt2zpyklong.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gt2klkxzqyb.html

JS:   String(42); (42).toString()
来源：http://dali.0kj1m.cn/Article/details/gt2tjmbkfrc.html

TS:   String(42)
来源：http://dali.yongpay.top/Article/details/gt2dbhetomt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daxiang520.top/Article/details/gt2vizpdakb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2rlwpwmbu.html

Ruby: 42.to_s
来源：http://dali.gzhubu.top/Article/details/gt2juxcrzwg.html

C#:   42.ToString()
来源：http://dali.yanxiufei.cn/Article/details/gt2ozgtbnet.html

[A08] 取整与四舍五入
来源：http://dali.wangdashe.top/Article/details/gt2wzkqpplr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2ayxzyata.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ocroxlvc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gt2sqmddtxr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gt2fsyfrvph.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2soflouat.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2dzmokydl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.redwolf501.top/Article/details/gt2yhlonbaa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yonumen.top/Article/details/gt2lbetjzml.html

[A09] 绝对值与最大最小值
来源：http://dali.c1oappe.top/Article/details/gt2chdvcicp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2hsllhyta.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2gpqgfqyo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gt2juejenxn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2bzrffqpg.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2wdzrcjrr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.ydzc1.top/Article/details/gt2xqsgjfcg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tian-w.cn/Article/details/gt2jjuzfvqg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2itdcaewo.html

[A10] 生成随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2rixcszwe.html

Py:   import random; random.randint(1, 100)
来源：http://dali.sweek.top/Article/details/gt2fxbseour.html

PHP:  random_int(1, 100);
来源：http://dali.jqgufenzy.top/Article/details/gt2ahlevzll.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2ybsmvkmj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gt2ptxcjqtp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2vtpbvsdc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dianchejie.cn/Article/details/gt2jlbgotmd.html

Ruby: rand(1..100)
来源：http://dali.jqgufenzy.top/Article/details/gt2cbgiosgl.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gt2zabbqrge.html

[A11] 条件表达式（三元）
来源：http://dali.yj202588.top/Article/details/gt2ijaxjsmz.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yj20258.top/Article/details/gt2ykkxfjzr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gt2jthovthp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gt2yktnfgxq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gt2kmtmavfw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gt2fghhnxxv.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.havefunace.top/Article/details/gt2dehdjjtq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2afzsnswy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2shgoowmo.html

[A12] 字符串插值 / 格式化
来源：http://dali.redwolf501.top/Article/details/gt2wjqykngh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxawkmt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gt2xsydodqq.html

JS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gt2wedrwemx.html

TS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gt2zwqxbein.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbnzfddp.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.kuanghao11.cn/Article/details/gt2qpxkupxh.html

Ruby: "Hello, #{name}!"
来源：http://dali.cheryme.top/Article/details/gt2kotesdkj.html

C#:   $"Hello, {name}!"
来源：http://dali.hywenlv.cn/Article/details/gt2yfmoulud.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigfzy.top/Article/details/gt2pronhezi.html

Py:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gt2fwwjmqsv.html

PHP:  "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2rxawopnj.html

JS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2gqolljyo.html

TS:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2javtivub.html

Java: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2uknubuly.html

Go:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2uyzwkxai.html

Ruby: "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gt2huqydbqn.html

C#:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2dhqfuvre.html

[A14] 注释写法
来源：http://dali.cqqwz.cn/Article/details/gt2vcxsrnrb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmssvmes.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gt2dpwstqls.html

JS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gt2rlojfzjx.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2mgqlnrtt.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2akxjooir.html

Go:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gt2quxmciog.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xylfe.cn/Article/details/gt2udmqcitp.html

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2sukqrufj.html

[A15] 空值判断与默认值
来源：http://dali.yuanzhike.top/Article/details/gt2ulzvnyhd.html

Py:   value = data or "默认值"
来源：http://dali.ppjwa.cn/Article/details/gt2jseudgtd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hysaishi.cn/Article/details/gt2vjaemjdf.html

JS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gt2wsertocf.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdvxmgaj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ljhkkdmo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shzxlz.cn/Article/details/gt2stqlmbmq.html

Ruby: value = data || "默认值"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmpjjovm.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gt2idbxyipd.html

[A16] 真假值判断规则
来源：http://dali.chenjidiqi.icu/Article/details/gt2wukdbzvo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmdcqsqg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.bjfxy.top/Article/details/gt2vncuvmeg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tianlin.xyz/Article/details/gt2drbgebeu.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imbrwjmr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gt2qkptmffv.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.svipenyu.cn/Article/details/gt2msfwnuup.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.kuanghao11.cn/Article/details/gt2fkvlsfdw.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xziqi.cn/Article/details/gt2mdyoocvk.html

[A17] 位运算
来源：http://dali.ivvv.top/Article/details/gt2xqzfaksl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2fixwqnbq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2oxmccnus.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2vawptlgl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2qddzyaed.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekxsrsre.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gt2icsdqduw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gt2mahpsltw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2zbcgpczc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.svipenyu.cn/Article/details/gt2usnqjduz.html

Py:   ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gt2opqsinbj.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyqgids.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2mhjzclii.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gt2qofnnheg.html

Java: (int) 'A'; (char) 65
来源：http://dali.tanke756.top/Article/details/gt2gnmuqbvk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nwbrower.top/Article/details/gt2kfnmtndy.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gt2muosazaw.html


<!-- 参考信息 -->