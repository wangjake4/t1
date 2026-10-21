代发 wailian999

[U97] JS：并发请求
来源：http://dali.zhixingplan.top/Article/details/gtibqvwvbc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xziqi.cn/Article/details/gtypfajtwl.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigfzy.top/Article/details/gtbfchcyei.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gtszxesocx.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gtrgjafckc.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gteudbmfht.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslfaryei.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gtxftycrud.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gteojdskrr.html

el.classList.toggle("active")
来源：http://dali.zhoulong.xyz/Article/details/gtodtjggvw.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtideplqtu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shzxlz.cn/Article/details/gtewgqerzu.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtyvtfnonh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxuanxn.top/Article/details/gtztaelwtn.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gtyroxdbwh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtfnaetyyf.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtnolyovnt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.quarkkingdee.top/Article/details/gtdbpqrvzg.html

[U106] JS：日期格式化
来源：http://dali.andypj.xyz/Article/details/gtlpvugnkj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pycfn.com/Article/details/gtxgbulzot.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtqipsqxrz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gtwdzekosi.html

[U108] JS：随机整数
来源：http://dali.guowangkeji.top/Article/details/gtjzngnkjo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gtdpihlqfo.html

[U109] JS：数组分组
来源：http://dali.yj20258888.top/Article/details/gtdkyepgbl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtdijjjbjp.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtpaldvzoc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtqskqmgun.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtnmltpbsz.html

new Map(Object.entries(obj))
来源：http://dali.jqgufenzy.top/Article/details/gtpoztjnkg.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtuepqgwwl.html

