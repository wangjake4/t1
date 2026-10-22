代发 wailian999

[U85] JS：可选链
来源：http://dali.xuetiantiany.cn/Article/details/gtumqnebyo.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gtcevnjeps.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtfmabdfwp.html

a ?? b
来源：http://dali.sxryk.cn/Article/details/gtusioacet.html

[U87] JS：解构默认值
来源：http://dali.dianchejie.cn/Article/details/gthijzrdbv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gtydoejygr.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvozjokf.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunfapfrk.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gtczhxgyev.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtcsrzjzad.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gteavtmomq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtuydenfcs.html

[U91] JS：对象键值遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtjtbbenvw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sysykeji.top/Article/details/gtxymqojbu.html

[U92] JS：深拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtzkmpjvef.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtybkdxfqt.html

[U93] JS：模板字符串
来源：http://dali.sysykeji.top/Article/details/gtavvcbfxc.html

`共 ${n} 条`
来源：http://dali.yonumen.top/Article/details/gtnvprhnmq.html

[U94] JS：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtgvazxqur.html

const double = x => x * 2;
来源：http://dali.ehwqpu.com/Article/details/gtnxfzmilg.html

[U95] JS：Promise 包装
来源：http://dali.cdnleiting.top/Article/details/gtrbylwrsp.html

new Promise((resolve, reject) => {})
来源：http://dali.svipenyu.cn/Article/details/gtbnixaxwu.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gtlbzvbrmz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtodrqqzad.html

[U97] JS：并发请求
来源：http://dali.meibo888.top/Article/details/gtbwngljps.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtaaifxkub.html

[U98] JS：fetch 带 JSON
来源：http://dali.ehwqpu.com/Article/details/gtbaijpycs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yuanzhike.top/Article/details/gtvehmvaiq.html

[U99] JS：事件监听
来源：http://dali.gaohongyu789.top/Article/details/gtjvmjbxaa.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijfyqkay.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gtsragkwtx.html

document.querySelector(".item")
来源：http://dali.chenlongwang.top/Article/details/gtjbzetjjj.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtkjedpmyd.html

el.classList.toggle("active")
来源：http://dali.cqqwz.cn/Article/details/gtcmscaged.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gtdvxtnupj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tian-w.cn/Article/details/gtcnfubezu.html

[U103] JS：定时器
来源：http://dali.tianlin.xyz/Article/details/gtcmadovkm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gttbjqrexq.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gtvlpwgfyw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cdnleiting.top/Article/details/gtszrhaach.html

[U105] JS：节流
来源：http://dali.svipenyu.cn/Article/details/gtdfvyyehp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yanxiufei.cn/Article/details/gtycylbahm.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtjneamkdp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.vqdsnc.cn/Article/details/gtxjwoznuj.html

[U107] JS：数字千分位
来源：http://dali.yueranfly.top/Article/details/gtqgujuruc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hammf.cn/Article/details/gtrpmpzcjh.html

[U108] JS：随机整数
来源：http://dali.chenzaomai.com/Article/details/gtxfuctofo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gtcihcebbp.html

[U109] JS：数组分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gthavqzvxp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gtnawzqimt.html

[U110] JS：数组分块
来源：http://dali.hongshengwenyu.top/Article/details/gthsnvherb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guowangkeji.top/Article/details/gtisputwpu.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtewdtiwuf.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gthzlakato.html

[U112] JS：字符串补位
来源：http://dali.dianchejie.cn/Article/details/gtpvxhzjtc.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtypkjfluu.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtkqxuwwll.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gthsbxrtmt.html

[U114] JS：JSON 深比较
来源：http://dali.0kj1m.cn/Article/details/gtvyodkbjr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtptstugfy.html

[U115] JS：生成 UUID
来源：http://dali.feifeiyinyue.top/Article/details/gthjfimyrq.html

crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtkixpumnx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.pycfn.com/Article/details/gtjfiqbziw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.vqdsnc.cn/Article/details/gtcjrgkcvv.html

[U117] JS：单元测试
来源：http://dali.ybcxt.top/Article/details/gtuoljagnl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhongyouzk.top/Article/details/gtxvnzexaq.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtdjokjsrl.html

npm i -D vite;  npx vite
来源：http://dali.andypj.xyz/Article/details/gtpjhnnnht.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtmnbblfct.html

npx vite build
来源：http://dali.chenjidiqi.icu/Article/details/gteanmopwm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhengqikj.top/Article/details/gttwcocvnr.html

import.meta.env.VITE_API_URL
来源：http://dali.zycfv.cn/Article/details/gtiytlkirt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtnxbdxgnk.html

