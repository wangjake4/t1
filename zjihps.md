代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmlzmgz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtghidmz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpskrhpj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcakjoez.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxwwrjc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xanpihdt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zducympp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbofqdq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sncrteuh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrozuyj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfgavhj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2oawutsbf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfxwljs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqkgbes.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvichcy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fsiniiwy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jpznbuyv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2clfpurik.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kenfigrv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqulecdy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjjaxge.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwjiwzp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbbvfud.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2cnghfwkj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqizhub.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcenndt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiscbrx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2utnwmytz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwritwm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kekiwojk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uecrujso.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwrlptw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2npjeiqof.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhrawub.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ujssxmqp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyzipnxo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pbldrruq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmeovpz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kecrtmmd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2amefmphb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvpprbc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaaqopo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsnxfrp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nepblimw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhkqiyd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwghrufw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2glkzhbxy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsyyhmf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvjaudm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pxphkcfm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2glfmymap.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfozibiw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jttsxzji.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxwjmwo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdewrrbo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jutopcnk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmiwtxa.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvyvbgp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sepbvhod.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgpqnaz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdxvyld.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtwoimi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2astqlvuv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rugouhtw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpvaede.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zubhfexh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2shtnrzda.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwnzbzo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfwjzvw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jezuqmgp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvcgqwx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gupyeala.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfyxeot.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwxjglb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2svzmdsbz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjonkhdt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aivhfcam.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hivlpraq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiucpul.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tdibdwzk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oohdxblz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2coefwenz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2olglrily.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xkextvfa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2epuzpelo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmvwyun.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2luqrbwrq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqkudzo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zjiraqtq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2miyqhqjs.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pspujoqt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2esmsoqxu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2domthmwe.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpnsmid.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxczjfs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wizavjki.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2raoacond.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmloxyi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmokqtz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhrzxxv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vpopvspc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbyrkru.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hehnfmzz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzyjmwy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdnutzu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbmocki.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lakznyby.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbyblsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdxqwml.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cafzbbkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfujgjks.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tckbnxgk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2djgpzign.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtztbdz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpmaidc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ethrzkgh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ffejaaca.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwhtddn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfpuxfz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvqybym.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qobfuzns.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbwxsgh.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hskzvofy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjffpktw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfvlhui.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2okvrzgac.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzyfpqn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2thvxqkrp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoocmlz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdglrwo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vvddlgwy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ipefsmcp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2moiklzdo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cxojkjzq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmarabz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywchhh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uifwgjiz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtcvcxm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dwctifas.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uetyvtxw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyettlb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ehximvzt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnxbmcq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxhmdyj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpnsrpi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yktevdoe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2jahpobty.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2drohkzdb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdneehf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmzjtrt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jiudxlto.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhhyfol.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2cnltxhvb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrowssw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbfqesw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvohtvth.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2leyhgkdw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2athgucgv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyodjmg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyrsaee.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjaysqn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqftluj.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbwtrzv.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcuwtqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbzkmgg.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiddhyrx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2yapkvdax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdevuzw.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2yphrjmtl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2gymenmmp.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yamlmaxg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbxdhvs.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2rncwsbiz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwoctpb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2yiisgkac.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2sftvtnhp.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vidvpvkp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uixddtvu.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaeqccy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqwojcr.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsulgwj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2okytynbf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2btvpjrqm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2moyfnctd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2shzsmedc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjzwyfb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2puniumbe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjodzdt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaruhjw.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfgkfqq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbpwfll.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrxpbke.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phskcfgr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsdksfv.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkumxbx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlvgxzq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zolybfhb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hotrnoaz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nslpwian.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhauaeud.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pajwneef.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbxwztr.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fscriryh.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkaqjpk.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdyuxve.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkxnnit.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkzobft.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnfojig.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkkfeif.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cxczligg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yphsbhsi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxezazd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrruzhp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjopfeuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdqllbl.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hozkzmow.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdksqytc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcwfwom.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2thicfamd.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2grhdeimq.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mnychrrl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iieiaolk.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwaktyzp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmvybnf.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2djrgklel.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2teyflbuw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysonztsb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpszdsm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aokallvo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmsavaa.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiaczfv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2agrmxjyh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqltckg.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iscpesqw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pfacapri.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oizpfjvh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ranhthhc.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcucqzb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwknpkfk.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2euuxxkwd.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xrigmmqa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdadpav.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2widnaxga.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjyonno.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2peyjftvy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mymdukxj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hztjppyq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rceiemre.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxndumbo.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwhxuic.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxragxq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2zndpevih.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mzworlrb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxumcrmb.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvwbnuk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rzelnykr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2amsymmiy.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkivwdp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcbljaj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dboterhs.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2izlxnpdt.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaisxxw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmcwnmaz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2idpjgmep.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2evezvlbu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnooint.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgrwbja.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxefjsd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyswgpa.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfwgcqp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgstour.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ithghthn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2htzqcrmd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxymrvn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlhutmk.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeggptgs.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvrtebe.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uizzhdnq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdbxmxx.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyzflrg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoyypsn.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sevvynqq.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcelncoo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2prkmlcqd.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmxjqrh.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2lhedjjgu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuiztik.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrpflbs.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxfsyoq.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txplkggl.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfsyhyo.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lslubzfv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jejylhps.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtynrnt.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbxtcgy.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbvdnos.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2likpssur.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqetdevs.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjngpryb.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtsxcdl.html


<!-- 参考信息 -->