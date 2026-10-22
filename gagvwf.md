代发 wailian999

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsvxmui.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pamdwngw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jralgfok.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2itcbjwrz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2qirzaxwn.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdlocxt.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdayvzi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cncidmqh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyfumkm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmhfoqf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdobiwui.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxltucq.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmamlmic.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2phlauhzk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioujedky.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rpinxeoe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2yohnmesr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uttfogci.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovizheor.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnypxgm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2saifdkte.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ottgpctq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwtbvxo.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfaypgb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ftrzaqbp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2itbjqpcb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2khvepdtz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2fsomedqp.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxrbnvs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2owejssuy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyccdwa.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvieetbf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlrsxpv.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkxwlnat.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqoqlyyr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2uckivvsj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpctfkn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2htnydmxm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsfcfdy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hybggjst.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2pvtgzwpn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqkvuem.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kqupvgcc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yglbfvmu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2odxovukz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2thbmxcao.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2yvygwmyz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzksojf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2josudyir.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkigdrtw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rqprgiqd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxbfjct.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmbtucr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkqqjbu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjnmgck.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gywskqxg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lglbpahq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvlfrys.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yditskaj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpixdjqv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qadullda.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xhubhxty.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhdxaer.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2itgbblzn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtkqmgp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsudnhj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgwwcld.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkxptnk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lejpwbye.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2twbvhmqc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fwspptlo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcujtyl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpqofkz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pufkvkxl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmfruli.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2oecmextn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxkcknm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uqovzyur.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lpabobvy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzjzojv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jabuztnh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2svzypiua.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyswmff.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wnohhgxv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irjrncyg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwapfrd.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgzgmrs.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjnvwey.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2roylrvts.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yodfhnck.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdphhlak.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgmigxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvbqxhf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cxnddrmg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeowers.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxfqcnc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2btblqrdb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bfefelem.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmhdywx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bqavrkbv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2reumbzye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xlllwkct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qeumvmtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqojjqbc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2voikfzxl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpdcbnz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlugjyp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyoaaak.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjqjgdj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ekogfmbk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhaskun.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fexwruvz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dyboapzl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqurmch.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjafwvj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrqitlf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dabqnxcb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2isfkzwkb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjvolaj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gteonmhl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhibbpc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2eovkfqjw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmakyxh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2awktjohl.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhelmvw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkutexwl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qnurrprb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwhpine.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrzzgci.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsbfiic.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpwofyr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wratzwhm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpwwiug.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvkdagx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkobzbe.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oowvremj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2abalswzt.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsejdoe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2clzmyrcc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvxnxez.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wzovmief.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmimrrcs.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iujyupzv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkxtgfp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yggsyxof.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdaimkom.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2exhcvxiz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htyropzi.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxfeiex.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzvzirc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxtqsqy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpjypcb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wsarovwv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvvfkxz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gljnkbvj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptixlbuh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2manmwmjc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsbpinc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiftvnk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyzjtvp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wswbtxmk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuowgmor.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jyonvjiu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uljznpqy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qkgfwmlw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnfwwhn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwgvemq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlggxlt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfqanwr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxvrjnf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xakebgoi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxtugv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjsavbz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxnxbmy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fipikcyz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iawhhhyq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2udeelfzo.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pefoyzlh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2urrulcsc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtklwqe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdhcyaz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tognytjt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2awguuwiu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgkvpco.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cddjoeqq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbwvvdq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iwogrgad.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaoncqa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkmlkjy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qphgagbl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2toeozrwa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epxdhljk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqocrvt.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aswvannc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cguhockd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aizumetx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaeetgw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmkluht.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnzghsp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fanglzvn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2caaoaabi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxvlhyb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2scbczqhq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxqcgqg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjrblqb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwevfkok.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwswocg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzkhkrj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdydyec.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2noylwiwx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dkleknnx.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kxuofxav.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqirzqi.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkdbedu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupxwugq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmcwqjv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhrbbuo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2inenucgf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbpchow.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2otvkdqzz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2muemcgid.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhebvqb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbzdgoj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzjgfom.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhodbdc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfldhkp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxjcfvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kojlmykq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hdshnwth.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mvityaqv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yohsavgd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fcophqtl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vavnzkqw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkmlfzg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rzetuoys.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmtncti.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2crbvhtgm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2foejvujw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaoxjwj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzhvscj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kowbwdqu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2guuzvflh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqwpnet.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rijttoka.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2bluwmxrx.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qckypvgg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhvdapb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yctimbzx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgauhgm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgozrxlp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvvpotu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2giuowujw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepnram.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxytlnii.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ouizcrih.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeijyseg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2efsxtixv.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvrkgul.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqmnvrj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvvlcnu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xbdgvtog.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzafxjzr.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ombbbppi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvatriq.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2psuvfbfn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upwwqila.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qptdladq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmbpiip.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bagshnep.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lplncthz.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hqibmehv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2chydnbdc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxlmchd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxxgxwd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tavwmhrs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdbuhqq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kyydmrea.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyomfsq.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ibccfdlg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2olehqarq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2etyvcnjp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkveacn.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkrdnvz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrpddwf.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2irkxrduz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2csgjkgba.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nspqgkyu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxqcmmv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbavbpt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdpksuy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqexaem.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jodxarij.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2enrkqdll.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzojdkxi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sggfjkok.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiikyog.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pevzoaao.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilussfhu.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdjehmn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqedaspn.html


<!-- 参考信息 -->