代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hddzuqsh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdrzcvq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrjgqaa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmhzsun.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tftvrqtx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vucjrwvr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiizkbn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2doeuborw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2fljllxkb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvzrxje.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qirlnqax.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qqebyqpd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfukna.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwwuaiy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkumpbf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kyogxadl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyikniy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzttjlkd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2buirfrdm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odlkcegb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyioexp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mprbtbog.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2oynlyipe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2scdlxgaa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfjojih.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgcthpk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsyxssj.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bgtqnmxv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ybssytsm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtwqwhc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2avijqzeo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prjrqpjd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrfssvn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpomuji.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owgbhkfo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxivmnu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyzgkrp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvinrcf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhwhfrz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmvwgif.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2usvkqkuf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2coslrcds.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2drizviqo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dchfgrnl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2flfwilxg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mumwrfcu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oppeugfq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygatifdh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhydrwag.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdyblci.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwuuasj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2btwmtixl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2itnsbhqz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2frrpahqr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dyquzazk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2oobgebhb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxoohq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2trrekipv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnctldq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jinltkqs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bijrspkv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbifuln.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrmlnfv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2idpceksk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxggsqqz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhtzlfw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lptscqep.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nauorxng.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fphdxxcn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjbfvmw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tlynbyen.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vubwwxqq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnnwvje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svrshrpw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzbapjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwevupw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiuqugv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sahytwca.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxefozku.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdicylo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hseomcqs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaaozpw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2asvxcccy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlyycty.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgjvbei.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlqedhg.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjzvbnm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqoktowj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wddcljug.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrkgfbo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbumlcac.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdjezwb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dzojnung.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rystewil.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtsjvru.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyifvsas.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kysqtxez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2axisrvea.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwpxgoo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsqwtmt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoshzvl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2afudikuu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iawhlnza.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2atwqijlf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqbuzab.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvhghgm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsopsvrx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2biwfhfso.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyarqsj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lumaxacw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2laepsoju.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgilvwx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2brxymhob.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqzgjfs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jaralare.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifajrlfj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrlkniy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jltxjhvt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbwfprw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2otjyhcpd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2whbsnfvu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xinvuvgv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2imqziruh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zffpfjim.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfcqyze.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgzgdax.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gijvnkpn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqvsmxq.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmynhmjf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkpszfw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jqawbare.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwlkbno.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtqeimp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcxohnk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sryvuclh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqyvzkv.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2habkcyte.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrosnsqf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnmnmun.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uowxeath.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdwymck.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tsllhbnj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmywrgx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoqezty.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjukizex.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrcgnrz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjyfmcj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2foiasxne.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2grwfbwyq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xmandnec.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2agphhmvl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kzggkpir.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jklycafd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaxnuzr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbpjesf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ihlnfptk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmofnec.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xarlkhxd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmsegdn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjamnzpi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsoovcd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzvclbb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dubpikph.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsymilo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2johxbudn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwunwos.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uaehgmtp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yulnkhyr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lbizewtb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzulotxg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2shqymbrs.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgozqlv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfpkzcb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvyhkha.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrljitr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtmgdle.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsidausm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaflefu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjveumq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fkznpcxp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkdmarq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jubexgsv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnwiqbe.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrjncoy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vplnqffy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmnarku.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fajbwgpn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvpvbdi.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2saxjdjio.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjczavs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiayodl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxjhsrt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbhxqif.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzschtyc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dthpbpws.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhvtcra.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vchoxxoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxeltam.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vaiyxknd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujniyljw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eakdyrjp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ebksujtm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxqmfpx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmwovkg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iundvgvu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2znifazlt.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ulszlzgb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wecdelvo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nopxuuvv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmxmxdl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzsqcns.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dgjhialo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ulygxxrx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfmqfwb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwgebws.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbtxpof.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfafwag.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyfpuhp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkuyarb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxezsjdr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyvysud.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wenotpeu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iqisvjvm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmegwryi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihympxvw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbxqfsy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcpwspt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2baowmqcg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dkozrdom.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvneywne.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vffsnhtz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2neqkrhbs.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2glcvxjon.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2crqhnlic.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnddqgq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbozvch.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ouigsbuu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdxvxrc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2inbngvkt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsocmjii.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjvbzux.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhjgbwx.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjrtggh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iveezzhh.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bavtrytq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rnntavoy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2onxobfbq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrheuyn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvflyhu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzhhiag.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbuqraw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgffusos.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxxbfto.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrknppj.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrbmfvw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eviyaipa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrsiepd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2knqzxawl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2grbtknai.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdmylvg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ixazzsos.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkulfas.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvxlyzp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnzwctc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2apzaqjbj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rstuxjus.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2spzbcbwz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufsjnde.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbtkzod.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmkbiri.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuhkqlu.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfiapbx.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsibnpj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ccectkpt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2etfmomvi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvvnvqh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2naztmfln.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdhtkme.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2efimxewj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvisvkfp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkqpqyf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hfillcqx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxbuegb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2drszsaak.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmzjwil.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqokdnlf.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dklbdlpa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdgujgk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxsngje.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dheictck.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ulctvfeb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2badidsrk.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwffcymz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqpdgzi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zcmwqmti.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cikrjvwk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfzrogd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2etwzpvbs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2muyrcjuz.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnauhrer.html


<!-- 参考信息 -->