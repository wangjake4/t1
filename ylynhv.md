代发 wailian999

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gtetggzlqx.html

a?.b?.c
来源：http://dali.svipenyu.cn/Article/details/gtveqsjtsi.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtyewknoiz.html

a ?? b
来源：http://dali.shangyingyoupin.top/Article/details/gtbpzbbdig.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gtmhkvxmif.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gtiqgvjawr.html

[U88] JS：对象展开合并
来源：http://dali.andypj.xyz/Article/details/gtgvmevbzo.html

{ ...a, ...b }
来源：http://dali.guannengcc.top/Article/details/gtjdgmrigx.html

[U89] JS：数组去重
来源：http://dali.meibo888.top/Article/details/gtkfnciixt.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtjnimrqrp.html

[U90] JS：数字数组排序
来源：http://dali.zhixingplan.top/Article/details/gtexprhjvb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gttadkvqrc.html

[U91] JS：对象键值遍历
来源：http://dali.yangfankeji.com/Article/details/gtujnknagh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuxming.cn/Article/details/gtbfwiyrhc.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gtzmfwewud.html

structuredClone(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjurddrfb.html

[U93] JS：模板字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtvjpwprfg.html

`共 ${n} 条`
来源：http://dali.ivvv.top/Article/details/gthuvdyxoa.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gttrhfrsvy.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gtbrcnakwz.html

[U95] JS：Promise 包装
来源：http://dali.shangyingyoupin.top/Article/details/gtbrqecqvr.html

new Promise((resolve, reject) => {})
来源：http://dali.hammf.cn/Article/details/gtnbcjsvyg.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gttjiffitw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtsfvypvwb.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gtsriakpaz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtemaqwlbr.html

[U98] JS：fetch 带 JSON
来源：http://dali.svipenyu.cn/Article/details/gtonhgnjsr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jiagoushi.top/Article/details/gtwgezcgwg.html

[U99] JS：事件监听
来源：http://dali.ppjwa.cn/Article/details/gtkycuxkaj.html

el.addEventListener("click", e => {})
来源：http://dali.hammf.cn/Article/details/gtjcjndvok.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gthgbogvig.html

document.querySelector(".item")
来源：http://dali.xuetiantiany.cn/Article/details/gtmzeemjrc.html

[U101] JS：classList 操作
来源：http://dali.pengpengdd.cyou/Article/details/gtppisvhas.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gtkuwueioj.html

[U102] JS：本地存储
来源：http://dali.cdnleiting.top/Article/details/gtmgzfdphw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guannengcc.top/Article/details/gtiyasnxzt.html

[U103] JS：定时器
来源：http://dali.ppjwa.cn/Article/details/gtwmcaeffc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgbhzwav.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gtxjgbonda.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtynkugvjp.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gtwlezifys.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmsjfkii.html

[U106] JS：日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtcqmxcjyf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.c1oappe.top/Article/details/gtgjitsmoe.html

[U107] JS：数字千分位
来源：http://dali.yvedp.cn/Article/details/gtbyihwdwp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtomokjltf.html

[U108] JS：随机整数
来源：http://dali.xinyue.icu/Article/details/gttymfebrl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.316326.xyz/Article/details/gtktkhcdal.html

[U109] JS：数组分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwndaqqv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gtnnczgqvg.html

[U110] JS：数组分块
来源：http://dali.andypj.xyz/Article/details/gtfadplwxz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cucudq.cn/Article/details/gttsjmaggn.html

[U111] JS：对象转 Map
来源：http://dali.yj20258.top/Article/details/gtlyqacvtz.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtttoeyhel.html

[U112] JS：字符串补位
来源：http://dali.yuanzhike.top/Article/details/gtvlhgexng.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtzepcdpzc.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gthporodtn.html

s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtzyhzmfyn.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtzneaiozz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gtnfwzixaf.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdbzgxzb.html

crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtwlellnpj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtiftokfad.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gtdwbcanqt.html

[U117] JS：单元测试
来源：http://dali.jqgufenzy.top/Article/details/gtprbmvlqg.html

npm i -D vitest;  npx vitest
来源：http://dali.iojbl.cn/Article/details/gtxbkmzexi.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtaazzebtk.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gtwcbmhivz.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gtkmuxyeej.html

npx vite build
来源：http://dali.dianchejie.cn/Article/details/gtcxfxxall.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sufxvd.cn/Article/details/gtyqzylpwb.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gttudmdazr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtdmgcswjr.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gtmncyivqg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtkawvomwh.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gttoobvfet.html

Python ......... 252
来源：http://dali.zdqjudy.top/Article/details/gtjthwwtxq.html

PHP ............ 252
来源：http://dali.quarkkingdee.top/Article/details/gtpvnbobqs.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gtbjkzkltc.html

TypeScript ..... 212
来源：http://dali.guowangkeji.top/Article/details/gtjilpsugs.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtbckicvqq.html

Go ............. 212
来源：http://dali.smart0.xyz/Article/details/gtslwrevlt.html

Ruby ........... 212
来源：http://dali.yj202588.top/Article/details/gttwckaxtz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gtaocpwslx.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gttouhxnsg.html

C++ ............ 30
来源：http://dali.aibaodan.cn/Article/details/gtaxqylijs.html

SQL ............ 90
来源：http://dali.nanxuanxn.top/Article/details/gtziisiwbb.html

Bash ........... 80
来源：http://dali.zhoulong.xyz/Article/details/gtsxffbyzp.html

Kotlin ......... 15
来源：http://dali.sweek.top/Article/details/gtfptfpnso.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtyrlaxpof.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gtzbgylnvr.html

Perl ........... 10
来源：http://dali.nanxuanxn.top/Article/details/gtwznkecba.html

Scala .......... 10
来源：http://dali.jyoumei.cn/Article/details/gtxtnbhlyu.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtsdvkyryg.html

合计 ........... 2106 条
来源：http://dali.tanke756.top/Article/details/gtgnoqdxmd.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcorkxwx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.iojbl.cn/Article/details/gttohebhvq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.hammf.cn/Article/details/gtxdxnpdad.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtaqgvlecg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gotoacloud.top/Article/details/gtmizedvos.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtriuhqxcm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrfjcjqc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtlcqwhyls.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guowangkeji.top/Article/details/gteusaijpi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtcuzkaftn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gtzwoxwkbn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtdppqdabt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtbqcgeowx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtgqcxmnmt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtdyzajyoi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hnxiangtu.top/Article/details/gtnuzvmozv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gtchryjrkd.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gtgngohmju.html

R Bash 专题                             80
来源：http://dali.yonumen.top/Article/details/gttivxxffo.html

S C / C++ 专题                          60
来源：http://dali.jinqigufen.top/Article/details/gtonkwohdp.html

T 其他语言补充                          60
来源：http://dali.nanxinkj.top/Article/details/gtquscdsza.html

U 高频实用片段                         120
来源：http://dali.andypj.xyz/Article/details/gtthygqyty.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtfqpjgmcr.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtobntkscn.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtvovvclrf.html

使用提醒
来源：http://dali.yj202588.top/Article/details/gtreiikite.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtyldjchki.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj202588.top/Article/details/gtovtgrktj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jqgfzy.top/Article/details/gtddssgrle.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.wangshuangyany.cn/Article/details/gtdkshzftk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflixfcfh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yueranfly.top/Article/details/gtxycskukl.html

—— 文件结束 ——
来源：http://dali.fengsongda.top/Article/details/gtqrwnthrn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbirttdlf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjezjgdas.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gttuoqietw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtflblimjv.html

【收录内容】
来源：http://dali.sysykeji.top/Article/details/gtjgaetqmh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.mhx1999.top/Article/details/gtiiusmarm.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yanxiufei.cn/Article/details/gtbbemnzyu.html

SQL · Bash · C · C++
来源：http://dali.yangfankeji.com/Article/details/gtxllqhbii.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xziqi.cn/Article/details/gtlyjbbojs.html

【使用说明】
来源：http://dali.hnxiangtu.top/Article/details/gtxwzshizf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenzaomai.com/Article/details/gtsyilcilk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenzaomai.com/Article/details/gtbnjfaigb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhengqikj.top/Article/details/gtlflgzuwv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hongshengwenyu.top/Article/details/gtgtoepayu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.nanxinkj.top/Article/details/gtcfbektuy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.xuanzx.com/Article/details/gtvyawrxij.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gtcbidgdst.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.9152youxi.cn/Article/details/gtacnxgoaf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xziqi.cn/Article/details/gtufklebxc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xinyue.icu/Article/details/gtftluqrnz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aizwys.cn/Article/details/gtrqbqtxhe.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gtssdjekvs.html

【文件统计】
来源：http://dali.pycfn.com/Article/details/gtozlrxgcg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yvedp.cn/Article/details/gtjqvkeord.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtybnmqxzc.html

目  录
来源：http://dali.yonumen.top/Article/details/gtewredgnr.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtqiscpybk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhoulong.xyz/Article/details/gtmmgynzgg.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhngrngi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.andypj.xyz/Article/details/gtwfpwvdiz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.tianlin.xyz/Article/details/gtnulcfdnh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhongyouzk.top/Article/details/gtwflrnndg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jlsjyb.cn/Article/details/gtjvnhclph.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtfwcxdohy.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zdqjudy.top/Article/details/gtzagngwve.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ybcxt.top/Article/details/gtrkquuzoz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtwowlemmb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtcfyexitq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtszjosgxt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtirceezlv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtsmgxozca.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gtqtoqtgag.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.shuidangran.top/Article/details/gtkombjqqv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ivvv.top/Article/details/gtcdrqoxuw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zdqjudy.top/Article/details/gtuiavaajc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtgtauhelr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtochpiwtx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtoaxubibj.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyspuvrcu.html

A. 基础语法与类型
来源：http://dali.nanxuanxn.top/Article/details/gtpscunomu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthrvmjord.html

[A01] Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtdvnwoctu.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtpduhqzym.html

PHP:  echo "Hello, World!";
来源：http://dali.yonumen.top/Article/details/gtzcuuacbt.html

JS:   console.log("Hello, World!");
来源：http://dali.jianghu66.top/Article/details/gthmdggzlg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.xziqi.cn/Article/details/gtzzobqphk.html

Java: System.out.println("Hello, World!");
来源：http://dali.dashuyun.cn/Article/details/gtdlblzsbj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.sufxvd.cn/Article/details/gtftlluukn.html

Ruby: puts "Hello, World!"
来源：http://dali.dianchejie.cn/Article/details/gtmdlzizqk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.vqdsnc.cn/Article/details/gtetjbdqgx.html

[A02] 变量声明与赋值
来源：http://dali.pengpengdd.cyou/Article/details/gtzsiruhfd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.fzhhl.top/Article/details/gtijyvycnx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtzuosscbi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhmvfkin.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuanzhike.top/Article/details/gtfrsulecu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtjyihrjzf.html

Go:   name := "Alex"; age := 20
来源：http://dali.tian-w.cn/Article/details/gtbjwzhfsh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxnwmcuj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yongpay.top/Article/details/gtjxrhtkhx.html

[A03] 常量定义
来源：http://dali.ydzc1.top/Article/details/gtvvnjttxl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhengqikj.top/Article/details/gtbqrjwgoi.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtqbbbnkqi.html

JS:   const PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtltdxhyfp.html

TS:   const PI: number = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtqtdnpptw.html

Java: static final double PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtblaqkohn.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtfxldqqhx.html

Ruby: PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gthwnjgqrl.html

C#:   const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtoeozomjh.html

[A04] 判断变量类型
来源：http://dali.jlsjyb.cn/Article/details/gtaegwxpbt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yj20258888.top/Article/details/gtcilqbtpy.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hnqzz.top/Article/details/gtqvvfzzun.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.iojbl.cn/Article/details/gtijcaevcn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtktepowts.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gteknmutny.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtesrfwqpq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnixrozwi.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gtfnwatmbg.html

[A05] 整数除法与取模
来源：http://dali.hnqzz.top/Article/details/gtamtjarqx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.gotoacloud.top/Article/details/gtcbwpcfjr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtidrqskzd.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtapvmesaw.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtlwvcqlne.html

Java: 7 / 2; 7 % 2
来源：http://dali.hnxiangtu.top/Article/details/gtqgvgkque.html

Go:   7 / 2; 7 % 2
来源：http://dali.shuidangran.top/Article/details/gtebcwwelp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtqqvxtxuf.html

C#:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gthlbmnbqn.html

[A06] 字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaiesxpu.html

Py:   int("42"); float("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtgspdqkop.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yueranfly.top/Article/details/gtntiseguc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtrsbhvrnc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.nwbrower.top/Article/details/gtnaxdpsda.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtfknqtycw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jinqigufen.top/Article/details/gtiuurqujd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hywenlv.cn/Article/details/gtcfrrlnvj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xinyue.icu/Article/details/gtssqvecsv.html

[A07] 数字转字符串
来源：http://dali.jianghu66.top/Article/details/gtvozrrjyk.html

Py:   str(42)
来源：http://dali.ybcxt.top/Article/details/gtabbvfrrr.html

PHP:  (string) 42; strval(42)
来源：http://dali.fzhhl.top/Article/details/gtzzyvevze.html

JS:   String(42); (42).toString()
来源：http://dali.yuanzhike.top/Article/details/gtowpjbkla.html

TS:   String(42)
来源：http://dali.ppjwa.cn/Article/details/gtvxmfjoii.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shzxlz.cn/Article/details/gtkmfpftxc.html

Go:   strconv.Itoa(42)
来源：http://dali.hammf.cn/Article/details/gtgtftrncc.html

Ruby: 42.to_s
来源：http://dali.xuetiantiany.cn/Article/details/gthdpmkuix.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtfehcxiig.html

[A08] 取整与四舍五入
来源：http://dali.shangyingyoupin.top/Article/details/gtjwdzibtm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtzcacuupa.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gthqbivpah.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhiwuduotai.top/Article/details/gttyogohfd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqyasopm.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gtmwkklpqr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.gaohongyu789.top/Article/details/gtuakhflqt.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.nwbrower.top/Article/details/gtqwbwqene.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtamtntbpi.html

[A09] 绝对值与最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtbcdpvndb.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gtbyriesmw.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtiuwixlfh.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxmdxpny.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwapdwbn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtfcicybyy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangkeji.top/Article/details/gthooxgpev.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.aizwys.cn/Article/details/gttprazvlj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.meibo888.top/Article/details/gthnxkblmm.html

[A10] 生成随机数
来源：http://dali.yvedp.cn/Article/details/gtwhjjcfgc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtakspupqa.html

PHP:  random_int(1, 100);
来源：http://dali.quarkkingdee.top/Article/details/gtzqwzwyai.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nanxuanxn.top/Article/details/gttrpxecpi.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.smart0.xyz/Article/details/gtrxcxyqwv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtlhlxzbtu.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcufzpyl.html

Ruby: rand(1..100)
来源：http://dali.9152youxi.cn/Article/details/gtccdjntdb.html

C#:   new Random().Next(1, 101)
来源：http://dali.cheryme.top/Article/details/gtfifbvuxi.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gtjitxagqo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwgfgxom.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtflizdgsx.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gthzoigssr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtymvjqati.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gthbcnrezg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cdnleiting.top/Article/details/gtzktzkzlq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhengqikj.top/Article/details/gtchbuqnim.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtjkhtzzvx.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgufenzy.top/Article/details/gtqerigpst.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jiagoushi.top/Article/details/gtmlkygunj.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nanxuanxn.top/Article/details/gttpvoeoya.html

JS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangtech.top/Article/details/gtikdyrmll.html

TS:   `Hello, ${name}!`
来源：http://dali.guowangkeji.top/Article/details/gtxexwxwry.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhxjktqq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj20258888.top/Article/details/gtpcrblujc.html

Ruby: "Hello, #{name}!"
来源：http://dali.jlsjyb.cn/Article/details/gtjlfufflz.html

C#:   $"Hello, {name}!"
来源：http://dali.gaohongyu789.top/Article/details/gtfbvdxpqy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sxryk.cn/Article/details/gtthtrldak.html

Py:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtjohnflxo.html

PHP:  "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmchiyyo.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtogmixsjs.html

TS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtlgklhpnb.html

Java: "第一行\n第二行"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwukyysgh.html

Go:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtlassqlrg.html

Ruby: "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtyrzngxyg.html

C#:   "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gtifyjkxxp.html

[A14] 注释写法
来源：http://dali.jyoumei.cn/Article/details/gtddchzqix.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yuxming.cn/Article/details/gtyzajrdwa.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtounhowui.html

JS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtgnfwklce.html


<!-- 参考信息 -->