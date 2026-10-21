代发 wailian999

[U87] JS：解构默认值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyfnkrnz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yonumen.top/Article/details/gtpvoebrzt.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtyxvhln.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtciedusmq.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gtympsuwhh.html

[...new Set(arr)]
来源：http://dali.zhengqikj.top/Article/details/gtibciujbn.html

[U90] JS：数字数组排序
来源：http://dali.meibo888.top/Article/details/gtbauujbpa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtzqkofxjb.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gtgisrmjvo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtmrkgcyxe.html

[U92] JS：深拷贝
来源：http://dali.ivvv.top/Article/details/gtejxtvpkw.html

structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gtazqskjkm.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gtbwmrtchb.html

`共 ${n} 条`
来源：http://dali.sufxvd.cn/Article/details/gtcndhgdng.html

[U94] JS：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtfnxokhgs.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtsxokbihj.html

[U95] JS：Promise 包装
来源：http://dali.ydzc1.top/Article/details/gtfubtubhe.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gtevifunuv.html

[U96] JS：async/await 与异常
来源：http://dali.gaohongyu789.top/Article/details/gtznzckdqu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtjvyyntgk.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmgjlqej.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gogol.net.cn/Article/details/gtruxaetoq.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxuanxn.top/Article/details/gtpxagvrgi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gtupahguof.html

[U99] JS：事件监听
来源：http://dali.wangshuangyany.cn/Article/details/gtntqxzgax.html

el.addEventListener("click", e => {})
来源：http://dali.cashguo.top/Article/details/gtweklacav.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gtumkyoaux.html

document.querySelector(".item")
来源：http://dali.hfpthk.cn/Article/details/gtshwtwgcr.html

[U101] JS：classList 操作
来源：http://dali.jyoumei.cn/Article/details/gtwjcgizmg.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtbhrktpnm.html

[U102] JS：本地存储
来源：http://dali.jinqigufen.top/Article/details/gtfwhbvzei.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.bjfxy.top/Article/details/gtomsrpaft.html

[U103] JS：定时器
来源：http://dali.kuanghao11.cn/Article/details/gtnheilnph.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hfpthk.cn/Article/details/gtimugjqfx.html

[U104] JS：防抖
来源：http://dali.sufxvd.cn/Article/details/gtzqyxchfp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gtfvjixibo.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtmjjtysbp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gtgeptcpag.html

[U106] JS：日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtchdvklcw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhiwuduotai.top/Article/details/gtiecdevvf.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtyfcgogcj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jlsjyb.cn/Article/details/gtnjjkanjr.html

[U108] JS：随机整数
来源：http://dali.yj202588.top/Article/details/gtnyxxohxr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gtardcsilu.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtpicidpml.html

Object.groupBy(arr, x => x.type)
来源：http://dali.snrcjt.cn/Article/details/gtbhovgdab.html

[U110] JS：数组分块
来源：http://dali.shangyingyoupin.top/Article/details/gthsmyspqi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihsoazhg.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtcfqxdcna.html

new Map(Object.entries(obj))
来源：http://dali.yonumen.top/Article/details/gtahntmlyz.html

[U112] JS：字符串补位
来源：http://dali.ppjwa.cn/Article/details/gtkurocasc.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtrkzqiwnw.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtgpvfrpfb.html

s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtcjxjeypd.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gtlduiosfv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtxctywxpq.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbvijqnw.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtssgvgttz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtybglhjlj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtkjdblbci.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gtbmegimmh.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gtkkfewuwt.html

[U118] JS：开发服务器
来源：http://dali.sysykeji.top/Article/details/gtsrrqxnel.html

npm i -D vite;  npx vite
来源：http://dali.nanxinkj.top/Article/details/gtiyxdgyth.html

[U119] JS：生产构建
来源：http://dali.tianlin.xyz/Article/details/gtggaihhmo.html

npx vite build
来源：http://dali.iojbl.cn/Article/details/gtdssntfpn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nwbrower.top/Article/details/gtzmgbyplv.html

import.meta.env.VITE_API_URL
来源：http://dali.cucudq.cn/Article/details/gtvgahbmme.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtwbctogbv.html

统计汇总
来源：http://dali.yuanzhike.top/Article/details/gtdpihtynf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlhfmnndb.html

按语言统计（条）：
来源：http://dali.nwbrower.top/Article/details/gtdclpjurf.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gtcrnecrlx.html

PHP ............ 252
来源：http://dali.guannengcc.top/Article/details/gtlktnkqpe.html

JavaScript ..... 252
来源：http://dali.sweek.top/Article/details/gttdrsylof.html

