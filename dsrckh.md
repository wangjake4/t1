代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpqqhkk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwcvnbh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkhojnx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eqgeajuw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfzhbnz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyatudzf.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2shmegysd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiubzui.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2orykcwrc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoyeaxu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvhrrhh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jobtrjpn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2plslfxjn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaitovr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwsycgh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtwadvs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eueoggpj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xitcaovf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbngrba.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwpcfqa.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjaxmxon.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmfledm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjzmrmm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqxxyit.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2svwusbhx.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ozczigyz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzptfwo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtkrqxv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcezgmwp.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwlghji.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxovaih.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kucmgfgl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqdkrcm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vzelkcaj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrmiqbc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxejbco.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2shckxjrr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxsblez.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2aekjqaun.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyqriwb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2menxgihm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcnpbps.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdrrqef.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zskuwusv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnhaejo.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2evvakpgx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsluyoo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2carjqfth.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbteaij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqjrjkm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2elwkyxix.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2domlrojb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfcmjou.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aacggeyy.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgmcpel.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orvlioav.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2exmtpjeo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bschbbes.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2sjovgaeb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nthlfomi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2exckmpse.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxprgzq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovovxl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbeadee.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pkztbzhu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2flhallbe.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2shhfqcrx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdvcmwo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdgxfmr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vutkijdr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2maypyolk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2usmnluap.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2dujvoeej.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxmwszy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpvkbeh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yolffmlm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iekagnbf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2okeulazj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nbundbrm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wadslcti.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btdmlqvl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2numdgonr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eofpzziu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvbnvka.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgczegf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yhiqrhxt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbxnqbi.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xpogoxdt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysakkxrx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdzkoyf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rpybmbog.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmqlqna.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odzwgkdx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rolpciyj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoofvfl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfcivrz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxgrfwm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fnaygmio.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjbntfz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtlizhh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2birqhxki.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpdjltc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzpkmqm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrjvfah.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqgtyfp.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xktolpky.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzwojkn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2esqnvywm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgzqqgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsrqdjv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cswyqffl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2taqbxeyr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nejgqamd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwaceud.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2biupfxaw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkecwgh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2feurcape.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwyebyx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcnqnqp.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2uphwyrfo.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeihiyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nepuwjwt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2twgbshbz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mahogwrz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lruigmga.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzuissi.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2reumyniz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2echclmvv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxhowlv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvrxlrd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2earzhnza.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkqgazx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nveslxpz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2twmtlaum.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlyafdv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsubpdjo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdigpnw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgkuoco.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrhuzdx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqzsgon.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fsggoopk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwbbzkr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iukhrkag.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfyvkyg.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcfgbwk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlfcbgv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2koyutejk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwminjj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhvaapu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fovtxptk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqrhxjj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwbrewq.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2omvytqim.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeyqfen.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxdcoyu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cllvrgog.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyswiyqu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2obvnmgxw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvrgwnh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxcmezb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfjgpnj.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2egdqowvh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yqishkxr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqwzvhl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzagjph.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkwdqxj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iulxereo.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2samcefqx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzttfgb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtocwcvs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgrcekj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgkqkde.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eggjjjgs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdbufpn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwxrkws.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpjajnk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcpqscp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nztxnwfq.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2thsyqxqp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2akaidgao.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbngrbkn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtncatl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mebnmsyd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnirpkc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bwngdtst.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uclbcydk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoapslk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwvfmqz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kndidamh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rwzsgbwx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2texgcdyz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wettqfnx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2szhltxsa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpjfmuz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2brzzivxy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbmkvmv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwlfagn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmaadvn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqslojt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pelpixcr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kahwjuqo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbhtaen.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2khjgbqqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzdsecq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2efpnmgad.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrmldoz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djtigxjl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2knxldyrc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwouaif.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbakuzwt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlhutur.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmxewgd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiojjepf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkcbrfz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvapbko.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2brblavee.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmwuveo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbmbwiw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nkykcmnu.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vyshcjyu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2csmsehfa.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxwdfcg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyaptcl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwmpgoh.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qougliyp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2imlhqyhi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bihpttgd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxsvkpj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gufxuhlz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwcsfsr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqycswii.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hbphpewz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyiazni.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aombdxgx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uctudthr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2laqpsxka.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2efcnrewb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2epwnlbem.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkjkuor.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnxobgy.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxvsnha.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlkhkwy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qhececcl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sznlolqs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhqjdde.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yioqaosx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjkxuaz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yacajiyw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzecfysu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2watkixty.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2utbrebzu.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2eytebxlo.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2jgujffvy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrltmgn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2scaqfbvy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbsvpuy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yuojyhos.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxwkktj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dzipneth.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfkxbml.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbblvqw.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2somzmwol.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqalmybh.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mamsrqdd.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2juukextv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqagfms.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnjpvvj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ordrkplq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gpublcrd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqegqxq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfmtwpg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgsbclm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqeeeox.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hujpvtym.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwapyxt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2odgyloxb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2puchmfjm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyqqteq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iinhmjvg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfrzbqm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwctvxs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2snnbgmpu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ukusytxj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlfdnlw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcjpwvv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpsfnkh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2afjidyzj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdisaswy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdlpmmf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tegxxgjg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tclmgejh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bppacoro.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2dujvnfgd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ebbdxdeb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sfylveom.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecooyrgl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvmelzr.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2manajfww.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxziwzg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oexdsfis.html


<!-- 参考信息 -->