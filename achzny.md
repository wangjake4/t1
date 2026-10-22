代发 wailian999

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gt2zzzaldfx.html

[...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2wasmasmk.html

[U90] JS：数字数组排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2nazcqhwo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2dbrbafam.html

[U91] JS：对象键值遍历
来源：http://dali.gotoacloud.top/Article/details/gt2rzpdmqqe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hongshengwenyu.top/Article/details/gt2mzynalzp.html

[U92] JS：深拷贝
来源：http://dali.aibaodan.cn/Article/details/gt2dhmrtuls.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2eeanvkrm.html

[U93] JS：模板字符串
来源：http://dali.dashuyun.cn/Article/details/gt2grkuzoyc.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gt2usmuvlsr.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gt2kegdqdwg.html

const double = x => x * 2;
来源：http://dali.ydzc1.top/Article/details/gt2pvftricj.html

[U95] JS：Promise 包装
来源：http://dali.wangdashe.top/Article/details/gt2hpesuiwg.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gt2krqjdpec.html

[U96] JS：async/await 与异常
来源：http://dali.chenzaomai.com/Article/details/gt2uofxidmn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gt2xoicszxt.html

[U97] JS：并发请求
来源：http://dali.9152youxi.cn/Article/details/gt2yijzrkyx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gt2mhqfzcyf.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2igqnimwr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nanxuanxn.top/Article/details/gt2wbmpbxzo.html

[U99] JS：事件监听
来源：http://dali.hnxiangtu.top/Article/details/gt2rcfmzeqt.html

el.addEventListener("click", e => {})
来源：http://dali.ivvv.top/Article/details/gt2hbxxwnlp.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gt2tkgbpdah.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gt2kctvbayn.html

[U101] JS：classList 操作
来源：http://dali.zhongyouzk.top/Article/details/gt2htksxnyg.html

el.classList.toggle("active")
来源：http://dali.ydzc1.top/Article/details/gt2wwjpopdd.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gt2zlfvzvsz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gt2gxwomjom.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gt2qstgodtq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hnqzz.top/Article/details/gt2kkjkcith.html

[U104] JS：防抖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aepfmqnw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2yvkolhwt.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gt2sfharaku.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gt2kaleqzfd.html

[U106] JS：日期格式化
来源：http://dali.dashuyun.cn/Article/details/gt2udfpnpjj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.aizwys.cn/Article/details/gt2ysglbgic.html

[U107] JS：数字千分位
来源：http://dali.hywenlv.cn/Article/details/gt2wrdxxnuv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gt2ujtxaxyl.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gt2gdkvceei.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gt2afnpdggf.html

[U109] JS：数组分组
来源：http://dali.iojbl.cn/Article/details/gt2wqxgybpu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cucudq.cn/Article/details/gt2bxemiyyr.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gt2wsytfkyx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgufenzy.top/Article/details/gt2frwtrbks.html

[U111] JS：对象转 Map
来源：http://dali.yvedp.cn/Article/details/gt2qcenfwiw.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gt2ohvxjejp.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mrlwrqsn.html

"7".padStart(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2oicoreij.html

[U113] JS：正则替换全部
来源：http://dali.zdqjudy.top/Article/details/gt2zxdruvkt.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gt2sujfrnqx.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gt2mihllzvd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gt2wqnqtckp.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gt2xhcgctfh.html

crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gt2rmslctgb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.aibaodan.cn/Article/details/gt2jbbbedpq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.wangdashe.top/Article/details/gt2bpfoltzq.html

[U117] JS：单元测试
来源：http://dali.zhixingplan.top/Article/details/gt2waupotvs.html

npm i -D vitest;  npx vitest
来源：http://dali.smart0.xyz/Article/details/gt2iwklgkbt.html

[U118] JS：开发服务器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwdsazbk.html

npm i -D vite;  npx vite
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpaauxpp.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gt2qqazeydq.html

npx vite build
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wndsyedr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gt2koekbmwj.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigufen.top/Article/details/gt2cqmevbpl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2fwejhzgi.html

统计汇总
来源：http://dali.smart0.xyz/Article/details/gt2yyusdlja.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2quxkuatz.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gt2hzfxdqvo.html

Python ......... 252
来源：http://dali.yongpay.top/Article/details/gt2nkvtjzha.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gt2olplusni.html

JavaScript ..... 252
来源：http://dali.bjfxy.top/Article/details/gt2xohoqret.html

TypeScript ..... 212
来源：http://dali.smart0.xyz/Article/details/gt2axkrtiiw.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gt2odjojzvg.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2linupekd.html

Ruby ........... 212
来源：http://dali.316326.xyz/Article/details/gt2xctudxuw.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gt2vcksntrt.html

C .............. 30
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulebddwn.html

C++ ............ 30
来源：http://dali.haohaochexian.top/Article/details/gt2pzwjondg.html

SQL ............ 90
来源：http://dali.cqqwz.cn/Article/details/gt2caabgwbm.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gt2dmzicgmd.html

Kotlin ......... 15
来源：http://dali.zycfv.cn/Article/details/gt2wrmoalfx.html

Swift .......... 15
来源：http://dali.nanxinkj.top/Article/details/gt2qcjfakhw.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gt2pixroyfc.html

Perl ........... 10
来源：http://dali.c1oappe.top/Article/details/gt2jlqkywab.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gt2tpzrkqel.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gt2thquxprd.html

合计 ........... 2106 条
来源：http://dali.shangyingyoupin.top/Article/details/gt2hyovwzfk.html

按章节统计：
来源：http://dali.9152youxi.cn/Article/details/gt2pypkkkhv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yj20258.top/Article/details/gt2xjpqvnah.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aibaodan.cn/Article/details/gt2jmlrzslk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hfpthk.cn/Article/details/gt2rivlcqnm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gt2ciobfhmt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhiwuduotai.top/Article/details/gt2wakrchut.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gt2dvhlefdw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gt2pmeomlwb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gt2ombtjhpk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dkmalynz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gt2ptxtnpnr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2qysmtwkr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.andypj.xyz/Article/details/gt2xdpvrsuh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2fezvrgsi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.aibaodan.cn/Article/details/gt2sjxrjfhu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjrttirh.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gt2qfxtpwif.html

Q SQL 专题                              90
来源：http://dali.yongpay.top/Article/details/gt2eqmussub.html

R Bash 专题                             80
来源：http://dali.0kj1m.cn/Article/details/gt2bobssoou.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gt2kdwtmyff.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gt2tdfpgdar.html

U 高频实用片段                         120
来源：http://dali.9152youxi.cn/Article/details/gt2arwgzzvy.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2mixykncs.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gt2ebdwyizg.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzhubpll.html

使用提醒
来源：http://dali.ydzc1.top/Article/details/gt2euhzdudw.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gt2nzprlnde.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.andypj.xyz/Article/details/gt2ipziyxoi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gt2kncojneh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gt2bbnnmzvs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.havefunace.top/Article/details/gt2tujxplgw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dashuyun.cn/Article/details/gt2pwqkovnp.html

—— 文件结束 ——
来源：http://dali.sysykeji.top/Article/details/gt2pfjrfpbh.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2fqeydaca.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.cashguo.top/Article/details/gt2doyssovw.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gt2pdpfimfy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pqknezcg.html

【收录内容】
来源：http://dali.sufxvd.cn/Article/details/gt2xugrciku.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gt2lotbwbmn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gt2picviscb.html

SQL · Bash · C · C++
来源：http://dali.jianghu66.top/Article/details/gt2hlbvgyvf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.xuetiantiany.cn/Article/details/gt2jxrehgbm.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gt2nhjkjqvz.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.cashguo.top/Article/details/gt2ikgwmqyd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.dianchejie.cn/Article/details/gt2ebveerbg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gt2ykmpsuwf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gt2slesspvu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gt2kyvqvsho.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.c1oappe.top/Article/details/gt2zpxntrjq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.iojbl.cn/Article/details/gt2peolxxrq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.svipenyu.cn/Article/details/gt2hdwoxkaz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jiagoushi.top/Article/details/gt2wqokjcam.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.aizwys.cn/Article/details/gt2zhtgrjdf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbustzej.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.xinyue.icu/Article/details/gt2iwmwfjum.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gt2ruyuaskr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuxming.cn/Article/details/gt2ewwbaxlk.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2glazjcce.html

目  录
来源：http://dali.shangyingyoupin.top/Article/details/gt2tyktbkbz.html

--------------------------------------------------------------------------------
来源：http://dali.snrcjt.cn/Article/details/gt2hdzelbth.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gt2uavcetpo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.sxryk.cn/Article/details/gt2kpejyjvh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqcdcfas.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2krvchqwm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj20258.top/Article/details/gt2mkssvgow.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2gtqkhgry.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gt2wbhfjluo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.smart0.xyz/Article/details/gt2enxbitkn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.iojbl.cn/Article/details/gt2lbpscwrr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hjdufcaj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2bvgakywm.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gt2poyfqovb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2pmrzovve.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.aizwys.cn/Article/details/gt2nfqjgtrw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.yangfankeji.com/Article/details/gt2ixvysboz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gt2eajcwnhz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.havefunace.top/Article/details/gt2rdlszpqa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sweek.top/Article/details/gt2ceaqebdt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.gzhubu.top/Article/details/gt2ieycfgvh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2iuvuatsh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gt2eucztkyk.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2jutfylrd.html

A. 基础语法与类型
来源：http://dali.ivvv.top/Article/details/gt2xpturhmy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2itiazdbr.html

[A01] Hello World
来源：http://dali.daria6918.cn/Article/details/gt2rliqsmfq.html

Py:   print("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gt2juscninh.html

PHP:  echo "Hello, World!";
来源：http://dali.guowangkeji.top/Article/details/gt2rmmsmrmg.html

JS:   console.log("Hello, World!");
来源：http://dali.gzhubu.top/Article/details/gt2ntylvxra.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yuxming.cn/Article/details/gt2swgmqnaw.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258888.top/Article/details/gt2qgpxtwud.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhoulong.xyz/Article/details/gt2ezxjlvgm.html

Ruby: puts "Hello, World!"
来源：http://dali.dashuyun.cn/Article/details/gt2txdrogkb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gt2prrcyqca.html

[A02] 变量声明与赋值
来源：http://dali.daria6918.cn/Article/details/gt2wacfyulk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.andypj.xyz/Article/details/gt2zyixctba.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ikywxzjg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj202588.top/Article/details/gt2oanqysew.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zdqjudy.top/Article/details/gt2urktdsqa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jqgfzy.top/Article/details/gt2cuyrrggy.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinghuilouyu.cn/Article/details/gt2etltxlav.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hnxiangtu.top/Article/details/gt2ekhqymoo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.ybcxt.top/Article/details/gt2mebyfokr.html

[A03] 常量定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nrwpoufm.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gt2qdjgamdy.html

PHP:  const PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2tfyqqcpn.html

JS:   const PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gt2ulajfiet.html

TS:   const PI: number = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gt2pnjbqykf.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gt2yualwlli.html

Go:   const PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gt2jqrfssam.html

Ruby: PI = 3.14159
来源：http://dali.dashuyun.cn/Article/details/gt2klovqakc.html

C#:   const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gt2dnudexmq.html

[A04] 判断变量类型
来源：http://dali.yueranfly.top/Article/details/gt2uwlgbnmd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.nanxuanxn.top/Article/details/gt2rewftfhs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.sufxvd.cn/Article/details/gt2xjkixeou.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jianghu66.top/Article/details/gt2bygywdoj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gt2bgkydcky.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2teityetf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gt2yuhrvfvq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jinqigfzy.top/Article/details/gt2eovndbig.html

C#:   x.GetType().Name; x is int
来源：http://dali.aibaodan.cn/Article/details/gt2ygjhyiod.html

[A05] 整数除法与取模
来源：http://dali.316326.xyz/Article/details/gt2xnubjyam.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.cucudq.cn/Article/details/gt2uwdoufcn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2iluwlgqk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gt2okehgyhm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2vsyznymw.html

Java: 7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gt2ibnqswbr.html

Go:   7 / 2; 7 % 2
来源：http://dali.gzhubu.top/Article/details/gt2mxizirha.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenzaomai.com/Article/details/gt2vlvajado.html

C#:   7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2pbenntby.html

[A06] 字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gt2xhmxgqha.html

Py:   int("42"); float("3.14")
来源：http://dali.0kj1m.cn/Article/details/gt2iwuwwnwr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dianchejie.cn/Article/details/gt2ckrlbyem.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yj202588.top/Article/details/gt2sqmxbyou.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ybcxt.top/Article/details/gt2zzssjfec.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gt2levejeac.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzicbecs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xvvuwsih.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gt2mypfqgpd.html

[A07] 数字转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2pjtkujhs.html

Py:   str(42)
来源：http://dali.birdmap.top/Article/details/gt2kxlhiqli.html

PHP:  (string) 42; strval(42)
来源：http://dali.aibaodan.cn/Article/details/gt2utqdioji.html

JS:   String(42); (42).toString()
来源：http://dali.tanke756.top/Article/details/gt2hwnslwph.html

TS:   String(42)
来源：http://dali.aizwys.cn/Article/details/gt2wcamuazp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.gogol.net.cn/Article/details/gt2tddqyjtn.html

Go:   strconv.Itoa(42)
来源：http://dali.fzhhl.top/Article/details/gt2aiiaumhz.html

Ruby: 42.to_s
来源：http://dali.redwolf501.top/Article/details/gt2lauvrlgs.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gt2jzcpcfqn.html

[A08] 取整与四舍五入
来源：http://dali.gotoacloud.top/Article/details/gt2feijfezj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2abzedoyc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xinyue.icu/Article/details/gt2sxaxvpwl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2rqjwavih.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gt2tuazrliw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gt2vtfnnrfs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2dfdoljgi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cashguo.top/Article/details/gt2lfoajffj.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yqlzhoto.html

[A09] 绝对值与最大最小值
来源：http://dali.yj202588.top/Article/details/gt2lnnfxtoo.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2jeczduek.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2thbnmhuv.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2mkpntarm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gt2mmncwgkz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.bjfxy.top/Article/details/gt2kvpwjbfk.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.yj202588.top/Article/details/gt2xdrdmvfg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gt2lejhzrwt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sweek.top/Article/details/gt2qwadnkkl.html

[A10] 生成随机数
来源：http://dali.pycfn.com/Article/details/gt2gvcuchsg.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhixingplan.top/Article/details/gt2egezfdmy.html

PHP:  random_int(1, 100);
来源：http://dali.yuxming.cn/Article/details/gt2aekhruxu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylsvvsgj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xziqi.cn/Article/details/gt2jlxeczle.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhnipldv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqoddool.html

Ruby: rand(1..100)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nliqdpjz.html

C#:   new Random().Next(1, 101)
来源：http://dali.hnqzz.top/Article/details/gt2ykmbktab.html

[A11] 条件表达式（三元）
来源：http://dali.aizwys.cn/Article/details/gt2uqqllodv.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.jqgfzy.top/Article/details/gt2ajtdpfkr.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gt2djulimkl.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shuidangran.top/Article/details/gt2gadyuweg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gt2rejzdzwg.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zdqjudy.top/Article/details/gt2nzfwcyrr.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.shuidangran.top/Article/details/gt2ulhqsney.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2litgrild.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gt2wlwxfwul.html

[A12] 字符串插值 / 格式化
来源：http://dali.xinyue.icu/Article/details/gt2kjiywxpu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxqrrxjz.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhongyouzk.top/Article/details/gt2xycsljga.html

JS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gt2iaulrfmx.html

TS:   `Hello, ${name}!`
来源：http://dali.smart0.xyz/Article/details/gt2grtihkci.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.gzhubu.top/Article/details/gt2sltomrpw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yuanzhike.top/Article/details/gt2nvueznhm.html

Ruby: "Hello, #{name}!"
来源：http://dali.yuanzhike.top/Article/details/gt2hxjcjsmd.html

C#:   $"Hello, {name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2vofrvqun.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shzxlz.cn/Article/details/gt2lkxiyrkd.html

Py:   "第一行\n第二行"
来源：http://dali.guannengcc.top/Article/details/gt2pseyfhoc.html

PHP:  "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2kqubgdfh.html

JS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gt2lceswqcc.html

TS:   "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihxadejh.html

Java: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfdbcnyv.html

Go:   "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2hyeszjeg.html

Ruby: "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2xwwrskyy.html

C#:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufcnhzhb.html

[A14] 注释写法
来源：http://dali.bjfxy.top/Article/details/gt2bvizvims.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zdqjudy.top/Article/details/gt2exahygeg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gt2rtypioga.html

JS:   // 单行；/* 多行 */
来源：http://dali.pycfn.com/Article/details/gt2mexygjpu.html

TS:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gt2unqbsnib.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ybcxt.top/Article/details/gt2tlswlxby.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzgsvsyv.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.haohaochexian.top/Article/details/gt2jvqdzdrt.html

C#:   // 单行；/* 多行 */
来源：http://dali.havefunace.top/Article/details/gt2mfdgqozt.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gt2boungnaz.html

Py:   value = data or "默认值"
来源：http://dali.ydzc1.top/Article/details/gt2qcwzvmrg.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gt2kugucwef.html


<!-- 参考信息 -->