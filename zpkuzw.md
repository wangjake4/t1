代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsckxwx.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjnqiin.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pktlptnh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdelpli.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jszwcewk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yhclozeb.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kezrjayu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2dfajqhgc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjdnftf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbqeywf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyztxye.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjmezed.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtpdqle.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbkjyqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxlhsyf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ziioqxyn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjxrppx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kuygtsou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwyilac.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzuwvnx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifabvekg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bljmxxje.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbnukbb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmaqryq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2odvdqybu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbelrhm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhymdjpr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gicdulpg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2flzjftoo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2twpubvyh.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvgutyf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zsilcusn.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2dacgafvi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwcmlwu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqwuhim.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cafnebop.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzvrakf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2weksrmew.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmboeog.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjiwtwp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2limtmjqv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvcxybv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtilqoi.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2klvyoxig.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzpndeo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceudftuc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aoquclwh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzuhrjjv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2esvmzlkz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zaiyvxmv.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2trnatbyz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyorurzm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ndajypdf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xumfchmh.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjfryed.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtpfjed.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tiubmjno.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2archesdo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpxwcrl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kootvolk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwzudpw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tzindjii.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ookdiged.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdtfrjn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2exbvwkag.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lditlded.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2svziodcv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqafonr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjrxbky.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bclocvtd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2svztjtkk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouypebkm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tighfqgh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxlhlen.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2anhvjtjd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2epixzqrh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoplwdv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2calfsmpm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjsltne.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2omjcyeyw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2epguxzze.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtppzseq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfelowz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2suapvoed.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2culqyohm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukrtfx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwipkihq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2usoukbhy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gndsmknh.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvtvnau.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmhvwfo.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2kfidripl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaqgucn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpdxmjt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pttzcphg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoyigbx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsmragt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfermio.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkictpz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxhkmgq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hddskfwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mceonybk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwsdpgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcmqvht.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcaaphn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mayzjsio.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fknidgpk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkakwwf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rcctwzxg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xksvanpp.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2htkutnpl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgkpphu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqjblrx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jisdqetn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uksjvgkn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2krlyibck.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2clhmyfrt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqenbmia.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrmghxu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvilgvp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jtixdwrl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2tambrwnm.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzwniqs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2infpgdur.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqyopqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cslzkhzz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2pksgxdph.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzixkws.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2prznlolz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2suyaejni.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvltran.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwflfpn.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvvdhch.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtwjgam.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nyughhal.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvcfusu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjrdlhm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlgwmqh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuxmboh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdecicx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xshoahxe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndokszsv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ducijcvh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrdknwj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2marfxnck.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qihkjesr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wmatfedo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmlqvqj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwmwzqv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxlcvuo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2klhqfrdg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2oktprawp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvzvvty.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2edjoegvq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nplocxeb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfeqnhp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gacmcqbv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zeinjxyh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2aunhujam.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2abshthso.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dadxpyfu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2whnhjpqq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qmifohmt.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cepvmqnn.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrunallf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtddfuw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xypzpeal.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jwxlzhsa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqovsjad.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2frrskxtl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2taytpxqs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtlevie.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdcrrkt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jtuqmely.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyptttdz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxffrbbw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pegmfgxr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bovvoavf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2riwcalyr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjipwxeb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ceckzayh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wprptflk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwqcodo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdlnlsy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2givaztuq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yulmkqjf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yljrmomx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpcnppf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oceutsiz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpxxntm.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2inbselul.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgehtfhp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wuywokiq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnatoqaf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyxbgxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqbrtq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jamlpuoh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bewwzcce.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpsxxxy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qanetlvy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbtgxau.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkottrk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drhytaex.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjsrbhw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgnoghm.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sykjunxg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2thsbffwv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvilhmp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2llqyllqh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2betpwrhb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbvsyaa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxlkzsp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuqohwa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pokgyevu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvleblpk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kysgsnvo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmutmnqm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2czttmmdx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozswgdas.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhgcdce.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfkaxgx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2smfnodld.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfyxaza.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtoicnu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2anyzbeip.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhkhrem.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yufgdkng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okquucdn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuznhmd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaerooz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtyuwmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jykixgko.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2syqrdzwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tphzkeij.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hrglyhjp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqxeutt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgcmtxr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wokxfoky.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sojazesv.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fryhmrwf.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxkzvgu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuaizoac.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmcmeao.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wkntulkg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2puarycze.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpfolhx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnjbqjz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbndrnh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcpgjys.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tblhtuxl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtemzrq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jocapbaw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tptmpxxj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkzzxec.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxslfrbz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjyrjqtm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jersizzn.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2stvqbqyq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2raqklpdw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxyhbcd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2kleltwcw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dztxpksf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjwhcoo.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwrskge.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2araqenoi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzuitwmn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2adxcoejn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvrmvmw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ajihawnq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwnzqsd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2acsqvdja.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxnjsgz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2icyvdoox.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hywlanka.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jltobors.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngptxetz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxfghme.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2cilpctuh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmnymrc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlwadbq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxcwnmk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxpjlxk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2juufvvjm.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2itbednhh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfxnkjk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2exlcunib.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktybqezs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pivluapn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wlykjgzx.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2kumfbjky.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqqgovp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtgiuro.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2nvytkong.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpnvoxd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pakwcpat.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqiwfkp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ibevabrh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2leitzlrc.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwaymoj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgolbpl.html


<!-- 参考信息 -->