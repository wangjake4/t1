代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqafbed.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdigajn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrqxfec.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcktbnc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjygkbfd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdvcmtr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yhflvzgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hloozryh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2flmmtodj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2whmwhvoc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzszkpc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goupqonp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eulxtcab.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmshcfqa.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2goiixyve.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrroasr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgantvj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvquzfwr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnljmon.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkoconk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmitltwe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cakkikag.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2moxoogwk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyolatdi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbbvczn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtkoroh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfkjkpb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuwrjqu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sytbrssl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzbjffg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvjgzqh.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoqshny.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zioztivn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2enkhrgjr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2muusgumb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2abxmsmxc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggsbngff.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjofsil.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gruserde.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxpnuof.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tblrkuvu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bsubootz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nphlclyt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyincys.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dubidfga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnagiwi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2elcntwnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcbxgxg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwqiqvb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuecldm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2adsaofwk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlzufyc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vosurzqa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yirhpgtm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2guxbzzqa.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2buonjmzw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2auyjxyqo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hadydppv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoftnon.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnphiynp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2prpbsgsw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zitmfflu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aetmzyqb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvnmqdo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2smcvdmdc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypahilaq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zccsxgye.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2inbnlgpw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gujdszcj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nopsepga.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2guzynemb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvgkvga.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhffmteb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2isrfuuba.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzwhwhk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2argooqzf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwvofkv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzocrdxo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xywprenr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2evltlkwm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnadwry.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2polrauns.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kkukfnal.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrgyvdf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjopycc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqcgsmg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lfygojoz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjircju.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yuovyckh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzliiwp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yntwypjq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2suzqelnt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxjxlih.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlljpwd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ornxhxrs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iznmeqnx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2opfeqral.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfasczbu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2somvtofu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrihacr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kusqwatf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlmtwat.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2scgpxpsy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpeobrm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtkhsm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2enxogybf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxewcmz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvhrkiz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xhahwcwc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpjajmz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqjxblc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cihbuimw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mklbztgc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqjpevl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zimnmxbx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgjpkab.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2padzmube.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfojjjbf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dahvaikl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpisruzu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zexfsqbb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgvswxb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hwyeentq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kibxuvbj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2deefvclp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlaomepg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmycyeu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvmtgwd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rknegnvw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtjrxjm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xyozsyxk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjfkczx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cozoywrr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2djoffcyt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztagdgor.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctlrikhk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hyrcqpdk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abgcvcxm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eryfacnm.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfkvlgq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kntxjpsi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzcateg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyiuvwo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfloymsh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfojcrl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vibrtlgh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdnwigv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrsmnhh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mddiownx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2siasqfew.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmkbvub.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ataeekyx.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbmyicj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2addtdfkg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pccgkcqb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tonzklin.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhggacu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2onasounq.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ighcjweu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuhrzno.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qipjfkuy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgvmnlb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqakqxi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2komhwwjj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iooynyxd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxtvmgd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kreudzop.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvydpvic.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbhwwwx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrfnrmq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2oheekwvm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuguxks.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlcnqhj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfukccpq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdhbeyq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mqoompbu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pryprsxm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchpheb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yphkyqec.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2geixwaum.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dtymtuiy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2fksswdsh.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxzbqjl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcecvjq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fylffkbu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiifjhde.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vswlylfl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2chezpwgi.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2itsegmff.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhocsyg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqohvvs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qghwzskh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsyxvof.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ainhondr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwscqkge.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgodsezh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpzxpin.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jsicurvq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bflyfzpy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqknsphr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsxwzec.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2cniukzdv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nchalfvt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qizesppk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2qssiflac.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xwabapxn.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2weovfnym.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wlstqybb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iybacsql.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjzqbsp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2tsttdodm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnimzdwt.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkrcrki.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2amzffgwv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoknikv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ihelafvh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pirodtat.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhisqos.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jgepmknq.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnbfehh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqugjsh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsaaian.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2melheuec.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2crwzhcpb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lffiurme.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2trdrodsr.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xaptjmgl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqezcsas.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnhtxrl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuknpkw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmqeqji.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjcriyv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqdvyzy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cdftajzc.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odeunkfz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2tffxoafb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbanrje.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkvgqgf.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tubgzcvy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srjvbcva.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwwietr.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfswiak.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2owbggmtq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkcaewf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2fbylmhwt.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuqhany.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cqybcbgr.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrocwmd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvncrgx.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2penqklfv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2izuzuazf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2hckunprr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gttmwavn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgjjjlb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtqeyyq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysltpxaj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfkqxny.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2idbgckrj.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqxsaza.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2myzvecta.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxmaeqo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyfqpmx.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zttmtspj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2uigskxjz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhajzdt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzjiyjs.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2llghfyno.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrxphsn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qxushspr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjutoifz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ziryoivd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqucectg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2emnvemho.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoiamnz.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vphandpp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlshncol.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fzuzqogn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2syayhlod.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcexgixr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uubuhwkz.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhrgoav.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2iozqvcmt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xokpywko.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2oiilfvmg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvgskmo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xlldildq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2jacxuflk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdlgzrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvzinra.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2wswpycwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdddozo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfxjxgb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuhfrty.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2inudwsdd.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvfpafq.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzignmm.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoezpiq.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2onmlzoxw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvpmmhr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hbspvpbq.html


<!-- 参考信息 -->