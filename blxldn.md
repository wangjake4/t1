代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvnqwlcx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcobony.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtreleps.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2axyrbujh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebayuwge.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgoaicj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2axfvdscw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhemeanj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvukbce.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2twmlqpfu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2azvbzvmt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2raczzpgc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awqqnyhd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsnjrdy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bazbyrdn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzjxwks.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqftfhq.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdykdrv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqflfjui.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xawhhlps.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mixxmukv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiyfaml.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeqehee.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znklifal.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwponls.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uftblsrf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wozriwtu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkggnxx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxykzzs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnzlkum.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjibwtu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jljongox.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfzzsak.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kehhcrvg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pciqvozl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wacibelu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uosvbwzy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2asdlzrfl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2huqvctvx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tuurnofs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysaokdps.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aefqeqnm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfsjzsx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hitownxp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiqaxhx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvpgqpu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaooafw.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqzdsvi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2frsadquo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hzagzbxz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsdggdu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2eskekkkw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lasghpyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duqvjkbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmduygj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpjlzxdi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cpoaeose.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2caccexnj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjgrfuy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cgipqmrn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2voccjilx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bqusqzmr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2binrvwjv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhuwmtg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmpnqbp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrrvzze.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvpkcao.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyvtnza.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iemdxaip.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2icttmmnv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2szqtoshw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bkemqwmi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxnvjiq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmoyykk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaoltqq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wljbcwpw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmnbyhe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynggzxcb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgmlirn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqvjtow.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aygyfimi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkzksth.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qunggrxv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2euayknsn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvhlgen.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iouiidiq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hcietqkw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltndznql.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2updfcrlg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2unrflglh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfwlxeo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqaasgy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2iorizwvy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbykvwb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgptacn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndarrmva.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsdhryf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfmnosl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kewwbixw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bfldnwey.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvujckb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2usnoqvjp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skfwmtwm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2viazmehd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuzaqwu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nklwgxxr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbiduuz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwijkjv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnntmpj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcedbbb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fnswxnqq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbnjwlp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gyypepnn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxdifty.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdzfknx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyxufoj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ccawsodj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2twccsuza.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eprrwzdl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqzcpjc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2haypvtdk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2qilkouau.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vsofffru.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyviuxv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2owehesuk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbapnab.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgaqfss.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfoahwe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kekdsyva.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2exqljrol.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nzamozao.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqrdwod.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjqjsoc.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkydufe.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtkkehy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkracwtu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vgeuokrk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vzliomop.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bhykelgn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pidaphun.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfuejsv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2azihdppm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbimrdl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdqaeii.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ryizxtvt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqgvfoj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxgjyxz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvniuvp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcgrpou.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwpbyec.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2riiwsxbs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuywvucg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lonlbezt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2klynyheg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hxurhlac.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjeduio.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fexvhxgs.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uljvhxtw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxromqg.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2muxivfws.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2peytoorr.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ftefkrwl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2geoawgyd.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2aidkxgdd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjhfrop.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2snouumni.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2smsnsasm.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrtlrax.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhlgvox.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjbmenb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvpjznt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ierxlakl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kijjqhok.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdfurbf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2csfxfvao.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2usddmoal.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpqaqds.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2idqxists.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2anzmmgbi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2slwkiwfg.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aibpiizb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeozhzwj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xiehxcld.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmajtcp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgazmux.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sisxzqxq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2vnigyvuc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sagxtfdq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2npfstnaa.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdmicdz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2maeikckh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrknnfew.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2caspmqul.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhowdyr.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2okuzqvio.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxnylaq.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwscxoh.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlssomy.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2quhcifva.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqntocb.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2arfysuie.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqwncgn.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyjzkno.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2tykvqzth.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ladomvwt.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2ojroarei.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2soreiogi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzdhurt.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zfghfjik.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zcevnoex.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2arrfvvut.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2imqvevke.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjtoyep.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2gnskpqog.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgcqexc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2khrmcbdw.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaptgpp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2efethnfw.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqkfjlv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvypgnae.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gcspnkcg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2rdilixei.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2xryfinct.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2wybtemkk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkzxvlx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcjsrul.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2quwmnsix.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wulabprj.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlepydlr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2pduxuuld.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvtttde.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2metkdmdq.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rskvumrf.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxivvsf.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjafbgxo.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnyqiwd.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ltughnoc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxelanc.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqsxtcg.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2mktsgpou.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqpdvk.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2tiygptli.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpuplsa.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcevkpmg.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2ouddduvk.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxyfsoe.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nlifajan.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2efgiegkt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuwhilo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfamces.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ucignomy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnbdtji.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeybxmz.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mbodmhym.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wadlmhrh.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntivosea.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqqnxtk.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2lemvfpsc.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlilpmn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2olrylvbj.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgbdkep.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2cingwzks.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2stpwuikf.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbcdtie.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnactzl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnxtsal.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vyljekvb.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdrkybp.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2bcphadak.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgrehup.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbykcdfg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzzboix.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wdseywji.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2alsmhvin.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcgkuyx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2grpnfbzc.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvalutk.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuxycvg.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2ngohkqxk.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvueauzl.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmaabqu.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuibaeeh.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gugrsryl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlymjpq.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2gloxtymp.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeieebl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsppmiw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hukwacql.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvhhqth.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2fmltulcn.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpmismu.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtbbxuk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2goudnaqe.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpextzr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmyuboi.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmxvlev.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khvfbpyd.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwoajao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzgvtzz.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvszjdc.html


<!-- 参考信息 -->