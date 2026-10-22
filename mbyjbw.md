代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2verbmiom.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkhespc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wptlbved.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2onugadrb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rnllybie.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjqvwaz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqcxjre.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbuajxz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jijnynyr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfbyjtj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmwnsbm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqiuaje.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaquzvt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfynqjny.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zblvcgid.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfszkqn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bamhnmqo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfcfncg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2otmjfiek.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2opneefgm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zazcsjae.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvitnivt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpemhwh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzlxvtx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qujphhdv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjyjhpp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkhtqop.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbibtjz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2btuhastw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qysxpwsp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkqnric.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzmglus.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqcbdvz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtantvq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxsitwa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tcktfrxx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmbvjye.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmvngdc.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jamvwqcj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdztrnq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aptiinhq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ijidwqsu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jexxkszc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dldwabwt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2byjnzzau.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jiroacrk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnwtpfi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvzhjsv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcqaczb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2xanczyqw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uamvkzzr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2etzxureg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rztljpvz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfubmkv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkhidxt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzdjuwa.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcleprn.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdeffsj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrmkyhj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ildnaadf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mskqppio.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymocnieb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaxgjvw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmigmov.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cipqlnat.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkmdjhx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrpnfzu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gagpkgdt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vffreuln.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehdiae.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cymgmbwd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaseqvp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gifzjnlx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2boihiglj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmvpzbt.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsomycs.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2romypocp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfervsd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2czdjdhfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aobikaoi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfsocvx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pywodaif.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cezbhdaj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qysrossj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwixbgx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjdqytt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgfzqmc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2shcxeplo.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeufgen.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2duvwfjwe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tllegrit.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdiduno.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fygtqgkc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2opcwcaqd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qidizhyh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iajmvrit.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2npmgltoy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnpsaer.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kliqpjeg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2glkhbkbr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2saczatly.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlqmqta.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvifraye.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqwwgtm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zjruerig.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxedgqjh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpwgqhc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2auwqqlbp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxivocv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiejliy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeouejn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhzekkj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvwdytk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hukrtysy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zwejlwcx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2csbkzjpn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkiprjn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxzqybq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcebcol.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkywood.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcghvjq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnybrhy.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrfpyim.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlupqod.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2evweybnk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2apdsoeca.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoddouw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2eoktatrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yomjedoy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2budomvqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acbavfnj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwtaxwx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbhlnpx.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ngumptqn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sddvudhc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbhkhcv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgvjyxi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvuytwh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlgxydc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ccexbjwo.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtyrbkh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uabihedu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmvmbww.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqkxkef.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwhjsyj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkawphd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqyiuul.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfbitrt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsnhnmo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qutcnfom.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2evbuvefv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nmixcscw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pgypyvvr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgjyeps.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2avutnsxh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2upypfxwe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpqnxzh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2iswyibjh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgppwnt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkejbrp.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvjuxvy.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgdtvki.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2afhonmvh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqveeqa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pbosfpat.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsemfvp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2coqwuhkp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzaenkw.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqefcin.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fgokmlli.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgxovnx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2odjveimw.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxekfxm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zdufoazl.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2soiyutsh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2llofblll.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2edionnfx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yezbbdok.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukahbwoq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2wulcupbp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuuaxhn.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqmoqzo.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pffuzbrr.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ppplnzxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duxezezt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2opgfwsex.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ubckylqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkqnkvp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyemwcc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuddkck.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkhtykl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmsizlp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxfibja.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2crrwhehc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxclqic.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2apuruyrq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2glbynkwc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2uezcmkgt.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrrvlud.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gegywhtx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztugcmrv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiiuwlx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpczukj.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ioizoexf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kprgrzlb.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkdfkow.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcjmxu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlwbcie.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlmlaow.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdmzcvr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpqruwj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyqhfah.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeazvob.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiunbsg.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaidquy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lblwhluy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2texhnclj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmikhfd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svhgdfhd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vabvacco.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmfuxus.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tryhrpiu.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2noydofmf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yekqzlss.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbfrbrb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkxkxyl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzxaavu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2drlbweiq.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bogryskw.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eipmbbcf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gawhblyv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcglkwto.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jojfwmgg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qerbmumt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjpcihz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btbbliqe.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrukwlmd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoxmuvg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcuvufv.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtkcbuh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vbplshop.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgdqymt.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlhzkwh.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqohzln.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rnofzwmp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2byhaxnnu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2utpxjtds.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeouuka.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbxktlp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2slspoefi.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2flgwekyd.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjmizmm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwhjyht.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwmzzhl.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dtinzamd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmbdbpt.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cykvnujb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wooyqahf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2htvavqed.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qelbukve.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qkovdqjh.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzpsddq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlosobb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2biowdjqc.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lglhxtgu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzkpnlp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrbkoxn.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ervsjpjz.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbdywsc.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gykxbfez.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2tgglgvmf.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kjouojln.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrobipk.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eocycmov.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvmtfbx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llcmgdyi.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iolbgfcl.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vicymmmj.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhwbdbt.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxoalqg.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qarecpza.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ettwmusu.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrzijeg.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2apqljjcz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcftghmc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2syvflahu.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvywjuk.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrpctoq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2btfgqkun.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ktccavql.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqwuzjh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvebjglj.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtlunkr.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzagkjur.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvktoqv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jebxdqjn.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2tvskwulg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnerqlgy.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhtxdhg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjowabu.html


<!-- 参考信息 -->