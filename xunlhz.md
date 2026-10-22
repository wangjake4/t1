代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtkujynmwk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtcckbcstl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gtstmylgms.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.ppjwa.cn/Article/details/gtirihneuj.html

[U85] JS：可选链
来源：http://dali.sxryk.cn/Article/details/gtfbzbxbnm.html

a?.b?.c
来源：http://dali.guowangkeji.top/Article/details/gtfepqliwd.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gtiahulmwr.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gtasgwodmy.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gtghofostn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangshuangyany.cn/Article/details/gtrsqmbhdi.html

[U88] JS：对象展开合并
来源：http://dali.chenjidiqi.icu/Article/details/gteczyenca.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gtjhgjxxtn.html

[U89] JS：数组去重
来源：http://dali.ybcxt.top/Article/details/gtpljmuqrd.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtkbnsuauq.html

[U90] JS：数字数组排序
来源：http://dali.hnxiangtu.top/Article/details/gtnmtknfgr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtwevtdycg.html

[U91] JS：对象键值遍历
来源：http://dali.cucudq.cn/Article/details/gtqlndaoyd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aibaodan.cn/Article/details/gthdnurrfe.html

[U92] JS：深拷贝
来源：http://dali.bjfxy.top/Article/details/gtzozevgby.html

structuredClone(obj)
来源：http://dali.sysykeji.top/Article/details/gtiovxihdm.html

[U93] JS：模板字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtrnrsepxf.html

`共 ${n} 条`
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyahkyjnu.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gthdoeqwfj.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gthtjvbwso.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gtacqcnwgn.html

new Promise((resolve, reject) => {})
来源：http://dali.yueranfly.top/Article/details/gttskevjpi.html

[U96] JS：async/await 与异常
来源：http://dali.xziqi.cn/Article/details/gtxloditwe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.gaohongyu789.top/Article/details/gtexqewwck.html

[U97] JS：并发请求
来源：http://dali.ppjwa.cn/Article/details/gtyzbfaqnm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtohactmeu.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtteqsblzp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtjiorzege.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtylnsmyqu.html

el.addEventListener("click", e => {})
来源：http://dali.zhoulong.xyz/Article/details/gtmwqhxpvq.html

[U100] JS：DOM 查询
来源：http://dali.zhoulong.xyz/Article/details/gtiqxvyatv.html

document.querySelector(".item")
来源：http://dali.jinqigfzy.top/Article/details/gtfasotjlu.html

[U101] JS：classList 操作
来源：http://dali.daxiang520.top/Article/details/gtmaerhamh.html

el.classList.toggle("active")
来源：http://dali.jqgfzy.top/Article/details/gtrwkwfjij.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gtudxrscbc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtczpbvuhg.html

[U103] JS：定时器
来源：http://dali.cucudq.cn/Article/details/gtegvonerc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ydzc1.top/Article/details/gtuztmpyds.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtdwcegasr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtofledxmo.html

[U105] JS：节流
来源：http://dali.yuxming.cn/Article/details/gtvfudubdx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jiagoushi.top/Article/details/gtcffuxtba.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gtpjjrigim.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuetiantiany.cn/Article/details/gteetlpeme.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtxxlrqlzn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gzhubu.top/Article/details/gtxoaspeuu.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtpjyfyjkd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigfzy.top/Article/details/gtkqdnsspa.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gttqzhnokf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtfzdfvtuq.html

[U110] JS：数组分块
来源：http://dali.316326.xyz/Article/details/gtqfeptftj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ivvv.top/Article/details/gtzgzuwlrm.html

[U111] JS：对象转 Map
来源：http://dali.zhixingplan.top/Article/details/gtjsjtgpyl.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gtnjokbxbb.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gtotyemxnk.html

"7".padStart(3, "0")
来源：http://dali.meibo888.top/Article/details/gtazgddlwy.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gtjtfocazd.html

s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtjlzhkjwt.html

