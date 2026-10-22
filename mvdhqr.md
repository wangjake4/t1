代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zjozfbvt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oocesiik.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gznmmfmt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhhkfuh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlkrqwq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2srxwgrei.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsywakqj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuygscts.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mlesgsyo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbgwgkr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqehanww.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udzmgzfz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nydiadjj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykblzznc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kszkfjmq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpybvcjg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zahznxzg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmnbfrq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsojhaym.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjedmva.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ipgoyzan.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpuvkus.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrpbeth.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyxahod.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqemvaxi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpzpusy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2unybjkss.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vhegvkeu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkxruuz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eojnpoxt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwewdgj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2shhogcjv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rookrufr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlrimgf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnqgtpi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cireaclp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2okzkjynx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2etgptjji.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtruzdu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vpstdscz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzxtqhe.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnauhch.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwavczjl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ydcvitct.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwydxeii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgurjyh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkecryb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfdkcci.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gplvndxs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jhoteadk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2igjsyrsy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfckfob.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lggkfmsl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2msqtktmo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbxgbgc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gltqzbna.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxqpiar.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2estgqupv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xikwwqbp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2loscbrdx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2knmfztuz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jywacdpy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgcfmhu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gobhcisw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2habdhdzu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdiofmo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnielcr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdanjutf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pwsjiuwy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2prkdwele.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjsmgau.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2imxbcbmn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqiaiit.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuyvwzm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bubksdti.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgiikyw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vmftknzf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjvjeot.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zdptmhjb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoamghz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2crdunfmb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfprziid.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kumbubyx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qakdwkpe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnafoht.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqylbeun.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cefrvsrg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ealbznbx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ksptnfdk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qulpamkf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwqhhgy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aenzxvms.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jviyghvu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wudaxvtw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdsnzidc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkigylw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyazaiq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhzohscx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dculoedv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hekvrxmc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2omxeqtul.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pisuknpc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsyxbtq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwfvbbc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2oahxtcug.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hehyjxvx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjyqphm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdslfrbg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wffayhho.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcuzmgz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2srwqfctz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oltfzfos.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2walxexyu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2owlgobdq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxgcldt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufstwwfk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cctoixtm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmztojth.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwbqqyy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqweolst.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2htfoxddp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zhoeeyqf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xucpzamj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ieepsitw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpsihuo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpqkiyu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2exzjssml.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2onotpvqc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnbgsma.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfpccns.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnofgbz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pseochht.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqyqmjq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezclhzxl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zonlelmh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kicjqxum.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgiwoguq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvbdxsn.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2degdzacz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrgxwtq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhohrxd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaqzfzx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkmstei.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fosooihd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2taexkpwv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fksedbaf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kyotquvt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alhvczvm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ctafsurr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsknzcpx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dimwrlmh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2edbugaki.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2pinrxoes.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jmtjgeyw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnvofcg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbrxcfl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhfhupr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uadglhds.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2asbzrqef.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtgwjjb.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgvnzyp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2thuhwhhv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2luqmbfhj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzunufrp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaicuwl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gchqfgib.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkslwxq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhehjoee.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmbbomt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwisocju.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2gstdmwoa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2apiuejsv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rygpuhzn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyofkdg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpzfbda.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2idhzixwm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2kalejhvo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2htanjpdw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dlewzhlg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbxkqbe.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hvukbzfb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vaovopsx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hkehqhsl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjbohrj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2btlptdyn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2akvrighe.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmsljjj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwdbigj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bymsfqiz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tduxwqla.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2veadadcf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2buamlshf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yeocojua.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gezevire.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfyxvzq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2kumgfjwo.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2lvassmqi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2exrsfxpy.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nzftuijb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lomegfxr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jptzzjus.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mctbexou.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkuwosv.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gmytnkot.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsrzwgj.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnvguqu.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uylaotfj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxunraw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxrcxh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zorkitoa.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uauetrhq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jejgfaur.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmvcroi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtejtgf.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbbnzyj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaeouwh.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmardvt.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2giqeavgw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vttonjng.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwsarwh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdafafah.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2badccfmy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkvtuyt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxljjiai.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xpycbkby.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgzxwur.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvszbut.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmrdmkw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mtegvhsl.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpuapmu.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2phmouznz.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgzbkfc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhafzct.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoajajx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apfxwmms.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lesspxnr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfsglgd.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrhldta.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xvznbwgy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqcihoy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ncecmfvk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2blmomhbr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaxtxac.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2jekeqexb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyluonc.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lxorntjz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2abneqtqg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2popwzsoa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fasmhwsl.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2yutnseqm.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjxsbiy.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxtwthx.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsnvivh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyqakhc.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rrxelkxq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2inijlcvn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2koepmnhz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjsmczf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tqignuci.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxhhfdz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2iikjtgjv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhocoxy.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtpmgko.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzrdiix.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrmbhgd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsejivax.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdarkjf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2huspmojz.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lenmsuss.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbbbcks.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2aykwperb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojspcaxs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2drytirqd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhcxqkq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qznviesz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkixzev.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpbeaie.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmboawzv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwtrxmm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujufwlqb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2oatmqkdk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbjgpgq.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrzqjdk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaejmjf.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaarnlb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqudmew.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgviplab.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xknitzgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svnfitdj.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkimosf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdjpvhs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmbapni.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmnqgad.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pcazfqcb.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nvekulvi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kufbtevn.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfhyikw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnphmnt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zvofzfly.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcmxtjj.html


<!-- 参考信息 -->