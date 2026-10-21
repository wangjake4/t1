代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.tianlin.xyz/Article/details/gtdxiisgmj.html

composer require psr/container
来源：http://dali.sysykeji.top/Article/details/gtumgjhxwi.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gtzqseeilh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gtxvsqspmb.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gtmfkuovcv.html

composer require twig/twig
来源：http://dali.tian-w.cn/Article/details/gtfuikiujo.html

[U78] PHP：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtlcgdnheu.html

composer require --dev phpunit/phpunit
来源：http://dali.yueranfly.top/Article/details/gtrmjnbdld.html

[U79] PHP：静态分析
来源：http://dali.hongshengwenyu.top/Article/details/gtvujwjlqd.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgfzy.top/Article/details/gtuixhvlcy.html

[U80] PHP：代码规范修复
来源：http://dali.daxiang520.top/Article/details/gtkngpeohq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.snrcjt.cn/Article/details/gtwkgpkztt.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gtatufuqmk.html

npm init -y;  npm i express
来源：http://dali.xuetiantiany.cn/Article/details/gtropcpluj.html

[U82] JS：package.json 脚本
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvdxrqya.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gthplnwzox.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtyfzxmuix.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtaucohjvh.html

[U84] JS：CommonJS 写法
来源：http://dali.cdnleiting.top/Article/details/gtjbtmhdgu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gtwojtbvwp.html

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gtrnxrucgc.html

a?.b?.c
来源：http://dali.shangyingyoupin.top/Article/details/gtzncqrrwa.html

[U86] JS：空值合并
来源：http://dali.guowangkeji.top/Article/details/gtlristrcv.html

a ?? b
来源：http://dali.daria6918.cn/Article/details/gtbhfedbgx.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtvnydszth.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xinyue.icu/Article/details/gtbobxtqqw.html

[U88] JS：对象展开合并
来源：http://dali.zdqjudy.top/Article/details/gtkogfpydy.html

{ ...a, ...b }
来源：http://dali.yj20258.top/Article/details/gtqfbjwtmg.html

[U89] JS：数组去重
来源：http://dali.jinqigfzy.top/Article/details/gtyfwdhrwv.html

