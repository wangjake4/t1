代发 wailian999

[U99] JS：事件监听
来源：http://dali.fzhhl.top/Article/details/gtrjscwqhv.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gtkxqirfze.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gtrvsovpxo.html

document.querySelector(".item")
来源：http://dali.chenzaomai.com/Article/details/gthouwkzzy.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbggmjme.html

el.classList.toggle("active")
来源：http://dali.zhongyouzk.top/Article/details/gthfmjxxjx.html

[U102] JS：本地存储
来源：http://dali.xuanzx.com/Article/details/gtsmaedkuz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gogol.net.cn/Article/details/gteacrfdsf.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtwvoktpcm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cqqwz.cn/Article/details/gtzhxdldwv.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gtacrrmhrc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtwlfkdgrx.html

[U105] JS：节流
来源：http://dali.vqdsnc.cn/Article/details/gtmhbldizd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shuidangran.top/Article/details/gthmvmixmu.html

[U106] JS：日期格式化
来源：http://dali.yuxming.cn/Article/details/gtuiqdkldp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jlsjyb.cn/Article/details/gtpbvihkbq.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtbgbzpxfz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtnhjubops.html

[U108] JS：随机整数
来源：http://dali.xuetiantiany.cn/Article/details/gtndfgcsjr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ehwqpu.com/Article/details/gtbqqnngts.html

[U109] JS：数组分组
来源：http://dali.0kj1m.cn/Article/details/gtzkdxjrtj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gtfpmbxdyn.html

[U110] JS：数组分块
来源：http://dali.havefunace.top/Article/details/gtwxmxxipo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.birdmap.top/Article/details/gtorpqojyf.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gtscypyvdg.html

new Map(Object.entries(obj))
来源：http://dali.pengpengdd.cyou/Article/details/gtrbbjldkx.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtuuczwhnd.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtdrgppycp.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gtrpphkpuj.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtrzqqrzlr.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtskbagqux.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gtxiiduxpj.html

[U115] JS：生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtadfnoykm.html

crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtbppmdcnj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jiagoushi.top/Article/details/gtfuhrbzbv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cashguo.top/Article/details/gtjvqqtydf.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gtzohnoigq.html

npm i -D vitest;  npx vitest
来源：http://dali.vqdsnc.cn/Article/details/gtajwjnvtl.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtyquyafqp.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gtkplwgjtw.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtvrruwxhm.html

npx vite build
来源：http://dali.hammf.cn/Article/details/gtxuxkzxaz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cqqwz.cn/Article/details/gtiacfhtyw.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gthrozzftr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtslfmyslf.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gtdfnxguql.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfoouujyp.html

按语言统计（条）：
来源：http://dali.aibaodan.cn/Article/details/gtdyznsyvi.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnhybbca.html

PHP ............ 252
来源：http://dali.hywenlv.cn/Article/details/gtbkmpraua.html

JavaScript ..... 252
来源：http://dali.xziqi.cn/Article/details/gtnrtgswvi.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gtpuzodtut.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxowapjn.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtqjbccizu.html

Ruby ........... 212
来源：http://dali.andypj.xyz/Article/details/gtwowerdro.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtibezqshp.html

C .............. 30
来源：http://dali.cheryme.top/Article/details/gtczhtfkjx.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gteyxhxrrk.html

SQL ............ 90
来源：http://dali.shangyingyoupin.top/Article/details/gtfowjpaho.html

Bash ........... 80
来源：http://dali.shangyingyoupin.top/Article/details/gtjoubjlnp.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtfunlsxaj.html

Swift .......... 15
来源：http://dali.jianghu66.top/Article/details/gtneanpzbu.html

Lua ............ 10
来源：http://dali.jinqigufen.top/Article/details/gtpgknajmb.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtdvplsvxh.html

Scala .......... 10
来源：http://dali.pycfn.com/Article/details/gteyxvxqzr.html

------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtcolwttwn.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gtlupbsblu.html

