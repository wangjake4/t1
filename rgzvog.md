代发 wailian999

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtkvxaaxct.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtlvtqwmbb.html

[U90] JS：数字数组排序
来源：http://dali.c1oappe.top/Article/details/gttzsqkmnq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtadxavlwv.html

[U91] JS：对象键值遍历
来源：http://dali.hysaishi.cn/Article/details/gtcflzhiog.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jlsjyb.cn/Article/details/gttlwsedse.html

[U92] JS：深拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtxknkfqyj.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gttdrwkexz.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gttqorfkia.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtxjmicnst.html

[U94] JS：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtgvggabzd.html

const double = x => x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtfmtmgcqe.html

[U95] JS：Promise 包装
来源：http://dali.shzxlz.cn/Article/details/gtfcyhswdk.html

new Promise((resolve, reject) => {})
来源：http://dali.pycfn.com/Article/details/gteyyodmkg.html

[U96] JS：async/await 与异常
来源：http://dali.cdnleiting.top/Article/details/gtfjyozljy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtjxohvibh.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtbyrizggz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtdfszckqx.html

[U98] JS：fetch 带 JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtwuhxtxhj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gtqaymcgab.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gtszufkxmt.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gtfrqzweoe.html

[U100] JS：DOM 查询
来源：http://dali.xuanzx.com/Article/details/gtojmnralm.html

document.querySelector(".item")
来源：http://dali.sysykeji.top/Article/details/gtxccwmphs.html

[U101] JS：classList 操作
来源：http://dali.fengsongda.top/Article/details/gtusyvyyjg.html

el.classList.toggle("active")
来源：http://dali.redwolf501.top/Article/details/gtedasbakh.html

[U102] JS：本地存储
来源：http://dali.jiagoushi.top/Article/details/gtaphahyft.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cucudq.cn/Article/details/gtdrvcxsyt.html

[U103] JS：定时器
来源：http://dali.xuetiantiany.cn/Article/details/gtlxcdobqv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yvedp.cn/Article/details/gtewkhympy.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gtheplnnvu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtxelzecmz.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtfxgmgfvl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yueranfly.top/Article/details/gtyemyfych.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkzfsndh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzosjfjm.html

[U107] JS：数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gtxxisvzlg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtkxrlybov.html

[U108] JS：随机整数
来源：http://dali.kuanghao11.cn/Article/details/gtkwrqpcao.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zycfv.cn/Article/details/gtlptmtpuz.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtnykmyfuk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yvedp.cn/Article/details/gtqmroiuja.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtadiirghu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sufxvd.cn/Article/details/gtbeqlnfcb.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtodemkoom.html

new Map(Object.entries(obj))
来源：http://dali.tian-w.cn/Article/details/gtqwbadqjr.html

[U112] JS：字符串补位
来源：http://dali.mhx1999.top/Article/details/gtkidxagls.html

"7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtykaeyycs.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtmuyezdpl.html

s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtgwciozws.html

[U114] JS：JSON 深比较
来源：http://dali.daria6918.cn/Article/details/gtkgxgquxt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.redwolf501.top/Article/details/gtfkhryrwc.html

[U115] JS：生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtsdnpekvm.html

crypto.randomUUID()
来源：http://dali.yangfankeji.com/Article/details/gthaayajzp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yj20258888.top/Article/details/gtishexepq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jqgfzy.top/Article/details/gtapsbkmrs.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gtqzwoccpj.html

npm i -D vitest;  npx vitest
来源：http://dali.sysykeji.top/Article/details/gtrbivflkb.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gtevvmajgg.html

npm i -D vite;  npx vite
来源：http://dali.smart0.xyz/Article/details/gtpddkrhjk.html

[U119] JS：生产构建
来源：http://dali.hongshengwenyu.top/Article/details/gtpsmxozik.html

npx vite build
来源：http://dali.gaohongyu789.top/Article/details/gtypanwhrm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ydzc1.top/Article/details/gtenvvsawk.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gtqgpybcyr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtljimrudi.html

统计汇总
来源：http://dali.jqgfzy.top/Article/details/gtkamudbyr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtezirxlic.html

按语言统计（条）：
来源：http://dali.snrcjt.cn/Article/details/gtlszobqlg.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gteedmdflu.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gtvehblkgw.html

JavaScript ..... 252
来源：http://dali.nwbrower.top/Article/details/gthoxhkimp.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gttdgdhnvt.html

Java ........... 212
来源：http://dali.quarkkingdee.top/Article/details/gtdeojcpbs.html

