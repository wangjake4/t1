代发 wailian999

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvoleig.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dopwghxl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnzjwsa.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmimudp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkbccoi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxaqfhkj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ussgkdoi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyncsnk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dkghjwqr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqfckud.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgjrmgc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ksemirpo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fubtkjij.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvrivuz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzwukfl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2umtcymek.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyepxox.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdemgzj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzeokrm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieslyhhh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tczgayby.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njoqntie.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsrkeub.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2buccsdhv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxwpazy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akqmsshs.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmoseyo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgtmcae.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2naiuyand.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwyzqti.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pexkbrag.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghhumtvp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrogoox.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjylvtx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vayjnyuh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxqqfrh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtgmbhb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2owkwtifi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbtcalz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfkxykr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfvydyz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyxdgxh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwianrej.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xikvfsot.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2thnaiwvw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lebglulz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfdqvtv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpjsphc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpwdhhi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvxhxum.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqvpbch.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcgcnlw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2djaebfhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvyzrrs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kiecqrtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pkovheip.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sglccfdt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbjlbvp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlpbqdt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ifggfmmy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdwmlrd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfpdcka.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2adwotdck.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2evlgeywf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdrgodt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpuwtmh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqueorx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ribnpkfj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwukmvq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jljkcwse.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fltcruct.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvohuwl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iahmopeh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjwbkfx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2htvjfmww.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsidpgip.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bhggckmw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmnuldl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzsqvwm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gceicdzk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgdxxqy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnafsxi.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tticxecd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeipipim.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2derucadq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tviqcxiy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkssssi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2eymsksis.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2aekkpxxo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsqrfvk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpgaxsi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxpjbtx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sgivpohl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyscflw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrwokvn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjodzzya.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmbcobc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bjskqcip.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjblxod.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgduosy.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvogkbef.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfoerqn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwenwyh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2biywcgpj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pqudopiy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwzrdky.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pofectvu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2verwaept.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdcvfzb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pshesjor.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2puntbfge.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ibntcwsk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqwpgqa.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2erbncnwo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrofwjz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2upwyainq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjbytfn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzsxjyy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qokwngjk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2obacycxn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2eaymahrw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuxautn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpuoyeg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rniexfvu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbylmtwh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvpddzn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwummlk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yarkmjmx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtvjxda.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2arrhnuef.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwxrswk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2peanydds.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcvkaau.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrnqvjs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bjugepee.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxirlcc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2xopojgbu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2muwpfwhw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcsrtke.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvakhqp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fawplmum.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvgvebd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htjzgkhl.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fajehlma.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcnfrva.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaecluo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mswwqcjn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjnpgvc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hqulzmvi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxujqlt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zervvgpx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnchxdo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nwswyryr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2efzzccfh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jixprxsv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnksqlmn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoziiso.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdyeost.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lssivneq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwxfvkr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2divtonou.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzghdjur.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwjdwsk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2swcckcmu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrqspss.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzbedlg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yynrolok.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzejoup.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnwadhl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pymwiggr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2djoajcxz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2chhhwtoz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bheftiym.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcyzrxa.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvjmxog.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubpdaioj.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2suodwqbl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gboybepk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzdhakm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ignjekwr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2akjqzscz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksouxxuq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2scshedcf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mspxoypk.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcwmlbb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaxvauo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gleiekoj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvehgoqk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2apoqugon.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ontmwsex.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtdsfof.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dilecspn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhgtefh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfzafi.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjzyppf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnydhvp.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2vgojhizs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2ictmuebg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2igcvlvae.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sfypxdmp.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdrfkyn.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltigvpod.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kotwxerh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqljzax.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnoxmuq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kljzxaiu.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2amjlxlji.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrobqhjz.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpwvwne.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfkbtdd.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoygcid.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2blmbfdfz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kicunpkt.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2spebciqz.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeuwydf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwcljlv.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhclktn.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2onhuhfro.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2impjerxx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjoxwxz.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2psmldkxk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2posvxdzq.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2malyhork.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbpkxqe.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwoochx.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkehvan.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2woyvppam.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyddnfl.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2zwerbmgh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2whojqkqh.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ohodrach.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nigthetw.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bfepjcar.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2thwspgtq.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onpafvlg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjakxacw.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wygbilmi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpwpoed.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2geuwzyqo.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2olcsaoki.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvkodud.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2cgelzgxh.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfftbkls.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wffsgovq.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkdvqly.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2mltgdlhd.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvnoygl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nonwcxug.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrbguxk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbhzzhi.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2axoidfpv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsioook.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2tsewscfp.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbqblpq.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ukslbmib.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2irksvrei.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idumlyuj.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbvikwe.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgkexzp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2idnpoajf.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtfjnuc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2viuqorpi.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2busxfzdg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uopxcwlj.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2urhblevb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tixglwyc.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgotlxus.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2lhouykby.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2yqngktxi.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpbjfdo.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhvcdfy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2aehwcazu.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ainamcyy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2glgrgukp.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2hgofgffl.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2delfgqyx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaxwdzd.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2rklcwpvp.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgcvhem.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpytjbtd.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zxiulbcs.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfebljar.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vanokzca.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekajutfc.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2creliprx.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2slqpfrtd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2cufqgvqh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2voxrqfpv.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2mdttjdme.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsbqbsj.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxphpdy.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2nsneqktk.html

[U119] JS：生产构建
来源：http://dali.zhijiandao.cn/Article/details/gt2njtkdoph.html

npx vite build
来源：http://dali.zhijiandao.cn/Article/details/gt2uctmmcnb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfexrqo.html

import.meta.env.VITE_API_URL
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzzjddd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsxxcny.html

统计汇总
来源：http://dali.zhijiandao.cn/Article/details/gt2gviwmvdi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxljqzj.html

按语言统计（条）：
来源：http://dali.zhijiandao.cn/Article/details/gt2pyktxtlv.html


<!-- 参考信息 -->