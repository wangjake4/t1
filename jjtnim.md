代发 wailian999

[U101] JS：classList 操作
来源：http://dali.quarkkingdee.top/Article/details/gt2lzhtrlve.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gt2oojjaawa.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gt2zfkwnefi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jyoumei.cn/Article/details/gt2fwyfvrxc.html

[U103] JS：定时器
来源：http://dali.haohaochexian.top/Article/details/gt2wmwekirs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.birdmap.top/Article/details/gt2fuozoxiv.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gt2vmcbywlf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2tcawgske.html

[U105] JS：节流
来源：http://dali.jqgufenzy.top/Article/details/gt2ajttldfe.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2zksvxozf.html

[U106] JS：日期格式化
来源：http://dali.yj20258888.top/Article/details/gt2qevxchnw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenzaomai.com/Article/details/gt2rsyqeknw.html

[U107] JS：数字千分位
来源：http://dali.hammf.cn/Article/details/gt2lkowubpx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xziqi.cn/Article/details/gt2tvypwhrs.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gt2kaiqsbqq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgufenzy.top/Article/details/gt2hhogazuw.html

[U109] JS：数组分组
来源：http://dali.bjfxy.top/Article/details/gt2pmrztwll.html

Object.groupBy(arr, x => x.type)
来源：http://dali.pycfn.com/Article/details/gt2fzrmrdan.html

[U110] JS：数组分块
来源：http://dali.haohaochexian.top/Article/details/gt2fvjagprf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cashguo.top/Article/details/gt2rqekxfji.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gt2wjhvdpsz.html

new Map(Object.entries(obj))
来源：http://dali.snrcjt.cn/Article/details/gt2vxpcmmws.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gt2hzigoreu.html

"7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlsudzgt.html

[U113] JS：正则替换全部
来源：http://dali.fzhhl.top/Article/details/gt2jcopznbp.html

