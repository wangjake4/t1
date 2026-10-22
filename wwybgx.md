代发 wailian999

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gthxkeragn.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gtreczmbnh.html

[U86] JS：空值合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtladulzca.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gthamyoxie.html

[U87] JS：解构默认值
来源：http://dali.gaohongyu789.top/Article/details/gtsekwpgpg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gtwklbrxzd.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gtdqznxkzw.html

{ ...a, ...b }
来源：http://dali.redwolf501.top/Article/details/gtbpwaoeee.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gthtdyqbiy.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtqcycmtff.html

[U90] JS：数字数组排序
来源：http://dali.fzhhl.top/Article/details/gtgwfytfbo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtkqsyktyu.html

[U91] JS：对象键值遍历
来源：http://dali.sysykeji.top/Article/details/gtevtjfalb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.guannengcc.top/Article/details/gtxtvilwzv.html

[U92] JS：深拷贝
来源：http://dali.daxiang520.top/Article/details/gtacefsoou.html

structuredClone(obj)
来源：http://dali.nanxuanxn.top/Article/details/gtkehzbbss.html

[U93] JS：模板字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzxxzfjq.html

`共 ${n} 条`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhcyydwu.html

[U94] JS：箭头函数
来源：http://dali.yj202588.top/Article/details/gtdgbayzzg.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtzvrfwqjp.html

[U95] JS：Promise 包装
来源：http://dali.tianlin.xyz/Article/details/gtecwvadin.html

new Promise((resolve, reject) => {})
来源：http://dali.snrcjt.cn/Article/details/gtfecisijb.html

[U96] JS：async/await 与异常
来源：http://dali.ehwqpu.com/Article/details/gtfkvlxdpi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtwqosyvec.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gttzscfdhh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.meibo888.top/Article/details/gtjzgnyuan.html

[U98] JS：fetch 带 JSON
来源：http://dali.hammf.cn/Article/details/gtoyursgea.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gtacgyfsvs.html

[U99] JS：事件监听
来源：http://dali.birdmap.top/Article/details/gtfxzjgidj.html

el.addEventListener("click", e => {})
来源：http://dali.c1oappe.top/Article/details/gtsjxwaebc.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gttaxucmru.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gtkjkylwmy.html

[U101] JS：classList 操作
来源：http://dali.yuanzhike.top/Article/details/gtuzusgefd.html

el.classList.toggle("active")
来源：http://dali.jlsjyb.cn/Article/details/gtcotsxtvw.html

[U102] JS：本地存储
来源：http://dali.andypj.xyz/Article/details/gtwczyrwfv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtheutyyxx.html

[U103] JS：定时器
来源：http://dali.sufxvd.cn/Article/details/gtnxxchpkl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.aibaodan.cn/Article/details/gtvcymuwvg.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gtqdcgjmhc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtyzhalyun.html

[U105] JS：节流
来源：http://dali.chenlongwang.top/Article/details/gtjjbtidgr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtqpxosrxb.html

[U106] JS：日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtsqegudky.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtnkdqreyk.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gtganfttdr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dashuyun.cn/Article/details/gtvxmsjrom.html

[U108] JS：随机整数
来源：http://dali.wangdashe.top/Article/details/gtzjwrwiiw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zdqjudy.top/Article/details/gtiadgorbu.html

[U109] JS：数组分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupiyhpev.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtzxtrvizi.html

[U110] JS：数组分块
来源：http://dali.daxiang520.top/Article/details/gtcqqpbika.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gtzzpdpmnq.html

[U111] JS：对象转 Map
来源：http://dali.aibaodan.cn/Article/details/gtgirlcirg.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtkqxiqwpg.html

[U112] JS：字符串补位
来源：http://dali.snrcjt.cn/Article/details/gteqiiuoxh.html

"7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtjcfnvufq.html

[U113] JS：正则替换全部
来源：http://dali.hnxiangtu.top/Article/details/gtcfgmsomv.html

