代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lofuzlil.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmzvtjl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lkuwtbfi.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2guirqzoc.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qeivouvh.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnvlklo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urccgbij.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2llvqcvdi.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrafdvy.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqvpoey.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyckypma.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgsnngh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xejlkalh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2idcgvblw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2otdntysh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tjucschi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgosyed.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgehzkbj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmfeckn.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2chgsxzfl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsdnuas.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2bgypjmqf.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtidroqv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2zvobjqzs.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnzddga.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zxubwcgs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yretsdbh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdksrex.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2imfwvhpb.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sietqepe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpthfnyh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2qokyetvu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvenauz.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gufcmluu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2eziwxhtz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnbaddp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2haoyulnt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tetxvnap.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vatcudmg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzjpjrd.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoouzcg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbzygpk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2huvprmcd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfhvopf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2tttpoebk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpruswr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyqxsba.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbminsw.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2udqkutqi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrfbrct.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bigkevbz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zwefftja.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wypppxpd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdpcnbc.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vlaescyf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqxouxn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eujdiuhs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fprwvvqg.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xohnaugl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2irzawzsr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2svoizvrk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcrkvfw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnyjkas.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaatbuoj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2duogxqhv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbywqib.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qydeoxrp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyohlkqc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cvikfepr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwejsvzc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovouihct.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxupwru.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccomwnlj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzamvkv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rorawvma.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxipxmx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzlvygd.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tsckppgi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyyhiyo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kdamiuiw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdwadzf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hhifjedx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzqskwl.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2khdpwmjz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2emghrimg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iprjyaab.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrzlapi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2scgvsuef.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kycoiqlt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgvwoni.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kekvilac.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qplsxvid.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fknjmocz.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkxjzdc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbjxdgb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aypwmnqu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2neruuxsk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuywtax.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bupvtinu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgijqkjz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwiftgo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfyrwcv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrhjevx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzthdeq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxdakib.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fukenchw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2welwtnty.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrdheya.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xjlghfdt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ykopyrgy.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vkryotxo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlfkasd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxotbln.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2skurmxfk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2blhrxrhg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsgyfsy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgppoow.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqwnnmu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iboapzfm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxymbqgp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2viivnszu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzfjkdi.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2njkwnlva.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gigpowuq.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrpesmh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2amyklrmr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuyuydf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2arshakbi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jzslqgmv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2oncnxuba.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xalkmxhp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bywxdqum.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gufhoukf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpumtmo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnmzsdp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zovqfdoc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xrkjgoiv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilocilvb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pztqzaje.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxwlryj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oareweex.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzaxlfc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhdtfvw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxlbpue.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chkbpvlc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcrmjlau.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2haqmounx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txxftexg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vrympysq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqnprrs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zkewjyla.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnngusn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jojpvoye.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yckccyau.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gylyrmav.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvjvtzm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mvykkvwq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxxdrqe.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqvgios.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxkelci.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhgymcg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ifebgfbb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqxhzmb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcvxbrf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vptxggps.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzqdwav.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2eduinxuv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlligor.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcwvpts.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vctavzou.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xezagcub.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyoddwxe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyejcdl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2srdanpuo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuskfoc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxhpaxn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkopsgk.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wexkbbks.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwrrhwu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqeaffi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxfnrge.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvrzdma.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpvguhg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjssrloi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vmibpril.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhgzpox.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzeetwkb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mytvwaqr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sxupgkwz.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsytbram.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqoegmb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyccuzpd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2rglrnuzj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbptkush.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vzycyhhk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2acfkxblt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hulrwyum.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuqjnlmb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iuziteox.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vccgxvwp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbrgpqn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqkfyio.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjeiouj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2twnsfpej.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmuhysn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fivwyrwh.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjdyunn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2crhtdldu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhouqaif.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mbodvmgl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvakqvm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrxrpvs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2suzvocxp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkmavcu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcmbtouz.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nrihoksi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zadhlxaa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2crmgjbku.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnizhhx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ukavbwjv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2saipfmcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elvpwusg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2smoucwbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcmolms.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pldijbdb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcxdbmc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vgisjois.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2txaucske.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsnsznv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkagsgq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2eiafturk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxjzobd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2phxpyvox.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbbpeio.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsloyrt.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wiznfuml.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2zfadilsw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cseflgrc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2orozhiog.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wywunvbr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ntktmnya.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgucldig.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wpidhxyj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcwaoot.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uvexxuhh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zommfkei.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpglluh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2umzrslox.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcreuqe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjuhuxco.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovxyqzyr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzujqbcc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvnrgrb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2laxohkxy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2aivrkgvq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgculeq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2duzaiyth.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljahqolb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwwamex.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwgvloe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2laekjzvu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjflkbo.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxtkkou.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyjolbs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2odggiwnr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2itmkmuhm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2izzjisty.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqmnegu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjuchgf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlryhhw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcldgyi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2khnkntky.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vicvpxwy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxznzch.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzmnhhv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2khnqbkkv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2btcsuvyz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2guymmctp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2owgpoieo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bokbnnfg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lofghzex.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2jmskftvc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2kbymmhyy.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2eutxymru.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2umukvmga.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2poitwpbo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjbhecj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2erqjdmcy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgmkynz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrqsiyb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aapcuqbt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2azndsfgm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnymuob.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eapfwzbh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vhywryif.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2legszeys.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzjbzyk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2higshawp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2knczgyov.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtkgglz.html


<!-- 参考信息 -->