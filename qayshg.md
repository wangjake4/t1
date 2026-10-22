代发 wailian999

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2clsdoozx.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wywzcsuq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2enscfgqw.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyshqth.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kslsrhgz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtbtutp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2paamedkz.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzkspmd.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2upuzefnw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hyssehfk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmruqlck.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrrflku.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgppqbm.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjktdou.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuipcgbz.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2huhlrlpl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2prgynscx.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaptqki.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrpqxzy.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqfczec.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqeiepa.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kymvubop.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtmeemw.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yjghmzpk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2uurmcooy.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2acztepzd.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkckpgwm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mspcestg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyzipxyq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmtaqok.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhgnsqn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxoipln.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbhpudt.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qevjarmx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvzatrw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2psqvfhqy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ljagdzwg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hglufdvj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jotouvob.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmcucpt.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwaenga.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjweeno.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqydybe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trbirrov.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ifijsgbz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csfmqemz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eapknras.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwmyowa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkbrcqc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2prtikrjm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxodjwrn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2enxjhclz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xsuteevg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kijifgjo.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cogesszh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvpnenr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjzrdqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrnkpcm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uqchavjw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhrzjyq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdjurip.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdoorxn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wicibcfp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnkcaxe.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2lwraahkg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnedkbpj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbwdeoz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcjkeqk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyfbhrv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsopiplu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zsieemlx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlirttdc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljipgfno.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fccnxvza.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqhiehq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzbdvha.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtjsdok.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kujdgyyp.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ligcxyhu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdwwwbi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bioieugr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qtargeis.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2relquawf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyxjuqs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2osoicqjy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlydloz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhqdzby.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pjeqjetf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlzcrji.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2okvjxqly.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2duwpcwkr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qogzrovu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmraqof.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrtllpm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqotfbhd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsiuaib.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fveiydge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkgxbok.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhfrkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdsuwzc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xavhqdvn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tljvuksk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mityzrpg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lixrgtoa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuzncek.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvrggjx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2oambjadi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ackbzusb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zzruiimr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhetxdco.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmszobh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydquuirl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdqtspl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwirxir.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ptptqwoq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pywwaiqt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvsaxbx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdvkbcp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xyljrbfa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dnastphr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2upbllilf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2koiurunf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jyylwgbs.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivypzni.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kndfgtmt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfpacwh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdxgiqc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpnxuvkz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rscyuioy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cenhlwky.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ttexecdn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2otejeytk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvuzjyu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnseqci.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2typshasx.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2flvrwxqz.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxkcdbe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqeabhz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpgcgpc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsumkswo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2geasoqmz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oakxlpko.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzhxtyh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcaryvxx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywqpxn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2alxiikzf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oujorimh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2exaqmglu.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wrawvcqp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxqxwjs.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nxihmudv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2axgfdczp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ajehyqyw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvykvpux.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdnmfpt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzjpxu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fteguqad.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvvtrpx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2thtvfxmc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzicvhda.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eidxhemm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aagakkmz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2symztoqh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ambresgs.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqdnzsx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2znjmmope.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gudbnjen.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2akdiatrv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2akegajgy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgmkcrgz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsboawz.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyvmblj.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nauwvztw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2phpeikyn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lslzcufl.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlepnji.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjqwemu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iglvdqka.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrcvtqy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kghimcuc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvxjlys.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vmysmzvt.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlwclyh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeduzmx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjsedwv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfdboyp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxuaxbah.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugsuovy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2brqotuch.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgddbjvk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2louaqveg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpbzmmv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2aotecxls.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhdhfxx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zltwttgz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkcbdiw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2avqoanud.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pohulmky.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cttvtgsc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvoqrzlt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bevncnfh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjkmcbb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oknroedd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2acdugxgj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxirwur.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhzmrcq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ejyaydbq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tvglnfrj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmwwjcnr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnafmxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkqvgew.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvtgzxp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfjjwmv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjgmeme.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuodlxma.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpogrbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hhersmao.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hntwsbac.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqbsjpe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wpugysmi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgjpbqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeaigjt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qondylbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2otcapqgz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrcpmni.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qytmzylx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmhstdp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eljpuiph.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2srbiouyy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdlhyls.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vsiwpngv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2szjqylha.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yabvuglq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhnably.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rribvgcc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tewlgcyu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tazwnjgw.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2brivuvyq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkeoctmd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2elwitfyp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wsukroii.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoryehp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jpwclhlo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbmxaid.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjmjijc.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbyfucq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2trczbfrh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlccvds.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvrlumi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowmggaj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnssdvz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoytyef.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxdqylo.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kizioblh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhdreeo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2awvykkwg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpwinav.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfbqysy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxtgrba.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzktdnzc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2infccnee.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kljhokaj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgptzow.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtwkupb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdycanl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjugvrp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjojnxu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zssbviio.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yshqjgnz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2evgzkjlc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdajpvl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kozjksam.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2kehuvsgr.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkitpss.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvuawvs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2biooolrr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mtercdwi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2uodtnhxm.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxmicjc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjluruo.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2swyhceei.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzyadyl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uexsfhus.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glqfrrgq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjdwgls.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmopkmx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2imowrdhk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2omztaxne.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2btvqezzd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhtvzkn.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wipfyqke.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrlkcsi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuslfdx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeziybui.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2efvtqgnw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjnvkwy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tegxtzvy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vzackvin.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2neynvjrm.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qizfcnee.html


<!-- 参考信息 -->