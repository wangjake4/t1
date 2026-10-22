代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvesyaf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrefbqc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkyfokw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqanpsko.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjxnenq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtdzsik.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qwluuxrq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2npnfobjv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvouqssi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2munwssca.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrrzlos.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvdzupw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ighkvkzz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2krtqcuvs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnrjzzc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cybzjwqh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzjtysu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbymkht.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yztclgjv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtahlkw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2knhcuhxm.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2anckqflj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mizhfxly.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2giemgmmw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkuuxyi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2olvcgmmh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbemoggm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ousxolry.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jytnzzti.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2umqjfhfy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iujdslnb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cwiztscw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2csruskgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vuufhgsw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2urlkaxcz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vywexasb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmivajb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiloeup.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcnlqqd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2skultnks.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiszado.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xccvxdzc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiuyqih.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzdzqnx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tyilfwiw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuquunv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjjumql.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpxgvru.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmfbeiq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2thnusmqb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzaxltz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2szdwsjat.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrucneb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqdojby.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ekflbvra.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tnillpgy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkscqtk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjffrhw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbfvwwb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mairdxgs.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkydjkyu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovajsgfn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmegvwk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfmlkei.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2orottxdn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzzchsv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrrvisj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybipquiy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aszjhquy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsurdcik.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgqnbtp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2urcrbieh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ddugrwzl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvstqji.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zbraocam.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvfsltr.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hudwpivy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrdshpx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwesozn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2slzeoqbu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qpztopiw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2twevwazg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzughsr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmrkclq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oafzbwsu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxvwvav.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrzwxof.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpqkiji.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gtirjkgg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ecndktcf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbjrakz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjwrsua.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgbmaqy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mraanafb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2upkzyvvi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2enmpbxpu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tihyvphl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lsenvmdj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2meeignik.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlabhht.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbfyeti.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqmizfx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2afhbtdhb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rehznyzx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2krnixqoe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddvqyaw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxaaowu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrosdcsh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nwadjjyr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dxllpera.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqezfze.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2woucfeyb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdgblhh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkftfjej.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2govfyzwd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrujwbq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pdknllog.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiyspay.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2imjplmzr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tocecmsi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnriyjz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrhtqqn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xisycild.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfhrjm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lexsnzft.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsazrgd.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjhtcld.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcawrae.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2spgwnfob.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwftcqc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lamjmvac.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tatkidce.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpherkq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgjiaoy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2befksvsw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkquqwof.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdgonei.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dswrinyr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzckplhs.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwarcoeo.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2blzkubts.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tldhbgpu.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfidjvon.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrghrhrq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2djkoxrbn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2eysbpipc.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmgjxic.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvotfpcc.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmwijbh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrahfmq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pxupcmaw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgdmusd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiexeil.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqexmcd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxelsrhi.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2odhlqaoi.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfrnlfd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2czeoyfpo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2bznzywhb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jnfraeas.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2urvvuifp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2azhgrjcs.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bolhinep.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2crlqbkyy.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wtrnhyjo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwglkymc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2iizqyknz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhtzvec.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ivotevrw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgqsqfr.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lowzcfiw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lngxqjqa.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jaggrfqi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oflkrbfw.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gbposzez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2rplxeoej.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqqvzwc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzaorcbz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdhykmy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaefhnp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zeytduyj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhgzfsg.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jifoyqto.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2zoakgeup.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2myiiolpm.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2csvdndvz.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bemftkiu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2exmokxyi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2psxsrdse.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2kubkblyj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmtplij.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wioaimhe.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpabkou.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fcimwhib.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpjkusy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2isegxzeo.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rzejafst.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2bzempchy.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsmdgyw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsdvyvc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2yawtmprf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vkagjcez.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2nbefvekp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2swkipkha.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2sxlcfkpq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2xevamhxb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2aotvauvh.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqyuybw.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxwosxr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqzlydp.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfugmqa.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uziljmiu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhbhygv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpmyork.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeivrbw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhttobzk.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyuohtw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2dijrcbln.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eexnjpae.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2biklomlw.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoyhdjd.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2gsovcnqu.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axkbmtta.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iivfiydy.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtuqrh.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwtbjws.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2gzspdyrt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2abqdfvqk.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2sdktorvt.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbipfjq.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2shpotmgh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2oiazfzmg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2ellgsdxd.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2tdblcczj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2shhfmvby.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2kftkwrmg.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoqlwby.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bijsiqsw.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2uwehkyqj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmcjcna.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgusjul.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgxtrrb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2vnztrteo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uyffguvj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrionxm.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjalfxy.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxwrtui.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2fyikgppq.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2onnxfpps.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzokvkz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xssixfff.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2fqitbdfr.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2jvitctbo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhaxnjn.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jiofcbmb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnzhinj.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoayson.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2kotregua.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2kcruwinn.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgydiqqs.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaccuwt.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbmlcmq.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfvlqiy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbanolxk.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jppswxft.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ektgozsz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnqmeqh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbdzptm.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjowkev.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nngqqyuv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2ovvootyk.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2kukklwlo.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnzxesw.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvnfgyh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvedumvi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtxjpfn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfqnksq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxlobyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oglfatwz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnpqqvd.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2azipvfoi.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcdjurw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjtqowp.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkhxbze.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtqpudb.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjewjif.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zieycxde.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsthmmf.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmvxkzj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ymspinrc.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2pcunnruc.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2pspfeetx.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaiorst.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2knjjodqq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2habjtwgg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2lgabyigj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzyugmi.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwnnksz.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2sstldioj.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrisise.html


<!-- 参考信息 -->