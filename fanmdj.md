代发 wailian999

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gt2gkunyire.html

new Promise((resolve, reject) => {})
来源：http://dali.iojbl.cn/Article/details/gt2vwwxppla.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gt2krqywqbm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gt2wttnfhor.html

[U97] JS：并发请求
来源：http://dali.zdqjudy.top/Article/details/gt2dbjejydj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2doqwsywb.html

[U98] JS：fetch 带 JSON
来源：http://dali.gogol.net.cn/Article/details/gt2lbwacyrh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hongshengwenyu.top/Article/details/gt2hidjnrmz.html

[U99] JS：事件监听
来源：http://dali.hammf.cn/Article/details/gt2jjdvztff.html

el.addEventListener("click", e => {})
来源：http://dali.nanxinkj.top/Article/details/gt2xcaetcwc.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gt2mbcjmwkz.html

document.querySelector(".item")
来源：http://dali.hfpthk.cn/Article/details/gt2vpxpwgrn.html

[U101] JS：classList 操作
来源：http://dali.gogol.net.cn/Article/details/gt2ckcxjpav.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gt2mkihmbgq.html

[U102] JS：本地存储
来源：http://dali.wangshuangyany.cn/Article/details/gt2aywydjfa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiyjaohj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwmhdcf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.snrcjt.cn/Article/details/gt2thvjrvyt.html

[U104] JS：防抖
来源：http://dali.yonumen.top/Article/details/gt2vyplkxoi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnjvxlg.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gt2hhontvtd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nwbrower.top/Article/details/gt2zrvukmdw.html

[U106] JS：日期格式化
来源：http://dali.hammf.cn/Article/details/gt2akdewrxm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gt2bpakqdgm.html

[U107] JS：数字千分位
来源：http://dali.havefunace.top/Article/details/gt2bgeumfci.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qllsfpbs.html

[U108] JS：随机整数
来源：http://dali.jianghu66.top/Article/details/gt2vrnozwjc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbxhanhn.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gt2vymzogbh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2exsyddcv.html

[U110] JS：数组分块
来源：http://dali.birdmap.top/Article/details/gt2vkmhpxld.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xinyue.icu/Article/details/gt2sxgxakfb.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gt2yrpibkrl.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gt2jrgwrlmq.html

[U112] JS：字符串补位
来源：http://dali.cucudq.cn/Article/details/gt2gjeywfbp.html

"7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2bjqikuqe.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gt2sceyltlx.html

s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2grcmwooa.html

[U114] JS：JSON 深比较
来源：http://dali.andypj.xyz/Article/details/gt2jvsuskrs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2hievhqbc.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gt2uahgeyob.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2qtrcicdl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.smart0.xyz/Article/details/gt2hvhlxsdq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzkzierp.html

[U117] JS：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gt2gednruey.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gt2gcrygtef.html

[U118] JS：开发服务器
来源：http://dali.316326.xyz/Article/details/gt2sbkpqcmw.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gt2bkydyhfu.html

[U119] JS：生产构建
来源：http://dali.yj20258888.top/Article/details/gt2waoxjlxb.html

npx vite build
来源：http://dali.jqgfzy.top/Article/details/gt2xcaflodo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gt2zkmqzvrv.html

import.meta.env.VITE_API_URL
来源：http://dali.jinqigfzy.top/Article/details/gt2kimplcza.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2vwifcfay.html

统计汇总
来源：http://dali.meibo888.top/Article/details/gt2rrskvxrm.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2yghsewzz.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gt2bjreunpf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqyjuak.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gt2ktsptvsa.html

JavaScript ..... 252
来源：http://dali.yanxiufei.cn/Article/details/gt2zrxcryax.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gt2sbewujpb.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gt2pmfgeyjt.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gt2fvdupmyy.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gt2lwiynymm.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gt2jfbkkrby.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gt2gdrvljqg.html

C++ ............ 30
来源：http://dali.tianlin.xyz/Article/details/gt2kkiiiygw.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gt2inowjggv.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gt2crzitcze.html

Kotlin ......... 15
来源：http://dali.bjfxy.top/Article/details/gt2uzbxajuj.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gt2goszvagx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwiicye.html

Perl ........... 10
来源：http://dali.316326.xyz/Article/details/gt2iryfawag.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gt2waappmym.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gt2obotribz.html

