代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeiylvo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onmyqnkl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyreilj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyszeei.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2appudwzd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzhbluv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aihiyuts.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpkawdg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpxlews.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aajsmwbe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bltwcnbf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmlpfub.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evoluyth.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfetashy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbnquso.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aattphuz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxklrae.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxfhseq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbbyyam.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qeokjvdk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yopqyvlt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxjzuzj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgpjhfs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxywobrs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnzomzb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwadtzp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eifoyxtl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mpapxqzf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2giykwpvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fukzeoqc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xubwydox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsgqcgs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnusijr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ionkcuei.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkvyvhw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtszfei.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsstxmr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tptebjgt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgqfpce.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iutnzaij.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wyolsxrc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywozijit.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tuokrlsr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnoablml.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2brsyvpjk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hobmvywt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yscjmxgc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxcwubm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbsqmrx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcloyga.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2icmwioqk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjizkkkt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuwaepa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eniqhocf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zloqchpv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2onmmbdht.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvjjszv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgioschx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gollabas.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmygqrzu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2urftpaqi.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyeoffq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmxxros.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2autvsgsv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsoiejj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtxhxlx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqkbkbh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2etpkdwmz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mprncdpg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmijtyue.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2faxxnqmt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2swrmrfww.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxokcmi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmkyefm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iemhbgny.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnnjbnl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjonfaw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhhyguu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wycxewic.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqzqdqt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfarskx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcioxyq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2epsgkvpf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hottvzmi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeiozie.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jggqqkse.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpzrtht.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqwxncj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zojpigml.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lyshycwt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lpshwtgf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtiamhkc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2przerftu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkroein.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pplpmakc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjmdgwg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gouqpwvj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxyosvu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhoprav.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cskjkvxy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkjhgsb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkefqbxo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbyeflg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwerunca.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwheivs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dekhlewe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pmitfqst.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lduwwaex.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nvandajr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2olawbxdy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqpfjl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgibspd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvrkxly.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkyihvv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2clpabjgj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yukahhrf.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sbochorf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkctiqpm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlowxsni.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaxirno.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvrbguc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okfkgfin.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqfmbfl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nutamkwt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqtdwpu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkdahim.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjgkbuq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxbckqs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2loooiefg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lcctqfya.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdurlmd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxauatov.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2eiipklfr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2toideusk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xekgbmbn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2orgocfmz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2trxhkcof.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzfstlw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifoileko.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzlqoog.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2edakuctx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2llnppwpp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eicayxwm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wheylulh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkcalyo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcogbhvd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fsumtxiy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsodoin.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvxmxpl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfstkyve.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqkwgse.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxvhubh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2upqvagrf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bufabnfg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rawqeigz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyacral.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvtvxla.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiambpi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsiczsg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cswfsuld.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbimpo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oavnkyhg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iaihlvrs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gshdhhnd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsksywk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdydymyq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2stkcrwdu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyqvzau.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pktspmks.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbggbltr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2eyidwyod.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqknrdsl.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxgkudu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpbahsm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iemmudkg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2stysdhua.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gdebjxlm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hencyykd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxumwki.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2djgqfftx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2arfxngdz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaibkbq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzpmkti.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lenvxokg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfgpfhq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwvolqz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rhozwlzm.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2epjsduph.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvlbtfq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ezratbjf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiblvvc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qucwloxg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iodtxvvf.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2timipalu.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxylgfh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvtmajq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjrycuk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfhrldc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgkdacg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfhhiql.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mdflulzq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgwqqtp.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2scbwzxdi.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjumwcqw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjihjhv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkoalrbq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zpehpfbf.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2owsgtphh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeevbot.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2apsbdrzc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyoyxsv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpbpqgq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oftictwx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2htdxdlpu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fppgddow.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuobcnbn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fbladqoz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nwveqmlu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yejpargi.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2khkcjhfv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rompsasp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtmfqjl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xbchfenx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfszzqv.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgvkomh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2crgxpbaz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dascszwi.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvecsfn.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2moopsfuu.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmetdhs.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aymefmye.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqbmtof.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvwtmmb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2taxioaxr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqodotp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfulvcv.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhxvvkk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2urxojrif.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejoqlr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2btggjirg.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtpceyn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxgjksb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qekioaok.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2hpryfwsx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2anowbhtq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeibuag.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdwuwmr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlnepud.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhtcqfu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhkfvtc.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kaprovhp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2azuxksrr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2csqrtfrr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdoouus.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzxtixj.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugprbwcz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyggjnk.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nihzpdqg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqlsnuz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbddjgiz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2akevvdrs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsxqvgg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgmckol.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsagyhad.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqhohzo.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qfobjemo.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ysplvbxu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrketvi.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2irwojxxt.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ebugcaae.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjztzdmb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gjacwlyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsiaenr.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqeeblk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvkknwn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlbknfm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqolonb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dyosmouu.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jblcgtrv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2phynqtuh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gzizadws.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsjyquc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lricrwuv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eyszodjq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyqfadj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oefhdpys.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2lupjtwfc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2atzbguju.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyujcyi.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2mzumyohv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2buyzhoao.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjuqqna.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzcgtiy.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2torpookt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxijnbw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkufxco.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvklgry.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iskdpqya.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkatiso.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2upoptmsk.html


<!-- 参考信息 -->