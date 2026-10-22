代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aejviiyp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhnkerd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwskucs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfqyalf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaisnvh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcwwijv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rryuoovk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdfehev.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fyarfxwq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qottscsg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gikmrgbl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcgssko.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2byqbbbgg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyzebfo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jxekxvgk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzgkuyu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsiapoh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxtouaj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfaafkx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwlmqbu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ejntumht.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfiodbu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjtyatz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vvucdevr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dypukrza.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgdxcuk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgnilol.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmubizfu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxsgqxd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2civqqryk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2opdawiku.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpptqexg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2gkagtuwm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iyczeout.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zazgfsrw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wytyytys.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsflyod.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2juzlgwbv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpuyrni.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2advudznl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bgolsxdd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzmgypf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfywopf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyojpgl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdxmiyp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zldxsvwm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yirrwolc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxsnvul.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmdvhxy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmgwkwm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwgsonj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2prymmkdd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcnuzrv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxansis.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkyvfhk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cswoxrck.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mokbnrxl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqcsukx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nyanozny.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fgikzosb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzxngzu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdvgbny.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfrgcqp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqspwdrj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sucexaik.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmenepz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xalxubui.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcckgxha.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpsnule.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwvrygr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2blsduuly.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhbkqym.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hydrhqtu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeuvwdk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpptcyf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjaubhf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjpjdon.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2arznpfsj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpzbppz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgilcwc.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2frefcsey.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2euirjhmm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxqnete.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbynded.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xykhdeio.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qupifeey.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2bujvqavx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmzkgjr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gzulhatd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxaauev.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lsryoypo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrexcgtc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqadrko.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rytbibmy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmnnpwl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seoxdaba.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cvthrmep.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsmyoyi.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsljqnk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdyjbmt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jxafpmuk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwaivpv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovobajie.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvwdfci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otufrnsq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qyangiam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbngckuo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcrfhli.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fywhrqmc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsttofp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oyslhbpe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2esjttzqe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vwciuden.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2swehezad.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpyypvb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvvwlzr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsvlpun.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxryzif.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpzrsmn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjqldky.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrvxvlx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2msouozfo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2itjqfhuy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fiovwroc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2quyghymu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aowhrxal.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lgscvlsy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2suolaxyl.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2syrxxzyc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjkkwly.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgztjyg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfqetao.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2skosrlyp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqubhr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2admkkaox.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvelgcu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqvxrtn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bknahgwy.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjlqlqs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwnzjzy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrcbwjh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2esonamcq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyoyqpe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoppcqc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2jzklijhv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qaoeedue.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaehjqw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zykjvngu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2apsmkaub.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtenhgl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtcbejx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2knmmzdxx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2veeuuuyb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmzbxlp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsxdbog.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2iefxtwjq.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2egvdilqm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxgqfdw.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhlroox.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbnhsxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrhnbyh.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2drexatnz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkivava.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glmwkubn.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlkivql.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2felybutb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iajxkvre.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xnloulrw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuwkyhn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2clzkwqxb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbdawbc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmjijye.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rljsmafm.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnuoqdy.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dstbdphi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyoesji.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzkuhen.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnwlvwm.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2raicbhhz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccskreoh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxoicjj.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jeebieae.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhavhjw.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nastnmdz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhfmnkm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2cxldnlaw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjidrrm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2modmbssa.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwihkcnm.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxbuoxqq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emzesdbm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbltawyq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlbxdwf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pelgxycm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkefgnw.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oicxytwi.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2czjnsstc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qawghelf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkwesro.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmxbvve.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkojaujs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqomspm.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnvbcfk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nawordlq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfjddct.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtasnovs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zplhkmzj.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hddtxfrp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orimjtem.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuexjlx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avpjvaba.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvzdbbn.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zioedssx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlbhgkb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2shmfjazf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2drfcvqnd.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2llytfjkq.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvvcvjo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrvmlsg.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xrorgums.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lllrfqgk.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2efrpqzsp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lighvwmf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrffnpb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2obciworh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdqquwk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2brxdrvmz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2daiwmsll.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsilayl.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nexblubg.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrahgdl.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwwnhji.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eincbxuc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2emuvhaju.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiqfkio.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpwgzxc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhecvrb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjzgyps.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pclftptk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiqbucl.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cypemnue.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yovqitaw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mcofouyp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2bgceodoo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpxidkm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iixcgnbu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmdwvnm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2pgteqioo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2chwefqyl.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avqycube.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lagnsicl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmxvzfe.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcokwhws.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2czyidojy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2geyqvfsd.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agrppzyx.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtvtwmq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiuevyg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2amypfjlt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwqgctc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqksheu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2opkxbfbw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2asxuijja.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuytzvq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoygnavb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbycpve.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzpzwss.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvkvycl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2huiongvk.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpnhxux.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2npqcgzyn.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fchkqluf.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbhwuhb.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqyhdkr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2itvmulbc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpqywzx.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzugrymy.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmqjgoo.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfowpkfj.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsttqmb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqvwsec.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2rghnoeuh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvggtpa.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oucmrcqh.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyktenr.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxnokyt.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wanklxeb.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxqxfky.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwufzzf.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbhofoo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjhyzrz.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ostdsflj.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdhqrja.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2tktawmul.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpplpnhd.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqqohcc.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lbryglxo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ucumtucs.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmtkyvk.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqggpqou.html


<!-- 参考信息 -->