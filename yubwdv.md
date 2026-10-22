代发 wailian999

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvmyqvf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiwpgbz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxvmhme.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cncnjdkc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwzysbl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlmgwxu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jcokrssv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvffyea.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nuimbjop.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2feranshe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2grbpxvmd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2aydtaaio.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfcfdia.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eityvyip.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2btntevfd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxigxqeq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiqidlg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdlkmlv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aznsesgu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2oifspugs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2chzwemvd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxepurv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxflguup.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2onetwrko.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rposhvxa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrhvsjj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcbxqks.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cffivbsa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2aostxahm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsikfwge.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjnqclc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbjaqze.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtdeqst.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qduyhkxw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzvhlng.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkydoyxr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkoifdu.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tadandnl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gvechoif.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uxavdpvr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwreyxz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2frkdepso.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lymfbfhn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2oiitjdkw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dunjulwg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdjhzug.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjijlmv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdqapbd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2atnpzowa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xomvwuhe.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zpskvpvm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahypkork.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qweqnjrk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjwmdws.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vacsequx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoapktv.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogytmebn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmpvltt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rvksjbeb.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mahtzknl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcpabuc.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlidttj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwhcbqj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yifhsfwh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnoxwmg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxzulef.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmcvepx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2taljiahp.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhyhgjv.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqsxdtb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gxagaicc.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbfddbd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmvrweo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yjghytja.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tohnrsxk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedwkwcv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2izuqscdf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimkqvr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhjnypl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjskdae.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgeegdo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaejdcu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xutlognb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzkzfyi.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yntbapgm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dioyigbz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gidbxdwj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtvjhqq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxyxyag.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oijrnsca.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ettvuysu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdexdgo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyzopzh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwrrnsx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2spmofogs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zataezdm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqgtrzi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2czbpyzuk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdvsomc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gppbbwau.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyeqhif.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxfhyrf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfskayw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2caecarsf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyvbcza.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2dejnmegb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgirwob.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbdgkeh.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnijvws.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrfufmd.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xljsybim.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzzwduu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yufwujaa.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tounksgw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2udpcssfc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcangov.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2siyxyzsj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwmcxvd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqcptzn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmrztvy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2zffnoebi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2talwgzvw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2honbvnff.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpsxrhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dscforpj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdgevbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjidpwj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlfaztp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uueajgqh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuwlzvr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2srjukezw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lzogkpsl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2orzhxxll.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfogean.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gryshrha.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2shhifvzf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bokbzrbf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjnysgc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2txemsynk.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2obgcrakq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzyoheg.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eltxsscb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmwjini.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaevlur.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dhesbepq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpswxti.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrncbrp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ludknnvd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrnhzzq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdkclcv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfoaeox.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xnobvkkr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaabuiz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkjbjjw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qwstuspf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hkymtxyw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2synchthg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2grlvwefe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnlvuiu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqkljhp.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vjacgpxj.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2czrnlnxf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vrstdify.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzqfafl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtxppaz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzhrhqd.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ubummgxz.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2sonqgfgv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwvzmdb.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gupwzewy.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rozikalw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gxodvppd.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ullvquxx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkeodob.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxgdtv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqeipfi.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2prbeusmf.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvijaum.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2ghszfpdm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2qradeiak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vifnuczf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdkumfy.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2lufjlzeq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqzvzaf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmskvgq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsbxaat.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2pkntauun.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2iniiuvtc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2iqggndqn.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtjffkw.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pezrbtdf.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2swvljref.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2oafnooxt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2qieiyhei.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwaszmg.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyiekyt.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fevjolku.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2qgphqlij.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkswbbu.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2xnovwbds.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzxmrhk.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhfpufu.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zboqpulm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2zokltjye.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsrmher.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvakicx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2faghrkcc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtgjxlz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qduasrpr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyfyknn.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjekgpn.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlseauyp.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlauezi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2boccqawj.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wogxknyk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2osudthfx.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvcqsit.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwwxljy.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2feiuzqda.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgiscot.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdaudjsk.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qitpqird.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnahzdv.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxhnkau.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fisdanve.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnsufdb.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gcljdaix.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2toyjincv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mlokqkrm.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlxavoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrmikpd.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2trqtzecx.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2owxzyjlt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2keuwxvvc.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uqegxsyf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwxjfve.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbesdrl.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbnbouj.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdtbqgv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqtyibi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2tnezxhbt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbppfjf.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmkwtpi.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxahdude.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxuzruqs.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2yafscfpl.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2zodqgdal.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxwyodb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwhktol.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtpkvpz.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2afnewzio.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufckiqqu.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlprbev.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aalpbmjl.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwolbuca.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2doqrvvre.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hulqmjjw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2catvhwyd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdevzjhk.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aypctxbs.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csjdxgye.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2acwqxtig.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvrpcno.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgsvph.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzamkrgx.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyryumzd.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2guvqrbvm.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjaymhc.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2owuuxnkg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evckzbuk.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qezuedrs.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vcljahha.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxpgudk.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zncznraq.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2accimdad.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tonfqzcu.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2chaktflz.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcbiext.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcxefsw.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2jokvmbcb.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfwwcvg.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2mndqklse.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2dazgidwl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2ecakavbr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eprvbkqg.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjphmub.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdzdnbi.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sprzqdyf.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjzgoty.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcffusud.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnodacf.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjibclsi.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgenwjs.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2apnxzsov.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkxvbxy.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmzdyrs.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiefxvpd.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsoqxrk.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdiiehtq.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednuwixp.html


<!-- 参考信息 -->