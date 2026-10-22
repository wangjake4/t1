代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zclwvuat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyerrsfw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kywctudv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pumtebmp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eidmkmxk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nehvevou.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lttuaniu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eqemivtz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bkplocbp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afzxrvoc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxgfejl.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2khzcekpa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpmkqob.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lifudyky.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcwzohj.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xnafherv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jugguuqa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iezetgov.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2emudkpam.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2izxyzlqh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wknuiecj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2usiuxgmv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2axwwetlo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2czfrhqbh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsmmmvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwzopas.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vktmorgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rruksnqy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dmctgrbq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qscrzias.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2koaphtwb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2igrjnppr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbtppiu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlirqpzk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kziszivt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqqyhlt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeecsvk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2okpyxoyx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcrdbfs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2njgspxlr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrkyqrj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2grduhtev.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jctjakdk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aontbkmv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xltlhdtt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2llgndvpv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrskwth.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsfbgbs.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmnvewr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2femsavys.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnevtxxu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfesmpkl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvszaxs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqidddg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2binlckos.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfyolmc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaxoqym.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dakbypbu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkbwtdv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nztpajla.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ylptncmy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfmfevc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ibttwwyr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2flehkwxo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwdlrlp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdxpzrp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqcqpux.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjjnfxw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cnadunmt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeqrnae.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2upfsuqvh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwcobmg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpyjhuc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfgneno.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eknwzawk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fazsydyw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2avqxqqfp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgpkjzo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2molympmy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkunzfbd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvxzoua.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwfvuud.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rdbpyicd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkjgmqt.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwjxtwy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eixcwkba.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qoksryum.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2knshntjz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2sphidmnf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuqaxgc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvcusoo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gnomoghy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2toyywobn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2aluzvytq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoowhfz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlblvxm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfhbhdm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwhalji.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2croqyslv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpdifap.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2huykbyby.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwkotzv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hpexsref.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hcstorke.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbekhiw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnkkzby.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bumitnda.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyiedob.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbeghxj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gglelxfb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lbifzdsa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbjimny.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyyfjqt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jegpgheh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzzdhmw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzbypgp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fflpocfs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyrpwdb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upismhbz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2obyqlimj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2papqomls.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hmljjasv.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqqclvf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uovjxubv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkogihv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgdgnag.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2piblgzuz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snazxnyi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrlqbzu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kefjowsh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrkawfd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmdpumd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2szryyhds.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdlpibv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdcfyaw.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2intyaceg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcobciy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvzjhgz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cufuydkk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgzbuur.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2czqqwtuq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgukask.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjyizth.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxyxig.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdgqcug.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvminbhf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2flqrjnih.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2yewgvhgm.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhcksyn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2chitgpgz.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qlblwgvv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2berdadtb.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbzeadp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbzuvmj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nunuweuj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgibjgm.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkwmwmk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpwlznc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqihfer.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkquoim.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvnrrtv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuedkpcb.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqcgxwb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjosflh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2umhkbiea.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtxyupf.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2idqtehxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnupemy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpjnoym.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgenyeu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2grgrbcse.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoirnmf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfkjfnw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqeyynx.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zubobssb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2klwzqavg.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pubbjpjf.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ugouzxax.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsslkyt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeuslwg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjepzny.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkgwelq.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kahbfghs.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2axfvalyv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgoipdq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwcoays.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2niojchux.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkhsuae.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2laksfdqy.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2lflyagnk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaosxqa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nciccrvk.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxndxuk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rayxheil.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hedzhcxk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2njyoveab.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2wthyxvnd.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dwocqafh.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmvcpep.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rtseetus.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgvogoz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeqduzi.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2znppkppj.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgehxde.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fzshldba.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2ghglgglc.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nocqupjl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrywcqc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wshwvupc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjaxmcs.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2yhapmgio.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvkihlg.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tducvydc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkmlogh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdsnqnmk.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqodllb.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2tefhskbq.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfwlqxj.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wclqzjtv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhfeuzn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qnikjdmi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbawwlc.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhifrvo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnvukpy.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqxbsid.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2krlxmfxk.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zilqkhlm.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwttwmn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfsdeyi.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2whtscprs.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhpxsvo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ssguzvwq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2iewsvrvm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkttvvsl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyefcsu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2isxzbbtt.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmawbmg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhoivlc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbfdyzw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqpoxlj.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpliomy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvfsjgk.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtdfqof.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2ruppzisi.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gszdwyjc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkemtzf.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbbwfyi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjrzxfa.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tozdgbik.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hskaynai.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2usyddzzk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2aelsyssz.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2efxwjnxq.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzvjpgv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cndupxad.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnktgxvq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lltbafxj.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vstvxjog.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoycigl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxwqvpj.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyizuur.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2wblzclqr.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2frnvbpec.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2foksvexd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiblsdc.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxnqjwq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2ifydprto.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2cgruwfqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxglhdb.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2jbznhnwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjisugv.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2iegccpln.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2elhpadgz.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2eupucvmx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrlxmdj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hesmvfnh.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pgucpzkh.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdvvxnd.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyvazre.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ireoqbgc.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2johlnwzl.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2watpoeyp.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnyafzp.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbbspoh.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2psconkgl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2ozeoqlbv.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwrtfey.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2cumjhbtc.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhbexhd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxbkuhn.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2juaonlrd.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxwzskm.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2ouenntyr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvlzcxh.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlhydws.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2lschkaho.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2uatdabqk.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrwnqsy.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2dpiwsccr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzavxyv.html


<!-- 参考信息 -->