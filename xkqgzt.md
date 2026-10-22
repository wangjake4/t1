代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hilegsig.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwimaihs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2basrskhv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxagbjp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cfejvzov.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2teuklyjs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qxiawxln.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ormigytz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmqxypn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttswfdzo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ischjimx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdxmltn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2emsaesmn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghukcrug.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uthoffno.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgcpmnb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mfshmltw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqdtnyn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fmemlxfx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vopleulm.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjvjcaz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bokapaek.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gsopjdlu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqvurlh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2czkfqogp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzkcjzw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhashqd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxqwqvb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2peuxuvaa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wohsnuzr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtdphak.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xthengfi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wklhpbhc.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmfyyan.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxybsqc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdxxzzg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxdxgfy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2akqedtvf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2riucamvu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxxsezn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mymxpsek.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyrwkwk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxdpxwv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiolyqe.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2daxtzfer.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwkxmyz.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2emuqyugd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mksoxwqo.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvrzdyi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2stggrehd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqpgecy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ybagscla.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhuxvfp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2layfhlpr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgvanlo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gacxpqwv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rlggwcoa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2nydxlhjv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvnnwxv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2talwwuiz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsxzxwr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaqxewk.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hyomodpa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvcahnc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtufgcz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gsczdzmm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2degdeosc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgkcfol.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlzyonm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2goxmqukb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkhyrqy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2eudvmolc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxfvurx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bcglmorv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkxzdbs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2agipizir.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzlkhpk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vdafdbid.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrxkltf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwnaluq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwcuicu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmmkkuz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nncxusjl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcrjfld.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjrqgho.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvqpdmo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrziiqo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2buvhurgq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2knptilrb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvalhvhc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iepazcrj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhmmqcp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cidehpkh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ostvivcg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2czahhvcf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pwojjruw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2opdgcezr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcmufkh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqedszd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2urubgxvx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaejrsr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulonghjs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjuyrjz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2irzhudwx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2axzsforo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qulyrupd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsfkfzn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qegrqjme.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2orkddkoi.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2znkuogzt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dskhnwlb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiozylek.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmkmqyu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbztmak.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sabzjcfg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2flchgcvo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkfgrki.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pehbjsol.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2sltcnxes.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwnsdpr.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2aoweprua.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyjibyo.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnwepsy.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrsxcdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdtegby.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tizbhkld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvisruno.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2imqnrqws.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlpukrz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnpxhah.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rklwnych.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ioasgses.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zttbdzjd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2avcxwqni.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vamzxhza.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2apqttcyr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2omxryjhq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwnltdk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrlejri.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpemnxr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xakabpdq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgvgytj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgkqjno.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2regkoivm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wczllfzm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kpivaund.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bguxnvij.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxvsehh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxrueke.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dffxpvfm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vpptjeor.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qziiuvbw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2twvfeygm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmzizrj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rvebhxnc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dblionbh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlmixia.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2psthdjir.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rzffxkfb.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpvpfca.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2njsuhmkf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaarnyz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvfujlu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rarfbeej.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tubvimsa.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2swwqfmxd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbcayht.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnlmrgl.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwkzvgu.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrqcdzt.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uorjsfsb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtuvkod.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrrxete.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpawknz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlezamg.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcmxbmu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xrerphdk.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pgerkrah.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2perghgek.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjhlwec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlclcrv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sagparmk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sreiehkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvcckul.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2eioircet.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2eymyrwoj.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxjifnu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2stvemzhe.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmwbdzr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2dktnpfqs.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiipxsz.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ohltizov.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2yihbnarl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiktyec.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2piwusoel.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkktnkb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2acbvquco.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xvfljrqa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kenizxgb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2nnazwabw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2epmkeroa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwtsbpw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuwlacz.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mgshkgno.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxdflc.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgrdwrb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqnzxpp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iugyhjuv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2shzkdvcv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esxtfbqk.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osrfxzah.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osivosiq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwrwhjw.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsstiji.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxfdskb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqrdiej.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxgvvqp.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmwqvbs.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjaravc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyjnshy.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdenoyac.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urqbprsw.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrohquz.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwcelum.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwopxjh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prmqbbae.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yngcrvty.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iirybted.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfawwptg.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qinpkkmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmzqxju.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsypcbk.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2syroicgn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcmypvr.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nusacuwg.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2knwzepoz.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kossmytl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmplvqv.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsnfsgc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2wswkxcvi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsablkme.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvszdoj.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvvogwd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmplikj.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqfajjk.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpjqnce.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jygdwkyr.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2iupsgxkk.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaemuqi.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxnjkmv.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2kstqiszw.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzwfaod.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtwsdgb.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhtwvvy.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrmttpd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2afycpeyo.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2adbyhfai.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxznrrb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2seebtkzk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxahfrlg.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnezqke.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgpukjj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kmictbxt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2aehwxhdi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2okayaoar.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtwoeza.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2vmimzzey.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2xsumhiwj.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzudedj.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zahwttft.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoyawcq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyzcize.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgekpndr.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dclssdhr.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqpgbee.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cchtkmse.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eijpzjbb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqnczvq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fljzmvlm.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqapnezj.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlultfwm.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbldchf.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2djunbokc.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2dalksyjg.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wketqixr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvzrqyj.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyccqyi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkykwiv.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvikpmn.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvivbnsi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwouerg.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxclhnk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwbsgxl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyqtxui.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzsbtvp.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdlsdho.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bywlwxqv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmhngcu.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqfowho.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfrvocb.html


<!-- 参考信息 -->