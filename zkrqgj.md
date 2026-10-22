代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iydxiwdk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtskyyk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jilzvmda.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qrficary.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pgujihtb.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjvekyc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2itaaiwxs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uiomtaok.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2czdsxqey.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuctohm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkxtxap.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqfonvk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbtepvr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjroxdk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkxdrhi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pistsdft.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mspcllrz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyzutfn.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmuohtv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2goyexqrk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zbspynco.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrhkdrm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2izwbwnia.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xaikzfly.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrawbbt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jqvdwmvu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gdzdblok.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egttmhxj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lumyjnqa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mravkeuf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cutlpaci.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ilozqiwy.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xphnxvbj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbagyzyo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoskmye.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgdvewh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rhszkomi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2axggukzt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdjwkhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikeeues.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzusxui.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkktxfh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhdahky.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbrxkiw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2skulgrae.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rltapshd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2riuuwmyc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxlxgwl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnrnuzz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2smbatoat.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnyljrz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2viulcqzm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeprfqh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ziudaogp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldahryet.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqbdvii.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2olidjcha.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sookcqyi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ruljbsia.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbxzyws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkmbvmx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpyokks.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhbtypz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2apakehtw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dppsfmel.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzwvvag.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwgsgkg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tcypqxny.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2crrpzwau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzjjpng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnwjtpk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyvzinq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndumasaa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbvkaxm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2buaptslr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2krerdznv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2mbyidayr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpkkmsb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdvztoz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2urtercfw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2agfilmlc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2unrjvjxr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxwholo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2amyrcrez.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2stlkxxyw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shrhecjx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqrpiab.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjubbbs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzsfeyk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2agruduhq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qqjchajs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2okuekshm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2umotvekt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2whykmhhj.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sicergtf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqydexig.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2unmptsid.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ushderpl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vsymexxy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihuclwvp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvtuxcj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2evwhlamw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jhttwlsy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lipyokqq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmeauzg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2teugzedx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjvrlbd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeibufyp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zzumcsya.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrcxeeh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fngmhvvr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpmbgbis.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmravqa.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpoylsv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zphdxjuc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2brdzktsb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vvlstvqb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwofrkp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bjctucil.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vllwkfpx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2smqkppoq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhyxrtk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2udqfdiav.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtmpkpx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abymjfby.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2suqpzwqd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tjplqlbp.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmrmeyf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgmhank.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqysdiii.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ivauvhaa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvovfqjp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2btvhqarh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2msimparo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggufoonq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dlimvpqi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lluryqlz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nazxhhgk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiebgje.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nftlrbda.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nklwhloi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2unrzaoxj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akjxsihe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bocdokjn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ybiqmplr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ueghodyb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2delhlxrk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2shpxhzhh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2csovypqd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2febkmasw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2abikypgs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2iusdxqan.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuhhcfc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgmkqfk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwuonyi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2abzszjfm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgkczay.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgfmvjj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2krjybutq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdxqwow.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wzugafhj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxnybga.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhqkyug.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwfqald.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2oeaoakbv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaqotxr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rwybzulv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmsmmuu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znuwymbb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqimkzhr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2keppxlig.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nympxrpm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onqsbhys.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpumrdm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2enmyjkgc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwhkndo.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2scefzueh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvojcnao.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjiztyrp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xquqcrtq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzargqq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2icyqrotq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvkwefl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2oicydfvo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bldnunad.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2txernkdm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqrqsy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnrmkji.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqdbyeh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqzsvif.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgzyyvj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2brchdjnr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2txnmyiof.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tdggkmeb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgpxepz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ynleenja.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zawudxrq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnlixpg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fxftaybz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2asxnuifo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cacxjgnz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yusbpcif.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqqlrxn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxxphim.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyujdpz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gctprblc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmvbcfp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnslili.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2noptzpfb.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2avqbuobg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ummsqhcn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgmeybc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2akraamwr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2usxpxuby.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxwjbqg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeqtgzw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bvixkjce.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djswrtuk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oznbmsry.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tglcqvvk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yxknmlrg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2itwipsmn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ohksjtui.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjvudkf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2neaqrcfa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gozmyrxf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aidklaos.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgorbtqv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgnulda.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksljlxiw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fayelxyz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2snrqgewf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2knbrvchk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lggrhpnp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyupqp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogymcxs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lfokdlmi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwrurzb.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cmsjouda.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqthhpr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnhfdkz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2aylgejva.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2merpollj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlamjbr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2urdsedkv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2kogiqypk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2itmbvpra.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrifrpc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwvzuil.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvduzpq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xadjmiin.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2eizfkoip.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pijdhztv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bidmnesg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xavomdyu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2inhcxkos.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdqewfm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnixlta.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yshnqdgu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2shzqhzyw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2namotayn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeaytcm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2efoeprjn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoquywcb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2amnntrhk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeelqiq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2yphhwfus.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcgxnqq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhzwlrv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2abjtdmls.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2udkkbyqe.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2aaajvpnq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqktfjt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvqluhx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmwlhmh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytygdkd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2oeumwyqg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2toovuwmv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvrghou.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2onlpumin.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzuuooy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeugeusi.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2okzzjfpe.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsamprvg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2srvfqgky.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsnczsa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mtysatxk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcmnjzf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhampuy.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnckumq.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwmwhyk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpndahr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthttfj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pytqycfs.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iddvascl.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qioujyqz.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fjedumjb.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2vasbtatj.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shsmssri.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzhhcub.html


<!-- 参考信息 -->