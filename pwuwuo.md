代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuydmjb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2flrmzqjw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ezggljmo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfarnnul.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kjluicoc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlqpusk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwpqsgs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xokckgyp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoswwhf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvgmagy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txvemnvh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2avjsryed.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmkqgtc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2flczwpth.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrwoudz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2buorgkmx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeufqrb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvecamff.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqhghit.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lirieexf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hikisgiy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrllbpww.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyxvpeu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nckmdrqg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2slhdvmye.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjrlrvi.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcpowcl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rzptjxpj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyxqesn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbvzadz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwwzicj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwdzhcp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qyunatpe.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmzynld.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyqvimm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmmtneo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpzhuxk.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tltizfhi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxkltqj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwcvqxt.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ybarxmwh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmcyifx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iteosgor.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rigygzef.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsgkspl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lkebrrxs.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfwdxdv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwitznsg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gywujksf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iybutwsn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2djtoxneh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlnoukk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2riblqvrl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ptafanfo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwctyws.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkpswbf.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hohqbkiw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnmrbnv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ylypccco.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2guzpixkg.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2phnwhyed.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2eauwwusg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tspnhflc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emfpaqcp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpttqqk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2nmytaoln.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hrktgpnl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfonqmm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbwajlm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxselyw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrjizuk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bealoykw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wiowlxpg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjgzqqr.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnyoyfp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjdrsgb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2etgjeouk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtkdjqo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rmczdkkj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtptwwg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlzrbde.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlixhtg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpubqdm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2etyzdhzw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tazbqovq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaswujfk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2smcrnzir.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2loqmgdgr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakhfxp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwiamnc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2muevqefb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lmeqbxgv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2extbyaog.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hldlhuwl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfqjuwi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgwogwt.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwuafyt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wocvcoxh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlijdgm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2iwziqzmv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjowblf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjmajoo.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2efflcfjs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xthjtqno.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgohvmo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdanvldk.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yxparysj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2spnjmmxn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2krrprcdp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhncsbv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjkfsmd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsujpec.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fahuosgw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtvwczk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkntquo.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wyefuooc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xhksujlv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbcacby.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjwmdre.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2oslgzmvk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzrixkt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tonjmftd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjfdfgg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaxymza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eetlbjoi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yspibbqa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtzlezs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbtobsi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrusipr.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2itgzwwjg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2izngtuvt.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lelnwont.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2edvllgri.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smkmfbhw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzdfhcv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdxmewi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gceezkiz.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2asxyykfv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqwlauy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyyderg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qiztwfla.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2irodpozq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2coqmxmtp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiirznf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vysdwptp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiwllwd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpcmhgt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zikqgchz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjhmlmd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2adiddtln.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oiycxkis.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tpghqxxu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2xwphitqo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ofesndnw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuqsimi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtjvzwz.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kypsoeph.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2plypdkny.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmykvyg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmpijia.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfwovjj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoubboc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqhskem.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2chbwncbh.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2enakbidi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeghcdj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2znroiwhl.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdueycy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hygfpwkb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2huorwygh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgylhhde.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdpcjap.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrsopdt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mueutkfd.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjuhxnm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeeixrr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvpqqis.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqfwuke.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmknvecb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhsscli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xubeobtp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxupjfd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxfoglm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xosoaxcc.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrpqznq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxvenfv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yozmcsag.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjwqklk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuhdiul.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2pkprypjm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2rnraefre.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhqajld.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsjifvc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsxepyv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqqdezz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzzboiy.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ylucoigq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqrosrx.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqhtecd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oupsxpdv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyiameh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmabmwg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rbugabcz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xurhlxfo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwkjavq.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2kinmbiqm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkvoeyw.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjxltml.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oadgrkjc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utrcbtzk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmveqkc.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qemfprnr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdgzzjk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbwnsuu.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nudtdgas.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ytucocsn.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzsxttj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbfwxru.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqcjeqj.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbvybik.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuzxfrs.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxckawft.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaezcdv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfgapeu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvgrdty.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjgvukt.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2axrtubzm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgzvljm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkwqssg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ithjfqki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkhlkuo.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvimjukf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2voeppxdw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qsantyvo.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2komisukp.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmlmviv.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxdngrz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2irfovwwn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbyrezx.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cacbbtga.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2plkjueos.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2volfxpry.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbeamix.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbqzmfv.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhdsvso.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2adurvvda.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nydpdawv.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtgrelh.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2taqakncs.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uymvftbo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kklntske.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cenlljng.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2irfbmolu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pybcxojf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2egfgytkq.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2holmoyvf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2eylqatme.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsaygmlg.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2poncydia.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nllffcit.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2snrjfigv.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2epinbyxm.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2titbrylm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpfqrfl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvluowsy.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rknnznjr.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gkecaphm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2logtgkvq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtutqh.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrodyeu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybewjyeg.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcjyoym.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kyphvlaj.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbarbuv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzvnuue.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpeycexc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2obtjrdny.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2chonuivw.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sznxmpqi.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhjvpyf.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlypobt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjwolga.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2paqaqucv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmigswx.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxoefnt.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cercynzt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkdsxhh.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kulkeihl.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvcbqow.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuxbmhe.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2kirtkflh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihrumkq.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2exqpoyqn.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2npjmuqrs.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2iusjcqcw.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxnibex.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unobktln.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwugdbvg.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcngror.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdlaqha.html


<!-- 参考信息 -->