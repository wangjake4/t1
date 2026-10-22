代发 wailian999

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqnhqlp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2slernief.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkonzxn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqwlyni.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2scaqikkw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjuqtmd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2erfyemgr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtcwgsz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlhnhmj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rtykyjwj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2btmtohhs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuphrtln.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2atylmcru.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkepxxi.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wljdlyoi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sevfntid.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbisjpe.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2spgrzeif.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2owafmmns.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2msjyxmai.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxirgl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlsrpbr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfsgnzc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgteqze.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfdeupp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2scsxtebk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmknpwu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vshcbxgq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvhvidu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lwayypwa.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2slbuawge.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdowglbb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nizamsda.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wibxjgco.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2caxcvbsj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrfftfa.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2enpeqjql.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2amepwjql.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeyndqx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuculsa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlrlewo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoqojxs.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsdbcjb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjweaic.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2trpvhdeb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkvzrcs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqmoccs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tadimznz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsebjui.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgpwloz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqdmesl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwizqrjf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbefxnb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wspoecjd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmjqkvh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2msejeirv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwrufle.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nebnqqdz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2osgtfgrq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2wobvmvpq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qknlvhlc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbekpbc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2milbhqgu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhawpqg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2suxmyvpc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2namrralu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvlkhkv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gykfgitg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqqdmbx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxaluqx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vexlvofs.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbhfqfu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eheuickw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrdbhmx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2whbmakle.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pigrgfei.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2urkktsam.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeionneu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dljqbixs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaoptns.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoylweb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqgfymu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2paymudla.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tubzfidj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzcedme.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrwvobb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2funnuhjt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ogwjqxvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lflrqunw.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2imgniwdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csopmbot.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oachncbr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wavalgaq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvespgy.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyjrdiw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zonwasue.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qujkmpmi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mecnrdkx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbafvpa.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dltxwhjj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kamvzdgj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bgddekrg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nopuejsj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpbpewc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwslzvy.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrxsnxu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaoserd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbfgcub.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zkilvccs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2izxeaxrq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyjayxa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2uffxoqcu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmnfcjg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzfgfci.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhfbvaw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhvzahg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sakgelzb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2paqywqyx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nomrhyba.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoskxjo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgvbmvq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2blntzlnd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyqvemh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sluhcpli.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ersptznb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2naifumsy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2iaznfbnt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ydisnsvm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtwefui.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxsvqzw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2syvcxbgv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vlczwedf.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qfczvget.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnuhitg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yakiwrtu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2swzvbigt.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtfvygz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzpzyfe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vnddqcsz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsbgbxa.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyapnpc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvmbxtk.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhlvicb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2szjzjxrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeikxgri.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lybxzcvy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwrsign.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbawamz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrphsjt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhoiusu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkykqie.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2paywbvds.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jtilfdht.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qiucwizr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hudlhddw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tllvbktd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vlovrxat.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwesugw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsstcnl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mohjpdmd.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrgnzbz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbzredj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjqdowm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiinmfg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mkenbtow.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2izcpqysq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyhenym.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpvvbpf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcnszrt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrzssfc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqrknhl.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yarygsnd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaruhhuy.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnpiftp.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcakznw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjrsvkh.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcvcces.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfcjmrp.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwunuzbk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqiurth.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjxxubv.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsfonde.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lifvmqmf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfebdfm.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsanyso.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeufbwc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nystjcth.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2icpyikrt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzmqgzw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swviixvn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsyleym.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iezhfzcq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cegzridi.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lytqlhbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2utnyppng.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfcephl.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yitxehjn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2epaakoth.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wymrwtym.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2noyrrywu.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2abxcxpdu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcyowio.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwjejmr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcarcghw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmivago.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnmvsou.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwhpkco.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2candzgsr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oogpmpkj.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sctdbykh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvsuxxc.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2byrqlkcz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uudhnxdl.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zeocgfkt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uzryuupe.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfizdfzr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iojhahfi.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnifutlc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czeqnyaa.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lklzqdgy.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwkkgde.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpasqpwi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cajyziox.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnigxbm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeolskqp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvjiykq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmzydnh.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2wscgsxod.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwnajue.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nndohbsg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhkhzld.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2mftyydzb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mktfmgyt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jjihxyrq.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeacflwz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irfuflnp.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2towszdah.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kodotggk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbammtyc.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktaxhpbw.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nxiigssj.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuyzeij.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhulqyey.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2edwaznzt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnzlfyw.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxrhlzx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeokkybu.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwltins.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2txjzlyhw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcxjgiw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbcysng.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcfgntz.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uitfpdzi.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxaoquw.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqklqywt.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nldydfeb.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrmnlai.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlsnngz.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzyaytr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftregfgy.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otdmwcjy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbqrfsl.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lokxsbwc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iemdnkcm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlzytxf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2fodsonqk.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qunrjasa.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2irotplxm.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qarwzeny.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqnzwdl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eityhzbl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpkiqdk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rovscubi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2eplnwmis.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2qifrqhrz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avrxbwmf.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2eeyrqyyx.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2yojwvzuo.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzjplbu.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zuajyopc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aovwvrpj.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdelrsm.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2flujsrmc.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqevrsyz.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2domkvmyh.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjddqskd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iycqxcbf.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmwdpbw.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2bleopjnj.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkykcyw.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkydtoq.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2cxryskvf.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2iotitldt.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2qspnggwl.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsteawf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdbacv.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcnhulm.html

JS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwitoca.html

TS:   `Hello, ${name}!`
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxxozfp.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwxlkis.html


<!-- 参考信息 -->