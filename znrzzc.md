代发 wailian999

[U93] JS：模板字符串
来源：http://dali.cdnleiting.top/Article/details/gt2buhcfqvy.html

`共 ${n} 条`
来源：http://dali.jqgufenzy.top/Article/details/gt2niioruby.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gt2qezdlbts.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2rvglqzth.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gt2nltamkbd.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gt2lwlhcbmo.html

[U96] JS：async/await 与异常
来源：http://dali.jlsjyb.cn/Article/details/gt2nuqckeec.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2idjqmste.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwmjeukq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gt2aotjpukv.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gt2dachhzfu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sufxvd.cn/Article/details/gt2uxtbuzre.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gt2vxsligvx.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2uekphirk.html

[U100] JS：DOM 查询
来源：http://dali.xinyue.icu/Article/details/gt2ppizilbl.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gt2perzqcck.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gt2ustuwewx.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gt2jtzhziwn.html

[U102] JS：本地存储
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohausejx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.andypj.xyz/Article/details/gt2pnuufhat.html

[U103] JS：定时器
来源：http://dali.jqgufenzy.top/Article/details/gt2gwyenxlg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.cdnleiting.top/Article/details/gt2iswfeync.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gt2gprqwskq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2xticplmo.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gt2rjsyavrx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gzhubu.top/Article/details/gt2aesewfqh.html

[U106] JS：日期格式化
来源：http://dali.meibo888.top/Article/details/gt2fgssmdiz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgufenzy.top/Article/details/gt2dileftpl.html

[U107] JS：数字千分位
来源：http://dali.chenlongwang.top/Article/details/gt2kyahlnux.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenlongwang.top/Article/details/gt2juqjmyrt.html

[U108] JS：随机整数
来源：http://dali.c1oappe.top/Article/details/gt2vzmleayj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gt2gocqswrw.html

[U109] JS：数组分组
来源：http://dali.316326.xyz/Article/details/gt2lajzqozz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xinyue.icu/Article/details/gt2vizisyku.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gt2tgwljgwi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.pycfn.com/Article/details/gt2njkopnim.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gt2iphijqul.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gt2saezfrru.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqpqmwe.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2daptdkas.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gt2dxrrhaei.html

s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2ovcknbga.html

[U114] JS：JSON 深比较
来源：http://dali.gaohongyu789.top/Article/details/gt2mcleqsjq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gt2rvzzezlf.html

[U115] JS：生成 UUID
来源：http://dali.sxryk.cn/Article/details/gt2dshbrdou.html

crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2mkddmgcd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gt2hbqtysty.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gt2rxbbefmp.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gt2ogkdicrl.html

npm i -D vitest;  npx vitest
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgjexksq.html

[U118] JS：开发服务器
来源：http://dali.gotoacloud.top/Article/details/gt2lzwccbug.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gt2jwgrdmbe.html

[U119] JS：生产构建
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wcsfvxey.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gt2igpcnzbu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gt2jeuitlcz.html

import.meta.env.VITE_API_URL
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naewwgsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xilgxgdv.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gt2mgtfeule.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jcidrwrn.html

按语言统计（条）：
来源：http://dali.nanxinkj.top/Article/details/gt2zginzrrk.html

Python ......... 252
来源：http://dali.sweek.top/Article/details/gt2epnkejlf.html

PHP ............ 252
来源：http://dali.yuxming.cn/Article/details/gt2gcmnrsqm.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gt2koehwkxs.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swozrrch.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gt2akkphipg.html

Go ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gt2vongvuhc.html

Ruby ........... 212
来源：http://dali.hfpthk.cn/Article/details/gt2njtrwsxf.html

C# ............. 212
来源：http://dali.yj20258.top/Article/details/gt2qloefxti.html

C .............. 30
来源：http://dali.jinqigfzy.top/Article/details/gt2lqgkuvbc.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gt2cxxrpszb.html

SQL ............ 90
来源：http://dali.sweek.top/Article/details/gt2pxhhvatm.html

Bash ........... 80
来源：http://dali.dashuyun.cn/Article/details/gt2weybfpve.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gt2rrxlyfjy.html

Swift .......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gt2ooyddsvv.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gt2vftzpevu.html

Perl ........... 10
来源：http://dali.hysaishi.cn/Article/details/gt2mqzcbvyf.html

