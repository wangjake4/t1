代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrlxyqp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nctehoti.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcjpocx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mvahjcoq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjglbeht.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xswkgkmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsejnve.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlyijac.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxubmpiy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jzupecqg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdxphrz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrhuezy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqguxkqy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xultbsxx.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lotndqfo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zymfmxbk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxfzqpi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgywwlxo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2trwteaxk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jefqkrtq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxlwnzm.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2atspqkej.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnzfjro.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etjsbnye.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfhrxzw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzoitwd.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwycwxh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxjichq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mymcdnva.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ermqdvmk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmpkirj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdbpne.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpvlrwt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pejqzjta.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wptemuym.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gakhqkwq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mekkngry.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtvkaoa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxktcwd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qvaqxndf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkyxfefe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ykovohrp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlcifxc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpbrian.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lplsmxwm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2citbuegm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brqibght.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvejxdxf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbvlcfw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnptnuy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lritfrjg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zceanurl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2fydimvib.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqxqtzq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2raacmvvh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufljcpsn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfqomfn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xevpgkrm.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrsfysc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2anxqzelb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeruybz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsjjqtf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2svligohp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjhqnty.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhlshfp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vfanqcyn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhjyzbd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2niahrjlc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cehveaet.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojriidxb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqxpafg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wzueyexm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvddccik.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjxtrpa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdomkbf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2foitptca.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbklffdw.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2glyhbsbr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcjinew.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2txqetjcu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqwetph.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeonylw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdoivcd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtvpkmp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdeqypq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjwxmkv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkqifcf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjiukcna.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hukbbpos.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyufjew.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hckyaalx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bmolfgtn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2eavjziyr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtcxelz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2laezuesx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2thdorjuk.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlfyeln.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhiduwk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nhswuhub.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrisfkx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcehyws.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eslqxgzu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnwklsa.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kueywvgi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2npvetrkx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsbwgjl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuttegqk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdvxcgv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hecjnxdg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xinvzqkg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2touymvqf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwliyrpc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2phdvjmew.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lunyrozb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2miaeaxlt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfqnypm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbjvgne.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwntnln.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2emzjcrsb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlleudiv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mghottwu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dwddyntu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlsspjt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2akgyxjxu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwqjllc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oheercgh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yggrpqzv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2otaavqeq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoxasmo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmtcqbj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvapoln.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oztnbitw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2utcqkveg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mezvndgw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2stunigih.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcbdcsz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2emuigamo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdyxxsb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2etobuxuz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkpsujp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjulfyq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bujnrtvc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gavgxdhi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfpelnx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qqczyeoo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2meqlsotl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2smnhaupt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvqxqht.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gboxhnqw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2anbnfbsd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxadziqe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2onzqpect.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrkqkdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kypvwevh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2drjuahhj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bcducgzp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcwnmsz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnvuxgn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbsezmy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrhgsvn.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2llpwspmz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2glhyfrtk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awjusfqt.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwfhwtb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wswwqiex.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2brxyreqg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqvmifi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jzalnzjp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2euxzzexe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxffvrn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mjornoyg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iopiymjy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcolduy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhkekdv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxzdvkq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jenbqwua.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2diegujlb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxzmanx.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ajduqefl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqvygmp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qqarrvfy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmudnelt.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfeytpmj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2klscwhhs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsntpwxd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gabnlrzu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiukljx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwpecbk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oimpenjk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cfloxtzm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uetlwbua.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwpmfej.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfuszse.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkqebpw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcivggvz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqqfkyk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nciopgej.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2byhrvqio.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvimxnb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsubror.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2epghcmmp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwnvraf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabduysu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2afbqjykp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgbrdks.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lniodkte.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsxulsw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjvfctt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqcfpgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mweyriwz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzdxnis.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfvqgtf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2azwjwofd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mwqivcug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkptmzx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kwauqtiy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwrwoek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoevzbx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fkvdpyao.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nnutbqyu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsffcwd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbugazuo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eaupjrtr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnbqqyz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrqyzzq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xiitjjnt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyaswla.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2obywmgys.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhfrjq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zztsoeeb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrutdsn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2quvpukab.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmxhstj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxwcbp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pruymenp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbekmcoe.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckptngno.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuvklse.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzntufn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxzwuyf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2swuowevt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxghrri.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyoylif.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvlpaopx.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dicyatym.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcavhpt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdylfiv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvsiumk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2muhsierr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdebeek.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ropqozjd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2llilfprj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vomcnjze.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mradfpjo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lsycjbvk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwruuxj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2skvebgxk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kjarjeep.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sslgxzdh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvpmzqu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwcvzbx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2omixthky.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pyusfrag.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pupyxsmz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfpwvdg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2xujznfjl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nkykiktp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2offenprf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgindyt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yenukfco.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gotkfclz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jifrgjlq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jipxrzki.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2bdslrkne.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gulchfxc.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2subhunef.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rbntmpbp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yblmouqh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eoimtagg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaowsij.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bifbbrtz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2czyawqaw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxncnyw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwbngef.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2npwkwvhp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cngsocpx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dinycwhf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdaveno.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2afhjbajj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbtuafv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2esejxyfr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxbovce.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2megeysmb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkfccut.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bofbdhks.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpuoihe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vuoyxeso.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbzwmwc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbccsnts.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrlimyf.html


<!-- 参考信息 -->