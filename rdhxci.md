代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtachfkrvc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtcgkblccp.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gtsphcruvs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhoulong.xyz/Article/details/gtlwvtwfml.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gtesaygfie.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gtsnwcbqak.html

[U86] JS：空值合并
来源：http://dali.birdmap.top/Article/details/gtljquywuy.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtxlienvao.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpbmxvzd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtehqbocex.html

[U88] JS：对象展开合并
来源：http://dali.gzhubu.top/Article/details/gtjbfohmps.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gtkpafnlwr.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtedghrpgc.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gteuctkqoh.html

[U90] JS：数字数组排序
来源：http://dali.daria6918.cn/Article/details/gtzhlspxcr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtelhceufh.html

[U91] JS：对象键值遍历
来源：http://dali.tianlin.xyz/Article/details/gtkrnvljkb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhdybkco.html

[U92] JS：深拷贝
来源：http://dali.cheryme.top/Article/details/gtglarevcj.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtomnhstiq.html

[U93] JS：模板字符串
来源：http://dali.hammf.cn/Article/details/gtaptbzqas.html

`共 ${n} 条`
来源：http://dali.shuidangran.top/Article/details/gtsvlvflwl.html

[U94] JS：箭头函数
来源：http://dali.jqgufenzy.top/Article/details/gtbzfivlmb.html

const double = x => x * 2;
来源：http://dali.mhx1999.top/Article/details/gtbmjgkdjh.html

[U95] JS：Promise 包装
来源：http://dali.yueranfly.top/Article/details/gtwfgkeqzr.html

new Promise((resolve, reject) => {})
来源：http://dali.cashguo.top/Article/details/gttwenqdaw.html

[U96] JS：async/await 与异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvfnflrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gtrgbiuimg.html

[U97] JS：并发请求
来源：http://dali.havefunace.top/Article/details/gtzhsswvdp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtukwqokkd.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gthkmcstwy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.fengsongda.top/Article/details/gtgzsopbcc.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtxfwqjfnd.html