s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtzjmxcaso.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtiqnmdiaz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtovqbvaoi.html

[U115] JS：生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtaehlhowj.html

crypto.randomUUID()
来源：http://dali.nanxuanxn.top/Article/details/gttrccgazp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hywenlv.cn/Article/details/gtqwpfeovu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.316326.xyz/Article/details/gtnticxgka.html

[U117] JS：单元测试
来源：http://dali.fzhhl.top/Article/details/gtpcnkyxlw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxygrsaxy.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtwuyyjdyo.html

npm i -D vite;  npx vite
来源：http://dali.vqdsnc.cn/Article/details/gtgqpbuuck.html

[U119] JS：生产构建
来源：http://dali.yuanzhike.top/Article/details/gtdtkzgwjg.html

npx vite build
来源：http://dali.jianghu66.top/Article/details/gtdmdibhlx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtwawgqhog.html

import.meta.env.VITE_API_URL
来源：http://dali.nwbrower.top/Article/details/gtltwyskpd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlpiytxkx.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtrmvaqjfx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqatzbluw.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtxklzifkm.html

Python ......... 252
来源：http://dali.ehwqpu.com/Article/details/gtyuagpwld.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gtyvpufnkc.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gtwulwnxya.html

TypeScript ..... 212
来源：http://dali.jinqigufen.top/Article/details/gtzkayxxtt.html

Java ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gticgwbuxm.html

Go ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtugdvceds.html

Ruby ........... 212
来源：http://dali.ivvv.top/Article/details/gtcyxbicgk.html

C# ............. 212
来源：http://dali.9152youxi.cn/Article/details/gtulcrykim.html

C .............. 30
来源：http://dali.ivvv.top/Article/details/gthpqjgtym.html

C++ ............ 30
来源：http://dali.daria6918.cn/Article/details/gtoyelttpi.html

SQL ............ 90
来源：http://dali.pengpengdd.cyou/Article/details/gtcrtsbsgh.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gtwszgodnx.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gtsalzqcml.html

Swift .......... 15
来源：http://dali.hfpthk.cn/Article/details/gtrbynktyy.html

Lua ............ 10
来源：http://dali.cqqwz.cn/Article/details/gtxlltitle.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtvxradmsz.html

Scala .......... 10
来源：http://dali.dashuyun.cn/Article/details/gtnecxddej.html

------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtjkplwury.html

合计 ........... 2106 条
来源：http://dali.xuanzx.com/Article/details/gtqxcwmrsy.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gtahdeomem.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gtywetyete.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.sysykeji.top/Article/details/gtvrnpcpdp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gtpoievqbt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.guowangkeji.top/Article/details/gtbebdlvuk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.birdmap.top/Article/details/gtmjxbhwpg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtpedofdij.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gthgmmtlbp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gtnsdyabfq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gtegtyhnlt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqlvcfth.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gteltwzpyc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gtcyghchuz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gthilahiby.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guannengcc.top/Article/details/gtyirnynvq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.aizwys.cn/Article/details/gtlxecyqny.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gttbhgnytx.html

Q SQL 专题                              90
来源：http://dali.meibo888.top/Article/details/gticjorwzf.html

R Bash 专题                             80
来源：http://dali.daria6918.cn/Article/details/gtcdqogzao.html

S C / C++ 专题                          60
来源：http://dali.aizwys.cn/Article/details/gtgcanttda.html

T 其他语言补充                          60
来源：http://dali.guannengcc.top/Article/details/gtcgehwsql.html

U 高频实用片段                         120
来源：http://dali.guowangkeji.top/Article/details/gtmdoaagjf.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gtwkjisrzr.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gtqojavscv.html

--------------------------------------------------------------------------------
来源：http://dali.yongpay.top/Article/details/gtnbtcbqqt.html

