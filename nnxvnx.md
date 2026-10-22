代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gtepvcudyu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258888.top/Article/details/gtsgkxgrxo.html

[U92] JS：深拷贝
来源：http://dali.yangfankeji.com/Article/details/gtawlqbqai.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtdwufxcmx.html

[U93] JS：模板字符串
来源：http://dali.iojbl.cn/Article/details/gtymytwpvt.html

`共 ${n} 条`
来源：http://dali.mhx1999.top/Article/details/gtadwyaely.html

[U94] JS：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtatxcfecr.html

const double = x => x * 2;
来源：http://dali.redwolf501.top/Article/details/gtnljzwfgf.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtprmyvnrt.html

new Promise((resolve, reject) => {})
来源：http://dali.xylfe.cn/Article/details/gthavzlrvk.html

[U96] JS：async/await 与异常
来源：http://dali.cdnleiting.top/Article/details/gtljtsiwoj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtewkgcygj.html

[U97] JS：并发请求
来源：http://dali.zhongyouzk.top/Article/details/gtmaymueci.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtijhpnpok.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhengqikj.top/Article/details/gtbqdrwjit.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.bjfxy.top/Article/details/gttwxguutc.html

[U99] JS：事件监听
来源：http://dali.sweek.top/Article/details/gtihwssqop.html

el.addEventListener("click", e => {})
来源：http://dali.cheryme.top/Article/details/gtwafbbgnu.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gtauyflxhw.html

document.querySelector(".item")
来源：http://dali.xylfe.cn/Article/details/gtnjfhwnzj.html

[U101] JS：classList 操作
来源：http://dali.feifeiyinyue.top/Article/details/gthdyumbnu.html

el.classList.toggle("active")
来源：http://dali.dianchejie.cn/Article/details/gtgkowolxt.html

[U102] JS：本地存储
来源：http://dali.guowangkeji.top/Article/details/gtaibfdlnn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gtaeloorzo.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gtuczvccoa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gtretkuajs.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gtvpvzxzgy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gtnjpgyhxk.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gtaihemkzt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xylfe.cn/Article/details/gtrvbseuby.html

[U106] JS：日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllzhmkbc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangshuangyany.cn/Article/details/gtlphwamkn.html

[U107] JS：数字千分位
来源：http://dali.gogol.net.cn/Article/details/gthqogveha.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtmxnhyhzj.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtialueaqc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aibaodan.cn/Article/details/gtogpzhoax.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtyvgkucya.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtlmbhxzlm.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gtotsogloo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gtpikdvbay.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gtrqawvito.html

new Map(Object.entries(obj))
来源：http://dali.hnqzz.top/Article/details/gtidyotstm.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gttwptizcu.html

"7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtlsqpyroq.html

[U113] JS：正则替换全部
来源：http://dali.hongshengwenyu.top/Article/details/gtqpesfqzf.html

s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtxahjrbju.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtyklxfifi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtwlnjtmam.html

[U115] JS：生成 UUID
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoitlxsrw.html

crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtjxobwwdc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtjldwfsym.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gtrcrjwrdy.html

[U117] JS：单元测试
来源：http://dali.tanke756.top/Article/details/gtutmnivym.html

npm i -D vitest;  npx vitest
来源：http://dali.0kj1m.cn/Article/details/gtfyagwzlw.html

[U118] JS：开发服务器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfyhwckvm.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gtpwobbmoe.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gtuqsfpjdr.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtkdetcipd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlypjxzzm.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gtzzyybucr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrleqjsls.html

统计汇总
来源：http://dali.dashuyun.cn/Article/details/gtjszhqkzh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtrpciudsh.html

按语言统计（条）：
来源：http://dali.nanxuanxn.top/Article/details/gtzeaqhbqv.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gtjglsbakv.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtjqfsauua.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gttifxcump.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gtkulbkeno.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtpeeeahae.html

Go ............. 212
来源：http://dali.sufxvd.cn/Article/details/gtjacsilwn.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtnnmbfrvd.html

C# ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtiqtqucjn.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gtzwthynod.html

C++ ............ 30
来源：http://dali.jlsjyb.cn/Article/details/gtbogxtftr.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtlfebubpo.html

Bash ........... 80
来源：http://dali.yangfankeji.com/Article/details/gthkwfqybl.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtfqncwdvl.html

Swift .......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkimzcbt.html

Lua ............ 10
来源：http://dali.wangdashe.top/Article/details/gtqvwdgrvy.html

Perl ........... 10
来源：http://dali.havefunace.top/Article/details/gtxtvjghhf.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtmlcdefis.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtacrsefdd.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gtmexxufox.html

按章节统计：
来源：http://dali.pycfn.com/Article/details/gthfpmests.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtezdkzsqj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtgdluhijz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnvektda.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gtctdarhfx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtyzbmbvfp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtzuzqcawu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gttpdmfqxq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.dashuyun.cn/Article/details/gtzqikemcx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtludyxfho.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtfbvdbjwb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkrndvzt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtqdedcdok.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtoqijsfdg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gtynzjjzcg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gtxaajgdhl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtqobvmquu.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gtngscxnwq.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gtyrcgtoov.html

S C / C++ 专题                          60
来源：http://dali.daria6918.cn/Article/details/gtgvzwemmn.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtnmskgivu.html

U 高频实用片段                         120
来源：http://dali.wangdashe.top/Article/details/gtpjvuffcd.html

------------------------------------
来源：http://dali.gzhubu.top/Article/details/gthymofcyg.html

合计                                  2106 条
来源：http://dali.zhoulong.xyz/Article/details/gtsbrhsuiw.html

--------------------------------------------------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gtekooztzs.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gtiwwqmpcn.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtjlbrknem.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.birdmap.top/Article/details/gtzzplbxfm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sysykeji.top/Article/details/gtjnhkzjsw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.aizwys.cn/Article/details/gtxuxforak.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.jqgufenzy.top/Article/details/gthrffazgo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.kuanghao11.cn/Article/details/gtlplxlwbs.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gteikfsfyf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtmklxphdc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.quarkkingdee.top/Article/details/gtrpqrxujd.html

Common Programming Examples Cheat Book
来源：http://dali.jqgfzy.top/Article/details/gtypetwrzw.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrjjrbgwp.html

【收录内容】
来源：http://dali.jyoumei.cn/Article/details/gtawftgtme.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtgoixglca.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuanzx.com/Article/details/gtnskhexmd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gtjkclucgx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenzaomai.com/Article/details/gtwqcotevd.html

【使用说明】
来源：http://dali.yj20258888.top/Article/details/gtxwkapayl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aibaodan.cn/Article/details/gtitfygrxt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pycfn.com/Article/details/gtjjfggqgu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.nwbrower.top/Article/details/gtxbyprksj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sysykeji.top/Article/details/gthjctcqmj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nwbrower.top/Article/details/gtczbbbtak.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shuidangran.top/Article/details/gtptkkqmwu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zycfv.cn/Article/details/gtuywiuxwx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hywenlv.cn/Article/details/gtqfmegopl.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cdnleiting.top/Article/details/gtpkzmbftu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gtqbrfxetp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gtppmovtom.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.snrcjt.cn/Article/details/gtlvmjwcxp.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gtvpnefnts.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guowangkeji.top/Article/details/gtojvhiwso.html

--------------------------------------------------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtfmkjlatd.html

目  录
来源：http://dali.yonumen.top/Article/details/gtyatunujw.html

