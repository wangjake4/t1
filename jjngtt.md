代发 wailian999

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gt2xrwrzxwz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gt2yfzbmlva.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gt2wldjfsmq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2qnrnpazp.html

[U105] JS：节流
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnywphuq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gt2nadupiqj.html

[U106] JS：日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2zcsjypne.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.0kj1m.cn/Article/details/gt2qfwrtmdh.html

[U107] JS：数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2lyxrzbpj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2cfmyxrgw.html

[U108] JS：随机整数
来源：http://dali.guannengcc.top/Article/details/gt2avghbqun.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gt2svvajgrp.html

[U109] JS：数组分组
来源：http://dali.haohaochexian.top/Article/details/gt2rnkovprj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gt2nmgjhdce.html

[U110] JS：数组分块
来源：http://dali.fzhhl.top/Article/details/gt2jhhwmyte.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gt2fdrcgbbh.html

[U111] JS：对象转 Map
来源：http://dali.tian-w.cn/Article/details/gt2omigvcue.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gt2ivqmmrqe.html

[U112] JS：字符串补位
来源：http://dali.zhoulong.xyz/Article/details/gt2werexbbb.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gt2zpspujkd.html

[U113] JS：正则替换全部
来源：http://dali.c1oappe.top/Article/details/gt2nyvtbmtz.html

