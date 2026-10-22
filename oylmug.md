代发 wailian999

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqfcsie.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezljhbbl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqfjnt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmpcigb.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jxajtoxb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2czvaixxl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wniysbnp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwlqewb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbxabwy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2osgirmia.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbjqoch.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrxheuz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrtkbov.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjyddfl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjdddex.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2upvbmbrw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmjladi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyivwuj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pagvrjft.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkshrfls.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2abuskuxo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvezthz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeufdhh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mckzdtxs.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2knmmymgl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbiwkry.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhhrtbc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjwwwrj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsodqyhb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiadpsad.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiurkff.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkqpksl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oeicdhij.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kxamfbjs.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yffhksoh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2enjexzmt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtdomm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrbylda.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiqrjqb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2phitcajh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydupbaki.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fbckxfpa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsyloky.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkvvuda.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdhciqh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtjhnxw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyrdufw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfehbnb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2feitzqik.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyskceyh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjywfwx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eoleuuec.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kpllguno.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pploqjfi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdzowxn.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2efqovpjw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvirydn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibobjfzh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2btlvksly.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlzbmyp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bslyfwjm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhmgmqn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsevqtx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eflgvwsa.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpxlprt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhzsisu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2runagwqm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmvuyiq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmufnmx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwosgah.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnkhmwp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ijltibwf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qylxsjcp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsxjtjm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xylznsab.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eylndjak.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bznvksji.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eaukomvr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhoumrb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2embqpouy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2octjrsae.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bldjirst.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ybznulfd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsnfrob.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkbyemk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnlbmly.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwefcyhj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgdoweg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yevistvf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkpoqgl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iozffeeb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rluqfjzj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2emxgdkkk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwdhvsq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpaeejt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2prfwbasy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqmwzec.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiqxcyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjtprsy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpnmwps.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2afesfhsq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmvukor.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmrgfeu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2weirkqwt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnkbzse.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsyxzpf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahggoacv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hhepdpiz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvhyfyf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmsidrf.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lpauvkdd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yauoqgwz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxzxwsu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yqldswhh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkfuska.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtrlovm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxhzilz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoujxmv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcqtccy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmsyoyq.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbxramx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2agdjwylt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzesljv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2txgbgqwu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjwokco.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2horqdrnh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhsrupd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrvzlnr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lddnxtrf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfjypgn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmannjr.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqbltfa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ialgnnfh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjijhse.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlpmmnr.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svixijvx.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxgeass.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2pgveaqjk.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2fleplkck.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bswqyaey.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tksjlytq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfrcfzg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2knebottc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuduydm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtilxkq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tlovepsm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2svzrwgzp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsrlzar.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2wggynjvn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lblkfaoo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhevjcg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbmemza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcdhezu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xaycksnr.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyxtxjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmkznbh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2grocuzpc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2etqrksvi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsklpmj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmtfcug.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtncmdw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhebyny.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2fogzxzhk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2arvvewwc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2puvuwzde.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vqipztvw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ufciuoxh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2meargcxf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2uprrdisx.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkktvwd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2orosczpo.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2obnkzami.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2opwhhflv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjaewnu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhgzjix.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqxcxqm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zystlfxp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kecmavzz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjdzqfk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpuodlj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgodsuxv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nupmeeca.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyetimlg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdshsikn.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzglslf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkzptsd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwubgws.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sifkfnaq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxtbcbp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrsfgvg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqymugjp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgsrkib.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijemcqcg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rboabebk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlzamsh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oilhpvck.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bertopct.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgglqix.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfxulqo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzvpzja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcxtrnd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxwvtqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfzwdyu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nuybxpdv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2pukbfiuk.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpozcpt.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aovjgwre.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfstocm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qendllch.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwhnnlg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sipwfojv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnedhvlg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2glbxhaag.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyzokza.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fibepnos.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbxxmnx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgxyoly.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eofjaaee.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzxxzfo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtqobif.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfeoeuz.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jslcvnpy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdvrami.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsvohgl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuawfmz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbksxhve.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygemkxkn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmmumez.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2imqspaey.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodgjwku.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlfkrla.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqkudgh.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdohqalw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjutuxf.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbulctc.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2caklbgip.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtujtodp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2eolhbgya.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjpfnkq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwgrooo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pudulihu.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvwncyo.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmbkobk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqbrzia.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnnflmo.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qikrembc.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdbqakq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpfnppr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcctneo.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2plxxwijv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsllvmks.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgtjqvb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2miatugpr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgrgqus.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2vygsqoer.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmefwnm.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2purtthhs.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqriilfn.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdujezhz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsdfyim.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2novhkeeh.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aciicwtl.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2amihsiue.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zneytejc.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhojdmw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyikvxh.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbabvvv.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfutsda.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqxkdpz.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtmkrvf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmoikgk.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyxhcve.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvydyaaf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2torlpiag.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkzlrvk.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2joigvlkh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmchkdri.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjaopgz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhveikkj.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmitjbn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzyqwpe.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuyirdb.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlwpiqe.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nninzvai.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxqvolz.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmulagd.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2skzrkqen.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyfylyx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oszjrkea.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrkthnm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbiweln.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwjnlbb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2eddaxtqt.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xarwmgiy.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktilugle.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnhdqsd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylissuay.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2biyvvsnr.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2tngtsrpw.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xedtccdk.html


<!-- 参考信息 -->