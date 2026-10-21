代发 wailian999

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gtodqebnve.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gtxcizutek.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gtoplqrwjv.html

document.querySelector(".item")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmimkgyjg.html

[U101] JS：classList 操作
来源：http://dali.andypj.xyz/Article/details/gttczonyaj.html

el.classList.toggle("active")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtianawtyv.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gtkikwgkcu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.mhx1999.top/Article/details/gteduajfmu.html

[U103] JS：定时器
来源：http://dali.yonumen.top/Article/details/gtsknnozek.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yueranfly.top/Article/details/gtahgxjult.html

[U104] JS：防抖
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgkkpump.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtajgfnhkq.html

[U105] JS：节流
来源：http://dali.zhoulong.xyz/Article/details/gtonmkorzv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtgwxvlswc.html

[U106] JS：日期格式化
来源：http://dali.cucudq.cn/Article/details/gthcndmqgp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtycdgciht.html

[U107] JS：数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gttoixbhlv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ppjwa.cn/Article/details/gtvwyxyoxl.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtvvccunfc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtilkxxodv.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtntmdlfxs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtaarfwlzs.html

[U110] JS：数组分块
来源：http://dali.zhengqikj.top/Article/details/gtuvmujfbr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zycfv.cn/Article/details/gtytuxqzhq.html

[U111] JS：对象转 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcccvlotx.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gtyoecnlxv.html

[U112] JS：字符串补位
来源：http://dali.aibaodan.cn/Article/details/gtpexrgdlf.html

"7".padStart(3, "0")
来源：http://dali.xinyue.icu/Article/details/gtginvpgvs.html

[U113] JS：正则替换全部
来源：http://dali.xuetiantiany.cn/Article/details/gtpiqkmaja.html

