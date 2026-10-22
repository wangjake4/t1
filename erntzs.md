代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2suuplnyj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2syoxvfel.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2blslxvli.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxrgejs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxzmixq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poecchil.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2svozehit.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbupasx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kysssgtf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uybvppqy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlgewdty.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxywkmb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooalrech.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rerbzsny.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hxebshcg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yckddnqd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjclera.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxgdlbj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfjnylu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzokrlr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yunandkv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uktamiyx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2isugegzg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnomjrk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xydciuqa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwjzxca.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhoeosr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxldhems.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2anqrvfol.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aszorabr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmyxykx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2axcwwfxr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xokpmzof.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvemejs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjdjyk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwmbhme.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqpmvty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npnanocg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvmdlfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2halhroqx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwgixjf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlvsgmt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2szhooqht.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mtledjna.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iffwfdmm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjdkiul.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsckkow.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tllluygh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fglwtpmz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnkumkl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vytizcyt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2azvgyecw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjjqgap.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlechupo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfokwr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqdgxot.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kijfejlk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhsdipn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2umhysing.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkruqnv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkisess.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdsyqwa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnllvtu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfmiyfa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2onlnszxx.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcckwsdo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blbvrroz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmluzbwo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2recdddpn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqgtjvip.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmylsyn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2woomkuwd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jutgaket.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyodvbii.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxzuuaf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yedzztog.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpgxmcs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjxyvql.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgzqwxd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojuwhfv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2opxgngkx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jyygibwo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkarbou.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwdgzhp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wljrtwct.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2luuibcky.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjuwquy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdickjyp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcjnhdd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgnsiwf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdhlpaf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbnlihu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpdpkta.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qkukmdch.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jygylywv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2plebimxl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sspvhxmo.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hopxwpnk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2imwylutz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgtryzl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqjlhww.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfsuwqi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hetweghg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdswizi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwgxluw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bupslgqk.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jweepmfj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2twdqsrzc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggviaebh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkghqfx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kawoogxf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmybnqas.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdomyxq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoabogm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aozjaxoh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfbjoau.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqumctm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyokpnne.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2twtvktkp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qddnzbpu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oojmmubs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2utyxqncy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfyxnth.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbtnaam.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnjlqlc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmgnozk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfyzidf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kumukgwq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jvczglgy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmcesbo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cryujmkw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxnfovj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzwpswr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hsioqtvm.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2badmxfkm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omxktivi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvvzasb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2doddfkdo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqhetvm.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2koejbtwx.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxanegc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjcjocoj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aonqtahg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxssflrb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2awzebgnq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tidhnbxn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2clerljzw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgbxjph.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgdjfke.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhbbfse.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2etlxjjfu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iggczsvr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqpvzgc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsiibss.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ajswltaq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjsewki.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2irinuvze.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcovayho.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2svuiwvxl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldatmdqg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ynefzbiq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkprxdr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zccocaou.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvcqqnz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgjvgev.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2idrsdjsv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mffrxbkc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqfzzsv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnuhlnl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlyalkp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmbzqjt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsrrptd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiyoplw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpobuurl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2furebshe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijritxbz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2awzgmwlo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycsdqpyt.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpexigs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcdocgm.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcoustn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhtvqmu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2omchkzxg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqyqyba.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sosobyec.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftosfext.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xtggjrdn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmrvqpf.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2rhveaafv.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2pcierzyz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrkkvgl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2fevymfzy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxmacvs.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2eoppnokj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2deyynime.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2serklhmv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2vzavteyo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqorpf.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmhcuak.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkfduld.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ztpgywfp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2oezyouoc.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyidfux.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvjbnmf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbbwyvn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2eelionri.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2trlwplnp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrieffx.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwpzrag.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhpdusi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2potcigkm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aenglvgp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkhjlrl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2cllqxnsf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhlhnlc.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpaitefb.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cszkljph.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ytazlfae.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtrfzvh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbzocdv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhjxvrm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgcltzx.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ildkruhx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdcqnjw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dkidbtlg.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2miemiefn.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ithklcab.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jskbjfvn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2eawwowtx.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uirulesl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2evitwvfk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezcovfi.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2escadgke.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mewcobbx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2iodpwawb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2nttneher.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrtrqtj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rozregai.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eugmabcc.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxenhipb.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jtttocxn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqfsvez.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsdexuf.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvlxvr.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmzcloj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2udffnhbe.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2exafrnje.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbexbpw.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpypuno.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhppzcf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cldnhcfd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2inmnyupv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2zcsicuwl.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoehjdws.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyswccx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2jjngluva.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2drhdpggg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxxptet.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wukobrir.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2wchoesmp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlberck.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdsafhz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyjlsgz.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mruaelbm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuniaql.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsnyjlo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcsoflt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsmciab.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jikdflmn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkrzebi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfpjdbj.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eofcmrvg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpmymqz.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2kawxkyfc.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wzraydve.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2oumahsft.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2riuzjgva.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2eitqjvez.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwkgwb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dujhouuh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwicfwjv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2ictkxjpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fyabhfgd.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmlgtr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2qlskklvw.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxaaqdp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmqlgwj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcjtffd.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvtsohm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwynggl.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2glkcbgar.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyfknqv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrajuxy.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcepzff.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2zylxyhbs.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmntiik.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2eceprkll.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2affcjkam.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ommbubja.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rftxfchn.html


<!-- 参考信息 -->