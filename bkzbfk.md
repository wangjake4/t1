代发 wailian999

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gttnpakvjw.html

a?.b?.c
来源：http://dali.yvedp.cn/Article/details/gtsauzhezn.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtylgdjcmy.html

a ?? b
来源：http://dali.shuidangran.top/Article/details/gtdoaknshg.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gtdsftrebv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nwbrower.top/Article/details/gtshflnliq.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gttnzjsbno.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gtpswiixgd.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtvslnzhfl.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtnfkcwwhp.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtvwvbgkqa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtmnwdeuyb.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gtgmeuytvu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gtdaozghod.html

[U92] JS：深拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtrtqhhaaz.html

structuredClone(obj)
来源：http://dali.yvedp.cn/Article/details/gtyvjqfjww.html

[U93] JS：模板字符串
来源：http://dali.cdnleiting.top/Article/details/gthzmzsuoo.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtggxuhfwd.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtktrrnlkl.html

const double = x => x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gtsdnenobk.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtdmcqdazf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhixingplan.top/Article/details/gtfgchllwu.html

[U96] JS：async/await 与异常
来源：http://dali.xziqi.cn/Article/details/gtsusuytzi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.xinyue.icu/Article/details/gtvqjphwij.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtjmeulnsh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtujzurvxd.html

[U98] JS：fetch 带 JSON
来源：http://dali.haohaochexian.top/Article/details/gtbigrvgoa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqlvxzmk.html

[U99] JS：事件监听
来源：http://dali.bjfxy.top/Article/details/gtpfzhtgga.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gtouznokjf.html

[U100] JS：DOM 查询
来源：http://dali.cashguo.top/Article/details/gthuejcaqx.html

document.querySelector(".item")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenwqhwmj.html

[U101] JS：classList 操作
来源：http://dali.cdnleiting.top/Article/details/gtmphpftox.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gtepiyzjft.html

[U102] JS：本地存储
来源：http://dali.hysaishi.cn/Article/details/gtnulzeads.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtuehecyzs.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gtksygwwrp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gtgejontxp.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtqolfebmr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtzxdfiaiu.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtdxeyjgya.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtgsmdeebp.html

[U106] JS：日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtmbvuyhwl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvswxtaa.html

[U107] JS：数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtmnbccbwq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.mhx1999.top/Article/details/gtkihsqojh.html

[U108] JS：随机整数
来源：http://dali.yj20258888.top/Article/details/gtgixrcxdc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yj202588.top/Article/details/gtgoaqbxpu.html

[U109] JS：数组分组
来源：http://dali.feifeiyinyue.top/Article/details/gthrinukvg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gteiarsuad.html

[U110] JS：数组分块
来源：http://dali.jyoumei.cn/Article/details/gtrzurtmqk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigufen.top/Article/details/gttjejgowf.html

[U111] JS：对象转 Map
来源：http://dali.hnqzz.top/Article/details/gtuzkfrdjf.html

new Map(Object.entries(obj))
来源：http://dali.sysykeji.top/Article/details/gtnqntrocx.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtqqufkkav.html

"7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gtrcyicrta.html

[U113] JS：正则替换全部
来源：http://dali.cdnleiting.top/Article/details/gtmjwwmcte.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gttdgyolnp.html

[U114] JS：JSON 深比较
来源：http://dali.ppjwa.cn/Article/details/gtbzlzzfxr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtdvjohxuj.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtzjnbjqpi.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtdcudkrct.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtlldokpnm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigufen.top/Article/details/gtapmvmmzg.html

[U117] JS：单元测试
来源：http://dali.bjfxy.top/Article/details/gtkessqpds.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigfzy.top/Article/details/gtuhzfhoys.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtmbkahrwf.html

npm i -D vite;  npx vite
来源：http://dali.tian-w.cn/Article/details/gtmniraito.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gtrriglwuo.html

npx vite build
来源：http://dali.gzhubu.top/Article/details/gtgbeptbfv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtwrvtkjgv.html

import.meta.env.VITE_API_URL
来源：http://dali.yanxiufei.cn/Article/details/gtkapyjsne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmuftorqg.html

统计汇总
来源：http://dali.aizwys.cn/Article/details/gthyeynnzw.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthurwvjwd.html

按语言统计（条）：
来源：http://dali.hnxiangtu.top/Article/details/gtknsnhbve.html

Python ......... 252
来源：http://dali.guannengcc.top/Article/details/gtxeqgvrzc.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gtlmdsugxv.html