合计 ........... 2106 条
来源：http://dali.fengsongda.top/Article/details/gt2odeaveov.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gt2euroxrkl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2arrjzvtd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gt2homizykd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cqqwz.cn/Article/details/gt2lxqnjohu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gt2lnmkezno.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.nwbrower.top/Article/details/gt2vwhkdtah.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yonumen.top/Article/details/gt2ekjeqxyi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gt2gzcmfkha.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gt2bascpsjd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gt2ewumdhsh.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2lnmwfcjv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.birdmap.top/Article/details/gt2xcvjuahm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2wjrnjxoe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhiwuduotai.top/Article/details/gt2rtvotnwk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.redwolf501.top/Article/details/gt2ynbpzjza.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yj20258.top/Article/details/gt2usirlslz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gt2tusmjabv.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gt2hmknfway.html

R Bash 专题                             80
来源：http://dali.ehwqpu.com/Article/details/gt2dmkrqijq.html

S C / C++ 专题                          60
来源：http://dali.dashuyun.cn/Article/details/gt2cotirogd.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gt2kvqhsrxn.html

U 高频实用片段                         120
来源：http://dali.hammf.cn/Article/details/gt2dtkeblye.html

------------------------------------
来源：http://dali.cdnleiting.top/Article/details/gt2uluaiswm.html

合计                                  2106 条
来源：http://dali.yvedp.cn/Article/details/gt2obyenfxc.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gt2exhqfxlj.html

使用提醒
来源：http://dali.c1oappe.top/Article/details/gt2lboacvqa.html

--------------------------------------------------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gt2owpsjbre.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shangyingyoupin.top/Article/details/gt2quyafjli.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gt2hvynkpwk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.birdmap.top/Article/details/gt2rfiydpbr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gt2uryeulvf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.wangdashe.top/Article/details/gt2zuzfxuxt.html

—— 文件结束 ——
来源：http://dali.tian-w.cn/Article/details/gt2uvhzuymp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lbbhxhfg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hysaishi.cn/Article/details/gt2jmhmdjqk.html

Common Programming Examples Cheat Book
来源：http://dali.316326.xyz/Article/details/gt2httyysmj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vjldfxnl.html

【收录内容】
来源：http://dali.cdnleiting.top/Article/details/gt2rtonbleb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.aibaodan.cn/Article/details/gt2aljgoboz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.fzhhl.top/Article/details/gt2dmbybzhr.html

SQL · Bash · C · C++
来源：http://dali.mhx1999.top/Article/details/gt2bfljlpiy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.shuidangran.top/Article/details/gt2jjiuneyo.html

【使用说明】
来源：http://dali.chenzaomai.com/Article/details/gt2mpkrtfgi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ehwqpu.com/Article/details/gt2sndbbuff.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.haohaochexian.top/Article/details/gt2hruxixvi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.chenzaomai.com/Article/details/gt2wjzkfbtm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.gotoacloud.top/Article/details/gt2boanmhxv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj202588.top/Article/details/gt2oguwrvau.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.9152youxi.cn/Article/details/gt2bjzgayps.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gt2jmyguadz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.pengpengdd.cyou/Article/details/gt2vsdrdjty.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gt2zzuxolxf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hammf.cn/Article/details/gt2fvzabmdx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gt2izxkurjx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fzhhl.top/Article/details/gt2lgpidcfk.html

【文件统计】
来源：http://dali.0kj1m.cn/Article/details/gt2yywflmex.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ehwqpu.com/Article/details/gt2ulqgkhth.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gt2jvieodoa.html

目  录
来源：http://dali.yj20258.top/Article/details/gt2bxagexoj.html

--------------------------------------------------------------------------------
来源：http://dali.bjfxy.top/Article/details/gt2thrijedh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.daxiang520.top/Article/details/gt2cgmqwooi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.hnqzz.top/Article/details/gt2zzkipqqc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gt2ffgfexun.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hywenlv.cn/Article/details/gt2piixxaka.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.hammf.cn/Article/details/gt2goxkzbzd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jqgfzy.top/Article/details/gt2rtppvywi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2kjswlxaf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yuanzhike.top/Article/details/gt2ahnutzuc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gt2uwmtmyrx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2klfqfeua.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2vsrsrsum.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jyoumei.cn/Article/details/gt2mtlfmajy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gt2jszzwdjb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.gogol.net.cn/Article/details/gt2idqliens.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.chenzaomai.com/Article/details/gt2zzjsaohf.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2ennjbdsn.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlgabuhn.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2fpemnkca.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.ehwqpu.com/Article/details/gt2vjtpwjlh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sysykeji.top/Article/details/gt2fvrstwan.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2rjsqangq.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2dikuvvgr.html

