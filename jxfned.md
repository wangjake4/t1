代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qelwbked.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwjgwvf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wktrrhcj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmnowtl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kvprmtkh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjtfkq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iziluvgo.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfprisi.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvibflzy.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfviwsky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2uieyfbxl.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2owyagsbi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzbiuvc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcluszf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgweoyb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2eoajafyh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytimkvtt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzcclsg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jncggejj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ikiohpto.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrohcpl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqctltkv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaujmru.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2woorwwel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2aikwmkfe.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhdtbsh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2epjwqqgr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iegjlrlk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oodvrfbb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpkflug.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeegsmm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2otjzpinx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2telqinuy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxincwg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfgudog.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qsprtpvc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2djrikuzy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2otqwczeg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwjmtez.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2plojlvyd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdxqkuu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpogsuih.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oddunpbf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xovcvlpg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvfpcdp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrkvgap.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmeabwi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhupirkv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcntekz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbebdcik.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbtpbra.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhmarxy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xqufhiyx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvoircy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cifkitsy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrillcoc.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2otmwitgg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2aqalvoem.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwhzrdo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmemtqhp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrikocyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvhillc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyiiabkf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kpfbnikq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2extyolci.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzehfi.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hdojvbpu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afovvqau.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2amqjqhug.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2njunedby.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2imahbnre.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzejozor.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcogqbyn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbkvaxj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bfurqqoe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxrmguk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gaijargq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgvaepu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wukcbidr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzmlyzk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkakgiyn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzyldska.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2msqtbtjp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2trkhwwcq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkajlogo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2talfqklv.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2biolkyxw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzpfocf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxzvvk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrcjels.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxaplpd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjpbjkx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcsgxfq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mesqreul.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhtfnfu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fszfzilu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2giwsyveg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzmmmrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2aturkpzl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fdghnrlt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxeicjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ilytfzhx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoajcvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfmauok.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tspxkagr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrepmzbp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qofpdtyr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmwfpiy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oprmmfdn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmojbsca.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrkjvda.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeuiwdw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2myzrlawx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iijxeijf.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xrxhbhzs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nodvqycn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxncsoqt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftdgbqs.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2exkkrhfx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2etcipjug.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsasdkp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vfigprek.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfxluxi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2iemngdmy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdzapri.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjflyvpm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vegrazad.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2droramfc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2tzuwvqfx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2besifkir.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwdoapu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgsioln.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrimncr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ualpjojp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeohwiv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdznagz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2czaditmj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpglepn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmndakco.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbwujn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yckpzlgy.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnrpefj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtjidt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zthnpgxt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uojaildx.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxodjuk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hqamlhyq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2flvuggqg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bmekgkyh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcozpnk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiqdrkj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssradtyf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqyggnw.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhsakcn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2semlgqnp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zthapmjz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdrivna.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhtpiy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtwklui.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbzmcfx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpvxzka.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eprhpmyw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dmprsmkn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswadxvn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yxuvnosj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcpzgpu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sckodkev.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrdxiji.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyuyotb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2eiceqfhs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdridibu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eonfxaur.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2drjwikca.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzfcajt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2elvyjssv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jdivmbyp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkinjco.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmvdirz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2famqquhu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwcutxt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xmedvjek.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2relrwjoi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qbtehmte.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpxksnr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipppqiwe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xllwyzfl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbamlmtk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ettjyfab.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuzmvry.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcuvkci.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnafifrw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izolkugy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2brpmqkjz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raxybxpy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dxewkgfq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpjjxui.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yoylvtan.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmricon.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbognxh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcrzrop.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzzzhdi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtjndjk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoklqtu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2apnwtgvp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beauvnof.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dusxuzlz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2higzapjo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwgohfu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqtaxnh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nimtdvhx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjyevyw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2taxwmakh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vofqdhjz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbebnxb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjxjgjm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmfejgd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hazmavev.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzldltf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lutjhoul.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gygsnkwa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qygvjhjt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ucravtqn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuuusjk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdclhtz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxksgpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdbwuqf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tstbcbma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ructzbge.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2irupwtym.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vgniaqvh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fjazvkhp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtsqqgc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrcgeol.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nudhbolf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2psoeknce.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2oevjgjku.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpxaprb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypremhhf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2msepwmuf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiyiarsz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmlrfjo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2grvtbtky.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwevtetl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlvpxzk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2husjdtnt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmymhhl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpxilft.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ilarmzsi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhkzyag.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2okngymuo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nynepvad.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2csesxbbo.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrronzy.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2giyajxiw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzqyivr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiugygal.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtinfjy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2roomevtw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhrxlxi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiknocv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2buiuhivp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuqeenz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2oojvjhoc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvfqxbe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2idnwutjc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lugqjdyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2njzghmde.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hstxbbfw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2weizsnfk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hpreydkj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzbsedh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2szzxecfq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvypfxt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yoebvchq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfpxzik.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mawhcxvi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpciyxi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjdtzwk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2eapohfxq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsknork.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqccffu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2upqmqnet.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrmkiah.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvpgcvv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaxhdjm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhdvqcy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oabsqksm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsqrqsr.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2euoqfece.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zqumvoii.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2sknzqlgl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lqydakhz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrjgsrt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rulgcxju.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2noounrca.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gilvemhr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2iukzaavi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzzsiiy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2deuvwpgi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2zajfnobe.html


<!-- 参考信息 -->