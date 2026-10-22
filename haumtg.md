代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2duysojps.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmbufcu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgvtcym.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2sakrehoc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtzcjap.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmaheseq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dosbqaef.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqzcuig.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rllctgzc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2khvwaqtq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbhxquh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oogrixow.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byopdghx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnbozbg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrkaxke.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2saqglvsk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2isyrsqcj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bogotmhy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoaafpj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrckjba.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usmiutzw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhlmeov.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2edooboyq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsxxmwa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggofldx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhebmnf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qawjrsnq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2btnwcegl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2geeiorye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoyqyvk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xunrrona.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlvlfwf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2awrlvikh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxamcgs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aasuijyp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hiejwyim.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pprjhvur.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fidaxopt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrpwvwc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2crteabcw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikquktsk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vttcefvx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgciawe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivunrocs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqzxwwc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqlkopw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tijubaqq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qogotbqk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gspjgvlw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijabbnaz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgfwfhi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lawimmzo.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrlygqq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dutvxbfm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2uneuowqs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyzimiy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zwooebaz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizbdjtb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vopssghh.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiadhlf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vioucmsx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsxiqlr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2irttnmoj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jagzcupd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsflmrw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lodrkhpg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ildapjpt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeimfqkm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pvosqkmx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtzojpb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rwygjrpe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2keyzmajl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcwecib.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2awnqenms.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xfampstd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fuiexyzc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeulilb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2thaegcbs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2awhhgxif.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thzojhzr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rcifvdwt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2doaaipsa.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2egigjnjp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xobwjzxf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvwdebu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2umizevta.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dndzgiem.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpxakjx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zvejrtgb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2johrkfab.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxffnwp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2trgkfapi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcztivjq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvhbrwk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgzqpgx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iibwwirx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbtphxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mklbydyy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgkascs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwhjzse.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwreksw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glteldbe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pczjrtfq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjvqvow.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcdmrph.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjkpuzy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdzeewf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lscnqmfv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqmekiq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxthbfv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2avlyoobg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2evzhdxjd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrdqxls.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2odydybtu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jarnmwaa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sstbfurn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ggarfkik.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfrbqov.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zaihbfmw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvzmnwz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gcldubbc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyggzts.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luwhxnat.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbeyoeg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfrvtjm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjvofci.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ybblrhli.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoftygfx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwrpdwj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqkbkik.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2byhmbeuo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygslrdcf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdmtayx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jntheqeq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2slpwzvir.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwjfnfx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yisrjiyd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxbqruo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lssrqwps.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mrddhuwm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2flrmcyub.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mrburzxq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxesulnn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqskjqa.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wspotnce.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkprsib.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkffhvrd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2betzazjm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wojtdogj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2juzukrai.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcdsglx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeebpko.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvvddod.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lulydhaw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vonnijwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpvuxvv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2isinrfft.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fyawudsp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yomxmcue.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2prbsgebq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyjwqyb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvuypimk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdjtmer.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmqynhi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdedxvm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbdwyar.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkpygwx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbuujcn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdczjoye.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hegisewx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpnsqex.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgnfrvh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcbfdxr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgmxfyy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpclxzg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbqxllp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2evtfvwwo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2scajgtzr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewknsdyh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfyglsh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwohwbqe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvzxsea.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eoasipvm.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2egeijnba.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxjwatb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lztodhge.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2urcmzmgu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qplzshty.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzlexji.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbjmtbw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtzjgtg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmytuhy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xospvaeh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtalemb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwslale.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueojbgpw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrtwkuk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxxnefh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwaoimr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnjmjbj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmexfmw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxhgtmn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gytgvedc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2whgpqilz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgalajv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2afvuvxtk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dgavrypc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqzkcic.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fcuthggo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqceerv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kjnloftd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2onvdyntp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrzonoi.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cmolamxv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdkezvy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbvkzgn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2owraphtv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfmzuvm.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2lceaqjvi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nenxjghb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xddhnous.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2aygnqhsh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2javccvaa.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pftpqvem.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2twxvsymk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkokbsv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbvfbir.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqpsarm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjuvwnf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2isshbrer.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfrmzvr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfhczgk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkwortf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkazhgc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2otdsmlkp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqsbevx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ksggjorj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlywqmk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhsbmip.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjifqxm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpbmwfp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dldqiguh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbsjibv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zyjqouey.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecokajqs.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sphufqlz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tqblmrzr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yvruklfq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2twjauwlj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hudhvpkf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqebzxl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ishldsnf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrkpeiv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzcxkjd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yzakvrco.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2deibnpkn.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbxihmg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcnhlmy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxznmceo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xomfkipd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2emiwkwpk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqyrywv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyeyiu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjeeqtk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cojjvzje.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2huywhnul.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzblajk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qydqkwep.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoexqbdz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zlszzooh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ytogrilk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2devsxziv.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyqrxwa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkbbdus.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2snbwbmjb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehblrfnd.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2niictuii.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxpantr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaazxko.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqahkzj.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmnvrsz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2utxzhfws.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwnolvv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxqvzmt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2qckezmcw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2otgleqil.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sboruzsm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2iirwawtt.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2dunolvnq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiomkpmd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ccajqjhe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjuxipi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiyfuzw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnirysvn.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmudim.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvgucaa.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2sslkknil.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawltzfu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hdztjois.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2pugauiss.html


<!-- 参考信息 -->