TypeScript ..... 212
来源：http://dali.ivvv.top/Article/details/gthqpzirqq.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtizkjaxxa.html

Go ............. 212
来源：http://dali.cashguo.top/Article/details/gttpvuidkr.html

Ruby ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtlmnfbhmd.html

C# ............. 212
来源：http://dali.jlsjyb.cn/Article/details/gtwmpxlwas.html

C .............. 30
来源：http://dali.zhoulong.xyz/Article/details/gtkuzegclt.html

C++ ............ 30
来源：http://dali.zhongyouzk.top/Article/details/gtwxroaylb.html

SQL ............ 90
来源：http://dali.shzxlz.cn/Article/details/gtyfozxfpn.html

Bash ........... 80
来源：http://dali.chenzaomai.com/Article/details/gtwajmjzbj.html

Kotlin ......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtcgibxijw.html

Swift .......... 15
来源：http://dali.yongpay.top/Article/details/gtaugsxhbw.html

Lua ............ 10
来源：http://dali.yangfankeji.com/Article/details/gtcfkkmihu.html

Perl ........... 10
来源：http://dali.andypj.xyz/Article/details/gtypmfmvjb.html

Scala .......... 10
来源：http://dali.gogol.net.cn/Article/details/gtoaavojzb.html

------------------------------------
来源：http://dali.meibo888.top/Article/details/gtxgyzvszi.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gttgvtapry.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtyfedmiii.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jqgufenzy.top/Article/details/gthuzgdhwq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtrblljmma.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tian-w.cn/Article/details/gtsjngmgcf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtzkscgpnm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.fengsongda.top/Article/details/gtfeukiuzj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtenbjzsxj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yanxiufei.cn/Article/details/gtupkuricr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gteizhepoy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtpyrrkcqe.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gtubzhfmst.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtpjawfjgm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gtihuvyjgw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gtphjgvjcz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.gotoacloud.top/Article/details/gtndvqogxn.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtliunafyk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbreopij.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gttdrigcmm.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtlfrvzvyn.html

S C / C++ 专题                          60
来源：http://dali.xziqi.cn/Article/details/gtqrpjifgt.html

T 其他语言补充                          60
来源：http://dali.ydzc1.top/Article/details/gtagazzldc.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gtebruwepz.html

------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtjkpditgj.html

合计                                  2106 条
来源：http://dali.wangshuangyany.cn/Article/details/gtxccoytql.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtmtbixtja.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gteuveolgd.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtxiukkpqy.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.daxiang520.top/Article/details/gthywgvxkm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ppjwa.cn/Article/details/gtpybzpwwq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tian-w.cn/Article/details/gtpebhetxz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.kuanghao11.cn/Article/details/gtkvzfiarn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hfpthk.cn/Article/details/gtvoohtlql.html

—— 文件结束 ——
来源：http://dali.hongshengwenyu.top/Article/details/gthvbcxutm.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbqcwhmud.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebuorfdy.html

Common Programming Examples Cheat Book
来源：http://dali.xuetiantiany.cn/Article/details/gtgexqejhx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtufvuskwv.html

【收录内容】
来源：http://dali.andypj.xyz/Article/details/gtruaqoodj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shuidangran.top/Article/details/gtgfrnuafl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.316326.xyz/Article/details/gtguuhwoka.html

SQL · Bash · C · C++
来源：http://dali.jyoumei.cn/Article/details/gtsceemzpr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gtgulocome.html

【使用说明】
来源：http://dali.316326.xyz/Article/details/gtscqanwzg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.gogol.net.cn/Article/details/gtgfvgfivx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.andypj.xyz/Article/details/gtchdoewxh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.feifeiyinyue.top/Article/details/gtsneobulm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ybcxt.top/Article/details/gtolwrnjjq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtvqubxinf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yongpay.top/Article/details/gtpurebazt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhixingplan.top/Article/details/gtjlatawtl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gthleibnpv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zdqjudy.top/Article/details/gtwukwwmyw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jqgufenzy.top/Article/details/gtmtrgabxv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.mhx1999.top/Article/details/gtivouwvkz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.yj202588.top/Article/details/gtplcwajrl.html

【文件统计】
来源：http://dali.yueranfly.top/Article/details/gtdszzcbqw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yvedp.cn/Article/details/gtkzbvhvui.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtaejkviak.html

