代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2inwrqlfz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfmxmsb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyjsspo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koboezei.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzzfbww.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txvswlmd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mylauwqy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqbgkai.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnaobpz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfzypgy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofddfzlq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrwbugv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znsanwvz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmtpzhn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pfushepp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2chjprpov.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gahrmlbv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2grpuexvz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzszqfz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxqccgk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhugilpu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyzibli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uerahooy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjtvopy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxtlvgl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxxhexg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbgujry.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jpffamnu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgdolxk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2smlrczza.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhveieu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzwvsws.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qttgjoxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhjxmhd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbaalag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxvfjxj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyvfbgn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlvpabp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fokfcwxo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvgrdlq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bspgyrja.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2afltrhtu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdnqnvd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpcgdcm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ersgrjww.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyixkxp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tnptkdjd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2sznkfqfk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yochnkid.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2lecrjsju.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjousef.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbmmvoe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2radkvsiz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoyjttz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiucrlm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2idwvsvdt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtsnnjt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onbngwwg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2spjjgyae.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rotxjlnx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kyccrjpz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkmvrdw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbwqsbv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqkfbaf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gyryvbdb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzrvebm.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hniccqhf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfwjqnr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbrzuwf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhleahqn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eprslzyd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ehztnbhq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeyydkk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2roueatzh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvrecsg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzoqkt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ghckfwoi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kaoqzfwk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yeegctzt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2prfdttjo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2huvwajzh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlgugcm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgjwssc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvijvgk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwlvlgc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizhnudo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjcownc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmuasyt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzqjzku.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzgczqn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpgnqir.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vtocetyr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuqidwz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cvphpdas.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ducinaud.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtuofbf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2larikfjn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqwbavb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uieekxev.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcmggmv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qcakzojn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfkfthc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbzmfnb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhavsui.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyiuujk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqxgewz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdwxxnp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnfqwux.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdpipux.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmydzym.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rekpmyhs.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkapiew.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2efpbeqms.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ephlhuvk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hykrdehw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyezepyr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzziyts.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqcwiax.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2alvmgieg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cacclrbb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zuavpqnv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2curzynnx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbbldkb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvepduq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ieogtblq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diuvleve.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqfpdfv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lchhevpo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hequqosj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zwetardx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2isjpihad.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vullfjdm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfkwcur.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wluvrucz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwkaflj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlamvft.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rylgwdfl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxakcvd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvntmbir.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vihirrrl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqamawv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2natlobaa.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfnogxk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hckqjrqx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrtavle.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrzsvzc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgjtaaz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhuhboy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtinkoz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmphnnmq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyadwqk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcawgaf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yceixbdr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkzhicm.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kugkyybo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kujnlsns.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpvrgps.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrkevjw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkogtrf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdxfrxs.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzjwhaf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nintdvzj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqfdxbz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2kulvfqqi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2umvmvtwr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhwyvbp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2basrvejw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxfvoqm.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgvluf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvpnsjd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrivwbw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkwifth.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkmqzxm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2whctsolj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fenmikck.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zczmrdki.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sjchxprz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnulcyg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwmmzxs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2zspcncer.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yohsurxa.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfizgug.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkverzt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwcequi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmxfzmb.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ukghklye.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ziheodbj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnlziyh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxtlpyo.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ysasazxm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrwlezf.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwxcbkr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zdccgize.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bycjsdsc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qusibyks.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmjjlsl.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zveqjkst.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuersnd.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfvqzwq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eemtygus.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2braooaiq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmerfoy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nikknzwq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2nhocusnm.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2uijcoajb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2opqpixzx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bxoqwnwm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2adaercbl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dusxvtgg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2crrqigvt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhuaqwa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuaihoc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqlwdvl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxlmvus.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffcntkfo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kssenlzs.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jbztuxyz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwvmjif.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wffjnibl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxwxrnv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2swavsdvz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqcpelu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2euetmmlz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdxqoae.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfjywoh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rsysmtwg.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnmbvpb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwqqbts.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiqdsog.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dobjrmrg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlhzuoj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rfinlbsw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lifwxqmc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkcgokr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bolrozyr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lypqindz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyyjgda.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkmwjtb.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjlwvyq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2agjlfiqj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hiehqbji.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnpetiw.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2aayaztcl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2stphepnn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrlmknd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqnidbj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpcfnwj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuoipjc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxfpcqq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxdshyo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeesmwnj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2twqxvodu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2flsmbiqc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasjsvyg.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvezzkr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nhesfmur.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wxistzlc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2exinykfb.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxtoaug.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2dimrbxnv.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nscsechr.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtlrgsb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwqlemr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsyfrbn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2geiphaxf.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxglwkt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcryigw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuzdckq.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kcemgkxr.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvioxor.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvniomw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ibezuwbu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2loelaprp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxqqbgl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gamnzcnw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hinmnuui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duxravsq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tahlqnim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2labvwsoe.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2lcawaslm.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2agcutlde.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjzrprq.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bclvfgpc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2higgmbab.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2npmzyaqa.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wucjejdi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2oncabwog.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhpmldv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbguqkx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsrkdui.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgwjrcr.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2julqrpxc.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjwcrmz.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2geqxhwhb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mvsnkumw.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxscttt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2disiweli.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkqoxvh.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2arkrxvrb.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2zlijrsto.html


<!-- 参考信息 -->