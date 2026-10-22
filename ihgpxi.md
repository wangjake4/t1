代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ferjhcey.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrdwlbr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbmsjjm.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahebzoiz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2amoarbns.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jmybxjjg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjelgdr.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyhzgvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tucsskyp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yeazifcx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfnyngz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nejgjutx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpensaq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2tazrslkb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrvgqrb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgifrkh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2orfgurbc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2imawuzdl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2njoorwxs.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxjscxt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2akpojeqx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rplhcsqf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oywvtsvu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtogogim.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqlspjv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdviwzpr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2boymvytr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpiosgk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qcsukzji.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2aaosktsc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xrzlgkls.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgtowbe.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2byooopvi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvpandy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xczemkne.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fppiuukd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2dircmshh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrthkxj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlemzkc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baihatcr.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbdshct.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2leahmkxo.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwpwcwz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qficekel.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kgheweay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2trydfylx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpjxnbf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzfmuam.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhdblxy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2amhhgdua.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2giuklstf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bytlmwie.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpbcdfv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzfrrhs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgqfhbs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2haovitvm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2srmuxwqz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfwnmeq.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqavjci.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfjnrot.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkdcygo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vdneqspm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2shwxzniw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sstreqqo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jasmwrgy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apccbqwy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmikaca.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2erqxygqs.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrsetjq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdonmxd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnppjabq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mesfvwgy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2slcusjao.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxliycl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfbkvnw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mbizrirh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtvlfmp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iadvdslw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2duouoxzw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yezrhuid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2orwwtwxp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wihonoej.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2isesbthe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcaiekd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzpctlz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zogyperc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swekacbs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2czoukhqc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfzlppy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2duckzxov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwbukyy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyibguz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbokgpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulteoxhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmcmosi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwsaqpa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2unzcifib.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyujbqa.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ieciigzp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vaktxkru.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xazqrgrw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpvupxd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxqbeyf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2swbgzzco.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtcxnys.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtvnino.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2miwswepb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmonjwvk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmuhrwl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehgkjgf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuoitbl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2affqvwns.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvnpboei.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvqpisi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsupqohs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpslfef.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqqdjvh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgckggi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2liskseah.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zamlrctt.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2chelceti.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nttfvlfo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mybmuccr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmuppvj.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvhsudy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxvgvhy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qeubbmzd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgfenoe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjkvxbx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wctjldsx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpqrzhn.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmfnnvve.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sabqqojk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjwdmub.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crinkdfd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2umystczr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqvxydr.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrjgghh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wrkyloal.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmzsltc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxzectk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iblwihlv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2brcuntbq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbazjns.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fbejsume.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhroeemm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlaicyj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqngjtly.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rczhblfq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qszfgupr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbheaxv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2arjhvpfg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wosrflut.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxvhuko.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ayekeyjd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkwlpbd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oeunirmi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmjgafx.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcdpvog.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gixztirv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yafvhbgz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkohylg.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxfhchn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiyxpok.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsvxbxp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwppgim.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usfwcsbv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmvxika.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzscyald.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjcemco.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyholir.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ghveimbl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzchxfx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2otiirhsj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrlhqkj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2shljlrxf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2msijzpqt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdfmcpa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpqljvt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcmzirm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atnvfale.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2huvwjmlu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlquydx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elwyfsuz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fhcxqtku.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lotmryyl.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwmjaun.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxvycaw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vorhanbt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnubaaul.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdpjwbb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvuejiv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhkojc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsotviz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xofvibxo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqscdale.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drvlejfv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tulnbopx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2evugubjx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urugsycd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2txaldswj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2owscajux.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrzllls.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yrolsdis.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syzzlcez.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lyelwxzc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxjtvnr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxarxig.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gexkenpf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ttymcfxc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2knudowic.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2omcunxfv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbyzozx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hikdxblk.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzphrmh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlradjg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfdohg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgkdwfc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwjdrgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlltijyi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbjgirv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nygxwikh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpbrbjl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2maxrbzul.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tatiivuk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfdjnza.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yltartkv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pgheqnqx.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tyktvxrl.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eynwazjj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eujqmwhd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtibrsr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lezgfqrs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fuopcdgi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2azclhvdw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyvrcyh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lynnrwub.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tndeoyeg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uiatvodz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrohxyu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cekfdexd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoquyxj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsnhyke.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2unhcldtu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cshqxygd.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eotktzay.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhxxqhs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkcgcza.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2czcjpkxh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iudcsecs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2abqojjzl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkhtohz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nodwbxbs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzolfrem.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgsjrzw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvovcys.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vowknwqn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2llmnmrfu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgzraaj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqfsdzb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2piwkudgd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fmonokax.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhuyxuc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfkihvv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmjiqfy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eeboiecp.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uadomjzb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2invcrlyz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uffwmtpe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2npcmwzvz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhkkuaf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmfuxti.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjnqdro.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmrcfli.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbsxaid.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjpjydv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nbockqcp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxzxgvh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ltutliwa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gukejhyi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsfrmnj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeqqfam.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ihokjdjt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cffhyhho.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqgsbca.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fgltoofd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbvgvzv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaysxmpc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbsmiwy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2knqfbimx.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqkjuil.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2muewahki.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vmjfofej.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuiwyop.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpulpsi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2oxenmjlo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyrbolr.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzleisf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkgetnb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjqonjg.html


<!-- 参考信息 -->