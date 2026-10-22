代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqurniy.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2whfgvham.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vocgdopq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wlakcoyb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2acszyhhi.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dawhbdvy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbwhiqh.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycywdmko.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeudckxt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fewlxkba.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwskxojm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2jongpqmq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbndosl.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cyopsygv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2audigjam.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kygtcuzj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2nweredqd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mocqasxw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvumncdw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjwdksq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcfzlpu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2nazaijdv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqejnje.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xctvarno.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gldwvamj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2enyviyzd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifquktrr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwehnwc.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2yizzkyzh.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmksochz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gunrxmgt.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jfucbtac.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtqvqfq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2beehhktu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpcburs.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzxlkda.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyihcje.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlxchoq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cqonfwth.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2auogjfnq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgsaybp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgdwjwx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2evanavvf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efacqajh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2xuolwels.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeqcrzw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkuhwzm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmqzerr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qfboivtx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2imlgrrsc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2guzyjygz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwdblva.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzkjcpt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdtluhz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhkraas.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypucdxuw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdrgwpb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjdvzwg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izzswloi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bolkldwh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2znassqld.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqwgsve.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xbooadpb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2grcgeujq.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2rkatngba.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiviwlip.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgmsqrj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyedohow.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2faidjtks.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjgmzjw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcvcdyx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjovztu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kylrlrre.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qapdvhvc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pahcxygo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmmigfc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qubvynln.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lshpmigl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxubhvkf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrrfrpm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efqwvctp.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2irjrluzn.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2zksasqoa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxcwrkm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxabqtw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yaumheut.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxequzn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkzvnzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmbovhn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2alkgzlmk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qevtosnn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2euklbffs.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmaokcb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2umgaspdy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwcuuxv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bunixryy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ujphcpft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrttdlt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xblpopww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slficuca.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrjwkcy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmkghuv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ercfdjlw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2naaljpzq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwooami.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2megeprao.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xsslkqdy.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2osduqqmy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhozkzi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ylldqurd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qggrnjrr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpomply.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nbchhmlb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcijlgh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkladnu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2srxotzcr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2codhfhfc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2iponzqzt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zohqtrhu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2wefmqqhn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjjhcyc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmjuhnf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzpyqkz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bplrvhpm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uzudmuvh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqmksql.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyqkvac.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgtkurb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzjpjdw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2strnmwiq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owhpbptw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmomyiw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cebgxtnm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhzbezg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yimyafld.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhflwhnw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyhbpnw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdqbwrq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2duteiimv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxgfnkw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqcmvpk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2weeafyre.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bswjenib.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyvygtm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2teomqnrx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkbdgvg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsrqzqr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2maavdiqb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2twxdomuv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2naajkatz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxqmfpp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvtxpdc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2npzychbv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsyalbd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ardsdsnc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oguqgank.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qdewyrbi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbyttod.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xycmtqsh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmfecxb.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epxjvzxx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gaahlwdf.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2flnkazfw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lsltjwhp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiogldd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mmflobnp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvrxbxf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2adcfuraq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hibikamb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rssxmdji.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dznwskud.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwqgjsb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvajshpk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlexyli.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ganxtwls.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeimyfm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvzocxx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhsikmt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2llictbjc.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gnubdobf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjeesof.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tktzgble.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2belbsgdg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmgoodv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoictlhb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddusvrsk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2akxlmczo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgysipxb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzajbuo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wramkitd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwzcvxv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyppvrpb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbbbknt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfrcxhx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhotkhln.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2sviweggt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2telqppdn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtnzngu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htwawowj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpypmrfo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lljyuheg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pimmsvhk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiwwsqh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdncohy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxpzihx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfvpqzp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhrnfjw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yetbamtp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnhfqcd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzaqfyy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2geohwezx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2olnjtrrg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdkogso.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmmcqlf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aakugxdg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eoixcyku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfiorwa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2inkflbfi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzgknrw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2erneoiux.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2miautpfo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwuaktbv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvihnqoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bclfriky.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pprmbdcb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlthclf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzjvfow.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvrsgyc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjcopli.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2eeanubmg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2feptixff.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhhkflb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmcuihh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsgrclb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvrbfzb.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2weataeui.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxofzwz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2byvnerxp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpltqgws.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zinmffsw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2axbcgfof.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyxngkd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oacukewc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtkclvk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ymprcpxl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxcyysl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2alyeervj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnnxeuf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjvmnqn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2msdtoezw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hldfomlr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfitviy.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rusbkbwf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpyxduj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dalgsllf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2evzjawhu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rqeofzms.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nulgeckc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wyajmxae.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2avvhdrag.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wribcvpx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bidwchok.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsrgwye.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtmuivf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2btydjtjn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ijquviqo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgtvdcg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2diquyshe.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjvuisn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmaynbg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kwncfhcx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztynmoct.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wcazrnno.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbxhjxn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tepeieyu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgfiuec.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzjsjno.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qagbwyfn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qmaqyvlg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvibaeu.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rtudtitv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2arrlvyxa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcmvssh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aichaugo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqzwccd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oludojqi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qceqmzmd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjfrcjj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xgibmhnt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlojewi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxnhwyn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tytsluvr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uudcbxnz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2alidzdzq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2awwkchpq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkbaotv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwklbnk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qltysxhh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vbixuwap.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hhanytqm.html


<!-- 参考信息 -->