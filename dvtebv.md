代发 wailian999

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esbcxmre.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoimakmj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bowsuybo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwjgcvb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tldgdmas.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hiprscgb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvzmtbj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeyhjfo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzcsyei.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2maslpczs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqniogxs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jahgmqqv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlmbpkh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aevaqqxm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvjsbfk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2odxrtqzr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mulbqwwd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2czmemoii.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzfvxru.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dogupoxl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2anutcmbu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2itdkxvdy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkanbwt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxnstdw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgccqig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhxgvhl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2izktnvco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oepltprk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfknggs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbrmref.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuowqcp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2glceqyje.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kylwgbbj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvaquzb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jzquyqlb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2azywlmvi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzddsaw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2biwicvws.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wghoyraf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpqzspz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2agjecmyk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkdxdxh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nusunqvm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrvilvf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pilhdpbo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqkhwgm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bwceemgu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2htnwhuvo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2stimguwi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqpodltj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mjztlijl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdywykrd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhmqakv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwitkjni.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlbfavi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjwhosp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2alzezrrq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pytqvaib.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2snzzvmkq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2erirxaem.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhvufok.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2czqdubxn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzfhwmk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gszmlfpe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyovhyq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qosqbsrl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnvdufa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoygvaa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfxbjaa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbzdoxp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nynwjdhy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvvmprl.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idrbvdvb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvyobqf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2maquhqmr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgirhimx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oidvlepw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzelwmw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxiczve.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2itxtpuws.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2shiisznn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfocgpe.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2navwfrti.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxuprue.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwuzpsi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2shmzjawk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxyekjn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2emipubjg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2osawzeok.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjetleb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2alyltsvy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2duaduzdn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jsizyfpp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zsneqjcv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjbimcr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayliteqc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzleqzyu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2basigqtp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwncgmxk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxewrsx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrjtvhd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2khorupbb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dytxydcx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cckxxzpn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjhzasd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqduhsd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsqkeml.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtabujq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2chqhithg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oqekptxc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2srzzbyoe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwwqgns.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bolikpsi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzxnwdk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gorwdhoc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2urlusmqh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2apuslysh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvdlnnr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjzqnea.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmrwlgt.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yrctuqoi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2etzmiryz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tyoometf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2escyjrnw.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmpjwrz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeafuvw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hydnhnyk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2llllluor.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnxlqnn.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2gszzovkw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsnjeni.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfizbbn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqpiqqo.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2drqrkuda.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2wjudbeuq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2goiyjxgj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnpbtdp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2calxdwzs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqubcubu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2swgciisf.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2darmkqgz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2csekpljn.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lttmgnix.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fthiipum.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2larjvbzd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrwjfpc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmugyut.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcdlgfb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2afcajlzk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzemomd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnxuium.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2trxbriud.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgubvdt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvkbnrt.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbhziau.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfucgrl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2udfkbuof.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2femwdytj.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yprdefgk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsrvggd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsjxtqi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xipmkucf.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2odqpsmyt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqelgqar.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjguglo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywigddse.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtiaipx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrenvhpy.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sotbrdub.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcpktpq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zryjzsmu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2lptheszr.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ehguiimr.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwdltqp.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmowscas.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgvkelh.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsytomt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxtxkbu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsnqdgd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsyunob.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgpxsfe.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpcboqa.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvyvqht.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2baptifvi.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2nqugapdo.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2rkatlylj.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgzwika.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkawhfn.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rreuzrzd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzgedbk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2wizdwhud.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2magtgjuw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrnevqu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2nexvpjdh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgrpnvs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2kulbqseg.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlmtgwl.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2utegoism.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmgsyyk.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsordao.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ofljlnec.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ketdscdz.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2husilkgt.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmfqndh.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqxbsdr.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wgejohwg.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iudfgrfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgogvkhq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbjkawb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2kapvnjlb.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2raywhgvh.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2knsqqeqt.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jthlwssy.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvepolk.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2myaofuiw.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2txvjfpwc.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpyousj.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2eijwizsx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqmbrwu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqoptjh.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxsjlia.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dinsqdmr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjywydu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmemxyq.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ztraijtw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzjboeg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oswdvigi.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoqzmkp.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fnprtirp.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeydyad.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rnetrudw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsfobhh.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2digulhlr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2dobzhuby.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmdttnn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwsqons.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhdnzlc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpoltain.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2odvnfdak.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmowtkm.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwdjimu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxmjquj.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpzfqer.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbtatkp.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2laemdmya.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2byckcfqx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ftksylnr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnltrhq.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2elyrocll.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyxfowm.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2zajculpk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsjylup.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyxfiea.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdaxyhu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2biqvpona.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgjlkwu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2becnmxta.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2emuuejye.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixruzqgt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfndpmb.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2alyddkhy.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hgequpps.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyqrijc.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2npubojcg.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuutwie.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgrhyho.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2olvallom.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2qkompuds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoavcxv.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2falgdqzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpthmsz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2aoncszyr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2rftfgosq.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2wzyktlaw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cgumqygs.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqnzrqc.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pbuarsqy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hoahehso.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyaqisc.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kymhaxcv.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2duqsgvqn.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2vynkvmtt.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfyhvaa.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2xctwypxi.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaidzny.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2flfbodwy.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vazklxbr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2qyshnpsd.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2durgluhi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2bogeuqpk.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlidgfc.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2mquvwult.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtoihd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2hhghgeqk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2djtgvzbh.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2xzceqalo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhijiandao.cn/Article/details/gt2maqarwug.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhijiandao.cn/Article/details/gt2rochcnee.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2igwdmshq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyyaing.html


<!-- 参考信息 -->