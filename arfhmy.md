代发 wailian999

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtcrjwpnge.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jyoumei.cn/Article/details/gtyfauclyu.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gttusxhluf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtmcbismym.html

[U105] JS：节流
来源：http://dali.ppjwa.cn/Article/details/gtsdqjkshn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cheryme.top/Article/details/gtmkntxfny.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gtldtsbokh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gtmnjrrwzx.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gtcfqkiprr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.daxiang520.top/Article/details/gtnthqcsmu.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtygrwmbwh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.kuanghao11.cn/Article/details/gtoxyjabwp.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gtbcjmouay.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtnrargieh.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gtxgxwlbrn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.c1oappe.top/Article/details/gtjywisrjc.html

[U111] JS：对象转 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtblisqykr.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtnnlirwif.html

[U112] JS：字符串补位
来源：http://dali.jinqigufen.top/Article/details/gtxnivilum.html

"7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gthyhpycve.html

[U113] JS：正则替换全部
来源：http://dali.sysykeji.top/Article/details/gttfepypar.html

s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gttjmthevi.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtibambkdo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtndbbsdxf.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtsjarwrfy.html

crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtbrfwrlso.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aizwys.cn/Article/details/gtlkeuqzcm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jlsjyb.cn/Article/details/gtlaloykyg.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtzonnrkpc.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gttejnqada.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtthswjdjv.html

npm i -D vite;  npx vite
来源：http://dali.ybcxt.top/Article/details/gtjfqnslwm.html

[U119] JS：生产构建
来源：http://dali.sweek.top/Article/details/gtrgnpymni.html

npx vite build
来源：http://dali.tian-w.cn/Article/details/gtyknzkbto.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtwqpfxqvk.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gtjqvlcemr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtufmqhtok.html

统计汇总
来源：http://dali.gotoacloud.top/Article/details/gtxyrbmvbk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gttgewucxh.html

按语言统计（条）：
来源：http://dali.shanyushiyangtech.top/Article/details/gtudancgew.html

Python ......... 252
来源：http://dali.snrcjt.cn/Article/details/gtbxucdddp.html

PHP ............ 252
来源：http://dali.jlsjyb.cn/Article/details/gtyhafpbbg.html

JavaScript ..... 252
来源：http://dali.yangfankeji.com/Article/details/gtflftxtlf.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gtmnhkquxj.html

Java ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtcokrorvy.html

Go ............. 212
来源：http://dali.haohaochexian.top/Article/details/gtppfmitli.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gtmfwfwkcz.html

C# ............. 212
来源：http://dali.nanxuanxn.top/Article/details/gtchzxnnnz.html

C .............. 30
来源：http://dali.cdnleiting.top/Article/details/gtloxvaiww.html

C++ ............ 30
来源：http://dali.cheryme.top/Article/details/gtbestttzw.html

SQL ............ 90
来源：http://dali.guowangkeji.top/Article/details/gthhshewrw.html

Bash ........... 80
来源：http://dali.hywenlv.cn/Article/details/gtgcnrkpjq.html

Kotlin ......... 15
来源：http://dali.fzhhl.top/Article/details/gtdluetszr.html

Swift .......... 15
来源：http://dali.hywenlv.cn/Article/details/gtlibckgti.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gttxazkglw.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtfuanjwey.html

Scala .......... 10
来源：http://dali.jinqigfzy.top/Article/details/gtxshlfsio.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtxvyiprvb.html

合计 ........... 2106 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkpsbtnj.html

按章节统计：
来源：http://dali.wangshuangyany.cn/Article/details/gtgvkftyqn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gtimiecrkh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gthmxnmdgo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtnynjdbsn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtvhmjmsxq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jiagoushi.top/Article/details/gtlrcdbrhn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gtwmslpzqe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtwnzvlcjc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtkxxkysdf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtbdekcwoy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gttboipted.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtpsuzzfed.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtuvqiwguu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gtegjapkjw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtwwmwkcbp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabowgssk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtedqkgech.html

Q SQL 专题                              90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqixvzdhd.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gtcgbebpzz.html

