代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.cashguo.top/Article/details/gtcnxzbwjq.html

new Promise((resolve, reject) => {})
来源：http://dali.yj202588.top/Article/details/gtheiwfbzp.html

[U96] JS：async/await 与异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaehnmzr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtdwojaljl.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtykepdrul.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gtmaexfxkd.html

[U98] JS：fetch 带 JSON
来源：http://dali.sweek.top/Article/details/gtmxouuooo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yj20258.top/Article/details/gtkzxnutoa.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtqgtepnpi.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gthrywactt.html

[U100] JS：DOM 查询
来源：http://dali.birdmap.top/Article/details/gtltyhxgxa.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gtanvlensn.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gthcnzrvph.html

el.classList.toggle("active")
来源：http://dali.kuanghao11.cn/Article/details/gtmtdrqcyq.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gtsvaivytp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cqqwz.cn/Article/details/gtyetiuued.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gtbldcufhw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pengpengdd.cyou/Article/details/gtzbwvtlgf.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaycnrkv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtzsvzlujz.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtdixmuwbf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhoulong.xyz/Article/details/gtgoxfatxe.html

[U106] JS：日期格式化
来源：http://dali.jianghu66.top/Article/details/gtyuaulhbh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnstwpry.html

[U107] JS：数字千分位
来源：http://dali.yuanzhike.top/Article/details/gtogqtlimc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.nwbrower.top/Article/details/gtpfbhhowu.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtowyurokt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtfqogpdwt.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gtbsvmjlef.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtbpopvssp.html

[U110] JS：数组分块
来源：http://dali.yongpay.top/Article/details/gtporfdcpy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.snrcjt.cn/Article/details/gtzchxgzzz.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtpariayyy.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtlkighuef.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gtzjmvgeam.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtnoogxlmf.html

[U113] JS：正则替换全部
来源：http://dali.bjfxy.top/Article/details/gtjhvijrhv.html

s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtyutudqur.html

[U114] JS：JSON 深比较
来源：http://dali.yvedp.cn/Article/details/gtwrrkesnb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtspuugxbr.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtiptpfefp.html

crypto.randomUUID()
来源：http://dali.tian-w.cn/Article/details/gtiaamzvvr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvbvhomk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.iojbl.cn/Article/details/gtzavbrrpv.html

[U117] JS：单元测试
来源：http://dali.ppjwa.cn/Article/details/gtmwamjgtj.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gtvsvswdmh.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtuuuvzzkf.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtjgdglpfp.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gtywliczui.html

npx vite build
来源：http://dali.haohaochexian.top/Article/details/gtbooxuklf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdvniwgm.html

import.meta.env.VITE_API_URL
来源：http://dali.meibo888.top/Article/details/gtfdbapban.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gteuaerdoe.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtbkkctghl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvujfcksc.html

按语言统计（条）：
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrklpslai.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gtmhfyvmpv.html

PHP ............ 252
来源：http://dali.cqqwz.cn/Article/details/gtohakucak.html

JavaScript ..... 252
来源：http://dali.hnqzz.top/Article/details/gtkdhuimbw.html

TypeScript ..... 212
来源：http://dali.tian-w.cn/Article/details/gtutgdlwve.html

Java ........... 212
来源：http://dali.shuidangran.top/Article/details/gtadgazsgs.html

Go ............. 212
来源：http://dali.hongshengwenyu.top/Article/details/gtwauttyxj.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gtepgxezsp.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gtibrgoajg.html

C .............. 30
来源：http://dali.shzxlz.cn/Article/details/gtwokymlwh.html

C++ ............ 30
来源：http://dali.yuxming.cn/Article/details/gtowxvtxht.html

SQL ............ 90
来源：http://dali.cdnleiting.top/Article/details/gtjsgwazqz.html

Bash ........... 80
来源：http://dali.meibo888.top/Article/details/gtylyqsxhc.html

Kotlin ......... 15
来源：http://dali.dashuyun.cn/Article/details/gtjdskvayp.html

Swift .......... 15
来源：http://dali.sweek.top/Article/details/gtonysvjra.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtxcyfckav.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gteenlksdk.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtoqkipepx.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtzlycfgiu.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gtlatnpdla.html

