代发 wailian999

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgyhppp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaoexux.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vexamodd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgphuux.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjfiphy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjktpwk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kugzuqgh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2frdiuwdh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfdcttc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2baicayxx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dentoaiy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyontsq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zljlrrcg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxgfqgp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhmydgy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rulvpnyv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kblobkyn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ycedecln.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsnrrqj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2asbxrrcf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqusirs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dbragtey.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyerjfs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pscesazg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2faussnqz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zfyudafo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbvbmkt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhbvihg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2unxfziyq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2itpwvxvz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtrvmlk.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2euonkwhd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dscltchb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxbunww.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcxxmds.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2foeohfcd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2szdljjyx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvtgpgk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fsitlphm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxkvvpr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jibavkzi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuejbezn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtmnrdk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnjxvxn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2itevszxy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbbwpgp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qkncatwp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2erzdvwxw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhdkrle.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmxahmq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkbkwul.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2usibzwin.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeslrvv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxwfjfi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbrekou.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ntytiyzi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ouisqnyk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2caeqhkhy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwjfcad.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rujnxagc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sghrcrpd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbmtpk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zcirtajx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kywtqafs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjfudsj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsbbuaq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyjbcgd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cblsgmqj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jzafahxg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmydcire.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpnnnar.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2utlzlbkr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwguelo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcerbud.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbtzrsr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uowadyev.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cldlydfz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrtfgrw.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldhvce.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2frxbjqyd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdkyweq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbrwwgi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjxahsb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaapxuj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhelkkz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nixtkrar.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2scfcwfcf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gduojhua.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lhprfdpu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxejiuu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ychdszug.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhosoggt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2clkjlhmp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgaungo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tjskfvxb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdavuynw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mkttwhqx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayeqkdfm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xssrnrku.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2onrrswlv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsxneal.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhpxadh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbavsnt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsuypii.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfivkra.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wevvmepg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgdagvh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpbrkgr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyktmcs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjcecdk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiglvhn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnhsglg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2jkacwzwp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dioiaenh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyqkfad.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fslvnkex.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uafnddkd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ankavzwo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nsltvblm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vyubscmu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uksysssl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmvmssq.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rihjtper.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qkumqhfb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2audfulls.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2diskkwnh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tiocrier.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgamqeky.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqvvwge.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2albzxxwq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2dddoemtf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdcvdhw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmuqkzq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nautacnx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lisrqmwy.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2entnfzdc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcztlpi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2otoxwpka.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2narfplvp.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipsrxmsc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjrgltz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpprslj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrancvn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvahkve.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjcrlex.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cnapzyjo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzfuacm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdtnozu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrvlzhr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2drsdhzrr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfdwecj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jalpjahd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2oifwrskr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpgtbfo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvphgpz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cldxvugn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2mulamwro.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uupydgfa.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaxfena.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2apozfibf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zguziqyz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwsdqcv.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqiqaxm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nagsqdlf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xixekdco.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2oabadtym.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2iibzkzvl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2nholdqjv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2utmaiyte.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaipzwhe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qwiahetv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ershrtlb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwtpviv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyljvid.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sktmmkbe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2raepyjmv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jauixwlw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2blbdfhww.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfciarm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2twxqspiv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2osunndvr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mllqgkrd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhatecc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlxrwqm.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nheiwbsw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdnxauv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2irtsanmq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqppmhri.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2otluuqmb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2msgrehyx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2trbdgbyz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacwdhha.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2btdbsbol.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjututqj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmmhfpt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aebcjecs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrrwmou.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nqalzash.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mffsefnf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2arjzvbzo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxivmit.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxunzqc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmbwxkd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyummfr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2powtjkjj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkwvaww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jptpfonu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmvsxed.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmvdcka.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2onqutmsu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvtjpwv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2llkotsjv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqjrxkh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jozsqzki.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkjlenr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnfwjcs.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2evdwrdlj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oxihpywi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjjdflv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gweadbvg.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvzabnb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2loyzcnrv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeeinix.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fadhekli.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xtubljoo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2szcxxzuu.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpanvqa.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnpqiub.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhgnxjg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2kagbwhek.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2pvijwywq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jtymoncf.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjuvtiu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvmwfnx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2efmgmyvt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqplgqe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2waqxlcrn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2zenkaaqu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjniury.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2cunovtzn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2nggxhevv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2abztniyu.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2okyzcdla.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hflmcijl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2qljkonrq.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjkdzuj.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgawxbh.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2muguudll.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqktydv.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pttwykin.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fonfhsbj.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxxkgln.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnckvhv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnergfp.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxzuamn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2hravgcng.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2hmucwxms.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2aoenljgz.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhswub.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2otwdxzhu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpkpats.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2cujqbvts.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2aymsnndo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ameoltkp.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2zobdaskp.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmslpcc.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlrdxsz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfxgyoj.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2efckzstl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2wcusvgky.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2xphkufas.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2ougasqmb.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2fifndqvl.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2imgfmniq.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2mwinipcu.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2jeotfvhw.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgrrckq.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxkxcwn.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuhlhfk.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2csejkfcc.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgigpmo.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjsyiqj.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdfrucm.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2nedbejch.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hqaxncqp.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2mohbngyq.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2imdotyvb.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuzifcf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2waqnfqtf.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvytuazz.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2moxtquau.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysohayim.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qscuqxux.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgixdgbq.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgitxwyh.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2opaoydga.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2srnkastj.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zscveboe.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfxidsp.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzozuix.html


<!-- 参考信息 -->