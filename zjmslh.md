代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgmmdxh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdxesoc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iixqadll.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imvgaqnp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2njorttyl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbfdtif.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyytune.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkzdzlo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrjifnc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2prnwdrqu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjbkxev.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlidxfe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yredwuph.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyrcafy.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pxipnwbv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2itvutwhu.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iefisqbg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnfikif.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2azhtqexx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvqyvjo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qasavxqq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnriadwn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sniorpsv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvwdqxd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kmalfppl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvanwao.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lzteyqgj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2viseotjy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhxdklu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafexwdh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2irfvhutj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ramyfcke.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oytjfqom.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfyttlq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpsdeth.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlyqpd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aieivbal.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2redursvs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwwytnf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fofvvacc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhpdtgs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yowyoqer.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzubxkz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkbkvdf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jexosbbt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2woiawokw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzstipll.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxzgzia.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpftnrl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuleqru.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iebsprao.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxqgsly.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2psqcuhct.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vimcgnuh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lrupehbw.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ifirxjxt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfyewup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzwzpaf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2laergwwa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2clrljlhw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2whgyjfeh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxfvdwq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvqqala.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqvojaq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ayicyzbo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfdxatl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2yhenrmsz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ndihjihl.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjngnwq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrrvfak.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxmdpxk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxjmbav.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsnoktw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rieaxdyf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuzpilc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjcafllq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrlwyeqz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtqpdab.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmhggrv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqwihlh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gbodzuns.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjuoihr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpdllqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nysvzxvl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpydmcv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwxrcuo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyqwaao.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpcoctb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2irvvhche.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnomuvkb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tswaqied.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdebyrmz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbzpvmn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbpdyfs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkqdcsz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjgwyyo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyggsnt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpibtmw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaubauz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qworixeu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqeozug.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2peczpolk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyvnnpg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhyrkqi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zgllougj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhqrynwz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uncdabxl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiolyhn.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkgssjg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxnbjvi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtfkbtk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfemnhhy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ouksxtrh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkvnmyz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tovrrkpx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsfdyqe.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyervlj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2oneuaoev.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgkrnbj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkrfnxp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uocdsgzy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixewdkbr.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwyvezz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjsazal.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ocndqmhn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkaydrk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2csaypcfy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsxdwdn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbdxtva.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ohffpvoq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkwmdjo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrpdxwy.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sjljsiui.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2npcsqpme.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxquwkw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2owpowkcr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxmjdbn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qruuwkfa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xepjyghe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2acoeyvuu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yvioxvvm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kchhkfrs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqoxhdu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cghfqyar.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xddmkxwp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvjozdw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2brbutjqj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjzenom.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2frannztw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjqdyvg.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2djqdpedx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkrhgej.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lukpdbdo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byjsfigx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrtdvyb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvwyxrz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpwexoa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaeysae.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxhkpdf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxdsxno.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziczipzy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fhavgkkl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2miuetwup.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2liqkypre.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wirwzzlh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2csgawqso.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqqmnxu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2helttdkl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzxranr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qjozohms.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjynsve.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsjzqqu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbystzsv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qmslwavn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dabpwggr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2frcfwvmo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2crrxymjl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dlapogws.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnywfkm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2etlgmwnr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpoutgc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhepipiv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrzwhze.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbdehaz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ofktwima.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgeiilu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2azkpieht.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbzhnqb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mrynklfc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgojezf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkyprsn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zfepuezt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmaomoa.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eyufzowb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hmsuvqum.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhlddzn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfinkzl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2foiytqom.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2enudeyoe.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yffgxlby.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vqhmdjbi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmilxqly.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtnqqxe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pthaabjf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxfpohb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2giwefipx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2avydogtb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xybywzmf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydawjzgw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxppxefu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vnrljfht.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzldemxm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2aexxrbdp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzbdste.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcyavhn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2aizrtddf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2btawulcn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aizcvjlc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2svzqoujd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnzxeye.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyfmkxv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsqkqco.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bkywwezu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcppieci.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnqkfdj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyfihda.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2orqkwonh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwajfbm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjzjhxq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tufwugdp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wlizsbuq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzwgzbm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2deobztha.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2omcgmfit.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dlevuesh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjnswou.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbiabog.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwnxwdc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kypcuqgp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsnbnba.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuzaxmy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vihlmkxn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qtoqumle.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbggbvz.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyrpvru.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2luqxbhhr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhmqhja.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ibujfzpt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpkeifg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jegsmpoe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmhygva.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvspgoy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2msetduqo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkidrlna.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkrmupz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqulewf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2odjhduwa.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xenowukp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoigeiz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzjdyuk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eodczgms.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2opgjhccr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjrcfwd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsuvvff.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iugtjupj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuluiun.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcwapnd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlfafdj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zramsclm.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjgzbhu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2feadonvd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fprvtosr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtumwcl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdxydmy.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2imagtbtz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rwosqqsd.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2licgzixm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmvmmgg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ltasqibc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbhyyoo.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tyomoxpc.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2isxspscy.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtkbrxx.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdvmnyf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2onphlthb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvwokcm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuiscuf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rusomsbu.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2mewnamqq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpcxerr.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2pmszucyi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2dinfgokk.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcamair.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtxnuxk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbfcece.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltylhtis.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fylnlncu.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qktaearc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2swoczljt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uolntmzb.html


<!-- 参考信息 -->