A. 基础语法与类型
来源：http://dali.316326.xyz/Article/details/gt2afujcbxx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vqxqylze.html

[A01] Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2esupavzu.html

Py:   print("Hello, World!")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itqpnatp.html

PHP:  echo "Hello, World!";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddtndhhk.html

JS:   console.log("Hello, World!");
来源：http://dali.ppjwa.cn/Article/details/gt2uvsqrpgz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.meibo888.top/Article/details/gt2bgeyygkv.html

Java: System.out.println("Hello, World!");
来源：http://dali.9152youxi.cn/Article/details/gt2dymtteco.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tianlin.xyz/Article/details/gt2amhpsbsk.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gt2mwcfobzw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.guowangkeji.top/Article/details/gt2lkjaadgj.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gt2rfpfsvhb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.svipenyu.cn/Article/details/gt2jamowukl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.cqqwz.cn/Article/details/gt2zeoinxfr.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jianghu66.top/Article/details/gt2rnibpnad.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shuidangran.top/Article/details/gt2nydskcdv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2dykurydm.html

Go:   name := "Alex"; age := 20
来源：http://dali.wangdashe.top/Article/details/gt2flywosbc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.ehwqpu.com/Article/details/gt2sdjxypii.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gt2epzsfefs.html

[A03] 常量定义
来源：http://dali.jianghu66.top/Article/details/gt2sljabciy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gt2uucesymc.html

PHP:  const PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2dwvysywu.html

JS:   const PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gt2hkandjhf.html

TS:   const PI: number = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2sxqzspek.html

Java: static final double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2adzwghor.html

Go:   const PI = 3.14159
来源：http://dali.xylfe.cn/Article/details/gt2riydozwa.html

Ruby: PI = 3.14159
来源：http://dali.yongpay.top/Article/details/gt2awicubdz.html

C#:   const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2alpcevjn.html

[A04] 判断变量类型
来源：http://dali.zhoulong.xyz/Article/details/gt2atwuqhrg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.tianlin.xyz/Article/details/gt2zchkybnk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yuxming.cn/Article/details/gt2tbqgixaf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gt2puhujowq.html

TS:   typeof x; x instanceof Date
来源：http://dali.xziqi.cn/Article/details/gt2vioqqkxq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.cqqwz.cn/Article/details/gt2pevmodtt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gt2mvrotlnp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.316326.xyz/Article/details/gt2hgxchigq.html

C#:   x.GetType().Name; x is int
来源：http://dali.hywenlv.cn/Article/details/gt2ywjxydeq.html

[A05] 整数除法与取模
来源：http://dali.jinqigfzy.top/Article/details/gt2ahuummty.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.xziqi.cn/Article/details/gt2xlppioem.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhxzxizm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2wllmrvla.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zycfv.cn/Article/details/gt2yjtfdiiu.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gt2jucibzla.html

Go:   7 / 2; 7 % 2
来源：http://dali.jianghu66.top/Article/details/gt2vltarxoo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.tanke756.top/Article/details/gt2wxakjwkb.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinqigfzy.top/Article/details/gt2lldjdqvd.html

[A06] 字符串转数字
来源：http://dali.hysaishi.cn/Article/details/gt2sasclrqa.html

Py:   int("42"); float("3.14")
来源：http://dali.aizwys.cn/Article/details/gt2ysjfzmds.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cizgbnry.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.birdmap.top/Article/details/gt2ciptdill.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.jqgfzy.top/Article/details/gt2fcxodmkb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yongpay.top/Article/details/gt2hrtvdple.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zdqjudy.top/Article/details/gt2xjtfldri.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jinqigufen.top/Article/details/gt2uxhfyyhi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2mokzxrhc.html

[A07] 数字转字符串
来源：http://dali.daria6918.cn/Article/details/gt2hrgptftx.html

Py:   str(42)
来源：http://dali.bjfxy.top/Article/details/gt2lsobttaz.html

PHP:  (string) 42; strval(42)
来源：http://dali.tanke756.top/Article/details/gt2cgzbrttf.html

JS:   String(42); (42).toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukeknljc.html

TS:   String(42)
来源：http://dali.bjfxy.top/Article/details/gt2ibymgvkb.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.mhx1999.top/Article/details/gt2kaxfpaph.html

Go:   strconv.Itoa(42)
来源：http://dali.jianghu66.top/Article/details/gt2hewlacgv.html

Ruby: 42.to_s
来源：http://dali.jlsjyb.cn/Article/details/gt2adklixat.html

C#:   42.ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2scsbqkfy.html

