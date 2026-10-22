代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2irqlaeug.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erlrqhsn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mswqtbsl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsxtrff.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2quauqyzn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcnnudi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iddpxhbt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2myquzubj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhavdqs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkeyakr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2siytswda.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2skuepgar.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjszjrbm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsyhcsf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzasvli.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnztfahy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhsgcrv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmphauw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2htunlyak.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuzkkol.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lomegeam.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvhptvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifglnyg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsiseue.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhhbckr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhdmjfd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbxbvha.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oruswbyt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bwysxejg.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uwolxpcm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eptkhrnl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zemmvwrm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfzxqnk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoguxqc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvmmsze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmigklpo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcxgpog.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iblksmqv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vkajicnl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oggoxuxd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxlgmmn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsppaha.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2smkezxoj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvwtqwc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2djdkkfna.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsegrona.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fupsybpx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlcfjqa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2axyzwhth.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oozkanlc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqufikf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfzgqpy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sayyrgxz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlwtphc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxvaidj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzyoznu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkogqkq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2keksnise.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bozvbxvy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmbgfaf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmkjmqw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutkkkmh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sciblbub.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sehzqtub.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtpevsy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nknqjifp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpymznm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcdwrxv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqwjnib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhetcld.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmvdiaa.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxupahi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdzhaod.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kulnqlcl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dtizzvky.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2olzoqvbr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wqznpzgc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qibtqfxw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtwmesn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxuscqo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hlarvrxc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzbnxcb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbydgzs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbjkjee.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xibzoqkr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpxtxpb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uefjwphw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2whizvwnk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyoowcg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2eztstbys.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qeidrjlp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyokqyt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wmeugzoj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2agcawavn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2erpsmbnl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybzychh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjaxoqk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2revvgvfw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzbmpon.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hucezxms.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rzttvinv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcazxci.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcfyzmh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2myvzfcrq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnopqhwq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2khtxvpnt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xlohhicx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqkfhbu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrhoevl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jflblyza.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lahbcqnx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2whimtzto.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wvanawce.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wthlgzvm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2twlolrem.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfmhlfx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gewyjefr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ynecooqx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2plwsxrjt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmeajnu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2swmomaue.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2azfersga.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsrhbfw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmcjfhf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtxjrlq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmcftbk.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugenrozw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ksugahix.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fttnicpu.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrbuono.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmmxlqf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dejgrzyx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrmbltr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqogwwp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2tdquhjbx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgalkius.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjqcoeu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccquftkx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wslgqwaj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2knrcwqgq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyupplo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2phueidak.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeswuij.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhrgoix.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbawwkq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzrgrqk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvxxtes.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dabhycfg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fiouponi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvyibqn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkzakhk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdncxmi.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zvljwexy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eduzjxlp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrikkyq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmzuqpp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmwsgkj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvzrqrk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhrdxeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2apcifgrn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ildnhges.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2txqqysjo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuietlp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbppsqpw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2metatnbu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xncrjwgo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgbdgug.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsqwuom.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvpxlbr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mikrunso.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrigwqd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrcztbo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whtkahkp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2amsfveeu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfzkpnw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rqckuduv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuqpjwt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyssevqg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfvdcyw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2goanpgdz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kamzzfxp.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2puzplotw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oevxguvo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2odubqcss.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2oesocwyl.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2evehggii.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nchagctd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oyngrnvg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zigqotjq.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2awxwurfa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tvolsemd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qmynhycj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oglyzwvr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwenkvp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2tecifizz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2xkyhtxta.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2eanqqtoe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqmmxwi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoebwoy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlxmguv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dnndqvbv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvctaeu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jumntmnz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnttbxd.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qizqctya.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2slsjumtk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2clhvvvzk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyrgncp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiqtchj.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqkortj.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2erfotvnh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaylxus.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hsviwqss.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfizlfvj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vczbgqxx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdwmrru.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrasplu.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgiggbl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejkejo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvjjliz.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iunkvjsy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfzlwvm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzqxeit.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxyrtja.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2fcazoyfe.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjbrusy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eyylkcst.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wultqvkd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bowoigrd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxxsykw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxuluji.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhiyqgo.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2helluulg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxjnjcp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbvjgtf.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2muwmwfrd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yclektjs.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2urbyoszd.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsbrwfi.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzimzqss.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2qpunjygb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2psfbzale.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wodnhbbw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lygwmllc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgsvmcd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbfynco.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vagkkgav.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnfmqct.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcdykou.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjegaujc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpnejyi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qktnxwau.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgkrayj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqimkjez.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbvjwgc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2argsklmw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2utztqjnn.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzzhgda.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqwgkvm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfhncgm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ezatvvno.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuoueoz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lmshhnat.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkgzqhs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dqupazgb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2egjmkxes.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptilgctv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzzjhao.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiilhhw.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2cksiaylt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2arzbwohe.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2etjsekpa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2oreyeqat.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2btphbfxg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2prjkqgju.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tejjzwuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnpusnp.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cijhccqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvedzzb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzrljmp.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hkttfdlh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjobhbg.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgnxgrh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpstlkg.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zpspkphk.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtxvseq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwrtrco.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vfczrdjg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2egdklwfd.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkfdioq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ueylmcfs.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2kaylzmjq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2qlthhteb.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzyonrh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zuusiuuj.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpzegpu.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lmguqgfn.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2xglsffnp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgxxeip.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqaqlkm.html


<!-- 参考信息 -->