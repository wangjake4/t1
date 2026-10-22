代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqujzmx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqksknla.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyjrwiv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oowqogyp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zedabvgh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iinlmfnu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zulmqpcx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbbpghv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inyordkf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjxcsgs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ploajrgo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duiougmb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbcbuyh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ousubjug.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwaosip.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaicqrz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sithwieg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2svcrbneo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvncjcl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2obsbuudq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbiyita.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wcefxbpp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjbuohj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqdxqtg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gisjlual.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2okxlyehb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xerusktw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2woncckyz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiffpbwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyzvpzv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsbfrkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lztcjnxq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnvlush.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgflkch.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbnozax.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tceoznte.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2npezjawv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xychqtrg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xoicgvrs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2coicfcmu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2djatqnmc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2lfivlzbr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcjbyj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzzgabc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tiawiaii.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbozomlw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoojcmz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2auqjublx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lemzxwbb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmusbyrs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdfyehy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2isrsuckb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zinkxaxu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqxkbyf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfgnefz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxdliwk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fspicdbu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2acdgzbro.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zpalpqex.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmdfdkf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2gegimtly.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtwccwv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhmffsn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnwzgjc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlobqmc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqojafa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2phfqdaqx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qajhrnab.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnxjhlo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbzmmrr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfexykj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hiozupzi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfbdrmx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoqmaym.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsakjvv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2okbweqbk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpyotiw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2syobtnnh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jnybzwgv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2akdsomjx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tjynbgtl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeaxfqm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hyctbxrz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqvteiw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aibniadq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxmoulu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cctkxkdm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgtsyhv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yaitrzic.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnvvxcc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvkkxp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvxgois.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjotrjz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtgussm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2egzwxgvu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2agvrqert.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2npffxqul.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhrpymt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rbofcpxu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzuykhe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkaeuzn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgijnhqx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2deifuone.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhfbkdh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2sgswmpba.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbhifzv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rifbbrau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2fryitqha.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfwihoi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhdxlcn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zayqxmae.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqukqwwo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zvswflso.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dndxsooj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2tkemthrt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcqfwqv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcdkdpk.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlwooed.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tiynrdwi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2efgzloem.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tslmptux.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqeslkew.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqhkxog.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2egpwmqgo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2emnmmtza.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2peperneb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlradacz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2exigzghh.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jiecxfsg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwdylif.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzhsbtx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbplchjb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xahbxgez.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgfbxrx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tudwbbmq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzrvwie.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdiwvyw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tdblivbx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgwddjh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnvabhc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thbzycxo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gecyjqbg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwxlmli.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjsbmxy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjzkppb.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2szafpeud.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oykeqtkt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgyneji.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lcczmujm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2voagejhr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2enojngzu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uygbtxao.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzbffim.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mylkaqjj.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdpdelc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoefkox.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2knhkmxhe.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcevqqd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzzcsje.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2twwpdcyc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2scbscoty.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkrxtyu.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuxjmtu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wezrarbk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgktzua.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkmkere.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsdlwjl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbtmbzq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2obicxbco.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwqmwms.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaqkxir.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2isysxaty.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrzfkhi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rotvtglc.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2swpukgoq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jjykabzv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhlhwrk.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewpnzva.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvsluow.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnfnijt.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2yykdnlfx.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsvgxgx.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2khdrqidt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2oprdauhq.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2iljrcnyf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dbegnphs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbuunor.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfyjvlk.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2azmqnalf.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuawrty.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmrywec.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vekcwogk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ahoifkrk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2gvumbzkh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2mgljpnhm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsazbmrl.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2erqfazrj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gqohucsw.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrjkrel.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ottxvvlj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aholojds.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbvjqgk.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxoghlr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2olhyoayp.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lujlydhx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbeclnc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2idayybri.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqqvicr.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zchjhreo.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcjqswb.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrdvjpb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bezyhmmh.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2liajhkue.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xeovjxts.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwzszyi.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zesrdosf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2neumbeco.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmeikcl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfkjjdj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnufyefu.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcdjusn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hzffckps.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkzaczj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyaslgft.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fezyinfa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdrxord.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwogdzz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaumwec.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2krkejegv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwpiiot.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2scnthmwh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqdarwa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iqupllsn.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqbfcty.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fekluodg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ruapwtfz.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2umqvyzst.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpubevug.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2qndasdph.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2epdnccud.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbsvixp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2spzqmldz.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnfhnkc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qvailtyx.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2abhcespo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsffwhgl.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lododjju.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2phlnerns.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2irhwruod.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2srdapyrz.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hzijcyxd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2vofyszza.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzpzmws.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiynkrh.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wujsqfnc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoymvro.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2swcvyfyv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2eskhgbwq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcmockw.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptexgixm.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qocktkjs.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqjtkrw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdzkrwv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfewqof.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdujazc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxxpytd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcofhrs.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrhprve.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqcfzfw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjbevfn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2brtxlpnc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2dilwdxcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwmdlvl.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jehfxwen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtcajrw.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bewwhjqg.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnsbgvn.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2aradynem.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jewwruji.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiwjymf.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xotvjppz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrayxsb.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iftnaana.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vtywfnnb.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqnpqtb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2slsshxrv.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzamvzd.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2gdufvcgv.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfcmiqx.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2hjshjalz.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gyopimou.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2uioziyta.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sofztypd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2seefxngp.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kgatnjjw.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2muxbmpdw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhnvakx.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtfygay.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrxjrew.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2didzkwjm.html


<!-- 参考信息 -->