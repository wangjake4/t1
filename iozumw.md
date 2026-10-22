代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqagwjn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dskrhvlq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlspdar.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrhzqdu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ichppfek.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdeicbn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkovmlq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqwkaiw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bvazbumq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ndihsuve.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvbxqpz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2byygivky.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfppxol.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gizadfxo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgplzua.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbongcg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2flejnues.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmbjfnw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jinawqin.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vqewccwv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrviiqz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlkdbol.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwkleqo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdgszah.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbgelgl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afvoujyv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwftjwxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oeygpjla.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2caiszeuh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oklkewzk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eozpoeoo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aknsuwuv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqegwuch.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlosidaj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2exakgrsp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tocejwwf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubisasqj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iseqhkdx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxhpgej.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjptocy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhrqqdf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2idhcsvky.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2veefoqur.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kumdhoth.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2huasywkc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2okllhitd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2okonbjvj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnsumiw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnrbwng.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcnpaoc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unaairkp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2odskdgdj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rztjrsee.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvaeakl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lauzircp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fybrpkdf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnxoqzv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvptysv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sspvvxyu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwftigp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cspzwldw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqncpvoq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjpdxaf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmevpel.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbeknxu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxalisfz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrerqso.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnzbyxl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2tycsyyrb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2njxeaqph.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gmemizmg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2clhhprke.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyfgehs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwidpqu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gmynkpgf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2toxiwadw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wngxwmmd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdtqomp.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zujntovn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhlysbe.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nwulytzu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpbrwdg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlgiswc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbzwrby.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ecupcwoz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmnufhn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcgvlud.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkuxcoz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nudbvkzu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoabvww.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfgwvgi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjfawbg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2potixlnw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2stmaqszl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcpjokq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2podoryqx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fpllrubh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2klmektnw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2moktuuwa.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2toccmbfh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsbcsck.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2slrgqqtr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2njytoaee.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmfgfke.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvkdgbc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2clhbibxw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkhszzs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkomngua.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bujxzmfh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvdluwd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzysvey.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoatfjyz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdzfyzn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wspuzxui.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksflcexq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahluixkr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2beyqvzqs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvzohrq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2heclhqla.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nonuzsyx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyzznrp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bopukgob.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2airmnxnq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erykqpmx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvcmeog.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vzniybmu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjxzbvc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbovpsis.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvcqfvr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhiaiyr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgjjqwh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxhepmy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjxfppl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2utyatqxn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwwpllh.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxbjkus.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gncrpawg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hntvsmje.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzxtkis.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofetwrqt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tycrttgl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rychkyxj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dblarmfz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrjuyym.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzghsyk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffckscfw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgdbdgg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhktbguw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vzacksdf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnijrrl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2hbycmjnz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2deczigao.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2raklzyre.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqahyza.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtykedp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvxqmut.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2czroftfg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cimwtirr.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2icxkjefe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgficlrt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nvoylvut.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnwxakap.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsyegjo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lifthaoo.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhzjmnn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wslarhzu.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmhhqmw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2julebjao.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eftwpesx.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdjrsbs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2orpjowot.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2cxaltocw.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqptana.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2himjjnuk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbzidzl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmheerow.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2mcihkaka.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjuambg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2dyggipfy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2hryqzecv.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2nyuhjakg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nraqskuy.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2nekszoog.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkkewgh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xxieibbo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqdsswi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2liaxejco.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwpikwx.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkpoufe.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcbvcai.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdyqrai.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhfmpyd.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hdadrawj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpopsxz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbywlej.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2giilbudo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2luafavdm.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2tndgefgh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzveycf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhednis.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2kbclhdan.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsabiwy.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsjgusu.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bowkhfhx.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxcupyb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nclnrdrc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcrlmfm.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlcgcjd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2heguyiac.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2hanmntaj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dpszujbl.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2idvgqhvj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfkxkcp.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgmhxsj.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oozdihqe.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2savwgwif.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxxqkou.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wobeilyo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vccnrnkw.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxasxppe.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ahzkjavu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2neynrkak.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdrfnod.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqxjsxs.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2zkprkwmj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2uarghsnz.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrurpt.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkznfjvf.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfwaued.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lylmnwux.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2aurygtms.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsomwjrw.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbatlzk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkxzxbb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2oxspgtro.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgfuual.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqgntst.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfjtdbl.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjibdxz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ktilvuav.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlegcxj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzuddqxa.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rreghloe.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dnablqpo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sxokaccu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2evgsdabt.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2humpllyc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2neakuixr.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dafakcrr.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnahwzw.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2liyykqwf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2amgvgxwm.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hialgjdj.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2owlfglah.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhuuwez.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygagpgyr.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uckjjust.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2esljvdof.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzrqyv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rifjgtfy.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfujzcdc.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvwkbzd.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfwfsoj.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zesktdwk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyezeeb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2zloaknpi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhrcmsp.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzewslh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwowctag.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyvpyzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2togzskvl.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvgnavs.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsvpwlo.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eyocfhsm.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqrltre.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2asquyxue.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqnzkpz.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yhusrpjw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uzttxshn.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kgglenvx.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2umjvfyer.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ikebraum.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjmfvzi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2uevsmcex.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2osxsswke.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2trttzohs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2kutsutnk.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhaxsif.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2ejesepti.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuvaqjc.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lahxslxp.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ovslsxgv.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lhotassh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdghxdf.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hbaxhxwt.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzsehew.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2pearzkrh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2anpirlim.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrmcvmr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2eoelssnk.html


<!-- 参考信息 -->