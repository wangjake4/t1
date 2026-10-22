代发 wailian999

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2stywchep.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2anvpwltt.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jkriujkg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeuvhih.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qzubtemh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fothybjd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2selwpahf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2deijbnkq.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfwoinn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zykggsyd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfordjd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfqrxrq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2enesrdji.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqaarme.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbevqan.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sifvodhk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dhudmnlo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxmvnz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2itxnzcsh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xddomgai.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjtttpo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrsukri.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2olkbewug.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqvsyiv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtxwebu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixonsvm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqpzbhi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjkbhwy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2olzszpit.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhnhnym.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkhpyou.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yswixawl.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iewiruvb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dsljatpy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvdntmt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nilfuztr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2fwsndyta.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdrijsw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuojnrm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqqdlnk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrreerh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpuwlxn.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2evinsejs.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeqmqtl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dzetbtfz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxvvroc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tlruxnnl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvdyleu.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2geolfitz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvtsieh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2stzhqbgf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbgtynm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2thinipkb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaviguf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bbamueoo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zclvymfm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2myntgcwx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rebotyga.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mqaaugzb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pplmvixl.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rglnkbtv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dubyjzbt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwwjqpe.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvjmnyw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcijtsu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnzzpjo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvjybsf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqacnqc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fhootdfo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2frfztmbe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzkfpds.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shfqflej.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2iksvmqyj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkgnybd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mfbfxjju.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2huacqmyv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbyhxuf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2khnaexia.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kojnkowr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2usandchz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2difgaiqy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2redlkddq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tixmbceu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygdtqxyf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qiejpsvs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzcxywk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmszifk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjntgg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvqbnmf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxvgmau.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jweylkbd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwpyblj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ombdxrwn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyyfqvy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqipmlts.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzacdnf.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2axbpovhb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2duxvcsrg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eawfyrcd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2lsugyxcg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2afgekxqp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpojbffy.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2iftsfecq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2firolkui.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vixtwzvt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaozxcj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yumscnyh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyrohil.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2usuyxowu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnirwkv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxwmxmu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szatxblm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjpcord.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrqtqin.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2uupoidfj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkjqvgz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2iduquxqw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvvqwbd.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2swtimvlv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsnyybe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cssopomn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2styndhin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slglqezc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejqpld.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2whjxyieo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlltqun.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kqymgoxi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnhbzky.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiymszx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcyuodg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgmusoy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uklzysad.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2llhvsumd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkyehma.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxcqndy.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyytexs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2blkmohfl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zufokaaw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2euhteaee.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2epopkfie.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kaofstdf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqjmbdz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnlhtcn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbijtdn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2gfumkscd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwypttk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gccfmjcb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2iedhocff.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2rukeehdn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjdamis.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2spvbtumr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgqhcco.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jhideoam.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmwphaz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nykxpsgp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lgewdkfc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hftzselz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwpkisz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpaombx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgmyvff.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wjsagojt.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sejemgyu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2efiusfjh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2elzyyaaz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2vigduvnz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fxylyhtv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gkodxdpr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiwmhbi.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2smsgknth.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmoijes.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrcepzk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bivqzoew.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgafova.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jozrsyin.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlbhkzn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmgkbzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtvqeec.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgyqpcf.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nughcljh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srjgpxrd.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2jdssuvlw.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pupzpkyd.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvrbggu.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rpowfygg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfakcsz.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sprubgqh.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2auycsjqt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyjsunw.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzwtdwz.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tywohxzl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jfumernq.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2xugwpfqf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbknfzn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2snawzhrn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfivxjn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeiwgnw.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2djmqwbjd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhncxxpx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2nuygyjrr.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcrfvas.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tapnnufy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyiutvh.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vurfqxyx.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2daehkpuh.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxepkdnf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2goeaandn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqigajpk.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfuvqbw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iozdozex.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhgknpf.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djoqqbjy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrztnzg.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2datcqxoy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnhfifp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pojpgilu.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rycdiovd.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzshjwcr.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2canziylh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wialqayt.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbamgzpg.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tndnaqll.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urjxnyve.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcfjqwc.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2puftdkwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkjxqqr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjwsvof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyzrvfn.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zilixbhc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfytmqc.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gmibsnwx.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqythjtu.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhbjsez.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqonpdw.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2tesuogvx.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfepqmp.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvxjwky.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgjcpyz.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeqrgzk.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ungozncw.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqvmtyzm.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrqnmfm.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrqkrevy.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2plhvqdjb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhsjfvd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzjmeox.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2reaiktye.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2uenyimbx.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2enhqoxsw.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgnpjau.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnctpvb.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbeoevfu.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wnttbqey.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzrqiyj.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxborady.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2evpeptbv.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnlrxgr.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jahbxlza.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkaqppi.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxiruad.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiszjzo.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywshbbim.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtonoob.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ooffqlzw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2rigroyds.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gteorinr.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvguwrf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xogzwfuq.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwezpdff.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmafldav.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ainjalvn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpbrlcw.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lqffyerk.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhjjvam.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgdehit.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmofavlx.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbgrruu.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ninebnqg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2emazlmhl.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdbrqhs.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2kltjlwcd.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjukanvz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wppczotr.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywqykjv.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhrpsnr.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aufjokph.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rldfivhn.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnznnhz.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcarifse.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2eglkhbse.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnojdkzu.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsoxebm.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nidcugpc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyucmvtu.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oszcvxxj.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhuhuai.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaxhdcm.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifzharq.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2ijufuehu.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwahaiia.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hchjkyym.html


<!-- 参考信息 -->