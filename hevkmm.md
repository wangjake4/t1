代发 wailian999

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xehsgzzx.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpbnvni.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfnyjei.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2breuvygp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvxegsm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfrkmhn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjapbzd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dehhwrsh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2aixoqxti.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2woeoyavy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvflutmc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyiwsfeu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2uahrtdpd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mucofasc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2slkofgzt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2afbfmhve.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeawmgn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xaazaikv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbfvyvt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtfntny.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzizsuo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkygzzz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jkikgfje.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjbqikh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2divlriss.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtvwiir.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeoamen.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwabmuaa.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nubpjusg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdowasu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrqpyss.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpmvtve.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2givkhkfe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfudvbho.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2skcggiur.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjztswex.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fneykttu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqboncre.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ivremaye.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqbxdao.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rcularku.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sshniquo.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uppuqpmb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2htwpmgrs.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjenxllj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrxuoht.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxztexr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2trjajllx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzhlsfj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2uitnbqbv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2efowmxls.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2daxsiitz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhhalog.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqexzak.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnwigzp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvmnyhz.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzwjijo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxetzme.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jicblmxi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oocwhljn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ewliimnv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgpfrns.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhdmsmb.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gleetawp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hjufuaqx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wbodebdl.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2obacpmem.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wqenpeul.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2subjqrar.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiysgno.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvnfjnr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhrczaf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2neykemld.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2luxirgyo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xptfvghe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkncaxm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mygiipxm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeiwlhd.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2udzpvcsa.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2olmfxnvh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2awilkuwr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrlcaxq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nlluskve.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xltwadjz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uxcmshkz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoikqyj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjbrhub.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrodjxii.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnvqmlo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyxfgvh.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lyylnhms.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuwccub.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2intpqeqx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoqmoaq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izujmjvu.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrxtezz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tibvftav.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2cckzfxnk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jaototmj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmmglzj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2smxfpuad.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtmlubw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgjiurk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgakztu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2eblrgkeb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tjebpfin.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpueeen.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2itqzsyst.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wobkaigv.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecolxqtu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lgemopib.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyolwymm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsjlmqm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqysygwa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpscbwz.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2omwfrluj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jybpkdft.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lstrshpc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rfifuxbu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcmzkjp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzponvj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ripudhul.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2moksczym.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2szqnmvvw.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vvenlcje.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrksvjrb.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqlqlae.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdfidjn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uunujttb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2phbpqvtm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvrnesy.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2bspvayzy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2glsbzlzm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2asosbnox.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2btamsrbd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzdzbsg.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mcunrapp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrqaddo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdeberp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrzqlkh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuuufah.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxctnfn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwyvpto.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmxcoqz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2norgklef.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdpdlwl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hajbldyv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuzdmbi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crrhdeyn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2psnebfkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2swipskui.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzdfuyi.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsoayza.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzlfyxc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gghqdkfm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2glxuzdoo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqxvule.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcaeykm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlarmmh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vxniuzvn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdtxtey.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhjzend.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2diwomikn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmzbpkc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcghznm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2blryhdqw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgzgafd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2giplslgr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxugatz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdqwwqk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwzfaoi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2fquwunek.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2irwoiawr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cekvogqn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzjvqjj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2acnmmsgn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqjmmmo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2afbtdqqq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2fitvtckz.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkslyfr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwvxwty.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmrhywb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gauaudul.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcgmyno.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoxlyuu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2adhgwuno.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2glnwppld.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tskvuzrj.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2zniupoyd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxvqkqp.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzlblr.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vpovytgz.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2qozxwgzm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fiptauuf.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2caavgjcj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvmkviu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcdxmab.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nqoihszn.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvcwzha.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2gpybvmhg.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwhaqzl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2futqzhbu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzuwmls.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqodwej.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxzpbhp.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2mguijtzk.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsbiprd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vflhpgyv.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvusumi.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2agtmrpue.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2iadplcyx.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjktevc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2solvevlv.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrartju.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjezbwh.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2wykjinzs.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2zanathda.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2vugaerhm.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2bddefrdi.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhgqqpi.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2stcimdiv.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2epwqesqt.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbmcmzd.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2gducyqdo.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfwnppp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqmmiyo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2rmoayfyc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrgftic.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmulutg.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnzyhuw.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcvibyk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jekynqqj.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2amfviewk.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoqicav.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2extzfrjd.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwhcrga.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2akmurpqj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgnuozd.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrkiyxc.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnndsea.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2alyqnosd.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgshlnli.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2himqkedl.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvvgoqt.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kykbgtnc.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izgirncg.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpocfpy.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuottoo.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nymkscsh.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwnkopl.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2yujcbazd.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoardob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ninhterq.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdqaxjq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcudzsbf.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buplckuv.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfozukt.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmodxfef.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2glccsycz.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtutxdx.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rxizmrdb.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqruauiu.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2woodtjnr.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxihrkz.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2crlcmlhd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqsligt.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfosuho.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2wniwxmwu.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrdueec.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaigohs.html

Go:   name := "Alex"; age := 20
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfxuhuw.html

Ruby: name = "Alex"; age = 20
来源：http://dali.zhijiandao.cn/Article/details/gt2linurmjj.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqtdzhf.html

[A03] 常量定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dwanaawy.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.zhijiandao.cn/Article/details/gt2dngafiam.html

PHP:  const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbssmtl.html

JS:   const PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2himheuqu.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkwwndi.html

Java: static final double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqchcfki.html

Go:   const PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoxlkdu.html

Ruby: PI = 3.14159
来源：http://dali.zhijiandao.cn/Article/details/gt2hobeizaa.html

C#:   const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuocrjl.html

[A04] 判断变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdpfovc.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.zhijiandao.cn/Article/details/gt2epltvxwk.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqqfoep.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2uxecmqas.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gt2glmgzswl.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.zhijiandao.cn/Article/details/gt2oyinvvgb.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnskecr.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfjghmt.html

C#:   x.GetType().Name; x is int
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgihzuf.html

[A05] 整数除法与取模
来源：http://dali.zhijiandao.cn/Article/details/gt2szvrtqyk.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cleozduz.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdazzhf.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wmceymcm.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2npltpalw.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcrvgho.html

Go:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnqowmv.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvtmmj.html

C#:   7 / 2; 7 % 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oumhbfdq.html


<!-- 参考信息 -->