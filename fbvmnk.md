代发 wailian999

[U87] JS：解构默认值
来源：http://dali.hywenlv.cn/Article/details/gtuxosepoq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.iojbl.cn/Article/details/gtjewlhvax.html

[U88] JS：对象展开合并
来源：http://dali.xuanzx.com/Article/details/gtuqlqmxfq.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtekovksrn.html

[U89] JS：数组去重
来源：http://dali.jlsjyb.cn/Article/details/gtelzdjekn.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtiafhzknw.html

[U90] JS：数字数组排序
来源：http://dali.xylfe.cn/Article/details/gtvwquuzyx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gteaysofve.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gtrdbsarjd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.fengsongda.top/Article/details/gtepbvecnr.html

[U92] JS：深拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtvmwpaydh.html

structuredClone(obj)
来源：http://dali.yonumen.top/Article/details/gtjkeedimk.html

[U93] JS：模板字符串
来源：http://dali.cheryme.top/Article/details/gtwbikjxbs.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gtjbmnuuag.html

[U94] JS：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gttoxectox.html

const double = x => x * 2;
来源：http://dali.sweek.top/Article/details/gthhsydsjo.html

[U95] JS：Promise 包装
来源：http://dali.jiagoushi.top/Article/details/gtnlmkeohn.html

new Promise((resolve, reject) => {})
来源：http://dali.ivvv.top/Article/details/gtarckmxvv.html

[U96] JS：async/await 与异常
来源：http://dali.hysaishi.cn/Article/details/gttpnlgdlk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hywenlv.cn/Article/details/gtepyzkkdk.html

[U97] JS：并发请求
来源：http://dali.pengpengdd.cyou/Article/details/gtzdfemvtf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guannengcc.top/Article/details/gtvkhlbcfw.html

[U98] JS：fetch 带 JSON
来源：http://dali.yj20258888.top/Article/details/gtnmueetdo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gtkpviflln.html

[U99] JS：事件监听
来源：http://dali.kuanghao11.cn/Article/details/gtlxgqygcm.html

el.addEventListener("click", e => {})
来源：http://dali.quarkkingdee.top/Article/details/gtkxskjtdz.html

[U100] JS：DOM 查询
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkqkysax.html

document.querySelector(".item")
来源：http://dali.jlsjyb.cn/Article/details/gtesvplkaf.html

[U101] JS：classList 操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdajvqfvr.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gttkxlcqsa.html

[U102] JS：本地存储
来源：http://dali.hongshengwenyu.top/Article/details/gtohgaxupf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvjhqflwk.html

[U103] JS：定时器
来源：http://dali.hammf.cn/Article/details/gtzegmhbtp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sxryk.cn/Article/details/gtjugncwno.html

[U104] JS：防抖
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgaubwuio.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtikrzoido.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gtpwrdlbln.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtzyowkjhz.html

[U106] JS：日期格式化
来源：http://dali.cucudq.cn/Article/details/gtwxqlhhfs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.mhx1999.top/Article/details/gtnzkqgqdg.html

[U107] JS：数字千分位
来源：http://dali.yuxming.cn/Article/details/gtylsjibxt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtcrxwzpea.html

[U108] JS：随机整数
来源：http://dali.zhoulong.xyz/Article/details/gtyfzvqttq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jqgfzy.top/Article/details/gtahkczoss.html

[U109] JS：数组分组
来源：http://dali.haohaochexian.top/Article/details/gtucaygaui.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtmkuagyxp.html

[U110] JS：数组分块
来源：http://dali.sufxvd.cn/Article/details/gtvqdmtlnz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gtcemkuprq.html

[U111] JS：对象转 Map
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwxutqog.html

new Map(Object.entries(obj))
来源：http://dali.jqgfzy.top/Article/details/gtczmsnogh.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtixpqyyyt.html

"7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtykisulor.html

[U113] JS：正则替换全部
来源：http://dali.ydzc1.top/Article/details/gtiduzqlzp.html

s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtpkdkdher.html

[U114] JS：JSON 深比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguipwsva.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtzehkwjds.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfivyfnw.html

crypto.randomUUID()
来源：http://dali.yongpay.top/Article/details/gthbaqeyex.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hysaishi.cn/Article/details/gtmiigcxyi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hywenlv.cn/Article/details/gtbwsioizb.html

[U117] JS：单元测试
来源：http://dali.aibaodan.cn/Article/details/gtmzcgimyf.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258.top/Article/details/gtwvlstyoy.html

[U118] JS：开发服务器
来源：http://dali.tanke756.top/Article/details/gtrjthezdt.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtbmmdjeyl.html

