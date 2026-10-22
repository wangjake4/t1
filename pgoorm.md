代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbsrcdp.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dydkteli.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2llqrbczr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rixnveok.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjsxano.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qikrorio.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwwhjdd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dggrpgjv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxyudzl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mubqetmz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uzenvltr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hobasvio.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ggoshqps.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhnvjzl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnahfgu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvydyar.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thhmpiyj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpthvqyk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juavtavy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzubmffo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buywtvte.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dixpzfxn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlaoyna.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ervtpwev.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtkhfrp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdzxbzc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nffckmcb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjwciyw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvtmnzu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzykejk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tggizlry.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vszrhbct.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxwbdgv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeqttxk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aujizrrl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2owcbwuuz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaykxeu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2apkbvqvy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iecilinp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2framwzot.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbybflmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqndyhp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2emumaoez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yklpubrn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yglpgmrc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2faofyuzd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvnnscz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xfysppnb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yakrkzda.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tugzaxzu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgucmkh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2thokekdd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsptxlc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhodldnc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ueejmxmq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnopqixu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kilgynwy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2akwvzwbe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blmsouxb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlfnxdv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgcrnol.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaygyyvq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfngfvi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaprjqf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2azmycjcs.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsbuwgh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2upanlfnt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsagoha.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsoyfoj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeerdio.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsfbtnx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkjkhhmo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqzicnq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxsegwk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hilokjah.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2smdokfyo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dynlmvze.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbkapiy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pqduwghs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdsfoao.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2igflqeoa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gthultpm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeidylc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhqxciv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiqjwcb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvoxozs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wlngtxov.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wztdowqc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eogqlwfl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gbozrowe.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2occicerb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrsqtvt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwhseqs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxywhyge.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cgraxmfk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxcflmk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmabian.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmkhizk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrnxumy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gltxoveo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fbddcqxm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2evdzpnxw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnrtdky.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2utbcrqbl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jizbbhqe.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwpendu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2shlplrjz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvahnah.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxavvkm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwhakmm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rgndxvwi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuifddr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvxpwvf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnczcyi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2exmszkzf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jflelkwi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcxwmxh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmrjfkr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vatbitdl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ypubuhwl.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mielnklm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfqafhu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hhajirve.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwxxhik.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dlprigfr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkvhwly.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpicjgn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaknqcw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbvxfzw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvfdniq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvzmpxn.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2smnlhiyo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erwyvxca.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcpubio.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiunrxk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rkymarxm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bymwsnhy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqnffei.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sjopdtal.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umvbbyuv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2csrixzkj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fehvjrhb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nsveichg.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzuytjw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbfgrkq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjgdchk.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kheppshe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2chnawhmp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsyxjjm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fygthgxc.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkkonzd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2khoaoqai.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmaqcrm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdeetxa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovshhuly.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozidqrtw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xizpkykn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcbczap.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vurozlgo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2juoddhcu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkqytbc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvzhjjv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2sltdvpdn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqmbsuow.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2elkvhtig.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xatamljz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqbbvld.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfqczrg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2doinekfp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxebzrm.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhdsgpu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrmzvhx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjdaown.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtycgdov.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2egipaxli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfyonen.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwvyykx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2aadfihvb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwoadjt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrhdnrx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lfchsqjt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuilcrpf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ogseyguc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxsacvd.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoobrlx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpivtekd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxvjdwr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ljorpkih.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuddtdl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2izmsvrfr.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jivirevh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqzptwh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlcrhzp.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuiplvp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvkrlyi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdldglj.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2aadnxtvc.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcggbol.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxwgqmq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2atnejpjw.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gcenpwvq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgjjhvj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjxtqmp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2azyyyntx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2okruivvx.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2irhbksfw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqffixo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvsiwso.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2rnohtlws.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2zvyfgcya.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2mpisinzd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqslfzl.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qvichrpm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlcatpa.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeahsta.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgnnve.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxdgyxp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgtipja.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrphzpr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqupykv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyrwfms.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2avdjthah.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xempwfmp.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmismvnj.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfojjyhq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gmygafxk.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfefcqj.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbcedcw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwirbog.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2qahiuziv.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esklbplz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwtlxou.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2cuebutnc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hpalylmu.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2oajzjyzp.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yspevvjd.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlxjjvo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjzzrfr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fytrwzxz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzlxfjk.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhraezo.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsezcak.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpsbkwx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhtfeue.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdufrbb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cydphagr.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wxugptps.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzownmpf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hbppuaey.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqewytmp.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hsydsxpx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2snittdpe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tivshayr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcrfyrt.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2srykkavc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbodoinf.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdgfexe.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdgomgj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhvxeis.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2coupzsjx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtokint.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwcjmdh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwgridf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaogirg.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dfszktxj.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsssmir.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2mywkmfpg.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhfgvgt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oplgxwyd.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhjqcdl.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ummyssky.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbdygeo.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ufsxltic.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2alovxwqo.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2kgerhdvt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdyjlgu.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2likzvcxl.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbbpvhv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzcaozw.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zflkzbbk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2pedslkgi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2mswudbos.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2wugjyseb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzbjvax.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlakwfe.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uokdaihi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuqdtdu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqjhcnr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkphjfj.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlthnwm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvvbwzr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ippetfil.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeannbs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nepkugvk.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2awyviksq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwxrqlc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2msefdmyv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2omeskhws.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ryloddla.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrmlsuu.html


<!-- 参考信息 -->