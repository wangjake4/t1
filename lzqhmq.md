代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhayfgc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2warfplpk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpshuju.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrcpamx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxmwriq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kobnucjr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtfjxyl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2milsdvdq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcbmwlr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrcepxn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dydwzofm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyaifjj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onhozghz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gtsqseyz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbpmtzw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uqebvuie.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvujphon.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wulhntxl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnelnuzl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qihkppza.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bnovgipp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2apmqmzdo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnjqnaa.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zusiksnv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthswiyt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtkvewf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjeztnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2actxstox.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pbviissz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kqynfrsa.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uhradybg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2shgnwizo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdpcmbu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvndunt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zodqvhto.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2webvwrgm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iznhjoib.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rglouutn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cikvhnzk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiygped.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2besncvaq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxxqbcd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjkulmk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsfaves.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fsivgmef.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcmrogw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ekghqplz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuevpyok.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ucxlgwxr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sachnvau.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jnopxyve.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aixeduon.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdspzii.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mztpxcre.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbkqkuf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjyjtdn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgwyivg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2avuxzpdc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqzjmeh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrtpvqx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpvbgtc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoiepck.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2satyaowy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eipldpcy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwwpkoo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdwcpzv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2njexstnk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fugkvxje.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cjimycmh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dianvouc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aroxskww.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhphgvuf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzqsphr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gbghdgnw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhtfydj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkoqjjgs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoxadhb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2azmzhzqo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mghkvtlj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfoeivw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lfccbusq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wujbyobe.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoyktsl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pcagcggx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdpcfvo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xumactpk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2axjpswst.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2itedgtpl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uclrmtbv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mylhktzz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2venunruv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bugbpvfk.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjyjuut.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxotlph.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhauynwc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vddvemuk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnqaldj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhduqjwl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdiytsb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmfjqmz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jgddnqwq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzilxts.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlxonca.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fulkvlww.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcygcua.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucorvpmk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2efhqwojo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxixwvri.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lepodiib.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jygnlvvg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvrlbg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmrubfe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhreano.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kobaomgb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhevcwi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlutspna.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqrzfbf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwlbphv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkovkte.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqiqybb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ndetozvg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkyxnfh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2keiwlvqz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fljwvyxr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rbiknrvu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzaemel.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qqojzhde.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oihokfbx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vtovimqm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2enkpjxxi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsiapes.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfdfjyr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrjiqdr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbrqcpg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fomtjevj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvkzllp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2objrzyco.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pagvuall.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tevftwif.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrndwotx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxncyrri.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2broombtu.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pthjxxus.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hocynfxr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktguqcdf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqiocrr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qyguljgf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzrbmmf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ikypwkab.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwuclrq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dimngxoi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdgbywz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2njmovpsz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtfniwo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqvmjmw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xqloekfz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmgbskv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhggtrbk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsccual.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzvquqt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dthnavek.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2agddfutj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bebsxndf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxujqye.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnhjrhw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2koxoyxds.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2detwginr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2lhodfvwm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcrejrw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2harkafiw.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkveijp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vljrintb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkhewog.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2toftomgl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjwnxkg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nejzpkkv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuuejph.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2savqtcew.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmcjthf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpplpmb.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeuhmyz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yynztlgy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfetqtl.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgstuxb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtdkeoc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbpfexc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2givzzrvl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcbrmlw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnxtypy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2urbpvgqa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxhocmg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hschsxff.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2egfzzajc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzafnmwp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2scxgkyud.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2fskxzhrc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2adwzlbau.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2piyojtrz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2srlhwpox.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rukiufjn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2mwesvojc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2glbhjxng.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvwufuo.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ginkocpu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiqwjso.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ggjqnija.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ssptdrle.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgikrtav.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvwmaba.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqsopwn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gstsnfmf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2denehofx.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdjrqze.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mahprvki.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuezbff.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2knfeeohb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2grlflqxq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yglbkbkf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2etvaytbu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pookhhhg.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2psixcfdp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgwhzjl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qryaskis.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgqmnej.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjmswd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjhclwj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhwhuvw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qktcgvjc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqerefw.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdxwhcr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqzfzwm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwhuaoo.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2xendydvi.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgirzuib.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfrwbfk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ztugijgl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjwdovd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2slokncrz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aoywnbtk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgeujbn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkluegp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxnmsvi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzcyvds.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2soxputys.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqzcgxv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjqeels.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ddupwskk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyezelx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2eckjekqe.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyfqpnr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqejayk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2btgqgtiy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2scijidfv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2idxbvuue.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kthiwojr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgenjbcu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qiujbacj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pajzmkot.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2givociuv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rengeabr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2afwteyjs.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2inupzwlk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yszonpir.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoqjtub.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2sihxiplx.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvgszey.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqggzbg.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xzawhzqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvenqxh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbuozts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhiweusr.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrxuyds.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlodcvu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2amawkiyr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2felczpnm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdujmdh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2abynxtpk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xsokfzla.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsdpdtq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsachxi.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pjtlxxhg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2libunofd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkykuhp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uhltsmpf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ogepgtbb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eyviozfn.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuqxgaf.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sltcqlfi.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2djpncrzh.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtkastb.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2twogeknt.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwuzcae.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhfnvub.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jslfwakm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cohfbpwa.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mozttrcj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2vduhrore.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzpjfuy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xuddiagc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwpejby.html


<!-- 参考信息 -->