"7".padStart(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gttfybjsjk.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gtqjlcxjof.html

s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtykffljti.html

[U114] JS：JSON 深比较
来源：http://dali.tianlin.xyz/Article/details/gtcpeqqktk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtumtvvzxs.html

[U115] JS：生成 UUID
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokyexpll.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtokvcjcsm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yueranfly.top/Article/details/gtquvqoipj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtqluuspsj.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunpedhrn.html

npm i -D vitest;  npx vitest
来源：http://dali.chenjidiqi.icu/Article/details/gttdamenxo.html

[U118] JS：开发服务器
来源：http://dali.vqdsnc.cn/Article/details/gtgibnkmhu.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtrdbsmtjp.html

[U119] JS：生产构建
来源：http://dali.zhixingplan.top/Article/details/gttnwcirst.html

npx vite build
来源：http://dali.kuanghao11.cn/Article/details/gtwggnerty.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhongyouzk.top/Article/details/gtnpyrgnmn.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtdztrbngs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gthvghzkih.html

统计汇总
来源：http://dali.316326.xyz/Article/details/gtkgoqlkbm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxycurgfa.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gtmdjhccyr.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtfxnkjgyj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gtbivubjzb.html

JavaScript ..... 252
来源：http://dali.gogol.net.cn/Article/details/gtbylbsees.html

TypeScript ..... 212
来源：http://dali.andypj.xyz/Article/details/gtkhxocedy.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gtpxookdzr.html

Go ............. 212
来源：http://dali.wangdashe.top/Article/details/gtbfmpkcsa.html

Ruby ........... 212
来源：http://dali.havefunace.top/Article/details/gttimhocbu.html

C# ............. 212
来源：http://dali.chenjidiqi.icu/Article/details/gtlmtyvdmr.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gtpevetcyo.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gtjgiuuniv.html

SQL ............ 90
来源：http://dali.9152youxi.cn/Article/details/gtnrfxfuhn.html

Bash ........... 80
来源：http://dali.yuanzhike.top/Article/details/gtqhkqsmdj.html

Kotlin ......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpismdgg.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gthphukezz.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gtkneeyegs.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtvjwlinzi.html

Scala .......... 10
来源：http://dali.sweek.top/Article/details/gtzlcpbdnt.html

------------------------------------
来源：http://dali.ivvv.top/Article/details/gtbvlddfen.html

合计 ........... 2106 条
来源：http://dali.316326.xyz/Article/details/gtqtgibeoz.html

按章节统计：
来源：http://dali.pengpengdd.cyou/Article/details/gtoczzssby.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuwmdkkl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtfninqqki.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtjjafsmmm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtdzmyjoxl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.andypj.xyz/Article/details/gtmiqxyfuj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtevqnspao.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gtdqofotun.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cqqwz.cn/Article/details/gtfabiurhi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtmvpwbfsb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tanke756.top/Article/details/gtillgjdst.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj20258.top/Article/details/gtvzogqhiq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtiygkoyjr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtkcwlbzxn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtxheudjjy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtbhobhapi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtjwujysny.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvrdsfvc.html

R Bash 专题                             80
来源：http://dali.fzhhl.top/Article/details/gtdmeevdgo.html

S C / C++ 专题                          60
来源：http://dali.bjfxy.top/Article/details/gtrutuscoa.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gtgraemlnm.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gtvucptjzx.html

------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtgdrfsisl.html

合计                                  2106 条
来源：http://dali.daxiang520.top/Article/details/gtnfsgstls.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtsohrppft.html

使用提醒
来源：http://dali.aizwys.cn/Article/details/gtftukhmxu.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtdtakehcr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hysaishi.cn/Article/details/gtjckyywhf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yj20258888.top/Article/details/gtgqnfrlld.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shzxlz.cn/Article/details/gtenoixduy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ivvv.top/Article/details/gtnafoytca.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hywenlv.cn/Article/details/gtpkskqzvh.html

—— 文件结束 ——
来源：http://dali.redwolf501.top/Article/details/gtwvtowtnc.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtusefypie.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigufen.top/Article/details/gtcuhnqash.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gtbgxerrix.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmzpvdbhg.html

【收录内容】
来源：http://dali.daria6918.cn/Article/details/gtixyqmwer.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuetiantiany.cn/Article/details/gtgtjpifix.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jianghu66.top/Article/details/gtlnegkpxc.html

SQL · Bash · C · C++
来源：http://dali.yj20258888.top/Article/details/gtejqrjffg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ydzc1.top/Article/details/gtxbftmgsk.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gtaboyziag.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.birdmap.top/Article/details/gtcxyndoss.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yuxming.cn/Article/details/gtudnjslpe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtaarlgyun.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.iojbl.cn/Article/details/gtcyqknxor.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.pengpengdd.cyou/Article/details/gtzvgmbisd.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangtech.top/Article/details/gtptbtkplq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtppdkwxhe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.birdmap.top/Article/details/gtbeehktsq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ybcxt.top/Article/details/gtypmyqiel.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xziqi.cn/Article/details/gtoppjqtzx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.vqdsnc.cn/Article/details/gtmeepbfaj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.shangyingyoupin.top/Article/details/gtvtznwidr.html

【文件统计】
来源：http://dali.xziqi.cn/Article/details/gtkntldqxx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yj20258.top/Article/details/gteolpdyat.html

--------------------------------------------------------------------------------
来源：http://dali.316326.xyz/Article/details/gtcrvosqhy.html

目  录
来源：http://dali.tianlin.xyz/Article/details/gtbbxktzgn.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgpbwrei.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangshuangyany.cn/Article/details/gttbyinnev.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.daxiang520.top/Article/details/gteckissqi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yangfankeji.com/Article/details/gtzrwgagua.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtpvawvgvz.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtelpcxyjj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xuanzx.com/Article/details/gttzeqfswh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtvemyntzf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzbrgijm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtubuxtmnh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtfmieolav.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ydzc1.top/Article/details/gtupifdfeg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtvqzmriow.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtakiwabag.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtkogvzorh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gtyyabmyev.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtmzmlngyx.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gtdnolzcdo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtptararxr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jyoumei.cn/Article/details/gtuzrkcmks.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtjytfscuu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gthyuqaiwy.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtynxqcony.html

A. 基础语法与类型
来源：http://dali.yj20258888.top/Article/details/gtklsntrby.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtoqdnnogr.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gtijzmogov.html

Py:   print("Hello, World!")
来源：http://dali.cucudq.cn/Article/details/gtudgfagzd.html

PHP:  echo "Hello, World!";
来源：http://dali.jiagoushi.top/Article/details/gtmytncxpn.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtwwkdzzea.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gtbqvpfabn.html

Java: System.out.println("Hello, World!");
来源：http://dali.sysykeji.top/Article/details/gtmooqwirr.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gzhubu.top/Article/details/gtcemlkqfv.html

Ruby: puts "Hello, World!"
来源：http://dali.xziqi.cn/Article/details/gthrhirdju.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtwoqptsnn.html

[A02] 变量声明与赋值
来源：http://dali.fengsongda.top/Article/details/gtnqyjmafg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.mhx1999.top/Article/details/gtnzyuvvzf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hnqzz.top/Article/details/gtzfgwaxbr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtdujriqlm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.iojbl.cn/Article/details/gtmoiqfndi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtpqmpyspy.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangshuangyany.cn/Article/details/gtzkfdxvhl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinghuilouyu.cn/Article/details/gtexgkwhcr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtpxkqvdmq.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gtjpkmpglv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ydzc1.top/Article/details/gtcfzxmpbu.html

PHP:  const PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvjderad.html

JS:   const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtzbidoztm.html

TS:   const PI: number = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtvxzsluqj.html

Java: static final double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtjwzltncp.html

Go:   const PI = 3.14159
来源：http://dali.tianlin.xyz/Article/details/gtdosbygsp.html

Ruby: PI = 3.14159
来源：http://dali.zhengqikj.top/Article/details/gtbtqunkgk.html

C#:   const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gteitptigc.html

[A04] 判断变量类型
来源：http://dali.jinqigufen.top/Article/details/gthxjcgxlq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xinyue.icu/Article/details/gtczadzszu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtvqlmuqsm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtvlshzyjj.html

TS:   typeof x; x instanceof Date
来源：http://dali.hongshengwenyu.top/Article/details/gtuvhfagjn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.kuanghao11.cn/Article/details/gtibmerirm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.snrcjt.cn/Article/details/gthloyoisl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.tanke756.top/Article/details/gtupgecqiz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhengqikj.top/Article/details/gtewxvezxj.html

[A05] 整数除法与取模
来源：http://dali.wangshuangyany.cn/Article/details/gtxthqupav.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.bjfxy.top/Article/details/gthfjfpwim.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtrsfhrznh.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtrxxetfvu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtigvrtbru.html

Java: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtyejsbwwi.html

Go:   7 / 2; 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtrcgityiy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtlgubrkzy.html

C#:   7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtrnnnxvsb.html

[A06] 字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtsuzzwctp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhongyouzk.top/Article/details/gtbftpdopd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shuidangran.top/Article/details/gtzjotkrls.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtrfxsnwnv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.andypj.xyz/Article/details/gthfmqqcaa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrwijjyk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gogol.net.cn/Article/details/gtnwehxoql.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtwwwlsfqo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqocxldj.html

[A07] 数字转字符串
来源：http://dali.dianchejie.cn/Article/details/gtsddslndk.html

Py:   str(42)
来源：http://dali.jqgfzy.top/Article/details/gtygmmsoro.html

PHP:  (string) 42; strval(42)
来源：http://dali.hfpthk.cn/Article/details/gtmlffyppn.html

JS:   String(42); (42).toString()
来源：http://dali.yangfankeji.com/Article/details/gtjenswurf.html

TS:   String(42)
来源：http://dali.shzxlz.cn/Article/details/gteqrwlddi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zycfv.cn/Article/details/gtryjxmglc.html

Go:   strconv.Itoa(42)
来源：http://dali.gzhubu.top/Article/details/gteofkvvfl.html

Ruby: 42.to_s
来源：http://dali.cashguo.top/Article/details/gthhctheee.html

C#:   42.ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsntgzcn.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwzgrlzi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtsbnltapi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ydzc1.top/Article/details/gtjddqcxqu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtskrzuclc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hysaishi.cn/Article/details/gthmcbuqsd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.iojbl.cn/Article/details/gtzpyqdxdo.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gturjalgje.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gtlgdojfti.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtmklpbppa.html

[A09] 绝对值与最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtwoiuloeu.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufolfhhd.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtojzinzcj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzavjwtif.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtmbccyqua.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlxjayylz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xuetiantiany.cn/Article/details/gtensrqlsx.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhengqikj.top/Article/details/gthwxdsvep.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtvghyetsp.html

[A10] 生成随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgezpiyu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.fengsongda.top/Article/details/gtjwojyzml.html

PHP:  random_int(1, 100);
来源：http://dali.havefunace.top/Article/details/gthwehggqx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyttmmxim.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtsuystyad.html

Java: new Random().nextInt(100) + 1
来源：http://dali.fzhhl.top/Article/details/gtselstjjt.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gtftsrgzmt.html

Ruby: rand(1..100)
来源：http://dali.nanxuanxn.top/Article/details/gtsiajsdbl.html

C#:   new Random().Next(1, 101)
来源：http://dali.jiagoushi.top/Article/details/gtcttxopxb.html

[A11] 条件表达式（三元）
来源：http://dali.dianchejie.cn/Article/details/gtpanfsfmi.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.wangdashe.top/Article/details/gtdjonsvgq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtmopkxfzp.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtwihizndj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.316326.xyz/Article/details/gtbbbzpphg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtkuxsacbq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.dashuyun.cn/Article/details/gtfwddsbjl.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtxndxgpyh.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtzfgaircr.html

[A12] 字符串插值 / 格式化
来源：http://dali.gzhubu.top/Article/details/gttpidprty.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.snrcjt.cn/Article/details/gtxuvxxsmh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gtwplkesud.html

JS:   `Hello, ${name}!`
来源：http://dali.andypj.xyz/Article/details/gtgciseefn.html

TS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejycgdfk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenlongwang.top/Article/details/gtsdjuakws.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hammf.cn/Article/details/gtjfsfeabj.html

Ruby: "Hello, #{name}!"
来源：http://dali.shangyingyoupin.top/Article/details/gtiarzbrdf.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gtaxdbhdqa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yonumen.top/Article/details/gthsbwnlcg.html

Py:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtwamkmzng.html

PHP:  "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtdbcwzjww.html

JS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtqmaprfir.html

TS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtetkxobip.html

Java: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtpdiihcgm.html

Go:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtzefqfisr.html

Ruby: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gthkyzciuz.html

C#:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrzwjdvd.html

[A14] 注释写法
来源：http://dali.svipenyu.cn/Article/details/gtuvdsfdcl.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.chenlongwang.top/Article/details/gtahqnxxoc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtvwadcmxt.html

JS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtcjcdebpo.html

TS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtuozfuzse.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.meibo888.top/Article/details/gteeaiegxg.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gturmeqppb.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhoulong.xyz/Article/details/gtmxbvrpzk.html

C#:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtkaylizaq.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gtwxbngulu.html

Py:   value = data or "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gtsitkpqgs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.nwbrower.top/Article/details/gtdziyvgbl.html

JS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtqqsiqwzf.html

TS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtseykkpue.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cheryme.top/Article/details/gtwumubrgz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.c1oappe.top/Article/details/gtvelhjvjo.html

Ruby: value = data || "默认值"
来源：http://dali.xziqi.cn/Article/details/gtifvthdyz.html

C#:   var value = data ?? "默认值";
来源：http://dali.meibo888.top/Article/details/gtmzdlmxhb.html

[A16] 真假值判断规则
来源：http://dali.pengpengdd.cyou/Article/details/gtplkkmico.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkogexzgw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jiagoushi.top/Article/details/gtdsmvxrqc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yonumen.top/Article/details/gtmupykzmd.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gtuxqwgnsl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aibaodan.cn/Article/details/gteyjfooxx.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cashguo.top/Article/details/gtqwzqkdzy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gtejimenye.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtkkqjtgok.html

[A17] 位运算
来源：http://dali.sufxvd.cn/Article/details/gtahyrgsfk.html


<!-- 参考信息 -->