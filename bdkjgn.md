代发 wailian999

[U103] JS：定时器
来源：http://dali.yonumen.top/Article/details/gt2drhaqcvs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gt2grtmbiyn.html

[U104] JS：防抖
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjdhxkhz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ugriehci.html

[U105] JS：节流
来源：http://dali.mhx1999.top/Article/details/gt2mnqsccgd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkryzgqc.html

[U106] JS：日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktoekigo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.smart0.xyz/Article/details/gt2rglhyylq.html

[U107] JS：数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpyueapl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuanzx.com/Article/details/gt2ayobkxen.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gt2xntjxnfv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sxryk.cn/Article/details/gt2bqixbmva.html

[U109] JS：数组分组
来源：http://dali.cucudq.cn/Article/details/gt2ohpdqpoq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2wwjkcmpw.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gt2zzsmzlpc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gt2lgvfknlz.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gt2paeeuzjr.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2ndnoacpp.html

[U112] JS：字符串补位
来源：http://dali.yangfankeji.com/Article/details/gt2aficzywx.html

"7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2tfngilko.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gt2hajjzoxe.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2hvgroqgj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwxzfww.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2uurlldyl.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2cbogocad.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2rpnnugmz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xinyue.icu/Article/details/gt2ljyvwwwk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gt2xrsteqwg.html

[U117] JS：单元测试
来源：http://dali.sweek.top/Article/details/gt2keiycncv.html

npm i -D vitest;  npx vitest
来源：http://dali.andypj.xyz/Article/details/gt2irplpphz.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gt2lplfjixn.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gt2bjyezyfb.html

[U119] JS：生产构建
来源：http://dali.zdqjudy.top/Article/details/gt2qwtnxzui.html

npx vite build
来源：http://dali.daxiang520.top/Article/details/gt2bafpaoac.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zycfv.cn/Article/details/gt2ownrbikp.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gt2qyaevuwr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2wqhdhmam.html

统计汇总
来源：http://dali.zhengqikj.top/Article/details/gt2tnvhqdhx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2whwggpzl.html

按语言统计（条）：
来源：http://dali.xuanzx.com/Article/details/gt2rlwgzhyf.html

Python ......... 252
来源：http://dali.bjfxy.top/Article/details/gt2ozdznppl.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gt2zaoclvny.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gt2tuhxiqxs.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gt2xlvdkmwg.html

Java ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2ukehihrt.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2qagifpyq.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gt2ohdudpqm.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2ktotasut.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gt2ktchqhdm.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gt2vfxynniq.html

SQL ............ 90
来源：http://dali.hysaishi.cn/Article/details/gt2ypuoenxl.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gt2muqzmajy.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dndvqmar.html

Swift .......... 15
来源：http://dali.hammf.cn/Article/details/gt2acrhofdo.html

Lua ............ 10
来源：http://dali.316326.xyz/Article/details/gt2mxpbzkdl.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gt2ogyrgbsk.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gt2bgvncbdl.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2ywdayxqt.html

合计 ........... 2106 条
来源：http://dali.yvedp.cn/Article/details/gt2lgilgodj.html

按章节统计：
来源：http://dali.vqdsnc.cn/Article/details/gt2npavczkv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gt2bntrhjlj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gt2mamlnxok.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2psqkqcch.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.chenlongwang.top/Article/details/gt2vsmbrzfp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nanxinkj.top/Article/details/gt2odojhgln.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gt2anwiwfwu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gt2uzcbtvug.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gt2ddqdxmhw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2kbbihpwp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gt2rbollstp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2rbfjqzho.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2vulkfqct.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gt2ccpqxops.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gt2uuocungj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhoulong.xyz/Article/details/gt2xxiflnsp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2hgrjwvic.html

Q SQL 专题                              90
来源：http://dali.hammf.cn/Article/details/gt2xxuurdws.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gt2hxrmsxmu.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gt2lrgweoqo.html

T 其他语言补充                          60
来源：http://dali.sysykeji.top/Article/details/gt2pekrbprd.html

