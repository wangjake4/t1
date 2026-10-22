代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjtplfn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2otwnxoae.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyellepm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfojukh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqgpahm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdelrusw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsveajs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qowyojds.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nftjytwp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgalsfyc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfrvocb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2slgbekij.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xoevghni.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtngqxb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ddomhmxu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2etcihjzm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jsujcgsi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2njwavwix.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2okdsswrg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2biraeazb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhbvohj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yujfcsni.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qexkcamj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrrtabq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfvysqd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iskfmjqk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcbmawr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbcoisp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2czaqnavd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkomupf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdyatfc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvrsyhi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kshwpkbt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahohzyov.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgutcxj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhnjoez.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjkrxup.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwpamiix.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kdybyxws.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmfwzbk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hlicfyzl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gepuezpl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lvawihzd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fczhqjeg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbsjltc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2odkgggsv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rsziuaxe.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dkumhakn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdsuawt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wxboseqc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnvvskb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fvchjypc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gclctlyq.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqzfrhw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2izfekfhg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekejqaen.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2blsqpbci.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2limxjkjf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ivivsrjb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vyaybwum.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkmcayx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaymxbk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hnazyrkn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvufnegm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjliecw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpkxsps.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gulkibsw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythnljuy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2embkdaza.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbammqyn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqyyeks.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfkrgna.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2smokzsbz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlwadrd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bpypvxfr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkhdhwv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjbxhmt.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwadvcs.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vetkmyoc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxxqoq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqyjgqc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wftskcux.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2amzafuds.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfunbvg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2aexdktxg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pztlzyho.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2xdywakjv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kflpvzvy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2appctjum.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfaowki.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2swlcxufm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2perynqbv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztygsgon.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2esrdkzgu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nlprcser.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvnegco.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgixwty.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bodsfqzr.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwizwpt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izbwprci.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhlzdcu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kacectbr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxscnfpw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vnavnuwh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrvmcjt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagqxkfs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bexqejkw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2llnllfnw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyolquy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhbauzy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2omtcxrcr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaupqez.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmhgbyi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeskbye.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ojepkeyc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjxvczq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfaryat.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdviwcuj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2drdxskcu.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaicdbbz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlkhjlp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrfigmm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzpdfgn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qspfsmmq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tlogicwc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hplhjtle.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2glggebnu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hruavkim.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwhmtst.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyxemuf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqpulha.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsiiswp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xctfejdg.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgmfkqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyzzrnq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uxypnhad.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2turthbsu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlcbgit.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfubxti.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2spokwpef.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvsthin.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmhbzjn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrwompy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2npeunowu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbnyors.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqcxzt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnxbktt.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mipomfwv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcirldz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2netisdxc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjnrbfn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2siktfuki.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sjveszqg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ijovxpbm.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfvtvlm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vubcubna.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrkiwfb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ydezzrpz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrsoqno.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2igfvlvhf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2zznehidm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ufemkyjc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgnuori.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pftiluwm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrzdjmd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2giujmfwt.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dbttwsnk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lwklsnll.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhqwbpv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2quymqprs.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfcnqvz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2duzubzdo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwfzavg.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqreswt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2snqireli.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwlbkgj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2msqeuimd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2twguokqr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkyameh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2klvjwviu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhnvzqh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrjquee.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2llvcknsi.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2giyyalsl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrdgook.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmblvrlu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfulzfh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2pdojxxvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzsphcf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2glxyslea.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtvalkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2abkihotf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2natjokzw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2aynfngzh.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2zekiejpg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2oiawknwj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrkwqbd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xgysjmzc.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mudahtqz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbyhefd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbpglmr.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ieibokus.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhuhpbt.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2grqksmzn.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyshvoa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsmctdd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hthergck.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2fdysukia.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjuzfrx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsmavop.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2takrjnzi.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhfowlw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxkqhcr.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzucsji.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmmdfgn.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbyzzjf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esyvkxsz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jiggnzod.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsqhzxp.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmznygkq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmufxqn.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nthiwfoo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrcqgvk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uirifiri.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orvyafhc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeojxxz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzylpvnc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqqscjr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmuqhie.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtapzbtc.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvreirei.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrjszks.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsavzlfv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rttpvinz.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfnbkrm.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hifsaoxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjuxati.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndntfsiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtaylzu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwbmqim.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxblxfm.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2prgsbphd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjewholx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jccgupob.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmcqbxu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwbqzxq.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iblgkuwl.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yljysxot.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxclqsl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2efkdenqi.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqlzpvm.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvzatkt.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwhfmnv.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxjlakt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2aitkowgx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2omdbmvfr.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyodplx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2brjaomfs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wfatdhys.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhdeeff.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2opnpdvnz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxpntbv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhgcntg.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2npkvlbds.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2zntmhdzb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qogiaqxn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttoijdqy.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2webvsmna.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xidtvdxf.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nucbzuhq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzeqygq.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjihrhl.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmdkmdu.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxutpzm.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2nyubkbsv.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2moanpxeg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fghpvhfz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsdlbdk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyfafhk.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwagdvf.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awjminsw.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpbgqzl.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wuafekqh.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwfqhgh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jswsjazp.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2doshdvnx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tndnjogs.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfpenor.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2skcsshnc.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2egmvefkb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2obacqgpv.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaxthui.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsniytma.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzoahjt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyoovjc.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhgzjwv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2juhigabd.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pttxqguo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nypdvyzz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsgpsnh.html


<!-- 参考信息 -->