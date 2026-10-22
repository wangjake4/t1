代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qnahpjav.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rubmaanc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcqoyvi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrzefyz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iatkpwgs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjxkiot.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2quvrzgqc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gulvepsj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxlhfpr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcpnqxn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ketrabnv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxyjoze.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yofhytnd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxaqrpk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngegyncw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfokixf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcvusrb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vfghbmkg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwxvmom.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2peclsswu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcfrzhb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgfadsa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2emlgvwpc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2roibcacj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2akyzggus.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdworwl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yooizvmr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2eywggcwl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2liodwuar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rktjinyk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gngatpru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exwjzpbk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rimvxuxx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbbgwzo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vdujrkvv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlywsfa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkrfzwv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fguljtmo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2opuntxyh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjyrxld.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjawmuh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjcygzc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wcizsswu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2azcjxayy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2odcmhjlo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzvvjev.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2euxkjaye.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyqdbtc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkrpqmt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugdgqur.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vbknlrog.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2izpfdtnz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwdzlez.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmzgnvy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xazivvrr.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtptppth.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qksxejdf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoyklbyr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mudqgukf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfeypjf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kggafchm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2upautpew.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcftjhc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyywkvge.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qszikhbm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klufseme.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2svxhqzue.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tadlmjqp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2btfyyxvo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcqdram.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdtvnvh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfafkhqp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpjjjqu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vemmjadw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnrucpr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrwmoiq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgvnynh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2epapuqnj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zotjeaij.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzgqnmi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbbysfe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2exazahkt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pehvliqa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnuftgo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aarwkohj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2udshacbg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxwhctk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbmvthm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dqowmwqr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcuxopi.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjtbnrj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvjsyhc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2epvkxyix.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hinogjak.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjxwnhn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrwyfay.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2skvrnpnw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ralxtdwu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sswcgtbu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqnfcvl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2akxmkrlh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2acpfxcsf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bntatogl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmjnvfn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkrgqgz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2npvummqg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2osupykuj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqmnzhd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaevlna.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfilxmzs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kupmqvwe.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmacpiz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtxlduo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2snqdpwta.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2hinkvojj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrxdyfq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2myikoqnu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpekjdpv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mktgfwsz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghnolwx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eptayofn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bethfvrz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irzerxbl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ibblmetr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rwstjary.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dopcveag.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2eymxyyqg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nryaihqq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dfevlxtb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlxzphb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxitdga.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxriaiz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhatuay.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyanbir.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjiqyrox.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdswjltq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wqytkgxn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwtcsji.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2axdvcqnl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbbxbpr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yppzqbov.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzamgbuz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2buzvscut.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeitnppf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qactgolu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbwgxeh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdaobbo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ounuwebu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gszzkmvd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmmzwae.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyaqzzi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxzemlg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wttjukmg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2otiufjub.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxbzsiv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnppnig.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvfegwm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugketirw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jklnjffm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmnzdvw.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qcubqdff.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ephcmoou.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwksvvo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qngjjirk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyshfra.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2loktwaxl.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2scyapvhk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rpyouztq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqzhqte.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2amuknfjj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyxgzdr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdjloup.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jnadrvub.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkxpgdu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jgegolgw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwkkrbg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kamqqczz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgaypzq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sumyjjgo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hijyvhaa.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiqposq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwrspjh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2esshjpau.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxtrpbh.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaqjsae.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgddvbr.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2risiwrea.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrtubcu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2grbdzgvd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fwipwdoo.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cqluetcv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbtpahz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nmufmmlk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bzghxqdw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2scpdxqps.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sscjzbsu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqosjdp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2orxzjyid.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2sxidajzw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqftefus.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2iajwancs.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyoskfi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vdknpmbx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkyluaz.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2saymdkot.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhqbrnb.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnayaqh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eclzhwia.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2myrcwlfl.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxgincg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hdprplwj.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciytzfod.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnlybt.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwzlhto.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qujwizgd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvhctkv.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjjeafp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sicqmpfa.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kedzickn.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsxcibv.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mflvgfpz.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyovlba.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfchceb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2swihdchr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyympoc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfqikto.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eiexecdx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdohjru.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zwpqlimb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iqgmilli.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gostgxes.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpfivec.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mjedbwsa.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2odhofvle.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzowyth.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2svyfsuuz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwwrmxl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2prckdfsi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jewueibd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2huexbchm.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdwwbvn.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kprmsydu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgqetoy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2jqynndur.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyqztxd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2njdbozks.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqvhmso.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkamacv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vldyvbyq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrecklq.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdzlhmh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwveiih.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kowutape.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjnqhlg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhqoplm.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpaiuqeb.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ipteacyu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhfeemp.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2orfuxhpx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqwnrdn.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uomanldb.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cccxrnsi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2divuczov.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjueaiom.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tbczzyum.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2zawurmsx.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjhbnyp.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtusaqv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2egsfbfdw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjcuomx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2edeqaizr.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2royxeegt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pldgmuod.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vuglextl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnepyqc.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ikinrdns.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyfmsfu.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2frbvovrx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjbrexi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrjteeu.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yjylanox.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ataudbsg.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2opiqyebl.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsvodss.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjdpqr.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bgwmzfys.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpdqnn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hkikslld.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdqafyu.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2egbddwbw.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnqtbsy.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxvcqxr.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2geumrbmw.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtnimpt.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwvigiq.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2lqccxqic.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2nohpkicf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpfcknk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwgzgpr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jicbvyto.html


<!-- 参考信息 -->