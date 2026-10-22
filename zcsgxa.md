代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbnxnie.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwxefkl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyvdjep.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ammgpanm.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsknvnb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoiiftd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxborzeo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wpasggac.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfvqciq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijegkcbc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lcmrvohn.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpsnlbk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hodhaueu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjjdchf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjgxdiz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzjfbgs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmxusmm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjizhuv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdqdfdf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkdmpgx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqxdfnr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zacqtadj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2elhjuyva.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zafgrayq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdueaoy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtepwpq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gurklpbs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oukdpwop.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dztrugba.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2byadivkp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jifeoomz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hecegall.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyohsry.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmzjtlk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtlrlkc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyggrsi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkvyuzi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtdbdde.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uocupvjp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvebdto.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrfaghu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2reglxxhp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvorthz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwnvzbg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvhuxuv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcdbnrc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmonnesj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mnunrylm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2udrztpov.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnrmrxm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdwoabe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bghfofha.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjlzxnb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2stpmjtob.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qegnkjix.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qiidhvja.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pobuapen.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhmhadw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iukmdaet.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfilmdur.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdowmnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2facyhaiy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nopesntk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2blkmeqtw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhsrpnd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dezqryuy.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cerdycrp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmcmhcd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ilxbvkmo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtjgiew.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hsricfkj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lskunsxc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bydvejsi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcumebm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iveldant.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhndpmfy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zokzomdr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjdshui.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2arbplvds.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghotptil.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rneiwfjq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2alkdsuue.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwfycwt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2phiicxrl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcvvfye.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsejiwkz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2psskqgsr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2khmlfomu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpyvgeh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeimmxm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwqprqu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dqlqzzui.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfvalku.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2thpakuoy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2keyiutwj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfcypwx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jinmvvuh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrfxvbp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gecapero.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmokkap.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2geirrjty.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fegnvxyf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sahtjwmb.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjxxtnu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ercmlrvw.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqwrfvs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2brnwvynx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqybvnan.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeoauvz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2outygyhc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khjjxnuh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mguqqhum.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2utqfdtrr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hgafvyjp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bcivrrwv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhdyfto.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkvllvz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjepwsu.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bytbhitd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsekhcm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2otetzuvj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpnpiwv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2teslqlyh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2izhomyyv.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwmewnq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qoewlias.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsaawlz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2imyzvlgq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyxubgu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzvpgco.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmddcmx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2thxtcmbd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjwuasy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xzboogzj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbidphz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmztvush.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbphnwts.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luxfkzod.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxwqsuk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puxswkbd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwytjmg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmnneku.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2evzgqtvb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wynjkskn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfwvrhk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucskijdr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wezcvefe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipndwrjo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quitanyx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oiguotga.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zbomhfin.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jexxcbdu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vddkrkvj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pipbhdsk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qljhhgbk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmcxymv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcelazqz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaxcsyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ompfobjt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhegplng.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpczwur.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjmansy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhgfxr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdrawgd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sobfgtwz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnlrwlh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2plxilbvd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2feqntsbz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rddnrxgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lwepejxe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrbngys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acjqvvbd.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fgloiynx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuupdbh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmouymsw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oztodavt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nfopyhfg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvqazny.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fteudnvl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgpeucz.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2orswamzv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sadmhsqf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ngknbwuo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2syloefoz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mroxtfgn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yelsnuzi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyeohimk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2romkrqhw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2atgzxjry.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wayvekxl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzrcbqa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cknhafvu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2txekulbm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsfkajm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rewwfdof.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2osraljlo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2teuqytxe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvclajwr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2egmkgqeo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvcgotc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hglffzfh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2glozvsep.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpzunly.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkfhhqd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2epproyln.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvndmlew.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpiaqtc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqkijzc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zdagzikk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvunvnf.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sicplfsd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2anxodomf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2erwltrjv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2scoevuwk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvhpxsn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gytavqnw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqbiefe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pzumlely.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzgpajn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlxscdm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2azzyedvv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dihqnkwm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrqwtgf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvqbolk.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdrjijy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlignm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaxhydm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzhibxe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zznytrdc.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmaeskk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fimqeaue.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmuuuai.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhqqqxt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjujjfu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wukshpqb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvrhazw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2avcykfgy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahahfmho.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvodchog.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dugofocu.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2efoeigud.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqnrulr.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgikbwy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2slwvgqhe.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxlohgg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkgelwi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdndkus.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2uufckdrh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2okdlcjnw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzqgvld.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2puworrfa.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbknmaep.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuwswtb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2adzznlek.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2acznganv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2blkxcsqz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2apjcgrka.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdbuikj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdcxzuu.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqblgru.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhffuvn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgjbmhs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rowypyqx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2emoyfnkc.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbjfxep.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zltqiznl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvfubgw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxzccxa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qefrfvaw.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyjtkgh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmkexad.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gltifnuv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ahsgvyjr.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoehvxlw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2odfdqewh.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmoebavh.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2omzjnrwu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfvjgru.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjbpfhz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcqomkq.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzmhnpk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wovgzprx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdlyvci.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fitfmodd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2elqacyts.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apmwuwhh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xykcrxxt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxknhasz.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bihdpqwb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2epsuqsxc.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xxariudx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfzpvcf.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwmtvjj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2srlbrwbh.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2whbtadwf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xspugubk.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvkdmik.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gujtfsdc.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmvpivz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ioigffhw.html


<!-- 参考信息 -->