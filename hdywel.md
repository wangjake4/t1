代发 wailian999

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtznvksqxn.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtdveoejbh.html

[U100] JS：DOM 查询
来源：http://dali.xziqi.cn/Article/details/gtfgkctqgc.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gtbwffmcdg.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtwyzrsder.html

el.classList.toggle("active")
来源：http://dali.sysykeji.top/Article/details/gttfrqfhmd.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gtmnwwuzaw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtuopcptch.html

[U103] JS：定时器
来源：http://dali.redwolf501.top/Article/details/gtmflcrbzg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gtktdwennx.html

[U104] JS：防抖
来源：http://dali.ydzc1.top/Article/details/gtsrwxbdui.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hywenlv.cn/Article/details/gtyiigkogq.html

[U105] JS：节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuygbbbd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gtxbycykkr.html

[U106] JS：日期格式化
来源：http://dali.yvedp.cn/Article/details/gttmrdmmxe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sxryk.cn/Article/details/gtvchbswnm.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gtncqrkltx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtgtngmwuy.html

[U108] JS：随机整数
来源：http://dali.xylfe.cn/Article/details/gttukekwyt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gtgjvrsvit.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtcjfrlyge.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqtjfuvy.html

[U110] JS：数组分块
来源：http://dali.yuxming.cn/Article/details/gtkhjopcqd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdcropuue.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzabezsfy.html

new Map(Object.entries(obj))
来源：http://dali.zycfv.cn/Article/details/gtautlbhmh.html

[U112] JS：字符串补位
来源：http://dali.yj20258888.top/Article/details/gthigqlnpw.html

"7".padStart(3, "0")
来源：http://dali.c1oappe.top/Article/details/gtuyhwneat.html

[U113] JS：正则替换全部
来源：http://dali.tianlin.xyz/Article/details/gtnaqaybnn.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gturyckoow.html

[U114] JS：JSON 深比较
来源：http://dali.wangdashe.top/Article/details/gtufoumqoe.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gtmmixirda.html

[U115] JS：生成 UUID
来源：http://dali.gogol.net.cn/Article/details/gtjscoocyq.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtlohntrkc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.0kj1m.cn/Article/details/gtdijecglz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258888.top/Article/details/gtqvnmggie.html

[U117] JS：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtbucuhbwn.html

npm i -D vitest;  npx vitest
来源：http://dali.sufxvd.cn/Article/details/gtlrgtbony.html

[U118] JS：开发服务器
来源：http://dali.hywenlv.cn/Article/details/gtkbdfogkw.html

npm i -D vite;  npx vite
来源：http://dali.cheryme.top/Article/details/gtkrrcgpsc.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gtsbeazhtb.html

npx vite build
来源：http://dali.nanxuanxn.top/Article/details/gtezrhsfhy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.quarkkingdee.top/Article/details/gthgfnowqs.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtduyexrra.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwheinbfw.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtlllwuugm.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtuwovakjc.html

按语言统计（条）：
来源：http://dali.yvedp.cn/Article/details/gtucaapxhq.html

Python ......... 252
来源：http://dali.guowangkeji.top/Article/details/gtonnoyhdx.html

PHP ............ 252
来源：http://dali.gotoacloud.top/Article/details/gtrsokgxzc.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtnjaovifq.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gtowjbqmnb.html

Java ........... 212
来源：http://dali.316326.xyz/Article/details/gtnbwzdbzi.html

Go ............. 212
来源：http://dali.svipenyu.cn/Article/details/gteowpxqqi.html

Ruby ........... 212
来源：http://dali.yj20258888.top/Article/details/gtocasehtg.html

C# ............. 212
来源：http://dali.redwolf501.top/Article/details/gtdpebmsql.html

C .............. 30
来源：http://dali.wangshuangyany.cn/Article/details/gtydcxoyfs.html

C++ ............ 30
来源：http://dali.shzxlz.cn/Article/details/gtfiwlkekl.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtexjwfhua.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gtlczokigo.html

Kotlin ......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtqrrgkltk.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtsfarlvhy.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtvteqdcei.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gtklnqjzun.html

Scala .......... 10
来源：http://dali.aizwys.cn/Article/details/gtkjyqrius.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtruryqzua.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gtrltpatsx.html