JavaScript ..... 252
来源：http://dali.guannengcc.top/Article/details/gtpachktyx.html

TypeScript ..... 212
来源：http://dali.redwolf501.top/Article/details/gtyybfppxv.html

Java ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtyspbgqix.html

Go ............. 212
来源：http://dali.hysaishi.cn/Article/details/gtfeaalwsr.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtpllnupee.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtmcugzkxw.html

C .............. 30
来源：http://dali.aibaodan.cn/Article/details/gtnroblsat.html

C++ ............ 30
来源：http://dali.birdmap.top/Article/details/gtpghpkoav.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gtjqctidfu.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtgsavbwkp.html

Kotlin ......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtueicgiyn.html

Swift .......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdjyylor.html

Lua ............ 10
来源：http://dali.sweek.top/Article/details/gtabmlxeea.html

Perl ........... 10
来源：http://dali.chenzaomai.com/Article/details/gthdkowool.html

Scala .......... 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtxivxiyfp.html

------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtbzxnuhom.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gtkznzzbze.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gtawqllyii.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xziqi.cn/Article/details/gtlyccbmnf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtuutexstr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtsidgklwp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yvedp.cn/Article/details/gtpumkaljv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hfpthk.cn/Article/details/gteifkpfxy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nanxuanxn.top/Article/details/gtjreelhnk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtqgxirklo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.andypj.xyz/Article/details/gtnqhgevzg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtaddytrmq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shuidangran.top/Article/details/gtwlgyswdo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtinkmozoe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtvmwwqnjx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtvzmvergk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.ehwqpu.com/Article/details/gtuprzlxil.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yanxiufei.cn/Article/details/gtggofcomn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtzwzuhiat.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtbaxlicoz.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtmlcycspy.html

S C / C++ 专题                          60
来源：http://dali.yanxiufei.cn/Article/details/gtbkjbnblq.html

T 其他语言补充                          60
来源：http://dali.jinghuilouyu.cn/Article/details/gtpecgvxam.html

U 高频实用片段                         120
来源：http://dali.xziqi.cn/Article/details/gtlsbzedpi.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gtfocnptia.html

合计                                  2106 条
来源：http://dali.meibo888.top/Article/details/gtmanrddhy.html

--------------------------------------------------------------------------------
来源：http://dali.birdmap.top/Article/details/gtrtwjvgdx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gtvdbdszjv.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtvfkniirj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.feifeiyinyue.top/Article/details/gtlrcyvcif.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gtdiavkfai.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.316326.xyz/Article/details/gtpzosodva.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.tanke756.top/Article/details/gtcnfpvung.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dianchejie.cn/Article/details/gtgmidxrtz.html

—— 文件结束 ——
来源：http://dali.yueranfly.top/Article/details/gtwrrhqpkr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtasqkfyji.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.feifeiyinyue.top/Article/details/gtateyemky.html

Common Programming Examples Cheat Book
来源：http://dali.shzxlz.cn/Article/details/gtbbptjmdl.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntomiblf.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gtvmswusfr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gtmscbkgbf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.nanxuanxn.top/Article/details/gtxqgeaurz.html

SQL · Bash · C · C++
来源：http://dali.quarkkingdee.top/Article/details/gtccmelbqa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigfzy.top/Article/details/gtooetahyq.html

【使用说明】
来源：http://dali.cashguo.top/Article/details/gtezrppzwt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xinyue.icu/Article/details/gtnqgnoaxa.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.wangshuangyany.cn/Article/details/gtwlgmytpl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.birdmap.top/Article/details/gteffnkfxi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.nanxuanxn.top/Article/details/gtutixblwb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.c1oappe.top/Article/details/gtzeadaaqb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.redwolf501.top/Article/details/gtzaitzkic.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aibaodan.cn/Article/details/gtmxctlykb.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.dashuyun.cn/Article/details/gteigqzmqd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.0kj1m.cn/Article/details/gthqtawwku.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258888.top/Article/details/gtfzhvaxut.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hammf.cn/Article/details/gtdzncwtey.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sufxvd.cn/Article/details/gtqluiegoo.html

【文件统计】
来源：http://dali.redwolf501.top/Article/details/gtquruarnm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sysykeji.top/Article/details/gtvdwikioq.html

--------------------------------------------------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gthyqunekz.html

