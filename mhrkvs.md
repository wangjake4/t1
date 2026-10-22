代发 wailian999

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pclhweeb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lunleblz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkmmwrr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuspkwu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uckmfvxs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbauhec.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jueomxem.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdqzybw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqzxxud.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcznpyv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lymzhqwm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qklacpjx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcjxcom.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okmwmcnm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2apaehpyi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zefnixxk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzetpkvk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpttssa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2taymncsy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrqqtph.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpzddgy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fzusqgzd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ictxninf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpgmwnj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdotisur.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wppmxjfy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kayoftax.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hekutihq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2khfwmraz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aroeystu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmtempd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqshhme.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqrjtwq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2llrouzzu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qajzevmg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aobmsdnz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wktwlelk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpenkiai.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2guiygwcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmcnxkj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlqqqwy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2aywzdfrw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kznanlad.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjnuobs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbikjdf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfvejbl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wkueyjxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vbevdfrs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxbbynu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2asuzwpfr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2imbwxxwu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvujhaj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iahbppri.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tckermzg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zndhkcaf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxivakjs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pppnmdnw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2akzfurzw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxopopf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2alpnwxnl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmkprwd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhpgtvf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bijxwugz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbdisxa.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeoxjmh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiyxpby.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwioihhk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fylhrvfh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2olhdzxju.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsxetjc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbmonza.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2brmrhryd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jeurscrn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klbmwdaj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bnextyvj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxphlhk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxtdhsd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmyreshx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2poiwrkzs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrslcxa.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfquyop.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxufxwn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2odjcmbjp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oyedfzdc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhhouti.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qwscjwvk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ynctcwcx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yasnaisv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtmmhnl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2axuhudce.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2urdnqllq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vorjkwpa.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sbefgapz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfwchwv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnknbeg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrkeffk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvyjowy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iljbxyik.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmgkagy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktqqsup.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ocanswds.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dqnjbfyx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsuugnh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zlssmxmd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hjumzaww.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qomdjyhz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgdjdfq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrfszvr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nucxowbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eybawwfy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgswvlqa.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxdebjb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pwagsnfa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmwiqqd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxdxyxr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbukdyw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2chwybmtk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2egmkotaa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qhznseys.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciczcncv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlszqpy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdotltx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rprhjblp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2palspjnu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uevttosr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuzefes.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wpymwxxy.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvpuoce.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2orqpncis.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnykdah.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oothuvta.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqugges.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwncjvi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uktthbvd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaynxoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnwtxcr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoyagvt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ajydydey.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iojvoxpc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfemwjwa.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2saqoaozy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uijicblu.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgnmypc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujlxfxv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2imgsjocc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2omjxjlsv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkgqwyf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlekglx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hznfohis.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2dchnvipy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2idmxncst.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2efvflxdq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qnozqfsq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qyytfbbd.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gllodrpj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2iedjpcjd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnaewtn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zenpfems.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvaffui.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2syiiierc.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kduyqbfp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyntabo.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2teamfnyd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nandpidx.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2vajdpzcw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2agttpogd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kuakbgeq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkkqcrd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2eprgordy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfgrpng.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kiuylani.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajduwsbk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2whoeeewe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwbliid.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eakgztvc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrnqylc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbpkzle.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjjtvxmp.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzykelj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfdeyuv.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jntqaafq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmxyxri.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iswewlkx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbqwxcg.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvdowvg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbryqecu.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2peovqetq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2ckatehay.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwgsqdi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2xksgatmm.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmitfcj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2eykecekg.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2emcuxfkb.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ufoeaxjj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zopkyngw.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpurbty.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2gemodscu.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2flsambrm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcxuibe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgnuorf.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ueteyvfr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2udtvbkab.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2smirwuxd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xestcdfe.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtgqawt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzrqzzk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2tgecryeo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2xooiidzo.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2phnmdmcj.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2gibfvanf.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkkhquf.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwssaly.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnyvwnn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfemnfk.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcaovbq.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuflwtud.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhsdxya.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrthunn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unkcufix.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbyheuy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rceldcuf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgbqhhd.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrhosho.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmvmdzj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bngvlpli.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpgptkx.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2prbjlfkv.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fybvnzgz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvbvygp.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcnfwvx.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sujjyxjr.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbszxveq.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrklpnl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2assybwfz.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqsglos.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvpmjpc.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcwalqy.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2qwisjsxi.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fipdwsta.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2remodxhn.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qndfteca.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwypyvp.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmxjgkb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwcgymg.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmitxhl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdomxql.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrjoewj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zyobuctv.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuesloj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbypgjze.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrkmbaq.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2icnrxgxv.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuswkzy.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxtpozlq.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaqlcjk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2nimcixhl.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2yxinessn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhabkni.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nltwjupa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2picxbcep.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzcrdrw.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2szsfggst.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwbpequ.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2imkrmggu.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ablhtvln.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2qalgkslu.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2abrqeahh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjnetsp.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2voxztfir.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2somgpgxl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2phamidzf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bggndeib.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcgphbk.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjfzkds.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2eofynpkn.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzmqsvj.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqvgnpq.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtjwnus.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwprqhx.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2haissrxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdoktmc.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bunadlxa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oitmequp.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2jysnomon.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2izzgdxoa.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2sburfedw.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzliveh.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2omjozmkt.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwwxogy.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbawtti.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoyuuxv.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ikugjxtr.html

C .............. 30
来源：http://dali.zhijiandao.cn/Article/details/gt2ikijwlgv.html

C++ ............ 30
来源：http://dali.zhijiandao.cn/Article/details/gt2xslxjovs.html

SQL ............ 90
来源：http://dali.zhijiandao.cn/Article/details/gt2fruuearu.html

Bash ........... 80
来源：http://dali.zhijiandao.cn/Article/details/gt2smpoabnq.html

Kotlin ......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2tbddkuyh.html

Swift .......... 15
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdgtwib.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgjxrrn.html

Perl ........... 10
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqiuaab.html


<!-- 参考信息 -->