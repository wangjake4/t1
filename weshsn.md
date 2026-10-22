代发 wailian999

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gtyiankqnh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yvedp.cn/Article/details/gthhgvohfk.html

[U92] JS：深拷贝
来源：http://dali.zycfv.cn/Article/details/gtanfoxkdk.html

structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtgookoxrl.html

[U93] JS：模板字符串
来源：http://dali.yvedp.cn/Article/details/gtasfzwsbq.html

`共 ${n} 条`
来源：http://dali.redwolf501.top/Article/details/gtufenmkqm.html

[U94] JS：箭头函数
来源：http://dali.vqdsnc.cn/Article/details/gtghrixupx.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtbpbscuco.html

[U95] JS：Promise 包装
来源：http://dali.quarkkingdee.top/Article/details/gtenalxhry.html

new Promise((resolve, reject) => {})
来源：http://dali.shuidangran.top/Article/details/gtgnuxebfm.html

[U96] JS：async/await 与异常
来源：http://dali.wangshuangyany.cn/Article/details/gtqxlewfow.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtzwpbnhzi.html

[U97] JS：并发请求
来源：http://dali.0kj1m.cn/Article/details/gtvmpluwzo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuetiantiany.cn/Article/details/gtkxtowzan.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtfrzbwaqq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gtdsckkphg.html

[U99] JS：事件监听
来源：http://dali.chenjidiqi.icu/Article/details/gtyqxectqd.html

el.addEventListener("click", e => {})
来源：http://dali.snrcjt.cn/Article/details/gtqxljexii.html

[U100] JS：DOM 查询
来源：http://dali.chenzaomai.com/Article/details/gtzfuwbtmy.html

document.querySelector(".item")
来源：http://dali.yangfankeji.com/Article/details/gtetmwfsdr.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gtpcbbyjgo.html

el.classList.toggle("active")
来源：http://dali.yuxming.cn/Article/details/gtujuwkmww.html

[U102] JS：本地存储
来源：http://dali.316326.xyz/Article/details/gtkejrlpme.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dianchejie.cn/Article/details/gticowhyda.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gtlrgkjxlb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gtfcgopyet.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtwxlilanp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gtkwqslnku.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gthgnxlyei.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.sxryk.cn/Article/details/gtumeredvs.html

[U106] JS：日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtbnuotevl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtjymtidtr.html

[U107] JS：数字千分位
来源：http://dali.sysykeji.top/Article/details/gtnwxceowh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtcfeinymj.html

[U108] JS：随机整数
来源：http://dali.gogol.net.cn/Article/details/gtysguofyk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gteourygsg.html

[U109] JS：数组分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjjtrfai.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gtszigjrqf.html

[U110] JS：数组分块
来源：http://dali.gogol.net.cn/Article/details/gttlehdblf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gtoqyrxywr.html

[U111] JS：对象转 Map
来源：http://dali.ivvv.top/Article/details/gtfcgobisq.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtxqkxzhne.html

[U112] JS：字符串补位
来源：http://dali.shangyingyoupin.top/Article/details/gtkvplehqi.html

"7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtycllhowm.html

[U113] JS：正则替换全部
来源：http://dali.aibaodan.cn/Article/details/gtyzusqdra.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtfqwisxtg.html

[U114] JS：JSON 深比较
来源：http://dali.svipenyu.cn/Article/details/gtberccess.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtunkxgivt.html

[U115] JS：生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtcnpmhtea.html

crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtlxpkavjg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhengqikj.top/Article/details/gticpwyfpd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.9152youxi.cn/Article/details/gtflgsthvp.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gthbgqjoey.html

npm i -D vitest;  npx vitest
来源：http://dali.zhengqikj.top/Article/details/gtyypyibpl.html

[U118] JS：开发服务器
来源：http://dali.gogol.net.cn/Article/details/gtskevumcb.html

npm i -D vite;  npx vite
来源：http://dali.gogol.net.cn/Article/details/gtathbbzcr.html

[U119] JS：生产构建
来源：http://dali.hnxiangtu.top/Article/details/gtfnklbvse.html

npx vite build
来源：http://dali.yj20258888.top/Article/details/gtihrnnyiw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xziqi.cn/Article/details/gtkpkskell.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtlvcqueyg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnqkqzqfr.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtuyaknzms.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtrrqrljuc.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtbyltzynn.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gtjerhfaho.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtfcawxdmm.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gtklbgdrrf.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gtehhwcaan.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtxpkvkbvp.html

Go ............. 212
来源：http://dali.kuanghao11.cn/Article/details/gtbgjbzyyh.html

Ruby ........... 212
来源：http://dali.snrcjt.cn/Article/details/gtpwyafzvn.html