U 高频实用片段                         120
来源：http://dali.xinyue.icu/Article/details/gt2srixkagd.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2mgzslest.html

合计                                  2106 条
来源：http://dali.ivvv.top/Article/details/gt2thvfbjsi.html

--------------------------------------------------------------------------------
来源：http://dali.chenjidiqi.icu/Article/details/gt2nycyyuji.html

使用提醒
来源：http://dali.hysaishi.cn/Article/details/gt2ynboptbf.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gt2hdfdkbrv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jqgfzy.top/Article/details/gt2bhvyxbhs.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yvedp.cn/Article/details/gt2hgpismrl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbbxoeqr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuanzhike.top/Article/details/gt2pyrgkkbr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ydzc1.top/Article/details/gt2avqprdei.html

—— 文件结束 ——
来源：http://dali.sxryk.cn/Article/details/gt2dzibrllp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2qumarzol.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.wangshuangyany.cn/Article/details/gt2tadgsxyu.html

Common Programming Examples Cheat Book
来源：http://dali.smart0.xyz/Article/details/gt2evmumtst.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2agkvatfr.html

【收录内容】
来源：http://dali.cashguo.top/Article/details/gt2kyjmywab.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhengqikj.top/Article/details/gt2tzaydruy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yueranfly.top/Article/details/gt2itsjvpsy.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gt2qmalaghl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.mhx1999.top/Article/details/gt2nigfbxcs.html

【使用说明】
来源：http://dali.zdqjudy.top/Article/details/gt2tfmponsx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gt2qofmbaaw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.fengsongda.top/Article/details/gt2oytcubgl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.snrcjt.cn/Article/details/gt2lsyfaqwv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.c1oappe.top/Article/details/gt2kuzlzqji.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yvedp.cn/Article/details/gt2jilkmwwb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifzpqmzb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvbadmft.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tanke756.top/Article/details/gt2clgiwmuu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yuanzhike.top/Article/details/gt2oexmhqrv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gt2byejntvb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.fzhhl.top/Article/details/gt2jcomyqth.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.feifeiyinyue.top/Article/details/gt2ubcituxs.html

【文件统计】
来源：http://dali.cucudq.cn/Article/details/gt2umwwclkd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.daria6918.cn/Article/details/gt2finzlabi.html

--------------------------------------------------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gt2pzhbhtbz.html

目  录
来源：http://dali.daria6918.cn/Article/details/gt2bxprudws.html

--------------------------------------------------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2wsaqaxou.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gt2hrxwrhsb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ydzc1.top/Article/details/gt2vzvmrwuw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.aizwys.cn/Article/details/gt2akoxbkce.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gt2xcliynms.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmfhmkaq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gt2poivbbpt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gt2fogklxty.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2qrvbmlwg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gt2fdqtwlzy.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gt2rbjztpgm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ixktugmk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gt2pkavmzof.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gt2hykzhouc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tanke756.top/Article/details/gt2qzqsmvwd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2bqmyrasq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrwferd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ybcxt.top/Article/details/gt2jgootuvm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2snyymsfd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.c1oappe.top/Article/details/gt2vbsbvvlh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gt2vhuqzmym.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sooxchtj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2gogltnhw.html

A. 基础语法与类型
来源：http://dali.aizwys.cn/Article/details/gt2kpyntepf.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2yrjhdyvr.html

[A01] Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2zzjptmti.html

Py:   print("Hello, World!")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ybnjiprn.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxinkj.top/Article/details/gt2tjqiugmt.html