[...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtrfqeaqdk.html

[U90] JS：数字数组排序
来源：http://dali.shangyingyoupin.top/Article/details/gtkkagqofv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gttvfgyjij.html

[U91] JS：对象键值遍历
来源：http://dali.jyoumei.cn/Article/details/gtnwcunvox.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gtulfgmgjq.html

[U92] JS：深拷贝
来源：http://dali.yvedp.cn/Article/details/gtjprdnucg.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gttesobekm.html

[U93] JS：模板字符串
来源：http://dali.zhixingplan.top/Article/details/gtrsvephzq.html

`共 ${n} 条`
来源：http://dali.nanxuanxn.top/Article/details/gtxvmftjxp.html

[U94] JS：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtwfekacja.html

const double = x => x * 2;
来源：http://dali.zhengqikj.top/Article/details/gtvuxuzkba.html

[U95] JS：Promise 包装
来源：http://dali.nanxinkj.top/Article/details/gthkbaleyx.html

new Promise((resolve, reject) => {})
来源：http://dali.haohaochexian.top/Article/details/gtyqkigyhf.html

[U96] JS：async/await 与异常
来源：http://dali.zhixingplan.top/Article/details/gtugmrgdks.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sxryk.cn/Article/details/gturajrmlz.html

[U97] JS：并发请求
来源：http://dali.dashuyun.cn/Article/details/gtsufuiway.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gtkfoorxps.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtstzhuqrh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.pycfn.com/Article/details/gtnmrzyfel.html

[U99] JS：事件监听
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgrxxynb.html

el.addEventListener("click", e => {})
来源：http://dali.jyoumei.cn/Article/details/gttgkqilww.html

[U100] JS：DOM 查询
来源：http://dali.gzhubu.top/Article/details/gtfccdfrns.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gtxfqugoqk.html

[U101] JS：classList 操作
来源：http://dali.xziqi.cn/Article/details/gthcatouhp.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gtdxksxqxn.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gtbaqkoxfc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.0kj1m.cn/Article/details/gtdbmevkof.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtfenztqhx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gtlylovbfo.html

[U104] JS：防抖
来源：http://dali.andypj.xyz/Article/details/gtpwckahsq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtlkcgvude.html

[U105] JS：节流
来源：http://dali.9152youxi.cn/Article/details/gtngeycscn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gtkgdznbpg.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gthzrzkylc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.wangdashe.top/Article/details/gtkpgkghyp.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gthxkoopyk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtsqfvacot.html

[U108] JS：随机整数
来源：http://dali.quarkkingdee.top/Article/details/gtcpsucukp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtlidshvgo.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtblnrntsb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.andypj.xyz/Article/details/gthmwsvmxd.html

[U110] JS：数组分块
来源：http://dali.hysaishi.cn/Article/details/gtvveppdtd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aibaodan.cn/Article/details/gtdsmrsnnu.html

[U111] JS：对象转 Map
来源：http://dali.zycfv.cn/Article/details/gtkoojybib.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gtexfnsibz.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gtwnfarrhh.html

"7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtymuhyjyg.html

[U113] JS：正则替换全部
来源：http://dali.andypj.xyz/Article/details/gtuprirbyr.html

s.replaceAll("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtgrfckgnd.html

[U114] JS：JSON 深比较
来源：http://dali.hfpthk.cn/Article/details/gtafnqqbjh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwvmcosq.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtuauvmkgd.html

crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtlteqfoxz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sufxvd.cn/Article/details/gtdrchuagq.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yonumen.top/Article/details/gtwgxomeez.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtcnbvkvcw.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gtfjpepwnd.html

[U118] JS：开发服务器
来源：http://dali.wangdashe.top/Article/details/gtnivizrmu.html

npm i -D vite;  npx vite
来源：http://dali.xinyue.icu/Article/details/gtsrumlbuz.html

[U119] JS：生产构建
来源：http://dali.shangyingyoupin.top/Article/details/gtzcpmhcgo.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gtfsrebcrz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gtedlfnugb.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtdszwybog.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzwlrxzhp.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gtuwerqhsr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmckqfdif.html

按语言统计（条）：
来源：http://dali.zhengqikj.top/Article/details/gtdwfddncr.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gtsiwcrgbv.html

PHP ............ 252
来源：http://dali.xuetiantiany.cn/Article/details/gtlbeemxyr.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gtesfxucjq.html

TypeScript ..... 212
来源：http://dali.gzhubu.top/Article/details/gtjqoenjkx.html

Java ........... 212
来源：http://dali.dianchejie.cn/Article/details/gtloxypzhn.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gturvwybpj.html

Ruby ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtaokzmawt.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gtvjzghzen.html

C .............. 30
来源：http://dali.havefunace.top/Article/details/gtlplvjkwg.html

C++ ............ 30
来源：http://dali.jqgufenzy.top/Article/details/gtkfhnssmi.html

SQL ............ 90
来源：http://dali.tanke756.top/Article/details/gtqoqzdwce.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gtqhhzxzcr.html

Kotlin ......... 15
来源：http://dali.hongshengwenyu.top/Article/details/gtvngygwlc.html

Swift .......... 15
来源：http://dali.sxryk.cn/Article/details/gtrscfcnfp.html

Lua ............ 10
来源：http://dali.yuxming.cn/Article/details/gtmkbfowoe.html

Perl ........... 10
来源：http://dali.yj20258888.top/Article/details/gtewgftxpr.html

Scala .......... 10
来源：http://dali.pengpengdd.cyou/Article/details/gtskdpbkby.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gtzstefxnq.html

合计 ........... 2106 条
来源：http://dali.jlsjyb.cn/Article/details/gtzokggqiq.html

按章节统计：
来源：http://dali.gaohongyu789.top/Article/details/gtowkdlqhu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtwmcefuwh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtjikxyziy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.sweek.top/Article/details/gtfzqwspxr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jiagoushi.top/Article/details/gtukzigenh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yongpay.top/Article/details/gtitcthged.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtqhpheptf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtjwhygfwy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhoulong.xyz/Article/details/gtdebswijv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.bjfxy.top/Article/details/gtzzygapms.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jiagoushi.top/Article/details/gtcnrctpyg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.fengsongda.top/Article/details/gthjueajlb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtnzllsgyu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtumqzoykl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnfokdvb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenzaomai.com/Article/details/gtmxfuetrz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtcycwzhyn.html

Q SQL 专题                              90
来源：http://dali.cheryme.top/Article/details/gtkahgamco.html

R Bash 专题                             80
来源：http://dali.yj20258.top/Article/details/gtesixcnxu.html

S C / C++ 专题                          60
来源：http://dali.shzxlz.cn/Article/details/gturxkimxj.html

T 其他语言补充                          60
来源：http://dali.yongpay.top/Article/details/gteubllscd.html

U 高频实用片段                         120
来源：http://dali.gaohongyu789.top/Article/details/gtmyxbkmhb.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtskquducy.html

合计                                  2106 条
来源：http://dali.sweek.top/Article/details/gtweugjylk.html

--------------------------------------------------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gtughaozpq.html

使用提醒
来源：http://dali.xuanzx.com/Article/details/gtxftbwxzo.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtesskhtus.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hongshengwenyu.top/Article/details/gtyudzbanu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jinqigfzy.top/Article/details/gtzjglmflm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.yueranfly.top/Article/details/gtqciqxviu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gtgmkkxvxj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.bjfxy.top/Article/details/gttqmsefqo.html

—— 文件结束 ——
来源：http://dali.jqgfzy.top/Article/details/gtdnbjvecz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtbynxxigr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.aibaodan.cn/Article/details/gtzdrnkzmo.html

Common Programming Examples Cheat Book
来源：http://dali.jinqigfzy.top/Article/details/gtyujzpypw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjmaviana.html

【收录内容】
来源：http://dali.aizwys.cn/Article/details/gtlwlwpxsn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhiwuduotai.top/Article/details/gtjfawmtap.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.chenlongwang.top/Article/details/gtuwnpngll.html

SQL · Bash · C · C++
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdabxebxd.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.cdnleiting.top/Article/details/gtgolvrgyr.html

【使用说明】
来源：http://dali.gzhubu.top/Article/details/gtboebmixb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.snrcjt.cn/Article/details/gtywdgbyfx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.shangyingyoupin.top/Article/details/gtfxjnimvn.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.gogol.net.cn/Article/details/gtyfmnitra.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.dianchejie.cn/Article/details/gtfyqisypg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.bjfxy.top/Article/details/gtodkkaela.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.yonumen.top/Article/details/gtbntuiwgo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.nwbrower.top/Article/details/gttzaevzbf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xuetiantiany.cn/Article/details/gtwmgmfcns.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.andypj.xyz/Article/details/gtjccfdhcp.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtbbuctyvk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhongyouzk.top/Article/details/gtskclougx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jiagoushi.top/Article/details/gtyucvngxk.html

【文件统计】
来源：http://dali.yvedp.cn/Article/details/gttnkqhdju.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.shuidangran.top/Article/details/gtnxofkzpu.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtaswqavzx.html

目  录
来源：http://dali.sweek.top/Article/details/gthnzhqjvw.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gtumginkte.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.chenzaomai.com/Article/details/gtzuwkrhzq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.smart0.xyz/Article/details/gtjylitxwq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jlsjyb.cn/Article/details/gtaxzrcghg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.havefunace.top/Article/details/gteowruuhl.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.quarkkingdee.top/Article/details/gtjuqsxmlm.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.shzxlz.cn/Article/details/gtezydkbdn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.nanxuanxn.top/Article/details/gtiohephcv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.hnqzz.top/Article/details/gtpqvzsnpk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.ivvv.top/Article/details/gtdfnngawn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.jqgfzy.top/Article/details/gtsaucswmt.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.cdnleiting.top/Article/details/gtyjmffaoc.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gtvirkqykg.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtodudlpmn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.xuetiantiany.cn/Article/details/gtgytfknjc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.xziqi.cn/Article/details/gttbsgeppj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gtyzqtcgri.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.fzhhl.top/Article/details/gtksegyisb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.sxryk.cn/Article/details/gttrtswmdc.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sxryk.cn/Article/details/gthfbkfjiw.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.meibo888.top/Article/details/gtxksdgogd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gthdpknjxk.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtipsrnpgd.html

A. 基础语法与类型
来源：http://dali.guowangkeji.top/Article/details/gtvbqlukpa.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtaiufaphe.html

[A01] Hello World
来源：http://dali.snrcjt.cn/Article/details/gtudpcpckk.html

Py:   print("Hello, World!")
来源：http://dali.tian-w.cn/Article/details/gteikqeqek.html

PHP:  echo "Hello, World!";
来源：http://dali.yj20258.top/Article/details/gttodalyfn.html

JS:   console.log("Hello, World!");
来源：http://dali.yongpay.top/Article/details/gtpqcdfbry.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yueranfly.top/Article/details/gtwszisbey.html

Java: System.out.println("Hello, World!");
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuknnekm.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.gaohongyu789.top/Article/details/gtarcfqigt.html

Ruby: puts "Hello, World!"
来源：http://dali.yuxming.cn/Article/details/gtflfcayuv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.hysaishi.cn/Article/details/gtvluzwpmw.html

[A02] 变量声明与赋值
来源：http://dali.xinyue.icu/Article/details/gtceatodln.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yangfankeji.com/Article/details/gtdsepmode.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.xuanzx.com/Article/details/gtevgcckdf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yj20258.top/Article/details/gtmjghlfky.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cashguo.top/Article/details/gtqxmuofdx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.gotoacloud.top/Article/details/gtcpblitzk.html

Go:   name := "Alex"; age := 20
来源：http://dali.cucudq.cn/Article/details/gttzqvpevp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.cqqwz.cn/Article/details/gtragspdnj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.mhx1999.top/Article/details/gtneckqyoa.html

[A03] 常量定义
来源：http://dali.hfpthk.cn/Article/details/gtwxnasjrl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.redwolf501.top/Article/details/gtygutofxs.html

PHP:  const PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtmeqkxvom.html

JS:   const PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gteqwkmjhb.html

TS:   const PI: number = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtodcrajtb.html

Java: static final double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtfpnkscbd.html

Go:   const PI = 3.14159
来源：http://dali.316326.xyz/Article/details/gtxqhvnvic.html

Ruby: PI = 3.14159
来源：http://dali.shangyingyoupin.top/Article/details/gtarndirgl.html

C#:   const double PI = 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtynycewwe.html

[A04] 判断变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtcvyefowe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.ybcxt.top/Article/details/gtojjjaaiq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gzhubu.top/Article/details/gtjnffviee.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.jinqigufen.top/Article/details/gtaekkzaue.html

TS:   typeof x; x instanceof Date
来源：http://dali.sweek.top/Article/details/gtlhihfrme.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yj20258888.top/Article/details/gtrflowzyv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.cqqwz.cn/Article/details/gtcvccsfuj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cucudq.cn/Article/details/gtqqbpwmij.html

C#:   x.GetType().Name; x is int
来源：http://dali.dashuyun.cn/Article/details/gtctyxdhlt.html

[A05] 整数除法与取模
来源：http://dali.jinqigufen.top/Article/details/gtqxmoxbjo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dianchejie.cn/Article/details/gtznhqlqmx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gttrifxsje.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gttmlabmwt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.jinqigufen.top/Article/details/gttdpcvpvc.html

Java: 7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtoeslbtgn.html

Go:   7 / 2; 7 % 2
来源：http://dali.xuetiantiany.cn/Article/details/gtipyiedqo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gtdlqgflck.html

C#:   7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtvtmbunrq.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmfnatip.html

Py:   int("42"); float("3.14")
来源：http://dali.bjfxy.top/Article/details/gtqeyfqscg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifwmtmww.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhiwuduotai.top/Article/details/gtcqzevfwc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.ehwqpu.com/Article/details/gthtbiykxf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhoulong.xyz/Article/details/gtmblwpeue.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.aizwys.cn/Article/details/gtzhualxsk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.sweek.top/Article/details/gtgmzrlwfq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.tanke756.top/Article/details/gtkdfxynve.html

[A07] 数字转字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtgfvamqdd.html

Py:   str(42)
来源：http://dali.nanxinkj.top/Article/details/gtfspmbdmb.html

PHP:  (string) 42; strval(42)
来源：http://dali.snrcjt.cn/Article/details/gthodypsyf.html

JS:   String(42); (42).toString()
来源：http://dali.jyoumei.cn/Article/details/gtlutxzpga.html

TS:   String(42)
来源：http://dali.sweek.top/Article/details/gtiifnctos.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.xinyue.icu/Article/details/gtvaumsgoi.html

Go:   strconv.Itoa(42)
来源：http://dali.yueranfly.top/Article/details/gtfywzpubv.html

Ruby: 42.to_s
来源：http://dali.sufxvd.cn/Article/details/gtvesoeqpo.html

C#:   42.ToString()
来源：http://dali.iojbl.cn/Article/details/gtbylximzg.html

[A08] 取整与四舍五入
来源：http://dali.0kj1m.cn/Article/details/gtmuyfusoq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.ybcxt.top/Article/details/gtqyjorifl.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.dianchejie.cn/Article/details/gthrdxionw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.jiagoushi.top/Article/details/gtgzsdjawr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.316326.xyz/Article/details/gtcjewzaif.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtyrpkvcko.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.fengsongda.top/Article/details/gtpmvylxre.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.bjfxy.top/Article/details/gtkjdlazke.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.tanke756.top/Article/details/gtqtdjtssx.html

[A09] 绝对值与最大最小值
来源：http://dali.ivvv.top/Article/details/gthxgjepfs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzidmkiuq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtawvgjuri.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gtdujcywnp.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.cheryme.top/Article/details/gtlixygjjm.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.sweek.top/Article/details/gtwchhqtps.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxinkj.top/Article/details/gtqgktcwvm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.xuanzx.com/Article/details/gtwjpscdtr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtbmiudmbl.html

[A10] 生成随机数
来源：http://dali.hnqzz.top/Article/details/gteylsyaea.html

Py:   import random; random.randint(1, 100)
来源：http://dali.jqgufenzy.top/Article/details/gtthcvndqr.html

PHP:  random_int(1, 100);
来源：http://dali.kuanghao11.cn/Article/details/gthfcszvls.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspsuveie.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj20258.top/Article/details/gtqqliecpy.html

Java: new Random().nextInt(100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gtadsygexf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.chenzaomai.com/Article/details/gthjgokjjk.html

Ruby: rand(1..100)
来源：http://dali.hnqzz.top/Article/details/gtjrhauavj.html

C#:   new Random().Next(1, 101)
来源：http://dali.tian-w.cn/Article/details/gtyjxoguxd.html

[A11] 条件表达式（三元）
来源：http://dali.vqdsnc.cn/Article/details/gtmkeywvzs.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.guowangkeji.top/Article/details/gtyqzbtmbp.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gtukxnauvu.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yangfankeji.com/Article/details/gtqvejlkbr.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yuanzhike.top/Article/details/gtjaaqxkle.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.fengsongda.top/Article/details/gtledaltbn.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.sufxvd.cn/Article/details/gtfcaqguhw.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.sysykeji.top/Article/details/gtmfwcpjme.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.ydzc1.top/Article/details/gtcibrhmfv.html

[A12] 字符串插值 / 格式化
来源：http://dali.hysaishi.cn/Article/details/gtmekblcqn.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinqigufen.top/Article/details/gtlkjyvwwk.html


<!-- 参考信息 -->