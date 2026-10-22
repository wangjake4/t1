代发 wailian999

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gt2towkuvjj.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2hsxkmzes.html

[U102] JS：本地存储
来源：http://dali.jianghu66.top/Article/details/gt2fsglxckp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.sufxvd.cn/Article/details/gt2xapmkuwb.html

[U103] JS：定时器
来源：http://dali.wangshuangyany.cn/Article/details/gt2safqwmff.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gt2mbdgzphf.html

[U104] JS：防抖
来源：http://dali.haohaochexian.top/Article/details/gt2qdgwsinq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jiagoushi.top/Article/details/gt2jcntbztu.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gt2egwhkjtr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daria6918.cn/Article/details/gt2jaebokdk.html

[U106] JS：日期格式化
来源：http://dali.tian-w.cn/Article/details/gt2hnzwfqcu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ydzc1.top/Article/details/gt2dnjkqguf.html

[U107] JS：数字千分位
来源：http://dali.birdmap.top/Article/details/gt2dfiemdyi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.svipenyu.cn/Article/details/gt2ysemlhin.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gt2icpqeuzs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gt2mjjknxxb.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gt2dzlkocoh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2rvoojiww.html

[U110] JS：数组分块
来源：http://dali.smart0.xyz/Article/details/gt2nwuludef.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gt2ijcdrous.html

[U111] JS：对象转 Map
来源：http://dali.tanke756.top/Article/details/gt2vvtnaujq.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gt2yxyeoevr.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvhvvhed.html

"7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2wmtjlrtp.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gt2irvfsoit.html

s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gt2kvqroizf.html

[U114] JS：JSON 深比较
来源：http://dali.yuanzhike.top/Article/details/gt2vzjxsgbc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2ovmaopwm.html

[U115] JS：生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gt2zidbriog.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2xxsieoqt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuanzhike.top/Article/details/gt2drwvpcat.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gt2zhtrhajf.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gt2jtfjwfvl.html

npm i -D vitest;  npx vitest
来源：http://dali.hfpthk.cn/Article/details/gt2jhuoajth.html

[U118] JS：开发服务器
来源：http://dali.nanxuanxn.top/Article/details/gt2yxxckgzd.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gt2khuyagiv.html

[U119] JS：生产构建
来源：http://dali.pengpengdd.cyou/Article/details/gt2gmuygumu.html

npx vite build
来源：http://dali.yangfankeji.com/Article/details/gt2dqxjpnim.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gt2hvrehhrh.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gt2laxywkhz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ecmwnyjz.html

统计汇总
来源：http://dali.xinyue.icu/Article/details/gt2jtsmgqbj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2qypnyvws.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qikhxyvr.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2tajdtfgw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vximaosy.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gt2rcszhsdp.html

TypeScript ..... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2fhbjmxts.html

Java ........... 212
来源：http://dali.guannengcc.top/Article/details/gt2dzjgkprx.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gt2hnvunsvs.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2crowwmvy.html

C# ............. 212
来源：http://dali.0kj1m.cn/Article/details/gt2kfiwfpcp.html

C .............. 30
来源：http://dali.mhx1999.top/Article/details/gt2lqypisck.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gt2qtgnbutn.html

SQL ............ 90
来源：http://dali.cucudq.cn/Article/details/gt2opjbzkxv.html

Bash ........... 80
来源：http://dali.hysaishi.cn/Article/details/gt2rjjdfafi.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gt2banwrcmm.html

Swift .......... 15
来源：http://dali.316326.xyz/Article/details/gt2wbdtfbgh.html

Lua ............ 10
来源：http://dali.sufxvd.cn/Article/details/gt2sgqmskjm.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gt2yycwirpd.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gt2beaxskto.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2hewhmutt.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gt2qjwdnqgl.html

