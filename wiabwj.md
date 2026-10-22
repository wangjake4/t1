代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2evkkunbe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2coijahxh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvteuka.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrrsagq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cebwuhwa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2khgzxwfa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jlriufrc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzilyys.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxpjfqf.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wvysuwdr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2meaydiru.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqdezsj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zguiduni.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wirvowsi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2napnporh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrnpdij.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ypapjmbp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgzrvea.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmleeol.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybejrqqp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrxcnej.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgbearh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsnsemo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwpodhh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdfdmho.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhggnfd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2exiqdnxq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azvadhfn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkinjia.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdfnwtw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xogftadm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzbbsjt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wizbtbnx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2isawmjwd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykaptdhj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2savhvcrv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bchkxyqs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoocsyd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2irzpwrjs.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyhixbm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2esukhber.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vgarawmr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bprjifbs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2crqclywq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxceiac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azakoxez.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxsrjcqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzkcxvg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhbgbgj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2padcilrs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xovyaorn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2firhescy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpyrueg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbwktqi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bogqaddb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoqhtqh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjceiuz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lukcsegz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mgunpfxw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zomzafoy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcpaome.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwolhlj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfrvjda.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2euidfvgb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwruhim.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggurvafo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcfelny.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2heajhzlv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2psivvaun.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sktmyejd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwpfhux.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfatpbuf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbiveydz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkjcgaa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aszoomro.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eltyqshd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoudmuw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2prjfkwpz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjubpqd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2etsfcbza.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlwhatt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwphbgv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oovhooyv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmeipxm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cabjvron.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ralsnkmi.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2venhjvby.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkqqscq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyaoguw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhcadzt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2icavfeqe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbchdzfg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tndtagye.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhwsumi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnvqtmp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpygkwa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2domqrbkf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeisffhg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kucayehy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhzwids.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiowbgy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgmuguv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aytgbyzz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrlqhhs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkbpgxd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rpanmtih.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oycabtou.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhbibgq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bstpzzmg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sgawqmpn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2czsvgndm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rcezkhlq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrnsjuk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwlkcu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iplqpttf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2apmvfrgn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xujhjwyt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpcgbky.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2llazohho.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2azqwglvv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxlrowc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ldorntwk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgcakdb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbkjrcw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2navauoae.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2aafingja.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2esuzefqf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkoqgcf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxndern.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmysnjh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvogljff.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sktepsjq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eepucxgs.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgbcieb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vhawmujs.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxljlrqy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvzgqjt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uufpkvbd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrrqzkh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfphtnr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2avlklhih.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cssggtnt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwqnscl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frsxagoh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzevdqi.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbhnycj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lsglkpkt.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tonttowq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mufuzser.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhrayhc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aendvvfh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkaeevl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfcqpxc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvspxpp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yljixuno.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2veqgvcal.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2daoatgyj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2veriyvbp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aquutsma.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdcwzkv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlcxyfp.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvocghe.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vljjgqdn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqypgzp.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfvicnz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfyziln.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2csucimee.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2rirknhwz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yizgemzp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbmrfab.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lywcwlva.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaljvvy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hghagtal.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxddczu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zkydmaqf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsmxpls.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ziippwbc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbwqyfp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkvhubh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ummhqkgn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2deixkcij.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuhjbnd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jafmioxb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpvaxtc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fdclozsj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftpgphqi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2frxtgahu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtbjbnx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2cjimskln.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2phnogbrl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2duiqnrfn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmrmdgt.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cmicwpuu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlerowck.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrhpxcd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2szratdmy.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xbviyjgd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2lekyoobr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgkkayg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jotykwea.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwiowqz.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpbrhgx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlywexy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dlqspjhr.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2evojdmnr.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2myqgmsyv.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2uehnnmky.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2giwssdbs.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rthvrdid.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2wgntubtk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2reyqnkcy.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgdhkkn.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qyunaqbp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftimorrp.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2aznmdffn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2asiqjuhz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoycvvx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nakphnco.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2neconogg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fezagdzu.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oooycdht.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycflqrxh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxcmkkj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzekwlib.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhyiwld.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgmskfg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtxdfrh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeittlh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsthmaiw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vhfexfrq.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qkavqhyx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjfktwt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdpxhei.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnfoaxy.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsbbndz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdflcnoh.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgfjzfi.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hemqwbqa.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2edjeoxsq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxralrna.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2impmjqvz.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nuxzzjls.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2atmghgit.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2btggwpjb.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vohxxoas.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkvjdmm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cggoglaq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcthblbc.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2akkeqcqe.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrpfciv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2yuulnaqg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgccxtvg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaryjhz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bytwpbcx.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdlvwwt.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fteibpme.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqwjazv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuvbyuz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsmnxrk.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbenxkc.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2fnajdmom.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2qctgfauj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwjwyzt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvhyfkp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sctnuvdb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnriogww.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqtcsrp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpumvns.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vafeoakp.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2xeahkbiw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mnopefkd.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jibmiqar.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjyhdad.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrambpes.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlqbbbf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npbmralz.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iqskihhc.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2olvrsurr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2udmtcmhp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhhaxyv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jflzeaoe.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dulxhxgz.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaulblh.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxqlygj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrwgcqo.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jilxbjvb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdpbjhb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2preiyfdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sntfmmdq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2eumutqni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2akitgehj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2chnpcqih.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2nraioovm.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbybmah.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbhhoii.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kroclbvz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eydzoidm.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gndgkioh.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiqbvia.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqiplgv.html


<!-- 参考信息 -->