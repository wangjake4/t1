代发 wailian999

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rwstvfzu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2teifuqds.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiudsng.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfntenz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxzmotk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2auvfnaas.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvfryww.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vupccdao.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2egjpiiwc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnvbkzj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hxapkhsa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnohvtq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xuafdpbx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurqwgk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhicvdy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqowdzp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuzyips.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2okjabgug.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fvehueep.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2emygptno.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2icxynnhq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbkmdfz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zhffdnyb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjjbkev.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iilxxgrs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kecypwqc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pyabkgyz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2drveiekn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzordxq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2riowasbk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2uccxdhqj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwyovpt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrmbprp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzdozgt.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkzwydb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jfodkihk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hitiydze.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrvmzuh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2envgpcep.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eunflvtj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmdvntu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhiyynf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjdmvnk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2knvpeakx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlqszx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtilrtn.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wxljaxul.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpzahnl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mokfwwxu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2oqippqzy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuiwakz.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2gizgjjij.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fesfkcmx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2upcvhqez.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zpidgxbx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2edvoyebs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fkybxfre.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2drbqkdsn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2azfadeql.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfxdhsx.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oghpdujy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzpxjzt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbrirzw.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwevgoex.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wwinwfaj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqzdnrl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2slzksksq.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyyecig.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2raifbitg.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wphtluhl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ooygnjnx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnnvhyl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zvigenxz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbfndqx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkbblva.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqcfkvj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxshlne.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlwkjsl.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2odniiisf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjpasqe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykucuiqe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2kusocopk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2aswtbjsx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2coeluokv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ghphcxbo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eniskctg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhgxlqe.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qahnimtf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lsejtivr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhudqzvz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpzodaq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmclkzk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cqismlzr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2haswndrc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwbdnug.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2farovels.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wsglilnk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kslerfdt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2frxlxqma.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtlwvyh.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkghnfw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeosryz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxnqjmp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dffcmllw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwuypkn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hyylmqoc.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqtpbdq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msofejzv.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2chxfpowp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnqfsln.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwklache.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaxfsdp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lzumawoe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dijnnulh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vbesvbrq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcuwrgj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsmwaoj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfyiqdc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqogkxbh.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsfjjfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiutzhic.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlgixtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzybjziz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ozknvmer.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rydsiqhq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjqamdr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgmffxl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njcjinzi.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhvfixc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfrymct.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2agvppskg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxwznru.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2elycuuxm.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgjfkic.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoaivkv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2qftmdehn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtxhtyd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rvakyctm.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqgxylw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vbahvtni.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhutnvn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dxonkmam.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ypotmhnp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2iujotykj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2vtowntpa.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iffdrjnv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2psaoewph.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ruklsbho.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2imapzoax.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2nlolsfvb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyrnaeu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsonfse.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2obhrilgw.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vpanljff.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqqviuz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsnwgyg.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2isnmwapt.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxnoigy.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhyxdkw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2awenghyl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpjkcfk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyoryjf.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2lefhpdek.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcqasor.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2oddeydka.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwhozol.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqxqobf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2njonmvdf.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zqckyubp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mmatkvee.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2plrvktpx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfbkjbf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfnhvoh.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ddowlfbx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcoeewy.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxemkno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjltnqbq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fejqoona.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqpwjeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lknttecz.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2amzryths.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxvkcod.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2eetszbal.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2weabzzbt.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgnzgmu.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtwbncn.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2snjqwxdt.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wttnodvh.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2flpnhrdn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2foglcdea.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2gadkrzmo.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ijenfcza.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyekrbu.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgshzzb.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnmcvlb.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcchtif.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2qfortpvk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2whatpmli.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2qnetupio.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtogymk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlahxoa.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvnctyt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrvckgo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcvsrpr.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2redwilqn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmrybrt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qogkucmw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsodtmp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjcgjcb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqzcjpv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hecskfqf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnfbons.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmwvvtc.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfbvjwb.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsaumia.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcamxlu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zngynwxx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwriwfiu.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wskqwehv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyrxkjo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tweityre.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztljpbzo.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpanjopu.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhctpasd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeffzwru.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vabdudqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcfkpfg.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2msnfhldv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2heaozuot.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueyzvhko.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdacnfz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2myebgwhg.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhubhek.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2izkxmnyi.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2osbilbkk.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmuohpg.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjajwjx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxbrkme.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbkenoi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyjvius.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbppwto.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgdqfsj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2umfzdjqu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzchaxd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2euoxhvik.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kfycjfwp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyqqhzi.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2raxesjoo.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2przcviqz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2actyaris.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmkvxnr.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbfczyc.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2phothlfh.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2msdjtimw.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzedzkq.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkhqitq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qofnvfte.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsfwqxj.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcibngt.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2xpoolhsh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqobnhze.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2sldwvapc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2usqkdubj.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwouohd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlhrjsi.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2adzuvtly.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gleeavek.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxzkygi.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjvusei.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dztblabp.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acqqegnx.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mftayglv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxfcsaz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbaapyx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuwokxu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2fccarbpm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2trxqvyno.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrmhlyn.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2etpecxap.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2lsedlrve.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzfecmr.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sdffhzzg.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvpcptq.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjqhosa.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgbgxby.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vulnbdbg.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxawhtuk.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hheozgle.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbzjgcg.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2odtyaicq.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpxncfb.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaiueja.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dowziwem.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2efqobxrs.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsunztc.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfursdy.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2sashtqbx.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2upssdvlf.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2oofigqbj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwqyjii.html


<!-- 参考信息 -->