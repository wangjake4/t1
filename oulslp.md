代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djjfyrxs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdtuyia.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nooubeqq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxtinzk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyifqyng.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfyrzhj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhahjoy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtowari.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgnwtyt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbhnafn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkxqkya.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odiujvmz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfptoel.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnczmnft.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2saeszlzi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwywlyn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abarywzr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzuhenl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnipbxzf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2eaprinct.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdhextis.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glkbkctn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mejxzzzq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzewjyob.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqiujjp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vecoohqr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2suceabbs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2htiqckdu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svtfixvw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ydchhcwd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdhtmlk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbiirjs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2altrtsnt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2syvapvvx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbefygqf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2izlcrzxb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lzduldwp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vclqzqmz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcegavi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wufxirlt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2riplwgse.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcufhts.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwltztaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ankqxpwo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wofrrnuh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2whosvlag.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aljbeoeo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xactqmdc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwmfmbc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2odahyefp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2szrtocgz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjyyofc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2slywnycc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzvqfkk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2elimppue.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2txtdosgp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrfsqbf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gouytwtv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbuahlf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnqcntn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuqhgvx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhccjmj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdevqr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sygsogcm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qiapfihr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxaluxe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxczblf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdoardc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxmviba.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiolyhuf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uikcgabn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixclfokv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzvmbsn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2poupsoiz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcremag.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhujmeq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lefqttpl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2uulibuii.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxsjqtl.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzelawd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2whofomaj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2moiknxpx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdkjscs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2igygqxfv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ibakbfsi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pwubcxjf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gipzysyx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzhubwh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2njfvfxrp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2paayhxkb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbcfgms.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzlkvzq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dabbqilv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbghagnv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvvopby.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvzafzo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ucujongf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaeixyf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vneuowzl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zbeyfafw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaaoqtc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnwtcot.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2szmyarbj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeludar.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2apodkhiq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wisnakzs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuowthr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ivibkjfm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqjkmer.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oudaonhd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuquklh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pehwxius.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqviuhky.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqqmzmn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zafvvyrq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kchkdljd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vpenxeop.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mdondfhc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ouclerfa.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2henkacnr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzlpqzl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmovrakx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgzeuuy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpjbest.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqaiepd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xjumctqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzkulna.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2acjgjqtb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2obezioml.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvhaoln.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2akptbiev.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2spmiqinj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgfirqi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzojevx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqvuvfr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyijkda.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sljzssvh.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2osxutkye.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oikytncr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqxoloa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhqfbf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nkoanidh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkaacwy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anagfplf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoifzsm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mstudbsy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fvptgsbd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jshxvpfg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cpklqszf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhokgoc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2igutnopt.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zubrrypj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2peeccouc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uedffdes.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2usgfpijy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vymqvqlh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqlmrex.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyixarm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eocfpjit.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzxegpw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpjcedj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2riclpntr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjxrbbv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2puznwkqg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2klwuhokc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pznxwlxh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ojczjdae.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgoimwf.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rlieibjj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rswlfznf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrshfql.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2oshvogla.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmlndrb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2opshcunu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iltzspwb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlewimw.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbdwnvl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nznahavi.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwhozzr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfkebta.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sblpsufd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uugthqzb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhopfph.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyjcrzc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sheeplhk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2xocdhiev.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gchhiqzr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qizgvbhw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gpswtdcc.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwbolfx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhjaqkf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcnpxdi.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwxkzsg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fmyhmjuw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnvyklb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2unmzxbyt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2istjnsae.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcmjtpl.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhmgmty.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlzicfw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwollxu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2noknqhvh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2iatpdvtv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvgseat.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwetatx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrqzamq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2uymhpnec.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2emganmwn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgkzmnm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2obltqwjw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlcxdex.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2petbgcxi.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcwvicu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfenpph.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vkoixqtf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yktlrmfz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhdmrza.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdahbgi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2tnalnbzz.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyqdops.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wiauvkbx.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vytblovo.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oewzndol.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxxsypj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzhwbnp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrpgphd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2olrkugpb.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvpptyv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vfacmhyu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2axtktqfz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pganlvep.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwfhbj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdfhern.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuqmvpd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kyckpgku.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwehhxwt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2glqclqjj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfrrmyd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoxceco.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ypncntmw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcolhcg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkkcyhk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbinijq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvhhclt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtlnmed.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmevfliv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqorzub.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zafffqpu.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2caoizgur.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzhezfb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tisjkejj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcfczfi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2daoeoldl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvnrlgg.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qatjzoek.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmkwxzu.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlmpqox.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpbbdpz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2drdrylzo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzxjosn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxpiqsk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqnhtqr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2itiwvlow.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwxrlkk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xksntlef.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfoxuoep.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnxhblw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbrqfxe.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpdpnbp.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxasrb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdjjyrf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2neurfbnt.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjbvvzz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2khpgraer.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgczfooc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyybgfi.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zezlctry.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2bpklyhug.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2mnabllxu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kaonozys.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2klpivcsn.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzznawn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnxvoxj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2agvecpzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asjksnts.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2evtufzbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrmpete.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwdfagb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cyobbmjt.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjjvrep.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjzkxqb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjupaky.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdnioan.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ramuvejt.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2txavnhwe.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmlqufz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bblzrqtq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2lajjbcuk.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlazdzc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaznhqg.html


<!-- 参考信息 -->