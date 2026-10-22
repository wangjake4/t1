代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhrqzpd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbvneaf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrvaunr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdbzavz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrgfych.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpscnfd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvdvqht.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ydukxdbc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gteqkfhy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgfwljg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwggdyh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymjpox.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyoqkjj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthnbvvz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uigybwia.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhvjjrm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2juqtbwkb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjzcoyh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2iyynirkb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2elbhogbd.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mfapwfod.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2funnnkev.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiervku.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kpczovoz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcmqzsr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbgaken.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdavftj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqmulnl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bskplfye.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2adsitxma.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjjoiuj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2exdbvazj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgbvkib.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uygnxman.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zkboqxpp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uahamtyg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yqetsvah.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfeufll.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxxboza.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrssfwo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kapsdufe.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkvaipz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvjaith.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqlqthwy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2puhyhrzl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2huilkamh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pijdtgcy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2frgfbmhy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmahjpq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2whgnwodo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpflfbd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxjpzqd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dinuchuu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uodjbhxi.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrsmiha.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwsfqby.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aegkngsj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xddjcvgp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvwmgla.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2glzfubnk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ydugyzdr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uveggric.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlcoyff.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpwyzig.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2krlnhagl.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qkoygbqh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hjulvfiq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcmzyih.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2byacqjrs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2udrgwayw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2brfukjzm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwezcbcu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2sskzkkhr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yotypkqt.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dttginnu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfkzhck.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvklxwq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2neefuvjc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xiwonsuz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjoyguq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tmndduuf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzgjmcf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lyipwynb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2quudemjn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkpewwg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2peeaefij.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzysuzd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2aewuhpzg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcpmgwx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbawbjr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2msxbbbzx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bifaodvm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2usnsnowj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lleimmrs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qefzkwog.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsywfgcp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvkyxya.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uofdzhld.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdaezig.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcxujlp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2coggykwu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqgpevk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mruqulcn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kddnyjfs.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jjavzhix.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bvglnozt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2egivpcmg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcqdyyd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqkqgfr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pihmfugv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbxnuqg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrboqji.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nywjhxwd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehmmko.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2owgsiwtp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cirhpejh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kohfcsxx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwsruxd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zybrqkhz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2apdbnjcz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dafyzxcx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hykqtnmu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2upitwppm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2eakntcav.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2crgrijpo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoerbjo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lojszvfr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yajvciwp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2suxbitvg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vthgqtrb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrvhxly.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeirzcw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvaovjb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcveqtb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sxevoiun.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ropuhdla.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcfkzmh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vadluldv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zutpksrc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiuoucm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlqwuxg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dweaumdg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpnzitm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2irzhfwag.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkqxgwx.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2siidgabh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ultjoqic.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2juaqbyxg.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2klpltooe.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qsejpemr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbmoxfb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlouort.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2afskrvkj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhoutri.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2esakcsxy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qtujtqbw.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmlvsem.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nemsmshh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2oolqyiuj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxzirrc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xeofdade.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvsmwbg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtpznpw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kaggoxzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfuoiog.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzjaaqb.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzgahju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knzsalis.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2wblflqmv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xslpgqkz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wztntfjv.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdnuohz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2erlxbafi.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nihwjith.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxwindw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkzpsms.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtawngn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpxtpvf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnhuiws.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jztnpkxq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwtbbjf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqiaogz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2edebserv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmaauld.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ifaotxuk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpqftla.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrexmng.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2chcdrgvd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xtunvswj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vattohcj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2srdsmncx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gajxgeyd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zabwddmz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkojiou.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksocfewm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkblehrp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsgymee.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dkweivfa.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbegsvkt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyfvppw.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmynslq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcghkrnj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clkvtebz.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csrbilbe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhwhuwi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbywzism.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlxkgud.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waoeqmgs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnhcuik.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpawfqg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvbavsc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdejfbbv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqzcnqb.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inefijgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oymtjzgf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rphcygpa.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrukmfx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2usvlhlkf.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgcdebh.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxwqlhv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cadnfkoa.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgcokch.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvkepaq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkpubuv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwgekja.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tubtpmyv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrgktip.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcuthjm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rarxvtjq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtunalxz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2triphtfh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xpicvqjz.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aenmcwja.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gakthwrn.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mnffkgpn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxgmocg.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2blpdyvba.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfmhjwp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvckpim.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmsnxek.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2yngjxclw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssugshjd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxhvhjd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucviovvs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvuamei.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cycsssux.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxqwrow.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2zvubpjvz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuosypv.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmnsbvd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2salewimy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2bljakjpo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2azohujdx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyewgmr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmjftxm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdmkykj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhijxuf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmoiipd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkxiumx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynejzcoc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yfczdzoq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwoiith.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sogvfugo.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpkpkuo.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uieqnexv.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2tanrivrx.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2paguqmyt.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqrmekp.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrapiikb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyshake.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlovojo.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvfrqjm.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2snhjypps.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcwrgny.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwlfzoo.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfhcolk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrdymw.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bunxrdlx.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2qziguhny.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2adudilcr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2datmeona.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmsslmk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2smtqpxof.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkvegq.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxfrxef.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ajadjimm.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcziegyq.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2shnfynjv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnebdni.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnixscb.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycshmfxk.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrlivna.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhimgntq.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2ksukqoal.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaatclj.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tevvctkw.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpshjtkq.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2grmmmzgh.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2efewcthr.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sshrnitn.html


<!-- 参考信息 -->