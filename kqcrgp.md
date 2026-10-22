代发 wailian999

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtvkxsvodm.html

a?.b?.c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxsupykz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gtvtilohbc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gtklrascwg.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gtfsnmamzx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gtgoacwglj.html

[U88] JS：对象展开合并
来源：http://dali.cqqwz.cn/Article/details/gtsncsghih.html

{ ...a, ...b }
来源：http://dali.hfpthk.cn/Article/details/gtxiluejkc.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtpqdlmfzf.html

[...new Set(arr)]
来源：http://dali.daria6918.cn/Article/details/gtytoknjdh.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gtnthtzyaf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtvoggzyuo.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gtqobagikv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tian-w.cn/Article/details/gthaomqmpp.html

[U92] JS：深拷贝
来源：http://dali.hfpthk.cn/Article/details/gtfyeklwsb.html

structuredClone(obj)
来源：http://dali.yuanzhike.top/Article/details/gtogzjqcng.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gtitutiird.html

`共 ${n} 条`
来源：http://dali.xuetiantiany.cn/Article/details/gtrcpnyiox.html

[U94] JS：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtskfzwatj.html

const double = x => x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtqxjcpprg.html

[U95] JS：Promise 包装
来源：http://dali.nwbrower.top/Article/details/gtzcoyyuva.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gtoevnsikj.html

[U96] JS：async/await 与异常
来源：http://dali.dashuyun.cn/Article/details/gtfmculnma.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gttpuhuykd.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtaphkrjuc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtdjrbsoiv.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsggxqlen.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gtgqkxncfs.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gtjyfvvsvk.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gtutrbfsgl.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzekofium.html

document.querySelector(".item")
来源：http://dali.yj202588.top/Article/details/gtiugttjvk.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtqcicdnrq.html

el.classList.toggle("active")
来源：http://dali.birdmap.top/Article/details/gtoguaovar.html

[U102] JS：本地存储
来源：http://dali.jianghu66.top/Article/details/gtuuceejzd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtngebplny.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gtinzjunln.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tianlin.xyz/Article/details/gttmlzuorf.html

[U104] JS：防抖
来源：http://dali.xylfe.cn/Article/details/gtcppuynws.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtsawpcxlw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gtbaafupsa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jqgufenzy.top/Article/details/gtzqrkloir.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gtvodvufdz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ydzc1.top/Article/details/gtmrgnxqde.html

[U107] JS：数字千分位
来源：http://dali.hnxiangtu.top/Article/details/gtqfjmnkja.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.chenzaomai.com/Article/details/gtyrxzfavi.html

[U108] JS：随机整数
来源：http://dali.ehwqpu.com/Article/details/gtwfdkeykk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxuanxn.top/Article/details/gthrxsiojq.html

[U109] JS：数组分组
来源：http://dali.hnxiangtu.top/Article/details/gtvzsuqqqu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.vqdsnc.cn/Article/details/gtryoweddc.html

[U110] JS：数组分块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxagvaupm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gtgtbcsmbv.html

[U111] JS：对象转 Map
来源：http://dali.cucudq.cn/Article/details/gtupimbkcg.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gtbfnhwifp.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gtkmegnbor.html

"7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtjqrhrfop.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gtmlxgsnnz.html

