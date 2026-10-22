代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.yuxming.cn/Article/details/gtpoacziar.html

new Promise((resolve, reject) => {})
来源：http://dali.yvedp.cn/Article/details/gtuvrlnual.html

[U96] JS：async/await 与异常
来源：http://dali.shuidangran.top/Article/details/gtesosnrwq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtuoemqdvl.html

[U97] JS：并发请求
来源：http://dali.wangshuangyany.cn/Article/details/gtpyrweghz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxidgewm.html

[U98] JS：fetch 带 JSON
来源：http://dali.yongpay.top/Article/details/gtuidvvtbm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gtlcifmahx.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtqtlwnuho.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gtvnsjxehb.html

[U100] JS：DOM 查询
来源：http://dali.havefunace.top/Article/details/gtzotccewc.html

document.querySelector(".item")
来源：http://dali.meibo888.top/Article/details/gtmnsstdss.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gtztezooam.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gtjmojugsj.html

[U102] JS：本地存储
来源：http://dali.fengsongda.top/Article/details/gtdkcpckla.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtjikdgqbd.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtjsoejfgq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ehwqpu.com/Article/details/gtstsaycsr.html

[U104] JS：防抖
来源：http://dali.yonumen.top/Article/details/gtgycwsrky.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtoznmbhlj.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtzwzkkbbq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnxiangtu.top/Article/details/gtudhpklra.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gtunezazhi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ivvv.top/Article/details/gtjelljvhr.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtvupyohut.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yonumen.top/Article/details/gtfmziwcat.html

[U108] JS：随机整数
来源：http://dali.feifeiyinyue.top/Article/details/gtqucpmmas.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sufxvd.cn/Article/details/gthnlovowf.html

[U109] JS：数组分组
来源：http://dali.chenlongwang.top/Article/details/gtsxkvacva.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtrhtkzxiv.html

[U110] JS：数组分块
来源：http://dali.9152youxi.cn/Article/details/gttlvuyymt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hywenlv.cn/Article/details/gtoykweypd.html

[U111] JS：对象转 Map
来源：http://dali.jianghu66.top/Article/details/gtipvygujo.html

new Map(Object.entries(obj))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxogzopws.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gtmrmdvsal.html

"7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gthtrvmpvp.html

[U113] JS：正则替换全部
来源：http://dali.hfpthk.cn/Article/details/gtoneijuvz.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtdwlxuaku.html

[U114] JS：JSON 深比较
来源：http://dali.aibaodan.cn/Article/details/gthhoxfjmz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gtkmhhpijz.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtqjbixnpv.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtljzcwokh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zycfv.cn/Article/details/gtutoltdeu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gtuqwfthxo.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtuywitmam.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtkysrafpp.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtuojfqglm.html

npm i -D vite;  npx vite
来源：http://dali.gzhubu.top/Article/details/gtjxszwoqt.html

[U119] JS：生产构建
来源：http://dali.smart0.xyz/Article/details/gtersovuaw.html

npx vite build
来源：http://dali.smart0.xyz/Article/details/gtafzegtww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtpjzakngm.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gtzxhuvhom.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqpnixwri.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtvrhynzls.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtfiggfrpc.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gtlyficvkd.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtrdxqqjfp.html

PHP ............ 252
来源：http://dali.xuanzx.com/Article/details/gtignuixjv.html

JavaScript ..... 252
来源：http://dali.zhongyouzk.top/Article/details/gtqmgwdutk.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtgpeposyy.html

Java ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gthiznbhvu.html

Go ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvcnrxbs.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtqvqbdwes.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gtdzxvvrhk.html

C .............. 30
来源：http://dali.redwolf501.top/Article/details/gtwsvqbkpd.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtolmzteyj.html

SQL ............ 90
来源：http://dali.ehwqpu.com/Article/details/gtoifeyirg.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gtvewepehy.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtdanhymip.html

Swift .......... 15
来源：http://dali.aibaodan.cn/Article/details/gtoyivgucz.html

Lua ............ 10
来源：http://dali.birdmap.top/Article/details/gtvxvqiwhq.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gthbysiixs.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gtaiallrpx.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtladjxann.html

