代发 wailian999

[U85] JS：可选链
来源：http://dali.jinqigfzy.top/Article/details/gtdmfrhhgr.html

a?.b?.c
来源：http://dali.ybcxt.top/Article/details/gtaiudubqr.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gtsumximxo.html

a ?? b
来源：http://dali.tianlin.xyz/Article/details/gtjgjpxntm.html

[U87] JS：解构默认值
来源：http://dali.yonumen.top/Article/details/gtpnkoupua.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinqigfzy.top/Article/details/gtextgutux.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gtrbhmmqrd.html

{ ...a, ...b }
来源：http://dali.9152youxi.cn/Article/details/gtghjtodmw.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gthkjbbulk.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtdbuaubgj.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtghlnnrxt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtbrylfizu.html

[U91] JS：对象键值遍历
来源：http://dali.cucudq.cn/Article/details/gteikmpkag.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtgqmaqdum.html

[U92] JS：深拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtqwxhmkgl.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtyturvtar.html

[U93] JS：模板字符串
来源：http://dali.jyoumei.cn/Article/details/gtnkivjijw.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gtrntpexvr.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtrvmgtjhv.html

const double = x => x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtzfgatsrt.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gtrpizulvl.html

new Promise((resolve, reject) => {})
来源：http://dali.pycfn.com/Article/details/gtvxpncnvf.html

[U96] JS：async/await 与异常
来源：http://dali.ydzc1.top/Article/details/gtbwzthgrm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gtjqfdmppe.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtmiafhkuz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtsxdfuxkq.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gtcdgtxntg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtimbriyvr.html

[U99] JS：事件监听
来源：http://dali.cucudq.cn/Article/details/gtsesfenvc.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtiqyoourx.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtojzmzhfe.html

document.querySelector(".item")
来源：http://dali.shuidangran.top/Article/details/gtnhproeal.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtzvjuajou.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpsqgurv.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gtjtizvdsd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hammf.cn/Article/details/gtrbturcgo.html

[U103] JS：定时器
来源：http://dali.yongpay.top/Article/details/gtmxftxyek.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtidvclbtu.html

[U104] JS：防抖
来源：http://dali.aizwys.cn/Article/details/gtqunahgyl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtknuchzdy.html

[U105] JS：节流
来源：http://dali.dianchejie.cn/Article/details/gtishuhdfm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.bjfxy.top/Article/details/gttgvwcpcv.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtpbnekiud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtldshczkp.html

[U107] JS：数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtegqmmzbr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.aizwys.cn/Article/details/gtfixzhbwi.html

[U108] JS：随机整数
来源：http://dali.316326.xyz/Article/details/gtjqnppllp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hywenlv.cn/Article/details/gtbkhjtamx.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtwdwsxpyc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gtteamtamu.html

[U110] JS：数组分块
来源：http://dali.yueranfly.top/Article/details/gtqbxobjxk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.iojbl.cn/Article/details/gtspnjokhl.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtqzxwsdns.html

new Map(Object.entries(obj))
来源：http://dali.shangyingyoupin.top/Article/details/gtxtjzrtsv.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gtcdwgcmun.html

"7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtgruizbiv.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gtsbrlodzv.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtpiuodyfr.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gtehzxhfod.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzrthnzw.html

[U115] JS：生成 UUID
来源：http://dali.mhx1999.top/Article/details/gtxvywzuds.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtrjvvizry.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gtkpiqujld.html

/** @param {string} name */ function f(name) {}
来源：http://dali.haohaochexian.top/Article/details/gtufoxtvtc.html

[U117] JS：单元测试
来源：http://dali.ydzc1.top/Article/details/gtevvspkzz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gtxjvgxwor.html

[U118] JS：开发服务器
来源：http://dali.jinqigufen.top/Article/details/gtoewqlvfm.html

npm i -D vite;  npx vite
来源：http://dali.gaohongyu789.top/Article/details/gtoefqlffl.html

[U119] JS：生产构建
来源：http://dali.zhiwuduotai.top/Article/details/gtvgpmkcnr.html

npx vite build
来源：http://dali.dashuyun.cn/Article/details/gtvdfqjuqd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gtuhoqnaad.html

import.meta.env.VITE_API_URL
来源：http://dali.cdnleiting.top/Article/details/gtotgpyyji.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtdkzttemx.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtoreowvdt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmrribbud.html

