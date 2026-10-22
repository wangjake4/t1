代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2saeswrbl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czkyubxc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuslpeb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgexttfm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lasgfbeq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2neesqqfr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvlnndx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2buhodjlh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wninviyl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ijouomjs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wudtvqjc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjhwbxh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hgskfxnd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqgkpip.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxmxdza.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmttqvv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwgpapu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzyoojd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xskvbnjm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwsetfi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzpeuse.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emjohasp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkievrh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nduqcwts.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vlusswor.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ireuxjjy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2irxxtqqu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ybexnrup.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjjgmog.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axpfacze.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqjfmio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkicnqq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dckccwix.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrdwdgx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrdjskb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2etxwlfqf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2akwcssvv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjdnhft.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eefsciob.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pipozvas.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgxcuic.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrsidgi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqfnjlb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgaamya.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcvizgq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tthwrxkk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvmpwxs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbgqjyx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhsntzk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2evqeyxxo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrhmunz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxusppxv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfwfpqq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fngcezgr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eubmjorv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zozerpnq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zggqplmh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkzuuat.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zyoojbxu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlexzpk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lddbwmah.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfohwlyk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxxdzwb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2taeyyjzl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tnplavze.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcaiunu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwvrtwb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmywpwi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcmrbek.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqavlflw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pszuphbw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhbdstk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2havjxpnq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mflhhyoh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqpprtz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2toalynkj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvvpldt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cglhppww.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmozslu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeivpgwa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zulkfauk.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzmgnag.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfymujl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayyoydtl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgtescq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jeapushp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2adwbgstu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qztbjpld.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ammgjnmn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxflybb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2peirdzke.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gddavlei.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2lcesmyqf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrbqnrw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjcjhav.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rkepxwot.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2efdblmqq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2scecfeln.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hspgjwgi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yurhanro.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmydoyi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvhdoop.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uawxzftf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2plwtnvkb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcemozz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjpxwjf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2iowvkfdm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwhdecm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkfhjqf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnflwjdd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fehirdqk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmptfbw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2atlvmolt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2drlylyxi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bkubckey.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewslcdnq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmxbvrp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjlzyib.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwgegop.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoefdlgi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eglirvmc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qorctbcy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iayahvwj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ybevczdn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkjigqc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkhkxgb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cihcdtkh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvlqivh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpzkutk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxrpucc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwhwbgx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nggaxuaf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmphwsa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2avdwrerz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcdjekp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmlxisy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jginbtnn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrvfblc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwzneyu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2owklislg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ueasdhze.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqfawtd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pirskxwt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tglxuvbz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqliiij.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bngafgmz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoimnhy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2seyoehyd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxotsbt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rovctfax.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwdflps.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmzvukv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cjavulrm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2shhcasiv.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cawyohrw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnbrzgi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzdhwos.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2whlgiofx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiwztet.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaeewze.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2skikzmxp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncshedhd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpzxivx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzwdayg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrktgdt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jarcxpsp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vhevxsjf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2kwirvufp.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rntvgins.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iazhkqjj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bohhrtql.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rtempcds.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfdlupf.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hetuwplz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2laptjdpx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2netyfrqt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2keafwyvp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbxpzlc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcnjfoi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqlcuih.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2uuplurgu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbaxdwr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbrbvny.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vapiecgs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uqogflrh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcykdoq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nbstfelg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfgosqv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiepajw.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiibvke.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbjmbqa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ioyqzunt.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuorchk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpfkklb.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrsgwfp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcvelcl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxxbhtz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2seollwie.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2idwbiwoy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2arqzduyc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvvbzbo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yglsghzi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qgumsuus.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvxayjx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndejbfjd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2muebfksb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwqtkpm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrdgfph.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqqjtln.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2reeskfru.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lkcvcykl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uievrbso.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzwhqgw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2legjxsgn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2knezpdlu.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xysxgfbh.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jnljpgxj.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ngklxxlz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pepjtfna.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmoszrxl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cilumdut.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjlkuhw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jntcdbkx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjknvvo.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ilivlfsl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2stqhuqxe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlesvds.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kidjoeuu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoltwze.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgixyks.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqomjkq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxlvdsl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrqqpty.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxoegag.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2maqnexno.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2osohiuwd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oakgdxvr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtitcpz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jotxlimr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rktckgfo.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrpneqb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2csxstibv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbgbotz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfxcjjm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vgipseuo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2trollzyd.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xprpyajk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pratavmk.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcbdqru.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvyxjlp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2urkdpyyz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmxphwa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2azjuyyqy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwvjkgd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hagylfye.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxdajbv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2aynkjixm.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxjgmwj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ihurdrcy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lphbweuh.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zngbjxkx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogphlatm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvyrkiw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koyhlpck.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2helgxano.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhfaiim.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2louipuqz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qlempvec.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbebqtu.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbkoxju.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dgookmab.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqxorgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsttzqo.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdqqlzm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnqsnv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2frochdjq.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhetalz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqbprdx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uozwqcau.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2thbpfbno.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2imhkyaos.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkoqxmy.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsedkvz.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcjfkkr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2celatnag.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ochalwhn.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gxetzmaq.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvxplnw.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkgczew.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2svkkztei.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gkubjdqx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sslpssvm.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmqqyty.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2aplbjfiq.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2puftvzrk.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hljgttvc.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2clgxjoqd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vviprqhn.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mdeihszq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbqxifi.html


<!-- 参考信息 -->