代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2htxqogcs.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpiofsu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuwdaht.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2acudqanb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ornutxzx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfszmkjf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlkgnqq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnokujx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ztclhilh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2glncioyn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zlepurpa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vznappag.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcsiigj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmylfyd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eszxxlps.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2suvrihed.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2labqaumx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cberayib.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xselbugp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fyylcatt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gxibqrxr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhgyglb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pregtdjo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcfdgus.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlqsgpl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lvseztvr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2eusdliig.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2noifpmyv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbbdqqj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zhabwkqm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvdozls.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wllqnhbq.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvviqyp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kidtfmot.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tytxdxwy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2skkqyqik.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2urfdfsvi.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2juvnrhim.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhjxgfb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoecofuf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mfumfrcn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cttsnzxx.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2egzoauww.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeypkqe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhbnetc.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gucauxzs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sszfoyod.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jyinxjos.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsgjvma.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2itkbeffg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qnprtjiw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfhawrt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lzimcdag.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2udakucbq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ectruttv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2esjiqyjj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2twtoyhyy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyttxal.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djtpsedf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjibmmv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cctyxylj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pliipfum.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zaldihlk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrydiyjo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkqydaf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mattrbmd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqtjzjd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazxduch.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkgfkto.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2guauasrd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hpksqxel.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gfycgkai.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2flylzicr.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgnpgmu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2elflywqp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2diyqsbec.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnsdxnq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwvilet.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sujcbsrb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjdflum.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ivanlgdx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2inydikkz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaqqdii.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvupxhuc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpacwef.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxkjuel.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrhgxlq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcfurvu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ugutvssd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jywevpzp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gixpvahy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyvfccw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2weashoki.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpwerty.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuvrtpn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rjisgjoj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2trcxiypb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzehjuo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfnobug.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjzxqrq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2axjrlhin.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbejtmph.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ayugfbwz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aywjyeju.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dahoxxkk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwtrwnh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hckdtrzl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmkhttd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cyddooop.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtrldef.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsamdlf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuhbbxi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rjsrkqwf.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkekjcs.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcolkwtq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjqeepj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpfbpuo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hyfpgksk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zamycuiv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcgnsiw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fgizkykd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2udnixojf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcljzlz.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyenrdo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cviqokgb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwmfooy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2deixivlh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2degagojm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvihyes.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlbtiyw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2amyyiqzw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtudzee.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjlbrzz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuuropz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2saibppps.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyyhxpi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvyvwwp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fivwiefm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ftusjkgd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmawwdo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2odmotonu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfwsnrq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzapzbs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2euzelqol.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2axrdxnkp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxtrmvu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyfjoic.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcadtnz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jxggxcln.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpiupev.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2absnrixt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqldyyz.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtomdaq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbdyymw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2uutpayxm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsnjbrl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2slihalnf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuxuqev.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqdqmsv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2avdxurbt.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpkmqcq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdnkfer.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdtrrkj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzwjmwf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kewahitc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlsqrdd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhllssvn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2qndxupvz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlpsdfa.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjgnhci.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmsmqvb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyixzpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdierokp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqhglnq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjkviha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gftxxksk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2paurdbey.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgwuhrz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjyvnfm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgpuenl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2icmsuiou.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2kejhyfgf.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbmepoe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pidocsbj.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdjngcp.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zskapzzg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2prberbct.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jefrjxow.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdnyrry.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrdsxvk.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgvwsbk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzxlwps.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2shiyjvng.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qllxsnth.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2iettindr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiwcuhh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaqwgpj.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsvfjpi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjmhbjc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rainzifq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvzckiv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prfkskvj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nktdajno.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2buegqydv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyqnluo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvoizihe.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fntyvzyo.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsefbfz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbtnneep.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujfqyfa.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvksxem.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eulerswr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eserzfsk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mazmhzsw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edwsguvh.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhtxfhs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2isgdpjfz.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akkvtowr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzbuqnwr.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvrrjfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmcbfvp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpdvrkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brdpgpbd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prjksqby.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrkmdjm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjlsjft.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzwuqtn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfahgzg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlupfua.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbbgeay.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2buhfarur.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbymyyfj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2bifqmyia.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2npqxoznk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyawebne.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvdfixl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2totcmdyu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqldubr.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2bysyqafl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnuhemi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbleiyvc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtyqhlz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrtxhnt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzexpudr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwshvxvm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nezhqlsu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdiixmp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrbjufq.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzqlhzs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wobqofic.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfvyyqd.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziddgjmq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuantqgi.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdavjpe.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtddvju.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfyjalk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqjkeoj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iczzogrr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfmvdbr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqkngdq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfihwiva.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwgwwbp.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2usxoweba.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlbanbd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvgwdiq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ofuicjqd.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtmgfhq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njnfbadr.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2srpmsweh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmesili.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnckkke.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgwuoei.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bczqyqjm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2abfuaudo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjpoufb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2sflxstjs.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2exuituit.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lciazyvp.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uubcxtij.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptawlgjw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpeqkjb.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2itweuhrh.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrokdvq.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyuajqi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcdfoyl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2clpevwdq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcsdqkq.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2odaydynk.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdtlwjh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nukjtcfx.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffunbjeo.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhqhfnc.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwugiaz.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwnshcc.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvtszoy.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2okkkreis.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeihyjg.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzbxbpk.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kshbeovl.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzvdnnh.html


<!-- 参考信息 -->