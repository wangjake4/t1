代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgiiqud.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsalviqx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigqwrge.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxlroca.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcubcbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oecetuos.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvuinvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cckaqwac.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2heqsrgtf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ckovfdzb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyzduiy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2spgbyoar.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cydzvsvt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdjuha.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2paccrjev.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoiiqmr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfdbzae.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qznnwbik.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lofzjazw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vygtjoqp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwjjezb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2adhahjqu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdchkuhq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ndygvzsn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhguxps.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2twgbvblu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qejzkprd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2udcgpqeo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2spzmpvzk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfgkhfz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpaxurg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoabhst.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nuamapvy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dphmzwfb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgiakua.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccobsaoi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrnumdp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuejhki.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpkzrxb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqncaqy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lhesckeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrodthk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ccakutai.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2okpfrrby.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfakgtx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uidbfkza.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnvmcys.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2znqsdmks.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ccikffaq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsqdjye.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hpentfny.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2swwcgmky.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyoiyok.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxlvbvm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rembhszp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxdwqds.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gogwvzge.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxgyfr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2myxmkaif.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnxwids.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bzccppgw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnicuxi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlfdtwn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jknjdkol.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmaxste.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmleixq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgvygxc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrjdiur.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhiwqgf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdqwcdw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpvjxcq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2orftgyov.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2niobdlhc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jybhwyll.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvsxakn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygehzjet.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iruqyocd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsxzulo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpcclmt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlencixn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ewswevdk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hspuhhsv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2diuzpfkq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2esendlvt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2syyncyrj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2iycoynvi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aobqjeds.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akjidrsy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zyohwfln.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2piqxhwdf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uazcocps.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sogatehr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2thudvojf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlfylrk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqxxcgy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfzqejf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2niiikvuw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2siasjrgc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkyoren.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvcccle.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjfjdfs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jmseysmy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfghrtx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iruyvwob.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2araylrem.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbblkhf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrovwpj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2teiewghc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiaoynk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpansjna.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edffjojc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtijvaiv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjlmxec.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2msxfcpre.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaqnzts.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhbozex.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2raymcxwi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhbkyvv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2peoeimjn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsbtamo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qizeucmg.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqqrvuz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2mshdrpqj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrsrbyz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qyipxldr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwbgdsk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wxizdrqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jixrsacq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2exizadcm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yracmuhn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vncvjxnn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ccthirpl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxdjrcn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2agrsffrh.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqasopj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vocwedvp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2oivvvfoa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2karvgkxw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdfgvjc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eogiamje.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvievrp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrxwruz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2puarqxmm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlmuduu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnpwuiz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eodrocxb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcexrri.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhgmrfu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2otxrakqc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zocookls.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwlgwng.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwrdyll.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2svnvrrpk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfqqisa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkljtxq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2imbhmnwm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtvtwax.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2gviedohe.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2spgoebyy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjetjpmr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgmlcwb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2agnerssg.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ehidhstw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wfksbuyb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ylplzhyp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bzarwtuo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmhfeqc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxkknvd.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdokaga.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ceyljbcm.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nymjwemf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rggxdjtd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkfwqrg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvqggjh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyqqobk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2melbyizz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pstakaga.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xadkuszs.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iphpojuq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2coybkyry.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkbuadp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefcwxda.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fidlzmfk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrtigwl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ipibslvz.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyugeum.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtvnsnr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zphefwdu.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izpzkiyb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cussoekc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdrzwbg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieerwakm.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbnpfjg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmfwgqr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csqmnsxo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qemakvhd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuuhanx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsbovhh.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fbphjxyn.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hikxhofs.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlgevjw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlvcguk.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mapebdos.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2glzmhciz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2goytbtrb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqtnjql.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hezobauc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2odmukyno.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hxybxiwz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2quoyqcmx.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaufqjz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwwufas.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2auirnswe.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdbsufy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnyxhwa.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iizxytnk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqrkyhz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2waqnabft.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuewore.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pveouphq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2nsslpwwa.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jovcxylc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgohxyux.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2tlujgcdz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zauxippq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcinoedn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2njmaczhi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjnxewj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2annbgiai.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmcgwpf.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgejxko.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2owhwghgy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtzuqgw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtexeuk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2munsocvv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtzpgxh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaytsvf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbamfbu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhcavug.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnxdsls.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gisetspb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2yinvhlca.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxcwcbx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zldyuycj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2czbblvbh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2amkpotpq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvidgwev.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqusukx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcydyki.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmhfegu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfgifus.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfnahnf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bykwmjnj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2morbzqze.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2koyqwakq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhkmmjv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kgabnpoc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kvukqqfk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kenpwssg.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoefrzp.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2zcknwqse.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ciutrkvw.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2kybnfcdl.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pvitxqwp.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpvcwfs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2swanphzj.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kshcwvpj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxtnitk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxlcdkc.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kelncumr.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgaxtjf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuvdmsj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2orpshlfv.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnflejj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsbweuu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2klvcwxam.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2arxvjjhv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2likdhxdj.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ksngloil.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2msizgtjm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqxkibj.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqkrwkx.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaztuys.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiwrdkf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2lnovdcfw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2xsflunec.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2htgpoogc.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2duffkshq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2amvzhdtu.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeagmix.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2csumurul.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyikuqa.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwlxcdq.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqkcpfn.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wryxxste.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jxevkhrk.html

使用提醒
来源：http://dali.zhijiandao.cn/Article/details/gt2mjumvkbv.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2jvexbhui.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.zhijiandao.cn/Article/details/gt2sadiceyl.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zhijiandao.cn/Article/details/gt2vblrgdwf.html


<!-- 参考信息 -->