代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2angicwpb.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvfeaeo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmvmuiy.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nperxdhc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiedoquo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfmllas.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uodvbknh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2apoiriah.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lisjubuz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgxcntl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkexlsh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qwubhssc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2mondwzoq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwewuoia.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2udczajlv.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2enpyiwyw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2edwaceet.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzwrolj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2staznvhb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2swxzfotg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2howfewgy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrovknz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmftbnsw.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ersmbvzx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnadktpg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjszeuic.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2otnueiqk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fpicjhdv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rpazsbuk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2usptbldc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvhkivw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrntvpd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpaaopt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwydddje.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fssvgosy.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzhtatf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzsyrvr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgqtbvq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2znesnlhu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjukqep.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyhbzef.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomvdrnh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2opwjettt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgpzqmu.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gllskovx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fubxgujj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuydtez.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzkrrwa.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2upcmerzf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2irvucdej.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqmvkfq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2oskulunc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjeithoc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2urqlieds.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axljdvhu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaictuh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhvkadj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqfslli.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxddtrw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csdpziws.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlrhltr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmjpylz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iviecqks.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrlsibk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxzrrbs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaoxbxc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2afcatwlc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2iudhznyw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioboawwe.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lobqbwjo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfcflho.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwzctli.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhfxsic.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crybjlyc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbovhel.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fupycovu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwmcsrw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hemrcmbi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwbjeng.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fppcuyhp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsygqxbx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2izewgbrf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrgripf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaihrhi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sznlwuvl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kxopbuqx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejazkrgq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqteukh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjupvmna.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2isrzvgsv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhigatm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mytkbfsc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2njrgpbft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzigbvdr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynpfvuas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcmnbbl.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvseayv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2azdzrocb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdbdyzzk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkargbs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uofsusvs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydaqlzne.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfhzkit.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pzknrnkp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ytabecum.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fincsqav.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dioobqri.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sevmcaxp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2thresynd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cejtlbqz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iamcibmv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnxuxng.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbozrdi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wokqmoqu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjihplwe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdwkjdc.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kydlsggg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2msndbexq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lshsrzha.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsazdut.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wyazvrpi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vapzhmbf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvvipfe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyaprwaw.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzcrdax.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2evglflxt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2digdvnnz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbvxhdn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fixsolze.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dicwimab.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wefvcfok.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkbcppv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xdobplrw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2owuhajja.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2odwukbkr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgcxzqq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bzctswwu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvwtkjs.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ddndyaai.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzvxqyz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdemfuu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iahyfavm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfvkzos.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oobrtold.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eivuytgi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmlqhyi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpopcmr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikfwrrz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2weqpucum.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazlhict.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2laicuzep.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgwiyov.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iscpbmpk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwogida.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yyokspej.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmthjuc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqxgllg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nfniosbj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizvyyj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jgaowhzq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmxczah.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oojxabmc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcvievo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwacfgx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkaurgrk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpsyuww.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dotdzqux.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2numqnhhx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mlptlpkq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lslpzgka.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mutvpdlv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2btwqicmw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eheykqpi.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2daijranl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxyzuds.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwewmeo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2andyvvqi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjhyxrp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkljaqx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rolabwlt.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlfpkaa.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wocbgbii.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsszplak.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skltbyyc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrgthhi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvamyuam.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvbxqaj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwbkgoh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2enmllalp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elhontrw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2knoqgsgq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2copxjtfv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dkggzjtq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atcbfqvw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcyoals.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmthzhz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktrkvnq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxmljxc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2odhwjono.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdtgrxc.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2awdsjvxd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaliocx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpybtuu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bycenfyh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnlxisb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iazipbzt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbqlupb.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2puzevthf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bepnlala.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmaheju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjqjtpu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzsteqz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eywxmbit.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2etgtrtek.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkyyfnbb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qhqdtbyf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rocqikce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmkyebh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyukazj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxtlmbf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2swvkttaw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hncriddm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2axgbuprp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiulxku.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uevrtstr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaehrjyy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2inhxgztr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oeidqmya.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2cumzickh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2twyawaro.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqkqnkv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2avagafhg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqvdpqc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpltwzr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaovpep.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnozsvb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2cunsztun.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdvgmdk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzmczgb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvxoqtm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2luwpbhjz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsyfepv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2usnvdqld.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2raimmhmz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbnbkro.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ernowogy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2myjtenhf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2abhfbshc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dsicshlw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2durndyll.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2itqkptzy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgpelxd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuzdnkt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kghjmsgi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2diwwiiio.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fehuzdgj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtrzpyc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jisyzkwc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmeobvx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhujbly.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwscmtbn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xkchacaa.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpfwlgo.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbpecqz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfgodqr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2duzijntg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lmoehzdo.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnkhizw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtqbvuv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsphjro.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2iknkjuii.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2spdqqvwz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrwlltp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnuggiu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nkkiwhgd.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2djqjlobm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyjhiiw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwwwwns.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfwbkdp.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcadlkp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwqughx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfdkadn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2suqmpumt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvwcvnq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jonvfisw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrdwgea.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2peidhbmu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkyjiwg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvrsthss.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihthrkag.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcttbyl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrjnjxk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsmhcoi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2loubopyq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gztrhoou.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pematout.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iysrapga.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfuztil.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwqwlxb.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ururgbih.html


<!-- 参考信息 -->