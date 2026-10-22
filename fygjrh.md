代发 wailian999

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpctgxx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxekakkh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdqsomc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hretzthv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfekxcu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iffiyoxj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmmmrp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbupwtj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjbdxlh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiqifya.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoyqezh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2falxvimz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nklaqlub.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqmbhrb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qckvpfgs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgciiei.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wfumueoo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzzzdfj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtatmnnt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2susrwfbi.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2idsmmffn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vngtmkvt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgefgrc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhczimi.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qazsmidc.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lyobngvs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgshaud.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbohfsm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvncmfmo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyleusr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zadhbiib.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhqdgad.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qokmzdwm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2agitxydj.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaqtxjq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwqthbk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrkgbwl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzsubjbc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbksyqc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooonihkf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjvhlgq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whmrjcuc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2taylfyly.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkhxakm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iogvtueu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdboshi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zhklbwsm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oedzgjgg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceitswkb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclscntm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwexdvck.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuhvqds.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrfujns.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyudcdg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmklksg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpvguny.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pvhupsit.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfrblic.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2golmjbhe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2buvrznuf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2obfuqyjp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uitnpjyy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzhkcnq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwxyzsq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vloweuwx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvccxiro.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzhpctz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2stphjsaw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zafoeqkx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2agmoiiap.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqcukkg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbydlbp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmxyqzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdskudj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsbtjhw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxrqdzp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wblkyclk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kcramjkd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vikngisx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfvfyco.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzhxzon.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgkqdbl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvthxkh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ijipdanv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2acquiimc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aimfbybn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyafwqo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2evtsawov.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wyukrfwi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpxwkls.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjtvcqg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjoleso.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwfzvik.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwsltqx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvhqgdt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2aljgqsoy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kuorxxpf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwleyrvr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmjwfar.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaciugl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smunukbr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzscsnnn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qzniacyd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xufpylhn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeqbyar.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrxydls.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sstclttx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwntffz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvsmqei.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjtdvzk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gemloxrk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cknlemxs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ceitvpsv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrgmrrh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmyvvne.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjxbjue.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2thgdnlqp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2erearpnw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzdbycz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdilgfkq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idvsejmk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eiptspcb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2auryiqpy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpkjkfl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hahjldpn.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mafylenc.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeycicw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxvfvbu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xoljpeul.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wfueavlv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuxorni.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2laurzxtx.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2evklagxe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2waskjrvh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pjazsyua.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvcqaxs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnlpmcs.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hblhtjev.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qgisesto.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdudqxa.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxcasnt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fitmsnfu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgfoihm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfeycvc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhapkib.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvoeflj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tlllheho.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwnvvvu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdfgiun.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2diklywoj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mvslkzya.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfjjhgm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2algtkwjq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2itwowlzq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xkowegdt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ownaztcy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iylkwqju.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xyepxoah.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwpesjh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbmrsou.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkwzipl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuqxmbr.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2giecpvsa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgubxuh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpqcclg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgdwdqx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brnatiie.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvqlrrf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yukhzkhi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvbicfi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pihjedyo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2almvzrzk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2abnptotl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2celjqnrh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxblbso.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwitosi.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rdldjlqb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgcxiwc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbxayyq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgadhnan.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2akdssgvy.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmirjdbf.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgpjmqj.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxmpjxe.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzaxsun.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrxlldx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqnetcq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwxkzdl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlwvshh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2htdktyce.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2zutaxmue.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfarvgq.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzhniwl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxtjasc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyplawu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwniieu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzgkesr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xulqcxmq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfeumgs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2amxypwzq.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuovsdt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipgyhp.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2umoffwtr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhooyxlr.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnxniaa.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnrrofh.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gyetvncb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zweqnkfk.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcoufoc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2eamqkkwd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2skyutzpb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2snlwlmql.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2doxkbwgt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzkrwsg.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpxacck.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fofwkmrf.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlaiznn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzyfjkk.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2muuyembn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhxwxbv.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ediafccz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpcqldk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oodytelq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2iefcmkys.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpxbrfq.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2kvesgmce.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2fmddpili.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2curoeaei.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiixksa.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbxgwxs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdhahhk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdtruso.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2xffofzmv.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2drdoxfmi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxxijlo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxgdbyb.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvjdrzp.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2revgavha.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrbhltx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xslyigaw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvfoxpi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwohupk.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2bloqshno.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ywimsrvk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2ikktchkq.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpqgpss.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2iwghhejr.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdcfjxq.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2youhgfvz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuiauor.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hlycpxlx.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2evxbinrc.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2otawhdqe.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2duixlywx.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovldqwnr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzmrzay.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vwonxsue.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuswxsn.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2armpyxgs.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2echpmpsi.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyjzcwc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2eynrgqvf.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bgratxib.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwekhjz.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqdafmr.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2odjralnn.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrvgciv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjoehxt.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2abbkohgm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcemfpds.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxchwuy.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xsubhutf.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2aziwiyfb.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2prorbsoj.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cphaujvv.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2odmizepd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ortxzggz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2robxkaed.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2erajyczk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2syprutzi.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmgoxms.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2vndjrlbz.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2fcesvibj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tsthotzp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2htjyxedb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyajovf.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umujvnmx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2njirbtuo.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxvinyf.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcaznpz.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsycxqtj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqfurib.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2usvbompb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2skokpdeh.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxjnnel.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdpdphx.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2egnttipt.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2muxzqqen.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2sptqgflw.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpeeqlmp.html


<!-- 参考信息 -->