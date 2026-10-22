代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2geijugiv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoqqnkb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufaatupe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzettfrv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqftcjd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zywdaywd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ogijsygk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2loignrun.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syhlvpab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nctutdal.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnmpfml.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyydtmbl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrewsaj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxnfpatu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkoranz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dslnsdod.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pieyfnct.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ssaqqoaa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfycueqj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bsughsgl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfapqsb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dashewvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovrtvpv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2joeebcue.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjktbwa.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmpgtpv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sncfivtc.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dgogptku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vitwaksk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2frupfbhd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2djpvjtcx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fuixnkky.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2djadqaus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgfvxby.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlzkxjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbuunrl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rverdnre.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ykiehmmx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2glgvvwfs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnttjqv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhiggdh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhrbkan.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmjtvdk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2isuluyfj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfsptfn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wglmylwu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2elrqnxho.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqmpjck.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gocyeatd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyuwynq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rberolwc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kflxbybr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2munzygbw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcoibcr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2snbaukgl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjugekj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uobblzru.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2atcktams.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvwmbfn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wssaddmx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlalgpve.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaibslxh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cknydtyc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2soyevhec.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jswzaysc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvypwbw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2reefihym.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pklwyxvv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eggjxejr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwgjazc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiimhqg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjnocnb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hdktxzsd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2guycwhyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mingoltl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwdcvju.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhgrfkh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ahifttry.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wgreuoty.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjinpsu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuewfnja.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fysnjvja.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2thtotgtl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwazqlv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpnlqdf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnawoaj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xubdsjzm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2eatgmded.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2olryksxl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pntldxfd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqlcrva.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rrthocya.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2evaazafx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2otuwzgqx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vupsybox.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwmslen.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzgbgqn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjixbzn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqsvyzq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zshzhhkz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfnshbc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfszvxmp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2twuvvuvd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmdbsfy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iavuhhbd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzezmvpk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2eayicetg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2iafjupay.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ygajlwrn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpzxana.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwzjvfx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2boemotqb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wiofeafa.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnueyua.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuauilp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jklletiq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2scgjvoqv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2auaomyrb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kenfipaz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2umppmltw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdjtftn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeemufkl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyojsydc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mosliojx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdrztcn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyfwyjo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fvbvtjub.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qldkxtgo.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaeerza.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2toditnxe.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zsatedgx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrevwjio.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtcnuhh.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjqcijr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dufgvdxa.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpwsojb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiyqenq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnnvgiv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcceztp.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrvdbmi.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrrrpdm.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsgmnxg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2csywhmco.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2abgfkxjo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkyglvv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2nduiyhfn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2blskvlbg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxazbigx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzigvwl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrejhqyy.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fghpynbt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2odempeds.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjwjkrn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrvwcyc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqgciak.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2itfekgrd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gurgdqst.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdebyeci.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqnbsyu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkwdxgv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzolyqd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mynwdidr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfturep.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvawxdu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hstnhcpl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yytzoqig.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmuywsu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtwvxyg.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmjazmy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqlaoee.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjpbrhf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyrkhjg.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuelxzd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qstghyon.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzcddtt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2jnccttyu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzgipcw.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgniolro.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hoodaoue.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2czymjiov.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lzikxmip.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaedwjf.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnriznax.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlulthw.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2avohmiwa.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2thjgdrmn.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqcxtez.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2paxckmgs.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2uehzywny.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxlcobc.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnchvwq.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcxapwn.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2bydjlvok.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2umwinatw.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2bifsbjtw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2akncxeda.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2jbruxobt.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqdsvoh.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhvamqd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdujwhz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfvbsyv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bttrxztv.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2oynzlvea.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwmpczb.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbfpwzu.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2eltdacbr.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bajclgzx.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2oahlwhwl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2udolgqsp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2aphtypns.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2vejzwlfd.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpaxmhdk.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ktexmwcu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaqlkaa.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2enjkbtlo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyiwzgz.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqnfpxi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2pwtyiofm.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ungjlkuk.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzxftpo.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeywdxx.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzcedru.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvbsipj.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2txgtakso.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hypmihmn.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2yfldaxpd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2aogoqrdc.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlygkjex.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqlflpe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iwuaqwmf.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2uixuigix.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2haprssjz.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2haealzaz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpwycqr.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgowewz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyebccsl.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2filfbjxh.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2egpphiiv.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkupcww.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2mabhggzk.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2roergfsk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsuwzwg.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvpgmwx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pvleeyzb.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uxggqhuq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeweuoq.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeigury.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2qdivfltw.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2cnglrkgi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2pewnzfdi.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjvayee.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfrhnum.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkmcckb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqinurwx.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ouclmilu.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpytmme.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuhubti.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvfkynt.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyxkqcu.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2owevdilt.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kysthxwl.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbvjoru.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dirctmax.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qatsbqby.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yxajozny.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdhpjld.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2sblmnefy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2shvlmvvp.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhkzkik.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhvzayv.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrtyqan.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2pociodlj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzfrpcg.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2ucicsylm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtcwvkc.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2hoexaigo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2panbjyql.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2xmndajwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzdxrsf.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2vicevcmk.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2cshpzogh.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrowphr.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdyjngy.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2mbytqwfz.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqwhclc.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2uiynsqru.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhxinhe.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2llnizemg.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2pamfygvj.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhmvigm.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbbcdsi.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtetsfm.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxukcif.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2vebjemnq.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuzwwvg.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2mikdlhef.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jheshfrd.html

------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2pihorfhy.html

合计 ........... 2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2edihujop.html

按章节统计：
来源：http://dali.zhijiandao.cn/Article/details/gt2ubowkchf.html


<!-- 参考信息 -->