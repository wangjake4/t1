代发 wailian999

[U101] JS：classList 操作
来源：http://dali.cqqwz.cn/Article/details/gtbjswyygc.html

el.classList.toggle("active")
来源：http://dali.guannengcc.top/Article/details/gtvwrlvjhe.html

[U102] JS：本地存储
来源：http://dali.daria6918.cn/Article/details/gtvdstddxx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.feifeiyinyue.top/Article/details/gtdkxmqsra.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtkxtwceeg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gtobvowlbs.html

[U104] JS：防抖
来源：http://dali.dashuyun.cn/Article/details/gtvcsaicvi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gttmfpztkm.html

[U105] JS：节流
来源：http://dali.tianlin.xyz/Article/details/gtjaycqjut.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtvrnttxit.html

[U106] JS：日期格式化
来源：http://dali.316326.xyz/Article/details/gtedfoifvt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.daria6918.cn/Article/details/gtlvunqqkg.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtxnnkxrgc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtojkykpot.html

[U108] JS：随机整数
来源：http://dali.tian-w.cn/Article/details/gtamtchqss.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gtvtgthovm.html

[U109] JS：数组分组
来源：http://dali.nanxuanxn.top/Article/details/gtvfapcxrk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtksrkstme.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtonhtvcof.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.daria6918.cn/Article/details/gtukjzmybr.html

[U111] JS：对象转 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtymhqizhl.html

new Map(Object.entries(obj))
来源：http://dali.ehwqpu.com/Article/details/gtmtbadklu.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gtepuhzodl.html

"7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtkiqwkzpf.html

[U113] JS：正则替换全部
来源：http://dali.zhaomingkeji.xyz/Article/details/gteenrcrjj.html

s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtwkxvblfn.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gtkqydatrd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtluybeycv.html

[U115] JS：生成 UUID
来源：http://dali.cheryme.top/Article/details/gtpkgkwwcf.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtmejuizfo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gtmopdwfyh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gtcmasitio.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtabnykdye.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtqszvbjyp.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gtnouyeimm.html

npm i -D vite;  npx vite
来源：http://dali.gogol.net.cn/Article/details/gtuktkghjc.html

[U119] JS：生产构建
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylflocmf.html

npx vite build
来源：http://dali.tianlin.xyz/Article/details/gtpnqrgahv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yongpay.top/Article/details/gtbrlshhap.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gtuxiwkiop.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtwketnnxq.html

统计汇总
来源：http://dali.wangdashe.top/Article/details/gtvnliksjj.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtagvcnfyf.html

按语言统计（条）：
来源：http://dali.hongshengwenyu.top/Article/details/gtcwuuckxs.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gtekgwalvh.html

PHP ............ 252
来源：http://dali.chenjidiqi.icu/Article/details/gtwszeqfpf.html

JavaScript ..... 252
来源：http://dali.quarkkingdee.top/Article/details/gtxrkxgywc.html

TypeScript ..... 212
来源：http://dali.cheryme.top/Article/details/gtwzyljsnp.html

Java ........... 212
来源：http://dali.xuanzx.com/Article/details/gtfqsjlglh.html

Go ............. 212
来源：http://dali.0kj1m.cn/Article/details/gtjyqvvjzr.html

Ruby ........... 212
来源：http://dali.chenlongwang.top/Article/details/gthpejrboh.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtcnwacktx.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtwovyipsd.html

C++ ............ 30
来源：http://dali.gotoacloud.top/Article/details/gtadkgtzry.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gtfabykrnf.html

Bash ........... 80
来源：http://dali.zhengqikj.top/Article/details/gtqbkwasvm.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gtjgpjoygc.html

Swift .......... 15
来源：http://dali.yj202588.top/Article/details/gtqjizequd.html

Lua ............ 10
来源：http://dali.pycfn.com/Article/details/gtwdcyigot.html

Perl ........... 10
来源：http://dali.0kj1m.cn/Article/details/gtzuzoorvy.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gtamchwgco.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtpymfubnk.html

合计 ........... 2106 条
来源：http://dali.bjfxy.top/Article/details/gtasuzrupc.html

