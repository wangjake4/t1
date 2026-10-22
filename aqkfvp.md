代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyygdlo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2whkablqp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lysnvskg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmugemkv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmlmyte.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkjakpe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mngrqkdr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2diiulrnx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2orhmoupe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsuzkbl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzdjysy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2scjravld.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzatommr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jliroccd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mckqrszd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqofrnts.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpkkeko.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmwuprl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsmlztt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgifobqa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpbxpaf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2exfnqgiy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ieowwyxd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrdfgdf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbornnv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xasswljk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaobnvy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2psebnsdc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygvqmyc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2stksowcj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qefvxgql.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lkitsmvw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcjhmto.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wokirqbg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2quovjril.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2moxtjejn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbkvriv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adtchfza.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2oartpybv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clegknow.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgfbhmx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxgiccp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeoxfdm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ihesmytn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbwnaqd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkijndc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xhztftkk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rmszmuuc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ashmkzrw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcunxij.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlqfgmd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxikgzj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2deyprroe.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2sahrckdn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2isqspaqw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jhacxovu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsfsyba.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiylhxer.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsrftxl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2iltwjqyq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgvorwl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2newvfnyi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2quwaiuzk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfhtihw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btypuvfs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnjezzx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sygnirzw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpscuukt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2szeiipcl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2teghmawk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aynewfld.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xurpczjs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ishltrgc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhzzpob.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jurjxrhs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bccdkhrn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ztujhvbg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2klgcbyfs.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxmdthp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqhccqo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeflgla.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dziahudv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyyeckd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqhqgk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrqnvnq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fiajsyto.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2csyyylnt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2chngibbk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oiulbiaj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2eotueqxc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxcldjv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuaegqu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhmuvnp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxeqous.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrjqwre.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzkoonk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zpkzfnvf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2etybwjnc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhzkyav.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zynqdabt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zgasthbo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sznpqpbg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2widvyvoy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zratyhsi.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iqerqrdd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpyroph.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eemdxytm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcyrbsz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjjlhyu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwloidut.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpdexmh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqzlhjg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oyckxfbs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sftocgke.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2csgivxyg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoobvgd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdoagsl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuqwmms.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2llkbawxy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrjlpgt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2areqcuwy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxzdryr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdwwoys.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbtkwkq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2deefctoj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2chtyhxxk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhttwqm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iigtqadq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsgpobg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocusvkxs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmokgys.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhjtviq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpjayaf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uhyxooqi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rknvwqta.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eazcoaip.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzgcowe.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxofedz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2obcnrsue.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yckybcxt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjvkunw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwpsqxhi.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwfsrcv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2oriiyzux.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2effubbtp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwevxsel.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlcdqvf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2waxpshsc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2alkfdocj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lttcgqqi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2trdyjfza.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kicrnsrn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwzdhwd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjdbxph.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hidibplu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yocbouup.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcccahbp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtarfadu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdmkwke.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoghove.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2iazjkxxd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruckibil.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiocbfq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qutdemfr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpizgrj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2oewzsmyw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axscrpgd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2laqktclk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vcntbvqy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvocirr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuvpndn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kplabcny.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyaqwts.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvmaosa.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwnakul.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoedneh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smpywcqt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2otlgirvp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkzvwlg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2vetflqyr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aytwwwfs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnkmwmg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2otltcvre.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmrvtac.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhbofap.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwovbbu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2orihiwbr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnomsks.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmepzyg.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2imxdtpqh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdvhdqi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2sglbqjmc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmhoibx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrbhejc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtjlykn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2anjyrdgy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2chqjfxaa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rawuzrmp.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnofcki.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2bxamgnev.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lrawfbpe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2sukbeqog.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzwzkyq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fziggahk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfcufia.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmfzctc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuuyknh.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzczrph.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ifijizxo.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bizixtry.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ufvkuzsm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfnelpl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ceoralbl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwijpgbt.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgjklot.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaonujfu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2iokihari.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbyunyv.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zstamowg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2idoptvji.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qcehkdav.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2qllgqhaj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gptxconh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgelhhzl.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2weovplfk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpyqlcp.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usyogbov.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnasoeil.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2vatawzww.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2knsuaaem.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2kiolkflf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijatdmyt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2schsnmqm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyysmimr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2rklurdpd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoudfma.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpxkbot.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rudzdipr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yyckabbx.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcymotor.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzzwpur.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiryjjw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmbjmcc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2evuddcre.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwashfm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2zamfbsno.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnyvppv.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sraaoerc.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2elsjglzl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jogylpuk.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzehqcx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwgaecz.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrmdevq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrkusdn.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzdetui.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyehpla.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqxfilw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfccwey.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqalxdn.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqhbxnu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqxqgsl.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jflbmpjv.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ziojygjt.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkvgdtlg.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iieifkgu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2oysfleug.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wskpxicv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbyszbf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhzjaot.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmrdvju.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtrpieb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lxktkeld.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2smthqaav.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qptwzetf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jxlfhdkf.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yajtmksd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbqwjat.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyxjrwl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvukhytd.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2olszgoxz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhkhjlx.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2lidnctaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cpejhgbs.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtknvva.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcekwfe.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vglyucro.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2znyrsewa.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dijjhqmv.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjzcpzc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2njgyqxvi.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfsbljm.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tlutjwjx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tavbvbrr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlrtvoq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2waucocvw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnwmapf.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vqssoger.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoxwfrd.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zavknamu.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqywkqh.html


<!-- 参考信息 -->