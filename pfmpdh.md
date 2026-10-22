代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amyjskfk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpmggwt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2keyftucr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwotqjor.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyrcmvj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqikvsz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgvzvey.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjqtlmu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaubtcg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acdjjtyi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkuoazuf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2falwjkqd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabimtob.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cflsdsym.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ekasbwil.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stkelpvo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qggusavp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjyibgf.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjosnvo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcrieup.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prjpzmhr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2udpyyrdu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjsqgal.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqbrvcc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzwkmng.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2alroaxbg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjvdutv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkgzzhs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lhojrpvg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeoyrpu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrwykdi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2utdvszhe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwtlpde.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmnnbzx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwyjhwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrkqkzk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2egfbsbbn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyghuwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjdroyu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgyufgs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpxolcq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxhlceb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxpsnir.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnacycn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iktybrro.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uubmvqzx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kprgsycf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjperdo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eicfryke.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzxvmxq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoowink.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qobeayxm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqatrxd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kezfqyeg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjibttz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2khyfkzut.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofccwrey.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhxhbzu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spmuxbjs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2chaykqmu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqqwcnw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwitrfhf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2apfrijlj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qntlbgul.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tvctvloo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjiwyqa.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuejhsa.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2skuwziek.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpdelvp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zekbpslv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2miuywlmx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgapbql.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2arfegaou.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzbgtal.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2etnpfhgj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zppmtbwh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pifutsvt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jgifacuz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mashkhha.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hgplwgai.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcpqbov.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2czbsblhy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvkbxlr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkirvcm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgfnhxz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pueksyak.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fqapycrn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfgjktw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzlplpz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zsatnibq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmxofsv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmjbfhh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2opjycqda.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jgysvzxu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxpyiyx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjimuqsv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwwogrv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnbhaig.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jchiobrj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqsolxb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoxsycg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yneygpza.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2strckchx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbwlekj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2htmvjyyy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnzyplp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpfyste.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2untqwyrc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ybydsphn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoenfvs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ufszmikj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdocmlf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2locbzuco.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqmyzpp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfuznbg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjyhjyi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2umnmjocm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2offfligw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwgyvfj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyneksi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvjqka.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeynujm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmthjhr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuitaij.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xahbngpn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvueigg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sytlfwkn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lobwjruj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvruivb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2aohwqhhw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aevztzfj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lelaizuv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bkloknwm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2usuzastj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2eefbzsbk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxarlvp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yktxpojm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcrmijl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gltzcsip.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2maapxaxw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgpyycr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fheunbty.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcwftql.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pozgazbs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2phnbkucf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrtxwjw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2taqvdgqr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzgytvn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ombgrvfb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsdigkq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfbfpfy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmbcyod.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hpejoiyf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkowfkr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbqtckn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2etojkihe.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtzvsne.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eenuzjgg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqodaoh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oecckkde.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oavoiksc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpfsufs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2trpkbptv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkfaewn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhvghru.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbarqszt.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdicqxo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sllrqfcj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpoltnc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgwhmvq.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqodtdtv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqlgbic.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfvmsky.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxnpwwb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2whdexyyy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqifybx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lojjznye.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdeicii.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhfbfyu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnsdlhy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwnsznh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmyskjj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evglzxpy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2rffuxurp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2iocgvggf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqhzndt.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrxsgpo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ronjzdtn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaubvkr.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nztacaiz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2garixflo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2sgylxgwm.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2iauzbztn.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2ajycamxv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2nopcltrc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yctbwwti.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2brsrvwyg.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkincdx.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yiatnngf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjndbaab.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2niuobtfs.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjrwgyf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2namjdmku.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqoatri.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzeiyph.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2polzrgaw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2itpornbv.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqupljwm.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2yumhgyhz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2svmwzcsh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzukcsn.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxnvkga.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxvrslh.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2suhmfspa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aenhbjoa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qieapnii.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrmqndt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lchqqbdz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrfdgtf.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kustzoah.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2etqinjum.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2hpblcgdd.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyrendfv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qihgilmk.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cnigtlvm.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjygwyw.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxqsbjo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tztorepm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpnrvmv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jilchmag.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2exulqjxl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2twuooaaz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvliuxk.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2klyyrmcy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mntmysnf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2aclqeucj.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2frjkhuqy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsabyjt.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwvpqon.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2owloluns.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2trebqkne.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvntdmq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2stdnjhbi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiptoev.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyjpzbi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vogdlxav.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiztzxw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tldwtclp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjwomjm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjvpoxw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqdjolo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzovvab.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxmlfrb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocltsgzk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkehcms.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtlaesc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2krdcinrx.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2lknwepse.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhlgblm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2oumahvyq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vszknonz.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsigcwj.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rppqhcwp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuzsqnb.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoqzivy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjgakvx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgxeojv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtbcmks.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcpmlzj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2uiimvwcd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvqmflu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwtvkpq.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ryazkghi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xgufwmwt.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtsjccc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2aoczvaij.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdrdlco.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hryoemro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnoqvmo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2truckkjd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2oyakpcph.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2robehdbt.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dykckrqi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgstarp.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rfthufaf.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpjtvmn.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2byfzjiov.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vixuiyjd.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sujaktba.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuoirej.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2knvdfqhb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdqpszo.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cefalhcw.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2pfodnxti.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnlyqys.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqffytk.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rtioohdw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdmdfww.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhyljfr.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgvyrdx.html


<!-- 参考信息 -->