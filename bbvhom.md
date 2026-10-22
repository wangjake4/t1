代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njjmnapp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwqtbte.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zcquezfr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvnkxit.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmzwpzm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwwiyyo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iovehrdi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkoitmy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpeeexp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgrviia.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhzgflc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvrqjfc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkwwgvj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2znjzpprn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2doqwgpcv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdnxkux.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyiptsp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2feaivjvg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpyqser.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ggegzkrb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2clxlhdud.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqvcnmu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2woybxjuh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kvzfhdlq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqodokjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrgxcih.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjxhehq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxqvjes.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsfxkeg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlxdzsl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbmfvlj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2izezlozg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ghydbhla.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjhokqc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvxygcc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qtisdrma.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnfybiv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwjbklp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbliqnu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsggiqvn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dplryofh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrfozsd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2durafpty.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpbgufw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nagyyayb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nibeemfq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ullgiwgw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2upixkbtk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkkrwtg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxugqrf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhpjxol.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnergcr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njkwbjai.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2thenmipv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxhzpwq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2irulqujk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqhxrgu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktntsdhe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbqzsqf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nnomnona.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twvpxgtc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdprruy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmyblpo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoyjxvf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwrozxn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbsepcw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpybsdu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikxkoj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiwioah.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqbrian.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpmxyog.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvfaudy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2esncfufy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgefxio.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfeeabi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricojqdo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzwhtjt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwjtefd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaqrvlf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqonblcu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxzzxsk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aukgmtww.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qssvoydm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sradjbgi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjlrvjo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyafnbt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yptlqvsi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhfsbbh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgilqzi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2chqvpbvk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuffmvm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tkniybbn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpvdjuz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcduxcv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxigojyd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwevpntb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkihgmn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmggwscl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hzromxxw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhilklhf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jeppzcem.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ooskmesv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wnggvclq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sfivatds.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uhugzbsb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgldskkk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2basytrer.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkixqzm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mavbtksb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sewlkbau.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtwfpgy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nahnfyaj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qviiyljf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffntbamz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsartfd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmpdiqp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnwxwfr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbwtyub.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdaaomp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xagnjorm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tuggrjhn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xazhishh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfhvxnr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnxatin.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qhekjgqt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2piqjhksk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2turwdqws.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgvcelv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkpmtvj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdayulj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipflnuen.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oczpgaan.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkiwaay.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhgplhh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmmvfbx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rypcmqxz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzyrkfe.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gifsesfz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bimzufvj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzugeqln.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gchyolyi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ungvrkxe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zcruqqeq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhyiof.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2txovlnsv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmgmbcb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2locmsbso.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2orrxnhrx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgxocdm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkbtpfb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2asaqorzg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvnfqce.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2odgzxxdl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhnzsvm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zoybtxll.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xambztvw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrywrwf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otidxrvc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kigyhhaj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2regopufy.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2drdmzaxg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2sreyzaod.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxggbvj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sqyxcawx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tolujmqj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkhucba.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyvsfav.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtfwnwg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pveoquzh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikamdhsb.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrcyaug.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rhposhwc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2opwppips.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzffhugy.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lecwtwkn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkcnfkx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2hrojbwtj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vhookfum.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqdghpd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wglktwdp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2endlyttf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hnadcewd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mvibapdt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgceabe.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbgbqkm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdyhgkn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bojdaqxb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrmuwyn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqftcun.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqbnccx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfwqklg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqtajkv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2petmuvxu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eckyjjke.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnfpgeb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2txzrnedc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjgjtan.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhgwjpb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2buapipjd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuoluoi.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnykjok.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrrdzun.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqvbrel.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvhvifd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwmgssj.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oyrirfvy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pamfyukc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcgprmi.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cujzkrrs.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsguuao.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnjjtdz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzamntr.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjjoujo.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqoisio.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmfosjz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpdptbd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgecqfh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjjskzp.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvmhpjs.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uooudjyg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfnetyp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2onnlurag.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvnurve.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbjwine.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tnopwtio.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxcasue.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bjagceid.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcadkgs.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jwihpyfi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeshvtss.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2tmatzjva.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoozcgp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2npbrwory.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2swzzsfst.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmtvhsq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjjstyg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2txkrwjqa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvvwoye.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvambwk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmhfmgk.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdatlrp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihocxxwz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxfvmuf.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2atcunlux.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjrcrok.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxmufdf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzhavts.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmuyleq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgndtai.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2euxuxlwj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tpojczhk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2szganwpi.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2soycietx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdjouxr.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qchfejuk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjhrmqz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtflmfy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdvdpsz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyimsgh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqruwbah.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hymugbcg.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fljsbiaq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnabaqz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wecwonkl.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpbppqc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvrqtnz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkgrteb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tkltxcsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2karhllcu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuynhtq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtzcpux.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kghaxnvp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrnpyfd.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrndbsf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2abyrzxfg.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sicwrhli.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hifqdfjz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rteivaos.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iimqgosb.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iropvqup.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xjapgulw.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgnyyrb.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2loxvgawz.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvowavz.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oxynhtht.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjtykyk.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nitjqpgm.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyamvfk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxsmvsg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcnwhyg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yywzwehi.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnbomzr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2delaepun.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2shnkhdym.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhazdmf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgdcnfh.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2lhchjxjp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgkpdzt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2azfjuoyx.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ztswpbkt.html


<!-- 参考信息 -->