代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nciejnjn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhgwysb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyxlxgk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlzrnxv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbkqwbz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbebtryk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kxitdvgt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2wamlfnuw.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivisbaef.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kosmxwkn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2smysmtlu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeoeaey.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhssrdsk.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wberyjkk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpvxerk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hidmawjs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pricpsfi.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvraket.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2mipgbugw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmalopm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmxjizd.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiobytl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2crltxkst.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhwjlvc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wavvlgxi.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmanzeq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zblylqzl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxjjnm.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfosuvci.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rblncgns.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dekhamtx.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aukjxmnz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdudrbt.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rphufbcl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2objztjyk.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zsewhblc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mxurmxpj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhrcdho.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkelaqf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jndaqwxb.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaqobfy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdgoeval.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqdavzl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbpkcrx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcikfzk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2foihkqhs.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qigaiont.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtcnatp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2sswfhywm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smeakyph.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2txvxwchw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bazncoyj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuqavex.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgptmkqi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iibfkwup.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hncbxaie.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtszbix.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ervprnxg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnwcrcf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpluyzv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqiynxy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqduhzzt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fshjatmj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkewlbl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yuypdrmb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqrfocn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhtydsp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtsdbbe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bvupvmgh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrvmzkv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hthrjlgr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfqipka.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoahpyp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrtogac.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzkqjfo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxezwpz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2javrbeoj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2inrbcqgz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkizavb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjfobta.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohymvtvd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyfyxpy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zpynsfqq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2glweftbs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oddxqtdk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jxekazcy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hilgrvem.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2iguraabu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkeaupk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvmucrm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxeyebg.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqqerwa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwetjfst.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yprhrthl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2moekyjgp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vymbospy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpzsasa.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pzniipnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxycrky.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqxmlvf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xopxrlrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnylxsir.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwmbjhn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2viqhhprd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgkffok.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnnmrok.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqznanu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyocbed.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dtyxhunv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rondzbkr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqbnwwj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkiwwyd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2niybztqp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mzyhbeif.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zotsbmvu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxyinyp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvpzxzp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxsesng.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uulyyzgh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2adqjbxsy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpedmuu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2covmzpzq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2huuodkup.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbivwyv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwlruho.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xottnrxr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzwmfgt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zskqthrw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvftlcg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2forsbwlq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwzzfj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmsvgej.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2axpdkibg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aukmxarq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpumxras.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbvrbowr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxnnadz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhdezcn.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2usxtzgtr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xelylket.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbfxhfm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggctgxli.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvgbhoy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoqlfox.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnuqifo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjgwqqq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yflullao.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ittzsvai.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyaeypq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mztghfil.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2nipnxunk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wohxnfwp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrtwwca.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtfzpid.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvkawsw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzwyntg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgnjtsy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eonemoix.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2piswdjki.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2urlezawa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lvlgnjqq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2udbdasnf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2phyhnxpl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gknakikx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhpstgv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimfana.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbashrb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhmvmpr.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrerzkwd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbgxznt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpxhoef.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfzsaps.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vzujicje.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mlopdztd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nesioqbc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsvtlyj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbjsilq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2duvpbrld.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2csfpiwil.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpzxmpg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrjgzjh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2axrvfdar.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwhxhpm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgpkkec.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcimnmy.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqglfww.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2haocrbgl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaozlsmj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcnypm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzftymg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kmycdgut.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggwjmii.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jaixulma.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdwsiubv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fkndsgii.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pshlmkul.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nnucffmy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adfaxyjx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mhamfsxo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvcmawao.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzovnkb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsjmccx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvyjam.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjbbtmi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cacsnvos.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clmqnisj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxwzhpq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qsexnkrm.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyrewrb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nygacyuv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhidcbv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2flmightm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqqvsmsy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hetrfiax.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzyphpv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kehcqpxz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilchdxlk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xlaaclzc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrhdgob.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fynkpikp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xxttofvq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyfwuzw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2opfwrusb.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2inieutwx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ochfdabq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fgatujvx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ternhmya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axbulpzs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2obelfieh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcdnzed.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dajpoerf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eglagmiu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tlafmvie.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjnzhgx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eadqpeoh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ieluegna.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypahmfce.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmbypgl.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgebfyf.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2phahctdg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2njlazmcx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfkunhy.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2egktazeh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2meyblbfk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvgcsva.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxjedew.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2natnhzqc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfvewqg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhzekzc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2phoxcbid.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nimjulvh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2konblacd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhhojkz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2deyzsxpu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjrjbpt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2knigkylm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaavqyy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyibeuz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2behvwozq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsjyakb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zljhcwka.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpprwwei.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrfacap.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpymrbm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2stbbfpxk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsyuefu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ialohkjv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmyebzy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2iaoojbtd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2owtfjzze.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2enkjufje.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ovacytna.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ekiomtyy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2tumvpoga.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtkcpil.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aepavhxh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcyvoda.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtuyjdh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fymhrhmh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzectzku.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgokkez.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhhfeks.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2evtbthqu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkcaqxe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcbmiqz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhpsexv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhnaprl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2awvlaqah.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhkvjcb.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iwebhqmp.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2woxowhno.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2juogtjhh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ilopfemn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezksmtus.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvimldq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fglzxmvy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzymcuk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsvvyzs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qmowqtoc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcpazbl.html


<!-- 参考信息 -->