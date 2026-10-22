代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ayialoux.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzpqumh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmprbifo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpauioq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gimmfurv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnhfacz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcremfa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwaiydyn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pujkxhbl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdnqxmx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2slnhardr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhnqhxs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cngwjfhq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2awekadgp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvislub.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kglbgkje.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzammqv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxidiyv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeomthan.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpktczi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2owienbdq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyxzcmd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcgrtcx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xmttszkj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2klffwzcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wuquhwrp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hckstnjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cofkfgnj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcmvxlp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sfeqvrge.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wpblhavg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aositkuw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhjwhdl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vruvydhq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdzdbcc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ygotllwx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdgtzga.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yikbozpq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ckzksbtl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtqzzyy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2opstvfnd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2akklrivm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhpeaqd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnbgrvg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzoglos.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkwudgf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2duboxduu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qumgvqwh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tyafvpen.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzuitoqo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnofzgm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxhohxh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoxitzt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgktzta.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2akgfcmgl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcfhcbz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxwyaqb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqzbgiy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdakjjr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcssifew.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjxogm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsgzwrx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2evswzcbp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkolwivz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxifbep.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfsxdcy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnsdzvk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpdxfkg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnqsjxg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpvfebh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2aozhcaxy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2qejybcet.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpqvgsj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aralxkuk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfteegp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eexvfymk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtqlvlu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jasjaapw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jslebcqi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjzwoiy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiqszzx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvbjxu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uubjvsob.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2venjfqrn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgbkavc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgilofy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qseljxbe.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2czoshgao.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkpukih.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xukxugda.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2grfbrxuk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvukbpx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zofrmuva.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnzfxco.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2klngjjjz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2togvdjdz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuueitq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2unuuyalo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmprsoz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hspesjgl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iznzgfmv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbrhswx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcmivfw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cxafvdya.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzdrymj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qumqcnqb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqyvytx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxtjnfx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2teamkeeb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkrwpim.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2akxoqcys.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjixwcjd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2viovnbrl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvajbkd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2utttvoza.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2svxrfsba.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frtlepkk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxscwjx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mttnacap.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mpforpjl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ueevzpmv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ltahckse.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjzlygv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbstpxj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2urdplptb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2moqdcbeo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2degpboge.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mifkvdsf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2swbugthp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2towchoab.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzbmwjn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswfnxex.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2znelcgul.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzowuvw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zphrlpwq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2akryeslx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehshiz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcaagbn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnclwjjm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbiiufq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxaeavsy.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2peerkgii.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2upjjyrww.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmxnwti.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ztucordo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2objmwmrl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2vsyhlsgr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdidyxxx.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eefylofq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xspppdnb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzgtoyv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2oukrwepn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfvrqwk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2olllcwjq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmjkscw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2txzgrjzv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gykgumpk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxxjqjb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2odngqmmx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nghhynul.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkbatpg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2inoarkkz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcpsvxw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyvuptqu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfesnzs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylydtraq.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2apxrbaye.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2dorxmmph.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrbudon.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpbwiue.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2agkiyhpq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lygkcvsn.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gvddkzlq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipddwref.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrwdshi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpryxvv.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2psqsudtz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwnsnii.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mddmprdh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnrxesg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtdiyva.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kdorfwgy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxpvhdx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2snuqmzxx.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2awcluyzv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2uanwmxdk.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2oyamnbiw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzzwxba.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkdyzhj.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cegwsmbe.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfxkkid.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmfoaja.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fefvkipb.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuzwaah.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2pvixebvz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfnmtdj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2rndbtlqf.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmirkyx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjujmpp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2stsckqjb.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiebpey.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsdswfp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2llznokos.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yacefoke.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2prrvaodp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2vjekizfw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbyibly.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqspaool.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eefptcaf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnetqjt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dzaivbth.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmrkmjd.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbvmnvp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2mimkjtxz.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgemqar.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlgdmgn.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2naclwjbh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfhdcwn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvbjtth.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kimnksve.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2envyhrcj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpelqlpb.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnezhod.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2dqfqnfph.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2scnrtmhy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaztlia.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfzvjsw.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsimmyt.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwjsqxm.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfakppk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2llzwwebv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhzjxpt.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfmqxbd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2neufpziz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uarupmyk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dawauonx.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyrbyye.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iazwjigu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gmksvvsq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2vgezdttm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzhjqnc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2eklwbsio.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2argusurx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuadvgh.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxjvdit.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmzzzlr.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2iizarcqe.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlbtulu.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dznfhudb.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqvczqi.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2rftynbce.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvhuzzd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqfsede.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnfudph.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfanuik.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhgmsxk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2apdrajbl.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuanmau.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcosomb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2munqwpxp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2vszzqeay.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2aweqtrro.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvwnfdr.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2juyakhck.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsxthyi.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2fatlvwoj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yknbhtii.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hayvymgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnwprxm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgjygus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vizodauh.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2fdicrahc.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkvurgs.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmbhtmw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2abhnpjau.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgnaaxz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2iziqhthl.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2extvixfc.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2aizcpfci.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2squbtzvq.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sjatqepn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2bracnrob.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwzohth.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsgwshj.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrpkwty.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2itsoiglq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2swugrxdx.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqikoqta.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxziqdg.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2obhpizzz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xpocdtjf.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ngizcrwf.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkkjmpy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2llzpkkym.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtdirph.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lgibhopm.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2wpujauwg.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2veqljjsp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2allonfbt.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxfgriz.html


<!-- 参考信息 -->