s.replaceAll("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtbnyaicov.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzimwajd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.birdmap.top/Article/details/gtwxchsiea.html

[U115] JS：生成 UUID
来源：http://dali.yueranfly.top/Article/details/gtckopfpnq.html

crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtsknpofvm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guannengcc.top/Article/details/gtgygtvsly.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtbekbznut.html

[U117] JS：单元测试
来源：http://dali.yvedp.cn/Article/details/gtydlvegrg.html

npm i -D vitest;  npx vitest
来源：http://dali.ybcxt.top/Article/details/gtydlathvh.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtgzlmmwdx.html

npm i -D vite;  npx vite
来源：http://dali.haohaochexian.top/Article/details/gthzighwfq.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtxgwnahnj.html

npx vite build
来源：http://dali.havefunace.top/Article/details/gtroyxsske.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gtzetmafxr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gtrajeixle.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgcmzujs.html

统计汇总
来源：http://dali.nanxuanxn.top/Article/details/gtiyqlknag.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbfvpkgam.html

按语言统计（条）：
来源：http://dali.guowangkeji.top/Article/details/gtscimmczj.html

Python ......... 252
来源：http://dali.birdmap.top/Article/details/gtfsdmtbyo.html

PHP ............ 252
来源：http://dali.jqgfzy.top/Article/details/gtiblvghjv.html

JavaScript ..... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtafwwbndg.html

TypeScript ..... 212
来源：http://dali.gaohongyu789.top/Article/details/gtttwhrwoo.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gtskexzlhj.html

Go ............. 212
来源：http://dali.gaohongyu789.top/Article/details/gttypvojfx.html

Ruby ........... 212
来源：http://dali.nanxinkj.top/Article/details/gtgjebbwvo.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtpmookaya.html

C .............. 30
来源：http://dali.gzhubu.top/Article/details/gtplxlkyqe.html

C++ ............ 30
来源：http://dali.jlsjyb.cn/Article/details/gtpdnxsfht.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtqefcdxwx.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiipfgur.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtgoynsipd.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtwutgeqda.html

Lua ............ 10
来源：http://dali.cashguo.top/Article/details/gtyowpfupo.html

Perl ........... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtvmcpgasr.html

Scala .......... 10
来源：http://dali.zdqjudy.top/Article/details/gtzphzvsfv.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtpxwzktfo.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gtctaenttu.html

按章节统计：
来源：http://dali.c1oappe.top/Article/details/gtacgxgznf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtpdlrfbkr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.chenlongwang.top/Article/details/gtnklyipuc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtwqfwiyqh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtmtwzcpzu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.andypj.xyz/Article/details/gtxlmzxsnd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtfiluhhjs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtbsajfbrg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtlytlxvcg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtufthveny.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtolqxmrpd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtsibjmkiu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrzmwwjwd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gttyiczwbv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gtqsmhjnop.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.nanxuanxn.top/Article/details/gthedajfvk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtvcgljabg.html

Q SQL 专题                              90
来源：http://dali.dashuyun.cn/Article/details/gtwjpntgbs.html

R Bash 专题                             80
来源：http://dali.ydzc1.top/Article/details/gtttttagko.html

S C / C++ 专题                          60
来源：http://dali.cheryme.top/Article/details/gtlkmmwlho.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtrasryupe.html

U 高频实用片段                         120
来源：http://dali.hfpthk.cn/Article/details/gtfyseexny.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtvoidybbc.html

合计                                  2106 条
来源：http://dali.svipenyu.cn/Article/details/gtrywvachz.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtjibnrdem.html

使用提醒
来源：http://dali.yongpay.top/Article/details/gtxafeujen.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtchhnsgrn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtkvyrqblw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.svipenyu.cn/Article/details/gttpxhvjzd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.xuetiantiany.cn/Article/details/gtlxeuthva.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yongpay.top/Article/details/gteyxhgzgo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gtzrddfxzt.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gtroxnecet.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbxohqij.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ydzc1.top/Article/details/gteljnpdcy.html

Common Programming Examples Cheat Book
来源：http://dali.chenzaomai.com/Article/details/gtbwftvfgw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtilqhdyvt.html

【收录内容】
来源：http://dali.hfpthk.cn/Article/details/gtocrgcpmr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.hammf.cn/Article/details/gtbdlilgdb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xylfe.cn/Article/details/gtwmhgfujk.html

SQL · Bash · C · C++
来源：http://dali.daxiang520.top/Article/details/gtoufweyuq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gtwyhwxzxd.html

【使用说明】
来源：http://dali.shangyingyoupin.top/Article/details/gtvxroauhm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.aizwys.cn/Article/details/gtkxkwsrfx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gtdvznvojb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cashguo.top/Article/details/gtqhiageix.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.birdmap.top/Article/details/gthzjuhxfu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.birdmap.top/Article/details/gtolsdkksy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cashguo.top/Article/details/gtqsjwfvwr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.redwolf501.top/Article/details/gtxvytfnoo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.cashguo.top/Article/details/gtrckcocyv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.hammf.cn/Article/details/gtxdpidhnp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhixingplan.top/Article/details/gtwaawnpkn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.ehwqpu.com/Article/details/gtluycmouf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtikpdudxa.html

【文件统计】
来源：http://dali.aibaodan.cn/Article/details/gtmtafiizc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jianghu66.top/Article/details/gttudxxxiv.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtmgbcliyq.html

目  录
来源：http://dali.iojbl.cn/Article/details/gtsddjynlh.html

--------------------------------------------------------------------------------
来源：http://dali.iojbl.cn/Article/details/gtbbzquziq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.kuanghao11.cn/Article/details/gtntoahwsm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.aibaodan.cn/Article/details/gtxqvucrcf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtrnqnrezs.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gtdecnjoym.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258888.top/Article/details/gtzbnprxrt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.smart0.xyz/Article/details/gtdjinuolm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.quarkkingdee.top/Article/details/gtkylmeery.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gteutuxryb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtagsqtgpj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.xinyue.icu/Article/details/gtftafknie.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtpujbkqvq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtoutxysce.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtnxagogqq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gzhubu.top/Article/details/gtykgzaxdz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmfunpno.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtncelqtjd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.iojbl.cn/Article/details/gtnujuscoo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.vqdsnc.cn/Article/details/gtxpgjzhnu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shzxlz.cn/Article/details/gtoiibrueg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gtxetknwmd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gtlscrlblm.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzodxeaco.html

A. 基础语法与类型
来源：http://dali.yanxiufei.cn/Article/details/gtpsiaxapl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgmyebdzw.html

[A01] Hello World
来源：http://dali.jiagoushi.top/Article/details/gtglzvdwqz.html

Py:   print("Hello, World!")
来源：http://dali.gogol.net.cn/Article/details/gtunqvqwax.html

PHP:  echo "Hello, World!";
来源：http://dali.sxryk.cn/Article/details/gtrxxpyxxc.html

JS:   console.log("Hello, World!");
来源：http://dali.shangyingyoupin.top/Article/details/gtkekqlzxp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.gaohongyu789.top/Article/details/gtfydtlceq.html

Java: System.out.println("Hello, World!");
来源：http://dali.svipenyu.cn/Article/details/gtmsoeqmfu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aizwys.cn/Article/details/gtaagmynwd.html

Ruby: puts "Hello, World!"
来源：http://dali.ppjwa.cn/Article/details/gtkmkctqqw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtahzthtwi.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gtmzipkyth.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.iojbl.cn/Article/details/gtexpemsxo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gtnvdricrb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhongyouzk.top/Article/details/gtkyckqprg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.gzhubu.top/Article/details/gttnlubclc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtgcrobyjo.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtbvfxuxej.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zycfv.cn/Article/details/gtofsnmgeo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtwkyamjtx.html

[A03] 常量定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaornxkai.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.iojbl.cn/Article/details/gtfxomvjed.html

PHP:  const PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtskaivpee.html

JS:   const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtpzjoptxt.html

TS:   const PI: number = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtdjuispwu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtvaacmfra.html

Go:   const PI = 3.14159
来源：http://dali.cashguo.top/Article/details/gtqkhbqztx.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gtoupwdyfy.html

C#:   const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtcfqavebx.html

[A04] 判断变量类型
来源：http://dali.yj202588.top/Article/details/gtpartrxiy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zdqjudy.top/Article/details/gtketxoyjv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shzxlz.cn/Article/details/gthizjdpte.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.sufxvd.cn/Article/details/gtlubuozet.html

TS:   typeof x; x instanceof Date
来源：http://dali.9152youxi.cn/Article/details/gtsgbvpbfy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ivvv.top/Article/details/gtoraxcytf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gtymoeaxta.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gtbwindnno.html

C#:   x.GetType().Name; x is int
来源：http://dali.yj202588.top/Article/details/gtigneycql.html

[A05] 整数除法与取模
来源：http://dali.yuxming.cn/Article/details/gtaldtdsen.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jlsjyb.cn/Article/details/gtvrjvnqno.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gttkmnelnt.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gtmcrkwrec.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtngqiugwu.html

Java: 7 / 2; 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtaqgumsly.html

Go:   7 / 2; 7 % 2
来源：http://dali.ydzc1.top/Article/details/gtuvfgvuqb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtqukrzdyz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtltyygmqr.html

[A06] 字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtqcwwuhqv.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gteupyuuqt.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jianghu66.top/Article/details/gtrqeizzbq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.0kj1m.cn/Article/details/gtrruusxqi.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.dianchejie.cn/Article/details/gtnqmbbygn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtqzqlokwt.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gtpqvwlfap.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigfzy.top/Article/details/gtjwqxdhul.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtzybbvryl.html

[A07] 数字转字符串
来源：http://dali.guannengcc.top/Article/details/gtlmwildta.html

Py:   str(42)
来源：http://dali.jinqigufen.top/Article/details/gtfhiygltn.html

PHP:  (string) 42; strval(42)
来源：http://dali.aizwys.cn/Article/details/gtzowabidx.html

JS:   String(42); (42).toString()
来源：http://dali.havefunace.top/Article/details/gtivzgfsez.html

TS:   String(42)
来源：http://dali.fzhhl.top/Article/details/gtlpwstamm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtbzkbaeyd.html

Go:   strconv.Itoa(42)
来源：http://dali.redwolf501.top/Article/details/gtsxzyjptm.html

Ruby: 42.to_s
来源：http://dali.9152youxi.cn/Article/details/gtxvrjsqlv.html

C#:   42.ToString()
来源：http://dali.daxiang520.top/Article/details/gtdzgpakpm.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gtagdmdakk.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.aizwys.cn/Article/details/gtzcfjwbbx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gzhubu.top/Article/details/gtknkcafye.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoizlugjo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jianghu66.top/Article/details/gtpdnszgtc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gttrhpklcd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbksqgkbj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhengqikj.top/Article/details/gtupditktb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtwnkytzgg.html

[A09] 绝对值与最大最小值
来源：http://dali.aizwys.cn/Article/details/gtcyffhxxi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jinqigufen.top/Article/details/gtrarwupah.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuheqdwd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cashguo.top/Article/details/gttjkvelbz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hammf.cn/Article/details/gtxofluxjx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gttqscqpbc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.316326.xyz/Article/details/gtycqxztgk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.wangshuangyany.cn/Article/details/gtggbwialt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtjffeapdt.html

[A10] 生成随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlkjxomz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhoulong.xyz/Article/details/gtpavnyeqk.html

PHP:  random_int(1, 100);
来源：http://dali.yj20258.top/Article/details/gtkfnltdss.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenzaomai.com/Article/details/gtxuxhvdcr.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yueranfly.top/Article/details/gtcdeqnhlo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhoulong.xyz/Article/details/gteybqxtwc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yuxming.cn/Article/details/gtyrbmzzmj.html

Ruby: rand(1..100)
来源：http://dali.dashuyun.cn/Article/details/gtaijbeddk.html

C#:   new Random().Next(1, 101)
来源：http://dali.ehwqpu.com/Article/details/gtcqifjehf.html

[A11] 条件表达式（三元）
来源：http://dali.gotoacloud.top/Article/details/gtzwtylfgk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.bjfxy.top/Article/details/gtpgqswzuq.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtbtyvkocu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cqqwz.cn/Article/details/gtffgywrgi.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtdmxprksb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtfcstgyqu.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigufen.top/Article/details/gteikizmfe.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtjzeaqmid.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtoxcxpzdd.html

[A12] 字符串插值 / 格式化
来源：http://dali.mhx1999.top/Article/details/gtjwwyzjds.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.daxiang520.top/Article/details/gtwqgbtulq.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gtiqhignxi.html

JS:   `Hello, ${name}!`
来源：http://dali.gotoacloud.top/Article/details/gtyslchgqk.html

TS:   `Hello, ${name}!`
来源：http://dali.ywan-chungtsiang.top/Article/details/gtciwchjfd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.dashuyun.cn/Article/details/gtlohodutc.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cashguo.top/Article/details/gtegbjzdvj.html

Ruby: "Hello, #{name}!"
来源：http://dali.gogol.net.cn/Article/details/gtmwuiwvzo.html

C#:   $"Hello, {name}!"
来源：http://dali.havefunace.top/Article/details/gthclelhuz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.tian-w.cn/Article/details/gtztuptkwo.html

Py:   "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtosuxqcxy.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gterqozybo.html

JS:   "第一行\n第二行"
来源：http://dali.jiagoushi.top/Article/details/gtnxqjdrid.html

TS:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtzagyybmx.html

Java: "第一行\n第二行"
来源：http://dali.shuidangran.top/Article/details/gtfkfqeawy.html

Go:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtxatywrzt.html

Ruby: "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtrzuailmj.html

C#:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtvpwpfall.html

[A14] 注释写法
来源：http://dali.iojbl.cn/Article/details/gturzbutxd.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgufenzy.top/Article/details/gtoxeurlco.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.smart0.xyz/Article/details/gtfqvxtzfk.html

JS:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnapqbzz.html


<!-- 参考信息 -->