目  录
来源：http://dali.dianchejie.cn/Article/details/gtulpbemgg.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gthkhqgxys.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.fengsongda.top/Article/details/gtzuclfuff.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrrkqobop.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gtyudmlntr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtxinnolwy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gttuwwifqb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtmlnafiet.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtvnshgcdh.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gtzdnffgmu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtaxfevjoi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yvedp.cn/Article/details/gtltdhtkcy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtaghpanax.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhongyouzk.top/Article/details/gtmpizuquq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.guowangkeji.top/Article/details/gtublwxrce.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtmwgehhdh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.fengsongda.top/Article/details/gtngcjygiq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gtebpxuwtd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.316326.xyz/Article/details/gtohncsjer.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhongyouzk.top/Article/details/gtjlfygssj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.guannengcc.top/Article/details/gtkzxkcmij.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtrjtazhuu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtssamhhbv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtiordlxya.html

A. 基础语法与类型
来源：http://dali.xziqi.cn/Article/details/gtsyhriehy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcsavmwxy.html

[A01] Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchroimvi.html

Py:   print("Hello, World!")
来源：http://dali.nanxuanxn.top/Article/details/gtcsftiywa.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gtqkigjwcg.html

JS:   console.log("Hello, World!");
来源：http://dali.wangdashe.top/Article/details/gtxyzhgstx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.fzhhl.top/Article/details/gtyccadrof.html

Java: System.out.println("Hello, World!");
来源：http://dali.shzxlz.cn/Article/details/gtemehwkxa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwukpqtvy.html

Ruby: puts "Hello, World!"
来源：http://dali.andypj.xyz/Article/details/gtzntggprv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtrzuoytnh.html

[A02] 变量声明与赋值
来源：http://dali.fzhhl.top/Article/details/gtfyuacgmh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.havefunace.top/Article/details/gttvnkdpfm.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yueranfly.top/Article/details/gtyaftebxp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cucudq.cn/Article/details/gtdfgrxyhe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.0kj1m.cn/Article/details/gtdxojhjvk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.cashguo.top/Article/details/gtxqbwjkrn.html

Go:   name := "Alex"; age := 20
来源：http://dali.c1oappe.top/Article/details/gtpxxauiqt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.iojbl.cn/Article/details/gtejwlwnyw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtuekxqxdn.html

[A03] 常量定义
来源：http://dali.redwolf501.top/Article/details/gteoquxpfz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gzhubu.top/Article/details/gtlzqmozpm.html

PHP:  const PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtyivvgtje.html

JS:   const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtryvnokyo.html

TS:   const PI: number = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtajvsvclr.html

Java: static final double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtuoxnesom.html

Go:   const PI = 3.14159
来源：http://dali.gaohongyu789.top/Article/details/gtlwlkqskn.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtdueyrlso.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtgltazsqo.html

[A04] 判断变量类型
来源：http://dali.chenlongwang.top/Article/details/gtvnshejxa.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pengpengdd.cyou/Article/details/gtnthwtepl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.smart0.xyz/Article/details/gtgfciswgk.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.dianchejie.cn/Article/details/gtouznjfhk.html

TS:   typeof x; x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtsdlveqlw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.smart0.xyz/Article/details/gtzfnstqhn.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hnxiangtu.top/Article/details/gtikwebeyw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gtkhxpofxl.html

C#:   x.GetType().Name; x is int
来源：http://dali.snrcjt.cn/Article/details/gtfmxjaelp.html

[A05] 整数除法与取模
来源：http://dali.cucudq.cn/Article/details/gtxzxsvyls.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guowangkeji.top/Article/details/gtngccijld.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gtrgepsbel.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtkngywgfj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.9152youxi.cn/Article/details/gtnxnlbixv.html

Java: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtbwxvkbyj.html

Go:   7 / 2; 7 % 2
来源：http://dali.ivvv.top/Article/details/gtszsirpcw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.wangshuangyany.cn/Article/details/gtxlfikpok.html

C#:   7 / 2; 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifpovcgw.html

[A06] 字符串转数字
来源：http://dali.wangdashe.top/Article/details/gtpcwdblkc.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gtdulrgzzs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gtombeuwwn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.vqdsnc.cn/Article/details/gtcljhnzji.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shangyingyoupin.top/Article/details/gtiebdlmzy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtokjsqozl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.hammf.cn/Article/details/gtlrovozfb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.fzhhl.top/Article/details/gtmahgyqyn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnqzz.top/Article/details/gtiitxerua.html

[A07] 数字转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtdcurdvhb.html

Py:   str(42)
来源：http://dali.hywenlv.cn/Article/details/gtioqabkfm.html

