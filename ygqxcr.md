代发 wailian999

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gt2ebapyazc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gt2zcstkink.html

[U106] JS：日期格式化
来源：http://dali.yj20258.top/Article/details/gt2gaxnsygb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhongyouzk.top/Article/details/gt2brxopkte.html

[U107] JS：数字千分位
来源：http://dali.havefunace.top/Article/details/gt2skdpaovz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gt2rnewxtit.html

[U108] JS：随机整数
来源：http://dali.yonumen.top/Article/details/gt2bkggvnao.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efmtdhtp.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gt2zwfervcn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gt2jsxpzvla.html

[U110] JS：数组分块
来源：http://dali.jiagoushi.top/Article/details/gt2vohxmcuk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gt2nbnyhxyi.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gt2xjagxiik.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2qeartrox.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gt2iansbwqp.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gt2bbxmdqtw.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gt2bkxwxrym.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gt2oidxveox.html

[U114] JS：JSON 深比较
来源：http://dali.sweek.top/Article/details/gt2uotjcfol.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2ckvqmumi.html

[U115] JS：生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gt2tuarmfvi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uoadkpao.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.chenlongwang.top/Article/details/gt2ebeducyt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gt2wlsvpbxc.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gt2reczhpmj.html

npm i -D vitest;  npx vitest
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkvevvyf.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2hobuvxjj.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gt2obefxsqs.html

[U119] JS：生产构建
来源：http://dali.hywenlv.cn/Article/details/gt2bugbmmer.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gt2blkvtzoa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gt2rovyyfel.html

import.meta.env.VITE_API_URL
来源：http://dali.yvedp.cn/Article/details/gt2aoyrzooe.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2gfrcdrkm.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gt2tplgxdga.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wpxvuust.html

按语言统计（条）：
来源：http://dali.guowangkeji.top/Article/details/gt2rdedxysb.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gt2zackhasb.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gt2hiywlmsg.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gt2gjhivzwx.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gt2pbpjpawb.html

Java ........... 212
来源：http://dali.ehwqpu.com/Article/details/gt2adlnamgg.html

Go ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gt2omgvpkac.html

Ruby ........... 212
来源：http://dali.yj202588.top/Article/details/gt2qvfqylaj.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2wesicjhh.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gt2tplilzui.html

C++ ............ 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxcybbok.html

SQL ............ 90
来源：http://dali.zycfv.cn/Article/details/gt2wqruwtin.html

Bash ........... 80
来源：http://dali.yj202588.top/Article/details/gt2fpimogim.html

Kotlin ......... 15
来源：http://dali.haohaochexian.top/Article/details/gt2eaiddyeh.html

Swift .......... 15
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmhhnkfr.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gt2kgefbxri.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gt2mqfbwrly.html

Scala .......... 10
来源：http://dali.xuanzx.com/Article/details/gt2pgjmgxwa.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gt2lwwzvkng.html

合计 ........... 2106 条
来源：http://dali.cheryme.top/Article/details/gt2ttyskrqu.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gt2pczkzbet.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gt2osfukkal.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gt2pymdrmqn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gt2yrormuwl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gt2wpjzatqm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.havefunace.top/Article/details/gt2cpqiibtt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gt2yxbelfyt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2bfyenqyx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gt2tzdvsavb.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2hxtebjso.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2beiwiemc.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gt2qnipactc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2xzgsjlip.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gt2euhauzfc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gt2foanqyzq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrlrbxkg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gt2gllfiqgg.html

Q SQL 专题                              90
来源：http://dali.chenjidiqi.icu/Article/details/gt2wbdcxxjn.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gt2gwydsjec.html

S C / C++ 专题                          60
来源：http://dali.yangfankeji.com/Article/details/gt2jfjyflvw.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gt2otdhrktn.html

U 高频实用片段                         120
来源：http://dali.redwolf501.top/Article/details/gt2qqiglica.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2nxfuiprc.html

合计                                  2106 条
来源：http://dali.yj202588.top/Article/details/gt2hhztzniw.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2rjrdkooy.html

