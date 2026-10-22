代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbxbenw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfwgzrn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwdppxi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfobsyo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtiupngj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zchnwzrx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2djygvknp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2drxbyppe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qogsbroa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsasqwm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrjzyew.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2radbdxgx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2aroozcjp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhwiikz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrewnyw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcorcil.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aljvjbzv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbewwid.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdjlqcf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfeixnyh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2atcquyuc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzwsbxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skmwimyo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rokqmnxe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cemqenwo.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkloxwwv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2syumkmna.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2crcghrfv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyejuhrj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhrnubu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kgemhwna.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaugdeg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhguniy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtkynrh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2acbhrwcb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnrntoq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bekwsfta.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iavclmqs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpzosst.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzgcugk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvepfczu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzckoom.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqytpzg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhvzwfm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkogdjuv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oiakzrli.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzqmynq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsmselc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqirvqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfibekt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwolunbe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llejnhmw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lxboflvf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mamicpnj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xykcokkt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uwufctix.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dxargung.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaxrjuo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tsldfmmv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2afxgonbj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cmdszovj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvctqyk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxuhlmr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nadyaill.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdhpoph.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nijvfown.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrvfjfk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkygdski.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skcrgmmm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jorplche.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aelsojde.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lscqdbdj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sqevuonw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpssedf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cyujumck.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qucrczio.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfguucz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxnugjt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ozblgoes.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpyzpgkj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkiwpsi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxelunv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amhzmspc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfckspqp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkprghc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkaokak.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmbzbkm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2afobztiz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ttioowsp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtnpzlj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwhfxzy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqkdcqk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kodkvqyi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2syojjcgn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrcaiyb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnlgkwg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgfspgk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkswacx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ltuwewdi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqjfana.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgdbqsh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsbkone.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbzihxq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyxsljw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2peniexow.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnswuze.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mppvoulm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tclcwfpv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2doybvfhg.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvpaifx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iysyvgbt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkabuueh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2entcdymk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvlpqsw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvcflrk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vahlmvex.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iprvwcgl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lauxcdpo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sljayzyw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfgoylh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzotfrw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sevsljps.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uafeciiz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gndbcibx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2puqzmzxk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lypafhup.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jugksfgy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zgochxtp.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjjlgom.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmlnqcm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeihuco.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aubzovvr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lawklelh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmqwdis.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iodfiaap.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fariqjbq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2enzmnbkx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fumckbqa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2litpzrdp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wettkrdh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2slyrwqge.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnekndj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hakxkgdd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebgwpixk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiamwqp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2milpagwg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgaxxnc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpjrftw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnfbfgy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkrbuwe.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvhuqvj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhszugc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvzrimy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avizqczx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkosmpq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sosrizaj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cervaiky.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgvjwyn.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmglczp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2whpdypir.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdpssse.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgicxrg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtyqxlo.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmxxcub.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvydfrpy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjqdeml.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bajzmkdd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfbhkuo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mncxsdhs.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gejoqpsw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrhsoyp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2meycrsvg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwhkjwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faoiozuw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qybstzyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnzwqoig.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqvowoa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uszwbole.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pjflwzhu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2naakmbap.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hybcozlv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wtehaokw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2cynxleuu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfbuvtw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdlzgcd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsdspzo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jamlrpgj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjhohgy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoggzmg.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2utvzwozv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnjdjxz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlvvcih.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qliktxig.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmuumhe.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoowgcu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2afpqckjv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oadwzqwg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imfhdnnf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdmxyeo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsndkehp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2glfoonmr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uotvnxqz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnpwjts.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtshtgdt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pfioaxjb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vebxdrhs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bouxcsvt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qreqippe.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iboralzc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mossjrly.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmnrrsc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvqnahg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xsknjvkb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pygsgois.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2stilprdf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2okjteyie.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmruyhl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlzjyfl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2btehflhf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvzsoqu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzqvyff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bobgclds.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmndkza.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbtfngv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zjefjaiw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hidyczvn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jzakncsa.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmswdeho.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdzczaq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvdusuj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbrkmny.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ahjmlbtw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmpuvzk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2totpfjkf.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzjguhh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnhfzcr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2skopahsw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwuaplj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhykkdc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2twpdluwd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlkbeik.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wyisuvor.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rxafnirw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2phydvgtt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmpelil.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwixzfgu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyrnnjo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnstphdh.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2noivntul.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqpcmia.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zoywifvu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uaixdyvy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2btcuoarl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgstgoze.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fyweeoax.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdgmwmh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpeotlp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rsahfmnx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xmneyjky.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2soszaeuu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2reazbovv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfklhqt.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrozwqm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pimmvaai.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2scwbielp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skgyatte.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gscysamz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2plsfefuv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ralpglyy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvcgube.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qasiqnfw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2streeagp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvpabae.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfcdedl.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjwlfyh.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wpivebnh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vtooacvz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlssezl.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkegbrrl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzorkeqm.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpkrfuf.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2unrngdih.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmiaqjs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tntmulzv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mipwuycg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhsatcw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbysjzhq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfunucr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrzoywn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuuykit.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuwivvc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvhdwhf.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfurjds.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2grornfzv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2lryeassl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgejtqrk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vhphxswd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2frftyghk.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ujblutvn.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjoxxtt.html


<!-- 参考信息 -->