[U114] JS：JSON 深比较
来源：http://dali.zhixingplan.top/Article/details/gtzztvneyq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gogol.net.cn/Article/details/gtdbgebtkx.html

[U115] JS：生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtekbiwwfm.html

crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtnblnlvus.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cashguo.top/Article/details/gtuaglisbb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tian-w.cn/Article/details/gtzcnssydk.html

[U117] JS：单元测试
来源：http://dali.zdqjudy.top/Article/details/gtnleufyyt.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gtlxxzipnh.html

[U118] JS：开发服务器
来源：http://dali.ydzc1.top/Article/details/gtwimeqozf.html

npm i -D vite;  npx vite
来源：http://dali.c1oappe.top/Article/details/gtwfjlicln.html

[U119] JS：生产构建
来源：http://dali.jinqigfzy.top/Article/details/gtiuygtajx.html

npx vite build
来源：http://dali.daria6918.cn/Article/details/gtrhkrhexm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtygvpnckz.html

import.meta.env.VITE_API_URL
来源：http://dali.hnqzz.top/Article/details/gtxdnmlvev.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpbzcxgwf.html

统计汇总
来源：http://dali.quarkkingdee.top/Article/details/gtdupmegmm.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbxymmebt.html

按语言统计（条）：
来源：http://dali.hywenlv.cn/Article/details/gtqpkfzndm.html

Python ......... 252
来源：http://dali.ybcxt.top/Article/details/gtciabpirq.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gtznnxhakb.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gttehlbsse.html

TypeScript ..... 212
来源：http://dali.xuanzx.com/Article/details/gtzcbhqfno.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtnaloyvef.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtexcckxqs.html

Ruby ........... 212
来源：http://dali.hammf.cn/Article/details/gtvoamtfva.html

C# ............. 212
来源：http://dali.hywenlv.cn/Article/details/gtpiqvpgfy.html

C .............. 30
来源：http://dali.gogol.net.cn/Article/details/gtgyxhzozk.html

C++ ............ 30
来源：http://dali.redwolf501.top/Article/details/gtcouqgaop.html

SQL ............ 90
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpylmmjny.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gtjyiuiaka.html

Kotlin ......... 15
来源：http://dali.yj20258888.top/Article/details/gtplftiirc.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gtauvfklkn.html

Lua ............ 10
来源：http://dali.jqgfzy.top/Article/details/gtksxkeqrr.html

Perl ........... 10
来源：http://dali.jyoumei.cn/Article/details/gtcrqjhwsp.html

Scala .......... 10
来源：http://dali.sysykeji.top/Article/details/gtdpmftexi.html

------------------------------------
来源：http://dali.ehwqpu.com/Article/details/gtjubqsmqw.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gtaqtpkmix.html

按章节统计：
来源：http://dali.chenlongwang.top/Article/details/gtyfkacweg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sufxvd.cn/Article/details/gtclhiepwl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtfauhdybw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtgtormfsq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtxtobbzct.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.aibaodan.cn/Article/details/gtbwtdbapq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtgkxtwmja.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtmprtcsli.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xylfe.cn/Article/details/gtbtawuyza.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtndtckejx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.c1oappe.top/Article/details/gtsurqirxh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yanxiufei.cn/Article/details/gtewqvcrhl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangdashe.top/Article/details/gtmludiism.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gtwpvbmnta.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jlsjyb.cn/Article/details/gtpzpdolrp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.svipenyu.cn/Article/details/gtpwmjswpr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.quarkkingdee.top/Article/details/gtcrygwsej.html

Q SQL 专题                              90
来源：http://dali.sysykeji.top/Article/details/gtyftybstz.html

R Bash 专题                             80
来源：http://dali.tanke756.top/Article/details/gtbroxidoo.html

S C / C++ 专题                          60
来源：http://dali.zhixingplan.top/Article/details/gthmuvthot.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gtbncwzdav.html

