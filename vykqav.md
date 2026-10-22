代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxpbmgh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ktzzbvsw.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2puqrubeg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nheggbye.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hckhnvtq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2owkzwobg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgphwae.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjjrdbo.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdhckiu.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zogmyedk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kocrqoxx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyhbqph.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbbofot.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oqlmbvjz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2folltzhq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eliqbynz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pysxmyag.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxetvvie.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwienjm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxxgweb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwukoir.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mdnffeqr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wosirnkh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2edpiepkg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dakcxbqf.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2umoladpa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtxcjou.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlthfzb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtfdgpk.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gowmpesy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkaqwhj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2akndneri.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkhengn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rcixnbob.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoexsgj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2taumjqxf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zwynefdn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awbmkejk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkzkwia.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ueknlamm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjfbmws.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkufzsuh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hlnxcxad.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnfebkj.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rscavnap.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqivtfay.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dsylxtfl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyllzrv.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmztsca.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2odtpwapy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpzcovb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqbraav.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxjlfya.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gaanamoi.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2atliurxy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2opzjmqco.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsreskvd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjcoaar.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zazkposr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkqdumg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kwctlztm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2onhirefp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uujozbop.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgapvgqw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxexzvg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrugbgnm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiwtijy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sarizbef.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hnznisqq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjfxsst.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmyexks.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivimklwv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zegvvtyi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etnhmbsp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkbqwvk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxtlcfl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbktqxgy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbrfgvn.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglsnlz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdffsyf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jraqmddz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wodfqqys.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gulbxlmw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzrcjac.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuxmsxq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvwjuti.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoexvpd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2eggfdmvg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqigieoz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2difxfgjk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yspzezqn.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kkffqysq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfigcplz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nctykjyp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2mxianoug.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjucban.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2btnpfwxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzhdvyi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdvdmqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsmjwih.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sycmneqm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2akcpvahw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmqceeg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2aesipxuk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rubbcejc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkilmlve.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtojaax.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqqtlik.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmfsjgm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dbalewqn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwfvzpn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqklquk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjlrhsl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuibkrt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ljsoeofy.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdrkacs.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ethycgqa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnzqnkx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swpfrfij.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzyvzaz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zboxenzz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuppbtka.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mofllmlp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dshgzpyu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zbymsozy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwpaeyp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hldfbijw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxblfbcq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbxaaoz.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqbrctx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpuqdnd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mojywbfn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejixejzg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkavrpt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zofnvxpq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jeouwhbo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2llsyakde.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdrslak.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2siadjqvh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyadscxo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdyjotz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlluxnnc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2aikgxcti.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yhieoomi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wttgzlad.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjljcezx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2byrzleti.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpgpjgf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcclbuw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgkbxjm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcontjhf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxpowjm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bevaaedz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pabphawa.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlbwenv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzwqwnf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wfeiukkz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbcnejo.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2nxorjxjn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxxhezc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kstzdczz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbznzvi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2grdiwfua.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oglqqkbq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsxiaeb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxsdrmc.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vohertff.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbzpgyj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eftiyifp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzwybfz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnzrhts.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dqinzhea.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxeyngv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzxjrxm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qdamlvro.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yccednsx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkehjcr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjvgsyr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaebwwm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wuehtwcx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2myxxrrrr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgjsljn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wphpmljn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dubacufm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyiyepg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rknekswh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkdwkfw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxqhelo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sighewvd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhnpfxv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2egwaihrg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvmjszp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaqmwhg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyaqeog.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfghgh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2josbdwlk.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqurmwo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vljiqyya.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2msakogpo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2teftltvf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxrtiys.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcixnsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtiwgxu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npajhegy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fztjibms.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iiaswczt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmmvnse.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyfkpjz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2goshxshj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2akccgbgp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2enyakark.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2obnfkzee.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hitjyqgz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qtztyabl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbipjep.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wzovocnl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wokipgtm.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ynrlyijf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmhqlu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zeocmsad.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pucxgiwq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amlmrmvj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzooote.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgetdrn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtlbgqd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfxcrkx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ixemwysk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oloodvmx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2euhlkntv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdfnxqp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eugnjbfe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrrtmrh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2qudmrjyz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbslyxl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2iatsvvcc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmnporc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsmhmgn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2puyjsuvf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vgovazis.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynptgiyu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2utaqxhvp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhilgfn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2buylgggj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjtvgdp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwkplnr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2thacwwgt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewktbers.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vopmlagl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfygsnne.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zertqhkt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gizkjeuk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iodwfwas.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhrhkxr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpisjewp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2soilyylj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2fevaqgdb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2eyttdhau.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzgocwj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lycuyxvr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbmnlxi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwwozju.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvgvjpc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dntywnvc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2huggqrgq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2mprichov.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2oieypfjn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2chsffawy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjnfeqr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cccdnmoz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xilexzcr.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2synkykvb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2irrxbcad.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvqhmhw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vknknrgi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2benmspha.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2apyzvdev.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2scpxsmcp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2woztngep.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxlzihc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxiycwf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2blduuuil.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmimkil.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2twvbobsr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkxauux.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yxaxjttv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaktmzr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sthwmqtj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfcajdr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mhusrcyt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wblravsi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfanejj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpqzuxv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2imclznqq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmdthfo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkttffs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzhultt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pfabsefl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdmowjm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mxitaqme.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xltnfosj.html


<!-- 参考信息 -->