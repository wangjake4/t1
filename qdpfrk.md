代发 wailian999

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gtlurtzugi.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtkwdrfnqp.html

[U86] JS：空值合并
来源：http://dali.gogol.net.cn/Article/details/gtyhobgglw.html

a ?? b
来源：http://dali.hfpthk.cn/Article/details/gtjmdquuvt.html

[U87] JS：解构默认值
来源：http://dali.yj202588.top/Article/details/gttaocvddt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfipqrroy.html

[U88] JS：对象展开合并
来源：http://dali.xinyue.icu/Article/details/gtdiqdnlbt.html

{ ...a, ...b }
来源：http://dali.yanxiufei.cn/Article/details/gtdctdwzwo.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gtlmiirqla.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtmdruywur.html

[U90] JS：数字数组排序
来源：http://dali.xinyue.icu/Article/details/gtmamqnitb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwuymbtsi.html

[U91] JS：对象键值遍历
来源：http://dali.jinqigfzy.top/Article/details/gtlujzlgcq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gtdmbxurzm.html

[U92] JS：深拷贝
来源：http://dali.hnxiangtu.top/Article/details/gtqfuwcxtj.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtgqtfwzrb.html

[U93] JS：模板字符串
来源：http://dali.xylfe.cn/Article/details/gteauushab.html

`共 ${n} 条`
来源：http://dali.fzhhl.top/Article/details/gtkyrfesfn.html

[U94] JS：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtgtxbnkbu.html

const double = x => x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtanwrsrfj.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtiwwxsxus.html

new Promise((resolve, reject) => {})
来源：http://dali.hnqzz.top/Article/details/gthgbskhgk.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtvcmcufor.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfikadcks.html

[U97] JS：并发请求
来源：http://dali.dianchejie.cn/Article/details/gthtmskgbl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gtpbhxwxik.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gtcqjaqmfg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gtvkpasezb.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gtkibfvqim.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtjelzahfg.html

[U100] JS：DOM 查询
来源：http://dali.ydzc1.top/Article/details/gtdpqozegf.html

document.querySelector(".item")
来源：http://dali.guowangkeji.top/Article/details/gtfwcoxdyx.html

[U101] JS：classList 操作
来源：http://dali.dianchejie.cn/Article/details/gtcfioxefx.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtfhbptcnb.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gtkvwivdmd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gtbbwpsvtt.html

[U103] JS：定时器
来源：http://dali.316326.xyz/Article/details/gtlqtckcmg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gtwhondzjg.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gtsoocfudx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtbiwcshvg.html

[U105] JS：节流
来源：http://dali.iojbl.cn/Article/details/gtasutukqp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hysaishi.cn/Article/details/gtgaqnbpqz.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtkvgdacmw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuxming.cn/Article/details/gtlgxkyqfe.html

[U107] JS：数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtdqsmyxjl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtgjwhewtx.html

[U108] JS：随机整数
来源：http://dali.jqgufenzy.top/Article/details/gtbyafttlo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ehwqpu.com/Article/details/gtwqljwoam.html

[U109] JS：数组分组
来源：http://dali.ydzc1.top/Article/details/gtbdvqgvhs.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtuitfbbcl.html

[U110] JS：数组分块
来源：http://dali.zdqjudy.top/Article/details/gtkftoqgrn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinqigfzy.top/Article/details/gtyhrjgmsk.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtirpoilwo.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gtumoraljx.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtzcsqozww.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlezecccj.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gtxqgermqd.html

s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtzyalrsgn.html

[U114] JS：JSON 深比较
来源：http://dali.guowangkeji.top/Article/details/gtzneuxydd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtwpsncerj.html

[U115] JS：生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtgrfccjla.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtduvltfca.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtjapbbhdu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gthgaqixla.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtipnuarxc.html

npm i -D vitest;  npx vitest
来源：http://dali.snrcjt.cn/Article/details/gtfvydquoy.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gtalyqdivi.html

npm i -D vite;  npx vite
来源：http://dali.aizwys.cn/Article/details/gtswhbcvlo.html

[U119] JS：生产构建
来源：http://dali.vqdsnc.cn/Article/details/gtkpngzjuk.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gtrisummpe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gtbavaoyww.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gtyucygkic.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtnppexopi.html

统计汇总
来源：http://dali.hammf.cn/Article/details/gtddmrrabo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtnkipiyqo.html

按语言统计（条）：
来源：http://dali.ppjwa.cn/Article/details/gtyzuenqgj.html

Python ......... 252
来源：http://dali.gogol.net.cn/Article/details/gtjlczstmt.html

