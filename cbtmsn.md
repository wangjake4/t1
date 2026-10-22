代发 wailian999

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cwncrofb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2opkbetss.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hahpawbh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kadiabbq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoirgnh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdsmbqg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wiabflrb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2atimrbuo.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hadsnmlk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nomyljhd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqjvpyl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2myhzatct.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnngpmv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgvnpiu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzxfhfh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mozchqgk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwfczvc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfndaewc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xkygjzzm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfoehhn.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xyslijcr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkakzvh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bjekyden.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbuqyey.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfncjuo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqondreq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrqhrwu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxoldef.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxzihsx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrhlrwu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbipeuh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwdaljh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnucla.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fuasgnzb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjfnatw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmqklsn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtblqezy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qusspsyw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkpcytd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2usvghnoy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2unsnxvdr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhazufy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxykvtq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njtblzlo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ykszelrk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvclgif.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pxabjfac.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgujoso.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dsylpxye.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvwrbqj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2anxwxwgk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2saqgjest.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhtkyyo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzlziri.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhmiwzt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeutmxgf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkuhqad.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzccpfim.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hlarmqgn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2helfdijp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiepdaq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yycctgxf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pytevipu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zggrqhqk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zlijseqq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvwqbtk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2etgvckzi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlnqnsj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhzarel.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcvntuh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2slxmmohm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyuveks.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xlksluua.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfhasbn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvsetcj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiifbkh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qhffxixa.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kutxvapx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ateqfuvw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwehqysc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsptbyj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bikwrovv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2agtsqtyc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grdxtmmk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hlylhupf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rnckcwep.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2alcgxtuy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wvplkjss.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbwdyxe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2frxsflqa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2smpqgyfh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcpjfxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txtublhb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ujntiiwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmrxoti.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vqloumfq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhlkuhq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lmabdevp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fhygyegl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jsozzdde.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjsmtyr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2khimaqay.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bublfmcv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqisqsg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2neuatbgk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgpvrvu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxztzgc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaezoxt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mcotnyja.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rwggcmtp.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzjkoma.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdciich.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2myzikpkm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzwovzb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rowutcho.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wurovkty.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rtysrfdl.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhrcqpi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppzcvn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eydayoen.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ywikrlqs.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlrhsjc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2trpoiobi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjjlptk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cvshnois.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iavbmdou.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aqecfcam.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ixijkwqk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcyakth.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwznlve.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2okpeibrb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2itzvxnja.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yohmfqjc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kviskkwa.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2duieybxk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2exudyktc.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2camquzii.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2laajocwo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvixwcr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qelmpbxa.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ztiehqrk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dwajzfru.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmvkgwf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhucyly.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjhypht.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yffuaqcr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpbedse.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2npffxoay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoolaqo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhgfccw.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoyjlox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsqpte.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gccctfvf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yoreejin.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaskzyo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnwtcbe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2whzrdqux.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hceouvmd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqkmtjg.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmsyffp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxnhfpm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2curmplua.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rfesvahw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlhtivc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hascvjjk.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2grumeayj.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nxevuxma.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwjshbv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2enkryrry.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqcsyxo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdrivjk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmicrjsg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2saqvgwcf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpzoxnb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyjctup.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqwqbry.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nekkbfnr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqkpjng.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsslpdj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuiemuub.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpdfyjl.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuhiayq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaigrhc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzymjdz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcgoglm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqidfgn.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hurotyuz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocepqisy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhwblfx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdhtpud.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vryadqdi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esuoxpqb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrxsiop.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrvqmfy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pilldsqo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiygyrxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhvjgww.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rutovacc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmrnhgn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzaaacqj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvdzxzu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2atjbtstu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xuceagkn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnlzuyd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iylzyepq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhlayuw.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhuklvy.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wypuddgc.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcjvsml.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2utrumatz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhagaeu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibeuhmaj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqczwdo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkhgfgl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ywluiywl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2blbrktjs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmquuyhw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2njcalvfc.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdmndax.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrvgqgu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pblhdczy.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcajsbfo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyytbrxg.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxwbwvf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsesirv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2feoxwcqe.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rehjegls.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oowsoxux.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvwxuot.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2jpowymdm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2flrwgxlk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhiwaw.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2inymwgjl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppczhqsc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlxaxkp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdthvtq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdafdpj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrmodbc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpqehmh.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbjiwak.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfzlrtz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rerutbuz.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aezkpkzh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oshwqsib.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjsescz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfztptpw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlatnxd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2swazrgnt.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwrtgph.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyprzmxo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjesjor.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkdlyuw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuvoyxr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cajjoydw.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkqzuhq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgxfjsl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmiobhd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcejtctn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2teoqhgqz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzkitis.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjarnqg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqumctt.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxwktmh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjrruee.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qztgkxed.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjekdond.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdyeytq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbljizm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwqzdcf.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlgqmxg.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zigqlhvq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmcocsg.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvuxbze.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2epjonddn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuflmpmf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oobqmynr.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmqtbrg.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2attsrnjm.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvcgehx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqjxlhp.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2obqlumze.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqocobr.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2akqydzwz.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkbdohu.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aszinqla.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dfocqzib.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxdxpyw.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nftacagk.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuiekbx.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2xozgjhfo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2agzxejrj.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2swvwejml.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2wozxlfxc.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcbejps.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbszwth.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnoceqi.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2ratpgjuo.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2glkfuqpx.html

[A12] 字符串插值 / 格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mqeaswgf.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlxuxom.html


<!-- 参考信息 -->