按章节统计：
来源：http://dali.chenzaomai.com/Article/details/gthgdiblyu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtlzdgioed.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtkclwknbl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gthenoadgt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gtbdxosryi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.0kj1m.cn/Article/details/gtbjlabthy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtgirjualy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtqsqcjvrm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gtneqpbnmx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtevznrlvc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.fzhhl.top/Article/details/gtuglmvgjk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtacsgfzjq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtvgkrqhtc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gtmsfxybeq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ybcxt.top/Article/details/gtxijffjnn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtqnvgudhe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtanrujgic.html

Q SQL 专题                              90
来源：http://dali.ivvv.top/Article/details/gtomppmlgh.html

R Bash 专题                             80
来源：http://dali.xziqi.cn/Article/details/gtssisnnse.html

S C / C++ 专题                          60
来源：http://dali.dianchejie.cn/Article/details/gttuledgcr.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gtozjqkjkv.html

U 高频实用片段                         120
来源：http://dali.aibaodan.cn/Article/details/gtjnpcchmf.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtsntdrlix.html

合计                                  2106 条
来源：http://dali.guowangkeji.top/Article/details/gtecfxpyoh.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtdxzcmryf.html

使用提醒
来源：http://dali.ehwqpu.com/Article/details/gtckkvdpzg.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtkddphhrr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aizwys.cn/Article/details/gtjhyvrmvj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yanxiufei.cn/Article/details/gtoisvayfv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gtrftcpidw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.pengpengdd.cyou/Article/details/gtmvnwzypo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.mhx1999.top/Article/details/gtcsvgrilg.html

—— 文件结束 ——
来源：http://dali.jqgufenzy.top/Article/details/gtmzkecgzs.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkjvhkmpz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.iojbl.cn/Article/details/gtkuztaxam.html

Common Programming Examples Cheat Book
来源：http://dali.zhiwuduotai.top/Article/details/gtoxknywfu.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtieejizkd.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtywtnyokh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gtrtnmpvrx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gtsxaymelo.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gtytoqoylh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shuidangran.top/Article/details/gtjviymnbp.html

【使用说明】
来源：http://dali.jyoumei.cn/Article/details/gtitbozlhb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gzhubu.top/Article/details/gtlhvnqppd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.guannengcc.top/Article/details/gtoxadhjxe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gtavuiajmq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.daxiang520.top/Article/details/gtrxwabtgm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cqqwz.cn/Article/details/gtfiypybyx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yangfankeji.com/Article/details/gtllxqgdph.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xziqi.cn/Article/details/gtozhsmkyq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.birdmap.top/Article/details/gtjpetnebk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.redwolf501.top/Article/details/gtwngqjnlo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnxiangtu.top/Article/details/gtyuacyecf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.cheryme.top/Article/details/gtwndqlpwz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yonumen.top/Article/details/gtlxvozuic.html

【文件统计】
来源：http://dali.sysykeji.top/Article/details/gthwooginl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.fzhhl.top/Article/details/gtjquuwemf.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtoecjvidu.html

目  录
来源：http://dali.jinqigufen.top/Article/details/gtpnpscpcz.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtqwaeptnw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gtyzddhqyo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzjbhmfe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gthnoqvvwl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gtevigcnod.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gtdiopiunl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxttrhdiy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.birdmap.top/Article/details/gtqmcxdyfv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gthejitqmr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.cheryme.top/Article/details/gtttkcwwsc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.nanxuanxn.top/Article/details/gtehjqdjyc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gtiphlqbta.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtftcvtwxb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtdgsbbehr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hysaishi.cn/Article/details/gtuxnmtvqj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yonumen.top/Article/details/gttdjqopgf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtqffhykvl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhoulong.xyz/Article/details/gtnxbdjvsa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.haohaochexian.top/Article/details/gtbtnnyfzt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gtqkredjmd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtglcayidb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.sweek.top/Article/details/gtumolvoza.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtktjqxgbb.html

A. 基础语法与类型
来源：http://dali.zycfv.cn/Article/details/gtdzjqlunx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtygkukoaj.html

[A01] Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtzprlyahn.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtnohpttst.html

