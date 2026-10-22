代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wguqixao.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2inxtkexo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zcboiphd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hldpfrao.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfomzla.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzqdezd.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2svvgzyxj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpqkgrc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zkazdpne.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tckchzhs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhegnsz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2eutjpwsc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2djhrzbyk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwcvhkz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfcoofq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpordwnk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sossmbgf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgofacvt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wadasakj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgfcrgb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdjibse.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysudgsrg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dytmkeri.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adubelnp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnipfsd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mjinpiov.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2undpepjz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spiylyst.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fifpaquy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dixgexka.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mibbryxz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgekcxsr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfomhit.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yodzcwrv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzjzwrw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkeqrwa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxugmwd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jueyaotx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjmualb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gocdvzga.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtrmlwo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcsbsdo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrthxdrl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzndyqs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2muakdpxa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eevzszmz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2feprjxjl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wpvombzo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrosprms.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2myreedkk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpldahdi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xrprsgwz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcsupdm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdwukrl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2seamodaj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2apldclma.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwzqbrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvxnsah.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnjhzmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvmmrtv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uncjpbzg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bucrcipl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcytibq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kuytiohj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ryksludb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgotegd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2juinbhxt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fnririst.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaqphbo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmuxwnx.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrrxreb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xljsmerb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ritxjylw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxycvjhn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvqhmrg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrpxynt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owhtotvm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwtnvbf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2flcyorkg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzunpzs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcdjkwg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2awruiosy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dkojyemo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgqbxne.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2avbuxyko.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqqdvwe.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjhyctg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxgtnmh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmofvec.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nijxkhmu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqowtpk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wexwmsxa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bydwhxny.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xzyryopd.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhnpvxu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkoklbv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vctvzvld.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eygsgcne.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hkridrqw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiwwxuy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xsusmkhp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qentgszw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyoevev.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfevxjpg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhszkcf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbmlcfd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxwbebw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2glnvlgnx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ieygjpla.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzbwbuf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2prcjszna.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxpllfz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faznnzmy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gihaeoao.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsqtluj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyvhslx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hewjhcnd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyfdbxc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nabfdsau.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjekensh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfnmxal.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbybntl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmikifs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2usuywxkx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2anjbnfkc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxmxpsa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2twvmmqoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqsuyafq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwnaftd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzdbbsb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdagxtih.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2atqqviph.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfrvwtn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtqdnjq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2grhefphy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2leygxhiq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dsukextk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdiymyp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ciztxuaa.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbdozdn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgbpjiu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2muajzgdw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhjfhmm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnrrrgiw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yrimigox.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mgitxgbp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2febfaomn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbpaotr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ridjgzyz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daieddpr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrkfnoz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcvhnlk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tyykfczb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvrojce.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxoqohj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnswurec.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyblwan.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsqnrtj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqjnanm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsodqtrn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnwjksn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhkipyo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbvmeoa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcleieu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uteidkqr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrqbkmk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hebclrua.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2czyemcoz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzllffj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjvhfgd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2onvomnzk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqmwblb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhqejrf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2djfytgzs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qafnsoex.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmbtnoz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtrggcj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ixffouji.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjpgxun.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgzndvt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqwwrzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgxlwta.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbznommv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyquagv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtetqon.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ejozbnyo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbfkvib.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obptqjqj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zweijmlx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqayzvls.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlsjbjq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpzilwg.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkasfwg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxreoch.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmhyipb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqoatpf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcyqxik.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzexqdn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrfrbbn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrvhaha.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgvfdxm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfsoxaxk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkyrmty.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qxftomcg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjptktt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzeymjbp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2byboroek.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydryauvk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pryqbxlv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qouaxpqy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxmjqzk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ervlnbfg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mburaeis.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2euflifdv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwzdpvz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqvubns.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sirtcyym.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahguboho.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwhcclg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uamesbhp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkxyubr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qqaynffb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2shxhzuul.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysupmls.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pximaufc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2enrbsxsw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzbnxus.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyrsvuq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fidcftat.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbfqdgc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqavhjk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2srrjwdzh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsteqri.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiasxmha.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2snduahow.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkdbpbw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvnukng.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lknoqgds.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbmpxls.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jntaxjbs.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxbjwki.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2msvlrsod.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjxhrdh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuvgkvk.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrbnehn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dndmgkts.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qadvolzc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsbuggt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2grhoualr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkcznnsg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rordifqq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekdmnwt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnnnynb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjzdtkz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqesrzm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyttdoiq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgkjfrk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eafmctlz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bqtlfhiw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kobxusgc.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2emihcowz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2avsqvpwb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ziovajlb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2znjujmrl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pyorbmtf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kecasnjn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ippzdwtk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpfdkcy.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qcctfena.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmpdftm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgtjbub.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mybycpyp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2btwspwsp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqrjxrw.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsqtcpp.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbswvmj.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gkalsqit.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lkikkrze.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yublziay.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkwqyen.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2czhecuue.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qinxhnyd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fecaqbsv.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjpbkqo.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxdrqsa.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlybshrg.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2megwpgrn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2nthrwdjs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqedzmp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxvrsis.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2napmlgkx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2nejkxbkm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uezloycm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2uxquishk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdkmyhn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lennalrr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cicdtryu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmchnhm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xksfkcqm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vntkexln.html


<!-- 参考信息 -->