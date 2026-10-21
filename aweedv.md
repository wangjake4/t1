代发 wailian999

[U81] JS：初始化项目
来源：http://dali.ybcxt.top/Article/details/gtplzlqqwi.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gtsypryfvn.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gtscrrhsrz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.redwolf501.top/Article/details/gttpeieuux.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gttadoimxv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj202588.top/Article/details/gteflgslsf.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gteygzlqxm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.dianchejie.cn/Article/details/gtxkkbghub.html

[U85] JS：可选链
来源：http://dali.pengpengdd.cyou/Article/details/gtxywsypor.html

a?.b?.c
来源：http://dali.fengsongda.top/Article/details/gtdmtkuifm.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gtymuzuvrj.html

a ?? b
来源：http://dali.sysykeji.top/Article/details/gtphgnfsbu.html

[U87] JS：解构默认值
来源：http://dali.hysaishi.cn/Article/details/gtfyrsbttu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sysykeji.top/Article/details/gtlfxmthmr.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gtidzixyvt.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gtqmcklafi.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gtguvstips.html

[...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtqmovktih.html

[U90] JS：数字数组排序
来源：http://dali.aibaodan.cn/Article/details/gtmqqqdckr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtpyyawitw.html

[U91] JS：对象键值遍历
来源：http://dali.aibaodan.cn/Article/details/gtdhjyrses.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gtmwfesqye.html

[U92] JS：深拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumsxtgzc.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gtwzgkkkyt.html

[U93] JS：模板字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvnagiui.html

`共 ${n} 条`
来源：http://dali.gaohongyu789.top/Article/details/gtfksurklj.html

[U94] JS：箭头函数
来源：http://dali.ehwqpu.com/Article/details/gtqxyaucls.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gtvdhedynt.html

[U95] JS：Promise 包装
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmkjsgis.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gtpsvzhyrw.html

[U96] JS：async/await 与异常
来源：http://dali.xinyue.icu/Article/details/gtygvqbsdo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtipaerdir.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtvgewgmii.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gtlevhehxn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtojrapmuq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhiwuduotai.top/Article/details/gtfgoeeujd.html

[U99] JS：事件监听
来源：http://dali.guannengcc.top/Article/details/gtfyelqiel.html

el.addEventListener("click", e => {})
来源：http://dali.cucudq.cn/Article/details/gtyasdjrce.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gtlirzqltb.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gtljvqeeuh.html

[U101] JS：classList 操作
来源：http://dali.zhiwuduotai.top/Article/details/gtqfwowxzv.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gttdvrnfmq.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gtuyafkrmx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zycfv.cn/Article/details/gtpddhlagk.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gtockjtrwy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gtmjijzpev.html

[U104] JS：防抖
来源：http://dali.nanxinkj.top/Article/details/gtdahyxyqq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtpandrkbx.html

[U105] JS：节流
来源：http://dali.kuanghao11.cn/Article/details/gtpodeyyih.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.fzhhl.top/Article/details/gtaztgkdgg.html

[U106] JS：日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtwhpeycqp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xziqi.cn/Article/details/gteimedglg.html

[U107] JS：数字千分位
来源：http://dali.jiagoushi.top/Article/details/gtozfzasjd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gtujksrlbx.html

[U108] JS：随机整数
来源：http://dali.snrcjt.cn/Article/details/gtntpatstl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yongpay.top/Article/details/gtholzaxxu.html

[U109] JS：数组分组
来源：http://dali.jqgfzy.top/Article/details/gtyopligtz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenjidiqi.icu/Article/details/gtgbgwnres.html

[U110] JS：数组分块
来源：http://dali.aibaodan.cn/Article/details/gtllupfaiv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yonumen.top/Article/details/gtvqnlukla.html

[U111] JS：对象转 Map
来源：http://dali.fzhhl.top/Article/details/gtwterxnal.html

new Map(Object.entries(obj))
来源：http://dali.chenlongwang.top/Article/details/gtxqjduxhi.html

[U112] JS：字符串补位
来源：http://dali.yueranfly.top/Article/details/gtlagphlhl.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtomxkipyi.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gttrldqftm.html

s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gttqzhhbey.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtyzrnmsnl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gteqsopcnx.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gtnqlmsnui.html

crypto.randomUUID()
来源：http://dali.havefunace.top/Article/details/gtrjseivnr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdeqptmv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtbofqipbn.html

[U117] JS：单元测试
来源：http://dali.mhx1999.top/Article/details/gtipfvztbp.html

npm i -D vitest;  npx vitest
来源：http://dali.hnqzz.top/Article/details/gtylqyvrlg.html

[U118] JS：开发服务器
来源：http://dali.snrcjt.cn/Article/details/gtfhwjsxrp.html

npm i -D vite;  npx vite
来源：http://dali.hnxiangtu.top/Article/details/gteyxyspxh.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtcvrbbjzi.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gtftnvkedp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.daxiang520.top/Article/details/gtezwesict.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gttqjndqhz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyruaetyw.html

统计汇总
来源：http://dali.xziqi.cn/Article/details/gtmduhmgbt.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgztjalmg.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtbtooewhi.html

Python ......... 252
来源：http://dali.iojbl.cn/Article/details/gttmltcuxt.html

PHP ............ 252
来源：http://dali.yj20258.top/Article/details/gtuwzdtfna.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtbchxfueb.html

TypeScript ..... 212
来源：http://dali.yonumen.top/Article/details/gtogdxffrs.html

Java ........... 212
来源：http://dali.yj20258.top/Article/details/gtfhvvyeww.html

Go ............. 212
来源：http://dali.jiagoushi.top/Article/details/gtbyjrruzr.html

Ruby ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazddpoke.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtnejwxhah.html

C .............. 30
来源：http://dali.9152youxi.cn/Article/details/gtvcsnpiuu.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtxfpccbsf.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gtwpkbsmmc.html

Bash ........... 80
来源：http://dali.yonumen.top/Article/details/gtfhowrgbe.html

Kotlin ......... 15
来源：http://dali.nanxinkj.top/Article/details/gtoejzyoaz.html

Swift .......... 15
来源：http://dali.jinqigufen.top/Article/details/gttyrbtzxx.html

Lua ............ 10
来源：http://dali.hnxiangtu.top/Article/details/gtaxkhiluk.html

Perl ........... 10
来源：http://dali.chenjidiqi.icu/Article/details/gtnilwxkir.html

Scala .......... 10
来源：http://dali.hnxiangtu.top/Article/details/gtdaepwnbb.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtulbjihvh.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gtgxkyekkb.html

按章节统计：
来源：http://dali.guowangkeji.top/Article/details/gtqiaovscb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cucudq.cn/Article/details/gtmeutgytp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtdnamxmvz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtehjcqfde.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtjgixkpfj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cashguo.top/Article/details/gtvbeidyva.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtydzkqank.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pengpengdd.cyou/Article/details/gtwnruoxym.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ybcxt.top/Article/details/gtpxupchxh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.chenzaomai.com/Article/details/gtvncsghiw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.iojbl.cn/Article/details/gtdulzyaty.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gtvikflsfh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtgwtwpejw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gtcpnmzlww.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tianlin.xyz/Article/details/gtissrockt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnssbdjyx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gtkmcqslnx.html

Q SQL 专题                              90
来源：http://dali.0kj1m.cn/Article/details/gtdsmfceir.html

R Bash 专题                             80
来源：http://dali.yj202588.top/Article/details/gtjmbspqck.html

S C / C++ 专题                          60
来源：http://dali.jiagoushi.top/Article/details/gtpcwjukum.html

T 其他语言补充                          60
来源：http://dali.nwbrower.top/Article/details/gtzttxwbqb.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gtvnjlwjls.html

------------------------------------
来源：http://dali.feifeiyinyue.top/Article/details/gtqnpeyypp.html

合计                                  2106 条
来源：http://dali.redwolf501.top/Article/details/gtlhnuagsc.html

--------------------------------------------------------------------------------
来源：http://dali.hnxiangtu.top/Article/details/gtgahiulit.html

使用提醒
来源：http://dali.ppjwa.cn/Article/details/gtivuzteqb.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtzzhmdjle.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtrhdwyscr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.haohaochexian.top/Article/details/gttdgvczzp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gtonsllsme.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.nanxinkj.top/Article/details/gtdchpzkth.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.feifeiyinyue.top/Article/details/gtsupvnwvj.html

—— 文件结束 ——
来源：http://dali.andypj.xyz/Article/details/gtcmcukvdk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtruurdann.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.redwolf501.top/Article/details/gttcjuiwsu.html

Common Programming Examples Cheat Book
来源：http://dali.fengsongda.top/Article/details/gtzuoyfojq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtbeiidavd.html

【收录内容】
来源：http://dali.zhongyouzk.top/Article/details/gtpsyztkat.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.daxiang520.top/Article/details/gtcxiewuau.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.daxiang520.top/Article/details/gtbxugvdel.html

SQL · Bash · C · C++
来源：http://dali.dianchejie.cn/Article/details/gteihcougp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yongpay.top/Article/details/gttnwnhhgv.html

【使用说明】
来源：http://dali.cqqwz.cn/Article/details/gtqothmlns.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.fzhhl.top/Article/details/gthjvynunw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.cucudq.cn/Article/details/gtsiuzgjma.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.cucudq.cn/Article/details/gtavwsllrp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.cqqwz.cn/Article/details/gtpoqpykdj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.shzxlz.cn/Article/details/gttcwiejle.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shangyingyoupin.top/Article/details/gtbzdruxpe.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.xylfe.cn/Article/details/gtvxmslzhk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.smart0.xyz/Article/details/gtqoijkevx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.quarkkingdee.top/Article/details/gtucolksmu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.smart0.xyz/Article/details/gttffdlhvg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.nwbrower.top/Article/details/gtkujksmxg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.9152youxi.cn/Article/details/gtopgbhjvr.html

【文件统计】
来源：http://dali.zycfv.cn/Article/details/gtdxalcxti.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.feifeiyinyue.top/Article/details/gtlgipeiey.html

--------------------------------------------------------------------------------
来源：http://dali.cucudq.cn/Article/details/gtkhzvpcxa.html

目  录
来源：http://dali.jqgfzy.top/Article/details/gthdfwrmac.html

--------------------------------------------------------------------------------
来源：http://dali.jqgufenzy.top/Article/details/gtptdcfqld.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.xinyue.icu/Article/details/gtdgwmpadc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.yuanzhike.top/Article/details/gtjkxshibr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.cheryme.top/Article/details/gtylvzzaek.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.pycfn.com/Article/details/gtsntpgups.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhoulong.xyz/Article/details/gtfpqfmmxv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.ydzc1.top/Article/details/gtrqbhxwgo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtdgerukqt.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.wangdashe.top/Article/details/gtvcqkmuuh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.chenlongwang.top/Article/details/gtjbqyqmrp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.aibaodan.cn/Article/details/gtvfusupdu.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtzrysitmj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yj20258.top/Article/details/gtxsocihsz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtzdvqmpbz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.andypj.xyz/Article/details/gtxzdgqmqx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.gogol.net.cn/Article/details/gtffkjvign.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtaamivxpf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhixingplan.top/Article/details/gtnmatqqdt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtuhbjjaam.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.quarkkingdee.top/Article/details/gtcmlpxdnu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtejkjcrjh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtvjicbuzu.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwsaedcqe.html

A. 基础语法与类型
来源：http://dali.tianlin.xyz/Article/details/gtjmcxqzbq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtipjupung.html

[A01] Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtieftggqr.html

Py:   print("Hello, World!")
来源：http://dali.jiagoushi.top/Article/details/gtkhtlgvqn.html

PHP:  echo "Hello, World!";
来源：http://dali.daria6918.cn/Article/details/gtcaerbuoq.html

JS:   console.log("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtlrskzsmb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jqgufenzy.top/Article/details/gtudliwbpy.html

Java: System.out.println("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtunmlqpzw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.yvedp.cn/Article/details/gtoobomelj.html

Ruby: puts "Hello, World!"
来源：http://dali.haohaochexian.top/Article/details/gthkywpdcw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtphzazukn.html

[A02] 变量声明与赋值
来源：http://dali.tanke756.top/Article/details/gtztspabtj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jinghuilouyu.cn/Article/details/gthlqmdcgo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gtlaeorpfa.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.316326.xyz/Article/details/gtansqlris.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.meibo888.top/Article/details/gtsqpxgzno.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.haohaochexian.top/Article/details/gtpnefbkyn.html

Go:   name := "Alex"; age := 20
来源：http://dali.nanxinkj.top/Article/details/gtyjufeidg.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhongyouzk.top/Article/details/gtmyrqorfm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.dashuyun.cn/Article/details/gtiaoafpqa.html

[A03] 常量定义
来源：http://dali.zhixingplan.top/Article/details/gtrjasggdb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.yonumen.top/Article/details/gtepelloiy.html

PHP:  const PI = 3.14159;
来源：http://dali.cheryme.top/Article/details/gtmekfkqkr.html

JS:   const PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtwtvkwjgp.html

TS:   const PI: number = 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gtydodrbzb.html

Java: static final double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtchbwvpxi.html

Go:   const PI = 3.14159
来源：http://dali.gzhubu.top/Article/details/gtbzjilbse.html

Ruby: PI = 3.14159
来源：http://dali.andypj.xyz/Article/details/gtzptdkhhi.html

C#:   const double PI = 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtblbnwenx.html

[A04] 判断变量类型
来源：http://dali.hysaishi.cn/Article/details/gtivrteazy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.shuidangran.top/Article/details/gtjfunubfq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.dashuyun.cn/Article/details/gtvvcepdpw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yuanzhike.top/Article/details/gtchggunqi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhixingplan.top/Article/details/gtvconvjcl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.tanke756.top/Article/details/gtptlgbvvv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dianchejie.cn/Article/details/gtvuztidjr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jqgfzy.top/Article/details/gthgamwjuc.html

C#:   x.GetType().Name; x is int
来源：http://dali.iojbl.cn/Article/details/gtsgoaonku.html

[A05] 整数除法与取模
来源：http://dali.havefunace.top/Article/details/gtlidgytuk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.haohaochexian.top/Article/details/gtdamjntnc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtuqnxnlby.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xuanzx.com/Article/details/gtuvvnskdb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jqgfzy.top/Article/details/gtjnxofcfq.html

Java: 7 / 2; 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtyoxrezpm.html

Go:   7 / 2; 7 % 2
来源：http://dali.iojbl.cn/Article/details/gtogvcalgm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.aizwys.cn/Article/details/gtozqzxlyq.html

C#:   7 / 2; 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtjpbnnjfv.html

[A06] 字符串转数字
来源：http://dali.quarkkingdee.top/Article/details/gtibtmqcoo.html

Py:   int("42"); float("3.14")
来源：http://dali.jinqigfzy.top/Article/details/gtsmojxwmi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gthklqvjov.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gthfujruvd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.gogol.net.cn/Article/details/gtmguiadgb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangshuangyany.cn/Article/details/gtfwhlmtyq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.nanxuanxn.top/Article/details/gtoygzlmxm.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.xinyue.icu/Article/details/gthifkchxm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.aizwys.cn/Article/details/gthmduceyd.html

[A07] 数字转字符串
来源：http://dali.daxiang520.top/Article/details/gtdxkermvd.html

Py:   str(42)
来源：http://dali.tanke756.top/Article/details/gtkcntcuvh.html

PHP:  (string) 42; strval(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbdoolli.html

JS:   String(42); (42).toString()
来源：http://dali.9152youxi.cn/Article/details/gtfmgoopoi.html

TS:   String(42)
来源：http://dali.guannengcc.top/Article/details/gtnbbiaspu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.hnxiangtu.top/Article/details/gtpvizwimt.html

Go:   strconv.Itoa(42)
来源：http://dali.hfpthk.cn/Article/details/gtbujqsdfi.html

Ruby: 42.to_s
来源：http://dali.c1oappe.top/Article/details/gtzcqkcidk.html

C#:   42.ToString()
来源：http://dali.birdmap.top/Article/details/gtfvblvind.html

[A08] 取整与四舍五入
来源：http://dali.meibo888.top/Article/details/gtvjhmimhg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtilqyiruo.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.birdmap.top/Article/details/gtoefwiurs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtpyookpfx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gzhubu.top/Article/details/gtzlnkezkp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jqgfzy.top/Article/details/gtzlpxurde.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gtpvnxqonp.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gthxpvcdqm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hywenlv.cn/Article/details/gtvqxlwune.html

[A09] 绝对值与最大最小值
来源：http://dali.sxryk.cn/Article/details/gtccwupjni.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtrmwfkwwh.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtoudpnfbt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtokybrgri.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtltphujqb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yvedp.cn/Article/details/gtjbislggd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.iojbl.cn/Article/details/gtykilfruo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.svipenyu.cn/Article/details/gthkessehv.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtlhrclymm.html

[A10] 生成随机数
来源：http://dali.smart0.xyz/Article/details/gtccekndxs.html

Py:   import random; random.randint(1, 100)
来源：http://dali.shzxlz.cn/Article/details/gtiialrqqg.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gtxdclgmzp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtxscwtdqq.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.cdnleiting.top/Article/details/gtltneluvq.html

Java: new Random().nextInt(100) + 1
来源：http://dali.feifeiyinyue.top/Article/details/gthfptmxke.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.316326.xyz/Article/details/gtauhbhmie.html

Ruby: rand(1..100)
来源：http://dali.nanxuanxn.top/Article/details/gtnwrrufgy.html

C#:   new Random().Next(1, 101)
来源：http://dali.jyoumei.cn/Article/details/gtidvttmlx.html

[A11] 条件表达式（三元）
来源：http://dali.xuanzx.com/Article/details/gtnbkpbtar.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gtkvapjpqh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.meibo888.top/Article/details/gtejlximdk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtszinfkcl.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zycfv.cn/Article/details/gtdjchorac.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.sufxvd.cn/Article/details/gtouhhdlny.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhoulong.xyz/Article/details/gtdiovxfhw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.redwolf501.top/Article/details/gtiusvpkud.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.kuanghao11.cn/Article/details/gtvqbqgyzx.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfpegegn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtidzywuyc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.yuanzhike.top/Article/details/gtbmftxoil.html

JS:   `Hello, ${name}!`
来源：http://dali.jqgfzy.top/Article/details/gtjqocdfja.html

TS:   `Hello, ${name}!`
来源：http://dali.dashuyun.cn/Article/details/gtcdxqnuww.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.sufxvd.cn/Article/details/gtfjdsftau.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.aibaodan.cn/Article/details/gtrglrdumh.html

Ruby: "Hello, #{name}!"
来源：http://dali.yvedp.cn/Article/details/gtuoolxloq.html

C#:   $"Hello, {name}!"
来源：http://dali.snrcjt.cn/Article/details/gtxiynxtzm.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gtockkduol.html

Py:   "第一行\n第二行"
来源：http://dali.zhiwuduotai.top/Article/details/gtdxctsssw.html

PHP:  "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtzxhclpcf.html

JS:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gttcpidoty.html

TS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtjjhplnrq.html


<!-- 参考信息 -->