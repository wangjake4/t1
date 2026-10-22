代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpqabjn.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gyinbtpm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dkitbyhu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqasipm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrtkyby.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcgqmiy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2etnzrjla.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeviumt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrnlbct.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hbczlmow.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2oymadtui.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fipqhjgm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrvzjjt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkkzfvb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgnatzp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2djaobvmj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvpwpjc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmxqpir.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpelbug.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpfhpbh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmxjmfn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgotbjua.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtygxxo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhdefoa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbormer.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yextwwei.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmgpokg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2okqloaow.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvkioqr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hvubjjtd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2afyzejpn.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2llupwbse.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2juankxtm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2evnvpwdw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzkpoov.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2stmcwscy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iukcekwi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tssaztih.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xolhsuvd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkkihll.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqdewht.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnulklhr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmjdqxa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pnirafka.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjswvyq.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpsxdzi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cthmiowy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgcxqeu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sldidvph.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oimahwpy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpcdiso.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnotaap.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmkbdpq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuleoetj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoladgd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfymjjc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxtecvi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfemptr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ludxdkqu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ovspvycf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wdawaznq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpgmjcq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnxfzsk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdldehg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvdampn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbululps.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dajbblum.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcawojn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvzcodb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvdjfkt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2crmnobqz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwjxpdh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lghznurx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2whztzqpg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kkylddbu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqmmqkg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oslmmrih.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2blmzvumb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kahcntno.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snlwfzac.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2brcnieng.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbydcfp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2egjgyjqb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaavfec.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tocybpeq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zywaarho.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2iccjyotw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrmbgmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyjtcep.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ebertvdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcfhzom.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2clveuetd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwvybmp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2simuodag.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjlfnuz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbebtqr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiuland.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2idyletvz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsilxhf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2youcpfok.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsbixba.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nldqylmm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2emxfycga.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ouieyztj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhjcvaa.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2azwfzyzs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hngxbatp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhtmpnp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2whhrslaz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2appqaipc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2srxrpuql.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2dogjkqnt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2myjjzjzn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hiptrkyi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fatmvakv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2auqmvpuz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2faljpzbz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtxotxz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjbamxr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijbrpo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2odsxbqgl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtxmogv.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cprkxgkv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jptxpflf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lvypejna.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vttlwxlk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxlbmsm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2neexibes.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjcuume.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzrytjj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkdfkdx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2awxejzgb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbgiepx.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xjuxhffe.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjgxyxn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2avoidbqw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdicigu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxkbqhh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vayqukrp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kqusevgk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkkrqew.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2crnnhgjm.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhgmqtj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2buajjpan.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2damxlacc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzglskgy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2upoquamh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gghftrpo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zucxelpn.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbxxroh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jefysfox.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kucyzase.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhuuptz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnoczgm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wslptubx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mhylxpxe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhjoxgm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vtesyteg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlgeihw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxuzozr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbnezxp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcchgek.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pipsofuu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nhayotyc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwpcewq.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cltlktfr.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjnuqfl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2kucvhghu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rvztrfyl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nswxmcxg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhrjwtj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdwvnzd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unonirqb.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdzuzgi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtfsqgx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfmtrex.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eqputwms.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbebnju.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yweodobw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jydsmgvi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aeebynfa.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtuqnzp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhirxhy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmjwbpf.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pffyizjb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyyqqhc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxeaaaq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ootlnjuq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmnsbix.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgkfgsh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hftwqjbo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qamhreau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsxajav.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qleowtsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzkhdun.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmovdja.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjscfxlz.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvbigma.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2balvawxk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxedqvr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqznkgcx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssptyseg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxxsxkc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmuzdum.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2dhakgzxe.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2anhlcbwv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhekzbhf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjlxkih.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2twephhvq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxswtbx.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2crgkjdqi.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzwvlng.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uktbujip.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aukrdofl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjvdegl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2clcayttg.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjpfafl.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2punqgosb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cevpphxb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oilacegq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2symfiivb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2twqxqbrr.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmkipez.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhrfxye.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjoabxq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bdraaiem.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2iguacfqg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhxymgz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmixxxez.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgmtrmu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ydptofug.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaqjher.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyyojam.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bswmodhu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oytfkhxt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2udxynwhv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxzvywb.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlvxxbq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwowiuau.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olrjrnkl.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aewuvsry.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zktfmvjv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcryedw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2spghezfj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtotdgr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxjgtpv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxnnykx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiotfuh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dytznarb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uktykgzj.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbrkdgr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrospgpi.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcedclx.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjmbhpe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cldqerja.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeryjudx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzahtqq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnloaedo.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbagvfp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2amytvvgw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyowqch.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvrmze.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgvihkp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eznxpjnv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgypzxq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnqzzgi.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiipqgib.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2riwbuamc.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsaqhpp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtncugf.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbntwtap.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qapvetty.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhlxacz.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2noznyuib.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2oomgczno.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuxwjgz.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dttxkgry.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2agcyiwue.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfimvtkh.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfadywx.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uiktmnav.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nuulliuf.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2cakvacpl.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhblfko.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewehwopa.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zarygltg.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2odsgveab.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2yimaqfdh.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gagiptas.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvakbnk.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsfpgba.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2mxckroqq.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlfcwmm.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2piywcdfc.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpgjwrm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2juqtvnhb.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2brcgfbcc.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaismni.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmrcbfe.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhinwyu.html


<!-- 参考信息 -->