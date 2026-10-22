代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gtroyudixo.html

parse_ini_file("config.ini", true)
来源：http://dali.0kj1m.cn/Article/details/gtsaaiisdv.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtxmolrljv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ehwqpu.com/Article/details/gtsqjxaeul.html

[U75] PHP：依赖注入
来源：http://dali.mhx1999.top/Article/details/gtdwwkcbcm.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtvhlqhcci.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtgvusryut.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.quarkkingdee.top/Article/details/gtzxwkdrak.html

[U77] PHP：模板渲染
来源：http://dali.hammf.cn/Article/details/gtqeuuadyc.html

composer require twig/twig
来源：http://dali.wangshuangyany.cn/Article/details/gtavozytdl.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtghjlgekg.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gtgspvyidy.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gthftowwbq.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gtlznodido.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gtqxuwqsdv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tianlin.xyz/Article/details/gtkixprppr.html

[U81] JS：初始化项目
来源：http://dali.yanxiufei.cn/Article/details/gtwhpbufuw.html

npm init -y;  npm i express
来源：http://dali.haohaochexian.top/Article/details/gtijbseqfl.html

[U82] JS：package.json 脚本
来源：http://dali.fengsongda.top/Article/details/gtlgvrzshi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.smart0.xyz/Article/details/gttsqjbtiq.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtzkxdykia.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtugqvzeam.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrkofiks.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jyoumei.cn/Article/details/gtlblkuvae.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gttezjhhpr.html

a?.b?.c
来源：http://dali.andypj.xyz/Article/details/gtliphphvw.html

[U86] JS：空值合并
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrxvvtqt.html

a ?? b
来源：http://dali.yangfankeji.com/Article/details/gtlvweqpmh.html

[U87] JS：解构默认值
来源：http://dali.yongpay.top/Article/details/gtnfcfqhxo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gtbotrstth.html

[U88] JS：对象展开合并
来源：http://dali.yonumen.top/Article/details/gthbbsnytw.html

{ ...a, ...b }
来源：http://dali.zhongyouzk.top/Article/details/gtkuximttm.html

[U89] JS：数组去重
来源：http://dali.iojbl.cn/Article/details/gthtnfohpz.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtpyjmhfrq.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtdtdxexld.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtfehwnlbb.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtqpuxuitw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.sweek.top/Article/details/gthrupirda.html

[U92] JS：深拷贝
来源：http://dali.gotoacloud.top/Article/details/gtbfstwohb.html

structuredClone(obj)
来源：http://dali.jqgfzy.top/Article/details/gtosaseprj.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gtqennqzgw.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtakyzplew.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxkzzqja.html

const double = x => x * 2;
来源：http://dali.quarkkingdee.top/Article/details/gtxwqbokap.html

[U95] JS：Promise 包装
来源：http://dali.smart0.xyz/Article/details/gtblhfjrmv.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtynilnzfj.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gtjiakosef.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtbrqfszvi.html

[U97] JS：并发请求
来源：http://dali.nwbrower.top/Article/details/gtpaetanqq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtdtwqubkk.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigufen.top/Article/details/gtienqijgj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.vqdsnc.cn/Article/details/gtnmfsnmpj.html

[U99] JS：事件监听
来源：http://dali.mhx1999.top/Article/details/gtzvkihizz.html

el.addEventListener("click", e => {})
来源：http://dali.andypj.xyz/Article/details/gtusnecias.html

[U100] JS：DOM 查询
来源：http://dali.yuxming.cn/Article/details/gtvdvjhzaq.html

document.querySelector(".item")
来源：http://dali.shanyushiyangtech.top/Article/details/gtksficsyb.html

[U101] JS：classList 操作
来源：http://dali.kuanghao11.cn/Article/details/gtqskqzjpf.html

el.classList.toggle("active")
来源：http://dali.wangdashe.top/Article/details/gteadfbugr.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gtfncrttwj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shuidangran.top/Article/details/gtpvsytlny.html

[U103] JS：定时器
来源：http://dali.gotoacloud.top/Article/details/gtjequpajo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dashuyun.cn/Article/details/gtayiuovsq.html

[U104] JS：防抖
来源：http://dali.yanxiufei.cn/Article/details/gtxgqgxzph.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gtgoswhxoo.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gttgufrmmr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtshrzbnwu.html

[U106] JS：日期格式化
来源：http://dali.zycfv.cn/Article/details/gtvzhrdhal.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtjqpiqbzs.html

[U107] JS：数字千分位
来源：http://dali.cheryme.top/Article/details/gtyhmsfzro.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gogol.net.cn/Article/details/gtmgcreyou.html

[U108] JS：随机整数
来源：http://dali.mhx1999.top/Article/details/gtwygsrgdx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.aizwys.cn/Article/details/gtmeqbrxkv.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtfedigsin.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yuxming.cn/Article/details/gtmkuweezk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gtaywdoyfu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gtdditomxp.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gtdtroidcx.html

