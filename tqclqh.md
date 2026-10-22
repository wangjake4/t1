代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blfrvvmt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2agrcuioz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2olcpsjax.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hojdllje.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2brjzfjyu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qzybgdyf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pljidsjp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tadbdahp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kosoxphn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdfhwup.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtkzjjr.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ducovgga.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqdovro.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzfvwea.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbhosxu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcipydwk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzlofas.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bklnvowd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2msqpzaon.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwnqxir.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nnspgzsi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnjkhge.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pxogkiqu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgpnlju.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2djgwsypu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubujguaf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2oepwcxtg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsclbjm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2geqwnfth.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yancwzaa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvpqeln.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfihxml.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgtyabh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2predmwqx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjxmlcz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2adgdelgp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tnysoizn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qleoxawa.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbwsenx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fspcmgnx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsbapra.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lukcrriv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2stwaiflh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtaqudu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2umxsldro.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnkpsbk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuhicue.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfqmfty.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oibqklnu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrmqwlx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2elspmtjm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrxejgm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jbyktgxt.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsbryuk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aclvxzyd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqldoie.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yosxgnjn.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsylkkv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jpofnokk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmafhfx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsjkixu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wgldpkkm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2frtuuvbp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pigksiio.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqifupm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2soregpmg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvtgqrb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqlvbih.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyilufv.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzfimnz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiqzusr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2szhxfcgl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ahawzxrq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2owbktqtq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jimiduko.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2przjfjad.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgefqpu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kizqjiry.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxajany.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwgexbe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vyevdcrz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjosxjrb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qetdwbta.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqibealw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uupiuetd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2moqbgvix.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2klozhrql.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2loidhpkc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhkngzs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2iouttpck.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2arldikbv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoiwpcp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaletwa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzuxsji.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkzfdcf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqutkvmt.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fybyfwtu.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjiobnq.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtcdcsl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzqmdar.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzcaste.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2amjknuhy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmpgjpi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgbawhs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzplfrk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjnflml.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fblctkhc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvtlgnb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ksalaqxa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hffjqwam.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vegxvano.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwocigcp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyoaweo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtveeicu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dfagcfbw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwnncna.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlpbpnx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsnjtxf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2asaeoywc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bsieomoh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiutfhg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeniglm.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhurwmyl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gspciofb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dynndfzo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2blbftwht.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nkieaijq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nptdkawd.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2emhzahvj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmkzqhx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2cchecunt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpteyyr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xruoocrw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvacofq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqhntxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msxsllmj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2znufwtkq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkluxsz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsjwury.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rslopeyt.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yvifuoyi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eherfgts.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2gfznqeiq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sfomzmbq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2szypfapu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2donltvtf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jchwjbtf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cmblyyde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucumqynt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbosevu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbozuggs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmlifxr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwamzco.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fclxyfth.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vjazfyiu.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sswzyyaw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqyslgc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoosuin.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpvqqiq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2psoisnqq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tddkaltj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vekruzit.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdbtvtx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkdmsbj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uhccwdug.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iawzuczh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzfdnzj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqjyybo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2viiqrtuw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnwrvjx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmirpyl.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gktaaulo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2atszwwbg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2whnovsse.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uanyoceb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2euysoilq.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2clhxtfqx.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpfpmjo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlpjuyg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2inmmelsu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ulybdegt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2oedefrjd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2esuiodfb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fvycqxdn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2srpigxhc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeagjmy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vgutprnz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2myfjwbsv.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2nhummdog.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzxrmho.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgedagm.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jacztvsm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvxupaa.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsqzwxp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rujzyskr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2llllpuya.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2owlvzwvn.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gaezrvvb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvdgkza.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugooaszd.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpoooqu.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2kewqvzrr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2sgifbrij.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2czeqxxcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vndxdqau.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtfghvk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtdziof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ityflsmb.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jkblucnp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbngfeo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2jeayotef.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hllfdzdy.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2sozhqhkh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2spzpusbq.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbgqxuw.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2unilovbe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2hntfdxfa.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2nmukkhnr.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpenuir.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyasmad.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2vughtsgp.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfoclrd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxsadux.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpmwtwc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmzoxsu.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2htudtskt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2angnxtps.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2iessdzgr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjjsgng.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdchefk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqxbnxv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yexnkwmq.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiduwls.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orjhcrai.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2orlrcluy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyxjwrb.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfqzyuv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qaszilwb.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoepoydm.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaipzrg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkivefq.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2punefhou.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuxzmlq.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uodegnpd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2billhsih.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgwuyxp.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvsrbli.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlflngr.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gsalaqvv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjaldkg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrwccqq.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbujdwzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrkvgec.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvtjwqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gihnrpcp.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkuyclg.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bymtotvo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aidqdeix.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsiapno.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2csltwoxt.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzfythw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnwhyiz.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ziewdlof.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfikwor.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwteniq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2smroqvug.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcejxgtg.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wctuioxq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfajwpf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2phtsowpy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkxlvkx.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2rrshtbik.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhvhsxc.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rgenmebq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2vduvdoqw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvetfofi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnedlxh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fceuduvu.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeciixo.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2sukvzoao.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuavyyj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkbgbet.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2guajcjov.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsksrjyb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxhoyku.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2towuffhu.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfnprwv.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2rntqiytq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2worjlbev.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkuzeid.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2lblkxsdx.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2psimwyry.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nsndvmkd.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhicjdcf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyazgiu.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjxxfjv.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ionyajld.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hxolazjh.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrrcinq.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsrwybf.html


<!-- 参考信息 -->