Go ............. 212
来源：http://dali.yonumen.top/Article/details/gtsltyltjx.html

Ruby ........... 212
来源：http://dali.smart0.xyz/Article/details/gtjwdvmmcx.html

C# ............. 212
来源：http://dali.yueranfly.top/Article/details/gtmahomann.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gttvsiibmd.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gtjpxxtosu.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtacsbvacw.html

Bash ........... 80
来源：http://dali.hnqzz.top/Article/details/gtipuhxrvt.html

Kotlin ......... 15
来源：http://dali.quarkkingdee.top/Article/details/gtsphjtymd.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gtwribyggj.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtyvkpvgej.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gtyvpkqzqk.html

Scala .......... 10
来源：http://dali.9152youxi.cn/Article/details/gtloczaxgb.html

------------------------------------
来源：http://dali.zhoulong.xyz/Article/details/gtqkgvoqni.html

合计 ........... 2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpzhaaca.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gtbvxuphyu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gttfsmthdq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtacukzgkk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtoesyskqk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtlszaczuu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yangfankeji.com/Article/details/gtmyazdnol.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xziqi.cn/Article/details/gtzxxqzdid.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtavgzvnae.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.guannengcc.top/Article/details/gtxzvuosvx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zycfv.cn/Article/details/gtgjizjrbq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gtmbcntosb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jqgufenzy.top/Article/details/gtqrggurgk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gtjtxufmjj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.vqdsnc.cn/Article/details/gttxvcchav.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.wangdashe.top/Article/details/gtyqvwwfmr.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.havefunace.top/Article/details/gtjwqnnfuq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtxxqhgdjw.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtqwvwbpil.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtqqkdauyx.html

S C / C++ 专题                          60
来源：http://dali.guannengcc.top/Article/details/gtwhilqweh.html

T 其他语言补充                          60
来源：http://dali.wangdashe.top/Article/details/gtfwauaxoq.html

U 高频实用片段                         120
来源：http://dali.birdmap.top/Article/details/gttlmfthal.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtmvrrxylj.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gtorvaffon.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtbvaumntb.html

使用提醒
来源：http://dali.ivvv.top/Article/details/gtfctmbwir.html

--------------------------------------------------------------------------------
来源：http://dali.tian-w.cn/Article/details/gtgyoinfch.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ivvv.top/Article/details/gtsrhzqxmk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhongyouzk.top/Article/details/gtyllfoznc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtenuuowcl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.guannengcc.top/Article/details/gtjhfcwbod.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.andypj.xyz/Article/details/gtpcqvuwtq.html

—— 文件结束 ——
来源：http://dali.ivvv.top/Article/details/gttcooeeth.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtymauftrj.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.9152youxi.cn/Article/details/gtpalocdfa.html

Common Programming Examples Cheat Book
来源：http://dali.shzxlz.cn/Article/details/gtopblorrb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtpvyufksy.html

【收录内容】
来源：http://dali.dianchejie.cn/Article/details/gtsggtixvi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.cheryme.top/Article/details/gtctlcrnuf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.ydzc1.top/Article/details/gtkovyitke.html

SQL · Bash · C · C++
来源：http://dali.aizwys.cn/Article/details/gtqxjitfaj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpknmdzg.html

【使用说明】
来源：http://dali.bjfxy.top/Article/details/gtwpwhrcbl.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.shanyushiyangtech.top/Article/details/gteufsrnrc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.ybcxt.top/Article/details/gtqolkmdkp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gogol.net.cn/Article/details/gtfaffjudf.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.quarkkingdee.top/Article/details/gtfquguoyi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsijjxzl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gtvhwgeacd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jiagoushi.top/Article/details/gtqsjbsdvk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.havefunace.top/Article/details/gtuwifrwae.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sufxvd.cn/Article/details/gthqsuxdfp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.guowangkeji.top/Article/details/gttqsahwsv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigufen.top/Article/details/gtovelpkoq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jqgfzy.top/Article/details/gtznlqlsbh.html

【文件统计】
来源：http://dali.dianchejie.cn/Article/details/gtrvlhvlyh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xziqi.cn/Article/details/gtyttnrzvd.html

--------------------------------------------------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtzrxmdrzc.html

目  录
来源：http://dali.pengpengdd.cyou/Article/details/gtwxaargcp.html

