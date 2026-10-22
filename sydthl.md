代发 wailian999

[U79] PHP：静态分析
来源：http://dali.jyoumei.cn/Article/details/gtdjvldcbn.html

composer require --dev phpstan/phpstan
来源：http://dali.cheryme.top/Article/details/gtvmwzpexz.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtbywscloy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gtrfotaiqa.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtjzobaefq.html

npm init -y;  npm i express
来源：http://dali.jinghuilouyu.cn/Article/details/gtglzvgupu.html

[U82] JS：package.json 脚本
来源：http://dali.shangyingyoupin.top/Article/details/gtqxkhjmkx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yvedp.cn/Article/details/gtxgummehk.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gteudcflmr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtuduwaelu.html

[U84] JS：CommonJS 写法
来源：http://dali.havefunace.top/Article/details/gtidfzhbgk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.haohaochexian.top/Article/details/gtdwvjpauz.html

[U85] JS：可选链
来源：http://dali.hfpthk.cn/Article/details/gtopkoipbr.html

a?.b?.c
来源：http://dali.gogol.net.cn/Article/details/gtzgajdtrn.html

[U86] JS：空值合并
来源：http://dali.shzxlz.cn/Article/details/gtaxadkzon.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gtjwkvfqzv.html

[U87] JS：解构默认值
来源：http://dali.cqqwz.cn/Article/details/gthwbjclut.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcodgnmox.html

[U88] JS：对象展开合并
来源：http://dali.chenzaomai.com/Article/details/gtcpsnsjmo.html

{ ...a, ...b }
来源：http://dali.hnqzz.top/Article/details/gtwrrupkaz.html

[U89] JS：数组去重
来源：http://dali.yuanzhike.top/Article/details/gtrjdvnlfx.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtdlnaghoo.html

[U90] JS：数字数组排序
来源：http://dali.feifeiyinyue.top/Article/details/gtfseqnzyq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gthjznhxfg.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gtlotzechl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.9152youxi.cn/Article/details/gtmjcorucc.html

[U92] JS：深拷贝
来源：http://dali.c1oappe.top/Article/details/gtzphlabfd.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtbngxoixu.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtpynuwozu.html

`共 ${n} 条`
来源：http://dali.yj20258.top/Article/details/gtduuxifoe.html

[U94] JS：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtbwbmridp.html

const double = x => x * 2;
来源：http://dali.hammf.cn/Article/details/gtadwhhtrr.html

[U95] JS：Promise 包装
来源：http://dali.jinqigufen.top/Article/details/gtopuddiuz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhiwuduotai.top/Article/details/gtrcgqlpyj.html

[U96] JS：async/await 与异常
来源：http://dali.yueranfly.top/Article/details/gtvngbmqtt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtypdgdtek.html

[U97] JS：并发请求
来源：http://dali.sufxvd.cn/Article/details/gtfathqovk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtcnqbehql.html

[U98] JS：fetch 带 JSON
来源：http://dali.xinyue.icu/Article/details/gtvoqzlwkg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gtehoghkqk.html

[U99] JS：事件监听
来源：http://dali.daria6918.cn/Article/details/gtfbkbzuyk.html

el.addEventListener("click", e => {})
来源：http://dali.yj20258.top/Article/details/gtdgnlckau.html

[U100] JS：DOM 查询
来源：http://dali.yongpay.top/Article/details/gtxfkbwuff.html

document.querySelector(".item")
来源：http://dali.xylfe.cn/Article/details/gteymrubcn.html

[U101] JS：classList 操作
来源：http://dali.aizwys.cn/Article/details/gtnwqeawji.html

el.classList.toggle("active")
来源：http://dali.zhongyouzk.top/Article/details/gtonxxfmve.html

[U102] JS：本地存储
来源：http://dali.kuanghao11.cn/Article/details/gtcrgetwyl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guowangkeji.top/Article/details/gtafepyifm.html

[U103] JS：定时器
来源：http://dali.xuanzx.com/Article/details/gtebtxeqpl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.sufxvd.cn/Article/details/gtrgnajqch.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtyxglgtld.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtwuljcsdh.html