使用提醒
来源：http://dali.cqqwz.cn/Article/details/gtwwhwdijc.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gtwvmfnbak.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hammf.cn/Article/details/gtpnmtewva.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhiwuduotai.top/Article/details/gtvvkpcitl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zycfv.cn/Article/details/gtewwjujpl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aibaodan.cn/Article/details/gtisstfuqj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.hnqzz.top/Article/details/gtoxzhmhig.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gtygfuyndk.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrfdjkzjt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nwbrower.top/Article/details/gtxwdxhkrp.html

Common Programming Examples Cheat Book
来源：http://dali.ybcxt.top/Article/details/gturemzuwj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtzbpowihm.html

【收录内容】
来源：http://dali.yanxiufei.cn/Article/details/gtmcwkbjof.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ydzc1.top/Article/details/gtzggtjjxn.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.birdmap.top/Article/details/gtfqstnqtb.html

SQL · Bash · C · C++
来源：http://dali.sufxvd.cn/Article/details/gthbidopyo.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yonumen.top/Article/details/gtsqdbllmk.html

【使用说明】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulxgclmu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jiagoushi.top/Article/details/gtjbceumhz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.yonumen.top/Article/details/gtusofzcjy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenjidiqi.icu/Article/details/gthxszsosm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklawjzkd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.fzhhl.top/Article/details/gthrfegijf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.guowangkeji.top/Article/details/gtmqcwwaxz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinghuilouyu.cn/Article/details/gtawttaaqc.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxdzbyha.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.cheryme.top/Article/details/gtbnkcrzux.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.sysykeji.top/Article/details/gtgxlbnkkk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.hywenlv.cn/Article/details/gtnoqubgci.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hfpthk.cn/Article/details/gtcwvagqzl.html

【文件统计】
来源：http://dali.zdqjudy.top/Article/details/gtauddnrxo.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.hongshengwenyu.top/Article/details/gtllrqddll.html

--------------------------------------------------------------------------------
来源：http://dali.yanxiufei.cn/Article/details/gtrufstsaw.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtrzpkhbkc.html

--------------------------------------------------------------------------------
来源：http://dali.gotoacloud.top/Article/details/gtumsokylu.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtomtgtrab.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.iojbl.cn/Article/details/gttpfmciyp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.vqdsnc.cn/Article/details/gtoymhuegv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.yonumen.top/Article/details/gtnhihqkcr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.9152youxi.cn/Article/details/gtgrndtuoj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttjoapbqf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zycfv.cn/Article/details/gtoxpkcbkm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtanbmyfcg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yongpay.top/Article/details/gtgraanchn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtgtxdqjis.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.shzxlz.cn/Article/details/gtcoshwlwx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtsphopqkt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gtyddhaane.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.9152youxi.cn/Article/details/gtcsaljyef.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.ehwqpu.com/Article/details/gttwiibogu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.hammf.cn/Article/details/gtgpbpgssw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.hammf.cn/Article/details/gtmtwudroc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.nwbrower.top/Article/details/gtacmycmpy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.yuanzhike.top/Article/details/gtirrakjpo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtsznfcaed.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaypxgpse.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdlemwmji.html

A. 基础语法与类型
来源：http://dali.yuxming.cn/Article/details/gtqkwodcbi.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtcfefzifa.html

[A01] Hello World
来源：http://dali.pycfn.com/Article/details/gtfkgylspj.html

Py:   print("Hello, World!")
来源：http://dali.ivvv.top/Article/details/gtkfjkrwom.html

PHP:  echo "Hello, World!";
来源：http://dali.0kj1m.cn/Article/details/gtgutjrtgo.html

JS:   console.log("Hello, World!");
来源：http://dali.jyoumei.cn/Article/details/gtmznsiuzw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhoulong.xyz/Article/details/gtnffwmzog.html

Java: System.out.println("Hello, World!");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxekvncx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yonumen.top/Article/details/gtgtpgxxcm.html

Ruby: puts "Hello, World!"
来源：http://dali.fengsongda.top/Article/details/gttidoolyb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtttlneouo.html