统计汇总
来源：http://dali.yj20258.top/Article/details/gtsqjyjdhz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmvpatxhh.html

按语言统计（条）：
来源：http://dali.yj202588.top/Article/details/gteaijvyis.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtkemffnku.html

PHP ............ 252
来源：http://dali.yj202588.top/Article/details/gtzrcecrxy.html

JavaScript ..... 252
来源：http://dali.zdqjudy.top/Article/details/gttwdzrvdf.html

TypeScript ..... 212
来源：http://dali.daria6918.cn/Article/details/gtjfykywbv.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gticbkdzux.html

Go ............. 212
来源：http://dali.cucudq.cn/Article/details/gtyxjqvtgj.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtvwhavjqx.html

C# ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gtepcvcsqg.html

C .............. 30
来源：http://dali.ppjwa.cn/Article/details/gtowfhnnqc.html

C++ ............ 30
来源：http://dali.yuanzhike.top/Article/details/gttocnshwj.html

SQL ............ 90
来源：http://dali.yangfankeji.com/Article/details/gtncgwgkwi.html

Bash ........... 80
来源：http://dali.shanyushiyangtech.top/Article/details/gthljdwyhi.html

Kotlin ......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugsdjqrn.html

Swift .......... 15
来源：http://dali.gogol.net.cn/Article/details/gtjwmaomzh.html

Lua ............ 10
来源：http://dali.feifeiyinyue.top/Article/details/gtbdpzstii.html

Perl ........... 10
来源：http://dali.ydzc1.top/Article/details/gtothfesis.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gtllnsmxum.html

------------------------------------
来源：http://dali.wangshuangyany.cn/Article/details/gtnvapshzl.html

合计 ........... 2106 条
来源：http://dali.daxiang520.top/Article/details/gtykxewszx.html

按章节统计：
来源：http://dali.cheryme.top/Article/details/gtdcpadggo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtbqabgyle.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtofherwjv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gttgigkhvz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangshuangyany.cn/Article/details/gthmkhmzje.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfijsrhf.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ivvv.top/Article/details/gtfzgsdkza.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtvfmjxrtr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gotoacloud.top/Article/details/gtedoojvpj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtfltkgjdt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yongpay.top/Article/details/gtvpasidta.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtzcenhrsd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtlabkckoo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gtzbddyqul.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtpraeebxd.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yueranfly.top/Article/details/gtymyutfau.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtlpsgnari.html

Q SQL 专题                              90
来源：http://dali.jinghuilouyu.cn/Article/details/gtliqijvqk.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gtsrasbqis.html

S C / C++ 专题                          60
来源：http://dali.sufxvd.cn/Article/details/gtlpftceqh.html

T 其他语言补充                          60
来源：http://dali.aibaodan.cn/Article/details/gtskgaofzn.html

U 高频实用片段                         120
来源：http://dali.wangdashe.top/Article/details/gtnwyxqgrh.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtjchjjbip.html

合计                                  2106 条
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjlmrnwi.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtzienqtxb.html

使用提醒
来源：http://dali.pengpengdd.cyou/Article/details/gtjrkswrxl.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gtbspxvatv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.nwbrower.top/Article/details/gtefyorfbh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.nanxinkj.top/Article/details/gtnloosacd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.fengsongda.top/Article/details/gtowovphdx.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ybcxt.top/Article/details/gtfjhloiep.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sweek.top/Article/details/gthzkkukkr.html

—— 文件结束 ——
来源：http://dali.quarkkingdee.top/Article/details/gtvolzfpah.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtujertpml.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.hammf.cn/Article/details/gtqcjqgmpr.html

Common Programming Examples Cheat Book
来源：http://dali.cashguo.top/Article/details/gtynhreimt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmysnghu.html

【收录内容】
来源：http://dali.svipenyu.cn/Article/details/gtybvyhahn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.sysykeji.top/Article/details/gtvmirtdbd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtyzzilnue.html

SQL · Bash · C · C++
来源：http://dali.bjfxy.top/Article/details/gtlklddxmq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigufen.top/Article/details/gtmwgbtypc.html

【使用说明】
来源：http://dali.hnqzz.top/Article/details/gtpmolfwqt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.nanxuanxn.top/Article/details/gtctkcnmid.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtbrlbwyhk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahangvcm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhoulong.xyz/Article/details/gtvbnasqkh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sweek.top/Article/details/gttpmdszzi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ppjwa.cn/Article/details/gtrobcmsiw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.hfpthk.cn/Article/details/gtijegitxp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.shzxlz.cn/Article/details/gtsxgftjha.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gthrxmbzof.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqkrvptq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.gogol.net.cn/Article/details/gtfszeiodd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zdqjudy.top/Article/details/gtmqtofbzg.html

