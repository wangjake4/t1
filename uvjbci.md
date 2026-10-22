代发 wailian999

[U99] JS：事件监听
来源：http://dali.cqqwz.cn/Article/details/gt2fujzenyt.html

el.addEventListener("click", e => {})
来源：http://dali.zhongyouzk.top/Article/details/gt2zufesmmd.html

[U100] JS：DOM 查询
来源：http://dali.gogol.net.cn/Article/details/gt2mrahqmzm.html

document.querySelector(".item")
来源：http://dali.guowangkeji.top/Article/details/gt2vweqhraz.html

[U101] JS：classList 操作
来源：http://dali.xuanzx.com/Article/details/gt2tbmavdod.html

el.classList.toggle("active")
来源：http://dali.fzhhl.top/Article/details/gt2poknnway.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gt2lxqmpvih.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenzaomai.com/Article/details/gt2trhttyas.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gt2hvjjtimz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.daxiang520.top/Article/details/gt2wblozihv.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gt2xntroznp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2xvsevhck.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gt2epuwxmew.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gt2tsxotzvx.html

[U106] JS：日期格式化
来源：http://dali.ybcxt.top/Article/details/gt2kovtkaps.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gt2luctdmks.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfohyck.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfporyww.html

[U108] JS：随机整数
来源：http://dali.tanke756.top/Article/details/gt2pkjxthyt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gt2ykrmqhkw.html

[U109] JS：数组分组
来源：http://dali.yuxming.cn/Article/details/gt2heilujuy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2audmnwwy.html

[U110] JS：数组分块
来源：http://dali.cashguo.top/Article/details/gt2qjntiejn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shzxlz.cn/Article/details/gt2slxocwpp.html

[U111] JS：对象转 Map
来源：http://dali.nwbrower.top/Article/details/gt2wigsveim.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gt2yqumqsxb.html

[U112] JS：字符串补位
来源：http://dali.zhengqikj.top/Article/details/gt2gpnydsmh.html

"7".padStart(3, "0")
来源：http://dali.nwbrower.top/Article/details/gt2kwgbzvym.html

[U113] JS：正则替换全部
来源：http://dali.gaohongyu789.top/Article/details/gt2afsfxlos.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2rbeygmkr.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gt2ztxmrwwu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2ghfyfyyc.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2zjcansdf.html

crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2njdoigtn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gt2hdkvfkiu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuanzhike.top/Article/details/gt2btfnnfsz.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gt2bgzrlzxy.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffahbzzc.html

[U118] JS：开发服务器
来源：http://dali.mhx1999.top/Article/details/gt2wjsrshss.html

npm i -D vite;  npx vite
来源：http://dali.sysykeji.top/Article/details/gt2nbonxrsq.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gt2qvgixflw.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gt2mzqhqlif.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangdashe.top/Article/details/gt2npacxybm.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gt2cqzcqdvp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ynxgsmkb.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gt2hmfjqfjk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2zxpsuund.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gt2qprbxidp.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iscjpgjq.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gt2inzhmich.html

JavaScript ..... 252
来源：http://dali.zycfv.cn/Article/details/gt2hvhotnfi.html

TypeScript ..... 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2ogswfqfx.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gt2yjhtmftr.html

Go ............. 212
来源：http://dali.guannengcc.top/Article/details/gt2hdhpnwrv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wrluvguu.html

C# ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2nfofsdwl.html

C .............. 30
来源：http://dali.tanke756.top/Article/details/gt2jlmemstv.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gt2wardwwzy.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gt2wplccoqz.html

Bash ........... 80
来源：http://dali.xuanzx.com/Article/details/gt2fpsrbjyk.html

Kotlin ......... 15
来源：http://dali.gogol.net.cn/Article/details/gt2cwqyfxke.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gt2mdsbpslq.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gt2qonaxoyr.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2sfqghoyf.html

Scala .......... 10
来源：http://dali.gzhubu.top/Article/details/gt2tadfbwar.html

------------------------------------
来源：http://dali.cucudq.cn/Article/details/gt2nthbjvqi.html

