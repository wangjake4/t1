代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iscjosjj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lfogmoff.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wzraldgf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbahehc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fifqchvq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2evzsifif.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvvvty.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2llijuulw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjkarop.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyofbxr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2shvzjcfs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lzreqdeo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmghneg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gfziyjsj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyfcihg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkzouoz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2weaecjel.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ncavpdpv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsxrrvf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddcyahdx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcvnbbv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjyqkxb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuqhqaf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmhcunj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmdwzmn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2svfitylc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sksdhxhm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yswstdwg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tatrjugd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mktfawsv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uojvsytx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kebwmyhf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwpxzgv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vllgiqjo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrgzqho.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuxlecl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqlhxio.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ostdsxev.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhwskxt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnpdqtq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkoxqoi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lggcdmee.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kawqiejh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiefbrsy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnawjrw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ietaxuwn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2btklyxnc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdhhrdp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnjtusk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiyeysb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcwjkdu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kudkdwkr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxegnnv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkcjmcx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjjvgn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2esdtigip.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqxctub.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhgscwx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2miijyvrj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjtmjtr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkpqxsz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaooxsm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhewiim.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtspmzj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fafqjzvf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2syealtvi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxcqwfj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gglvnxwa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xoedsnmi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jymlnsqe.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2aobcjhej.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2cspahuzr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgyiyhct.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bazoxbqi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2npuwqlbe.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2coqnsfen.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdxaeft.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrqvsgz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owcahsbk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpjvhlr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwnbust.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxpivge.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyujsbe.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pscijbll.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2drjjifqa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2otvhxwnz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuoxrxt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cayfeqgf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sldcnphh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2whnwfjql.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjangkmp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2jkezzduv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzjzfwz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ylugzrqx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsaycxv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tskmzpek.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkqjvuv.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wewgzgnd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2azybiizr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiuyqik.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnwdbhs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzgnzwk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2shegvjey.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aosvrxhk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hatjvxkb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2epyongwo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqejnal.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fizrzkmi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwncvox.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrwdcix.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rksqfrmu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqsris.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vrseymms.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgthdwj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2judducwj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2bughxfzk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jsouziiw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tklunqnb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qsclksxp.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kngcboln.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuvixgo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdhugck.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmiyxpo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hsipmwpk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lycvkaiz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuavxoo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrrhsoc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyleazd.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kxowmkwo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjsnnmi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cfobipfk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gophzdxe.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ywibevlj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rxavzkhn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfowsfh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2alzelvcf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlbhbro.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vaspjeaj.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iyltgubp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wkziyrqs.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2atdtugrd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2coqbdqfi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2iiswqtxn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2sicgunco.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqaatit.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbihuci.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrnqjpn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqghixb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oywxzyim.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmomxdfr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtxllyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtorftk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvwbwmq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rybmsabr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2maszxugd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvzcjpt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2svkxmtek.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nifhcqpi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2peexcwdy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2knicjurt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfspkxi.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2rctujdcf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2siwcwqri.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyqlyvy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2strdfial.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfzhsrc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2avfxbuax.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqpdxkz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtacbhb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2soqhyrix.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhwldie.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ryojvcim.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cslzwaea.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrzyuxc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdspznk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzdetvv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvutnpz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tuejssbz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rliyfjmu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzsjyhl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iehuoflv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkshlbzs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjdjzcm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unicvksf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwhqyas.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecihhlfd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjrezxz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usrnlanq.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kggbhkil.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klxkkisx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svvozrhe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqhcmzg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aougbczf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtspdbs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmkidsp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eunosfcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agchsscn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owlwolms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2moknoima.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pokhlthp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpmrjp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2alnufgnv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qynhhsuu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzblqwh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxellume.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qphnfkcl.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsselrkh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnpppvc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjpooat.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2chuuaarh.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlglwubw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2svvfulle.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxncsrlg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtkreks.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwdezgc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uydjdupa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fknkzolt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2guywjzew.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wykdfrvn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxbgteh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvcwdaf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxprwdl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmhgyaj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyhzavk.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2prhrncdc.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvokuaxk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jblidsvl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzetwaos.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckddxfpq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfecuhr.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2aebktrar.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsszopi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaqxclp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwczklho.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwgidue.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpjhtnj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdnrqxh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlzsuuq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwqzksl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ingtjkqa.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnztabk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ombehftm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aoafnxfl.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hazmkrlu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eanszytn.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2foloaock.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2phfejxzj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpmnigq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ruydqefm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnhfpka.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiozdhd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsaznhq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvrzfba.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2darlrijr.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccoqdbt.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjdzmjx.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuffhdl.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzknqzh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvncaufg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyndfwvl.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hponzafb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpulbrgk.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2slakvrai.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkttqqg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwyegoi.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkimcqkk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2knnezjqk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2enulrrhc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uevvqvlu.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lbagmnff.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eltxennc.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvygarrx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnmtmxf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2byspqzqf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezynycjz.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cklahkrb.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2taynhqem.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2qdnlnrsq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2joudtuco.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luvtfrcq.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpjavap.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2shpojpid.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoxgusf.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwplskz.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlicctqg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhukvqf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2psxfkoyb.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2adetkjgr.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2egagrtkt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgszlope.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyauwgs.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcqkosj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcumnjqx.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcequcny.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvnqmkjz.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfkrcwf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hynqysfc.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qabctxgx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wlezsyke.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqvewkj.html


<!-- 参考信息 -->