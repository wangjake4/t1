代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2soqqqisv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2krwvdqtq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlxhtpf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kguylarg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2skyehbby.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxcgske.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2awlkvwpi.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wooavnwm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqgoukv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdnkxqw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2prxeomgh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2faaodybo.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tojlvvfd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvqwgif.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbuqzku.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeqxved.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ehifsfjf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcbhaet.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfoorrh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuzmojr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxdibcz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2koqgsrxd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmbsgnl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2svyidycn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxxpkux.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyrszmq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tiowtgxz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxrsfva.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfkzdyr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgurhgp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlbqvsf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2phzpacin.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2onohwtiu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcggyaii.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2shedxwox.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jitkghxp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcupgkw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwoswep.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2usaahrmt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyghnai.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2flapzzjp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbelmgm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoxaoia.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhpwmep.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpomguj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqldgho.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvjrzta.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrhatjr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzljcyu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wexerczv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2saojiusr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wotexalz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqoablw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2qanvdqcb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zajypcix.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cesxwfdq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvrqukn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kgejsyji.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lseqmhwb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dluazeyn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qbedezez.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgxyvli.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ailtubab.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yirdkaeu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuauxud.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxffnfn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2argpfweq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpebzvu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgddaty.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjledkn.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxbqrvr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2koerrkyk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcttxek.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtobxtl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ikputvfh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqtbdrt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2joaewwbh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vzefxwve.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfxlmay.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfetzisy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkfdcpe.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhmuorz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzujktj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqohxvcn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ergilqhb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtufito.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqpysxw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtjrqxe.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmufisj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjaglci.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2lfggkdgr.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrzeqfp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvvrpuy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvelyamt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uibdjzbk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2imteaahh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2noortitt.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfpyhai.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpecfps.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2drpnnwvs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbfrpcq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhopeyd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrhwqa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lptqyfdn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxgfzxu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqovvge.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2clzjhmsh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2prbbalzn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2licroypk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jupurkbz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nedfavph.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsisonw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxmxmmx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikyslat.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrqkppb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uqerdfvh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzngraf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvepsyt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkgxtvn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpmelct.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ulegpgug.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2omswurrw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2amtvngnx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmnjsum.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbfldne.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfopcnxe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbfxugi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vphplsdz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uvogvicf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2thqqqsdk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2zsunaapv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2owuxdnpc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cdudgcov.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jltgqwof.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2auzygnwa.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsnymbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyduuyu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtktzph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkgqkia.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2huodkckx.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sktqbwyk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rblxmyzk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdkdsdb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiyzrkv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jdutzdxi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyztyfh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqyuxmr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyvydbp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sekdsfys.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wzsxpuzk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ascyrpln.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgzrdin.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgukmba.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vheieamu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqvkqyh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxpchna.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2udjxfdgw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcvzokh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2iunubnbo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vslkpkke.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2oppytoxp.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbrecmu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbaxfpx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gsipyfdk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2oozorlsi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdqxwjy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpbbwjf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rejzeooi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgxvzvg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmvbwpm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhewkcm.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2minmepzq.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2quhgsxzr.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2obozpwpv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2yhykxujy.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nouqvhkc.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwadoyj.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfpnvxx.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nilhcqbp.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ugufnnnu.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzixhsu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdjbvdh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cerossqg.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwqvwfv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jmndzmbq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjnokcn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qvymifpg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zeawzcgv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2oabmhwix.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpiigec.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxsjtje.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xkhowega.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkaioxlm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaopilo.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkibyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amgmcbwa.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdskapb.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdhzffv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2spxomdnb.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mlncxpux.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzuekvy.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hehnsoxd.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtjrmzs.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ttavonto.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2mltysvgz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nzareacp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ssepbycs.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgojyjb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwboeeod.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kkigwetu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2iexoewsk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukscnupa.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtfyzyw.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxwjzky.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwprdhg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ewriaixb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fpeartui.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuymxmq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qlasdwpa.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpftuncu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlqzuwi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auosmigb.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pepwmrho.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2llvbdsye.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hroymxea.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qebmswwm.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcvhdgb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myvhayha.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oamhlzbg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzhiqaw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkyxfbm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuajqpa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dszrphko.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwnhooi.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2edsfikrk.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lokkgjjr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvadanxj.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsatxz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hukepuls.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwhkrjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrzuwzr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yknfxngh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sghdgnmj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqolsrh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxrlhyx.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtkgzax.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2blkgeoqu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2leoumkqz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxtrxta.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2aufewgnc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vajdpalq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvrcufe.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgejvfs.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2khgbqeyx.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2akhjykyi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmftbsaq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcxgfog.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2trylffmd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrvohnp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gguvtvgh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jitvigrf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jirqeqne.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyttrlf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjylyzw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcwqovr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xajulvzi.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyslwc.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2nghvrivj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmpuuzp.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqtdhzs.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzbidjs.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nccehhgo.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urytokyj.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2klbcdeyu.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nhytdnxm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2amzymrov.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbjluff.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgcazlu.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ismxcdlh.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqsibiu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcqyyss.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2arnxeqzf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwskozvn.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdcwsxx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izrvavuk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlzsvgm.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ombikrle.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdsdiae.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uugdxxqd.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2emxwwjhb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2psatrxev.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnnleme.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlawxvsz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlibmrad.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwqeszw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cixcexmf.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2coeumgxs.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jyruewyz.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdgzoyz.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgsgfiw.html


<!-- 参考信息 -->