s.replaceAll("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpvhnzty.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gticzzlawo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtlsfmaoie.html

[U115] JS：生成 UUID
来源：http://dali.andypj.xyz/Article/details/gttjqjdrko.html

crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghieavyi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gtjnwyxwqg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqvryuwtm.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtxbqrxbpa.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gtnsnqcsft.html

[U118] JS：开发服务器
来源：http://dali.xziqi.cn/Article/details/gtbcmyxvzv.html

npm i -D vite;  npx vite
来源：http://dali.jqgufenzy.top/Article/details/gtqxqhxbat.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gttxwcqzvr.html

npx vite build
来源：http://dali.jqgufenzy.top/Article/details/gtcliwouob.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gttvmijafv.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtrfbuwezi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtolssveqw.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtdeolzsfe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcdusbqvm.html

按语言统计（条）：
来源：http://dali.andypj.xyz/Article/details/gttziowczp.html

Python ......... 252
来源：http://dali.xziqi.cn/Article/details/gttxvnsszp.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtcpvohtcn.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gtcmldtxev.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtojgmsazq.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtvjhgelgq.html

Go ............. 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiflmyyf.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gtcmtkmtvx.html

C# ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtsolrjhdp.html

C .............. 30
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsbdvltb.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gttdanrrzq.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtvnhlybdf.html

Bash ........... 80
来源：http://dali.xuanzx.com/Article/details/gtwxsqyokc.html

Kotlin ......... 15
来源：http://dali.jlsjyb.cn/Article/details/gtahlfjckg.html

Swift .......... 15
来源：http://dali.jiagoushi.top/Article/details/gtvnzsllpv.html

Lua ............ 10
来源：http://dali.zhongyouzk.top/Article/details/gtvvlimrkc.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gtaftoinvj.html

Scala .......... 10
来源：http://dali.fengsongda.top/Article/details/gtkucfewqt.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gtqzteohqn.html

合计 ........... 2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtgguppmbc.html

按章节统计：
来源：http://dali.jyoumei.cn/Article/details/gtzvvlvrdm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gtgwlwgxqg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtcvrkjncw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtruakvfrw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtzqnknite.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtdgwyztxy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinqigufen.top/Article/details/gtoxbuywyl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gtpyoxggxt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xuetiantiany.cn/Article/details/gtjctxekup.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yonumen.top/Article/details/gtjkmzevce.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtggnnhgbj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tian-w.cn/Article/details/gtleqwxdor.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtirmhvysy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtaecblxvi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.mhx1999.top/Article/details/gtophdjsrs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhiwuduotai.top/Article/details/gtwrzppqun.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtzwaguwca.html

Q SQL 专题                              90
来源：http://dali.hywenlv.cn/Article/details/gtacbesmlm.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gtpamfevuv.html

S C / C++ 专题                          60
来源：http://dali.kuanghao11.cn/Article/details/gtsaubihec.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxybmcse.html

U 高频实用片段                         120
来源：http://dali.nwbrower.top/Article/details/gtjaslnshs.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtgfcfazhm.html

合计                                  2106 条
来源：http://dali.yj20258888.top/Article/details/gtkprduvcl.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtwdvbfgco.html

使用提醒
来源：http://dali.iojbl.cn/Article/details/gtzvmfeigz.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtfzklrvlw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.0kj1m.cn/Article/details/gtklsxyydm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ivvv.top/Article/details/gtbftowiht.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.kuanghao11.cn/Article/details/gtfyseyyim.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zycfv.cn/Article/details/gteocfpcyw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.aizwys.cn/Article/details/gtsbraokme.html

—— 文件结束 ——
来源：http://dali.xuanzx.com/Article/details/gtmflnyzbr.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbdifyyme.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.sxryk.cn/Article/details/gtqdjrbaib.html

Common Programming Examples Cheat Book
来源：http://dali.yj20258888.top/Article/details/gtseqqjycw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsymilytv.html

【收录内容】
来源：http://dali.hnxiangtu.top/Article/details/gtlynogehq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.guannengcc.top/Article/details/gtssrvaduq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258.top/Article/details/gtbbsznvxl.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gttqqxxtgo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.smart0.xyz/Article/details/gtpuiqdcyw.html

【使用说明】
来源：http://dali.birdmap.top/Article/details/gtymoammpg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.yongpay.top/Article/details/gtxeldthoj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.gzhubu.top/Article/details/gtfehpyffu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtmwwylelk.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jiagoushi.top/Article/details/gtstduelct.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hongshengwenyu.top/Article/details/gtrmkpvpyy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.fengsongda.top/Article/details/gtgfxdizrp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gtbziqcica.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.iojbl.cn/Article/details/gtjlszhulz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuanzhike.top/Article/details/gtwbtfmpou.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj202588.top/Article/details/gtqprmwhqx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gtpfmwlzhi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sweek.top/Article/details/gtmtajjind.html

【文件统计】
来源：http://dali.gaohongyu789.top/Article/details/gtsfvupqrl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.haohaochexian.top/Article/details/gtqtycheqi.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtzmhqqyhl.html

目  录
来源：http://dali.ivvv.top/Article/details/gtiiildyhk.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtjgyjzzey.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hnxiangtu.top/Article/details/gtjpceeecv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtbtfyofkt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtqppfgfyz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtbftawyso.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.svipenyu.cn/Article/details/gtugfrdoaw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtyypwwjma.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.0kj1m.cn/Article/details/gtfdxycoiw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gzhubu.top/Article/details/gtfoizafez.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gtbxhomtmm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.cashguo.top/Article/details/gtrrkcpixq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtbovjyhqy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtobaibyaz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gtpkbntlew.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guannengcc.top/Article/details/gtwqgvgmsc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gthtyleezz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtpktdsqzk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqkxrbyx.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.snrcjt.cn/Article/details/gtevdwvhvv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.dianchejie.cn/Article/details/gtzhnuxpqm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtpnjjazvm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtppbtpehz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwoegrsvs.html

A. 基础语法与类型
来源：http://dali.gzhubu.top/Article/details/gtydxdkjqd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtkuvdruir.html

[A01] Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtwjxvlzgu.html

Py:   print("Hello, World!")
来源：http://dali.jlsjyb.cn/Article/details/gtmgicjjnp.html

PHP:  echo "Hello, World!";
来源：http://dali.cashguo.top/Article/details/gtckgzsynh.html

JS:   console.log("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtigttdvhb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gtpgumxvsu.html

Java: System.out.println("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtddmnammu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gtumnulkxd.html

Ruby: puts "Hello, World!"
来源：http://dali.yj202588.top/Article/details/gtwtpaanzj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gthheufimx.html

[A02] 变量声明与赋值
来源：http://dali.xziqi.cn/Article/details/gtpxzvofif.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yueranfly.top/Article/details/gthitsmcgc.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtcajfkcam.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gttkleyold.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ybcxt.top/Article/details/gtpeoipuzb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtxzkyepyk.html

Go:   name := "Alex"; age := 20
来源：http://dali.daxiang520.top/Article/details/gtwcgyowns.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nanxuanxn.top/Article/details/gtswkezapi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ivvv.top/Article/details/gtiyhhsilx.html

[A03] 常量定义
来源：http://dali.cashguo.top/Article/details/gtxztehsbr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.9152youxi.cn/Article/details/gtrnwgnnod.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtzczaozzd.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtwuykkqpz.html

TS:   const PI: number = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtyyxmcokb.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gthgkxepzg.html

Go:   const PI = 3.14159
来源：http://dali.dianchejie.cn/Article/details/gtbuxxfsye.html

Ruby: PI = 3.14159
来源：http://dali.zhoulong.xyz/Article/details/gttczypuud.html

C#:   const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtziwnbqnc.html

[A04] 判断变量类型
来源：http://dali.zhixingplan.top/Article/details/gtnphxyfhh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gtbmvmdali.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuanzhike.top/Article/details/gtnpskodbu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jqgfzy.top/Article/details/gthwslwfej.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtfomjgbaz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hnxiangtu.top/Article/details/gtqsfgrroi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gtunekabdx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtzuhiuhqa.html

C#:   x.GetType().Name; x is int
来源：http://dali.quarkkingdee.top/Article/details/gtbjdaqeqc.html

[A05] 整数除法与取模
来源：http://dali.bjfxy.top/Article/details/gtulyuwwos.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbsznsue.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtlvzuoehq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hammf.cn/Article/details/gtjqfrtvwm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gthpdkfess.html

Java: 7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxmpidrk.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiquozwep.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtirqljaan.html

C#:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtbstbhtzk.html

[A06] 字符串转数字
来源：http://dali.cdnleiting.top/Article/details/gtcuimilaj.html

Py:   int("42"); float("3.14")
来源：http://dali.xuetiantiany.cn/Article/details/gtjljijvfb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zycfv.cn/Article/details/gtogninzaz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtxolktsxa.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gtqmovfnmw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gtclmnefzf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xuetiantiany.cn/Article/details/gtrphwnwyd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gtutjzshrf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.316326.xyz/Article/details/gtdxhteqbe.html

[A07] 数字转字符串
来源：http://dali.cdnleiting.top/Article/details/gttqavzkbf.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gtqyxyirwx.html

PHP:  (string) 42; strval(42)
来源：http://dali.c1oappe.top/Article/details/gtmjzageqs.html

JS:   String(42); (42).toString()
来源：http://dali.yvedp.cn/Article/details/gtmlkennzr.html

TS:   String(42)
来源：http://dali.guowangkeji.top/Article/details/gtmzgyavmn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ivvv.top/Article/details/gtdecbkwce.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gtqbmcgxfl.html

Ruby: 42.to_s
来源：http://dali.hongshengwenyu.top/Article/details/gtvussvxwg.html

C#:   42.ToString()
来源：http://dali.hammf.cn/Article/details/gtpweenbfz.html

[A08] 取整与四舍五入
来源：http://dali.gaohongyu789.top/Article/details/gteikeztdr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gtfigdmwid.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tianlin.xyz/Article/details/gtwpujzwsx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtuesnhkat.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pycfn.com/Article/details/gtqhiltudw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtmjjmdryt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtzptspjuz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gtqbaygvcz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmbrcjax.html

[A09] 绝对值与最大最小值
来源：http://dali.cucudq.cn/Article/details/gtplucaqno.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.birdmap.top/Article/details/gtjqabwenc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtjgazerzp.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtdgbllepr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtiinhwonk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gtmxfcxzft.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gtrzqwcndj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhiwuduotai.top/Article/details/gthjegyuir.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouscluyr.html

[A10] 生成随机数
来源：http://dali.cqqwz.cn/Article/details/gtttfndnyt.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yuxming.cn/Article/details/gtlmqmrtae.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gttujvlogn.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gtlulhntlq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gtlzplzkhd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.dashuyun.cn/Article/details/gtawngsyfh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.sufxvd.cn/Article/details/gtozjnavqa.html

Ruby: rand(1..100)
来源：http://dali.smart0.xyz/Article/details/gtlzgweehq.html

C#:   new Random().Next(1, 101)
来源：http://dali.xuanzx.com/Article/details/gtzqivlopv.html

[A11] 条件表达式（三元）
来源：http://dali.yanxiufei.cn/Article/details/gtycurawqp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sxryk.cn/Article/details/gtdtwmdgfw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gtqmtrihaz.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.havefunace.top/Article/details/gtkhhaonrx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtxpwqgdac.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtaiqmxqol.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zdqjudy.top/Article/details/gtwsfujvri.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gtwbenxmjg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtsqgpgnyh.html

[A12] 字符串插值 / 格式化
来源：http://dali.jyoumei.cn/Article/details/gthdcctngg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.gaohongyu789.top/Article/details/gtqxilogcm.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gotoacloud.top/Article/details/gtanutsise.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtkzupnrel.html

TS:   `Hello, ${name}!`
来源：http://dali.pengpengdd.cyou/Article/details/gttoxhdmmh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hnxiangtu.top/Article/details/gtbwkhmjig.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cheryme.top/Article/details/gtzjezzzqf.html

Ruby: "Hello, #{name}!"
来源：http://dali.9152youxi.cn/Article/details/gtiweiccjf.html

C#:   $"Hello, {name}!"
来源：http://dali.hnqzz.top/Article/details/gtwpenxiir.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cqqwz.cn/Article/details/gtrdvymwrj.html

Py:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtaytdykki.html

PHP:  "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtlhrvyxnh.html

JS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtdgmmyyth.html

TS:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtcnntbvhk.html

Java: "第一行\n第二行"
来源：http://dali.chenjidiqi.icu/Article/details/gtddjvdfzj.html

Go:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtyxwtmvef.html

Ruby: "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtapoqqtwm.html

C#:   "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gttehwcvfg.html

[A14] 注释写法
来源：http://dali.ppjwa.cn/Article/details/gtfblucjgh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hammf.cn/Article/details/gtpnvjuzdu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gtcpahbnsu.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsfislat.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gtvuqkknup.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yonumen.top/Article/details/gtytykknbr.html

Go:   // 单行；/* 多行 */
来源：http://dali.chenjidiqi.icu/Article/details/gtmfllotin.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yongpay.top/Article/details/gtudgcsncp.html

C#:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtpbptczdu.html

[A15] 空值判断与默认值
来源：http://dali.shuidangran.top/Article/details/gtfydppyni.html

Py:   value = data or "默认值"
来源：http://dali.c1oappe.top/Article/details/gtgfzjvqrb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gtwbvtrnhn.html

JS:   const value = data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtybhchela.html

TS:   const value = data ?? "默认值";
来源：http://dali.yuxming.cn/Article/details/gtykxuxfcv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.vqdsnc.cn/Article/details/gtitlidaqu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yvedp.cn/Article/details/gtdwjrphfv.html

Ruby: value = data || "默认值"
来源：http://dali.xziqi.cn/Article/details/gtnbcqxnga.html

C#:   var value = data ?? "默认值";
来源：http://dali.cucudq.cn/Article/details/gtavdgtmap.html

[A16] 真假值判断规则
来源：http://dali.yongpay.top/Article/details/gtqvgczqxi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gzhubu.top/Article/details/gtlilzhasl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gtfntevghy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yj20258888.top/Article/details/gtoulzvepb.html

TS:   if (!x) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwggomwmd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.bjfxy.top/Article/details/gtsfeftgsr.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuanzx.com/Article/details/gtwdufhdlp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.redwolf501.top/Article/details/gtnewmgvau.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yuxming.cn/Article/details/gtlzeagoms.html

[A17] 位运算
来源：http://dali.zdqjudy.top/Article/details/gtdsohgdgl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtwsoppvfd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtqxpoxbki.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtymrblibk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtynywhhnm.html


<!-- 参考信息 -->