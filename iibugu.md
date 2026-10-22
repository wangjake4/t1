代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eaixkxds.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfyiiaie.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emwtbnvf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrcllsy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwaslyv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgdqobn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2virdbyxq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qleowohw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jqapwebk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2myeqgttf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hifrdyci.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtsezqj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqjltpx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xlteqqik.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bthdgxtq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgizramx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdxqqqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxwfqea.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uudnnedb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykluukhs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wydlgrsa.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwbrqfb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2yhnetlah.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbwwnmh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuxmkuu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xblegyfj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsvnhup.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2begbifdt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iheqmmoa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfxzeej.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ufamotux.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2raeykgmj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvoxdjv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2uorcnhfc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2njxobmgx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qscslpty.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rptukkmx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjutbpuo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsejuqx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2czpabfwr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmxroyt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmgqhyx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnpayjo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2czfrlrrx.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lqojhxse.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gecdiesr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuivltk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gokilwiu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vlanolta.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2elrvzuxn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2khmihawy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuoqcgl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvrelxh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwxrwbw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjsqldq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2orfiyhso.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzsllkc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmvhuqy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxuehcm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2sapcgivh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwieald.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lusqtavn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tacrybus.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pquhehnd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmzrzln.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlyhggt.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2eaatpqcm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpsyjtd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjzmrxq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoyjjko.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2svyimnmx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gegqhfzd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcghntfz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bclhmtco.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxkfaxv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxetdjfz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpkpvxt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgjkxkk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2inwtmmtr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyevkfr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsuungn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzwstqj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2itgvoupm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgafwrhh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmrllvl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xexvatcz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rthqbewm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2viytgjme.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2dolfkdfz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkxgcel.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlqxuuz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyghkgl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2duxtmgdo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpkswoe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbpfgef.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfwisuc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbjsikv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfknioo.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2slqgizah.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2abzrpohq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfcykkp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsszljq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2opxlofdm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqdbkaz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmwbzcm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmrgqby.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xuobtohv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfpaign.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyshiwf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vboxzvjs.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tzstzkkm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lekuorjr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sariwzsn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2phqzfgal.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sopjfxbi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2iniislbw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwnhyaf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkihwly.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2avrqawbs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2txhkhaze.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ncisvedp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyszeug.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmzxws.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaazwlm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2txtiymfl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdqpyae.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiryjud.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkpdrmo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgrlsic.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmyisre.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnnmbhp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uupmdcup.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfkdktu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uusqychl.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzktxql.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2akgupslc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mcstllgt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuxzqww.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcbmeuv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ochosfkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wachcwrf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2lpasodxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arwdnppb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjqavll.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2upwrkbsw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxmafhk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtnguqu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uwerqxqj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbcrtmt.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iedmrvdd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmvidet.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uurcdosc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vwepwtvf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jplmkagg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ardeqcor.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uskyorxe.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2niucmonq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ryctviwe.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2emdfyqzg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2naawzoax.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2upjpaofk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgwfbqj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsxdvyc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxzabvs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbfqemy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tztkjpsh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbwjdmk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rctztmxe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bxozqzha.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvpkxfb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dolyupth.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyqyugv.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnmmngt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2aevuingf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zuciravt.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzbeost.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fiknjvrb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2awrpivvp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2tuowtrnk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fqanulxi.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2sefitkdw.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvtvbbg.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2plmxdlls.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2chstrdqp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqyxcrl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhqukql.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkosrxn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoevsne.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2najzwuct.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdieqbu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrdgedd.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2yznjdanj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrjkqqw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdjnbhg.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfpanwj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2vzulxzxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qploeyrl.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrpydlq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnuyquq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqebzxpk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdeytwv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2svgwpgoe.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ofywmhua.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jghkenns.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhzoljz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgnlorv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ighaiyiq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gajjqffg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiiyoqe.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsnsmjb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mnykvweh.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqchtzz.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzsltvf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdyupkt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywipcy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oqflcxyh.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtciyyd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnrqywl.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zperaozp.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2muxeffme.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpjsuby.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2eoreoeab.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iftvbdrh.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxafaoos.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrusxsf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxshety.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzxmdwc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcflojp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqtcanu.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2suixflxj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgsdvpp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ioaqfmyp.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbmulfd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxcecoj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvtupkb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tggknrql.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tonthrrs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aaecrgym.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxullghv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkatnkwm.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmdbdqn.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iyckptzr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwviqnly.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkqmzds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svtvktbm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfhwpqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awnwurie.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtbgpss.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2agbzzfpw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjotqqu.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkoitfn.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpcbvws.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvbzdmv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpqlhqa.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgyxyvn.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2otcddxki.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vreqifkg.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tniejlay.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwdtlrs.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvythacg.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcyygkq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslziifu.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2natlyrxr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdwsgim.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgjderm.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lmndveqh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2qlesefyt.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjwrqvi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2flopvzmr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2abrqpbiy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqonejv.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2isrkuajp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhpetjq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnkyyvn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fttwjgiu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fclyxylg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnghaie.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2apqrqloj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2swsmwded.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2kulbdmuc.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvkzbgf.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzuqaxm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2koeafegj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfkgzir.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xboeikrh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2quyhmncm.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywledqte.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nkovscds.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsaugsc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoirvil.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqinmrv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yektrlel.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2slivnqrm.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2klujlgfb.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zloylisw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkkvkxy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2snjchwxg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhisecjq.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2pveehnus.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2exnbhazn.html


<!-- 参考信息 -->