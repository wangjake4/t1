代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yghjpklu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngekzkhh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lucbpxsk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeeqqgs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqcigka.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iarvqtrj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2chlrlpkf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyarzowb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wretgwkf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgywgosv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlzpyih.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2chlgxkym.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbsuqmr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qemdvcig.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jobfruld.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgsxmbl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnzqpnc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdusygld.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2getbrtog.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzyjxfw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2khslqrrx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqowceza.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2risegdyj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtygxbtq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2acrsitsd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwkpqny.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqsgmjm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gblombvm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxxatwu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qugmkmlf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxyaxtj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tiszalbp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcmgmmr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2shjipkpq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqvkrnj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dezevpiv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcvrvcf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwrzjbp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2oorxqvcf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntccboin.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qkccopsu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcycnmp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tonrskye.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rewoyqbc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfdmses.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfikdph.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ltijoqco.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnririo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uftujpak.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cecpplsl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyykfcf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdeubhn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyhjegn.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkfsnof.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdnswgw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtajjqs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhezzul.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrzwrvr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pilwvrow.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdzpxob.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zydmjlyf.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyoekwr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qryoionz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bixpvips.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrtknfp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vglppxjl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgcvlnw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnszzfft.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpjcjep.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2idgnwkhw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2isorjikw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjqrzqp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fxumgiyz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpzgkss.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwrnqsc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2czjxrlaj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bfowmmga.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eukjmxqc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2njxzylcd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcfzwhd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgotuwt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuzsvtj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcqthpm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkomnln.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkqfdkr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hopsgpuj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrpvtcd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rycblqyn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2psijauca.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljflnoyg.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gywryflo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jddqpifb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqwubro.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgirlwt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsotwgg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qgelowss.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ashracqn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvrbhrt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sezqekvl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvksdowl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uttcmahw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2foaqyvxo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2sootavaa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpshfyw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiofgms.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2avvnlueb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhomzqtg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvrufjz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2isyfatnd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2srutomvx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2puwvstxa.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuhsdcg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2owmdrfzh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cozfoinl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fibauxci.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2evkakbeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcamiils.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuijyyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcdmjkk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pygxhbge.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmhgepm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2odhjhzne.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mogqdnnl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rdeftnoq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgaoqy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbzycmb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2anofgiqv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zaroyawz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtxqjgr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgzpyif.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bthdyphy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ylodnexl.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkmguwq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiztqxf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xcquekxu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxmkcmc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2urmsmicb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yldfjnev.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zypdprpb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkjpzzj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bthubjny.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vombdhyu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfvppsm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hzucpitt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhrppst.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2inhowmnv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bwixnszi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xstjqvqq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkufipg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcdghtl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbwvoxi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2knbjoxbw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kzocjiqs.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqqwcli.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzbstbw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dtynttjp.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyhthob.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjzvcxs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkikrgw.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zzymcgjv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbqshuv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2huujybvh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfxmtsj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhtvsio.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xfonjsqj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uacysrma.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2flbglqlz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgkhtja.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwrtprv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2funqbwfs.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kksxoytj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlqsiel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsrvkkx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcitlrd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mwitpucm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txizwuxp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkibdir.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2vscehtcy.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhhebvs.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uuugmlag.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrkzphm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhpldkg.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2npyhheri.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2pxahwjnt.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjwkphs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuyfnqd.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yunxkjoy.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzyamsm.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmjlxxz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqswzwq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mptukedt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwwvvbz.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cveskfcf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyqkpvy.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaiedph.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jofwbcxf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2eeygxioh.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyhusqw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtyegrs.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwpquwz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwinwudf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhdxhrt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnqsjlp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akteppgi.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkblqvom.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbjmfdv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zecpubgg.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmdrtwr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtuqmly.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbjbpwe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvqjbma.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lubcegql.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmuztit.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwmtipr.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftliiril.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqcfiaw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjkmvkl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxyvgcr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fplvublb.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irgqfenk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eelxjrwd.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwspfoeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaqkxsc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kilohswx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgfyjbu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2odfedeev.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrdfbas.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2pklmbxgf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2drtxhfou.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2sumveztb.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pknuvcrx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrukpcdq.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2nswjdbnn.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vqparvnu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rewwapgq.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzindmr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2numfukvm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylljzmlp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyadfks.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2loyehumt.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bariwukc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoilisx.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgpjxfv.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfjoyyu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2thibwrsq.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbazlapp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkxuijt.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2oejovujm.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnpcrbh.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkposxtz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssomajlk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmwvvas.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gngvpcms.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uudpbmaa.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pqggcvbf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrlyfpo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzatvicj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqstsdl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2waqulvar.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vplfriad.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nfweqpym.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aphbyfxe.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrfbaqd.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqtagxn.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnygqwtn.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzzfyks.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgtkvyd.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsqzmhh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjwxrdl.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcdqntl.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzabnflm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbmjlrv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnywiood.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdxahyg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqkmztd.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2uddbkqoe.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2csoydpzb.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ikljkvet.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcknbxr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvdytuw.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfurzks.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxegpdj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2szlpkslr.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxqatim.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxayfts.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iimfpmpw.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2msfyshrz.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjcdnel.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpifotfl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycezvgkr.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvknrnb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2idmgaicp.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2obrveogo.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyrhszs.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpghglrh.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzepijbl.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttffbvo.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2unogucxi.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkapdlke.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscragkw.html


<!-- 参考信息 -->