[U105] JS：节流
来源：http://dali.daria6918.cn/Article/details/gtwpcfgmno.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cqqwz.cn/Article/details/gtigbferor.html

[U106] JS：日期格式化
来源：http://dali.pycfn.com/Article/details/gtmdvhpwkg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhoulong.xyz/Article/details/gtdgqlscfp.html

[U107] JS：数字千分位
来源：http://dali.jqgufenzy.top/Article/details/gtxstljlgu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtyhcvvusr.html

[U108] JS：随机整数
来源：http://dali.andypj.xyz/Article/details/gtpyybwexa.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guowangkeji.top/Article/details/gtpjkaddrd.html

[U109] JS：数组分组
来源：http://dali.zhixingplan.top/Article/details/gtrbztqlxa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhixingplan.top/Article/details/gtarhfeyej.html

[U110] JS：数组分块
来源：http://dali.redwolf501.top/Article/details/gtbfdqegih.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gttgjngvvf.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtutrxqygz.html

new Map(Object.entries(obj))
来源：http://dali.zhongyouzk.top/Article/details/gtdsskfxvz.html

[U112] JS：字符串补位
来源：http://dali.chenjidiqi.icu/Article/details/gtrzhltvwn.html

"7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gtlzendbkr.html

[U113] JS：正则替换全部
来源：http://dali.316326.xyz/Article/details/gtmkmijptg.html

s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtltxmotdb.html

[U114] JS：JSON 深比较
来源：http://dali.cheryme.top/Article/details/gtltboskbo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtqspqfbrn.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtpxyhlctx.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtzfvjkxqg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hongshengwenyu.top/Article/details/gtztrgyajv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xinyue.icu/Article/details/gtxnvzvnko.html

[U117] JS：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtncxpwsqn.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtzojklyes.html

[U118] JS：开发服务器
来源：http://dali.feifeiyinyue.top/Article/details/gtsefjcjmn.html

npm i -D vite;  npx vite
来源：http://dali.cucudq.cn/Article/details/gtzitbpjun.html

[U119] JS：生产构建
来源：http://dali.9152youxi.cn/Article/details/gtdgaoalmn.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjzpctuu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gaohongyu789.top/Article/details/gtqgunrtfk.html

import.meta.env.VITE_API_URL
来源：http://dali.aibaodan.cn/Article/details/gtsxnrwcsg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtwtfzirwg.html

统计汇总
来源：http://dali.mhx1999.top/Article/details/gtwhsvvlxr.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtorrvsfil.html

按语言统计（条）：
来源：http://dali.aibaodan.cn/Article/details/gtgzpkpuha.html

Python ......... 252
来源：http://dali.aizwys.cn/Article/details/gtmaehkqxo.html

PHP ............ 252
来源：http://dali.shangyingyoupin.top/Article/details/gtydatlfen.html

JavaScript ..... 252
来源：http://dali.hywenlv.cn/Article/details/gtbhzomina.html

TypeScript ..... 212
来源：http://dali.cqqwz.cn/Article/details/gtmwllprcz.html

Java ........... 212
来源：http://dali.wangdashe.top/Article/details/gtksddgmkv.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtoigsicyv.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gtqzqbfiql.html

C# ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtlayydjjx.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gthpnebqaj.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gtogarxrkl.html

SQL ............ 90
来源：http://dali.smart0.xyz/Article/details/gtnlxycpmq.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gtxnbmfhas.html

Kotlin ......... 15
来源：http://dali.haohaochexian.top/Article/details/gtgwmkckly.html

Swift .......... 15
来源：http://dali.vqdsnc.cn/Article/details/gtyfmmercc.html

Lua ............ 10
来源：http://dali.daria6918.cn/Article/details/gtnozyuowm.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gttklkmkbr.html

Scala .......... 10
来源：http://dali.sufxvd.cn/Article/details/gtyaxmbuqy.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtoofvdjdc.html

合计 ........... 2106 条
来源：http://dali.ybcxt.top/Article/details/gtrymoxlmg.html

