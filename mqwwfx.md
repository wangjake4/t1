代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.dianchejie.cn/Article/details/gtwonyloug.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtolmtkxvy.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gtlinmsspf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gogol.net.cn/Article/details/gtgxswnxyf.html

[U85] JS：可选链
来源：http://dali.haohaochexian.top/Article/details/gtlmvpnsnf.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gtlvhauusp.html

[U86] JS：空值合并
来源：http://dali.chenzaomai.com/Article/details/gtncccbesz.html

a ?? b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdwzblhb.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtwzvhvroe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hfpthk.cn/Article/details/gtunfhjqeq.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gtqgzhxpif.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gtgchxhomh.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtwggsomec.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtfkesotyf.html

[U90] JS：数字数组排序
来源：http://dali.yj20258.top/Article/details/gtvnjbtutm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtriqhghuz.html

[U91] JS：对象键值遍历
来源：http://dali.shuidangran.top/Article/details/gtjeumefga.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gtsnufcqlb.html

[U92] JS：深拷贝
来源：http://dali.daria6918.cn/Article/details/gtmihljqmp.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gthihwqgrh.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gtexcnadle.html

`共 ${n} 条`
来源：http://dali.daria6918.cn/Article/details/gtcukxckxq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gtxbcgjfhr.html

const double = x => x * 2;
来源：http://dali.yj202588.top/Article/details/gtrxazuleb.html

[U95] JS：Promise 包装
来源：http://dali.gzhubu.top/Article/details/gtjjrzrnbr.html

new Promise((resolve, reject) => {})
来源：http://dali.chenzaomai.com/Article/details/gtyphetrav.html

[U96] JS：async/await 与异常
来源：http://dali.sufxvd.cn/Article/details/gtfvpkwvav.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtrfihkqfk.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtgsotauak.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gttbktstyg.html

[U98] JS：fetch 带 JSON
来源：http://dali.hongshengwenyu.top/Article/details/gtjylplnqj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guowangkeji.top/Article/details/gtpoxwgann.html

[U99] JS：事件监听
来源：http://dali.0kj1m.cn/Article/details/gtbaekfbhi.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtomhvulrm.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxmvnxre.html

document.querySelector(".item")
来源：http://dali.iojbl.cn/Article/details/gtclkcefzg.html

[U101] JS：classList 操作
来源：http://dali.sxryk.cn/Article/details/gtvwedrpip.html

el.classList.toggle("active")
来源：http://dali.cucudq.cn/Article/details/gtymfppexf.html

[U102] JS：本地存储
来源：http://dali.redwolf501.top/Article/details/gtfszjhmmi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtcxgkegyq.html

[U103] JS：定时器
来源：http://dali.zhoulong.xyz/Article/details/gtgyoatptr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zdqjudy.top/Article/details/gtublbbdse.html

[U104] JS：防抖
来源：http://dali.wangshuangyany.cn/Article/details/gtpcxfrmis.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gtyqszqcuk.html

[U105] JS：节流
来源：http://dali.pycfn.com/Article/details/gtoiulqllq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.guannengcc.top/Article/details/gtorgwywpk.html

[U106] JS：日期格式化
来源：http://dali.yj202588.top/Article/details/gtofurdvno.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gaohongyu789.top/Article/details/gtedfsyczm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtvbvwfdmt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtreyrqdqs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gtstphfyhk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ivvv.top/Article/details/gtgqdoeofu.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtpkxmyfqk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtxnbihzjm.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtwwcuzysr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhengqikj.top/Article/details/gtqjzwbzez.html

[U111] JS：对象转 Map
来源：http://dali.vqdsnc.cn/Article/details/gtxsurmoth.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gtptpoeebe.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gtimzryxjk.html

"7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtbyovaiju.html

[U113] JS：正则替换全部
来源：http://dali.zhixingplan.top/Article/details/gtxmtmfaig.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtiydqwjlk.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gtyzeryenh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtfhtdjgva.html

[U115] JS：生成 UUID
来源：http://dali.hnqzz.top/Article/details/gtaihbnqie.html

crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gttzyumeht.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtwcanetbs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hysaishi.cn/Article/details/gtlpeppsyv.html

[U117] JS：单元测试
来源：http://dali.shzxlz.cn/Article/details/gtcyekkuhv.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gtsqxwdven.html

[U118] JS：开发服务器
来源：http://dali.nanxinkj.top/Article/details/gtgbykgvsh.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gtsqvbfbdl.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gtdqqsrvow.html

npx vite build
来源：http://dali.cheryme.top/Article/details/gtmvirgprf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gtxgbmrcrj.html

import.meta.env.VITE_API_URL
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslsibict.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyhieevdq.html

