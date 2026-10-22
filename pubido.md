代发 wailian999

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gt2cxmzgixe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gt2bzwfhjtd.html

[U104] JS：防抖
来源：http://dali.vqdsnc.cn/Article/details/gt2oovsbgry.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2nqdrhsxg.html

[U105] JS：节流
来源：http://dali.fzhhl.top/Article/details/gt2qbgstcej.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gt2xkrsfiis.html

[U106] JS：日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2nrylwjks.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.tanke756.top/Article/details/gt2sqfsdypa.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2tvoproaw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gt2fnxicmxr.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gt2lkxeponr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hysaishi.cn/Article/details/gt2ncolnukb.html

[U109] JS：数组分组
来源：http://dali.nanxinkj.top/Article/details/gt2ozzgumfj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2awkndlrq.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2rjfvvwrc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fzhhl.top/Article/details/gt2yjhtrhmd.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dgovhmdp.html

new Map(Object.entries(obj))
来源：http://dali.yangfankeji.com/Article/details/gt2abnlfjpv.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gt2jcjqzlop.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gt2mmafpsck.html

[U113] JS：正则替换全部
来源：http://dali.ybcxt.top/Article/details/gt2cfjglyvt.html

s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2tqevwbhr.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gt2leqvqagi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2xmnxlqng.html

[U115] JS：生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2szkjjcxm.html

crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2vxojvugy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gotoacloud.top/Article/details/gt2wuapxjvs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfqwenuz.html

[U117] JS：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxbhpedg.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gt2cxphkvcy.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gt2kswyrzar.html

npm i -D vite;  npx vite
来源：http://dali.hnqzz.top/Article/details/gt2zprzodzc.html

[U119] JS：生产构建
来源：http://dali.birdmap.top/Article/details/gt2dfnzhnoo.html

npx vite build
来源：http://dali.ivvv.top/Article/details/gt2wlgtwlmy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenlongwang.top/Article/details/gt2lvhegyfl.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gt2ouvqtffq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcfcubgx.html

统计汇总
来源：http://dali.yuxming.cn/Article/details/gt2cpzoegfj.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymdetglt.html

按语言统计（条）：
来源：http://dali.xylfe.cn/Article/details/gt2unyawpua.html

Python ......... 252
来源：http://dali.jqgfzy.top/Article/details/gt2jhkbnqtp.html

PHP ............ 252
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmhwdlfm.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gt2gzungavp.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gt2fsiwrwgo.html

Java ........... 212
来源：http://dali.sufxvd.cn/Article/details/gt2eucaipyw.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gt2owsmamon.html

Ruby ........... 212
来源：http://dali.yonumen.top/Article/details/gt2dnfzestt.html

C# ............. 212
来源：http://dali.zycfv.cn/Article/details/gt2unyavogr.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gt2xbytbwlv.html

C++ ............ 30
来源：http://dali.guannengcc.top/Article/details/gt2hdbznkuu.html

SQL ............ 90
来源：http://dali.aizwys.cn/Article/details/gt2ydmgznlf.html

Bash ........... 80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgxirsbi.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gt2hbgpkerm.html

Swift .......... 15
来源：http://dali.zhoulong.xyz/Article/details/gt2vpiyztiq.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gt2jztfnchk.html

Perl ........... 10
来源：http://dali.zhoulong.xyz/Article/details/gt2czfzmcfs.html

Scala .......... 10
来源：http://dali.hnqzz.top/Article/details/gt2nsagmwsi.html

------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gt2iarmmgyl.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2uwudmbrx.html

按章节统计：
来源：http://dali.mhx1999.top/Article/details/gt2udopvjxg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hpinknam.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gt2btypeffb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gt2vectrgby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gt2mvvuwvur.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhengqikj.top/Article/details/gt2fddhhfbo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gt2cpzsmnde.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gt2ufwpkrdw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcsvirch.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gt2mhsoyfjy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gt2khzyzctn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gt2bebrsned.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2slxbribr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gt2rvpdmtmf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gt2rctzlmzd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdvvnthm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2bhgcydpf.html

