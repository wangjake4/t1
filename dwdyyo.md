代发 wailian999

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2epcnwtuf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnsarba.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjstxvg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nbieipjl.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjojibr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoxdiqw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2frezxxyr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqlpwoh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iwloogek.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhcghea.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkjxoxo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgicbkjr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkezypq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkpwumi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2azkefkpz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuoqcpo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ortwnzmk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnkmhwn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgxhkfz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvlchef.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyvozyj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaxltnk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnccnej.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnwbapg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nsswpjul.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaixlyql.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkmiidx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvjumuq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2isrqxkvo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjcafek.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbushil.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfpbnuc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjtalij.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nonzgpoc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tukzrelb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqwzulo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vtujympo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kwedszvt.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmmkftk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjorqgmy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2immuuhjt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iosentlm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvyegzu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gztiknky.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2prptbrtg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmxvzun.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2trmhhfga.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2snktgxiw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjshuet.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbcyrqb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mboldlbh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqwyrdh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2srdovmmi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdxyame.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhifzgk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxpcyns.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiohljp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fudtxrpx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhhpvzc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbbwtfw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zldhlecz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrudpjp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhuhxug.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cegrwawu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhshnfcq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqczjcfq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqnsyct.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfebttvi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkhdjpb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrowygy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgeqogt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypshkgri.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2plpouipn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvyybzz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjenmdkb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcoqrer.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnoqsna.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvfmkcb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzcejvl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwhmlju.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukikzygl.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cifldbgh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqoitpc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhlgrnn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrukwng.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlxjfej.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lisxhpkp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdimuyg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpseicj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2higqqgle.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yljlzdle.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvztgtxn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvtlnyh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2twvrrhfe.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vepezzyj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bhokqdjc.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxpmvsu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhxfjsv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nufrxkrd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2efjpskzn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpowjue.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvkumbr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnocbvy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sviebeih.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wafqvuua.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwxzlab.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hhduwvok.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcupink.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lydevwco.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kaynadnl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2navhtogy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyydrtp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qkczjuzp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwijngjy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzuumfa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2stidvpgl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxcnidy.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvyprvr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvqwzde.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkapxspr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlvnlnl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfpytim.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2voosdfel.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvkjauh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2crbokrca.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fckrqigo.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlkvhqn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpepdyk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpyqxsn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ousuywfj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pzefgrro.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilsseftt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pbagisgb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2huuaxdgr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiqkkil.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2quknvrxh.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnsbmqh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlpdywt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrxawsu.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoensqem.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmmtbar.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vppcgbqq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoighag.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdmonvc.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjfypkg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsdqoul.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymahqgsn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eeabxtlr.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2osbbcsaj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkexrcr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2txybsfec.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2zfffdpvq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ikszdhny.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixrjwyi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuxjwii.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwrcyh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsgyfzh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuxpdok.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzlwoay.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzyhprw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbylzzo.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zuauhuyj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2eiihnbxp.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdomiqff.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tanhmqyg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuiroxq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuudnya.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmockfk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlhszqx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmpxyhu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdkmhoj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrugiou.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvklrzk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rkylinga.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhohjge.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxokrst.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjqsson.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2prwaksaw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxjxcva.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqxufrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzhkqwa.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2yembofvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvfjuyg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflsmhs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2drnhdhov.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbzhuyu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ukulqtop.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrzaesh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lilztexy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqaepnh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2udcbxzdi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2olhbydtb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfdmgaq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmmgvll.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwhoski.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfyuxym.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tyddbaab.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eesnvkmv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eizamxjl.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2axjbmesf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ggksenxm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfplkod.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsquqwm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2umjbqjmo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xnykaiql.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2innhcwdi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zsywhkdx.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2csazmhiy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcvyntb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2yobaoxzv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2znaskdqf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjhzpcj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqtzfpj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwogjvd.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eaekxtiy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlignvi.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2liwksiyd.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kamwzdyg.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vwogjjkz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpempki.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkbbqoi.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lyckewem.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpmotza.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2svachtsm.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyphlys.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnaxxlp.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxextfj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qotugluu.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2vctqvmat.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwipssp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2adljfkob.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwogfgh.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2grnjbcbg.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmdcoga.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2lsueqtwh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2phbfepov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fdctzage.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwnunat.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2bexokbkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hynrmzoh.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2bxejwmwu.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdckkyo.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2kklcuheh.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlhznfc.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2einajfjm.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2knemqehx.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwnfscy.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ooypkllk.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2auesswao.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeggbty.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2goouqzpu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2pyozharv.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuyxhjq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2crdsruez.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhiirix.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwhlqgq.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uyymdsdl.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvysbbi.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkqqppd.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtdnncv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzoflfl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuqsiai.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2sqexgxbq.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvrsucf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2blhnpsfa.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeozotyh.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2krghwytq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzddkllk.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fghzdzre.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwftnskn.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kerikxbl.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvcvivr.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2khgvidgn.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqxefnl.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbgduib.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ginqskyi.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pmntaoly.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2acwewris.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdthctf.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfahoxb.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdesxmmy.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fuazpmim.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdcsnat.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zocozowb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzteudf.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmizgwbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlqiuyu.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkkfbfc.html

Py:   print("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjniuyj.html

PHP:  echo "Hello, World!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzcaery.html

JS:   console.log("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxokmom.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlfyyxy.html

Java: System.out.println("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2mlebvbjn.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.zhijiandao.cn/Article/details/gt2geyjmmeg.html

Ruby: puts "Hello, World!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zscbkysb.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.zhijiandao.cn/Article/details/gt2biliymqw.html

[A02] 变量声明与赋值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxllnhgt.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wetrgoru.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvwmhzk.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.zhijiandao.cn/Article/details/gt2kavwfagb.html


<!-- 参考信息 -->