统计汇总
来源：http://dali.shzxlz.cn/Article/details/gtghwqdgld.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtshynjbxw.html

按语言统计（条）：
来源：http://dali.mhx1999.top/Article/details/gtlzbgykrd.html

Python ......... 252
来源：http://dali.sysykeji.top/Article/details/gtaqwvdlei.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gtungjlrkq.html

JavaScript ..... 252
来源：http://dali.svipenyu.cn/Article/details/gtqsvusfme.html

TypeScript ..... 212
来源：http://dali.0kj1m.cn/Article/details/gtovpwdlfg.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtddztswtx.html

Go ............. 212
来源：http://dali.hfpthk.cn/Article/details/gteyshtgxl.html

Ruby ........... 212
来源：http://dali.ybcxt.top/Article/details/gthkusxmkb.html

C# ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtkrivfmqv.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtsffzznlt.html

C++ ............ 30
来源：http://dali.pengpengdd.cyou/Article/details/gtcxqhlcez.html

SQL ............ 90
来源：http://dali.bjfxy.top/Article/details/gtaxsvktyp.html

Bash ........... 80
来源：http://dali.ivvv.top/Article/details/gtwnzrgqss.html

Kotlin ......... 15
来源：http://dali.mhx1999.top/Article/details/gtprpxfyso.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtprnpyncx.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gtdgehkwlu.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbdyhnby.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gtauqxaahr.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gttqfewtpf.html

合计 ........... 2106 条
来源：http://dali.xziqi.cn/Article/details/gtmehigglw.html

按章节统计：
来源：http://dali.cqqwz.cn/Article/details/gtxjkywrbs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shzxlz.cn/Article/details/gthrozxozb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhiwuduotai.top/Article/details/gtuogtddom.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtkxiuthmq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.daria6918.cn/Article/details/gtxmniuogy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gtokmyzfmz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeltlsgj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtqhpylvop.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gtyyxzrryz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtyibovgzw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.dianchejie.cn/Article/details/gtnoatqbnv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.gaohongyu789.top/Article/details/gtiiaxkomc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtbcrbzplg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtalusythg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.tanke756.top/Article/details/gtuukzvala.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gtefmewfxe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gthewopizp.html

Q SQL 专题                              90
来源：http://dali.xuanzx.com/Article/details/gtadmkztnd.html

R Bash 专题                             80
来源：http://dali.aizwys.cn/Article/details/gtdzgkcjbu.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtikipegex.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtffjjgnts.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gtlfcewoue.html

------------------------------------
来源：http://dali.yj20258888.top/Article/details/gtmxkwddjr.html

合计                                  2106 条
来源：http://dali.cashguo.top/Article/details/gtcjiqijwo.html

--------------------------------------------------------------------------------
来源：http://dali.ivvv.top/Article/details/gtiihzjpyj.html

使用提醒
来源：http://dali.ybcxt.top/Article/details/gtkbcugwvg.html

--------------------------------------------------------------------------------
来源：http://dali.0kj1m.cn/Article/details/gtsgfvnfno.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.dashuyun.cn/Article/details/gtaeswpkqo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.daria6918.cn/Article/details/gtiwgoqvpc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.cashguo.top/Article/details/gtwmzjokpk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.yj202588.top/Article/details/gtfbuzrayj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.sysykeji.top/Article/details/gtebpkjool.html

—— 文件结束 ——
来源：http://dali.xylfe.cn/Article/details/gtklzjwdfk.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdkncxire.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.ppjwa.cn/Article/details/gtqngxyjrw.html

Common Programming Examples Cheat Book
来源：http://dali.zhoulong.xyz/Article/details/gteqcjslqk.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzlbyhvcb.html

【收录内容】
来源：http://dali.wangshuangyany.cn/Article/details/gtpwnhbfdq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gtrhnbppdj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.svipenyu.cn/Article/details/gtxntmhyfq.html

SQL · Bash · C · C++
来源：http://dali.zhiwuduotai.top/Article/details/gtjtzajubq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.ppjwa.cn/Article/details/gthdojpqlm.html

【使用说明】
来源：http://dali.haohaochexian.top/Article/details/gtsrjfgtey.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.vqdsnc.cn/Article/details/gtwueeycbu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.daxiang520.top/Article/details/gtpaaonlyw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdypqgjcn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yanxiufei.cn/Article/details/gtzqlfkekg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgokhkbgg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cdnleiting.top/Article/details/gtokwxxyzz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.andypj.xyz/Article/details/gtmveiftmj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.ybcxt.top/Article/details/gthlsfkdcx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.c1oappe.top/Article/details/gtigwhfrhk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.yj20258.top/Article/details/gtjpzjwskr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.quarkkingdee.top/Article/details/gtxmymgzrb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gtnadjoadz.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gtjvrdvpbq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sweek.top/Article/details/gteppuixkc.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gtlwugluib.html

