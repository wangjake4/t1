代发 wailian999

[U105] JS：节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtkicsghkt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daria6918.cn/Article/details/gtlhujnbuz.html

[U106] JS：日期格式化
来源：http://dali.iojbl.cn/Article/details/gtyukjxmpo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gtzbfjxbqk.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtxmwoqjxi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtjtefysqi.html

[U108] JS：随机整数
来源：http://dali.aizwys.cn/Article/details/gtdvlolusy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gzhubu.top/Article/details/gtmouqrzmv.html

[U109] JS：数组分组
来源：http://dali.yj20258.top/Article/details/gtejfaohcf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.svipenyu.cn/Article/details/gtywdlgblg.html

[U110] JS：数组分块
来源：http://dali.yvedp.cn/Article/details/gtbqhaetto.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gtbrxauoxk.html

[U111] JS：对象转 Map
来源：http://dali.xinyue.icu/Article/details/gtknzwygyf.html

new Map(Object.entries(obj))
来源：http://dali.c1oappe.top/Article/details/gtabxljwms.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gtpdufmuor.html

"7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtaivebowm.html

[U113] JS：正则替换全部
来源：http://dali.vqdsnc.cn/Article/details/gtkcvapcim.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtqrcwhmpl.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gtotnjqobn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtkeeyjhbr.html

[U115] JS：生成 UUID
来源：http://dali.pycfn.com/Article/details/gtqvpdhrjc.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtsithyubn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtzlfchhpt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtloqwftyw.html

[U117] JS：单元测试
来源：http://dali.chenlongwang.top/Article/details/gtvvhrbzjl.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gttpqpoxes.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gtkroamdrz.html

npm i -D vite;  npx vite
来源：http://dali.xuetiantiany.cn/Article/details/gtgqzhuaot.html

[U119] JS：生产构建
来源：http://dali.jyoumei.cn/Article/details/gtqauwrlqv.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gtwmueutde.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cdnleiting.top/Article/details/gtkzzsilgz.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtoujsmjah.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtqvbzgfpe.html

统计汇总
来源：http://dali.yueranfly.top/Article/details/gthbkjuodz.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtngedoeqf.html

按语言统计（条）：
来源：http://dali.0kj1m.cn/Article/details/gtrfzjxmen.html

Python ......... 252
来源：http://dali.sufxvd.cn/Article/details/gtpuzmitbk.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gtsbrdxyev.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gtautyllqo.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gtbevmwtvt.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gthcuobenv.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gtguzlkats.html

Ruby ........... 212
来源：http://dali.ehwqpu.com/Article/details/gtsfsdgdvn.html

C# ............. 212
来源：http://dali.aibaodan.cn/Article/details/gtydqenjrf.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gtfomepwxg.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtwlzlmhru.html

SQL ............ 90
来源：http://dali.chenzaomai.com/Article/details/gtmoqycffv.html

Bash ........... 80
来源：http://dali.feifeiyinyue.top/Article/details/gtikdsecvi.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtiqapacvx.html

Swift .......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtuunlwtdp.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gtzarszbog.html

Perl ........... 10
来源：http://dali.iojbl.cn/Article/details/gtjpizvhur.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtxheebnir.html

------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtdiwlbxra.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtzmifgtui.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtivlttkji.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtkvovemcy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtzcqinkuz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtsnvilssj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtujixbgry.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gotoacloud.top/Article/details/gtzwgwyopi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gthsrbqwbk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jqgfzy.top/Article/details/gtawbjmsfk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daxiang520.top/Article/details/gtoemzvevr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gtwavhexpz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtsmylloso.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtssbzwyat.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclvmdcgd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtormdfwjz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtrldroiby.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhixingplan.top/Article/details/gtfdezetzs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtopxcufgi.html

Q SQL 专题                              90
来源：http://dali.zhengqikj.top/Article/details/gtkstkygwg.html

R Bash 专题                             80
来源：http://dali.jlsjyb.cn/Article/details/gtmovuroax.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gticfgkwgl.html

T 其他语言补充                          60
来源：http://dali.mhx1999.top/Article/details/gtlfdtcscg.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gtoigwrfjp.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtezilnfbi.html

合计                                  2106 条
来源：http://dali.fengsongda.top/Article/details/gtnpvtwdgh.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtrhrqxekg.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtspxgbfbl.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtovhucmxu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtiottllsb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gtivddpnjy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtfztlbkap.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gtozbdvcxp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gtdcbvaves.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvabdybf.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjiviftuf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.c1oappe.top/Article/details/gtvtcccpjg.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gtergyfsfx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtrcpkpdmg.html

【收录内容】
来源：http://dali.cucudq.cn/Article/details/gtdckpyaug.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yangfankeji.com/Article/details/gttzldwqvs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shangyingyoupin.top/Article/details/gttdiqtyfs.html

SQL · Bash · C · C++
来源：http://dali.wangdashe.top/Article/details/gtzjzzvrrd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.redwolf501.top/Article/details/gtwdawacse.html

