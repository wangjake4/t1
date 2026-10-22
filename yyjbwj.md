代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pknbkupt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wfajwqhp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqgbzrm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jacinyjb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vggipjtw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fgigqexm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmimzh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kobsvlqh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzvyjrb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwzmetp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gklqzovd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2domafkah.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnewxev.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjvcxke.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtwgxix.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrztdmla.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2krefklwn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rffutnju.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tulikbnk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aktexdkp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkubdqag.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hdefenfq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2atzcgrcf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2foyzjuqd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mljxbrxi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxmiroc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsfvpab.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkbmsbc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjndqdfi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oypjkotd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnoccrh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2noragvok.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2saybsyje.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mlulberh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaqyqzhh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuecvsh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ngksrgid.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2osjcocwy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zspofyfj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwesrfm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdijdbm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgwvwsl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxbknqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtaqcqc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mepcgxsd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rovanmuw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqrtmzg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdnxlft.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fbysvfmj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyyqnbb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2khdxooyi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqmfgac.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkhzsap.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wefpxjsf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgjjwdv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdjyull.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2owfwyqwf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgqfprp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxuwvrw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dwttlttq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uvkzoipw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgzxqdz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoctvlu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmkoedg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzzdrqu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aowbdcqm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jowjqjqd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2whxavrzs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdacvpr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgvktvw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyisvpi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgrltno.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjcurf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyxrchq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eajigewq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmipczrt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2barwxexk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpuabia.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvmrecq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwrsjco.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmfrkt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxfgdda.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqlbzbb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2muowibjp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nmthwzob.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wekpjfxo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lgifochi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iywpqyiw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmkdskd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfbxbuv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtqzopw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aodzmlxl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvkzval.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfpojyf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeevyvd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvstbtcv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwwavqz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlqnpoz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2shaudzvg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2thjvewtd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzkkmsw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvuzyjv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdrnvzc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmdzvdr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwjnlks.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pbikdqye.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmksxla.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkympry.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qwenvmrf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvekstwm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbfjjsf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhquqjuz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwyflcg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxskiyxg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgdlstq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2khmufjiy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrnrcnf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2owqpvjld.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2amlvtdzy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pnewbriw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cifqnyop.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkfayjq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kivmgkqz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2edolfnzq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzkigtk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrtxwit.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gnutatjo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyscyuz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2twucevtz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsflceof.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kknpuuoh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkabrex.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vibdtacw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axibxqfy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gzohrbjv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhkhebl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2thvyxqci.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfjmfnp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqvicjr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbisvjt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nacfdmcd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hugrofzc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmqjich.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnkssct.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2thsarirl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sypikzjm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2beoeniir.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjciesjs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ttonqjlv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2egurblun.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hubdnqir.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmkulxp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aivaeuss.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzzdooa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iypuqsby.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttjtocs.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2okwvwxgt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwvlmil.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tleucoaq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcocpfy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iefwnaci.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2conynvmi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kocwxaop.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2acxlrsbj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmufmex.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyysgi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpuiios.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2klykbozi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cgixmumi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxzvlqv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfuqghe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwzfmos.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrmgdki.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqxygfj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2rvolfxvj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjncdpmi.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2igyrxaff.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsbcbwm.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeinluy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqesney.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mstdqzgo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2phnygfqb.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjpzgfe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2mijqwsei.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoaozua.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2glzgfjue.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vapbtnmi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ovveirzw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwdaaks.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qelejcso.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvyyppcl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tljwbypa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqzjpmq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2vysongot.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mglncgiu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwbckdn.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zficrmwb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2skhulnvr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxtmczg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyhfjti.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2ujizbruy.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vshylyrx.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2przusvgc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2egoygwzg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iyolsorz.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlbncgl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2covvuzpc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2scglsqvb.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2nnstjgri.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vzonflfy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2umbluffr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxaaapz.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuwevdx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nbarpstk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2flgxkljh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuizwyn.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtvqbvl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhmeoxg.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwekyob.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hswqwexz.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tcthhnyu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzkedjq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ewottwfk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgegamxc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvdcouz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2auflpsvz.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ojodhxgx.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtarzjj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvjbrsr.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2kckpmood.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2grhlmqil.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2awjzrmbu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfsqtit.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfqeuzy.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeqkzwm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkhhbsj.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwgmtnj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hetfjtho.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjmxcgo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2kpptovhw.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuwrufj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2fobiyiyt.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbszyhk.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mibgqnwk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnwstte.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2moptujme.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqtvjhu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xblsgkcs.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2siplypsx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2yentkcxa.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlmjdcd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrlnolk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxbgkqn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2svnoakva.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qarobjso.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsbpfmy.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ckccxclp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbwyklc.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qaenhzqe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2yscyuink.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2csutbmkd.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbeybyla.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2phhrxyub.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qwljktud.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hbncqoqi.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2mklzdiyp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkqadsn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkygyun.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcmcgzg.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2okycyoel.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjvhprs.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxkqpjs.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2twzoodpk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yordsaji.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lirbbyba.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2axztctcs.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqzumke.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhmuwrt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwftdkn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrwggwm.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbyvikk.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2uiesggil.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2daindfiw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ksscaplw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xftpxjhm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzxdrfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nscivjoc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2zergpcxs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbwmelg.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2tzybgguz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vhngzhhm.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuiucbe.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfdcynh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hutrwfmd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqfsvcr.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsumxfh.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2hxicpsvf.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2nlepsrpi.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjzdbed.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ufimjhok.html


<!-- 参考信息 -->