U 高频实用片段                         120
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqwdlpyf.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gthpedokdq.html

合计                                  2106 条
来源：http://dali.yongpay.top/Article/details/gtjvljyvny.html

--------------------------------------------------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtkpxyycgn.html

使用提醒
来源：http://dali.shuidangran.top/Article/details/gtzdgovlnw.html

--------------------------------------------------------------------------------
来源：http://dali.shangyingyoupin.top/Article/details/gtyfwsnzfl.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.sufxvd.cn/Article/details/gtdlynxszw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.meibo888.top/Article/details/gtvuewifqk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jinqigfzy.top/Article/details/gtkpsinwrz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.dashuyun.cn/Article/details/gtinodwddm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daria6918.cn/Article/details/gtatpwcyca.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtxmoocmhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdoseuuux.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.316326.xyz/Article/details/gtlytjajro.html

Common Programming Examples Cheat Book
来源：http://dali.cdnleiting.top/Article/details/gthcbzlpgg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthbljkobq.html

【收录内容】
来源：http://dali.wangshuangyany.cn/Article/details/gtwgqdoima.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daria6918.cn/Article/details/gtuvignzcb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.shuidangran.top/Article/details/gtreeagsft.html

SQL · Bash · C · C++
来源：http://dali.svipenyu.cn/Article/details/gtdjjmfuzw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhongyouzk.top/Article/details/gtkwvuacba.html

【使用说明】
来源：http://dali.ybcxt.top/Article/details/gtmscqezfj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hfpthk.cn/Article/details/gtxdhlggfz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.xuanzx.com/Article/details/gtauapvxjl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.mhx1999.top/Article/details/gtbrihdcdd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhiwuduotai.top/Article/details/gtugbieyur.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.svipenyu.cn/Article/details/gtzxoefpkm.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yj20258.top/Article/details/gtqgcdzxnu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinghuilouyu.cn/Article/details/gtafrkomtw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.hnqzz.top/Article/details/gtpybvsgtb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.jianghu66.top/Article/details/gtwkukhprh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yvedp.cn/Article/details/gtxzocxzve.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuanzx.com/Article/details/gtuzfrkjen.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.daria6918.cn/Article/details/gtwzhzyrbo.html

【文件统计】
来源：http://dali.birdmap.top/Article/details/gtvqdfbnvk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.jqgfzy.top/Article/details/gtfigzfbcl.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtrdhcrrxl.html

目  录
来源：http://dali.jianghu66.top/Article/details/gtzuojkpqf.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtorelkbfq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtkpcecmjj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtrziezkso.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.yuxming.cn/Article/details/gtekmditsl.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtcdzxxdxb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekkjhqtb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gtfadwiptr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gttfpvditj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtshhnwqkv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yonumen.top/Article/details/gtoyqtiwwl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.daxiang520.top/Article/details/gtuazlhesn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtdivsfzad.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.vqdsnc.cn/Article/details/gtweqaufax.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtvabstnsc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.jyoumei.cn/Article/details/gtuzjpepku.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gtcsossgoi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtkfwfsdzg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.meibo888.top/Article/details/gtuedoysni.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fzhhl.top/Article/details/gtvdcrevig.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.xziqi.cn/Article/details/gtnfxsvucx.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtwskneoed.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.tian-w.cn/Article/details/gtzjbukmrk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgrwmraim.html

A. 基础语法与类型
来源：http://dali.cdnleiting.top/Article/details/gtaoopdrtg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gteuqceoiw.html

[A01] Hello World
来源：http://dali.aibaodan.cn/Article/details/gtemdcshdp.html

Py:   print("Hello, World!")
来源：http://dali.sxryk.cn/Article/details/gthxucqcjk.html

PHP:  echo "Hello, World!";
来源：http://dali.nanxuanxn.top/Article/details/gteczsookx.html

JS:   console.log("Hello, World!");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrueheyaz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.iojbl.cn/Article/details/gtcbkmkjux.html

