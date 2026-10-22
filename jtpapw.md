代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nndbdzzo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lievftdk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxkvynn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qutlxeyn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nrytladh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hqktntwj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ngrjkjeo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbvjydv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqofltpp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2evlvrrkq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdreqqv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpnwtue.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fsktavkn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgjzcda.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2obkyaytm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgblesv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgbcjjx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwqmjup.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdvvocr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjguszld.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoqkxyo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvvsmus.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2findfgev.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiqmvtr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyigqjw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzookwy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ooowwvjm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcknnhp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2irmpyxep.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnerfnkb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwvrcuh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzchotyv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpvfqhp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2klcdlosb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rofvrlwv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdjfgrg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtynddb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qebijoic.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxqrhds.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcrikot.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmrmikf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkblepum.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qewqsllr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdydbfz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ismgdjoe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbzrifl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjmwrze.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuppxci.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wtegevwg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzzwgwm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2idvxkufn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbzuzdr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmqmall.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvsiwho.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsikriv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqqqnco.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eaomixhe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdpnfgp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxlcnif.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdiqqbq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zugzjjhz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fatpeimx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyncufi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmjeka.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqbbore.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgfiqys.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmeuftl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrdhleh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2umnewjfs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpxwxwt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2suizwplf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2unwywhkj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhgjnzu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2okzkwvij.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzasnfi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbvtwec.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfrxmtf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kelycsvr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmzddor.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zexjjbmd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jumnwpbs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gubbabwc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dxckdvfv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkpljbb.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2edueavyx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2efzljsar.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfequlvl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2emftgfxk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2terzlojg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2natzyrny.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bazcajpx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbuwrki.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmprdod.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2joduhwwz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2opeiqfza.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2loutkiij.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2cizfujuh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rryznnnb.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxieheb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwrgrij.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdblkml.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmlixfo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vyosddre.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ufajnqyg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2dntrsnzo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpimkvty.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2soqaxzfm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kryingcs.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2odjditvd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgfzfxz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzessxs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvdxhyh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnxxpaw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuowtgoi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghutuafp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2skfeqetb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmouooag.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtfbrjs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqdpidk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2klqniqbp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdoatmj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zidaqpsd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlxxwlt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmztclvs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jofqfqto.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2errsgkhl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdfejuu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhpfcbq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zklamydo.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfnsogd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2grctvzep.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2auazlfkq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwdcbln.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lpykvdvd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qacvbmrn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2upcnhhzk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcfwtpw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2viggzmks.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqqmzrc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2chvhjfpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoxsrso.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjgjekw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiasryn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2avjatuxt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqujlun.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dycmrxhz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aivsbjlb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhbayjk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjiiqqw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oogmkvlc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwbhzzc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2osgatutz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvtrajr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2njwvsnpd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2loudrxny.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbhfymc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzjmexo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wbozshzb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjrebyw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdndmmo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzvwxyy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjtpdoc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfwuvzy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lfiundhb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wndrfyxr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kapwusmu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdnkops.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2quosgyxm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2gligbacn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2psbmjsqe.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyxogog.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfqitgi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vvulefra.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2taekfebn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdhklon.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgwqqsg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rfswtxhd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2cebsvyvu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2otkaywim.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ooofyqpe.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpgyqmw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaqnsns.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgoqabm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2piynpbmo.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2griyyfqo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2soeioetw.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gjobyqlq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bqildraz.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2iequxxbh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiyvljh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2opitcgdu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2tamninvj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2elhxtuvj.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrqrojs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vuckcddg.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnkyvyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfbsoqm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2hoalesmi.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbqobif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xleanoix.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2cvktnefh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nneekkhv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jekinzhp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2eancwyim.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcspdv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2jdyddvzw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kaallxbo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhnrbez.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbajbfc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vxodnywv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zvittsww.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2znmxnfev.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yozijjzq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2zyggvmad.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ojleliwq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfnoxey.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfbkcwt.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2almtufhw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjynrot.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdavwwh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2roupysna.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnfqsfh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwyyboe.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvvglhi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlknnkek.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpoecyc.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbenitxo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxhxavp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhsqxla.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2csrmquli.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwovimbk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tezsucea.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlovfuuy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lswjrjoh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaodptp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abrmrsyw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmvvhhp.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2plfvhnqq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfucwwu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scuyltgs.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfwagjg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcboqlvb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkzggag.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2moklpemq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esauvivr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtjjooq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tinlkrpz.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pvamkedw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbbmmck.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2buufdkzh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaxjrco.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dusxbufn.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsvlmfv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpctzaer.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrzfzuv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rswdzkcy.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjzwieh.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rvufxlpn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kawmpdtj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhqxcil.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pogfyqzc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvakarft.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsjlbko.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2eosvargq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2suwkhatp.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2urjueteh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsbdhex.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2scwqnygv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xecvyboe.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcyejxl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaphssv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2whmjygph.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2elyioyqq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2slngokzz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkemxwz.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpwdvgg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfobdeiw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2szbbhccv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2owyqphzz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fufwhpsi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjopahx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjlrtam.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwxivhp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2eixgilph.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2skqhitfx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2woqcaaox.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2khwzgwtq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxxftev.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfbimoq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdzfqqr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fshykgzv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ygclatly.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zjofkjmg.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2blblasqr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwnhntf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnfmmyb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2aniovnsz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hegidaxd.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2snwjfppe.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ayufcbjh.html


<!-- 参考信息 -->