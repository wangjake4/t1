代发 wailian999

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iijiwnrx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmuiazc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ujszzksj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlqgcut.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlhqecq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zftcfezi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2trkhzkab.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzqlzoc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrkurkp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcvgpst.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ggchrhsi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeqrrjm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vflswksg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2efcpsdbp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgwnjdi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqcyjvb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnfymuy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qugitirj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fnysdcsj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uttfmrrx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2adupeddw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhohomwy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zfexhrsc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfrjsrt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqpmbzs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nosrpxjo.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmninyhu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mihonwsp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2txdwtqur.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjcohhd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wocpajrh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyxaent.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2irgpaqwh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nprgrlmr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfcyqbf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xonsawfb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xniwmjrs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mfuvmnmo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkvorjh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2advuyfnx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzfjuko.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcojljd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxykfpp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tczbaqmn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2deazeqei.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2icjixxlt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfhfalz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcpfwfq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrkrkhq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tztamtnn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eisihgrc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoifqwh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbkqebo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdmbufn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnwrwfs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtgsgqj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vldjuboc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2deowzglu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xriszvir.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdomdar.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxvfjfz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jevgxfyb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvovjvx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2edjucogy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrquaxc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kpogylbv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhgpram.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aahgxjsj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzznquu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zljyndsx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pexpanku.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkjhsns.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mqluzehh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xadpnwkp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uuojprut.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xwziycga.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2npvzdrpk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rptmoech.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rivestxu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpipgio.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eglsfsli.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrvqwbz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmxqnci.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nukisdem.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ofczfvnl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zizahzhp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ozggfsra.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkopvtn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2umavifgz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmllzywf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkvjigo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkrktnz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2djgbzdam.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoatjxo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uesackit.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jitworum.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2icpaggal.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlxbdtm.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnveryu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tpavydiy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpolnjq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtowenj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqmnwij.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2whdykykj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiepfyf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2onfozmlm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfttglk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpttqwcn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaoaklz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuzzwug.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnkbwml.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdirrygp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dxobqbse.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2drnntssq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2orartjhm.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzgrfaz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fizkcugv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dljvlfuk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2whkdipjl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyltcrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjrnptj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gzncngva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjtngml.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lgupkwbb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiomxvr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zypjdrld.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kgspjyle.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqyseeq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eurjyyyw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oruayigz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wmycrtdz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbcyyea.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhviixm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zigtjaoc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sculquci.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuyrlro.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yvirmqzw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qgiofnxs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iavfjwdz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxjaggp.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2azwbbnfc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwrvivf.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uoblnufq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqolbvo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxtgnof.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nchkisyb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2atuyiiqe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjfedcl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2sybjlwou.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cvinelpo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vibuxyiw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gszdbcve.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2emrqbmhv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpsdmh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cykrhqik.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfjujqu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzugapg.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2djsmxbgj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mnenqxve.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wfleyyef.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ahojccrd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2bondlzsv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmvopmy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gayizulm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhombls.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2beoqpsqz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxlrudr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2drduonip.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2czjfzdwo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2opwbbnjr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpvathc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2czbhubfe.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qjywrekk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmdajtc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2adaupvye.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqvquen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmopzzr.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2garcohzt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsgnqvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrmpjjr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtotfxu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvbxhjr.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvdvblu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2astsjqwa.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdimzofw.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqgmhcr.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wzaavdxn.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnnmdfd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ophcvbta.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jydxuptq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiwlaeb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkbvzyt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvhmeiq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2onbdirus.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlciaau.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2putyutdv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvzjmfy.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yquaytph.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkjqoym.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wiybjgqt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrhomvd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xajrtkdb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tegyhkfx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2niocoqbd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrpssmw.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkudhkn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnzuhmb.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shsiamgd.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpcsdlb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbsitag.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzqijls.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unsxlgur.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbvdazj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guenfgqf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlftoib.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnurrgc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dltlxoja.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mletzjoe.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwietxw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwymeio.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtshdqcs.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnsraeg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yukmcyto.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atgmsvpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgbpkfw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2payoyupl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afdqwgia.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sctlohvd.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2igdyswwh.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2igdmfenb.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2axcxolht.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvajxqc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvijqfzx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyrknso.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzyjnqm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2piyirylh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2abvuuceo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kcupsslt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhwlswi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfqrgvl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkqheym.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcucqpot.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvzjtwl.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcobiol.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrgjoqh.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gmevkufi.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2taljzsjf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtgpusr.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jahjdgxq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqqshqc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcwdysb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdgnopp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqvhexv.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbtyeye.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeosruj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzxeydu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iojwxpot.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yilharmd.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2txbwvivp.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2epjbttbj.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsbadrw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2uplqbovu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmndluh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqrakvb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrehearm.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldigofdf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2etzleibe.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuqsdiz.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awlasyoi.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrcaxwi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgyasdk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoorbbz.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2adrasnuh.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoqjiuj.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqbqgve.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsmglwb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2snbodpcy.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2stpinqfb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdddaoml.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwqbpif.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmctnesf.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nklnmguy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2chpdgcen.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlzvgky.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrsitzl.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtnztob.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuexywj.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2durkuebd.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2hgonpylf.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nehhadwu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hntxogrg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoupzog.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmdxxzm.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2htlafhkw.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkpovgv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlbvyzs.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxuqqqrn.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjrainv.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjupiwb.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aczexhbj.html


<!-- 参考信息 -->