S C / C++ 专题                          60
来源：http://dali.0kj1m.cn/Article/details/gtetcsclee.html

T 其他语言补充                          60
来源：http://dali.hfpthk.cn/Article/details/gtnqkdqaot.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtwjsetzdi.html

------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtangskmsv.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gtyfqitokv.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gtwscxzbry.html

使用提醒
来源：http://dali.iojbl.cn/Article/details/gtucucinnb.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtekxcjaag.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.gzhubu.top/Article/details/gtilynltji.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.andypj.xyz/Article/details/gtlcykolkv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.feifeiyinyue.top/Article/details/gtjsyylrql.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gtxmmzdwsn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yangfankeji.com/Article/details/gtyullvobm.html

—— 文件结束 ——
来源：http://dali.feifeiyinyue.top/Article/details/gtqxkcdugl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttaioxxgs.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xziqi.cn/Article/details/gtciwhqidi.html

Common Programming Examples Cheat Book
来源：http://dali.haohaochexian.top/Article/details/gttsekvtyp.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfdfhweiy.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gtdcbzdiva.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.mhx1999.top/Article/details/gthpgedkwq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gtdxkbqahi.html

SQL · Bash · C · C++
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoijpejv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.c1oappe.top/Article/details/gthjdrximo.html

【使用说明】
来源：http://dali.yanxiufei.cn/Article/details/gtzesaekbf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrkwxox.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jiagoushi.top/Article/details/gtdfukxilf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guannengcc.top/Article/details/gtcmuoimdi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.fengsongda.top/Article/details/gtfimuqdwv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.bjfxy.top/Article/details/gtmmdxdvoi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yanxiufei.cn/Article/details/gtsquzlkjc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.tanke756.top/Article/details/gtvhxtygtg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gtamqdchil.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.gaohongyu789.top/Article/details/gtudkulnpu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xuetiantiany.cn/Article/details/gttyknrwtt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.svipenyu.cn/Article/details/gttdmbgqna.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gtlajjnkcu.html

【文件统计】
来源：http://dali.316326.xyz/Article/details/gthlbijftr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtavsinumz.html

--------------------------------------------------------------------------------
来源：http://dali.xylfe.cn/Article/details/gtcarilitc.html

目  录
来源：http://dali.shuidangran.top/Article/details/gtqfpapfyb.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtwxrbtqzz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewbusgqj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtrdkahhlo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwehzxoie.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.mhx1999.top/Article/details/gtbieztspd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.gaohongyu789.top/Article/details/gtcvsdgkat.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtzpwwqbdd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtnvdiygyu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gtxqwqjkes.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtfzvxnhky.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.mhx1999.top/Article/details/gtntkeyagf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gtbvraqzcn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gttpcyvuks.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtknkwenqz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.guowangkeji.top/Article/details/gtnqngwmdm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zycfv.cn/Article/details/gtebdxunaq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtjwojvdlb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gticqzkjcw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtqoshxuds.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hywenlv.cn/Article/details/gtfeorxwsr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gtettdbghn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gtlguzabff.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtnudauoqq.html

A. 基础语法与类型
来源：http://dali.redwolf501.top/Article/details/gtozkfbimt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttiixmlsz.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtyeihccca.html

