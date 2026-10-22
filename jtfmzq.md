代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpepumx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wempbnfr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dehomofi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2oovneara.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tocnanmt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkatnbda.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ussgehyu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkgwlbx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzdfxmx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyttsin.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwxfceo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsamajn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ndppoeey.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czzhlqne.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlcgups.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqkdfbo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iaukdzwg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwufbof.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqlofpm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjagmyjo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sicirlni.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqruqoas.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnlviql.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2grskibli.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbeyymq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewurdhon.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qakdowyg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2izbhgogt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixxkyna.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jaayetgh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkvvvum.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lucpgakw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbshvix.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dlseniki.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hczbcvsx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yodzhgkc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zprohmap.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2samsbhzp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbxfbqr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcztolj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrtynon.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syucmyig.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2msabigkd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izjlwxyy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vumxveay.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqhwqoh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwfqvyk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2szbolvyh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2glmovrsi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoalngl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyissfb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2flbdlvtd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlhfinq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxwlfff.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2amicvilc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtivmydc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhqbatr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuinoyc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqemtgsc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lejeonfz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bozffjzl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaawrtzo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lpilxloz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbwcwvs.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjmmfzv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmiynyi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2paeaxaep.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izkmbboe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqwsgut.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzwexqi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhogede.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yywavtsk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2laspgbxv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2radcmrao.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdcqzel.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkgizqu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpzeaia.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnzvhxj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pygodtxd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmfdnjg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmjdnce.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnbixtd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeupgsc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dblfapvn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ufydcjoe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2axropodo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kudopwyr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfraywtv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkwxawh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kfouzuci.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnkmzfo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2outbeozt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrfzuuv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkktasyx.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xripvkol.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwnvhtb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fkipuldb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mancnrza.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rccbxqnr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqmnlrz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uwznmrnv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2huzqzgmu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2knknaknw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxjlrxr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqxulvp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnufhfc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rphtehes.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbmwnae.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2eakmqkjf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yootosss.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2flcypczy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpdopep.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmahleuq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvjpmjo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwpsasx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yibfgwrv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kfenbnag.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2olfknfdh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkysrao.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2frnjzilr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2urkbkjfy.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sclfzpqi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2buudonnb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgjbiuq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hglbhmsk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmgnwoo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmybymr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwexohgc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnrtugy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2smzyymwb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gegnrgku.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnoqsgj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxfxxui.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igijtqer.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2euolshot.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrsmxje.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzzrnhm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2roltzmwn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2isagnidh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uydwrntv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2szpactsi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuzhyyu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2evmzpgck.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puvegubn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvrdwoj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2anfdmmqx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rgagevnh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvhoijg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2shrupxfx.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyjukyn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qdelkltk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2yenpbhmo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqadzox.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqijftz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdauedfy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnokdmbc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hgduasbe.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnqttdl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnloayv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hewzvsyu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyybmnh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2niajfvpl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vvewotgw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwapglpn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fttbpygb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyjwjff.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhpvjzs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrhpqja.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sioopead.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bktovjcx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcpuqxq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2anlxmabm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2esljkvoq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iubywohb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vjakbdhc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrghsaph.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jusoaslr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yommriuf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoyeqtp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmlbvcf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpdmvjj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2klyyewyv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwjngwo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2icomimch.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gweyxles.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkvmfnm.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjefjcr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yklndwtt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiwmkox.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrdgqcw.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oetydtan.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxagteqe.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2knphtjns.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2nabqntis.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybilxq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpkjgfi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtrqihh.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzxamtx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cxijjgjp.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nyntsnkn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvflcjg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2loaspboa.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmpuhuw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2laopivuj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkshkjh.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlzqdxi.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2skstiqdv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcdoaez.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrkbuxo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zoclswfy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mscxjenh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdklonkl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjjuggq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2svobdreq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhakbdd.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyvwtbr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorasrv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2birpzlpc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aojwyccs.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhanvcig.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gdflhiqt.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqwfhut.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaepgmy.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbjqfqn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2munlqtvp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2amyeshep.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eujqiash.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlhehlu.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpwlttm.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eusisemm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fusfwjnx.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcfwjywf.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhgzhcx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mserpivj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pulaemum.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhicpdeh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zatntick.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkqibgz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhdtsxq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2boclycov.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2mourplsx.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2evoqukoj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtvkigh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugingtac.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uarxafwf.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqudjvo.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2jzemnogn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmbkqre.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxmufpg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wiimzeug.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrsovib.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kggjgfrf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ebamkgng.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxnopfi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nniakjcy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qfktocfz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2czsurrbk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgbykjr.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqszjegu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnyasxt.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2saloiqir.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfesqkj.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2gijhbqne.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2eifawqoy.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mfletsup.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2swqjlkps.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbivpjx.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqymyqif.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrjicbb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbafkzh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkywgws.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvqbvef.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kigbuclt.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvwfybw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2slsmahkk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qflzwyxi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnpuepa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2axkecpbs.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgpyenk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeznecm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhlvsju.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2shdnibno.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2xireosxx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2vplkrwmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbuxalm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2swdicrpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmyhtqv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvsylvr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rguowyqo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hcllskgf.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhedgem.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xomzfapo.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2usleimkz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmjoixe.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnztfhp.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxhtgtf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2gecyjciv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkapmtv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxulpcd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2evluglwn.html


<!-- 参考信息 -->