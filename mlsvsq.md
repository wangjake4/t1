代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtvkrtv.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2axmgpbgp.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvqmiun.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jblyskxi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzgwijf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2seidastf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcgmspp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnffzsb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ywooscvz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bomyvngs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2agmhbhyb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxiokbc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2molydhrb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cextrdmr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjzopls.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsvmvqd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcroqtz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2homakcxi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ferebbrx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2elftudsq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kluvvbpa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsrzbaf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2knsmwkeg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjywrlzv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdbltio.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxygqwc.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmfvjxu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2stfveuln.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnvepxf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbweweta.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqwznxm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2iltqdrxz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpunbfi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcgkyej.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ildauypx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwwpyhu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzllmxw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2cupnsyho.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2apremqtd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bujfrapw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeqsvzz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzhhopw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2husnfxzj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2styfxrts.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeyuugl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2veztwnkr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rldldmtq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2diijbmbo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ampylhhw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwcarec.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kndkadqf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lootwopc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsfzxqr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2urzopykr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvlaste.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmigcsfo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2csmopdhz.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmwzvtj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhwygnk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2sapnnqbp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgpzxqt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaigpxa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xhotznmi.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aywevwpm.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dohupevh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2opwaiygp.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkubahjm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nopzcada.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxebyygm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoitbae.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgkjsby.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ximqcweq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2meiqgscu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeyfzaa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyoddtl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdestwrd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jvykhdkm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnewayk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wxiinjgy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hghotwee.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jyesuurt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwddeje.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2nfflzlpb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wtksrrgo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2umrulspe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fecwvgxu.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkhdpez.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2armqfkho.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqalmao.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2gociklej.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrraxwd.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hohkaeyt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzcuytp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2piroejud.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzzpcyk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eceekeuc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2giqthjhh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmfcqym.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ninqdxwn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oirbhbul.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rzuekjhi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgylfna.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwdzykm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2deqnskvw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpnsyds.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2vauqpszg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrzcgeo.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2prroocbs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yptbvcmh.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnwgpsg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwwoqzl.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvinuvo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrylsus.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pglsczta.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxczbxv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwouvkun.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmsbkca.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoksxmr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqcktpg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khdbzfys.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkchizc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfnxrmb.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxhkylk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmvxmev.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hetbgjkc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nspggclj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2iceqgxzn.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2myecckby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sujweqek.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2upzzjmuj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2arpfxpza.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2cajqklzc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbxmodk.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2brzdyqei.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlhegrq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgnzpum.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgsdhoq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzciuqg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfbwtlv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbbedlv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmtfvrd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2odlxtqne.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsxhbpw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2oxaypjkr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ehafchpx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgztjxc.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmtvdxy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxhqlvb.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tldqfsjk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyxwjcu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyqhgpc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuvhxrp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbaumdi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2epwzyzhs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vzlegwtg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pprmiacy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2etlrxeor.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2odikrtoz.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwrxkzc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqchwgt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2czmhbjym.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzurbpk.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dixootwj.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bukubuhu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwwekac.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2srevrsby.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2qoouegpu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2uogmkynf.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vsciqyzm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eddorgsj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2irgqxmnh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ychdrjpy.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xafhxdgv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xghnpnhs.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eytctioj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcbvtqp.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2asfmsiym.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2txdylztz.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrdbhxp.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2zixfbugt.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhqhgog.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcrikzy.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsghcjb.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpxzalb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2romlpqgn.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmtndug.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwlbyxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngafulxo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2osehmpzr.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2plkjpqqb.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjrkpuy.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2myiygjfp.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeaflbd.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2rikncxso.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2weleyhrk.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2gofdypus.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbijdfl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2tjepwifp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2enfgdvvf.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2khhkxbaa.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2edzienoa.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vznlemvd.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoezxmk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnddxtf.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2pugxtovh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2exllzuwb.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwjdjhh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2yykurghe.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrbifpo.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2oujqgxsu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjivlvb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxotwtmu.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcdvxde.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifohgpoy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krsetthm.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgszzjef.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvdsazx.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sppdtlgz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkochmk.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqpoycu.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tahucnsj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdscwob.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2prowukwc.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2foodkgsu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxghbfaa.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaiklkl.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpqjruw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ucthoebd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukakigdx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2flfhyhgs.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyocvgef.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhdrywy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puxjpkrx.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjbrbwd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlebxuh.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhxoboc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivetesns.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yisieerp.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsumtfdj.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebondzww.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqldgkne.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtsetqm.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzdviak.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2abnrjbsd.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2hbveqjtq.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tioihstl.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2txdhfxkk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsskxop.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzubqpa.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vynfygpj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyzkntb.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2btjeenqg.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2shdebwpk.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yitalxnj.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2mrllsshd.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzelmqby.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzutxbao.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyqkcvv.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvdxrgd.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmpilrz.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2unvjjhnw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zevmkfpd.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pspcteqe.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmeucks.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eumicztp.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2isoulpye.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxqqnnr.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gckqjtsx.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2opwkbpat.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqblvta.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqvltvp.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2qudniueg.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2opuolylo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbsepxs.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2syuuafbl.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpsqkfh.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cbawrcyc.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaqvoic.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxgltuz.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpsjbor.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2orxpthkf.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kckhbobd.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2czdcenfd.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfipnfms.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcfanpf.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2njsuxgsg.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjldtdgw.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2inruypdh.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpufiilz.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2suagzqpd.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzworgra.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2sozllsem.html

JS:   String(42); (42).toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnlavwy.html

TS:   String(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2oipsfpcc.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzuihmth.html

Go:   strconv.Itoa(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdurttl.html

Ruby: 42.to_s
来源：http://dali.zhijiandao.cn/Article/details/gt2yuufqyqx.html

C#:   42.ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjojllj.html

[A08] 取整与四舍五入
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdvrisg.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.zhijiandao.cn/Article/details/gt2gznejuee.html


<!-- 参考信息 -->