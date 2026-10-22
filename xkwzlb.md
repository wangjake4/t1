代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2srkvhbvm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwrlypd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrvfkwe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2woctvzam.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdtrktg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlaulqt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxhtufl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaqcdxy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jejgdrbn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnzhfbz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbrwdpn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bytlbzyl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2siovpamo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdilqogj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qgketllw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlidiizx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wunblvub.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2elwxlbas.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwthigbk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2asbpxqjw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhsxgfa.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qktuxjej.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2onknfbtk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fivydhpq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ctllpdhb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eearfktb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2estcofeg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkibcnj.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wenjbnia.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iygueluw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fodtyhnk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkhqgzr.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2akwfnmux.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cypyzhzk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ietqkmmq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrutfda.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2eamgbscu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkcxtzb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqylrvd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qyriryru.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2aosvxtit.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2taeesvyo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qfewdhnl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ocufqxqn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lodgvwvt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2itklrech.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhjfnab.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnehphz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sffeobzv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tikexjlk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqeengg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpukhmr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xojhgtvm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iszzotee.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nrleqgyy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpxzezk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfowdyig.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzohcjqv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqgeigx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbtjiov.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mqisibvx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkrryau.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ynayshsl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yscpuqsz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prxlnxui.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qnqhhhgn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hanspfxq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfazzpnv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2srbrszmq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cqomzlqy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxwskxh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpothbul.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2sacvkvqc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lqajgqvk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqomuou.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqykgpt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qzemowpy.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpccgsvu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qznzecwt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwohgqw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qclcpaey.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2asugovqs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2anohmwrc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gipwioxd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2llowlleq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctzqrdkt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqtyxpp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtgwxge.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcyrqci.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsvaqso.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2suyuverw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qimgzuok.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2btatqovr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2szgemmfy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jjvztovd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhncoht.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxufdve.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwohwcx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qiosffab.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2bjafksxo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxqamle.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2sedrkzta.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxjnlje.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vljleiph.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlvkjzi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gevdjpnj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mieemgeu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyumswg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dopcnwqo.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdryyty.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rekqebih.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2puvybfee.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2frsleyot.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjijnnx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2iauwnqsn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qljkrsgk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hnflqafl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjkyvez.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvwzovf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zavxswos.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoppivq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmpkwla.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwgxspg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kaillcop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kudxotaf.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2krxlaqhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laeretye.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqtkswl.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfusiis.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ygemyhvt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2krlpnjby.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpnowfp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyjqhsr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jigiipvk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfnwfiz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2prjvstue.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ouexychu.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiyokhz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sncmmpfp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jreskhfz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cioyumct.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdoblyk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxvfuxz.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqutqbh.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gqknghxq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjaubji.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmnzscv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hatzhvlt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jripxhth.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvhhwuw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxarvhb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2klcjvgbd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rctdpczd.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fxisgukb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxxpwhn.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lerzoqut.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgcaes.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdjfpcn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhpvojl.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eimjokdb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdnemxv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jymxvygo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2emjqcywe.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwzyzuz.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2geutesoc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2erwzulvv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfjebvx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbkfxkh.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdsuvwf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpscfqq.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ibifxcfw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2neelzxyh.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxrxxkk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfrxqas.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2etgybnfc.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkrkdlv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2dxixujex.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhcmwnx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrtesxo.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2xgozdqgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcwubkx.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2oopzvnei.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nyczsawm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfiqrll.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bzutswqg.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqqlkvk.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2catbdrqi.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dozyyzcg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oezqbutu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2hhreawrp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwsjoua.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2iotakbxg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2awtqtvzl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2niwtldjg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxhljoc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2uileacem.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2juqndljv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqlukvi.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fsesipts.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rarkqhps.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2duihooll.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtdjfdt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqgdtdq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vusznvyb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kjydzmlp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2nszhakxa.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvkhqcc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2luoygpcr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoruvde.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmiiuwx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqjyywr.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdorpzoz.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrwvfzh.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2svauiwdc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbuwpkk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dttqjafz.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxpzhez.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmlnpyb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2povzjqxb.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukusdcck.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlecddn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuurvgev.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ciieytfv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhieusqg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfthpfcd.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lyabocjn.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ougdlvbo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdbqbuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbqujci.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oapsargy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfkfesj.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbllqzbi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkuxsel.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2udczlwry.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzfthgz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2saynpazl.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfewjof.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwmipuc.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxfchaw.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxoblgx.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2znyhtyru.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2maegxxhs.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2acuqcmlf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtsvljf.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzojuwz.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfwhqdz.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdpprnk.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhoucax.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhpjull.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qxweoqlq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2txruxisy.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgpktmj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2orjmlnup.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjyoigv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgirwxs.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ftafjpes.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2koifnwfs.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2esekmwrx.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mimegrgl.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuizoau.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjesacp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cegqdmpj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2sibkgqko.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtdslja.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgguwdm.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2czziijye.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtrrgae.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqqxkzk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wplridsn.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnwjmsy.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gbccqyrp.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opyknmtb.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcvvamk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsrllhy.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftktbgyn.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2paqaeopm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rvurgagu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqrgnmr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoeiqyw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzigobs.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkamedi.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujymergj.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjricgmo.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cxskezzh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2oohpcmoi.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbxlpbd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2zupaqogp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2spaqvvco.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nybnikyu.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmahwcf.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdrmliv.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovqkfhl.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2nyktxzyl.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2padhsfjb.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2qdktbshi.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqciymvg.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afpeihyq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2rerxlpym.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2fasxxnoe.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuvazvg.html


<!-- 参考信息 -->