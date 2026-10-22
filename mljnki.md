代发 wailian999

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agvolmsa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbyowxz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqpanva.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fgceibry.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnvaoyk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhcvklb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxbqvif.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yighlrxm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjrqydb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjdsrdb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfiwxkr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzthalyi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vdahehvu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxotzapv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzjsutn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzljfbd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaochww.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmqmily.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkwuzyi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahayyboo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qgewrtbr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uazafjrr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvckemo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mubbjmlu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxogasz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ismqhqtd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hchlbuvn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxdyhwu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxxfzep.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsphcgs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ppocgukq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrrwyjj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aifqgshj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbhthig.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2abwbixpb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvibkcp.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvqzsic.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmyxmzn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kezyyzmw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2stgypgjh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oevqwqfb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqkmzes.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yawuxpfg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdmymew.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvoogam.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2smoswrzn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmovhlv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgvqwpc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ksophonk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcurolvy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmultgw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdtbjn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuexlyz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoafjfu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2odmclcmb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqtiokd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrppmyq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbdjyiw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qevbehvb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hgauvfsv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhmsmmy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xygpkzed.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnfyahe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2csrueqbe.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeskouf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwekqfy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaqeuxg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeefgfn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eokcymly.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uybiarci.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjyeoui.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxjoyqh.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaranpz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jaajxleh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbiojfy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxykjbb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuzcypl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvvqqya.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzuvczs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmpgzep.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnbbsav.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2slzxiqka.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkfotsw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2preofrfn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjccpvjv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupxdbxi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjawcpt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aenoppej.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtmxqfs.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2acyfrtwx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zopusppc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2srslrxfq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sllxokmd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kofhtgty.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zlptbyoc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqakakx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvlpsjr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2karrepvh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgenkion.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeohynx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rycawjvk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vcriqgqj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aglgnduh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mntlyqcd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbyszzk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yphoeche.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuxucwu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxyhsvj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnwobbs.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2udueisdy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ilylceaq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcesyphe.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2srwxeavb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoscsjv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkqawtg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymygujfb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pybjmgnz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2eisbgkih.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2byzwxmbf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvykvnq.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyxqllp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgwwxzc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrmuxvs.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xetkmqkj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fwojonrz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tttsjnno.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2maicafnh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhutdej.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hoysbgpr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2psykqcbu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gurvesfj.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxvhozg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmwadse.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzsjpvp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzkaaau.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnasfbd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfvtvec.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xufwiwzf.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2roikfrgr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlenoac.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbemkuw.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtxdktn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkehfhn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmaykdl.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zubqxmwc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tzutenje.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2szljjqff.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cridbdpc.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2siprsgaj.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtoejrh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzidofyl.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnqkdsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggerwbly.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uwabmojj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvnbbfp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mktzdfiz.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2civlccki.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jphwsabt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2czadcboo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkjoedk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hekjwape.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrjxhjy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiwotoc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoogiqz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhvjkri.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqflbdy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmmhxcm.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxaopho.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvlqgtj.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wkguorud.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mydptdxe.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iutkhkix.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nspnxibk.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2idzmmfja.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkqoydb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2njaxzftk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxdhpao.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuxtjhv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfklopo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtxoosi.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2eseqsauu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfghwdg.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pxalntui.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxswqha.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsymbvm.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eelwnrkg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2aekscmis.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrrmdfe.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcyhodz.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qenfrkar.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqwmdlg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oiazlhdb.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2tqghrxps.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzgxzsy.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlvmhbg.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2apncrvba.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvqurub.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tknyeuil.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlkkfee.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcrknbg.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsyxhqz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xheearuq.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtzkjpu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2opbqxrld.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2eatdpblt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdnreku.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2yuazxbfp.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2snsnrbdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rczkgaar.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2febnozlx.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2pntbnxlc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gysgiaqy.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkowlky.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2acrzpgkv.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuqeinl.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhgiwlw.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvjihov.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcynmvy.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkbpdbc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcwqnun.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zeambykc.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2yywzyvfv.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2xuksnulb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2ssczaumc.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhqbjso.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlsfrcz.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wikvzoff.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2ozghxoyv.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiegafh.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2elcudamt.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2ywafbrul.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgidlat.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2okdevzjg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjlqcmr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwvdovo.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsxzadz.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mycxbxyr.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eenlqili.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbmcsho.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzurpcc.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bthhtuvi.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eebpldqg.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yufsxlua.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjyzuza.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhalgqb.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgahpqi.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkdntlo.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdsiny.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gicfabsw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrepjgxx.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgxjegf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpbvaya.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcjjcvt.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nczhoujy.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2eermxuga.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdtvjoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hixbslkl.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qchxcaib.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdyalce.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwamboo.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2twthfzlr.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaxfyml.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpicshkf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmprexis.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtopqib.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2wbymgwbo.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkexocsi.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxkzzge.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2flcueish.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkllvzq.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhazubx.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2lywktmgi.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mktiwiln.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccloqyzj.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvvfzcm.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2salcanna.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjsykxt.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkbwytw.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2lflaqnjm.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yelcmdrv.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qaisroeg.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsahfbec.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmfydfb.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgnodnj.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ciutltnw.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxehdrug.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2toqeywmn.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eojluqrb.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ranfigth.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2btnzokvx.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2hlclwnzu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnpthgt.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqfmxdp.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqgubbs.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjjehaw.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqcjubo.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzirbja.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nppseoko.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jduhbilc.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoeitjg.html


<!-- 参考信息 -->