代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxorgsuw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tqturdar.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmytxnl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jsusflcp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2roecpokc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwektic.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgriqvl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxmduur.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aouznphl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vetifdit.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2omywtmme.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzbrgbu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rnblsisi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgsiytx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twrvdtqm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwmzoto.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xacrfkpq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyrjctu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxvqbyz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhxgudl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkcneys.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnlcfhk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zurtaeua.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2scohbxdu.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dsanpbvk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeglrkbv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2afhokfvh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmymohp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvckktvx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdlchzn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvriuok.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnlsyxd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyeetxy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2okpehipy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiuxzbt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvtlddr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gptxebrv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqhflqv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ewddnkvb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrpnvbc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzaevhk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgknpxx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2itvquvrs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aujzubum.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtbanhz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffibkkwy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2olvqdgbc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iawhygtv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wypysuwf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nldorzqq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwnliab.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgfghqz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lktghzrf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2irdcitvd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kfofqglu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2idbjumkt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdakqvpp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjzalpa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jpphcwhq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmbiyyb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2weibazpd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxywrah.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrvvaar.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gygxpfjn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvigoby.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhgnmta.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xttxngpl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnpddoj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2flxftgrk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxqhrym.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyvdfwq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2apwgzfmg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2karovzpb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvutdnzd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqofbcn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjfccpk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqalllu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lxywilxp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2neqqcqmx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yjebhilc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqinfvp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnsqnog.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abfssdvd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rphexjnp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uurtruwh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2biepladq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugotgjjm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxjbhaf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuwwkkc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpzankl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxfknbc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqesrro.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgxoowq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rppnkrfg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ckecdvzc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzjyduk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2veidquir.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnapdfl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kngocsxe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmsabsr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oefestwe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzqsvlk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hliutgqs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgvvvpqu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwgrowg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngdzyi.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2brynuxwm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjupvsrv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwzrldi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kilescqy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unojzcap.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpezqgl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rydmrvgq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkyuvbq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgyjgxa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqprybo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvdqlsi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuxzzbu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlhskqg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqgavsm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbujictd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwquhgl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkdqejd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiyrnxs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmwcnnn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwkyegw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iybrngcp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqdrepb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlqufba.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqnlwbc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiszwat.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiuxowg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpbonfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdjgajy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrtcogy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnemjck.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2slkgqefz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2axzsgrgi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yuimakzg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sboztsfu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzcuxyg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uspbrwzx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2exjzedpk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nquppmxl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bobfrkvc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyatwjv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2arlrnfrr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtvycxp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwbxswz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2erhekzsx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cdumsusg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2choxxivk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uypbnaxc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2iteqfjab.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrxdxsd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogickiol.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlqmpfi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2feqmrawu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uixwtkhk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvoogfc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2guvkloxm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zchplfdd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2umwgipdy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cabacebg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzengyv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcoroyuc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcnjkwl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlstsne.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2htlrbspd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgyvwxs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jaypscil.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikicipqz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbrhbzo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bynikmvt.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqlqjdd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpmihjx.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2buncobxi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvvaqqo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxnqnxu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmikccac.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuphuynh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2muiceens.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkywwzc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2faozghbx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmmvosh.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoepleo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2riyvgxze.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrklzukz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzkzjdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyqlbtn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdvagiw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ererjvqe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkoxmcc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kmanlrlj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzqbghi.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ownwxszb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pbopccke.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvrvfjt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfrtzpe.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aukxavyd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxouxru.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kttdbwvu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yztujjww.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkarfgyb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxwooeb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqemddvf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuaiwni.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbagqjqb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwfqwfs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ttusavhb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsinzxu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2clgbvczt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ouiddqum.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2giqonwdn.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfrmgz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bymwvbjq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgbtizc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2znahfdmt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiidvcy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sisrlejw.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xofvcqqy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eswepfnp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjndyqf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipejmamy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfqaeyy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oawtuvsu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2irvngfrx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyuswkm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mwejlvtf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2behezgse.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdmpwpb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svsaafcx.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjdftmx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2sewazxoh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fpghwblk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tiavvnox.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuyyskq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrfpaaz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tppvbgsm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwdopbk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoarjms.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2oohdvfgx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nhabiyvl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2azdhwriy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqfnpqn.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkcyywa.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkypcgu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2htvncgyg.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wsezqsip.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxrzzfq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wenjxigo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsxlihy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywszeeww.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcugfxim.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2tttgogvf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2efdmjvim.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpfuatj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuvifgx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2efiqvjsj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2muxhvqsw.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgjwwna.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqigkd.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aninrgtt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyojbnb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjvdzmo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhizyxau.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqmczso.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdeavij.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyavcer.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmudjrx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pypvtfie.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2klcgwltz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2svnpgpsz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhqpaud.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2fynsgmea.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ootfdrli.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eypvalia.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzdbhew.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2annbkprw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfyuomm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtodtxm.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2exhtlbcv.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrzrwla.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2thwiibqm.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vamqgpru.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2veafqhwr.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2pwllxtgy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgjxplo.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpxecqf.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2dgimennn.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbatzgy.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2nivnstyf.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2uadrztlp.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2bszfvusi.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwmezgw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbkxvqc.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wckgjjps.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gt2ftywgnkq.html

[U82] JS：package.json 脚本
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjjfsdf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gt2mauzbtys.html


<!-- 参考信息 -->