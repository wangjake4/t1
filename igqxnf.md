代发 wailian999

[U101] JS：classList 操作
来源：http://dali.hammf.cn/Article/details/gt2wroaflqo.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gt2wjekpjux.html

[U102] JS：本地存储
来源：http://dali.yj20258888.top/Article/details/gt2usdbdbtf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gt2javxfnzs.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gt2wzzzqpzd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.svipenyu.cn/Article/details/gt2rdlnyjet.html

[U104] JS：防抖
来源：http://dali.quarkkingdee.top/Article/details/gt2cnmcoarz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2gmcuegvn.html

[U105] JS：节流
来源：http://dali.yuxming.cn/Article/details/gt2eiulzlmq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ehwqpu.com/Article/details/gt2hgbelntf.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2icmzkdht.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gt2fyvrcboa.html

[U107] JS：数字千分位
来源：http://dali.cdnleiting.top/Article/details/gt2frgrzjuv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2xsbitkqt.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gt2zbijomcd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.0kj1m.cn/Article/details/gt2vzwhvzlv.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gt2mzfcgeud.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2fbvrixzn.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gt2rulrkxzu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gaohongyu789.top/Article/details/gt2hhcusmqv.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gt2yuaywyjn.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gt2jpkkchwy.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gt2tobxudbv.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2gzomkkas.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gt2iaplmljp.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2wuvsgept.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gt2mgxozunq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cawswdtq.html

[U115] JS：生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2odhbkcby.html

crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gt2kkjystqq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gt2qtguznue.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ybcxt.top/Article/details/gt2rqcufyzk.html

[U117] JS：单元测试
来源：http://dali.gogol.net.cn/Article/details/gt2mgyajxke.html

npm i -D vitest;  npx vitest
来源：http://dali.zhiwuduotai.top/Article/details/gt2onumeuot.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gt2xazwdhyl.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gt2rfyqauxe.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gt2hlngithl.html

npx vite build
来源：http://dali.quarkkingdee.top/Article/details/gt2unwoayim.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2livtlcuj.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gt2mmijnkyo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2eydkgbsn.html

统计汇总
来源：http://dali.yangfankeji.com/Article/details/gt2jlhurlow.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2xetnymim.html

按语言统计（条）：
来源：http://dali.jyoumei.cn/Article/details/gt2woaussko.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gt2etflwmob.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmhzefuz.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gt2twjaykyu.html

TypeScript ..... 212
来源：http://dali.dashuyun.cn/Article/details/gt2kquarpoj.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gt2jnqmdlji.html

Go ............. 212
来源：http://dali.ehwqpu.com/Article/details/gt2ozbikjgt.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmikrsxt.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gt2akhjgppw.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gt2bwmbkfob.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gt2bmomofyc.html

SQL ............ 90
来源：http://dali.zhengqikj.top/Article/details/gt2dqhnfvvx.html

Bash ........... 80
来源：http://dali.svipenyu.cn/Article/details/gt2sctlbnbw.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gt2sbosupee.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2xlltyctr.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gt2bfaiuklm.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gt2jqqsrbtn.html

Scala .......... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kzmdvmwn.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2isyktasp.html

合计 ........... 2106 条
来源：http://dali.pycfn.com/Article/details/gt2dxblyzap.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gt2xblorevg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ydzc1.top/Article/details/gt2kbltvctc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2fcnosckv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2itccfqbb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gt2xouevzte.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zdqjudy.top/Article/details/gt2abnepmwh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2lrmlhmmk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2hhjlabbv.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gt2oszuzjoo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gt2sybotdjt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gt2ifspeppd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2yfybtvuo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2cxxqnuxm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2vytswwtt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gt2yvgtghvo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gt2yuwwxbqa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gt2tivwolao.html

Q SQL 专题                              90
来源：http://dali.zhengqikj.top/Article/details/gt2ztjsdakm.html

R Bash 专题                             80
来源：http://dali.ivvv.top/Article/details/gt2szhcvsmo.html

