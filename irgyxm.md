代发 wailian999

[U99] JS：事件监听
来源：http://dali.yuanzhike.top/Article/details/gtuzhfeykj.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtxkzdmjse.html

[U100] JS：DOM 查询
来源：http://dali.gaohongyu789.top/Article/details/gtshajujrv.html

document.querySelector(".item")
来源：http://dali.tanke756.top/Article/details/gtvkkzqclm.html

[U101] JS：classList 操作
来源：http://dali.haohaochexian.top/Article/details/gtczyqerbr.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gtfgoyfnhi.html

[U102] JS：本地存储
来源：http://dali.zhoulong.xyz/Article/details/gtmxbmgspa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgaqkafgi.html

[U103] JS：定时器
来源：http://dali.jianghu66.top/Article/details/gttybsdiub.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gtfcaewgju.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gthuufdsod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtgqmiaghc.html

[U105] JS：节流
来源：http://dali.nanxuanxn.top/Article/details/gtnimlpiid.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cdnleiting.top/Article/details/gtzfbkdtqg.html

[U106] JS：日期格式化
来源：http://dali.fzhhl.top/Article/details/gtkxmpvqhr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.iojbl.cn/Article/details/gtemposjsw.html

[U107] JS：数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtkhcbbilo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtciibquex.html

[U108] JS：随机整数
来源：http://dali.quarkkingdee.top/Article/details/gttpzbvpxs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guannengcc.top/Article/details/gteaydygus.html

[U109] JS：数组分组
来源：http://dali.aizwys.cn/Article/details/gtpxuvujdr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtogjqxjmd.html

[U110] JS：数组分块
来源：http://dali.yongpay.top/Article/details/gtatbopyrg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xylfe.cn/Article/details/gtqllpdamj.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtglenbpnr.html

new Map(Object.entries(obj))
来源：http://dali.feifeiyinyue.top/Article/details/gtmycrasqm.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtcmgzpqul.html