[A08] 取整与四舍五入
来源：http://dali.sufxvd.cn/Article/details/gt2vgqsgnjd.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gt2srltkdjp.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.aibaodan.cn/Article/details/gt2cdxdukcq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gt2ldxtmzgx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.quarkkingdee.top/Article/details/gt2ebtkohop.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gt2vofxswjr.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gt2hjwtjtmu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.dashuyun.cn/Article/details/gt2ryodgzaz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhongyouzk.top/Article/details/gt2bngdktww.html

[A09] 绝对值与最大最小值
来源：http://dali.sufxvd.cn/Article/details/gt2hguemepg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2kqgvtkcl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lqphrbme.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuqxpntj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2epahbbst.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2urpolfwg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.tanke756.top/Article/details/gt2sgtlflmg.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258.top/Article/details/gt2nfnrkktt.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2atcwurhl.html

[A10] 生成随机数
来源：http://dali.cheryme.top/Article/details/gt2mnyvybfp.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xinyue.icu/Article/details/gt2xseggnos.html

PHP:  random_int(1, 100);
来源：http://dali.chenzaomai.com/Article/details/gt2trmbwwyz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnqzz.top/Article/details/gt2qvhqdiyj.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.c1oappe.top/Article/details/gt2ijuehdrj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.sufxvd.cn/Article/details/gt2rwcwdbfe.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.tianlin.xyz/Article/details/gt2gosjwjol.html

Ruby: rand(1..100)
来源：http://dali.cucudq.cn/Article/details/gt2ggcyzygy.html

C#:   new Random().Next(1, 101)
来源：http://dali.cqqwz.cn/Article/details/gt2hpoewzhb.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddmlafbh.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufvoewjj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gt2bvtsiqcj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yueranfly.top/Article/details/gt2mszgrjlc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gt2vducvxzv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.xylfe.cn/Article/details/gt2mcunvauc.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.ybcxt.top/Article/details/gt2rbnczvgy.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hysaishi.cn/Article/details/gt2lshroiih.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gt2xwtedmdo.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gt2fcppkeyx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.xinyue.icu/Article/details/gt2sybyyorr.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxpyrgtz.html

JS:   `Hello, ${name}!`
来源：http://dali.aizwys.cn/Article/details/gt2ienvsema.html

TS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gt2zzouuqsq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.316326.xyz/Article/details/gt2jhulflzv.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.chenlongwang.top/Article/details/gt2zwxlnzxt.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuetiantiany.cn/Article/details/gt2cgbqyuzi.html

C#:   $"Hello, {name}!"
来源：http://dali.jlsjyb.cn/Article/details/gt2ikfxwabq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.zhiwuduotai.top/Article/details/gt2ruuyycex.html

Py:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2nzwwwzqx.html

PHP:  "第一行\n第二行"
来源：http://dali.nwbrower.top/Article/details/gt2dftbbiac.html

JS:   "第一行\n第二行"
来源：http://dali.shzxlz.cn/Article/details/gt2mcmomayp.html

TS:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkpiqwnq.html

Java: "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gt2vznzxyva.html

Go:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gt2rckeihes.html

Ruby: "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2abqwnjvp.html

C#:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2szdyxebj.html

[A14] 注释写法
来源：http://dali.andypj.xyz/Article/details/gt2eiawxohk.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gt2dhutpkzd.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gt2myjzkshz.html

JS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gt2mxaytdez.html

TS:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gt2rxvzdueu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guowangkeji.top/Article/details/gt2noknqgay.html

Go:   // 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdyubimh.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.zycfv.cn/Article/details/gt2ndbphhhm.html

C#:   // 单行；/* 多行 */
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ivpjatrx.html

[A15] 空值判断与默认值
来源：http://dali.yj20258888.top/Article/details/gt2hqixanzx.html

Py:   value = data or "默认值"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hkxgzpyt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gt2auqdyqdp.html

JS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gt2opsbnbmz.html

TS:   const value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gt2qvmreuuo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ssqtewut.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhixingplan.top/Article/details/gt2cwrhquzr.html

Ruby: value = data || "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hapqydzh.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinqigufen.top/Article/details/gt2etauevdt.html

[A16] 真假值判断规则
来源：http://dali.zhixingplan.top/Article/details/gt2byxjfbrz.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zhiwuduotai.top/Article/details/gt2xmnauecw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.feifeiyinyue.top/Article/details/gt2cwtkkhmj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxinkj.top/Article/details/gt2rqhnmdfn.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gt2aammnygt.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2avektnkb.html


<!-- 参考信息 -->