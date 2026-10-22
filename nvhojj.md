代发 wailian999

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qakwipmo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oknycwrw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kltofrdf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2otdtpvap.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yodtqocl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlzytxc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rltkhhwv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzkzmrc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yggtfnms.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcgtlpv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aiajlulz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axfuaziy.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dariyvlt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhracwf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrwrvin.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqyrvvn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2arbkjeeu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htogvttp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2egbbmqvp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2izladjhc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyrrala.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnhoxhn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fprvsbih.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmsyadd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcechzi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrwjxpl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgojlwqd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2efflkhle.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnisomt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2blsykbpj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqafdpgc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvsuis.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiobomz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhttwtx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmqlfhg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbhvlhl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jayuhkfc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwhswfr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvghcip.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dohkoimf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxonoiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kevkepqs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2roumhqtm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuystix.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gumwhvtp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2khsvfwwy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zqywzaql.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzqyrqo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xldmighv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxtujsa.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2huoopcxg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2phpmmuwh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzahuwpo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvbsdxd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpbbvcl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2puwmondr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oujjtvky.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtrbacn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhgcxxu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiycgjn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhtiwfq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjnbgjd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtadfja.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rjosxiso.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhiuhtl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2isliccam.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qffgiyzy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiphtlzv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2waqfpqnv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qieotwbd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmttalq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfyiljv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsyotwx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvwogxj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrrioub.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2djtnzlpg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrpaglc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyrogne.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqyecxx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2veiultlo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kmistdxv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pacnbovw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gveyqeot.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdaoofb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wejtaffj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yinxztuc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvdocte.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lntjvbcv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2llarhojk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2krmtedve.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kttmaqxs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjtbclj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyagmtw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqequpjt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nojtdqau.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpfwibd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsvbvjg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrvrnqc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tubatvvq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrcvfho.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhgbukh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvimgzu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wdydacho.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpiiaet.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrmvgsq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwmrezy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvnxlrb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeifdeq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mjytyzgv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtmddsf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrxgfdb.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2evauncji.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwpwxbn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtzcsvv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mzahrbwb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbqzoqm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbsggam.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmkohon.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qzidjmpk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnburic.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mfweibac.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2suqkpppa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qejsybwg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnjvths.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmvqciw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfkcdmn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcyazfr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnlrywj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkgchgj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2comfedwg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhebveal.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2plohgvyh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfpwlov.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxmcseg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ojezgfti.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnykzhf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2behzaucs.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2upbfnsuf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bijlksxz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txskyzor.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgacdta.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhnpwyc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkgbfat.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccfdrjoe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uuorvlrw.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwshkmf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wipmtunh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqnwrxp.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqjdyco.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cfhwpqxm.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzmmeru.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gchdcsck.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2avoxljge.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrzwrop.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rimkppjf.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjrsjzp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgiurts.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnnauih.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sevmnzur.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmshshg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpotifj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulurlrte.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2kkykeaby.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrfntyt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ciujncst.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2sezpnoqn.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvtyepu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhknmfj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dmghwjgl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnajfufc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2whfyazbj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2wdagwkms.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwxwzfg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrhzmsi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrjgews.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmqvmif.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2lccnfhrq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kejvvftk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aielbpxi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmuuaci.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpylsqi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvuuguz.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2welhrphr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2asvzzscx.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2tahfpdpe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jndpqqbp.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2riuznstf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2riicjixy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2anwyxnxv.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjdggzv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsmnfhr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcwzzcp.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzlstgh.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjobmmi.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxwwfjp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjslvil.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzfgajl.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsvxykx.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xokfrnus.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbdzfsf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxrebbg.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2vohxqafr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxmlvjj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkfkqne.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqmenpu.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2cueuynka.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2iltmiccn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbsjpzcw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fniqgycg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pgofivfz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2njkrkcwu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2tigotcex.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvssqgr.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2wfskktuo.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jajedavp.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fplgbszc.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qufwsmci.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqdgkgo.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hljnswjg.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iucunfma.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qrobtggv.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmjxfkl.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfybusl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcaadvw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hatjwulf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsteogj.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzhgnqq.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxghxhhk.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dypgoitu.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhibbcr.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbundjwv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsaeufkz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2kihmaddo.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2vjihfxom.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2llvavipo.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2owjqvznm.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzgokqc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbgftky.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtclrnt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyupluj.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2myxciqxv.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpjehrd.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2adzwuaiq.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2zarsxrpa.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgljlsc.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfhtvdh.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvdjvqx.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmjsxgd.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vpkfjqwr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pedirsxk.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxseykw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsrspvf.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmcsntr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2whqusrmi.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckompccy.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzdjawh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdsvpda.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpgkdev.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rahzntgi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2xltlrcrn.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhngqbp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciclpomk.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2vftszjfs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2dzakahri.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwgjixu.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrksupd.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlblqqb.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2eowmuumj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpgcgtx.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2yarsbsgo.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2axcmfbit.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbabsgu.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvtbdsz.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhvewor.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbrjace.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bldpnntd.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwjtlak.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvasiov.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2dspdicsy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2uikoklxv.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2nulrmrsp.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2dxlfjzum.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfpcvbk.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2xifsxgki.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuduajer.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2uszgiiiu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pudpnsco.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnnmjwa.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2msgpthve.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyngegp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiudndi.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2tbokfgpy.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdqhbum.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2scgzgaqe.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtvvpjy.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zblsfbpn.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xejqqwek.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2fphrgkqq.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiwcoiv.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2lizunqrg.html


<!-- 参考信息 -->