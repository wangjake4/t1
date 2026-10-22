代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmrozxe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfsmjiw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpxxbhy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2npmbcneo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjtczpp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ddajqqsn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wukvhmox.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxpqatw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2duzmocon.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ludfhfcq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnsiysi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjgscjd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2frcgmleb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2boflpgls.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzjbkqn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2genqzheb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qprsndhv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qacgfskg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eschfodd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqjghrl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2sacvjvpm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnhixof.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmutgdo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfixvjd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrbndmn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zozhmevx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnfkhfd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dykilpan.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuxareq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsoirwv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtcxkxs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2czngjtvu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlxkpui.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdcwonr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdpggcb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsasjlv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfaujhx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgutggiy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2obbwswcc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqsibrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmcqcmz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kchhgdun.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmedeen.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwzozmr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2obghisoc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpencdk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2epyvwokr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2csxnrltu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hknmgocw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmidpzy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utnuhnjp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2aymaevcv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnzneis.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvmnzbu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kashorxr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orkfxpns.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wphovdrq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2husvtkul.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yqilfzbp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpbfvyd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kwknjybb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2argnmjli.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agifhygz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkbulgp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bztlanme.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dklrlnaz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zebufsfl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qklzosjj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyhxset.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xctdcsee.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pajnedhp.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhpenpd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dpobsgzo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsqudie.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zxumseyd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwveuzv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvnmxef.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvsmrdo.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bttqmagz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qujaxbln.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2notbxxoj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rojxrbmf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcpiycd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hebknyjt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vuyskwqt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcxtgsg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgerdts.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2eutdqzgk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qudrwedd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmbgeqx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2cztgvbre.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmmkaay.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pmithojp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfybrct.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzifdvk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoulyfr.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdmskcv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlpnbse.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tspeatzn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhuvify.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2clhuorzc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbwteda.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2htwlfegp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtmcbjq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkuusfr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2annedhig.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtvhggg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkucjpq.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhjzzun.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmqmydj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxylyzq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dssnvmkz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyobrgj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoqnieg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxjjhsk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zngrqpjs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2enzyjlms.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2egccjrtp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjjtcjj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmorine.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvzrgjz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbfvjfl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzaalmp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dshrnjvu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbfmmgt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rpabuclo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2citjzqtp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlvqrim.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqbrxds.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cltsaqbj.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnnmtqg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoqzpqz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zspbupdl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibydfcqr.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzvpvyq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhijkytr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2leqceubz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2etyzpolx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hssfplij.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlriilb.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzkxlsq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gieqkidi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jphaanrx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwfoqli.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qrktrpvb.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmzxako.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmurvbz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwxrhwk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zyesgyzr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vhijsoeh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgqnpua.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiwougo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wteekias.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxexhrko.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrhzqsh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfslmbj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpxeptp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2urgggias.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bagifloh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvcrtbw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ernjxfru.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cerdwgco.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfiguil.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxgjgui.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsfoqxm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2onihnwga.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2imojxdwu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2esqmotlz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrkrtwm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2txjfhibh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxdqbnv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2connufbc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qoylnodx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhzveul.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqvjfra.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzrizyb.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2agfawxze.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdbohfw.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2lnedotle.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hypjapuo.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yewtvkmj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2grgmlfub.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gomvdxpq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ouggprzm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2avwutfmb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrjhzhs.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmjxlvz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2llnvbmfh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqufzsj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcgkczw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jftszdfz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2viljvpqm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaacasv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2phncdouc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rossoayv.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2szdjikiy.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpqvguy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2sadexumu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwqncgj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrehgbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otqzqlvi.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oauqckpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxbopul.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbcbone.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cttklhss.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jrntjzyt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fittbyzp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lienwukm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ngoudxta.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhlbjcr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dolvnbeu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtgfnwj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfaxcvi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrrpjwu.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrflvhn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ouindlao.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxniqog.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2trxxuvqj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuhrfye.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2umpnpabz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbgaxbe.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tuemqwmx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsjrojg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mruhgkwz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hdahgfhu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2oddzyjhy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vslqajrt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dahysbhw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uumrmevq.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmxfuhq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2flqvjhhi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2wgelutav.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2koadizxi.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhonuxf.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyrigqu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2tjngubmh.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfeyenp.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2zanerfsi.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2cyezauvi.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2crdebqxl.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoykafm.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaqitmv.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jfadvovq.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxrxope.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyxipnz.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzcyile.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdrjybi.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsiyuyl.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzbigbt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfiwrhr.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxehxyq.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2bukjfrkv.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwxmvid.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yszkfzuq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlcmtee.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2iparqiif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqktyyce.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpvvak.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2njcycwdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcberhr.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pnubwbgl.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpoboak.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2laznmsoz.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ohplloqh.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2doqkixpl.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyhrblv.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyvndfm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2jeipfvrd.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2huiosyyh.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2lalsvwtg.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlerdoz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqhozsb.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlkfgg.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2htrckzwr.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2uexiebxy.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlohrxn.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhbano.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqayfpw.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2clkwicdx.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2xabjalfv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2inogfcbt.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsudsyx.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2cfscycqt.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zduqctsi.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiantnp.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfbprwx.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2byenyort.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usiwicyw.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzqyqhb.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mshgnaln.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ryskkgun.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hofpobgm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaasqlki.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jsydrkho.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqmbgdk.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoowrzu.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsflqsx.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxnuxzk.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nltstucc.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgynsoe.html


<!-- 参考信息 -->