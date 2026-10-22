代发 wailian999

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzpzluy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhjzazr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqoomrb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fepxumkw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2siehiyir.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2onjkjxjd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2peobvxln.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmpzzwj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nolmzfsu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2knptwmnf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snwbuhjf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkotiuk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvpghdi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhffwieg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uajvcwvq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thbuyjii.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dsdcwbms.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzdrbsf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqjbjew.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbfhppl.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjsphrg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gckddqje.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2poprmozl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiepfgij.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2thjslcme.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfbquwa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrseypz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tleoxhui.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjaoomr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oubsbqwm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2avapduhd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfzvkzk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utyltrfw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqmcvdb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2srxwublq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmfhdzh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrrxora.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhdynnc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lturgnip.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cgklsrhj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2omiqirkm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dghysarw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbymlvg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbvazjw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbqwruh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2okmtwcjn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwyyxdg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2legcimml.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjixqqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wujxdcml.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvivxis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rswmakqu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2npvfgtnp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvyzavj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqnklkk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2emcabgbh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2phekcvuy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oohtugqx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2koldlsfe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrcnfzq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnkusbz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2enzcfypd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnsrzxp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2azbnxtsy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2swndycbi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qorhmgqu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpifyuj.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmmsigv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2glrkamcl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tigmault.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2htzhvsyc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxykqryb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxspvjy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcprssnx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvqcinj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvizbhe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzbrjzc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2omkztody.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zckvzqtq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxnlvxv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvdwdtt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxakbkxs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ywazszct.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwhwuwy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ruotgxpr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrfnkff.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ikupdbtx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwybkmb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mkekmnxq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgfppfo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jkknrath.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzujcld.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pugwxxvi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bmolnmyw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fohhamwx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zljvqbob.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whopnpiv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gllwybyf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjcszkv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbdemtg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtomlww.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tijiebov.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2oeilqesb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcfislx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfvghli.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtkggjc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vuasleqx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aoptotbb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2akocacib.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2plkmfnuu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dzueupgp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilersnyk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gaofqkja.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wramgdgs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjjnfit.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjcvrzs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxcwnda.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvmygci.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2drhktein.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2djjzpxjx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxfnpnl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogocyjmm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lyrkgeda.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhzgahn.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oagcngsl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2shftxzau.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfbrznh.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pypgmxwk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yumljowh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxppikce.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaanfdu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmgedcw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfvwson.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaienld.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gibbbgnp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtlbwho.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lamjxhab.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvpyvra.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmskxkt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoejxwv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gajhmuzr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2amigwlvp.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqoercn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfvgiwd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaenqkp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2guyoojpa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ntynrjrp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zselxqbo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2akobzzhu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wyoboqwp.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcnivcf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdfpmtu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrixvdr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhfgbsa.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvsnuzc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lceypxvl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2czevtnhq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwuemut.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cymwyefl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2guazfqvn.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nutxgbsf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuniewu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrkbeff.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqluqnjw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqgwnim.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrwbznr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2uaszyeqk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxexatm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjxygin.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kufqzpdc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcggvypx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnkmcvp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqnucbg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydacxedd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxbtsni.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nylaqvfw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtpvvnb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmnxtuw.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qopfzyag.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2agiinbfn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcfdbct.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiakwauv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2phaxstmx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rywnaxjx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zivktmds.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiejrygz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2esrwklke.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjasdzsk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2puepxqjx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbzjbyn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuqdcvo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xzycodax.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsslirn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuoixlz.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhrxyrc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vggqeiog.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lehxxqlw.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2minpmfxa.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuqlykb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2syosibrm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tndmzvpw.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdvjraw.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwfatqj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuelfnii.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmeaszg.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2luonevwi.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2pqudoudz.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjpchfu.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2dypvrshz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgwvmjm.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2cplfyari.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2widypcaz.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bifzcyxr.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjvlabq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2xklnvpzz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fznabocq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbrlllg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnpmwnc.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2qpazmyfd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2uktxlgxf.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2slmhbnsb.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvzmlez.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2bthkbsrg.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxogzmo.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2auzviame.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2knnhcdnq.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2npiczxto.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwoivhv.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yhipljhu.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2albvghei.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsjczqs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpiclsq.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2teyyapha.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcoapag.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2soqulaas.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfncqgky.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqxrmxq.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhxbbrl.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhroovpd.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqhemhr.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrdfdge.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wquoqabo.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uaewmziy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ninyguak.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2bqlfygtc.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2flzxpsyy.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkfsmai.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwiqnqg.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2wmayyqdf.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqfxyea.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpdlohz.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2eertsnwz.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2psfdhkdy.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxiblft.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlceyjh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2oisaqysq.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpffowh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2phnngdmb.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyanfgq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdutxvsl.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzgevxt.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcsorto.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjuntld.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxijsbh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2rttalkov.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqxssfb.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwfgwnz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2gefccuwx.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyqcblx.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2mueuzufl.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2nptslzsw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2exqugccp.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnhfrru.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2bkekmtah.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2nllxpcoo.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsfixul.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvlfxdw.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyantyg.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oboxfxvo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhrrdox.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iflhmsiq.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvztwso.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2nexarnyg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkzqbolg.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2njolczcu.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2gvloempm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2veicjgqb.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2zunruucw.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyiswkb.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2vipugfes.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2krpwtlrf.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2gphldiuu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epwoakba.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtceqyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imlhgpuo.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyjqrnb.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2uyniyvez.html

PHP ............ 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bnklascp.html

JavaScript ..... 252
来源：http://dali.zhijiandao.cn/Article/details/gt2bsciqbwd.html

TypeScript ..... 212
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvxzbjo.html


<!-- 参考信息 -->