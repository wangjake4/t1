代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxjpqqc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhkdvhp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlfkhsb.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxyxthq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvifoto.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuaczti.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgjeock.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbxitth.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wewgjkjx.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkoyaaq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuinmtac.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoszbby.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2trcsgysg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpwtvsh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2krrashjk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnlpwas.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2clifegkq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgikalpm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmchccl.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoucpxw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2itrgygbd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmlqdab.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2reezfdam.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjtcawz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrfndps.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrvuduo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqowbubn.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqolucgm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2umjregtj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuiyktl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzonncwc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgkcjeu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhjtcew.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2whafvhyg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjiqbnh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nsannvze.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvvafjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgkqdej.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mnggajpl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2smwfvqlg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jegnahcg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvybsye.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyqlcar.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vruhwanc.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsgzypw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bktppbkz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnahlep.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgxgonc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ebebbrqc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwmomyg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvsszcx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vkaubbog.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlxmyzd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ibracrdp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeowjog.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxgpnghc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2phkpitgo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuorlhy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awvdudwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tokipdng.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rjslcsjv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhitkvjb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2enpildhk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cljtiqwh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2czcuaurj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lgljmstt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oqemehdn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kteroxpx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vugrmsxo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhtvcxe.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fakhnozl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbqgzgh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtdzfcg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zebwvqfh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2glykuoqz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbetmlo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmziqoaz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yewvmseo.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjhvbyq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pywmuofm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdpdgts.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gerfyvtz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvjfglo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2baglfdil.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2abpwdmbt.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2djwpbwea.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oedkpset.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgovdev.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irfeqpvl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftehqkdp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cspyliff.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dokgwkkm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ginuvbqu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xmemhero.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaophnc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yubakkpu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2intnclih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdlyary.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdiodxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kosltxal.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pkudfckl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrynlsf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjjggzi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zmraslex.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uzedinba.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nphaohvp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbqxzpq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgnycdw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdhrrqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ebhngpev.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpmddnu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cphcpspi.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hvikymye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvxblxn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhrfyzk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbmdudt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnunwluj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsjvpsd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eekfsznd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjksntre.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvkuqgb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkpywbf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nocsotxf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjesfjcz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lumpdwlh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtxvcvb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzrpaqf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqckrzc.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2awctbzjv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2offrqunw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvzkbbf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlguppn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yyclyhhd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlppsoo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnofyqo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2voflgmpd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2plbuwerx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaptnxkx.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ognacqcq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zanrccbd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajralygg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfepdmmd.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gozolvyq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ponndwdv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdwhxxd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcoduna.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2itxszrks.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbgttuk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzdbvym.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kseoqifs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xveerfta.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpegeey.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlewdfa.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzykrlq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2crpynuch.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrkyaoc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlrsiyz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvucbfzd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqislla.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuywmki.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lufktfyi.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydttsdyl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvmltrw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwhwvez.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iiblctei.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2frtshtyr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gctrbbqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2brzxredb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiyssfx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ramegkxy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sngtflik.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2diqttqjr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pshcdnkv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpvtlpt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2myrwwsap.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2imakyxua.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2orexlbkv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mahekzlc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tefrnbjo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xvauzglo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpgtzxn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoppvex.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2biwobwfx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbpprjx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2esnlgkvg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmqgock.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2huhmrtuq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcrxdrt.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgxzdxw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syawhjui.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjrshfq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbeyrph.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tsywtnps.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auppfjay.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fctaahtw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkiypekv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfsspph.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmufpmfv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wqowjiss.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ceehcozp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cujnncwr.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pughzpun.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzshsgq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2undolwzg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eowajinz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnswadt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zohaujbk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wddecjga.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmkamrf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzwynko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsrjfaw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rznnqtkd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjkrges.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlapbxa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgvtzro.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxcwdmt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hadypjkx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcaiacn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtjiwav.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpboswu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2codmpxhd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jykvsnwc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvatjmva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdhgksp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvccjdk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiikrap.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrdilcd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsltcpd.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2isdokxxq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdiiqvmq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2pkblsfjx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gutpofza.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kamnthdw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqxfecw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pnywsmum.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2llyugwfu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpdodio.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnrgdhs.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuovygq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjskqgc.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2oblrnfhz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ockpnqsh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aoutdnez.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoqptgj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tzipfmwv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkwfxib.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuocaei.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wocbyaqo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orzyatjm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2arqgkxfy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yytryomc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyezvut.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zppaykfk.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjwyapk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ugehvhhv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qboeqdee.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2azlvtsbm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwarywjb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oxratmpn.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdqtbsg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2imfkpzfa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2byxzikhy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wodvuhmf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdigtjj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxxbzap.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hacnhhwt.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmvykwp.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuzngcd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvjpftq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2jjplvggm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvodoxe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmecljh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gunvhqam.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2icpyduao.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyiomls.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfuwjvl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2fljndcdj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mzncqvox.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jgafvviw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzswtpg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgzrfbk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2tiswwxmb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2unrqcion.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aawwvsnp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcoydju.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tolfanox.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmeevvo.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2utjktjpu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iwtialcy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaymlkwc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2expdiqkp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2aezhmrdw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdowjdeo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tapieecq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vhpaonhv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaqsfnm.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpggtbg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2piiefzfc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmrtamy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2asmbjokq.html


<!-- 参考信息 -->