Py:   print("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtjusurrav.html

PHP:  echo "Hello, World!";
来源：http://dali.sweek.top/Article/details/gtadzitfyj.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtrcfvemqx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jinghuilouyu.cn/Article/details/gtojzxpplc.html

Java: System.out.println("Hello, World!");
来源：http://dali.kuanghao11.cn/Article/details/gtgwkpvwgu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.nwbrower.top/Article/details/gtnzvxgxhu.html

Ruby: puts "Hello, World!"
来源：http://dali.yanxiufei.cn/Article/details/gtuinnegio.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.wangshuangyany.cn/Article/details/gtbsmmtaqt.html

[A02] 变量声明与赋值
来源：http://dali.jinghuilouyu.cn/Article/details/gtejurnpow.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.vqdsnc.cn/Article/details/gtsdyycbfp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtlxicqdgh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.sxryk.cn/Article/details/gtejuuhhjq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gtiwicexbi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtyglrjjzc.html

Go:   name := "Alex"; age := 20
来源：http://dali.shzxlz.cn/Article/details/gtslfwfgzw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gtcvgpcpkp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cqqwz.cn/Article/details/gtklwkfbzf.html

[A03] 常量定义
来源：http://dali.yj20258888.top/Article/details/gthhgyrtxi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzkxyizp.html

PHP:  const PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gthfzrnikm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtburaqdps.html

TS:   const PI: number = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gttqcaqimc.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gttnfkeuhw.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtpmkkynss.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtelrwfklp.html

C#:   const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrwmdous.html

[A04] 判断变量类型
来源：http://dali.fengsongda.top/Article/details/gtlvmibtqq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.sweek.top/Article/details/gthaotqyiy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtinfofjol.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sweek.top/Article/details/gtkghplvie.html

TS:   typeof x; x instanceof Date
来源：http://dali.feifeiyinyue.top/Article/details/gtrsybtrun.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.sxryk.cn/Article/details/gtzhsyjkdv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gtvtqtdvou.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shangyingyoupin.top/Article/details/gtaltroqit.html

C#:   x.GetType().Name; x is int
来源：http://dali.redwolf501.top/Article/details/gtcvjrtnoj.html

[A05] 整数除法与取模
来源：http://dali.chenzaomai.com/Article/details/gtgalrpnrq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gtisieuwjo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtrmmxvvsb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtsvdaabdo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtgghkuqva.html

Java: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtmtbbeira.html

Go:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtniycxifh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtatugnazh.html

C#:   7 / 2; 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtjkuulpty.html

[A06] 字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtcasuziqp.html

Py:   int("42"); float("3.14")
来源：http://dali.yueranfly.top/Article/details/gtvqibtyco.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtxpvrxzct.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjgfftmag.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrblydgn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.cheryme.top/Article/details/gtfitovmpi.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj20258.top/Article/details/gtimklfiqw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gtsmnzufur.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gtjrhltdke.html

[A07] 数字转字符串
来源：http://dali.sufxvd.cn/Article/details/gtmnxdxcax.html

Py:   str(42)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqekerkp.html

PHP:  (string) 42; strval(42)
来源：http://dali.gogol.net.cn/Article/details/gtqpctqqhm.html

JS:   String(42); (42).toString()
来源：http://dali.gogol.net.cn/Article/details/gtlyqpbauq.html

TS:   String(42)
来源：http://dali.zhongyouzk.top/Article/details/gtmdkxugok.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.redwolf501.top/Article/details/gtiwyrxrvi.html

Go:   strconv.Itoa(42)
来源：http://dali.jlsjyb.cn/Article/details/gtcbnrnisa.html

Ruby: 42.to_s
来源：http://dali.yueranfly.top/Article/details/gtepprxzbm.html

C#:   42.ToString()
来源：http://dali.guannengcc.top/Article/details/gtipaofijc.html

[A08] 取整与四舍五入
来源：http://dali.hnqzz.top/Article/details/gtskxiguof.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gtrxcopcwd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gtutnkofci.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtuwtqqpad.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhiwuduotai.top/Article/details/gtuhrrgszm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gturcmwoym.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gtqsppisjf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvknynzua.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtnqaktzuf.html

[A09] 绝对值与最大最小值
来源：http://dali.chenlongwang.top/Article/details/gtpgmvzxuy.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtfzjhcjfv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtbguxfulo.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtesenicpe.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtwnxmuxlz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtdfbusmvo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.bjfxy.top/Article/details/gtjnpqkywi.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yonumen.top/Article/details/gttisbmdxo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtokffnljc.html

[A10] 生成随机数
来源：http://dali.zhengqikj.top/Article/details/gtefuvufdq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffotefpw.html

PHP:  random_int(1, 100);
来源：http://dali.zhoulong.xyz/Article/details/gtzdadhnwe.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.andypj.xyz/Article/details/gtxaaqzdmn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtrigtwrwh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.gzhubu.top/Article/details/gtznzmiwig.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xziqi.cn/Article/details/gtamcaiuvn.html

Ruby: rand(1..100)
来源：http://dali.chenzaomai.com/Article/details/gtkhkolrht.html

C#:   new Random().Next(1, 101)
来源：http://dali.daxiang520.top/Article/details/gtiolrtivc.html

[A11] 条件表达式（三元）
来源：http://dali.xziqi.cn/Article/details/gtvnphqsls.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xinyue.icu/Article/details/gtcurzltsg.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtmtrzgvkj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtpynlpgny.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gtunikvjtb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtghmjsqld.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwccoauyt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gteuflykfl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtnlqubjgl.html

[A12] 字符串插值 / 格式化
来源：http://dali.bjfxy.top/Article/details/gtyuhqczcd.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.dianchejie.cn/Article/details/gtrkjujmrs.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nanxinkj.top/Article/details/gtakzcvwly.html

JS:   `Hello, ${name}!`
来源：http://dali.shzxlz.cn/Article/details/gtzjeknqsc.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigufen.top/Article/details/gtmnywwrcj.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenlongwang.top/Article/details/gtwccfiuwn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aizwys.cn/Article/details/gthiogabbr.html

Ruby: "Hello, #{name}!"
来源：http://dali.bjfxy.top/Article/details/gtlivrbwnv.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gthvlggxzj.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xziqi.cn/Article/details/gtmkwizusc.html

Py:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtwrjdnxqi.html

PHP:  "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtymgaudal.html

JS:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtkkqxofom.html

TS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtczrdnwjd.html

Java: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtoizefvbl.html

Go:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtddzwwyte.html

Ruby: "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtokycmanj.html

C#:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtjgfzduix.html

[A14] 注释写法
来源：http://dali.ivvv.top/Article/details/gtozugtlpw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnqzz.top/Article/details/gtszcgbgub.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gtopsbhpfm.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtkipwyesd.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaidretvf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.haohaochexian.top/Article/details/gtyqwcjdfm.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtnhbiqybr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.aibaodan.cn/Article/details/gtypysxxdf.html

C#:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gthmztsmdl.html

[A15] 空值判断与默认值
来源：http://dali.sufxvd.cn/Article/details/gtosgbmlmz.html

Py:   value = data or "默认值"
来源：http://dali.ppjwa.cn/Article/details/gtexranzxc.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxdxjajk.html

JS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtihetlprq.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtlcxzkvnj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.iojbl.cn/Article/details/gtbhmogbpw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtdookxkhf.html

Ruby: value = data || "默认值"
来源：http://dali.mhx1999.top/Article/details/gtduvwkwct.html

C#:   var value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gttzbnzfju.html

[A16] 真假值判断规则
来源：http://dali.yonumen.top/Article/details/gtluzlhdsu.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.havefunace.top/Article/details/gtuferwbud.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cqqwz.cn/Article/details/gtfnijhkxz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigufen.top/Article/details/gtphfzjerz.html

TS:   if (!x) {}
来源：http://dali.hfpthk.cn/Article/details/gtjmjcuagd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ydzc1.top/Article/details/gtrlezxxbz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guowangkeji.top/Article/details/gtoimuskru.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yonumen.top/Article/details/gttfuqawxi.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtehejccin.html

[A17] 位运算
来源：http://dali.zhoulong.xyz/Article/details/gtbjkmokkx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtgwzoferu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tian-w.cn/Article/details/gtdjjvrfgt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtealolwrz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtriiudojq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtggnvpsod.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gttatheajm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtyjosrnvj.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gthblncuwm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.feifeiyinyue.top/Article/details/gtyebrwpni.html

Py:   ord("A"); chr(65)
来源：http://dali.haohaochexian.top/Article/details/gtzxizbeke.html

PHP:  ord("A"); chr(65)
来源：http://dali.wangshuangyany.cn/Article/details/gtsyqrbsyy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gtcpvekrqg.html


<!-- 参考信息 -->