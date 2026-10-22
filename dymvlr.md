代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhcushz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2znyquvmr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqscxat.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtubjgwz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpipjgjd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2biqdcabj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpwekdk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bawlmoed.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbttkge.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjukabe.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2badcehld.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nzusmgdm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvmcqkt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnpuoql.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdzjnkg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2iesokaej.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eilbqayn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtajckj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2shtxxfkb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xclcaxae.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzkcqeg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckquzqyl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fekxwryx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzxxthd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmhzmnx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2izmtnszs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2evkggvpt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2klniyzal.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpvrkuf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2iamkxowu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvmpyie.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhehofy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmvjjug.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqdqts.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dplhsqxc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2elsfzhfy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlaicgr.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpqqthl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzjglrp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2plguhnji.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ourlkfit.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjrqmzs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwjwqxo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyvbkpc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2treqpkzu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2elvpdihj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2blqdqnuy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2apqnsueg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vckzvhew.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmbmqnf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwubrgv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yddthujp.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeblwbf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnysxbl.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnsmzxj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhhqdej.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkqlpgd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoqvdlz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uioiryzv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoendyp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eztutttk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2szxzjzuh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2luongnqv.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjyjlst.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvarcd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgzdulq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyknbal.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjvvfeq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkzfkod.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmdrons.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcosyuy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgrpwup.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2alikneiu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mgddhxsj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eihsxcwa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxcugby.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ascrnazb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsmdjfx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fossesqy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwxmoiw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2uqefpcnw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xolonsio.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvpwxw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaeyeod.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ioachpsj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkdhfqf.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbiyczq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjvoxsr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbvnqqk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrulhzpy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2nsukbffq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbptdly.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nehxhuqm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfccedf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dyktapxy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxngrhi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhfppmc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwbuolw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxuccabp.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgqhjle.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2stswajfx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpvjlpq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwamdjm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwrqdro.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbtdndg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxotjtl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkeknut.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxllwde.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2khkzigbg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxllonx.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xbadlfto.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwtlcmq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjwyjie.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bumnplej.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxdymgq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjtdgyr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2eliuiiqp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2iececjoq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2skpctcmw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qunkrioc.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ztymvrbq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2suqlyflh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtmkibu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hlummzns.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jeasmnrg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tejfcxrt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmoqrznx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pysbakxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yitxecdr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuyygkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnpgpqt.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2klntqjaa.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qjolpatf.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gnofsdxj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiwtdsc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xobfodux.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgyaezu.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzgcqyz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zkveltgm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqpjjww.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2idbpayrs.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkdgvyb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlgqbzc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhtdgnt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxetzzz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdknghb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xjoejqnd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvddzld.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyfpxqq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrjhonq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cphsalvw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nomrvroe.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lglalbud.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoxkudb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwsssdn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hftjllri.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ccegurtv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2amiyboag.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nslwotkh.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ofazepsi.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qowhmmtd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbiowsp.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyqufky.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwxtppu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2wepuhfsc.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vchqazcx.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkdeshl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwktlwb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzxfysc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfdfpln.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbwetrb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqqeylp.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2piuhzjwk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjscwuh.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkypbxo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrtpggv.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ryahyfju.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qszzhigh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2jitocqgf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2jydyomnp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2kshvqjif.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxvxqkr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkglsxh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2lipbsrpc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rififehp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpwsuvd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2sedapfwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmscywk.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfzhppr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpcrott.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2esfhazjp.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2csuxtzwi.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdjvcfj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2fagsoifj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcwrtu.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2uyezmekd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2nklfiyll.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpgvtyi.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2radqdmyn.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbcuyiv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2qizkpybw.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgdnwoe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkgwexa.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tblfjiib.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2wsslpvhv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2crsmqsjh.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2drvmsqit.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnrhyaw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2owkndtqn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2younxhlp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrcczky.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mprmcele.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vznucnmc.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcurynm.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqufovh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtqtpfr.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2axkveafv.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzekswjo.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zapghisd.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxggyai.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2irtdpfiy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrueqps.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcasxkb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxqyvgb.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2toicayzc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyrndsy.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udgbrwad.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jaswchaw.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzyczcbx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpodbmif.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzbkqzi.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtcmeyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opjyaslt.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szvbzrln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wolnhaal.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwulzzt.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2shgmdrpn.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2slavwktd.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyywljwf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2voxhjchr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwziyxri.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2kinfdtus.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmnwhox.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fmffxiub.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2acsxplyl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sjewoufv.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjulvicf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqsbhfq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdznfopr.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsimnxd.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sgknrhfo.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzadktm.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2anctktim.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjurwnh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wokdkljf.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgxzyqm.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2inuuhboe.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhcdlgn.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzlaovn.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rjakyftb.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2magilkpq.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwayrja.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrdqpht.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvylpkue.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrrjfhu.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2adtsalkv.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmhpkpi.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqqrjyq.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrirvjz.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeaujhw.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2saappvqq.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2drfyvwpx.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmrrildg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpagriw.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2elwoxsra.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfgtczq.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmadfxvk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwuuldn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbtlkry.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2szzwnthk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwxkhww.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2fidlcghy.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2roxudxnj.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdceucph.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2detpftlb.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2djwxacvr.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmwuqqq.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjionwd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2whemkdsn.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mceposfl.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgkzdph.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2odszkzbb.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zomaitwf.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchbwcbu.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsydkqpv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgiicnzu.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpnxpxh.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvlyyl.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbslxyb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxdwylc.html


<!-- 参考信息 -->