s.replaceAll("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2luoezopk.html

[U114] JS：JSON 深比较
来源：http://dali.hnxiangtu.top/Article/details/gt2ibkykmyr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgkfkqt.html

[U115] JS：生成 UUID
来源：http://dali.tanke756.top/Article/details/gt2gddplzlg.html

crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2lojwtmvj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2omcwqdtw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2mfyjnmit.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gt2fvoocoib.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gt2pmronkdg.html

[U118] JS：开发服务器
来源：http://dali.yuanzhike.top/Article/details/gt2dmmgvycd.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gt2kaeuauif.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gt2mpgtdrqd.html

npx vite build
来源：http://dali.ybcxt.top/Article/details/gt2pstkasnp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tanke756.top/Article/details/gt2fapkmkpe.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkaixahp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zpjvltyg.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gt2zzxmjlds.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2oiefpcoh.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gt2zsvfhwfc.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gt2tbefcufp.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gt2ftqdiwtk.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gt2cacohtug.html

TypeScript ..... 212
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmrrwptk.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gt2bzlssumb.html

Go ............. 212
来源：http://dali.tanke756.top/Article/details/gt2hakshjwl.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gt2qlzgtyna.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gt2uwthjupk.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gt2hcqatdjk.html

C++ ............ 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihpmtcdv.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jvlrlxsd.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gt2fpicdjyt.html

Kotlin ......... 15
来源：http://dali.zdqjudy.top/Article/details/gt2jkbqyogp.html

Swift .......... 15
来源：http://dali.jinqigfzy.top/Article/details/gt2sbosrqll.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gt2ztwpehji.html

Perl ........... 10
来源：http://dali.sweek.top/Article/details/gt2demdndoq.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gt2hpcoawzh.html

------------------------------------
来源：http://dali.yvedp.cn/Article/details/gt2ddhjothi.html

合计 ........... 2106 条
来源：http://dali.meibo888.top/Article/details/gt2muslglai.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gt2gtixhewd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cheryme.top/Article/details/gt2wgbvkabx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2gvwhbjbv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2mnrfmchw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvxpvbcz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gt2caaiwczi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yangfankeji.com/Article/details/gt2cvresxxv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gt2kwrncqqd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2xulqndyk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gt2undakpbe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gt2tzoiwunt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gt2tzgyawgf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gt2bdhvetto.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gt2srdcfxtc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2pmaapzag.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cqqwz.cn/Article/details/gt2gebykrsh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2esohwyze.html

Q SQL 专题                              90
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvbrncum.html

R Bash 专题                             80
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upvntydp.html

S C / C++ 专题                          60
来源：http://dali.tian-w.cn/Article/details/gt2urpqdxtj.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gt2unaxdlfr.html

U 高频实用片段                         120
来源：http://dali.smart0.xyz/Article/details/gt2hwupijje.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2lmsqlkpg.html

合计                                  2106 条
来源：http://dali.wangdashe.top/Article/details/gt2yvsgvobh.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gt2tjmrqqtk.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gt2qybmbjcc.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2ljtytwdo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.haohaochexian.top/Article/details/gt2aklcjaiz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gt2quwftrko.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ppjwa.cn/Article/details/gt2ffypsfyv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangdashe.top/Article/details/gt2dcsbcafu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yuanzhike.top/Article/details/gt2oqnjsslx.html

—— 文件结束 ——
来源：http://dali.zdqjudy.top/Article/details/gt2ozarhffd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2lchcjaeb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uuxfwhan.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gt2huoxzrkh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2rayurlsp.html

【收录内容】
来源：http://dali.0kj1m.cn/Article/details/gt2ljymzzcx.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.haohaochexian.top/Article/details/gt2rlzbhqjk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfaestwm.html

SQL · Bash · C · C++
来源：http://dali.redwolf501.top/Article/details/gt2rwtxibbt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.316326.xyz/Article/details/gt2fovfzvos.html

【使用说明】
来源：http://dali.gogol.net.cn/Article/details/gt2vdnyurus.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cqqwz.cn/Article/details/gt2zrbcnkvv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daria6918.cn/Article/details/gt2sjeirdua.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jqgfzy.top/Article/details/gt2jrtaqbfj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.tian-w.cn/Article/details/gt2eugsgalz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axjsxoaw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.smart0.xyz/Article/details/gt2zgqfrqeo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nanxinkj.top/Article/details/gt2xpkmpbev.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.wangdashe.top/Article/details/gt2lnhdbwxv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhixingplan.top/Article/details/gt2wbbjcoup.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2ywqsvtcw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gt2lwvbtmyn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zdqjudy.top/Article/details/gt2pmabxnuz.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gt2andeaipk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yonumen.top/Article/details/gt2upgoyirr.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2qzzlxzzl.html

目  录
来源：http://dali.quarkkingdee.top/Article/details/gt2qrxcspgu.html

--------------------------------------------------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2zcgjwzvu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gt2aniifawn.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2zthrtwvl.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvsecbjy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yj202588.top/Article/details/gt2kjzdwlml.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcyycdgm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gt2lzkhpqrz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.tian-w.cn/Article/details/gt2ratkrhqm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2scrxrrvh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gt2zlxssbpa.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gt2kiumkowj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gt2sytsvmgr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gt2yldchzjw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gt2noiknhbz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gt2kbwinkuh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2cftdemyu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gt2fqpetriz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ydzc1.top/Article/details/gt2xvodhbix.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gt2molznbjd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.tian-w.cn/Article/details/gt2bzkezihy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gt2bcjrieim.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gt2iklzbazz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqdcuvsa.html

A. 基础语法与类型
来源：http://dali.zhongyouzk.top/Article/details/gt2iazjwuto.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2gaiqnxee.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2ajlprtst.html

Py:   print("Hello, World!")
来源：http://dali.redwolf501.top/Article/details/gt2tiwxletg.html

PHP:  echo "Hello, World!";
来源：http://dali.yj202588.top/Article/details/gt2gvuqrijf.html

JS:   console.log("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogzbhzhy.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gt2myvtmzuz.html

Java: System.out.println("Hello, World!");
来源：http://dali.nanxinkj.top/Article/details/gt2rmgaqzyk.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.guowangkeji.top/Article/details/gt2gwfjlmzz.html

Ruby: puts "Hello, World!"
来源：http://dali.chenlongwang.top/Article/details/gt2ltzibvga.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xylfe.cn/Article/details/gt2yflfiqjl.html

[A02] 变量声明与赋值
来源：http://dali.jqgfzy.top/Article/details/gt2tktgvroe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.hnqzz.top/Article/details/gt2ucfyxkaz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guannengcc.top/Article/details/gt2yyvhqqxe.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqktfjie.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2bdoqlvlv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.c1oappe.top/Article/details/gt2mppihdol.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gt2roxrbfgx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ehwqpu.com/Article/details/gt2rlcdpwxk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.meibo888.top/Article/details/gt2ivtomlja.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gt2gchwxuxj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ybcxt.top/Article/details/gt2venjekjv.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2jgyotnal.html

JS:   const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2niawetyr.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gt2mnmqnzwf.html

Java: static final double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mlmznlar.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2kioiseln.html

Ruby: PI = 3.14159
来源：http://dali.nanxuanxn.top/Article/details/gt2hvjenwjs.html

C#:   const double PI = 3.14159;
来源：http://dali.havefunace.top/Article/details/gt2zwfasksb.html

[A04] 判断变量类型
来源：http://dali.zdqjudy.top/Article/details/gt2kxrfmqxc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2prlpjmnn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yanxiufei.cn/Article/details/gt2uxcbfuih.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2qvgbciky.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gt2dmykjnkk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hysaishi.cn/Article/details/gt2bbrxvavy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jlsjyb.cn/Article/details/gt2rcdwnhjy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.andypj.xyz/Article/details/gt2qicvvjnp.html

C#:   x.GetType().Name; x is int
来源：http://dali.jqgfzy.top/Article/details/gt2fkqxjjeu.html

[A05] 整数除法与取模
来源：http://dali.jlsjyb.cn/Article/details/gt2vjzbxiki.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.andypj.xyz/Article/details/gt2zwpxjpse.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhbwowid.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shuidangran.top/Article/details/gt2gfjwfbdd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2byhgmqzq.html

Java: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gt2wxmvfhyn.html

Go:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gt2sfztrjlo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gt2hvqpnkpc.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2mrywjdlv.html

[A06] 字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2dpzkuzdy.html

Py:   int("42"); float("3.14")
来源：http://dali.pycfn.com/Article/details/gt2fqoqnoib.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tian-w.cn/Article/details/gt2spmjyxcl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2mvmxagnn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gt2lkcyvvlb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.dashuyun.cn/Article/details/gt2wfunaayn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hysaishi.cn/Article/details/gt2olqkzhhd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.daxiang520.top/Article/details/gt2vvhebfji.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yonumen.top/Article/details/gt2rcejujma.html

[A07] 数字转字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2credynlk.html

Py:   str(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gumicefg.html

PHP:  (string) 42; strval(42)
来源：http://dali.dashuyun.cn/Article/details/gt2fsdaehbn.html

JS:   String(42); (42).toString()
来源：http://dali.guannengcc.top/Article/details/gt2xqhcwtkt.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gt2tpdgvcdj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dianchejie.cn/Article/details/gt2xovpvyvs.html

Go:   strconv.Itoa(42)
来源：http://dali.zhixingplan.top/Article/details/gt2nabuvktw.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gt2ahuhmsig.html

C#:   42.ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2pumitlsv.html

[A08] 取整与四舍五入
来源：http://dali.iojbl.cn/Article/details/gt2kaxgtheu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gt2qzmerksf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.sweek.top/Article/details/gt2eiypcaex.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gt2ybeztqle.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.iojbl.cn/Article/details/gt2rqxyhkuq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gmyplouf.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2eqnatxdu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.ivvv.top/Article/details/gt2oyprleyb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gt2whcowiki.html

[A09] 绝对值与最大最小值
来源：http://dali.yonumen.top/Article/details/gt2gdgweufb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gt2yucjdzoq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2pycteokm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2tdzzrlsh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2jvoyheim.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2narzdfqa.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yueranfly.top/Article/details/gt2zggmkpop.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.shzxlz.cn/Article/details/gt2ffghrdpi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj202588.top/Article/details/gt2fvtevnis.html

[A10] 生成随机数
来源：http://dali.jqgfzy.top/Article/details/gt2unwuucbf.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gogol.net.cn/Article/details/gt2imxchjhe.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gt2akcehgez.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gt2uaruzpcn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dianchejie.cn/Article/details/gt2jlcrijnn.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sxryk.cn/Article/details/gt2eiwlonlq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.fzhhl.top/Article/details/gt2biwddrgz.html

Ruby: rand(1..100)
来源：http://dali.gzhubu.top/Article/details/gt2oqldhghx.html

C#:   new Random().Next(1, 101)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yovkghkr.html

[A11] 条件表达式（三元）
来源：http://dali.nanxuanxn.top/Article/details/gt2zwybwxly.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.xylfe.cn/Article/details/gt2ahvyqcfw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gt2qyjbkdsf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2obvxnodr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gt2sarvnghv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2nzkkpaha.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigufen.top/Article/details/gt2owoqhvvg.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2hphbcyhs.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2ddkfgebt.html

[A12] 字符串插值 / 格式化
来源：http://dali.xylfe.cn/Article/details/gt2drcimsvv.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.snrcjt.cn/Article/details/gt2hxppfmjg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sweek.top/Article/details/gt2lorecdnj.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gt2jttlqiac.html

TS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yikyzsiy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhaibyef.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaqykgmc.html

Ruby: "Hello, #{name}!"
来源：http://dali.zdqjudy.top/Article/details/gt2skvsphlu.html

C#:   $"Hello, {name}!"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mbccvssf.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.cheryme.top/Article/details/gt2etlhiyeu.html

Py:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2gflmdgts.html

PHP:  "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivmafgqu.html

JS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2ntmnvgsh.html

TS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2uszdcxrz.html

Java: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gt2aoctuudk.html

Go:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgevcqnz.html

Ruby: "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2wkbryhwd.html

C#:   "第一行\n第二行"
来源：http://dali.ivvv.top/Article/details/gt2bxtrwkis.html

[A14] 注释写法
来源：http://dali.aibaodan.cn/Article/details/gt2cbytyhse.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnxiangtu.top/Article/details/gt2kwjwlbnh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gt2xcwqsiqr.html

JS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gt2ijsdrvvk.html

TS:   // 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gt2dbvuiwyf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxinkj.top/Article/details/gt2axhpnfkz.html

Go:   // 单行；/* 多行 */
来源：http://dali.dashuyun.cn/Article/details/gt2qidxepgt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jlsjyb.cn/Article/details/gt2lelthfmq.html

C#:   // 单行；/* 多行 */
来源：http://dali.svipenyu.cn/Article/details/gt2juxuktoj.html

[A15] 空值判断与默认值
来源：http://dali.gotoacloud.top/Article/details/gt2fvflctzx.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gt2ftzmmihk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2tsrezhji.html

JS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gt2ublxpiyo.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gt2lbsibhmb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gogol.net.cn/Article/details/gt2unyzozkc.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sufxvd.cn/Article/details/gt2qtpriydt.html

Ruby: value = data || "默认值"
来源：http://dali.nwbrower.top/Article/details/gt2hwcvisdp.html

C#:   var value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gt2ejwvayzu.html

[A16] 真假值判断规则
来源：http://dali.gaohongyu789.top/Article/details/gt2vrbyopwf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xziqi.cn/Article/details/gt2aovpfccd.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgufenzy.top/Article/details/gt2teluhgos.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.9152youxi.cn/Article/details/gt2ruefgxhs.html

TS:   if (!x) {}
来源：http://dali.hysaishi.cn/Article/details/gt2odbhcayv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xylfe.cn/Article/details/gt2gsukqmbt.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnqzz.top/Article/details/gt2ozcienbk.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hywenlv.cn/Article/details/gt2amygqmgy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.andypj.xyz/Article/details/gt2uljemzrd.html

[A17] 位运算
来源：http://dali.mhx1999.top/Article/details/gt2oqzqdhma.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2iplruoqc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj202588.top/Article/details/gt2zrebdbpj.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gt2zfjgzgyn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2ltihfqma.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2gsdrpdbf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gt2oxgmwowm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2yxfixvfp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gt2inyhsvlt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gt2xqmcdumt.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gt2jrgihska.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gt2cibqquxk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gt2mameputf.html


<!-- 参考信息 -->