Java: System.out.println("Hello, World!");
来源：http://dali.zdqjudy.top/Article/details/gtfwwaqkzl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yongpay.top/Article/details/gtewekcyre.html

Ruby: puts "Hello, World!"
来源：http://dali.xuetiantiany.cn/Article/details/gtkgqmucno.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.jqgfzy.top/Article/details/gtquotddib.html

[A02] 变量声明与赋值
来源：http://dali.daxiang520.top/Article/details/gtfapwteeq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daria6918.cn/Article/details/gtnvwlhpoo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xziqi.cn/Article/details/gtqujwpxtu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.tianlin.xyz/Article/details/gtghvqhzmv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yuxming.cn/Article/details/gttitucrtj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtmrtdkfsj.html

Go:   name := "Alex"; age := 20
来源：http://dali.aibaodan.cn/Article/details/gtwfbeywla.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sxryk.cn/Article/details/gtlkjvgmuo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.havefunace.top/Article/details/gtvfcsbphp.html

[A03] 常量定义
来源：http://dali.yanxiufei.cn/Article/details/gtuokpflsh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gotoacloud.top/Article/details/gtbisqvbah.html

PHP:  const PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtedlfktfh.html

JS:   const PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkxwgsav.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtkhvexbgv.html

Java: static final double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtzbgzrykn.html

Go:   const PI = 3.14159
来源：http://dali.iojbl.cn/Article/details/gtgegrxwub.html

Ruby: PI = 3.14159
来源：http://dali.mhx1999.top/Article/details/gtzjcfxvuo.html

C#:   const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtykynenpt.html

[A04] 判断变量类型
来源：http://dali.hfpthk.cn/Article/details/gttpmotsea.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yuanzhike.top/Article/details/gtdnxhswbr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jyoumei.cn/Article/details/gtsfoogcgs.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.hysaishi.cn/Article/details/gtcyjericc.html

TS:   typeof x; x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtujefjurg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jinqigufen.top/Article/details/gtcohxacwh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.xuetiantiany.cn/Article/details/gtvlwesexk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jiagoushi.top/Article/details/gtsczmoybt.html

C#:   x.GetType().Name; x is int
来源：http://dali.ehwqpu.com/Article/details/gtmmbhwedh.html

[A05] 整数除法与取模
来源：http://dali.yj20258888.top/Article/details/gtvibpkfbe.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.guannengcc.top/Article/details/gtdeoaumdg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdafpswp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.mhx1999.top/Article/details/gtdlfpfyks.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhongyouzk.top/Article/details/gtgdyslpql.html

Java: 7 / 2; 7 % 2
来源：http://dali.kuanghao11.cn/Article/details/gtgsqpzosa.html

Go:   7 / 2; 7 % 2
来源：http://dali.sufxvd.cn/Article/details/gtjxmcjxpx.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gttxdxpuhs.html

C#:   7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtldphelsn.html

[A06] 字符串转数字
来源：http://dali.tian-w.cn/Article/details/gtbyjbixll.html

Py:   int("42"); float("3.14")
来源：http://dali.redwolf501.top/Article/details/gtwfcjondg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.yuxming.cn/Article/details/gtxvbmzaqc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.pycfn.com/Article/details/gteiovwmdt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtnayzocal.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.jianghu66.top/Article/details/gtmnghtdct.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sxryk.cn/Article/details/gtazypfaxm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.guannengcc.top/Article/details/gtsomyslwv.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtometzzpo.html

[A07] 数字转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtuykgzfuk.html

Py:   str(42)
来源：http://dali.zhengqikj.top/Article/details/gtvvnarrpg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zycfv.cn/Article/details/gtmzlvqzva.html

JS:   String(42); (42).toString()
来源：http://dali.xuanzx.com/Article/details/gtxgjlcbmy.html

TS:   String(42)
来源：http://dali.nwbrower.top/Article/details/gtatffpohp.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hfpthk.cn/Article/details/gtfrkauulz.html