--------------------------------------------------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtdkxpniwg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.wangdashe.top/Article/details/gtxzmhaibl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gtuyngetfh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.tanke756.top/Article/details/gtdbjbvfjf.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jianghu66.top/Article/details/gtxunkazst.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sxryk.cn/Article/details/gterlxjnpo.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtpabirojj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.chenzaomai.com/Article/details/gtlbzbacsd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gtkrhspcyr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtlheaitrg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtgibmyexu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtuvaxjlss.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtcyjdulpa.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtshwhnrio.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtnhkpqdcp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtoziipudb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gtragdlvvu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.cucudq.cn/Article/details/gtorecplwl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtsgoccpce.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnxiangtu.top/Article/details/gtliydxgmm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtxvxvtlqa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenzaomai.com/Article/details/gtxwnaliqd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtstxzwqyi.html

A. 基础语法与类型
来源：http://dali.sxryk.cn/Article/details/gtghpsdunn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtmynbxwaz.html

[A01] Hello World
来源：http://dali.sufxvd.cn/Article/details/gtevthbcjf.html

Py:   print("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gtdggagnwb.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gthajqqdkg.html

JS:   console.log("Hello, World!");
来源：http://dali.redwolf501.top/Article/details/gtdkigamai.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.snrcjt.cn/Article/details/gtqacqnfee.html

Java: System.out.println("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtohzpgvhs.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.fzhhl.top/Article/details/gtudfpejnx.html

Ruby: puts "Hello, World!"
来源：http://dali.hongshengwenyu.top/Article/details/gtskbbxoff.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.andypj.xyz/Article/details/gtgovgoatw.html

[A02] 变量声明与赋值
来源：http://dali.jianghu66.top/Article/details/gtqifmqpec.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daxiang520.top/Article/details/gtdlprfkwr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvznfusx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwkegdfc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.vqdsnc.cn/Article/details/gttwluyfpa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gthowqbqmm.html

Go:   name := "Alex"; age := 20
来源：http://dali.hfpthk.cn/Article/details/gtooihzhxl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gtqhfzuuwy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jqgufenzy.top/Article/details/gtltxmhrgk.html

[A03] 常量定义
来源：http://dali.svipenyu.cn/Article/details/gtbmeaubbs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tanke756.top/Article/details/gtkgovacrt.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtfqwtdega.html

JS:   const PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtmtlbvjka.html

TS:   const PI: number = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtdpuucsxv.html

Java: static final double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtnhwkqlto.html

Go:   const PI = 3.14159
来源：http://dali.sxryk.cn/Article/details/gtqatvaqjj.html

Ruby: PI = 3.14159
来源：http://dali.wangdashe.top/Article/details/gtlrdhabhz.html

C#:   const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtnucakrbk.html

[A04] 判断变量类型
来源：http://dali.nanxinkj.top/Article/details/gtabrgrjfo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.daxiang520.top/Article/details/gtebyrqllw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtbewrrdhz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.bjfxy.top/Article/details/gtivlwgxcc.html

TS:   typeof x; x instanceof Date
来源：http://dali.guowangkeji.top/Article/details/gttgoblfds.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrhaaujie.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawstabkq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.meibo888.top/Article/details/gtabohmgsj.html

C#:   x.GetType().Name; x is int
来源：http://dali.316326.xyz/Article/details/gtcpbxkkjg.html

[A05] 整数除法与取模
来源：http://dali.hnqzz.top/Article/details/gtfthjefsi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegsisrtb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gtvcqvdldm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtxefhydyf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gthprrnfog.html

Java: 7 / 2; 7 % 2
来源：http://dali.pycfn.com/Article/details/gtbwujglem.html

Go:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gtvqnvgeew.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtgmgyptsl.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuanzhike.top/Article/details/gtawvoximw.html

[A06] 字符串转数字
来源：http://dali.jqgfzy.top/Article/details/gtrlifavom.html

Py:   int("42"); float("3.14")
来源：http://dali.sxryk.cn/Article/details/gthmxalgbq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinqigufen.top/Article/details/gteyjflric.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.ppjwa.cn/Article/details/gtximegspz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yangfankeji.com/Article/details/gtbgyyvbrp.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.sweek.top/Article/details/gtohzejgfw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.haohaochexian.top/Article/details/gtxarfvxmb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbdqifmv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tianlin.xyz/Article/details/gthtcrxjvh.html

[A07] 数字转字符串
来源：http://dali.bjfxy.top/Article/details/gtgorlwjag.html

Py:   str(42)
来源：http://dali.yongpay.top/Article/details/gtdokuuvcm.html

PHP:  (string) 42; strval(42)
来源：http://dali.xziqi.cn/Article/details/gtagrmjkmn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gtqjpxfsdx.html

TS:   String(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtfyszkcqy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.jiagoushi.top/Article/details/gtrrpykehc.html

Go:   strconv.Itoa(42)
来源：http://dali.havefunace.top/Article/details/gtptufzsvm.html

Ruby: 42.to_s
来源：http://dali.yueranfly.top/Article/details/gtnihadlks.html

C#:   42.ToString()
来源：http://dali.nwbrower.top/Article/details/gtkarfdcnp.html

[A08] 取整与四舍五入
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyeurnxm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.guowangkeji.top/Article/details/gtfomomjnx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.ybcxt.top/Article/details/gtwbqcoafs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gtpswfgzyf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xinyue.icu/Article/details/gtwxcsabrl.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tian-w.cn/Article/details/gtoramtcta.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtanltmhes.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpgxonpb.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hammf.cn/Article/details/gtzqtfnsaz.html

[A09] 绝对值与最大最小值
来源：http://dali.meibo888.top/Article/details/gtoezxuitq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtlhpemwua.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtykypivkf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtyqnufeeu.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.daria6918.cn/Article/details/gttlslplcy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj202588.top/Article/details/gtwxuaqekb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.aizwys.cn/Article/details/gtxydbltrv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jianghu66.top/Article/details/gtznkwrqnj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprfpprpe.html

[A10] 生成随机数
来源：http://dali.tanke756.top/Article/details/gtsonksbut.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenlongwang.top/Article/details/gtytuoawbk.html

PHP:  random_int(1, 100);
来源：http://dali.jiagoushi.top/Article/details/gtudxnwpeu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.nwbrower.top/Article/details/gtpdpnpkzq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbpszyxv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.guannengcc.top/Article/details/gtowfvvumg.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jqgfzy.top/Article/details/gtabprconr.html

Ruby: rand(1..100)
来源：http://dali.mhx1999.top/Article/details/gtmxkyqvgx.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhongyouzk.top/Article/details/gtbbzzumos.html

[A11] 条件表达式（三元）
来源：http://dali.ybcxt.top/Article/details/gtjigytysr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzbfbuap.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cashguo.top/Article/details/gtjvkrsllf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gtxpwjrshb.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtqdbnykgb.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtksjllqka.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.gotoacloud.top/Article/details/gtvdzwvevy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.jiagoushi.top/Article/details/gttoysyggm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gtjodlomsx.html

[A12] 字符串插值 / 格式化
来源：http://dali.haohaochexian.top/Article/details/gttuaogdyl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.sufxvd.cn/Article/details/gthwmioogx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmkejdrt.html

JS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gtoxfovvsw.html

TS:   `Hello, ${name}!`
来源：http://dali.wangdashe.top/Article/details/gtridchdzo.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hywenlv.cn/Article/details/gtxgxmnwon.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.andypj.xyz/Article/details/gtztsmmdku.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigufen.top/Article/details/gtcrjkguch.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxuanxn.top/Article/details/gtmcjedscv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yonumen.top/Article/details/gtmdqsplnr.html

Py:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtfvgsrzdz.html

PHP:  "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtvuctfvju.html

JS:   "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtdxzwcxyw.html

TS:   "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtrsjtqydp.html

Java: "第一行\n第二行"
来源：http://dali.iojbl.cn/Article/details/gttuzfgtqm.html

Go:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtgynkutsd.html

Ruby: "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtohemajzm.html

C#:   "第一行\n第二行"
来源：http://dali.smart0.xyz/Article/details/gtjmrjwcbb.html

[A14] 注释写法
来源：http://dali.cashguo.top/Article/details/gtraxcxttj.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ppjwa.cn/Article/details/gtblrsvewj.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtffwjiqhk.html

JS:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gtvqwxuolo.html

TS:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtwuunonia.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.yuxming.cn/Article/details/gtxoybkzpo.html

Go:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtieiojkgk.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shangyingyoupin.top/Article/details/gtwknhkkjc.html

C#:   // 单行；/* 多行 */
来源：http://dali.jqgufenzy.top/Article/details/gtyrjfhiyk.html

[A15] 空值判断与默认值
来源：http://dali.jinqigfzy.top/Article/details/gtlsspwczw.html

Py:   value = data or "默认值"
来源：http://dali.chenlongwang.top/Article/details/gtvrzbtznn.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtkkmffyzw.html


<!-- 参考信息 -->