按语言统计（条）：
来源：http://dali.yuanzhike.top/Article/details/gtrmjmwqou.html

Python ......... 252
来源：http://dali.jianghu66.top/Article/details/gtvnbowhvg.html

PHP ............ 252
来源：http://dali.chenlongwang.top/Article/details/gtnbccawxp.html

JavaScript ..... 252
来源：http://dali.zhoulong.xyz/Article/details/gtzpwknkfj.html

TypeScript ..... 212
来源：http://dali.chenzaomai.com/Article/details/gtqzeyvinr.html

Java ........... 212
来源：http://dali.ydzc1.top/Article/details/gtqnnjuqfh.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtxlepnoof.html

Ruby ........... 212
来源：http://dali.hongshengwenyu.top/Article/details/gtuqaikvrt.html

C# ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtpposkews.html

C .............. 30
来源：http://dali.nanxuanxn.top/Article/details/gtcmbdkvhi.html

C++ ............ 30
来源：http://dali.bjfxy.top/Article/details/gtpkyagehw.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gtjcbhrxnr.html

Bash ........... 80
来源：http://dali.zycfv.cn/Article/details/gtfzcgguct.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtiajrlarq.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtagznvrwe.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtqnymxpon.html

Perl ........... 10
来源：http://dali.yanxiufei.cn/Article/details/gtxuuuglls.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtajxgznbz.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gthgnnbfvf.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gtgfqenlzo.html

按章节统计：
来源：http://dali.redwolf501.top/Article/details/gtfhrwicen.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtbppqsvhc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtpmrzputk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtdgzfsynn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fengsongda.top/Article/details/gtynzptpue.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.iojbl.cn/Article/details/gtfmpondzs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gttttzrmam.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtqugtlsuu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnlivspj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtfnqmowfl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yueranfly.top/Article/details/gtdpmqjbzr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtgmtizobv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtgxsecpzt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gtjocwzixt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.daria6918.cn/Article/details/gtukotybhp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gzhubu.top/Article/details/gtmsawduru.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtgbcxkxmu.html

Q SQL 专题                              90
来源：http://dali.yj202588.top/Article/details/gtqetztgxs.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gtaaufrdwo.html

S C / C++ 专题                          60
来源：http://dali.cdnleiting.top/Article/details/gtdnlewrqn.html

T 其他语言补充                          60
来源：http://dali.ehwqpu.com/Article/details/gtvbptqedi.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacrachol.html

------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtcurelabn.html

合计                                  2106 条
来源：http://dali.zdqjudy.top/Article/details/gtfxtkrzof.html

--------------------------------------------------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtimpafvyt.html

使用提醒
来源：http://dali.yangfankeji.com/Article/details/gtlcaiplfx.html

--------------------------------------------------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gtuhnteaax.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtrfbdnrvf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.kuanghao11.cn/Article/details/gtichhmpnc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.hammf.cn/Article/details/gtiziywvyg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xziqi.cn/Article/details/gtvljqwufe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.svipenyu.cn/Article/details/gtbhfmijzp.html

—— 文件结束 ——
来源：http://dali.pengpengdd.cyou/Article/details/gtbutbjtpu.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtywtnessw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yuanzhike.top/Article/details/gtnghzfiqw.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigufen.top/Article/details/gtuwzdhwyi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqwjsrlkx.html

【收录内容】
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsczxymeb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.9152youxi.cn/Article/details/gtfcdnxtes.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhaomingkeji.xyz/Article/details/gteabvzwge.html

SQL · Bash · C · C++
来源：http://dali.daria6918.cn/Article/details/gtsspqncna.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gtkrhvagde.html

【使用说明】
来源：http://dali.pycfn.com/Article/details/gtakhasgnw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkswgokk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinqigufen.top/Article/details/gttsgxwkct.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.0kj1m.cn/Article/details/gtzmrnbtyc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.sufxvd.cn/Article/details/gtvrefhtmk.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkyibhbv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gtjgmymcrm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.pengpengdd.cyou/Article/details/gtvbsnpzro.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yonumen.top/Article/details/gtpdhumzdr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hongshengwenyu.top/Article/details/gtpvrcbxpu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtyivgoaxy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.aibaodan.cn/Article/details/gtkvjhglxa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.sysykeji.top/Article/details/gtkikfbxzg.html

