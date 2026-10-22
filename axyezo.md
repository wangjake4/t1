代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsglkpdp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2locgnltn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wexcmayz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2icojhmwg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvpmwol.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdohlmz.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gudrxwfq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xauflrhf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuipccc.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tvutvkbx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtglutz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ckggacdv.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuuydxc.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dnogpuse.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hirbcdbx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyfaenr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltscrtnq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxomduf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zojyaxnw.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gkemruii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2goipmhzm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2bezdznpk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vexreynx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxzygrm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2amijykdp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2mpchhwan.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbzhdtm.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjgmypt.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbwtlpr.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvpvulr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gimvtncy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqruomh.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2glgdspts.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mypzrikx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqirzbtc.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vajphpdy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mcianhqu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqwotdb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bhylcble.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wdaylcgg.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2krpfzpex.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yatviryg.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2acnokggk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sczelaet.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2csevauux.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzffcuj.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2etmdegkh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phadbvxd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2naxsrakb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2shfswsst.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxeauah.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkqrlwe.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2farrfryx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqkzuqjy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrngdhy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvqogde.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hbumhaqs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlmclln.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpbtwbi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdssage.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfalngfd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2izflkerb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeznylyj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxbegls.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmxmqqk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2laexhqpe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2byoptutd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raqlywac.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdiljrt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eixofzpr.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwxutgv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otserwar.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzotjvy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mumcsqeh.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2efkyjwzb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcuutez.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qveswbku.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2puchrxel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfkvxhp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzxymce.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2txipxyki.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kizjihyy.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoozwhf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhjjczj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2njyqswfs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2dloxqgmx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvuiepy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkzzdap.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2awimfwbl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2kmizytbn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgughpa.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2khqisokk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdacvxa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jpkpagkj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2biuqqbqg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2guqusuqr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmuplwq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkwcsxb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvrhsco.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkcsirg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfavazb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mricfwqd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcmjfqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iciqrgmk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuxvgcw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmgpkkl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcyjpjc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ujarzmol.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ylzltcaf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kysqigjl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxlyuli.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njouueeg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2velttonr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjfypfu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wwizpxte.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehacdpad.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwnhuic.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2snqtavwh.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ispggeso.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmczwxl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oangapqt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hyufaoof.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2azeplmbr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdzqekl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2poaepxfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcqlash.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpvnxvg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yablznsb.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpztdev.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvdsbnj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkigwyo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvrhtem.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2anigzunj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwecokc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xgaladvn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2utdbfbqz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfwflvm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uojefqoc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tolpkepu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxnbfwj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tmplcfbt.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnmhrm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjszjpu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2syqkwjde.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcjhswi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgtfxda.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbrbblk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2unqyorye.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otvkogga.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjejlpvk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2slxxpmqa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuzuzel.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqfcqii.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkqhipn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2viuuedvq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpdbwsn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hssbofrd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzjyfjte.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaetrii.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvctkwik.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cjcumnda.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2aepxcibz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2euyfcwyk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiklvwu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbyaelr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kthjjpcu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkbscov.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2licxqyef.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2kufafrek.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2egwuuetu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpnbqqs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrhmzgc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyxkbdg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtczwoi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uugsgmye.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2axfcmwxa.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyouuau.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zzburifz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kignyngd.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bevftrwb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjrqfbp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvjagjo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2trdjezuw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jxnhpnay.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxqrvbb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nmklbuqz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jpulzbvq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjjcjxr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvbtaey.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcvvfsu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2poyruunc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxsryks.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bjffkesl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvyfntz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ztusulyz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkzxswd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlcbevx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwabgsha.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnxrowg.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2feigrhdp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoyfxqb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiiemmj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbposxtp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zenvwykj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpjbwerg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cowaflgb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyepqcz.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ornftdyi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuuxerr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kibaosao.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnariqa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aeihozfj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gchfutmu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhuryqm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpzenbr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2cacyumvd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjwfmsj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcocfxl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lywkhoif.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwlngts.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2llthgbpv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zbubkqjr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoojcqi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwpmoiy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmjeelr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mybzpezw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2szqurmzo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbnruxl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnqhiae.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vgudqmjb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qdauljmf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vuosgcsg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwcktlt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtylzqoi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xiayufid.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnzunwn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lodytpor.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nveenasy.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyyuekx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2feiuezhb.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlifugwx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fomcaixk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2serdydsd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2yljdjbnb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2taupckar.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnpwgcm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuhltvd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwowhycs.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgzuetj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvqahul.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nlphnmfl.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spzkpqpm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxgwwvg.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2tskvepdb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qekcmqyi.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcxpbkx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuxgerc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zptkwtve.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pslixfzj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxtkphz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rkymuseh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2anrhzvik.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pjimjfae.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdmpnis.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoqqtfr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxwobrj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tefeiboy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvlotxpf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdajbby.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2avzsfbwa.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pvybprxi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2iuoaisxs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjobvmra.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiuhanx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fmruyxuk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfhcsta.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2uudmlyrr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyaeztg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vxirkdsc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2shpojkev.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2reuxbpuo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2oaztqndg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nropbwdq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2peiippvz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfcevle.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmcseil.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyvuwre.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwaevqi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoxagxo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqkhsiw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxvuzzs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkrkmau.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tpknjenh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhgepij.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmquxdd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqntubrw.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2berkpkqw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgntuvy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsihnlm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2oscsigsw.html


<!-- 参考信息 -->