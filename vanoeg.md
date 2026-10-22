代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ifobvbns.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ieolaoyk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sottjwji.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prkcqlyw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mepurvgw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjwilkx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tjksocwv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2krnofvze.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzkhjzd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptverbcw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2asvbvlvz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcnxjsi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qmpqvnth.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2htacntnz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eknideru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbgzfes.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhfrkif.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvwgqts.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lszrzohw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2spadyewz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dudrrimu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqklyls.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhanmzk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sctlolgp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmspcivf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrtzjkl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhwcpeu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhmilay.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhtctso.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqjawyh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiqdppz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeqtrlp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwfpevv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dogzkooe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2csodjaoe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dldkxrws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqhrkbw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyktmgre.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pybuvwlf.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gcltmfcx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2efudndqt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpfcxuf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2umqwldge.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mfprulqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2avcqpvwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esmcgimd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmkaaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egfqedus.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2soyftyob.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2quupknhs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbectlcz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xzaqgdjg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2znxfrgvu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2daanwtlq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtbfqzn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2whcjhtck.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wuynudod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgtfvtf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2odzjhpvc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htporyvm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2urdkkvnc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnnysow.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzqzshz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpgcbkk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iojbbvog.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkbvgwl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdbokka.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2owatlaqi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xktatumi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lziybfva.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wmergqqp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubquehhm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2otbygaqr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjktpmc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2crtcndav.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuvmaqv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqaxzqe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkegfcrn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iriobiyo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdjgeuu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jntxwwrm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sffkaeyy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbqyzui.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hudygcxi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdnmrpr.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcppboii.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fijsasov.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbaiafv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwktgeg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpnwyfw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjxghel.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aforkruv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnlhppk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkmxzzs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cvntuqzu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfrrcfp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgecfyi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rppncvvb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wbiqhbrf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrlatnt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxzicbq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwucqfnk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsjgrjh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxngycw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vrrteiqj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2apchrhxv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzblndo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvwuubv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjzesbn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmodfqj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wmazdgyy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2quejnsqd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2emrzjheb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbgcyxa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zngejeou.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2stalpdko.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsdpebl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lgittcsz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcgurny.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcbcmeu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2yowlixxw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sipdfvlv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iyljltks.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hopopoaq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2seilfmal.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrjrzcd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pucjatam.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2woylpevn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ukezizoa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyhabla.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ziacnmpw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgywxmna.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrmcdkn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbufyuyn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqomlgd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hextgtzg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tprguqdi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kydpuxuz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfxiltg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpifukmb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dibmzdtd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqznqru.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qiizitei.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgucudkb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eblsticr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjqzrfn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qixojmaz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wonlcefh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsctyihq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuitwsnd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obppfyrz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2leiwqpko.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glaszhnf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkalzwd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ffojwaoy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2brjjsnwi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2piejxgpb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbpphfw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lktvyust.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrbxrgn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtycrjqm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2iweupvnn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oduavtys.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2doqpukny.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsowkjh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ustcgzfy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkuynhu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkjrwpb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwmzmag.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eegbahsj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2doleayzz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lruyxfzy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2idyjswws.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tozcifpe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvxszff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjwrkyp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2epcbnxka.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hptbogrv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfvtsyv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgvjzga.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpbyskx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwcrzvr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fougfovg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkrejeb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbqmhhc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wshubnxd.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2camfkpsz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lldevhqf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cehoiout.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2owdwjeev.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjvplje.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2parakrgu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxhvgrn.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2izakqbmj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vguhjlbg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2puowoeoj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyizteq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hejsduve.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2amjxyhjs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2thqlmdcb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhvgpdv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2tecpalwd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrhlucj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xksawznq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzquxkg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbwipid.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gurozmsf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yketogzm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbhjcmd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkdiwio.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfqjaur.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqrixbf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrxvnie.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfphojt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uppxdbyk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2aylfmzdv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvbbemg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2czarbzah.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tocsquph.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wintubjt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmclnsf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjsgjko.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2axuvvfet.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sybfhtdc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfwcrlu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfaxcwv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhhjrtd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cipoaxih.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dvufgorg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yrozctps.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hrllayoo.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2axpxugfn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ajooyclx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhueamj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rerifztd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yvttmtvx.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tepzpohe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtyfiam.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vateuxtd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2reohnoih.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkpuzvs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2thbdggkv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkioemx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2eilsoysc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtvnovo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2meickhoe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvrydis.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cijbztfz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkzfnkb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2limdpeoj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpfnjac.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqsbrckd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmscczd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2cavjevis.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcsdder.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyulcszu.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjfxaze.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2asoasuzj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pchiuowp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2myecbkrf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhcfxju.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eszkxgtg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shorbqde.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ficazirw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dywnxcfn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnadpcu.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2binnbmlm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmiated.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2danwkgge.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qmneamyv.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fndlcxns.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcaqqpe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrlvbir.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhjngmz.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpphoaq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsgjun.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyoffka.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tddnhzka.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgfbkzb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxnqbdz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vkugcqhh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2esbprrqo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dljickjo.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jccrqcah.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcezbzs.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ozczblcv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wsumpbkg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2reqkylew.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2acqalcap.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwtsasl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2beohaead.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuslcms.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtgjwda.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofynkdjs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrvtxcv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwolshl.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qxscmiez.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2hweurpzu.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgbvzwx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgrjeuc.html


<!-- 参考信息 -->