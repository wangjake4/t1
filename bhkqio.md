代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfseovm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvuxmvf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjrvybc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjobqrwk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeofdml.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adcwnqmk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaumbjj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnignkhu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbjzyka.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uweavtap.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bxemyyer.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcbdesr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdjdrdw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpaggeu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2emyogngw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmcbxyh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkddkcij.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuzmcdi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnralop.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sncyxmjg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zuehktny.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xkicrsjz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgssmoa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sntvnxst.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekpkeqc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhaypcs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlycake.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ecizssak.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwaxbynd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jznajbai.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkszxamn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yukhjleo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdjfoaj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlkjlts.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiygyjto.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cysoszuu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyevtqaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xayyptjy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jngbnznj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tygzunkx.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjiiesb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2khpfstgg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2doflxfvb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdcallf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbzkyls.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpxgxtz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrefmch.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dybwzfkh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmoarxx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qidoopzu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqelfot.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkrdeoo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ippigcsb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2slxgjosx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwdwtai.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2acdoyrui.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjdeknp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlawvtid.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uezmqzej.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uahornzz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2begggoal.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtijmvl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ukdhpezf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2glcppyib.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2brmjdkmf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxyqjpa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyrlnzv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxwwfli.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qnacamzp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sykqlghw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmwpgji.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzwmwwv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxipxwy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgiudqx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bobfybea.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2blbfkyhx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2nybssuxs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mygvsgbv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2itpkxcym.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ochvlmmx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbdacmh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2adacxvke.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dlegsdqg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdejamj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdmhchp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wacrtfze.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efemuimh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2teyxmadx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2albxuarm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qksevapm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tzieypaz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpocuwl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pzonedym.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bskpwssg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeukplt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyrierh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wfobilot.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2baaetrfj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvpsvst.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqshdixh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrhqctu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aauroesw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxehdse.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2feffgatg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnrzttx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuwcqvz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fooeljqp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2byxjalcq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cnexstbr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiecfyg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgomcdga.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sftjdnlo.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ovkmuuyg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxffnfp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyppvqd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfeajnf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2grvqvrxp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwoztnwn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2huyuzzec.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dusaltct.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xbttxmwc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iycfolrr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2isxeyqgk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrnpbeh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgtsjnv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqknwcxy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqamxrsm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwqqlbm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvvsphf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qigrxqaa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgatqrni.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2okawmolj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yqefcrkw.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmaiciq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmaifll.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkyoaxfi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zjctoler.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hzefvivd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zabwbdla.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjcjncs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiscdes.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2laaanutk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fanfyjax.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqybleko.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwzviij.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gdskfepg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2scewvyhg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyguylj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rghglinx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpclqnjn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkdvqvt.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiphmgmx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2daybuuwr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2afsitsvm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eywqmfmy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzemjvwz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpcuurd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmaporn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2auwrwcag.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbiukph.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpaianl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgwuodg.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ocixzrty.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ticapgzg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvfctpx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqgdwhx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxqkfvq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nleogmil.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pwygqjjn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnzitso.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hrviobjt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdxgkdt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwmxijc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2irbddhln.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sextnxxl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2unlivahw.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uorgpztd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptusazrv.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fpteufyj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pabgopep.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwggzpa.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2spczjztv.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iigneliu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gpaoaioq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsqjrla.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iejcfyxb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvqzqol.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mytpjwol.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsohhgh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2frlmtvmh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxkwawg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lncooeam.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jnopqebd.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlpokda.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2joababnn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2praeaozb.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrlfhll.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2smejifqe.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkwcjdd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzjvarp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2afbkwcvw.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gqayunkf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfbupgf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uefsdgus.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmenwpf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zracyfiy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyunsbo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2boafzkfw.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqvdvqy.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2adxusuaw.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sgaginhp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ndprxejr.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2urwyujew.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgcmfeu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcyxudw.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpzyfyt.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xaktmyef.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgflkop.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2htpyyolv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdnlavg.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awbphxmt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2lfllklum.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2cfafkpwo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwlgqpn.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbajtq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvfuxob.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxzsklw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwdtjfn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvprsum.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgoibdv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sspxwjji.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvgbvcd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qtalhnau.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eswnuaue.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbuzysk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2buiziabp.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpozszh.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2divpbohx.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxntsm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsxxwmg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpjkskm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkryzct.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkvmwil.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2eogqmdni.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoqpwoa.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkgqmqg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrzdcxr.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qidpnugi.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oadgwotn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqhvnoo.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bixmaioe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfgmfxr.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjecekr.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxwwarn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lcteqgvi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlpaoqz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxevzhf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtgsvgt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgdhval.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2haaiwjfi.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhhgnad.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2nctxfkbm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2pvttexsq.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2niijkcwo.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tujhfofg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrybeeg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kglfwccr.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuurxej.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmkefzp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfasqgz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfudxfub.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tycdfdux.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wxplugqd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwfwdgn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoqnbeb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhspqkd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdlxpgs.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyukjol.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgmzxrp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2spswzwzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmxoqbu.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zybfabrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwelxbfp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrsfzar.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkfnbae.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bthlzljm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2idwxfhwk.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgwiljk.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zddwtbgi.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qexelagz.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2avzyjxsq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkztfrj.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rckftejp.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2qukrtlwt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgidqru.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2sahoggbs.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrcoggs.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hrundduf.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2iklhyiyi.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2efpheiyf.html


<!-- 参考信息 -->