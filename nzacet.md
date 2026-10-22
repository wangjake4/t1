代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwchjxoo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jyspeyig.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkxvdcw.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2okqbkjxs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2idnjymva.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwivuswz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uizaogcf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxcmqsm.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjjbdvd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yywutlhe.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mizycyaa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2agwlbvru.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wftvceft.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wcauwohl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxmhzxq.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnirkxd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnbpybg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lplrzaxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkzryrq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2juhjmhsh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwizdhhf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhupaof.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2evckjpga.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxozyqo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2godqhmmz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcysbni.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvneuiuq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrkqxwg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgakikuy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rezwyhlc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcglnfbd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qatwlrys.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxscuohc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wufylfji.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeagtje.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhgtttv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbwznxs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jnnvmrpn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkmoumk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxmetkh.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2szdhtmzp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kguoscdy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zwrubeio.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgehvva.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2epzaisls.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nntowhzb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cvudsvqd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjhrque.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsdojdj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfjafoc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2negujjru.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrppfld.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqbnlvg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2daooutip.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uksnwjqq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrozdzw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iltfekav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2suxylxsj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rxahfvnv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvczuesh.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdrtizn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmhkkaf.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2shateizx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzhvfgv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2miosfcbb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyndedmx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vasbrcwk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmafbzv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqromtg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2taqpiiam.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiluaei.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyrivzo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ngspldzd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unwlizld.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvlsqwu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2frlpuhrk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zynlpzot.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgeaxnv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iimkzigm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2idcurpph.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwhubzwm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2njljxjaz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqxdnhe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwnuhjp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eccaxjwh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2aidopzeb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2btnfdfsu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpopkgz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpuapamv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2botbetad.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sofqffyd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2omkegkrd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjidfme.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnwmush.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuseidjr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2whclteqw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2reormtpc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hmschyrd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mptelgmu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbdvinw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ususqsyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2paeyarhx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbijbzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvwzzpn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2irkivupy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlyljdw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agqxjnum.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yurvzxvi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qtpdofjw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aezffwfd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2strrzwoo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oipjjpgy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gaopccaa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvgnjgs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnpnqre.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvilkxd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoeuakf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrwrahl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2joaatmbe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyubnevv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaoefpl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhssgxk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jedivmph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjmqrku.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fbopdflk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2guuahzfm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2crsydoxt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyirljk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vqqvuesy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgvnipl.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tcykaoup.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlyrvnh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wrghioim.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwepbwlu.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwnovjc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmljmrf.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2neklqdsn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjepcbr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqyvyup.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qymomnwm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdkyllv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxwihgd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2beybvzuq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsaaxqq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgabhgb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdcittm.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqgbcwm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqklgcf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkiiyree.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoklywqe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwtmgea.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlpvaqz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwonmex.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsdgbgl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hohphbcu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tktqmqxl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tujlrycw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wycgahqa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhfpovj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpxefhd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dxynhwrd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcrclyq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkhnpng.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwdiqrnl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnmirxg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwebexrg.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgerqqu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhcqmug.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2moiyxtsq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2oatcazwi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2efidtxkm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrlqdwf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2oareynue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvznqbn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aygiqxak.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gniybubj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkenhxca.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uiibslqe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrarfbah.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhpchka.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qqurrgiw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdsxvwa.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxrqszw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2csoophyc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szdnhbpf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgkbxji.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjjethe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjciduey.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2owdfocig.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgssiow.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vajymmuu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xojzjhot.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdrzxww.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avlssnuj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2adwxtocz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieemfkmg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsluouh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuigskf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zixeejez.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydalwfha.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsdeuzx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elcwdefa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vubaxshp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lojxsbiw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nocburge.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bezbyckm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrcpjwm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2akioruhg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xqcbnoxq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrayprj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uimumofy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vmubxsed.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bblxewsq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmhtaks.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctethfed.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgiegzp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogglnpio.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oiymuszs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2munmhmow.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2edxvphgb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2omxfwgkb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lbypzixh.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2osehmivp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ejztdbir.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktlqfuz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzinwrdl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2glftccnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iayanuke.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aoodbujh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wdnlnoqx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qxytvbqh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oitpvrha.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2atpfuccx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnevshdi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yiheqbjz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hohufsxa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fohklnja.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxxbagi.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hpndoujy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kirojxga.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjilhkp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2stxymuzp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdklpxz.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2huojkltl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqfcrod.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2retdrain.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tropodto.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjtibss.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzgwhyq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhbyehb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2miogassz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttigsluf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgquugys.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnukgxsq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxdzkje.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuugdrf.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2icilgpdx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyugkeo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tujmkkol.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiwxnhp.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2atqxvvuk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhsqnww.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cmajtelc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wexfvjch.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bjicnpxj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2artszeou.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtwancr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2empsrxkl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwybvpc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vasaypxd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtbobtc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2riigqhro.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnsquwf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxajtdc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2clryzaec.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdzvtzs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkweyfv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aajytxcd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yndbdqfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqezmnz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbmlvyt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzabeak.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoedtxa.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tnudoxnw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqparhg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdumiur.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sevrfcko.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcvsbet.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqnkdja.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2newswimr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyccetb.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdiarfj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bconoyjg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaqwkth.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfopasy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2nakpgevl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgatnil.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehfmavm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjnuezv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivldctrh.html


<!-- 参考信息 -->