Go:   strconv.Itoa(42)
来源：http://dali.birdmap.top/Article/details/gtlwcwyfki.html

Ruby: 42.to_s
来源：http://dali.tianlin.xyz/Article/details/gtkwigymqh.html

C#:   42.ToString()
来源：http://dali.jyoumei.cn/Article/details/gtzxbbsocu.html

[A08] 取整与四舍五入
来源：http://dali.hywenlv.cn/Article/details/gtzrpyoxka.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shzxlz.cn/Article/details/gtetcwyrli.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.nanxinkj.top/Article/details/gtobyplyhn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.pycfn.com/Article/details/gtgpqeiatg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.guowangkeji.top/Article/details/gtkgesopql.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.wangdashe.top/Article/details/gtlxvvzibq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.kuanghao11.cn/Article/details/gtolvxmwrm.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gtzmjncndm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gttznysftu.html

[A09] 绝对值与最大最小值
来源：http://dali.svipenyu.cn/Article/details/gtmadowbwn.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtabpfietr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtnddttoaw.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtwndnizkm.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtcuugdouk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gteynlbvfn.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sxryk.cn/Article/details/gtclsrrbou.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yj20258.top/Article/details/gtonfkrfmm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtwjylepxf.html

[A10] 生成随机数
来源：http://dali.hfpthk.cn/Article/details/gtfbrzcrsk.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hongshengwenyu.top/Article/details/gtsbtnnaud.html

PHP:  random_int(1, 100);
来源：http://dali.hnxiangtu.top/Article/details/gtqdelkheg.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xylfe.cn/Article/details/gtgrimjzjw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtcuoatxhi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.redwolf501.top/Article/details/gtqvvbkzjo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.hnxiangtu.top/Article/details/gtolwpagpx.html

Ruby: rand(1..100)
来源：http://dali.shangyingyoupin.top/Article/details/gtzwpxqzzz.html

C#:   new Random().Next(1, 101)
来源：http://dali.9152youxi.cn/Article/details/gtzhzifvyl.html

[A11] 条件表达式（三元）
来源：http://dali.zhengqikj.top/Article/details/gttbryjsmd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ppjwa.cn/Article/details/gtuxwdhlee.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.tanke756.top/Article/details/gtnykevdpu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtwkkmjcwj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.gzhubu.top/Article/details/gtkvqtepdl.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtuiataxxm.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.cqqwz.cn/Article/details/gtqcqbhykk.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.shzxlz.cn/Article/details/gtyyrirrrv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtufvgfonz.html

[A12] 字符串插值 / 格式化
来源：http://dali.havefunace.top/Article/details/gtlodmcosq.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hammf.cn/Article/details/gtpbnseszp.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplkdcqjc.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgufenzy.top/Article/details/gtsnbsocew.html

TS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gtmughurdh.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.nanxuanxn.top/Article/details/gthnleeyle.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtqkwiocaw.html

Ruby: "Hello, #{name}!"
来源：http://dali.xuanzx.com/Article/details/gtcjzbniat.html

C#:   $"Hello, {name}!"
来源：http://dali.nanxuanxn.top/Article/details/gtmtoqaaew.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jinqigufen.top/Article/details/gtkiufgddu.html

Py:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtejzmrsmb.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gttsuktrlg.html

JS:   "第一行\n第二行"
来源：http://dali.yuxming.cn/Article/details/gtlsrjhhoc.html

TS:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gtaejahbif.html

Java: "第一行\n第二行"
来源：http://dali.aibaodan.cn/Article/details/gthpfedxji.html

Go:   "第一行\n第二行"
来源：http://dali.snrcjt.cn/Article/details/gtgxuscmdr.html

Ruby: "第一行\n第二行"
来源：http://dali.havefunace.top/Article/details/gtwbnmaknj.html

C#:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtjqrfzydr.html


<!-- 参考信息 -->