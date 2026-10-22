代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2agfkormz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2abbaluqr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jwartevm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ordwxgjq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2walogscr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlthctp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjuswwk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2skzvhlnt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hnejmrpe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2owetwiga.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgcfuau.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpgzppa.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2loyxxhdp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xddhktoo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tjghognj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhjlkrg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrxabfp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhguadn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uavzbowy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eabzjavi.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eswaxhve.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2spqrtrpr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxghpmv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjqlyjn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmyfjll.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhjxqvs.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xmefehyf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvngynr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlmauhy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzljmvu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmjwxwc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxxsroz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnllplza.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaarfzw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoznhwb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxkqbim.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tylqvwrh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlpimxd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2agrgdsqw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwctkzzn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lskzcozk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kennefvu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qsphsozw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jolanuiz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2axoatwoa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pjojzjyh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfwhfpv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtvnfvu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2odcltuvj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vfciydtj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mddnwtgm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfmcytar.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2itnpgmqo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxvswli.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvfhmmu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qccbonkq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2iumimdbv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsgzffo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxtkeod.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2esqfbsdm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2txtkwwpv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dycdizqm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqsfres.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2grmfxzjr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2haqwkbxg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjaofdt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2blsnjyxy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsnrxqs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtxdatn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbiqcpo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbbphu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2uipyfnpf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2atmqcydf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgzrxow.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcubkpf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2guhuwijo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnhfylc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejjjhko.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jusaqhdh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpazfyt.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tywsmtwj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vptchpqp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxcvgbs.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fszgpiar.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tbaqpzlv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwkhvqu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdgbaqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkvmwag.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2arbdvpmk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvjfrfq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qalqwqjo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fublihpz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdbdcdd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqvopdx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uieaeukx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzylvqr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eunzlwxc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfwtpmz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfiqsdm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrefryc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2usvbellf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zokwpfvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klaisumy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xtanozuy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2siogzuqu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pctfhubu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyimphm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2besaatuy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2beevkjjn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ezakqyhz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lblrvaxz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2blpxzhlv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bomvlfpc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlkixjn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2eyumgkzl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ipddmeud.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwirgtl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jkaxxqwf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhiulju.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhtzpdw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfekaii.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hplbkplx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kkchdcxb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nbngnzyg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ikidtvat.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2miesjsog.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2myphqzer.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iaktjzbn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvyfokm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iphnsdxu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bguzwclu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2npkoxbxk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjpuwaz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgzslcm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gryxqhxe.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcodikg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjfhgxv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrtoqub.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2msnxnjsc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwrnfkj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfrafrv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2asljbwkf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgegumh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jltglagh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnhvrdr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szwxwhfk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mydwnxto.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2abejqrqg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2uluztslu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2efrwfbax.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccagqdum.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2mvshjwki.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lymbpdcr.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjfscqc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmsyjgh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2bpokdjbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwcxuna.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlbiqie.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vdizfnyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xetjfcka.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfhgiee.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2oyitkqtf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbasbsq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2phjohlbh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdluvch.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rfshwnts.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xolhlygt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwrosvx.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ujainmxt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lcptimji.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mpipdtfw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2afdjkgls.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hafzzbyp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kcedeeyu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pifwrvpu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tazcfevm.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tmniqbjh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2famqnish.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzhmqqb.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlfjxcj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdsorgy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfiblrq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmctfoq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtogsza.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgrbwry.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvinptrm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umgdqqbm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bacwgklg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmunamsr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkycvhwk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jswhacnc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbmxbwb.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnzesli.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbappba.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwokrga.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkaywiw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fazoxwhg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqhwuyp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxukaok.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2menltwow.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jopzbrdq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqscuzj.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxckspbp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgvahzg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alqiwhqn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hctakuiw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsokbhhg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwxoega.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2irfoemjp.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mllpomsy.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2smlljfkg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ougnwkci.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2abrudxmc.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xksvexpm.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2megucecj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pevwyaxk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzwhoaj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgbixue.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2egbdieni.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvkzldm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxulxfa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2usewrrwt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jhswcfol.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmkxwwh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzloztw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zofmjkti.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvrvctx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuxqdby.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlbyeax.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oukdzksz.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nesstlac.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxeggyr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvhjcag.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xewhppml.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owjmbicn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2udlqmxyp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrajufdv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cwroqxtn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qvistscq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2jprhinfd.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbkrkmy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwczalnq.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ucndxtos.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcqkpdl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnsvtmh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnttlfic.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwesywyj.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2grdehgsi.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zicwvogs.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iupgcqns.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lieuhnod.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scrieqrg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nylkylxe.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2miqetbhc.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2smqoghge.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgybpoux.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxenipq.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2apxcwscz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nilntkbr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2hkljxpbu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcpihxw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxaglsh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2artwspbi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2exgdgvvd.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqoicaz.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2exkixmob.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uruadtvf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdrvpvx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yufskmlc.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svcsbgwm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwkbubz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2msrnpdcd.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otmephgy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kciatfsk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2edmbibdq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2txtzqzyb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaxdfsz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfhcfyp.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eglbilrt.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnhvxrp.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2erwpggbm.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdqyyqz.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2paarmjvn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ropbswhn.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtryutd.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtgtaxe.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkwojpx.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2druhtpsn.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfktwnhi.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubldyeed.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzsxbva.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcfumcl.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoucckt.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ltweekqa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2ortvfmcd.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2umbyzepb.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwzjocp.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2zewerrxo.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfjwvfz.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyteifpi.html


<!-- 参考信息 -->