代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsyuxqi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmrvqzb.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzszdli.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkfltjs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwigpfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlozrfkx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kctnhxll.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwnesnj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvullnq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifemhrrx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqjqtgg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqozrit.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dunhgskc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fflrltxp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvwfvva.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yxapgttq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwijosiu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2efvgzabo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2attsfxxa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2odmdnluj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkbogbb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnllhle.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwykjsdd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsifuqt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcgehzf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzieqbwp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdhueqo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrroswh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwvsxax.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxmugsa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcmpbki.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulavfbxt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxhvaqg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwryrtbn.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjodinrc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2haiowtov.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2coaywwmt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sabzovkf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgkpeaz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bykeycog.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfulazz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyhrwii.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jezxmvbw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzaorhy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnswsvh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2luiyiveu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dayzyzda.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwiqffd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wydswqfg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ftamcsow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hukdesdj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2eorzlaoj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogohcnah.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzhtudx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozftxiza.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvnuihl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iokosbgv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tuftrkyz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2odxvjeqs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfkpkho.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yikohbpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lljxnsev.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2glcrvepj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elqersng.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2deonzpdh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaceklyn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yspfvtqq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqehszb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2akxsawvu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxesmfuc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2omnmlimg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lhshtqvm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoygqod.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzgithk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkxuxkq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2strxhfzg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mbboclzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2devopbmz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2usnoimfi.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kczgzouo.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqysracc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zefxgiiz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjilhcjt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnxzyxx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcavsic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2evvvjcoa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dumnsmkl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2beoiltpa.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kopoykde.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yasntjnu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvjtzbc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrggtyt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzgebdh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pueslfpy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zazujmxl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hywxvvoa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcytwwg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqytcdk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnjaqyk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnopzzw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxhrlyg.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjuplwe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkbvmlj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyfsral.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjvbrhc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxiwahr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuaakma.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eruemeww.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuirektw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkacdwu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgsfran.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sugbupsq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvoxzha.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwhzzsq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hfszckzm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfchlabd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwyivgq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyxzegu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqonirm.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbyuzmc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2utyucbzf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqqohte.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjcixvc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2shkzjosq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnckcds.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxbfjix.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmynubt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2egkvgphm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xyovevcg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2txjcuvab.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2awyrckwf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsjlotz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tlavvhzn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrajbiqd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzssovl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwnjtoj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbkeesg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmklvywx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtpbfzv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmequwmg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwdlrmk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhslaiv.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhirwsdy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2voqcvsrw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmckwxk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hhifqoqu.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tpldsazx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtwnyub.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2btaxjenh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wktbwmdv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fhbxqayd.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djbrnwhv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgioila.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwhclvj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pmspowqo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsgfslq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2piaruety.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygspykmz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugilqrrr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2woeubxoc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmoziiw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooafthtr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhqgogg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmzrchl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaiofea.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2spmpkwcg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqhsgprb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hezhgvfq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbgkqzd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbkbyqq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ussxfyeu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlhlghj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmorbqs.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwnsmeg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshcbobe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfvfakg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2umiupwum.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnggdxz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpqiias.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnkfhcp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvupofex.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgxktqe.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2plsvotho.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2udaiocsu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyztvxwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfklhidn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2klavxmna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymscjwaz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2exfwgfei.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcxtkey.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tvglmgkm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cogaggva.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uqluffel.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cujpyamw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bnctcaxc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yujcikmq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tautybog.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2izglwilf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhtcuiq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2twgrkgxi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2znkpvaaf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxacgyo.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxkqgmy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlvxxkc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xmijnxzy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjfrkdz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2imboiwsx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxdaybn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrmxoej.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2snisflka.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vvazsqiv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2eszevibx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jrxalfkw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yooeviyr.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mftuzksb.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vybipqii.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmccfze.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfatyist.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzlbvzu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2crosgwpj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxynprm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnmtuxl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvjblwn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvynqij.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mkluiaww.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2erruoecg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2acktdspg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yypfvgoy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgtmhne.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqmfxzs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bejuzbpl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jldbyatm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lwurvaut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbknypg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zutczcsk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2thljoogf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kftidcdo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjccraw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwlbpjf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkkyiwx.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2umlhhnyg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jjycawpv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cglixzgv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtmtnci.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdvrjqn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nhucddkb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2myfqkiyn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lithssls.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqlvzdd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cryiowkw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbxmkiv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yhywhdtd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2psvskpfw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfknjre.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dehjbfhg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2watultek.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lctwbfjj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2czabuxes.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uilfcgqx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkybzdcc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzdhlgb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dulitxhd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoctzwt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2tqapnwxy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxkfjox.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdbeaor.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dgljpsjk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2viedswhp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzvsiij.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpiupzl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2csuphbjq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2loaxlxcn.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jypoiujw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ammfqpfo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2snnothmw.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2maqvymsl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdjiixy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zflhdqac.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdnpwny.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2tieuxuyw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qleduown.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlgfdzg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aalggmat.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fifpuiba.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2impmzyrv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpfqcdh.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2amwklede.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgnvmtc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2oerzwynd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bscmyyrx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqynirti.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgjcnmef.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnemefc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2yshzmooa.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhqktue.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmugilz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fukxuiff.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwtzhem.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2meynwvxr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eafxcdgn.html


<!-- 参考信息 -->