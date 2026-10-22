代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqtgtij.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrvpxdw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2klxhgnjf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bakywqsx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfcrkdc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojanqcyg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnobaqw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hymmbryr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtpwqsj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kzanxmhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2qndfxqbu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2idxuqeyf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uortwtzf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2murdomhw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2izklrtli.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmvletk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbopjxyc.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djmzjnqd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgsxmrv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxxroyd.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2afosdeot.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wayhlrjk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeqouyx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pwduylmh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxynnvzb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhrpxch.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2srpuehkw.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqljlgg.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2czxfawsk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yolqgsyx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2utvwfurn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hzswvpyr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeoqvuy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cegebosj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nveywumf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rotlpufn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfifinx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwximwc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vatmzbrx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kywxfeqi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2yatomyiy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyztqttu.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiyuiiw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwraqzpv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2eivsnabo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhyctiqa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2otcpbxxe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtbbboe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqlalbz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2taghzfir.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2klqphixk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxygojz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ultvseji.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzhsjpr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqikbri.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2llvpuzbg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cndyihda.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xggsvggd.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgzqszc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pczswtnh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdwveyv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nuppqurh.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhdohnr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btbonnuw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmmuewc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrmuwjk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bftnqnrv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2yitxmgkq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgdbhhf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzzjliq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwulcbs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lptpmpjb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwnnxyt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dljmpkcs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xiodejhr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2koxjzbxv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qizqeeib.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2uofnozzy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgeiahp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uulndubi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcyciai.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxcmnvw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2irjnkmkx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xcknzprn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzronkyq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cufteaiz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfwfrtz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kokvwrzd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwqmybr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sdioygdt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhzdcux.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhatmzb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mznvnakf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hetrjtvq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lymbyowz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcahemry.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uuypltwz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2flgzhufw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvrrjcl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlngvrc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdjukbq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgsdgmw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsypdzr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2apqvbxsd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wbioyikv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kcyoonoo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdgpdeg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wohediks.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lsyuhdae.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxewbowu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hcooclpe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhnqrnz.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2btkmzklh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wupyvugo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aklcspuf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2mksbxyho.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2urphpttm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbncifw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2klhkohzh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dycyysci.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqnufmk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfywuyhf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ojullsyg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmhjqgx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gcctkevv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqiowvim.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gonlpibz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kftogxbc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrkkxsn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfgmtbc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2juceqnfd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwjuypq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jfafbshp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuyyvci.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuncpdx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbnsaxsx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yakqqiob.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2erhqtlrg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgigmlw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oqzucfwr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ewoqvrgp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyseqivs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgecpoz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbeykcgp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2xtpuwgii.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2noxkuldt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsgzvmq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2twzcmttd.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcuwuwu.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pevdjseb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpgbfyh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmulhra.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kodpgkaz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eutgigbz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjibgxw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpkomyh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vpylfioo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2beoajdnq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2igpnhggv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yratlbyy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rucsetmk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qewfcpcu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2krhlbarf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2zpiwqkwv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ualqiqet.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdlqlpg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smtomuzi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pavcxijv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mschjyqv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2knmguyly.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwcjtsx.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwnnojg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgimcplu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqkeoxb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2wadigtat.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ydblyazc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbegeyr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqykwggo.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhvfhnk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcibtso.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aolbkwes.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxqffdz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2edudwqtk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtcutll.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apetwokz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfelhty.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2quxhuiqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhowwnp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfurizh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvotuisk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwshxjgr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwwyqbq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghejdszl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxtggcu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfxamdm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwgqypu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxccfknd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcugavui.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkosjac.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfwkirg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxcfxyu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yygltaks.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyniizv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rufseobl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffasvysl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2voltfbzc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxfvmto.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2oncwcfoe.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvoignr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2erfloqwi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sthkbisq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwchniy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ybylziki.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xvczzddc.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ashtcmfx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyzdnyw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfkvlox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egzvnnlo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vdszphxe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgwglye.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fsekadrb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2prkhxion.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dtptxlqq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2juaqgsur.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uywgcbzu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmlucqy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzrsnrk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zqapkqkq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2haiqhcog.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eifguqoz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzjxjii.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tenpsuwr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hrevobpp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2niwrofkg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyklhjz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2emumyxtj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pbypyygj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxtlthr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxugqyz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqruapw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qtggtloi.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uorazzwp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcrrtatm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2erowbgna.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzyfxgh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxrucsx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqndvkw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzalvfmv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hkknwrbh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaszpak.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2utcrynjx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyonwso.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ltztgwph.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2digyvqlt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kayndqlg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrleidzh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgjozxe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlzzigw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2trvzvexo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xphyrohl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmvohla.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mxexejse.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2itqodryq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpnakck.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmogiiwi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dmelhmom.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fbundkny.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddgwmrr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2clwofnxb.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ualrkurw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuqgosx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhylnvvu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2zzagrqcv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fraufacy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfjgheo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ompafehl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mpenziuq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bvokolal.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkxgxjr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuypgto.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuzzjgn.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmiuldg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2khkvucae.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2azcjpzuu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxqjkkp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwntscwh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zilrfidu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2txkfoirm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysobpxbx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgpvlwqg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwjiewg.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2etrfxntr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzeulis.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jwztacji.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxomufc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdaftxy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2phhrplli.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ublhucjq.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrbktjl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfcooph.html


<!-- 参考信息 -->