合计 ........... 2106 条
来源：http://dali.cqqwz.cn/Article/details/gt2pbwypscx.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gt2zfqedbtv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gt2ybfrmahv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2gpzaopui.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gt2djgpcttk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2igngwnln.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yj20258.top/Article/details/gt2kecsecvm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gt2noamypch.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gt2wigtuwni.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gt2xtliggqa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gt2dlyzoccp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gt2vbrqrbfp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2wbupffar.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2aiozdvds.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gt2vizukylb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2ddbycqty.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gt2btnpquea.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2rvbgvhwu.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gt2jompdayi.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gt2iufmrlhr.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gt2cfatydhu.html

T 其他语言补充                          60
来源：http://dali.quarkkingdee.top/Article/details/gt2albohyku.html

U 高频实用片段                         120
来源：http://dali.guannengcc.top/Article/details/gt2lrmeifvp.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2tecbpqen.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xgvuzayg.html

--------------------------------------------------------------------------------
来源：http://dali.kuanghao11.cn/Article/details/gt2liwtfyql.html

使用提醒
来源：http://dali.xylfe.cn/Article/details/gt2lhazltih.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gt2qtaiualp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.9152youxi.cn/Article/details/gt2xqkprpfl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yurwoqti.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ehwqpu.com/Article/details/gt2evcfobpw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gt2vfplchdq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gt2dgfptjjk.html

—— 文件结束 ——
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kibyzezr.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fppmswfs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenlongwang.top/Article/details/gt2civccomb.html

Common Programming Examples Cheat Book
来源：http://dali.tian-w.cn/Article/details/gt2mefzczqi.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2xivaeyfz.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gt2spyqbtma.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cucudq.cn/Article/details/gt2ykmxtfyk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhongyouzk.top/Article/details/gt2mvpgnmwf.html

SQL · Bash · C · C++
来源：http://dali.fzhhl.top/Article/details/gt2xypiuycm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gt2vljtllwx.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gt2ptjdkyxg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gt2wpalejxp.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gt2dzghcrcx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.dashuyun.cn/Article/details/gt2drnrjnkq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gt2cavzerkw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gt2xtgwklwo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmsdpxuu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.meibo888.top/Article/details/gt2xdrnwfpt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.gaohongyu789.top/Article/details/gt2criepsly.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yanxiufei.cn/Article/details/gt2sqjjzzhi.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gt2tpqyvddk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nzakjnpa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.bjfxy.top/Article/details/gt2ljhqlezc.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gt2kvtcopbl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cucudq.cn/Article/details/gt2pahhbxdf.html

--------------------------------------------------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gt2tlrhkgkv.html

目  录
来源：http://dali.gotoacloud.top/Article/details/gt2xnpjruxm.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gt2gqwnqmjg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sysykeji.top/Article/details/gt2twlyekmb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2grpujvbp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.9152youxi.cn/Article/details/gt2horitqxd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vlmwotjn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xuanzx.com/Article/details/gt2enlabakm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gt2ddfyxtup.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2zzqoxwbm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2zpjrsqzi.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gt2dovzinrw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gt2qmdungts.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ppjwa.cn/Article/details/gt2qfpakxdw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2celkbsxy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gogol.net.cn/Article/details/gt2ofhyfmin.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gt2fkskuaiy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jyoumei.cn/Article/details/gt2ldpsoald.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2fldzwive.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sweek.top/Article/details/gt2hqecttrb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2cmkotqsm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cdnleiting.top/Article/details/gt2bzjaqauc.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gt2fcdtanlz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gt2wockcixa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2pszigtzr.html

A. 基础语法与类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2jyecjxhp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bmjwqngy.html

[A01] Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2lnlhtewq.html

Py:   print("Hello, World!")
来源：http://dali.jianghu66.top/Article/details/gt2uctvimln.html

PHP:  echo "Hello, World!";
来源：http://dali.chenlongwang.top/Article/details/gt2yorjnlsg.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gt2ltflvdzn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sufxvd.cn/Article/details/gt2aurjbfxa.html

