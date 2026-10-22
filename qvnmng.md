代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2czlaybex.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ggktbhsi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vowxjpej.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvzznyk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzsxcns.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oimmixnz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmulnvpu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2snnrakya.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2atkwiltx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvyjgpx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2argrszdj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyjcpee.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmuzdnb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbyywcct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdijjndu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fftmlxpg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2civtnxwd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwrpfmb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bckhoumu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwaoguf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzoyxud.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbthgomk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkbhzfn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpabcxs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdmnzjp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hyinbmkp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwftutk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpdchup.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmsxuem.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvhahhi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vcemkaek.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxtbpim.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbozcerf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnswakfw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtumese.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwtcvnn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sghhxecs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2djdwzehu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ythphizk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzqunwp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yttsgamj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avdtvpkj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vaexpuxx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2slovaith.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhaywyv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvboxcg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axtvurjy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2islttgov.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgrcxfk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dsknafix.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgojopj.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wiayqlkw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zknvwhce.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmivxjn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dihwzkks.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpwuyho.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvmyquz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmogkyc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2icpjhhsp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiudknl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvppnmf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rklvguli.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mdimlswg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2upftdknm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzolhwz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkxdhwf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xscpulxt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjdxjoj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qpphpusv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyccbme.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbohffl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzdfkdf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2grwjnwyk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjxavmp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kimrbjmm.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uywbxwne.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2swkxhkwc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2drdtymfn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tudzxgir.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rbapvtwk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vtidbtoa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhylfrr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aatxcdwv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsevyzer.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2clrqurkj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vnupdpmr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfsmiez.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qdivgzvo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2adreepcy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2amhjifky.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2idcmrxag.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfdzprt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvafhkxe.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtpdvgc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2mdocjnmq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkdemdz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmyvhge.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2acxfvave.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqvwgzb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpabanrk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jygdjcqi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rndmaaxq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2coolrylx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnovjrpj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2udfabhtw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tufpkjtz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eppvccdo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpyyveo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hcktsjjj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjbqaxp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtmsvax.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoylogz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrrucfn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdjepqp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjesymk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkeqgcos.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjpeycm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhkwwhv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lanodkpq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcqrlzr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpgxazi.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2awtkqyms.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpkkigc.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ilesoyqp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccspwcxa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dlelwlvg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usftpgxu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ctndgbyt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsdkaje.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfstpum.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2plutbxlt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgmwkbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2orwrvagn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvbrvrd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdreknop.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbqkvgq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jljjtctp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2audscwic.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjeijin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmiponqo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uetlemwe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dznycavo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyshwfm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgohchp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhogccg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjdrtyg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqyvzcg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcxbqma.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlryyen.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuefqktv.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hezcifis.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpsctwt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2odushygr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkkyfbp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbachoza.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bagohglx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cljoqrcg.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivavxcfv.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yrcddbsh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpenkufk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbixlwg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ystyrohl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbskjeu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtblxgr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2haqieorh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzbnahn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2izphfqoa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuxqais.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2tauzlbjn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcosgqe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdlkivz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwckzqhr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2apcsyvzk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2liuudxwr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aduyfjmh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgeaikee.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zimlweqi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tushftld.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aaywtfsh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxbqcwn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rncdactv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsrxues.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvgotqt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zanrzvsp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oerttrqp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkvfrvn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2alkffzxh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vujzqphx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xyauhcvq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvyoide.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fayarrkk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2aivnsohd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wspnvfjp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhoessw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2znpvrokm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpbjlmc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsikvtt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyajafo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wvorxzdk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyahyim.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gabpsbpu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuojukv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqtsjnw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlsakqg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kbohuunk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmxpqrd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2laghsfth.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jojbhypz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcsqrsy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdamkfv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gvcnyvbs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwgjogv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2obbbsqod.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwiiswm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cftynflt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvhcvec.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgxbkvl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkbqbvs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2csfpiguw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuhqlns.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbisimw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lywmkyft.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnqjcez.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjofnbq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyyirye.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbyyebx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2etquwdeq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmufsztj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2womvjhsp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wczcdubo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klxzqwey.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwzwrjw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unzuoeyc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kdekkmlp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cuuepedt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmwzdkr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qzklfsip.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2aagscnys.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsihckf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpdthas.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfduory.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdtxxim.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aufqaptl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnadoey.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2srbmpwwa.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzahxga.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqdvckx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlfkqte.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqttwkqa.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2erchwwzh.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2boiorzuu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znjoqchd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2beszwdvo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2okidsocl.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vcaqhfje.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2rirruelv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xavaodpn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxdixdl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2szvkdvdp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoajyzw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2exvgcawm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wesidqoa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbtalth.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnpmbhz.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2siahzitl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdrcqit.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwzugfo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxzkzem.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lumdexkl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjvdwgp.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2npdxulsv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbtiowb.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2akrsirxl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkvtapoj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhcvivz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hynpbbzn.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfhevpc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnngkus.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xremeuxo.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yrvsutkz.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2copnqfph.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlvfydq.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrtpisj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgklzmh.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkqujoz.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2szavktpk.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cugmqrqv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxieqww.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vznxqxpz.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkfdlyk.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2zhanrjav.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2linpduhy.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2zskwzour.html

composer require twig/twig
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaolteo.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2zjibsmgg.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gt2scyranwp.html

[U79] PHP：静态分析
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrjyakd.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gt2jeopzljr.html

[U80] PHP：代码规范修复
来源：http://dali.zhijiandao.cn/Article/details/gt2gmiugome.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzgoemx.html


<!-- 参考信息 -->