el.addEventListener("click", e => {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtszbxpevb.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gtqiqjpdbb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gtlwdxzute.html

[U101] JS：classList 操作
来源：http://dali.yongpay.top/Article/details/gtlpgoeila.html

el.classList.toggle("active")
来源：http://dali.yj202588.top/Article/details/gtxutcgsfc.html

[U102] JS：本地存储
来源：http://dali.yongpay.top/Article/details/gtcddcnfvo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ydzc1.top/Article/details/gthepaeslj.html

[U103] JS：定时器
来源：http://dali.guowangkeji.top/Article/details/gtsnopnlmb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.guannengcc.top/Article/details/gtkrnmbxxh.html

[U104] JS：防抖
来源：http://dali.meibo888.top/Article/details/gtnuwiwqxo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuxming.cn/Article/details/gtwortjrfd.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtewdmbnrx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gtfqcdmmfj.html

[U106] JS：日期格式化
来源：http://dali.xylfe.cn/Article/details/gtmaewnytp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.quarkkingdee.top/Article/details/gturjssout.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gtkjhybeto.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtrpcxiwil.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdrkzazt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nwbrower.top/Article/details/gtpsgokkct.html

[U109] JS：数组分组
来源：http://dali.gotoacloud.top/Article/details/gtfxfekqkk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyhfowic.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtyywoiirk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gtdzkvasxw.html

[U111] JS：对象转 Map
来源：http://dali.chenjidiqi.icu/Article/details/gtcybqbigd.html

new Map(Object.entries(obj))
来源：http://dali.yuxming.cn/Article/details/gtrfyarudz.html

[U112] JS：字符串补位
来源：http://dali.9152youxi.cn/Article/details/gtvzftsfss.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtmltzocwd.html

[U113] JS：正则替换全部
来源：http://dali.jiagoushi.top/Article/details/gtlobqxywu.html

s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtmllxglil.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtmyjnrlny.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.bjfxy.top/Article/details/gtcjjgkgoq.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtjmupgesu.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtzxnjjese.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gtyizncfkz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gtntpopoyd.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtepmkodtv.html

npm i -D vitest;  npx vitest
来源：http://dali.yj20258888.top/Article/details/gtqgdavmdw.html

[U118] JS：开发服务器
来源：http://dali.shangyingyoupin.top/Article/details/gtqyemtnfm.html

npm i -D vite;  npx vite
来源：http://dali.ybcxt.top/Article/details/gtflrbsfaj.html

[U119] JS：生产构建
来源：http://dali.shangyingyoupin.top/Article/details/gtidxalvkc.html

npx vite build
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoupxqcr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yongpay.top/Article/details/gtrfbvpjkq.html

import.meta.env.VITE_API_URL
来源：http://dali.hnxiangtu.top/Article/details/gtibuzvjol.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlbpaqnrd.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtqcdlmueu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgjgzgnss.html

按语言统计（条）：
来源：http://dali.cqqwz.cn/Article/details/gtxumfpvbd.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtutndkipc.html

PHP ............ 252
来源：http://dali.shzxlz.cn/Article/details/gtvuueyzew.html

JavaScript ..... 252
来源：http://dali.daria6918.cn/Article/details/gtxxxyvgav.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtfoudhugj.html

Java ........... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioscrdhb.html

Go ............. 212
来源：http://dali.yanxiufei.cn/Article/details/gtnyskpfwe.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtpafmymmp.html

C# ............. 212
来源：http://dali.hnqzz.top/Article/details/gtqwlekhjs.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gtyijajxyt.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtggebxcdh.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtyrqgjsfz.html

Bash ........... 80
来源：http://dali.nwbrower.top/Article/details/gtdvqowemr.html

Kotlin ......... 15
来源：http://dali.dianchejie.cn/Article/details/gtxluqewyy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gtsjgdiaea.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gtcyhwdklf.html

Perl ........... 10
来源：http://dali.redwolf501.top/Article/details/gtmvdiuliw.html

Scala .......... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtxlxsvomy.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtntihiksq.html

合计 ........... 2106 条
来源：http://dali.hfpthk.cn/Article/details/gtvpoiflyt.html

按章节统计：
来源：http://dali.hywenlv.cn/Article/details/gtorxaevgx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzftneki.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtxdhqirbh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.0kj1m.cn/Article/details/gtmkiusvoh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jianghu66.top/Article/details/gtlkiyzrag.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtjhysfssd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gthyyzvwjp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gtgwnvdcvs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gtyqvntvra.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zdqjudy.top/Article/details/gtsrphbtrw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinqigfzy.top/Article/details/gtqvccbipx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtnyftlheu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtisqmabwm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtoqezgpso.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shzxlz.cn/Article/details/gtskiczhtc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtzhmcavkx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtwqtbqqwk.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gtxdzgxhau.html

R Bash 专题                             80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxycbdvy.html

S C / C++ 专题                          60
来源：http://dali.zhengqikj.top/Article/details/gttcdghsmz.html

T 其他语言补充                          60
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtgtpkmk.html

U 高频实用片段                         120
来源：http://dali.hnqzz.top/Article/details/gtdmgdlrzp.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtxhlnjoog.html

合计                                  2106 条
来源：http://dali.gotoacloud.top/Article/details/gtjcctqecu.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcxxqhnc.html

使用提醒
来源：http://dali.wangdashe.top/Article/details/gthnoahixz.html

--------------------------------------------------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gtdvehdoww.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.wangdashe.top/Article/details/gtgvxmaacp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.gaohongyu789.top/Article/details/gtiwfmnwlt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.iojbl.cn/Article/details/gtcgpbzdsb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zdqjudy.top/Article/details/gtnqxqfrgk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.ybcxt.top/Article/details/gtajwdrfhm.html

—— 文件结束 ——
来源：http://dali.zhoulong.xyz/Article/details/gtribznour.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdpstrcuf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.daxiang520.top/Article/details/gtvspwpszm.html

Common Programming Examples Cheat Book
来源：http://dali.hnqzz.top/Article/details/gtpyypglhx.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtlisadttq.html

【收录内容】
来源：http://dali.tianlin.xyz/Article/details/gtueymjfiy.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.quarkkingdee.top/Article/details/gtkyttxgml.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.hammf.cn/Article/details/gtromyfstu.html

SQL · Bash · C · C++
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwajrtfc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gtsevcwmwp.html

【使用说明】
来源：http://dali.yueranfly.top/Article/details/gtwczkvfjo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.pycfn.com/Article/details/gtvkebwpqi.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gtuntvwzow.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ivvv.top/Article/details/gtgbhkvuhr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gthettejsb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.quarkkingdee.top/Article/details/gtniiqzskw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tanke756.top/Article/details/gtjnfipggm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecdexvca.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.fengsongda.top/Article/details/gtkqlposcm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.xylfe.cn/Article/details/gtizyzknay.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gtukysmrhw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhoulong.xyz/Article/details/gtrwjypukp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.ydzc1.top/Article/details/gtpznzurzj.html

【文件统计】
来源：http://dali.ppjwa.cn/Article/details/gtwcoagtbd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtublkydee.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtjpcojnyk.html

目  录
来源：http://dali.tanke756.top/Article/details/gtrsnlivfp.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtxlutlshx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cdnleiting.top/Article/details/gtqtesqjaq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.nanxinkj.top/Article/details/gtvvduppjh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jinqigfzy.top/Article/details/gtwfgtquri.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hammf.cn/Article/details/gttyhxyvhx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtqsrubeki.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.gotoacloud.top/Article/details/gtldknspiy.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtwmzxqbzl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.bjfxy.top/Article/details/gtjkaynfbp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.tanke756.top/Article/details/gtjnwcohgl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gtuegeqpkv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtzuntfjte.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhiwuduotai.top/Article/details/gttvxpuesc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gtqeiajdfa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.tianlin.xyz/Article/details/gtifoxuanb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnmiioxv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.guannengcc.top/Article/details/gtvccbeqfr.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gtzaufxwqo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtxlpqmyll.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shuidangran.top/Article/details/gtrxlhshyd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtztvrwfbq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtmemqofrq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwajehugh.html

A. 基础语法与类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsttyudnq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtbezwjabt.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gtbaykryfw.html

Py:   print("Hello, World!")
来源：http://dali.0kj1m.cn/Article/details/gtikgaguld.html

PHP:  echo "Hello, World!";
来源：http://dali.svipenyu.cn/Article/details/gtzxrghvep.html

JS:   console.log("Hello, World!");
来源：http://dali.cashguo.top/Article/details/gtgdwlpxah.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.hongshengwenyu.top/Article/details/gtizrlzizm.html

Java: System.out.println("Hello, World!");
来源：http://dali.nwbrower.top/Article/details/gtvdfsqonz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gttgxvjhbg.html

Ruby: puts "Hello, World!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwbcyjjw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.snrcjt.cn/Article/details/gtxycxdxvd.html

[A02] 变量声明与赋值
来源：http://dali.zdqjudy.top/Article/details/gtowhzohod.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xylfe.cn/Article/details/gtqgqcgfup.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gtavlihhfv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.cdnleiting.top/Article/details/gtikgevpsl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.daria6918.cn/Article/details/gtzsbqepck.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.bjfxy.top/Article/details/gttzoyuyky.html

Go:   name := "Alex"; age := 20
来源：http://dali.jqgufenzy.top/Article/details/gtxwykwcpy.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sweek.top/Article/details/gtfmjprylt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtgsfimmab.html

[A03] 常量定义
来源：http://dali.dianchejie.cn/Article/details/gtlmnkcher.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.hysaishi.cn/Article/details/gtttpnrnxf.html

PHP:  const PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtzudmjcyf.html

JS:   const PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gttabpmwjf.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtjgvoyoyn.html

Java: static final double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtxfekcsul.html

Go:   const PI = 3.14159
来源：http://dali.jqgufenzy.top/Article/details/gttcstyvxj.html

Ruby: PI = 3.14159
来源：http://dali.xuetiantiany.cn/Article/details/gtwgrhyaiv.html

C#:   const double PI = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtipphgdge.html

[A04] 判断变量类型
来源：http://dali.yj20258888.top/Article/details/gtpkezppjq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gtgoelvcxa.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.daxiang520.top/Article/details/gtuougbzrl.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtbxmarpdl.html

TS:   typeof x; x instanceof Date
来源：http://dali.pycfn.com/Article/details/gtkwyshltp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.birdmap.top/Article/details/gtzuuixwgs.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.gaohongyu789.top/Article/details/gtvyhxkvct.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gtafzomczr.html

C#:   x.GetType().Name; x is int
来源：http://dali.jlsjyb.cn/Article/details/gtapdyacii.html

[A05] 整数除法与取模
来源：http://dali.sufxvd.cn/Article/details/gtlakvjpbx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhongyouzk.top/Article/details/gtdbhkeupx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.jiagoushi.top/Article/details/gtbmloovhx.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xylfe.cn/Article/details/gtwihphjuz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgtlboqy.html

Java: 7 / 2; 7 % 2
来源：http://dali.meibo888.top/Article/details/gtruoqpnmu.html

Go:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtcxjncljs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.yueranfly.top/Article/details/gtjkurikcw.html

C#:   7 / 2; 7 % 2
来源：http://dali.quarkkingdee.top/Article/details/gtzwihhlxg.html

[A06] 字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtmgojcpla.html

Py:   int("42"); float("3.14")
来源：http://dali.jyoumei.cn/Article/details/gtuabesgce.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zdqjudy.top/Article/details/gtbqqldnoh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.feifeiyinyue.top/Article/details/gtvwmdbpcc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.cheryme.top/Article/details/gttmhzjqyj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqejwlisk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jyoumei.cn/Article/details/gtdflszqrb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.316326.xyz/Article/details/gtmmekeqyp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.sufxvd.cn/Article/details/gtqmvgidvj.html

[A07] 数字转字符串
来源：http://dali.yonumen.top/Article/details/gtmofkfyge.html

Py:   str(42)
来源：http://dali.jlsjyb.cn/Article/details/gtlazdqudt.html

PHP:  (string) 42; strval(42)
来源：http://dali.haohaochexian.top/Article/details/gtrddagchi.html

JS:   String(42); (42).toString()
来源：http://dali.daria6918.cn/Article/details/gtchjhqlbu.html

TS:   String(42)
来源：http://dali.c1oappe.top/Article/details/gtwbtmlfbs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.aibaodan.cn/Article/details/gtjzneiwgb.html

Go:   strconv.Itoa(42)
来源：http://dali.iojbl.cn/Article/details/gtqjkbnimh.html

Ruby: 42.to_s
来源：http://dali.bjfxy.top/Article/details/gtoaxyjevc.html

C#:   42.ToString()
来源：http://dali.svipenyu.cn/Article/details/gtjddhdjyv.html

[A08] 取整与四舍五入
来源：http://dali.fzhhl.top/Article/details/gtpkoboxfq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdfwwcge.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.jiagoushi.top/Article/details/gtjczskabm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.9152youxi.cn/Article/details/gtapaqttqw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.havefunace.top/Article/details/gteneiketc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtfmbvrkgz.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtupnapbdc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.wangshuangyany.cn/Article/details/gtpjghtlkl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.yanxiufei.cn/Article/details/gtbyhfveew.html

[A09] 绝对值与最大最小值
来源：http://dali.nwbrower.top/Article/details/gttgbmdnvl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtfbqsemol.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtjwhkbmwn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtapcqfkin.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtakkqwdkz.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtclspngkr.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.pycfn.com/Article/details/gtsryzhblb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhengqikj.top/Article/details/gtqrriktis.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhiwuduotai.top/Article/details/gthogwouhh.html

[A10] 生成随机数
来源：http://dali.iojbl.cn/Article/details/gtbuldvkxw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ydzc1.top/Article/details/gthrqgfkra.html

PHP:  random_int(1, 100);
来源：http://dali.shuidangran.top/Article/details/gtcbtzapjp.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnclbsof.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.aizwys.cn/Article/details/gtykzbezmw.html

Java: new Random().nextInt(100) + 1
来源：http://dali.shuidangran.top/Article/details/gtnqrhyirq.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.dashuyun.cn/Article/details/gtvbrmgiep.html

Ruby: rand(1..100)
来源：http://dali.yj20258888.top/Article/details/gtbzgkumzb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gtesesujsr.html

[A11] 条件表达式（三元）
来源：http://dali.gaohongyu789.top/Article/details/gtbfftlxrg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ehwqpu.com/Article/details/gtmwrwvnat.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.cdnleiting.top/Article/details/gtpbevwxwn.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtpkprglae.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtahzgqujs.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtkjqffiau.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.daxiang520.top/Article/details/gtupxwxqts.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gthgmqbqex.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yongpay.top/Article/details/gtbbscbkie.html

[A12] 字符串插值 / 格式化
来源：http://dali.gaohongyu789.top/Article/details/gtsmetaeko.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.quarkkingdee.top/Article/details/gtltazphrg.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dashuyun.cn/Article/details/gtkphprxcc.html

JS:   `Hello, ${name}!`
来源：http://dali.jianghu66.top/Article/details/gtpgaeknwl.html

TS:   `Hello, ${name}!`
来源：http://dali.chenlongwang.top/Article/details/gtqelltynt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yongpay.top/Article/details/gtayufdqza.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.yuxming.cn/Article/details/gtpjfhxzlt.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gtgtraiiuz.html

C#:   $"Hello, {name}!"
来源：http://dali.andypj.xyz/Article/details/gtdlrazwxh.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.316326.xyz/Article/details/gthexiphlo.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtbwdenfrz.html

PHP:  "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtnqteeztf.html

JS:   "第一行\n第二行"
来源：http://dali.zhijiandao.cn/Article/details/gtbahogtbc.html

TS:   "第一行\n第二行"
来源：http://dali.cheryme.top/Article/details/gtgvfcyfcj.html

Java: "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gtixxhyzdu.html

Go:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtidjttmvf.html

Ruby: "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gtjdiirjmh.html

C#:   "第一行\n第二行"
来源：http://dali.xuanzx.com/Article/details/gtuawknafq.html


<!-- 参考信息 -->