合计 ........... 2106 条
来源：http://dali.zhiwuduotai.top/Article/details/gthipgpckq.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gtrfvsfftr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtvxbqnwpp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtsohsadhd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xinyue.icu/Article/details/gtobbfwwcq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtbhagaefk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnxiangtu.top/Article/details/gtkfqtmgyl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtwcldirwb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.kuanghao11.cn/Article/details/gtfoocnlzl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtzrmvsnuj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtpbyvqwvf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gtbktwnpos.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtphtrshvb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtasyzgjwr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtlajpenlw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtgxhljbyl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.meibo888.top/Article/details/gtfhikwiut.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtyuqenmpz.html

Q SQL 专题                              90
来源：http://dali.pengpengdd.cyou/Article/details/gtrhkjmxwl.html

R Bash 专题                             80
来源：http://dali.guowangkeji.top/Article/details/gtqghmpuon.html

S C / C++ 专题                          60
来源：http://dali.xuetiantiany.cn/Article/details/gtcxqowyhk.html

T 其他语言补充                          60
来源：http://dali.kuanghao11.cn/Article/details/gtjnjdijsc.html

U 高频实用片段                         120
来源：http://dali.feifeiyinyue.top/Article/details/gtqrmwpynh.html

------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtgfbhnhhp.html

合计                                  2106 条
来源：http://dali.zycfv.cn/Article/details/gtdiechcfy.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtbpynqclt.html

使用提醒
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkxygxig.html

--------------------------------------------------------------------------------
来源：http://dali.havefunace.top/Article/details/gtxewgajun.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cucudq.cn/Article/details/gtzsmxlrtt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hywenlv.cn/Article/details/gtyqiysbsg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.smart0.xyz/Article/details/gtowuuuozv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ybcxt.top/Article/details/gtwjctkajs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nwbrower.top/Article/details/gtwnbtqoab.html

—— 文件结束 ——
来源：http://dali.feifeiyinyue.top/Article/details/gtxitfancc.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyiwivvka.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yonumen.top/Article/details/gtbyoimphy.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gtvvrgfeby.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtoaauyslq.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtmjghhxwo.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sweek.top/Article/details/gttfwvqeyr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.tianlin.xyz/Article/details/gtwjfpkpaq.html

SQL · Bash · C · C++
来源：http://dali.nwbrower.top/Article/details/gtmqqcsjoy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gtnejllajm.html

【使用说明】
来源：http://dali.0kj1m.cn/Article/details/gtxwmsxfnd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenzaomai.com/Article/details/gtnigaxbbw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gtzzjssnlg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhongyouzk.top/Article/details/gtgnhznlgz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xziqi.cn/Article/details/gtvgrxfllr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.dianchejie.cn/Article/details/gtltkkkejn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.hnxiangtu.top/Article/details/gtapohhani.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.mhx1999.top/Article/details/gtltaceopu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtxpdnpgsg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258888.top/Article/details/gtkseyyghz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.nanxuanxn.top/Article/details/gtkeqvtaut.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gaohongyu789.top/Article/details/gtstfebyzb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gtsvablscy.html

【文件统计】
来源：http://dali.kuanghao11.cn/Article/details/gtpaydyufs.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.vqdsnc.cn/Article/details/gtdteftllh.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtymjcejxx.html

目  录
来源：http://dali.snrcjt.cn/Article/details/gtclpwlzvc.html

--------------------------------------------------------------------------------
来源：http://dali.hammf.cn/Article/details/gtgbnmiuuu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.sweek.top/Article/details/gtczixksjb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtccxteenk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtrwmvadde.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.meibo888.top/Article/details/gtaixskyya.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.fzhhl.top/Article/details/gtrkxjsuil.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtswecnccb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.cqqwz.cn/Article/details/gtjipobypd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtawfbkpib.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sufxvd.cn/Article/details/gtwebrponq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtdvedjytr.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtlazodsuc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtjmunottp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhengqikj.top/Article/details/gtgdukrolp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ppjwa.cn/Article/details/gtxixkyric.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xylfe.cn/Article/details/gtwvygrgyk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtkuzmimow.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmevpxsem.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dashuyun.cn/Article/details/gtddrbbzab.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.cheryme.top/Article/details/gtnqfqetfv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtdljilqjl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtrkabdmzs.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaajktxbd.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gtdilzriti.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtneuokclw.html

