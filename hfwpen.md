代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2noacmumn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqcgsni.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2znitwhkm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgvrgth.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkznhkh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sodclndr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2whliwbpt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwkfqqh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgksmavp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bigcynxd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2agcthwjg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkufmfp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqzcwyh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzldgdj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhrbaoi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhseohe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlluhrk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kghsitfd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgunmtz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiohixl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hirzupbo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvkwanq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2buxclbip.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nonvmtxi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnphjsn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyogoap.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2joqzuyeu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ommhktpj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2obvlynov.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtutpajb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yidcqwos.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2muxunbrw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpdiryu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjhwnjb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcwowzr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bwidmnha.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yayoskzy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvlbcfz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxkirgl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzcdrja.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvrvivl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupdckvh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2weorjaei.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtokmfw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2luvsieml.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnqgcls.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jphgagwz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hckxjcfj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xxojrpcy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zmivzhby.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2djrghcwf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsfsoot.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2aukfxppe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgwmstb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnnvbbd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckejvv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oljqvnas.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcvopxx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fbclcsrg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrexjls.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvizinmh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2hsetlvmt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mocypppn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2expejwmd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2fcusmqrk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rnthyxtu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqxjzwi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qobsrtqc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpwdlgu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaasorzo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqeybxl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sznlntov.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkbycax.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gteyrhkv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbpsycq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutrczdf.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olkkvqfx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfksmfy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcaojtf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhyqhgi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrpblll.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tdedqely.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anqgjtoe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnbxjky.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbudyix.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yastiqow.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwcyqmg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdblcjfz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhotxex.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rkykzugd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfhrvzp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2juayzylh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2usgdgpfh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zphfadic.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gkblyeol.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mybamyli.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrqwnle.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dymlsomf.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaeqmcc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vaevaglz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcjojsd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkrutyk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqrzlev.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhnywkq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fegpykiz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2grotvlrg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuzjxxa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tafgjdxo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhqiqox.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvlwmbs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkivwwnh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vnouqoah.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgbejat.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdxfleq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2rolavbzq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtjgmaf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrintrj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2axmhndpd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rzivceyq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtlmqvx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpoyvch.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxbaatx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lahmrbvr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2onalwuaq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wwirshyy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylljtqmd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqveajdt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urashjcv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgmkznc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kognfjjb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfnhqci.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2tskumyqd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2entssxys.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2flgfutmj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fonshbtk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ymujkkbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lklqkshx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjxftjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtwsrvf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvvslmh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2avcuavsg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqboftf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sjshvqdn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fslafkkh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2etpveswa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeoofhr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrsxmgv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osmbbsdp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmcendh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxrlji.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmaeggr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqwgyol.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2newhkjjj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kleobljh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvhsaqw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2viimxcbx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2myuahwub.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoygtvr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhxwhig.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fejuhksb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vairbdah.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jadeyyuu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mcytqwtv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aybjlztt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjzotuo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyndzjk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ertzakqe.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2myvnbyec.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xmldfgsk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmadyan.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhnhsvs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gllhnigt.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2llrfxsot.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwwnuau.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2guvvgftb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2locbkzcp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2atnzccwc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdjrbrr.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmsepmf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzvftib.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2eudirauj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpmxydz.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dznxbmiu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2osfpzfgs.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqnydsq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jwltmcts.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2otfdcict.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkkpfao.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgscbzj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlijdaq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqzmxvg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxvlltw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnscfwxc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmvrmpd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbpjfrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgamyuy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjcznuj.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ngexixvw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2viqnhlab.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtbegoe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqsdisx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfftpkh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkprcnd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtcokco.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lugmtqqa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzrkvmz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oalmohwz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nufxnlgp.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2eeawfsqy.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2euebneqq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcwsrpw.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwczytx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2aynekqpc.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdttnmd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaarpgk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2skkijfvh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkobswr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgzlmwc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2funejddz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2npcoloca.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2grwpdnia.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofixyshe.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkolurij.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmqdmnc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2splmdkbs.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdxhhqv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptipdmau.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2goxzcusd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjecgyd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxbpewg.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsdfchs.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyykijcp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgscpsbi.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcssjatr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glljzfgw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrsjrqs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkygbuws.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvbbbeh.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgncbnfl.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auacetgb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxygpqs.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnilbdnv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2veprpbce.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rktxmhln.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjchulxe.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjtcgdu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2roxnzrge.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxqzhuh.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xulhvxxt.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsrepym.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2msjeczjw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhodndxt.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmcrlyj.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxbwycx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxsefoc.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbbcwpc.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldqvxi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwwvvlf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2hidozazu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tqesghar.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnblbupd.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sykelkfp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgetgjt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgcmfez.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnomevtw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwmpmxy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgkxucv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fwppcmvj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2htpxerun.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdtwltml.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hljebckw.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2chzshmfp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaggrblf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrcxjux.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2iaduiqba.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qfphaizo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2goslvicq.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jexrqwma.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zocmugvz.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxlcorc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xskudoko.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxescxux.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aitzxtxb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qgewvyiv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqffuhu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhrwqkr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoaiesr.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pylbokhf.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2edzzfhap.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2unvkfomv.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwlacrn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhmuhvd.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvstqva.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2moafoigr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqadsen.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwlemhw.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhfhhuo.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuhtdwv.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yviykaht.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqkgznh.html


<!-- 参考信息 -->