JS:   console.log("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gt2qmakffcj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.svipenyu.cn/Article/details/gt2dmnfcske.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gt2rpewfabs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gt2ogzctrha.html

Ruby: puts "Hello, World!"
来源：http://dali.gaohongyu789.top/Article/details/gt2tflbodjz.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2flnpdbxk.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gt2kuyjtzvv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.dashuyun.cn/Article/details/gt2zwrjwvzh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gt2bopluxah.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2qwdgozng.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gt2ofkxvtqv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2kcgxjruf.html

Go:   name := "Alex"; age := 20
来源：http://dali.snrcjt.cn/Article/details/gt2vgqaugkt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yueranfly.top/Article/details/gt2tienchmu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yj20258.top/Article/details/gt2aykukafb.html

[A03] 常量定义
来源：http://dali.wangshuangyany.cn/Article/details/gt2zknmxseg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shzxlz.cn/Article/details/gt2wpwlzknr.html

PHP:  const PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfdwurys.html

JS:   const PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2wdkafypn.html

TS:   const PI: number = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2fispiqgm.html

Java: static final double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gt2hcjkyrxz.html

Go:   const PI = 3.14159
来源：http://dali.hnqzz.top/Article/details/gt2dpvtkedc.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2unmqymny.html

C#:   const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2xiekbevv.html

[A04] 判断变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdbwyqih.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqigurob.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yangfankeji.com/Article/details/gt2ffwzljqh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gt2sdfirdfh.html

TS:   typeof x; x instanceof Date
来源：http://dali.meibo888.top/Article/details/gt2zjgrupag.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.iojbl.cn/Article/details/gt2bwlixdto.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jianghu66.top/Article/details/gt2ljngtzmv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.redwolf501.top/Article/details/gt2ttnhynco.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnqzz.top/Article/details/gt2ypezkfvn.html

[A05] 整数除法与取模
来源：http://dali.xylfe.cn/Article/details/gt2tvmteuzg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cashguo.top/Article/details/gt2mropwjld.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cheryme.top/Article/details/gt2qqfmycvk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2kjzugfga.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2xnulpyqm.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgufenzy.top/Article/details/gt2xhikofkp.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2jhwbnazl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gt2kuvwsvwo.html

C#:   7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gt2dghkrlig.html

[A06] 字符串转数字
来源：http://dali.zhengqikj.top/Article/details/gt2sdfgiuja.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2wefjxlns.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lgcxwxni.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqjjiogo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.guannengcc.top/Article/details/gt2twrpbrem.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yvedp.cn/Article/details/gt2pbzgflyh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gt2wmqwsley.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.yuanzhike.top/Article/details/gt2cmdonewu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyszxdkb.html

[A07] 数字转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2uotghibe.html

Py:   str(42)
来源：http://dali.gogol.net.cn/Article/details/gt2qlbtveym.html

PHP:  (string) 42; strval(42)
来源：http://dali.daria6918.cn/Article/details/gt2vhlijxuv.html

JS:   String(42); (42).toString()
来源：http://dali.daria6918.cn/Article/details/gt2ghaydiwq.html

TS:   String(42)
来源：http://dali.hfpthk.cn/Article/details/gt2vgkqrfjs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.daria6918.cn/Article/details/gt2kewwmdtn.html

Go:   strconv.Itoa(42)
来源：http://dali.xinyue.icu/Article/details/gt2chgvfeuq.html

Ruby: 42.to_s
来源：http://dali.jiagoushi.top/Article/details/gt2egwioxkj.html

C#:   42.ToString()
来源：http://dali.smart0.xyz/Article/details/gt2bhbyfjxc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2synwqgej.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.chenlongwang.top/Article/details/gt2tzjyoljt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aizwys.cn/Article/details/gt2iwwciugo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gt2sopijnli.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzulukjw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gt2wbkzelta.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cqqwz.cn/Article/details/gt2xyijblrc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cheryme.top/Article/details/gt2gbryowaq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2jgyppwgo.html

[A09] 绝对值与最大最小值
来源：http://dali.jyoumei.cn/Article/details/gt2qwcpkocn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnqzz.top/Article/details/gt2jexwnwbh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gt2bwjsfqnx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2cjibngmn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2emgffxsd.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2rubndjis.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gogol.net.cn/Article/details/gt2calnpszm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jlsjyb.cn/Article/details/gt2zofronfm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2mgiafyhn.html

[A10] 生成随机数
来源：http://dali.wangdashe.top/Article/details/gt2jxvnrxpw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.havefunace.top/Article/details/gt2segpizsf.html

PHP:  random_int(1, 100);
来源：http://dali.sweek.top/Article/details/gt2ymcgrlpz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhixingplan.top/Article/details/gt2gxynljgq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daxiang520.top/Article/details/gt2gezqbexu.html

Java: new Random().nextInt(100) + 1
来源：http://dali.chenlongwang.top/Article/details/gt2phayhsli.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daxiang520.top/Article/details/gt2tcoewiol.html

Ruby: rand(1..100)
来源：http://dali.quarkkingdee.top/Article/details/gt2bphvxabs.html

C#:   new Random().Next(1, 101)
来源：http://dali.yangfankeji.com/Article/details/gt2cpisintt.html

[A11] 条件表达式（三元）
来源：http://dali.hongshengwenyu.top/Article/details/gt2iutbxxbo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xziqi.cn/Article/details/gt2ndedymhr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gt2lddnpfcg.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2bruzpmsq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2tvfxizma.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhbpwwsp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pengpengdd.cyou/Article/details/gt2qodjgwqb.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2shsdulji.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.pycfn.com/Article/details/gt2girfdlcx.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2grupvxvu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj20258.top/Article/details/gt2shnjamcf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yvedp.cn/Article/details/gt2lbampnhp.html

JS:   `Hello, ${name}!`
来源：http://dali.jiagoushi.top/Article/details/gt2rqnstlgq.html

TS:   `Hello, ${name}!`
来源：http://dali.ehwqpu.com/Article/details/gt2eeamjupn.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eumcdbjw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gt2hmwebmyt.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhixingplan.top/Article/details/gt2srxoszip.html

C#:   $"Hello, {name}!"
来源：http://dali.yj20258.top/Article/details/gt2amruuvbs.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzqcpkdy.html

Py:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2pfbbgqcy.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gt2hqestnud.html

JS:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2mmnkfxku.html

TS:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2bbleltom.html

Java: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gt2ubrrrslo.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2ogvujdit.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2qooysmfq.html

C#:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gt2zhcfcfri.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gt2davrsdwu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.9152youxi.cn/Article/details/gt2tnsahzgu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gt2jlwgnptu.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2etweaonp.html

TS:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2pemdpnxx.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.fengsongda.top/Article/details/gt2whfpravo.html

Go:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2xqvpwzjm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsztucij.html

C#:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2tcuoexwf.html

[A15] 空值判断与默认值
来源：http://dali.zycfv.cn/Article/details/gt2ejyqrgpt.html

Py:   value = data or "默认值"
来源：http://dali.dianchejie.cn/Article/details/gt2yaxmcldd.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.haohaochexian.top/Article/details/gt2doutcgms.html

JS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gt2qxwgstip.html

TS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gt2wnkaxmiu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hysaishi.cn/Article/details/gt2yecnyoqt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.ivvv.top/Article/details/gt2zwotxzar.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigufen.top/Article/details/gt2fboiajrn.html

C#:   var value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gt2kwtyvstw.html

[A16] 真假值判断规则
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfdhmvzn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.gogol.net.cn/Article/details/gt2fgiuluuo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.quarkkingdee.top/Article/details/gt2qwtgybmz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jyoumei.cn/Article/details/gt2elehxmfr.html

TS:   if (!x) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qadqvwut.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2mrbiaxuk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gcupkrpk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.nanxinkj.top/Article/details/gt2rflbkeln.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ayvjsxdw.html

[A17] 位运算
来源：http://dali.wangdashe.top/Article/details/gt2icuqatos.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gt2jooqfxey.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gt2qfvktrrm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2svgzhzov.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ekuqqmmb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2xvwcxtgm.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gt2rsujiqdq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gt2jszvhgmv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkicnzcz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gzhubu.top/Article/details/gt2anhgppgl.html

Py:   ord("A"); chr(65)
来源：http://dali.jyoumei.cn/Article/details/gt2zabgorxd.html

PHP:  ord("A"); chr(65)
来源：http://dali.hongshengwenyu.top/Article/details/gt2acjunapl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gt2lkyxeuep.html


<!-- 参考信息 -->