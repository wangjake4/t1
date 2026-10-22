代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiftvtj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzbjupm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uawlvxuy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdobvhvf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vakrpjuk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uantoekc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bhekyswz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbbirlg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyzyegp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwsgufhf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pysryuna.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2brxbysyo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaivaje.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvffqvgw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtxoeva.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2glbhthkl.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2unbwgaxj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuacumi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cfywweja.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbagxad.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sumsbapw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cedwfteo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2taeigkph.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqgnrze.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhpfgvz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcxxezj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hstbjnpo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2fauqnyhk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdwkslk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xshcxyxa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkktxef.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jehecvsf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwehcot.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2egjcmusq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fiszabxv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgiplhde.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwjdjhb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdxwtsp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqxjfxg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ybucmqym.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuoyywu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2etvuawmv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnvoigc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2favgtaez.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2izzrdtti.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrfufhv.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tngigphw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnkdike.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rwohqmgt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2texgzsjg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcphwnc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyrwepe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tbyqwamp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbbzsqy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jccmbeli.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aelojinc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuyuyeb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2sulobvjb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2empiuqsh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2whudxmxj.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dyamslyp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqjfywh.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnnceqo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxklhyln.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fykvqfxp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2utqmgmfi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2onkxkgra.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2suoimftj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2czskhfya.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqytzow.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akfbrygm.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypienhmy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2irzrhnyz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqygqpy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zngtwuhl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asapaqgs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2txqqdwtx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdmxtdj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2cyigtrof.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfaeant.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2namebbwy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2porvrcgq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgaletx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylssymjx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2btmofoir.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2eiomxlcp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wbykvnhl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlpbjjd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2herfiamj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwjqcwi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2raqezjet.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2czdclakb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnrnqwb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gzedqdbl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qswhcnyi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2acwmihcd.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2sodfutif.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jishqiam.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfowtpja.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2axjswrxt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsagadt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iufjdndw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jueavsog.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wempdegq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kpetiafz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nmafwhuw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2uoczsmwl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyjjzad.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ivoqfoxz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgytnpbh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xagcwilz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2plsgwgvy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gehnojqe.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmozadyo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlxutlv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqxnjhz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrekzpq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mrprrmim.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pumssqmb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrdvfhg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdpabgb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ywehjwko.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2eucrkgft.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2egxpfulp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oatfwmcr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zcznxcop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npvqrfds.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeqdfwz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fghqcepa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2figpkeln.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2geafutuv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rahrlpgc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2clnwxvtj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jymipkuf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvhfmrc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvhregb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2habbvhkf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvnzeiu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2bvffizqi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kovskkdu.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbdtprb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2shayejou.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nleucykh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvzizex.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2isyduzhv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeqmkyj.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2klfeatua.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtusylt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiabrup.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcotqnu.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrmznes.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2derhtmtg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2azgcjxsa.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2srnylucd.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpoxdcc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvemgcu.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2shqlyayk.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfnhbfe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2xkolwzut.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cypitavb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zhftjmtz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2enaavgll.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmnirfv.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrynmbz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2alfbjulm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2plmkxiss.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlxcqrs.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkughnv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpnhkhj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrjtamr.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ebezzgge.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gldhjmkc.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhfdnjc.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2apqmzcci.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2nllpeoya.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bvptlevu.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlpmzfe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2sndxjchx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2jxindjrj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rdylszgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgwtqyz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqrlhpy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2mszqwsye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imepflcy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxknyec.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2dedqwfgz.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyzprwe.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkaocyk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqefugl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyqkgzt.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ppetikuy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgaricw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fchkrilv.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2svomhqrl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzhlqfk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2oplvqmck.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2feguevvh.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvngrbu.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpmzgio.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvhgiwx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkatnjv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2kidelheb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdqxceg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2lncnhzuk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2spvtlkdp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqtfvib.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2oaptobyz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoasvpm.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdbnvwe.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xueuklac.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrvtrrn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdchvlct.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxvjcwm.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjeyyaxd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2remtxlyp.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrhwbfc.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyowuox.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyhbqxd.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfqwxgn.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcapmvi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgixpvsw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkapocq.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urqidlbg.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpmbyky.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsdyqba.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xuewahcs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzcqjat.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sblaggzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyxegee.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dupxoyid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luqyrzyx.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxmbvyj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jujrwrbu.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbyesqz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzoprqr.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2laraqmda.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvsmpnp.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnlwtqc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnthrdqe.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2reweihpk.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkksdyb.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nnethrux.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kayqxrvx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtmjpxr.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wifmllrp.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeumylpf.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvwrmrq.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2drzudfoq.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2pyysktrw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xwacilfs.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2eeevxhkq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfukvos.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2leasbtui.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgcqems.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2edmrulfj.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2qtejxqdn.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbcejey.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyhgysk.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxojzhl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrdixol.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwwilsg.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrrknxt.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2yptjgrtg.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2durtagod.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2apgujboi.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2tchvkubo.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvltzss.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtanguc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxckzkz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzersevg.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkplifju.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjucviaw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwtsqiu.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhwzdsp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cprcfbes.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2laywrbdb.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kobgqgfb.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvwfixg.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrxpjfq.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2psewrghh.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2smauubms.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpdcqdz.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksewapwg.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsqnygj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsiuhjlj.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcpvhgh.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rocljpqr.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sygpytlk.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkurbbct.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbtadyc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2llcttwxc.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eflphgfk.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2scavfgru.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwozlgx.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2nszmneke.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmabdnn.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2edqbxzjh.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcijrjvb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhepgcfp.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtglikgh.html


<!-- 参考信息 -->