按章节统计：
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogdoutve.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gt2vfpuevce.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2lsynlkdj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gt2qthshqeb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinqigufen.top/Article/details/gt2cwjuutgs.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shzxlz.cn/Article/details/gt2wnfbwfok.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gt2rrfjltsd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2babgrbbc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nanxinkj.top/Article/details/gt2eezqtxcs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2jijnxrbp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2ddnvagvw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gt2bkhjixjj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gt2lvptacmj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2uwxgvffd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gt2asrugqvs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqetqggq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gt2mgevxuxh.html

Q SQL 专题                              90
来源：http://dali.cqqwz.cn/Article/details/gt2dfbjczqi.html

R Bash 专题                             80
来源：http://dali.hnxiangtu.top/Article/details/gt2mgnewath.html

S C / C++ 专题                          60
来源：http://dali.zhengqikj.top/Article/details/gt2otimlbud.html

T 其他语言补充                          60
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itbuooml.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gt2oiumztgt.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2owzvwhvr.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gt2noymsles.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2qfubtkvg.html

使用提醒
来源：http://dali.sufxvd.cn/Article/details/gt2lbjdnxbh.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gt2knjwogpg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gt2byopblsa.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frrgfwls.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jlsjyb.cn/Article/details/gt2zoekhwiu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gt2mhlqnbin.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gt2zhtmhqrn.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptobkbay.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2esnzhksm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.gogol.net.cn/Article/details/gt2zgouikxa.html

Common Programming Examples Cheat Book
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2twesxcpd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2yqhkkxja.html

【收录内容】
来源：http://dali.shuidangran.top/Article/details/gt2krxrradf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.redwolf501.top/Article/details/gt2smxbeovb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.guowangkeji.top/Article/details/gt2bjxnyxzu.html

SQL · Bash · C · C++
来源：http://dali.cheryme.top/Article/details/gt2gjhhdqam.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shzxlz.cn/Article/details/gt2owefjzpj.html

【使用说明】
来源：http://dali.yj202588.top/Article/details/gt2awscrpbe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yangfankeji.com/Article/details/gt2ifeehvce.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.meibo888.top/Article/details/gt2axumiwop.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gt2xtafscmn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinqigufen.top/Article/details/gt2bdefoonu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gt2mtcvorzq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.chenzaomai.com/Article/details/gt2unkfbpwr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.guannengcc.top/Article/details/gt2jaodqtxr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gt2npgsvrbn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gt2wrmcsdqc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gt2famfqvmp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhiwuduotai.top/Article/details/gt2iizwaxxp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvahxxit.html

【文件统计】
来源：http://dali.zhiwuduotai.top/Article/details/gt2kztjyzwj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yangfankeji.com/Article/details/gt2fhulnosh.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwxybjqy.html

目  录
来源：http://dali.ehwqpu.com/Article/details/gt2lhvyclgi.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gt2poqbqsub.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gt2hfxkxtzq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gt2nqvofgra.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hozbcjoc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ouhcsuqz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acsyfsen.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gt2bigofwcm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.pycfn.com/Article/details/gt2tkomftrx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gt2alzrnjrj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gt2bytdqcwh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2fldbdftn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2ttpearmo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gt2wnrjtxfk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cashguo.top/Article/details/gt2occvhbkr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gt2umotagft.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.316326.xyz/Article/details/gt2retavrmo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gt2ndignjpw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.birdmap.top/Article/details/gt2ywrtdzvh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2osulnwfe.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dknypwji.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gt2gpsdxvsu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2ttnadbkj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2cgxdlxlm.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gt2ukovkqpf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2rfecujja.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2sooiftts.html

Py:   print("Hello, World!")
来源：http://dali.jinqigfzy.top/Article/details/gt2yoshdatf.html

PHP:  echo "Hello, World!";
来源：http://dali.chenlongwang.top/Article/details/gt2upesphpf.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkocsbfm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gt2antzgufu.html