s.replaceAll("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2xjgahpeh.html

[U114] JS：JSON 深比较
来源：http://dali.birdmap.top/Article/details/gt2ovtebyif.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yonumen.top/Article/details/gt2renbgyje.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2vqgsctgm.html

crypto.randomUUID()
来源：http://dali.sweek.top/Article/details/gt2tnfdvihh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.redwolf501.top/Article/details/gt2jytuunql.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zycfv.cn/Article/details/gt2iasjzixg.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gt2zizvnmlt.html

npm i -D vitest;  npx vitest
来源：http://dali.shuidangran.top/Article/details/gt2mbgtkkjv.html

[U118] JS：开发服务器
来源：http://dali.cheryme.top/Article/details/gt2ywnymxzn.html

npm i -D vite;  npx vite
来源：http://dali.yuanzhike.top/Article/details/gt2nmidoxsm.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gt2deotegqf.html

npx vite build
来源：http://dali.guowangkeji.top/Article/details/gt2tyqiiesj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.fzhhl.top/Article/details/gt2xohlsiik.html

import.meta.env.VITE_API_URL
来源：http://dali.hysaishi.cn/Article/details/gt2wleezdmu.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2jmpmkbut.html

统计汇总
来源：http://dali.ydzc1.top/Article/details/gt2xuvmykjp.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2mlevnmff.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gt2asfgrmda.html

Python ......... 252
来源：http://dali.yj20258.top/Article/details/gt2hmapvcrr.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gt2tyjenraz.html

JavaScript ..... 252
来源：http://dali.fengsongda.top/Article/details/gt2nfirxweu.html

TypeScript ..... 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2klbeeeld.html

Java ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gt2lrohpexa.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2jugxmpjc.html

Ruby ........... 212
来源：http://dali.yangfankeji.com/Article/details/gt2gmirxsqe.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2ocujoejs.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gt2sxgvyagb.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gt2xoyrarev.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvguvbk.html

Bash ........... 80
来源：http://dali.ydzc1.top/Article/details/gt2cvbxbgbh.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gt2avzzhfav.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gt2xxfgmfyw.html

Lua ............ 10
来源：http://dali.hfpthk.cn/Article/details/gt2cvdfkiqz.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gt2plvczinl.html

Scala .......... 10
来源：http://dali.zhixingplan.top/Article/details/gt2gqyocgbs.html

------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gt2pcrkummv.html

合计 ........... 2106 条
来源：http://dali.fzhhl.top/Article/details/gt2oqrotaey.html

按章节统计：
来源：http://dali.meibo888.top/Article/details/gt2wkkkpqry.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.mhx1999.top/Article/details/gt2bvwlrnks.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gt2ebvdlwgq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2wfxnudkv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.feifeiyinyue.top/Article/details/gt2zetsytqi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sxryk.cn/Article/details/gt2elhygzhz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.aizwys.cn/Article/details/gt2ybfnlwco.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gt2rmhdncir.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gt2mhrspccr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfrzmuty.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gt2cccsodrm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2cpcgufvo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gt2cgavbcah.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gt2mbpscfzr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yanxiufei.cn/Article/details/gt2zxewqjqi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xuanzx.com/Article/details/gt2vcggcmqi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2ahniahme.html

Q SQL 专题                              90
来源：http://dali.hysaishi.cn/Article/details/gt2axsrwtef.html

R Bash 专题                             80
来源：http://dali.hfpthk.cn/Article/details/gt2pkagelxf.html

S C / C++ 专题                          60
来源：http://dali.nanxinkj.top/Article/details/gt2tligdbcr.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gt2xytxfyrl.html

U 高频实用片段                         120
来源：http://dali.yj202588.top/Article/details/gt2xyhtozoq.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2pwoogfxm.html

合计                                  2106 条
来源：http://dali.haohaochexian.top/Article/details/gt2wrwklcjr.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gt2bdisnmht.html

使用提醒
来源：http://dali.vqdsnc.cn/Article/details/gt2cycgsqfp.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gt2mqocqaye.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.fzhhl.top/Article/details/gt2kpbhqyoq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.havefunace.top/Article/details/gt2ocxszqme.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.c1oappe.top/Article/details/gt2ooblaoed.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tianlin.xyz/Article/details/gt2coxgdpwt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pycfn.com/Article/details/gt2ahrqnvzj.html

—— 文件结束 ——
来源：http://dali.ehwqpu.com/Article/details/gt2znredtrr.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2mhcmhndn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.kuanghao11.cn/Article/details/gt2kjrgwaez.html

Common Programming Examples Cheat Book
来源：http://dali.gogol.net.cn/Article/details/gt2oeymbbcg.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yakwdjgo.html

【收录内容】
来源：http://dali.yongpay.top/Article/details/gt2pxrkjuyy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.svipenyu.cn/Article/details/gt2xulpalcz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jqgufenzy.top/Article/details/gt2usuylkqd.html

SQL · Bash · C · C++
来源：http://dali.daxiang520.top/Article/details/gt2ydzpfupw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.mhx1999.top/Article/details/gt2wukbmpoz.html

【使用说明】
来源：http://dali.jiagoushi.top/Article/details/gt2bdyrxlkp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shangyingyoupin.top/Article/details/gt2wgrllown.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xinyue.icu/Article/details/gt2jxmvscpi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gt2vxshqzub.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.iojbl.cn/Article/details/gt2cylfflei.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.guowangkeji.top/Article/details/gt2mrhubbym.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gt2dhigqaym.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghijqjzj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gt2yiraeriz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.birdmap.top/Article/details/gt2kldxsdna.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.smart0.xyz/Article/details/gt2tqixroar.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gotoacloud.top/Article/details/gt2krwyzphw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.chenlongwang.top/Article/details/gt2hdixzsoz.html

【文件统计】
来源：http://dali.jlsjyb.cn/Article/details/gt2rmsvxrgx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.iojbl.cn/Article/details/gt2qcaraunz.html

--------------------------------------------------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2vekuduwu.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gt2frolyybl.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2fjtobtch.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yuanzhike.top/Article/details/gt2wedtwmto.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gt2dbwpnduo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.meibo888.top/Article/details/gt2bukuhhsk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tian-w.cn/Article/details/gt2dukxvuem.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.svipenyu.cn/Article/details/gt2ujvlsiuy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ciwbnrlo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2feyhpben.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.snrcjt.cn/Article/details/gt2ljpoeysz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2ghwgspsn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2fauxczei.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2tufnejrt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hfpthk.cn/Article/details/gt2czchyzog.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gt2lfmwtmrd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2raugpmff.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.dashuyun.cn/Article/details/gt2tabddjoc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2hvihzzww.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ppjwa.cn/Article/details/gt2pfwjxgmj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.cashguo.top/Article/details/gt2vkvpmllu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2kjfwtkrg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gt2yfbfsevd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gt2lsxnpxnu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2abuoyjso.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gt2ujnruffu.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ljsvqwkn.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gt2abbftiyk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfxysqb.html

PHP:  echo "Hello, World!";
来源：http://dali.316326.xyz/Article/details/gt2huvfiltr.html

JS:   console.log("Hello, World!");
来源：http://dali.tian-w.cn/Article/details/gt2prcfuwba.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shuidangran.top/Article/details/gt2fqkqypfy.html

Java: System.out.println("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gt2gkpduqhq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ydzc1.top/Article/details/gt2lnplwrxy.html

Ruby: puts "Hello, World!"
来源：http://dali.hysaishi.cn/Article/details/gt2zpqfaexv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gt2ttxdkhjn.html

[A02] 变量声明与赋值
来源：http://dali.cashguo.top/Article/details/gt2ubslmahf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xuanzx.com/Article/details/gt2chchomwr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ydzc1.top/Article/details/gt2fdhrbwqw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.nanxinkj.top/Article/details/gt2qtqwopsp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.hammf.cn/Article/details/gt2qaglytfv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2uqkhogxo.html

Go:   name := "Alex"; age := 20
来源：http://dali.yanxiufei.cn/Article/details/gt2rtiyrzfd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zycfv.cn/Article/details/gt2uoodfaoy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2ncmksdea.html

[A03] 常量定义
来源：http://dali.nanxinkj.top/Article/details/gt2ipkrypwj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.snrcjt.cn/Article/details/gt2cvxitgdy.html

PHP:  const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gt2inatbbnc.html

JS:   const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gt2umdbatts.html

TS:   const PI: number = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gt2usfesdsa.html

Java: static final double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2dtasuzus.html

Go:   const PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gt2aorzriyx.html

Ruby: PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gt2drjikpih.html

C#:   const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gt2mkeanmwg.html

[A04] 判断变量类型
来源：http://dali.guowangkeji.top/Article/details/gt2iqgdmxfb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cqqwz.cn/Article/details/gt2mjrpplap.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.quarkkingdee.top/Article/details/gt2cflyowop.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.pycfn.com/Article/details/gt2aljhinjr.html

TS:   typeof x; x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gt2cumxskrl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zdqjudy.top/Article/details/gt2ntfrswoc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gt2lcgbllrk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.smart0.xyz/Article/details/gt2qtkswekr.html

C#:   x.GetType().Name; x is int
来源：http://dali.jiagoushi.top/Article/details/gt2wmwjrvdz.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gt2gbtohhlf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qqykljhs.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2ejwukqpg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gt2fnkznitk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gt2iamqcpdt.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2txzzrucx.html

Go:   7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gt2nkzqyjkv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gt2wppzdxgk.html

C#:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gt2kdzxynqc.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gt2dtvmzamr.html

Py:   int("42"); float("3.14")
来源：http://dali.wangdashe.top/Article/details/gt2hmjmefoa.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jqgufenzy.top/Article/details/gt2pvqbsbsm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ybcxt.top/Article/details/gt2fbsgznce.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gt2ubtaifku.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tianlin.xyz/Article/details/gt2fychvbpm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.wangdashe.top/Article/details/gt2pxjyqnpv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenzaomai.com/Article/details/gt2isycfrgz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnxfhcly.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gt2hukijbzq.html

Py:   str(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2goahzdwk.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pzgxnozp.html

JS:   String(42); (42).toString()
来源：http://dali.daxiang520.top/Article/details/gt2ndcldczp.html

TS:   String(42)
来源：http://dali.yangfankeji.com/Article/details/gt2awqgrulg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.c1oappe.top/Article/details/gt2fqyskzik.html

Go:   strconv.Itoa(42)
来源：http://dali.shzxlz.cn/Article/details/gt2mxmoldyk.html

Ruby: 42.to_s
来源：http://dali.ehwqpu.com/Article/details/gt2kksgtzwt.html

C#:   42.ToString()
来源：http://dali.dashuyun.cn/Article/details/gt2zlqlfeoi.html

[A08] 取整与四舍五入
来源：http://dali.xinyue.icu/Article/details/gt2cqkpmpvl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gt2juqphdsp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhongyouzk.top/Article/details/gt2kvdyqxas.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yangfankeji.com/Article/details/gt2gtpcgvzf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2akxgkddx.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gt2awypnwaz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gt2qmojurbv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.daxiang520.top/Article/details/gt2bexnzwkw.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2nsoonpkz.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gt2subqimow.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuxming.cn/Article/details/gt2ugwlybke.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aklqvbfs.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sweek.top/Article/details/gt2ojvarqer.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2dfwsxdir.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2zqmplikd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.feifeiyinyue.top/Article/details/gt2ifwxiqsr.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.daria6918.cn/Article/details/gt2xwpgoeuh.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2zofnccch.html

[A10] 生成随机数
来源：http://dali.0kj1m.cn/Article/details/gt2lzyyotab.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fengsongda.top/Article/details/gt2sxfiktgu.html

PHP:  random_int(1, 100);
来源：http://dali.tanke756.top/Article/details/gt2ikoaeitg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yanxiufei.cn/Article/details/gt2berhgjgz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cashguo.top/Article/details/gt2ellejtfj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2namaljcv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yueranfly.top/Article/details/gt2lvhkfemd.html

Ruby: rand(1..100)
来源：http://dali.yj20258.top/Article/details/gt2tinipcsv.html

C#:   new Random().Next(1, 101)
来源：http://dali.shzxlz.cn/Article/details/gt2uuuwgljb.html

[A11] 条件表达式（三元）
来源：http://dali.cucudq.cn/Article/details/gt2mqcmytta.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guannengcc.top/Article/details/gt2uutcqajt.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gt2ajsjjttc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gt2ejhmdxll.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ppjwa.cn/Article/details/gt2alktxzia.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frjawgti.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.nwbrower.top/Article/details/gt2ydijbkmf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2umzwecqv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnubiwjk.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2gewjeqwg.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ppjwa.cn/Article/details/gt2xevbrjkp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sweek.top/Article/details/gt2rkkaxyob.html

JS:   `Hello, ${name}!`
来源：http://dali.hnqzz.top/Article/details/gt2croomnza.html

TS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gt2rgbepvft.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xziqi.cn/Article/details/gt2nvwkfovj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj20258.top/Article/details/gt2yjoukidh.html

Ruby: "Hello, #{name}!"
来源：http://dali.shuidangran.top/Article/details/gt2hhemlscl.html

C#:   $"Hello, {name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gt2cuytsspv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sweek.top/Article/details/gt2deonhvsm.html

Py:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2xabdsupg.html

PHP:  "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gt2wfqfpcgu.html

JS:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gt2hlcotyus.html

TS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2bcwvhylz.html

Java: "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2enopdmrz.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2azvmmeqv.html

Ruby: "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gt2jocbpfuu.html

C#:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2bougytav.html

[A14] 注释写法
来源：http://dali.wangshuangyany.cn/Article/details/gt2ghgiobwh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sxryk.cn/Article/details/gt2gehfifio.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2qjefqvox.html

JS:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2chnfifdu.html

TS:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gt2zaqmrlnm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.haohaochexian.top/Article/details/gt2dhjfcoom.html

Go:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gt2xpaenddl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hammf.cn/Article/details/gt2tkdqcrlb.html

C#:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gt2gpaerkdh.html

[A15] 空值判断与默认值
来源：http://dali.pengpengdd.cyou/Article/details/gt2xzgjdwtl.html

Py:   value = data or "默认值"
来源：http://dali.aibaodan.cn/Article/details/gt2ffnjjgxh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gt2dijrddrb.html

JS:   const value = data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gt2jbvvetip.html

TS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gt2mihkkgpc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ehwqpu.com/Article/details/gt2otvwgoss.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258888.top/Article/details/gt2mokjlowz.html

Ruby: value = data || "默认值"
来源：http://dali.daxiang520.top/Article/details/gt2wwdqyqhh.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhoulong.xyz/Article/details/gt2xddmdngb.html

[A16] 真假值判断规则
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfejnrbk.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhixingplan.top/Article/details/gt2ewjrrurl.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.daria6918.cn/Article/details/gt2gmqpmqvw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnqzz.top/Article/details/gt2ktmkrlhh.html

TS:   if (!x) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ftcsqfgx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cucudq.cn/Article/details/gt2wksmyjxt.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gt2vskpjezr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cheryme.top/Article/details/gt2mrtoqnjp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ryoezegh.html

[A17] 位运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ebskmanj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbeiqazf.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhengqikj.top/Article/details/gt2bhxmsryg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gt2kgrjtwag.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gt2oplgfqtt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2spniqpjf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2fmdbrzbl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gt2atifvdss.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2jsrvrhub.html


<!-- 参考信息 -->