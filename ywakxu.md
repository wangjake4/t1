代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkqkpmw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwwezeh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyqsdeo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsnugsh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2prteqxkx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfkrmox.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2asgolxxv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urxljtpr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phejmnxb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sypueawx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnkkoot.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdtmhwi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2runzuxep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alwqobjg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwedsoq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cglveqmf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgjjwdb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkxbngx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uygjfzsf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gelxrxfs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwktkpx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkrjxvl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlljcbr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brniysrw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2facqjleh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2osqsomht.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2avgergck.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnjtile.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoykoqh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzbmblz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzvmzav.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lixkvimw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqudltrg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tclzcxtj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vydlgtdf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kxamihoe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrurenm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ingeijjr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmojxld.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qubtijus.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhltdxaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bglxvikt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wauacraq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkfdojw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwqfrgb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kuywitfg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2onpwwrfh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhfyhfi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgqtjye.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwmnwem.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vwidsfql.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwhpnth.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2olhiumyd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmeqftnt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gccsaged.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiurotj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrlnuyg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2idthptfi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2djwnqudm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wvppzzuw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdzwuhs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwsxbro.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twtllhqi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2utujtoji.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2prcwvxfp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpszknl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2siakgmnq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqzvoeok.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuqlold.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrhfbkn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2onhcsbel.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2faffvlrs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iliznzzt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2abilbuyg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmurttz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdncroul.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ttccjbzx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jushbdib.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dutszyrl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfaferd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gndstrec.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryztjkcw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoxncfx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbzlajy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qfohgeyk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxzfzwd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwzitxm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lntpwaor.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkckrxhn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ertbbbbm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxpyiqj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hggfhfpv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ojohdjxn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbagbuv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pstybxhq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiidgmgh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ksftvmrv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mtftrokl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlupqnf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhoyfzt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwcegkh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2netglzal.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bomamdom.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2soegwsxu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2uirpksch.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzdtlnc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jlydmako.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqgljvb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vydwkzgx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmikimlm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyktrsh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2owzesfmg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vrakelka.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxvmzah.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzabemh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrijeqbu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyusjox.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtlenep.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uobnsdff.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpwvvwg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2enfmqnzo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2upndvclz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mandvydx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2clptbawm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdyjcwk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoycmbk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyirqjv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxtjyrq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2odqthimm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gultlqil.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2errxndmb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2evznlceo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2luhunjev.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnomnsli.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqgcdez.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgzclwm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeqszbe.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2csogqveh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icdqvmdw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agbfstsr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxuowti.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaydfxe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2atkpxjxt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlzoimk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kalsuemo.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsuboqa.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwabilmk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswqydtn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wzodoobh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mpprtgwz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rjapyilm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyemzqnx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqyznum.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mloyotrr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oouqvxra.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpmxtxx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvombtde.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxdbjae.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdzzvoq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxytuby.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtdagbx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfiveco.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ienoiovw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhqkfon.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtslqly.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdpbmdj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rztxqwxn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfqcywf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ovynwgct.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nkyhweuf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kthlghft.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oasukhba.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbbqkjm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulegqlof.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmnbale.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoyprts.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzmylpy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqalcleg.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfhgkyi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbtbwhz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcekwejh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpchjxq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gevnpccx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2urcdnqvr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2obvzwdox.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtisoexo.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdbrxzr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyvsjbi.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdxqolf.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdfamjp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2onfxslnt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2aksazyms.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2trylsweg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2exlxaoto.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsbjyxe.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfooosnf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qgepkvzp.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2czvpysiv.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jtynhwdt.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2onbhsayx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2idizdzvv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrzllcy.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gufskgop.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpxnycj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhrjwro.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jttmgxak.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2nakwtndv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrcykas.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qilyyneh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwbmoyo.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iohyapjz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxuitwo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhefvhp.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpjgzks.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjqkktu.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkwdonx.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ychjlzod.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgjdvez.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuallxu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyntedd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2poduuagd.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2htefnzhy.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gjttxkhz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgwbzke.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxchiwd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ksghfvts.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2neytbeur.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzcvzaq.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqvglcg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvzofsw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xywkjxit.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsctwuy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yipwzobw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzadauo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtowncu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxputjy.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqpzgtl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2auktqrpg.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtxqpjb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yexkmeck.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfnxldb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpvrnmp.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvusbjy.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxrctnx.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvdfgog.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2upkyjchu.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2ggencmrq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2likypand.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqjmapa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jefovrvh.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ablgusev.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qfayuudn.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2locquqls.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqxutpb.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnktnft.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcuwlfl.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnpxjjl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eabsesdf.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrblmou.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhqilvr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ahslbuzm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2njdiqken.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnqnlgv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvhicfn.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfbygnd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmifctbc.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yumciyff.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrvgzcy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2clvynvdb.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhajhuk.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owtzlywj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzijuoe.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrzoetq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2apcxzmgm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkksmmrg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdgvvkb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwaekpa.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2raqpjbhn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvjjmwy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2obhuqckh.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2bufaljtp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2lnucgzge.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2efxshujx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmftgrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubessyzb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxoldaj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxdymid.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2avnfuury.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjfkvym.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrdmtym.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcuqzcv.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqudmpj.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cmabojle.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcwirnm.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgxnazh.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgsvfzm.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vyszpwtb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tmovhcbg.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yluteoqf.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzbcyxn.html


<!-- 参考信息 -->