C# ............. 212
来源：http://dali.havefunace.top/Article/details/gtubcrcqeb.html

C .............. 30
来源：http://dali.ydzc1.top/Article/details/gtaoeyzuwp.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gthyjxqccs.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gtsdmolzgn.html

Bash ........... 80
来源：http://dali.tianlin.xyz/Article/details/gtetkswkmn.html

Kotlin ......... 15
来源：http://dali.jiagoushi.top/Article/details/gtmbszibvt.html

Swift .......... 15
来源：http://dali.redwolf501.top/Article/details/gtsjyhaowd.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtrggmbtgt.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtqgphmnbw.html

Scala .......... 10
来源：http://dali.hfpthk.cn/Article/details/gtmlrkpskz.html

------------------------------------
来源：http://dali.nwbrower.top/Article/details/gthgdnnfnh.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gtmibnaupo.html

按章节统计：
来源：http://dali.tian-w.cn/Article/details/gtrpogwfhl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtbknystuw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtxnbuejuk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jianghu66.top/Article/details/gtbatqyosl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zycfv.cn/Article/details/gtpyzvsbig.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtwjcwwgnx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ydzc1.top/Article/details/gtvspwpudi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gtjprknvin.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtmaduabzv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gtpygmdhak.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gtiaocxrtr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shzxlz.cn/Article/details/gtlmxiwgsj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtbxudoujw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtxlzbdihd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.sweek.top/Article/details/gthjouwppc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhiwuduotai.top/Article/details/gteydkfuih.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtjofylhbr.html

Q SQL 专题                              90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwbcysop.html

R Bash 专题                             80
来源：http://dali.cucudq.cn/Article/details/gtjrfmjqeb.html

S C / C++ 专题                          60
来源：http://dali.daxiang520.top/Article/details/gtbqfmlovd.html

T 其他语言补充                          60
来源：http://dali.snrcjt.cn/Article/details/gtpvxsbkak.html

U 高频实用片段                         120
来源：http://dali.jianghu66.top/Article/details/gtstedngwu.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtxrgdwxwt.html

合计                                  2106 条
来源：http://dali.yuxming.cn/Article/details/gtouimcgxk.html

--------------------------------------------------------------------------------
来源：http://dali.vqdsnc.cn/Article/details/gtqknvuexj.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtwrgldcic.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtkzqyqibf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhixingplan.top/Article/details/gtrjpltrlq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsjrglri.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.andypj.xyz/Article/details/gtyhhyxrnd.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gtowboqfto.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guannengcc.top/Article/details/gtvdwrrlcf.html

—— 文件结束 ——
来源：http://dali.guowangkeji.top/Article/details/gtgvdtxwqz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtmaiiwiic.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.smart0.xyz/Article/details/gtjcggdsbm.html

Common Programming Examples Cheat Book
来源：http://dali.birdmap.top/Article/details/gtlipcllqm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtubceexrp.html

【收录内容】
来源：http://dali.c1oappe.top/Article/details/gtvdfmhzmj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jiagoushi.top/Article/details/gtiaxfpevj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.smart0.xyz/Article/details/gtpitdsefg.html

SQL · Bash · C · C++
来源：http://dali.zhongyouzk.top/Article/details/gtifbstwln.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.sxryk.cn/Article/details/gtgajqrpgj.html

【使用说明】
来源：http://dali.yangfankeji.com/Article/details/gtppzhvugi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhongyouzk.top/Article/details/gtkrrjaekm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xziqi.cn/Article/details/gtyegcnojh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.mhx1999.top/Article/details/gtynsxgcwh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.ivvv.top/Article/details/gtwqnjcskq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.aizwys.cn/Article/details/gtmshlmgec.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrjgoowe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jianghu66.top/Article/details/gtuothoucm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gtmzdejkqy.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ydzc1.top/Article/details/gtnynstksx.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.chenlongwang.top/Article/details/gtcyllpdyt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.feifeiyinyue.top/Article/details/gtarrwjmqv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhoulong.xyz/Article/details/gtjpvjhuhr.html

【文件统计】
来源：http://dali.jqgufenzy.top/Article/details/gtvyynsuvd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jyoumei.cn/Article/details/gthhupmaik.html

--------------------------------------------------------------------------------
来源：http://dali.yj202588.top/Article/details/gtrhalcotd.html

目  录
来源：http://dali.shanyushiyangtech.top/Article/details/gthptleoit.html

