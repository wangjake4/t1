代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gilpmefw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbneahg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtqucyf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylryxylq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iacysilv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2orfrvufw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2plbluvxb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbskunto.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbgbbjd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjntfxq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzigjcoj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvuvqfw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2celzzvqm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgduvbln.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2syfgbqhk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gscbdfhv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2skbtizwh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwvethr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2skvmlmvc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbscoicf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2upsdmwll.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxizccex.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tmofrbpv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwcrrxx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwtqjpx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ragizrmo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hpclyvfn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2erufemoh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpxsvqr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hctfnsra.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2thclftdh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgvemgt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cvezxsfw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfgfzyl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2epnnoouj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nclbfpby.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtfmqle.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohivnhfv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdovzbh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxatwvg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jspgiidi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbbpgqx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oidywzhu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fygrhcdy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsckwyvj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2epmmnwwg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjhreby.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkrpeda.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fcprhivp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vydsotfe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hktkbils.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdmktyp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jnydlipg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtbdfji.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lkisphqc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoufhef.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vbocinzr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hffmftrn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fggbqmms.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iclpzeld.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsvtnaz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ithvvfyi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qidfyxeg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jprzilco.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvcazrg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmezuhy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnvagtx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuybooem.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxxktbx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eshhlrck.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhctpyv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvntysva.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqibexv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vykzkrnn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeuvidg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbkjdtj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwxknci.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2uevjonio.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuzavjz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnyyqyf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2usiaqggq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfcygyf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkhqzjm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdupduhc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2asybyaam.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xefxnbua.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxzkgoi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzzntbb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sfimemvm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2aupnheqv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgdjdrn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqhutnv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rseirkgc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vffjkwtb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsyiixg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vhucydue.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ggymphzs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2usandzyp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwrskzs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnfsjip.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iytkphti.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvggasie.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrlanik.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjzkkbg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsnjsuo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2upsjzwjd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmidfbh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbipqeaw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qarfrqzc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzqvtqn.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2azzxsfoj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhfutxi.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmntzbt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjsgpch.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgchrtr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zofudvfp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwgcphw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjruntuy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2emsyoixa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkzrfie.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbohubi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfeqssr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aotlpdej.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrphbvu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmnyezd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjlvrfy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lggrgodo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sogyphrj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rshykdkt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jatczdwa.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekodfknx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cphjoiph.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2noigiech.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzoqqly.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kogenxoj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpcldkj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kyorjrms.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiaxihn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaokhqt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnuvtkt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bidvzjep.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfgbcda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpauzrxc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmnrngr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2esqkyonh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yflhxbqv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2isspvdll.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnwfuit.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2azisuvit.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mwptmfct.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rbusnckl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnoofgu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqnsvix.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjpksto.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2suysfyzy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhllefu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nofakthc.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iohtdhvo.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnoztqm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2enuhugjv.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzffgtc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qkitavur.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bpepjeko.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2cvltgpkp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kugoqwma.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2czolcbfy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ajstwvfx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tymttaqd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkrmjvc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyrnxfb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kjizbahg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2glnwjgkc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oslpnicv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2waxekuys.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmsayih.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yaskkpsi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hutckpnf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rpeohosw.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcskihy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uakbenqk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bwropdpm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cepxvjam.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxufapc.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2soggbcvq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2levuvgld.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjlzhzf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cgttrmto.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpplwgx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2bcaeohap.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmtficv.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2hxybmdak.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2baeikrae.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bppiptah.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fytvcpbs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2bgczwkun.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqzntmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnkmedn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2trnlbmwg.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmnrmav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txantnvv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2peszrnss.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2drbrnhgg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iewsiuuk.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnqvzug.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2cytsylsy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2uajoplxa.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbgjpyo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2douxralb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2thjwbpyd.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2izymhmsl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2csjjatun.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ufimpkru.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhunrlho.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2riprohcx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pscbnjbd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zipschsw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpkljge.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uttlqvof.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2exwjcpeh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2phfntqqr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbqgsfd.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jnztzqlp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjpenlv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzdxygy.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsvhkem.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdlpgki.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dybvdmcs.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2innqjejz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsljunkb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eontfnan.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwiscsb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wajxceaz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eldvhxvf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvucund.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmelniy.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzgjszj.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qebzzldo.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmjhxap.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2seipprou.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkhnisu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xstaultu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpcjcxf.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xweizggs.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbhhycs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2snrzilsq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbakbdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfuzswqn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2livdfpsz.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmztkatg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqeajrq.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tievnfij.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmnejleg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ocherlgu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgpwjge.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2avdnwxky.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2dixdrypa.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pznjxdrx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoexjul.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuiilxl.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtumibe.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvglxivc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxtvqne.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdixxji.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2haqmrzyk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkykmnif.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxevsszk.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcbwiaq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkijwtfc.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2udgmhfzm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjocorzt.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbifxxk.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wewqjfga.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkcuslf.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmujxtpk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfaeqkq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqloydm.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlqwhpu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oblglijt.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2apjzpqsv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2aznbczav.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnahimf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2toenllyt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrutxsb.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoorvcj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnynoyi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkrxtfr.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sstrbbih.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2maxtmjun.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdmdvsz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evhcehct.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ornjudxy.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbzofnk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfalkdi.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwnyrkd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojfxawza.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlnpdyz.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdwxphd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ficiwbya.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrcfovr.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cijitjkh.html


<!-- 参考信息 -->