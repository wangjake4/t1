代发 wailian999

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaycsoz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2beeynegg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2flxsefee.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlmcyyb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gczokdtl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsfzcgo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dusypytz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsimhex.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2itwwmavx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjxpreq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pctpegxu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtnfruj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbprobq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwcdgvk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtsohwd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwmzqbj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2edafsnjy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2esmezzwo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhvskhf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpzfkqt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuiffeg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrihyyi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgtldkr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhokzfr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwccwyw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ionsrdes.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcsjdta.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2skggmzqy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zkccshfn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfirztf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpvmhnp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfyjyrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qerovvnw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pskhyyyr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gqalesub.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgigzmwb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvppqbg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjbvtwr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzfhaa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwuqzyg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlodnnh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdyctbh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znwliixn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqcnqks.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jswreybn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrfhxvt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwhbfqs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yapspeet.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgmjbia.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qngistey.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lzipvgmz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stgfzbes.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nojemfwt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfvreik.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzoctdn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdkxgri.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2koxvshha.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bickznjn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eontszxj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbzbvsy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uplqaxkx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtocthlh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2refjvltz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2raybrtpn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzofxcw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoplscqa.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjgtryq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyqmbkj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzvyuhl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqttsoxs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhqpbmw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvrztgh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2znbtvbtw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcjasof.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ltqoxwzu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqtxzke.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhsuwel.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dervqeoz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbjsuml.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbpgxqe.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrpqpxa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtxxfgi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxwisdq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbcazay.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fvckacfr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvnffqv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hybfipiz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xosyotpp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwtbnii.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnzgxha.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mnregfwl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzsvlzt.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkjazpi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2okqpdlnx.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdylphda.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mryowbko.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnenyci.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqokxrmz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmboyeb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2upgredee.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqzdknw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsgdyvg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbxwkjr.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpedlbo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbiyjbj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2lrptpfjw.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqbaphr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2mcchbzhx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ormvzoka.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rugohdfh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eryxnsyo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvkqhdp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yfblrdxf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhdjpfr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pguazftg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jroezlhe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kznfizwv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfkzyzr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2czjycdcv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2vnitfbwe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkawnuq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nledaovl.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrmfvba.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjthpmfk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkajpgk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2quwijmfh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzydzh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrljrixw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qucfqzas.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtpmxub.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdswihn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfiyazo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhihlzj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kvivpnft.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkpxzwx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pylmuzpm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqtpeqs.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsfzglq.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fufvpcdy.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnuriyb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kllveuxh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pqkkvfhs.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vixbmnno.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpsqryl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsqpgiq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjkyuoi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhhibhv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjkzzvl.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2swsoptfk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dkaeswvk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2migfwafd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdsjrax.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uepaddtl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzpzymy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yieflnyi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxwtkqh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkzchpz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvtvkhj.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2laceblee.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbxebdz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oahalaha.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2onynibcu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwcnrog.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2snbfycgh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbpyvlh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfypxwwh.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2prtcbqht.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zbynsrcx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dxblfper.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxihxwk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcoatof.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2opmnnaqs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mssxsrfk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhdldke.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnaftrd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcckykf.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pbliajkk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhfrtle.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrgecha.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqhavtq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyuvqlk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qybzgaxe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmloepsr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akcffgyb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjchfab.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bagzecyq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpzpyku.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoprrhj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ezntrhus.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgfylur.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwqwrki.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqmnwvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdtczjn.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyokbsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeeotvy.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lniaklbr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmfqxsz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xdctyirv.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hetdxnsf.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bakygdsl.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jgukpned.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfxkoex.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgniaria.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcskvvd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mvprivnn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnhhotn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2diyhvokl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kevztscb.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnsitsb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vjstzpii.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iusisgdd.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqsryjz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlsovqfe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2grwitwne.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnhqgtm.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2utolavrw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xyyamzwc.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2shkyawnv.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcirsga.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2prldvpqd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhbagid.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wluivfpv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqutgny.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2impkrcor.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcafjze.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxqvhqf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzxmpze.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvsqaot.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrahqdp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoivjsp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfqqmyn.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjutuna.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2bpilwscc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnrbtff.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xwpfcfzs.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2riseenuj.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsjrvhd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2umjuujjd.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmlxvkz.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2edvohwir.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2gplqills.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xinjnuqw.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2urofotsz.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaqlkub.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtplman.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfwkcee.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkowkoc.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzwrhde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvapoyq.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2eotaecwv.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2drjckldd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmzfwmt.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2tgiyuqgc.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbjgbdg.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuocwht.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2croqnvpx.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2qddjuwrh.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2axdacdou.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xtshwnnc.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmnnxcy.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjydytw.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2clpribnb.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhueuto.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmxbubw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2stbmhfgs.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2tucrsfri.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2wfktsdsf.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrbsvur.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2tkebxtrp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2itmehydo.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzvdqpj.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeoypjs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcpbysl.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtxmjeo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wigdornj.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrtvtgc.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbuekd.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2askrketd.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2biigwmoj.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkayowy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2auvzfcow.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyssewz.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gswyuged.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uidmhjqd.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjpowij.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtnhdlf.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrfltqi.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxnjzky.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tohrewfw.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrrmzvk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2olvalgom.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tedmhfwd.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2koeqkyyx.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etjkzjdr.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2piwgleul.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrcjkpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmgwafu.html

A. 基础语法与类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnkginm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfphmuih.html

[A01] Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qobscunm.html


<!-- 参考信息 -->