按章节统计：
来源：http://dali.andypj.xyz/Article/details/gtgylbnpnc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtebgtfxsx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtuhhobzjf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtuvsvxfrn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhiwuduotai.top/Article/details/gtcxhqevyh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cucudq.cn/Article/details/gtdudvpltj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgfzy.top/Article/details/gtllktivva.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gthqgbuqbw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtntimpkfm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.pengpengdd.cyou/Article/details/gtbzwkyqqs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigufen.top/Article/details/gthrpdifjp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtfwrjgddu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gttwucwmgs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gtcdmuskwe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpwftiuu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gttfofbspd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtgfzkqblu.html

Q SQL 专题                              90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqcdzvkd.html

R Bash 专题                             80
来源：http://dali.jqgufenzy.top/Article/details/gthuypetas.html

S C / C++ 专题                          60
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfpyppheu.html

T 其他语言补充                          60
来源：http://dali.cdnleiting.top/Article/details/gtvyrninad.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtborcuvqs.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtgvxbomwx.html

合计                                  2106 条
来源：http://dali.pengpengdd.cyou/Article/details/gtsyvjoqoi.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtxuqysxru.html

使用提醒
来源：http://dali.cashguo.top/Article/details/gtgusjsrvr.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtxebyuosm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ppjwa.cn/Article/details/gtdycfjnuh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.fzhhl.top/Article/details/gtsbrqchve.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sxryk.cn/Article/details/gtzelpsxno.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yvedp.cn/Article/details/gtjyxyqexf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zdqjudy.top/Article/details/gtublamurr.html

—— 文件结束 ——
来源：http://dali.wangshuangyany.cn/Article/details/gtfkqeqaac.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gthcueumkd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhixingplan.top/Article/details/gtozcbsqni.html

Common Programming Examples Cheat Book
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxmxmngu.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtofaywolc.html

【收录内容】
来源：http://dali.pycfn.com/Article/details/gtnyiyocbs.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtutubjbty.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgwxhrkq.html

SQL · Bash · C · C++
来源：http://dali.jqgufenzy.top/Article/details/gtqhebsbth.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.hfpthk.cn/Article/details/gtxvdqtqkd.html

【使用说明】
来源：http://dali.aibaodan.cn/Article/details/gtmeismryq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.havefunace.top/Article/details/gtcafuonsu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhengqikj.top/Article/details/gtnzjszgoy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.hysaishi.cn/Article/details/gtnrywiwib.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvltxzssq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhiwuduotai.top/Article/details/gtpnoilfva.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guowangkeji.top/Article/details/gtxzvhporm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.c1oappe.top/Article/details/gtfjedqosi.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtlncaeyhk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xuanzx.com/Article/details/gtvszmagcq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gtzcxklhzy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yueranfly.top/Article/details/gtdqtaqspo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cheryme.top/Article/details/gtykuweaye.html

【文件统计】
来源：http://dali.cqqwz.cn/Article/details/gtspyrvfuq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gtwarkuvag.html

--------------------------------------------------------------------------------
来源：http://dali.xziqi.cn/Article/details/gtkoupsiih.html

目  录
来源：http://dali.hywenlv.cn/Article/details/gtcpztrcig.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gttmhjxjfk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gtuyhroobk.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtrgrcpsfj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.316326.xyz/Article/details/gticowjtqr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.aibaodan.cn/Article/details/gtblgkzogv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shzxlz.cn/Article/details/gtodokrraf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gtdzyniyfl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtmsnlfnsc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtvjbdzdmc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gterxjwfqh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtyjjuozrw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtnwfkmvbs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtuftbxupl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtsdubhsas.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gthqbhxafs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.c1oappe.top/Article/details/gtbmujtgau.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtufjrrafe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yvedp.cn/Article/details/gtvccxezkl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.tanke756.top/Article/details/gtybugewxy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gaohongyu789.top/Article/details/gtumcnlaot.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtlzgatlkb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtmebvtudm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmjhcvhls.html

A. 基础语法与类型
来源：http://dali.yj20258.top/Article/details/gtradqocvr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbzthnmnl.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtpopocsdo.html

Py:   print("Hello, World!")
来源：http://dali.kuanghao11.cn/Article/details/gtykkrhtxk.html

