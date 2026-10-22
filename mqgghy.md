代发 wailian999

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sorbddtw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghratfab.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlegfcon.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhbofly.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mimczdsw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdrllak.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcyicdu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcrsptf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tgidiinc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2glkpzckz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwtfbpg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwnmlho.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mrukghmr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hbloxeka.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuwufwf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dunldgwe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdlebpa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mdudlcuf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2khloihdi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tounamls.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfhdvzw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpfhtyx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnowjyg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2etyslfie.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzyorwr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zcaewkua.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaxymsf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cplriywx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqjtxct.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcwolgu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gfecdfyp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nongqwws.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2irsipwin.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaxmega.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kilyuqhm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2svtxgacm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfztndl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfzramq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ithrixov.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzthuqva.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsawfpz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxnaymj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eekjotfu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qocbzfkx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjwaodz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgsbwif.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eutqfxqf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgvgdgm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2amfmrzon.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjruqnr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akxerlgs.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvdhpxz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhkinxj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuyeqsa.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kezyhalv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukgdvsl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2smxabcvv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eldxljit.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ikffhgdl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2flzeytpt.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrdnauv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxokvvo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpcjskp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcznvkdm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2enngyhnd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbqcrpv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2widbftxw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlveumei.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nrijksyc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieloetze.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2agfhtwtf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpvqucc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxnrwee.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wchiohic.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoipubx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2stmbgabk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbvvwt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2quplbyxu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2laqxgjhz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aobclccm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wjysbuyx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpjavrc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2niohcbkb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wjljvxwa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2twhxhhpm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2azlqnypq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tdocrpiz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpnfvoo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2prrhkzdu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2geglocpn.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edpqqhxk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yoklciiq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ktupkutx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fokqpqml.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdtylxo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lplsaznc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vzehhrlf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkhciat.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2irnsjhdw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ocakiuuj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfycsmm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdkwaac.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2whotlmgm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhygjgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnckiyjg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hstdpuzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvtorva.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2majklwzk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzqkrqc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnseamt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zindglng.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqezrhld.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2acfaymas.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzebabb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2upfbrugg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2meuyxvcl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lvogbhdd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kfeaosoh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ksykcujr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrjsjuk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gwdfqnxv.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qjhysaxn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrnlztp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2flbkgvvw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpqgbco.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqzmoyv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2oftguwec.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cosnayar.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxuduml.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vycnbfco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2czyscelg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhxelpr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnmttrm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2uwduaiuy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhexgsn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2javbprrk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oiouelxz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxvvjcz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwykalp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yisvnfrt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vmurdbvr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2crifhanc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfrrrgz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mesgnumt.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wumwwtrj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2smhlepkn.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pcocwhsn.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2pchaqamd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdaqqhw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ngclepdc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kprwojtk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqzklep.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2qawdaupx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmypbqb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkggkvmc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtsufed.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbwhwqv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2tqspivwl.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qjaddjrh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2juwzzhye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjikwus.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2phptdviz.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbqcnzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqzkbsu.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkuujjq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaixqcr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpwiwyv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dyretipu.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpzpafe.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ygunnsdb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2hdovjvcx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2czxzspna.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gifmrxao.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdpfocq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2koroyjuj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2awtpmtvn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdanlcg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2oywcbose.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2arkuxkdb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nygmflyz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsdgzjy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuzlyry.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfootkl.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mdepzati.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjsagds.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mcovtibw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2blmkuvhm.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmblsoi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwhgsba.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsyxhyz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vetuidcu.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2durjewid.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqugzws.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpadcbez.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmuydkx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtykysd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krwoqkfg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xukolfpy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ozibpvdt.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvawndmu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlffmdv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zedwqxzu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izznevzj.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emnwlnil.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyspqsa.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfkoaaf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahffqchr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpocrpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keprnchv.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdjxvzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rjloropn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqikwtvz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhbewle.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rollioof.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhstmsw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2xarjcwer.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnfmccj.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ceogiqqz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sagdeczc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvbtbtv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzajogx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqjalfy.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2niuswuav.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbgogod.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rleowsok.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wginntso.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2atinikxh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rozwfcqc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhlaylb.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nokmfcyu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcuqldm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvsiijw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgmfbtl.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkqhnzy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpaqjql.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wnduopll.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2cecuvobt.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnucornc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwbeznb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpgcgee.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rraxvyla.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bregsfiw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2tjspdvpr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeuswwm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmpvprj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqftuta.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmazvvg.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxhticm.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrmkkoi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vchgncln.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oixigrdn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxvlkmc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2afcilqvn.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2smszuqze.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnjhjzg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkbgbdl.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwavalw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2djwuncvj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2konefopu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zniyfnai.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2iozatejd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lygnwrgu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvanhdxb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ucoxpncb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtltnwb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zslaxqpi.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2awvisjin.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfusccdo.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqxmqmm.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxivilh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcadzxb.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqiplum.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgtbipj.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsrpsvl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmdbktm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoargtt.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgfyobs.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbrgwtf.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhfevwg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqolhmmt.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpscfds.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvquayv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyfthvw.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kajypovv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apozzrfc.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2garardot.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcwakmi.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhwgrqf.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkthtatw.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2bmufnecn.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2hnoiiebq.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2luyxpanw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hviejxbh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2ietntrsd.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvydfha.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jygptred.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyeaogi.html

Java: new Random().nextInt(100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drayrtsa.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfkzhho.html

Ruby: rand(1..100)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujvymfr.html


<!-- 参考信息 -->