按章节统计：
来源：http://dali.hywenlv.cn/Article/details/gtqxceapuz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gtseheogmn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtpbqnynyi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gthqqlzrwx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtapzvzkew.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gtzlxjuxnx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gtckysowyf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtollbrujy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvadbjpce.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtclnpdwim.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtifcdeyds.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtapipusmb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtllmpyjrf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gteaefxcsk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gtfybzkksq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuxming.cn/Article/details/gtqyoudgim.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtjwzbpvpq.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisyutscl.html

R Bash 专题                             80
来源：http://dali.hnxiangtu.top/Article/details/gtlkvwwudj.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gtlzbgkeyl.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtorqxyoni.html

U 高频实用片段                         120
来源：http://dali.zdqjudy.top/Article/details/gtyzgpdkce.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtghryduar.html

合计                                  2106 条
来源：http://dali.jinqigfzy.top/Article/details/gtrikedndw.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtrjubryox.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtyapquocc.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtnxgpxxea.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hongshengwenyu.top/Article/details/gtjboyranr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shzxlz.cn/Article/details/gtcsrsswkt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.meibo888.top/Article/details/gtkgtxuydz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.hnxiangtu.top/Article/details/gtjdnsyxob.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinghuilouyu.cn/Article/details/gtrapvutuv.html

—— 文件结束 ——
来源：http://dali.daria6918.cn/Article/details/gturbmgilj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdztxpyde.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gtyiqetvjx.html

Common Programming Examples Cheat Book
来源：http://dali.mhx1999.top/Article/details/gtarfwuain.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtrlccoirf.html

【收录内容】
来源：http://dali.yj202588.top/Article/details/gtwctvqqqm.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gtzpdaovcp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gtxrqomqpi.html

SQL · Bash · C · C++
来源：http://dali.pengpengdd.cyou/Article/details/gtoakdtkkv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.guannengcc.top/Article/details/gtdlmbijmu.html

【使用说明】
来源：http://dali.cheryme.top/Article/details/gtujcawmsm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fengsongda.top/Article/details/gtdehoyvxe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtvyaymjit.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aibaodan.cn/Article/details/gtsxlbjdxn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhongyouzk.top/Article/details/gtkakmhyfu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhiwuduotai.top/Article/details/gtepebnzko.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ydzc1.top/Article/details/gtxfvvxjyx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gthmninzaq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.jinqigufen.top/Article/details/gtwkhpknps.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtmhxqmqpz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sweek.top/Article/details/gtpzxzcljs.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.wangshuangyany.cn/Article/details/gtwpukfraa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pycfn.com/Article/details/gtjslrbuwx.html

【文件统计】
来源：http://dali.yueranfly.top/Article/details/gtszjbsfow.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gtbxhewblr.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gtschwcrap.html

目  录
来源：http://dali.yuxming.cn/Article/details/gtfeozoeez.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtwgvxolmo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.andypj.xyz/Article/details/gtfwiaicvj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gtkcjzlwig.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtutbnfwbi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gtcgorlyiu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhengqikj.top/Article/details/gtsxclxxqu.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtvlwxqoee.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtmvpstbpb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvavcsjkq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gtbgwreslc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gtazrpbnmc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtuivvqvbv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtsvfvrpoq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtgzranwdf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtbecbtpjh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jlsjyb.cn/Article/details/gtabwenbji.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtysovozne.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hysaishi.cn/Article/details/gtnsnfuxku.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtydcvlyww.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hfpthk.cn/Article/details/gtuqenldfo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtrkmzsvod.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtrobpghoc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtmlfvwtvh.html

A. 基础语法与类型
来源：http://dali.chenlongwang.top/Article/details/gttbkaajsd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtppmluhsg.html

[A01] Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwysihhhb.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtgrljyiaf.html

PHP:  echo "Hello, World!";
来源：http://dali.guowangkeji.top/Article/details/gtwefuvutx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhengqikj.top/Article/details/gtpdnlonpw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cdnleiting.top/Article/details/gtxurxzqhr.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtsaluhuch.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cheryme.top/Article/details/gtqziuufcn.html

Ruby: puts "Hello, World!"
来源：http://dali.hnxiangtu.top/Article/details/gtzalzrhuu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hnqzz.top/Article/details/gtflwbushd.html