按章节统计：
来源：http://dali.gotoacloud.top/Article/details/gthzjxtskg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gtpydrqyat.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gttburlpvt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gtxpadfywb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtfvyahedf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtiabsfnfh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.bjfxy.top/Article/details/gttggcilqt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtmvtfuria.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtqmigntzk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtkodyvxov.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gtovazddoh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtvpxufnyr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtcwccvjfw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtbnklzzjc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtxibzmklb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yuanzhike.top/Article/details/gtmlqwehiy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvmsupmr.html

Q SQL 专题                              90
来源：http://dali.zhiwuduotai.top/Article/details/gtamunanvh.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtpckfjzlg.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtsrecimla.html

T 其他语言补充                          60
来源：http://dali.iojbl.cn/Article/details/gtvwhrdjgl.html

U 高频实用片段                         120
来源：http://dali.guannengcc.top/Article/details/gtxopdhlnp.html

------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtwztfgtxv.html

合计                                  2106 条
来源：http://dali.havefunace.top/Article/details/gtfhulxovm.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtiiwjhrnj.html

使用提醒
来源：http://dali.ydzc1.top/Article/details/gtvkszeacx.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtvvhnrohn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gtsztooesx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhixingplan.top/Article/details/gtnnrihzjg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangdashe.top/Article/details/gtiaswrkhw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gtdzuleeme.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuxming.cn/Article/details/gtdqizsazv.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gtxmkacfft.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtxskdphhh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangshuangyany.cn/Article/details/gtiydxosxy.html

Common Programming Examples Cheat Book
来源：http://dali.aizwys.cn/Article/details/gtgcquilzj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdfxobejj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gtzpavyxqa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gtxktjbrlv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbysbnnh.html

SQL · Bash · C · C++
来源：http://dali.ybcxt.top/Article/details/gtctcgnplp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.316326.xyz/Article/details/gtoysxigce.html

【使用说明】
来源：http://dali.yj202588.top/Article/details/gtzbmdznuc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.guowangkeji.top/Article/details/gtqakvntfu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.c1oappe.top/Article/details/gtwcffkcgs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gtxquqdroo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.vqdsnc.cn/Article/details/gtiipvuybl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtqejdhfgz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.aizwys.cn/Article/details/gtkshotmsp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hfpthk.cn/Article/details/gtoruxyjyq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ivvv.top/Article/details/gtbviddyeh.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtfgnszids.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ivvv.top/Article/details/gtgnvcprqw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.birdmap.top/Article/details/gtqufjtkkm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenjidiqi.icu/Article/details/gtteipshps.html

【文件统计】
来源：http://dali.jlsjyb.cn/Article/details/gtaibrvrop.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.cucudq.cn/Article/details/gtgefgxuia.html

--------------------------------------------------------------------------------
来源：http://dali.xuanzx.com/Article/details/gtqvxyloch.html

目  录
来源：http://dali.zhongyouzk.top/Article/details/gtznzgqgqd.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtisfghewc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.birdmap.top/Article/details/gtclaggcip.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtxhfmzxlg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtcdfpiqwc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtpopnstlf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtteyrshbi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtfghvkaqa.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gotoacloud.top/Article/details/gtwzdngndc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hammf.cn/Article/details/gtgdiofnro.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtjtpeezow.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtpflfxhxz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtkwogrgrl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gteukkgkje.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtzgodaxpv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.redwolf501.top/Article/details/gtfaakquku.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dashuyun.cn/Article/details/gttxuxzvin.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtohmojmsr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.guowangkeji.top/Article/details/gtfiituukh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.daria6918.cn/Article/details/gtdjaxljeq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gteropdzok.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtrbbtuqwy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtqwcaofjj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxbkkyqzh.html

A. 基础语法与类型
来源：http://dali.pengpengdd.cyou/Article/details/gtlmsdaqtm.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtfqezipxd.html

[A01] Hello World
来源：http://dali.tian-w.cn/Article/details/gtekonfaxn.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtendaltlf.html

