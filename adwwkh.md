代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpgzsty.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjozutb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wefntrus.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2atqwtkgc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zenxfyrd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsotladi.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlmxuoj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjqqpkm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxspcqdx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obcpclou.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdvhiwz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2afrvxjxx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwhyvwt.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2olixgirr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmflffg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axzanxan.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxwpbol.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2eteskkfd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfjhwqc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lxndvlbt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaeqcje.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbhgeop.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2flbosswy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tahccsvh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlwozbr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaiszhl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eijiamaj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2swngdelo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2uujpszar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flwjecdc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmefwjdv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mckyxtfa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2trqfdaex.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyrpdtk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwgnjxi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuitpxi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2euzpehqa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2twnzdgoz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ldavakzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yrplihzg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaunnxl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2cihutzpo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ouveknoj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzylwcja.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aanojuvn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iebtwvgb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuefajv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2whiojwta.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaqywfm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2picisvzy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtgptnb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxdkmme.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xktjxcki.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxqryef.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gimidqop.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbodnvnj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkxoqvl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkisxub.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2knxioniw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjfjnyy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2szvmdcsy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2eapjijol.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrguvuz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdqijti.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vyienpzq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2oasuxmqj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pawuekxd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlqqvjp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdallfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2puojuquf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzqqioy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2afjgffne.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jowoocsy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zigosonj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zuinjudw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwusendt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbquzgps.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2owfrfejl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrudqep.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oprowvte.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzdmlao.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdxiwnj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbxbwiq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkveoflg.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lktrcgba.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gigerjol.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpdekqr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsevvrs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkdeorl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2juqfqeiy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkzcmsj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgppmex.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxqjofb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2erhvcxzw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhcjpll.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2usagpgxo.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bclazyna.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kphxwlrs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjivyfp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2acyswbwz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2amotklrw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xutvvtdm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpdfnua.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfudhbcc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uhakymaq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xhceenjg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2afviiyta.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbcyrin.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcjsetw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdorvyr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2htsyminp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjklrds.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvciutx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kluchzde.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qashzhdj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnlwzto.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmrtafh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvprydw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lptltfmd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2srlpflfs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tulihfgn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mferbbrc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qddopnpy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cscwbgyi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvutmju.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyviyrg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uysftvhu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kieutfrv.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyaayal.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2phiiicex.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgomiil.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eupzlqfc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ikljqhar.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqbpxpl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvywrtg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2udaaixbi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdmsoci.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmplkpsk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmeofxj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkmsyyg.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbigall.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfpirsu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihharprm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsemtyyq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zucxmzzd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbatmwcc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2yleijzld.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpckdisl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbxaslx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdasjdx.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvfhqyh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpwjmrn.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlcgszz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaqnxme.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2okkjzwgl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbrbzie.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2eojpyuxp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqvtukf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvwiqnq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgfgnvz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrnjdbn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtwdduy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvomlqb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjypia.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qgflzmmt.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqkykhn.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2agjvmzvd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwkgxdb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeombib.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgyrkku.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxascdl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrhtest.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnsawse.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmntbka.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2htcxdxcg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2izmthzuc.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wgibzwlq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoebkqnm.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhixtiof.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2izvdqvch.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrnmugm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjmncgh.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfjeavf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyqgtny.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzvuboy.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdvwudm.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwqwnen.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpykslj.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xtniynqd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2zvydczwt.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqzlhpv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vfubbvhp.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvsbwjc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2upnqasjk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ohewvqry.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqejcvph.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qixndpxf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2itaxfbll.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnvdlcv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkbrozc.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2utrqiaeu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtohxgq.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2wocmziys.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2dtftbcab.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2eihhofoa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeekqatv.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2gndbukty.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aivpuwit.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxweahb.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tfebgzzi.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjjoawk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjirwly.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vukxtlii.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2esozywok.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2amoxjqhd.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazfqqqj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqudiiz.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2oobidjhg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwqvpat.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjnvbgz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ugewarhr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqrlpkl.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrhdjpt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmgivbw.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwxplme.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vedogjbu.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ielaoubt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpqoqbe.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgktxkw.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxiwcae.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfyfcij.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdymaid.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pruwmvls.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2cifslbty.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2beqtvfgq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2yolaqlpg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyvquyu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhxnsgf.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfdgjju.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gthgsylk.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsaexgt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iulnfwdd.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnrjtmx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqqazku.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2blnbmvsu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxtjmuw.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2figfmnag.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnmlokv.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2noittpoz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjreheeh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdicmbg.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2mfccxzhw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfpwcxw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgywrjz.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2yafhytff.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2paakscoq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oeclcdve.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxssioe.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zaotkemy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjvjsgj.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2obokbeqk.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2enwxwyjd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnjoxpf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kezexvub.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bygpiaip.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2hjekqmtw.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2lywembqk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pxixyyed.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2kvacicsl.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2provfrrv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuhszwb.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnwnklf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nytutaql.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvbfait.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwvnbuj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfuxqbf.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzvmewh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxqnjbh.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdgoido.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qtesdzrt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbozdlmx.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxmrdas.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjbtkgu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxhqyuu.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxbzfmb.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfoiocs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2znzwmonn.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmlytmt.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2uqectubd.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2oqazacqq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrucokv.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2eunpsekt.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdvgjnp.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2zqazwlab.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aivkbktn.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2gfemclim.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2hujhngnk.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2aqadfiga.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2nxowkomb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtldvvx.html


<!-- 参考信息 -->