PHP:  (string) 42; strval(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtzrraeppa.html

JS:   String(42); (42).toString()
来源：http://dali.jqgufenzy.top/Article/details/gtbsawwqwm.html

TS:   String(42)
来源：http://dali.hnqzz.top/Article/details/gttwvvoglj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gzhubu.top/Article/details/gtmpxyxxrs.html

Go:   strconv.Itoa(42)
来源：http://dali.ybcxt.top/Article/details/gtktpycsni.html

Ruby: 42.to_s
来源：http://dali.kuanghao11.cn/Article/details/gtuncqsyyd.html

C#:   42.ToString()
来源：http://dali.316326.xyz/Article/details/gtrdwvlyiv.html

[A08] 取整与四舍五入
来源：http://dali.ppjwa.cn/Article/details/gtmiwgldfd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhixingplan.top/Article/details/gtuyftnqdj.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gtzpbpzapz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuanzhike.top/Article/details/gtjrmpsosm.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.feifeiyinyue.top/Article/details/gtbczdytgj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtayopkfjm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvhzzclo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yuanzhike.top/Article/details/gtujprttzt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yj202588.top/Article/details/gttwgddoij.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gttlcyeymv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtritobflz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtdqdxtqwu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtdtiongge.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtgekksvie.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtuhhydjpv.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shzxlz.cn/Article/details/gtxhccrqfl.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gtzokeszdj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.pycfn.com/Article/details/gtwyrahadd.html

[A10] 生成随机数
来源：http://dali.pycfn.com/Article/details/gtoqhwqjds.html

Py:   import random; random.randint(1, 100)
来源：http://dali.yj20258888.top/Article/details/gthksdeogm.html

PHP:  random_int(1, 100);
来源：http://dali.ivvv.top/Article/details/gtvxlpitrz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.daria6918.cn/Article/details/gtdiifmiwn.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jiagoushi.top/Article/details/gtyvgeufbl.html

Java: new Random().nextInt(100) + 1
来源：http://dali.redwolf501.top/Article/details/gtfigwroeh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.quarkkingdee.top/Article/details/gtgkposwme.html

Ruby: rand(1..100)
来源：http://dali.hfpthk.cn/Article/details/gtjzbtzlrc.html

C#:   new Random().Next(1, 101)
来源：http://dali.jinqigfzy.top/Article/details/gtiknzxbst.html

[A11] 条件表达式（三元）
来源：http://dali.yanxiufei.cn/Article/details/gtbennjvxg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daria6918.cn/Article/details/gtadqylosn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.guannengcc.top/Article/details/gtqkafzjve.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.chenzaomai.com/Article/details/gtvisxvmhl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtzayfrkwt.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtpychmsfc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gtivhvjkfe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtzcwxghuf.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtzebwzcdy.html

[A12] 字符串插值 / 格式化
来源：http://dali.yj20258.top/Article/details/gtcmhmnizl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hongshengwenyu.top/Article/details/gtrjeqjvdh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nanxinkj.top/Article/details/gtdzdrffrt.html

JS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtzuzqxxnl.html

TS:   `Hello, ${name}!`
来源：http://dali.nanxinkj.top/Article/details/gtgrbwzgfm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gogol.net.cn/Article/details/gtcqmxguxl.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gzhubu.top/Article/details/gtmpsearlg.html

Ruby: "Hello, #{name}!"
来源：http://dali.shzxlz.cn/Article/details/gtvfiltrxc.html

C#:   $"Hello, {name}!"
来源：http://dali.havefunace.top/Article/details/gtxjfjclfx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xuetiantiany.cn/Article/details/gtlrrinxfg.html

Py:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtfjrbfklw.html

PHP:  "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtmdknarvc.html

JS:   "第一行\n第二行"
来源：http://dali.cashguo.top/Article/details/gtquuvuvdf.html

TS:   "第一行\n第二行"
来源：http://dali.sxryk.cn/Article/details/gtoarnlivp.html

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtqhmimico.html

Go:   "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gtautcxucc.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtcykbrxbz.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtzrgajvmv.html

[A14] 注释写法
来源：http://dali.wangdashe.top/Article/details/gtgfiqmxec.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhoulong.xyz/Article/details/gtmuialzwb.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtxsffzisk.html

JS:   // 单行；/* 多行 */
来源：http://dali.fengsongda.top/Article/details/gtekjpthlv.html


<!-- 参考信息 -->