使用提醒
来源：http://dali.hammf.cn/Article/details/gt2wqzccbaa.html

--------------------------------------------------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2wzgaqbdp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hfpthk.cn/Article/details/gt2rhnnqbpm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gt2xwohefys.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.dashuyun.cn/Article/details/gt2pqnajkas.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.andypj.xyz/Article/details/gt2ajorpiji.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cdnleiting.top/Article/details/gt2fjoduzye.html

—— 文件结束 ——
来源：http://dali.cashguo.top/Article/details/gt2khcbqrwd.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2kosobxxb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cdnleiting.top/Article/details/gt2iugztcyd.html

Common Programming Examples Cheat Book
来源：http://dali.9152youxi.cn/Article/details/gt2jlgukyyf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2rqkvuegy.html

【收录内容】
来源：http://dali.aibaodan.cn/Article/details/gt2bzpihkcf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcliwxnr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daria6918.cn/Article/details/gt2qsnsxctr.html

SQL · Bash · C · C++
来源：http://dali.ppjwa.cn/Article/details/gt2yqrglytr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ivvv.top/Article/details/gt2xaovzlhp.html

【使用说明】
来源：http://dali.shuidangran.top/Article/details/gt2gomqrspa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.iojbl.cn/Article/details/gt2wdaqktqf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ppjwa.cn/Article/details/gt2jtyxyddm.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gt2mghbwwet.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.quarkkingdee.top/Article/details/gt2htnyesho.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ckytmpuf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhixingplan.top/Article/details/gt2bfunwpcz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ehwqpu.com/Article/details/gt2wiscwnzp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gt2rropfyfl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gt2lmgxhyot.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.c1oappe.top/Article/details/gt2hkxwekrq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.redwolf501.top/Article/details/gt2tnomfsxq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.aizwys.cn/Article/details/gt2sglrutve.html

【文件统计】
来源：http://dali.cucudq.cn/Article/details/gt2vqpcipyl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.pycfn.com/Article/details/gt2oicvuwqy.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2xhptgtru.html

目  录
来源：http://dali.hammf.cn/Article/details/gt2tuufumyg.html

--------------------------------------------------------------------------------
来源：http://dali.shzxlz.cn/Article/details/gt2snzukvtr.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2cbrcymuj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yonumen.top/Article/details/gt2zoskspal.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2mgulemxq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gt2lnfhkepw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.havefunace.top/Article/details/gt2odfysodr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gt2odrhpahk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2jvzjilep.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.daria6918.cn/Article/details/gt2nqbnkvzk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyjvewkp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gt2aqvtubpt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2fbvgorvo.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2nurawnpa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gt2wqlwutmi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cashguo.top/Article/details/gt2hcngmnns.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yj20258.top/Article/details/gt2qbarieos.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2rdrtabuf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cdnleiting.top/Article/details/gt2wxtfklea.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shzxlz.cn/Article/details/gt2afhxqjoj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.mhx1999.top/Article/details/gt2whaolclu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gt2ayymithe.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbyamuyy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fryahssh.html

A. 基础语法与类型
来源：http://dali.jianghu66.top/Article/details/gt2joodzthj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2sstxbvjd.html

[A01] Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2ruylrgvr.html

