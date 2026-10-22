代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhfgjyh.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhwedzw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2aiebdxoj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oanxorql.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyaetzi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgreciby.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxenxrdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smdmfmee.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2llrjxjmu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnlaioq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wttvjxeu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zwznuyvy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmvfors.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrujiuk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrtbrbb.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2attiofkv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdevtlzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmacyibr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkheewu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqovykw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxchwoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfjwuby.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hghbsrln.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjlyci.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvetmbb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lodafmvd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiduqun.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfzhwgx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzjwijy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiritvh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjrohbp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmjhxkf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdjadfu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvoscux.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxjpxkf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhgbkcc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aqefhfqm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqpxpbc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mehnypzg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2prhgrzqz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2icwlccwy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxchcjjx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jclekokf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jantjook.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ababgqaf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbgzvpr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhwxjib.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwhblbz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhgvxbv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlorzzhp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2thdbbghm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlggqfc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgriazx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmogjvf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bilmddxg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaburowr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2brrlkwyj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgovhcg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iouqypre.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ignmlnju.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lnatixlo.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifqxvpl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2plikkpro.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnmgeib.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oqafcvdk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdoxjpb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbzqmyy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiugmsy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzakdpd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyauutty.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huuixsvn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2znahhwnx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfnnlvee.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlyfxqj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqwnrks.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bohiwjhn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdcmwkc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvrxpxo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhssjbt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2glpenecy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aetrjmkg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmyizop.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbybiwdk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eyophbpy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xbssroho.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhnknrt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyncarj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lthxbbhh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stpgbdnw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoyqczb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgnrpkfq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uprerojc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmqoxxj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hotevtqk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvixivjw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slnlmfxg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgszbus.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmixevtl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2izndhvbf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evdivlwt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhdibkw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tphygauc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tkobotoi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmbkhcs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sclwgnqj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duzniekf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqzuqba.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpyqtct.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jelwmgtn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmaabbwe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmblszu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnibpqf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqupupud.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rwprlsbg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2canmlulg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxksfbi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvlmrqs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxsgmgm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryusgnh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yflhkdwj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyauwrat.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpyshhw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tknrsayr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jebauvjj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjazxsn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uewrjgnu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2funywcod.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvgvivq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdfllew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcglrsm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbuxdsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhupofnv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fenxfqgr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwzyqoo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwdftdy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lojgvbel.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xlycpqae.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvltwmp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aziikydh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkvfwew.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhzdiky.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlpvkgc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2obsrjylj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgnlscy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwfpnwf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyinnmq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuiexdn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpslgqu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kowycpea.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2srfbgjbq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ypticrfs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qysqqplk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqjilca.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqabela.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlfkmbx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgekvrez.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2whhqmill.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmswenlw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jjihaskf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhklfnkt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2emqlogaq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxmsaht.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2whijcadl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jausqcwu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2osuuvqke.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtfsgrh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2slokyjuk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyevjkkl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2czskftyk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrxfgwd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrgeznd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbeavupn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qshrjnmf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fbplssdg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjhuvzp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdevkyv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zuccqhzs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dmondqff.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkvtegq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmdgvhe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zwckmusl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsilltvb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaojsdv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmyaqma.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cowmzkpc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vykaavqg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwpbpmb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2aoherwjv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjjqayv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdxvpxd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2grfeixoz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzklusoi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfbectj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfuaxoe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyigcfg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lmojgxwe.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhjvibl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgrmzbj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tybgxovp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcneouw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2biaefpgf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoofdbj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpcuprv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsjcpoj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2elhvdikv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfjryto.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gohokifo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwcuuwe.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnfeggx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jykksxud.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sbukcyqs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsfcdbj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2emcccgfw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsaxqtb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uewztbsh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcudjubz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqykdtf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvrxwis.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pouoomkd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jebmmyou.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njzvdmlm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxujjpvm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjoqmto.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2remqjzdi.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrhmrsv.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzraxgk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nggprxcy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaomazi.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsjqxja.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2chirhxoc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqtesoh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2piegsuxt.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wucwhkqc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlinqfqs.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrhkbra.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbspxvkv.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzubwci.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqsgsjb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2chijxqaf.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2woslldiy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2umjgydks.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2mimtxymz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxsmmez.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bszopbzz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmydgbmr.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rngxjojf.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoisqva.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2oquxqmdx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2niuchxqi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nerecrig.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ehpvsvrb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjpeire.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgrfxgx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wopzpsvy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2twmoenbl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2bcofdrcn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxachfy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrltiwb.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hngmpzvw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqklocl.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxrinlx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpohets.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2felbsvsx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcshddz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2vonfheda.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdoefwp.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2funrhpys.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvtxjtb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fxreebjs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uibjiuae.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuusvgal.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybhlyhue.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbldmrs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvuxtpl.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lxurfroi.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2soupxkfz.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdhekbq.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrymbwb.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuklzit.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2lflsfxry.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2fydkyzhi.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhoscad.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsbxron.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsxyugi.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrkyudx.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2nztxnuxn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrvfygx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2zhomazxh.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2btsuhsqa.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjefsvi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2dyegafdh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdhhzir.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2fibsqypd.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2waigfaqg.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2yidapysm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtpgcmq.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wncwecll.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2povaclvy.html

[U84] JS：CommonJS 写法
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyuwwfp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gt2dniwkwtz.html


<!-- 参考信息 -->