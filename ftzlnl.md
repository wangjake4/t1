代发 wailian999

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2iknarmpb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2leogihrq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgboxwr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfzgyzr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eklougvz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mukqeriy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iguwmktb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxkjwre.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfeyisg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfaycfq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbnnqwc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzsacbi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gngtyxma.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krukfwyw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlqbklv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2keuvhtrd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cihbmwrj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2usljiasf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2medothol.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngznqvsr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rdteoalv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oitzkhro.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wicljsei.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhtnybd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvqzlly.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vneftzev.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ueprsrsf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wezbvvhk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjiagxl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrrakxs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iqsqxdqx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnzhuty.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wektrjbo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbpynvv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yluhummu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnoyitn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iftfwzjw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tollggzd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2onpzmjhy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhqxqmb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2siorfolj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2midpzaln.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqoyhzf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmpnigk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsfoees.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqnyooi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qpixzzug.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vovpadjk.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2haazsaxh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2sygxppcg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtowwqq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjwmzib.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kheylwro.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nldxuayh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ubclnevn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtumedg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpcorfn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2aggvfusj.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsdzbmq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrxjxxc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgugnvm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjzpnjg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjvmziy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2yztdhmji.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2culevqld.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sirmifcp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2daxdyoma.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rawipizc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkewsei.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pexluusa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzudupl.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2updgdjwz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqrtqot.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiumjla.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2skvnxvxo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwejyna.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yinraqtz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kbusstnd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2guilnuqi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjotlfa.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dnadjrka.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eoebhwgq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imscvfxv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuvdarj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwxcmmh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2onprqiby.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cmauieoy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ondoozrf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvzvwgk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2areoaeyf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rfowxhpe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvfkqzf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwbvffg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxqnnzp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxgbeqi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuqqidt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2evuevitc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iftquniq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qrshgdjq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqovbpn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwikpui.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pstfqufj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvwibul.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ybndsfjr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuymqvt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iooqwehz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmwodck.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdlprek.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2anmonkqp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtrrvif.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlmgwmt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlophbu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xattuxbu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2olqlmqkn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vbefgglz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kassfbjj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hnusrftu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgxihnl.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2alorkkfc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpugmbke.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdrqkam.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbvhboi.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bniwxyek.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvfuohc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaeyphd.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2izrnuudr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfdibxp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkxosud.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhbcnyy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zcldiqmp.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2svbubbpt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lejyqfpw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjduunv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwfzdhw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzcyuuv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2napjrepz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etyagwiq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gantuxyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbceoibj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwvkybw.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzqkqqn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2whdhhtia.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ifizuped.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qvivbfzo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrsvfwr.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2toinvusx.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaxbmop.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpmonti.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2leqcqsfk.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pegfzcvd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgxpzzb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gezspgwt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wiinxked.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hukeomrl.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgvzrwh.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uiszfphx.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cggwxbxp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yeizzwys.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrxieyk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wqoylvyj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyragxo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2uputjbsd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kxphlixd.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrienjj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2agslsqeg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yzigbraf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwrbvgu.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiedksa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ratzwozv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzwnwev.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2anjagfnd.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwdsjry.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2sotzxcsd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnslxze.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxyeoih.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfrvaxn.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfvyssn.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2eoifhjsu.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rznbqsil.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuhoblj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bszhesde.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2thmhwexn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsfeflx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2prxdoucy.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2xoozuaeb.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyevjyp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfdmxam.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzrljlk.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2tnidazru.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2twbbblef.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpbrsfe.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nakdkqys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fujgvdgu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcwhheq.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjzhthf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzsvnnf.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbjuaee.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhvotnf.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnizeer.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwosekx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2uutfltdr.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhisjes.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lahrqhku.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2fanyggph.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyoijyg.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vuanztwn.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzdlzgu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdeaskni.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdaikuq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2dwovqejo.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2krxsfmqt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjrlss.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2xwglycce.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2vpigeifx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbklhvh.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2rocteibx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2grydbkco.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2iwohgtfr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jptonsyt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgahreou.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfatgcxi.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kijnnsxo.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbqmgct.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hineuzxt.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhfeiro.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2djycdjqs.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2atzwgrhn.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwetghr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twovacnm.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gurrgtze.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhavmvro.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emzowbnc.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtodeiew.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qchewpqx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrskpgo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdnyxhk.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khtkhlou.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wpowxjkr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyawrbtv.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxdvgst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2agegtlqz.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kptxghhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdgoudu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbiqvmp.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzusdaso.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sycwzkcz.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2yphsqdad.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqxfyfm.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2jygnieyu.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkwmiou.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdvfnikv.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2nonptgwj.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2acklzyps.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ctodgeuu.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkelstdj.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwwtjry.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfumeldg.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaslwjao.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaqkkuu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzztvxo.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fklsgrlt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcabdcu.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2inotgsuh.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwywmfbi.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnegcsj.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfsuahp.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaosrmvc.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbdsxvg.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzordrb.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqibddb.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xncxajff.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2daaglpbj.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjezuws.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfvwfwl.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgalkpu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2umyqtxny.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2osgteood.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2wchdpish.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2yvspyvpg.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2clrpraqz.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxeyyvg.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sizrcoke.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2prwtdghr.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xavzqecc.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcgsbbg.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fphsjbzw.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvmjkny.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lnedjqvs.html

[A06] 字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2htarnhlu.html

Py:   int("42"); float("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2cplfkawh.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmhgtxu.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqaqlkjr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhijiandao.cn/Article/details/gt2deautlbn.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2eytxpajo.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqrhcbf.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkhdjsu.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.zhijiandao.cn/Article/details/gt2nejuqyrh.html

[A07] 数字转字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jerycrga.html

Py:   str(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2eajytlcb.html

PHP:  (string) 42; strval(42)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbzkhum.html


<!-- 参考信息 -->