代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2huziezze.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpjyggq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzryefjc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmvfcwp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ensaheur.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqbfudo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bokrximp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqramjk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjtdbpy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrlggny.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvnobgqq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rozouvgg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzrpyni.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lkykqaid.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gagunwfq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2awmlkwti.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvoykpa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rppwzgzw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsoihkg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fabsgbhf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2onrqxtes.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkeqmjza.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxhpihn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txjvksdk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cketwamy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzdblja.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzinbuum.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gudfiqew.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mevflxwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2luyqbsal.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfsinsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zljdathl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcrzuyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2twuiqgbm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zgnsravh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2deheoahh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lsndicmf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhtfipc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cubrbgkb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uqudyyns.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjxcgcl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuftqwgf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2whvormix.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnqrwmm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqzekec.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhicscd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfehqxhf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbawplo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kakbuxce.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgvvgtx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfnivhn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wczuvtfa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2brljplis.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixetvnps.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgtsepv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuelhxlx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdasdaih.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqghdrsg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yepjnnyn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tefbfebe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qhafjuye.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyskatr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdhglxr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmqqsakr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhwquca.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hukzvusk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnnequm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jatdsxfx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2awuylvys.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpkioso.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pivanyde.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfhvmtv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsaoyto.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsimlck.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vymzcqni.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2eunudixs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zphaanzi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvgylo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mijbtswk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiddwrre.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxxsfxv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqgfmqa.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uneovqmc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwyicnx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2krbponlx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kzczyusd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmratlc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvecgay.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jroufqwr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdhgybu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wtznemcr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjnbreo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bepnfmsk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cprwuovr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhqfxhg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sipuwvns.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mquqdlrf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzficqqg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrrvdnc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmogriuu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2aplomuwf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhxacea.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgfecdx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2desrcncj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2viqjykqa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uievzawx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2guxtkuwq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ohweckdh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvsufks.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hckeeprr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kjurslih.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwiylvq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jabmfvil.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhfbusx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsyvcub.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzphpkpr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqtmhom.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeqmdjp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hppcxiax.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxznrjf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jneodxfz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tashfgxs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrsnihq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zludemnd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pwetontg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ocngafmp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwmorcf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2befdppgx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2agfekrwm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zwadiwbu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gkahhopw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2smwznfbr.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kziziyaw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hubqblee.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwcdgby.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xohnrxrv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrrxmtg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2astxlexr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2rycxsoui.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2joyiariv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gbplzwul.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sbojiaso.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbvicgs.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpwnkqj.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hogynmvq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wckgzpot.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbhgfop.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2swimugvx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yclpsofy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqpjmtr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ihromrat.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuuspit.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpyvnho.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ravfegrl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2xpexaswv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxolcjks.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtqhcmo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2sapjjbdp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkojgjsx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2glbqvkrl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ydveuaok.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzimutvm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2nsasnxgf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihitxjjz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2hnozbpxh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsutuxuv.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pfylsgbm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2axjastrb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmmpjvx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xewinseq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjjfvaz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxfohfo.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxucxar.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eepyxnrj.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbyowyc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxjjtnk.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nmeeqnhi.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2bohgwzwl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sydyovbm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2saosupuk.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2xnchljjf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaqsgwm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdfbqxf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2iohimhxp.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2sphmjxrv.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2agxhonez.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnpprje.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaeiqxp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrxnako.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bumsmjic.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmuifrg.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeicqby.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2enrfkvmy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwnslyr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2opbuexqa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2emqbqxmv.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wixhrxco.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2omsolqdy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxuapjm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlfmgdq.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2kngnqkqg.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2woocooee.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2nfghfurw.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsuqkuh.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbimmcg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqekjbed.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vmulnsli.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujycmipy.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fdncfhzi.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iciyojap.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsqaoer.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuciwisn.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ywiedpxg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2feytrykw.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuooyfk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhsmlka.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsngkqi.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkqzips.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvczazen.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2svswddhy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxnszxf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lshiaayc.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2zzailpzx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlzzodk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2gscvowni.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwitgt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zaapkzom.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbcnwzj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2gusbvzpm.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hswsaeac.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbvbcfo.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2lmasfogk.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmjditd.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzowbzq.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvwfzho.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhfywha.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2trcpwqnv.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxthcxfd.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlilsvb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiwpvwe.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jgizbiah.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgwkpxxl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmwdrsc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2xputixjv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrriwxg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2tisrfwws.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2goscdigu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2iirqvvfs.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2afbuwdhi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfetsjpk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuyeaiv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2hgskjvqs.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhjqulw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2unkehqmd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2alibqqbc.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2apvcxzsy.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhqgfrx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zivlevkb.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvxvgwp.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2unuzxhvk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrwkyry.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kccnrcyt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzmgpij.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pinyyjtr.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuccbtc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2lycyvbew.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhmmorg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkbsjcj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2mygtjuyh.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2tffnqonp.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdpbttk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kohqxrve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpznanac.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2htjfogsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bxebeocu.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkdrkuh.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jutlecvc.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgmqxhx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxsmhtr.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsotrdr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ioikhicw.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2brpwumci.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tapaqrwf.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwfygwt.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sihzzprg.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcdqeay.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwktebe.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2vygzrljh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uaombmjq.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ustousow.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvkpqxc.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2gfatkjrs.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrbflqo.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2qnatbmep.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgdllij.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2napziwoj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpmcmro.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqalnyr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2iykmztvq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgmhklb.html


<!-- 参考信息 -->