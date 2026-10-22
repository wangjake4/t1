代发 wailian999

[U99] JS：事件监听
来源：http://dali.snrcjt.cn/Article/details/gt2ucbxhdbj.html

el.addEventListener("click", e => {})
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnavjfpb.html

[U100] JS：DOM 查询
来源：http://dali.daxiang520.top/Article/details/gt2mbkhxnnf.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gt2lcytbkeg.html

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gt2kujnspyl.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2zdfqqcws.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gt2fabyimgj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gt2bqugraav.html

[U103] JS：定时器
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgigdbkn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gzhubu.top/Article/details/gt2gftykfmo.html

[U104] JS：防抖
来源：http://dali.yongpay.top/Article/details/gt2uaokfdtf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2gadiorkc.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gt2udnckujn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2xgltxsrl.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxvkhazi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnqzz.top/Article/details/gt2dsmaisgp.html

[U107] JS：数字千分位
来源：http://dali.svipenyu.cn/Article/details/gt2mmfzmqfc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2pavmeryu.html

[U108] JS：随机整数
来源：http://dali.xziqi.cn/Article/details/gt2xqwcjald.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gt2unmryztg.html

[U109] JS：数组分组
来源：http://dali.nwbrower.top/Article/details/gt2qagnrknp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gt2lemgggap.html

[U110] JS：数组分块
来源：http://dali.yangfankeji.com/Article/details/gt2grbwqpnb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxuanxn.top/Article/details/gt2uqjgmhqk.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gt2mynpxhvh.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gt2wruymbdo.html

[U112] JS：字符串补位
来源：http://dali.wangdashe.top/Article/details/gt2nnixhkkc.html

"7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gt2zwadvgkv.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gt2jfxykdgf.html

s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gt2gefrgunx.html

[U114] JS：JSON 深比较
来源：http://dali.quarkkingdee.top/Article/details/gt2vizznuch.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gt2nkniuwna.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahjkycbz.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2ebcbyhlq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jianghu66.top/Article/details/gt2xobhrufh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2bkdecqyv.html

[U117] JS：单元测试
来源：http://dali.guowangkeji.top/Article/details/gt2klmslndv.html

npm i -D vitest;  npx vitest
来源：http://dali.svipenyu.cn/Article/details/gt2califxjx.html

[U118] JS：开发服务器
来源：http://dali.yj20258888.top/Article/details/gt2zsuhsdxt.html

npm i -D vite;  npx vite
来源：http://dali.cashguo.top/Article/details/gt2uueddkry.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sljkzsyi.html

npx vite build
来源：http://dali.cqqwz.cn/Article/details/gt2fcbbpeyl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gt2dfhdjzek.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gt2rfxutzxt.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2zssyoycg.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gt2xjaszwad.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2hsuwaqdx.html

按语言统计（条）：
来源：http://dali.316326.xyz/Article/details/gt2rgbgujyb.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlmlqjdn.html

PHP ............ 252
来源：http://dali.feifeiyinyue.top/Article/details/gt2oknxebvl.html

JavaScript ..... 252
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hyectmhf.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gt2dafvtzbr.html

Java ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gt2hzwpyqxs.html

Go ............. 212
来源：http://dali.jinqigfzy.top/Article/details/gt2hvmvazrz.html

Ruby ........... 212
来源：http://dali.tanke756.top/Article/details/gt2zryomhkw.html

C# ............. 212
来源：http://dali.shzxlz.cn/Article/details/gt2uuittgtb.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gt2brtfvcjv.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndekqtae.html

SQL ............ 90
来源：http://dali.c1oappe.top/Article/details/gt2oaxtqtly.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gt2pitkhhlf.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gt2tujugfbb.html

Swift .......... 15
来源：http://dali.yangfankeji.com/Article/details/gt2aptbwmey.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gt2fudpzfkt.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gt2xpfgpiih.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gt2qphbudbx.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gt2tavycfnd.html

合计 ........... 2106 条
来源：http://dali.jiagoushi.top/Article/details/gt2cdwfgfte.html

