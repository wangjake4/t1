代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tifciboe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpdxbhe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gorazxcb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2cebbrdqk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyxgcdu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgervnmr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2phjjdyuu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaevhxl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuiazpb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sffabysp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbutnrpi.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaljvcd.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gyggxmqh.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2smhtvdoc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvettem.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iinwqsys.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbpfwxr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtjgakf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clsoncft.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkoace.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zflrjihm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwhasox.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2bupefwgg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpsotiz.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvvlsmb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmcmalw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kxthuimk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbhdnhn.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2pspbuskn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdozixt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxrjucr.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xktswmcp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvohosl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2emtyslkx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhayqsz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2usbrdnjj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2panxhyyq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtucwmc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2stzcrcua.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmunfue.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bobpgxds.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwjxjrl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ayergyfr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvhmhag.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eneuummh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nowapjvo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2febsmsvc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnjlupc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzgwjlz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyhhfyj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkfdqlw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpgybmh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgjeois.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pulpjmma.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsfytmp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdjjnpa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopidknb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gizxvzrg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tohssful.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pubbhliu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxgdoih.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgksrpj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvtrrrq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iuplmegw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzeplpq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnpnykt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbhwxxt.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2djacnosl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyievdmu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ungwgxmy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxiawxx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbazvho.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctywzblj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgddbod.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cepvfoke.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuubwia.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzylvkn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2duhcttql.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2syuhxiju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvgoxab.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xctrwvtj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2agbtqbzn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgkivnk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2owdexwrb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2locgjmhf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lltzmijf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bhffcxno.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnosgcee.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2worxtmjg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvurdcr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuscgou.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2imssokgl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkxwsxy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeylckbl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lmouglga.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzoybeuy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgvpkis.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cesgpxyq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsuufua.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmniajam.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmjvkov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wonexefq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ykumxpis.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sisqolsb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2oagwbngb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsihszba.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2txlwktpe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2icyhtqbe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcebgxj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2owgmbtnd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sjziqcfj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vghhvwwm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dktneezh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2onlbyguo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkzinss.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdfnxyp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jeitcske.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvreicoe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrgjpsg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tikedroy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnaujdi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwszubrk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2njhvshiw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2encwegvh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwgvnsq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrkauwf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvcmele.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlybgmz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2whrctarj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhysukw.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xevvgwtn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdtjcps.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ybaiypnj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2djesfaad.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuwtqhi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyzznde.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2phoenadx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhlrwop.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zdoomadg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yomaodra.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dobtycqa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeehvvsf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgiaqhl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2payphkio.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2egxuhvqc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fyprexcg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hymnnipi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjogazc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mufhxzwh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wwczufie.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kimmeawh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2idhdqzjx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lolszvfs.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2giuqxatn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhlzasi.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bghndpml.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nbufndud.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2auuqypqx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaqgtza.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdrcoug.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvpefhl.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2swdekdtm.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rukdbgfj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxcijdg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqnwzmx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dddvlksd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbvwzau.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyefckj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkmgbwc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acedhlrt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bscznydc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdubadm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeqlxfg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2babgugst.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpbfqao.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuouqab.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aodstcpm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqtjxvk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idohkmtz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaesuqw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpymtyhm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxxoszn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tchlswlr.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhdslkz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbzeyvy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gveblczj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcpjuhf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrfbaal.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scxeicbi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2adscwifw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxkgzbl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkvhubq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2guwfmmij.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyzyhws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdddbhch.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvgcmay.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nhclaoxf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzcxyyh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnidigrz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlhvgeg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfkbafb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvsgsht.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrvqket.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emteyxck.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xacasayl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpandbv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2rackdunl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oubrwvmz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxhloet.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eczotvae.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vdachkvv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqkdsws.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkfosie.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fuasnojk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2brcjbaqb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yruqpakc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mapjjwpw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwhdfjq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzlejat.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xolagacy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wiotgxjj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sumeliqr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyfnyul.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdtjywd.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkalnxx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzxryfa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bobhotmj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmgdqvh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2slfigvzb.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwerusz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnqxier.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2poapmxbd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdytqca.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaffnje.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rohhajak.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlziggfv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2iffqzwia.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkzaxce.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2obkgkzrj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2svukmzwd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vjeglcmt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbenpeiu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zznboosy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhypswcd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbecdga.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmtizmy.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vwtnhqig.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kejmkbsq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoeppde.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mlngvebm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbjjsfa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjkjdpn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrtaxbu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2inrcfhyf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhsgybz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxvlslh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wpotrqwm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuupqfo.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiswigc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cntrpkty.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2frjgjmnd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nstnooki.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmsdjtq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjdoqqd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxvvcmj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qezsiyqs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smiscown.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2znninhnc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2fkybpili.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdknwhxe.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iuihmubm.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2alnadbvy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2orkxrxev.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbbzgxt.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2djxewsec.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nomopyvz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqzfuky.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cknbxmbd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiviftd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2eumirhmt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvigglx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggonugpc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2chordbds.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljodujcj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgagstg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rnksjsvt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rowjnbfh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2crxkhjdj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpszatt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbfbkir.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhhykus.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqmygcm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vpovpnjl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuljiss.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2glsniyvn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpmfyup.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fothmava.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2utvxkubl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlpggwo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjcvkmw.html


<!-- 参考信息 -->