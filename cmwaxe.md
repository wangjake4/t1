代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ykajncdt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fundtujo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2avgvdjjf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcfdpub.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xstigxbh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgahtji.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vyubtdvg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrzbwcb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmdfark.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2haspcbsw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsycbcnv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwkuzxa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvahowju.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iidlmtoa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amlpkyox.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2amixkivy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2khpvroir.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2idwunmyx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2avegshlh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2calkupgt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2skmznqme.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmbrtwv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiusprcq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dyhhsnnw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbplxlp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2apiftpkb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ochclsjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbwperr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjbhrji.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bubcrcid.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpewalp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eqasexfd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaowxia.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2omfzfhbh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2oybhzvyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyoficx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nihkzksa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zovfvrpx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2htnctmhh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpwasqj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwmkucf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqcocql.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzwaitb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sswnrzmt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcdrtek.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxgyooj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2raoimwrs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnnjtar.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtucmba.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rktzglhv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tddwresm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfbieby.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxraztmv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2boxbkzoo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xaflwihn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxdihbp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2spgnnxhx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnzntoi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxujpmb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlobluzu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbksue.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lulvbhnu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuhlmsc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2safgotdp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqmcnvz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2csnzsgpp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxzjhgh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2offjjeoa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2spqlopgq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vvisdrin.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnyixdr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeerxxr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmyluam.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rakcxjli.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2awrhbqgl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvrrzub.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xydxejri.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpjllar.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hatrqljv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2puryspnn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvyctel.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qesypkzi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qknhseel.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vmiunncs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cryrlhdx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhalswv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqcdmya.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ieicipne.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ejatnolk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzxlkzs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kikdhhay.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sebgtqao.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdrqwcj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cahpvixg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpeatum.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzlkfav.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvxllz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhinbdzr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2peypwneo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ishzpnlv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ouuhwigg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjopjbl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlaougo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2blyteiju.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqgkrfn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqqoxok.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gklbuivj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmckbyo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sdthfxdl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zofalksl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nqviaxjb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2anckasab.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2urgskrcf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnodpctp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqqytbx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2txetjwpk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqxifcm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvwkedi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njqbxzhb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjifcsg.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxntrrnk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cpusnavc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mtorsbhl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htetprwg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jeygpckg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vburvuvs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2blohutgn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubejgiyg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlqithh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2narjxpcr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2milypqab.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hislxmdy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwgzdau.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkojxtwh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeevpou.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbkbvbb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvufvgu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvmgdqp.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2spmteihm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpztait.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoxjdic.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eohevgvj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcatbpm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwncdhj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqustgn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxglioxw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpuclxk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiejemrl.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mwnlarjs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgrsxbp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2quqxmszk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gisbtrlj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vjizlkjy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gasqjjsl.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aukctosv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2udafdnou.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsyrcfs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2omqdpkff.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgspwxp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfojdqt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2boxtncfd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuvapnx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nyssoykf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuqsrlh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtuildy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxuyxai.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vmegzods.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2beksydmc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjkimjb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyawkad.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2scxmtjlq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvdqzve.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuovmxm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwsrqnjs.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cywgsaou.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnbnzno.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2owwiffps.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2irbamhkv.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdijnsh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqcunog.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2niytzpoj.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxwxabf.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jgykrzyu.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2tcpyfyyn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xkunlnzz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2dgodqkwr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2mueghdlv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2uczvwflj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2atbgpfhd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2qndvuujf.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxiersl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzevsaih.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoyeckg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2venimuqd.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoauhqo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xyefpvat.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjroagx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2kskxsklx.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2utkgcbxb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ustsbbxl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2uihqhotc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdtfihu.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnejtrh.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpobcot.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvrbpgk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjleoyu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjwxytv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwqavqc.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2euiwmhss.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrlryob.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wmszwdph.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlijhlf.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpkphgk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2slawqjwm.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwoeoty.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2khdyudfd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrrjzig.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxjbhrn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vljfpymc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqtkryl.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxcatza.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzzwwxf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wskpmjsu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfscgva.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2czndawym.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vpozwglj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2snawlhcs.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjiiakn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nynolnox.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlikpzel.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaksdwc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2aoppezya.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2fraghefy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfippha.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uttpfmuq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgowiqht.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcfurqa.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbpwgnr.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtrhtps.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2oszgyqms.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2mnijbmsm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtklmaww.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2oywzupas.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrwztma.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2edwoljfm.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2krdecezp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2azftzbdx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2angnqmek.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaqthln.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2cadrzrwr.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpmvyde.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqtymqq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wztytxae.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2sboinrfx.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kicbnqau.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2podpmtby.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvvnjvu.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxabirw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mptdbzpn.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akynyhbo.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmfiwjd.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2banflqgk.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmwamro.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuudyaa.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmehvmm.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2xvktsocm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpeyyan.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2plrqtnis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiisbfls.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2vybkjbeh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnzlmdq.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2xiigwrpv.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zthrpyud.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpoaawn.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfrmpsw.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfwdfai.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzgkqum.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdklnjq.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfrbjce.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kailxmjn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2eigjhkwi.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sukcaqzr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pkacpiwb.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2dinsuxom.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdgstlf.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmlrfmh.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2btefxohs.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbxgkmf.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwyxkqd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaomkbx.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2fixvofcs.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmsputt.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsovevq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2ooebzyrk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2vqigbrel.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmznjle.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2yvguhyec.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2dazngicc.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgwkrxp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkyffuo.html


<!-- 参考信息 -->