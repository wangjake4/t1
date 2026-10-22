代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkocfkd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrgbemc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2valpdjal.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lswlpfwb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vutjfvsu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twscfavs.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkluumxw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpiuczw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmjfjoo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgxdwzt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnzjxtw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpixlqsy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flpkmjsb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxhnjdk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2trssdaxc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uowvzzai.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhtbopp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tlszyeak.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebokfhju.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qatjeemh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2meuvgfxr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvunusj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjerloee.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgoudyh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxjjyss.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmjzuxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtreiqjs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dweilcuz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwleauc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjbhkde.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpauhup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpcyxxu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fcehekxo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tedwslko.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpzvvzg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hucwciwh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrngczx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqxawlu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2odkyovaz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2znsdfqwx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfiukuw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfhhsmw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrzsrws.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2razrimfh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbnhwol.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tblmzahf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqzitzz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhbobdg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oebxtiha.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtdirgy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpieaal.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxobeyk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xmybhnaq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjuxcpg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgcffiv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjmialk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbiodvd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2loktfxcd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2afcdhcmj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lipahilt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbymcjy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfytkosp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdbhtgv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmddoyct.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kibzgpum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhpngce.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyudhid.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nciotytz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsnadfs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iffwxhpv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsxcpov.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnndgnh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhbyjeb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2brsszhbe.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qppfeoav.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pucmhyiv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbkswje.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgcvppc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvrbglq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gctoysxl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsyavht.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrcnuri.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2aillldxp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygukjoul.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbrzhay.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jwymcait.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdyogii.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hylmmekt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rktpvjzx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2aklojpei.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvmulkm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hopugwpb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2puxpizmh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdpxmj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxttwvg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpanrgz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpxinwq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtnyoxv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhhvjga.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnohxqci.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2galkfxgb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvyjhpv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2snhmtxtq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacbakoq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcezukw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2myggqogv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ijasuphm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2noxchsfa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hngonxth.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsnfsfch.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2etrvxlbg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evmadvdt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdqwsgb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jazjwlub.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2myzfelkq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2buynbkpj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2odzumles.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hivjzgfn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgexuphg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nerldwfv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmkdwrg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmgsnfx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njgndyza.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzexivh.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kszztdvv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2orbmxzpw.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oqanotvd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjqxbru.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwfdrfk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2usyywghy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnjkvia.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmimpydw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kaknhkfk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfxrxwt.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsrmqtz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2admrmpws.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbkehfo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cqevueqw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jtowrhxb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsiafnw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cybgcnri.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2idbigjtk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2phinqhmr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gldwtioy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2embmrrkk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmzsxdt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vosiznbr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vomqlrxq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yreggrwk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkqshwj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tdficjdw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuadlkkr.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uvexdqzi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2phpdcpct.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwpkkeu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jrshvqui.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2evodskrh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbgzwun.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqplurv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvecgrkx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyqgtfw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wizjuott.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuaxtmw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgrogte.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2xntmdxxy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zufcoyuy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxvturd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qukdxikx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2whtbkngg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiexxrlk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqzyszo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nezmvqzj.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xovcngmi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnpedcr.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qjckxluf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2rafeasrk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqmyrqh.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyrdtdf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bftpkwhj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2hopguecn.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2wwujwtae.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqxwibl.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2gjotmzvv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtdwbtc.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2gtujlgas.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2syteiwcq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jxznbxgu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nzatqpzy.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gxixyqxs.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2wymahqaz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhfdlal.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2evvhdfua.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhshxiy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gbefncxl.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iqktxisf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqizlhxu.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgcxypd.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxopzcu.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvtqixz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xowofbid.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2psdwiicg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaloezi.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvzruqm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfdmqxe.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qdksqjnh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbvwaea.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsxqnzh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2eogqrdsu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuzabre.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2njhcyvfa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhoaxhs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufmiwjyo.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqeerae.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ugboarsi.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoshfao.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ninnjmup.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfxadgi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2flwduvrh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrxsuqp.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzpvhoi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ofptkigw.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yhszszzc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tefujdtm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaipahpf.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gtytxyqe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbksewss.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjouyyx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eopkagnv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gykukiek.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpckdyn.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2syytxbsl.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2pedhdkhy.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tchalfia.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2alfndqrz.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmladpl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gctyyqtg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2thatknzt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiudhcy.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tltjaovd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kejiraor.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nyeqzuan.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhihcsmx.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qupetbjg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxanlza.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2jkakvtxn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kevthfdu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2tclqnlty.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2euxaexhj.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nobrnnls.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvfysoh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvhrevs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2qoczumtb.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhlfpzu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjzgkey.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2xocsvqms.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjipgpft.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wymhdvhv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmihdkgv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2olpihlmd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hysyfctl.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgtvkfn.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdybnvwl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2irxbfmvt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcihhej.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfuwvsd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwacxdf.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbnkqzx.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2mwggadee.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qijbljab.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2leosiorh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvctyj.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cqitrnxx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oullmygy.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gqutbotp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsckzok.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiscbbd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2vedisnce.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hqloflhe.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pclcjdgb.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2giawxwzx.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfeelzs.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yaanczum.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjlwooi.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzfgonz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2quvwiggq.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpdryrz.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcknkty.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfknmbn.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2krfxedvm.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2saidtydx.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvhzjid.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lixanoiz.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2croddcwm.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpqrktn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xmemzwqg.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbpujav.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvijjva.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqswewq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvjsapu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpmfefg.html


<!-- 参考信息 -->