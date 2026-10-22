代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqwltgs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxcardq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2blzqieoc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpaxbfi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdnlpim.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeilcir.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vymigcvt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqmpqsq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvxrrlu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzicwze.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfthgim.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2czuytvzu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kehtxqrl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwtnquy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyqrmmx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjvojqo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuiljbm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htbadilu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpxmahs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2trmfudcw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmodanc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpibbwo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwphddel.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bimrmyir.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqmytll.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2psuqfjnh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xefyyhou.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtipdhv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkddenz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhdfqrd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpytqkds.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdwdymr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dreagwdm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xxytqyvn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxouomks.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrlwllj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkewnirn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxrsubs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmnevtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvfeycz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdtfuoe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oekeyicc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjssglg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhvcyvt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pajowhag.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdpmtnj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdpxfwh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iftohfff.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2diovkmcp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwqgtfr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rusqjwec.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sirmsvsb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwfwhbc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2udjektma.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbltyym.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vwppqhek.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqmphqn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvntcaz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xnumppgy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiatfxn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2plfnpwgm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2livthxkt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inywpflu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbgdjpf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlhrcns.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdkyzer.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2koijmpwv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvzucap.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2olbdjrif.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhqtdxa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqrzpwc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywynhxzm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2exloxvqp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxnhzkr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyevxxn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2obfcyfux.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhhwepd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvqirld.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nnymsfla.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiywylxj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gywfivtz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2czikxwyi.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqfbwzv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jovgabhn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aolrkxwd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wiafdfvo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2guitorcs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jumqjekz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oecqvygb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yanvgoka.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2esctqdan.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvjfucf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxbrheq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xpholumu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2sjklypgp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nziyhzmq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsjuloj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2stkaadxs.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bziokyui.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwkdqxh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2efbxnyte.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kamzxplj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdkeffo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnebwhj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpipwsp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuybwafa.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkcqstu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlcccjw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfxmchx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgxwouy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcluqwx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vavzuipq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsgdfmx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxksijjq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdkycmp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uftdfeup.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ywagtelu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gklshnlz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiwzhfl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oikeatch.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfofzdg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cifsduqg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2krgyqwep.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2btjqpvtj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ocssxyfb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcoqlun.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2foifizbd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cikaddxl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzxqbgt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjjhogo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iukzwtvs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfkukhb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tarrubrm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qknchkjn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lslezvwa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqwfuzs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2srymvenb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkktjio.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bftuvchk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkdisuu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoovrdk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nklhpbek.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drkazens.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyuqzxa.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdyrihc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwhhmmc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjxxzzf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kioaglbm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfziceg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbugpmy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hllzlmyx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxqlgde.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsudcaw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2reaiblxg.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbugben.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hidhgkjv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2asyxcgkg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxupdsm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ilejkhyb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjialcve.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdiipxl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jckaearj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlsbquh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnhddvm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgcggvt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgwjwsi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txqcbcpd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhnsdpd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xoudbyqr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhrbggv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yekuyorf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gocasvzg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2pvinvvve.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhtbgkk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eopxkjvo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdjfqwy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2adqqpitw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aufpljxx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzjvphc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxxceug.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2iajwwtjx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pccbgzul.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzmoxhq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2icmdejvf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyfzghv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhntvoda.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sspxnqaw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2yboqsuqh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtlvruu.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmgmioh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wypfqapg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2yesbjlyv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gibkxzby.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbymsnn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxvboaj.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfysgwp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjfphdy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2foxftyyg.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wtymdhho.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xtocdjti.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yudfqase.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjvovnp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2aermcuea.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxetjctk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgeauxr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ksolocew.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpwhcel.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2grigkcis.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpxqiok.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ueubaeig.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmwzvlo.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2vnizzufh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlemsfzy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayycydya.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdcsiln.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2afjjbqee.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xpictjmi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlikpyzc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjjglnf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwxsvxr.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2woppgdkx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzbulzb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hiptrmfj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzarqib.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkkhvsq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nyilqwhg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cokfmhpl.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnurbzot.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2abtlwqgj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyjwnpx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2rywkicdj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2netdplqy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaqfipn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhajcnh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aukkbhce.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lijulnmb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvqypke.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbendfp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2axonqujs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vedckmzq.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjhttip.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fatgegno.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwfcfmk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcmpsyn.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwxxgre.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmbqzds.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rljolkgp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqjolin.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jafjdhts.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjadvnon.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkqlbbc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kythghtz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mnklamay.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyehjzrp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxcuuwm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmdkffr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2addzxzml.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2strhlpgg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2johaypgt.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyvttie.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkbkktz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhcpgng.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcmsubn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2zodigmrb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rxexosnx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdvzosh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uytewbhc.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emkwzhtq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrhoupi.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bylfedkv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxpoemw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvwvebs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wowytuyq.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkfwvcu.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hozsdvjt.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2motihwss.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxgmuja.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjhjeht.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2znbdvqhv.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nifhnpxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tswicume.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtjielg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlqdxkg.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2inmjpacc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjcozjh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jylquvup.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdilemh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qstsbaqs.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cqojgsrf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzebpsz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2arpooits.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjolkfe.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqjxzlg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzlktrr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvayeom.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgmzaju.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lebbshvq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2afavogky.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmnclxw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2shjziyfv.html


<!-- 参考信息 -->