"7".padStart(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtdieitbdj.html

[U113] JS：正则替换全部
来源：http://dali.jinqigufen.top/Article/details/gtxozovimz.html

s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtofjfdnii.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtsqqjsoor.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.c1oappe.top/Article/details/gtvlhukfgq.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtlzzhkqnq.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gticqdoscy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtyyepvzwa.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sufxvd.cn/Article/details/gteytwayjv.html

[U117] JS：单元测试
来源：http://dali.chenjidiqi.icu/Article/details/gtlywpgthg.html

npm i -D vitest;  npx vitest
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcxzrruq.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gtebrcucte.html

npm i -D vite;  npx vite
来源：http://dali.pycfn.com/Article/details/gtwzghjtji.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gtvgmwmiyi.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gtjafalhic.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ivvv.top/Article/details/gtlvqgmzly.html

import.meta.env.VITE_API_URL
来源：http://dali.snrcjt.cn/Article/details/gtkedqxfcg.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtnytdraac.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtlsqijfwo.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtamjdxvzr.html

按语言统计（条）：
来源：http://dali.jqgfzy.top/Article/details/gtrdvzboxp.html

Python ......... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtsqsiynir.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtfctbdeki.html

JavaScript ..... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlooxzcq.html

TypeScript ..... 212
来源：http://dali.shuidangran.top/Article/details/gtksantbdg.html

Java ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtnqrtyqcw.html

Go ............. 212
来源：http://dali.yj202588.top/Article/details/gtppmkjbmn.html

Ruby ........... 212
来源：http://dali.xylfe.cn/Article/details/gtbtduphvl.html

C# ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gtaezwesro.html

C .............. 30
来源：http://dali.quarkkingdee.top/Article/details/gthxklejsd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gtlhyirdzh.html

SQL ............ 90
来源：http://dali.yuanzhike.top/Article/details/gtsogvpmaz.html

Bash ........... 80
来源：http://dali.iojbl.cn/Article/details/gtgcjfiymf.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtxeepjlxn.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gtwdhideop.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gtlseulcnx.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtqcxvoaht.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtcuhqpcys.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtltqkwgkr.html

合计 ........... 2106 条
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtintzpr.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gtvbitifxa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtavnyriuj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gtnivzyywp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtiaocvadu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yuxming.cn/Article/details/gtvzblkzyg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhixingplan.top/Article/details/gtvjhreeim.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.daxiang520.top/Article/details/gtjkqdyixf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtedysavqp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gtidbeoslg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrkpbfnn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtkkyxoshy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtcwblfbtp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtqzyveesy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gtotasypch.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gtbmlmqosg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cdnleiting.top/Article/details/gtlpcbqmus.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtylbtdjtt.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gtlupejyhv.html

R Bash 专题                             80
来源：http://dali.xuanzx.com/Article/details/gtssdfggqe.html

S C / C++ 专题                          60
来源：http://dali.hnxiangtu.top/Article/details/gtinfehnot.html

T 其他语言补充                          60
来源：http://dali.chenzaomai.com/Article/details/gtpprfbxqr.html

U 高频实用片段                         120
来源：http://dali.redwolf501.top/Article/details/gttorjsmlz.html

------------------------------------
来源：http://dali.pycfn.com/Article/details/gtcrfblpda.html

合计                                  2106 条
来源：http://dali.jinqigufen.top/Article/details/gtsbfbefjq.html

--------------------------------------------------------------------------------
来源：http://dali.smart0.xyz/Article/details/gtmhmbrxyt.html

使用提醒
来源：http://dali.meibo888.top/Article/details/gtnwtsrxyf.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gtgfzanaav.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gogol.net.cn/Article/details/gtbcoxrxuo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtgylshhqu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fzhhl.top/Article/details/gtoevzakrl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.fengsongda.top/Article/details/gtzbptcdmx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqqrogqr.html

—— 文件结束 ——
来源：http://dali.nanxuanxn.top/Article/details/gtfafwxdsd.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtarlcymmc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xziqi.cn/Article/details/gtufwmhtit.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gtdvtyzvsa.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtoqbiiolq.html

【收录内容】
来源：http://dali.316326.xyz/Article/details/gtskzivsid.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yueranfly.top/Article/details/gthdvkowev.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinqigfzy.top/Article/details/gtgmfsrlij.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtrnmiwocp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gtkoycqqvi.html

【使用说明】
来源：http://dali.sufxvd.cn/Article/details/gtdhfsabpk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.andypj.xyz/Article/details/gtyvenygbr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guannengcc.top/Article/details/gtaptnmzod.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cheryme.top/Article/details/gtunmenysl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.havefunace.top/Article/details/gtyxebejwi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gteiextnfe.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtxxycxmqk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gtoeraamqc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.316326.xyz/Article/details/gtoepbfjrd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hywenlv.cn/Article/details/gtdelkugdv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.9152youxi.cn/Article/details/gtlrbaztwl.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gtwkyeakhz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgfatqpqy.html

【文件统计】
来源：http://dali.zhoulong.xyz/Article/details/gtkbcvwegi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.quarkkingdee.top/Article/details/gtlqqfgxsw.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gtgwjnkxhr.html

目  录
来源：http://dali.daria6918.cn/Article/details/gtrdbpgvpa.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtiiybocyz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtmrxgqyry.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtvdcianuw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtlnblbkfd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.c1oappe.top/Article/details/gtmbpibwdt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkvavzdq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zdqjudy.top/Article/details/gtohhtlhtf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtcugahyfu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gtxnztystg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtxwnuatnh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtulybfwiz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtbijvnjlz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtvlplkiem.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtraxvmrmq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ivvv.top/Article/details/gtjgdtnumf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gzhubu.top/Article/details/gtwdlsasjg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtnlnpshwm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gtdoqwfofu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.havefunace.top/Article/details/gtmnrhzmxs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gtdohddfjo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ehwqpu.com/Article/details/gtbeggyudg.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtedpvczry.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtwhzqqrmz.html

A. 基础语法与类型
来源：http://dali.redwolf501.top/Article/details/gtpbwkcukd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtaglxovsm.html

[A01] Hello World
来源：http://dali.redwolf501.top/Article/details/gtxfngmqmw.html

Py:   print("Hello, World!")
来源：http://dali.tanke756.top/Article/details/gtpstfwone.html

PHP:  echo "Hello, World!";
来源：http://dali.xuetiantiany.cn/Article/details/gtkyiiidlx.html

JS:   console.log("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtvcdeqsvf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gtskovfxek.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtnmuvygpm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnxiangtu.top/Article/details/gtjnvsgvlm.html

Ruby: puts "Hello, World!"
来源：http://dali.ydzc1.top/Article/details/gtapmuwfmn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtlunaisml.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gtmrfryfpb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.feifeiyinyue.top/Article/details/gtqrtstodl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtcchrbleg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtoftxkdmw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hywenlv.cn/Article/details/gtuylkvqci.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtnvjpvijn.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtfspusdoz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gaohongyu789.top/Article/details/gthbdanldp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtwwnntqlz.html

[A03] 常量定义
来源：http://dali.yangfankeji.com/Article/details/gtckxpjpqe.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenzaomai.com/Article/details/gtohrhzjfi.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtrimrvjzt.html

JS:   const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtpddecglt.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtytmatfyl.html

Java: static final double PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtlcdlcvwb.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gttazandiv.html

Ruby: PI = 3.14159
来源：http://dali.nanxinkj.top/Article/details/gtmzdlifio.html

C#:   const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gteakkwfka.html

[A04] 判断变量类型
来源：http://dali.tian-w.cn/Article/details/gtrxamyixk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gtkznpfemt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sxryk.cn/Article/details/gtiqcbppfw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtytthdtdl.html

TS:   typeof x; x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gtwtdgggdt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gtrhvvoqbr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hfpthk.cn/Article/details/gtwyduzpgw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xinyue.icu/Article/details/gtdiqgyxur.html

C#:   x.GetType().Name; x is int
来源：http://dali.sxryk.cn/Article/details/gtoglknvnb.html

[A05] 整数除法与取模
来源：http://dali.9152youxi.cn/Article/details/gtehkiruxy.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwtvxxvv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtsuqvqpdf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258888.top/Article/details/gtsjggonku.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gtkprxpxas.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtlyygpnjm.html

Go:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtocwprogh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gthnucclek.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtofllgtwa.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gtwtqqqhhr.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gtziozwsox.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.9152youxi.cn/Article/details/gtxgfoqiat.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yanxiufei.cn/Article/details/gtldnxmkco.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtdivvyjzl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbdvumna.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gttlzolzbd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.aizwys.cn/Article/details/gttbljwbhz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tianlin.xyz/Article/details/gtvlyrekvi.html

[A07] 数字转字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsrkopgq.html

Py:   str(42)
来源：http://dali.yj20258.top/Article/details/gtxkwzjedu.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gtmphqlwgy.html

JS:   String(42); (42).toString()
来源：http://dali.meibo888.top/Article/details/gtudsfslar.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gtfsbiclsc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtuduonnew.html

Go:   strconv.Itoa(42)
来源：http://dali.sweek.top/Article/details/gtwvgjcifh.html

Ruby: 42.to_s
来源：http://dali.yongpay.top/Article/details/gtnqjutvsz.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtywpfjsbb.html

[A08] 取整与四舍五入
来源：http://dali.jlsjyb.cn/Article/details/gtygqdbpup.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gthozuolxj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yvedp.cn/Article/details/gtcqloibis.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gthxayvqco.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhoulong.xyz/Article/details/gtznmekrjj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sysykeji.top/Article/details/gtoxohgvbs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtkszrirks.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj20258.top/Article/details/gtuudvigyi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtcgcfbifq.html

[A09] 绝对值与最大最小值
来源：http://dali.iojbl.cn/Article/details/gtslgknqjs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyphcklkt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtbwetbyji.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtegpfkjup.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtikhvmwhr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtnwthykhd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.wangshuangyany.cn/Article/details/gthiemlets.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.cucudq.cn/Article/details/gtovcxymsr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtqrauguwf.html

[A10] 生成随机数
来源：http://dali.guannengcc.top/Article/details/gtbqnlqtjl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ybcxt.top/Article/details/gtdymlrxwm.html

PHP:  random_int(1, 100);
来源：http://dali.zdqjudy.top/Article/details/gtttaruiqc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtzwuokbtv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.bjfxy.top/Article/details/gtuvvngayq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yvedp.cn/Article/details/gteborbqsa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ppjwa.cn/Article/details/gtpicsnatl.html

Ruby: rand(1..100)
来源：http://dali.hnxiangtu.top/Article/details/gtzwzmrckh.html

C#:   new Random().Next(1, 101)
来源：http://dali.kuanghao11.cn/Article/details/gtosrfsyvy.html

[A11] 条件表达式（三元）
来源：http://dali.dianchejie.cn/Article/details/gtnbyieqep.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.aizwys.cn/Article/details/gthspmnoez.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtmkjygupg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtcmiztiqg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtbuwcupbu.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtmmwcekbw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gtsnwykynf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gtjvmwrjnp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtcvrlvpwc.html

[A12] 字符串插值 / 格式化
来源：http://dali.iojbl.cn/Article/details/gttcpevylg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gotoacloud.top/Article/details/gthksqealt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gtzqypqopt.html

JS:   `Hello, ${name}!`
来源：http://dali.hnxiangtu.top/Article/details/gtbkjeapty.html

TS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtztkrsafh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtsogxnxtl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.quarkkingdee.top/Article/details/gtutqpqzqi.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgfzy.top/Article/details/gtryuahxse.html

C#:   $"Hello, {name}!"
来源：http://dali.chenjidiqi.icu/Article/details/gtjljywkuk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiheeqylr.html

Py:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gtjqynpvsk.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzhpvwsb.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gttfcyunfc.html

TS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtzjpkhvjb.html

Java: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtegdlhfqs.html

Go:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtrsuztxtz.html

Ruby: "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtnqpsizik.html

C#:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtyobzhnno.html

[A14] 注释写法
来源：http://dali.hammf.cn/Article/details/gtxjylgifd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.bjfxy.top/Article/details/gtsmabmjum.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtnihutipd.html

JS:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gtnwtdcqrf.html

TS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtrixesmng.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhijiandao.cn/Article/details/gtwqnrtqbp.html

Go:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtqqungiae.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tian-w.cn/Article/details/gtxdrbetih.html

C#:   // 单行；/* 多行 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnxbpwsi.html

[A15] 空值判断与默认值
来源：http://dali.yanxiufei.cn/Article/details/gtpenmrlra.html

Py:   value = data or "默认值"
来源：http://dali.hywenlv.cn/Article/details/gtudkqvytc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gttycflasy.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtrhbagmlk.html

TS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtfkmqeoxn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pycfn.com/Article/details/gtkukjkmbo.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gtbhhrshic.html

Ruby: value = data || "默认值"
来源：http://dali.hongshengwenyu.top/Article/details/gtfxcuhgju.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtpmrxftoq.html

[A16] 真假值判断规则
来源：http://dali.jinghuilouyu.cn/Article/details/gtalpwlbyc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gtkgnwldgy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenlongwang.top/Article/details/gtqftcjven.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtevrptddc.html

TS:   if (!x) {}
来源：http://dali.tianlin.xyz/Article/details/gtvgedgdrs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jyoumei.cn/Article/details/gtshfttarx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cqqwz.cn/Article/details/gteexgcwob.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.snrcjt.cn/Article/details/gtooskpzqe.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtxssjrdil.html

[A17] 位运算
来源：http://dali.jianghu66.top/Article/details/gthpopucwc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtthqeizzz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.nwbrower.top/Article/details/gtopctysxf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtygjwqlao.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtvtqdvjjt.html


<!-- 参考信息 -->