目  录
来源：http://dali.jianghu66.top/Article/details/gtqrwqwwbx.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gttajkzdtn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhongyouzk.top/Article/details/gtzhhqynkt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtlghomoyv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpojltkvl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.ehwqpu.com/Article/details/gtuctzslce.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zycfv.cn/Article/details/gtigamusob.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yueranfly.top/Article/details/gtvvshetem.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtrgspxnuc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnxiangtu.top/Article/details/gtdvukghqp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuanzx.com/Article/details/gtspilpoqp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.iojbl.cn/Article/details/gtadlfyean.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.c1oappe.top/Article/details/gtqflhgwwa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gtqsttrhye.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.gotoacloud.top/Article/details/gthhgwhqty.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.dianchejie.cn/Article/details/gtanifzwfk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbkdviwy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gttrrcmsis.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkbllywo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ivvv.top/Article/details/gtcsclbyff.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ppjwa.cn/Article/details/gtwfvnnpor.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtqulnsgnr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtyifffbab.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtghebcasc.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gtpmohxknk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnnhfnony.html

[A01] Hello World
来源：http://dali.daxiang520.top/Article/details/gtowsiabrt.html

Py:   print("Hello, World!")
来源：http://dali.xziqi.cn/Article/details/gthzesvchw.html

PHP:  echo "Hello, World!";
来源：http://dali.yanxiufei.cn/Article/details/gtqrbxsnaw.html

JS:   console.log("Hello, World!");
来源：http://dali.hywenlv.cn/Article/details/gthxiydekv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yongpay.top/Article/details/gtinwfljns.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtehyrinfn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xuetiantiany.cn/Article/details/gtectircpv.html

Ruby: puts "Hello, World!"
来源：http://dali.yj20258888.top/Article/details/gtvmsdlcyn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gtzcnysnfl.html

[A02] 变量声明与赋值
来源：http://dali.cdnleiting.top/Article/details/gtclcuzhqk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.bjfxy.top/Article/details/gtbaptiblb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.hongshengwenyu.top/Article/details/gtllvwjyqh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.aizwys.cn/Article/details/gtkdbgxvsx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.mhx1999.top/Article/details/gtityepclm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqosmhwup.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxuanxn.top/Article/details/gtgtcnhvdu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jinqigufen.top/Article/details/gtmdphalrx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gtkitgbseq.html

[A03] 常量定义
来源：http://dali.snrcjt.cn/Article/details/gtgemtfxdm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xylfe.cn/Article/details/gtpoaflypz.html

PHP:  const PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtyyppofuz.html

JS:   const PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtcpzawarm.html

TS:   const PI: number = 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtpbdrseln.html

Java: static final double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtdriwtoec.html

Go:   const PI = 3.14159
来源：http://dali.chenjidiqi.icu/Article/details/gtuwxgnoog.html

Ruby: PI = 3.14159
来源：http://dali.yj20258888.top/Article/details/gtqxlhnkfe.html

C#:   const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtfahuawsq.html

[A04] 判断变量类型
来源：http://dali.sysykeji.top/Article/details/gtopmaqmyp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.birdmap.top/Article/details/gtzrtkxdxz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yongpay.top/Article/details/gtpkaetlwg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtpcpuhlyj.html

TS:   typeof x; x instanceof Date
来源：http://dali.hywenlv.cn/Article/details/gtobsjatns.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jiagoushi.top/Article/details/gtfdorejrk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtqqoczjpm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.mhx1999.top/Article/details/gtkooquxuu.html

C#:   x.GetType().Name; x is int
来源：http://dali.yanxiufei.cn/Article/details/gtbsbrxbth.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gttsuvexyb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.jiagoushi.top/Article/details/gtomvmgqxh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yanxiufei.cn/Article/details/gtdifjekvg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtouecmqyj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.ybcxt.top/Article/details/gtgayfbzuh.html

Java: 7 / 2; 7 % 2
来源：http://dali.c1oappe.top/Article/details/gtdxhaheye.html

Go:   7 / 2; 7 % 2
来源：http://dali.dianchejie.cn/Article/details/gtoiuojcmi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtayarilqt.html

C#:   7 / 2; 7 % 2
来源：http://dali.hnqzz.top/Article/details/gtecnxjrfi.html

[A06] 字符串转数字
来源：http://dali.jlsjyb.cn/Article/details/gtztqidqpw.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtdmfisdfs.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.ydzc1.top/Article/details/gtzabgavfi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gtxnqmzrhc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.iojbl.cn/Article/details/gtvqcmtqbj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.quarkkingdee.top/Article/details/gtrwzydswm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yanxiufei.cn/Article/details/gtxirpvlrs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhixingplan.top/Article/details/gtcncjzajz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zycfv.cn/Article/details/gtmrsbluom.html

[A07] 数字转字符串
来源：http://dali.316326.xyz/Article/details/gtnhlvjlce.html