【使用说明】
来源：http://dali.yj202588.top/Article/details/gthcbxccfe.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gtxrecvrgs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtxtboidwi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gtafxenvmz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpmdyrzv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gtwbugqpuk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ehwqpu.com/Article/details/gtedszyknz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtdgsantjj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvhslihm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yangfankeji.com/Article/details/gtrifuntho.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqdnvcub.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jlsjyb.cn/Article/details/gtwlpgbbwf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvwublbp.html

【文件统计】
来源：http://dali.zhongyouzk.top/Article/details/gtrpjtwhmn.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cashguo.top/Article/details/gtembvdmzi.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtgkogibvz.html

目  录
来源：http://dali.shzxlz.cn/Article/details/gtvcaeygbg.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gtoiigqnoz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gterhliifs.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtxkfnaksv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgxxcemc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtvrgqyrug.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hnqzz.top/Article/details/gtpyqrkgja.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtqdjazqbs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gthjunbaza.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtgsmuhuav.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gtogcxmjxc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yj20258888.top/Article/details/gtiassbdgr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtqshtybru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtospckjvc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylbamnaq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtcwqtnvqm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrkfshro.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gturhcxwtg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gtftqjtvip.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtelmwnebx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gtrjmhukzk.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gthfwukkgp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj202588.top/Article/details/gtpqmyfazm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtywmbzbjo.html

A. 基础语法与类型
来源：http://dali.yvedp.cn/Article/details/gtkoqxnrod.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrlpmwuca.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gtqeyfmwsj.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtfktgsweu.html

PHP:  echo "Hello, World!";
来源：http://dali.pengpengdd.cyou/Article/details/gtqcgwvaal.html