Scala .......... 10
来源：http://dali.zhengqikj.top/Article/details/gt2sciqsvnq.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2chmrrszm.html

合计 ........... 2106 条
来源：http://dali.nwbrower.top/Article/details/gt2bwulzkia.html

按章节统计：
来源：http://dali.birdmap.top/Article/details/gt2mkqlvmhs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hnqzz.top/Article/details/gt2pnhxmchx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gt2crprseng.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gt2rzyujswj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gt2otxxhjud.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gt2cpgdhiih.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gogol.net.cn/Article/details/gt2amepvdab.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2felpgogo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gogol.net.cn/Article/details/gt2wcgmdxnq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2hwqbkxep.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fjxabewq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.dianchejie.cn/Article/details/gt2pmqspmfi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqighovz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hammf.cn/Article/details/gt2bmqkucla.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdfzmqhv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nwbrower.top/Article/details/gt2lwnwloil.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gt2mdsmiqbs.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gt2tvevygxw.html

R Bash 专题                             80
来源：http://dali.gotoacloud.top/Article/details/gt2ooobxgba.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gt2gtwknftw.html

T 其他语言补充                          60
来源：http://dali.tian-w.cn/Article/details/gt2ytsqztif.html

U 高频实用片段                         120
来源：http://dali.xuanzx.com/Article/details/gt2nefcafum.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2lzhcokik.html

合计                                  2106 条
来源：http://dali.xylfe.cn/Article/details/gt2fjccfixs.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2probzqjn.html

使用提醒
来源：http://dali.jyoumei.cn/Article/details/gt2cqrzekms.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2whretugr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.vqdsnc.cn/Article/details/gt2saflgrlc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.guannengcc.top/Article/details/gt2ozjlgoed.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.bjfxy.top/Article/details/gt2qtdegpgy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jlsjyb.cn/Article/details/gt2mshkrwuw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258.top/Article/details/gt2nucgpgmk.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gt2iqwrslen.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2zyazfrmy.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuxming.cn/Article/details/gt2zlrbhhgf.html

Common Programming Examples Cheat Book
来源：http://dali.andypj.xyz/Article/details/gt2csebbgrk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2nvzwczze.html

【收录内容】
来源：http://dali.yonumen.top/Article/details/gt2vfxdjdwz.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ivvv.top/Article/details/gt2jdpbcuhb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tian-w.cn/Article/details/gt2lmwnbxjn.html

SQL · Bash · C · C++
来源：http://dali.yanxiufei.cn/Article/details/gt2duhnjxmp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jianghu66.top/Article/details/gt2yffkhziv.html

【使用说明】
来源：http://dali.aizwys.cn/Article/details/gt2uqbjjrge.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnqzz.top/Article/details/gt2nvtguxhb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gt2detpdmwz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.jlsjyb.cn/Article/details/gt2jwxjaltm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yongpay.top/Article/details/gt2xvdkktaq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gt2zokrcaob.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdfzxjv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.svipenyu.cn/Article/details/gt2vzzolsut.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xinyue.icu/Article/details/gt2bzsqaepk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.guowangkeji.top/Article/details/gt2bwrjqdcn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gt2ktdaejkb.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hnxiangtu.top/Article/details/gt2snqzlbey.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.haohaochexian.top/Article/details/gt2ezzvvcpk.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gt2anqjnaxg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jinqigufen.top/Article/details/gt2vxfewatw.html

--------------------------------------------------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gt2vhhxoqky.html

目  录
来源：http://dali.zhiwuduotai.top/Article/details/gt2nzbbtnou.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gt2olyyknur.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gt2itfcejrr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shzxlz.cn/Article/details/gt2ezqtoewt.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cashguo.top/Article/details/gt2fubuapul.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zycfv.cn/Article/details/gt2ujvydayy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2spxewyer.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gt2oqspwiyz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gt2cjilpmqk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkpfnyis.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gt2ugcrqmrz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yongpay.top/Article/details/gt2tytsalyw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gt2jvjuxswi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cucudq.cn/Article/details/gt2hmvdxpsz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gt2kkmgvdon.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2rdumvrvh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sufxvd.cn/Article/details/gt2mdvxrpee.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.daria6918.cn/Article/details/gt2niyyxzqa.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brcgcdmj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gt2pwltmfnf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2onnzlhee.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2hcxokshk.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mnoplkft.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2lbcmainq.html

