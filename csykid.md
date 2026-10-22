代发 wailian999

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdyhutf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuslyfwx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fqppcmhh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiozwwz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwpqaaq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcyvhia.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2syrzfjvg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqfymcg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oxectfpp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbreetl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nmelfosx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnluixd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gsunzacd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxawhlcm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2npnjwhsy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yolmsswn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fiajtkus.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2koxovbqw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlyawch.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbftvnru.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ycobozvy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbzjscr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pnofsjwa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2boodyoar.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzvyqae.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2upcizphp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmuvxbi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuqwqzp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2anlkptvu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsxfsfk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgksxdb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaauzwk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjgpdpn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgbqksx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuomuol.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ischbnni.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2lgylazfx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvvssls.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsmynrh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbsquxv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnleibz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuttmrf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgtwpky.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbyoesj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rerfzdva.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2onrgpjyc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmbxlds.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tduswdia.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdxwgmi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxisytj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iehqpwhn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2reljummd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aywkjvob.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2mugesaud.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgunxyr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuehldig.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgbpmjg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2rridwodj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpahutmb.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfasseh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bziflzsm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2haffmwww.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dduhkknu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyissgod.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ueokvgty.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxgpnwf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wxaojhnv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgzqtar.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmommlj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzfezci.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvbfrtb.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiyywwu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jekklxdg.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtozppsq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2swlibojx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwizoop.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2puhrcmbr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2odvwuhou.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ncimitse.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqkuhif.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ckennevd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhurtcvv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iyozypie.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2dohaguwv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcndaap.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2aojgepev.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcedrcc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2teqrewao.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvlyruq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2frileufy.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoammod.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2imdsifye.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkksnck.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdavech.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zixvtkuc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2coehaoks.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhrkbzv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2casjivnw.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrbzmmv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2msfeheti.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmzffsg.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhpgna.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvumbts.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhjpreb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgclsnz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tquekfga.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2orcpnnev.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkhyvtv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifqoqe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gudpckpf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cntozvnt.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bismhnkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hidmljmx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfksfvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rycxapmv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiehtec.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmybncz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rgswlrqi.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2psarozhp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrovzle.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ejssggqo.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wftrckvv.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2axzlilhp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzfpopk.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvaqpys.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wquzzxpy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmxctnc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2djujymrj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhphwle.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mwywcxeu.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfaduhu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2httkxahw.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gukcpegq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aqunkrav.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2grkbgspj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnggqqp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dcayfkhn.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwhfppj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rptnjunl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2expasgyw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2qoysqxcl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2irfbijsu.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vejtfqqr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2xerwnbtk.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgzrteq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2thcmdioz.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnoptvf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyllepo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmnpdsf.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxgojsi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mesyoyrp.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdfnfgs.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvqkzzn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcwajps.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dvngzafe.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vntxgifr.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2eahpmohn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fccxfbhd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pofnvlps.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2euhvkfft.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdjftgb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2afxxkhnh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2kftfwocv.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoibaxm.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2envxklmz.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2epkwtvwx.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjwekvz.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqtezgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkuetzv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2lakyawsd.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wvywdjnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htfgvfdq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbokjsa.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2nptcjpis.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lxycleln.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimkhaf.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2ywelzqsk.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbbzdno.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lghbmrub.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyqbvxq.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjyxsqt.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxcttxf.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2brkucbpc.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2wsytjnzl.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2zfoxkkjj.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqxcybv.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhosffg.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2oarjurds.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uimlcyhd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2seyszkpc.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2otriohwg.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzwsqlm.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmsdhqy.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwzrnzk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kpekrslz.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzasang.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akrwhgvn.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjleaqr.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scyzsgtw.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvhqirg.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbaqxgtj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unjsgrre.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2heiklfpt.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgggwlwd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbofqbwg.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkewdon.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpqxokx.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2adfegpkw.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxrxsa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiluagqd.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfinzif.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oemqjmim.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoddncf.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zceoypxu.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jagdscux.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfqjbvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaijset.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofakyllc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obnnxvdt.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtigztdi.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2srrgmdgj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbgzqvm.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxdydyi.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2umhintqr.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxvqmdd.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2mepabnny.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tapsrvvt.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uprblrbi.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnexcbu.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbeulej.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysczwbns.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookaclbl.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzyjreo.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmxkwwt.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2loimverh.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2spcvltcb.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcojcu.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvvarsj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2pblqsjeq.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2todtysmx.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dimhjylg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fueapuyo.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtykfmmw.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiehaua.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2odwcntlx.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulclbtj.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpdzkeu.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeaohkxq.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozwrfnm.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2oonauoiq.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgnjlvy.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2eshqdenx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2eorcuzeh.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlkbekz.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2btkzsfdy.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnjgvgf.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdikovf.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxcqxqi.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcdozei.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdapnkt.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2enshbczx.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqgctjci.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiiwrhp.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmiyial.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnlsbix.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwatsqn.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvbsudn.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjscwju.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2exsohzio.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzthtzkw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqzwbzf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2jausghym.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwblgzpy.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmyvahk.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2reqfophf.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnmooor.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtqmiob.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyouazlj.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2bttglfzh.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrzeapv.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2jismuqea.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkjdocv.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2amlgxlex.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gusotsnf.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsajpnvw.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowukzai.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.zhijiandao.cn/Article/details/gt2bofebega.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzldsai.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhwyatr.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtthdwz.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqquito.html

[A09] 绝对值与最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvecymz.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsbinhl.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bczdhsci.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeruhqf.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjinhbp.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudrselt.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.zhijiandao.cn/Article/details/gt2lbytggjf.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxnulcd.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwkfenw.html


<!-- 参考信息 -->