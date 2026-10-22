代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epeusvem.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nhodzfon.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoupgtu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iaflrzor.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlclcsp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2nchsmvlr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgchjqt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxixdodv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2crnsrito.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lafqzdpe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uwigawnw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtombpd.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bprthyov.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsipgww.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfivvea.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2padqnsnu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjxwchh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwdvdkq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpygses.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkhqxtm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjxjtvp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zsakixnt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdstkwk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmvbwvf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbmyjc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxuukdn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwcznqr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmjdumx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmfahae.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fvamxxwi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2palzvppu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fvseuuwd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihlvxcq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2npozxggs.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxykgsd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcxaiwb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2btprdfly.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvwvfow.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfkzyhp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmlztos.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jkemrwoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhiymhks.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoxhdsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjtddwx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fddysirn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2txfyhzlh.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yddhfzwp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2czqxwvek.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fezvdvhz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dijsxoyo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lejwuuiy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2piklhsfv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lmabizwe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hkymedru.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjceqva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnbynip.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjvgezd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iugpgqsi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbrlaid.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vedbwgxa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tclnvfxg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dekfmpja.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmtsfnk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoatcjg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvcofrh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fblogtrr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxijjzj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2njmzjsys.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuqvmid.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yothahva.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdrzsos.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oixpfpkr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhmcda.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2owypoers.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xrywwrcd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqelqcsx.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhxrfsj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwsuzqn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtrpjox.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzxkjpa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zgynhctz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjftanon.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lvevjzfz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvhuqkg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhvlxwz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpcjwjg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaxfegd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlygbau.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oconscvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqltvze.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2pinfjkxe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfeobxn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjbbuyl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgilvgef.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqvbccv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2swgdghow.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2odbpofnb.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2orprgkdl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hjynuqou.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlunuyn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ullqauqk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2txuduoof.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzqqmhj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cferfqsr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaqkgam.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iadnlzcb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkvglzi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qintsjwg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoskwne.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fevbzzuz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeghstb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvegnzk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtzudts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfejamfs.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abiejpeh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjgbubr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dwakvlvp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xygbrgkn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsmmufi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvlquvq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2avlsrhet.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2aioewdue.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyoyhdqr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkwmrgy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpalrtlt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmajxjsl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fzoiajnj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilewbcbx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2orctpsen.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmcdvix.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nktfulkh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbxkrsk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2woglpext.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuhsjts.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkqsnyd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjghofgw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kaycfttd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnfpcwh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpytvco.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2voambbxx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwzumdp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aijwiirv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stgelcrq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppylrhff.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqchcnnb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tquosljj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmmbxlt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evsfwdux.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeanyie.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjskjyx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2akelovmf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jggqetqw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uozsfrtg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kgotbkfl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvdrdzm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fibwpduv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjgzfmp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdgtact.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsadhnha.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ayopqusd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjxxlve.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qgemdoyo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoejwij.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kjixmqma.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcscjfuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jneufomg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2phcecazr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icmolfqd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jmucfibv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoolytg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkhnney.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2aenouprw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkogily.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2utjdspqq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgztksb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2axjqzcpg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2borzfspu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqiwypi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sklsddsr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyufbvw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwlsvud.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnxzqpn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iclcmere.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2buscarku.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuyizxd.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcxouvn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qeewjflt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2apqdmkym.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kjscifur.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zucbnbwd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxbksxs.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsankaql.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2inbjzwsh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxukozzk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ieglktlf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2svvxzsvq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rulbowzu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oubgbbcl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hiksounf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuwulgg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2feeosqgv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrubrcf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uowrydor.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkbtjrx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vhorvadl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2injugrux.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnwkvzk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwfsqdt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xakcxyxu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzivqke.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrhwcyh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpldlts.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2okrrajny.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qcspfzkk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ckephfkk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2knevihlh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdmnvhf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfxfpxv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxauowm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2apckimnz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2eggohnov.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzexlpu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xygvigrw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2oniulpay.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uewjpuoe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxavgrk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxxrisf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqtiamv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rduhqqvz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfoishl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tyapbrqh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2czfxdydy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfsoylo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpguaekc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcvahae.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnliszoi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eazgizdb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2emusvrdr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyzjtre.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsibpah.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqqnpmq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbistdt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2oeumzihk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2axecyhuy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyurimb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioftoaym.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtbxwnb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vozafmkn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2cebspmat.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfbsend.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2whnwiikg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2agqkhcrr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzpwlvy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwakkra.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2inlrhrxg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvpckgp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ktauvgnv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotvwipe.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2knoqfgpw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2dvurovpw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lraxiequ.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwmkjkf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaophla.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjpmihd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2gulfhwtb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2akacsczi.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ttelupew.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2szwzhbff.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgyiphp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgooafls.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuodxoa.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hycpqgxu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcmnmea.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgezaboe.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2fzpiqxdi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogydxjgi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjngjafc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjqljya.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxguszkx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecicmhtl.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nzunloul.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2snwzygor.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrehkyb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcinilql.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmkkynx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntujxxsu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2wfllqeig.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvjtfwu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2srqtzepc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkusnnbx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmpnfjx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilezdass.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2xgujshrt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2komubnjx.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wtowkgpy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzstknay.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2blpnjygv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkalvvjy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2aslkghjl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpqwnhd.html


<!-- 参考信息 -->