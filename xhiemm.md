代发 wailian999

[U93] JS：模板字符串
来源：http://dali.vqdsnc.cn/Article/details/gtyymnjzgn.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gtzitdzvee.html

[U94] JS：箭头函数
来源：http://dali.hammf.cn/Article/details/gtvglhowaq.html

const double = x => x * 2;
来源：http://dali.meibo888.top/Article/details/gttjszdpks.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtpdojoxye.html

new Promise((resolve, reject) => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtpmuulsij.html

[U96] JS：async/await 与异常
来源：http://dali.haohaochexian.top/Article/details/gtxtiyxfvq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtohgjaegf.html

[U97] JS：并发请求
来源：http://dali.yonumen.top/Article/details/gtduzzmnfy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.haohaochexian.top/Article/details/gtkxlyvovy.html

[U98] JS：fetch 带 JSON
来源：http://dali.cdnleiting.top/Article/details/gtugrbtjbd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtptcoesov.html

[U99] JS：事件监听
来源：http://dali.zycfv.cn/Article/details/gtctyshsre.html

el.addEventListener("click", e => {})
来源：http://dali.sufxvd.cn/Article/details/gtzqbggeaz.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtgjxnxveg.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtqgezxbzo.html

[U101] JS：classList 操作
来源：http://dali.shzxlz.cn/Article/details/gtlwlwwkrg.html

el.classList.toggle("active")
来源：http://dali.havefunace.top/Article/details/gtyhwqozjw.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gtmzhgvnko.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nwbrower.top/Article/details/gtdolswwmi.html

[U103] JS：定时器
来源：http://dali.nanxinkj.top/Article/details/gtmirluemg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tianlin.xyz/Article/details/gtqjeoiryq.html

[U104] JS：防抖
来源：http://dali.hfpthk.cn/Article/details/gtffhqkjqk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gtvuvjniqo.html

[U105] JS：节流
来源：http://dali.zhoulong.xyz/Article/details/gtiwfpbbdo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gtznvxphuk.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtyiqhjwjx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gtnzzuujln.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtnfbdlpgf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gtmhxylywi.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gtfkaktalb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sysykeji.top/Article/details/gtvoouekey.html

[U109] JS：数组分组
来源：http://dali.hongshengwenyu.top/Article/details/gtesvgkvmb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gthxgjsspb.html

[U110] JS：数组分块
来源：http://dali.ehwqpu.com/Article/details/gtcvxrtlcl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtihybpcfs.html

[U111] JS：对象转 Map
来源：http://dali.bjfxy.top/Article/details/gtoevtlazi.html

new Map(Object.entries(obj))
来源：http://dali.ppjwa.cn/Article/details/gtkgvaaebw.html

[U112] JS：字符串补位
来源：http://dali.cqqwz.cn/Article/details/gtqkijcjdh.html

"7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtnzldxgth.html

[U113] JS：正则替换全部
来源：http://dali.yongpay.top/Article/details/gtdfldeioq.html

s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydgffeji.html

[U114] JS：JSON 深比较
来源：http://dali.pengpengdd.cyou/Article/details/gtbvhgkdak.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtohocuksj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtazzxqslm.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuafvavm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gtatytpoxm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nwbrower.top/Article/details/gtctrmpbga.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtvefuhlao.html

npm i -D vitest;  npx vitest
来源：http://dali.hammf.cn/Article/details/gthfhorfkb.html

[U118] JS：开发服务器
来源：http://dali.daxiang520.top/Article/details/gttbgggpqx.html

npm i -D vite;  npx vite
来源：http://dali.xuanzx.com/Article/details/gtgprlfxcz.html

[U119] JS：生产构建
来源：http://dali.zhengqikj.top/Article/details/gtsujjdotu.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtcahanpzf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.9152youxi.cn/Article/details/gtmcmswfkt.html

import.meta.env.VITE_API_URL
来源：http://dali.gaohongyu789.top/Article/details/gtlvigognn.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcyywurkw.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gtiviifnpl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gttnuqxmaq.html

按语言统计（条）：
来源：http://dali.jqgufenzy.top/Article/details/gtaoxavvwx.html

Python ......... 252
来源：http://dali.fengsongda.top/Article/details/gtgthqknba.html

PHP ............ 252
来源：http://dali.vqdsnc.cn/Article/details/gtpwtgbckc.html

JavaScript ..... 252
来源：http://dali.cucudq.cn/Article/details/gtixexuqof.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gtladwytkp.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtwvarphzq.html

Go ............. 212
来源：http://dali.tanke756.top/Article/details/gtthzwxjvr.html

Ruby ........... 212
来源：http://dali.zhoulong.xyz/Article/details/gtoyvnicrv.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gtuflyuvtj.html

C .............. 30
来源：http://dali.0kj1m.cn/Article/details/gtlbupzzcj.html

C++ ............ 30
来源：http://dali.ydzc1.top/Article/details/gtplmckoxc.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gtkjzrdivx.html

Bash ........... 80
来源：http://dali.chenlongwang.top/Article/details/gtdwmjtokk.html

Kotlin ......... 15
来源：http://dali.9152youxi.cn/Article/details/gtkvqnqdsf.html

Swift .......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtrpkmjjzw.html

Lua ............ 10
来源：http://dali.shangyingyoupin.top/Article/details/gtptvoglfv.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtbratohmp.html

Scala .......... 10
来源：http://dali.yanxiufei.cn/Article/details/gtebooukvj.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtcfgjihai.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtbgtejtda.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gtkdsaitxb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtsgugwixn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtumhftmnq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtpnrxlmdu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gtwyvnkrml.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxsufger.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtqvopzkfc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gtnukcnitd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jyoumei.cn/Article/details/gtemlnwlou.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtufjppcng.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtzptrddog.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtmktxntfz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtwhyudoos.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtqacxeiis.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gtiinfhojs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gtfpnpopcx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtvgqvimfq.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gtvishmtpg.html

R Bash 专题                             80
来源：http://dali.hammf.cn/Article/details/gtrhuiznna.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtmtuxuwox.html

T 其他语言补充                          60
来源：http://dali.jqgufenzy.top/Article/details/gtzfkwqjcv.html

U 高频实用片段                         120
来源：http://dali.ehwqpu.com/Article/details/gtakwieptv.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtxxvkxlku.html

合计                                  2106 条
来源：http://dali.guannengcc.top/Article/details/gtfsncsupa.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtmqyjgtcr.html

使用提醒
来源：http://dali.zhoulong.xyz/Article/details/gtgdlaikag.html

--------------------------------------------------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gthcralvji.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gtmezyavmx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.cucudq.cn/Article/details/gtrkdjjzbq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cheryme.top/Article/details/gtwelhyzyl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gtrpnbmcyj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwvaclyf.html

—— 文件结束 ——
来源：http://dali.chenjidiqi.icu/Article/details/gtylnwqpzj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtshaqzgra.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ybcxt.top/Article/details/gtxlaxsjlr.html

Common Programming Examples Cheat Book
来源：http://dali.ydzc1.top/Article/details/gtklpxvjjg.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtaqyhiwfk.html

【收录内容】
来源：http://dali.gaohongyu789.top/Article/details/gtdnsgwjow.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shangyingyoupin.top/Article/details/gtjesyuodf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.bjfxy.top/Article/details/gtvgqiupoc.html

SQL · Bash · C · C++
来源：http://dali.jinqigfzy.top/Article/details/gtqocijlmr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.aizwys.cn/Article/details/gtmjauuszy.html

【使用说明】
来源：http://dali.xuanzx.com/Article/details/gtdhdazdlb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtdozfodqn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.feifeiyinyue.top/Article/details/gttmthimxp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.xuanzx.com/Article/details/gtvxzgdqhi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gthdkkhjuk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jinqigufen.top/Article/details/gtnewslrwy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.wangshuangyany.cn/Article/details/gtqwcmvnsf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.sysykeji.top/Article/details/gtklrfqjne.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fzhhl.top/Article/details/gtdmeclnia.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gtgzlmydbd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.tianlin.xyz/Article/details/gtrllhzdwp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.yanxiufei.cn/Article/details/gtkqwwdang.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.pycfn.com/Article/details/gtkudmnrcz.html

【文件统计】
来源：http://dali.shuidangran.top/Article/details/gtmwbbpluq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xylfe.cn/Article/details/gtwpcvjzsb.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtaqlmxtij.html

目  录
来源：http://dali.dashuyun.cn/Article/details/gtklgghveh.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtukyditmw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gttsbnyajj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ivvv.top/Article/details/gtlqceyhjx.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtahdtywmq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gtqybkooku.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtyqsrwjvl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.fzhhl.top/Article/details/gtsqjecidz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtfwuqigkw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtkfqoswwg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtiawkaiop.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtezoeessl.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.haohaochexian.top/Article/details/gtokulqymg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jiagoushi.top/Article/details/gtwrphzohk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtvogcunfy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.vqdsnc.cn/Article/details/gtdinvugjm.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.pycfn.com/Article/details/gtvoudxbxf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtzlukuind.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjamdzwsv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.0kj1m.cn/Article/details/gtyyfwvtmu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.vqdsnc.cn/Article/details/gtiiaefdni.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gtmftcorfo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtzpmndthy.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodpbotsc.html

A. 基础语法与类型
来源：http://dali.zhixingplan.top/Article/details/gteqmnylei.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtftdplphy.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gtzdykofek.html

Py:   print("Hello, World!")
来源：http://dali.dianchejie.cn/Article/details/gtgrrkugfc.html

PHP:  echo "Hello, World!";
来源：http://dali.fzhhl.top/Article/details/gtfqclnskx.html

JS:   console.log("Hello, World!");
来源：http://dali.mhx1999.top/Article/details/gtjisqvsgk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yonumen.top/Article/details/gtkroulyed.html

Java: System.out.println("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gtmlazpjea.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hnqzz.top/Article/details/gtqfbridtg.html

Ruby: puts "Hello, World!"
来源：http://dali.xylfe.cn/Article/details/gtzzalgliu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.gaohongyu789.top/Article/details/gtideyunxd.html

[A02] 变量声明与赋值
来源：http://dali.redwolf501.top/Article/details/gtlrqzphze.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cheryme.top/Article/details/gtrhoegyxi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtwnnylwud.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.birdmap.top/Article/details/gtleieibqy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cheryme.top/Article/details/gtinsjalio.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtxokfzcgq.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtlhliuwsa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.redwolf501.top/Article/details/gtcatgzvbt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gtjjfnmbci.html

[A03] 常量定义
来源：http://dali.pengpengdd.cyou/Article/details/gtnmvhbqml.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yj20258.top/Article/details/gtusyvgazz.html

PHP:  const PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gttbhkrzwa.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtfzdfkurs.html

TS:   const PI: number = 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtgnpbrjvo.html

Java: static final double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtrohtnkey.html

Go:   const PI = 3.14159
来源：http://dali.havefunace.top/Article/details/gtfhrjjedv.html

Ruby: PI = 3.14159
来源：http://dali.aibaodan.cn/Article/details/gtlbdbvxoc.html

C#:   const double PI = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtojxtloeg.html

[A04] 判断变量类型
来源：http://dali.jqgfzy.top/Article/details/gthmkxnsep.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj202588.top/Article/details/gtpodfiuil.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ehwqpu.com/Article/details/gtlgyagosg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtthvmzrsy.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gttwgsmpvc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gtnydjxpsl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.316326.xyz/Article/details/gtmpjfzaca.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtvomymbkz.html

C#:   x.GetType().Name; x is int
来源：http://dali.cdnleiting.top/Article/details/gtkkpgsuik.html

[A05] 整数除法与取模
来源：http://dali.vqdsnc.cn/Article/details/gtxfupchzd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.mhx1999.top/Article/details/gtvgvsrbvw.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtnravwicp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtfeatyoez.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtzadylqlt.html

Java: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtatqmblvn.html

Go:   7 / 2; 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtybwytdix.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gtotqgnmnr.html

C#:   7 / 2; 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtsdxqxvaz.html

[A06] 字符串转数字
来源：http://dali.nwbrower.top/Article/details/gtagzsfyaz.html

Py:   int("42"); float("3.14")
来源：http://dali.redwolf501.top/Article/details/gtutenukjd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.haohaochexian.top/Article/details/gtcstleanp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwfhllsx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.pycfn.com/Article/details/gthuciyzth.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.tanke756.top/Article/details/gtsdtaltyk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.gaohongyu789.top/Article/details/gtfkroiwxh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxinkj.top/Article/details/gtaeqvpgzz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.bjfxy.top/Article/details/gtqxczjrnw.html

[A07] 数字转字符串
来源：http://dali.ppjwa.cn/Article/details/gtwuxmfqgg.html

Py:   str(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtlamyjssh.html

PHP:  (string) 42; strval(42)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfsbmrpx.html

JS:   String(42); (42).toString()
来源：http://dali.hnxiangtu.top/Article/details/gtwcpiohkv.html

TS:   String(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtxzuuusas.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtxfmhqvds.html

Go:   strconv.Itoa(42)
来源：http://dali.gzhubu.top/Article/details/gtgdsgrtrs.html

Ruby: 42.to_s
来源：http://dali.jianghu66.top/Article/details/gthxquobrp.html

C#:   42.ToString()
来源：http://dali.ehwqpu.com/Article/details/gtpdemneib.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gtzvxdqsyq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtamqmrrpg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.feifeiyinyue.top/Article/details/gtoqmedtkk.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtmwmsxygl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xziqi.cn/Article/details/gtdcalqcxy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtnebniwop.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtolsszxwg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hfpthk.cn/Article/details/gtxuslcacv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtmvroptor.html

[A09] 绝对值与最大最小值
来源：http://dali.jyoumei.cn/Article/details/gthyxottdr.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tanke756.top/Article/details/gtpynwzsll.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtcvnyhzmj.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtkugfwrut.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gtqnrowenv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtxvnjvsyq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gtcmnfrjoz.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.meibo888.top/Article/details/gtglcxwdgc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtdqaywxwd.html

[A10] 生成随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtyucxlsrj.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuipvxfss.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gtiyiuvrau.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtsuujdlxt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.9152youxi.cn/Article/details/gtiowlnsqt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.haohaochexian.top/Article/details/gtphndfqst.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinqigfzy.top/Article/details/gtexygzumq.html

Ruby: rand(1..100)
来源：http://dali.dianchejie.cn/Article/details/gtpatslkru.html

C#:   new Random().Next(1, 101)
来源：http://dali.bjfxy.top/Article/details/gtkivxhnzs.html

[A11] 条件表达式（三元）
来源：http://dali.kuanghao11.cn/Article/details/gtubacbkzg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yueranfly.top/Article/details/gtaojypvxr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtolxkmyta.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtogkohthk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfhkyrmwg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtcszamqbh.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.0kj1m.cn/Article/details/gtogtqjzpt.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtrbkhhksb.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtkghqjnpo.html

[A12] 字符串插值 / 格式化
来源：http://dali.guannengcc.top/Article/details/gthtatggfx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gtujwdninh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.sxryk.cn/Article/details/gtrietczwi.html

JS:   `Hello, ${name}!`
来源：http://dali.jiagoushi.top/Article/details/gtybpalhxv.html

TS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gtdgtpunor.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sufxvd.cn/Article/details/gtsbgqzzgg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yuanzhike.top/Article/details/gtdhycqmav.html

Ruby: "Hello, #{name}!"
来源：http://dali.daxiang520.top/Article/details/gtdappjyuj.html

C#:   $"Hello, {name}!"
来源：http://dali.meibo888.top/Article/details/gtwtoaimbh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.feifeiyinyue.top/Article/details/gtaaiggtgm.html

Py:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtnrilhjgd.html

PHP:  "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtqggtuupt.html

JS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gtwzxgzuxb.html

TS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtxjdkjbsi.html

Java: "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtuslghbqb.html

Go:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gtexbrmlha.html

Ruby: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtkbbkbeqi.html

C#:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkvharfw.html

[A14] 注释写法
来源：http://dali.chenlongwang.top/Article/details/gtwevxxefr.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.shangyingyoupin.top/Article/details/gtmoabbqgt.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gthwzllguf.html

JS:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtnwewkrml.html

TS:   // 单行；/* 多行 */
来源：http://dali.haohaochexian.top/Article/details/gtxuxehgzs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgeouojq.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258.top/Article/details/gtjayinsgd.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hfpthk.cn/Article/details/gtzbbinoao.html

C#:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtxmdiedlm.html

[A15] 空值判断与默认值
来源：http://dali.9152youxi.cn/Article/details/gtvfkzsfzr.html

Py:   value = data or "默认值"
来源：http://dali.zhixingplan.top/Article/details/gtlebroqdn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtnnuzbffw.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangshuangyany.cn/Article/details/gtruaatkdq.html

TS:   const value = data ?? "默认值";
来源：http://dali.ehwqpu.com/Article/details/gtxajbphvb.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.c1oappe.top/Article/details/gtbmgbokvq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangdashe.top/Article/details/gtojfxiykk.html

Ruby: value = data || "默认值"
来源：http://dali.cqqwz.cn/Article/details/gtgwlkxnkv.html

C#:   var value = data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gtvmgrxvsq.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gttxjzsssn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cdnleiting.top/Article/details/gtevsibpjd.html


<!-- 参考信息 -->