--------------------------------------------------------------------------------
来源：http://dali.nwbrower.top/Article/details/gtrhxhfsph.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.gotoacloud.top/Article/details/gtqeztewyh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtnejwybtn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.hnxiangtu.top/Article/details/gtxecabrte.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtbfiukgwq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.dianchejie.cn/Article/details/gtkseylrjk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtugbkhktf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtuosaljji.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gthdusuprj.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtcihdtuhi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xylfe.cn/Article/details/gtyfknszxv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrjyhunr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtoiplzrib.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtthsonrxo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.hnxiangtu.top/Article/details/gtbpoxqhqg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.meibo888.top/Article/details/gtljfbdtby.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.fzhhl.top/Article/details/gtlvrzmpig.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.sufxvd.cn/Article/details/gtzwegjsbc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtazzisitd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jqgufenzy.top/Article/details/gtfthylyva.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guannengcc.top/Article/details/gttjdwfbvp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtcstjmpxy.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtuuytpfyz.html

A. 基础语法与类型
来源：http://dali.yueranfly.top/Article/details/gtlvpmmsde.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtircedgak.html

[A01] Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtlzcbuokz.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gtgwdgugyf.html

PHP:  echo "Hello, World!";
来源：http://dali.yongpay.top/Article/details/gtviaurckl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtdtwwmhfo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gogol.net.cn/Article/details/gtknlxrbus.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhongyouzk.top/Article/details/gttsxxmcvj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtkvtqfsmw.html

Ruby: puts "Hello, World!"
来源：http://dali.nanxuanxn.top/Article/details/gtlruwquxi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.sxryk.cn/Article/details/gtrrwikwqb.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtqewabzzl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cashguo.top/Article/details/gtbzmgsjct.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.nwbrower.top/Article/details/gtdmbwrrmf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtrjnqjjdn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfooxuorw.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtsgjdwkpo.html

Go:   name := "Alex"; age := 20
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtpzrryq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yongpay.top/Article/details/gtovthrqdw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yonumen.top/Article/details/gtpsotrlzw.html

[A03] 常量定义
来源：http://dali.fengsongda.top/Article/details/gtmatzagek.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.havefunace.top/Article/details/gtxblkcuat.html

PHP:  const PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtekbkbswb.html

JS:   const PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtizxdonaa.html

TS:   const PI: number = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtfhjbigbb.html

Java: static final double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtbdalhkfn.html

Go:   const PI = 3.14159
来源：http://dali.yonumen.top/Article/details/gtfihmkpnr.html

Ruby: PI = 3.14159
来源：http://dali.ydzc1.top/Article/details/gtunqlpyyc.html

C#:   const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtdcmyftrh.html

[A04] 判断变量类型
来源：http://dali.tanke756.top/Article/details/gtvdrfuxfo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.gogol.net.cn/Article/details/gtfgqmpkef.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkslufmgb.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jiagoushi.top/Article/details/gturejxhde.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangdashe.top/Article/details/gtptcijugk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daria6918.cn/Article/details/gtvannmifr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.meibo888.top/Article/details/gtxwvjpsal.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.dashuyun.cn/Article/details/gtvgfcsvgx.html

C#:   x.GetType().Name; x is int
来源：http://dali.yangfankeji.com/Article/details/gtskctnvzy.html

[A05] 整数除法与取模
来源：http://dali.pengpengdd.cyou/Article/details/gtxnphvylh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.chenzaomai.com/Article/details/gtucocccit.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtekkpmjqh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gthyoosyqn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtzmyzzwpd.html

Java: 7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtyjlxyuij.html

Go:   7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtrukudtvh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtgvpiywlu.html

C#:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gthvpgpohg.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtueerfavr.html

Py:   int("42"); float("3.14")
来源：http://dali.guannengcc.top/Article/details/gtmqvysatn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cheryme.top/Article/details/gtgasgjfej.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtjzwjzwgx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yuxming.cn/Article/details/gtadokdnya.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hywenlv.cn/Article/details/gtnkhbvfmw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ehwqpu.com/Article/details/gtdftxhfzx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jqgfzy.top/Article/details/gtvmfszqol.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.pycfn.com/Article/details/gtcapiamyz.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwtcrcps.html

Py:   str(42)
来源：http://dali.aibaodan.cn/Article/details/gtgqtayljn.html

PHP:  (string) 42; strval(42)
来源：http://dali.yueranfly.top/Article/details/gtakghotwn.html