PHP:  echo "Hello, World!";
来源：http://dali.yonumen.top/Article/details/gtqcohszgy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtjyhtomft.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hysaishi.cn/Article/details/gtzviyidwk.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtwmclmevz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xylfe.cn/Article/details/gtjirsfewt.html

Ruby: puts "Hello, World!"
来源：http://dali.cucudq.cn/Article/details/gtveiddpxk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.birdmap.top/Article/details/gtlvbbotvx.html

[A02] 变量声明与赋值
来源：http://dali.shzxlz.cn/Article/details/gtetvulcad.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hongshengwenyu.top/Article/details/gtcgylrvsw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.meibo888.top/Article/details/gtywqeufwd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtpukzdnee.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sxryk.cn/Article/details/gtdfrgdysp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtcurohjaw.html

Go:   name := "Alex"; age := 20
来源：http://dali.gogol.net.cn/Article/details/gtsbapxpyx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ivvv.top/Article/details/gtywvktbzg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.smart0.xyz/Article/details/gtddcgnnsk.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gtoxxhkbxd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hnqzz.top/Article/details/gtcexixuvx.html

PHP:  const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqnpwdpbo.html

JS:   const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtmvptdcuo.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtcogzycha.html

Java: static final double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtlpjjjcve.html

Go:   const PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gteqerrfmb.html

Ruby: PI = 3.14159
来源：http://dali.aizwys.cn/Article/details/gtlxupchhq.html

C#:   const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtllrsfcxc.html

[A04] 判断变量类型
来源：http://dali.9152youxi.cn/Article/details/gtgkcnteoz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gtwpypxzow.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.cheryme.top/Article/details/gtftgeczgu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gtfglsmaab.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnqzz.top/Article/details/gtgffaeevx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.vqdsnc.cn/Article/details/gtlrfxrdqy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gtcfbtsgjv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.sufxvd.cn/Article/details/gtpsoazlvp.html

C#:   x.GetType().Name; x is int
来源：http://dali.ybcxt.top/Article/details/gthnvneruw.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gtvozchnst.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hnqzz.top/Article/details/gtlkspozok.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtjakfbybd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdnjhtmh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtmxzwgehd.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtyigoebtd.html

Go:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtbajciycu.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtjbylpcwb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtvuoowmcz.html

[A06] 字符串转数字
来源：http://dali.hammf.cn/Article/details/gtwrsesmai.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gtsqjxucld.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.smart0.xyz/Article/details/gtztcuxmte.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cucudq.cn/Article/details/gtehvfvxgu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.fzhhl.top/Article/details/gtniwvlczs.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dashuyun.cn/Article/details/gtxwynvmhj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.bjfxy.top/Article/details/gteikkwtbx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnqzz.top/Article/details/gtokoqhkrh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cucudq.cn/Article/details/gtkhtuupwx.html

[A07] 数字转字符串
来源：http://dali.meibo888.top/Article/details/gtqcyusbdz.html

Py:   str(42)
来源：http://dali.daxiang520.top/Article/details/gtwsnotoum.html

PHP:  (string) 42; strval(42)
来源：http://dali.tianlin.xyz/Article/details/gttjntlbzo.html

JS:   String(42); (42).toString()
来源：http://dali.sxryk.cn/Article/details/gtrjafidlt.html

TS:   String(42)
来源：http://dali.gotoacloud.top/Article/details/gtluhzdbpe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhoulong.xyz/Article/details/gtclqxzbmt.html