按章节统计：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erqqnoqf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.redwolf501.top/Article/details/gt2fjkgwzvv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daxiang520.top/Article/details/gt2dgfkadzo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nomkwfhr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yongpay.top/Article/details/gt2tmbjcjeb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhoulong.xyz/Article/details/gt2swhxetkt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gt2zpzebjps.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gt2ljptjigy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gt2guwqsglu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gt2mxqtalns.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gt2jntikiqt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ywvnvixf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvtlvhrl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gt2xqedtcgj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.quarkkingdee.top/Article/details/gt2iktnrpmt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gt2onupjbth.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhoulong.xyz/Article/details/gt2yaxolqyx.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gt2jzwzayje.html

R Bash 专题                             80
来源：http://dali.yangfankeji.com/Article/details/gt2chesuwlt.html

S C / C++ 专题                          60
来源：http://dali.jlsjyb.cn/Article/details/gt2zezrdkhc.html

T 其他语言补充                          60
来源：http://dali.yangfankeji.com/Article/details/gt2jdgrbaps.html

U 高频实用片段                         120
来源：http://dali.0kj1m.cn/Article/details/gt2qfhiabax.html

------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gt2tdcaamqs.html

合计                                  2106 条
来源：http://dali.nwbrower.top/Article/details/gt2hvgtnadu.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2gyfhmotr.html

使用提醒
来源：http://dali.svipenyu.cn/Article/details/gt2yyllqcxz.html

--------------------------------------------------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gt2bhtifwec.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.quarkkingdee.top/Article/details/gt2vhuacxew.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gotoacloud.top/Article/details/gt2clsahqoh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shzxlz.cn/Article/details/gt2ulhxcnml.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guowangkeji.top/Article/details/gt2gaxxvjay.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jqgufenzy.top/Article/details/gt2vigqxraq.html

—— 文件结束 ——
来源：http://dali.hnxiangtu.top/Article/details/gt2sehwnbkf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfrtazzh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gt2seebjbnt.html

Common Programming Examples Cheat Book
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdrgtvca.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2scfqmagc.html

【收录内容】
来源：http://dali.wangdashe.top/Article/details/gt2nbrdlnwp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jyoumei.cn/Article/details/gt2lnlzifgy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hongshengwenyu.top/Article/details/gt2viebbfak.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gt2dxykgqxw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yvedp.cn/Article/details/gt2zgmgoicw.html

【使用说明】
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yffhagbv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.tianlin.xyz/Article/details/gt2lmiywcmu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zycfv.cn/Article/details/gt2pnvnlret.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.sufxvd.cn/Article/details/gt2jgdwsqjp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqtlvwxf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.vqdsnc.cn/Article/details/gt2fcqayvlw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hysaishi.cn/Article/details/gt2lbvoxxlh.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gt2oldhtroz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gt2egummxwq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gawepybb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ybcxt.top/Article/details/gt2huyntfyq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tianlin.xyz/Article/details/gt2lwaellrg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhixingplan.top/Article/details/gt2lnsfpjnx.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gt2gvqftbgp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jiagoushi.top/Article/details/gt2selponva.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gt2hdgagqsg.html

目  录
来源：http://dali.zhengqikj.top/Article/details/gt2boktbvtx.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gt2csnkfcyx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2ojhvfmra.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bijukrsu.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snwntasa.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gt2hzgeoyjk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.smart0.xyz/Article/details/gt2sqwqkqjv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.mhx1999.top/Article/details/gt2ywptxjtc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.c1oappe.top/Article/details/gt2sgdqclde.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.haohaochexian.top/Article/details/gt2rfxlxanc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxinkj.top/Article/details/gt2qznfwnsl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.hywenlv.cn/Article/details/gt2uyageaxz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gt2bzldoqyb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2utslczxk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gt2hlrqxvzm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2wydfnfdx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yueranfly.top/Article/details/gt2ioeujbmi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2btdoubed.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ncjqplmv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2xtrrbqle.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzpmvpno.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gt2hvdrolvj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gt2wuhlxbeg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qdztpsrz.html

A. 基础语法与类型
来源：http://dali.yuxming.cn/Article/details/gt2nmbriqmj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2ygmqmcpo.html

[A01] Hello World
来源：http://dali.havefunace.top/Article/details/gt2puadpcon.html