[A02] 变量声明与赋值
来源：http://dali.zdqjudy.top/Article/details/gtkjvftthj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gtipisgthq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.9152youxi.cn/Article/details/gtwzyomxyz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258.top/Article/details/gtcagoxxxo.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj20258.top/Article/details/gtfrcpgzxc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszycupqa.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gtzgufqudc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbryvncek.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gtqkzrlsya.html

[A03] 常量定义
来源：http://dali.cheryme.top/Article/details/gtgmhihxos.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gaohongyu789.top/Article/details/gtzwgkyeeu.html

PHP:  const PI = 3.14159;
来源：http://dali.yj202588.top/Article/details/gtjjyypzpv.html

JS:   const PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtevcwprmk.html

TS:   const PI: number = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gtkxhysgbs.html

Java: static final double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyikvqzyf.html

Go:   const PI = 3.14159
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxiwgxfg.html

Ruby: PI = 3.14159
来源：http://dali.birdmap.top/Article/details/gtpfgdmskh.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtcpevddgi.html

[A04] 判断变量类型
来源：http://dali.fzhhl.top/Article/details/gtnzcygtmx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.chenjidiqi.icu/Article/details/gtaxebaaws.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.nanxuanxn.top/Article/details/gtcdjmikhf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gtymmeigrk.html

TS:   typeof x; x instanceof Date
来源：http://dali.cdnleiting.top/Article/details/gtiygyvaup.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fengsongda.top/Article/details/gtsxjooott.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.shzxlz.cn/Article/details/gtuupttpwo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gtgngxlbpm.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gtpkvqkyuo.html

[A05] 整数除法与取模
来源：http://dali.svipenyu.cn/Article/details/gtsrjedihg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gtrsquupvl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtxcoyqwac.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.meibo888.top/Article/details/gtpcrkchul.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtxpxumqza.html

Java: 7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtjdrjidnm.html

Go:   7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtbnczxktu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtcvcqhcus.html

C#:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtnaetybxt.html

[A06] 字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtvdsinaak.html

Py:   int("42"); float("3.14")
来源：http://dali.yangfankeji.com/Article/details/gtudbapizo.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yonumen.top/Article/details/gtgfgatbkt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gtrywhqvtw.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nanxuanxn.top/Article/details/gtpvfkgxem.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cucudq.cn/Article/details/gtzvwusmyg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hywenlv.cn/Article/details/gtgccwdbro.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.ppjwa.cn/Article/details/gtftzwcloy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.svipenyu.cn/Article/details/gtxmgmkqgq.html

[A07] 数字转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtseafcili.html

Py:   str(42)
来源：http://dali.hysaishi.cn/Article/details/gttuwxxdge.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258.top/Article/details/gtoartrjjp.html

JS:   String(42); (42).toString()
来源：http://dali.bjfxy.top/Article/details/gtjbyoftey.html

TS:   String(42)
来源：http://dali.vqdsnc.cn/Article/details/gtpcmuzxwn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtpywjhyzq.html

Go:   strconv.Itoa(42)
来源：http://dali.hnxiangtu.top/Article/details/gtfszkijmk.html

Ruby: 42.to_s
来源：http://dali.tanke756.top/Article/details/gtalemyypp.html

C#:   42.ToString()
来源：http://dali.aibaodan.cn/Article/details/gtbdfpnaez.html

[A08] 取整与四舍五入
来源：http://dali.hysaishi.cn/Article/details/gtlvtccerx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhoulong.xyz/Article/details/gtuhycmkla.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yj20258.top/Article/details/gtgixqymvr.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtuvwocyqo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xylfe.cn/Article/details/gtqhivfutr.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmvolzzh.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gtmvydfbxw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nanxuanxn.top/Article/details/gtreluvyne.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtgzygskor.html

[A09] 绝对值与最大最小值
来源：http://dali.zycfv.cn/Article/details/gtbykrguaw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxvophukc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtzbuyocfy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtrvrpiplg.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jiagoushi.top/Article/details/gtzvwrtvqu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtenugwudg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cashguo.top/Article/details/gticlinuvh.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.tanke756.top/Article/details/gtwzmsevvy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtvaeiibly.html

