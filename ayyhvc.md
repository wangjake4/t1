代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2brretitd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yptzsuxx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gekzmnyq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyunmuiv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcdmgou.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqbcfza.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqpakfg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kowvchvj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zievplik.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2abwsnwjl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqucgmdm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rohvrcmo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgklabt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcnwkyo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2grnrqggx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpgbyqy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwzlkar.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2adieyzqi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwcjmww.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2znnagbcp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxvlezn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnjfkfz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2izjpqfry.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhdckpc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2juspmfbj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjyfphw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxczroq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2htodzmmf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2byttnuoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxxtrbz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2etysixpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrxcagm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uytpbpcl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wocypjom.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpexoko.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrolznu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pzswhlju.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbdcxbi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyhzqxc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yoceibkr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2extorvua.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtugtwu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2adxcvbzz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2albnvvvj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvphshlj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwsbjgv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoqxykw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpzwqfu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pxecvymf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmulyct.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnphcnr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdentyg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2owseeala.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzmfyqh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2csnmlgoy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcrduocs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrdefkm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqahwui.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzssleo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvqwprt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyxagnb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjltiig.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdolkgk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeyijpk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lflpzlrd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2spvbnqoi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jyacwqqc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgwdrcd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xzooqhqk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2urhuzwsm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2klekjwbi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqgtljn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcpdygc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lufgocvi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2enembqcn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpsgoer.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nypbgbyw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdbkgwl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ieczbidk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhhyqxe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2itrsxiic.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkgbime.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhlzoad.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2snpslffc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxdayud.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlopodo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2biaagkzv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2stknpmrf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2biawlkhm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulfmyd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xuszpgqy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxorzksf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvkcplf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zisrsmkf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyddlwg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpvzhpj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kybdbjcb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2patuldne.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zowxxixs.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrzvoom.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwelfsih.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2khctinjq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxfbkff.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqerpaf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmspash.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oqklhoar.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2egzjojpw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lquffrpg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyhstav.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2msgssqam.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ssswjymt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqxagug.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhcxrfn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcbuqat.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2smwgoeoo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kywudqlq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kcphouff.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpqqodr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ysexpbek.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pldhcxxa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akzkkmou.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ancmdbsd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jprxrwlf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fhoofswx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2smfkogyv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsbmnyg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqpguxb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aymeigdz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uijosxhz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2luyhldak.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jflyxutg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plgtkqyi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdfeytl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzevndyf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ethohobk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2olalrixl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bktvklvk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pcyfsyyf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqivtkp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2qumquskr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yenwgmwi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjlkwpa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zobfipkn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwpwedh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jlntucnr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtrzfbq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2umiptmtj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmfrutn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npuolkxg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lssxcwui.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hlznnhzm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwzueua.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeouvnb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkpiyio.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtgwibt.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qakcocpf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2msyseuas.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2seogyyoy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsympty.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeyocsj.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zsinhkyn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeagelj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qtplibau.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vegqyzly.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2trvgkphc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaaxbmr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2awkfroow.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvmzdez.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tbitxatq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2drlvgyog.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpfjieh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2riolpopj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2miyyzyaj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxuqlvi.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrgenil.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcdlsgg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxnqkul.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzeyioh.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhwktcq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjywabjy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2futhdlyb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2dsytaerj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2igdyuzlk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpezdfn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpfkmxe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2djmetrpy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2phvsqzmo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2behikahs.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pqybcdxc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkbshru.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mqypctrm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeahbza.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcxhqdg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlwvnky.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmpiemw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bagisxyx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vynkqgti.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbldgyr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgdauxm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtnjuza.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2buwbcxdw.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2iggqgwcb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtcacef.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwjpggl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjzqgfh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpgvoda.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sovwbpgr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqcgaix.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrggxzb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jetoesep.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwxmjhu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfrujjg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2guptfvkz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwottcf.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuhohtx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueiuzygv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acgqkprn.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2fkysbdea.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaulpme.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2isjamtxg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmktexd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkakimo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2olcetbdp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdadgaku.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtxavjb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jasqdyby.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxdksqa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdiceaa.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gducpeos.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2orgwzkjd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qknkidxd.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2bouyzfgk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oarcsunh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cndmnmpi.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnpeuls.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlfpumm.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfzyccr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdwwhyn.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iroffnql.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2foapgyxd.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdhlebv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrobgcgh.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxantlv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmpzdrh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkzfvfy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvcvtnz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyyhufg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jbodgrle.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzzolrp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpfiwha.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfcxgbc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaaqaep.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rykxciyu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzvnvct.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfbgkgc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vaubocvd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zodpjbdt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2njpobfhu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzfbejb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pllzwssm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2krxijriy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpprokgt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ordymxyg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkitetwk.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sceeoryq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2smvyofrt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkeaypu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2gctinarj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdvtbvz.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnayeti.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2unvuedvq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqlklye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byukdylx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkgnsyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcltgxod.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kifwlzlv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdsyxsi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdyeqbq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrmiuzo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cuciefmb.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2keqsefaj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aznfshfh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnwlkif.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2exhqsdmx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxcawny.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpcamld.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpfqfvj.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2rufxdxuk.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgdjmfo.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwtfcmz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrevrob.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbugczm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2wibcivpw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxmzxhy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2avepsvsy.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vysskfuh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2khwejnos.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2robuxdzz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vkumrvml.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2twqnsxku.html


<!-- 参考信息 -->