代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lutzpupo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gurynsza.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwsihgf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoqmvyv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rziglmyv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbgflds.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bdiqtkvc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaeymnr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxgbldi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2briavqnz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrnkxgv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2powregqn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aprzmwdo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmsqbwz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpofrhj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbxdhthu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdbnltd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxubno.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyyozbp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rslteuvt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykenigqm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfgyahq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsjocni.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnkvkjs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrgzgne.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmtlkan.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvtdslq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zmteshqu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmtataj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2txwalwvg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwlfxrsr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hexqcufv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxxcjsg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtvcxsh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdcutdg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rquemhth.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyopywl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2juaxaurl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcpxpis.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2werxgfff.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwfwdpb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aninejfv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjfuicr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvhcsup.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2orngamyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxnowat.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvawexq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzntwnux.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2indyssty.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tceqlshf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nrudmjsn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acfamcdc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fjilaaun.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vryqkaui.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhusebb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2czxwopma.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iavrwbri.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgnlgnw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqyffal.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2twkcvxjd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxlhpvw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtinmut.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aebtqgmm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wleoieje.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rcomzgkj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscoafjs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zifvwvln.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2brclpbpt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyvumpi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqynqxac.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qobzihyg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfvuzck.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkekrir.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yitenyrj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqetedcb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2irkhvbko.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jqouugmq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2aopzigzp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxypxbi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gviizdmt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uhehragt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kufaiicp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqeihoz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjnqnch.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcfhcep.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2slaukboz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbidfoj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsexxvol.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wskihocj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrnwbog.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ptparxkb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hpaaurdi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muaorxmg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nsocvypt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2akovwuqb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2icfexrci.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpatgyr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfzpuvt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjdtxse.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzbusjj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kldunypy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2okomymqp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbtadoo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2netywkjy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbnvipd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfbhrap.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2upsgdocs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyckjtz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rwujgnpi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfpgjqo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xonjdhdf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dowkvlim.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nmybiscj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzblefbg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2repdltyc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnteyfjc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2aenbcdcs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzodowkv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxpzvkv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjyzsbt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkjiewl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxcfydv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvstyid.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfxyebo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrowcxz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwyxmwj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjcqlyk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzryliw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2heammczn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2icubqvob.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudpjxz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewtvlxc.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qupmtwjp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2grqfocvn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyacctmz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngiecxwa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqttueeq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qucxowsb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icnylzdk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2iaptsuiq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2miedntbg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdsjvoc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iismjkxi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrfqemv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2eopsmsjc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfpajhw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmvmset.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbqclnew.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbtsrox.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuthmns.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqizaueb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewawvocs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbpynog.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsofqcw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2unnrjwqd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2humjomtx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfhconp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwxsvmp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaeclsd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxfxbao.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhezvuc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeqpcsz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bksvloef.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvswlspp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wivyifdo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxwjpde.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2iizelexo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoizndjy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2msyghlgr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2icgepzkw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2vomqbwfu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnjbmdq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xeouzgof.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxtncuc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgwzucc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2znaihggo.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rplegchd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlevfjlo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2lypylsyv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vuudugja.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2eazteyws.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2juczewls.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgluecm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcvsaqq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwcjhzi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mblmzsqr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyqezrw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mauuzqex.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tdcsewhd.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufldcjsn.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dhljumvs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2yulhddis.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjuwrsm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvvuynr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mektjsxb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2prcjxowa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2edvtdtsg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcfogez.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2aljjqcll.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxznqxsf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2abanjftf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzawpdn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2okwkdwor.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2xetcgvga.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ngydsmxt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2tszfpkbm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyupeii.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2zsepyict.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmdulzz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmxrent.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqbogaa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbbeoyn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuffzen.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2shvteyec.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyuobkd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwitdzl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2prirjmlv.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2uglpgjos.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2zivskozb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2tyguwppr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2iduscxpc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikblubim.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jbhfalfx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkelrsd.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dgedfjci.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxvtcok.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmluwflr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqantwj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2buxffexn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2naafudbi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmochld.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcdbkme.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hniankfw.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2snwrdofb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwakxzxd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2exqdptiv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2lhujxxio.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwmcqpn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2utoeoibp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orpuhztq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rverqamj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mifqawmh.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfnemvw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2rritdnrw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xttrbieo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vgybthlr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlctrac.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2optuebpg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bqugygyz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvfjvws.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qplaifek.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2alhsycch.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2exrpkrta.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnrgql.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrrecff.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnicala.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mddyomrs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2odfvyxpw.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gburidmb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2tvohpvwb.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wpybxsjy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqvjlse.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pimyteuy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2hevlwnhi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxvzwhy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuelczf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxmwfrv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2itrzxwyr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vwohqlnt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkwwgbn.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwkqyqa.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2tiljycyw.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpfzkzq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqucows.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxhhpjq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuolrrn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjfbhbu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rakegntb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2esrmqdew.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvoainmw.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlookd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aejojuxx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfwfpps.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rptujfwu.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnfsmgb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsoutku.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtayzrq.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2iaulbhdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcselyt.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2iizhbdrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvrfobn.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2plojqmbb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgzjdoz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tczwrpsc.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rupbthoe.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcsvoht.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2lbstgkzg.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkjslmc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxxssyi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvpcnvv.html


<!-- 参考信息 -->