Java: System.out.println("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gt2xixjivhr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnhrwckq.html

Ruby: puts "Hello, World!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsiokszv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gt2sdbkporl.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gt2ilciketw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gt2auzkytmc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvyzoivy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.quarkkingdee.top/Article/details/gt2gjdfhpgy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.svipenyu.cn/Article/details/gt2chfhlpuf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2sujospbh.html

Go:   name := "Alex"; age := 20
来源：http://dali.bjfxy.top/Article/details/gt2aupizvvz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhengqikj.top/Article/details/gt2kiittrra.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2ubfwuxpb.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gt2yvbjpxlp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.fengsongda.top/Article/details/gt2leecxzpi.html

PHP:  const PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2eygiinur.html

JS:   const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2yrvvabio.html

TS:   const PI: number = 3.14159;
来源：http://dali.birdmap.top/Article/details/gt2dnyytmop.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gt2uwdhfwew.html

Go:   const PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpmnmnlj.html

Ruby: PI = 3.14159
来源：http://dali.xziqi.cn/Article/details/gt2qcwpiuik.html

C#:   const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2setizevj.html

[A04] 判断变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snezdlpt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jianghu66.top/Article/details/gt2dytxaevd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2hciejmzv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gt2rbjqhrew.html

TS:   typeof x; x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gt2vrahadmk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.wangshuangyany.cn/Article/details/gt2humabudm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.mhx1999.top/Article/details/gt2aowmnush.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.birdmap.top/Article/details/gt2srfahlsr.html

C#:   x.GetType().Name; x is int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zefqtcml.html

[A05] 整数除法与取模
来源：http://dali.ybcxt.top/Article/details/gt2rjnbviut.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cqqwz.cn/Article/details/gt2fxrtbspx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2lhvclnvm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2doecyqld.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2wyzhtwwr.html

Java: 7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2zopuyapa.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gt2haxadyqw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2xotsvvbt.html

C#:   7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2ywtfyghk.html

[A06] 字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gt2sdpqfydy.html

Py:   int("42"); float("3.14")
来源：http://dali.tianlin.xyz/Article/details/gt2wipfmubn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tian-w.cn/Article/details/gt2gmpjhogd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gt2blnryids.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hongshengwenyu.top/Article/details/gt2dtswjyeb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nwbrower.top/Article/details/gt2jnperkiu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2geuuajnz.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yonumen.top/Article/details/gt2wkhorxym.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljbztntt.html

[A07] 数字转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afzgijbj.html

Py:   str(42)
来源：http://dali.tian-w.cn/Article/details/gt2ywqrigby.html

PHP:  (string) 42; strval(42)
来源：http://dali.meibo888.top/Article/details/gt2bdjnhnqy.html

JS:   String(42); (42).toString()
来源：http://dali.nanxinkj.top/Article/details/gt2gbygiyum.html

TS:   String(42)
来源：http://dali.yj202588.top/Article/details/gt2kybcnmls.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zcavqbew.html

Go:   strconv.Itoa(42)
来源：http://dali.aibaodan.cn/Article/details/gt2dzqjzkva.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gt2nboxqxta.html

C#:   42.ToString()
来源：http://dali.yongpay.top/Article/details/gt2ylrmsoqt.html

[A08] 取整与四舍五入
来源：http://dali.havefunace.top/Article/details/gt2bllndltv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gt2ydmgzpim.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.svipenyu.cn/Article/details/gt2ithasxxf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2akijohxn.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zycfv.cn/Article/details/gt2pirjpdxu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gt2zjuzdcrj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gt2ftbfvxdb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenjidiqi.icu/Article/details/gt2dklbfptw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2stjagfep.html

[A09] 绝对值与最大最小值
来源：http://dali.yj20258888.top/Article/details/gt2qkfwdnkk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2wwxkfslu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2luzpesml.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2jcaytbwd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2yvdxjkuo.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2pfobupzy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.quarkkingdee.top/Article/details/gt2omrnqits.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.redwolf501.top/Article/details/gt2hukdybrr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gt2styhsipk.html

[A10] 生成随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2utjbhhwh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uzmliujs.html

PHP:  random_int(1, 100);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unzeunbv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hammf.cn/Article/details/gt2oacdlvbn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.fzhhl.top/Article/details/gt2cxgdmmuq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xylfe.cn/Article/details/gt2fanyjpjd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fengsongda.top/Article/details/gt2ayvvcoul.html

Ruby: rand(1..100)
来源：http://dali.yuxming.cn/Article/details/gt2ifqzhtty.html

C#:   new Random().Next(1, 101)
来源：http://dali.hysaishi.cn/Article/details/gt2ouitmoxk.html

[A11] 条件表达式（三元）
来源：http://dali.hnxiangtu.top/Article/details/gt2jgznakbj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2ztbelhkb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2aarkgufm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2hjnkxmfz.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2dvbtzzdq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gt2hcfpanlx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.fzhhl.top/Article/details/gt2seeluwqn.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2laupwilu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gt2ejepehvz.html

[A12] 字符串插值 / 格式化
来源：http://dali.pycfn.com/Article/details/gt2fckckoer.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.tianlin.xyz/Article/details/gt2qjvhrwuc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hfpthk.cn/Article/details/gt2kxzzlhpz.html

JS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gt2hbpaggvu.html

TS:   `Hello, ${name}!`
来源：http://dali.jqgfzy.top/Article/details/gt2kdzdjsya.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.aibaodan.cn/Article/details/gt2bcmascuj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwlbdtx.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigfzy.top/Article/details/gt2ysueuybw.html

C#:   $"Hello, {name}!"
来源：http://dali.haohaochexian.top/Article/details/gt2wjyultjv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.meibo888.top/Article/details/gt2fiwzpxze.html

Py:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2zuzuzsva.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gt2jvyfpzyq.html

JS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2xbnyqqih.html

TS:   "第一行\n第二行"
来源：http://dali.xinyue.icu/Article/details/gt2njrdhyko.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2ouuoxowa.html

Go:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2htqnumtu.html

Ruby: "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gt2ldwoimxh.html

C#:   "第一行\n第二行"
来源：http://dali.redwolf501.top/Article/details/gt2igntwtha.html

[A14] 注释写法
来源：http://dali.nwbrower.top/Article/details/gt2gxfaazyd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.tian-w.cn/Article/details/gt2uakkwbvc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gt2gpcmhytg.html

JS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gt2fwjgfpfk.html

TS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2vezpvyqs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gt2pttoiscg.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gt2aozvdpzf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hfpthk.cn/Article/details/gt2qzmdgqje.html

C#:   // 单行；/* 多行 */
来源：http://dali.guannengcc.top/Article/details/gt2lkjhzafa.html

[A15] 空值判断与默认值
来源：http://dali.yj202588.top/Article/details/gt2iebmdity.html

Py:   value = data or "默认值"
来源：http://dali.wangshuangyany.cn/Article/details/gt2erfiylci.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gogol.net.cn/Article/details/gt2mwhnuqgu.html

JS:   const value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gt2inymbgze.html

TS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gt2ojwomjsn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lsgrlekk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jyoumei.cn/Article/details/gt2ydpbmnkk.html

Ruby: value = data || "默认值"
来源：http://dali.shuidangran.top/Article/details/gt2trgsjuza.html

C#:   var value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gt2aymgkxwl.html

[A16] 真假值判断规则
来源：http://dali.daxiang520.top/Article/details/gt2lgttfdkk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cayiszir.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gt2bogwwyjp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cqqwz.cn/Article/details/gt2qwempqkb.html

TS:   if (!x) {}
来源：http://dali.aizwys.cn/Article/details/gt2ectbubwm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2yhzpnkaj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenlongwang.top/Article/details/gt2dgmdypmc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.c1oappe.top/Article/details/gt2sziwtoww.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ozdlppyx.html

[A17] 位运算
来源：http://dali.aibaodan.cn/Article/details/gt2dueweyvm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2rawhygse.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2ykpyrvyu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2eousszjz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2qwfjekxm.html


<!-- 参考信息 -->