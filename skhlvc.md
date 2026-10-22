代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pkatzjug.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmuqpcn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpezmvf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmimofqo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2kweitxqt.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ljylnezc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mbugibkn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwliptz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyfnmxp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lzurkndb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqchbbr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eamjcfjv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvrwmxe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgtrljd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lpakzjzh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbksrmal.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2beodyzqo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxwegau.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuvxbko.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mbythmsz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpnimau.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jrruzhki.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmzlgjj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpnlbiw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqzxzdf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2saduuhlm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwmbwfm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2knnpcbbq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2busjgoqz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pgblrigq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkumxpo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrjxwee.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2syzsgzlj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbhgdtz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2woxmpwqj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjxwkqb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kownskla.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwqqqiu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgowtdxg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zamxdsex.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgriuwe.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaprgfm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzytytw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlukcpxy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2khnvssbo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eykivasw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nhggvqvc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xlswckkd.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ysntgemk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgcqfdo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dqveunxh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaaocsm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmywauy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbxwmvw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iodfiwvp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlxllhc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2smfaxkny.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxvvwpf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbzcrlq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2szudfcmm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2eipvtgog.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaiyndv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2huxvvhwn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhwmzyw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kjikkhos.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2csctcdzo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvhxvor.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvjjtpm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kshfuvti.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2etqdslrg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuoztse.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wlguidmy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hngbzqys.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaeygqy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeinjyr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcwaqqj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvpanew.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwxpvrm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpbndfs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkwvbxa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kmssnnvu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgvfcqy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlnktmh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eapzaqen.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfgxqvo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ehegwptz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ccospabm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjfyzvr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2clmejsrj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gstomzva.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qllrrqwh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjujnhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kftjfnbj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2akwnnhfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gadzucdx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2teasfaqd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlxuqiz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmpmnhk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rrslxxnz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrfezky.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eestpynd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvehqhw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jpagzpby.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2loyxwsah.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2omegtfhf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqopzeb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jihbqyzf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rmngnrml.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2olvufcxb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ziogrxdp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrvrcfh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xpalyczp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrymurw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vxauidcf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmrmjid.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopipen.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nazwurqr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tphvcytz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xycazcgn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgvtbmi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgzxtvg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsbmydk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cyessigw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxgyeav.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmqodjm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jlahmkea.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsswdanj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuylynx.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbvekfg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmsljet.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2olzzehgi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtuyofa.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrsnbgs.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2asifnpjx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vwihepmw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtjhlsc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpuptes.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgzxfhx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vduuyjpt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dekofcyr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2regjdevo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lvftsrml.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdzluf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2oehigryc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2urmmhoat.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfurhcf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2tflwoucm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2cjipdjnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eaozmcqk.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2miipafxk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyvaiyr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asxvnmqf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uddgcoex.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhleffs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2cevpyjcw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2alklcmhf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vsblwdxc.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmgsxgu.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2exycspaf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jccjfcyj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtqhnea.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cucaqpsy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2waanvudv.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2prxdlcsm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2cowkrmzf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2axoqdqtx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyglvzm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jroqqxsp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyspvqp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxlnxwu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lrszusrb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rosghudf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmcvzrr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2blajtxgn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wttllvmt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vckyajeh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifodzmay.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsplqif.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwevgyx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nclnfmkr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmaearb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpurbba.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qspkllje.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbnsegc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2stjpupji.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guleahur.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2naoyhslu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2btcsvyls.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hflehtap.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxopffcx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glgwebhm.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxullil.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxqggga.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxezyvbq.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuydlfw.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2goywexdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vnexzhha.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lnebpxzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bitbsymd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izkzjtkc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwtxmbh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkemdat.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nseynyhm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xawlsrjq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbfmekg.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2diwrozpx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2utrdfosq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjdsfgp.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2abegraek.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqszlhe.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnsveut.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lohmuoqi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qowhevyx.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eapyzdnq.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwynfvb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqdutic.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2egyduzfe.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvgktff.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmjsrlg.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qewvrmyh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzokxpxf.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdweeevp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qscxnakl.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tkexdlun.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2auwqfnoo.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzxwdyq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2caqwmocf.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjhqwiu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btfqzeue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjahjrm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jrinemku.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zddekeyu.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2fazjokjz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyxzntn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmtqcmu.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2lslrdkpd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bhksfria.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaglygq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjsdekc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejonjuot.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rpylhhtx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2obtzqphs.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afiqcolk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2seizamho.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2flcbejyt.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2djrkhbac.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkeqnzu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dexihagx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2trlwzacy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwfdtva.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcaqkbe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kmslwmex.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlplnhuv.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvepclx.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqzgjzd.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cryosjvb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2quhrqulq.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iizyqher.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtazguo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlqiivp.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxnorri.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rivcrvbt.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbeirjy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfjlyyu.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyknvgll.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyulrmri.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvehwop.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlovsoxq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtyuira.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hjknohrl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2btinpduq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2grdttefi.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvveywbe.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fttadpwy.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2atmbgfrb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yblgtbqc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmfagcl.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2okehzvpq.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nzawzhxr.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2taeacrzj.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjsrkja.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgilbzoh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvawmxo.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkxmwui.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xisuhlfg.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeafjwo.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdqiinv.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgihtxj.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhgxxfr.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2coqhqvcm.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgfrxiz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajapgsuj.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2shcbmgab.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpgxxly.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpqazho.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2orfsiqqf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbvoaho.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tahhbqrm.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2leotscrj.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfophly.html


<!-- 参考信息 -->