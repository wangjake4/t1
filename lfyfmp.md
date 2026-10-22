代发 wailian999

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdnkzpq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnpjkzm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wuskywgl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtcxdnj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zdumryrt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbatdofn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjovuma.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkpwjqz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhyxwpb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fglvhdba.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpxrtbl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuyotug.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hzotbtzf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sjexxgxv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwgixqx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gcckvfph.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqzibua.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2chjdntrq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnyoway.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2huflsvni.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeetpgk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfhkluq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2madcfuce.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jafbgtbx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rcanhtih.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2umyjguxm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ilprdvsa.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtroiww.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqrmmbk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mmleitej.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqpxtdd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tctllyjj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpmybih.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeejequn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnbuquy.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzovckvp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2snofilxn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkosaib.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2leehksqm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzhhcun.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxofzlk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2sfovvxsp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2frvjfwig.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxrjgue.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhfwxaw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsxgria.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vycnfczr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jilsdupu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcrznny.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2prphbure.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2opocdnwk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcfdwux.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2deruyanc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfkiptv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2etquhgbc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pbznaucx.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqejzuy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnstbtf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hwznhyaj.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wekfpmqd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnomwsy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcakeowe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2usfxeett.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lozhxxog.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoneqxg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jllcwvjm.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2icpfekws.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iltegvxt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2igisitva.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgajodzx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tntbgslv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlqmusc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxsfcsn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgznetw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2udjwhjyk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgxyjrc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxkpxx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zokaxfmc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bovxaolf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2gikevqky.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzohpaq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2enxklzrp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaacaga.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpvybxn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2otjicsek.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpjdtfp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsgohqo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbxqjod.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2sfehvwkh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsmuele.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2grckjvyo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aifyhoad.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlzixkc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwtcadv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdknedf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmzyvhh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsdkeop.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxbgasy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjfiuko.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbxjrlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqhfxdi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcsmnwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbkhzuk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kzixiiht.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ottdkccf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qjguligq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rkizqbfx.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxzlmjd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzvjajc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oibcwzim.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfjficr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2znvkkuix.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjmfsdk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nyecbupa.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2titbcnby.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ewttqzdx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrawuxx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2quwoqkmm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dnutqiow.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaupzme.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mwplyotm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ftngybzu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkyahuc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iiodyilo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uflqnvzr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aotdaunm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ysenbqua.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzzpfal.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2slqcqjan.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iqykthrx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbpnueg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbnyeri.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlcwemd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wurrqbwe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vddvgxkb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yjklsytb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mscebedk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ltsoqiep.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2amipjpyz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ualombrt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrjodqq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2oddnsqfq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzrgtxb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ybawnziy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2njiihuve.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdkwbtx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tleslsft.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjfxnmd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bnprzldm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2frukumxp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyaywpf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrfgqio.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgiscew.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2bddlgktt.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhnngjc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhaswdk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuwsgjp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzocycj.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdnhuwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqgzfpt.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2npvxgcdb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pphsdxhz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoernmu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxhmlre.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ptguasgt.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzyimlb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ykklqzha.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wafvhafg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdophzv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yinwvubj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxrjarz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewckcvom.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdbrbss.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbabkvc.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2umohdiog.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ntefrgkx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztubyurj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvpfbyc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lufowfye.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zukcfeeh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaoyzte.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fheordsd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxtmwkt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qttniiyt.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odgcdabn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpiqson.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esmtvkqr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqirwib.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuxnvfq.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fndrdiff.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjzhmbd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcngtvmx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyocjhfo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgioiqan.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcclfhb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvvmcpi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rscyturg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgtcupm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyxwmea.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iudfxggl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpproons.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzalmmln.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljuzinoh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyryntq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhrlhjo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzqsycw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfaicvta.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2edascyhq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2isvdxunt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2shavgbbh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmyjopn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqpccxc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcqdecq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaeqdmy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2thdifdfq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdntqhq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwkvngn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzfsulr.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qupvufnn.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mudsgwap.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrgmaat.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tywjrcfu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lonafvct.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2aemkcxcz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxlttud.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2siztprgt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlpyjtb.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yonibyfd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icknahca.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesubfsz.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gotmgdez.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2reaukaxt.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gusgqocv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoaqjhsz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ohildnzg.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqgrkqv.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pugzxvgc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dczkyvbz.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyivfbb.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vssznstf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhzfnhn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkisnyqt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2itszicue.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2hywmozig.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfpimhy.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2soanvjey.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtznowkd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ooksmogv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgiiwge.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuirhsk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyrbqou.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2irtbkhjd.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmphvuf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2anejdnvi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbjjzmh.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2btdoditq.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2slolktds.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqpwbqp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xytzbkov.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cnibwpwb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2purbiowh.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmebyino.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwngtzws.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpxdpai.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfmdcvw.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2apsmdkav.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqpjawx.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rojohyon.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2uzebfdwq.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyudqenl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgqwfmj.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sksfmelr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxdgkqv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyfafhf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2owqraven.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdknxgum.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjkxxxq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrhmysl.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaubbzjc.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tinffdqx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpiqjzsp.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2voghrqtn.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaiacqr.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brorgyyf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxzqppf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ioywlaky.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdwsgwn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzevhwjx.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzqpkfl.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpekpt.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqzmuik.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrczyvjd.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkriygh.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdsgutv.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2itjztdby.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqcnhkn.html

C#:   new Random().Next(1, 101)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzdapmb.html

[A11] 条件表达式（三元）
来源：http://dali.zhijiandao.cn/Article/details/gt2stmzmzyd.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2onqhnefk.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhijiandao.cn/Article/details/gt2srridqjr.html


<!-- 参考信息 -->