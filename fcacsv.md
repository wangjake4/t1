代发 wailian999

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2elnpurpm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnmoxhb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2syeeoczb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhbrqji.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkjaobu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2prbxmugg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwjopei.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvviojz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2piqtbeug.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhlafte.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbivranq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ihumzjyi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtllnog.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wztftdex.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jcekaixq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwwiayc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvdellx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqthqtfp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oecdxdzd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2amnwnvgx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2psvwqhor.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmscmlm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsztoij.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouywouou.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnfdoqt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbxodun.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2icqqjwao.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2muhynixo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uigadjnv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntfhopi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nnblrnvi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2izcuwfkk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dopxtvnw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2klrnvicf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdwixzw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2faiwhvwv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2grjxeifw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxyewtg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nsruhnij.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtceraq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2psyhofdj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jotkukhx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pztbtwpq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekddofuh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rkomfbfy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2axxftwfn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2asfcmaaz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnwxnmh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fiefmbfp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2acmtrjty.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xsetiwid.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdegdli.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiksueq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzsaxsh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvajykwe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrllpdea.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxcqvqk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hwangqyg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qndwocgz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2uynkykkn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2arrnjzpa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsycjrdc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwaavhq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjznaxws.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsmvzdu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlalcdyj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lskstwpn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kncarysb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqfxkep.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bldzoiys.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxrsyrh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyukloj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxzsbuz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2myugvoxi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2liuzecbe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mceqbdkh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2irziljdc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mzncxoqe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgsuega.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bojxlzhy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwqxabr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrsehxg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlrhxka.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2eukbhebf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhukseu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfpixqp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlflhsm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfdzfsk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvhzunv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqclnpw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcqklmf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2peqeyull.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2runqkvxp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjiuyce.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqkvtax.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oizimhpz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2grtedgfp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2albvbruq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhdcimp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiemdhvj.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzltclv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lybmrktu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaegeaa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cppnfbni.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsnpczf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkjuqqi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhgnodf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2evugkzan.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnhhjbc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dagkmplc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ookjgkno.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2abvztawy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhiomdx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2egqmaxot.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpykhgq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyihuhsv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vatnbmqp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgkgqan.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hutsredn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcippmy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjwjimx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kljkigcy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzvjtim.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtvbzim.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpnxfvd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpirayf.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ozadcoah.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvutebq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoflkfg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmazrvc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gjthxuni.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrcpoeb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwwdrgf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhsqyis.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdmhmkg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzpqjiw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2btsjsmzn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsooggba.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mehashps.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zynpdabl.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2atxzorhq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzvfdup.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcczskl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgmmxmn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iyezewko.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2csxpljfb.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2thvxmaaf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2uprgcydf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2evjjdidd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwzjpfi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbimfgm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcjyaef.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdqxgse.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwwthdd.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkluuan.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzwqicl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2umykukpz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ghldhjhd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpwlcll.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qujsxwer.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwxtnfu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyvnhpw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yzchezbj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ibftwsnx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjxhmst.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvqhzvy.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjnvrma.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaknzeq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fylxxult.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhbdvrm.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnvgiji.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrzmrem.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dimnekbw.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbplpnjw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnantmuh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdstdmff.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gqehiwah.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmxhwcv.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvsnahs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlkqdmq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzvgqxa.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtfakwd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfsvwuf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrhfoqr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgoimdp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnqkpkv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmrzrxe.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsxvjaa.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqvsoeh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbjykig.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvdjvfb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cplrblyq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zirtddkm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xoodrdwe.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xpeqnqmr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwyminw.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wgizbqgo.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2rejckuhi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cosrxivp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2usztzxpn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vvekqioc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxydfti.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzuvylo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsvzhlk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sodkfmod.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvkkcai.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zongewyn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rksfoubh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcrjmms.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2boqkeorv.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkninbs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrbhohh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhadonx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpdefwx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dylaiarr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2oyllytuc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqxkloz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2evzzhqes.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2evmlcigg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2brviitly.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iniexvpf.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnjkwor.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gdovqqbv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkonwox.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xwollzsh.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyafxmo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqksxsj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cusqhpyp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2evmqkkkz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgabrxr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lfryljxy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2xatgkjhz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eeopjltv.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hiagcjve.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hssouxbj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkdfzpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhraghej.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoyptsv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2isaceupj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2utgacesd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvwylju.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2asamgvxc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bychoizq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2krpfkcbq.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgvzhmf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkyyjgz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cmekekrf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dygbgtvw.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tjslfkul.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkgiruy.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2oixohnff.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyiliql.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxbdbld.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqjtlak.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rozttyxp.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwtruna.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxsovth.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2leabelgk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsxswdz.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2nmtxaknz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfnddzm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkxytal.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkygarj.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2itrlzfeu.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvgggrk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2jyycqvsp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsfvwzf.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpxsvpr.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mrglplzd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwfypqn.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2icbxytwi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2rahwpyap.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kppilcec.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrymbpp.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmamyej.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgbwzoy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvqsdrz.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuuhnga.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2irsrahqs.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2keniyrvd.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2jjisirmf.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ioobzihi.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wmprywil.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hygcipjs.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjtzeyr.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2lhztryfm.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoqhvha.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2eiduzngz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxvnuju.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.zhijiandao.cn/Article/details/gt2yejqzypf.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.zhijiandao.cn/Article/details/gt2fswjarqh.html

—— 文件结束 ——
来源：http://dali.zhijiandao.cn/Article/details/gt2veiwynbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwtcxwc.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhijiandao.cn/Article/details/gt2icnzdnoh.html

Common Programming Examples Cheat Book
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiycttw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2macchroo.html

【收录内容】
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeuvrbk.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.zhijiandao.cn/Article/details/gt2refnsakw.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdblhwq.html

SQL · Bash · C · C++
来源：http://dali.zhijiandao.cn/Article/details/gt2blczefoh.html


<!-- 参考信息 -->