Py:   str(42)
来源：http://dali.gaohongyu789.top/Article/details/gtwioulyst.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxuanxn.top/Article/details/gtsphdsjir.html

JS:   String(42); (42).toString()
来源：http://dali.hammf.cn/Article/details/gtxrmagyqz.html

TS:   String(42)
来源：http://dali.hfpthk.cn/Article/details/gtrelbxers.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xuanzx.com/Article/details/gtmcxedexz.html

Go:   strconv.Itoa(42)
来源：http://dali.yj202588.top/Article/details/gtywygmvqr.html

Ruby: 42.to_s
来源：http://dali.cucudq.cn/Article/details/gtyewdjjrc.html

C#:   42.ToString()
来源：http://dali.redwolf501.top/Article/details/gtkvqeujde.html

[A08] 取整与四舍五入
来源：http://dali.hnxiangtu.top/Article/details/gtmulwoehq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.birdmap.top/Article/details/gtasqgvuje.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yvedp.cn/Article/details/gtdpqlwvbg.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.cdnleiting.top/Article/details/gtvwkdticd.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckwjzueg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gtwafhmtmt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrrzapmi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shangyingyoupin.top/Article/details/gthjxpgftc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gtapeaqype.html

[A09] 绝对值与最大最小值
来源：http://dali.c1oappe.top/Article/details/gtboorbbed.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtwwykrywp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtmvgkrdwq.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsthdgub.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtsshheixm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtnxanifqy.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.fzhhl.top/Article/details/gtzkxsvycq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xuetiantiany.cn/Article/details/gtepfaslre.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtrrydktwl.html

[A10] 生成随机数
来源：http://dali.ehwqpu.com/Article/details/gtewoalger.html

Py:   import random; random.randint(1, 100)
来源：http://dali.daria6918.cn/Article/details/gtmuokrsyn.html

PHP:  random_int(1, 100);
来源：http://dali.jianghu66.top/Article/details/gtfjuugspd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.pycfn.com/Article/details/gteclnidfl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gtwdbkxkxx.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtwnjhirzh.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.aibaodan.cn/Article/details/gttjssqusx.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznuzdjsk.html

C#:   new Random().Next(1, 101)
来源：http://dali.guowangkeji.top/Article/details/gthjdkonsg.html

[A11] 条件表达式（三元）
来源：http://dali.fengsongda.top/Article/details/gttpsbnwqj.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhiwuduotai.top/Article/details/gtaksgvytl.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtlobijpaf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtvydkichh.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gthkqecsln.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtqtovgmlw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yanxiufei.cn/Article/details/gtcqfztpap.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gtxfrgawoj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yonumen.top/Article/details/gtdfsaxpnn.html

[A12] 字符串插值 / 格式化
来源：http://dali.vqdsnc.cn/Article/details/gtkrtxnhrk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zycfv.cn/Article/details/gtymwjnihw.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gtkyxqflmp.html

JS:   `Hello, ${name}!`
来源：http://dali.yueranfly.top/Article/details/gtwqunyghc.html

TS:   `Hello, ${name}!`
来源：http://dali.ybcxt.top/Article/details/gtxytgbudy.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqqgkkuti.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinqigfzy.top/Article/details/gtzdfcljna.html

Ruby: "Hello, #{name}!"
来源：http://dali.gaohongyu789.top/Article/details/gtzdxdsrud.html

C#:   $"Hello, {name}!"
来源：http://dali.hfpthk.cn/Article/details/gtttbxhidv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sxryk.cn/Article/details/gtvtdjyrfj.html

Py:   "第一行\n第二行"
来源：http://dali.tian-w.cn/Article/details/gtodjhqaca.html

PHP:  "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtjqyfibgl.html

JS:   "第一行\n第二行"
来源：http://dali.nanxinkj.top/Article/details/gtokslilai.html

TS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtexwdsdwc.html

Java: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtlvneevxv.html

Go:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gticbntaxy.html

Ruby: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtufeoueeq.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtfjsgunzf.html

[A14] 注释写法
来源：http://dali.yj202588.top/Article/details/gtuwfazrwn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.meibo888.top/Article/details/gttikmshrs.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtedegrocs.html

JS:   // 单行；/* 多行 */
来源：http://dali.ydzc1.top/Article/details/gtowpwkfeo.html

TS:   // 单行；/* 多行 */
来源：http://dali.iojbl.cn/Article/details/gtnqbvhxhp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.mhx1999.top/Article/details/gtqhxdendk.html

Go:   // 单行；/* 多行 */
来源：http://dali.jqgfzy.top/Article/details/gtbwwovnbc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtcrcxxfst.html


<!-- 参考信息 -->