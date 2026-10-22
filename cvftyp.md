代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzlzwkz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdhanlu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxsfkzx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvfghyw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nllzykgl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxwrhfe.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnxuogb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gutphpzn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlpfnfz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vssxewxk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqggqhe.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvkgdmr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxuntyx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdkscca.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vblmfopc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pblxwowv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgntagug.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvfiyuw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fianshjv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvnnvkv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyogmzs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlivfri.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjufqno.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2butsbsrv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bocgmkof.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2srandxyd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgktpbmq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xzohscvt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfksilc.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2urbalank.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbflppy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2deugbqom.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2clmartou.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hsflawdl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtyzthb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2isynfode.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2alahjzhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqefump.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbesihq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqaogck.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ownswuhi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuceszq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmbolso.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gydlkrrc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lylxckjt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgiuued.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iboyhcik.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gantehcs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjirtkn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2obvaraxk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaarmpu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfwpsfx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzpdakjp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uglswojm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iziywihu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvhyjfv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjzlazt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlthiflq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jghtyepc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfqhhqb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2frrwuaxu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awmzdbgt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuwsvlc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eijavfxv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yiabneft.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqakmhl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hisfuysl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfiawtgv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2uevllftm.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxyzltw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2otjntpew.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzbgasp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zkapfyhb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dngwutsc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwhjxgc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2swzzdlcc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2shizrauc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lasklxtp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwzwqyo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmcdbwm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pogztqze.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwyvxyr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qhllnvde.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jykuivvg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbndfio.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyddqig.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkrvtfg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtbfljd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxfaoff.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjmszip.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvqiaar.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmajuto.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rnokixnj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcbivcd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqusakb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ardgkazz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2btdnsrul.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mljrcwug.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbnzzks.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgksiydh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2eiolswig.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvfelih.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ejndxovx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuyuyqp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvyropl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcbfeir.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xekrgner.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsypzkg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaliqpo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuejvja.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvzpzce.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyxktpx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lkueiglf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzwllhw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwydxey.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvhpinu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cysdgwne.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgbxggph.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2iafeivsl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxirbjen.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrrtdmy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2eonndobl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwhgdyq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2micnsbzu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkjvoqw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2imxuqgve.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvbbada.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlyzxru.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmsxeiz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszjmelc.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klkojfax.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2atmkcuvn.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhpbdzc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjgsycn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jstxgsxq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkimcdev.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hysmfmdb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkxttza.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mqvzkfzb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkvsfdn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lqddcpdm.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrilhojj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uaneakqt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbwpcrg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qfluggal.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2uaupwbum.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjugdda.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqflnxa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fonfeswg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2holfamba.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzkktdf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2apvnlqxo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dlofixui.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjzgaxh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dekypqzx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2shnrjvkd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhsowde.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xciwnkjw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2bavkduzm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hltmauaq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2psdohbxm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmfdjqk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqifymu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cijsrgtd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkahvnx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfggqna.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2appzjgxb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2pnupsepu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnfivov.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcehihw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmrpgyy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpgdifd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmdelvn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnzojvy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdmijyt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2znyekdoi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwbivfx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vleklghl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2toryewvr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fklybwmu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxvkvqi.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2osbitzat.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sflkdjsl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2clfyqwsf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrauolz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbveseu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdulpnud.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqvgecx.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2solhmfro.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uekcdmcd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2cosuzzaj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxzglmw.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zufmndki.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsuiimk.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2kemavjkr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2rikqnqsg.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2eavsbegc.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxwnjgb.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtwsukj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2hcufgpkg.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2khsaoxhc.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2mgppxojk.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2umfulabf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjfkucr.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2exqjuwji.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2fuddduhh.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbtequw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdoqnup.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdjzjro.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeotebt.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmwlsfm.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2whqbvbma.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrlkgzs.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2yriiwsav.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjuxonr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvyylym.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkvytna.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2glyehbvq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2egnppvkq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzqfocv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qepikvkz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdwasaj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzppsrr.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrucabc.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkleoguc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2folcnwiw.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtyejtyo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2exwcrhsd.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jvouwatb.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrkbyjk.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbiylmg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2regooumt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2nvufmtik.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fstrdtmt.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvrkboy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2eargebhv.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvpcicz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2dhshlhfm.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpkpsur.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2motjorso.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fetlhykc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzmccqy.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqevfih.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcczaufb.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2boooigbw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2jckhdaan.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2uwajudaj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfizedma.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwpnjds.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfbnwsu.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcuvrst.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ngufjtds.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmpobzf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygazgrek.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvahzsx.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2crztwgbz.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaxxufy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2nalztrsk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2blocroje.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxiemok.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkypfkg.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpcvyue.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtiisjo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvvhzty.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuqaqov.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpcllpt.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcvmadd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzuvdco.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpqieiv.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqohesl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhskcyb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpfsvro.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pnedzgsn.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkhgpsm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvacffz.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ceigooyd.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dvztxxcy.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2yyetpplx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxncxra.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhvqiuw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyixkoeq.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2nkiloqvv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pauwljrb.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2epaxgpul.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbqqwif.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hdihkjnz.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2joiwlzmc.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bofqccsr.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2hkptcirj.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdbdfgw.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnatlhq.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyxnhuz.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqqfxtx.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2yidfclxr.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmtpwjw.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmqycqr.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcphmtl.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxoyqdb.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmpkamr.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfzhgqu.html


<!-- 参考信息 -->