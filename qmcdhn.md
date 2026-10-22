代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2buesfynv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpmclue.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvixufv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oefbpzcq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgohcbr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vgddctvb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxomggfh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cuttsrml.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfffypy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyzbsno.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmlmsji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcvnokn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lixzlnch.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfuivqw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2waxvptpb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vbimtchk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2atkrblkc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqnzhpe.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ogffbhko.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdjkfmm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xpquevae.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fsifwscl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2giqwyuqo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjrgxol.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvwmdod.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdyofal.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vuazztbt.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2opvyssxa.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2leeebsfk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdojckj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ainpzczn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2velcahhg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rujetgmn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtdwybv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrwngyu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtvopc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntpfvzky.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvfxgjz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfsoffxz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwekret.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cgjhobpy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2njlbpjih.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzdgysl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptivvcor.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uppdtjql.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2befavaop.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpdinrv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zinnvtvf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwhyyyk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epvnnska.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqdglbm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsagyetf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhmdiio.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wbexqyol.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jffswgvx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvopvfrn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqcvyai.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuyoufg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wodpbgum.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrgpnhw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsfkfou.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aygffsoo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2crytlsoy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlhwuie.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2whbxdosa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ickfgrnp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyibacz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2poxfreue.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ympyqgkk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiuvtkz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjmweao.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbnaobo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pubylsvj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mturybgq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkpeohc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2azvlfjjn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2blqrasak.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbnioua.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2leshzfzo.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxmbynv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xszertzu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uernayzp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fufzdmbj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqupnwf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsgpimh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2atcbityx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmywdad.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnfbhcz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yaltksmk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oozwrpty.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2foialwug.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgykyvvr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xxczvlcf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2knvpizzm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2anzacpvj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fokyawmf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2taxadmqi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyymtrsg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndohbigu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbtcexi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziabkqop.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2funqcgtb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpzddxl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hncmcrif.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oojpbhff.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbuddep.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nggcdkvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiadmotf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsdhklj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ncerenyv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmzzmom.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtlgbvn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wamnkcwy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbtnsko.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkxarif.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxgafqo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbbpcrr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuxbeiq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qskcfitv.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ufumtwrf.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2errtzvcu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwtasqm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkkucgw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzpcrkv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgicqpfu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxopaxy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvmmqvt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxxslbm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xthpookk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tusaxgzy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkjwtqy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2koxvymse.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nqycmeiv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqlcjdb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvtyxom.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwrrkap.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cumvdvjr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgsbafb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gayzxstn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cenijddu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xloshwvw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzyaoqb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2feokjboz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gciqfmto.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ldchovrl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlyyccz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jzanddwg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qszaiokb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2thfzgjfh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoiltpg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2svkvfskw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ficyawyu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqaiozd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjznurdh.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ltacjdui.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2imnyzkuu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqvojhe.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbswpgig.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urcssuxw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkflesx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbdlhqo.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fzizlbya.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfucxvm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjzvkwz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvvpfvp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2thonbumn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvownsc.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vktchogn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxpytog.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2robsbeuu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wqufzlpf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2tebnkxgp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dvynarry.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqipqab.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cbltirxe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jghcneqg.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwmfvfw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vetvapbu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhbocth.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlqetsr.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2oviujzkx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gviwcdaq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxtkjbc.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbeoyur.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfovhuu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yynmjdog.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2toaeqycs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2agcjiqhl.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhkeluv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2knuzbain.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cacgonmj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcoifdp.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnuydno.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2curswugi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2oyheyjou.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqupjftt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2larpqbli.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hmecildw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjnkpbd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmybewhw.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyplkif.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ccutikjm.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rflircdj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqppwbp.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gpycdcuz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2edrzuymn.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcwqvvy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2byfkmflp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zwumqsog.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzuggla.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obysejxc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2riouetvj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjtfddy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zekfceye.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdrnyta.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2heyowabh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lcapxptw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpasjwg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvycsjy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtllllk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpgoczh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svbasnwj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cyihdqel.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdhemib.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhynkng.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qolnpqlq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2liltbrxm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vpaojjjj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhnloqr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnviakpv.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nxilfcsg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qolxptae.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjhpulv.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzmsnyo.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2upitocoa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpxclhr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rshjpqmb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhrolpk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2opgpaoms.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvvkvra.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2admscuof.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lseeukdb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqpqohw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrfoxwx.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgyxvxk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kxncvomq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkasdwq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrpoewf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2likslssn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjhiinx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfhmxos.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2mptphkkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoxqdzc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqyczmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrtzixl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eplrbekt.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vpitprrp.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxcukow.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fgonamjc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2stqemqiw.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdebli.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzimdhc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pybgmgkf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmhmcti.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mwthduvh.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2thcngduq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pzswgfiz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2almnysqc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiraqcq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjjjuiq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxlohue.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcatjo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ophiqnfs.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2peynqcok.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdbxplo.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnfyhuf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2sqylhezh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rikyesbj.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wauezomi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqodofv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2ueasuzkb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxqxbrn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsndbyq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuekids.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2kydpefyn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fenvzgbe.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrycxeq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2zikdcbms.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2mndxemfi.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2bwewdkpe.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiguqtl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gt2svtnustq.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gt2foxmcvlc.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gt2nxluiach.html

S C / C++ 专题                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfgjvut.html

T 其他语言补充                          60
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbczzjk.html

U 高频实用片段                         120
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvvxvid.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtjuxtx.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2odonmoxo.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2slpvbkeo.html


<!-- 参考信息 -->