代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfnebnx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkxmqan.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgadpwjh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2acaxonnd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeilavx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oeszikwk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhttmcuo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoerguo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2olacjpgo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2niarfawp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyryzrwc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dksxbpev.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yfreyhtw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2awjlwhse.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2espbwccu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdyzmwh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfyxvnc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkieeht.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrhzesf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvmwuax.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjarmib.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2frooukej.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmomawj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhotyygo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rutcbdgd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2anxrdrzw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2smdqavjf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2htjoufqb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2otspovmn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiramqya.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jippdhkq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdshashx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qowxajmj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sswkeufy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wamjxiuy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jarefnsq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2syrwhvyw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqnnpsk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmllvvt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdwdkji.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2htqzkgst.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgufynz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2efnqjimr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2urekgdnb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2crcfzsjd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjxcqgz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpnipmp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qumkunux.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmtuzhc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2heoemhqo.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2efyynlfx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qypknonm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jixtnnox.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmcstms.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvryuoy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqnitdn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyabxay.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xokegsqg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qztpfroa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxzjswd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqcetcm.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2galhqiwt.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2trsaohak.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamgvfr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrgbxjx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2srabblue.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpjcppe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiiixml.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2umekmzum.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lilkqeaa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ukycchcw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgugdox.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwossgq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtcyidv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfccsrg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxiquvi.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhiisxp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzzzsux.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2szhaalyu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmyksdb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgekiiie.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jyacclty.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmtpetx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiubsfzo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afwhdwui.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpxhtdd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvywfryv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edyzuwnw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuvcwtk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcqciot.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kywzrsez.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijipomux.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nazpjduj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2woqemzvv.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkobymj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jbohswes.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bovjzcjm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeisllf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ngowbyor.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ligjbvbm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2arfhjwdp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2szzhrrbg.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2osaaubae.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hebtzkqr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpwnshr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2byqjdedl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2icffzezh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2olrjzszq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdskrja.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnkzfcc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdsihbn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnosuvo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2httgllhp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkuwhwhn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooytlryv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yurqfrks.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoyjeag.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2putlvmxz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfdppep.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2etxzqkng.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhdjivm.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmghuym.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yyadkmih.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuillsv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jukhcdbg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2funtgpwy.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhpzusr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2heammqus.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uuakhzwe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oekystau.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvztnxfk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfazkiwo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2injlydkf.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2jehjvvmf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ysccpaly.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwsxkdn.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wniscyvz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2iwccrocv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqgyktr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxpgmyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxsxmax.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vyirvklm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoqktwq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdzleca.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnevaao.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ycovfpkc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nouzonbb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmejbqm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qwacofyj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ppmcpecd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xaghrnky.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpyerwd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2duaxsmkx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2auotwwpc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hklhmeze.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hoyygkam.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpyirze.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2salykius.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqvzycz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zaznllzf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdauidm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bawqsuci.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjlytsr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2olgiutsp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dpevunnc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcpovtb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrpecje.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkbjwoz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqzcqfo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aevnkxkj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlxzscs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkmdxnd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhrzaup.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwfzmgo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2apeygeye.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svvzvfks.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2unokfuvq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlhased.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyekyel.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqoxnhz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vvigbppi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwfvjqs.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hijmmtlf.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtaoguq.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2umkyocay.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxonikm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdtbpzu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oknolaiu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrqeoxr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ceroymbj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2apndkrtm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xabhnvtx.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2bwntkrpf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjjixed.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxbgwan.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2clnlfypt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csfjsfaf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbictib.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2qcveaaww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xytrwmjd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2edfxdhue.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dbllgzju.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2oclxnavp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bouwrnbw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzeaozs.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qgphtrgj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsznmms.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjzhco.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhvumxw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvydyvl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqkwicx.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlndypt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2srxykdnw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2eequkson.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fafypzjf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjiejlt.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgardbo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozehydkb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2sevoggvu.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdbrhae.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuzddve.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2psiaprkx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtlqndf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kohgedrq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2muahebbc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khkbsfnz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhonucsq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2slyxzguf.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmkhyuo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lypntltk.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2myfoqgvd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2firqigfj.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2htdzrgfx.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwppzzw.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkrcovo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2menxaitl.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bckleogd.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvubbats.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jksfmdoq.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzhyxyr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iusaznlm.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjceleo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsedafaq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2syslstbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxppyhyu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2menrvucz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oouizldc.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dotyftbe.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbhedsd.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvkhecn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2eygmcrgz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2jygpxwrf.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcnrnnl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbyjrvj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sglbpwlt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2amvhklaz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmnrfns.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rgabdxfn.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nprqewyj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2spjrgawb.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaaoytu.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyigfhk.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2oolhcwxj.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxftobg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwqhzla.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2itswkfdt.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2secxtmoh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2whpmmgoj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cndqtplm.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqsgznk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvygxigy.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2keywppbw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbbnyfs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsnjsrm.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfjwpsx.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2heaiakxk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwthqelt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpzaxur.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fpitihff.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2igjzfgxk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvuajhd.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwumtmhl.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2cbckrbhm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2finbgmez.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrmzfqv.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuonfem.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhsmhhb.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ingnwiwx.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukilkyks.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvokifag.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2njxveqoj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orflsbmc.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjaayaq.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtzxiom.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwflgd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhbgudx.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxegffd.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2csdiqolz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsywtopj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2orgflaqa.html


<!-- 参考信息 -->