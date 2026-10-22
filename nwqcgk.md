代发 wailian999

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2muxtdofp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vojsadfo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbojdyaf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuzmffa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvcmvlt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaravnd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eabtesfh.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2godoqale.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwpepbm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2agezdviu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiulpsds.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nctwbvkl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2lksttodd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2maicuprt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2znaxqobk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqdlavn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2shsnbgfy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjabzln.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2symqrztf.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2aldltvly.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2neoopgml.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdrrfer.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztasxchb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2urraxslu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2erromadb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2axkjflcm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2orahqlwr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxbmocq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wwcvhibl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqphczw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2gkoadujp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yjidtufi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zsagtidz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqolzzi.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qksfeecs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwgawwf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2klzbyclb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncmjhpdv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dodvutez.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdisyrws.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mydcvgfu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyngzwzp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2cbntikku.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aboxqbzr.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2nhixffrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ladagwur.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkrbbsd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sstenyyx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2onpldkxj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2frgnxlcl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwpigkv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrekvhb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvaedsp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzjqvda.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zinupmzc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuigayw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jkucbwcs.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfapuqg.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgaxlqa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjpdwof.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxxgcny.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ishyevcf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqrkcbz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ximopvoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2adeqlvpq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fndkouag.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwuqfkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrudgeho.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolxbrlm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uibrsdvx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2evvscjsz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuskpip.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcvjimi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvwvxdk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mibfsdhy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrznunj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhgluys.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hinxondu.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eurtmlgt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwfufmg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uogesrwu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tagqvsvb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kafaxeap.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlfcsnm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2veokqvdk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqutiol.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eikhtdek.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2agfvbfyj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjcteai.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fleeouxv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgiaecww.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlopzwk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cysudnpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfxqhpa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzonoawt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqagxji.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eudvfzwr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgvhukec.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oukkavgd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlfzmkt.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2byjjprtw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcvqlck.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vprexjss.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpoqmcnx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cccoqjom.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrfwzvu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xvthbded.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ernyuhsn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rzagespv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlmunzy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrblbsc.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjycfaad.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmhapdhs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzrbgpf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxwcaba.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuqhdgv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2baspsupq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnlvtua.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ievbfhmn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehweobcp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2helomjtb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfajvgn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2szmjogwy.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpprypp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgbiuak.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzexeeew.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeswobb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkpbggu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2thahexuv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gezyiwbf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlytmcul.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2havjgffu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgmbvlw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2brsetvim.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2whohbfec.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2knpanpuw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqxxoyp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcawdul.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkgczof.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqcaftq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyhjbed.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcalhvfx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzovfaa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdurbri.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkptefd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nanbmwyj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdxkwwi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rykbpzqu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2efewkkkz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aygafxde.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlymndi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2aofnkmsx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iilsptfy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxipnie.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjiypfu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbusnfm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpwtrca.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiriyxp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znebayhm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2djwbuler.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwapvha.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxqcnir.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqzwjzd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uywetttj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpzrple.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2krnczhmo.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgasseur.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxohbynq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkslfln.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nxycckwz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2moipmbdz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpqbazu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ielhxlmk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpksygdc.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dumuuvpu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoofwex.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrkqrwx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfhxkit.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2azlflcya.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdzhgpl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2unxcsyio.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkjzmdi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2awtmppir.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfiuplx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvzyfwi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kswknqbj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lneruwel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zpouubiu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqvmhcg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnywefl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfwjsup.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2veojvaoj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wshrxrvs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djomxrpw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaawazq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoicsgf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bojvrmym.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eeeyotzd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pihtnydh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jyypqmmt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tznoimsw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcyakzd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtycucf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnvivhw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkoknbgx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dthiglsp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeucyszt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ketiifzo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzglvpgx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxeymwr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnkamed.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwalfbv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwawawb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2csxtayjf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwneuliy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdefvha.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoytbgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iatdacmg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrloxem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbhyuoj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgrokig.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dagvwuzz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ciebwirz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thhnepeo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkipgcf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hylcwryw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiuzdis.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqjkthy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eowlyrrb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xclgoarh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzgimum.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncupqmjq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpymirn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzclsop.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrugynfv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmennip.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mpobjycb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlxrlap.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsjiuid.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvupzhy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zysozzzg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebreeqkn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzfhmjq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoiihfh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgupyyjf.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhgwwkj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vibuxgpw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrmsqrp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkdrvfj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2diasenvr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yancsxcj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdsujhg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwrnnyw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhogrdgy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dtiihsqb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oczivhzx.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2avrnkvzl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oesbdszk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjpdnra.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2phttmfil.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2conrdswk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjnmvti.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2belxyxdi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2telagkme.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqzrssg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoclrds.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2scaorctw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnguwgau.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbuzsnd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2bndqirbv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fturripg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzubeyxm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2psclelvx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qpguoavq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnvxgrw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kooxczzh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrzmgmq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pvktdlce.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuqrcio.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vagygvmo.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rnivxbef.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jqklpnhg.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkrijzi.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vwocobns.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeggmxr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcqkryb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmpmktg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxstayza.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkfkxxl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhgcjdz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ormsnxlx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fehfjgfc.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hhllxutv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2piubbymg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwunik.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kjovosdq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhtyfjd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ephgzimd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qjoionwh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqymsfzw.html


<!-- 参考信息 -->