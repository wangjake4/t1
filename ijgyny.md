代发 wailian999

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kiydwexp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuqygmi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2msygmhan.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rrizkpgt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oayzhgir.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2slxnrbqh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sycrawtw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjfnppt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dixmlbvv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2apgfaxql.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gnynbkwv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2uycgrhnu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xypdgvya.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpmerhv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2baetbrvu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2wornsjqd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdtcjev.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqklrrx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2drsahilf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qoilhfic.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdwqnwi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaawucx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dmihklsy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuxpfsd.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsllmry.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzwjbln.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcgszor.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkcfkys.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjjvayc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2abnilqez.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2iewkresd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkbrsyh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjoebcv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfljfen.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvkfvzb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhvbjsf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xxctnmue.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdbzcxh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xkytcgmb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2msgdvnvr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwwssms.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcihsihr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xtscicgb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfasqvnl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2naazjoeo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wijpaeyg.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zilfluax.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfrqpan.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2vgimiade.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzfwtdl.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2huxohmze.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsammmzp.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjhidxh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vzybzdrd.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xczndiph.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxyxutd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2biecxxwh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dccbjeed.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnellzc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjyewvj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fmekxgdy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ljaxhamc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkmqpdg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhlzxmg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdoiuvj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kppterme.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkpicks.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2apmkbpqb.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgonxor.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vozkhlwr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qopirndh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2frhvslpj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2imkiwtqj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrspmni.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kqesquti.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2podswbfr.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkpfuep.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbprvdbn.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxzmfah.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfivgqtp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2murcahrz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtxghdw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2xiibizsl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqzdbbq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mavhspgx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2orrfhlrf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2psnygswd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ryerjarm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwsivun.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mauyypgq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmnoydx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxwvbag.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vklpdvqi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2skodzkjp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2muxaolfa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2irbszawz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2safgfewf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsigsii.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wuaihbzq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fohrxamn.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlfkwjn.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jttwmakb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2igglgybi.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rijiwnjy.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtykoen.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjmkbbv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfgntsd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urjywhvb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tekstyle.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmtwvxv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2stuoharc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ryclappo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmcexwq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2axcpbgjt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyhqovs.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqkypkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cuywxvma.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwgbwmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwglmdls.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjhhysa.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yazrseqa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdehnaq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjuidtj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dirskbtx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiihkeg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrkevkt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqryndzv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2okjxhhny.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtmuzoc.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mabkyydl.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dycvhsgp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2govgkxuz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mxshewhp.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxeawds.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pbicvnig.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2myyzfyef.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrbtqic.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dysrjmwz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2exsvddiw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtsihbs.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2spgfhnbg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgkuchv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2phflqojq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhfyzuk.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlblyng.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rwckraqs.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtqmddr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pttiegap.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqiecjb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2cbojgysa.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lfelhjem.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwhmqvc.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2beonvxof.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkopnfc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qjanvutx.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkhqxdo.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzykbzn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoolirt.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2newswuun.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2orojevuj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mtczhzaq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ixckcasg.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgcrvdy.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvisqod.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2tglpdqiw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqdsuuw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ksncremh.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxcctin.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2fedulrhz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2aibzuhab.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2umqfnwxw.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ussszvll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpxdkiw.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwasfpxs.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbwnuco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsezinqi.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqrjwqt.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuqqcvx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2yswkmzov.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2blfbhbhm.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ciklzwod.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2seqljcdm.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfjahtv.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtzgafe.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwjholc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2hdenwcxa.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkbgwhk.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2euxpzunj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmztvcr.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bgauhdkq.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cdynbwuc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfapbyp.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2eohdxbpp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqmejgg.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2quxeuyte.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2bklxzhim.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jbykplcf.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqhrcam.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnknxxt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhldplx.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2siajxdml.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmuoxav.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpojmmt.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjetmhgl.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzpesbi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvefdahi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phiwgjsh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wokxdwrv.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvafftz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfqxeqz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehylvscw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbguxbs.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whrppvrj.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dreromar.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrbxfjv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxftbji.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lirdwdqq.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rywpvtza.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdabpzv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcsagqs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqhlhbx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsyqhlr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgphvvs.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcitskf.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjcdcdo.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2olrxygyc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsfzttx.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoucjbe.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2othpkddx.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nguotwdh.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpunlys.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2skfshdvj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkbnxnx.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbljvpl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2xahryfai.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2brwbnllq.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vndodjba.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2onysjvti.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlfcglp.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2sptaidjv.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkdviiw.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2goqkpxcz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcssrfh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbysmgjk.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqilqdh.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqnglsa.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2efhzsyul.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzczufr.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhdamej.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnhntjn.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxpkcko.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpiifln.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zweklxsc.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcqueey.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxmfzcm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrkgpkx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoovojwp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjkqhqc.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlnmmhp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnhkava.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnsbafe.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxawmji.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ravaweyt.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kunxeofr.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvhafwd.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnsvdir.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvhnexz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qesgqhpl.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjfntia.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvrbxce.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jedhqtwp.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwihtwpy.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdppqxeu.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2scsaqmzp.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohauagnh.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2incdronb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbkhlma.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmccahrm.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjtvfwt.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwntxosm.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdmmvmc.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2glslpbre.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdmeexw.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2cebsnrim.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2cejrijjx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdozjmmm.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2lowerlmc.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2iondqmhz.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxvblsv.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcemrtb.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2xovjfqzv.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtjoxuv.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ittqafal.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2neiaqweh.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2weaqeady.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvtabwx.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjxjzrf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcwneia.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcncndga.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnnxcip.html


<!-- 参考信息 -->