Go:   strconv.Itoa(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtaomxywyh.html

Ruby: 42.to_s
来源：http://dali.hywenlv.cn/Article/details/gtcohnxybq.html

C#:   42.ToString()
来源：http://dali.pengpengdd.cyou/Article/details/gtjnhrfpfg.html

[A08] 取整与四舍五入
来源：http://dali.cdnleiting.top/Article/details/gtzxrivxar.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtombherzh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuypmbybh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjjodqvi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gtpbcbtehu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fzhhl.top/Article/details/gtibtbmdmm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtgjtztgpe.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.mhx1999.top/Article/details/gtttkphtzj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtvnxdbqrs.html

[A09] 绝对值与最大最小值
来源：http://dali.fzhhl.top/Article/details/gtyxkgrwvi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrhwfrsr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtusoyzwbk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yvedp.cn/Article/details/gttwfuufli.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtbffuwajv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtkysoondl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fzhhl.top/Article/details/gttlycnbtv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gtgtviyeqq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtrugfpgze.html

[A10] 生成随机数
来源：http://dali.fengsongda.top/Article/details/gtkidlworw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cheryme.top/Article/details/gtacbvaxcn.html

PHP:  random_int(1, 100);
来源：http://dali.tianlin.xyz/Article/details/gtikfrlxfu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtcuaxjkgb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtplqvfzti.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangdashe.top/Article/details/gtfbkbzevm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cashguo.top/Article/details/gtwyvfybfw.html

Ruby: rand(1..100)
来源：http://dali.ehwqpu.com/Article/details/gtxupwgxkl.html

C#:   new Random().Next(1, 101)
来源：http://dali.shuidangran.top/Article/details/gtfwrvzkel.html

[A11] 条件表达式（三元）
来源：http://dali.shzxlz.cn/Article/details/gtrigjwytv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xylfe.cn/Article/details/gtplefahlz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtaecexuur.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtmnfolokh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gttypstbra.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhlmakyd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yongpay.top/Article/details/gtosgowgdn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzujtpfgy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtjvikizxp.html

[A12] 字符串插值 / 格式化
来源：http://dali.0kj1m.cn/Article/details/gtghdwderg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sxryk.cn/Article/details/gtsfdjlldk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.daria6918.cn/Article/details/gtvojjsgpp.html

JS:   `Hello, ${name}!`
来源：http://dali.cucudq.cn/Article/details/gtvnjfttti.html

TS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtlokrexmv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sweek.top/Article/details/gtrffxftjw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ivvv.top/Article/details/gtrzigdguu.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslqqfppb.html

C#:   $"Hello, {name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcabmyus.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gtzykqgosy.html

Py:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtbjkrchbf.html

PHP:  "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtlbagjgnv.html

JS:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtbqugawkp.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtkmagrpjh.html

Java: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauypyhll.html

Go:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtjacrrvob.html

Ruby: "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtfjgumnae.html

C#:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtfsnqckex.html

[A14] 注释写法
来源：http://dali.sysykeji.top/Article/details/gtecvyrzvp.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxinkj.top/Article/details/gtqgbyfdkk.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.nanxuanxn.top/Article/details/gtxlfsyqpt.html

JS:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtneysaxoj.html

TS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gtenxxgrtz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xylfe.cn/Article/details/gtmnmvmifl.html

Go:   // 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtkcitbdxc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hongshengwenyu.top/Article/details/gtqwaipyen.html

C#:   // 单行；/* 多行 */
来源：http://dali.aizwys.cn/Article/details/gttntjehdw.html

[A15] 空值判断与默认值
来源：http://dali.gaohongyu789.top/Article/details/gtncybgxfx.html

Py:   value = data or "默认值"
来源：http://dali.cdnleiting.top/Article/details/gtblwdzueq.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhengqikj.top/Article/details/gtnyuvqnpq.html

JS:   const value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtlcsmbayy.html

TS:   const value = data ?? "默认值";
来源：http://dali.jqgfzy.top/Article/details/gtjdsyezvq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.chenjidiqi.icu/Article/details/gtqrxnmkwj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gotoacloud.top/Article/details/gtemibbdnf.html

Ruby: value = data || "默认值"
来源：http://dali.ydzc1.top/Article/details/gtotywbubt.html

C#:   var value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtfuofdkgc.html

[A16] 真假值判断规则
来源：http://dali.redwolf501.top/Article/details/gtebmwijcg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jianghu66.top/Article/details/gtbqrminam.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.daxiang520.top/Article/details/gtabzoediq.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhixingplan.top/Article/details/gtvlbnenad.html

TS:   if (!x) {}
来源：http://dali.hywenlv.cn/Article/details/gtszufmzvp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sysykeji.top/Article/details/gtqmavpore.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangshuangyany.cn/Article/details/gtpybksgfy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhengqikj.top/Article/details/gtlxzlbhlv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gogol.net.cn/Article/details/gtmjtikons.html

[A17] 位运算
来源：http://dali.tianlin.xyz/Article/details/gtzudkyahz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtowqcjlcg.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shuidangran.top/Article/details/gtlbetuatr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtwhftslfl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtufejkynr.html


<!-- 参考信息 -->