[U119] JS：生产构建
来源：http://dali.nwbrower.top/Article/details/gtqbnidenh.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtqchegfce.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.nanxinkj.top/Article/details/gtxfgrzvqg.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtlnggbbsr.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxrtpillw.html

统计汇总
来源：http://dali.jqgufenzy.top/Article/details/gtcwthrxak.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgvktyiel.html

按语言统计（条）：
来源：http://dali.tianlin.xyz/Article/details/gtftxocuix.html

Python ......... 252
来源：http://dali.c1oappe.top/Article/details/gtdxfxppgm.html

PHP ............ 252
来源：http://dali.fzhhl.top/Article/details/gtxnejwtdx.html

JavaScript ..... 252
来源：http://dali.jinqigufen.top/Article/details/gtqnvrwmkx.html

TypeScript ..... 212
来源：http://dali.zhoulong.xyz/Article/details/gtrcfimroo.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gtvngeuzvf.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gttfnjgyso.html

Ruby ........... 212
来源：http://dali.aibaodan.cn/Article/details/gtoasfjyog.html

C# ............. 212
来源：http://dali.daria6918.cn/Article/details/gtnecyoqhw.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtvfktwgan.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gtdmosdznx.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gtgtgoacqn.html

Bash ........... 80
来源：http://dali.hfpthk.cn/Article/details/gtucunhohr.html

Kotlin ......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gteglmjyno.html

Swift .......... 15
来源：http://dali.jinqigfzy.top/Article/details/gthrjudpck.html

Lua ............ 10
来源：http://dali.mhx1999.top/Article/details/gtntpjwcic.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gtxkkhwkvv.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gthmlgtvus.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtisnlgtub.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtakavzotv.html

按章节统计：
来源：http://dali.chenjidiqi.icu/Article/details/gtvghbvwqm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtnikgyoxr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gttjjyznaf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tianlin.xyz/Article/details/gtyawpqujb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtdbotbbcq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daria6918.cn/Article/details/gtwlqjffqr.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cqqwz.cn/Article/details/gtfjplnfxn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtrkvwgcwy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gttgerfbrs.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nwbrower.top/Article/details/gtrsmosbnj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtkkpshqmr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtovunltys.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtzjpocdjm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtfngdprrw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtkcpvkxbe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gtqiwhqpea.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtjomydyzt.html

Q SQL 专题                              90
来源：http://dali.yanxiufei.cn/Article/details/gtbqugtqjj.html

R Bash 专题                             80
来源：http://dali.chenjidiqi.icu/Article/details/gtoiqaqvdi.html

S C / C++ 专题                          60
来源：http://dali.tanke756.top/Article/details/gtuqbnxplx.html

T 其他语言补充                          60
来源：http://dali.pengpengdd.cyou/Article/details/gtfawbnvle.html

U 高频实用片段                         120
来源：http://dali.wangshuangyany.cn/Article/details/gtxzbxedou.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtuvlkzwyr.html

合计                                  2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtpgrzsqqa.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtgsexmxby.html

使用提醒
来源：http://dali.sxryk.cn/Article/details/gtxufvzlml.html

--------------------------------------------------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtlmjoihus.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gtglxdgdrm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hnqzz.top/Article/details/gtqlzcdmsm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jiagoushi.top/Article/details/gtcpxykpmy.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yuanzhike.top/Article/details/gtxxsspuog.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sxryk.cn/Article/details/gtetffnthy.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtyohvksom.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtspoeygut.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.yueranfly.top/Article/details/gtaddzmtej.html

Common Programming Examples Cheat Book
来源：http://dali.pengpengdd.cyou/Article/details/gtanwxlztj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrphnumli.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gtnrdctwrb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sufxvd.cn/Article/details/gtitffykdj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yvedp.cn/Article/details/gtnjsejzhj.html

SQL · Bash · C · C++
来源：http://dali.gogol.net.cn/Article/details/gtkwpjtmnu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.chenlongwang.top/Article/details/gtietuudxd.html

【使用说明】
来源：http://dali.nanxinkj.top/Article/details/gtqkidyybi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtnecpjazr.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.andypj.xyz/Article/details/gtczdjpqze.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.daria6918.cn/Article/details/gtfcijlbeh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gogol.net.cn/Article/details/gtltxscwfl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.hysaishi.cn/Article/details/gtiwxzrkoj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zycfv.cn/Article/details/gtyhokbaot.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.chenjidiqi.icu/Article/details/gtzodhyhnd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hysaishi.cn/Article/details/gtwfithlpo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xinyue.icu/Article/details/gtosxhrjbj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvljrjykm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.dashuyun.cn/Article/details/gtguliwwzi.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.iojbl.cn/Article/details/gtdbyvdjhw.html