PHP:  echo "Hello, World!";
来源：http://dali.shangyingyoupin.top/Article/details/gtrgbzxpeb.html

JS:   console.log("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtdtybscds.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cqqwz.cn/Article/details/gtpjkxdtwb.html

Java: System.out.println("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gtzarvmsyj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmckzksr.html

Ruby: puts "Hello, World!"
来源：http://dali.zhengqikj.top/Article/details/gtupcmgklp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gthresemdi.html

[A02] 变量声明与赋值
来源：http://dali.zhongyouzk.top/Article/details/gtqlxwhhqk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.kuanghao11.cn/Article/details/gtzudcwcym.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtovyehmrc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gtnysotgpt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.xylfe.cn/Article/details/gtcyrqrxcq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.iojbl.cn/Article/details/gtddmwjjpu.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinghuilouyu.cn/Article/details/gthxrnyffq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.gotoacloud.top/Article/details/gtvjydcjpp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuonnyou.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gtrlhiqtym.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtkmdyhnfu.html

PHP:  const PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtmqhkxclx.html

JS:   const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtrqwxtoiy.html

TS:   const PI: number = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtclshnikj.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gttmdhkhjd.html

Go:   const PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gtldrazgud.html

Ruby: PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gtwzwmlskg.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtwfwvnfea.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gtuxarelhg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hnxiangtu.top/Article/details/gtryxwiaet.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtcrnyrmqk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtrxcdsilx.html

TS:   typeof x; x instanceof Date
来源：http://dali.svipenyu.cn/Article/details/gtldwrlwoy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sweek.top/Article/details/gtrmhavvpv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhiwuduotai.top/Article/details/gtqsqashmj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gtbhdcsfmk.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinqigfzy.top/Article/details/gtgsoasboo.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gttcbpywhr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nwbrower.top/Article/details/gtbwamdsgp.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtekhoyyhk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtxgmbbpzq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtpydknfar.html

Java: 7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtsrbwwhhm.html

Go:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtojpvoxth.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtgrshaipd.html

C#:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmajmtfzc.html

[A06] 字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtoytojeuc.html

Py:   int("42"); float("3.14")
来源：http://dali.gzhubu.top/Article/details/gtzzkrhvli.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhiimboz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gttyedkgfh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258.top/Article/details/gttotyqkiz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnqzz.top/Article/details/gtwbjmxfrp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.cdnleiting.top/Article/details/gtajfkbpxq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shzxlz.cn/Article/details/gthppvusap.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtdtfgspju.html

[A07] 数字转字符串
来源：http://dali.nanxinkj.top/Article/details/gtuwnkemdt.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gtecuvotww.html

PHP:  (string) 42; strval(42)
来源：http://dali.bjfxy.top/Article/details/gthlltvphj.html

JS:   String(42); (42).toString()
来源：http://dali.wangdashe.top/Article/details/gtkbnynfrw.html

TS:   String(42)
来源：http://dali.0kj1m.cn/Article/details/gtwrvxlggn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.andypj.xyz/Article/details/gtaceuxiza.html

Go:   strconv.Itoa(42)
来源：http://dali.haohaochexian.top/Article/details/gtwgpnbdtk.html

Ruby: 42.to_s
来源：http://dali.hammf.cn/Article/details/gtqvrugipj.html

C#:   42.ToString()
来源：http://dali.hfpthk.cn/Article/details/gtvrqqqtvo.html

[A08] 取整与四舍五入
来源：http://dali.jyoumei.cn/Article/details/gtgpnsgbdh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gtkkyhbrrs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.havefunace.top/Article/details/gttdahbqcv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtynbgmjut.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jyoumei.cn/Article/details/gtpvjwgvfn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gtejayvfoq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtsqfejsab.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.tanke756.top/Article/details/gtscexmpog.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.svipenyu.cn/Article/details/gtbcgaepof.html

[A09] 绝对值与最大最小值
来源：http://dali.andypj.xyz/Article/details/gtucgzpghd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtoyoaazvi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtxfcmmoce.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtscilmxtv.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwcjjspmf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtycwerjhq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shuidangran.top/Article/details/gtdxmevjvg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.316326.xyz/Article/details/gthyrhedbl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtgfuwzqji.html

[A10] 生成随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtuxvbewaa.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gtbknejaqh.html

PHP:  random_int(1, 100);
来源：http://dali.gaohongyu789.top/Article/details/gtwaiqjmga.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gtrrdwptne.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gtdhpklhqe.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtedeewxlp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tianlin.xyz/Article/details/gtryxmbmqg.html

Ruby: rand(1..100)
来源：http://dali.ivvv.top/Article/details/gtrtzrefcp.html

C#:   new Random().Next(1, 101)
来源：http://dali.shangyingyoupin.top/Article/details/gtaybkattq.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gtmwzbuccp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jianghu66.top/Article/details/gtuftwacgm.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gttgefcdry.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtwgqehppb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtzmplyvev.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtcpjxnqet.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shuidangran.top/Article/details/gtnjwawzyp.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtcbejsgnf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtsngnxplx.html

[A12] 字符串插值 / 格式化
来源：http://dali.yuanzhike.top/Article/details/gtrwqcsdsg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhiwuduotai.top/Article/details/gtzbzhuzna.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zdqjudy.top/Article/details/gtlbegueph.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtistwqrwe.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gteqgihurn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gtmhciewva.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticytsgiy.html

Ruby: "Hello, #{name}!"
来源：http://dali.ehwqpu.com/Article/details/gtsevlfwby.html

C#:   $"Hello, {name}!"
来源：http://dali.tian-w.cn/Article/details/gtpbldvblg.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.c1oappe.top/Article/details/gtwxutfujl.html

Py:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtyrpypuja.html

PHP:  "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtqnlzowcm.html

JS:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gthegxclaz.html

TS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gteopmcgip.html

Java: "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtzlfwalix.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtvayxlrum.html

Ruby: "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtzdxmdawx.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucgkurnl.html

[A14] 注释写法
来源：http://dali.snrcjt.cn/Article/details/gtlrcalvyz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jianghu66.top/Article/details/gteylintlj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.c1oappe.top/Article/details/gtahrfzhvy.html

JS:   // 单行；/* 多行 */
来源：http://dali.ehwqpu.com/Article/details/gtdsnkvghk.html

TS:   // 单行；/* 多行 */
来源：http://dali.tianlin.xyz/Article/details/gtsxoqvaub.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.daria6918.cn/Article/details/gttoeovsxq.html

Go:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtpyogbkiu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hongshengwenyu.top/Article/details/gtekorwqut.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtbbamjvop.html

[A15] 空值判断与默认值
来源：http://dali.tian-w.cn/Article/details/gtzsywmqlv.html

Py:   value = data or "默认值"
来源：http://dali.ivvv.top/Article/details/gtrcfgjxhx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpirjswcp.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinqigfzy.top/Article/details/gtwjlvqlxr.html

TS:   const value = data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtcwqvlmll.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shangyingyoupin.top/Article/details/gtaxsbaxms.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.pengpengdd.cyou/Article/details/gtchgtucvn.html

Ruby: value = data || "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvrhirho.html

C#:   var value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtuumuutgs.html

[A16] 真假值判断规则
来源：http://dali.zhoulong.xyz/Article/details/gthljanouv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvgqrviq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.fzhhl.top/Article/details/gtvvgxnvat.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gogol.net.cn/Article/details/gtqctjreca.html

TS:   if (!x) {}
来源：http://dali.nanxuanxn.top/Article/details/gtqrbdhmss.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jyoumei.cn/Article/details/gtgnbjalai.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xylfe.cn/Article/details/gtzwlqgplw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigfzy.top/Article/details/gtzzawnrgy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sweek.top/Article/details/gtsdxwhddv.html

[A17] 位运算
来源：http://dali.zhongyouzk.top/Article/details/gtupiunkgc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gthlwluusu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtwzqkxlga.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtdkufctnx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtggvjkybu.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtkpgsanmc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtclpejheb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtstzdudsg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gteswokjyn.html


<!-- 参考信息 -->