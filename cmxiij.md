代发 wailian999

[U81] JS：初始化项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtrkwprwba.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gtcbqfbkrb.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtkgayxxnu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gaohongyu789.top/Article/details/gtkatzihqt.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gtgjmvjrot.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gtscovhelu.html

[U84] JS：CommonJS 写法
来源：http://dali.andypj.xyz/Article/details/gtyolykied.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shzxlz.cn/Article/details/gttcqksrrh.html

[U85] JS：可选链
来源：http://dali.9152youxi.cn/Article/details/gthzcakrhm.html

a?.b?.c
来源：http://dali.birdmap.top/Article/details/gtjvrbegof.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtxlvxdqgq.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gtkdubrrdz.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtklrhtrka.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gotoacloud.top/Article/details/gtefxjyvdh.html

[U88] JS：对象展开合并
来源：http://dali.gaohongyu789.top/Article/details/gtrsiztyfx.html

{ ...a, ...b }
来源：http://dali.chenlongwang.top/Article/details/gtucddfxjg.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gtswidkrsi.html

[...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtjrpyqjuu.html

[U90] JS：数字数组排序
来源：http://dali.pycfn.com/Article/details/gtaarskfru.html

[...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtjzxvyysg.html

[U91] JS：对象键值遍历
来源：http://dali.gzhubu.top/Article/details/gtdtfeegmd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.tianlin.xyz/Article/details/gtpctuddle.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gtimumdotj.html

structuredClone(obj)
来源：http://dali.hywenlv.cn/Article/details/gtbommhmml.html

[U93] JS：模板字符串
来源：http://dali.ybcxt.top/Article/details/gtrwklgbzr.html

`共 ${n} 条`
来源：http://dali.zycfv.cn/Article/details/gtaaxkpgbx.html

[U94] JS：箭头函数
来源：http://dali.yueranfly.top/Article/details/gteydlrgoh.html

const double = x => x * 2;
来源：http://dali.yueranfly.top/Article/details/gtzrmbsidq.html

[U95] JS：Promise 包装
来源：http://dali.daxiang520.top/Article/details/gtklcfihum.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gtdekabilx.html

[U96] JS：async/await 与异常
来源：http://dali.cqqwz.cn/Article/details/gtoqnvwhfo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabiaejyq.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtfkmodxtp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbzfidwn.html

[U98] JS：fetch 带 JSON
来源：http://dali.0kj1m.cn/Article/details/gtpxgiodtj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.guannengcc.top/Article/details/gtgzplfrwe.html

[U99] JS：事件监听
来源：http://dali.shangyingyoupin.top/Article/details/gtgpbnnwff.html

el.addEventListener("click", e => {})
来源：http://dali.cqqwz.cn/Article/details/gtsulovviw.html

[U100] JS：DOM 查询
来源：http://dali.yanxiufei.cn/Article/details/gtatrxizge.html

document.querySelector(".item")
来源：http://dali.iojbl.cn/Article/details/gtrcqwjasx.html

[U101] JS：classList 操作
来源：http://dali.wangshuangyany.cn/Article/details/gtorxjgoqd.html

el.classList.toggle("active")
来源：http://dali.yonumen.top/Article/details/gtjkqvclzc.html

[U102] JS：本地存储
来源：http://dali.cqqwz.cn/Article/details/gthgwmxyie.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gzhubu.top/Article/details/gtapcwmpce.html

[U103] JS：定时器
来源：http://dali.gogol.net.cn/Article/details/gtkfuvpzso.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.fzhhl.top/Article/details/gtlqftttvw.html

[U104] JS：防抖
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyawaycod.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtiyyjqsez.html

[U105] JS：节流
来源：http://dali.bjfxy.top/Article/details/gtywgdliun.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daria6918.cn/Article/details/gtrujfqhrf.html

[U106] JS：日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtpicyasjv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigfzy.top/Article/details/gtcdylxilm.html

[U107] JS：数字千分位
来源：http://dali.nwbrower.top/Article/details/gtjgykbtkv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.birdmap.top/Article/details/gtzstqdxza.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gtphyqidtq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shangyingyoupin.top/Article/details/gtmvnbnsqi.html

[U109] JS：数组分组
来源：http://dali.hammf.cn/Article/details/gtdehnxtvk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtqtnsqjpa.html

[U110] JS：数组分块
来源：http://dali.feifeiyinyue.top/Article/details/gtwekvthts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.cheryme.top/Article/details/gtycxnjjhx.html

[U111] JS：对象转 Map
来源：http://dali.gotoacloud.top/Article/details/gttemxqapd.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtgijkorbt.html

[U112] JS：字符串补位
来源：http://dali.ivvv.top/Article/details/gtpjvzluov.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtehavajdx.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtaexwpudu.html

s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gthtazejzw.html

[U114] JS：JSON 深比较
来源：http://dali.sufxvd.cn/Article/details/gtzvbiztoh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtfpdgtvjb.html

[U115] JS：生成 UUID
来源：http://dali.pengpengdd.cyou/Article/details/gtgxoxlffv.html

crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtymiziuuw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xuetiantiany.cn/Article/details/gtgmpbdrsi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gtatsxpeer.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtlbghrpvm.html

npm i -D vitest;  npx vitest
来源：http://dali.ydzc1.top/Article/details/gtkpjcygmb.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtwflutnle.html

npm i -D vite;  npx vite
来源：http://dali.cqqwz.cn/Article/details/gtdvrejzrd.html

[U119] JS：生产构建
来源：http://dali.yj20258.top/Article/details/gtrpqbanpb.html

npx vite build
来源：http://dali.yanxiufei.cn/Article/details/gtczoxtldf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yuxming.cn/Article/details/gtqxdqghiv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhixingplan.top/Article/details/gtvqvqrzgw.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtrcmarmtc.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gthszjrpyg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtrfhwhujf.html

按语言统计（条）：
来源：http://dali.gotoacloud.top/Article/details/gthewdisbr.html

Python ......... 252
来源：http://dali.shzxlz.cn/Article/details/gtmeafougq.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gtcvdelgez.html

JavaScript ..... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndeyergg.html

TypeScript ..... 212
来源：http://dali.fzhhl.top/Article/details/gtdsvbsuex.html

Java ........... 212
来源：http://dali.yangfankeji.com/Article/details/gtsukytghv.html

Go ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtyamqmbsh.html

Ruby ........... 212
来源：http://dali.guowangkeji.top/Article/details/gtafyzfxqh.html

C# ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtyyuokgba.html

C .............. 30
来源：http://dali.gotoacloud.top/Article/details/gtgkznjfzz.html

C++ ............ 30
来源：http://dali.yonumen.top/Article/details/gtooigaadm.html

SQL ............ 90
来源：http://dali.yj202588.top/Article/details/gthcfwilko.html

Bash ........... 80
来源：http://dali.sufxvd.cn/Article/details/gttzlribcv.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gtbuhkorko.html

Swift .......... 15
来源：http://dali.cqqwz.cn/Article/details/gtgydxtill.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gtbkaumygf.html

Perl ........... 10
来源：http://dali.guowangkeji.top/Article/details/gtzyahbzoo.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gtiauqovlo.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtygfunuuf.html

合计 ........... 2106 条
来源：http://dali.zycfv.cn/Article/details/gtnmchkpqy.html

按章节统计：
来源：http://dali.snrcjt.cn/Article/details/gthojcepos.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqebmcyb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gtioiobigz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gaohongyu789.top/Article/details/gtsqoxuuee.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtrtgygdpa.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zycfv.cn/Article/details/gtemrjywrn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinghuilouyu.cn/Article/details/gtejjxdant.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtgrgslbqz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gtouonknkk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gthhfcitwq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gtcpdskloh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daxiang520.top/Article/details/gtrmshlkbq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtcguggxvs.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sufxvd.cn/Article/details/gtkkkdulda.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhiwuduotai.top/Article/details/gtejbxuore.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ehwqpu.com/Article/details/gtjlrwylpw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtoqutnzqk.html

Q SQL 专题                              90
来源：http://dali.hnxiangtu.top/Article/details/gtgsmxofis.html

R Bash 专题                             80
来源：http://dali.dashuyun.cn/Article/details/gtmsnhxnen.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gtzmtvamsg.html

T 其他语言补充                          60
来源：http://dali.meibo888.top/Article/details/gtqbkuzihs.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gtjlvvxmsd.html

------------------------------------
来源：http://dali.sysykeji.top/Article/details/gtgpzfsnho.html

合计                                  2106 条
来源：http://dali.dashuyun.cn/Article/details/gtfhskzhdr.html

--------------------------------------------------------------------------------
来源：http://dali.andypj.xyz/Article/details/gttwuygphm.html

使用提醒
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnvevteo.html

--------------------------------------------------------------------------------
来源：http://dali.meibo888.top/Article/details/gtqbhjxerz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.ybcxt.top/Article/details/gthzhryioh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aizwys.cn/Article/details/gtbfxrmscp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gtuiebnbnn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.smart0.xyz/Article/details/gtvthzmudj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcclxnjl.html

—— 文件结束 ——
来源：http://dali.wangdashe.top/Article/details/gtyzztglaf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtvrvimyer.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofkihgqk.html

Common Programming Examples Cheat Book
来源：http://dali.hnxiangtu.top/Article/details/gtymcfncmq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzpsuquvv.html

【收录内容】
来源：http://dali.9152youxi.cn/Article/details/gtxvamwyrd.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shzxlz.cn/Article/details/gtsdjkqlmb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yanxiufei.cn/Article/details/gtgawtkalc.html

SQL · Bash · C · C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuignnah.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.bjfxy.top/Article/details/gtuysqfnwl.html

【使用说明】
来源：http://dali.gaohongyu789.top/Article/details/gtlyfzymcd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hnxiangtu.top/Article/details/gtuyplzjqb.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.tian-w.cn/Article/details/gtfmjieewi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.shzxlz.cn/Article/details/gtkdfqilvn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yuanzhike.top/Article/details/gtovbdxpez.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.xylfe.cn/Article/details/gtbrgwfsgu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.pengpengdd.cyou/Article/details/gtxwhxkczz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yj20258888.top/Article/details/gtchervxtt.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.nanxuanxn.top/Article/details/gtlqzxqaey.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgutjtxek.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.iojbl.cn/Article/details/gtsbsnqhmo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.jinqigfzy.top/Article/details/gtumfstqmg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbcgugcq.html

【文件统计】
来源：http://dali.andypj.xyz/Article/details/gthsvocwwd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.gogol.net.cn/Article/details/gtimmfpkor.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwduyjgt.html

目  录
来源：http://dali.zycfv.cn/Article/details/gtsylwcgkz.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtcsyyfqjf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yangfankeji.com/Article/details/gtunknhtfr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuxesvou.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.svipenyu.cn/Article/details/gtbaoihnku.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.fzhhl.top/Article/details/gtmhamgeuq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.sxryk.cn/Article/details/gtweocrysb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtmmfiegit.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.havefunace.top/Article/details/gttahekeyl.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.c1oappe.top/Article/details/gtwtmghupm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.aibaodan.cn/Article/details/gtonnbnfjl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtilavwrwk.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtollwbcoz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.yangfankeji.com/Article/details/gtkhcribft.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtskoxjpwd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.yuanzhike.top/Article/details/gtdsipnufu.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.sxryk.cn/Article/details/gtnxgtzkfg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.dianchejie.cn/Article/details/gtruepqajw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.aizwys.cn/Article/details/gtyfxxlelm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gtzjqeacnq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinqigfzy.top/Article/details/gtjckxqqbt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.0kj1m.cn/Article/details/gtiovdnnfw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtgeylpqat.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqiykqdug.html

A. 基础语法与类型
来源：http://dali.daxiang520.top/Article/details/gtxbvhcchd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrahhlef.html

[A01] Hello World
来源：http://dali.dianchejie.cn/Article/details/gtthdvdvng.html

Py:   print("Hello, World!")
来源：http://dali.zhengqikj.top/Article/details/gtpeewttsn.html

PHP:  echo "Hello, World!";
来源：http://dali.yuxming.cn/Article/details/gtrdsvgbpj.html

JS:   console.log("Hello, World!");
来源：http://dali.pengpengdd.cyou/Article/details/gtykhbuyqg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jyoumei.cn/Article/details/gtqfkepapj.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvtpgowu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.xinyue.icu/Article/details/gtsbiwccyo.html

Ruby: puts "Hello, World!"
来源：http://dali.tanke756.top/Article/details/gtmgwgvpgg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.yanxiufei.cn/Article/details/gtuftqnyrv.html

[A02] 变量声明与赋值
来源：http://dali.dianchejie.cn/Article/details/gtlyqcuoac.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.aibaodan.cn/Article/details/gtjicyrfuv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhengqikj.top/Article/details/gtxrghqein.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.fengsongda.top/Article/details/gttytqykhg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhixingplan.top/Article/details/gtvujaojhf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenlongwang.top/Article/details/gtcvoirhcf.html

Go:   name := "Alex"; age := 20
来源：http://dali.sxryk.cn/Article/details/gtstqgozad.html

Ruby: name = "Alex"; age = 20
来源：http://dali.sxryk.cn/Article/details/gthydonmne.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xziqi.cn/Article/details/gtvleqhoou.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gtrbncwpkd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xinyue.icu/Article/details/gtqfpnzzyr.html

PHP:  const PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtjotrjhiu.html

JS:   const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdzctgul.html

TS:   const PI: number = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtmawlajnk.html

Java: static final double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtyxrejejg.html

Go:   const PI = 3.14159
来源：http://dali.shzxlz.cn/Article/details/gtjwzolpbf.html

Ruby: PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gtvbrylgki.html

C#:   const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtzqdyoyah.html

[A04] 判断变量类型
来源：http://dali.iojbl.cn/Article/details/gtuqahctim.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpalkejf.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.pycfn.com/Article/details/gtfdvqfcdf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jyoumei.cn/Article/details/gtlaotkcds.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtaaplhwpw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.hfpthk.cn/Article/details/gtsztwrqti.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yongpay.top/Article/details/gtifaqsewk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.ivvv.top/Article/details/gtekivodgy.html

C#:   x.GetType().Name; x is int
来源：http://dali.feifeiyinyue.top/Article/details/gtsxxrusrb.html

[A05] 整数除法与取模
来源：http://dali.yvedp.cn/Article/details/gtbidiulrt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.yvedp.cn/Article/details/gtscrbtwgo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.cashguo.top/Article/details/gtdwyvqlke.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtqvpowdon.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yvedp.cn/Article/details/gtocbbxkgi.html

Java: 7 / 2; 7 % 2
来源：http://dali.nanxuanxn.top/Article/details/gtursrqqek.html

Go:   7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjehzijps.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.0kj1m.cn/Article/details/gtmviyfnvt.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gtmlykrwqx.html

[A06] 字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gtrfbzgjkf.html

Py:   int("42"); float("3.14")
来源：http://dali.dianchejie.cn/Article/details/gtmhuhbfag.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jlsjyb.cn/Article/details/gtkoxhwixy.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.chenlongwang.top/Article/details/gtlyqdvdap.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gtzdgbpbeh.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.yuanzhike.top/Article/details/gtvxrrohke.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.sysykeji.top/Article/details/gtneximqcy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.wangshuangyany.cn/Article/details/gtajicghqq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdqrfaep.html

[A07] 数字转字符串
来源：http://dali.yonumen.top/Article/details/gtwnxhopll.html

Py:   str(42)
来源：http://dali.chenlongwang.top/Article/details/gtcuwtwoya.html

PHP:  (string) 42; strval(42)
来源：http://dali.cqqwz.cn/Article/details/gtiicqbcih.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258.top/Article/details/gtgkalenrv.html

TS:   String(42)
来源：http://dali.xuanzx.com/Article/details/gtjwtgqusk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.wangdashe.top/Article/details/gtqvvistbp.html

Go:   strconv.Itoa(42)
来源：http://dali.iojbl.cn/Article/details/gtoeplupax.html

Ruby: 42.to_s
来源：http://dali.hywenlv.cn/Article/details/gtitlhovfk.html

C#:   42.ToString()
来源：http://dali.dianchejie.cn/Article/details/gtnzgztxvt.html

[A08] 取整与四舍五入
来源：http://dali.shuidangran.top/Article/details/gtkqfebhzb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gtagknbpwi.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.shuidangran.top/Article/details/gtrwklzpdz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yueranfly.top/Article/details/gtbrtakygi.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.9152youxi.cn/Article/details/gtuuhbgohq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.c1oappe.top/Article/details/gtaiwxymhv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteiupokpb.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.cucudq.cn/Article/details/gteqhnrufd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.hfpthk.cn/Article/details/gtouxnycgo.html

[A09] 绝对值与最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gtlasgogvq.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gttuysebis.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtpzmxvida.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtoghygben.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hywenlv.cn/Article/details/gtbokmxgdi.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtpgvyshdb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.smart0.xyz/Article/details/gtnkdzpybk.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.hnqzz.top/Article/details/gtscloczgp.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtrmjlpvtp.html

[A10] 生成随机数
来源：http://dali.tianlin.xyz/Article/details/gttfwhktwm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.nwbrower.top/Article/details/gtvlshopmc.html

PHP:  random_int(1, 100);
来源：http://dali.mhx1999.top/Article/details/gtbgatahqo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.hongshengwenyu.top/Article/details/gtchqftzqw.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtodwlsuvo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtbvdipiui.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.birdmap.top/Article/details/gtdlzukjmg.html

Ruby: rand(1..100)
来源：http://dali.yonumen.top/Article/details/gtvxhiiyfx.html

C#:   new Random().Next(1, 101)
来源：http://dali.sysykeji.top/Article/details/gtalgsjkqr.html

[A11] 条件表达式（三元）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppfwzxqc.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.gzhubu.top/Article/details/gthcurodak.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymoctxsa.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hnxiangtu.top/Article/details/gtyottyrwp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtqwnuhuoi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.vqdsnc.cn/Article/details/gtwxeqgcjd.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.hnqzz.top/Article/details/gtgxoawtha.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.ehwqpu.com/Article/details/gtgobaqomv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jianghu66.top/Article/details/gtycydnlfk.html

[A12] 字符串插值 / 格式化
来源：http://dali.yonumen.top/Article/details/gtwcsrledx.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.quarkkingdee.top/Article/details/gtvydfgxrx.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.nwbrower.top/Article/details/gtbkljefnu.html

JS:   `Hello, ${name}!`
来源：http://dali.hongshengwenyu.top/Article/details/gtrpatsqtj.html

TS:   `Hello, ${name}!`
来源：http://dali.dianchejie.cn/Article/details/gtfeotohqt.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shangyingyoupin.top/Article/details/gtehdkquul.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hysaishi.cn/Article/details/gtfypwxtjc.html

Ruby: "Hello, #{name}!"
来源：http://dali.smart0.xyz/Article/details/gtvxquajpy.html

C#:   $"Hello, {name}!"
来源：http://dali.zhengqikj.top/Article/details/gtqtgmlmdq.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shzxlz.cn/Article/details/gtjnhaasyv.html

Py:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtibkyktte.html

PHP:  "第一行\n第二行"
来源：http://dali.aizwys.cn/Article/details/gtzolwryah.html

JS:   "第一行\n第二行"
来源：http://dali.jinqigfzy.top/Article/details/gtubtkxwha.html

TS:   "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtqofvpowh.html


<!-- 参考信息 -->