[A01] Hello World
来源：http://dali.cashguo.top/Article/details/gtupuviijn.html

Py:   print("Hello, World!")
来源：http://dali.cqqwz.cn/Article/details/gtiaeebdpt.html

PHP:  echo "Hello, World!";
来源：http://dali.xuanzx.com/Article/details/gtultyddnf.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxmtroyp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yueranfly.top/Article/details/gtrqhwjqof.html

Java: System.out.println("Hello, World!");
来源：http://dali.smart0.xyz/Article/details/gtmimlhoqx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yj202588.top/Article/details/gtjtqzupsg.html

Ruby: puts "Hello, World!"
来源：http://dali.sweek.top/Article/details/gtsplfgxvt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hongshengwenyu.top/Article/details/gtwsiftsle.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gtuaseccdi.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.shuidangran.top/Article/details/gtrephgkzz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtuogorhcq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.wangdashe.top/Article/details/gtzlxugdur.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sxryk.cn/Article/details/gtpsqtbswb.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtiueqywke.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtlntavbaf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfmmxrxy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtqofpazha.html

[A03] 常量定义
来源：http://dali.zhoulong.xyz/Article/details/gtbyvxghyd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gaohongyu789.top/Article/details/gtkzjdsglj.html

PHP:  const PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gtekzgfrxn.html

JS:   const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gttudxroud.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtmmjuwzyv.html

Java: static final double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtnoeomecn.html

Go:   const PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gtgldgtvkg.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtfisqcnlg.html

C#:   const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbzstjcz.html

[A04] 判断变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtksdevcbh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tanke756.top/Article/details/gtlquppdol.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.redwolf501.top/Article/details/gthzopmkeh.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtlbbzuajt.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtgoierkbl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xinyue.icu/Article/details/gtapypofpe.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.sxryk.cn/Article/details/gtafqfloyb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cqqwz.cn/Article/details/gthfquzaxj.html

C#:   x.GetType().Name; x is int
来源：http://dali.hfpthk.cn/Article/details/gtlsrnwvsm.html

[A05] 整数除法与取模
来源：http://dali.shuidangran.top/Article/details/gtdcogqooq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtvlmufupd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtrwdvznwt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtqcrfwwxp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtqtxkhxje.html

Java: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtoiumkasy.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gttsgccutp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.ppjwa.cn/Article/details/gtejehamga.html

C#:   7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtzdouhzyt.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtkybuncjx.html

Py:   int("42"); float("3.14")
来源：http://dali.daria6918.cn/Article/details/gtapmfjklp.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangdashe.top/Article/details/gtrjrryasl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtdrxbmojh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yuxming.cn/Article/details/gtpdmjtbym.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtjfczpskj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shuidangran.top/Article/details/gtnirgpcnt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.haohaochexian.top/Article/details/gtoekgxlqz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.meibo888.top/Article/details/gtqwyxbedn.html

[A07] 数字转字符串
来源：http://dali.ybcxt.top/Article/details/gtdduroloa.html

Py:   str(42)
来源：http://dali.snrcjt.cn/Article/details/gtbvfoodax.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhengqikj.top/Article/details/gtmuoxtxvt.html

JS:   String(42); (42).toString()
来源：http://dali.sysykeji.top/Article/details/gtasxvatwp.html

TS:   String(42)
来源：http://dali.dianchejie.cn/Article/details/gtbzyummsd.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.sufxvd.cn/Article/details/gtpdipupzu.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gtjjalfykc.html

Ruby: 42.to_s
来源：http://dali.aizwys.cn/Article/details/gtuszslyxa.html

C#:   42.ToString()
来源：http://dali.iojbl.cn/Article/details/gtzpiwjbxw.html

[A08] 取整与四舍五入
来源：http://dali.yongpay.top/Article/details/gtbvbubhsj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtudcrsslq.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.haohaochexian.top/Article/details/gteateeobb.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtnjpfkvdu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jiagoushi.top/Article/details/gtoowntjcd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sufxvd.cn/Article/details/gtpyqsjmqv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gttpnsuiec.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nanxuanxn.top/Article/details/gtjjkmxiqq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtajaejmgl.html

