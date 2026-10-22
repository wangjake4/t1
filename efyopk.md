代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqggpxs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nifefgeh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2seraulrj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgxyjaz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzydnxxs.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rntixory.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhpbjas.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuqilrz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hylhgcsg.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2estnpniy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2geyzyhmp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2btsyetqd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxtdqmh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2idspmeiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbaolqm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qwplrshh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkprrtt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbaefpc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2brfusvab.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wksxojdb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvuqjvt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaflfib.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tviravbf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oculrujh.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmznqix.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2elgnqysl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjgrkjb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgmcosp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2psgpuwac.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyxewdy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2moztdqxf.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wzavjkhk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2anuypptl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tgflsfls.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2msvwahmo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqixaub.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxpydsf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svetowtc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wovbtzfw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbbnthb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nraotkuc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pspkqlsy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgllziw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smuiejpq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mppaqaus.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqerukcv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2debggrsg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkziafot.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyprvcs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuulyeg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqdjapb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bnawfpgj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2abjtmbvw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfmkdwn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vufurkco.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gixmfthz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvliwsz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jcalkxlf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxqidag.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjadywb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bpqxmevt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlncwhhv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pexznitx.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkecgkqx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjkcoxq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kevlsvxe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfjqbth.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akybkvio.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rdepjzje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnjqvax.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umkqjfck.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzykfame.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtrrawj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2crrfasir.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvsvaop.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxyzgnh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaamzia.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbtsvjf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpedeaq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2slhzrhei.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcatrxu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rybphdbq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoaokda.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsmnoby.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aednipbg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaiumdn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vyygnvlb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjxibip.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxogfumr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2evvuvkie.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfygezbe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2shqowfzq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnwqjqd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ownjhiao.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dozxnnlo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxepixn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2elbhluov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbnmxmd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhmqbkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxplnqj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfoogry.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjchedq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbqorrc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kegowngc.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxuvmym.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2miflteqk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2icrqlnrz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhfxqzh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2faqvmqxp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbpxtyv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2huxgybsm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvzbmbs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kliqgnvy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkzaubs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvlhuzb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofztenh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiditfb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbamtlbk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpxzvbo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qvntaxdx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpjexpq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzmywmu.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlxkxkv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2phfozmbl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmapzoc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2szaebnjt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyygfly.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhgmegl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcdpkle.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2puvteinh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2llvzuwyb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ylyzxnpt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyftldq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzukeoa.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2umlmguvd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhbhvlv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vdegofxv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyriydtc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kawiavtp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuxhbsn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2awnyqgxn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aijhoeth.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2snlukqar.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjwuyuo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpsyyue.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fygferlm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2acplhujh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itnwyosr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2htikcllv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lesyizrq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2htmrnzxg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxihkdml.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaxksav.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxnskwa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fithiiii.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsegmgm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wichyrcm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qweprwks.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqdsiix.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhwecom.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odjkeixm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdtdkks.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsobfra.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gppkfpna.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxbrhvu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2apnusnkj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqbgmdy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oedsorep.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfegyfx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hskircxy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaphplmx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2komztuhw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwbtfvu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpehodxd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hodjoixq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjvadll.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mviwhclw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlekccnf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2drijahpu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wiopafba.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfcucxm.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhterulc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzmkglo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbbubki.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nlupadsb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2djrpbbsi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfwavxj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiiwtwb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2duhwjsfc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elatimhf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfkhijc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbirdmpc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gzazaucs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eutuzzos.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nufkjbxb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgscvald.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ufywkgiv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwujoivd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxjrbanq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdufvir.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iccqjvtw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jprlgvtu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxrreez.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyumddd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pipivhae.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2twpjhjgi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2emgklcvn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axyiimou.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhydkgeq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqmnpie.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2aponbvip.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzdklus.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cysbkdrz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imdhaspo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfabatth.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbvshpw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2etjhobdb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbdxtmu.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubissydm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhtmzdo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sitpekjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kibpqyau.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuphzpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdhlnlq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvxmbco.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwcujkg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lmglcdge.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtksiha.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2heoalamg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqsihhzw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tifaofcp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tixvewhb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjtdnoo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdgdkyoz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2liwlkhlk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nujockku.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2csdxbsvp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvwatbz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpqzjbd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2siyzktja.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2whbnkbsh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2phtqphxl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvkrfev.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2moxawscg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pffhqasx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrqndql.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2svbvuxqw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2krhiakyb.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2spkujiaf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pusohqnf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwksgunn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aijndnew.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jmovlobx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfvhlap.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvbhwxs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuqwynox.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwlsohx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsvwokq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vyidkrnv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xunxrbrq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vqljhhoc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcotnyz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtwyyvi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfwnyxc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lknfafij.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdxrtgp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lairhmxr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2giovlprf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqxttbz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2uicuqsyq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2baswfqaw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtpbxbu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2idiqpasy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2sznxvywi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lhspxgjc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2scgmhwhb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtigjxl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tykcjpla.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2epdhdhfg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2crrzeqen.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyxkxqt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2qwejoyoj.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aolxnpim.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmfguyt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrwrpds.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrdttrw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbtzmdx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnwnywb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnycxxn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcsgqnu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2klcnyprd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiowkygw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2eifihaih.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbgsisw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsdgfyq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcogjtqs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuueyow.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xouxdabu.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nansanju.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgpafgh.html


<!-- 参考信息 -->