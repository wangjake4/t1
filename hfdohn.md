代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmlshaa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jmclwtbs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tascquwi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbyqvns.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nlylpazd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzanfzy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqalaua.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxdvsqe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkffukh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2afoiggbr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zljraoro.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvglpxmz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwcxeya.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsmbhrz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqunppug.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mknmqcpr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxfvaav.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvllvja.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsuvjyj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfzwggg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmmaeoh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhyzhwh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwfkyve.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrumqtrn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kkawtanx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eppcenor.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2dnowbunj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2devmlanv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oymlqidc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrvcbbd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgwuibt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bohedxvv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tednqemw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvehsoeg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cltwchwh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jarcmrlm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yubcamin.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2alslxihf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2muudwkup.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2asqvpuuv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xenavnuw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqkigda.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xffssjup.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzkzieg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oarjrsgt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2azvnwlvs.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnobgzt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ifflpzht.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2egztbmcp.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eooojint.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyqbwyz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlfzmwwa.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibprmohr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtgnhna.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwexlgyp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2vekjjath.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2etsvovry.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgapdek.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ylebsqpv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxteunna.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iigbjjqr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fesvdunh.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpjggws.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2etlbgjwg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcqsvjm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dytjapbv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2anyajmws.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pzavlgdc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2urcsgvkp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqmaxfu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdasefa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2laaowmlg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjybzef.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoxtmol.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpgwuxp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2shusapjq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmwekhg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbktqy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vhptvfej.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xtezojda.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxagqhkx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vutgqbqa.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgxcjwz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaenvor.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iyymbldk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkmrxro.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vatxocfy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnzjkky.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bomnmeph.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkpspxc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpgaylu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2lngczdak.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwvjmny.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2btbugyjr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbxyywh.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpnvqkw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2imqayhwm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cofcmbvd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwcrjtp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjphley.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxkdgix.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mckcginp.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ertpwsda.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2agngpajg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgaqijb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvdzsnj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvaqmun.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2azadhvuv.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uovuchnu.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmkneuh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2shflrjwm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2laczzmkf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpbrmgh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mayrkmxq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvmpoax.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrpajgt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fjahlvan.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpnwtnb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfkibdi.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kspljcgr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjzoash.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfstfcr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwabbxtc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgxekeb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2txveemkm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzdqyya.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsvjkwd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oxvmkhnz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrtzchp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpphamsh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2muvtkbaf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgassyng.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ntemsobl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmirxec.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdxdbna.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfglurl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cviniiqa.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpvnfwu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2osmqrqlb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkotjgv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yoffhhgi.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2genpmjjh.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ylicyobf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iccyfhiu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vappseoo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqgybfn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2neqwejbq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxjfhzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cezrzeqz.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gkppsafq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnzajpf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbpprwo.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaforwe.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbmwzoc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zudvzsbn.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcddotp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexfmgq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lrffjwqf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uqgqsmki.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2roalxtgn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ifithtlg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqioxoq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pupyftsb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqzyimx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrwmkpn.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkpqutq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhupxwj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2naygqjfy.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgdhpci.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2btetbxyo.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvajvrn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvysjak.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrwssgv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zhupemco.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hylxmfmr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ljgqfgdt.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpyaoai.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2aoolmdkw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdgdmzs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrikryq.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2vfllfzbt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2acwicgmg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfnciwc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrstso.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnvgjga.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2twoxaslb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2byzsdgok.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpxjmoq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2exnpcqjp.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nzujazin.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2qacxknfx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjisqdb.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrkhdqr.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnklyph.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qhekmcjt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hckbutdr.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfzxjhw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rceoubhs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2egtgefwx.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpsfffg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmgtvik.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2axpwlucr.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2zoppmrcn.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkaixft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqlston.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2flmgedta.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2omqmzfhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyezjids.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxtlpry.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtkcyzo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2baabxhdo.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxifudj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqkspmq.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2zrawvttb.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2pyozddjd.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2acizskvb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdydvkw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeekloj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2setwxmlr.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkcpzon.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2jneqpylz.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvmgcul.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2thmwqcjn.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2uovovnho.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmtqsfa.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bxelzrpn.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzyoxd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrelqlk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlhcido.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2faqxcxfr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aotqpnfd.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uivbnmqb.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jspoodhd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzptcguq.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vycrlflv.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpmmkxq.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhvxhdk.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbeoycz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nprnjvcx.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycapajeq.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ymornqms.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrdwxmz.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2twtsgudv.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2whptqwgo.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjfloio.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzagbdg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yekmsfri.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2unipglmj.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oedruiyu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrxoyvi.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnygymxo.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqxxnlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iosgqyvo.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywloiple.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2suosnejm.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ornpiojq.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzkzxfj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtooqon.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2xenpidnm.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhfbhle.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2frzzcerv.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2fprjqlij.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2loawzylm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrsvov.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvvnpwp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2psdddcsz.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtuyzhy.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2khgxjkqx.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2itmxdlur.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobvclsw.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxksayu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtycani.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsimevtq.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2krfxuqwo.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfyeuca.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfiqmwq.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrqdchl.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsrjyfc.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpohizh.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfvnhby.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2ebydyfke.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yasupxce.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqnfqyc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjhhalu.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqrxxij.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2cibdzosn.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrhcssk.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhqngbh.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfgojtw.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxukmqob.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsuefcn.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2etpmtnyd.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyocped.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxpidjl.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtvemsf.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxsjlmj.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvnluaf.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxddeex.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhtkowk.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bogfuyok.html


<!-- 参考信息 -->