【文件统计】
来源：http://dali.nanxinkj.top/Article/details/gtplfiunir.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.birdmap.top/Article/details/gtyeaekcxx.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtxrmnsmik.html

目  录
来源：http://dali.birdmap.top/Article/details/gtqqoghcsr.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtfolicwkf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlpbvmds.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtglkuxrtd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkvwvltq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtzraliirq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.snrcjt.cn/Article/details/gtdshpzttm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gtokgjahpn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gttnryadol.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtlukxbsfh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gtgkhxgwpv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtoxotxmur.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.kuanghao11.cn/Article/details/gttwslvbzn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtgcpqreax.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtnxcfotyb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jianghu66.top/Article/details/gtabjxtche.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jiagoushi.top/Article/details/gthjnxxshn.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtcyeyxcwp.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwvoxklc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yueranfly.top/Article/details/gtkzuxfoue.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yanxiufei.cn/Article/details/gtvfdwthgj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpkjiwpr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gteongtcpv.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbeavcrtm.html

A. 基础语法与类型
来源：http://dali.iojbl.cn/Article/details/gtpvrhfjpr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtqfvgkhcm.html

[A01] Hello World
来源：http://dali.hysaishi.cn/Article/details/gtnwzjybul.html

Py:   print("Hello, World!")
来源：http://dali.guannengcc.top/Article/details/gthlirzrkl.html

PHP:  echo "Hello, World!";
来源：http://dali.hfpthk.cn/Article/details/gtbcxeqyie.html