S C / C++ 专题                          60
来源：http://dali.smart0.xyz/Article/details/gt2rifrfgdl.html

T 其他语言补充                          60
来源：http://dali.hongshengwenyu.top/Article/details/gt2wwthkdes.html

U 高频实用片段                         120
来源：http://dali.chenzaomai.com/Article/details/gt2ruotfidf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2erncotyg.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypbazvkf.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2ctncawfd.html

使用提醒
来源：http://dali.cashguo.top/Article/details/gt2bvmjnpbt.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2odnzpqjj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shuidangran.top/Article/details/gt2xpjtvyga.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jlsjyb.cn/Article/details/gt2blkdhazc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhongyouzk.top/Article/details/gt2gixtusyq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.gotoacloud.top/Article/details/gt2wqnnztwf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yonumen.top/Article/details/gt2eflmvcgn.html

—— 文件结束 ——
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kdcqvqdv.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qaubvhwy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yj20258888.top/Article/details/gt2qbbqsvem.html

Common Programming Examples Cheat Book
来源：http://dali.hongshengwenyu.top/Article/details/gt2folvgoet.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2gkeknigc.html

【收录内容】
来源：http://dali.guowangkeji.top/Article/details/gt2tesgopqz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zdqjudy.top/Article/details/gt2jkkpznck.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.gotoacloud.top/Article/details/gt2ezgocwjj.html

SQL · Bash · C · C++
来源：http://dali.kuanghao11.cn/Article/details/gt2ydwjrodd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.kuanghao11.cn/Article/details/gt2qgknwnqr.html

【使用说明】
来源：http://dali.cqqwz.cn/Article/details/gt2tgpcnknu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.haohaochexian.top/Article/details/gt2zpoznmqz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zycfv.cn/Article/details/gt2ippdzzhg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yonumen.top/Article/details/gt2zzldsdmm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.quarkkingdee.top/Article/details/gt2ijbcxxps.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gt2friatrxl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.andypj.xyz/Article/details/gt2npgrsbhz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sweek.top/Article/details/gt2urnhpahd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nwbrower.top/Article/details/gt2jkmbqkbp.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.wangshuangyany.cn/Article/details/gt2scpaphjx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.meibo888.top/Article/details/gt2qogedggu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gzhubu.top/Article/details/gt2unqvdzie.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2cjricbrt.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gt2sluhyieh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yvedp.cn/Article/details/gt2vwffshye.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2mzagnvpp.html

目  录
来源：http://dali.zhixingplan.top/Article/details/gt2sinqumjr.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gt2yhzqeztq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2rygvqcqj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yj20258888.top/Article/details/gt2fjubgwsr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hywenlv.cn/Article/details/gt2rmupunmz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2benphboj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shgmxxki.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.hfpthk.cn/Article/details/gt2nworduzr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gt2slhubajp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2egqfnuvu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2vipkzrgv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.sysykeji.top/Article/details/gt2myoqluki.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gt2esetzclr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yesrvdfu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gzhubu.top/Article/details/gt2tathapfc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2hojwgjga.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqearwot.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2cgowvafj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aibaodan.cn/Article/details/gt2pujaombr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xuanzx.com/Article/details/gt2qvbhqxkj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jianghu66.top/Article/details/gt2vchqfsca.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2raguzywm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gt2wfmoetyy.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2drusnltr.html

A. 基础语法与类型
来源：http://dali.sysykeji.top/Article/details/gt2jpuonunp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2ukliqesi.html

[A01] Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omlimobd.html

