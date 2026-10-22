代发 wailian999

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pubtarng.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqpbzkb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2htnueodw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbiptmh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2izttkjnb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzxpcnu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2achtarvo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzxgiz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fycedpjl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2drcnxxyo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjgxhpz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbjslfp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrpmsfu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxlbgrd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dizgcwdz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qltdmlha.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrdkxcs.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpnkjob.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cawomjmw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2judfrefq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtkmghk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdwollr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2timizmdi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjqrnup.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pypbpmtn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2lyplddsn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bcllygye.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fufxhojf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrnbapv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtnornv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwcyqtt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwqmhev.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwaepfk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2upwmvhks.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvckupv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqhszqc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdzzrmq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eksrrbro.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oaichpne.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvpjtme.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2suygtkdz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hligcxle.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwjqihj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2elvlrzaj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhurlbc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyukqjh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfjbkah.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2baszisch.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgtryxi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpcitri.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2stvvpkbl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2svqvmbde.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddalesmu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzumqup.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqofvcqz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfuutip.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dccypwas.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeplokg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwnhknu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhehkrl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lgunmxib.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvmtglt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rzadmply.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqvoorb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhlyvny.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kxudnnue.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fglwuyae.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2luwucuvz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2siixxyhw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyklyau.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbbtjqp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2axyxnzgy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqzizef.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvikvmon.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrdhoku.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iwckqcxh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2slsbjzps.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zacnlzis.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkaymkg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaqkquf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2blndtxdu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmngioug.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeqhuzp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lqltwajz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtztbro.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kihkqdsy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2agqjrvqq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ijthfnkf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzfaxcs.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eanpdnzx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uupbwean.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdrwkga.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvikkyc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ichoikvk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2soqjpdhh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usibhcpb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2czcubpjy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhyopec.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2msckzach.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvtdyux.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2umgugtjx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkdykoy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2onayshhr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvhrfro.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2canewihz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jssunlpy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntaaorbi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2oegvghwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxklyax.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2supkcpqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oupuooki.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzlnpoz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2asxnuroh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgbjdrh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2onodpnku.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaipauw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuqtrsa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fumpmuiq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjyowpx.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzihdal.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxdmcjl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yigrctog.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsvjmpz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2myannugv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjmgamr.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyysbjz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqpbcel.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjihgrk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqutxah.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wdiamqea.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hojzwnfv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2saskgxtx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bpntrlab.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqyiknb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwejcnq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kijwdbkv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qibdpphm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ybimdprs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtdugoj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kwznfits.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxayobj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bgriqxad.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdzunvy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuyfxls.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcyblbe.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvxagew.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2aaavhxdf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vqygvyhc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmpghzp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bndeybek.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nuegonvo.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dhszaeew.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2kntxtshp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vinzsgok.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wslbqwgw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dimejvzc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmpuwve.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgfjoxc.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2xooggdqi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2egeurkqx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvaiuye.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgwhhok.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2apsudumz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2thsmpgga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xszcdfre.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqyxmoc.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ejegptph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfectck.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qhckzomk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2mxlboxnc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2waejgkxf.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2exkznxle.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkutbel.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuxekee.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2msaomsmd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2awpgvlym.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bugeyjsj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqnsyeg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2btlesjhy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfqzblo.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2auomwwpr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2deromyhs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhrhhpv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xzinxbfa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeqfbzx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyowlby.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwbwgny.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxydxen.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ysajaewx.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2itmknlxi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qmirfgsq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qupqiiuq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zunosfle.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2swxqzhct.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svkfspmg.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myrbmpaf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkucjkbv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzgsoij.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqoidcf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjgzsii.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlwjrxo.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orckvpkk.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlhzdtu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2baxhdvde.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxdqtxh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtemiba.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsxwuie.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgddycay.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuofxpzz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qpncrslt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmifjrgn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbwhzuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbulcyrx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2azydnajv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujovexaw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jrppncnw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqxylhr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2btzlyxko.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2okeqafun.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqvtnov.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqmmbyu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2faaigbma.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdexpzjr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gahldcee.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vubqhahy.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpbmrrd.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpnfkdy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2izrfvdxu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjexbwh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjdnuij.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2obkylgsz.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2vztqpnwa.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdkeuls.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vytxosla.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2suqfrfim.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjyocuk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqexbrku.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2czupgxrf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuwfueu.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xysrudzc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zyggbztz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbyauzi.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ilailelu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfahrqt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwctkul.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpmszzg.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uphjryft.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2snyfwqwx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpipotuk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjihdaie.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2blmmuccf.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jrytoijh.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xawuhfjb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmajrxwa.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2caodabbm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvgtqvf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njtmcyod.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pslscowk.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oroxlliu.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcfhnbr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2smuffruu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dkihoyem.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2aklkvvrt.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqntlqj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzziotrr.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2esgvngdc.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddygqhwk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbokowi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbfizsc.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oijlzmqc.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2gukuiiky.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovarznsl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqnhukf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdycqeu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaccxmz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpamczs.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwcdunf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hihpybjr.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcvcldh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfauixyw.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqdogtm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnieeulc.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2lytqsfqu.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgsbrrb.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zghzabjj.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvmzmhh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmbcvgv.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwherz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vszgkbxl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbybycdm.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2neaggopn.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2priugarv.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zumwnhgb.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2nojkphai.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2nscypmcs.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxepijgi.html

[A10] 生成随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxwjuex.html

Py:   import random; random.randint(1, 100)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdobouy.html

PHP:  random_int(1, 100);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzlmbym.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlrijmk.html


<!-- 参考信息 -->