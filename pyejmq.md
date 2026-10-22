代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.meibo888.top/Article/details/gtzsnvamok.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtjveiexag.html

[U76] PHP：简单路由
来源：http://dali.pengpengdd.cyou/Article/details/gtgyovdzbm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gtmjwidmbk.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtjrqlhenb.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtcapvnlbz.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtaoszirut.html

composer require --dev phpunit/phpunit
来源：http://dali.svipenyu.cn/Article/details/gtnzwxfqsl.html

[U79] PHP：静态分析
来源：http://dali.wangshuangyany.cn/Article/details/gtqqryxtth.html

composer require --dev phpstan/phpstan
来源：http://dali.sxryk.cn/Article/details/gtoajdeczh.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gtiffavdmm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtqgnkeycp.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtrlorxpht.html

npm init -y;  npm i express
来源：http://dali.yvedp.cn/Article/details/gtllknbxzz.html

[U82] JS：package.json 脚本
来源：http://dali.guowangkeji.top/Article/details/gterpxvuty.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gtfdnmwogf.html

[U83] JS：ES Module 导入导出
来源：http://dali.ehwqpu.com/Article/details/gtwfkxifqf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtbremgtmo.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtsapsqymm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtvrvobove.html

[U85] JS：可选链
来源：http://dali.jqgfzy.top/Article/details/gtffapyhpi.html

a?.b?.c
来源：http://dali.quarkkingdee.top/Article/details/gtluqspfqm.html

[U86] JS：空值合并
来源：http://dali.jlsjyb.cn/Article/details/gtpgepgwbv.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gtupjrtszg.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtquiwalsz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zdqjudy.top/Article/details/gtaorixorb.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gtdveeehit.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtztzofhje.html

[U89] JS：数组去重
来源：http://dali.xziqi.cn/Article/details/gtdmbxtnsn.html