【文件统计】
来源：http://dali.gotoacloud.top/Article/details/gtggbgtkzt.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.guannengcc.top/Article/details/gtmvzqifzw.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtywyautcr.html

目  录
来源：http://dali.mhx1999.top/Article/details/gtcwggmefh.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjemkksud.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yanxiufei.cn/Article/details/gtwqddkibd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtcfujyznv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.ehwqpu.com/Article/details/gtqndqocud.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.0kj1m.cn/Article/details/gtjojvencw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yueranfly.top/Article/details/gtkplqbvdb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtcquymtal.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtlnuiuzir.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtknzejywu.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtwngftanw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxnxhrpe.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlczjbnvi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zdqjudy.top/Article/details/gtjwjsujby.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.daxiang520.top/Article/details/gtdamksofz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gtjzncedoy.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sweek.top/Article/details/gtpptpxcfm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gtsjwpgcvj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthuyuihhv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtzydrvdhs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sufxvd.cn/Article/details/gtvpnvnbln.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtzjwcwofx.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthhjahwki.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthegvhkld.html

A. 基础语法与类型
来源：http://dali.jyoumei.cn/Article/details/gtlazsktkh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtcirtyrrx.html

[A01] Hello World
来源：http://dali.xylfe.cn/Article/details/gteiylsgfh.html

Py:   print("Hello, World!")
来源：http://dali.yueranfly.top/Article/details/gthhnltpsf.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpncryyy.html

JS:   console.log("Hello, World!");
来源：http://dali.xuetiantiany.cn/Article/details/gthicaeley.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.sysykeji.top/Article/details/gtdavmqkup.html

Java: System.out.println("Hello, World!");
来源：http://dali.fzhhl.top/Article/details/gtyfbzwgem.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hongshengwenyu.top/Article/details/gtzqsbkbeg.html

Ruby: puts "Hello, World!"
来源：http://dali.smart0.xyz/Article/details/gtsdmqhacr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgufenzy.top/Article/details/gtopqhompd.html

[A02] 变量声明与赋值
来源：http://dali.jinqigfzy.top/Article/details/gtdpiqlype.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gotoacloud.top/Article/details/gtnsciaqsy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.dianchejie.cn/Article/details/gtuatsfvil.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.jianghu66.top/Article/details/gtviqimkns.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.ybcxt.top/Article/details/gtylojwbul.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.xuanzx.com/Article/details/gtwqwifyus.html

Go:   name := "Alex"; age := 20
来源：http://dali.sxryk.cn/Article/details/gtgqpqqgqb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hammf.cn/Article/details/gtxdokvszx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gtlkenalaz.html

[A03] 常量定义
来源：http://dali.ehwqpu.com/Article/details/gtsfgxglab.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbunhxaq.html

PHP:  const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtsknhudou.html

JS:   const PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtmlvtdgeu.html

TS:   const PI: number = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtobqrpoic.html

Java: static final double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtdiejpffw.html

Go:   const PI = 3.14159
来源：http://dali.yueranfly.top/Article/details/gtjqkyiqrj.html

Ruby: PI = 3.14159
来源：http://dali.feifeiyinyue.top/Article/details/gtykegtuho.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtcjblpqlc.html

[A04] 判断变量类型
来源：http://dali.sufxvd.cn/Article/details/gtshoncjsy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhiwuduotai.top/Article/details/gtbhpfhksb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gaohongyu789.top/Article/details/gtzvmkgslz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.xinyue.icu/Article/details/gtckptuiqi.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtlcdfnqtu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj202588.top/Article/details/gtrcksaigs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jlsjyb.cn/Article/details/gtssvtrybr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.xylfe.cn/Article/details/gtzpnikedu.html

C#:   x.GetType().Name; x is int
来源：http://dali.hysaishi.cn/Article/details/gteuthvonh.html

[A05] 整数除法与取模
来源：http://dali.guowangkeji.top/Article/details/gtipletsji.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtulsfemfv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jyoumei.cn/Article/details/gtlsldpurq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzkwptga.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gtmjwxlsqy.html

Java: 7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gtuxcblkly.html

Go:   7 / 2; 7 % 2
来源：http://dali.jlsjyb.cn/Article/details/gtsvasoeal.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yangfankeji.com/Article/details/gttludgxok.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhoulong.xyz/Article/details/gtiwtbnzzt.html

[A06] 字符串转数字
来源：http://dali.ivvv.top/Article/details/gtmxgfjtry.html

