代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrunjxr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzglfvb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuyfibg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyjypda.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2baxjnjui.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2virfaeez.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dshaxplx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qktmgrsi.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2prvqzbsy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2busmvjzc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2takajbxo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmfkfhe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ejufugty.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wicnhtxp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmsfnne.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xruherip.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2metthmaz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhqslrc.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqtizom.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vhshdpai.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2evwmdwrj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2szhkjkpb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dircvdvm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqshhil.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2autkpzul.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmsogfl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vooymylg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2delgejjs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzxzkhh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2arsqkskm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zjowvuzm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nodfydlx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvvblqb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjihcnq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfkxmil.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbxvrof.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaelbyr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbfbkrv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dniuimjr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtigmuqw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2euywkhyz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfnvrmq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rumxidku.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqgfwow.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ioebynbf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2whvodxsr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ristinvh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrgubts.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzpdrzl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmgcqum.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wywesmsn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2aewrlfwv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2psejlhmp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndrhodd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpygytc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmxkxdu.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2emdxfwaq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xekpudbr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlezzqr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuujzoo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2esolorvb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlczzdnh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2atympxfq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqiwrbu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oclpslof.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2njkrwvzj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mirimpsh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vhighcmb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvvpywz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2twxtcwcd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gawxmvso.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehajgssz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbtweiu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuvfpnd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kjndltgb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwoltutg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfqkfpv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jctmywny.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmblkfuw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrvpwek.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ygommgaq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ccthcvat.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jimtfwdh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nasylguh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tlztazhu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2joywirjb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nypfrfbi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2palymrnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enomijaq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwyvlep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiwayrb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltvefe.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cshzzllw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnqybya.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pszbkegd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2duaotstq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jrinsjgf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2itxfrlao.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjybwde.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpqwwcd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wvimiidk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2htkfxivt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nkncbczr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxqgoyy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqladxz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kcinagfk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsdxsaf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2craqsjmf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2stgzdars.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqpzhkx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nstojzeg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gbheabjy.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zmptijfi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyqvqqk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjypati.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2njotelnq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vswmvatq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nxokejrp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xyydxcgh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2crpvmarh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjcowgc.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rysyewmj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uajhswul.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aqiapnod.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgkzvyc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrcmcir.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsrluct.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkvpmdc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xmihowzw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2radgdktb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lznprsyb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyuqjcl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2auljdkww.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjtofvk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nfarzjpx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzvfmjd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2woxdhfug.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfwjtdo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2alkcdlky.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxmdprf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzphogl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfmmvxw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zapcbfqd.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2thjovsue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wubrpbig.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjycggja.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmhqnej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlylwzj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtarqys.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2iltfimdo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uoppnret.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jamjthlq.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bafdwduv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqkuakj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2qieegyhs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ncotmgqu.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lehpnppj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qzygtmvh.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnhkzvf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfblmqo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xrikyigp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbpenbu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcidraan.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2uftgstna.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2resvxidu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwqlpqr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2epcpqiir.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivijayby.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqscjej.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2refliilp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qrpupsjv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbapuuj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnjunwd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrbezst.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2igjqccdu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcjcnsc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kacrddft.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhuuzlo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csqxuydk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkohhvov.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbusvbyw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2imckjzjf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjqvpgw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2okdejfqj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qafbtngr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsqfzau.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdunest.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhyemva.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfqkzfb.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pknxduow.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbjrxrl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcefpxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvhirsr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nlycxjev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfpoxmp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dapjbzwi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lawadvem.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiycwbs.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwepcso.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdiripv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uenrsstj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2asirtxna.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeyurfp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2onomrabo.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhpiwnd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2narbjwwx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aebghhdh.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vakkpagv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhuglmf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kevvfduw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfdgshf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsbvfqe.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzpadey.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2crrsmyam.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2fcovenkw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcwlbuu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcbudzm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2webibyyv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lesivynj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xapmvowb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yjabhjrx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xokygctn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiboheg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfinaju.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfivhly.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oztdwuht.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cangfutv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdlpvpo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcotand.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcnxbmg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcliknr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxnphqv.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqpmaid.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2inakqdex.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uawngrbf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbgyxwr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxlpos.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qlazvstg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqioqung.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xyurtgvm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdztchu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oemzayux.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2djctgacs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtcnmpt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwexugc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2opgcvpml.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zikgqiwg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzxiahm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvauqfx.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tujepehk.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2umvyvofg.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hatqsylb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fasdshod.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmbbhxj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeklqzqz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2npvgfusu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2rgteiwbx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2efdlmmdq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2mghfigdh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqfbiwu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrbkgkc.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtdzmfq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdtlnci.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmldwmby.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojynhqyl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsebcnd.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtzaood.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfonqhmv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xknobzjx.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcziipd.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsvkcfo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnaufzw.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wttryypx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2agydcrym.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2gthgxpdj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzetabgf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oswztrgm.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxnrtzg.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdvhtkm.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqgbblv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvvtrit.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcjfogs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2chxsbwvz.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlnhmfh.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2znzmgigu.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjruifsm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2algjvsfu.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2recaorpe.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsukwsnq.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwykohji.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxrmsae.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2axhzzjuf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2carwvznn.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2henrmixy.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxymnfa.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgqasqh.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2svkkmuty.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyludkv.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2psoflxvk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfpfkko.html


<!-- 参考信息 -->