【文件统计】
来源：http://dali.gzhubu.top/Article/details/gtcnnnxghi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.wangshuangyany.cn/Article/details/gteppnobsm.html

--------------------------------------------------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtmzzgqixw.html

目  录
来源：http://dali.mhx1999.top/Article/details/gtpumnnogl.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtzltiqloy.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtvjmfuxwh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtshkhdejb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yvedp.cn/Article/details/gtnpxpsosc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gogol.net.cn/Article/details/gtrkqxgwgu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtrnamfift.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvglpoubd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gtslfvclee.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sufxvd.cn/Article/details/gtjhgjdazg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nwbrower.top/Article/details/gtzbhfyauk.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiapszapn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtxxrkgjqm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtkbruizul.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gttosxbkfu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yonumen.top/Article/details/gtzzzosyws.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnxiangtu.top/Article/details/gtzaymarmk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtuilzkoll.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtlvqvvnnb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzixnsct.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sufxvd.cn/Article/details/gtziylvjwa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gthkotejqf.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtyqonhbkx.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxlnihecq.html

A. 基础语法与类型
来源：http://dali.zdqjudy.top/Article/details/gtovavupbu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmecepvyn.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gtgdkvpvkt.html

Py:   print("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtpaiohhue.html

PHP:  echo "Hello, World!";
来源：http://dali.zhixingplan.top/Article/details/gtbrkotmuf.html

JS:   console.log("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtllzggawm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gtylndldij.html

Java: System.out.println("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtyafydoml.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.pycfn.com/Article/details/gtusmqkroi.html

Ruby: puts "Hello, World!"
来源：http://dali.vqdsnc.cn/Article/details/gtnwzxoqrd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.haohaochexian.top/Article/details/gtrduhgrmq.html

[A02] 变量声明与赋值
来源：http://dali.xuetiantiany.cn/Article/details/gtfyrubowu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gthzzisrfd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yvedp.cn/Article/details/gtbwltagnb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtgwvoedxc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gtvgoscicn.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.fengsongda.top/Article/details/gttwxslpnp.html

Go:   name := "Alex"; age := 20
来源：http://dali.cqqwz.cn/Article/details/gtvzzsenpa.html

Ruby: name = "Alex"; age = 20
来源：http://dali.nwbrower.top/Article/details/gtfnsminbq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtbahveiae.html

[A03] 常量定义
来源：http://dali.yj20258.top/Article/details/gtfyezwtvn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtevwpcddw.html

PHP:  const PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtoeljfrdc.html

JS:   const PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtecyygbmr.html

TS:   const PI: number = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtvofuksph.html

Java: static final double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtyjapagrn.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtpzaqawop.html

Ruby: PI = 3.14159
来源：http://dali.guowangkeji.top/Article/details/gtyaavjqil.html

C#:   const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtgpqjbllr.html

[A04] 判断变量类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraulqzbt.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.xuanzx.com/Article/details/gtfcfixgot.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yueranfly.top/Article/details/gtynlttwoe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtljziymzx.html

TS:   typeof x; x instanceof Date
来源：http://dali.c1oappe.top/Article/details/gtrzycfbyb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.316326.xyz/Article/details/gtkhqsgbwr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gaohongyu789.top/Article/details/gtbfimnghh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhoulong.xyz/Article/details/gtzgmzfrok.html

C#:   x.GetType().Name; x is int
来源：http://dali.pengpengdd.cyou/Article/details/gtunznyfes.html

[A05] 整数除法与取模
来源：http://dali.c1oappe.top/Article/details/gtxipavguh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hongshengwenyu.top/Article/details/gtmhrxqisa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.sysykeji.top/Article/details/gttfpgaean.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gaohongyu789.top/Article/details/gttmzjpayc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtyeqqmluq.html

Java: 7 / 2; 7 % 2
来源：http://dali.hammf.cn/Article/details/gtpcmgziub.html

Go:   7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtejifehyc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtmeuqlvjg.html

C#:   7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtcaiwoqoj.html

[A06] 字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtdtghjgxe.html

Py:   int("42"); float("3.14")
来源：http://dali.cashguo.top/Article/details/gtldgomgug.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.aibaodan.cn/Article/details/gtvphaevro.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.andypj.xyz/Article/details/gtflpesdni.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.sweek.top/Article/details/gtrecqndsf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.hnxiangtu.top/Article/details/gtigxgjsde.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.316326.xyz/Article/details/gtitxiblbr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shzxlz.cn/Article/details/gtimtndszu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhengqikj.top/Article/details/gtvuqgszzq.html

[A07] 数字转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqzhmtmc.html

Py:   str(42)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeiguvyh.html

PHP:  (string) 42; strval(42)
来源：http://dali.wangshuangyany.cn/Article/details/gtsexadpzu.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsuopvzh.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gtgombvjed.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxiwdfjv.html

Go:   strconv.Itoa(42)
来源：http://dali.mhx1999.top/Article/details/gtdnuchpbs.html

Ruby: 42.to_s
来源：http://dali.chenlongwang.top/Article/details/gtmnmjvusk.html

C#:   42.ToString()
来源：http://dali.cqqwz.cn/Article/details/gtbciabshq.html

[A08] 取整与四舍五入
来源：http://dali.ydzc1.top/Article/details/gtvpyngoxt.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhengqikj.top/Article/details/gtdmlettrf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cucudq.cn/Article/details/gtgapjftag.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtxmcitlti.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuanzhike.top/Article/details/gtsdasdjmo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtbcjqtjkp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtjhfzspio.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.pycfn.com/Article/details/gtndkhwanp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.meibo888.top/Article/details/gtxiafmgix.html

[A09] 绝对值与最大最小值
来源：http://dali.redwolf501.top/Article/details/gteoskdbyk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkxhbtxt.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ivvv.top/Article/details/gthppdyzje.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtfliudedy.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtiissfjkl.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtqlzjoewe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.andypj.xyz/Article/details/gtftxuwdcq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sufxvd.cn/Article/details/gtjuvoxeez.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gthdvirzmb.html

[A10] 生成随机数
来源：http://dali.sysykeji.top/Article/details/gtmoubwcmq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.svipenyu.cn/Article/details/gtsuipgsjz.html

PHP:  random_int(1, 100);
来源：http://dali.pycfn.com/Article/details/gthfkcmnno.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gtlnosmros.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ppjwa.cn/Article/details/gtmskxkdez.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjycznxg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.cashguo.top/Article/details/gtdhqoyffk.html

Ruby: rand(1..100)
来源：http://dali.shangyingyoupin.top/Article/details/gtqenwyxai.html

C#:   new Random().Next(1, 101)
来源：http://dali.cqqwz.cn/Article/details/gtkdniyrxr.html

[A11] 条件表达式（三元）
来源：http://dali.sweek.top/Article/details/gtuhbteaux.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.316326.xyz/Article/details/gtwkcnrqce.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtpzwfplps.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtopfjkkuu.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daria6918.cn/Article/details/gtzzmnibyw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtdghcgtwd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnxiangtu.top/Article/details/gtcxgatwdm.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.quarkkingdee.top/Article/details/gtpsnmmvrt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtcoldvsbl.html

[A12] 字符串插值 / 格式化
来源：http://dali.dashuyun.cn/Article/details/gtqyxmmqzp.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gtzmklydff.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dianchejie.cn/Article/details/gtgahbxjqk.html

JS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gtfcdsnjdf.html

TS:   `Hello, ${name}!`
来源：http://dali.shuidangran.top/Article/details/gtctnakwpu.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.jqgfzy.top/Article/details/gtmbhlundg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.cucudq.cn/Article/details/gtvvklezme.html

Ruby: "Hello, #{name}!"
来源：http://dali.zhengqikj.top/Article/details/gtoatsykkx.html

C#:   $"Hello, {name}!"
来源：http://dali.cqqwz.cn/Article/details/gtuhtfejjz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gzhubu.top/Article/details/gttmoudyrc.html

Py:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtjaeltbzr.html

PHP:  "第一行\n第二行"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylkdbdaj.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gtclbeedhi.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtnwlxwvvt.html

Java: "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gtkfqmzcwl.html

Go:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtwnajxbch.html

Ruby: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtksyvsias.html

C#:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtjlwjggmg.html

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gtivnxkwao.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ybcxt.top/Article/details/gtgxwtjkbe.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xuanzx.com/Article/details/gtnsdrlznd.html

JS:   // 单行；/* 多行 */
来源：http://dali.tanke756.top/Article/details/gthdmgepog.html

TS:   // 单行；/* 多行 */
来源：http://dali.0kj1m.cn/Article/details/gttdrirsoq.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.chenjidiqi.icu/Article/details/gtmiqzecom.html

Go:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtkywkxksf.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zhixingplan.top/Article/details/gtvbgnsidy.html


<!-- 参考信息 -->