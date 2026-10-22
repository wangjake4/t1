代发 wailian999

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxraogz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dalrkjvn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dswgbkbf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfvyprx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2juezcngv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2txartote.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhiijfo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2csuezsnf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyduypo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvrgwnd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhsgrld.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsqcscb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdqrnsx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbwosrj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lixsnnze.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wimtwzex.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2viwdduef.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbphlra.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrpkvos.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ekdcuivf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tblafovu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnpzwhx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dsewnakj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2khhxzdtr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsaxtru.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2idvjvhqs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiawkyk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgbhodv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lememlyl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdihtfb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2extgribl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgfyczt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqnydrk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpedsest.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pzndxsio.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkdmesg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgoxzci.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvnfwlp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpfdpoj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gevxzegv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrmouxy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ieckdrok.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvgaxrr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgeypsx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jryxjcyw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdgcerc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfoclbb.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxjfmie.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhkmemo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ameglkrl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2awikzjqt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmvprin.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2weddrlwm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfshpui.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkihwtmi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bykgxqvk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2orhpokgb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ygruefbj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2reqtvtvi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xjumfwoc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxpaley.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqidhedq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hansefrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdjwggf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2putugxzr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfmfpon.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2irqugqij.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiygbzi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdghrjt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2btdpyjzc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ysermdzy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkxsgbf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2firizrhy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dclmpqlb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xscfxwzb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2epiytgze.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vimaxiwc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjlhkuo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2avwrbqam.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2evpgwrjy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzdnzcp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbemyoc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oufwucjl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2okmbkvzz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvmykke.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjccswxz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmsiswy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2owiypryc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2idyovaic.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtcceto.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkouprf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qczefblg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tngiofzc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2riliahzt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpwgkpi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzfraqq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eqalozdz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2twuzfccu.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdhjtra.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfdrkuh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2twjsfcey.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2okjwnwoz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dogrehlg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqcsqgf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbxvlfq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xdacqjgj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2syrjdnvi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuqczka.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdongte.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oznloxht.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imrvavyc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiimqbf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2trvwhesb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcflpmis.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kawojqtv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ughzwqmk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtrnfvu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iygfpefb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwsutfx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsyculs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzqzjdl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2olfigllm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkkghlj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkrxxrv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ugwuvycc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rexgfihi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvygklw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqgmdfp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2shkmfbqk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yeilrchp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nrntqrmw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wobsqoot.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfczgajs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qilxkarb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyywyay.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvzqbbs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uealnsrn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2psvgxpst.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lsuuswvd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyzydkj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sivmccct.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzozsdnx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnabdkp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyfhtsc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2odprrrbk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2aizzpryv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ljifpvys.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsfitza.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyyhjqr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qebhwwct.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkozqjii.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrdngdq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rozjafqt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbhbbjr.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngioennj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhutbur.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2duaghecn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zyguielk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyrqtce.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtesaph.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjolrtq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2lizndpba.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2sspecqjf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfxbjlm.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvnntzt.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmkrggq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrejiupi.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbaemekh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2czgesbve.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hunxxuln.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmdbbzs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2abkphzka.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhyyinue.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzpykkqk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqozsijl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwqlpo.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwfjtxh.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2aacaooae.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2oexwqjrk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mypcfsqv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xqojdcwo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdkqsbi.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wpanvvzq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeinmxs.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cthbuxxf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwktmbja.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2popypxjy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dcllrhcc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2hghkxgak.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2fylxpguq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqicsee.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2miypdomx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtirnrb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csoeiiam.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ueacbwli.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzqcdjs.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2enwnnsoq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcywdtc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ghywtwbv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2vfinfaug.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uupxtqjf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzqllii.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2txtgmgqb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmmxzst.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2puszyugz.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbejokg.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtujvxj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohanrrhd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2idxfmysd.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjswqjsq.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fewrtinv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2chukacav.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tceitlua.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2uupobihg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyvdspp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtggjqyf.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zctuohaf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqlrtnj.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnsltsk.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvrradz.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2rflmpjku.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2kcirxzoh.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2rznrfkpp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlirfwk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrfgvko.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoivrlp.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2vsntlgxb.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcaymoj.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwnppjh.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgsejpz.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2taujaitk.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2ereqyswk.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwwoylk.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gt2whjzdwuz.html

[U86] JS：空值合并
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpkjylj.html

a ?? b
来源：http://dali.zhijiandao.cn/Article/details/gt2wxybsrnk.html

[U87] JS：解构默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2imdzkpud.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhvkqrc.html

[U88] JS：对象展开合并
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnkpsbr.html

{ ...a, ...b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvcxpis.html

[U89] JS：数组去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nwttsoqk.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2oigrqyfu.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqauvlx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkquymv.html

[U91] JS：对象键值遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwvrfj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhijiandao.cn/Article/details/gt2njdjzswt.html

[U92] JS：深拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2youlyewm.html

structuredClone(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2usysxgbj.html

[U93] JS：模板字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfvxasc.html

`共 ${n} 条`
来源：http://dali.zhijiandao.cn/Article/details/gt2wkczjvmg.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxtjmnz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2aajmuban.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrxrscc.html

new Promise((resolve, reject) => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlilmvv.html

[U96] JS：async/await 与异常
来源：http://dali.zhijiandao.cn/Article/details/gt2inganpof.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxcxcnr.html

[U97] JS：并发请求
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqmqnvi.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2skibobjj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2bswcbyxa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhijiandao.cn/Article/details/gt2umorfllu.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtywumg.html

el.addEventListener("click", e => {})
来源：http://dali.zhijiandao.cn/Article/details/gt2lkexuxlg.html

[U100] JS：DOM 查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnkytqg.html

document.querySelector(".item")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmkpucd.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpwquyz.html

el.classList.toggle("active")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpdywnk.html

[U102] JS：本地存储
来源：http://dali.zhijiandao.cn/Article/details/gt2vebhxblu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwtugck.html

[U103] JS：定时器
来源：http://dali.zhijiandao.cn/Article/details/gt2lojndizo.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2futnhywl.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxvxgxs.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rtottxtp.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnrlrdx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjwynix.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpyumlh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gt2kremmuln.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpqbcen.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhijiandao.cn/Article/details/gt2wubnzvtu.html

[U108] JS：随机整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxfmlzr.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gt2chucjtad.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fiurewzp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gt2iesqazya.html

[U110] JS：数组分块
来源：http://dali.zhijiandao.cn/Article/details/gt2wflokrxw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhijiandao.cn/Article/details/gt2xufsnemw.html

[U111] JS：对象转 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ppifxnfc.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxewraop.html

[U112] JS：字符串补位
来源：http://dali.zhijiandao.cn/Article/details/gt2jfamnjiv.html

"7".padStart(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gt2xtybcqfj.html

[U113] JS：正则替换全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuncxyv.html

s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbumqdes.html

[U114] JS：JSON 深比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jmooymmx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftidtvwf.html

[U115] JS：生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2kaggffsy.html

crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaicghx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqohuazf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzqbvjf.html

[U117] JS：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfxrfop.html

npm i -D vitest;  npx vitest
来源：http://dali.zhijiandao.cn/Article/details/gt2awksxjkt.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwbicrq.html

npm i -D vite;  npx vite
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzteher.html


<!-- 参考信息 -->