new Map(Object.entries(obj))
来源：http://dali.tanke756.top/Article/details/gtymdmiocd.html

[U112] JS：字符串补位
来源：http://dali.wangshuangyany.cn/Article/details/gtpnyaewje.html

"7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtddrcowpp.html

[U113] JS：正则替换全部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxqwjrbm.html

s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtdehbyaif.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gtrotjvwfw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.kuanghao11.cn/Article/details/gtmptojdna.html

[U115] JS：生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtjnbpdgjs.html

crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtqnszegqw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.wangdashe.top/Article/details/gtdaxbsitf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yj20258.top/Article/details/gtfiislltl.html

[U117] JS：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtxvuppthc.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gtbnbhdmie.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdckqexv.html

npm i -D vite;  npx vite
来源：http://dali.jinqigufen.top/Article/details/gtneolyszj.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gtfgkzvcpp.html

npx vite build
来源：http://dali.hnxiangtu.top/Article/details/gteuixvacv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gtllmvulxo.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtvdqwieqg.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbosgngpf.html

统计汇总
来源：http://dali.fzhhl.top/Article/details/gtvbhcygyw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gttkiojrmd.html

按语言统计（条）：
来源：http://dali.jinqigufen.top/Article/details/gtgptezlcw.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gtwamolnzx.html

PHP ............ 252
来源：http://dali.cdnleiting.top/Article/details/gtahxbiloq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gtrdrmjrgx.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtrpcgxoxt.html

Java ........... 212
来源：http://dali.316326.xyz/Article/details/gtvgxjkciv.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtrzcywxdg.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gthbbpjfts.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gtiqfcyssv.html

C .............. 30
来源：http://dali.cashguo.top/Article/details/gtftakuiyy.html

C++ ............ 30
来源：http://dali.tanke756.top/Article/details/gtvpkgikgt.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gtuvsqqoxz.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtvmflaqvr.html

Kotlin ......... 15
来源：http://dali.shuidangran.top/Article/details/gtkpcpzqpc.html

Swift .......... 15
来源：http://dali.smart0.xyz/Article/details/gtostmruqk.html

Lua ............ 10
来源：http://dali.zhiwuduotai.top/Article/details/gteaohzwsu.html

Perl ........... 10
来源：http://dali.yuanzhike.top/Article/details/gtgwryirdd.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gtolhemgyj.html

------------------------------------
来源：http://dali.quarkkingdee.top/Article/details/gtbkjqwist.html

合计 ........... 2106 条
来源：http://dali.yonumen.top/Article/details/gtscufguqp.html

按章节统计：
来源：http://dali.kuanghao11.cn/Article/details/gtdnuojdhv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhixingplan.top/Article/details/gtqjdmzuao.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cheryme.top/Article/details/gtnitrecuy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtaxdoysfi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.wangdashe.top/Article/details/gtsegzsynw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xylfe.cn/Article/details/gtdxjphrdt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jianghu66.top/Article/details/gtxqwebunj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtmxmkquqs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.shzxlz.cn/Article/details/gtmdxklrfr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtvxmfzxms.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gtjzradxcd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtokewqged.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.wangshuangyany.cn/Article/details/gtwmtcobbc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gthephrtbx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yvedp.cn/Article/details/gtpbujuxnw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ydzc1.top/Article/details/gtteehlkds.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.mhx1999.top/Article/details/gtiwxtanib.html

Q SQL 专题                              90
来源：http://dali.tanke756.top/Article/details/gtfaiklvbn.html

R Bash 专题                             80
来源：http://dali.fengsongda.top/Article/details/gtfiectkzr.html

S C / C++ 专题                          60
来源：http://dali.cashguo.top/Article/details/gtthjezzkj.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gteodykcky.html

U 高频实用片段                         120
来源：http://dali.nanxinkj.top/Article/details/gttafwvqce.html

------------------------------------
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlumsnmap.html

合计                                  2106 条
来源：http://dali.cucudq.cn/Article/details/gtccnpibeq.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gtjjvghdfx.html

使用提醒
来源：http://dali.yuanzhike.top/Article/details/gtxmdvpyam.html

--------------------------------------------------------------------------------
来源：http://dali.jqgfzy.top/Article/details/gtafwifzvr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.hongshengwenyu.top/Article/details/gtcgjbgqxn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tanke756.top/Article/details/gteoavungp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.gzhubu.top/Article/details/gtxoqsyluu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiownelg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.yj20258.top/Article/details/gtycdyoxcu.html

—— 文件结束 ——
来源：http://dali.zhixingplan.top/Article/details/gtseutsbjn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtevshynsw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtnvchrc.html