PHP ............ 252
来源：http://dali.9152youxi.cn/Article/details/gtfbmxfudi.html

JavaScript ..... 252
来源：http://dali.ehwqpu.com/Article/details/gtdfxlbghx.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gtxnicgrgr.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtobdfigxy.html

Go ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnokoafqr.html

Ruby ........... 212
来源：http://dali.daxiang520.top/Article/details/gtxzefwjcw.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtaoxkpsit.html

C .............. 30
来源：http://dali.zdqjudy.top/Article/details/gtzjlsaolu.html

C++ ............ 30
来源：http://dali.chenjidiqi.icu/Article/details/gtxbsyljxi.html

SQL ............ 90
来源：http://dali.xuetiantiany.cn/Article/details/gteaoqqjxi.html

Bash ........... 80
来源：http://dali.daria6918.cn/Article/details/gtsuwfuqdc.html

Kotlin ......... 15
来源：http://dali.jqgfzy.top/Article/details/gtouibfkuj.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gtgzapdfha.html

Lua ............ 10
来源：http://dali.guannengcc.top/Article/details/gtmmenizjh.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtztqeuuvz.html

Scala .......... 10
来源：http://dali.tanke756.top/Article/details/gtxionspuo.html

------------------------------------
来源：http://dali.zhengqikj.top/Article/details/gtgciaaesl.html

合计 ........... 2106 条
来源：http://dali.daria6918.cn/Article/details/gtsbhtrddo.html

按章节统计：
来源：http://dali.zhengqikj.top/Article/details/gttlhnqgfa.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyruupvbb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gthqzwdwwi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtfamximxw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.fzhhl.top/Article/details/gtphdjypnp.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.bjfxy.top/Article/details/gtfwgfdsae.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jqgufenzy.top/Article/details/gtvupcsqfi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gtcbhwwhxp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtyvijbxaf.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtezjkilnb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yangfankeji.com/Article/details/gtekhqbcrq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.feifeiyinyue.top/Article/details/gtgativbar.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gtvztabwwh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbybagljl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jinqigfzy.top/Article/details/gtzznntdem.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hysaishi.cn/Article/details/gtlwahuxfc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtbeguppej.html

Q SQL 专题                              90
来源：http://dali.wangshuangyany.cn/Article/details/gtodnhqieu.html

R Bash 专题                             80
来源：http://dali.sxryk.cn/Article/details/gtcpqswwtq.html

S C / C++ 专题                          60
来源：http://dali.aibaodan.cn/Article/details/gtnkbwzzlm.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gttjrqenia.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gthjkehcta.html

------------------------------------
来源：http://dali.tanke756.top/Article/details/gtcnxmachp.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtjgpqtrba.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtlkxysrlo.html

使用提醒
来源：http://dali.zycfv.cn/Article/details/gtlmqnoxda.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtkcycrxav.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yj20258.top/Article/details/gtewlqxhil.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefogcrba.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.ivvv.top/Article/details/gtbdaiooup.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nwbrower.top/Article/details/gtnzitqoyl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.cashguo.top/Article/details/gtdjiqhobf.html

—— 文件结束 ——
来源：http://dali.gogol.net.cn/Article/details/gtoufbwgao.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgwlpicls.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.chenjidiqi.icu/Article/details/gthozodhhs.html

Common Programming Examples Cheat Book
来源：http://dali.yj202588.top/Article/details/gtpvaikwjc.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtemhiewnr.html

【收录内容】
来源：http://dali.zhoulong.xyz/Article/details/gtkclfdihj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.yuanzhike.top/Article/details/gttjqdwbzo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.0kj1m.cn/Article/details/gtqdnlwrqv.html

SQL · Bash · C · C++
来源：http://dali.mhx1999.top/Article/details/gtykrloshr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yuxming.cn/Article/details/gtihbjvvmx.html

【使用说明】
来源：http://dali.nanxuanxn.top/Article/details/gtjwraknnp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.chenlongwang.top/Article/details/gtzexelhdf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cheryme.top/Article/details/gttxliagiy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cdnleiting.top/Article/details/gtotyprkvo.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gzhubu.top/Article/details/gtrusibnvq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpntuziyf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.jiagoushi.top/Article/details/gtomdkkffy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hfpthk.cn/Article/details/gtfvdaeivf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.daria6918.cn/Article/details/gtpfreqnxr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfywrelut.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyfepbao.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.andypj.xyz/Article/details/gtafrmqjzh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.kuanghao11.cn/Article/details/gtnsdqjpha.html

