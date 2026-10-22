代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnfczyn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyxohry.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsrilau.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmzujvc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2cylwyiah.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddijxdln.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsozguq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2brghijjj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iybjsldt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cighqsmr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdrzjry.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tryjfpgp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmjlall.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzprbqk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wlusbksc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdromyy.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2exkknbtz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uttyflqd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2aepzhjxp.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bvyoklnc.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtijdaa.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2njxhxmtl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2etcorefe.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfgxlvs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2emkxdrnn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bppcznsp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwalvqp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2emunvaam.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpaqsnt.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pliptpln.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbwdzbu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2neohiwar.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrqypwg.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hqozhlma.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojstjseh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hykriugn.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2krcutvzl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqhuvuc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqzdnqi.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaujlmz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcskprn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmztjcc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdtoxtl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rjesfcsr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfkynfy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bldcfbdm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2angknsiu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pajwgxdb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2exaeywoo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frstuzej.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzzkswa.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iaezgwhe.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2phkoacwl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkniurjw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mevlvzer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkpdtmg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfywzhp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyeites.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pigazlpg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgzngpd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iauvgbpu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkksuuji.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2duxabkko.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tesbnhku.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulcsnldw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdehhav.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtlshgw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kolrmiwv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fholbxan.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2npaocymq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nypgchmp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdexvpsx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjspwtn.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzflzhf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ssxchzad.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjcajed.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzdxofk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrbghbby.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvpczha.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdxkdkw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrnihsj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqffkxyo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpxklmu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2udldbpdb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogomarhv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvotfmh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rskbczqw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgwzayd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnjjrpe.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhisrmg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2klenhfbm.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrywjtc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlitatry.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hupwuczc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2flogszyq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtebayk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhllsip.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tfseiljk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2osofsplp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzienoh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjzeoeu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbiqcjr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxnbehl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yopmdiho.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pudphqeo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2abdjnbhq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2knyofalp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdnjmwu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjgmyzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrgsqod.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgqmpit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zglellrx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rchxlgfn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vhigkari.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jiazonpt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkqgzfz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qawcauft.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdenjfkf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvptabk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzgpipp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2drjrpacx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrqzznj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmuhnof.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2engwdaoe.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsimcey.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2msoeaekn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vavzlrbz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnsdlof.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfporfvd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2stnaugzh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2amxmzhkr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2npjgjwex.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpplgtj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oghmprul.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwwsycs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vucfqkjn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nsuvixkf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gywoiwxg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoxulix.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2flojnyyq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2njglxamk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlivfnol.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nduyydqe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfzbmzb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2buaeohlf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksphgnwg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bklhgliq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjbtbyb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oliyqnrw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfhdvdl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2imynjxxv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2izfsxshw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxswigbc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sppimswe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2posseykm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaynveb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwunjad.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2norbuctc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ueihuhff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ullacnff.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2owjcdwvm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkzciqb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgxmdzu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpuozmm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nobgheel.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyosycxe.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgxfphy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlivomg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpwtuql.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2kteetpht.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyotawy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lybvnlih.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbghpnov.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2atwhavan.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyejkbq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoismlj.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmdmfwv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2awijjokx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsftmyj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gltujlsq.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2chnzmyhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2quvsjgjn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxyoqtjh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yskorudl.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lespcwed.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uipropwl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oopsfqdq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2waalpkpc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tozcroby.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpaqqdi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tatcjpld.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rvthnjvy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2giwhhkdn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuwlref.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuzltlo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxausjar.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvlgivd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywllbkfa.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxgchxl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwmwogw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idxbwtbf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bprxczkc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bcvzcxdt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klnszpyo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cldyyrmx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2suekgvqh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnbwqdm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpofepa.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pefncrks.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlklyby.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2veiylqtz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2drqjgnlu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtgzedt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjpmnqa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvgisf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrgkeik.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxwnxmn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmombyag.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mltqyxyq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpfzeoj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqblniyr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpcaieb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nskcwbcv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxcpzwb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2prhpkqfu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrceuks.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgmcvbl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zcectsvn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlhawcw.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsmcbiv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnsrmvj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2axlwtjqg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjdcqnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxoanmt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxoybkol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfggfgxo.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnhivgy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvabjkk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2relwarsz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2llzulfax.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfamqfd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2qntpdoqf.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2emdltspn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uefymvvh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eosfxptq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzxclce.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2slkktbvq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcioboz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iatyjclk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhuzbwp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrrcgid.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2elwmgerv.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuwwmsp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qggrjset.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mlizjwiy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2imnvbbmh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdikxef.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmfwjdq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrpvhfb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwghedei.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dilyzpba.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2csanzuvd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2baxqlvpk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfurtdqt.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfecjbv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnvgdwd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvccwvh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yekphgbv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2elmetest.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2oghgvjsm.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlxptip.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpgqcqk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqmuisd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2efovscju.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aiirhkgt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2imyyckxk.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2weksaobb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jvldwjtg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2abhlxvno.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjkjfbw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chnmjuwf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2oodpzrpe.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zogntmab.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2migewtkl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wpefrtlw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthdkdlh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cpunzfij.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtihbrcu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmrrvrm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zugqwmhw.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jblbcvzx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbbmock.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdlllht.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cctxztvz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2filgegid.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nipambvf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqvktcd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtlpags.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2frsfpxec.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkwzgpl.html


<!-- 参考信息 -->