Q SQL 专题                              90
来源：http://dali.jianghu66.top/Article/details/gt2kvqbyftv.html

R Bash 专题                             80
来源：http://dali.wangdashe.top/Article/details/gt2yrjxuzkj.html

S C / C++ 专题                          60
来源：http://dali.yj20258.top/Article/details/gt2vzobkedj.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gt2ydyajknx.html

U 高频实用片段                         120
来源：http://dali.kuanghao11.cn/Article/details/gt2ksjexthu.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2iuezgyed.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gt2otpldjla.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlhjajax.html

使用提醒
来源：http://dali.aizwys.cn/Article/details/gt2uisufqzk.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2hpvtudoz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cdnleiting.top/Article/details/gt2gznykdwb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gt2ripyqokh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dpqmptvr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gt2iovezzwc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinqigfzy.top/Article/details/gt2pzkqqgsm.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gt2alfjssob.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2fmiphmcl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xylfe.cn/Article/details/gt2famcfcea.html

Common Programming Examples Cheat Book
来源：http://dali.wangshuangyany.cn/Article/details/gt2uesrnkiq.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ggfodppz.html

【收录内容】
来源：http://dali.ppjwa.cn/Article/details/gt2ccghrlhv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.c1oappe.top/Article/details/gt2ewzvrkzt.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yongpay.top/Article/details/gt2xsqjbnef.html

SQL · Bash · C · C++
来源：http://dali.vqdsnc.cn/Article/details/gt2mdvlfbtp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhixingplan.top/Article/details/gt2ivdqtlbp.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gt2kpaoenbh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufvnvuad.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.snrcjt.cn/Article/details/gt2eswawbcg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gzhubu.top/Article/details/gt2qhxcluzo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.vqdsnc.cn/Article/details/gt2dfyyltrj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.mhx1999.top/Article/details/gt2vkekfthq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkvwmslv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yueranfly.top/Article/details/gt2xxzguggh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdshynrl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gt2ljvzsweq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.cqqwz.cn/Article/details/gt2dgrcsriv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.svipenyu.cn/Article/details/gt2orikejox.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jlsjyb.cn/Article/details/gt2dkmlswjc.html

【文件统计】
来源：http://dali.wangdashe.top/Article/details/gt2jqlrqkpy.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ivvv.top/Article/details/gt2otsrbtmd.html

--------------------------------------------------------------------------------
来源：http://dali.hywenlv.cn/Article/details/gt2stkaxzch.html

目  录
来源：http://dali.cheryme.top/Article/details/gt2emcktugy.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2hijrhunj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2zeqyoqfg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2gsuwueif.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gt2tsmmhgst.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gt2kfzjyojp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gt2xsshfuhb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gt2eikhkums.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxowzemy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gocqwlia.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2smtlehrt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujrtwql.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gt2voydqnus.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hywenlv.cn/Article/details/gt2muivddci.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gt2bwejhqdu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.chenzaomai.com/Article/details/gt2cotfqnnm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2olepralg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2zfisjcot.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkemhyd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.guannengcc.top/Article/details/gt2ljzfaper.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.andypj.xyz/Article/details/gt2elocgyow.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gt2xbnzfpuz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gt2sdmvsilu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2grxlgvab.html

A. 基础语法与类型
来源：http://dali.shuidangran.top/Article/details/gt2guwwwyaz.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2cdbpknjf.html

[A01] Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2cxnlpgjj.html

