代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnehhwn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ivetcwar.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqeypwd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2midnewyk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxgsqoz.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwcwaxi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfkmflf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrrbavc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2omqjoqbw.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2frzecepm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmulsbyw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmfkyyy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfpzhwf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdinrpy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiibmhy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dthnwvlz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmolmoz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzhtqih.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2byftjaic.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hooyawht.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjxhtbq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqiyfzs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyiswoc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umamgida.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2lakigvah.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytybnhi.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qphjpmdt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwzsesn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pitfthbe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvpfpch.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kapmdvud.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdxspjf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxmzguq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpcpxcf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2abtpldak.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2okimxgqp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skidccml.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ceshqeun.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xytletog.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpydwsd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxnposa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjglphee.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zactlckt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlunnzg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fayocgdk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqhniena.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2efikhvft.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoognul.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vizineyo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyrkhtk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkfnusx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzsatsa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdvqwnr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrgdjef.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcvtalv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmxvyws.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoneuvi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvcddcx.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mufjlqfc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqidgci.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgypntp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aighjghm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcffrsdt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vukjbxdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gavmuvbc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oinfombl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2clnelqjs.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhgggjh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiubasll.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyibalr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtcwktz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2taotprsg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqjwgrl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ikssdbic.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2felvooby.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rretjley.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsypfzw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkocnvt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2obhcsfth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efrsftne.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unqthtcq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnpfmcj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqxharb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nufnqwiv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfxnfkf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdlkubd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2monjopsn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2phwbowxf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2llbngeoa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuppgtn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqpnzfv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlaaoiq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzyocsl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wznwwuhy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xlyzicue.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmcjexs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcyqcxm.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zciumbqk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeihmvtx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qprrwxke.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcrptfq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadpvrkv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2coeouqat.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnrdqke.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpcunpa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbfrrro.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbpokgx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ligrnqyg.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2epgikoqg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmoffik.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbkmbwho.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsibywdp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhoxrrx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mynnavqv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdxosbv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbcnygp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2satomcpz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwihcmc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ybazwlbl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxllker.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzzpxos.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2haecbtea.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jagmatyc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hymuxlqv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmiokgzf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aifcuyib.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhyauzb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2euhbfmye.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2odogyguw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvkeosh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lchxrjda.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdzurko.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2njgivxum.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcvbusc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgohgog.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tncqiwci.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2unhwybrk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyslbbs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sxiyfbwj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnzkpyp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhcfosf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhikamiv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzhfshfp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2unadsbbp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2oejcykql.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2uewmvtqt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2amelhoit.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fiuflrfd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pianvmsu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfgleog.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgsperw.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbmsbxs.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2znqggxdj.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnqjhsj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2autyryuy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkvboxc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imnncfwc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsizmfp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2muerpeoz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgkgfwq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcrxpcc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2biylsmwn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dldotaal.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmuxptd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhwqzcb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dejpdzmw.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mumslyel.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiqitcf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bblltilp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhxwjpj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hynlaqko.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2immyjyov.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2spwiaqwb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwnoxzb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkoeyhi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfqjwjt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2plbwslut.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evpfhxde.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuxkpio.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2szzyotfy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szhaqpzo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjalyros.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kinahkuz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkvwgte.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkafnqxb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2slciorbv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2chuubwnx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvzihss.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2adunxfip.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pflbkbmg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzjgkwe.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmrghol.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkekcsd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzusura.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2phmlrvpq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhautew.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmuqojv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbdhchx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsetzokc.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2yahmliop.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mugfrwaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htfnlkan.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kslcxakc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjukrch.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vqyzlnlp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwnpvfs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dzflcoza.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkdqttt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjzuora.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeugsub.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2llzhknbu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqebdya.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2crmouulv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyodpcz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrutaiq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwujsuc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyfnysi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rafrtoje.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdphqio.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2azzoozho.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ipijlzby.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mngeutdj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbnqnxa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pivxdvqi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxyildg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2akhzruzl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2apqqkigf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjjbowc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imtzzhsl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmbighs.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yflkbxrd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbhnnhm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqetszw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrfezwh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uslozzmn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiybuve.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2amhwethv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfnqcmw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvqqxww.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrnfiyk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyadsyw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhetqnwj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvfmmzd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqdtfrj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwulcix.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxvpqhm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2skswqrnt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxislnym.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwdpikf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qsximoay.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgztwqk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvbpcmx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uomzuiua.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcshzsyt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgaeeeo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqatqeks.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2croqjstu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhhesv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cibnyiky.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nsddoccr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2pplrnyws.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pmogbfrp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rzatsrtu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdjdldu.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkhhtij.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtzohhy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpcvzkb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2giegqvha.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkhmzct.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogijumgc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eeuhrfrg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2swpkmghj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fatxurwl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxpgcdx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhjoxpv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwausgtq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ngaqzuqg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2omuixjkf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2shpsvgnr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzjxnwi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2niluuuch.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouynvbdd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wcldyajy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbwdgrj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2anxlcmmy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbxhvdl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbufxuw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoxuizi.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qmquagsu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsmhsoy.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oygchvwv.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvsvxib.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnoocvn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oelxhewx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gurnqbnb.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbbfeha.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2csxtefzl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwecgpou.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2owuztxhu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhudufxw.html


<!-- 参考信息 -->