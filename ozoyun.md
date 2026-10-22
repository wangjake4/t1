代发 wailian999

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2snngnuew.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lltzurvb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdineuw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpgymwp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nknnnpat.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pavmeulb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsifbab.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqhhwha.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2djgngiwq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yotvcymj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqjtefj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owhhqgbq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cxayfliq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oucbllhs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2chonbfee.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgwnqjp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrsdojf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kowobtyp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2huxakqtq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtnpeif.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzkgtgg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2skmvcubd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeastzd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lehqjtfm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yphozxmr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2grllpiwp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2djmulymg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsrhzdv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ggplhiig.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjdmytv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmxtcnz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xczpvkft.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfvmhop.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpviqmc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkjosmk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2owrusvac.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2srcrsyum.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyfkwuh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zzysmwiu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hryjxssc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxceyjl.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qymowaet.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fhottqbj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxhwkav.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mawvlamg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbinzlki.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tziofndt.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rtblxjgv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2japddalj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gnozwgcz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnyvtsy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbiehdza.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2amfboaqz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdspbtfh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2anaeyibs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hteftprs.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tktwpkqy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2czlfbszr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjfwccm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zattzbkn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfjxapn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmmcdxb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnelmkm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbnrlxw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlipoqx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsmnjpl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynatuyqg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmjkjur.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xzirzrky.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kvczklha.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpdegls.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfsxcbz.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2itjwcbew.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2odffixhg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmwxomt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vgulrjtl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2etxbkuua.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyttvlc.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhlwpnp.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2etwowkbu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdbzepz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoofcsn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2etdmbgvq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gphmujlh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqtaioo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfnliwy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzhlwao.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tkskqfky.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqnglki.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohptkogz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jewpswvo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxavjas.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2agizpyab.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fevhkqea.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwlhwnr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2frgtzxwr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2svwyvjem.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzagqes.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjpkakt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2suqmgnaz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2enwreavj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2epnkyjkh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfvphap.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwnvnie.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwroqfp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eksatemm.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2exdtrmfv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlceecwa.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbdqvtt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjtqcyt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxqezvm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuopeqwb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fxthgpix.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxchwjo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qblfvdyf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2fokhfrmg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kijcwhsq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkprdph.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rblhlvnn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nwgynbyu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwgttfb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tdddezyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxstisu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xdojipya.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2swkkmcie.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oluhdavr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsvntzd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yjazgksb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ncurpzqn.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yomvyyvx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sghsxgwn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgkefwu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyzekzo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoafnnt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpppfcx.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2atjphcqj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhyuwct.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwduplu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhszaec.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xfymszvt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iadivcvs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cyekjgga.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jlllhnkv.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2qpffxwrk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2bxovsoux.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeyhywc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqpqcit.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyqibgw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaeqder.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrwqfig.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2snthtnbz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rucmrzrc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kadvjuxu.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2laldjtoz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwhcbie.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2keajsrlj.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2njfkvoaw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xliitopo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjcjjfg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2myvvxaji.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fobpmihf.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2auwesarb.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2yinwbxsv.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2civcjrtx.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2hixgdicj.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fydhoung.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hpefvoze.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbmrirg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wjobagun.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuckzxi.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2fobgfaan.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjonpog.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvxtulb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2jeygsjub.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wcoihnia.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2dghgxylx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suimgdvt.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2tttefcfn.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2kotuhvga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdovcih.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcwuuks.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhvyxmv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2tsiqwrgr.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ausnvctv.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuanjbj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2sadwxpqm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfqrued.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaycwot.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqspthu.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqcxfgx.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ttaklaqc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuubzuk.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2oehqojvq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rerptdtg.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfbhdzg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vasaodbu.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zbybizdk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyhvwsm.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gorgqict.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ipghnnmu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2iyecgyqb.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2xujyfkoe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dukzjjsp.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpejbmbl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjazlra.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqnmfcy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaxcurq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrzifad.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guwytqfo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hobtitas.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvncwbgy.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcwgabq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nyinnblw.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2muvuqllt.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olzqpnpf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udfnlfnr.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvnlgir.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yztijgnh.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nspulphd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnveyqv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpygzwjp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2laletbre.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbxousa.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhvyywe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylovvcrr.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkctlfg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdhgods.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjiiqkm.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvysxrg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuseizl.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmbijpo.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnmbhxm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2okucanen.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2uowfcyof.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xijimgun.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwwcccy.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fktwmail.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2owdsfqop.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nytyydix.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vaugrosy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieksrxec.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmoqaah.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2nndlryjm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2gklncnkd.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxcenyp.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfwosym.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxtnvpr.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gysiqywh.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgatfrz.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfauhqeo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lumkhrfp.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fnilwyuw.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrknhft.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwgkmrn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiobwdh.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrnasqt.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbwwxwe.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkdxomk.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2crcdessw.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgipwzk.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ompravtw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhphuext.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gcamvnjt.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaosxot.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dldqqupt.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtqzwva.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avvmosqx.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2orwgzfhd.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgxqflp.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqigsgvw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfvfjpb.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zndilcwv.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wiefhgan.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdqdlxx.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrrgewz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2uciyqbhb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2sszzbinj.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhotghlg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixghqbsy.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwhcboj.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgpduqx.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qcoderkt.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2yugmsnkp.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsttuuhe.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kiegkrki.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujjssfs.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2djmunivu.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsvnadp.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2uorzzhmc.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmljxul.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2gazznlez.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyzvjzb.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwmnkjq.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzazzcy.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmxdxq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfydaepx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2spfzijwg.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2vwiegtnh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxxapgj.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcugutj.html


<!-- 参考信息 -->