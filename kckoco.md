代发 wailian999

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ilheirhi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aqahtzdp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcokaka.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2grajbldz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhjtsw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfchols.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hemgyvea.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfaoojd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kvigzquj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2opjduacg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qczgdayw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpoayxg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvfkkbp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtruvhml.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnujnys.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnwbfek.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsqsvsr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgrfwxyb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyjcnup.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjrdgsz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyxixdl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oimezuyo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wauupyxn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rmcbunxd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cemyrfiw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2aufavtyn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmgobnw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eltksqly.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmtvcyg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmlmzwx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2poxppvmq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbodtta.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzunmect.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2avbsntoe.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxwkpyq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutsgzcl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqtbihe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwafxryb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziigehrz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gzztasqc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gztfpfag.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdeismu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qpymbutv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmruwqp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsnnawa.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pealegom.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vlepsrrt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqfoowy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhfimrf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gibnonzj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xquenhps.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxigfdg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rndrosga.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2esbawygx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eheqfndy.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gngnoarm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mafphitl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2msrvmkuz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tioiqvqd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmxirsf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wblkrxkp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlkkzzm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qivlekxs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiqdivt.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zqirxjyb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmambco.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhzmzgd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyvipbe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjdwzsj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywokryhh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2axgpicyv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmxwzpbn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvthfrk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fltmhhql.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ucusjpuq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2olgyamzm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tohkggyl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgijhbbe.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjfulzn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbfdhd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uukfyqxz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxlnwhd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqzhvad.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhonjmv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjknhgf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvctfqn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoexmkm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2phgxymum.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2djwgfmzh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mslvdmha.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoghskz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnkxwjh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuuysne.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqrksbv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvcokjh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoayqzh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rntnnwwi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrrdccs.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2amwwwbty.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaxntev.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtnsoui.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpxigts.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hgziqfpi.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrdxmfw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xayzupcq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bpiymruy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2khnfsjrj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtoyzhp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2scxejypf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fxehqtba.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iweshffi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgyclre.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqzmrvv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwgxhvz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vaaamqlz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjsripv.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqbwmbf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rasdnfwu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iwepgsov.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfyfnvs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmgluir.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhowccd.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2oprjxeod.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkddfkeu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pglcexox.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjjqwav.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaopxbbf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uljooubm.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmmdpiv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmacsyk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfjqpgh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomjgykk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2galcqonj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoarzkj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwauaoea.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iowyetnh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfuxckn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtaczrd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mubshwbb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnccflsk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaqshmj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfxcfos.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqerwst.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoyxjpi.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwtadhd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rbskfgcd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnkopkz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofsjmiur.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yluccjfw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaedklop.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2lenfwexi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnmpnor.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyeyfwc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxslsvx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ipespcdw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbqkiyc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qksoubjz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbwtlah.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dejoacjo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zaevmbqn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zodeydqz.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvdiuxt.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgehlkj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2kgodputl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fogruuin.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2odzuguha.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2epupcbba.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nizhbvcw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoffeea.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoltldq.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2esnmlpsm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pyigpvwf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxanjmk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2exeotrfe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2femluywj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slikoyws.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tibybldb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgepcvl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmernsx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gixierou.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zehbyprn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpohzcn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dtairkci.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsmvzrk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qscuxwdc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bvftzboy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdvvbep.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dyznspcy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwzooxe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2rylxupvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oliwttzg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gbguunfq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhhhmvd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmlbjro.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cvwmnidy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsytipr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iouutcze.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uerldnyz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qrepvoex.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2axmsoivz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxkckox.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2khptauyo.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pdgmurlo.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2euqmlxux.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmuaugx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hwaiuvje.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wptmjzui.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kjajffiq.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eizgyxwp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pleeqfiq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dkksacow.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kablzego.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ykafqbmo.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hcthsssm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zoacqezu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xunahbxb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2scevqqfj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyimkjo.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfdiyfa.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdukdaid.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2drhczqjv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvpvmao.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oumzilhq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkdyhfh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ylchatcy.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfjmaxh.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwnwcuu.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fpetezsd.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2usiewdpv.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2omyywvoo.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnieatx.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbjvmmv.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2mruqdzae.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqipsvx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwkmtst.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2camimyrn.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2juaqcnpo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjukudm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkbmlyj.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2erhwuhek.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjuajwc.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjfzyhv.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfldpvt.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2kszrcpes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnzmhzm.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrmrcvt.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmgzuvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhajcp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zepkdmny.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2aimqkclx.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2avtadrjj.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2utcmhdgx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2oyvuysrm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2nlltakhi.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2tarbrvob.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbfdluk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpfaszs.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtnhomp.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfzbkyu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuobrzj.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyojcfo.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtjwqul.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2uydahkxz.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpufhgwd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2lyepwprf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmdmnwi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2huropuln.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2pysmlxbt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2rorbqayn.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcgrmxt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qejcxqsc.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfysutvf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkupkssv.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfulvwt.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2neroophy.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2epewmyip.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2preldjoo.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsascval.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpsfolf.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blpmsfqf.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kudcibhf.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubbconcp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2awzrzqkw.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfmhwlu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfytghlg.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yywfasvo.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nccnrjfd.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhiguigc.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2enunigkl.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wakmttul.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzysubqp.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdilkvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otkfieiw.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bjguoyrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bysadpst.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nisypqlh.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2npuljxqw.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qavpusdh.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfvjtuk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtklrqng.html


<!-- 参考信息 -->