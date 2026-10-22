代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aqpldxmu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eonwtgwt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkeqcbe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cpateccp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyhcvws.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecktqfet.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjpmfuy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pslpljrm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nofmnquv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdgzjtn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdywjwm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2civaribs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcikvzc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqvkjfg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzdrljv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjpuukv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wamlhypz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eatkmqhz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vykxksps.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvyoflk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmypvwa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iscsxbvt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xazlskhj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2oerhzzap.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kryodsif.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmudcwb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hywaqcvg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqxhvic.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlyxkak.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nesghurg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2guwslzhe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2usdqrujd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnrpspt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iaakxgch.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aphfaayr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnwlyxj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cripxbkz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqueqjme.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2scvkfooy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtwchtw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxjsqyh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbzmzmf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqljnt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xthcsyvg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvksetv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2onoyvjni.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwckzhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkzuxmb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiljvhn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxghic.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2unleodqo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xcemtgjr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuoiihq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcdgcwd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkpjosj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtxyrez.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wmazoaai.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2plbqfcsy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vshapzzd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnlrszz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcbvsig.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zngipxed.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyerhrg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2luxebkrx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhtbqkl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxogciea.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkkmwhu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnpolqz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uofiljkv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdjpijq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iucxddph.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyivffk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsugcxr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2luqsqiso.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpejauyb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2actxpywq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2klqjgjzv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lelwxaih.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2evtxtyxi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkglmqka.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2reqllblj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxgruvx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuyhuph.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkymybw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qztntxmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsaofqi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pujsqzkl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2slxpdbpq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2exumccaa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2beigokzq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxfjacu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhvdwrc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qxagtfzn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oiniqklf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adekfgax.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rexluenc.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hyomkblx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vghyybuc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lrazpaxp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpdbjnh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gxijkccw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qufhxfmr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2batiazzm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nyacikze.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvkxijo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgmcdlv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmerfyp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksthjrtq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfrvtew.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoumbeb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zabdozog.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvgzasw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgvuyah.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwezbkfs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vxornhgg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2feacqdmy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bvujwwcn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyqtfui.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zopcuujl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2engcohrl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtladoh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdprody.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2paprrdvt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoyzdrz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2drriiimv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtsvrtk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxzqiiv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeldxygq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiazbgy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ofohjuxi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cyckoldw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyashos.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mykbghif.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffacsopn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lginkzla.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khbngokj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdemzwm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snxhkvjo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rajitegt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtwqibk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpvjglz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvdktlg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lednpyyw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpasnuh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2juditpom.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dclbvnnk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2quykvroq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2scnrdvwu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmauaqw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mptyuwfx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjapylgx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2egmmzoag.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqklawf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbofakb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ggckddyk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnfprws.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxueocb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilawdvtk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aozqfktk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mceqlotf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2btkfxzcl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuwxqgh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pcueuiqc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2whmhwkqz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflyxqj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phetuvve.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjbqjgr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cctpzaah.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cttuejye.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hksaqjqa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaoefgq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tduouadk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hkgxxfau.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2vitiycbe.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjdqqou.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xwykivwg.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ylslpbfk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmncwdr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkesxly.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtafytvk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lhewdrqp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmldalan.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrbwzib.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2sfvqewjz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lerncozg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krhpfdpz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrrutzf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrsrhnn.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hnurgcqn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2reuqslno.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyoakff.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcqybil.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzskujx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkqopjd.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvaloyq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2drnlosgu.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoyzojj.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2jcanrcyj.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlbvodm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtdcagn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2npcwrito.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2gbihicti.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ooibfpgh.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wahzocfd.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrnialk.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2siocmgin.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqxuigx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwpcapf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwnvlau.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2afxllocq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2abyuoscl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vguzczio.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nssfwjbd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwgzcwh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbsbzxd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pruludrk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2czjoqsok.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrphpze.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mccuwwbj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rimfdvwu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjuzqtw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhirpkf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yigltsxm.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdvjsdc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwwzpag.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwxshmj.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqslghn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zayrwkmg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cytbuvxo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2jczayvfr.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2iayfepce.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhppxdl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsrjcej.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfesuge.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzkodpf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmuqyxqo.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2wschkdqd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdhtaph.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzktnuf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqpxepf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqyrytt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwexmswf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2aotszeqk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2szpjnrrc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2rterkfpj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2utzdepfk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mocqzgqy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmrkhmu.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pcejrasd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2izydarht.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjaaeos.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsloxkpt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxexqvf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqvgfqz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2iowgtril.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mppiytkz.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxleqoa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jquujheb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlbhqtq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhdqkua.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbsdrzv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkzodgc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwzgpfb.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aervrejg.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnygerf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrobituu.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2flwkneel.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wcaguovq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2euykcozf.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcizlil.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2itlqsaym.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbczqhwr.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxorfmj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pndvezhp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uemcocgp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjybpmw.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mrckkkau.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayliufxy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cnscrgrt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxiqeold.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xswvqtdv.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpnamwr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfrnaxs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2clvhubfp.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdzcgca.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyqyapm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjqtnvr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cabhsema.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vianivvh.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ircqvvpb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ketyssyb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2wkevbuab.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyvcedt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjngejp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfguweo.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjrgnnv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qpljpmym.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zlekdwbf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bpenqvtr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvktvoz.html


<!-- 参考信息 -->