按章节统计：
来源：http://dali.yuxming.cn/Article/details/gtpdznvwmu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.chenzaomai.com/Article/details/gtyjujjnsn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.smart0.xyz/Article/details/gtkoaynbyw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gtsvqfhuly.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxshrejgw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gtrdgvitha.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cucudq.cn/Article/details/gtayffpeew.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtouydtcmm.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtbmdwalvt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.316326.xyz/Article/details/gtjdxgxiaa.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hammf.cn/Article/details/gtzhkbwsbp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gttmtaqibp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtviebkaom.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.0kj1m.cn/Article/details/gtndqqpmwi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.0kj1m.cn/Article/details/gtmcjawphb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jqgfzy.top/Article/details/gtlkmpoqai.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtyockpmve.html

Q SQL 专题                              90
来源：http://dali.jlsjyb.cn/Article/details/gtpsqyqqvv.html

R Bash 专题                             80
来源：http://dali.ybcxt.top/Article/details/gtzwhqctnk.html

S C / C++ 专题                          60
来源：http://dali.chenjidiqi.icu/Article/details/gtshglvwiz.html

T 其他语言补充                          60
来源：http://dali.sufxvd.cn/Article/details/gtrivpjfaa.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gtgeubseme.html

------------------------------------
来源：http://dali.zhixingplan.top/Article/details/gtbvkjaapl.html

合计                                  2106 条
来源：http://dali.nanxinkj.top/Article/details/gtvplmvhza.html

--------------------------------------------------------------------------------
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzkcgwus.html

使用提醒
来源：http://dali.tanke756.top/Article/details/gtsdnacylc.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtxvwwevia.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gtaxklempv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.wangdashe.top/Article/details/gtdsqencyc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.nanxuanxn.top/Article/details/gthndsfmuq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.shzxlz.cn/Article/details/gtgtftsgey.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258888.top/Article/details/gtlrdzyzss.html

—— 文件结束 ——
来源：http://dali.guannengcc.top/Article/details/gtxefobqph.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttaudzyeb.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.nanxuanxn.top/Article/details/gtyehdmpsc.html

Common Programming Examples Cheat Book
来源：http://dali.jqgufenzy.top/Article/details/gttokmxshq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtictalmxf.html

【收录内容】
来源：http://dali.ybcxt.top/Article/details/gtqpzkaoso.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xuanzx.com/Article/details/gthmzzhiif.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.9152youxi.cn/Article/details/gtntyywvqq.html

SQL · Bash · C · C++
来源：http://dali.xziqi.cn/Article/details/gtynzcgbcl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.jinqigfzy.top/Article/details/gtkcvgwkxk.html

【使用说明】
来源：http://dali.dashuyun.cn/Article/details/gtqejcdgif.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.jqgufenzy.top/Article/details/gteerxfbvo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.quarkkingdee.top/Article/details/gtuglccumi.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.meibo888.top/Article/details/gttudmufnt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.xinyue.icu/Article/details/gtbyomcqcj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.haohaochexian.top/Article/details/gtfsfaphxt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.daxiang520.top/Article/details/gtanvolhvf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.cqqwz.cn/Article/details/gtobjobhlk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gtpqfnzeys.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcptcwkbd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqympskx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.iojbl.cn/Article/details/gtsdezbcms.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.redwolf501.top/Article/details/gtsxpkgrsf.html

【文件统计】
来源：http://dali.jianghu66.top/Article/details/gtcofubtff.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.xuanzx.com/Article/details/gthhqkwuvm.html

--------------------------------------------------------------------------------
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmcgcyxk.html

目  录
来源：http://dali.hfpthk.cn/Article/details/gtapckesvl.html

--------------------------------------------------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtqccsgsma.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.yueranfly.top/Article/details/gthdtrnzic.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhoulong.xyz/Article/details/gtnxcbwbww.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jyoumei.cn/Article/details/gtkccehdao.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.nanxinkj.top/Article/details/gtkamsfzml.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.cqqwz.cn/Article/details/gticonlnih.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.xylfe.cn/Article/details/gtzinmwvmp.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtotvofdth.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.guowangkeji.top/Article/details/gtzscumedz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.wangdashe.top/Article/details/gtwssruofg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.shzxlz.cn/Article/details/gtarkcqbda.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.hnqzz.top/Article/details/gthwhgkbng.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.meibo888.top/Article/details/gtbflqjczn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.yvedp.cn/Article/details/gtovpiggdg.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cucudq.cn/Article/details/gtkxdsrfyp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcjovbes.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.nanxuanxn.top/Article/details/gtibaokkfi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yj20258888.top/Article/details/gtvzpqdzgs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.fengsongda.top/Article/details/gtworuzgap.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxcrqghp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gttpgjvmfy.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtgdgggodb.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdlredboz.html

