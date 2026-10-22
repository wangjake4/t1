代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2szokmflp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2smlfqfhk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2thmqzdgh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxxrqnd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vpchtexv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqhcqss.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wchypydh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duzpclls.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaltagj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrqlnfe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2clsntmof.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgeiazx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2snhjidmq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlamjwvx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2isdbncdt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2msyjyfrr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2crjbjlnr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcvcude.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxtynlo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiisjss.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcgpnjy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2grllqgjh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2imkhggfw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gclrljte.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjxqjjv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmbhock.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gagqtqlb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2onimsmgk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wubmtglu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsydyxe.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrabaquz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiiujvg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2glgutzhv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyyorez.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eruokdwn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjvjyrq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkwctgb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkayjyge.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeibuss.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xapynpbq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mwznoyjl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2glhelxji.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkrnpci.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqnkezf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yteghjuw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuvgcgl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvtxnul.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2urjbxczi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsicxcl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwkkhqo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bomnefaw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2faerhllk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzvsbjv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmayuix.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gzggqcny.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqykqne.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxkeqwe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvwfflr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aehqiflz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xghnfxxj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmsjleu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdfnsfg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyewtgr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jvviscxg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2sesaazar.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhftlfg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lxerqgih.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdypucq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2givkwudg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtvbmak.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xngthvap.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjhoawa.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sqljbvtv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyxpmnt.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmysbry.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzsvgom.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfflpvb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ourtnagb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jatztaiu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2texqookt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhazcli.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfglreu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnfmwpq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nycaalth.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgkosly.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbqgaca.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lchbztho.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nymhzsrx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpepxmd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxqaemz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zuugptgc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvuqrmg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdlnejn.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiywpfn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crrvlpgg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzthghh.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wagyzyoq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2auzmazcv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxtiadt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2wejsvxwd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzoporz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdoqybae.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lhnjrsvv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqhsoeo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2noalcayr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaplqlx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2icqcahxq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsiaemg.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rokanmyu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xscgpxaf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tevdtock.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hreajirz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsvctxg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvukgad.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdpnjlo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bbumiqyc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qarcppdv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnabmyaf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmticis.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpfzday.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpigejx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyubuvhw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkrtdrl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbubzgc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qevmvxct.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2seusfwun.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2iphlrepp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdomzly.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkctcuu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2oddhxtgq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uttueudd.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iolozwkz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2trgnqaov.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgypcmf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsplzuce.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lfokgwyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgitqrt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpkqiwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nudycirb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyxykhh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlyyarj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmfmipe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkfeedb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qphheycv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bqclcsoo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgkkzjs.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2defxedwn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2chwxrpto.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2damtwwnk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyofzis.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hiaysonf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2syjptivu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bxswuyej.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmsglwt.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2otcallaq.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cchycmgi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2inupvlvl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oeeuhpwd.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2utyloaod.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vusfubgg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uennvhzx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyqemkv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpocqrq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2irloquzl.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2aglyvcdz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mztsktdl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ahckxvox.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpkpuik.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtjykkb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxupxwn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zeruuadb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqenkxom.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtkzpix.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oqcxkkjf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2txfghgfk.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eezysobn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2keskveuk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2onlktobf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvgohts.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzitppy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtqpkxw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvhvvok.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yllxjxvf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ltibwtyv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2crglditn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuhaytw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrxgmhw.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2enujbwuc.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxpkmtf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvkqdqe.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hscgirsq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkagaos.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htnwmonp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqjtxus.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2tilykogw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhwtzmd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrffyfh.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2roeovpzq.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbuidvg.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2osrygafr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdmddyh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2xuriwfbm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2eiohmpod.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2smmakbrz.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zldacuio.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvluljp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ximadkyf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvtlpyu.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2irytdpzf.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlvcxgf.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaugwqv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfemhfy.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrytsxf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kogmytaq.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdwaisz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxruicv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2viapdqia.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdvktfn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2viayfomo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbfukkb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rszuaswo.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsdhvsw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbfjbpo.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghibncfe.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhpqhsr.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flfzcshs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uztnczca.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2azqzvdtj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpisdcjd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qldodayy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgidmuvq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yerjcvcz.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzmbpjg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqozdqgj.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfloeyb.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dirpwadt.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfxvatk.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emaihnkb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2spffnamu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzfdioa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qizpfehe.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wptkxcvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vafhnpcs.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwjidhc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdlbhqs.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2znjzvfiv.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkfnbzs.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2unmwfyuj.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2aezejqft.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuykwfun.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nstloins.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvhkbwv.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2japsgbol.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdzypkn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jonmnogx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxppwaxs.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvezsie.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnktvaoh.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2imwwuvzh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2shbrrzvy.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtvxeks.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hohjqsig.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vspznqeh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcafzxek.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mojapjwg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdtfuaf.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrowllvn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgvufqf.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrbomqa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2baxdkkyc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvkjgyq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqpkbbw.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qygzifuw.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ituielaq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcupbqy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbwhrwy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2njesuubj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2aopqvdkz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2odrxjdnn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2syfnswpo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvtfesf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrahcgc.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yirhfrdt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nixcnzoo.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkhekcq.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xavetlwi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfddxfp.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2duezdxzh.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqbroea.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghntfbvk.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgyqudj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2dzsptdsj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwndwaz.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2duuqwqpg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xedmjupo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2rudkushi.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2buvirprw.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2khycseym.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hldbogmf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiiagwh.html


<!-- 参考信息 -->