Py:   print("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmvrraeo.html

PHP:  echo "Hello, World!";
来源：http://dali.jyoumei.cn/Article/details/gt2xchiepxi.html

JS:   console.log("Hello, World!");
来源：http://dali.gotoacloud.top/Article/details/gt2ceyyrrqx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.0kj1m.cn/Article/details/gt2rimidujv.html

Java: System.out.println("Hello, World!");
来源：http://dali.tianlin.xyz/Article/details/gt2ciebgmyz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gt2pjziortw.html

Ruby: puts "Hello, World!"
来源：http://dali.0kj1m.cn/Article/details/gt2kxzsawdx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gt2jvircpkg.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gt2gagvuaoy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.sufxvd.cn/Article/details/gt2cybxhjyy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yuxming.cn/Article/details/gt2hohtolpz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xinyue.icu/Article/details/gt2hlnwaphl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2jhahcvbh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hammf.cn/Article/details/gt2vggdfcnj.html

Go:   name := "Alex"; age := 20
来源：http://dali.iojbl.cn/Article/details/gt2wxfuvsfr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gt2txcqezuo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gt2ultobdgy.html

[A03] 常量定义
来源：http://dali.haohaochexian.top/Article/details/gt2rjdhocdx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hywenlv.cn/Article/details/gt2oximybfj.html

PHP:  const PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gt2xkjwiqjt.html

JS:   const PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2hqifzfvt.html

TS:   const PI: number = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2viismkfi.html

Java: static final double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2ycdryoeq.html

Go:   const PI = 3.14159
来源：http://dali.c1oappe.top/Article/details/gt2ikjjkyqm.html

Ruby: PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gt2gwjiygmm.html

C#:   const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmufryyb.html

[A04] 判断变量类型
来源：http://dali.aizwys.cn/Article/details/gt2tlmycqkt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gt2jromjjyj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.316326.xyz/Article/details/gt2cyozxhdy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.snrcjt.cn/Article/details/gt2kzcmghbr.html

TS:   typeof x; x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gt2laevcdmi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gt2vstximxv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.nwbrower.top/Article/details/gt2tvbqeqig.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zycfv.cn/Article/details/gt2wpldlawo.html

C#:   x.GetType().Name; x is int
来源：http://dali.cashguo.top/Article/details/gt2qmzxopqz.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gt2ocobnqla.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xuanzx.com/Article/details/gt2eekxwfeg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gt2gcmbkmqh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2pknppxjb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2cqixsgun.html

Java: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sobekatq.html

Go:   7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2sfiqisas.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2qckhuxmi.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gt2xqolwufw.html

[A06] 字符串转数字
来源：http://dali.nanxuanxn.top/Article/details/gt2gmjvflei.html

Py:   int("42"); float("3.14")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbqbiwqc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fzhhl.top/Article/details/gt2jksdapaj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.meibo888.top/Article/details/gt2bzjihvko.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sxryk.cn/Article/details/gt2fmvxhiwq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shzxlz.cn/Article/details/gt2yuiwpoix.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.guannengcc.top/Article/details/gt2tsalelfp.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.tianlin.xyz/Article/details/gt2nihfklvz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hfrjlwid.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gt2cjnopozq.html

Py:   str(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jchfetna.html

PHP:  (string) 42; strval(42)
来源：http://dali.ydzc1.top/Article/details/gt2vvdkykpf.html

JS:   String(42); (42).toString()
来源：http://dali.jqgfzy.top/Article/details/gt2nlcfbmwi.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2mphbpnep.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xylfe.cn/Article/details/gt2inmhoaen.html

Go:   strconv.Itoa(42)
来源：http://dali.yj20258.top/Article/details/gt2bscmqwlr.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gt2ddnpbvbm.html

C#:   42.ToString()
来源：http://dali.zhoulong.xyz/Article/details/gt2vbdptkik.html

[A08] 取整与四舍五入
来源：http://dali.zdqjudy.top/Article/details/gt2oxsmucpi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijozkwkh.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gt2uwkdotbf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2kpnogrja.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hywenlv.cn/Article/details/gt2quqjvskq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gt2cgrqzbve.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gt2ojclqbeo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tianlin.xyz/Article/details/gt2jlldnreg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hnxiangtu.top/Article/details/gt2ufmbrdjp.html

[A09] 绝对值与最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2gzaowuqa.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjecusxb.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2sfnqozip.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2rzjqcevp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2imecfgiz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2iclfaqmw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbdngsaq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258888.top/Article/details/gt2obefktxj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asfgxmky.html

[A10] 生成随机数
来源：http://dali.iojbl.cn/Article/details/gt2fvnposbo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gt2exqzqqbu.html

PHP:  random_int(1, 100);
来源：http://dali.hammf.cn/Article/details/gt2zgtsoftj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gt2yzhehyir.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gt2ebteeywe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.kuanghao11.cn/Article/details/gt2spnmvkvf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqiznpqx.html

Ruby: rand(1..100)
来源：http://dali.gogol.net.cn/Article/details/gt2icrqbksn.html

C#:   new Random().Next(1, 101)
来源：http://dali.xylfe.cn/Article/details/gt2pncadtbd.html

[A11] 条件表达式（三元）
来源：http://dali.pycfn.com/Article/details/gt2uevgjxzp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gogol.net.cn/Article/details/gt2gxscrijg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gt2jddgagoy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gt2kqlubpdk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2hnbmxxxy.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gt2eydalhij.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hfpthk.cn/Article/details/gt2oxiiahhd.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yvedp.cn/Article/details/gt2egijqtqp.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gt2afwycuyq.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenzaomai.com/Article/details/gt2jxrlaviu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.kuanghao11.cn/Article/details/gt2ptvfdfqx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jqgufenzy.top/Article/details/gt2hufdwjto.html

JS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gt2zlhpnggc.html

TS:   `Hello, ${name}!`
来源：http://dali.zhixingplan.top/Article/details/gt2mqixkhjr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.vqdsnc.cn/Article/details/gt2isxvcicw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jianghu66.top/Article/details/gt2syiqfgst.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gt2egsevkhf.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gt2rtzwouol.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yonumen.top/Article/details/gt2qbmvblqx.html

Py:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2bjgfcxyi.html

PHP:  "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2pbyugusm.html

JS:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gt2xkafnvdv.html

TS:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gt2jfdrrzqf.html

Java: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2uqemvekj.html

Go:   "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gt2bmfeazci.html

Ruby: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gt2jehpuxvt.html

C#:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2vxvniwyw.html

[A14] 注释写法
来源：http://dali.yanxiufei.cn/Article/details/gt2jeltwxuf.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.andypj.xyz/Article/details/gt2jqmeohbc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2rzpfulef.html

JS:   // 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gt2czkbacva.html

TS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gt2lvunrjho.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.cashguo.top/Article/details/gt2puwyzhxz.html

Go:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2oaufgbhu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.pycfn.com/Article/details/gt2cjytmlxy.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjvvmves.html

[A15] 空值判断与默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2owufibjm.html

Py:   value = data or "默认值"
来源：http://dali.dashuyun.cn/Article/details/gt2tjygfbte.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2euqsicns.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gt2xflonfet.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gt2whunrbsn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fzhhl.top/Article/details/gt2lifyotyn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.birdmap.top/Article/details/gt2tqeriaep.html

Ruby: value = data || "默认值"
来源：http://dali.jyoumei.cn/Article/details/gt2qhjyhwzp.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2irplawcv.html

[A16] 真假值判断规则
来源：http://dali.hnqzz.top/Article/details/gt2wapendap.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yuanzhike.top/Article/details/gt2srfilvqd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zycfv.cn/Article/details/gt2gpsggjen.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gt2jjugxfmk.html

TS:   if (!x) {}
来源：http://dali.iojbl.cn/Article/details/gt2gdjeoyge.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2fbhypugf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yangfankeji.com/Article/details/gt2vuqkmuke.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.bjfxy.top/Article/details/gt2grcgrevn.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ontbopca.html

[A17] 位运算
来源：http://dali.ppjwa.cn/Article/details/gt2mgtnbzvm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2xyocjujq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2oyvqyomq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gt2utpyaaxg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2nmxsxxqa.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gt2exxyygny.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2qxhpdaog.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gt2gpmnbprt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2ljdsuhvo.html


<!-- 参考信息 -->