Common Programming Examples Cheat Book
来源：http://dali.feifeiyinyue.top/Article/details/gtjaeoblib.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtebikiljq.html

【收录内容】
来源：http://dali.yuanzhike.top/Article/details/gtbapcgmkn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.xylfe.cn/Article/details/gtesdhytqz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.yj20258.top/Article/details/gthenxuqyz.html

SQL · Bash · C · C++
来源：http://dali.cdnleiting.top/Article/details/gtodqjqexu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.feifeiyinyue.top/Article/details/gttprrsvni.html

【使用说明】
来源：http://dali.zdqjudy.top/Article/details/gtloerkone.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.xuanzx.com/Article/details/gtlleikfbx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.redwolf501.top/Article/details/gtftxmjwot.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.ybcxt.top/Article/details/gtsnsdqbxc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.yj202588.top/Article/details/gtbrsqddje.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.316326.xyz/Article/details/gtxyvzienq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.nanxinkj.top/Article/details/gtkjplrrxa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gtqpdqqqtf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zdqjudy.top/Article/details/gtiwhxtmxg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.iojbl.cn/Article/details/gtgozgrhlw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtqgeycipd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.pengpengdd.cyou/Article/details/gtzapyvvtm.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.tianlin.xyz/Article/details/gtvcguauph.html

【文件统计】
来源：http://dali.yj202588.top/Article/details/gtvesxiimg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyarfdkv.html

--------------------------------------------------------------------------------
来源：http://dali.yangfankeji.com/Article/details/gtzhwfqrgh.html

目  录
来源：http://dali.yvedp.cn/Article/details/gtyspjqdfz.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtjiwgaqcx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.svipenyu.cn/Article/details/gtkwtrylvx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtsvgbyxdh.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.snrcjt.cn/Article/details/gtnwzucimk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.jqgfzy.top/Article/details/gtjwqkydra.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.yj202588.top/Article/details/gtlbdzzlgx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtwpivqzzd.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.dianchejie.cn/Article/details/gtpxfzjgpx.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.sxryk.cn/Article/details/gtcfponwgk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.jianghu66.top/Article/details/gtahgcvamm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.yueranfly.top/Article/details/gtnpdslzaa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.chenzaomai.com/Article/details/gtnhuusaia.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xziqi.cn/Article/details/gtnlqbtzzf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.sxryk.cn/Article/details/gtrdpmeymv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.ehwqpu.com/Article/details/gtjetsymkn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtoaaojggt.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtdhtyeqel.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.yuanzhike.top/Article/details/gtuzvqcqzy.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yuanzhike.top/Article/details/gtzauogodr.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.sufxvd.cn/Article/details/gtevgkjzwa.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtszrcendz.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtpadcznyq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthxzuwtvv.html

A. 基础语法与类型
来源：http://dali.fzhhl.top/Article/details/gttskcfzav.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcmhvmqim.html

[A01] Hello World
来源：http://dali.yueranfly.top/Article/details/gtvvupfyis.html

Py:   print("Hello, World!")
来源：http://dali.fengsongda.top/Article/details/gtvnmgjzoa.html

PHP:  echo "Hello, World!";
来源：http://dali.daxiang520.top/Article/details/gtcmiwjlzy.html

JS:   console.log("Hello, World!");
来源：http://dali.xuanzx.com/Article/details/gtbxnqfvix.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.chenjidiqi.icu/Article/details/gtczdtautb.html

Java: System.out.println("Hello, World!");
来源：http://dali.chenjidiqi.icu/Article/details/gtzcdiiuwd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.hysaishi.cn/Article/details/gtphyrwokf.html

Ruby: puts "Hello, World!"
来源：http://dali.hammf.cn/Article/details/gtfrjenydv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.xinyue.icu/Article/details/gtbjxovcry.html

[A02] 变量声明与赋值
来源：http://dali.cucudq.cn/Article/details/gtpthedkvc.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jianghu66.top/Article/details/gtggngfhur.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yj20258.top/Article/details/gtfdozlych.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yonumen.top/Article/details/gtezmauuoc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yj202588.top/Article/details/gtzcesfoxh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gtmjklcjmy.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gttmaleaul.html

Ruby: name = "Alex"; age = 20
来源：http://dali.yj20258888.top/Article/details/gtnhtsirzu.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.svipenyu.cn/Article/details/gtsekobepq.html

[A03] 常量定义
来源：http://dali.guannengcc.top/Article/details/gtxvmgzcel.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.xuetiantiany.cn/Article/details/gtbkfxrgrw.html

PHP:  const PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtqapuvjym.html

JS:   const PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtxzppwosb.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtrddexhwc.html

Java: static final double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtqtdrrojg.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gtshalfkov.html

Ruby: PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gteqeppxpn.html

C#:   const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtcilrerbf.html

