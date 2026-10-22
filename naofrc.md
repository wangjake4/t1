代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iygmhear.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rctjndmc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyuojnq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxmhhxx.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyykxth.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qeauhwzh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2kanpusod.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xgagmxgx.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2klqdovug.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjxjjje.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaemnwa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuhnroq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dbckgvlp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeywvyl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkngevb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iarumdcg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhelsxw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtfptish.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeeixhy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmnfydo.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjdikft.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eroghdgq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdoacnv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cscboehw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpztmsr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nldoqhis.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lisuojjz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpummwgx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxyofnpx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fldwotca.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxueqcy.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2beibcerv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtgpchb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuuisvf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ixilscbr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lytkxtcs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpznjwl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeeabow.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cprwubhf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vruencsk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2orpiqsbx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdoqaazj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxqnqci.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhayetop.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmeawrc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ckezcgxi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqpajgi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmpqyqc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyncxkvn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nyjkkgbn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhlwohc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aavxkiur.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssecmamh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwecvpi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfuzlqbb.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yvelwgku.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtgncyx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkfyrcc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnragmx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ogboqeas.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqoppuqb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mufnmbes.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2isssomjk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oopusawu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lujgljsy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bbmsyesh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdglzlg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhgpkzt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybigqylw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqauuqcq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbvoovl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uqentdai.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cklmfgzi.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlsxeey.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dshmjfxs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2paqmmrop.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwgmnhn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2awosykcp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2kgriyyrn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdxcjse.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjizaik.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrfzgcp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kujrmlgl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqctkbwi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mpysamze.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhinvdj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdspjip.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmuistru.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrliuko.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkhqsdd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2alcpisro.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfirixt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vucolzok.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvymgmci.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcjrtwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrjoara.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mixvikhb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihtvdix.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2znhyontu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uisvgvla.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgvhvmf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpfqzui.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzvyfhx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2blxqyvhb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2icdqvcxl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bogthrpy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2angcdrfb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2slmnexfx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpcpgpa.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiewjsmq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mqorhhsm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2spyzehzg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2emppnppf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqpmmhxx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2labpgumc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2idnkjkob.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqajbsgo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvesjze.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xooujtvh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ythfcsqu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ennfrqrj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vheppsob.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2asvbtfxj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjmdeag.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rwiptgxx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnafpwj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mlckhlut.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2utdozytb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aneogskh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyssgaxf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlcfypy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzubkds.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gagjfwum.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkbsoft.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwxdwhi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2excqpibb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2huofvtpl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2onyqernl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcctavg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlbtnrs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtybheg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vkurhvnd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmeegkf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oerkrptb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkvzewv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjqlrvo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnzzfzl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2woarhjbw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdcqini.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihomaqxu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kaomewib.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnvojbt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plqdofed.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvapkisx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oamzkooq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2njmsjyiy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2movqitsr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2behcpuex.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtthqibw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhsipmp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sepzfbfz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nohapfzv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjfumrq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagbjodk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2efkqruzb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avuytvmr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaoivmu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxucafq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vacqzrns.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2envegdvg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmiaxpkj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoskgbz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwplzsi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwrstmp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2arabrpkh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwkasni.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swvhsrog.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2igmnaokr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgvfjdq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2huowvjbh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yttmcbzz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vtogmogq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibppiiee.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2katuuitj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2prqruffn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2prajwurl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzyfijn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkbwzkk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfhdsir.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkbyrvw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmudlbq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfixenk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdesotf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amhecgqw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2utgtvaks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfozlbu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2shdxwhgm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wzndmjhk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhyyesc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxblcki.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kiluzjyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcaxits.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2smxhwtig.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqirngr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qttqzkex.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2frqbjjgq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2htjnffhv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cusjpkvi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnonsdd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtfjxjk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xjejjxlu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2djlzjtmf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2iteuevxs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2khesdgwu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjivyfec.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgisvtn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2afgzshpa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjdwzwr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2npfaaebu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2suxqywfi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2urfzvrry.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lygydtkl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtgxiad.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpovwld.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mnijyrhq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvunzgf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qilxfcym.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlmdmuo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzrzeeu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmwxxfk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hswdciuy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nppuvulg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvuyphb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2imsnopas.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsmctkn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizcbzry.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrgfdkg.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgvkvef.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtvxcav.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ndphzrpb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrnuwlv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2riwudisv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twvnhxav.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxggwlzh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtotlgq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhchglbf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdvbajb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtcxwdz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqobooy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vvdlkcdn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kkaqcyou.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jponqerm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgzxzzs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvxhjzj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcbasrr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyasrbx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fzletohf.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxlvxpj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpivsfx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vkobzeje.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxboptk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdxczan.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hkskajig.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2utyuivju.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgvrvwx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2krcrfkik.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrbooza.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2erqkbnnq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkmyfzl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2umymrdqg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2cvfajson.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2htslecvn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jwldkkcr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2umqllfmu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2oojegpvx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vesyzsfc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqxcbui.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hpumgnvk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2upqlsgku.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2novzwxai.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wphyjkug.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdoeulm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsvszfo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjmuegd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnolgwc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybvczcqi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2plsdtfzb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyrueth.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ffemsiyt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqtegtz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bbezmywg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqywdvj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2nszqbgpq.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2khjnewwn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhwecsf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqggvphj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2saaghwhk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tobvtewf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2linwqvml.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzcynsn.html


<!-- 参考信息 -->