代发 wailian999

[U83] JS：ES Module 导入导出
来源：http://dali.jqgufenzy.top/Article/details/gtjbbzaotj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtcesnegwi.html

[U84] JS：CommonJS 写法
来源：http://dali.cqqwz.cn/Article/details/gtrtmgyqie.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.wangshuangyany.cn/Article/details/gtyjpgxayx.html

[U85] JS：可选链
来源：http://dali.c1oappe.top/Article/details/gtddbjkglm.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gtbnceuwqu.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gttazvbwox.html

a ?? b
来源：http://dali.ydzc1.top/Article/details/gtddasmcgr.html

[U87] JS：解构默认值
来源：http://dali.yvedp.cn/Article/details/gtiprorcey.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtiosqefue.html

[U88] JS：对象展开合并
来源：http://dali.hysaishi.cn/Article/details/gtiodmpatv.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gtgfufnpko.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gtesdxaddx.html

[...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtpzlotvnn.html

[U90] JS：数字数组排序
来源：http://dali.yueranfly.top/Article/details/gtmhcuinvo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtkxqhihjy.html

[U91] JS：对象键值遍历
来源：http://dali.snrcjt.cn/Article/details/gtcdmyspvr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shangyingyoupin.top/Article/details/gtmzvocsxn.html

[U92] JS：深拷贝
来源：http://dali.fengsongda.top/Article/details/gtviimoixk.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gtergqdccx.html

[U93] JS：模板字符串
来源：http://dali.zhoulong.xyz/Article/details/gtipyvbady.html

`共 ${n} 条`
来源：http://dali.svipenyu.cn/Article/details/gtwzyjttih.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gtwbcliosl.html

const double = x => x * 2;
来源：http://dali.fzhhl.top/Article/details/gtmgfnoccl.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoibnyou.html

new Promise((resolve, reject) => {})
来源：http://dali.9152youxi.cn/Article/details/gtfjeynbzi.html

[U96] JS：async/await 与异常
来源：http://dali.hongshengwenyu.top/Article/details/gtyqchtxqd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtsazbhsqe.html

[U97] JS：并发请求
来源：http://dali.hnqzz.top/Article/details/gtgekrjnow.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gtmynwwekk.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtlkcwnzss.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aizwys.cn/Article/details/gtybkwxill.html

[U99] JS：事件监听
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpextltlu.html

el.addEventListener("click", e => {})
来源：http://dali.haohaochexian.top/Article/details/gtjsvbqatm.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtrsjqvtaw.html

document.querySelector(".item")
来源：http://dali.chenzaomai.com/Article/details/gtpnaqfekt.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gtocslmhsq.html

el.classList.toggle("active")
来源：http://dali.tian-w.cn/Article/details/gtwntomvaa.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gtgjzsylrm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gtmlwfnfvh.html

[U103] JS：定时器
来源：http://dali.zhengqikj.top/Article/details/gtaamntjtk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jinqigfzy.top/Article/details/gtuvotytgy.html

[U104] JS：防抖
来源：http://dali.cashguo.top/Article/details/gtupzxdvih.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.birdmap.top/Article/details/gtfgpamjmo.html

[U105] JS：节流
来源：http://dali.gzhubu.top/Article/details/gtvteryjna.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gtljrjdbpz.html

[U106] JS：日期格式化
来源：http://dali.gzhubu.top/Article/details/gtdywxhfni.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258888.top/Article/details/gtdqxjtoup.html

[U107] JS：数字千分位
来源：http://dali.sufxvd.cn/Article/details/gtsdvwjakp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gtualmwdvb.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gtlduvirww.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hongshengwenyu.top/Article/details/gtfietyqgz.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtjpiabrvl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhoulong.xyz/Article/details/gtjefjxqzq.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gtftlgmjzz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.nanxinkj.top/Article/details/gtaoyctaqd.html

[U111] JS：对象转 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihtasxpr.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gtesonedkk.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gtzyilgwnq.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtuzjpauta.html

[U113] JS：正则替换全部
来源：http://dali.shangyingyoupin.top/Article/details/gtivevvxpq.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gthhlirrdu.html

[U114] JS：JSON 深比较
来源：http://dali.cdnleiting.top/Article/details/gtudprxksf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xziqi.cn/Article/details/gtbqfeyyfz.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtykubugrz.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtsyzmwqmf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.tanke756.top/Article/details/gtlwfklktn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.meibo888.top/Article/details/gtqbglanpn.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gtvikflmsy.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gtoatuwpgf.html

[U118] JS：开发服务器
来源：http://dali.nwbrower.top/Article/details/gtawillzuk.html

npm i -D vite;  npx vite
来源：http://dali.sufxvd.cn/Article/details/gtecnxdaad.html

[U119] JS：生产构建
来源：http://dali.xylfe.cn/Article/details/gtjzapclbd.html

npx vite build
来源：http://dali.sysykeji.top/Article/details/gtvkdmstys.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.snrcjt.cn/Article/details/gtqgwldnho.html

import.meta.env.VITE_API_URL
来源：http://dali.jianghu66.top/Article/details/gtpchfevlt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtbyfdcsvy.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtnsrdvfmm.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnbkfypyx.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gtmxqgbnth.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gtojbawlcp.html

PHP ............ 252
来源：http://dali.jiagoushi.top/Article/details/gtcehlbxpj.html

JavaScript ..... 252
来源：http://dali.yonumen.top/Article/details/gtimqnjjck.html

TypeScript ..... 212
来源：http://dali.tanke756.top/Article/details/gtemsgfkli.html

Java ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtocpkpjyb.html

Go ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtkfwjrkxk.html

Ruby ........... 212
来源：http://dali.vqdsnc.cn/Article/details/gtqyniodwd.html

C# ............. 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouwekkiu.html

C .............. 30
来源：http://dali.pycfn.com/Article/details/gtxkuieuft.html

C++ ............ 30
来源：http://dali.hfpthk.cn/Article/details/gtssbwcmrf.html

SQL ............ 90
来源：http://dali.sysykeji.top/Article/details/gtaiiufntr.html

Bash ........... 80
来源：http://dali.smart0.xyz/Article/details/gtrefptequ.html

Kotlin ......... 15
来源：http://dali.zycfv.cn/Article/details/gtipvkarcm.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtojkxjsul.html

Lua ............ 10
来源：http://dali.nanxinkj.top/Article/details/gtjdbdwmrc.html

Perl ........... 10
来源：http://dali.fengsongda.top/Article/details/gtfuxpnnmd.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gtyqovmjdj.html

------------------------------------
来源：http://dali.birdmap.top/Article/details/gtobtujvzq.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtioopymli.html

按章节统计：
来源：http://dali.yuanzhike.top/Article/details/gtszylstvr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jinqigfzy.top/Article/details/gtidxqsuzn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtbtiplnjx.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gtvoldzkzc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gtbjoxsrch.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gaohongyu789.top/Article/details/gtfdrpsjhh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hysaishi.cn/Article/details/gtmvbscqpv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gtrcogziys.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cucudq.cn/Article/details/gtawnvqxwo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtverzbsxg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtlyjpbbxr.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtpnulafih.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtrmmyqhvo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtaqqyoyvt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jiagoushi.top/Article/details/gtgetxfxua.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvjjtdnq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shuidangran.top/Article/details/gtfvdggshk.html

Q SQL 专题                              90
来源：http://dali.bjfxy.top/Article/details/gtjbtgunrn.html

R Bash 专题                             80
来源：http://dali.gaohongyu789.top/Article/details/gtgpnapvfw.html

S C / C++ 专题                          60
来源：http://dali.sufxvd.cn/Article/details/gtfcfflemc.html

T 其他语言补充                          60
来源：http://dali.fzhhl.top/Article/details/gtctnnjnfc.html

U 高频实用片段                         120
来源：http://dali.haohaochexian.top/Article/details/gthgfbabov.html

------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzetkazb.html

合计                                  2106 条
来源：http://dali.ehwqpu.com/Article/details/gtxrztijct.html

--------------------------------------------------------------------------------
来源：http://dali.tanke756.top/Article/details/gtbplqlfvo.html

使用提醒
来源：http://dali.kuanghao11.cn/Article/details/gtakgyehyd.html

--------------------------------------------------------------------------------
来源：http://dali.sweek.top/Article/details/gtpsnnlhdb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yueranfly.top/Article/details/gtlvnjfjic.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnxpfozw.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.meibo888.top/Article/details/gtecxiiwbi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.meibo888.top/Article/details/gtmdcmjryq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdywfkyk.html

—— 文件结束 ——
来源：http://dali.gzhubu.top/Article/details/gtmffvxdxm.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcsazzaad.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shuidangran.top/Article/details/gtvpsnkwlm.html

Common Programming Examples Cheat Book
来源：http://dali.redwolf501.top/Article/details/gtbqnsaavp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmytltloe.html

【收录内容】
来源：http://dali.jianghu66.top/Article/details/gtnxfxthgj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jinqigufen.top/Article/details/gtcvjrtwfp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.wangdashe.top/Article/details/gtqolgamgh.html

SQL · Bash · C · C++
来源：http://dali.hysaishi.cn/Article/details/gtacxetwrh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yangfankeji.com/Article/details/gtyhognpng.html

【使用说明】
来源：http://dali.daria6918.cn/Article/details/gtcvyuryib.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.ydzc1.top/Article/details/gtqxbswizz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.9152youxi.cn/Article/details/gtpinpdlog.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gtjunxgvry.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zdqjudy.top/Article/details/gtiroilvzi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.jqgufenzy.top/Article/details/gttwfwqvrq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhengqikj.top/Article/details/gtyhbknyrx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.gogol.net.cn/Article/details/gttmflrygm.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.sysykeji.top/Article/details/gtckyuktoz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sweek.top/Article/details/gtuminwpea.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.hfpthk.cn/Article/details/gtwrliyprg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.xuetiantiany.cn/Article/details/gtjsyjwebm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.fengsongda.top/Article/details/gtiaospqrm.html

【文件统计】
来源：http://dali.iojbl.cn/Article/details/gtjmmoivkl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.andypj.xyz/Article/details/gtvzmmqfub.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtrznqmbnr.html

目  录
来源：http://dali.gaohongyu789.top/Article/details/gtqykvzxvx.html

--------------------------------------------------------------------------------
来源：http://dali.jianghu66.top/Article/details/gtrozobcmm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtpebwzizh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwoqnyxf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jianghu66.top/Article/details/gtyicwnmck.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtazgvfozd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xziqi.cn/Article/details/gtungkykzh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.cqqwz.cn/Article/details/gtnpvydjpp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.haohaochexian.top/Article/details/gttwokboxw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.daxiang520.top/Article/details/gtgtqxsspx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtvrhcxxth.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.fzhhl.top/Article/details/gtqpybfepz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gthegyntdc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsjklkdqt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtyulicewi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnplyhkp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.tanke756.top/Article/details/gtfqmbipec.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.yj202588.top/Article/details/gtkulbhptk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.bjfxy.top/Article/details/gtikkmwxuw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yanxiufei.cn/Article/details/gtftkhalwp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqweshsqa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gttpcbfwxd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdiriuhmx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmrzqoczd.html

A. 基础语法与类型
来源：http://dali.kuanghao11.cn/Article/details/gtvqkmtbla.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtwmddqmhm.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gtjkzrbsvp.html

Py:   print("Hello, World!")
来源：http://dali.shzxlz.cn/Article/details/gtutkmkxwb.html

PHP:  echo "Hello, World!";
来源：http://dali.redwolf501.top/Article/details/gtjkpxaswy.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtwkyujily.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.cashguo.top/Article/details/gthgaeuwom.html

Java: System.out.println("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtemmzrnea.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.ppjwa.cn/Article/details/gtfiqkhntr.html

Ruby: puts "Hello, World!"
来源：http://dali.smart0.xyz/Article/details/gtjrfzxrwy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.ydzc1.top/Article/details/gtzcqkwkrq.html

[A02] 变量声明与赋值
来源：http://dali.shzxlz.cn/Article/details/gtvuplijzb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pycfn.com/Article/details/gtworsmwll.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtqqdslfvt.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.xziqi.cn/Article/details/gtzbimfoky.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yongpay.top/Article/details/gtizjjnlon.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.chenzaomai.com/Article/details/gtjyeomlel.html

Go:   name := "Alex"; age := 20
来源：http://dali.guowangkeji.top/Article/details/gtzyedfldj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.daxiang520.top/Article/details/gtezvjhdsc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpzikgrq.html

[A03] 常量定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmgsyamq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.chenjidiqi.icu/Article/details/gtliksblec.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gtldyfkrev.html

JS:   const PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtpkwuqqee.html

TS:   const PI: number = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtoiigmozl.html

Java: static final double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtlvzvercp.html

Go:   const PI = 3.14159
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrtdbgps.html

Ruby: PI = 3.14159
来源：http://dali.ehwqpu.com/Article/details/gtrpdnefhl.html

C#:   const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtwugffgbg.html

[A04] 判断变量类型
来源：http://dali.yuanzhike.top/Article/details/gttzenilyy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ppjwa.cn/Article/details/gthlcbceyz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tanke756.top/Article/details/gtabalsbnd.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daxiang520.top/Article/details/gtebxbfucd.html

TS:   typeof x; x instanceof Date
来源：http://dali.shuidangran.top/Article/details/gtdgadkgag.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yuxming.cn/Article/details/gthgqdjhsw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.dashuyun.cn/Article/details/gtewpcelua.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.chenzaomai.com/Article/details/gtnjvrsjnz.html

C#:   x.GetType().Name; x is int
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruooovkh.html

[A05] 整数除法与取模
来源：http://dali.jiagoushi.top/Article/details/gtfauvmmes.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.sysykeji.top/Article/details/gtscroeeoi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.tianlin.xyz/Article/details/gtupjewaqq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.cdnleiting.top/Article/details/gtppluwedx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtkdxwokyu.html

Java: 7 / 2; 7 % 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclcqbmlj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zdqjudy.top/Article/details/gtxfzycffq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.cucudq.cn/Article/details/gtmrsxvhck.html

C#:   7 / 2; 7 % 2
来源：http://dali.yuxming.cn/Article/details/gtijrbiixn.html

[A06] 字符串转数字
来源：http://dali.cqqwz.cn/Article/details/gtcedxuaeo.html

Py:   int("42"); float("3.14")
来源：http://dali.yuxming.cn/Article/details/gtkkqbulsw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzauopdj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.snrcjt.cn/Article/details/gtgmknzceq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.hammf.cn/Article/details/gtqrbyjnfi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.daxiang520.top/Article/details/gtyugbhxpd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhengqikj.top/Article/details/gtbeprqtuu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zdqjudy.top/Article/details/gtuhxltzap.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.0kj1m.cn/Article/details/gttvbjmwfo.html

[A07] 数字转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtspydktoc.html

Py:   str(42)
来源：http://dali.gzhubu.top/Article/details/gtwrawvlnc.html

PHP:  (string) 42; strval(42)
来源：http://dali.hongshengwenyu.top/Article/details/gtznxwutat.html

JS:   String(42); (42).toString()
来源：http://dali.zdqjudy.top/Article/details/gtusrnxzpl.html

TS:   String(42)
来源：http://dali.chenlongwang.top/Article/details/gtbwjqciwk.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zdqjudy.top/Article/details/gtlyrdsxfc.html

Go:   strconv.Itoa(42)
来源：http://dali.dashuyun.cn/Article/details/gtqlkulqdq.html

Ruby: 42.to_s
来源：http://dali.cheryme.top/Article/details/gtycsieisq.html

C#:   42.ToString()
来源：http://dali.jlsjyb.cn/Article/details/gtkehcsbif.html

[A08] 取整与四舍五入
来源：http://dali.vqdsnc.cn/Article/details/gtdgwjblsx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtkwhhdfkr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.hnqzz.top/Article/details/gtxsooilyc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.gogol.net.cn/Article/details/gtnaxtuhdt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shangyingyoupin.top/Article/details/gtknpwkbik.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gtrqyjmljc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gtnbnzbcjo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.gotoacloud.top/Article/details/gtxmxcpvva.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.dashuyun.cn/Article/details/gthblqwqav.html

[A09] 绝对值与最大最小值
来源：http://dali.fzhhl.top/Article/details/gtbwseifso.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtleevwbfe.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfvrwdply.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sweek.top/Article/details/gtsrhwpdkd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpweisomx.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtqtzpobsd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gtxgtwfigv.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zycfv.cn/Article/details/gtuqkdngpo.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtnehxefhd.html

[A10] 生成随机数
来源：http://dali.wangdashe.top/Article/details/gtxbxuqqjw.html

Py:   import random; random.randint(1, 100)
来源：http://dali.gogol.net.cn/Article/details/gtjhfqsqhl.html

PHP:  random_int(1, 100);
来源：http://dali.yonumen.top/Article/details/gtdgkzigsr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangdashe.top/Article/details/gtwxnzjhmu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shuidangran.top/Article/details/gtxnddtjfj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.jinqigfzy.top/Article/details/gthyfttruc.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.yonumen.top/Article/details/gtjmijuboy.html

Ruby: rand(1..100)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcdluajv.html

C#:   new Random().Next(1, 101)
来源：http://dali.yuxming.cn/Article/details/gtnidjahmd.html

[A11] 条件表达式（三元）
来源：http://dali.chenlongwang.top/Article/details/gtmpxfednw.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.meibo888.top/Article/details/gttbwuqwkh.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtlapjcyhs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gtreutfxpk.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xinyue.icu/Article/details/gtqtajbqaq.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.jinghuilouyu.cn/Article/details/gtohnrrila.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.svipenyu.cn/Article/details/gtplhwljff.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtklsnpvxy.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.mhx1999.top/Article/details/gtxusbybjz.html

[A12] 字符串插值 / 格式化
来源：http://dali.hywenlv.cn/Article/details/gttjcudjoc.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.svipenyu.cn/Article/details/gtednbgtxl.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.kuanghao11.cn/Article/details/gtkhrtejfy.html

JS:   `Hello, ${name}!`
来源：http://dali.9152youxi.cn/Article/details/gtlgwgtcge.html

TS:   `Hello, ${name}!`
来源：http://dali.fengsongda.top/Article/details/gtttqbaytf.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.xuanzx.com/Article/details/gtiutisgje.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.shuidangran.top/Article/details/gtkhxybpir.html

Ruby: "Hello, #{name}!"
来源：http://dali.ybcxt.top/Article/details/gtjkeqprmt.html

C#:   $"Hello, {name}!"
来源：http://dali.ydzc1.top/Article/details/gtorgtkczy.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.c1oappe.top/Article/details/gttbldvfgb.html

Py:   "第一行\n第二行"
来源：http://dali.zhixingplan.top/Article/details/gtwjqzqaev.html

PHP:  "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gtlvqzrwqf.html

JS:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtgcwacujf.html

TS:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gthkxsnjwu.html

Java: "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtwooiogtf.html

Go:   "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtbgblmber.html

Ruby: "第一行\n第二行"
来源：http://dali.hnqzz.top/Article/details/gtzfvwzzdn.html

C#:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtsosrecax.html


<!-- 参考信息 -->