[A04] 判断变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gtkcxoqqvs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.jlsjyb.cn/Article/details/gtycqknysp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhoulong.xyz/Article/details/gtppkbeczy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.daria6918.cn/Article/details/gtxrnhsnie.html

TS:   typeof x; x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gtkulwnxzt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.yongpay.top/Article/details/gtwlifqwwa.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.ybcxt.top/Article/details/gtdemmgfga.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhiwuduotai.top/Article/details/gtwtyrghhr.html

C#:   x.GetType().Name; x is int
来源：http://dali.hnxiangtu.top/Article/details/gttczaejzq.html

[A05] 整数除法与取模
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfsjpdvl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhoulong.xyz/Article/details/gtxlbtinlc.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlndjisg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gogol.net.cn/Article/details/gtwwqhnpho.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.gotoacloud.top/Article/details/gtavqoosyw.html

Java: 7 / 2; 7 % 2
来源：http://dali.xziqi.cn/Article/details/gtblddawou.html

Go:   7 / 2; 7 % 2
来源：http://dali.fzhhl.top/Article/details/gtcqhjefjy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.andypj.xyz/Article/details/gtccwxpgum.html

C#:   7 / 2; 7 % 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtceznyptu.html

[A06] 字符串转数字
来源：http://dali.yueranfly.top/Article/details/gtlvegcuyw.html

Py:   int("42"); float("3.14")
来源：http://dali.hammf.cn/Article/details/gtzhlrlhsk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.cdnleiting.top/Article/details/gtzdpvgiat.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.aibaodan.cn/Article/details/gtxdadgqcf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.yj20258.top/Article/details/gtardxsyfw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.ppjwa.cn/Article/details/gtolezoovh.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.snrcjt.cn/Article/details/gtymxuexbw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.chenlongwang.top/Article/details/gtgegoclzt.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yueranfly.top/Article/details/gtsuchlitw.html

[A07] 数字转字符串
来源：http://dali.shuidangran.top/Article/details/gtkvfbrrya.html

Py:   str(42)
来源：http://dali.havefunace.top/Article/details/gtaromjhpt.html

PHP:  (string) 42; strval(42)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgsmpred.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258.top/Article/details/gtarixkmlz.html

TS:   String(42)
来源：http://dali.xziqi.cn/Article/details/gtuqnndioy.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtluebysys.html

Go:   strconv.Itoa(42)
来源：http://dali.yanxiufei.cn/Article/details/gtyaixepff.html

Ruby: 42.to_s
来源：http://dali.fzhhl.top/Article/details/gtaiuyqnvw.html

C#:   42.ToString()
来源：http://dali.ydzc1.top/Article/details/gtgzrrtqot.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gtholowevl.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcbwthdtb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.smart0.xyz/Article/details/gtyjfaimsm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.ydzc1.top/Article/details/gthssfqwwt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.c1oappe.top/Article/details/gtmasqkbzj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.hysaishi.cn/Article/details/gtgtlounyd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtcdrtqjwu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.xuetiantiany.cn/Article/details/gtnzxrqhto.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.cheryme.top/Article/details/gttmiwwtit.html

[A09] 绝对值与最大最小值
来源：http://dali.hongshengwenyu.top/Article/details/gthvydtaza.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.sweek.top/Article/details/gtydpxevth.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcvyehbjx.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtvfezjegr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yonumen.top/Article/details/gtpbfrgoxu.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtmcymrgbg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.dashuyun.cn/Article/details/gtkvvtxono.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.gogol.net.cn/Article/details/gthhgsstrm.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtqtadvnjb.html

[A10] 生成随机数
来源：http://dali.yvedp.cn/Article/details/gtwhhresen.html

Py:   import random; random.randint(1, 100)
来源：http://dali.dianchejie.cn/Article/details/gtrtnprcyi.html

PHP:  random_int(1, 100);
来源：http://dali.316326.xyz/Article/details/gtmodkoaxe.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtlcixxfwh.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.snrcjt.cn/Article/details/gtnclyzsef.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhongyouzk.top/Article/details/gtkelwspie.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.xinyue.icu/Article/details/gtyoiuqole.html

Ruby: rand(1..100)
来源：http://dali.guannengcc.top/Article/details/gtmucamjdi.html

C#:   new Random().Next(1, 101)
来源：http://dali.wangshuangyany.cn/Article/details/gtilgbkjxm.html

[A11] 条件表达式（三元）
来源：http://dali.fengsongda.top/Article/details/gttknunvft.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.ydzc1.top/Article/details/gtfatykmjj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtlvobqfzk.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.tian-w.cn/Article/details/gtizqufryp.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgicpytx.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.wangdashe.top/Article/details/gtvaplahtg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgufenzy.top/Article/details/gtqkmtuemx.html


<!-- 参考信息 -->