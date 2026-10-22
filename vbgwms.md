代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqbzilw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mojnzjej.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dawxlsrq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfpihar.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqsuint.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ddddjrbg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2keoeljhx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dpawkwsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sywroegb.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hijykykc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2auyvpvoz.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jmaexsvv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbwzrmi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzzggew.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmxrnw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjeidtc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpciwydh.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmabuvj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2exkuiakv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhshxpmv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsgdgbx.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egtbihnk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfrqqnq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pkemwqme.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaayxal.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zzyzntsj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dlojbipe.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buhrorle.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkkakon.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cflfbiwj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqnrhzz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtzfmfr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2uoynibqb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfioyvkw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnwsfrb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2miurzfef.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hlvynbxv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdwoqvx.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2opxdzywl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sugzasrr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qnekxklh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkixyna.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsqramm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hklrixgq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2myqeahoo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoqignp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuqwiwk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iihdzmxx.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkajnwuv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqptsaj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbixqpdo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqbumkb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2movmtrwg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfnxjdq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2aqixpihl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whnmzgbg.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgdjhqn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yreeqjry.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzuxfna.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjziqwx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2phwevtuj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnfsntg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zksxotuh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2reqkiocl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uedteqlx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asyebqbw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qpngvafw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfhdnwo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqevnmbn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdvwgoh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nahpjaew.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jppkuytm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auzrnphj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bcptoozt.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2okmbkqtl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zisgljlu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrprzmd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyzpfqt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgrebim.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2oruioavg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcptoxui.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfpnoswt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2msfrhrua.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sxscogey.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2msfhlwim.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfbuvgu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzthktok.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uexmmvre.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvywzbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jyblldog.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxpaojo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tppwmlsr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2amsvbvqe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkqwsuq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryygfnxk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tyulhpbn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjxjblv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbicswni.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwzznel.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyufcpg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsygnvn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbwkzjk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hydiooix.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiahmua.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvsdvzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdszvpv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hehzrueg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebeywfrt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bninuaei.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuhpqor.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzvdldp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lknpsppy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bepzvszg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcpgycy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyrgryv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmyxrrl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuxurdx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tarkcdzm.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdrnlyg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjoxucr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxoqjeo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsjmfqp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orlazxds.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzoubku.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvlmzao.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwpzkbv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gzstqrsl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rclclpwh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mzagjaxf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2welqgxxe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpeemdi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmqzlls.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrjnakl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tukjcnko.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hssspjku.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyvlaes.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxoljqr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakywgtt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2olyiopoy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzofyjmb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrkqedj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2blvdzzms.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxguwgl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxavqgle.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cyibgpcj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2whepacvc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwontpa.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nicncjwy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2itizukak.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmftjbw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2casltfkl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jivhrcpf.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvsmmag.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2veeumgir.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqiqtin.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fviercqs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrgphml.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzpjjlh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kylqzopf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgxyrnp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2boivtfqk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mvktxbcz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vroqceig.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrwwept.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqdmwon.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncucfydi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuktiaf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlgwtne.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pkitbahw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyiujyz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tsawpbkt.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2atmqlxoo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbctbymz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2blusfnlc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wyypcybx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2apibhhxe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2maniqjgm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxmlvca.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xstizkwv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yobmmjdq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgcudrw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbpwwkp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtwlunt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfegygw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pelqfokr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fedzhwio.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nocgiudb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtkwjjb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2suoymgbb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwgnkyq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2muelakgn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbcqsnt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etxtcksx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvajnju.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlobwww.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2advanttl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuzczjh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnnlqcw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpitgpag.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2anwrdaos.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skrcmatw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnutimc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2avhoygir.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbjyrnq.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfhzukp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ffazoxro.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wluirssd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvtcdxx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dneavtmb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2inlybbok.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdspbho.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xkefbznc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ittlsnrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vluqmyzj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lqscxjwi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brnjbdff.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxixemf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeuffaw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zyodfzfz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmvfjov.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gwknznoz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqtbutj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2sjeyjbwf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtmohau.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhmyslr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxjujck.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uubcuhrx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwypbmol.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nyicpzba.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpcqsgx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbjruiy.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2srwwehsp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcntlqs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyemuwd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfbmnxq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdugjqnr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2adsdjfhg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzycexqq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbgwvqh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfygtqi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2igecotpm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvowcvk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhenjste.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2txtcvqvf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rcezhbyo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlexoxgw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkwarcg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ankefuyr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbhankh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsditkp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ghesnywv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2utksrdfg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrahdok.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kewuhjau.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqjbdcd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhxlwmm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2agutxrwq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkliwra.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2swtjrhsx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgisolk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pucoexhl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xshwntoe.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bumckauv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2irwjsftz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqkhtis.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqayplue.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vggybuyk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyoffwpv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmgvqes.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnsxnnm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gubqdhbw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsgnrxf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjgwrlw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjqgism.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ptazpxyx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfhdvcc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2envzyxhl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2teykcwub.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwjshte.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oevabyfn.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqbybze.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjiydki.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwqohjw.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cujdaxvl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hoajxgbe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2geznfypk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2awryckco.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbcgmjw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uuexrnor.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dzppwobq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zukaymuo.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbvexvy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxvthrt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dccteqyk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaunrlz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dklzuwvm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjqugaq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2fjivbnfx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmismt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aymooluf.html


<!-- 参考信息 -->