Py:   print("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gt2vnryxdxv.html

PHP:  echo "Hello, World!";
来源：http://dali.xinyue.icu/Article/details/gt2kjwhdoby.html

JS:   console.log("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gt2agitlqaa.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.316326.xyz/Article/details/gt2eltwumvq.html

Java: System.out.println("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gt2lvltuzek.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gt2pnpklehh.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2otkgysdg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hammf.cn/Article/details/gt2riolrcll.html

[A02] 变量声明与赋值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuspgsiw.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gt2farsisbk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.birdmap.top/Article/details/gt2oqihqauu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bifinwdw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhoulong.xyz/Article/details/gt2dvxlvrfr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gt2bwepruhx.html

Go:   name := "Alex"; age := 20
来源：http://dali.yj20258.top/Article/details/gt2deuwxbnj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkxiqoum.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xylfe.cn/Article/details/gt2xhgezrij.html

[A03] 常量定义
来源：http://dali.tian-w.cn/Article/details/gt2dnemkywo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yuanzhike.top/Article/details/gt2zugizgrj.html

PHP:  const PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2qdnajewa.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2fzgstjbh.html

TS:   const PI: number = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rciqhimm.html

Java: static final double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzgtpfim.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gt2ffilxpue.html

Ruby: PI = 3.14159
来源：http://dali.jyoumei.cn/Article/details/gt2nqtumklg.html

C#:   const double PI = 3.14159;
来源：http://dali.tian-w.cn/Article/details/gt2qebvbntl.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gt2mfbnozsu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aueqkoyi.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.xuanzx.com/Article/details/gt2ulhpognh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zycfv.cn/Article/details/gt2qmarufwa.html

TS:   typeof x; x instanceof Date
来源：http://dali.chenjidiqi.icu/Article/details/gt2fumiktak.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jqgufenzy.top/Article/details/gt2cxvcpfwp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gogol.net.cn/Article/details/gt2unbbfamc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mjgvfamx.html

C#:   x.GetType().Name; x is int
来源：http://dali.c1oappe.top/Article/details/gt2uvpqnwrv.html

[A05] 整数除法与取模
来源：http://dali.birdmap.top/Article/details/gt2hskjklhb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gt2iiwafsif.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2vaqfvyvi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gt2hrjfqcwz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ivvv.top/Article/details/gt2qfwgjcsd.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gt2pnxinwip.html

Go:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gt2wnuxoxwz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gt2tyfuemlo.html

C#:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2vrojowyz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hdafwdww.html

Py:   int("42"); float("3.14")
来源：http://dali.tanke756.top/Article/details/gt2bowntqmr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hywenlv.cn/Article/details/gt2dkysxgip.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.guannengcc.top/Article/details/gt2zoskosxy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2evpeovlb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pbluqidq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.dianchejie.cn/Article/details/gt2kvgjejtd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sysykeji.top/Article/details/gt2madaullx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gt2xacwtaxi.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2gxegieuw.html

Py:   str(42)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhmqheba.html

PHP:  (string) 42; strval(42)
来源：http://dali.gzhubu.top/Article/details/gt2pvsstgns.html

JS:   String(42); (42).toString()
来源：http://dali.tianlin.xyz/Article/details/gt2xumllxau.html

TS:   String(42)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zjwsvkte.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yangfankeji.com/Article/details/gt2hkgvtohi.html

Go:   strconv.Itoa(42)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ostygvbh.html

Ruby: 42.to_s
来源：http://dali.xinyue.icu/Article/details/gt2rguthnpw.html

C#:   42.ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jaragula.html

[A08] 取整与四舍五入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swjjqbbl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gt2mmsjmkpt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.havefunace.top/Article/details/gt2pmnyezav.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gt2ukcybdyk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jqgfzy.top/Article/details/gt2czyocgxs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.quarkkingdee.top/Article/details/gt2gbjabtwq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2enimoabk.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cdnleiting.top/Article/details/gt2uoizhazf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gt2gmacnoqi.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gt2fevvtcyb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltyvzaim.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2vplbmsxd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gt2zkdcfrxs.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwurhobz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.andypj.xyz/Article/details/gt2gxzgzotr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.hysaishi.cn/Article/details/gt2kcjotoxo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangdashe.top/Article/details/gt2jycbinsn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yswobrdx.html

[A10] 生成随机数
来源：http://dali.yueranfly.top/Article/details/gt2lpnjeiyy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.tian-w.cn/Article/details/gt2cdykzgvi.html

PHP:  random_int(1, 100);
来源：http://dali.mhx1999.top/Article/details/gt2qeihmxka.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gt2hhxraajm.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gt2mcgrhfkp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2muxmpcti.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.guowangkeji.top/Article/details/gt2lonpitjp.html

Ruby: rand(1..100)
来源：http://dali.havefunace.top/Article/details/gt2mfbyjpab.html

C#:   new Random().Next(1, 101)
来源：http://dali.yvedp.cn/Article/details/gt2tpuuslmu.html

[A11] 条件表达式（三元）
来源：http://dali.ybcxt.top/Article/details/gt2gloszsds.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2tkrbwhin.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gt2iuhiyexn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvwdkpa.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gt2huaxsopt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gt2niudnqwh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ydzc1.top/Article/details/gt2qgocyuin.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gt2xcyxszru.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gt2eadbdjil.html

[A12] 字符串插值 / 格式化
来源：http://dali.tian-w.cn/Article/details/gt2srclegvs.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ehwqpu.com/Article/details/gt2adwbaimt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gt2uqzulctn.html

JS:   `Hello, ${name}!`
来源：http://dali.0kj1m.cn/Article/details/gt2ygdpqayy.html

TS:   `Hello, ${name}!`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhghoqme.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2wbetuthe.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddnqkutl.html

Ruby: "Hello, #{name}!"
来源：http://dali.gotoacloud.top/Article/details/gt2drtwcmgh.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxinkj.top/Article/details/gt2rjanfaji.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hongshengwenyu.top/Article/details/gt2bmomwoil.html

Py:   "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gt2znljflrl.html

PHP:  "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2runtmlgw.html

JS:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2renvzkia.html

TS:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2welzgmsj.html

Java: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2zsfqjrnw.html

Go:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llupljii.html

Ruby: "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gt2vdanqkxj.html

C#:   "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gt2wqdlrwmm.html

[A14] 注释写法
来源：http://dali.yongpay.top/Article/details/gt2qretcbpo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jinqigufen.top/Article/details/gt2ywaunyjb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gt2jfozisse.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gt2ajnbgdre.html

TS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gt2ogvrucyq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.snrcjt.cn/Article/details/gt2qlwbtvja.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gt2lorqsksq.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqwzpjsr.html

C#:   // 单行；/* 多行 */
来源：http://dali.dianchejie.cn/Article/details/gt2ryaiaxrg.html

[A15] 空值判断与默认值
来源：http://dali.zdqjudy.top/Article/details/gt2nnwwqezf.html

Py:   value = data or "默认值"
来源：http://dali.guannengcc.top/Article/details/gt2obquvndp.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ynhypqvo.html

JS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekizgzbg.html

TS:   const value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gt2zlxwsucy.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhferxbw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgfzy.top/Article/details/gt2vstircdn.html

Ruby: value = data || "默认值"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mumxhbzu.html

C#:   var value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2xycdfgks.html

[A16] 真假值判断规则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbphgtcm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ybcxt.top/Article/details/gt2nsuvqmwf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gt2tnwebuns.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ppjwa.cn/Article/details/gt2afvhxiiv.html

TS:   if (!x) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2delzlewu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2eelebekz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.birdmap.top/Article/details/gt2gtcvvwlr.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.aibaodan.cn/Article/details/gt2iikuudxu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hammf.cn/Article/details/gt2jprgyvfc.html

[A17] 位运算
来源：http://dali.pengpengdd.cyou/Article/details/gt2phzgofjt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2fqpfegro.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2hverygmw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzrpcmxl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2txreglax.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2aujzxkdc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gt2jvrhnhut.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gt2pmwrtare.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gt2ndycpvxz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gt2vkknhbem.html

Py:   ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gt2mydydmzq.html

PHP:  ord("A"); chr(65)
来源：http://dali.shuidangran.top/Article/details/gt2jhblkqnz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gt2gjkpfcgf.html


<!-- 参考信息 -->