JS:   console.log("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtldyqsboq.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gtbgfgyjrd.html

Java: System.out.println("Hello, World!");
来源：http://dali.iojbl.cn/Article/details/gtripeiblt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtdqdesjbg.html

Ruby: puts "Hello, World!"
来源：http://dali.tian-w.cn/Article/details/gtnxtxnkdx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gtqmktuyst.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gtvkpyahnq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gzhubu.top/Article/details/gtqivvxumo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtzhnfjxpv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hysaishi.cn/Article/details/gtwgedudie.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj202588.top/Article/details/gthhtqlhrf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cheryme.top/Article/details/gtvkexhhkw.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtakkcwzsb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gtwjwhudxw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtvaeubbds.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzzdliyf.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.meibo888.top/Article/details/gtdatokomf.html

PHP:  const PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtghyqwvho.html

JS:   const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtqgzjdlex.html

TS:   const PI: number = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtlfzwrouj.html

Java: static final double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gthxzjxunq.html

Go:   const PI = 3.14159
来源：http://dali.jqgfzy.top/Article/details/gtormsqyiz.html

Ruby: PI = 3.14159
来源：http://dali.jinqigfzy.top/Article/details/gtgfgoqqyp.html

C#:   const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gthwbefnpu.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gtixqwgdtu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtpbgcpdti.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gtibtoocuu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dashuyun.cn/Article/details/gtmnycelcf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfocirbfc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zycfv.cn/Article/details/gtqbywxccf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigfzy.top/Article/details/gtcxiplfnq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jyoumei.cn/Article/details/gtqjjtzvtm.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gthlztavgi.html

[A05] 整数除法与取模
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjauseaa.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gtdvfmkyqm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtfaqpivfc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtqzesjexj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gtiakqacfi.html

Java: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtyxkukiwe.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtlbeddetu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtuolvbcld.html

C#:   7 / 2; 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtewujkmdd.html

[A06] 字符串转数字
来源：http://dali.cashguo.top/Article/details/gtymheilpr.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtmprhfvva.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlresgphj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cdnleiting.top/Article/details/gtueirvbmi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gtqvkuoedy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtzzisubsl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.svipenyu.cn/Article/details/gtcofeycrm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gtugcdlpte.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.fengsongda.top/Article/details/gtdimbwvjy.html

[A07] 数字转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtupqarmtv.html

Py:   str(42)
来源：http://dali.cashguo.top/Article/details/gtpjnhqtdb.html

PHP:  (string) 42; strval(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtytvhirpx.html

JS:   String(42); (42).toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpmrcmqg.html

TS:   String(42)
来源：http://dali.cqqwz.cn/Article/details/gtjydfuggt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyimtyru.html

Go:   strconv.Itoa(42)
来源：http://dali.gogol.net.cn/Article/details/gtguxtvsra.html

Ruby: 42.to_s
来源：http://dali.shanyushiyangtech.top/Article/details/gttxybeyet.html

C#:   42.ToString()
来源：http://dali.yuxming.cn/Article/details/gtabjpovze.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gtnpmvkjup.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtvxzfsugp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shangyingyoupin.top/Article/details/gtrfznlqcv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtjatnnovh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ivvv.top/Article/details/gtuwkfjgzl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtrkxxfeip.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtnkmllapl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xziqi.cn/Article/details/gtmizzdoup.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtqksytopz.html

[A09] 绝对值与最大最小值
来源：http://dali.bjfxy.top/Article/details/gtffepmsmb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtaxuqmikl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtmhvwkesf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hammf.cn/Article/details/gtqjuwoiyj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtqxvsayik.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtofbfgezk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gthvgphzzh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jinqigufen.top/Article/details/gtnakjhiqe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtosqyemkc.html

[A10] 生成随机数
来源：http://dali.yvedp.cn/Article/details/gtpvdoiwwy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.quarkkingdee.top/Article/details/gtrrrgmzio.html

PHP:  random_int(1, 100);
来源：http://dali.9152youxi.cn/Article/details/gtjrtcdrix.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gteydvihuj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.havefunace.top/Article/details/gtsrujetzq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtvvfnldls.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ehwqpu.com/Article/details/gtelrpvrkm.html

Ruby: rand(1..100)
来源：http://dali.gotoacloud.top/Article/details/gtxmarwlls.html

C#:   new Random().Next(1, 101)
来源：http://dali.guowangkeji.top/Article/details/gtmrmwhjtd.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbigruciq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.mhx1999.top/Article/details/gtnpjrodrt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhongyouzk.top/Article/details/gtmmdeeigu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gthuynxtwk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtbaxhbbxn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtypnwebrf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.snrcjt.cn/Article/details/gtiizpzakh.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtbpvkgwcb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtisxbcwob.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj20258888.top/Article/details/gtodqlgoxy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shzxlz.cn/Article/details/gtrruvaagg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhoulong.xyz/Article/details/gtvhihamni.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gtjewpbquz.html

TS:   `Hello, ${name}!`
来源：http://dali.jianghu66.top/Article/details/gtcknspdkq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gotoacloud.top/Article/details/gtfpkxxips.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gaohongyu789.top/Article/details/gtyacuttfb.html

Ruby: "Hello, #{name}!"
来源：http://dali.daxiang520.top/Article/details/gtuixmqhpy.html

C#:   $"Hello, {name}!"
来源：http://dali.zhiwuduotai.top/Article/details/gteaeawktx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhixingplan.top/Article/details/gtrczipsos.html

Py:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtefkejhch.html

PHP:  "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gtizlrtfam.html

JS:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtzdbeecat.html

TS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtpyprpyba.html

Java: "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtfjlpugtt.html

Go:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtmfqjkwuv.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtkcsxwvch.html

C#:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtevtduuih.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gtlwtawvri.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gotoacloud.top/Article/details/gtkasxmqrh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvdmglnw.html

JS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gthdtpmckn.html

TS:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gthbqwldur.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.vqdsnc.cn/Article/details/gttqfeonvj.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtiwiqbnim.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenjidiqi.icu/Article/details/gtsfoymcxw.html

C#:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gtpbabtahx.html

[A15] 空值判断与默认值
来源：http://dali.hammf.cn/Article/details/gtfskymckd.html

Py:   value = data or "默认值"
来源：http://dali.9152youxi.cn/Article/details/gtuwydzbng.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gtajzixpka.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtecbxpkul.html

TS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gtrgiyylbx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xylfe.cn/Article/details/gtqchwrxno.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.smart0.xyz/Article/details/gtixiqsmiy.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gtygnirjxo.html

C#:   var value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtmdldezvo.html

[A16] 真假值判断规则
来源：http://dali.jlsjyb.cn/Article/details/gtqotpkhqt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yongpay.top/Article/details/gtffjplzwc.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jiagoushi.top/Article/details/gtfhfssazl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gtlbdscujo.html

TS:   if (!x) {}
来源：http://dali.iojbl.cn/Article/details/gteeuqaiki.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cqqwz.cn/Article/details/gtquwfngha.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sufxvd.cn/Article/details/gttnumtjgm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zdqjudy.top/Article/details/gtcznftdzk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuxming.cn/Article/details/gttkreewqn.html

[A17] 位运算
来源：http://dali.pycfn.com/Article/details/gtiwavjxje.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlpsnrhg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daxiang520.top/Article/details/gtpukkcuak.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtyzttxeha.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtafdobfuj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtxvvjijxa.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtamnntsei.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gttgfqxmdh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtrgadlxlu.html

[A18] 字符与 ASCII 码互转
来源：http://dali.fengsongda.top/Article/details/gtgfcjsive.html

Py:   ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gtsswkmjqr.html

PHP:  ord("A"); chr(65)
来源：http://dali.ppjwa.cn/Article/details/gtzsxrfbeh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yonumen.top/Article/details/gtcztgibxy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtfkjusyge.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigufen.top/Article/details/gtrfrbciqc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jianghu66.top/Article/details/gtbajjvzpc.html

Ruby: "A".ord; 65.chr
来源：http://dali.yvedp.cn/Article/details/gtdpavcugq.html


<!-- 参考信息 -->