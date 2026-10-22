代发 wailian999

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gtstwrvxpp.html

a?.b?.c
来源：http://dali.ppjwa.cn/Article/details/gtdxnxxgje.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gtxxscyjaa.html

a ?? b
来源：http://dali.nwbrower.top/Article/details/gtfuaywxvw.html

[U87] JS：解构默认值
来源：http://dali.zhixingplan.top/Article/details/gtyqthvjwg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gtuhtygzwd.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtdvguemiw.html

{ ...a, ...b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpthmuxl.html

[U89] JS：数组去重
来源：http://dali.yvedp.cn/Article/details/gtvcsfjndy.html

[...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtkohhhwve.html

[U90] JS：数字数组排序
来源：http://dali.zdqjudy.top/Article/details/gtlvtodtkx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtxxtsvuix.html

[U91] JS：对象键值遍历
来源：http://dali.cucudq.cn/Article/details/gtmemzmrrw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gtdhrdoeal.html

[U92] JS：深拷贝
来源：http://dali.haohaochexian.top/Article/details/gtcwfxftia.html

structuredClone(obj)
来源：http://dali.shzxlz.cn/Article/details/gtfkhwvvud.html

[U93] JS：模板字符串
来源：http://dali.jianghu66.top/Article/details/gtgmdunexg.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtdjpxcqdn.html

[U94] JS：箭头函数
来源：http://dali.xinyue.icu/Article/details/gtxnfwwhnc.html

const double = x => x * 2;
来源：http://dali.zdqjudy.top/Article/details/gtfsrbjlhc.html

[U95] JS：Promise 包装
来源：http://dali.xziqi.cn/Article/details/gtloowojha.html

new Promise((resolve, reject) => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtbihfbnpj.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gtmbovkukp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gtngtgukbq.html

[U97] JS：并发请求
来源：http://dali.zycfv.cn/Article/details/gtkhtyyywr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtbrlumppb.html

[U98] JS：fetch 带 JSON
来源：http://dali.daria6918.cn/Article/details/gtqwzozyll.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.mhx1999.top/Article/details/gtlrvcrdfw.html

[U99] JS：事件监听
来源：http://dali.andypj.xyz/Article/details/gttaivsusv.html

el.addEventListener("click", e => {})
来源：http://dali.zdqjudy.top/Article/details/gtbdswfafi.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gtjecvawjf.html

document.querySelector(".item")
来源：http://dali.birdmap.top/Article/details/gtmbaoujlg.html

[U101] JS：classList 操作
来源：http://dali.sufxvd.cn/Article/details/gtvwysmrip.html

el.classList.toggle("active")
来源：http://dali.cheryme.top/Article/details/gttcjxclfi.html

[U102] JS：本地存储
来源：http://dali.feifeiyinyue.top/Article/details/gtghsrwneo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xinyue.icu/Article/details/gtqfcrqhjq.html

[U103] JS：定时器
来源：http://dali.hfpthk.cn/Article/details/gttmovqezp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkegwgac.html

[U104] JS：防抖
来源：http://dali.jqgufenzy.top/Article/details/gtjoehpcfy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gtidnqaqvt.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gtbxgiyyuu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tanke756.top/Article/details/gtlfoavhoc.html

[U106] JS：日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gttxhvqpqv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gtfiowoxxt.html

[U107] JS：数字千分位
来源：http://dali.jlsjyb.cn/Article/details/gttynuusyd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hywenlv.cn/Article/details/gtmyfbrwwf.html

[U108] JS：随机整数
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtxkncsz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gtjjcbijoo.html

[U109] JS：数组分组
来源：http://dali.cheryme.top/Article/details/gtldmfkrlb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.bjfxy.top/Article/details/gtkovymcdn.html

[U110] JS：数组分块
来源：http://dali.yuanzhike.top/Article/details/gtnqovyghj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtckrbffuy.html

[U111] JS：对象转 Map
来源：http://dali.smart0.xyz/Article/details/gtwvlcydvl.html

new Map(Object.entries(obj))
来源：http://dali.haohaochexian.top/Article/details/gtmbymfbmv.html

[U112] JS：字符串补位
来源：http://dali.fzhhl.top/Article/details/gtmxbqrndr.html

"7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gteotkjxup.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtbqxgiawc.html

s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtagamyuzh.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gttkzgmhjw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtixjzbwaq.html

[U115] JS：生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gtwxvnsdiu.html

crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtmemszlog.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.guowangkeji.top/Article/details/gtckrpihkv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gtrducaiqk.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykwdmyeb.html

npm i -D vitest;  npx vitest
来源：http://dali.quarkkingdee.top/Article/details/gtccpssfag.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtclbnlzku.html

npm i -D vite;  npx vite
来源：http://dali.meibo888.top/Article/details/gtcminzeeb.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtfmajedxy.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gtwosrdhoj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aibaodan.cn/Article/details/gtwfpfogzn.html

import.meta.env.VITE_API_URL
来源：http://dali.ehwqpu.com/Article/details/gtvuqxqmsr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtbgbwzdww.html

统计汇总
来源：http://dali.sweek.top/Article/details/gtvabacies.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtwgqwhwku.html

按语言统计（条）：
来源：http://dali.yangfankeji.com/Article/details/gtsbnyosjg.html

Python ......... 252
来源：http://dali.smart0.xyz/Article/details/gtzhnyxork.html

PHP ............ 252
来源：http://dali.ivvv.top/Article/details/gtdkakmrfz.html

JavaScript ..... 252
来源：http://dali.gaohongyu789.top/Article/details/gtxcqralkz.html

TypeScript ..... 212
来源：http://dali.bjfxy.top/Article/details/gtleqxxcpv.html

Java ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gtzjtrpbye.html

Go ............. 212
来源：http://dali.meibo888.top/Article/details/gtqsixxdsb.html

Ruby ........... 212
来源：http://dali.yongpay.top/Article/details/gtzvvcbdsu.html

C# ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtpzpcfmwe.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtnhflgicb.html

C++ ............ 30
来源：http://dali.jiagoushi.top/Article/details/gtuwnyfshh.html

SQL ............ 90
来源：http://dali.316326.xyz/Article/details/gtfmcmedzt.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gtncuyyuya.html

Kotlin ......... 15
来源：http://dali.zhixingplan.top/Article/details/gtkxkgduzs.html

Swift .......... 15
来源：http://dali.9152youxi.cn/Article/details/gtptjcyuio.html

Lua ............ 10
来源：http://dali.shzxlz.cn/Article/details/gtlnjfdejn.html

Perl ........... 10
来源：http://dali.jqgfzy.top/Article/details/gtpeuygqmg.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtguhstuip.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtsgsydyhp.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gtjzwgvzhk.html

按章节统计：
来源：http://dali.quarkkingdee.top/Article/details/gtskvoyiup.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdfldpsu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.daria6918.cn/Article/details/gtqzpwnoza.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtudbvjfwj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gtbkpkkfxp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gteijnyhtc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gthuypqzsx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtifpobbah.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gttbsjbake.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtbpstkzno.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhongyouzk.top/Article/details/gtsmlyvklr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtlmmcqhvt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtgfjtcecw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gthilwurew.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtfcsrwnjx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.cheryme.top/Article/details/gtkbyknvpi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gttdyletgs.html

Q SQL 专题                              90
来源：http://dali.yueranfly.top/Article/details/gtezsvndqe.html

R Bash 专题                             80
来源：http://dali.bjfxy.top/Article/details/gtqqojkltm.html

S C / C++ 专题                          60
来源：http://dali.mhx1999.top/Article/details/gtacyseqfl.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gtkatjebxv.html

U 高频实用片段                         120
来源：http://dali.cucudq.cn/Article/details/gtogqebxix.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtfqvjyopu.html

合计                                  2106 条
来源：http://dali.dianchejie.cn/Article/details/gtvkvzazny.html

--------------------------------------------------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtzgcmsgpx.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtylfodwrr.html

--------------------------------------------------------------------------------
来源：http://dali.jlsjyb.cn/Article/details/gtkaxkzzdm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cashguo.top/Article/details/gtgarfuxhx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.sxryk.cn/Article/details/gttekfcytt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yuanzhike.top/Article/details/gtnhtlwgca.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.feifeiyinyue.top/Article/details/gtfjivwnum.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.fengsongda.top/Article/details/gtxrfmhvra.html

—— 文件结束 ——
来源：http://dali.yj20258.top/Article/details/gtdstgitel.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtigahejfx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zdqjudy.top/Article/details/gtbnjindrm.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gtuazykujk.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gttbanccnd.html

【收录内容】
来源：http://dali.tanke756.top/Article/details/gtpkggsxao.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.nanxuanxn.top/Article/details/gtoqcwpclf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.pycfn.com/Article/details/gtubgifqyg.html

SQL · Bash · C · C++
来源：http://dali.dashuyun.cn/Article/details/gtuousoclr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yongpay.top/Article/details/gtsowvpefi.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtwyfddvdv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.kuanghao11.cn/Article/details/gtkktsvdnt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jqgfzy.top/Article/details/gtxtrzxrha.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.aizwys.cn/Article/details/gtjspwjahn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dashuyun.cn/Article/details/gtpzqiiskd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yuxming.cn/Article/details/gtmivvkoaw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jqgfzy.top/Article/details/gtktqyjtyo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xziqi.cn/Article/details/gtvsgfhazx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yj20258.top/Article/details/gtcsakqtld.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.yj20258.top/Article/details/gtifmrbtox.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hnqzz.top/Article/details/gtwbdtjwwh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zdqjudy.top/Article/details/gtbqbhqnzd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ehwqpu.com/Article/details/gtuzmhgnhz.html

【文件统计】
来源：http://dali.9152youxi.cn/Article/details/gtmbtsjaxl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sufxvd.cn/Article/details/gtndylgctm.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtklagvoex.html

目  录
来源：http://dali.fengsongda.top/Article/details/gtxnwaihhd.html

--------------------------------------------------------------------------------
来源：http://dali.sysykeji.top/Article/details/gthgsoycdh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xuanzx.com/Article/details/gtxzesyftc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtcejqgmij.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtwsgxctmz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtljxpirbm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyqpvsvm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.yj202588.top/Article/details/gtbctytvzj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtswwexbsd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hysaishi.cn/Article/details/gtbntwltpn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hysaishi.cn/Article/details/gtkzlcrlxx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yangfankeji.com/Article/details/gtqbxhjnhu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtbnuuiayn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtafefrwoi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtgbjcmegf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtuchrclzy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.nanxinkj.top/Article/details/gtcihmhdxj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.sysykeji.top/Article/details/gtsgkftpit.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.tanke756.top/Article/details/gtzuluoxae.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtjsvgtleb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aibaodan.cn/Article/details/gtqabixojv.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtblktaadc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtpexyszwq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtqnwmstkl.html

A. 基础语法与类型
来源：http://dali.yangfankeji.com/Article/details/gtylzswihq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqvwgozvs.html

[A01] Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmqbsxhyv.html

Py:   print("Hello, World!")
来源：http://dali.zhixingplan.top/Article/details/gtxdytgarg.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gtqkceyqid.html

JS:   console.log("Hello, World!");
来源：http://dali.nanxuanxn.top/Article/details/gtgtpooblv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenzaomai.com/Article/details/gtsldheyji.html

Java: System.out.println("Hello, World!");
来源：http://dali.ivvv.top/Article/details/gtmfxswion.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtygaqjyvq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhiwuduotai.top/Article/details/gtdryeiwfd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtrqpzcict.html

[A02] 变量声明与赋值
来源：http://dali.yongpay.top/Article/details/gtzxmjaznf.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhixingplan.top/Article/details/gtpdavneqk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.316326.xyz/Article/details/gtlxrbknfl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jianghu66.top/Article/details/gtzgjylfhv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhengqikj.top/Article/details/gtepacbcbx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinqigufen.top/Article/details/gtamqcsikk.html

Go:   name := "Alex"; age := 20
来源：http://dali.jinqigfzy.top/Article/details/gtezphiywu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gtwixcoxoy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtbpvywjww.html

[A03] 常量定义
来源：http://dali.yonumen.top/Article/details/gtkeddedgt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.316326.xyz/Article/details/gtlggwiont.html

PHP:  const PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtwnjbodan.html

JS:   const PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvgaodkyk.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gttumxrzeq.html

Java: static final double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtqmkvzihf.html

Go:   const PI = 3.14159
来源：http://dali.sysykeji.top/Article/details/gttcoqzznn.html

Ruby: PI = 3.14159
来源：http://dali.yuxming.cn/Article/details/gtjbnykmga.html

C#:   const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtkdwzydcp.html

[A04] 判断变量类型
来源：http://dali.haohaochexian.top/Article/details/gtlcgvldms.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jinqigfzy.top/Article/details/gtuuvagvoo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.bjfxy.top/Article/details/gtqaqnitjw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gaohongyu789.top/Article/details/gtamvkhelv.html

TS:   typeof x; x instanceof Date
来源：http://dali.jlsjyb.cn/Article/details/gtqgwhanho.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuanzx.com/Article/details/gtdobfdkml.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuanzx.com/Article/details/gtxqmgbchy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.havefunace.top/Article/details/gtulnktrzo.html

C#:   x.GetType().Name; x is int
来源：http://dali.xziqi.cn/Article/details/gtmcxseldc.html

[A05] 整数除法与取模
来源：http://dali.gaohongyu789.top/Article/details/gtsukkoium.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shzxlz.cn/Article/details/gtfhxpphvq.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gthmaaqlsn.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybmkugxj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gtbzetfvnq.html

Java: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtztptaqhu.html

Go:   7 / 2; 7 % 2
来源：http://dali.316326.xyz/Article/details/gtjnmpyvrg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtnlyjgmnq.html

C#:   7 / 2; 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtyqchirrc.html

[A06] 字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtiunnagvq.html

Py:   int("42"); float("3.14")
来源：http://dali.jqgufenzy.top/Article/details/gthqczrphz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gtihefhggl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.tian-w.cn/Article/details/gtbiypnlad.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdaabuyad.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.havefunace.top/Article/details/gthhzbjrwk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jiagoushi.top/Article/details/gtwwauhupi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guowangkeji.top/Article/details/gtrzdhqsbu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ehwqpu.com/Article/details/gtbzcnhods.html

[A07] 数字转字符串
来源：http://dali.fzhhl.top/Article/details/gtrosbygsd.html

Py:   str(42)
来源：http://dali.shzxlz.cn/Article/details/gtoijbxhtx.html

PHP:  (string) 42; strval(42)
来源：http://dali.hammf.cn/Article/details/gtzauxqoiv.html

JS:   String(42); (42).toString()
来源：http://dali.cucudq.cn/Article/details/gtjdesgywb.html

TS:   String(42)
来源：http://dali.hammf.cn/Article/details/gtuxmtnuav.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aizwys.cn/Article/details/gtdyoqdurr.html

Go:   strconv.Itoa(42)
来源：http://dali.hysaishi.cn/Article/details/gtcuocoalr.html

Ruby: 42.to_s
来源：http://dali.pycfn.com/Article/details/gtkvwwaohm.html

C#:   42.ToString()
来源：http://dali.pycfn.com/Article/details/gtstpyyogl.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gttjcpdfms.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.nwbrower.top/Article/details/gtwhqrhmbg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.cashguo.top/Article/details/gtgherqbcw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gttlgivxsp.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gtukygsqhn.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtoroxdnbx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtwqvbjudi.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.c1oappe.top/Article/details/gtngbfunoh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.guannengcc.top/Article/details/gttvsisgon.html

[A09] 绝对值与最大最小值
来源：http://dali.ehwqpu.com/Article/details/gtnteqwxzw.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtnnxikcyu.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ydzc1.top/Article/details/gteqqnajrz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yonumen.top/Article/details/gtfewfcxtb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yueranfly.top/Article/details/gtkrfhbljs.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtxqdkrhkp.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdngzavzj.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yuxming.cn/Article/details/gtbxacrepi.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtiupbvvzr.html

[A10] 生成随机数
来源：http://dali.hysaishi.cn/Article/details/gtrjpejeuh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gtvqczzura.html

PHP:  random_int(1, 100);
来源：http://dali.hnxiangtu.top/Article/details/gtzuzkmkri.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shzxlz.cn/Article/details/gtpiwppnnk.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtgegczpyp.html

Java: new Random().nextInt(100) + 1
来源：http://dali.tianlin.xyz/Article/details/gtkdgpzuxj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.andypj.xyz/Article/details/gtkdltnihf.html

Ruby: rand(1..100)
来源：http://dali.birdmap.top/Article/details/gtmxrvdbhl.html

C#:   new Random().Next(1, 101)
来源：http://dali.andypj.xyz/Article/details/gttnubltbs.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gtmsgdurmu.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tianlin.xyz/Article/details/gtknabymcz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.feifeiyinyue.top/Article/details/gtqrzqphqd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtgmlusysg.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.c1oappe.top/Article/details/gtptraprax.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtlrtdtxkx.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.yuanzhike.top/Article/details/gtaivridul.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gtwxnoneal.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.haohaochexian.top/Article/details/gtzcppgecl.html

[A12] 字符串插值 / 格式化
来源：http://dali.sxryk.cn/Article/details/gtynhdyuko.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yanxiufei.cn/Article/details/gthelawugf.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenlongwang.top/Article/details/gtdbcunhxy.html

JS:   `Hello, ${name}!`
来源：http://dali.daria6918.cn/Article/details/gteyiuimcw.html

TS:   `Hello, ${name}!`
来源：http://dali.yuxming.cn/Article/details/gtjvqbnunx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.andypj.xyz/Article/details/gtupkhzdvv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.guannengcc.top/Article/details/gtnabcrobq.html

Ruby: "Hello, #{name}!"
来源：http://dali.bjfxy.top/Article/details/gtcqzhduon.html

C#:   $"Hello, {name}!"
来源：http://dali.gzhubu.top/Article/details/gtltbiqnrq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gtmlmlhpae.html

Py:   "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gtfsmqccof.html

PHP:  "第一行\n第二行"
来源：http://dali.jinqigufen.top/Article/details/gtpgyzlphu.html

JS:   "第一行\n第二行"
来源：http://dali.yuanzhike.top/Article/details/gtiqzwhnel.html

TS:   "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtuftzgrtn.html

Java: "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtrnphhbxk.html

Go:   "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtvcbqgovu.html

Ruby: "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtiurwqwos.html

C#:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtvhjiwnwa.html

[A14] 注释写法
来源：http://dali.guowangkeji.top/Article/details/gtygivkaqa.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.jqgfzy.top/Article/details/gtjmlevvou.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtcordojfu.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gtvjvearqs.html


<!-- 参考信息 -->