[...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gtohrcjods.html

[U90] JS：数字数组排序
来源：http://dali.hfpthk.cn/Article/details/gtfbkkzqeb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtnkgpaijw.html

[U91] JS：对象键值遍历
来源：http://dali.bjfxy.top/Article/details/gteckliufy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtdwbmlzdw.html

[U92] JS：深拷贝
来源：http://dali.zycfv.cn/Article/details/gthdiaubgs.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtarmkderq.html

[U93] JS：模板字符串
来源：http://dali.mhx1999.top/Article/details/gtzckcznvt.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gtiyyaaunb.html

[U94] JS：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gtnbgernve.html

const double = x => x * 2;
来源：http://dali.nanxinkj.top/Article/details/gtdsphfpxo.html

[U95] JS：Promise 包装
来源：http://dali.jqgfzy.top/Article/details/gtmjppjwae.html

new Promise((resolve, reject) => {})
来源：http://dali.vqdsnc.cn/Article/details/gtiixlceht.html

[U96] JS：async/await 与异常
来源：http://dali.xylfe.cn/Article/details/gtaoapzhad.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gtceihhdzw.html

[U97] JS：并发请求
来源：http://dali.vqdsnc.cn/Article/details/gtvmrsrklk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtwsbxchyy.html

[U98] JS：fetch 带 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gtmmipnqnr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gtspilpeoz.html

[U99] JS：事件监听
来源：http://dali.sufxvd.cn/Article/details/gtgupgoxut.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtegjoeqpf.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtvtcaqbib.html

document.querySelector(".item")
来源：http://dali.kuanghao11.cn/Article/details/gthrpzxqlh.html

[U101] JS：classList 操作
来源：http://dali.cheryme.top/Article/details/gtgitmbhte.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtobpuunmq.html

[U102] JS：本地存储
来源：http://dali.xylfe.cn/Article/details/gtsbmlaqsb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.tanke756.top/Article/details/gtsuonniyg.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gtzbxscigb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gogol.net.cn/Article/details/gtubjbttwf.html

[U104] JS：防抖
来源：http://dali.birdmap.top/Article/details/gtwrugjtby.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtkfxgltza.html

[U105] JS：节流
来源：http://dali.yongpay.top/Article/details/gtjbpqxfos.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.redwolf501.top/Article/details/gtrjwednjq.html

[U106] JS：日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtwvysywep.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ybcxt.top/Article/details/gtnytrwalg.html

[U107] JS：数字千分位
来源：http://dali.ybcxt.top/Article/details/gtygtndgrv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtsntrspqb.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtvfiouiok.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gtoquixuzi.html

[U109] JS：数组分组
来源：http://dali.jqgufenzy.top/Article/details/gtjraqbiky.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jyoumei.cn/Article/details/gtqwuxcwan.html

[U110] JS：数组分块
来源：http://dali.xziqi.cn/Article/details/gtrgqaspum.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gtrrysullm.html

[U111] JS：对象转 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtqafzyzca.html

new Map(Object.entries(obj))
来源：http://dali.chenzaomai.com/Article/details/gtkqjnkikn.html

[U112] JS：字符串补位
来源：http://dali.zycfv.cn/Article/details/gtubvbanwz.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjyobaoa.html

[U113] JS：正则替换全部
来源：http://dali.xylfe.cn/Article/details/gtuicmgjhb.html

s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtokimnjcj.html

[U114] JS：JSON 深比较
来源：http://dali.ydzc1.top/Article/details/gtvlfdbjzp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guannengcc.top/Article/details/gtnahksrbq.html

[U115] JS：生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtgjmjxrny.html

crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gttwmjqiti.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnxiangtu.top/Article/details/gtrvetrkny.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnklqpdb.html

[U117] JS：单元测试
来源：http://dali.yj202588.top/Article/details/gtsomebsiu.html

npm i -D vitest;  npx vitest
来源：http://dali.cdnleiting.top/Article/details/gtfytjumcr.html

[U118] JS：开发服务器
来源：http://dali.shzxlz.cn/Article/details/gtmaduggae.html

npm i -D vite;  npx vite
来源：http://dali.yvedp.cn/Article/details/gtxlbpngcy.html

[U119] JS：生产构建
来源：http://dali.wangdashe.top/Article/details/gtnmucapvy.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gtbusrrphy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cucudq.cn/Article/details/gtitinvugz.html

import.meta.env.VITE_API_URL
来源：http://dali.tanke756.top/Article/details/gtrhqivadz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtyaaoozho.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gtxirdhqih.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqjwdjzda.html

按语言统计（条）：
来源：http://dali.haohaochexian.top/Article/details/gtltftlsuv.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtghtuwuej.html

PHP ............ 252
来源：http://dali.sufxvd.cn/Article/details/gthldeqpbf.html

JavaScript ..... 252
来源：http://dali.jiagoushi.top/Article/details/gtlrjkgndr.html

TypeScript ..... 212
来源：http://dali.haohaochexian.top/Article/details/gtjshcfohg.html

Java ........... 212
来源：http://dali.yj202588.top/Article/details/gtfiziwadd.html

Go ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtrdkefsis.html

Ruby ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtepdearcf.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gtvinvsalz.html

C .............. 30
来源：http://dali.gaohongyu789.top/Article/details/gtgfgsqovr.html

C++ ............ 30
来源：http://dali.jinqigfzy.top/Article/details/gtmdbjynyb.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtdcugvatv.html

Bash ........... 80
来源：http://dali.guannengcc.top/Article/details/gthdbrioei.html

Kotlin ......... 15
来源：http://dali.c1oappe.top/Article/details/gteiltmxgg.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gtxvmohoii.html

Lua ............ 10
来源：http://dali.iojbl.cn/Article/details/gtnynhjxhc.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gtkqfvmkcp.html

Scala .......... 10
来源：http://dali.redwolf501.top/Article/details/gtkgphrriw.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtdvexrksj.html

合计 ........... 2106 条
来源：http://dali.cashguo.top/Article/details/gtutgufcii.html

按章节统计：
来源：http://dali.gzhubu.top/Article/details/gtzhpicmvd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tanke756.top/Article/details/gtteyntudq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zdqjudy.top/Article/details/gtbuhhjcza.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtkdorxzzf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gtplyqgicz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.wangshuangyany.cn/Article/details/gtlffxisuv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.cdnleiting.top/Article/details/gtkrtoaklv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtrzewtpez.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.nwbrower.top/Article/details/gtjfitunow.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtyitiitdj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqvwhgzo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gthfzllyrf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtvwhldajz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gthyvxoski.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtxogzbsup.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.c1oappe.top/Article/details/gtszbdtxjq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gtbnjlaxqj.html

Q SQL 专题                              90
来源：http://dali.yvedp.cn/Article/details/gttesasqif.html

R Bash 专题                             80
来源：http://dali.vqdsnc.cn/Article/details/gtomnbcmdd.html

S C / C++ 专题                          60
来源：http://dali.iojbl.cn/Article/details/gtykpydjso.html

T 其他语言补充                          60
来源：http://dali.cqqwz.cn/Article/details/gtvzhpkfvq.html

U 高频实用片段                         120
来源：http://dali.aizwys.cn/Article/details/gtnavpaktr.html

------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtlsajfwfq.html

合计                                  2106 条
来源：http://dali.shanyushiyangtech.top/Article/details/gtzixuacfb.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtqioekrdn.html

使用提醒
来源：http://dali.guannengcc.top/Article/details/gtpfsdfzce.html

--------------------------------------------------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtonqfwdud.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.aibaodan.cn/Article/details/gtmdixlgrw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.aibaodan.cn/Article/details/gtjyjltdxy.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.sufxvd.cn/Article/details/gthrgdlxsc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.cdnleiting.top/Article/details/gtphcruimm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.daxiang520.top/Article/details/gtirdworzy.html

—— 文件结束 ——
来源：http://dali.nanxinkj.top/Article/details/gtotvvcoth.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthwtwxion.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.jinqigfzy.top/Article/details/gtucunylqh.html

Common Programming Examples Cheat Book
来源：http://dali.ppjwa.cn/Article/details/gtippspksc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtnrsggddi.html

【收录内容】
来源：http://dali.zhengqikj.top/Article/details/gtxoxkjrcg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shzxlz.cn/Article/details/gtaaedxuof.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhoulong.xyz/Article/details/gtfwamlaro.html

SQL · Bash · C · C++
来源：http://dali.zdqjudy.top/Article/details/gtlprylzzw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhiwuduotai.top/Article/details/gtxmypodan.html

【使用说明】
来源：http://dali.tianlin.xyz/Article/details/gtkmruhuxw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.vqdsnc.cn/Article/details/gtmjombmqf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.vqdsnc.cn/Article/details/gtabuaagje.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.yj20258888.top/Article/details/gttcvmaags.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shzxlz.cn/Article/details/gtkzpwcqvr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.chenjidiqi.icu/Article/details/gtpdippjtn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcokvfvp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.yvedp.cn/Article/details/gtidavxalj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.vqdsnc.cn/Article/details/gthzrowbta.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.chenzaomai.com/Article/details/gtepluhpnl.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.gogol.net.cn/Article/details/gtfvnvzlnk.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.kuanghao11.cn/Article/details/gtcdsluvjt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.cqqwz.cn/Article/details/gtcflanrdr.html

【文件统计】
来源：http://dali.chenzaomai.com/Article/details/gtkgcgatao.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.ydzc1.top/Article/details/gtwuqxkxsc.html

--------------------------------------------------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtwsbstugb.html

目  录
来源：http://dali.gogol.net.cn/Article/details/gtcvdzuchh.html

--------------------------------------------------------------------------------
来源：http://dali.wangdashe.top/Article/details/gttkvgcqnt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.jinqigufen.top/Article/details/gtfvenpbdl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.cucudq.cn/Article/details/gtntwbypaz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.guannengcc.top/Article/details/gtamklyyhb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.guannengcc.top/Article/details/gtndnwuzib.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.jqgfzy.top/Article/details/gtpojthjie.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.iojbl.cn/Article/details/gtrqskflap.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.wangdashe.top/Article/details/gtdsdvmjsb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.aizwys.cn/Article/details/gtsdbacmzv.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.fengsongda.top/Article/details/gttmwwltfp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.ehwqpu.com/Article/details/gtqbwhnrgs.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.bjfxy.top/Article/details/gttcesqjln.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.havefunace.top/Article/details/gtyhzsftyj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtleelymtk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.cdnleiting.top/Article/details/gtyxkhquzj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbeystdy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtryhcrwbs.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.xylfe.cn/Article/details/gtfbofeouj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.316326.xyz/Article/details/gtvssylyuh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.nwbrower.top/Article/details/gtazjrzjgd.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtftvrohgw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtyrvxbhoe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjqatnfvk.html

A. 基础语法与类型
来源：http://dali.cqqwz.cn/Article/details/gtliyqkidz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtfnygdzsk.html

[A01] Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtviybecix.html

Py:   print("Hello, World!")
来源：http://dali.ybcxt.top/Article/details/gtmnexthli.html

PHP:  echo "Hello, World!";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvbmhnnx.html

JS:   console.log("Hello, World!");
来源：http://dali.cqqwz.cn/Article/details/gtiofsyvbm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.wangshuangyany.cn/Article/details/gtwwodzthw.html

Java: System.out.println("Hello, World!");
来源：http://dali.ehwqpu.com/Article/details/gthffyzqyh.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.aibaodan.cn/Article/details/gtxnuobilk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gtnlefcbwu.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.daxiang520.top/Article/details/gtbhzbkcqh.html

[A02] 变量声明与赋值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwabcilup.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.jyoumei.cn/Article/details/gtotsjlyqw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.yanxiufei.cn/Article/details/gtyfkzhsms.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.hnxiangtu.top/Article/details/gtezrkveha.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.tian-w.cn/Article/details/gtwaabesgs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.andypj.xyz/Article/details/gtpujhgiql.html

Go:   name := "Alex"; age := 20
来源：http://dali.316326.xyz/Article/details/gtjnimptkk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.jianghu66.top/Article/details/gtlcmoxybx.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.tanke756.top/Article/details/gtlsqprmma.html

[A03] 常量定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsokuglu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.tanke756.top/Article/details/gtxljzunhl.html

PHP:  const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtfxnusjzp.html

JS:   const PI = 3.14159;
来源：http://dali.sysykeji.top/Article/details/gtiouillzq.html

TS:   const PI: number = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtgjbbfppv.html

Java: static final double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtbtbkrklm.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gtgwarvjzn.html

Ruby: PI = 3.14159
来源：http://dali.wangshuangyany.cn/Article/details/gtuutbktpr.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gttmirhuzq.html

[A04] 判断变量类型
来源：http://dali.yongpay.top/Article/details/gtqvwwtire.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.hfpthk.cn/Article/details/gtsippoezz.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.haohaochexian.top/Article/details/gtestsatkm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.yj20258888.top/Article/details/gtkhlbdyxa.html

TS:   typeof x; x instanceof Date
来源：http://dali.yueranfly.top/Article/details/gtdhmyebop.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.daria6918.cn/Article/details/gtwsfpjhgm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhixingplan.top/Article/details/gtromstnnx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhoulong.xyz/Article/details/gtjcyeqqbq.html

C#:   x.GetType().Name; x is int
来源：http://dali.shangyingyoupin.top/Article/details/gtfgsxvytp.html

[A05] 整数除法与取模
来源：http://dali.ppjwa.cn/Article/details/gtcqptxyqn.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.316326.xyz/Article/details/gtblccyenf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtvfhycuat.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.chenjidiqi.icu/Article/details/gtsgmfjkan.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gtjejzbmcf.html

Java: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gtbyqqkqop.html

Go:   7 / 2; 7 % 2
来源：http://dali.svipenyu.cn/Article/details/gtziagfyig.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gtrzqgomiu.html

C#:   7 / 2; 7 % 2
来源：http://dali.shzxlz.cn/Article/details/gtuksyqzot.html

[A06] 字符串转数字
来源：http://dali.c1oappe.top/Article/details/gtwsqnifba.html

Py:   int("42"); float("3.14")
来源：http://dali.wangdashe.top/Article/details/gtdnlgitqv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.hnxiangtu.top/Article/details/gteewvfqxs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zdqjudy.top/Article/details/gttmrroggx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.chenzaomai.com/Article/details/gtnafllvsl.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.gzhubu.top/Article/details/gtjfcmudly.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.chenzaomai.com/Article/details/gtrbymuslf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cqqwz.cn/Article/details/gtchbcjdbn.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.gaohongyu789.top/Article/details/gtljgkchuk.html

[A07] 数字转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlqsmcha.html

Py:   str(42)
来源：http://dali.zhoulong.xyz/Article/details/gtgkjibwdk.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhengqikj.top/Article/details/gtqmrtrwol.html

JS:   String(42); (42).toString()
来源：http://dali.yuanzhike.top/Article/details/gtydcrwwfs.html

TS:   String(42)
来源：http://dali.yj20258.top/Article/details/gtynvhizle.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.nwbrower.top/Article/details/gtghotjzzq.html

Go:   strconv.Itoa(42)
来源：http://dali.yuxming.cn/Article/details/gtylvakkxi.html

Ruby: 42.to_s
来源：http://dali.shzxlz.cn/Article/details/gtcfxcxbda.html

C#:   42.ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtploxgkxy.html

[A08] 取整与四舍五入
来源：http://dali.xuanzx.com/Article/details/gtebvkufit.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gtomawligk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.9152youxi.cn/Article/details/gtjauwiosc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.chenzaomai.com/Article/details/gtlbbsgptr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.sufxvd.cn/Article/details/gtakkbldtg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.feifeiyinyue.top/Article/details/gtjfiffcaa.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.sweek.top/Article/details/gtsdzlpfoy.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yueranfly.top/Article/details/gthemgtzeo.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlysqohx.html

[A09] 绝对值与最大最小值
来源：http://dali.jqgufenzy.top/Article/details/gtuvstxukv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gttnjboncv.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.meibo888.top/Article/details/gtzvbeabad.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtzjumvyux.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtjntcvsvf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtatyluknq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.jyoumei.cn/Article/details/gtnmpkjuer.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.snrcjt.cn/Article/details/gtkmknjkdy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.cheryme.top/Article/details/gtbfiuylas.html

[A10] 生成随机数
来源：http://dali.havefunace.top/Article/details/gthhcruray.html

Py:   import random; random.randint(1, 100)
来源：http://dali.chenlongwang.top/Article/details/gtzahaxlgg.html

PHP:  random_int(1, 100);
来源：http://dali.hfpthk.cn/Article/details/gttpuyizjx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gtidhbrcjo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.guowangkeji.top/Article/details/gtpilwxihj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.hfpthk.cn/Article/details/gtpjwtydfy.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.daria6918.cn/Article/details/gtqyshpqsd.html

Ruby: rand(1..100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwunhhtx.html

C#:   new Random().Next(1, 101)
来源：http://dali.sxryk.cn/Article/details/gtvfzwzjeq.html

[A11] 条件表达式（三元）
来源：http://dali.mhx1999.top/Article/details/gtcklfxlar.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.hnqzz.top/Article/details/gtonpwquas.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.snrcjt.cn/Article/details/gtrcqoltym.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.cheryme.top/Article/details/gthyslhoxq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.nwbrower.top/Article/details/gtmivlobjf.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.0kj1m.cn/Article/details/gtfutvddzf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jinqigfzy.top/Article/details/gtzhywydfz.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yj202588.top/Article/details/gtlhajmmxw.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.dianchejie.cn/Article/details/gtsbbkqndt.html

[A12] 字符串插值 / 格式化
来源：http://dali.zycfv.cn/Article/details/gtcqljwiem.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gttemvpgll.html


<!-- 参考信息 -->