JS:   String(42); (42).toString()
来源：http://dali.pengpengdd.cyou/Article/details/gthhdpludr.html

TS:   String(42)
来源：http://dali.gotoacloud.top/Article/details/gttdgpnmoe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlrxdsta.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtltxtqkju.html

Ruby: 42.to_s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbaagagv.html

C#:   42.ToString()
来源：http://dali.cashguo.top/Article/details/gthrqbmlkv.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gtwqcpiqwd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtrwflleml.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gogol.net.cn/Article/details/gtfqfblrtx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtvsyqrour.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuanzx.com/Article/details/gtxmxqsszz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtjhtvtqvv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtdxfqjehn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zycfv.cn/Article/details/gtvqhksvlc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj20258888.top/Article/details/gthhicryzz.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gtdmqfngjs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkigkxpmm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtywrqsfht.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtnfxlfpct.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.havefunace.top/Article/details/gtegmmtlbc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtvtdnbwix.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhongyouzk.top/Article/details/gtppfrzkkf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.chenzaomai.com/Article/details/gtdweyxxpn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtvqibevsg.html

[A10] 生成随机数
来源：http://dali.jiagoushi.top/Article/details/gtwrmohhmd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gtmuhatjie.html

PHP:  random_int(1, 100);
来源：http://dali.wangdashe.top/Article/details/gtpfjeblyt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gttiiwwexf.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gtlntdogup.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtwwerbbld.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.andypj.xyz/Article/details/gtkpkqtrmy.html

Ruby: rand(1..100)
来源：http://dali.fzhhl.top/Article/details/gthpuyqbfj.html

C#:   new Random().Next(1, 101)
来源：http://dali.yanxiufei.cn/Article/details/gtxbcfnebb.html

[A11] 条件表达式（三元）
来源：http://dali.snrcjt.cn/Article/details/gtbpuctdqn.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gtnncoztky.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtasikrasu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtxqrdtmto.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtvuacmjmv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtagusojrd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jyoumei.cn/Article/details/gtysmwomdy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtujufkujf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtmiwzulgo.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gtknnehgrk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hfpthk.cn/Article/details/gtqchedduv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yj20258.top/Article/details/gtbcyoatps.html

JS:   `Hello, ${name}!`
来源：http://dali.jiagoushi.top/Article/details/gtbtadftre.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtufocbzwv.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvykmxvw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guannengcc.top/Article/details/gttpivbllk.html

Ruby: "Hello, #{name}!"
来源：http://dali.mhx1999.top/Article/details/gtmvvupffl.html

C#:   $"Hello, {name}!"
来源：http://dali.aibaodan.cn/Article/details/gtbvkhefxc.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gtskxfxwqk.html

Py:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtttloujxm.html

PHP:  "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtlnysmkxq.html

JS:   "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtjyuhxgxp.html

TS:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtattzntlv.html

Java: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtkyrrlhqu.html

Go:   "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtcdquhkcs.html

Ruby: "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gtfvweccya.html

C#:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtnltynptg.html

[A14] 注释写法
来源：http://dali.chenzaomai.com/Article/details/gtxnzclpxn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gtxozqsply.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gtnavcszxu.html

JS:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtaebcvoxl.html

TS:   // 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gtbjzgprbg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinqigufen.top/Article/details/gtgelibbnm.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtebjwxjvv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.316326.xyz/Article/details/gtbkenwmsa.html

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtqnjxvgoa.html

[A15] 空值判断与默认值
来源：http://dali.birdmap.top/Article/details/gtohogijgc.html

Py:   value = data or "默认值"
来源：http://dali.shuidangran.top/Article/details/gtrijimxan.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gteqwhxvvq.html

JS:   const value = data ?? "默认值";
来源：http://dali.fzhhl.top/Article/details/gtcwevkuyp.html

TS:   const value = data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtnrrphwhz.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gteuszmfnt.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aibaodan.cn/Article/details/gtjuqwbjjz.html


<!-- 参考信息 -->