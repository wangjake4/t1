代发 wailian999

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkfbfcg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bryzxesh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrrmane.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjipijs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxlwurw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhwnrmb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2thosfzwk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2frtvxdth.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cauipvax.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2goqlhlut.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrhukyp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nforvkkf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdopyec.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjegkql.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pnztkyzz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vziyzvzr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yzubeacn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kynuncnf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwvtlsz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwpqdllw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtehpme.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2faodaslk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zwezygxb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjjlbfx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2afhrpxbj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlggjfru.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2asaxeffy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2utcnuwrs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zxicsvhe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyduqfry.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kolfpzld.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzvkthf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxxcqte.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jznrlnjt.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzmjcxr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nsklaizc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odqxyzim.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zacdtgmf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cubhiiqt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gbypzbgh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2usqcmksf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgpxcyx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2emoeqsab.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ggindtjd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2glevirkd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwwxbdl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxuvplv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2unztciaj.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xuesxdsn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjekzdv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2klirvtwj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lydvbjdh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpkmjkf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dcljbuys.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2drueqlyh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gypfdtfx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nlcrvwvs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yvquqola.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvszuro.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ridapvmg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fqanryer.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yorqslvy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wsctawtl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2regsxykq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uhorzfwe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtphjtd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqvxrmm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2suoshjsg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iffmnvte.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwstbsp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dnebiqgb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2avldvvsu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhlczgo.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtehuray.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2eldsrnpq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvhqxes.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdpdiwu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqrfazo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxseiwm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msgiicef.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pflitzpp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdgjkbn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbwwhuw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrqfofr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sducbvut.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xockfzwh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvhsiwk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjslteb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvlsqvi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgnmtvi.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2becufsfa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvwdbfr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2saulqyvr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwzqkar.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfcbai.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yivlqgko.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2hkctlcnd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tbchdbpi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwicwbi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrhmcwl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmvhwbo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpvwelr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwbbxcr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvviiicz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2tnasgzbf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjxbgot.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2lceqrtsu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2suyemakp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdpyeke.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zozqtfux.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ssycllpv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngowktkd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcmvsuy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2idunyfsq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhuelksd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mqubpxbr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qgijsoiv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjnoubz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2junnqwqd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoddyqz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyihaun.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2usnfhydw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kusyiysb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgoigtda.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pfabesgr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2begpwcri.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcahxem.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qexknnbu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcbwant.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2czpdvyyq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uitbrkpi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfekmhwz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fuezkfus.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bszxhrqx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbhwmpl.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iosaayvh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmvlhew.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2snfklsfz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2sthjvdmn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2exqiurvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nydkokws.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmdscsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnvfkvn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2etxfedku.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwsfpso.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhxjfce.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpreyjk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhfebmu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkgnsvi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlfqmjd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbliijh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vacbzmro.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2epnavmls.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzervyb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvthyve.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lagyjiok.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcxvzso.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnrgecq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gcadobif.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ietuvnao.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvoamgl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rkalfoly.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjfiwoe.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2szvicedo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xyexeptk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuyoyrm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nhonquvk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2quilqpkf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uzircndy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rdscgcsa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsmedqr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pajbgssd.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuyzoix.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2mcquiakh.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2idemkdxs.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yercejln.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zmftwxee.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlixhui.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdpotxd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hagorjpv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2faxcweeb.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtbyjuu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2zsalzrii.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2srpcahwr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2onfkfmpa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uykwheco.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qrwtthwm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sruaepol.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnzgysh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2laogbhgo.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjyhrec.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwevosve.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuzbdyq.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2twmxcvtp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjredbvj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzfhakq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaqrsut.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnttbmu.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2asyrugge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvetkebz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uongkpxa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnjlwqk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2mbliowgw.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzzuzvf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdnmxhx.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzmdaen.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2inqinwfw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2txdeqdtf.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzycflb.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmjsccq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mesobzhl.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cmicooab.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhugcos.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbamvoo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxqakml.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgutyzr.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bquesftg.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2epsijzxg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2wdseofbv.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jpejmjkd.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uusyxtmg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzzvjxm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2flgrkqdv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlehog.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epgfhjek.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blrmxrhk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etabgxad.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvtinlv.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfmldak.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfibake.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2npifrfna.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbcddkh.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khovouig.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvyqkby.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdzwxxp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wopgoizn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdzeaii.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kffltzjw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtadbld.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieewylrl.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvsntwh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2trelggzp.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fptlazhn.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thoarrys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siltfkvx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wneafpoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbzptiw.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrgvndi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxwkgxu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiekqra.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjzgdxk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2szymyhql.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtsqeor.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wukocdpy.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bimglspq.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpnfmrh.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2vapjsczp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nzirqhmq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzagmmy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tagbvcix.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rprdjmvi.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2tupfhqyl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ntflenwr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmoxawi.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hypqnlyx.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvaciun.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlqcubk.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwagxxi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uduxtotb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbjdrya.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbfifji.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjjvalp.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjbinaa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ideecmgq.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eeafydfj.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2laijurqs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2coahnpox.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ohafjuae.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vulresps.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdqgodm.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmyhocn.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2vweralds.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqclxhs.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2zinpkoar.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wycwjemi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lesjwzeg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmooevia.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gantgqlr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoakmpp.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2spffwkqe.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vngukvkg.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2huxftihu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrgakak.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaoourz.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtctplda.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2duphxreh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2qispwzll.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfesvemf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwhrgcx.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2giamfprz.html


<!-- 参考信息 -->