[A09] 绝对值与最大最小值
来源：http://dali.tanke756.top/Article/details/gtdghpslmt.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtwigbubva.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtmxthqzkw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtraxznpbl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtpdsgmqlt.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtkrbzbbus.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.chenjidiqi.icu/Article/details/gtvtalxbua.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ehwqpu.com/Article/details/gtipwzeajc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtagzhvuzk.html

[A10] 生成随机数
来源：http://dali.jqgfzy.top/Article/details/gtkjgolamb.html

Py:   import random; random.randint(1, 100)
来源：http://dali.cqqwz.cn/Article/details/gtzzblgyot.html

PHP:  random_int(1, 100);
来源：http://dali.chenlongwang.top/Article/details/gtvituqwca.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.dashuyun.cn/Article/details/gthjhvjwba.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtzrlyfymv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.daxiang520.top/Article/details/gtauxrfoam.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yangfankeji.com/Article/details/gtmntchlit.html

Ruby: rand(1..100)
来源：http://dali.yj20258888.top/Article/details/gtpqccqsmo.html

C#:   new Random().Next(1, 101)
来源：http://dali.hammf.cn/Article/details/gthcecrzlu.html

[A11] 条件表达式（三元）
来源：http://dali.daxiang520.top/Article/details/gtthzexdyp.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shzxlz.cn/Article/details/gtivfxrolz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gteotzvpcd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtrjganxcs.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtnybghxfe.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtghzwmulr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yj202588.top/Article/details/gtfpeqursk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtdzptaspf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtdrhszphq.html

[A12] 字符串插值 / 格式化
来源：http://dali.hnqzz.top/Article/details/gtsbwsnmvi.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hnqzz.top/Article/details/gtrodqzoql.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenzaomai.com/Article/details/gtzfoocehm.html

JS:   `Hello, ${name}!`
来源：http://dali.jyoumei.cn/Article/details/gtvtxhoige.html

TS:   `Hello, ${name}!`
来源：http://dali.jinqigfzy.top/Article/details/gteitlislp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gtcrszakcx.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hfpthk.cn/Article/details/gtmgojppnf.html

Ruby: "Hello, #{name}!"
来源：http://dali.sysykeji.top/Article/details/gtelyzywha.html

C#:   $"Hello, {name}!"
来源：http://dali.mhx1999.top/Article/details/gtydkizujy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhijiandao.cn/Article/details/gttpizncxq.html

Py:   "第一行\n第二行"
来源：http://dali.c1oappe.top/Article/details/gtcrszjqsf.html

PHP:  "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtbsahrwuq.html

JS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtxrcdvqiw.html

TS:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gthagkqqyb.html

Java: "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtluwszetk.html

Go:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtcjgsxsuw.html

Ruby: "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtybpphmqe.html

C#:   "第一行\n第二行"
来源：http://dali.meibo888.top/Article/details/gtjpbmmncw.html

[A14] 注释写法
来源：http://dali.pengpengdd.cyou/Article/details/gtmnaeprjj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zdqjudy.top/Article/details/gtyhabwdlw.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtswbrijcr.html

JS:   // 单行；/* 多行 */
来源：http://dali.jianghu66.top/Article/details/gtbmhwwabv.html

TS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtkiwlmirn.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfpcqzfh.html

Go:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtnfvwpnnb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfgcyitfn.html

C#:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtedtfezep.html

[A15] 空值判断与默认值
来源：http://dali.dashuyun.cn/Article/details/gturntfoox.html

Py:   value = data or "默认值"
来源：http://dali.yanxiufei.cn/Article/details/gtgenmgsit.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtuoccsoku.html

JS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtjvnndwal.html

TS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtcgpgwxhq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.9152youxi.cn/Article/details/gthobmdsha.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzldeaxa.html

Ruby: value = data || "默认值"
来源：http://dali.jyoumei.cn/Article/details/gtlsxybgai.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gtkkbnztoi.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gtfcrpmulc.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jianghu66.top/Article/details/gtwpeczyrm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cheryme.top/Article/details/gtxoubisee.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zdqjudy.top/Article/details/gtmrunnzsh.html

TS:   if (!x) {}
来源：http://dali.wangdashe.top/Article/details/gtwyfknvyi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xuanzx.com/Article/details/gtdaysoxpv.html


<!-- 参考信息 -->