【文件统计】
来源：http://dali.wangshuangyany.cn/Article/details/gtypkzmrhm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.0kj1m.cn/Article/details/gteshrstda.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtpybxeffo.html

目  录
来源：http://dali.jinghuilouyu.cn/Article/details/gtlzrtrzmj.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtodaqdtup.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtzucwrcxr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgxwfrdus.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yj20258.top/Article/details/gtyxdkacdr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.cashguo.top/Article/details/gtwtuodxug.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.iojbl.cn/Article/details/gtemayjqdj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.kuanghao11.cn/Article/details/gtnvpjmdbb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtaywhjfel.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.ydzc1.top/Article/details/gtafcpvfic.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtuulwrdbh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jiagoushi.top/Article/details/gtleeertff.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtbhjikxnc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.mhx1999.top/Article/details/gtqvwerbbr.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxydfhhzb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tian-w.cn/Article/details/gtvadjhvti.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.havefunace.top/Article/details/gtgnridilz.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gthbogixzl.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gtzslszxyv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.jiagoushi.top/Article/details/gteuyutdyo.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenjidiqi.icu/Article/details/gtbrmlwmvo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhiwuduotai.top/Article/details/gtlwwnvgae.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtadwkmmnm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmiwqjymf.html

A. 基础语法与类型
来源：http://dali.daria6918.cn/Article/details/gtglcibjzu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbsyrtfwz.html

[A01] Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtdubrkeuc.html

Py:   print("Hello, World!")
来源：http://dali.zhongyouzk.top/Article/details/gtaoflyhra.html

PHP:  echo "Hello, World!";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprjhwdre.html

JS:   console.log("Hello, World!");
来源：http://dali.zycfv.cn/Article/details/gtnzjyhgmd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hnqzz.top/Article/details/gtpffnurdj.html

