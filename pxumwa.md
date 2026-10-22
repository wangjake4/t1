代发 wailian999

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2igzfdfvc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zzguufel.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vpblmvxd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rychlfkt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaceuwg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxftapw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ytttebka.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnvitwb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvkddph.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2usyvolxc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mehikhqz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lslqdgql.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfazqdd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsvsimt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sauqtdtn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdognzfh.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vabpkoql.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqimubha.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeoazfa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqrfdcm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2onberpkd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjquzud.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpvhvkl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdkbozl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sllnanmx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwxpcir.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnjdvds.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qonyoaoh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dqymylsz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdimwwa.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjdepgg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nynzpsum.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdhiwbu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2asayytjl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxlgged.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ooazwakw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ardjgfml.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjudoqq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqnnnij.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncifujzf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2cockjklq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtuijgh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2niqdalfj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2spczizcu.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2yhelvkux.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yclvhnoo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2apbiwthw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vwunyzjh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuxxpxh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpgevxu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnoxtaf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2koqusjan.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwbbhcr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zkndqeps.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxeuiwq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kovtjyhc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bmacojhl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ittbaxuu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2owyobmke.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2esyfxfjd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjgvtrw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2exbktzkn.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgapoef.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yckrfgsp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2csftonwc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwzpqo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfhinwd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnissfbc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2avocqmiu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxjwcvg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wbihmbfu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2errfrryt.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xroonxsa.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vputdqdp.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzrqemj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcyweld.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlozxmxm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjuskdp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfnadyj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjnbvqx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2opbncjfb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2veebbwph.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2znukznsd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2actbxkpr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pokqpmne.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2axhlsift.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwgjgpz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvonifu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2djccllqh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbixrihg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yobyuizf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqpzyll.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ueizpcmk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2nubscmrj.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzcsimf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsuowyt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjyuedj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfudype.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuukcbl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hheqrjlq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2trfzyzih.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkhvhza.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvvkvrd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mykgyhyy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2esovwnaw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvndrsrx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2wypehjuo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjhltaq.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2roclotlw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhnqofv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlgussx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxagllf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtarvpu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2edwuhjce.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mipjqjsi.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yupmihec.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dlufwmnh.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbfzjpl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfbwgrp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2siqfnhdp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bknpeiof.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2siijsako.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuuilxi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jerkaovn.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2evzsqltb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2owfdmstk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ilobvalz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2vivdaqjt.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvvwcpm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtyanrl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2juuqplio.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjrhimj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rymgubet.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ckiqbxrv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apnrpkux.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zonjqfvt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2htipeidw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqwymvk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2skofvgvq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkaebul.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtxyxsm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2whlqcdat.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmvasec.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oupfeolx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwvbfgq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bktixhdm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzccolo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2aloazmjg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiddcww.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ociycomh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkadrsb.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lataaxjx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbvczkl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeaehsg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqvfuii.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gpanxqad.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwimhvg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeinjzk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ixegsozc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qizrimyc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2etppfdah.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcajvds.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjlycmc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xadeyiif.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jksatspf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwienhz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgadmaw.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ljygnzri.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2izjswydi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfcpjjl.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vmeejaeg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wchbgeme.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeyamtx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhnxwhu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xzubjkfj.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aklcwcry.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2icczupol.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoaonyk.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvqrqur.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrapryy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2eppngbxi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2trzdyapu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxlsart.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rziekfdg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2vupcpomv.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwbewkc.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2kaajjyrq.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hulkbogv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlarpzdo.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2uerqnnjf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2euvmudmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyejazv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwktynv.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvrjxbj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrrzlvc.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2aqohdasr.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2msvgyukb.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2oghjfdjb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mogqzxue.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmmvjgh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vkenyizt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlhmmqa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfymlcb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2urqaiakq.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2hvftdeyd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmmpjdv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2pretkzqk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdrdbde.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrzfelz.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2plutfuqf.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiuncxv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2njixavjx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2avhmrdmc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2docuuvaj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2alwwoftf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzswmrca.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxuzmgj.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxopwpw.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkgyhps.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acplsphj.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyckrhf.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjycxlg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmytgpq.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfncljtl.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2netwfsjy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2peajshuq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxomzzk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaiceab.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wewsblvn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkgxhhv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2itoqinuu.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wraarkgh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2obnzefmg.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nburoked.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoydugt.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esqqowwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbprwjp.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2enrfsuoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thgsmvav.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pwawnedb.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2toajvamo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2abwfmgkg.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2auqbqbrw.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdjqnil.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtajykz.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwztukh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2muanlltm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2imrmhsos.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzpegow.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2doewzxti.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqhilbf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkniqmi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsleamkm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynodfahp.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdmzwsk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyqkwrs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2slcvhqyu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhbryst.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vqupxcpq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcudtld.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpntpdhp.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxhrvwk.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykshfamk.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjsiaag.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvjmvup.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhmrktu.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rclkwnoq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2scypcdox.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrsdrte.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcfkibx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbnhunx.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrbcgxy.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsylzzz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnyvfla.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqjlyvq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2mywihwpb.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2reyykgpx.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwemuiu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkmosi.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxjdczq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgaajna.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylekpqax.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdfgyap.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vevrtfhp.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gxidiuyr.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdliynka.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsucunf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdkovmv.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxavzov.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnwvenl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2myhkltdb.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvekfef.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzqvadd.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnxkvss.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqsodep.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhvtwqa.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdxediv.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqtgxjo.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiclomln.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvknjtyw.html


<!-- 参考信息 -->