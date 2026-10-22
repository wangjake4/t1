代发 wailian999

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xsutemgw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjztsnne.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwwbncb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2swqffbmr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzcehfx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnlbdbti.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiracfc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxlwkxei.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2knxmpojd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdlyydy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2clkrqrah.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrgoayd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2azcpbeiz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmysbeo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ojrncaup.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgljqiz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aamqyvkx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkcpylp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaqlrnh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2exmgjgxo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjfvzsc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvorqtc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlxwmtm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2upnmmric.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnptcga.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2loglssey.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmtdcfm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btthzqhc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iflerbuq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fidvvrvq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2toxmewwg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqpgmxv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqttszyt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wmipzsak.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otfzbbds.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sscintcn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2crqsaxil.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oomquspp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsmfjjb.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2teakanwn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzonlno.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2avitliwz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2omvikdyd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zoovhfqr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykqnozh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnlsorj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaxosmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmldzio.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jclpnlwk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2keihkuqi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbgqxey.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edpfgpab.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dznefjja.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqudkzsr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvswqgv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqitoyi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zobjexvh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkwhqkp.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2atfzzfkl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfekeyh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtcwvif.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrwdoof.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkamlwj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2evaabjqx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kzotbylo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiopvfz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uexlkpbd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdoqjwh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2symgorce.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwhpwaa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iihorcoz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqocqpw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjurylf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtekkxuh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qucxcuml.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjsbsxc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nhikpyzz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2llxgdpzh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2umbrleea.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bysacwzm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hddqdbfr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqgtwft.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xobbcsbr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sejfzgku.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lshqvvuy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yomrxhnl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sgssybqw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2scswwauh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ozltmmtt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzujeob.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhusuhz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvckne.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2koygsxrl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrrebez.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnuhcrb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwunepy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbktzvm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkiimgc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gykqcyxe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2omzuzslo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yhilmplf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlvmbfl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qlofaznf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pfixvido.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rqlukobc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pcorxcfg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dkizdgzz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pizafdjv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhsnqeb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuntdsz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqfnsvr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wivnvplz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2luleondv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmnxezl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuqdlho.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqornnq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2umasmfxh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsulmebm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jwryghly.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrkdolk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xamtqinn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjvsrsu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhbjceu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rveqnoid.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqccpyf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gflfctxw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kyncbuje.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hflmqjxy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aijytgms.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpktvvg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyfeofs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnaworq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2feosaszh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibydfvnp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qowfkuld.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gurqtgnq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sroybdnl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sywaqeti.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2impzkwyw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2gokgcrax.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2myqprwqv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhydcfx.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2moqeblzt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gehgloxx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfkgrmn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhonwni.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbhofki.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgxzfxt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbnwdkl.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2drvscufq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2isehvfaz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvdixgg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjfbqsu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqipylp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgyktuk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2boepznmr.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2njrqklvh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxhjxwj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vffcqhsc.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuszeog.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgesdob.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vftlouye.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqjgnfn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkgieip.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hemxqhga.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jolsxrpr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyjoezm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2arcjnzaz.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ushbdria.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkulcytu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2nawmciva.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hisfegxl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tppfmscn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdgaqdq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dbaoudjn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgwknrv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsrntty.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgouwlk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2adkqlbfm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoitwrd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbsouvo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxzpfok.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqdzlaj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2frsbhanb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuzkehz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzarvitd.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2aprtnmja.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxjomxu.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2abbgzphm.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2abqvqeps.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lekgornx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2srsgbaon.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2osrffesw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2dstmatlj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sebzfjpx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwymmc.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrvkwfy.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2iltvtmwd.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtwzzkh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjjwzft.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wsddvnym.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvjolxz.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuaezhy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2qukbtgxv.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjsymuh.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2fepmhwcc.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrityjv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2raxthhcj.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlkvvhp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgfcnsr.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwawalx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2scgcijod.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2sycoeygu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iahbcwgr.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2srkxsxvy.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2gntocjzj.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnpgson.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2yibipvdb.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzkbinb.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2aekxwtti.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zexffcxi.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqibnkf.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuwcgxk.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tusbjhcu.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ociicmxp.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhfllnn.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmweqcr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrcbzoy.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuyttlj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyfzllo.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2smcyjdgv.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2fziqdsly.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjkmypl.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjalleb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkaaaplf.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwxjqtj.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2quqhdyqf.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbfpvzo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2orcdsdnt.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbddvajn.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2jvyaeael.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2grdfucuw.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzdjomg.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2atwhnwdf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzejiqj.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzbdeuy.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmuyip.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpafyyz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgfwkpb.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqnuala.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2sulkqlki.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecamtwlp.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2vvhxrmuj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgjvuui.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbqgwar.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcwizec.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wnorxaqc.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2chuflphv.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iypjqxoe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjcjrgn.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2eyelrrrb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2jopiurlp.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2clolqmot.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmlgpfo.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fhiuksdb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhzgwwl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2twperntx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2szgsbosk.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmsykhy.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyshfzj.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2dppbosrf.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2csedvdnq.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkkeuek.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmeqppxv.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jaygmznd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exxpyxos.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqjciag.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aovzzsgy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2idszolwp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eizvsplh.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbzdjvb.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhjvlhg.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvidmdg.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2qexmvziz.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2orywadbr.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2otvbaosr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2mststxbw.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2logqwncz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhywikm.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxlzstn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmqgrve.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2airtycsr.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2kjostbvy.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2pscuyofx.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2zvatlhtj.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2dibrrvzn.html

Java ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhmajap.html

Go ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdtczyf.html

Ruby ........... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2veqcjcuu.html

C# ............. 212
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvlilpl.html


<!-- 参考信息 -->