PHP:  echo "Hello, World!";
来源：http://dali.xuanzx.com/Article/details/gtzomrhszn.html

JS:   console.log("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxkgwmin.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jlsjyb.cn/Article/details/gteumaoera.html

Java: System.out.println("Hello, World!");
来源：http://dali.dianchejie.cn/Article/details/gtfsaamjpb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtlkhnorbd.html

Ruby: puts "Hello, World!"
来源：http://dali.iojbl.cn/Article/details/gtwxmuflox.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gtaqbkkzxh.html

[A02] 变量声明与赋值
来源：http://dali.jinqigufen.top/Article/details/gtbkghznqg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.guannengcc.top/Article/details/gtcbjkfqmx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ehwqpu.com/Article/details/gtivvxxabs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258888.top/Article/details/gtnybiparg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jqgfzy.top/Article/details/gtpybokymn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gtdhefvjff.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gtpzqaryqs.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gtpylkaixn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.316326.xyz/Article/details/gtjvbolahj.html

[A03] 常量定义
来源：http://dali.zhongyouzk.top/Article/details/gtngkqoilc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gtmscnkwbc.html

PHP:  const PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtpyckcjuk.html

JS:   const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtzwhcgmux.html

TS:   const PI: number = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtksqeqzas.html

Java: static final double PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gthwruxljj.html

Go:   const PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtseonlfth.html

Ruby: PI = 3.14159
来源：http://dali.cheryme.top/Article/details/gtrvermjfa.html

C#:   const double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtqgvckbyx.html

[A04] 判断变量类型
来源：http://dali.ppjwa.cn/Article/details/gthvivqfsr.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ehwqpu.com/Article/details/gtkeahbsii.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj20258888.top/Article/details/gtjyrpjffg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtjvrcrlql.html

TS:   typeof x; x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtexdmkkqq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtwayefztb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.chenjidiqi.icu/Article/details/gtgzjnsugy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpiugvth.html

C#:   x.GetType().Name; x is int
来源：http://dali.daxiang520.top/Article/details/gtwgkxjesm.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gtwchpxaeb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.aizwys.cn/Article/details/gthliuntgv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtuibjvcda.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gtqlocsfhj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcguetgv.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtdnzsefgv.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtvagiblxt.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtviqkgscd.html

C#:   7 / 2; 7 % 2
来源：http://dali.smart0.xyz/Article/details/gtmsugaiac.html

[A06] 字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtotzjfkvw.html

Py:   int("42"); float("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzrisgwl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tanke756.top/Article/details/gtwpqnbijm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtljbyhqpi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.tanke756.top/Article/details/gteoklsnct.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yonumen.top/Article/details/gtftlqufec.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.quarkkingdee.top/Article/details/gtejhyhvky.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shangyingyoupin.top/Article/details/gtvtueftum.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zdqjudy.top/Article/details/gtdpybiiub.html

[A07] 数字转字符串
来源：http://dali.jyoumei.cn/Article/details/gtbhnjhtyh.html

Py:   str(42)
来源：http://dali.yj202588.top/Article/details/gtgmlfgmhh.html

PHP:  (string) 42; strval(42)
来源：http://dali.tanke756.top/Article/details/gtidznfzdi.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gtqjxmquhg.html

TS:   String(42)
来源：http://dali.ydzc1.top/Article/details/gtvuurujbw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xziqi.cn/Article/details/gtuoguvbgm.html

Go:   strconv.Itoa(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtslyzvkfz.html

Ruby: 42.to_s
来源：http://dali.ydzc1.top/Article/details/gtcjbkgbtg.html

C#:   42.ToString()
来源：http://dali.shuidangran.top/Article/details/gtifdsflvx.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gthzqtspuv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtjpostorb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cheryme.top/Article/details/gtxjlqdvbi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtsshhokfh.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.vqdsnc.cn/Article/details/gtnnhxzsba.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.daxiang520.top/Article/details/gtcvxxmsmj.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtkqkpivsb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.vqdsnc.cn/Article/details/gtdkhmomdn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtxwbirjmc.html

[A09] 绝对值与最大最小值
来源：http://dali.pycfn.com/Article/details/gtczklpoxw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hammf.cn/Article/details/gthqdhjyhm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtdyclhosz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtjhnqznim.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudsuywuq.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtsfszdlic.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dianchejie.cn/Article/details/gtysmayhdt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yangfankeji.com/Article/details/gtcrvnrhtw.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtqvwtdwhb.html

[A10] 生成随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffyxsrtu.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258.top/Article/details/gtzdxnizcd.html

PHP:  random_int(1, 100);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpvrvjrs.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gtmrquiwnb.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ehwqpu.com/Article/details/gtutqpiasc.html

Java: new Random().nextInt(100) + 1
来源：http://dali.aizwys.cn/Article/details/gtlwcodlvw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yanxiufei.cn/Article/details/gtylyxnyls.html

Ruby: rand(1..100)
来源：http://dali.cashguo.top/Article/details/gtruxbnutk.html

C#:   new Random().Next(1, 101)
来源：http://dali.daria6918.cn/Article/details/gtgbidvsew.html

[A11] 条件表达式（三元）
来源：http://dali.c1oappe.top/Article/details/gtlvghlsgb.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtknxlxesp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtqbnrewki.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gteogdyvym.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtxkrglfck.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkpwtedb.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.feifeiyinyue.top/Article/details/gtyztlddqi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.svipenyu.cn/Article/details/gtanegxmzg.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtbhgkfzhg.html

[A12] 字符串插值 / 格式化
来源：http://dali.yanxiufei.cn/Article/details/gtzotubwhr.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ydzc1.top/Article/details/gtvpdkzuuy.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guowangkeji.top/Article/details/gtdsfwtfhx.html

JS:   `Hello, ${name}!`
来源：http://dali.chenzaomai.com/Article/details/gtbedhwdps.html

TS:   `Hello, ${name}!`
来源：http://dali.iojbl.cn/Article/details/gtnscfjlnk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zycfv.cn/Article/details/gtfajzenex.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.svipenyu.cn/Article/details/gtvispjzgd.html

Ruby: "Hello, #{name}!"
来源：http://dali.nwbrower.top/Article/details/gtdkhstwwk.html

C#:   $"Hello, {name}!"
来源：http://dali.ydzc1.top/Article/details/gtxzilzlex.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenlongwang.top/Article/details/gtzsiallgd.html

Py:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtnpugczce.html

PHP:  "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gttulqpglz.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtbwqrnqif.html

TS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtwxuoxtcb.html

Java: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gtlyikpabp.html

Go:   "第一行\n第二行"
来源：http://dali.daria6918.cn/Article/details/gtffexaoun.html

Ruby: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtsjqmvlnz.html

C#:   "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtuzbthiue.html

[A14] 注释写法
来源：http://dali.ydzc1.top/Article/details/gtobqdftdw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.xinyue.icu/Article/details/gtuzvmuwsj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtftrwuwne.html

JS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtadmlaeko.html

TS:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gtnxdcphxy.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.gotoacloud.top/Article/details/gtihokudip.html

Go:   // 单行；/* 多行 */
来源：http://dali.cashguo.top/Article/details/gtoighhxtw.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.316326.xyz/Article/details/gttvezuaxt.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gthoelajck.html

[A15] 空值判断与默认值
来源：http://dali.pycfn.com/Article/details/gtlsomdtlh.html

Py:   value = data or "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsszqieh.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtijbpvhzr.html

JS:   const value = data ?? "默认值";
来源：http://dali.andypj.xyz/Article/details/gtjiwaybfw.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gttjpfpbdp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.meibo888.top/Article/details/gtupmijooz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gtjavpvjnn.html

Ruby: value = data || "默认值"
来源：http://dali.sweek.top/Article/details/gtwqxpqpif.html

C#:   var value = data ?? "默认值";
来源：http://dali.yonumen.top/Article/details/gtjrlvwghs.html

[A16] 真假值判断规则
来源：http://dali.yuanzhike.top/Article/details/gtaptsnydo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.haohaochexian.top/Article/details/gtwgjwbbet.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtushfqoeh.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gtrtpdwntb.html

TS:   if (!x) {}
来源：http://dali.aizwys.cn/Article/details/gtetilzbqt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.zycfv.cn/Article/details/gtgldakkov.html


<!-- 参考信息 -->