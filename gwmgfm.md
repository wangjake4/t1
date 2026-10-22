代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2whegxqqd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2outzbfel.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxbjuan.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2armuoxfe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2oldalyzp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavpqtvs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwydndvh.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hywixiku.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyoijbj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfbqlbh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeovvpp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjvwlri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzocwlce.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bibssmsc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yypwvlqn.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvfsove.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkgqdlm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adjgejpm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2krgfzwbf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwzttao.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bttprefs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dprcexzt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpqocsa.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhylcfv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfynldia.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oaadglyc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtooitf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vldowfkt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbfeogl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudvpel.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oskcqzhp.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdkwihx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2bawnrkhu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrzobpu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiqqgwl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2meptvoth.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpjzdap.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgencpq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsjftzh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rngleqnb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eathqslz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmbalej.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbawhnrh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2zoawdpwi.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hakeiqop.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hzofzeyz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyeoses.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2semfqlou.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2oinmxflx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwcnzfy.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqwkxhp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcknjqr.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qssvclsx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeopqcvo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2nccjsoqn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfvukkb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrvyzuw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkgaudk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ndimlpnn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmyvyxh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqsmlfq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mykhinwf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdikrdm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jnszopqy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2blwnfocv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfsypme.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgjscma.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpoprrj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlolwxn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbyhpfm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdwfxfm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcwvuch.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ivovxjqf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvutpamz.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuehdxa.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jakkitrc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfwafyd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijewgfdo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2unhzdizt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfxkjoh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etqjzcxa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqazocl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgziypjy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ophnronz.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdflstz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uxallktn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqvfxgv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dhydhlyf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2washsedy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbxqfmf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmmbpyu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rwepnsjx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkprnac.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jlqsraxi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnwmhoc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjrumnl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfudwme.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vitvfprv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbrkqga.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgmhbfu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgtewdk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tfghfdjv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpzbpch.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gptlqgqp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqsyssj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wfkxfosk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zquitrml.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gbodmwhh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zorwebby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2voexelec.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ssznfhlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgepghr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhniivy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghecwexo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxunvfdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2czcivdhk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbjwzrr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyjcnoi.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxxsrul.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2atgedsnt.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2posxeqsh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zblnzylo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlgmlqo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2atqtqfwa.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2akxmorfm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uokpqbja.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kdogjhax.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkldnxt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqolqkb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ynguxfao.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvxyrns.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzybezoz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tahhxgjr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiujvkwy.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gflfnmjo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcnysnz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2csxladvh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtneetw.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdnvbun.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2juzigyqt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeucikc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfqrknc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdeduhx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lczwhxhk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbpzmbw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2keffbpuv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpdolop.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgyauuk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2spyleesc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eavubmfu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjyciet.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrviozh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lndlsmiq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sirgoczp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2opopkddw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xoruelkx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uotmzrdy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cehmoruj.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdrwiqq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpsjefs.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2glqlgfny.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjejkzt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mkygazaq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2usqapplc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxgdrdv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2unwxagqq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkxayuw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vquhkprh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yekgbtya.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvicrci.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2judcahsl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nngvudhk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aikzgxki.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxryadu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2elzyenbt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pinhksbl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqzcava.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vwngvrqt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2subzqacg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ejtckjmt.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2merobdqe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2glsnplaq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alqgpvht.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bljnpvpj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcchaas.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2evfgubwo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2urdsbfxq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqoimof.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2emnncwax.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqeuxnpl.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmgyzspz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kglsdcdc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2euyfuzns.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxmovow.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olzskykf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2djmvxnfk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2olhhprlh.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiojovx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xuifqfsr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyatwuhy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2apfkxnlx.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxucfff.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdtvvwr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyuwcbi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpfblhn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ducseljv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yofulxnu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwikhovb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtetbxqh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llbaiavt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ggibnrpr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2enbyhgwd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2undjvyih.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzhztwr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfmozhk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfjycwh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilespnpb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvmquvj.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fokgunkp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjjkyiw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iijrlnub.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2igmjndcp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvuqxtr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyhthjc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvwwubb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzvxbvc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnrygqn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhhpcyw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2xstivett.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvjkiet.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vncnogke.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nuibyrrl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgmxpsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smbthtjq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkthduvb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dffuspge.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjuwtcn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2piwsxhle.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2phrcmtib.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdzlofa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcsugni.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwxjccl.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzrozud.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzwiiqc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2abtbrepi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzykewje.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mufbtghg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgtchzo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2njaksmlp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2apxuzjkm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjhcqqp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpgqjxe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhgvmhs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nanhtzab.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmulhzc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2evszvdsn.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mhawjsoj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtcsbnc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvaveej.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmzbuva.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wijgmwah.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bckrhrjf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2miftnjti.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnnmtye.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvnplye.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dchgktdd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjsnrsf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hudwttqa.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoznbrv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpuhjsug.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqzyamk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2izefunnc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbcvejm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxmcawr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcvphbc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdcrkjy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bswoflvz.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiitswk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2bskomigc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxephduf.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkcxnsh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfvowog.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfinivz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfppxha.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoezxxi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvjheii.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhmhotb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vugutamo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2brjpsayl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2adeuvxrk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ddettnyp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkdrwsb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2adklmlcr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dodmkkaa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qofbakch.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxaniyj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnsufsm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwygffn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2dczdunvz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jerblnbl.html


<!-- 参考信息 -->