Java: System.out.println("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtyuwmxbuz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yuxming.cn/Article/details/gtideffjqt.html

Ruby: puts "Hello, World!"
来源：http://dali.yonumen.top/Article/details/gtqcbsbrnm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhoulong.xyz/Article/details/gtqqexjqvt.html

[A02] 变量声明与赋值
来源：http://dali.yj20258.top/Article/details/gtuylfvthr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhongyouzk.top/Article/details/gtmcltgmqo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.ybcxt.top/Article/details/gtzbgqffat.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yvedp.cn/Article/details/gtyuaqvryw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.haohaochexian.top/Article/details/gtlcmfvbzo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sufxvd.cn/Article/details/gtgtrzrfqo.html

Go:   name := "Alex"; age := 20
来源：http://dali.chenjidiqi.icu/Article/details/gtgcmshybg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhengqikj.top/Article/details/gtcahpylxv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtaspmbxvc.html

[A03] 常量定义
来源：http://dali.hnxiangtu.top/Article/details/gtilezufla.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtnnlcomuy.html

PHP:  const PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtrkpuczfg.html

JS:   const PI = 3.14159;
来源：http://dali.yueranfly.top/Article/details/gtscfymyvd.html

TS:   const PI: number = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtvkekkajh.html

Java: static final double PI = 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtkieoqsnl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtorojhbtu.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtthdvifqe.html

C#:   const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gttvfxtyds.html

[A04] 判断变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtqqjgknig.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.pycfn.com/Article/details/gtdvxaffwn.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daria6918.cn/Article/details/gtkdojdbvs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.cucudq.cn/Article/details/gtfjssiojw.html

TS:   typeof x; x instanceof Date
来源：http://dali.aizwys.cn/Article/details/gtmlalmxcl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jyoumei.cn/Article/details/gtybkufqzr.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yueranfly.top/Article/details/gtfftmhpqt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.iojbl.cn/Article/details/gtauaeerxj.html

C#:   x.GetType().Name; x is int
来源：http://dali.kuanghao11.cn/Article/details/gtzznxmrbk.html

[A05] 整数除法与取模
来源：http://dali.nanxinkj.top/Article/details/gtspfelzqk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.hysaishi.cn/Article/details/gtjwaynucv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.nwbrower.top/Article/details/gtthxzpjbj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gtcgahvnld.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.sxryk.cn/Article/details/gtlyrlrikg.html

Java: 7 / 2; 7 % 2
来源：http://dali.daria6918.cn/Article/details/gtshsszgfi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtkulbrknz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtiltebtci.html

C#:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtpwhxbuta.html

[A06] 字符串转数字
来源：http://dali.yongpay.top/Article/details/gtkwvpgymn.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtgutfrjgk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.nanxuanxn.top/Article/details/gtbxjcyiik.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cheryme.top/Article/details/gtfyjljuqz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.svipenyu.cn/Article/details/gtlxsgbnwb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gtgetyxcyj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jianghu66.top/Article/details/gtmifgcuoi.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gtudjegfpy.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cheryme.top/Article/details/gtwwlkftpk.html

[A07] 数字转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtbzsbzxjg.html

Py:   str(42)
来源：http://dali.hnxiangtu.top/Article/details/gtnsydyqah.html

PHP:  (string) 42; strval(42)
来源：http://dali.smart0.xyz/Article/details/gtggcbydyh.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gtygkeqffq.html

TS:   String(42)
来源：http://dali.vqdsnc.cn/Article/details/gtohkmmupq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhengqikj.top/Article/details/gtagzstnoi.html

Go:   strconv.Itoa(42)
来源：http://dali.yongpay.top/Article/details/gtikemlkbc.html

Ruby: 42.to_s
来源：http://dali.yuanzhike.top/Article/details/gtksqhjfak.html

C#:   42.ToString()
来源：http://dali.xylfe.cn/Article/details/gtlgshuosq.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gtcfkbgbxm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtlxqzgjmk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.meibo888.top/Article/details/gtgmvrttwh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.nanxinkj.top/Article/details/gthsgcrjta.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.xuetiantiany.cn/Article/details/gtnafwelxk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.sxryk.cn/Article/details/gtcfrekkle.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.jqgufenzy.top/Article/details/gtxhghnhdo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.guannengcc.top/Article/details/gtfcyrwimz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zdqjudy.top/Article/details/gtbrdhuhcr.html

[A09] 绝对值与最大最小值
来源：http://dali.hnqzz.top/Article/details/gtluyrbjkv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cheryme.top/Article/details/gtbzibgvsv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.fengsongda.top/Article/details/gteubneyfm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shzxlz.cn/Article/details/gtnqhdssnh.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtkmwvlbil.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtdjorshkt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.bjfxy.top/Article/details/gtdoykxnwy.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.0kj1m.cn/Article/details/gtrlhdzybv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gteyrqfxbz.html

[A10] 生成随机数
来源：http://dali.hnxiangtu.top/Article/details/gtcbxakusy.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtajoiwruq.html

PHP:  random_int(1, 100);
来源：http://dali.hywenlv.cn/Article/details/gttyccavsb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.chenlongwang.top/Article/details/gtxtrufbid.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhiwuduotai.top/Article/details/gtcpextghd.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gthldvhvuv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yangfankeji.com/Article/details/gtehdodctw.html

Ruby: rand(1..100)
来源：http://dali.aibaodan.cn/Article/details/gtxergmlyd.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258888.top/Article/details/gtzlwijkpw.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gtybhwrjln.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.yueranfly.top/Article/details/gtxyvmgpdh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtfigrdjzm.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.gotoacloud.top/Article/details/gthsxusxbm.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gtpijmwnhx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jqgfzy.top/Article/details/gtwhtjkfll.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ppjwa.cn/Article/details/gtrpqtapfj.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtojvmuspx.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gtxnzpcexa.html

[A12] 字符串插值 / 格式化
来源：http://dali.fengsongda.top/Article/details/gtllkfxgog.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.yj202588.top/Article/details/gtqflpvttg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlclkzwuj.html

JS:   `Hello, ${name}!`
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslwxkplp.html

TS:   `Hello, ${name}!`
来源：http://dali.sweek.top/Article/details/gtmdznprqa.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hysaishi.cn/Article/details/gtflylvcyi.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.zhixingplan.top/Article/details/gtqupldhfc.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtojicqcar.html

C#:   $"Hello, {name}!"
来源：http://dali.zhongyouzk.top/Article/details/gticrjonpa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.xuetiantiany.cn/Article/details/gtojwidpkv.html

Py:   "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtxdyeepjz.html

PHP:  "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gtacxlfgkk.html

JS:   "第一行\n第二行"
来源：http://dali.bjfxy.top/Article/details/gtcotcmuaz.html

TS:   "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtjfqnfycf.html

Java: "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtkynyoleq.html

Go:   "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtxstlgpph.html

Ruby: "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtxyukbwxs.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtrppympdh.html

[A14] 注释写法
来源：http://dali.sufxvd.cn/Article/details/gttysntsze.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.nanxuanxn.top/Article/details/gtidpjugzg.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefsjcmuy.html

JS:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtyivlspyn.html


<!-- 参考信息 -->