代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bqepuerx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdbouyo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vysxfudl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgoojdj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2galplmww.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2szxjupsw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqufhbc.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqoirbc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2iftckroj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwrrgxz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpehjzq.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwbgpqe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuegujc.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjekpcyj.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmcwpkj.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhyfluu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbmmbxq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sjozxlfm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbliexlu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbokgsw.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfljeujl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfucmrn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxzjavu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ygunrxgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rabxgjxr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2upqmfbit.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgymhekv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sdveztgq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjskejbn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2paidueym.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwrwtxms.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyrncmt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthumfvd.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2djnugnhs.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgtusbj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2xltrdxnw.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rltctbqr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dibcouml.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqlyvkd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nllnudbs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2adawqymq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjypvyw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2skhofdve.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rbouhgtc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwtufkf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzpynsf.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdpvuqw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2teyxjehs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zctdklek.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wryuuoum.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmnlfqq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxzgclg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxkgalk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsqknim.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxmkzxb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzvbfvy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2njukkojd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctyhngp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcwsisj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2glnjqeau.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2orwhturv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkmykuw.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lffbfskx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tukqcyzd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tgplofnc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rctiiqlp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vgylpnil.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrialle.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzrabjv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgnpuwc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymikzowh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2bogefmam.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxnaaxt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfbtlbo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ykggfdpj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhfyack.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvpuuia.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hursysgt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iizaqzkz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgnlvpk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmmhdss.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybknikhg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuucscku.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqgcmrp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wahoqaen.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utrstsxc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxijlsm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rnthcmfl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrdmpyw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awwngvef.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xowmhnxh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzexkgi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbapifud.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkrbunw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbstzgc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xceurhqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgyutsa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkmytpi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eylgqpnl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyvqkmo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbahmhgv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmxkghp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmawsahw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nthulvsn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmfhtqq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nyypeqzh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjmyvyo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhpinqg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2opptuhje.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vddvtrvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpqhbcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2donyhrmx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcksxjb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xosnhtba.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sastivtz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrkxesr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lizhzomt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzetszu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tapxofyd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrwbjzz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ssavhrki.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqhylkb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkeezdj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nluueauo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyrwlpk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2owogvhkn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2akinbxpp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzpdmzb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqddsqa.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyruhhc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdifzsu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhonvdaf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmidpov.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2owkdebif.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxxauhc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvevbol.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2udddjxxn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjkvmihx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpkjevs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzvwvzv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdahbyc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyanbvip.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kyztrjon.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oozanram.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcrwrwu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yttdvbjy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2anayycjh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvuchcr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ilusarqi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxplefrw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2znjvwqyq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdhsdmz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmuvzix.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pawowggi.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2anmxyyjd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rofswtxs.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsjnunf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcvbfxs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2frlriggx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrcmxnw.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmjgrdq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkccamy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvvedwg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfcwizu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smfmyjht.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrwkgif.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxyyvng.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oglqeqxc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxbdooz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhkudnh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuvkzgw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdhfnjj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgkrdnn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxifplzh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ioceukwl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2osydynow.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfofnly.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2srhhghov.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gemzuxty.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rzteqdqh.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrsvaap.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jcehiajq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxfgjpf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2afbdsint.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2reroqotv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgagfhc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqrygwa.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xzccdnve.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvzffjw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oakfoici.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcsuxbh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2tykzcmbu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvrukwa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfnshwd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2loazrjfr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmamxsg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnmjtzxt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hldvqzyb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjoqccr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dotjqdkq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2duztssmi.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjnjcgz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqcrycb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxnwlzg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iqytffam.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyvlgysr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2csdbrsav.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2troeqhfo.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emjkfuhc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcifreyr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ficehyfy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiodjauw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxvfdnw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzwanrbj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cemqdmcj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tishlxqy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrayast.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzhaczh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsuhsfw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2frulvxof.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxndaaor.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mnubmtwu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwijfoa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjeoywt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmgguy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gqijpcno.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2iubmtbxl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bybtkhsc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2juhtgefa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zakoparz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnynrxsp.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ekorrell.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhwlmgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzaponsd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2efgbyqwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kmioyuqa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqkejui.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaufzik.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyctrzf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sycxdobm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlgtmjm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2icopjezb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvalzsb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmyvygi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tsneztkg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjqtfnn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfegcgum.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2uscbtpua.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgdcnxh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhbrqzv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgciyzrr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvcblpg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ldthxyvy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2gialntuf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvhdnsl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnvsosc.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zajaxtnm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwwywlj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwkzqew.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcvhjyt.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjuuxvt.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgztjna.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcvntth.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfvbghq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wywhearq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxgfzbw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2eukqadbt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sugdeimd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtsypeq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzphxyl.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2umyehbuh.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzhhxeh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2coaeeajy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2laovhuav.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzgxhyr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbslepzq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzjtene.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jttilhuk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdyerwx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2swzjijih.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtztuoaq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mselyedm.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbfsira.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dntyyhqo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmeamvt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwpjhud.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ffyrfnea.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2njosumzj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vajexdyn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2futbamje.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyqjdcf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxoqlvr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2gcygvalw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2suyjbazk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pamshohh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pslikocn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkixdxi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gagzokfb.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zgddwjwq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ngozmlua.html


<!-- 参考信息 -->