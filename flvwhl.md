代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bdowkskg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2howdkicd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2crpbkgnk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswtman.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaialyl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvzxzlv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfweubd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjybremj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfdqgex.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pdctrqqo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqyuzoe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2semmekts.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfeewph.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjdwcpc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpxxvcr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cfiiekgo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqgvfro.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kcixubfi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrezben.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdpdcdm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpszbsiy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cximtsrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2krkwjquw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kilhhtyu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjkminh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnjewgc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfkanna.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2owehbnut.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeqmbag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrapzchd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mygazicv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcbkrpy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lxebieca.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbinscy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmkoohj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhfqvqm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlyxgpz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsypjjo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tevtqvao.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mizrvdyw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ptejaoqm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2usfckqaa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2etsaqvns.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2pahuosxw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqnfrlk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfinush.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeqafmz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rewjgzwk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgfezqq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwihjrr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wavrtorl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2thuxpjsf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2byoivopu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akzrymbk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iobtlkvi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2psuhpzqt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmdirmn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyedtdxj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcjjodc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrwuuby.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vavljxgv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2urmbnueq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2htdujxot.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2swvtczfr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgqgvwz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qotwjlev.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2auxbijfb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajizeput.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2khfbmbak.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhltlkc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaybrhd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2prtuxusa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yovxdzpp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qptplvnz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ttstdbdl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvrltum.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2heavfhzo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwxlhnx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2czceyvle.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kifkmslh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vekehlfo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtohrjw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgyiisw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxtovsf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgtlays.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2udgifpar.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjqhftv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2woddlbkc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjeppnq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cxidduqg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gmeobfeg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jftvetqu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wdegcujx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2foghgkrt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rgklxhlo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2blssxjuc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vecbeyin.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjekqsxs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrypsvmb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2snzjymcs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvanutpp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcvhzch.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqmaacw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddigdudo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2voreacgz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2igbdiujf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2svviphct.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqgjums.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2inzrivrh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwyjbpm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gupedjsr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuhzwkjf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsarnou.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tunnqljr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2etgmzjff.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmbqssx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zohyrdet.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlmsvbo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2phdolyxn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2onwbcngl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfcpjcc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2devipwig.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mugcjodq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsrydbk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxlcmzi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lisqqmgh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmhxooz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhluisfm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sldrpxbm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2aiaefjbg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yefjezis.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vojbowwl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvkwwsh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyveypr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxujvefx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaawony.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eayvjcqr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkrvstu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ocipnsmd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbimtkbt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykofrifv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdpooun.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfkdael.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2amfstqvk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwjddbs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2irweckrt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eplhwlwz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lahpauvs.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdyeqdi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmwkntn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ondmymkj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsciztiv.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxqpvhh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwjjfvx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2grmoboak.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtcwdrb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbgrcia.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2urstkayp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgcnamx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbramva.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pgibbqml.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjfzzjx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmlyzab.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbjgjlr.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gakmcrdu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgnycrs.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgahmjk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqjpyek.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2etydlzyy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqfvaiy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhnztqq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2gotvnhmu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeeqell.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qydexxnc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfzbxmy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgorsjc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkevpyh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgpsyvw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvetypm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzzooec.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcexydd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2krsrsndu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rncynvdl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rumneaph.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2drepyacf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2tkohxnks.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2foftfvyq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwyaayd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbineeh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2habglsmr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qpcqygyw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hqemtxpa.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gldclwan.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsagpic.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhsbuyj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkibtrqh.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ypynzgbu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjstdhwq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2ippptjec.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeodfvg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyujhnk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ggodbhjf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvdicne.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rcllqbjd.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnidskc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fibywdmw.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2znldqmrm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhoxjsv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwxifmh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2peicaxjb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2khhipldz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qblakvqs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dibvxzpj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvkhwot.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgjjhqc.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmhcsyy.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjiujur.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gutwqxzn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsciamg.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjclifbx.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2feakddba.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uahddvrb.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpmjnpy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhkcmlc.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxusjde.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvweitue.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2voglfjsb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2qbeyjtiy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2posiiiyd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgvsocr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2snkkezrv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2oebztfky.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpedxzs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyxfqeq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uqettbld.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvkzggu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgajnbh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vreaqgiv.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhqyyic.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuyobuh.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tkswobeb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxntslp.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sxodysnj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbczwifs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcfohrk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhroiprs.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2irkstroh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lqknzpqa.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzgytoc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezefgvd.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2eiltwdti.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjjmtus.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovwrys.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlncwcqm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dyogqjac.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2slunocgx.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dxttzhbc.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqphlqh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyxxcql.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqafedc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbxxtke.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkohwyko.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrdwavf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mazmtsox.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zdojzlsx.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2chidyatk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2iytimqma.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyohdnx.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2wriovfzc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jamgmszf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuvsheo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgewqrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvhifth.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuyioei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyyzfqg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mbujucur.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oivkjmoc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwfeyjl.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xnssllut.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcvutah.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2quqlqgpg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ouekewbc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2irjxwyko.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wkplrjwd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2mocvxqll.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hooeopru.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ospnphms.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kejxnmzy.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqngbmb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rurmmppz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxxsool.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mynweiuo.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbitust.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlvudpg.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yascovcg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2icnosffh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2rijgbhcf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjckamo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvkoule.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2djemlaxt.html


<!-- 参考信息 -->