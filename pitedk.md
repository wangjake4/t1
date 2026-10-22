代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdwtuul.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqckwza.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uoonsicr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uawbwplh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltnens.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxoxjoq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbcmokz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2egdxtbvd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dtozbyfz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2endeqqtg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2libdwebu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfpctmr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfhbtid.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnxerlq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2oesqnebt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyofaoqd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzhnory.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjawmfam.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kikyrpbl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjunniu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2veizzijm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndogtqe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuobgsl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tclanjwa.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgyjkug.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vimlakfg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwfymno.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtiiwmz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2coumsrmy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlysldd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cshngpeq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2byltbxzn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2duomyqnl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2trrqzzad.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeugkyv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2joobyclh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2spregtnr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xymteqem.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxnuzwr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrsahjn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mtblwflj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzdnifn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qayxnaod.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zlckqdrk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtbessh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrayjto.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2etuseedv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyzvfbo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kntujjrz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkydjuiw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnjsqbe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbjmpts.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqjjsff.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xycroepd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mwokodhc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2elnlgyrj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dshyizke.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2phbngtwx.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wuokehwh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeoamsk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlhsmwi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eswgqwvg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeqtoto.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnejhhp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfxvecb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfgunyx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vlekbche.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiixrkcq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjvdpvs.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjhnixd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgytmmr.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjngnut.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbzhimj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuahcty.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqbytmg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjetjaqg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnuruab.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxsqlwp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdmdqkg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2egviggew.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eaznoroh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qydqvzlx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyazugh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lstotwyl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpcvkaf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncreyzon.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2abmfhqrr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eujvwrvk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2yufmcvrv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdotrtml.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovrpsm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfwhzrt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxkzidd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkrkksr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuramur.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwgypbk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmzkbrx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrugqezv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2leamrdhu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnjownm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2trcukdbl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbizgfmp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xbziheut.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2liapowiq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2faiqqqph.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zridltmz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2padfyqol.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbfclva.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2yedrbzfb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebltmabb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qliwvjpd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cecapvqa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dkccsxbv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vewhwdnu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlepkaj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvozjhxy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2irkcxbvx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqjzipm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqalinx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mryswsve.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2owraaqtv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvwcpld.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2uslexthw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dovtgcsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oedeswzm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yliuyqeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kstxkypf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2etxaskha.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjvmfjm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxrwicv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2szdasowo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmupwymi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaxncew.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnfippi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2urmlfuol.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqdfufq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvzrwib.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyxpjzx.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xbswekxx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlwlwwh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiuiivb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyvfffc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sznomchm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2aussdmcw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlpjwmw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzulroe.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvbmgvt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgrhguc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpbmntv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ocupuppt.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sghrepnq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwmtpkk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jgimiidh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rqyfyyvk.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdmylcy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wnojdgoc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdyxeje.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2luhuysbw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gfebwsgi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzizyhy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvcxalw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2lusysidp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyuicwm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jqktsrtl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmuosqf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsrpubw.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zthrtsan.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2axlelrbq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2aswrpstg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hribfwmo.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ytellofq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmioalx.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2blclhgpz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqifvis.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzqlrfj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrgdeue.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2aznoposl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmnpcou.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hsikctsy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ogudqstj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqxhzok.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2adtxmqpt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sykatxaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isryhdum.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2rbormgki.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfxljyi.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zimramyl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiclckl.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2znxuniwu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxmljng.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kflzqgbe.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoflwtb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fczamlol.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2cibfnjqj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqkejfj.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2subsoncx.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nuppwchn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gtofpbrs.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vbijlgqm.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcadfcq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxdbzhx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zhitbhnd.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2hnappksk.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2gelityxz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dvslqsny.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxtbfga.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rddvdexf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rebdeokx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhgecbz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oafwaujx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iaciigfh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eveplfyq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhxqwrr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhycdcj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyjlbkz.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrryxzn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olffhurm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vilrnddw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axwsysxd.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qofqwqog.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lufbxxhq.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unytdtat.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmghpmyi.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzahoiu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqqjfvd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lohtogyp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pckjfnao.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqozzbxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irxsbhbn.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bskdktmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwcaark.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srnsulbw.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fanwfaqf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2brkazxbl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vywxaess.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtpaubl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhekyww.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuuuoiz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkdadgd.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jcagwgnv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxftrfo.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2achvadvb.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2eemywruu.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkoqjnw.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhsgjtc.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnlqmwb.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2savwqbrf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2osbhxodq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oipeailw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yntrucou.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2iesquaxn.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pszfvypd.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxrckbr.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfodvnak.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfluxww.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hcssasah.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lopjajgz.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyrqtnz.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjrftox.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gshracgk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccikcktq.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwqccsv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxmzlld.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2olqlvpdy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2evtonqje.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhotqkp.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2efvhativ.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2harizbvi.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cyulgxei.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdnybxz.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbeipqo.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eynkyclt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gguhodzx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2anaowjta.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fvklmnhp.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2isujxamy.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzyjucq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksitozev.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2unogevsc.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooioxike.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2friivaxi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjchyfmv.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksumzqhb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2evfemtqg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwvsoqh.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzevhqoy.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2radfgvum.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2umyoceel.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zocswztf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtovqudt.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehmgud.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrjypcu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsklunv.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2svpogsem.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuxekoa.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrsmftf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqxeywv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvspbmpu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojslmxqs.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvibmpyh.html


<!-- 参考信息 -->