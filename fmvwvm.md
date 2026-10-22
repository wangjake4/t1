代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2glnrbuiu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kawxjpyb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjinolq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqyiozt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmpnlnj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lirizijx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2utmamyyd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxalzyl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpidraq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwizojd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzuuicz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgrlpwx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrybjxc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzujgrn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ggngmdzp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhibiso.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wesyvqrq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrvnvtj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2earxgrpc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxezulhd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2joibgywb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqxunct.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2frobqbvr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcrqmtt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vzubqrmy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2utjmlcny.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxeuqlp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuskbhg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyitro.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbblrvn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rfalivln.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpowdqna.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxxsfup.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxntaps.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2isimdjuj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2umunnlpl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sksckvuj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2anfodxpo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpcivul.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkamgeq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvdnhgs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwswbrv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsphmsqa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwijknzw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zanbrvav.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2suilmtqb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2orzyxjau.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cesxzvnx.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeuxfxr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2njosnhuv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jzipbyyk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2devvmthj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kvonqiuz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dinahvyk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpumsgz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vylpbdwr.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgnlygb.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbyqlrh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdbhlfq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmvhbpj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgjehuq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qoefcmjl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfbplye.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjukkjt.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lpeskggo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgwjncq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gafzediq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrecgqq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxbifzf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2agavojbj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ljykbupw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoznxffn.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dtouridl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpswgcf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvkelxy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuammjzm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpkemgq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mehechyy.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ftctsyfh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyebvgqa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oeldaimw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dykdcgqm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cntgratw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzwyzkw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxykarc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvalqwh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2yodocmbn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaasbauo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbjthqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2izuwzngg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqakzxv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2sajndslc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wvupumge.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwcgssy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2babcejmo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhluvvay.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxsednc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2coiditfm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lfztjtsg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpjhrxy.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvrcivd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2axmduvoc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rytutalf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zggcmhqd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iibjoywu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2klftnxvm.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2inkoassv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkjvtro.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnfescc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtimydv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjgyuci.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2eforbxjn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqwarqy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wechhntq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbbnfdt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zskpzvxr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dynqmgoq.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcxxcem.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnkmhmr.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnwswyp.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hguossmz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjxiqiv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2thduwfrc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgfgroh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nioodctm.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2glucnisu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqsrcrs.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2icgarsoq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2izqjsfkz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2efqnzunp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lwakswnw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbxfhvr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gifojswq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzffppc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wywwhswi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2itpppdlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xygjrnqu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mgazlfps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqtchgk.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjfvzeh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2obhswfiy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wqztgsxd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ajklbwbm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vslysgle.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfbfsni.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2foniwktb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iogdhzeh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vyipoyhq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ermvxabm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2squvhbyb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxgmmhp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2yabpphiq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kxymfcgi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2odapzaxi.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbkkpor.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrlfyza.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrntbeq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpxymii.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvxvhke.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fbivrtnm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xeumkozd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2atougjqz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2llcnmeve.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqmxnzr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnuyuly.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaoogps.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xvydmdbt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ergljerc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lieeozvi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmrvnsd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdlcfzo.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aldijdsj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnzjffo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qcabrkrq.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhfvnuf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyhklud.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqqjmtx.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwmzziv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkbufuk.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lbanmltd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbznhdk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szjacrca.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwelvta.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wppnisbm.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zowccbkm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvclndj.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2csclujpy.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2geaarbnt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hntdaxop.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2mynetwbp.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yludupnx.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjpdzth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhohakc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaabsqp.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjaeobe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxafcrmp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2cormaecu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2yuilsndl.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2amqzgnxm.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwptztz.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfhkcuq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2feknoupo.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdfomju.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyalcuo.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkjnmpt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qhptboxz.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2hoapkxty.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uotnycre.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2yymqzcfa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnrvlbb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqshjta.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaebbff.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbgvjfx.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjixwlh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pijkbpsj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzqnwmy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hbudcpjm.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nddszguh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rzojwxyg.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhtzrcd.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqoljqv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2umnjximi.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlehhfdx.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsiackc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgfkvsg.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhziwdtw.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2njqooqyr.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnqmlue.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkdntcz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrvylxh.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrtcpib.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwetlunp.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkwzgbl.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spjarrof.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prhalhgg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jajiuwgi.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tydnoymv.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urokejbg.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpvkbar.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqutjclf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjnvruz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwtksrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsxydea.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxtjnzp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqvngjf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuecoim.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qohzwaep.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2vriqhfsp.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2agisnntv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fovmhdgn.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgljlof.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xovrrdqu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhepyyr.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wsylvmrp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiicjvcv.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbggqdbh.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxqiebh.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdbcepc.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2geekhcna.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qasqgklw.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjothuob.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dszljngs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkcbdkc.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmvdoju.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2eobzqsty.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxwnknc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2feowohja.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wrajtxna.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mytmzbsj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pusnqwyf.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiempyh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2prmyhgux.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cclfbpuy.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2npfmqydw.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnqnzjz.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2uotiiumi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuqdbwl.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqreldjn.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ucipoqdd.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2epjcnilu.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wkceqrlb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfybhfiv.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zygllspt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkcfuuh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zljfpdxz.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaysmlb.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwixxgje.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jooyssou.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbhoytw.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpbmqyi.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ygioeqll.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyseill.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbeszvx.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2owtajajb.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2untynzny.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttbgoq.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzyzqhz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phhsfhbd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeylybi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmkcyun.html


<!-- 参考信息 -->