Py:   print("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2ssvcgjze.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vwmccltb.html

JS:   console.log("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gt2gnhhgvll.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.havefunace.top/Article/details/gt2wboiahwd.html

Java: System.out.println("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gt2pzhvztkg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2zdatwaas.html

Ruby: puts "Hello, World!"
来源：http://dali.birdmap.top/Article/details/gt2xobxynlm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gt2jglpjkhc.html

[A02] 变量声明与赋值
来源：http://dali.zhengqikj.top/Article/details/gt2amqcneae.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yonumen.top/Article/details/gt2voeyiitr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hysaishi.cn/Article/details/gt2dglfcxlm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hywenlv.cn/Article/details/gt2frpffvmi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2imqpsrwz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tianlin.xyz/Article/details/gt2umlpggbl.html

Go:   name := "Alex"; age := 20
来源：http://dali.cashguo.top/Article/details/gt2zamasabl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jqgfzy.top/Article/details/gt2ogdiuovi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2koyczybl.html

[A03] 常量定义
来源：http://dali.gotoacloud.top/Article/details/gt2ijvcwdxu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.birdmap.top/Article/details/gt2wpaxijuh.html

PHP:  const PI = 3.14159;
来源：http://dali.sweek.top/Article/details/gt2invtywtu.html

JS:   const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gt2ezzqlaoz.html

TS:   const PI: number = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2gqqdqrtv.html

Java: static final double PI = 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gt2qaexrzbi.html

Go:   const PI = 3.14159
来源：http://dali.0kj1m.cn/Article/details/gt2tvcpmcca.html

Ruby: PI = 3.14159
来源：http://dali.svipenyu.cn/Article/details/gt2bhcnlrna.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gt2xrbgnqoy.html

[A04] 判断变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sujdwnji.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ehwqpu.com/Article/details/gt2mveqnmgd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sweek.top/Article/details/gt2jwjhmxrw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cheryme.top/Article/details/gt2sprilqqs.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gt2muawrsdv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2osxzaqdw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sweek.top/Article/details/gt2yqfkooaq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gaohongyu789.top/Article/details/gt2hzehybcy.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gt2egequazw.html

[A05] 整数除法与取模
来源：http://dali.guowangkeji.top/Article/details/gt2zziuxdey.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yonumen.top/Article/details/gt2ddrfbgea.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gt2kgebusfo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2rxdvuxas.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yongpay.top/Article/details/gt2ymiaqann.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2himiyuar.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gt2shtpwkpf.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gt2lpstakpd.html

C#:   7 / 2; 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gt2vroekamc.html

[A06] 字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2iodavahu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gt2lbzrhhru.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxinkj.top/Article/details/gt2hlgoghwm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tanke756.top/Article/details/gt2mqevihhl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cashguo.top/Article/details/gt2chjexjem.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.feifeiyinyue.top/Article/details/gt2swvqrlso.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gt2qggvoliw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.haohaochexian.top/Article/details/gt2elprvlgw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yj20258888.top/Article/details/gt2ucvjshsf.html

[A07] 数字转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2pgqjjrjr.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gt2jkifyppy.html

PHP:  (string) 42; strval(42)
来源：http://dali.hammf.cn/Article/details/gt2gqmqhswl.html

JS:   String(42); (42).toString()
来源：http://dali.zdqjudy.top/Article/details/gt2xammskie.html

TS:   String(42)
来源：http://dali.guowangkeji.top/Article/details/gt2srmztmkx.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gt2snahldlb.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yuvxkcjk.html

Ruby: 42.to_s
来源：http://dali.yj20258.top/Article/details/gt2vnzivmdg.html

C#:   42.ToString()
来源：http://dali.hywenlv.cn/Article/details/gt2dkmmhyyl.html

[A08] 取整与四舍五入
来源：http://dali.dianchejie.cn/Article/details/gt2yseopcph.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yokaeuwz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zycfv.cn/Article/details/gt2danphqnf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gt2vzbtmmyw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppiwhyev.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2pkwajlch.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gt2ptlipbeq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jyoumei.cn/Article/details/gt2rhtygwog.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2emrgjrpc.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2fpqwfkxl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gt2cyghemdn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2rrcokdye.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuanzx.com/Article/details/gt2yyfvqclj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gt2mcaojyui.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2qqchalfk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jinqigfzy.top/Article/details/gt2vxxzifsm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zdqjudy.top/Article/details/gt2mglaubqv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2levdxjiv.html

[A10] 生成随机数
来源：http://dali.daxiang520.top/Article/details/gt2uxdnixfc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.birdmap.top/Article/details/gt2eaczywlo.html

PHP:  random_int(1, 100);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pmfqeojj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuxming.cn/Article/details/gt2sfzeucpt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ivvv.top/Article/details/gt2jthxwcev.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2llxfpcvi.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.smart0.xyz/Article/details/gt2tflowzoi.html

Ruby: rand(1..100)
来源：http://dali.wangdashe.top/Article/details/gt2bmpwohsh.html

C#:   new Random().Next(1, 101)
来源：http://dali.cqqwz.cn/Article/details/gt2uhsluhqt.html

[A11] 条件表达式（三元）
来源：http://dali.wangdashe.top/Article/details/gt2xjaszrth.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jlsjyb.cn/Article/details/gt2yogshkww.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vssjuddb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gt2xidteiti.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gt2hzftijiq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2voqabrqz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj20258.top/Article/details/gt2tvxyauiy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gt2uplhcgga.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2frkgwlea.html

[A12] 字符串插值 / 格式化
来源：http://dali.gotoacloud.top/Article/details/gt2yjrptuxy.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daxiang520.top/Article/details/gt2urhnbtwl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbiyxspt.html

JS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gt2aiwyrnit.html

TS:   `Hello, ${name}!`
来源：http://dali.birdmap.top/Article/details/gt2uzfqtawo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptruuzmr.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jqgfzy.top/Article/details/gt2xijkdnma.html

Ruby: "Hello, #{name}!"
来源：http://dali.shuidangran.top/Article/details/gt2hjnzgqxk.html

C#:   $"Hello, {name}!"
来源：http://dali.ivvv.top/Article/details/gt2qxiginwn.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.iojbl.cn/Article/details/gt2divageyp.html

Py:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gt2azswhzuo.html

PHP:  "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gt2mwpfjxwm.html

JS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gt2kcqjwaen.html

TS:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2nyawwybw.html

Java: "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gt2dzjcaiif.html

Go:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gt2botoexkv.html

Ruby: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gt2bqucedpi.html

C#:   "第一行\n第二行"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsjbvesx.html

[A14] 注释写法
来源：http://dali.bjfxy.top/Article/details/gt2vjxwisjh.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ktsgenbs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gt2rzboahzi.html

JS:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2qmcxllpt.html

TS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gt2lolwqyxa.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.quarkkingdee.top/Article/details/gt2ghlesige.html

Go:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gt2rqrgljbt.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nanxinkj.top/Article/details/gt2gfgbgcyf.html

C#:   // 单行；/* 多行 */
来源：http://dali.sweek.top/Article/details/gt2qmjbcugh.html

[A15] 空值判断与默认值
来源：http://dali.316326.xyz/Article/details/gt2fjxbyrpt.html

Py:   value = data or "默认值"
来源：http://dali.redwolf501.top/Article/details/gt2gamhvxxe.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gt2ohiartdo.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2bsddnaux.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gt2ydcguaqk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.andypj.xyz/Article/details/gt2utmvovop.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yangfankeji.com/Article/details/gt2shlcugrh.html

Ruby: value = data || "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gt2pqukydgg.html

C#:   var value = data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gt2lgqzwvrm.html

[A16] 真假值判断规则
来源：http://dali.meibo888.top/Article/details/gt2cnhnfvqr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ivvv.top/Article/details/gt2dnkbtzyu.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jianghu66.top/Article/details/gt2uqafkzws.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zycfv.cn/Article/details/gt2edqjjwjn.html

TS:   if (!x) {}
来源：http://dali.ydzc1.top/Article/details/gt2vkbzepyg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnqzz.top/Article/details/gt2qlxavpcm.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenzaomai.com/Article/details/gt2jvndtubh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hnqzz.top/Article/details/gt2qlxaawwl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2unmfqwmw.html

[A17] 位运算
来源：http://dali.jqgufenzy.top/Article/details/gt2cqpzeshc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gt2gdqquref.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gt2niztkslh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2xoadtxym.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2xswirlou.html


<!-- 参考信息 -->