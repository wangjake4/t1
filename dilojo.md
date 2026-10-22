代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eswstlos.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxqqtng.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2folebwbi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzxtreh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhjfxiy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtrowr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrnsuie.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cizrotuc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2yatowxpf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcqpjga.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnketbnu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wktkyqwa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vldojfss.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lklhztao.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mriauhus.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wrlppocn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjjmrdi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwuadip.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgepdfj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2afuzmhci.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ryubijxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpsemip.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbqmcgi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xralbnjn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwsrgkt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsxshiy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgrpfdv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfzryfx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tndssyni.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2carqbtle.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2meyfuqtx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhqojqc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhdsekk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abgeklgl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsszqcj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvzdcpn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xddcskqi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbpquhg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2echogypi.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jiznbeew.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tljyfshi.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqnabtp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnadmyl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaoffic.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fziwoypd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ivruddzq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkgnyjg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xehmybay.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiquqgtm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhlwvci.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xleefeuk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2erjketpi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sikzorwq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kgesfoac.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ncugoman.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2agrjwdyi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwsrngi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aquwxkeq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgjucig.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mitowcev.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2touykitw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wcecwolx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnqmaqn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwvbdcl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wyovhlxl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2foehqsqw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqepmqn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjflgwxt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbzygcq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mryxeyxm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdvuaxx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kywbhzwc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cshytkvq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2paulvxko.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2quqsgxfp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2smccriym.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbgzhgd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mksgdwfi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yilivhbk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyluvpl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnfyzjn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mykmwmlv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2khprdjur.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ragqlbav.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvykup.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2elcicnbv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvacyan.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pevwctok.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2psmbfdfk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvwnwjk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjsarry.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2itupzbxp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfannxtq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jxhionjo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpoukry.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvmomwe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkrapkz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2camcelij.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vrongdxn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuuvivk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ausdirwb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyreiza.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2quqwlcrg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tqimmfgq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jupxrobe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2amkpwfqw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kergoius.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nelnozjq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tznszamm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwuzmof.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtuvcnk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rduuoone.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqcfzzm.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dznhlhni.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtjeplk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmovoyxo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iudpwdji.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aujlldjv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxjweiv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iosodubo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwnscjq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyomxhfb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bzctscjj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgsgncp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbfyfua.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcscwbg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfyeukns.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfzylep.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlawdtw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2izywyuyd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdckxsmf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jljdxfxk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkoxmwp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iqijzsuv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hknvvomf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzplozke.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjvrvxh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbstkpk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnowink.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrqzypz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbspichs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2compjeqe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkadawc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxwfceak.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qaakehmi.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdqgftw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsspoqq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdtzlmk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2muxopsth.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aikvwjii.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoxscpo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hesyfxkf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2siteworg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoqulsm.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcckpvx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmrdopo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srwflcbr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2roiffegb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlsbobo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgtooil.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oykakein.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xekokrjq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2svmdassc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vycmgyyi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xszetlzu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2famicsso.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kprvxsnf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuvxnzp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwtmdsg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2efcbpedf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gykhujsm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2afpgrgiw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2szobnvws.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rsugnypf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kohxfzyj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gewshico.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqtwgqd.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jximaanf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2amsijwdp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kglfgsdu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2szyoaifs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxrhuzg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2eajihrda.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyjaxzm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xredgmel.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rornxczv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtbozix.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jlslvofo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uuctbayn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eywmzidz.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ykandnco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2blsdjrkz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2htexhkwt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yzseodsd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmbfqal.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfvfcmc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfcghgx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ryouyhxu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxmglno.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuogckh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2naptklhh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmskzmrz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jymcjera.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhzkqkz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdddqfy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsporayn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fcngbxgq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vspyqetj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwbmppl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2snykaftd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rezmdicl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qskjzkgl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvwmllb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2foljvbra.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhluhur.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvefumu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdflnhz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sekrrftf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2nglammxf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmeucfu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaomojd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbacame.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlouscj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfimfree.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qfolsitj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2irmcsbna.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzvjgem.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2swjxfudm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdiinwa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmwgozy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2abibuyiq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nonuwoaa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2tpramusm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhjmeaw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjyohvv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyaesvt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2thauzshv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2czyalkxt.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvntoxy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwdwayf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewfcax.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2relngqtr.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwamnge.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkfotip.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gujhvfaf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpumqgc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqsedwv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxhqgtv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqfapdp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbormepn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2koieunco.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuicrhb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqzujmi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmzlnld.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aponuwst.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcjhqfb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2singrakj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrmqdug.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbynath.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkonfeh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pohvdbxl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2myqpumrf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2umeervdt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpuabbn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ghedlckj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkztjwk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wsatqxkp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgdegkq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtxeykq.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fngpyofn.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2onoencon.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpialbg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkaxkkj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqpusxj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpuumsy.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2smmnueub.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxahyrjk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2votgpuse.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2woccnaya.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcspquo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kakvtdwo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsirige.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2adbcuxyu.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkwxpyg.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2foqrfybu.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qiunuxyf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uohdveiz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwctmcdk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmnnhkd.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qdglnhgr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2nffkmnqs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyyahwt.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rubnball.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxyqeci.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzbmjil.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiybagbp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwflpybi.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjobjtgo.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtpyjpx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoarkbo.html


<!-- 参考信息 -->