--------------------------------------------------------------------------------
来源：http://dali.chenlongwang.top/Article/details/gtzurphzpx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.316326.xyz/Article/details/gtvpqladeb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtkyadpvep.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.gogol.net.cn/Article/details/gtcaosaqot.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.smart0.xyz/Article/details/gtmvtevbgm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gtmjndswen.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.svipenyu.cn/Article/details/gtdsqlaggc.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtmfvzjaox.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtadfsvphm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtbxswadav.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtwncwtzzv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtjnnbkaug.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtbrijpcdj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtjikhbdsb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gtcuxrofhg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tanke756.top/Article/details/gthmczwngi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtceiemtkd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.mhx1999.top/Article/details/gtqlynbnsh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jyoumei.cn/Article/details/gtrulmezhz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.daria6918.cn/Article/details/gtsdqphauj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtyqvioawn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtmqxjtzty.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkocjvjom.html

A. 基础语法与类型
来源：http://dali.hywenlv.cn/Article/details/gtevdcoeyf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmxobsprn.html

[A01] Hello World
来源：http://dali.gotoacloud.top/Article/details/gtoxotwzzj.html

Py:   print("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtpqczsnkr.html

PHP:  echo "Hello, World!";
来源：http://dali.yj202588.top/Article/details/gtfyeldtji.html

JS:   console.log("Hello, World!");
来源：http://dali.tanke756.top/Article/details/gticihydsv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfmrslog.html

Java: System.out.println("Hello, World!");
来源：http://dali.sweek.top/Article/details/gtlmeczkmx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.jqgfzy.top/Article/details/gtogtkzaak.html

Ruby: puts "Hello, World!"
来源：http://dali.shangyingyoupin.top/Article/details/gtrvtumonw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtxcqxdhea.html

[A02] 变量声明与赋值
来源：http://dali.xylfe.cn/Article/details/gtdpehbpgj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gtdgrrrlay.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zdqjudy.top/Article/details/gtfaafwvwz.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yangfankeji.com/Article/details/gtaquvjzdx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tanke756.top/Article/details/gtgryakbrg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.aizwys.cn/Article/details/gtfalnfygg.html

Go:   name := "Alex"; age := 20
来源：http://dali.pengpengdd.cyou/Article/details/gtukgucbir.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zycfv.cn/Article/details/gtlhiivtag.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.cucudq.cn/Article/details/gtvvlugwvf.html

[A03] 常量定义
来源：http://dali.xuetiantiany.cn/Article/details/gttcyeuovr.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.ppjwa.cn/Article/details/gtzljjjjud.html

PHP:  const PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtqovvcywe.html

JS:   const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtocwsnemh.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtymycbuhj.html

Java: static final double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtssntpwcz.html

Go:   const PI = 3.14159
来源：http://dali.smart0.xyz/Article/details/gtsmrhftwr.html

Ruby: PI = 3.14159
来源：http://dali.jinqigufen.top/Article/details/gtelpfwcau.html

C#:   const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtbuuyyini.html

[A04] 判断变量类型
来源：http://dali.yanxiufei.cn/Article/details/gtazlrephm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.316326.xyz/Article/details/gtroafmldn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gtxbaysszn.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.birdmap.top/Article/details/gtecifpstk.html

TS:   typeof x; x instanceof Date
来源：http://dali.shanyushiyangtech.top/Article/details/gtknqxmaet.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.ybcxt.top/Article/details/gtfwitwptz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.aizwys.cn/Article/details/gtuifunvgk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yuxming.cn/Article/details/gtsqohdlgx.html

C#:   x.GetType().Name; x is int
来源：http://dali.andypj.xyz/Article/details/gtillzbist.html

[A05] 整数除法与取模
来源：http://dali.hywenlv.cn/Article/details/gtmnhxfnhe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.0kj1m.cn/Article/details/gtwxtmfwsm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.ehwqpu.com/Article/details/gtltwyicoa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtmxvozfnb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gttvvodhnv.html

Java: 7 / 2; 7 % 2
来源：http://dali.guowangkeji.top/Article/details/gtnwigkyre.html

Go:   7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtjgdtbyvo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtppsqlvjh.html

C#:   7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtswgffpbe.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtdnorivck.html

Py:   int("42"); float("3.14")
来源：http://dali.ybcxt.top/Article/details/gtnjrxhczb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.tianlin.xyz/Article/details/gtnnsfzads.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtmapesfqf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cucudq.cn/Article/details/gtsynvfiwz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.kuanghao11.cn/Article/details/gtzbpjskay.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.snrcjt.cn/Article/details/gtgrwhculy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xuanzx.com/Article/details/gtdjvaillo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hnqzz.top/Article/details/gtwzikctkr.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gtffhoobog.html

Py:   str(42)
来源：http://dali.vqdsnc.cn/Article/details/gtjnesmfjh.html

PHP:  (string) 42; strval(42)
来源：http://dali.jqgfzy.top/Article/details/gtrgofaxmy.html

JS:   String(42); (42).toString()
来源：http://dali.yuanzhike.top/Article/details/gtmjgbzxfy.html

TS:   String(42)
来源：http://dali.aibaodan.cn/Article/details/gtozafgusl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aizwys.cn/Article/details/gtzuzmcode.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gtdzfmpyql.html

Ruby: 42.to_s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskgqewfk.html

C#:   42.ToString()
来源：http://dali.mhx1999.top/Article/details/gtiflhmqoh.html

[A08] 取整与四舍五入
来源：http://dali.chenlongwang.top/Article/details/gtulmpxsyv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.jinqigufen.top/Article/details/gtqrbafwru.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xuanzx.com/Article/details/gtbnkrfszf.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtxnovjquw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.jianghu66.top/Article/details/gtntmqyawu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtrxbpradm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtenzpmjvj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.chenzaomai.com/Article/details/gtzryguaau.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtmvlwhwnz.html

[A09] 绝对值与最大最小值
来源：http://dali.hammf.cn/Article/details/gttmzbpvtp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtqcdzfpch.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtixkvydcu.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtnzkdhmmn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtivaakpkz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtajsrbnio.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gtwezagfcc.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.jyoumei.cn/Article/details/gtqccitmls.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtxxonhunz.html

[A10] 生成随机数
来源：http://dali.cashguo.top/Article/details/gtghhrebkd.html

Py:   import random; random.randint(1, 100)
来源：http://dali.svipenyu.cn/Article/details/gtsuubqksh.html

PHP:  random_int(1, 100);
来源：http://dali.yj202588.top/Article/details/gtrjdcnwbc.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ybcxt.top/Article/details/gtxgvguxru.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gtxobvynyz.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj202588.top/Article/details/gtprtlmhoc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.aizwys.cn/Article/details/gtidwmlkst.html

Ruby: rand(1..100)
来源：http://dali.vqdsnc.cn/Article/details/gtfxzozgup.html

C#:   new Random().Next(1, 101)
来源：http://dali.yuxming.cn/Article/details/gtmsvwpbvi.html

[A11] 条件表达式（三元）
来源：http://dali.tanke756.top/Article/details/gtzshqguon.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hnqzz.top/Article/details/gtwfkbwdfp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtqrmvwntb.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtendjntbw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ivvv.top/Article/details/gtazvohmyn.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.cucudq.cn/Article/details/gtquvlsney.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.quarkkingdee.top/Article/details/gttganbbir.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtqhmvwncd.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqozluem.html

[A12] 字符串插值 / 格式化
来源：http://dali.hammf.cn/Article/details/gtdatqqijf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.havefunace.top/Article/details/gtokgopogt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guannengcc.top/Article/details/gtikrlkbcc.html

JS:   `Hello, ${name}!`
来源：http://dali.snrcjt.cn/Article/details/gtdsaygblb.html

TS:   `Hello, ${name}!`
来源：http://dali.hammf.cn/Article/details/gtfkggdpba.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gtltumhtqb.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hnqzz.top/Article/details/gtxvgspjmq.html

Ruby: "Hello, #{name}!"
来源：http://dali.jqgfzy.top/Article/details/gtjfqahhsl.html

C#:   $"Hello, {name}!"
来源：http://dali.zhengqikj.top/Article/details/gtscdpejbx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.yj202588.top/Article/details/gtbrgjiosi.html

Py:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtanrjtada.html

PHP:  "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtcctoxkxe.html

JS:   "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtasttnsbt.html

TS:   "第一行\n第二行"
来源：http://dali.yj202588.top/Article/details/gtpeaszflb.html

Java: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtrszuujgx.html

Go:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtzumqeqok.html

Ruby: "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtpxdhbgsa.html

C#:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtvulcrdzk.html

[A14] 注释写法
来源：http://dali.jianghu66.top/Article/details/gtiihctfsx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.hnqzz.top/Article/details/gtjijodbyu.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtbsfnszeq.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhiwuduotai.top/Article/details/gtmepiiack.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangdashe.top/Article/details/gtexeaywfg.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.aibaodan.cn/Article/details/gtmcfgpxzq.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtnjfbxlho.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jianghu66.top/Article/details/gtmtjswtct.html

C#:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtfcmkvvnl.html

[A15] 空值判断与默认值
来源：http://dali.ehwqpu.com/Article/details/gtygwoaosj.html

Py:   value = data or "默认值"
来源：http://dali.c1oappe.top/Article/details/gtmxticxok.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.daria6918.cn/Article/details/gthajydpee.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtiwjclruy.html

TS:   const value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtfsajmvuw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cheryme.top/Article/details/gtsfcmnaqp.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozutzolj.html


<!-- 参考信息 -->