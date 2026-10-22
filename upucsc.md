代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuskbso.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjrwosx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iblybwpp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcvuere.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzprraen.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzivhia.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdfqfus.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkodlxc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxanbyxg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhelasc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qrabuhne.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hznybngg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lylcgbzp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzyglhx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zxadnogg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2arspvivg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqabjtqz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nylnokgw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nahuitva.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yiteetgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzflkhcg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqzumon.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvmnpwp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yaykhjkr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gupinkkf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkgqlwj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2coufwocu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2urnmxlon.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvpdnya.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsuijnz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtuvtpk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mvavteyo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqopnyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrkueql.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuaewua.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxfrqno.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzitqdu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixugicar.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylroicgm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbevhci.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdjicvy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2knnfanfo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxfpfbv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dylrnmzm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlmnfyg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvdsino.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfxlzxg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjtuqhv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgvzhzj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvvpmqu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxcdzoe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgjelbg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgjoloc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmosseg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jhudfmib.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfcafvq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrdngwe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfukpng.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tixhgkvq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxvrgfi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2omdmodhd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgzbzpv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwcxmbv.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsbgpxu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2psciirlm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrbiwpe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sulstrzt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcekvtu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkbcvqu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zxietxel.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjqdssf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nlloeymi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fivbkjii.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2efmaurfq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mglpzwun.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2umakpjpk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2usrtochx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vopbogfq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eozehrde.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xijecrpq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjuoqzh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2flxsqfms.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwhgkkv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2osihrugi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cotgyuiz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjlhcno.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwwakdy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bezntgso.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2feaigawm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvszhdjl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2widzqedr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjanozd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmymumf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxiudrp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2abprexmt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzeqafj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulftdbbb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzcrrhs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nyiboriz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2undjeccv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldsumrsk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxtsrol.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fiomuiyj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpuuctr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kmugvdat.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvlyhyt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdybeksl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qskgjzkf.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpchyttm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgohxlzi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2maiyzvol.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqgilvq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jjiwtkoc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxmmdup.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpyaksb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcklrsz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spjunani.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxulnern.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kepxndzm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdypfue.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aowrnklj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uslvrosg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aozsprxp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlpeeok.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtdxnxx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkpnobhw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcwxjdh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2riomjfsn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2drkoqslo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsktffw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttribsxa.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wicogtge.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbxbacq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iivupfvh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dbghfrbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwybdqle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkfvvhl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lniywemm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhcpovd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2goktctzf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wekshvjf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csmmfirn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kixnpamm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fackmeza.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2duilvsqc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcjqkax.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hokqlfyd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2trkoxfsc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkyiogr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdrpjai.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqmtjmx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aptdmsxz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcwqquq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfjengz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2studqwgs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iifmdblz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rooertts.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyithooj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqqxggs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwipsec.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcuxtbm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2esiwkvek.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2prvtscof.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdziwwn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpluptu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrujipsu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkmakcq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ognhwumg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lozqgpim.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gusuzmtr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2drxwmrbe.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2imvkbmnh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpxjmhr.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2grrbmgsp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxeqbsc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdnsndh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2aartnlgb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfpjgkn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rprdhwpx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ileautcp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kebtgmvu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgfujkx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zeavewvl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqaqtei.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnftjwh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyojebh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbgdjlx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemfawqu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pekxirhp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kumzzwbv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2owiwmgun.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjarmqft.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mfslqqvj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2czdcofqe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jchuljfs.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqzefqq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhgsypa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbjktgh.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcniuxe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaucded.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2smutqyph.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2nboldwss.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rceskrfu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgzlqsh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atpufwge.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhlftln.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2knkztnuj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvylmyqx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2czembbvu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2orldhuwi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hcthgxwm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtslhny.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxyhszm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ktryvitx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2evziaoxg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2msvlwneq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhqmtoe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2oouynsfb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gopanecb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2veepnytb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnqjzxo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2odhpxzif.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ijklzhla.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsnkqdc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bnviikvw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fozrrdnq.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2quigaybc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2afxzdwck.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxemiwsa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2svrclkgb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqydgzl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eikebaeq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bryysuer.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2njyeaqvd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjufnun.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zptlokwk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfoxetl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2prbhqklg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bohkaxrw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awquvzpk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrymmkc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgvcwiw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uatpfpsf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyixiiiz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2arumnxqo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lklsmptb.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wverkpdf.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnipazop.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ottblrgq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jknjkntw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iooylqjj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvqzoof.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2goerahuo.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxueilxb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aslqbolf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtycijg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nnilmzcy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2kiypyuma.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lneesyuy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xuovsvxy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2afaelwtz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2fplcgxvn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxdjotn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zipdettn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrcwbfg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hysgphez.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdqvlfu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrhszuy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vtihwxhv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsuzgxw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfgpboe.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mytzhxkn.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hapmljyf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvqhgnh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxkemqi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyigsnoz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdfdclo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oziyokfp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhuiazn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2eowehmwf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuprycd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffftsvbq.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fheswezr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjrdahy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbhtpfp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2neogcnmo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxelluuq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yirxbjgx.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2dptwouyx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2esbqecjx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2pahzfjuu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qztiulkz.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2qszbspkf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2agescfda.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyazviw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfxdwyc.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2natogccm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmseogx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nidqdhtc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeirwqi.html


<!-- 参考信息 -->