[A02] 变量声明与赋值
来源：http://dali.hfpthk.cn/Article/details/gtrsjallxv.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.cdnleiting.top/Article/details/gtogwruecv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.mhx1999.top/Article/details/gtyrjgsjdy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.guannengcc.top/Article/details/gtzmppjnqy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.sweek.top/Article/details/gtxakesoqk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.0kj1m.cn/Article/details/gtynivqclp.html

Go:   name := "Alex"; age := 20
来源：http://dali.sweek.top/Article/details/gtczzgqlcp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.aibaodan.cn/Article/details/gtztmkhkjv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.shuidangran.top/Article/details/gtbrqevnyd.html

[A03] 常量定义
来源：http://dali.sysykeji.top/Article/details/gtsypeablq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yanxiufei.cn/Article/details/gtvomzixkj.html

PHP:  const PI = 3.14159;
来源：http://dali.yongpay.top/Article/details/gtnqoiklrw.html

JS:   const PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtwinlwsjv.html

TS:   const PI: number = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtmnehxhsh.html

Java: static final double PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gthmqucdme.html

Go:   const PI = 3.14159
来源：http://dali.guannengcc.top/Article/details/gtwzuaafhp.html

Ruby: PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gtruvfvfkk.html

C#:   const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtyymmvqzo.html

[A04] 判断变量类型
来源：http://dali.zhengqikj.top/Article/details/gtfiknqeja.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.meibo888.top/Article/details/gtsvybdrdt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.redwolf501.top/Article/details/gtnmfgpbfu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fzhhl.top/Article/details/gtkvcoajqc.html

TS:   typeof x; x instanceof Date
来源：http://dali.hfpthk.cn/Article/details/gthpshiuxm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.andypj.xyz/Article/details/gtmsqmcxpq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jyoumei.cn/Article/details/gtbtbdxfuh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.hywenlv.cn/Article/details/gtofzvlvwd.html

C#:   x.GetType().Name; x is int
来源：http://dali.xylfe.cn/Article/details/gtfmoovhrb.html

[A05] 整数除法与取模
来源：http://dali.ehwqpu.com/Article/details/gtnjdrdjtm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtakjuehug.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtcnmglsux.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtvqmdirql.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gtsnqwagmr.html

Java: 7 / 2; 7 % 2
来源：http://dali.wangdashe.top/Article/details/gtgtuhtoca.html

Go:   7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gtjdvhxhua.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yongpay.top/Article/details/gtvvwzghjb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gtfiyovkqq.html

[A06] 字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtvtynzzuz.html

Py:   int("42"); float("3.14")
来源：http://dali.nanxuanxn.top/Article/details/gtwxfemysu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.gotoacloud.top/Article/details/gtmgwyudrl.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxigohhq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hfpthk.cn/Article/details/gtpdilzaej.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenlongwang.top/Article/details/gttotnuees.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.xziqi.cn/Article/details/gtienoafff.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jlsjyb.cn/Article/details/gtsuqnnigy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aibaodan.cn/Article/details/gtvjuvshzn.html

[A07] 数字转字符串
来源：http://dali.cqqwz.cn/Article/details/gtnrbikjit.html

Py:   str(42)
来源：http://dali.zhixingplan.top/Article/details/gtfdvnskqx.html

PHP:  (string) 42; strval(42)
来源：http://dali.316326.xyz/Article/details/gtobpwqgbn.html

JS:   String(42); (42).toString()
来源：http://dali.chenzaomai.com/Article/details/gtipgiinvp.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtfjmidchc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.0kj1m.cn/Article/details/gtmzzjeofg.html

Go:   strconv.Itoa(42)
来源：http://dali.jyoumei.cn/Article/details/gtcehuugqs.html

Ruby: 42.to_s
来源：http://dali.ivvv.top/Article/details/gtybgldccl.html

