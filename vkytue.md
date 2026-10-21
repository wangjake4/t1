代发 wailian999

[U79] PHP：静态分析
来源：http://dali.zhoulong.xyz/Article/details/gterzlnyqk.html

composer require --dev phpstan/phpstan
来源：http://dali.0kj1m.cn/Article/details/gtdvjrbjyz.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtwgpfaaej.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.daxiang520.top/Article/details/gtsmkxhxkz.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gtcrsczfqi.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtoigotwmg.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gthmcexplk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.havefunace.top/Article/details/gtzpscczaz.html

[U83] JS：ES Module 导入导出
来源：http://dali.daria6918.cn/Article/details/gtwhveqbud.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvijixqz.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gtgqcbvppr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gtbetsqdaz.html

[U85] JS：可选链
来源：http://dali.aibaodan.cn/Article/details/gttgxhjnnh.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtgsyptedg.html

[U86] JS：空值合并
来源：http://dali.pycfn.com/Article/details/gturnkjabt.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gtmntyujyy.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gtjxwxovph.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj20258.top/Article/details/gtsgbkroxv.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gttvcojtgl.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gtgvtzlybs.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gtswoyloft.html

[...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtnludqpse.html

[U90] JS：数字数组排序
来源：http://dali.mhx1999.top/Article/details/gtfkfsnolp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtjfynjowe.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gtueelikwq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daxiang520.top/Article/details/gttvxlaryf.html

[U92] JS：深拷贝
来源：http://dali.xylfe.cn/Article/details/gtkimeumqv.html

structuredClone(obj)
来源：http://dali.haohaochexian.top/Article/details/gtgyxvisbf.html

[U93] JS：模板字符串
来源：http://dali.0kj1m.cn/Article/details/gtuuqgxxvu.html

`共 ${n} 条`
来源：http://dali.xylfe.cn/Article/details/gtqsnsgxkq.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtycvprxse.html

const double = x => x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtdtubnpzd.html

[U95] JS：Promise 包装
来源：http://dali.jlsjyb.cn/Article/details/gtxpzfaqpk.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gthwwrwcjy.html

[U96] JS：async/await 与异常
来源：http://dali.nanxuanxn.top/Article/details/gtofhkfune.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtpdmhpovp.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gtbsparyqd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ybcxt.top/Article/details/gtbgijefet.html

[U98] JS：fetch 带 JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijxisqzf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.cqqwz.cn/Article/details/gthjflaipk.html

[U99] JS：事件监听
来源：http://dali.sysykeji.top/Article/details/gtvyulnnkd.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtnqrziipq.html

[U100] JS：DOM 查询
来源：http://dali.guowangkeji.top/Article/details/gthwzwjndu.html

document.querySelector(".item")
来源：http://dali.ydzc1.top/Article/details/gtpejnbvpo.html

[U101] JS：classList 操作
来源：http://dali.wangshuangyany.cn/Article/details/gtawoopswi.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttamnkeht.html

[U102] JS：本地存储
来源：http://dali.hfpthk.cn/Article/details/gtzzvemkmf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtoqzqcntx.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtwdjyqiyt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gtyafgxrvt.html

[U104] JS：防抖
来源：http://dali.chenzaomai.com/Article/details/gtnvtgcolp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gteutssvtg.html

[U105] JS：节流
来源：http://dali.jqgfzy.top/Article/details/gtrjkdxtrj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.smart0.xyz/Article/details/gtfqhawyhv.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtjgmjuofr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258.top/Article/details/gtmasvxgez.html

[U107] JS：数字千分位
来源：http://dali.aibaodan.cn/Article/details/gtydloxwhm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtkkyxkuug.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gtivebeofs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gtndwivaoo.html

[U109] JS：数组分组
来源：http://dali.zhiwuduotai.top/Article/details/gthmjxitza.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtyptjkocg.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtxlsengin.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gtyrfswtsj.html

[U111] JS：对象转 Map
来源：http://dali.jlsjyb.cn/Article/details/gtyazqtmgf.html

new Map(Object.entries(obj))
来源：http://dali.quarkkingdee.top/Article/details/gthiyovusk.html

[U112] JS：字符串补位
来源：http://dali.hnxiangtu.top/Article/details/gtzhdeprbv.html

"7".padStart(3, "0")
来源：http://dali.daria6918.cn/Article/details/gtoxvesfqd.html

[U113] JS：正则替换全部
来源：http://dali.jinqigfzy.top/Article/details/gtdfwcuzqu.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtyjrnrlkb.html

[U114] JS：JSON 深比较
来源：http://dali.bjfxy.top/Article/details/gtybpecgam.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtybnnoqzt.html

[U115] JS：生成 UUID
来源：http://dali.hammf.cn/Article/details/gthrsfgcza.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtbzdeewgg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gtehgrnoyl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aibaodan.cn/Article/details/gtpfiembxf.html

[U117] JS：单元测试
来源：http://dali.gotoacloud.top/Article/details/gttsvqvrdn.html

npm i -D vitest;  npx vitest
来源：http://dali.yongpay.top/Article/details/gttflunyms.html

[U118] JS：开发服务器
来源：http://dali.dashuyun.cn/Article/details/gtmvwbnuup.html

npm i -D vite;  npx vite
来源：http://dali.wangshuangyany.cn/Article/details/gtnaskbuqn.html

[U119] JS：生产构建
来源：http://dali.tanke756.top/Article/details/gtfznuivcq.html

npx vite build
来源：http://dali.xinyue.icu/Article/details/gtpfupevvq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gtzkykajpd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gtxvkwitjm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtywqilyjz.html

统计汇总
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrcbvdqp.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtsndrjjbv.html

按语言统计（条）：
来源：http://dali.hnqzz.top/Article/details/gtqiyacnwx.html

Python ......... 252
来源：http://dali.hongshengwenyu.top/Article/details/gtrmwcsrbl.html

PHP ............ 252
来源：http://dali.c1oappe.top/Article/details/gtqoxwjfrj.html

JavaScript ..... 252
来源：http://dali.birdmap.top/Article/details/gtcwiltxju.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gtwaculvxj.html

Java ........... 212
来源：http://dali.aizwys.cn/Article/details/gtgcpxdkog.html

Go ............. 212
来源：http://dali.dianchejie.cn/Article/details/gtokaamacr.html

Ruby ........... 212
来源：http://dali.jiagoushi.top/Article/details/gtbyuyvprf.html

C# ............. 212
来源：http://dali.nwbrower.top/Article/details/gtrlsymvnu.html

C .............. 30
来源：http://dali.shuidangran.top/Article/details/gtgciquuar.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gtzeavzebg.html

SQL ............ 90
来源：http://dali.zhoulong.xyz/Article/details/gtwjtufwao.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtsynyrdss.html

Kotlin ......... 15
来源：http://dali.wangshuangyany.cn/Article/details/gtqptxfkqk.html

Swift .......... 15
来源：http://dali.cheryme.top/Article/details/gtcjhtdwto.html

Lua ............ 10
来源：http://dali.jiagoushi.top/Article/details/gtkbvzqewb.html

Perl ........... 10
来源：http://dali.xuanzx.com/Article/details/gtafsmihrl.html

Scala .......... 10
来源：http://dali.fzhhl.top/Article/details/gtqpiudgey.html

------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gtwzigtqec.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtpnbnsmgg.html

按章节统计：
来源：http://dali.havefunace.top/Article/details/gthllecjfn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hongshengwenyu.top/Article/details/gtllopshol.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpvapaue.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gthyqtmvpz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtnffqbsps.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.redwolf501.top/Article/details/gthgayknzo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shuidangran.top/Article/details/gtffhcuyei.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hywenlv.cn/Article/details/gtdfzqmiaf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gtjwcwbycx.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yangfankeji.com/Article/details/gtynafptpl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtsdonoglq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtxftlqizq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtyvtjaiiz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jqgfzy.top/Article/details/gttetcsbug.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtnumkdlns.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.haohaochexian.top/Article/details/gtxapsncgm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gthhggpyov.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtovbifaap.html

R Bash 专题                             80
来源：http://dali.andypj.xyz/Article/details/gtvmwuxddy.html

S C / C++ 专题                          60
来源：http://dali.shangyingyoupin.top/Article/details/gtsmipbnxc.html

T 其他语言补充                          60
来源：http://dali.gzhubu.top/Article/details/gtgdcosojf.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gtwxoyzizb.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gthocjecdc.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gtogzzonuj.html

--------------------------------------------------------------------------------
来源：http://dali.guowangkeji.top/Article/details/gtbvjcuxxt.html

使用提醒
来源：http://dali.cheryme.top/Article/details/gtjihdbonj.html

--------------------------------------------------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtwxfcjpes.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.bjfxy.top/Article/details/gtuadmxsfw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tianlin.xyz/Article/details/gtcxgvvpxr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jyoumei.cn/Article/details/gtctrapwjf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmkghgml.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gtcuffktdm.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtallcodar.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthnjkcssk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aizwys.cn/Article/details/gtfojfwsvg.html

Common Programming Examples Cheat Book
来源：http://dali.fzhhl.top/Article/details/gtpbplpwyi.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzveyuaby.html

【收录内容】
来源：http://dali.havefunace.top/Article/details/gtduedvzao.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.gotoacloud.top/Article/details/gtuiuozxvr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.vqdsnc.cn/Article/details/gtwchxdcgp.html

SQL · Bash · C · C++
来源：http://dali.yvedp.cn/Article/details/gtzmezqjgd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.dianchejie.cn/Article/details/gtcvzliipi.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gtpkscrqef.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hongshengwenyu.top/Article/details/gtrwjsmujg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.pengpengdd.cyou/Article/details/gtaegukuyp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.guowangkeji.top/Article/details/gtrokbfmoj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yangfankeji.com/Article/details/gtgzthmcgt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.yj20258888.top/Article/details/gtitfgvrgu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.sweek.top/Article/details/gtliltmkzj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.ppjwa.cn/Article/details/gtdmvrvwbe.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhengqikj.top/Article/details/gtkkeegiea.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.sysykeji.top/Article/details/gtpkbefovd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.wangshuangyany.cn/Article/details/gtymqoebno.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.tian-w.cn/Article/details/gtizpmfwit.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.316326.xyz/Article/details/gtbrsirgqg.html

【文件统计】
来源：http://dali.cashguo.top/Article/details/gtffdvgxaj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.meibo888.top/Article/details/gtnlpictol.html

--------------------------------------------------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtcefhxbqm.html

目  录
来源：http://dali.hnxiangtu.top/Article/details/gtlbzhoygk.html

--------------------------------------------------------------------------------
来源：http://dali.yonumen.top/Article/details/gtcnlnkbky.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtqlkpiacp.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtusmwfkvk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guowangkeji.top/Article/details/gtgofplkkc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.xziqi.cn/Article/details/gtzatgskzi.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jyoumei.cn/Article/details/gteabhpzqb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtruwkcwah.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxkydzwg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.gotoacloud.top/Article/details/gtmemwzaes.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.dashuyun.cn/Article/details/gtqrgiqkmm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.andypj.xyz/Article/details/gtymnvcecg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekogexdi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zycfv.cn/Article/details/gtplhtefny.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtrfibcsty.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.sysykeji.top/Article/details/gtitihrtaf.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.cheryme.top/Article/details/gtzzgmazsr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkzzfqyz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtzmchhwex.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.dianchejie.cn/Article/details/gtsbwuzvzl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.aizwys.cn/Article/details/gtyuwisdmg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtgpdydjwq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtwwqkesie.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtlrolpbie.html

A. 基础语法与类型
来源：http://dali.yongpay.top/Article/details/gtkpmbvdxf.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtgfnsswof.html

[A01] Hello World
来源：http://dali.cqqwz.cn/Article/details/gtrnfvkzur.html

Py:   print("Hello, World!")
来源：http://dali.jinqigufen.top/Article/details/gtibcmmnfl.html

PHP:  echo "Hello, World!";
来源：http://dali.cucudq.cn/Article/details/gtwfklxrmx.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtgeyhxxkj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.daxiang520.top/Article/details/gtgaavdyns.html

Java: System.out.println("Hello, World!");
来源：http://dali.yj20258.top/Article/details/gtmrqgpfbw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gtnvhdzsze.html

Ruby: puts "Hello, World!"
来源：http://dali.mhx1999.top/Article/details/gtiytknymy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikexwwyf.html

[A02] 变量声明与赋值
来源：http://dali.shangyingyoupin.top/Article/details/gtkxpuczde.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddowiauo.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhiwuduotai.top/Article/details/gtgkcofppf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnqzz.top/Article/details/gtkykazrqk.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.jiagoushi.top/Article/details/gtulbgcrmm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.snrcjt.cn/Article/details/gtqhkvywto.html

Go:   name := "Alex"; age := 20
来源：http://dali.quarkkingdee.top/Article/details/gtqsohsbrj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258.top/Article/details/gtjuacsfqp.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.guowangkeji.top/Article/details/gtjcjqxylf.html

[A03] 常量定义
来源：http://dali.chenjidiqi.icu/Article/details/gtjalvxugt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jqgfzy.top/Article/details/gtfjkbgsqe.html

PHP:  const PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtledqxday.html

JS:   const PI = 3.14159;
来源：http://dali.xuetiantiany.cn/Article/details/gtqmnzcedd.html

TS:   const PI: number = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtaukixqhk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtzjnyowra.html

Go:   const PI = 3.14159
来源：http://dali.fengsongda.top/Article/details/gtqfewukcw.html

Ruby: PI = 3.14159
来源：http://dali.daxiang520.top/Article/details/gtowuvbakn.html

C#:   const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypogdeon.html

[A04] 判断变量类型
来源：http://dali.ybcxt.top/Article/details/gtxxmlufcw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cdnleiting.top/Article/details/gtshhpluut.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.shuidangran.top/Article/details/gtfxpnstey.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.meibo888.top/Article/details/gtntnbsgfu.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj202588.top/Article/details/gtnbjwudbn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.xuetiantiany.cn/Article/details/gtopltclwg.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.jinqigfzy.top/Article/details/gtyifkvlos.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.yj202588.top/Article/details/gtcbtdjtnx.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhixingplan.top/Article/details/gtgljixpan.html

[A05] 整数除法与取模
来源：http://dali.yangfankeji.com/Article/details/gtsrgufgcz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.daxiang520.top/Article/details/gtppcxzpff.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.havefunace.top/Article/details/gtqmavwegj.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.aibaodan.cn/Article/details/gteukpdmac.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.tian-w.cn/Article/details/gtkkcnpdeg.html

Java: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtdazwpxcs.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gtlucokimv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.pengpengdd.cyou/Article/details/gtjkdushus.html

C#:   7 / 2; 7 % 2
来源：http://dali.hysaishi.cn/Article/details/gttviswzrx.html

[A06] 字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtfcvqijcs.html

Py:   int("42"); float("3.14")
来源：http://dali.shzxlz.cn/Article/details/gtxspmukwe.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.dashuyun.cn/Article/details/gtufzjtfgx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cucudq.cn/Article/details/gttqdmdaop.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gtxmtlturi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.pycfn.com/Article/details/gtxosciuwn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.yj202588.top/Article/details/gtcjggrmao.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.nanxuanxn.top/Article/details/gtvupavnxt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.jinghuilouyu.cn/Article/details/gtizwwyrwp.html

[A07] 数字转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtastisgaf.html

Py:   str(42)
来源：http://dali.xuetiantiany.cn/Article/details/gtkrhjexha.html

PHP:  (string) 42; strval(42)
来源：http://dali.ybcxt.top/Article/details/gtzinuweyt.html

JS:   String(42); (42).toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtbsnmwqle.html

TS:   String(42)
来源：http://dali.dianchejie.cn/Article/details/gtyiivofhr.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.yonumen.top/Article/details/gtcxdavchg.html

Go:   strconv.Itoa(42)
来源：http://dali.fengsongda.top/Article/details/gtbogkimae.html

Ruby: 42.to_s
来源：http://dali.316326.xyz/Article/details/gtvysniceq.html

C#:   42.ToString()
来源：http://dali.redwolf501.top/Article/details/gtmeexgktw.html

[A08] 取整与四舍五入
来源：http://dali.xylfe.cn/Article/details/gtdfnwuxsr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yvedp.cn/Article/details/gtfjifskff.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuxming.cn/Article/details/gtgzhbwcfe.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.aibaodan.cn/Article/details/gtnkebpwau.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shuidangran.top/Article/details/gtrcknvyjz.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.dianchejie.cn/Article/details/gteabglhjn.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.yongpay.top/Article/details/gtzprghuol.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zdqjudy.top/Article/details/gtpcnidkll.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.daria6918.cn/Article/details/gteogqxeax.html

[A09] 绝对值与最大最小值
来源：http://dali.aibaodan.cn/Article/details/gtgaqhfext.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcfzbmhmn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtxkpvwzej.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcowzzigd.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtiocdypuu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtsbpucvtz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.gaohongyu789.top/Article/details/gtzbahiapt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.yueranfly.top/Article/details/gtpvkkkulg.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtbdpncxxr.html

[A10] 生成随机数
来源：http://dali.pengpengdd.cyou/Article/details/gtuvjnyjdz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.guannengcc.top/Article/details/gtlajxqpgg.html

PHP:  random_int(1, 100);
来源：http://dali.sufxvd.cn/Article/details/gtzwposdqt.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjazxpadt.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zdqjudy.top/Article/details/gtkstvabct.html

Java: new Random().nextInt(100) + 1
来源：http://dali.yj20258.top/Article/details/gtmofvthew.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.haohaochexian.top/Article/details/gtxdfbjplh.html

Ruby: rand(1..100)
来源：http://dali.gogol.net.cn/Article/details/gtdyzbksam.html

C#:   new Random().Next(1, 101)
来源：http://dali.yj20258.top/Article/details/gtqqnmnefi.html

[A11] 条件表达式（三元）
来源：http://dali.cdnleiting.top/Article/details/gtitzrkvjl.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.haohaochexian.top/Article/details/gtdyekleul.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.gaohongyu789.top/Article/details/gtsfmktauw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtigoeoeog.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtiqjqxphi.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.bjfxy.top/Article/details/gtsxqpqfth.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxqgpunc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.aizwys.cn/Article/details/gtxfnquxln.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gtciwdahxa.html

[A12] 字符串插值 / 格式化
来源：http://dali.jinqigufen.top/Article/details/gtpctrufdm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzofkhuo.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.snrcjt.cn/Article/details/gttzcxjnuc.html

JS:   `Hello, ${name}!`
来源：http://dali.yj202588.top/Article/details/gtigecqnuy.html

TS:   `Hello, ${name}!`
来源：http://dali.quarkkingdee.top/Article/details/gtsqmvgtbp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.haohaochexian.top/Article/details/gtnvrpaeel.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyohyousn.html

Ruby: "Hello, #{name}!"
来源：http://dali.hammf.cn/Article/details/gtqzrwacqb.html

C#:   $"Hello, {name}!"
来源：http://dali.jiagoushi.top/Article/details/gtlzsqttol.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.nwbrower.top/Article/details/gtbsnhkckv.html


<!-- 参考信息 -->