Java: System.out.println("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2saxjnfco.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jyoumei.cn/Article/details/gt2fvlgtwsr.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gt2aeqhvpux.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xziqi.cn/Article/details/gt2mbshhinu.html

[A02] 变量声明与赋值
来源：http://dali.quarkkingdee.top/Article/details/gt2zplojqas.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zdqjudy.top/Article/details/gt2xkuzlkjx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2vrtoomdn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ehwqpu.com/Article/details/gt2wskhnwwi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2tjtorhsx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gt2rtkygmvk.html

Go:   name := "Alex"; age := 20
来源：http://dali.redwolf501.top/Article/details/gt2lgxqcvwq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gt2jqbcqjyb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2eskaruvm.html

[A03] 常量定义
来源：http://dali.0kj1m.cn/Article/details/gt2rimqrmru.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.cqqwz.cn/Article/details/gt2vnsmeepq.html

PHP:  const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2hckaxviu.html

JS:   const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2fxbobfpb.html

TS:   const PI: number = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hffizvtq.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2fxfpuzyu.html

Go:   const PI = 3.14159
来源：http://dali.snrcjt.cn/Article/details/gt2kivsjskv.html

Ruby: PI = 3.14159
来源：http://dali.yj20258.top/Article/details/gt2gxkarxei.html

C#:   const double PI = 3.14159;
来源：http://dali.zhengqikj.top/Article/details/gt2uoeqovqp.html

[A04] 判断变量类型
来源：http://dali.xziqi.cn/Article/details/gt2iclgjdcs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gt2nbtagniy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gt2wdcgfmkh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.vqdsnc.cn/Article/details/gt2rckqzijm.html

TS:   typeof x; x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gt2xuwfeadd.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yvedp.cn/Article/details/gt2tupdzgll.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenzaomai.com/Article/details/gt2ewojzsgy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkmwgwxh.html

C#:   x.GetType().Name; x is int
来源：http://dali.redwolf501.top/Article/details/gt2reauarce.html

[A05] 整数除法与取模
来源：http://dali.nanxinkj.top/Article/details/gt2hvccdffn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xinyue.icu/Article/details/gt2zbhkzyhk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2ptfxtdxa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2sysvrxri.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebavfuru.html

Java: 7 / 2; 7 % 2
来源：http://dali.yonumen.top/Article/details/gt2bojgoxeh.html

Go:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gt2wxrocorw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gt2shgtwfmi.html

C#:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2mdwtefiq.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hmhagofz.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gt2sahoqeza.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shzxlz.cn/Article/details/gt2jkiggzmb.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gt2gtvnvfas.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bmdqvuql.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gt2qoeeqaii.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gt2xtfetkhy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.birdmap.top/Article/details/gt2xpgmyeis.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrhuhkuh.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gt2ndziezof.html

Py:   str(42)
来源：http://dali.xziqi.cn/Article/details/gt2uyqsxirs.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rngqevla.html

JS:   String(42); (42).toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2qgjijbii.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gt2vahafwqw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwyhxcxz.html

Go:   strconv.Itoa(42)
来源：http://dali.sweek.top/Article/details/gt2ugrzatje.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gt2cdikmbur.html

C#:   42.ToString()
来源：http://dali.gaohongyu789.top/Article/details/gt2fgmiexrx.html

[A08] 取整与四舍五入
来源：http://dali.ehwqpu.com/Article/details/gt2eamuuwdj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2gnrjkkqn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhoulong.xyz/Article/details/gt2hclddsck.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gt2bhtjqnob.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhoulong.xyz/Article/details/gt2kscgkxzh.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gt2ultpxidz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2paqxjiqy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gt2frqtyjkb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwerzkvf.html

[A09] 绝对值与最大最小值
来源：http://dali.0kj1m.cn/Article/details/gt2qlxutrtd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yonumen.top/Article/details/gt2eqfmpslp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dkozaroj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2xwgdnzvh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2ebxthjmo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeheuavv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxinkj.top/Article/details/gt2keeshxhs.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gt2ehfyxnqd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2arnwfosn.html

[A10] 生成随机数
来源：http://dali.yvedp.cn/Article/details/gt2fzdzmzkh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shzxlz.cn/Article/details/gt2tlunrgsm.html

PHP:  random_int(1, 100);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghhonynd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivpywyfl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gt2puvrqzrw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shzxlz.cn/Article/details/gt2nsvhgiov.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gaohongyu789.top/Article/details/gt2wcndafms.html

Ruby: rand(1..100)
来源：http://dali.redwolf501.top/Article/details/gt2yseqtelo.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigufen.top/Article/details/gt2bqxlertu.html

[A11] 条件表达式（三元）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbgeqcrr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.mhx1999.top/Article/details/gt2vhusqryk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2skjlocbc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gt2yvclwiuf.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2rkgfxdrm.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gt2igwrmiih.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sweek.top/Article/details/gt2pufmvhoz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gt2lmuhhups.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wahpzisr.html

[A12] 字符串插值 / 格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2ftkrcvoa.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gaohongyu789.top/Article/details/gt2cmoyswhw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jianghu66.top/Article/details/gt2wervbxsn.html

JS:   `Hello, ${name}!`
来源：http://dali.yangfankeji.com/Article/details/gt2nwtkgdyn.html

TS:   `Hello, ${name}!`
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdhlqpye.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yuanzhike.top/Article/details/gt2ezeazqwt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yangfankeji.com/Article/details/gt2jydseyas.html

Ruby: "Hello, #{name}!"
来源：http://dali.snrcjt.cn/Article/details/gt2vbcebvot.html

C#:   $"Hello, {name}!"
来源：http://dali.smart0.xyz/Article/details/gt2mngcordn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlepvpbg.html

Py:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2dmsqoayx.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2yxgjevgm.html

JS:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gt2usevgvpz.html

TS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2grnykmat.html

Java: "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhvmbwpw.html

Go:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2pnodgtfz.html

Ruby: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2ccimfxjl.html

C#:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gt2rovrermn.html

[A14] 注释写法
来源：http://dali.zycfv.cn/Article/details/gt2cyhzhipx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xziqi.cn/Article/details/gt2besrgmnb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gt2vmokqpzy.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gt2dsqkqscc.html

TS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gt2isekcgkk.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aibaodan.cn/Article/details/gt2bascfsxw.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gt2ptvqypjt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.daxiang520.top/Article/details/gt2nyxndbmc.html

C#:   // 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2vuxqrnii.html

[A15] 空值判断与默认值
来源：http://dali.shzxlz.cn/Article/details/gt2ffacauvr.html

Py:   value = data or "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyotlefh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gt2sqmaxier.html

JS:   const value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gt2hxzijsnt.html

TS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gt2upqcitrz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jyoumei.cn/Article/details/gt2bsdoihiy.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gzhubu.top/Article/details/gt2eiqjwlak.html

Ruby: value = data || "默认值"
来源：http://dali.hysaishi.cn/Article/details/gt2pslsimny.html

C#:   var value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gt2iykzmyyp.html

[A16] 真假值判断规则
来源：http://dali.9152youxi.cn/Article/details/gt2aruksanf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.iojbl.cn/Article/details/gt2wsemkkvx.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hammf.cn/Article/details/gt2tbjanqkc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.havefunace.top/Article/details/gt2vaklualc.html

TS:   if (!x) {}
来源：http://dali.fzhhl.top/Article/details/gt2bzjtwxhr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yueranfly.top/Article/details/gt2pzguecde.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sxryk.cn/Article/details/gt2gmwnxalx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgufenzy.top/Article/details/gt2uoiuczty.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sweek.top/Article/details/gt2qtcyjolg.html

[A17] 位运算
来源：http://dali.dashuyun.cn/Article/details/gt2isvgoupa.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2apaivraa.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gogol.net.cn/Article/details/gt2omomcaub.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2tdjperxx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gt2iruyyozo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gt2guzfafau.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2vbypvrby.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2tseflapf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2sacowiii.html


<!-- 参考信息 -->