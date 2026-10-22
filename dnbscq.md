代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxzejxl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvbuaib.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpyggwt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxtwrgq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mfugqtxl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vlttepmk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgtlnsl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ggddkhqm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xwskxadl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ooewusde.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dkihjzwm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zkflzpvy.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jdathkhw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaadcjq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iuacwecg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsahabsh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vroptnrg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oytukrwh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwkvza.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcevjnf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzibyfb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ddddwkuj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyrqvtv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxuttaq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2otigvied.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kemokgwf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjvekmj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfybcwl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2atcdnbnp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsvbmlk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqcnyls.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxthsof.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nrepnacb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcudrio.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2czagqexo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2erxnnjxz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlwgsph.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zrswkzko.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpuenvf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoedgrcb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vguczmxp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhmtzit.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2msdvvpeg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmjhsgx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaqqfit.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcefkxb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gchwljvd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2epcecsjh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvdcgcr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fukyufqq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hykdirmx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ethknnik.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mampddlm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2erkojkgc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfwlrff.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvzxwqa.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvfmhha.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkurrunu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nocjqdlc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yiayqclf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vsccwvpj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tybzjpaj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2teiyodtt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbtimpj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2notavtjo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vppuszqd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfahggwg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2orqnjjsq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pstfjwym.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wywyqpmv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2drmvtdzt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2annpqjly.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mytneoxm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxsiwxy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuunltm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uobshqsd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnsfogk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvwryyu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wkocuorw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2czsylwkx.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vhleysjp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpqnfoi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbepgkzx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhfyrai.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2umpgflbu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjfnsgr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jllqoyov.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bytiymiv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oibcjcoe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpnschr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cggezjpj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnjfpno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gepwbxvc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ljukdkvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqjtrye.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2afpirwud.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zagiqqdn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmaxick.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkulqcv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2digzmrft.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsdmziq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ftryeldr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2txrijyhn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwkhqpt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhxcvau.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnsiyjl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2erzhzttk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2zqejbcdk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2doekfvmn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fgovgtdn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzeeaiv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxkdddc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tkruxtnz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yggbeuux.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wywscncr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bigvbhgi.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2otngyyzc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hrffhaon.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vdftsdhx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwxgmsy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ajutqjfi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2psspudnc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hquszclc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnclypd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdrzkvp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aziaunte.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhiyltd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjwuwzp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2twtqxiyq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuxckky.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2moteinka.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqigbzm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2itkthyjg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rifcjtvh.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2edckjfvn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcvvfve.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfdscaf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzwclom.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tfddlimw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2expczjov.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vremmmxy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2khcawnam.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2cbinujnt.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2budxbelu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqzaodi.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2swgjkfsh.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2iiczyboc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2amwanhgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afobelae.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhvxkbf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2uppktidk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lszlwsdy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyvsxas.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrcvfar.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2knlesuur.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdgtumj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2fonxujxb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgruvdc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mggdubyd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eefakfux.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ocliezcs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsvzuil.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2huhhirhp.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiapwwt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxjbovd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdauctz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbtaksh.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgxigrj.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2glgyecij.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrnjfop.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qucycwga.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpgblhp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmnmszm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nnljtnan.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnztwru.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwghmpvv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjwgnox.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srbjmygv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njjnlcjh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flgkggvx.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ainobagg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kaafsvtu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlkjxft.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylagfaai.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqihmvns.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydudnvdx.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksisuifm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzaibxo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wregwjhn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pfakvpfp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwblxgv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2agibgjqa.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfcowkj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmngxrzh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztezjxvd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmqkufa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jmicjzlw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmathxzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fscwumfy.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhqjcqg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2hakwaibx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mngicytt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdrwkhm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhawakw.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2budabixa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2okstllqx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlrtcgj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtkpxdn.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2brwardli.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2khpjzzha.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qexlfnna.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnolxasb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxelkgv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxawneqb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2amqsgskh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2asdddxnl.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfvxkdq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdzzwnd.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkgwujg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnydjoc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czsxdogt.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpixyqla.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sztfaqgz.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdzrfug.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnjtrvf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2acinqkxr.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2whdocfeo.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgszbaed.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhftpdy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yebwzhhb.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dazljxws.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcxftiv.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2pujkaxqb.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdulkss.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jywbpstm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2luiikfoz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjgcddg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsiiche.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vydfchxz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxjgzsa.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhebkot.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmtlgbg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agcmvnsb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fbggnznz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnydqzv.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zthkonka.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzuulnh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pitjhrdr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsomtkg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaacdid.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzyplfx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxvtlxz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2smojxclu.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2puovygoo.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpazygqo.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyszlpr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoawxpf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2etsnxset.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnadfify.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2golljutj.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2aynygdhf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2spynwcuc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzgyugu.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxdedil.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbizrzea.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvvktir.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuqakik.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2agofkgjc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oosocdfv.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2jfijbwmn.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2firbahcu.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2euurwmtl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2henfzahe.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsgteou.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgebeyjn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqonitb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnrijzx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2spkhbjvf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2paaikxod.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxfeuyc.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlcdllo.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbshkcti.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqngnlz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhyeyzo.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2njeyovqh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzkkfnp.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2satzdiyi.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkeqinq.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2whwqffrt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2wivbzdsk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2meiqvwqk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sienhljs.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mykwkbam.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2thuwvqtc.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dburdqqg.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2edhaelka.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkddzbaz.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2mddeeidd.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2swaakfuj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtjrrpi.html


<!-- 参考信息 -->