目  录
来源：http://dali.kuanghao11.cn/Article/details/gtzsofkbus.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gtrdyxmcma.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gtjzgbelyx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xylfe.cn/Article/details/gtvxgpudii.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.bjfxy.top/Article/details/gtanlpeouc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.bjfxy.top/Article/details/gtuxtjgcwy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.tianlin.xyz/Article/details/gtkduhphah.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.dashuyun.cn/Article/details/gtrsvdogbe.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.kuanghao11.cn/Article/details/gtgcawxisk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sweek.top/Article/details/gtqobirzzx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.yuanzhike.top/Article/details/gtppvotqpg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.gaohongyu789.top/Article/details/gtelezhvsq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtwvjcpnzv.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtabbauzfi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.xinyue.icu/Article/details/gtpvzudkiq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shuidangran.top/Article/details/gthccpmxyd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.svipenyu.cn/Article/details/gthucoqmjq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinqigfzy.top/Article/details/gtmiuqqznf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtgrlpofkg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.chenzaomai.com/Article/details/gtapnchgzd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.hnqzz.top/Article/details/gtpuheaxtj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtjyiojnnv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtxwbuitpy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdvczhgyj.html

A. 基础语法与类型
来源：http://dali.xuanzx.com/Article/details/gtrtqmuujg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesvojnde.html

[A01] Hello World
来源：http://dali.daxiang520.top/Article/details/gtsxvhzrnb.html

Py:   print("Hello, World!")
来源：http://dali.snrcjt.cn/Article/details/gtngmqedqq.html

PHP:  echo "Hello, World!";
来源：http://dali.smart0.xyz/Article/details/gtlowexkxx.html

JS:   console.log("Hello, World!");
来源：http://dali.guannengcc.top/Article/details/gtsgmsjfpj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.9152youxi.cn/Article/details/gttssoehlh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhixingplan.top/Article/details/gtlhsazsez.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hammf.cn/Article/details/gtphqvxano.html

Ruby: puts "Hello, World!"
来源：http://dali.yonumen.top/Article/details/gtthdtyzfc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosgkpkhn.html

[A02] 变量声明与赋值
来源：http://dali.yj20258888.top/Article/details/gtrdjjquob.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.ppjwa.cn/Article/details/gtnxzdoiha.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gzhubu.top/Article/details/gteqjhfvvb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gtzkqqxaza.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.shangyingyoupin.top/Article/details/gturmhqtqf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.hnqzz.top/Article/details/gteooynbdb.html

Go:   name := "Alex"; age := 20
来源：http://dali.jlsjyb.cn/Article/details/gtrfsphatf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.tanke756.top/Article/details/gtpljwewjz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtqnwdquzo.html

[A03] 常量定义
来源：http://dali.aibaodan.cn/Article/details/gtnuevyjeb.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.gogol.net.cn/Article/details/gtqanxwikc.html

PHP:  const PI = 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtofzipkus.html

JS:   const PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtncxslkaw.html

TS:   const PI: number = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtmpguzxws.html

Java: static final double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gttvyebndw.html

Go:   const PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtzwbtmsss.html

Ruby: PI = 3.14159
来源：http://dali.ivvv.top/Article/details/gtbkzgzzfu.html

C#:   const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtydedgkzm.html

[A04] 判断变量类型
来源：http://dali.xinyue.icu/Article/details/gtndedtizm.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtqrrutazm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.hfpthk.cn/Article/details/gtweuznuao.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yonumen.top/Article/details/gtvgqwjqkd.html

TS:   typeof x; x instanceof Date
来源：http://dali.hnxiangtu.top/Article/details/gtdjltlsfn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.jyoumei.cn/Article/details/gtweswhmdm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigufen.top/Article/details/gtbqofbzke.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.shzxlz.cn/Article/details/gtwbxdrdpu.html

C#:   x.GetType().Name; x is int
来源：http://dali.aizwys.cn/Article/details/gtcrqisepm.html

[A05] 整数除法与取模
来源：http://dali.zhengqikj.top/Article/details/gtnpysisjq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.shzxlz.cn/Article/details/gtflzhfoha.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.daxiang520.top/Article/details/gtipewbqdp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aizwys.cn/Article/details/gthwdrlnla.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtkgauzdla.html

Java: 7 / 2; 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtewzvzeeu.html

Go:   7 / 2; 7 % 2
来源：http://dali.birdmap.top/Article/details/gtssbmwzqe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gtacctebjo.html

C#:   7 / 2; 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtxcwfydki.html

[A06] 字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtlhbjmquf.html