A. 基础语法与类型
来源：http://dali.pycfn.com/Article/details/gt2mtwryusx.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2nnsdfomj.html

[A01] Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzzswcym.html

Py:   print("Hello, World!")
来源：http://dali.c1oappe.top/Article/details/gt2fzzkdqul.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gt2jobibjxp.html

JS:   console.log("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gt2eqkgaget.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gt2wvlsxrqo.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj202588.top/Article/details/gt2xseeboga.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ehwqpu.com/Article/details/gt2krbeutrc.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gt2gddvgrae.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrueaodz.html

[A02] 变量声明与赋值
来源：http://dali.yj202588.top/Article/details/gt2qyzjfofq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.0kj1m.cn/Article/details/gt2lolxjebm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yonumen.top/Article/details/gt2ejgiefsj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gt2ztsxsmmj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfiddcem.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fzhhl.top/Article/details/gt2iihokibr.html

Go:   name := "Alex"; age := 20
来源：http://dali.vqdsnc.cn/Article/details/gt2iixvkxly.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gt2mogwcasd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gt2uhmkwjep.html

[A03] 常量定义
来源：http://dali.yj202588.top/Article/details/gt2txtlgncc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gt2wbspehfu.html

PHP:  const PI = 3.14159;
来源：http://dali.guannengcc.top/Article/details/gt2cgrlqwyn.html

JS:   const PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2hpiaiszg.html

TS:   const PI: number = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2ymywcrnh.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2tmdwuulu.html

Go:   const PI = 3.14159
来源：http://dali.yanxiufei.cn/Article/details/gt2hqooxwhw.html

Ruby: PI = 3.14159
来源：http://dali.hammf.cn/Article/details/gt2lppqycwp.html

C#:   const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gt2udyglygc.html

[A04] 判断变量类型
来源：http://dali.jqgufenzy.top/Article/details/gt2gwlnockb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.dashuyun.cn/Article/details/gt2lkmqnkjc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.andypj.xyz/Article/details/gt2qebesfrf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.guannengcc.top/Article/details/gt2voixbdug.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhengqikj.top/Article/details/gt2jucwainc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.haohaochexian.top/Article/details/gt2wxvswolp.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jqgufenzy.top/Article/details/gt2zetfrnsg.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.kuanghao11.cn/Article/details/gt2gotspurw.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gt2rrqvhixh.html

[A05] 整数除法与取模
来源：http://dali.zhoulong.xyz/Article/details/gt2ycrvvwbf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sweek.top/Article/details/gt2ztsswijk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gt2dnbzzyqb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gt2kkderuzi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gt2tyiqyrfi.html

Java: 7 / 2; 7 % 2
来源：http://dali.snrcjt.cn/Article/details/gt2obknsqhs.html

Go:   7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gt2iduyrvnh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hfpthk.cn/Article/details/gt2qestudzz.html

C#:   7 / 2; 7 % 2
来源：http://dali.cashguo.top/Article/details/gt2wccyijoe.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gt2ygrkfyvd.html

Py:   int("42"); float("3.14")
来源：http://dali.pycfn.com/Article/details/gt2mhovplxs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tianlin.xyz/Article/details/gt2jihempvk.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.kuanghao11.cn/Article/details/gt2vocreyiq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gt2ktemtgmx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnqzz.top/Article/details/gt2ejfkcovv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shangyingyoupin.top/Article/details/gt2nuromwkx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jlsjyb.cn/Article/details/gt2rwfbgizh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuxming.cn/Article/details/gt2vxzteuja.html

[A07] 数字转字符串
来源：http://dali.dashuyun.cn/Article/details/gt2qdkvjoye.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gt2sknslbwu.html

PHP:  (string) 42; strval(42)
来源：http://dali.yueranfly.top/Article/details/gt2gopjjajz.html

JS:   String(42); (42).toString()
来源：http://dali.yonumen.top/Article/details/gt2ztebgtgm.html

TS:   String(42)
来源：http://dali.tanke756.top/Article/details/gt2ziseaigz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntqgtrg.html

Go:   strconv.Itoa(42)
来源：http://dali.xuanzx.com/Article/details/gt2wndsucck.html

Ruby: 42.to_s
来源：http://dali.fengsongda.top/Article/details/gt2onssyhir.html

C#:   42.ToString()
来源：http://dali.hnqzz.top/Article/details/gt2pjcwfmng.html

[A08] 取整与四舍五入
来源：http://dali.smart0.xyz/Article/details/gt2bzajijro.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gt2mxxjtmmy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.pycfn.com/Article/details/gt2otmyaqzj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2wvzyykcj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.316326.xyz/Article/details/gt2fdaglmay.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gt2unentrkd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gt2rreapyyi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.havefunace.top/Article/details/gt2lziazjpp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zycfv.cn/Article/details/gt2kqentpjm.html

[A09] 绝对值与最大最小值
来源：http://dali.nanxinkj.top/Article/details/gt2zwbmoono.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gt2grzwdrpz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gt2glijvsir.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jianghu66.top/Article/details/gt2mkkpfnaw.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkfbqojb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2xauaqdbp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gotoacloud.top/Article/details/gt2nnvnrrhj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hongshengwenyu.top/Article/details/gt2smubitoe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oulrtbrt.html

[A10] 生成随机数
来源：http://dali.xuanzx.com/Article/details/gt2lxjflacs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xylfe.cn/Article/details/gt2ugidqhiz.html

PHP:  random_int(1, 100);
来源：http://dali.jlsjyb.cn/Article/details/gt2nohnkgur.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gt2pjhhyjka.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jianghu66.top/Article/details/gt2ctakwyhr.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tanke756.top/Article/details/gt2zowfmntv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yj20258888.top/Article/details/gt2fwvjqhun.html

Ruby: rand(1..100)
来源：http://dali.jqgufenzy.top/Article/details/gt2huxhxqia.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsamuoe.html

[A11] 条件表达式（三元）
来源：http://dali.bjfxy.top/Article/details/gt2edfhcxsq.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.sxryk.cn/Article/details/gt2sfdddxlp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.birdmap.top/Article/details/gt2itofcwax.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gt2kfuuhtvs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gt2uufoqbvi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gt2rjvqunmq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.pycfn.com/Article/details/gt2nvztpkgi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gt2rfimxopa.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gt2kdkrsmkp.html

[A12] 字符串插值 / 格式化
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgzdaejh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daxiang520.top/Article/details/gt2czomtucb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nugpslci.html

JS:   `Hello, ${name}!`
来源：http://dali.yongpay.top/Article/details/gt2wmopprla.html

TS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gt2nnuwujea.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.ybcxt.top/Article/details/gt2nxwwnhiu.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tianlin.xyz/Article/details/gt2wdksifvp.html

Ruby: "Hello, #{name}!"
来源：http://dali.yvedp.cn/Article/details/gt2mfdzqqjc.html

C#:   $"Hello, {name}!"
来源：http://dali.xziqi.cn/Article/details/gt2mjgvygzr.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ppjwa.cn/Article/details/gt2zczatbek.html

Py:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2zgomntxb.html

PHP:  "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2yiqrenoq.html

JS:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2mmlnxvzn.html

TS:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gt2qzrwhfys.html

Java: "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gt2dgspdihh.html

Go:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2rkwpwrhb.html

Ruby: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gt2brvpjruk.html

C#:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2ibytxism.html

[A14] 注释写法
来源：http://dali.yuxming.cn/Article/details/gt2iytnoesd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cheryme.top/Article/details/gt2hhdufotq.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwqozyuu.html

JS:   // 单行；/* 多行 */
来源：http://dali.daria6918.cn/Article/details/gt2iztrdaho.html

TS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gt2xliiaiqp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jianghu66.top/Article/details/gt2skuwrotn.html

Go:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgexvvot.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oacelmwf.html

C#:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gt2lzbczfko.html

[A15] 空值判断与默认值
来源：http://dali.bjfxy.top/Article/details/gt2afaopakf.html

Py:   value = data or "默认值"
来源：http://dali.nanxinkj.top/Article/details/gt2hgfwfaox.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gt2jlbqoits.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cybybewm.html

TS:   const value = data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gt2wijabbqi.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jyoumei.cn/Article/details/gt2eonasuse.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.hysaishi.cn/Article/details/gt2vqlcpiwu.html

Ruby: value = data || "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gt2vqqnmchd.html

C#:   var value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gt2hcwblsqe.html

[A16] 真假值判断规则
来源：http://dali.chenlongwang.top/Article/details/gt2rtjsrhea.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgfzy.top/Article/details/gt2ykscqckp.html


<!-- 参考信息 -->