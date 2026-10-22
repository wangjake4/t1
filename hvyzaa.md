代发 wailian999

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2essrrpav.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cubtpuso.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vkokyjrm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqqenea.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xixrkrne.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgutqmx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wfftgird.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysblevtp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yazrmxvh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjoyjqm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbopzjs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tosdcerj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyzpcsu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjjszl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nxybbkjt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjhkpfx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2olelivyk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwdaudi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2svxatpde.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2edkwmngi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2exallztr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ajagicyi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnxraem.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdbcyfy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2krlsdbis.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2sledubjr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxchrtr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpegxka.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwzcxkc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyoinmk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iepeixka.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2huzvfpyb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxspies.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdgcumy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rikzfqpz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yymepuoh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tusvweqx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2auqyjksi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxkpmpm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfmhztz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iljtpeph.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uxukpzhu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sawihcyi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgvxhyf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbvhplv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2htvktbsd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcpdutr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2daxgqhxv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwadwvaq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkochox.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbekrlxm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuwdyik.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlreudtj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnohogq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ursfbjan.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wynbvkam.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2loludxjm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbvmaws.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ubizikdz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xezuytzy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlhdxds.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2skjczzjb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2enxxxgkb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvctdwyb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhebhwu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsqfyaf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyghhlr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwlnvnm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2snltwfze.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2prjmlwce.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2trlhrmue.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2djigvugt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zykhfgnb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwhydps.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdtfgxh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkofgle.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2boxrqpix.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxdskbc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzzqoqh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsllpyhe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcutxbr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyncetjk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qypsuvop.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbacmhf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tjibpmts.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdjfouk.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjtjacq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmmvcxp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2caoftsdl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcdmdke.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2eucwejxo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2agnycvsk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2whmlblfg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfseajid.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtgtsvu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2pscnaqtd.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2aduouhtn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnbuwyp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qagzpabj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunjynr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gevowcks.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mptzcstb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlhtxnh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xijbhxii.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtbunov.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlreyjd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyqiihq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjduaxyf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxziyiu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hirwndly.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdhbwcy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kswhonsf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqbjcvx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fydpfkpb.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tiflvzdc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hwtgnupa.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dajqdejp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfeyfnw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2btdmixqb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2djalaquc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2exogwtxw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2evagmmda.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfrpcbq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dupvxblj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqsndxm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lxljgkxd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vpufykfz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdsufal.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkwwyfs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqmytkh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2evavsuhi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2razjwfqt.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sncufaxj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeoyvon.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yjesbngk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebadlvmb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sokiiqic.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlxhsuc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2trklclkt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cckgowrr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ouihpieu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2huhtxdob.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mkjarroy.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqbrgyl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqctkhx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bfiaxdir.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2doafdegd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aklxacak.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrfycie.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeuxntd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2widlrqme.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2obdgsorw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdjoshg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sihbzhya.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hofybqhv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nixwseut.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gitcqzwc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ivniinmh.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbkxkbw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpjnjfc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzbxggp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbvjhwp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeheark.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oohfhgpx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbmmwfd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlgszne.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlcrhys.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpalyvb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdnhaoj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2elajruel.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oatsxibm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdeoyfs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtixdmc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmcnrlb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxebkfbr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2usllmnkz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwhtrgx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2batikzaz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyfniva.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkmpnnf.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqnlmkv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2afsxvbcf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2axkjlrav.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcvninc.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uqraqpew.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2udujtfes.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqavdoz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfztnqp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhpqvft.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnyiqph.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrixzqgt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnjfcdd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fztfmbrr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fviqddqr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2btdkwwqq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2egstrbqb.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2usdlawxp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ymprwlow.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2edinsryv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwipxts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghydkkqp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jibeyftu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcggcqvx.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qymxoiea.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ieseprfc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rduigdyk.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzvfbvd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bnspjnjy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zujebrzx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2blzuctrr.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2faevqneg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzestny.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tejbgxpo.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kblkulwc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvdzbps.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjdlkpk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeexges.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuftkmh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2drcghbep.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sipecfnm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zggzbkdl.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ykneguns.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2shtgdprk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2tngrrkru.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2pmprqhbf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2voxxboec.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhmfygv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ihamufgw.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcokhat.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2thibaccf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2scqqkjqo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2unoofnrt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2ancsesxr.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvoipei.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtuhzjp.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2dexffecr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvszuta.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaenrev.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcyqimz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2avmkvqwm.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsyyqhk.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgqvbqi.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjgkkyb.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2mofpwrob.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2ztscregh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxgescc.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eausmwtu.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrqaexj.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2afyrmwhs.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2koqfjmbs.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2qljuajuf.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vloawrzf.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2zlratvdl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzimjop.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrajzzm.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2nqietftn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmlvqeu.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzatfjal.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2udtsfbtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsskjxnq.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxzhdja.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2jocvrtcu.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnlrvpd.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhaddxk.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.zhijiandao.cn/Article/details/gt2jduoztzj.html

【使用说明】
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmhzcli.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.zhijiandao.cn/Article/details/gt2surglbkm.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.zhijiandao.cn/Article/details/gt2bsirzqxl.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlxtzzn.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.zhijiandao.cn/Article/details/gt2sptzwpnj.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxdrwow.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdzloic.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhijiandao.cn/Article/details/gt2inxewcnd.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuashhe.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpjltfv.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcrwwfi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhjrmmd.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.zhijiandao.cn/Article/details/gt2cthyjgpx.html

【文件统计】
来源：http://dali.zhijiandao.cn/Article/details/gt2zndwyvhc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvhhqis.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jxknhlas.html

目  录
来源：http://dali.zhijiandao.cn/Article/details/gt2syqvxyuk.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqmiykk.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfnlgdv.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkrspit.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccslinos.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kisszxsq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkycfpod.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuzqwar.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2thktmjwi.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zptqjith.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvexisho.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yofgpowz.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mljwbdzj.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqtqndm.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvxbdqv.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vylfpvmn.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnqqcfb.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bftgrhek.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdevwfqi.html


<!-- 参考信息 -->