A. 基础语法与类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzmjvcjtv.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnuflfqpt.html

[A01] Hello World
来源：http://dali.redwolf501.top/Article/details/gtgugwqyxw.html

Py:   print("Hello, World!")
来源：http://dali.shangyingyoupin.top/Article/details/gtlivqplko.html

PHP:  echo "Hello, World!";
来源：http://dali.gzhubu.top/Article/details/gtdvfzarex.html

JS:   console.log("Hello, World!");
来源：http://dali.havefunace.top/Article/details/gtocegphup.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.ppjwa.cn/Article/details/gtgwjfycyy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhiwuduotai.top/Article/details/gtvujupoec.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gtxhxwhnpz.html

Ruby: puts "Hello, World!"
来源：http://dali.feifeiyinyue.top/Article/details/gtyjhtjfmf.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.fengsongda.top/Article/details/gthtetlogm.html

[A02] 变量声明与赋值
来源：http://dali.jiagoushi.top/Article/details/gtfxitcwuk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.gaohongyu789.top/Article/details/gthwrfqcpu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxthwgrm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.shuidangran.top/Article/details/gtpysbitwr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.aibaodan.cn/Article/details/gtlexvbzsl.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.redwolf501.top/Article/details/gtyaeccsrf.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gtxtntkkvk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.pycfn.com/Article/details/gtstlhylup.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.gogol.net.cn/Article/details/gtqdwmkmgh.html

[A03] 常量定义
来源：http://dali.dashuyun.cn/Article/details/gtdtdandkg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuwgjnpz.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtemolwncc.html

JS:   const PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gthcgvxuke.html

TS:   const PI: number = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtpsbrjmtz.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtlkjmkrzo.html

Go:   const PI = 3.14159
来源：http://dali.chenzaomai.com/Article/details/gthpvakzbk.html

Ruby: PI = 3.14159
来源：http://dali.kuanghao11.cn/Article/details/gtpaamudtq.html

C#:   const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtahurawis.html

[A04] 判断变量类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzucdswrq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.yongpay.top/Article/details/gtvnketwno.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.yj202588.top/Article/details/gtvyhenveu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.fengsongda.top/Article/details/gtopfisipl.html

TS:   typeof x; x instanceof Date
来源：http://dali.yj20258.top/Article/details/gtnawlbpra.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.0kj1m.cn/Article/details/gthmenhlsb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.yj20258.top/Article/details/gthwqyfsbt.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jianghu66.top/Article/details/gthbzgppqf.html

C#:   x.GetType().Name; x is int
来源：http://dali.iojbl.cn/Article/details/gtbrckcvgb.html

[A05] 整数除法与取模
来源：http://dali.hysaishi.cn/Article/details/gtbalohbjz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.vqdsnc.cn/Article/details/gteynyevti.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtblzlloac.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtkjgggqwy.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtepsxlfxi.html

Java: 7 / 2; 7 % 2
来源：http://dali.yj202588.top/Article/details/gtfxbtqqwc.html

Go:   7 / 2; 7 % 2
来源：http://dali.bjfxy.top/Article/details/gtqnlvnrbs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtykduwnyt.html

C#:   7 / 2; 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gteuizgkps.html

[A06] 字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtaigcomox.html

Py:   int("42"); float("3.14")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxyzuojm.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangdashe.top/Article/details/gtkfuyyztx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.hywenlv.cn/Article/details/gtarkcqqxf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.c1oappe.top/Article/details/gtgvpnjoil.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.wangdashe.top/Article/details/gtpoivlngk.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.fengsongda.top/Article/details/gtxtuenzoc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.jiagoushi.top/Article/details/gtpcxssjob.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.daxiang520.top/Article/details/gtcvlvogwu.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gtfvtunadn.html