[A10] 生成随机数
来源：http://dali.yongpay.top/Article/details/gtpykuoshs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gzhubu.top/Article/details/gtsqmhsrbr.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gtyypctlay.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtqtrdapzc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtcshrjfln.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gotoacloud.top/Article/details/gtmwoldghg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtyhlaayeb.html

Ruby: rand(1..100)
来源：http://dali.yj202588.top/Article/details/gtlrsqqtwi.html

C#:   new Random().Next(1, 101)
来源：http://dali.fengsongda.top/Article/details/gtmjkktajg.html

[A11] 条件表达式（三元）
来源：http://dali.pycfn.com/Article/details/gtqkovilbk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.0kj1m.cn/Article/details/gtcjqcfrqj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtqntuvwdg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gtmfrgwaqx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtuytjhfcj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtywgwfupn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.haohaochexian.top/Article/details/gtpxljqhuz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtswtxtcbk.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtqvpzfvoz.html

[A12] 字符串插值 / 格式化
来源：http://dali.nanxuanxn.top/Article/details/gthaoegbjk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shuidangran.top/Article/details/gtclmxpoxk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xziqi.cn/Article/details/gtyrhooeci.html

JS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtldymlmyo.html

TS:   `Hello, ${name}!`
来源：http://dali.c1oappe.top/Article/details/gtomfunmef.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258.top/Article/details/gtzyfvujts.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.mhx1999.top/Article/details/gtipdmpflt.html

Ruby: "Hello, #{name}!"
来源：http://dali.svipenyu.cn/Article/details/gtqafpffkq.html

C#:   $"Hello, {name}!"
来源：http://dali.shuidangran.top/Article/details/gtayeppwnd.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cucudq.cn/Article/details/gturyaeyur.html

Py:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtdbotjlec.html

PHP:  "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtippfxddg.html

JS:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxiiehwu.html

TS:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtmowgnmnn.html

Java: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtxlwsfpyc.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtkroedkjn.html

Ruby: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtwnepdcxt.html

C#:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtamjvmrez.html

[A14] 注释写法
来源：http://dali.shangyingyoupin.top/Article/details/gthyhsvflw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.birdmap.top/Article/details/gtsmmhctzh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtoqexoziz.html

JS:   // 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtifvoqhps.html

TS:   // 单行；/* 多行 */
来源：http://dali.yj202588.top/Article/details/gttnthddcv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.wangdashe.top/Article/details/gtfyufgrqk.html

Go:   // 单行；/* 多行 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkplzswyb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.cashguo.top/Article/details/gtguxjrgpw.html

C#:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtlqdnnmwi.html

[A15] 空值判断与默认值
来源：http://dali.jqgfzy.top/Article/details/gtinxxlyfh.html

Py:   value = data or "默认值"
来源：http://dali.gaohongyu789.top/Article/details/gtvgivnwbp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtcqefrmoc.html

JS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtpgfunacw.html

TS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovkykehu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pengpengdd.cyou/Article/details/gtfpkdlyzz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.snrcjt.cn/Article/details/gtigkpeoqe.html

Ruby: value = data || "默认值"
来源：http://dali.ybcxt.top/Article/details/gthywgovah.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtrxerurxl.html

[A16] 真假值判断规则
来源：http://dali.shzxlz.cn/Article/details/gtbacuicfu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cucudq.cn/Article/details/gtmhgdqbjb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtdbbzprtz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yongpay.top/Article/details/gtabspmupe.html

TS:   if (!x) {}
来源：http://dali.yj20258888.top/Article/details/gthziclghp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ivvv.top/Article/details/gtskwgyaoi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigfzy.top/Article/details/gtmfrbmrpl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtbtrsybkn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangdashe.top/Article/details/gttyksjkqy.html

[A17] 位运算
来源：http://dali.jianghu66.top/Article/details/gtjsspfyug.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtazqwobtm.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.fengsongda.top/Article/details/gtgfnzwcld.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtymnfiapg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtwpenemle.html


<!-- 参考信息 -->