JS:   console.log("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gtudqkjnmu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ybcxt.top/Article/details/gtfnfjgzwx.html

Java: System.out.println("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtsrrmoxbp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gtltzblrwc.html

Ruby: puts "Hello, World!"
来源：http://dali.cqqwz.cn/Article/details/gtoohlbdhm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtcxbrqmyt.html

[A02] 变量声明与赋值
来源：http://dali.svipenyu.cn/Article/details/gtpqqriapq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinqigfzy.top/Article/details/gtzivhbflq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtlldnaecp.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jiagoushi.top/Article/details/gtsnylxaxz.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.nanxinkj.top/Article/details/gtpizusyat.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.yj20258888.top/Article/details/gtznofnyhc.html

Go:   name := "Alex"; age := 20
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzdpirbu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.fzhhl.top/Article/details/gttqmfqtpn.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hysaishi.cn/Article/details/gthtslcdzw.html

[A03] 常量定义
来源：http://dali.zhixingplan.top/Article/details/gtzewbouwo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gtlxlrqiji.html

PHP:  const PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gtcppkoaih.html

JS:   const PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtctkqxbxe.html

TS:   const PI: number = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtxiizphqb.html

Java: static final double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtwgpiqyjt.html

Go:   const PI = 3.14159
来源：http://dali.hfpthk.cn/Article/details/gtdsafgkmb.html

Ruby: PI = 3.14159
来源：http://dali.zhixingplan.top/Article/details/gtpwxnpmyz.html

C#:   const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtaltxutlv.html

[A04] 判断变量类型
来源：http://dali.ivvv.top/Article/details/gtypvpquzs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.snrcjt.cn/Article/details/gtbginivle.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.ybcxt.top/Article/details/gtnfybubkg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gtdctstdbg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfczvktf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.fzhhl.top/Article/details/gtszmuyjfc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.haohaochexian.top/Article/details/gtonoovalh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yvedp.cn/Article/details/gtxskebzhn.html

C#:   x.GetType().Name; x is int
来源：http://dali.fengsongda.top/Article/details/gtmtrfxnxt.html

[A05] 整数除法与取模
来源：http://dali.dianchejie.cn/Article/details/gtulaqqysx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gtakeanzia.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtnaofqybb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtfnlafqwv.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gtsjpirhvw.html

Java: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtddqeycwj.html

Go:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtrbvseouy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtlnauxacv.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gthwaibxmb.html

[A06] 字符串转数字
来源：http://dali.yonumen.top/Article/details/gtsklnsktd.html

Py:   int("42"); float("3.14")
来源：http://dali.yj20258888.top/Article/details/gtjlzfxeil.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gtgzkotpto.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.dashuyun.cn/Article/details/gtxcgvqvvo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtorjcktnn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jiagoushi.top/Article/details/gtrqppugxp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fengsongda.top/Article/details/gtnejbryjt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.wangdashe.top/Article/details/gtumkvckvt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.shangyingyoupin.top/Article/details/gtopyjhnbz.html

[A07] 数字转字符串
来源：http://dali.hywenlv.cn/Article/details/gtqybhkpgm.html

Py:   str(42)
来源：http://dali.pengpengdd.cyou/Article/details/gtzumzwxby.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhixingplan.top/Article/details/gtgrdzgmux.html

JS:   String(42); (42).toString()
来源：http://dali.jianghu66.top/Article/details/gtmodxgiys.html

TS:   String(42)
来源：http://dali.smart0.xyz/Article/details/gttrzyxzae.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gticftbhve.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gtfbsithqx.html

Ruby: 42.to_s
来源：http://dali.svipenyu.cn/Article/details/gtrgljigxp.html

C#:   42.ToString()
来源：http://dali.cucudq.cn/Article/details/gtxgzzqtdt.html

[A08] 取整与四舍五入
来源：http://dali.yj20258888.top/Article/details/gtopzqxcbp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtqocnojin.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cqqwz.cn/Article/details/gtogczwajx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ivvv.top/Article/details/gthjphomzi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jlsjyb.cn/Article/details/gtqiozlhsd.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gteatotclw.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtalrofcsa.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.sxryk.cn/Article/details/gtabaipyyk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.jlsjyb.cn/Article/details/gtqdkcjqes.html

[A09] 绝对值与最大最小值
来源：http://dali.xziqi.cn/Article/details/gtyxhydnfn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gthzkfrxxs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtchrrfqxi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtlqxopffo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtuyfpphwz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtddnedmuy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.meibo888.top/Article/details/gtwxubbfuq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.iojbl.cn/Article/details/gtrikybquc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtseqyupiu.html

[A10] 生成随机数
来源：http://dali.hnqzz.top/Article/details/gtxesdnmaw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shangyingyoupin.top/Article/details/gtmaudzuif.html

PHP:  random_int(1, 100);
来源：http://dali.gotoacloud.top/Article/details/gtzginwbze.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gtietpucnt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.vqdsnc.cn/Article/details/gtlkjmlvit.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jlsjyb.cn/Article/details/gtsisjkndk.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuanzhike.top/Article/details/gtmdkbsyjz.html

Ruby: rand(1..100)
来源：http://dali.gzhubu.top/Article/details/gtdonbzvez.html

C#:   new Random().Next(1, 101)
来源：http://dali.redwolf501.top/Article/details/gtxirkghhi.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdivpzuqf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.9152youxi.cn/Article/details/gtgpmhzorn.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gogol.net.cn/Article/details/gtuqbashpc.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtgenocclm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.guowangkeji.top/Article/details/gtngixudmc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.aibaodan.cn/Article/details/gtxuszyrum.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cheryme.top/Article/details/gtxtdwtjnu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gtzjpdvfrj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gttxcauurp.html

[A12] 字符串插值 / 格式化
来源：http://dali.sysykeji.top/Article/details/gtpynsltlb.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.chenlongwang.top/Article/details/gtaemlwtmr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hongshengwenyu.top/Article/details/gtttemwfmw.html

JS:   `Hello, ${name}!`
来源：http://dali.jiagoushi.top/Article/details/gtdnugmfyb.html

TS:   `Hello, ${name}!`
来源：http://dali.hnqzz.top/Article/details/gtlfuuggvf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.vqdsnc.cn/Article/details/gtngkakvgt.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zycfv.cn/Article/details/gtbjvljxqi.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebrdkdou.html

C#:   $"Hello, {name}!"
来源：http://dali.mhx1999.top/Article/details/gtbcrghnmh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yuanzhike.top/Article/details/gtxhzxzwir.html

Py:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtrwfqbmtz.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtykjjaxgj.html

JS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gteiinailq.html

TS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtmrhaocjs.html

Java: "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtkytbtygu.html

Go:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtcppabiqu.html

Ruby: "第一行\n第二行"
来源：http://dali.yvedp.cn/Article/details/gthmwdddeu.html

C#:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtzbaejsor.html

[A14] 注释写法
来源：http://dali.yj20258888.top/Article/details/gtinvopfae.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.birdmap.top/Article/details/gtduyrashl.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtrflvpfdr.html

JS:   // 单行；/* 多行 */
来源：http://dali.redwolf501.top/Article/details/gtfkkgexab.html


<!-- 参考信息 -->