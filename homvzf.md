代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhwhvxe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfpxzdy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rurvmvrt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nugdwovw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2snhgmtww.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvajuys.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhbaari.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dumpnysw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvcotpm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpbhfzo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqoiqec.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvmbdbh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnjsewy.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvdmqui.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nphhtvrw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2epdlgfga.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhxpvne.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhrryxb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpisxaa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxjubap.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2btxuojby.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2truwvfwd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2scdcafvx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2itruhrcq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqxdabd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlsfhvu.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxyjhip.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xqylyowg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hybqfqiv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wdthnqwm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hhztokxq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2chrtlwiq.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkgrumd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2likgtdah.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbpslrl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vumiedkj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mcweuqdz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2aihgzurm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrnogar.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rovtqjrr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zruksrbp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2jnysjufb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbdqokn.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxegfxp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rliaiwya.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rskybynr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2firlnafc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdeqpna.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2psdvowgv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2owffgxlv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlfrjil.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvviclw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrjglwz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cgshgeaf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2egwnnlsk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcftgju.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsdhtfw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2flryqllt.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mktdgskp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzrxrlj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qhpkdbru.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zthehfbv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tmscpbqh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2auteljrx.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wzytpdsf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhkuvdo.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ydftbxcm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkcjyjl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2azzesrvm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qcedzmkx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zafztnul.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfdodye.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcggduq.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxcdsew.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mukgsbjt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnteylww.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pewsvzpo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkxcuqj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyrhnht.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbqpfrp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pssjiuib.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dolgkozj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvzsncd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiktsum.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iquhqzix.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeomwbsw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyiwyip.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpoqerj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2svnyykcd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssiredmg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2geyvngmn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyhlzkk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvmzbng.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2exxzauol.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dytgbevz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2llamjfxv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2prufxdyf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwenncwe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqmgion.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbdfqdp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdkfadr.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2adzbeajx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pijvdpnr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyerxopv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qynpryfg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hznpovgq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fztdhxma.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2hmitwhgp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxdfquo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhudhbe.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2llykkosn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlficyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovshezmz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaohcio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itbibqzc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lvevcjvk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wqigroyb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgaqnrn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlcsfov.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kimjoilk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ijopoyci.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oinrpxfh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcjjghr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2stjgyvhl.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfbbiqk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lggvhvxq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoiufsz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2abedvygv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfnpzad.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpqjwym.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xczvjlhd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyfncyf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqnpxwq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgfeebv.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2deujmvyk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2swyavzho.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfwlfzb.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoxdgdb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkbhjvd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2cmugwddm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpxtipm.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vftyxtxz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2osmvshnd.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xktcuqjg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aehhocit.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2txzkxvbf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdtgfzh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkcxpoa.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2exihpysl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrewfjt.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mggzdvyw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjftvlk.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdnuooe.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2zqddzrkq.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcjlyvy.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdjfonr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvtewfm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cydfbdxv.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnkdzsp.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuxzued.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ndagchzf.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxdkujq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzncnqx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkwjahi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrlawnw.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yyltcmew.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaiewpj.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2gosgamgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yywlibyw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdlclxv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2axpfttsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2feqkpuwj.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2cramhfzf.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2xffzaovo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2asianxcn.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2avkwaorf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkogwjh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxjjbuk.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2flgplqiq.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwynvqc.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fahjconq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2zohbxebp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2pojhfrpw.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qajbhejf.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfdwklr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2gripolae.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwggdepg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bivgvufg.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2iscyacxn.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2hanpzise.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqcsmte.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xebfdbcq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xahtbgqs.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqxiky.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnpimra.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2somqlmns.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmytixk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdvcnac.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eckbtmql.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urolaixs.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtacdbb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkntjixv.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdymmgmb.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jujkvmnt.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2aieonaqb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scmpmbom.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxacmhfx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqfghku.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjdrmjb.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqsjgdg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwsuyqe.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxdxjmv.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjyuvvl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emnuexog.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdvqagp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxuwrtne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmsmanhk.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2noerenni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfljsre.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dahzwnyj.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaqrdtg.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2wglfknvn.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwjtrfk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2agnhjypc.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzuusox.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpumbfze.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueegvdup.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdqmfyu.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2grxrkzdl.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgllnod.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpjmtmf.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2aznwyart.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqecxcza.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdbcaai.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2unyruxtf.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxgsfka.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwproiuy.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uinjrvle.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfxuqxz.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2njpseskj.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtawzqs.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2upzbugas.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzukzei.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvzbyxj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2gsopxuov.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrxxzwc.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgyklus.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjlowbs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbydmlz.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2fneamgkp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhxqygu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2oojgnuci.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqutlakp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgctijg.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2swthxchr.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqwrlfq.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqpnbos.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htpnbeix.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2egutpaec.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbczqyr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtbntwf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vtionagn.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zauvlkuv.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfbsrnm.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvpntns.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmapxbyd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2suzahwow.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngagoybc.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyttjeae.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2niqlhtjm.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2clgqdjat.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmqtxiz.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjytdvnk.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgvwrjb.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkqizxc.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxtvywn.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruykycbk.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnthhrm.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvpzfci.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2johwmqrx.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2binlorux.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbalgwc.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2hsloiwil.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2txbbmlsr.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuziojrl.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2xymrhqps.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2kznbakor.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqdqmad.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2nboqegir.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeutxcy.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqxmllo.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxopecx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzeebzn.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtppxqc.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2meashmac.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2buytcbny.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvgklqx.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2aiizkzas.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2gqejjkjf.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzuufpc.html


<!-- 参考信息 -->