Py:   str(42)
来源：http://dali.316326.xyz/Article/details/gtnvgtlump.html

PHP:  (string) 42; strval(42)
来源：http://dali.cucudq.cn/Article/details/gtmpeabxai.html

JS:   String(42); (42).toString()
来源：http://dali.jqgufenzy.top/Article/details/gtwlmjuhwr.html

TS:   String(42)
来源：http://dali.zhiwuduotai.top/Article/details/gtkadnoesq.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.cqqwz.cn/Article/details/gtjlscbdgy.html

Go:   strconv.Itoa(42)
来源：http://dali.feifeiyinyue.top/Article/details/gtwkfiwivu.html

Ruby: 42.to_s
来源：http://dali.nwbrower.top/Article/details/gtwnnmhpvb.html

C#:   42.ToString()
来源：http://dali.mhx1999.top/Article/details/gtiubuckjp.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gtsvxcnytm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.wangshuangyany.cn/Article/details/gthmvrsfsl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.fzhhl.top/Article/details/gtlltaekdy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jianghu66.top/Article/details/gtmqtcrwcv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqauplwf.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hongshengwenyu.top/Article/details/gtsmtcsqky.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.xuanzx.com/Article/details/gtfsrfwpcc.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.316326.xyz/Article/details/gtichdaqju.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.shangyingyoupin.top/Article/details/gtgukrsdtx.html

[A09] 绝对值与最大最小值
来源：http://dali.dianchejie.cn/Article/details/gtkijuvwbd.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtoaswfetx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gtpnhyggwk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yongpay.top/Article/details/gtdapetocl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtfbqnfkmm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtkuwrylmo.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.cdnleiting.top/Article/details/gtjhvjgvgu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ydzc1.top/Article/details/gtblpsplma.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtfzlndptv.html

[A10] 生成随机数
来源：http://dali.guowangkeji.top/Article/details/gtpxzrglqc.html

Py:   import random; random.randint(1, 100)
来源：http://dali.hongshengwenyu.top/Article/details/gtapxibkmx.html

PHP:  random_int(1, 100);
来源：http://dali.yj20258.top/Article/details/gtchlzphrq.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jyoumei.cn/Article/details/gtozwtjhgz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.meibo888.top/Article/details/gtuqmkizni.html

Java: new Random().nextInt(100) + 1
来源：http://dali.nwbrower.top/Article/details/gthqiwnnwd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhiwuduotai.top/Article/details/gtgqearwvk.html

Ruby: rand(1..100)
来源：http://dali.nanxinkj.top/Article/details/gtopifezif.html

C#:   new Random().Next(1, 101)
来源：http://dali.pycfn.com/Article/details/gtsyszwsuo.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gtjzytwfzr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hysaishi.cn/Article/details/gtlscmsyie.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.fzhhl.top/Article/details/gtfltgybsd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.jqgufenzy.top/Article/details/gtnxmmwoms.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigufen.top/Article/details/gtsshyhpqv.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtysydfcso.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.iojbl.cn/Article/details/gtlatksewr.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sxryk.cn/Article/details/gtjsqrkzxl.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.xuetiantiany.cn/Article/details/gtgzaknplf.html

[A12] 字符串插值 / 格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtygapvpoh.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.guannengcc.top/Article/details/gtmxwnhfrt.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.jiagoushi.top/Article/details/gtdosvackp.html

JS:   `Hello, ${name}!`
来源：http://dali.svipenyu.cn/Article/details/gtujvvaukk.html

TS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtdruemrxr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.yj20258.top/Article/details/gtomftfjfz.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.xylfe.cn/Article/details/gtudlbsddd.html

Ruby: "Hello, #{name}!"
来源：http://dali.haohaochexian.top/Article/details/gtldznuwuk.html

C#:   $"Hello, {name}!"
来源：http://dali.hnqzz.top/Article/details/gtqzcywmxi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.hongshengwenyu.top/Article/details/gtagytviem.html


<!-- 参考信息 -->