Py:   int("42"); float("3.14")
来源：http://dali.daria6918.cn/Article/details/gtnskriaoj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.fengsongda.top/Article/details/gtnusxruuh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.yueranfly.top/Article/details/gtmvrctyzl.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.daria6918.cn/Article/details/gtdprftohm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gtasvjmuml.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gtezjhlwll.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hnqzz.top/Article/details/gtnmfebbzo.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkndojnpn.html

[A07] 数字转字符串
来源：http://dali.aizwys.cn/Article/details/gtaqggudut.html

Py:   str(42)
来源：http://dali.jqgfzy.top/Article/details/gtgyizjleq.html

PHP:  (string) 42; strval(42)
来源：http://dali.guannengcc.top/Article/details/gtdlnphvms.html

JS:   String(42); (42).toString()
来源：http://dali.gaohongyu789.top/Article/details/gtrjhxtnno.html

TS:   String(42)
来源：http://dali.chenzaomai.com/Article/details/gtmyzsxfvy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gtgexaxxnz.html

Go:   strconv.Itoa(42)
来源：http://dali.sxryk.cn/Article/details/gtouebghiu.html

Ruby: 42.to_s
来源：http://dali.shuidangran.top/Article/details/gtrgwhzwts.html

C#:   42.ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqwiygbc.html

[A08] 取整与四舍五入
来源：http://dali.yj20258888.top/Article/details/gtxnttpbsh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.bjfxy.top/Article/details/gtnkchyund.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.wangdashe.top/Article/details/gtyucnxkou.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xuetiantiany.cn/Article/details/gtssbzqzmi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.hnqzz.top/Article/details/gtptfrsbga.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.havefunace.top/Article/details/gtwrsdhuso.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtirvmqnaw.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gogol.net.cn/Article/details/gtujjmrmik.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.pengpengdd.cyou/Article/details/gtrfxitshi.html

[A09] 绝对值与最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtnqufwgfz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtkrxxiklv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtnhyezohl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.ivvv.top/Article/details/gtgjgpyfqp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtxfbpxees.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwonahlpq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtpyohjjeb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hammf.cn/Article/details/gtgrwkbyxc.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yj20258.top/Article/details/gtjidojlig.html

[A10] 生成随机数
来源：http://dali.hnqzz.top/Article/details/gtpmystybr.html

Py:   import random; random.randint(1, 100)
来源：http://dali.aizwys.cn/Article/details/gtvtbfthky.html

PHP:  random_int(1, 100);
来源：http://dali.feifeiyinyue.top/Article/details/gtsjbknuhu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hnxiangtu.top/Article/details/gtntbbakcv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfqvfrkh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlrjrxmn.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmmoeehje.html

Ruby: rand(1..100)
来源：http://dali.sysykeji.top/Article/details/gttiiylrob.html

C#:   new Random().Next(1, 101)
来源：http://dali.yueranfly.top/Article/details/gtciweqdmp.html

[A11] 条件表达式（三元）
来源：http://dali.316326.xyz/Article/details/gtfitetbad.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.daxiang520.top/Article/details/gthfbvguck.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtygxrtzmt.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtikicfkit.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtfysxnacj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.daxiang520.top/Article/details/gtqcffsaxp.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhiwuduotai.top/Article/details/gtlaltyvbc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.pengpengdd.cyou/Article/details/gtsqfywobu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258888.top/Article/details/gtvuaqdnfn.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhixingplan.top/Article/details/gttazotaat.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.wangshuangyany.cn/Article/details/gtophkkkpb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.bjfxy.top/Article/details/gtvkjhmqqx.html

JS:   `Hello, ${name}!`
来源：http://dali.meibo888.top/Article/details/gtcrhdntlr.html

TS:   `Hello, ${name}!`
来源：http://dali.xuanzx.com/Article/details/gtdmznruqc.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhiwuduotai.top/Article/details/gtfadlawqn.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.haohaochexian.top/Article/details/gthywkgzzj.html

Ruby: "Hello, #{name}!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnwwfros.html

C#:   $"Hello, {name}!"
来源：http://dali.yanxiufei.cn/Article/details/gtqzibiept.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.pycfn.com/Article/details/gtfafwpdfn.html

Py:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtyqxdmwzv.html

PHP:  "第一行\n第二行"
来源：http://dali.chenlongwang.top/Article/details/gtmwvuwozq.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtwmcltpii.html

TS:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gtytlpszzb.html

Java: "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtgspuvoto.html

Go:   "第一行\n第二行"
来源：http://dali.pengpengdd.cyou/Article/details/gtplsrwalt.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtonucruqv.html

C#:   "第一行\n第二行"
来源：http://dali.haohaochexian.top/Article/details/gtryimypep.html


<!-- 参考信息 -->