Py:   int("42"); float("3.14")
来源：http://dali.shuidangran.top/Article/details/gtoldcuavx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhengqikj.top/Article/details/gtavqrfqkm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtpsrbfdvn.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtkaqbxivh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yvedp.cn/Article/details/gtpilktfow.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.ybcxt.top/Article/details/gtmwwpwetx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.mhx1999.top/Article/details/gtqxewdxyf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.hongshengwenyu.top/Article/details/gtvphahini.html

[A07] 数字转字符串
来源：http://dali.yanxiufei.cn/Article/details/gtomvkizfz.html

Py:   str(42)
来源：http://dali.redwolf501.top/Article/details/gtxafmvimp.html

PHP:  (string) 42; strval(42)
来源：http://dali.nanxinkj.top/Article/details/gtwzuvbxqg.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gtlhpessfw.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gtewxpjjqy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.c1oappe.top/Article/details/gtugxrdzkw.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gtrdsrjcwg.html

Ruby: 42.to_s
来源：http://dali.yuxming.cn/Article/details/gtijxbovhy.html

C#:   42.ToString()
来源：http://dali.zhengqikj.top/Article/details/gtosquqdis.html

[A08] 取整与四舍五入
来源：http://dali.ybcxt.top/Article/details/gttxaipmcv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.redwolf501.top/Article/details/gtjmubkeck.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.tanke756.top/Article/details/gtjwcnblsx.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtvddqkdma.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.meibo888.top/Article/details/gtnfqdbvsb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.316326.xyz/Article/details/gtrymdnvqz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ppjwa.cn/Article/details/gtuzyimesp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gaohongyu789.top/Article/details/gtiduvqcsz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.snrcjt.cn/Article/details/gtvrzmjuqr.html

[A09] 绝对值与最大最小值
来源：http://dali.hnqzz.top/Article/details/gtrzseisdn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtkgodrvhz.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gthakbgrde.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.tanke756.top/Article/details/gtkqipoybm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtaqofsofe.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtdlzikqss.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmfoulee.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.sweek.top/Article/details/gtkpscrnim.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqfktytj.html

[A10] 生成随机数
来源：http://dali.cucudq.cn/Article/details/gttmosbyqm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemkbjdqy.html

PHP:  random_int(1, 100);
来源：http://dali.xziqi.cn/Article/details/gtvjlvvwfv.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.birdmap.top/Article/details/gtbzwuncto.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yuxming.cn/Article/details/gtislrvfpo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xziqi.cn/Article/details/gtrqnmgtsj.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbezcrcmb.html

Ruby: rand(1..100)
来源：http://dali.yuanzhike.top/Article/details/gtcysmcrnr.html

C#:   new Random().Next(1, 101)
来源：http://dali.shangyingyoupin.top/Article/details/gtkaembxti.html

[A11] 条件表达式（三元）
来源：http://dali.guowangkeji.top/Article/details/gtsbpnvoxm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.tian-w.cn/Article/details/gtaqqgozuu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.chenjidiqi.icu/Article/details/gtpdznwhvf.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.dashuyun.cn/Article/details/gtyklfkmao.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.9152youxi.cn/Article/details/gtzpytipvq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtchtmjtoo.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigufen.top/Article/details/gtdpboiemu.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gtcfthblaj.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtxpojxfpy.html

[A12] 字符串插值 / 格式化
来源：http://dali.jqgfzy.top/Article/details/gtzgometbu.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.cheryme.top/Article/details/gtbjtadmfd.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelwmtehz.html

JS:   `Hello, ${name}!`
来源：http://dali.316326.xyz/Article/details/gtxnexvzmm.html

TS:   `Hello, ${name}!`
来源：http://dali.ppjwa.cn/Article/details/gtedpdsblm.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtuhyaagaq.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yj202588.top/Article/details/gtozjquhfr.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspdpnxne.html

C#:   $"Hello, {name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtlcwbpdph.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.gogol.net.cn/Article/details/gtstgbstdf.html

Py:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtabpvsqqj.html

PHP:  "第一行\n第二行"
来源：http://dali.jianghu66.top/Article/details/gtukhzvdbj.html

JS:   "第一行\n第二行"
来源：http://dali.chenzaomai.com/Article/details/gtrglhreym.html

TS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtxzqkyhye.html

Java: "第一行\n第二行"
来源：http://dali.ppjwa.cn/Article/details/gtwvmrpopb.html

Go:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtlpazvkhm.html

Ruby: "第一行\n第二行"
来源：http://dali.zhoulong.xyz/Article/details/gtkrswampx.html

C#:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gturabixyo.html

[A14] 注释写法
来源：http://dali.smart0.xyz/Article/details/gtoxhsmixv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.zhixingplan.top/Article/details/gtrmphcwyn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yanxiufei.cn/Article/details/gtisemstag.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gtkudbkxdr.html


<!-- 参考信息 -->