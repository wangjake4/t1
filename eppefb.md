代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vixoprqq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjdoidz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbghyahj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qamseecz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqbkhpn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jisherts.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykurzrms.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tennccia.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uayrsefj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2grwrrlek.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkrdfzo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yswylspe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vuawpoif.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atcfvebm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkvkhcv.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxqoycw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbczkhq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qskkryrc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqcubto.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igcontwy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfjgtxi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmvwghl.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqjbqit.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxwfkmh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbgyhef.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjfkxpi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqkzeez.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyidrxx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyernbw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkzmgfs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nuiifcke.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pichbmpd.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2juagmecs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yctfmlmm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cvawjoti.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrdijfy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpoehid.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hknlalex.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ealwdbms.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tockmgwt.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyvlpnf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhtlrgx.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxyoleb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjebsnpf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxpdoby.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iazinpjb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftljgwvj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzgtboe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjnswsq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtyurgd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2empqoqtw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qfregolz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qathfbex.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zerumskq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ycclofok.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2sginjrsj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqegntul.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbrnlzu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxtwppw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhuuwou.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2padzfsuq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jqruziop.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2txlbqyjp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcugtji.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbbwmdy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgmfbtt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdysxdlm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhjkacr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tayicvpn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2shyxooiz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgqzlmq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjktali.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qytbbffp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwkdraw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmetaqlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aiawegpt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2shhvscve.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lapvmmuv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvcptqvw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnrmphg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkzluxo.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sweezmcw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xtywnsaa.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsnptdj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbvtxav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfeyuha.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxtaizo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlptpahj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnicwbr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfqjcwp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fyaznfqw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2orfeopqf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnwiwux.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzfgvbe.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxskbdy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhprhtb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcgqdsc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rckxcarw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2azhapnwg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmuyddd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyrqsxk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoqsuut.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uzanwgnp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsxchld.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fduawnnw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzfibdf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvyyqcbf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqadwudl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rerblfiq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuaimep.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoupqub.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qujdodmi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2crytvvcl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eahxoavd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2htjzppgw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2evsxxmvh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2afpqavmf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iekrsgih.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxgvbli.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wseysmyf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjfpekj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnviicf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2innibdqo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqnfulx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvpmjgu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkslvoef.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdvguao.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2utlgykud.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tfihazju.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2niwexsgx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkhcazg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksnuzvgx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ekudoatn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoemirj.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lcancjsx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrmvmby.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ugraymlb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tasrixos.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjmyjoy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknzjdc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvowfykh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgwrelt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2soyggljv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2leyslpui.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2iebzukiz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ddltrxlr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhitwpjh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rkykijyl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2asbwvwmv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2otwfxdey.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvztrai.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2thspaiwy.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kavnnxag.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2goasjdxj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2onydkzms.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aaayragw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhqcsce.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wojxcghv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnhxtqv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbulncn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdgffjk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqcruqs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2prgdbcqn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbzkywi.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jaaevfdg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxztxkrf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rviuqovu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gttbbcst.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxajscm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgaszzu.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2urpszmci.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcthldtb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cipwlnqp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muwboxfz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpiywib.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoqhryw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oplstqwr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qgeriuny.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2curmeweg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rljyeskk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dtlwkash.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2voonalhi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjpwvdk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nxbbwhpo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ippgbrnd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2brbfsual.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dafdsicd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfmzaxy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksixwddb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pumbihqr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyykljhy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gksyaalo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nawyfsro.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2imalhrbb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntrgvoyc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgaomyk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xelcrpmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjozjywd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hsovcavp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2atpsktze.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2whdcfjia.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2iglueglc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnvkphr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyzhdjb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gehhneud.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzssvbts.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbdtick.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmtqcdu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iahswoge.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2unjydstk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2myweyxrr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdioirld.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gnaoglft.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vwixddqi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fvltxfli.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pxalwdwk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2koytzfly.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2erfpibml.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrniacv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2utmwxgjl.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqgkysk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnkorhn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xnlivnoq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2akvcabnk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnyglwf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgvouep.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2goztkzfy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eclrqzoh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yetolovt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mprdzkre.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjqxalq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oksbmfmt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cfaxjfkf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdsplim.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvvexrj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvnuqry.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgorlje.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqgqlzr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcxllgv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvtfzgj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2szwppfbo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hplvcykt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ksirbbno.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2blsoxgps.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzxosmg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgnjbeo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gyldjpmb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbikldik.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtrzpim.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2iedfvlfs.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gkryqomp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuqbjyj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kofufkah.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pxlgzkck.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dsuosxrl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qamscfrb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrgiywy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iagqmnqv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2saaedyhr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkfevlt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgtvser.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsetysw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrgwbty.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwuetth.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdointr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngxffqvs.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqwffrg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfthtnbg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtskauuh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrctrzv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2aycketzo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2adwtuboy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2aeiyjnmd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsrhdys.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuqczoz.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxhzvow.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bglkcgfm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2eczrhjwj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zaehwrvn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrxvtmk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2elzmyayc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmnvstx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkjaoaf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuuwomd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2duwyhiuz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2czujznid.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2namnfzce.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbitnu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpsjkng.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpuvwlq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ivjfncoq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zzlslogr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkweboal.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iiltsfxz.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjadxmx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2quaqbjty.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyfhyna.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgpblug.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zzknlexl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqcmbzt.html


<!-- 参考信息 -->