C#:   42.ToString()
来源：http://dali.vqdsnc.cn/Article/details/gtdojcusyx.html

[A08] 取整与四舍五入
来源：http://dali.nanxinkj.top/Article/details/gtmcjyouki.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.hnqzz.top/Article/details/gtmdfhnxrn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.xylfe.cn/Article/details/gtiskrtzoc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgkqaazi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.pengpengdd.cyou/Article/details/gtsclqrmfw.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jinqigfzy.top/Article/details/gttukgkyty.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yj20258.top/Article/details/gtotwlevyu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.hysaishi.cn/Article/details/gtdmfzecwa.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.andypj.xyz/Article/details/gtphgzgafi.html

[A09] 绝对值与最大最小值
来源：http://dali.c1oappe.top/Article/details/gtatuawryk.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtoqmfipgs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtzqrbfalb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtabcplfxp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gttbmutjoy.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.daxiang520.top/Article/details/gthysxhhwa.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jianghu66.top/Article/details/gtusezrrvq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gaohongyu789.top/Article/details/gthsnhjplu.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtaxsnxiuh.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtzpgawvfz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.0kj1m.cn/Article/details/gtvmvfpulj.html

PHP:  random_int(1, 100);
来源：http://dali.tian-w.cn/Article/details/gtuxhxrihj.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guannengcc.top/Article/details/gtmuwrifvy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtjpgwoaxv.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yonumen.top/Article/details/gtdfdzyssw.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.redwolf501.top/Article/details/gtnnhszjoz.html

Ruby: rand(1..100)
来源：http://dali.xuanzx.com/Article/details/gtymspzdpi.html

C#:   new Random().Next(1, 101)
来源：http://dali.jyoumei.cn/Article/details/gtjtqontzr.html

[A11] 条件表达式（三元）
来源：http://dali.kuanghao11.cn/Article/details/gtvdrwybgf.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.316326.xyz/Article/details/gtyfypdfzi.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtlalrjetd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hammf.cn/Article/details/gtbmyzjwik.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtrxwgjtza.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jyoumei.cn/Article/details/gtilnppuvy.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.tianlin.xyz/Article/details/gtglymsvak.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.chenlongwang.top/Article/details/gtqfjlzjkl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtrfolbckr.html

[A12] 字符串插值 / 格式化
来源：http://dali.smart0.xyz/Article/details/gtxjvtcpwk.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.ivvv.top/Article/details/gtqmpbbpgi.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.chenzaomai.com/Article/details/gtjjfpxmxg.html

JS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtqerhsiaq.html

TS:   `Hello, ${name}!`
来源：http://dali.sysykeji.top/Article/details/gtdqskxlml.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.chenzaomai.com/Article/details/gtxduvpiug.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ybcxt.top/Article/details/gtdrkiotqi.html

Ruby: "Hello, #{name}!"
来源：http://dali.ybcxt.top/Article/details/gtpjezpcaf.html

C#:   $"Hello, {name}!"
来源：http://dali.pengpengdd.cyou/Article/details/gtwoexnouz.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guannengcc.top/Article/details/gttfsoasvd.html

Py:   "第一行\n第二行"
来源：http://dali.hywenlv.cn/Article/details/gtsqcfylut.html

PHP:  "第一行\n第二行"
来源：http://dali.jlsjyb.cn/Article/details/gtghctidls.html

JS:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtiixtigqz.html

TS:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtnnwqozgz.html

Java: "第一行\n第二行"
来源：http://dali.wangshuangyany.cn/Article/details/gtxsnqxyur.html

Go:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxzkjfubl.html

Ruby: "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtzowfymji.html

C#:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtftdbuauj.html

[A14] 注释写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijwhcwqb.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.9152youxi.cn/Article/details/gttdfxdouy.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtjjlsrhvq.html

JS:   // 单行；/* 多行 */
来源：http://dali.yonumen.top/Article/details/gtrwlaykms.html


<!-- 参考信息 -->