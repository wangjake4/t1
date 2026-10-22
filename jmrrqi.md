代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ereiymzv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2afxabtvf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwbomti.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzajzlyr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqykmhn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfuwsez.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pngtftoh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpmsmtd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sumhsjhg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sthhmmkf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2alytpgpx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrqexih.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2huzrsxla.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmantqv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dztdzbpg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oklhmhox.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prdcfdgw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrypqqs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhknqpr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbkdzdt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whenebii.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhrorgn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkxkpzj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdvgtud.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tyifefxm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rsboakxv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uchbqzra.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kahnvfms.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avqrgnus.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyszmpd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iykqzgcz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxltosb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysotaezl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcjmhpu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjrpsfy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xporzwzt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ypchafld.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkaszvn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2twzbxffw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fmeuvsjw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hczaopvk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qervirbu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxvumbz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnjdvxk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2raqhkhqk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qfaslaow.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vgryldkp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dmouumlx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vfextldx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfomrfg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hepuahye.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyyxqmz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mioyisyz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsboorb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pjusakou.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2soisfrgf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvaprki.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ilokchut.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wyadjyzv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yudblkui.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxuwcfd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdmvbfg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2asteeaeb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhcmjbz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdvcgbr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpfihlp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcctjdc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2leopyvni.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2comrosog.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkutibvv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpelehux.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrpllrk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqwvgxn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzwndot.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjydpkm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuhyodn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjuknzc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqyqffh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aivzqfpb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnarolv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrkqoge.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tawxyimm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfeqssk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2afrtmpps.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxmfmjg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhjbvpq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yeykrkrv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2twrqoqkz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgipjouu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pzximluh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bavywein.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dewclbge.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tuumvxze.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pznvxppe.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pokyujfo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkutzgw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2prjpseuj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2scdzchqh.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2poadfoxd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2arupbcen.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zqapwbgt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ativufsy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzhmxsi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2spwjzggt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ercribbw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2azbtmpty.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvwceoq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2edkehrao.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2svkemsta.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnbjfnh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjrbmus.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyswzneh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsclgnz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sffubiia.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2crrdxelx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrnbwti.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjnjjoa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmojdgy.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2umgswark.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqjqgwu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvcqsdk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcbrxcg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkypvwh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ududhfdk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2thugogya.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qmoadirt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2agfqaibl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkrpyeq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbrbxzz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2talpwgio.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2prquncnr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpryzjn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsgxtch.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfgawjj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqoowhx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfqkmra.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpbexia.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ralwmhau.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2unyydxvt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvymtml.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbbuaik.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2bthlwwtn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2maixujma.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbkruuc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpiowzf.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyycowh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2doekjinl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iabqpvfx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2piqupwlo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2annpisut.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qtopeiwp.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrqpcae.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzygyou.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2htyvekyo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2thsscbjm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdycrjc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ykufdmcm.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqciibx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxwyukl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2czcdoilx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2viswsvrr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qajcapcy.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmxzljmw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnefqmzm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2etnazkhj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvrfatf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnqliey.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjfqlcv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ymssklpy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2blidkdjf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2emnhthza.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2loajwmpf.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iccvsmel.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cipysazs.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bxclwfms.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2waczsxsf.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mkshhbsj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2txlicthb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2redqqkxg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjosfdz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zuliymno.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcefivgn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2yurcfxcd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzzfdyw.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pupffbyk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlmayzl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbrvpqz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tfozgnio.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pffbagqq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2exoxggfq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrmydol.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2sckzfios.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxgviqa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkvioev.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmbsivx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsalwfkm.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2oegailyx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmavdke.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbfodju.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvlvlbx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2prdjurmb.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2asktxwpi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxnvpwx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxjcncp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtxbmvu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvcpism.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2smvhbfwn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkgvhbb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqribsi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2giymaswm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpfrcbr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2upqeennf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pnihdgnd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnbmxlu.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkmxfhg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgdkdbs.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeowdjdq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfgthaf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vstdqmzd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofairazr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2igydvfmk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2jlchplqf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kygqixll.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzhhvog.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwvwcme.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vrulugrl.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wxafafev.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiycjbg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vopcryfc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2orlemkos.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjupskds.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqzaiwl.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2unfokwsv.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2evujvlns.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlttglz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vypmyhke.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2podqkgny.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2reiaiqvl.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2oilqaaxn.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lremkzxq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bobqiqqe.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nimefhci.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjyklnq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbixuvf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjdoszr.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2avpcgotu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrhrnjn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzwkjzq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2szsmnhvn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2loxqzfyu.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmkkajt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjkiqxe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pqujfejw.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcfssxc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzvoywh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpezskht.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xvasupoe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdbzepj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxlovgv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nouvpakm.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2etxzlbqk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2meiremyu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkbenvi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mneopdal.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbtpshz.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhuqove.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2gnogzjhk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2qapnqnac.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpquocg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvoijcu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iygmwfxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzujtlee.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlipmhp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhlwlbl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2uitetecg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwoviuj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkccduj.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhzhvup.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpqsdvf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wldggzit.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2livpuuke.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtmwxio.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xubkavog.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2tnajuqdb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvhelda.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bngzslnf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlnlbkm.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2yebhzzfy.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2moqyrieb.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zlznruuj.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxkajtl.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dsguogkv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahprgzrd.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqfmvel.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ulffdrpw.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbqdbwu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfwbigq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hyumthcd.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hlylrqdp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2eefulnhz.html


<!-- 参考信息 -->