Py:   print("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gt2zeccabho.html

PHP:  echo "Hello, World!";
来源：http://dali.zdqjudy.top/Article/details/gt2xxpdvlqr.html

JS:   console.log("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gt2zkbphxbs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sysykeji.top/Article/details/gt2efdggbdq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rehrnrfl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gt2siyfmktc.html

Ruby: puts "Hello, World!"
来源：http://dali.xziqi.cn/Article/details/gt2htcuybut.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2jzmatska.html

[A02] 变量声明与赋值
来源：http://dali.nanxuanxn.top/Article/details/gt2fhkvalka.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gt2niutdlmk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ppjwa.cn/Article/details/gt2xlljprdi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenzaomai.com/Article/details/gt2xnizyiqb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.andypj.xyz/Article/details/gt2mqowtfba.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2izvfvstk.html

Go:   name := "Alex"; age := 20
来源：http://dali.gaohongyu789.top/Article/details/gt2ziizdjae.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yuxming.cn/Article/details/gt2tvirvpen.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.nanxuanxn.top/Article/details/gt2zpnzvmbr.html

[A03] 常量定义
来源：http://dali.chenlongwang.top/Article/details/gt2rphowjcb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.quarkkingdee.top/Article/details/gt2rjnsuxxl.html

PHP:  const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2qfvvdmfv.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gt2nrdtnycp.html

TS:   const PI: number = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2wesoxjcv.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2iwehmlfi.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gt2iwqrpqan.html

Ruby: PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gt2hwaokroh.html

C#:   const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2dtgmqkgm.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vbailjhg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2emcvelvd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.mhx1999.top/Article/details/gt2pgimaysp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuxming.cn/Article/details/gt2lgbjarkg.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gt2gzolwprv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yueranfly.top/Article/details/gt2gpyhxdsc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgfzy.top/Article/details/gt2kbizvzfv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.nanxuanxn.top/Article/details/gt2pxlhgdaq.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gt2oejrwcos.html

[A05] 整数除法与取模
来源：http://dali.gotoacloud.top/Article/details/gt2naiwkzbo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yangfankeji.com/Article/details/gt2ktqrieci.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gt2ecbcrvqi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2hgqcquni.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2btubpfns.html

Java: 7 / 2; 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gt2dydnlanf.html

Go:   7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gt2zlglvgcv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2fmkcxmor.html

C#:   7 / 2; 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqpfbioo.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2yejiojjg.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gt2scdwmpby.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gt2wteglpwj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gt2uulnofax.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gt2edkvdujb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.guowangkeji.top/Article/details/gt2whdmufuf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yongpay.top/Article/details/gt2zrinjfkm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tian-w.cn/Article/details/gt2sqzvwnsz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gt2fzpuzubt.html

[A07] 数字转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2fobwoghb.html

Py:   str(42)
来源：http://dali.gotoacloud.top/Article/details/gt2ixuimuvt.html

PHP:  (string) 42; strval(42)
来源：http://dali.yvedp.cn/Article/details/gt2kbwblmxd.html

JS:   String(42); (42).toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgqwsxnf.html

TS:   String(42)
来源：http://dali.yonumen.top/Article/details/gt2hrpjwlwp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuanzx.com/Article/details/gt2ewwgrsfp.html

Go:   strconv.Itoa(42)
来源：http://dali.birdmap.top/Article/details/gt2lkgngkpg.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfjirhnp.html

C#:   42.ToString()
来源：http://dali.andypj.xyz/Article/details/gt2xjyrktny.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gt2vollfcws.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gt2iwdscgpo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinqigfzy.top/Article/details/gt2wvpvrqan.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2aejgoiol.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gt2ihizrrle.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2zkdsltbq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gt2ishllcbi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jianghu66.top/Article/details/gt2cevsecwz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gt2axslqkve.html

[A09] 绝对值与最大最小值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukzeujyd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2cicqkxgn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2rozdsxgd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tanke756.top/Article/details/gt2vbwfwyqj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qchzzwdh.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2yjjidpzi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj20258888.top/Article/details/gt2iyaicbad.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.andypj.xyz/Article/details/gt2ttfwgbbq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2vzcesklf.html

[A10] 生成随机数
来源：http://dali.bjfxy.top/Article/details/gt2zwujcihb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.meibo888.top/Article/details/gt2fwbajudk.html

PHP:  random_int(1, 100);
来源：http://dali.ydzc1.top/Article/details/gt2lfzhtcbb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gt2bfqdurbw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zycfv.cn/Article/details/gt2yclvfznd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.snrcjt.cn/Article/details/gt2czuhtnmc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yvedp.cn/Article/details/gt2dpfmhqjh.html

Ruby: rand(1..100)
来源：http://dali.zhoulong.xyz/Article/details/gt2vtjdsjli.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gt2yzhypady.html

[A11] 条件表达式（三元）
来源：http://dali.jiagoushi.top/Article/details/gt2leyyqtxa.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.316326.xyz/Article/details/gt2gyarwmdb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2igkqzgse.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gt2vceuqsnq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2eposbrks.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2hmtghgmb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2zndvdfmn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gt2npcepcem.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gt2todowxow.html

[A12] 字符串插值 / 格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tojwfpti.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenzaomai.com/Article/details/gt2axymwukf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gt2sdxfucst.html

JS:   `Hello, ${name}!`
来源：http://dali.havefunace.top/Article/details/gt2mmqcymfd.html

TS:   `Hello, ${name}!`
来源：http://dali.kuanghao11.cn/Article/details/gt2kwtnnptr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258888.top/Article/details/gt2vsmybjuv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.svipenyu.cn/Article/details/gt2hjvigotn.html

Ruby: "Hello, #{name}!"
来源：http://dali.c1oappe.top/Article/details/gt2zkonqaby.html

C#:   $"Hello, {name}!"
来源：http://dali.jqgufenzy.top/Article/details/gt2nwuvgwub.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ybcxt.top/Article/details/gt2zeabfgqt.html

Py:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gt2csjownkm.html

PHP:  "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2mrxxyznv.html

JS:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gt2jetzhrxe.html

TS:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2mmblyxlw.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2uzqfjjng.html

Go:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gt2azyhkryf.html

Ruby: "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gt2vqwezjnl.html

C#:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gt2gcgrwywb.html

[A14] 注释写法
来源：http://dali.guowangkeji.top/Article/details/gt2aqenjhup.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ivvv.top/Article/details/gt2yzvslgxs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gt2vqgufmvf.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2qyukmhkm.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2qsgwrdbn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.feifeiyinyue.top/Article/details/gt2rukrowef.html

Go:   // 单行；/* 多行 */
来源：http://dali.pengpengdd.cyou/Article/details/gt2bvtbeyfh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.xylfe.cn/Article/details/gt2hiokwczb.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqtrjaya.html

[A15] 空值判断与默认值
来源：http://dali.wangdashe.top/Article/details/gt2mjnvcuyx.html

Py:   value = data or "默认值"
来源：http://dali.shuidangran.top/Article/details/gt2yelpqods.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gt2kiwllavi.html

JS:   const value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gt2jkquxuak.html

TS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gt2pswuzpjm.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.guannengcc.top/Article/details/gt2xtfmyctr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj202588.top/Article/details/gt2hjxipxpy.html

Ruby: value = data || "默认值"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibxvvskf.html

C#:   var value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gt2brbdtsqk.html

[A16] 真假值判断规则
来源：http://dali.aibaodan.cn/Article/details/gt2ijmlgbva.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2btivshwh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tian-w.cn/Article/details/gt2ltkedolh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuxming.cn/Article/details/gt2vmczvrhc.html

TS:   if (!x) {}
来源：http://dali.svipenyu.cn/Article/details/gt2lhrofmss.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2gwjbyble.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhengqikj.top/Article/details/gt2cvjormak.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gzhubu.top/Article/details/gt2tnnksmtb.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2qeibbnjs.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gt2qksnyzlj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2zgurfbhz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zfmtgntw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gt2eljbxccw.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2nsuvhydy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2arnqtejo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2nsplgxwm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gt2tasnrzlm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2cuxrbcen.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jinqigfzy.top/Article/details/gt2ezeqvctz.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gt2nemwmyqp.html

PHP:  ord("A"); chr(65)
来源：http://dali.zdqjudy.top/Article/details/gt2qiuazfhk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gt2oqrozgtv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daria6918.cn/Article/details/gt2cqhkexrv.html

Java: (int) 'A'; (char) 65
来源：http://dali.ydzc1.top/Article/details/gt2zlpzpzdy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hongshengwenyu.top/Article/details/gt2ajanprpb.html

Ruby: "A".ord; 65.chr
来源：http://dali.jqgufenzy.top/Article/details/gt2wrhmakxz.html


<!-- 参考信息 -->