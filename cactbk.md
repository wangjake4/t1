代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvtknqr.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsawmmr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2sayqlgse.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzyqywn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzmdpjg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2pimpaypy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmhpaut.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vdthtpjj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmtutyu.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzpxkyb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2uynfwyzu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwmchik.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcdigbx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqwthif.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpayoad.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zgklsmdy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iznojlnq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxfyhoj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lashkcui.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2stfdizyv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyanafn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2omunzhjg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvolada.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkosaqbj.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2utqtbnnn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyifkpm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2plbfeain.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rztqfwih.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkzdacx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxlpphu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2guelhkzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxymibec.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtrzloh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amfjzduk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tijrieqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2atqqicto.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvqqiau.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqbtwvj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vjerdlqc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ivsslpyj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rahxhvnl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2sogvjnaf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpmodve.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuubyqqq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdjktnl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vppezlkn.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrklevqr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ioptltbi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hqszjpld.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ithtsics.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xcblkyvu.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyosmwf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2oyojcjvd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeuijws.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbextba.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2horzfnkx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnhhtem.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bafiudlu.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjukzjlg.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwftkmb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pydwjoqz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoatxqj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wjujpnlw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vtfwoxqg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2noazczvc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdrtnwq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2paefzbtd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmwepiq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swnachmm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmseglw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eeccbiwt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrfqgfu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlndxxm.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gehqpmxg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mldqjtfr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ythefyvi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvcxyrk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhgbhpc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpbdsiy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pnywsqfb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2euwrtnmu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkowiqv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvupqkvs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hpopjimc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzebgja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbmvqcv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pttsrksi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjljegj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bfrgxzuy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2elowpxun.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bhiqnicj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dodqrhvl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tngwgiia.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzysgsdd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ouljuddl.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fksozesf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2urcnbnfq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2btjttyaq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrlwpwb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mysokoph.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2etxickiu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fegpfoub.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdloava.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmlzrma.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rxetschb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhywbdz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oazdzyuy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2svtwijze.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwdewda.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdsomle.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lrenvepe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2emqhqazm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwpzkea.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoqqoym.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ynouopqt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svjklufq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fadrihoa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tanonmpd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnuluwt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtfgpdb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lddrmiyu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvzcxxh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuvrgcv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbpxinp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2julgfkrw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgihrjcz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyxvahn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrttqt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnicujh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuddvuh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqlnquj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfeqonl.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvbrfyn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsozasp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwihfip.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyjbxhb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rvocedey.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpikthg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhuycul.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuvuicr.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwxprwe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeqjanl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvfjuoy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrerorbr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2liioucbo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcjvykr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2iotsyywi.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrgougm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2klqpbaes.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cidbishc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lmugrczz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pgbvmxov.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jocjmamt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2htnbmjtp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sccpxfpl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoibzue.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2chmatril.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvszjxmd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwmhymh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vohytlzp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbnhdwz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbitvus.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjygtzvb.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yisuehsw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2msuadyop.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qaozlycu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2leisklps.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbomkxj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yzahdjqv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2akgzzhwy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lstozomp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmjctqm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fljjwmpx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2upslbwbs.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaiprnb.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txapawpq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhlcaho.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2linbtsqb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsutlmo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxehhyi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2imbjfcxx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yczhyuif.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2foderpcq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjdaauz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwzxkxzv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdeazzl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akukxnrc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmpqwnp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeebwbe.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjruofe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhhlcbm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpqqalp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgtfjjn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2skabzmts.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcauyhk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoljotx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2khemxtbo.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nhofsvkg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtfiqzq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhxhtbv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2esutbjzo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aujdnmfi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjsamrf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkjmruj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqermuf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwewfju.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsrelok.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kagqrtmm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2keenyror.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psdwxplh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtjggzf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2baargawl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rzupzkqf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hdysxpkn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bfupctwr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyqaiux.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lbbwojqt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2irsyzlin.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqkuoso.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ihktmaqv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2nislwclu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtbnjgg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkblpyx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2iuctpzkk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvgceqt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkimffji.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvleybl.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2trpvmuxf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnawrmr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbduaan.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpctaxf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qofexqmm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rhiaipcw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpdazdz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2apajawpv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbsoaha.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdmeyqq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwavezc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pygpeeoa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iejkuhzm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmnllyr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhwfubk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2osaylwij.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnraxkvr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zqktjxik.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhyyaxa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ureptrja.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxgxpvw.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjjtuia.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2afleezoq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fkabfdaj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vflmkieq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yriwunpj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdmkvtj.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cqukpokd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zssykljk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxwofgv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2psuoivpq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmdmxy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2flpyikgx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdzwyzc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvdscap.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbpzirt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dudleczi.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wfogyvpi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdxzkyi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzeujqh.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfbfnrz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrygyxm.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vltjfcoz.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxaxece.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crahbvvp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2crbqsmrt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2laflsdqt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbjybeu.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqgqeiy.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vexlvszj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2muvhipbi.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlbsvel.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2iezsyycx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytndjead.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsgigdh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hidbkgpp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdtscji.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxidpdn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mtawkjvc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ucjvnkls.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxnekza.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aneeojdq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sglflnnw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2eqymvyxl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrimmhf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uxedaafs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uddycacw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2nfipbcjd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sarqxsqp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjjfcek.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2btseuqiz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mcgitxdm.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2azysgfbz.html


<!-- 参考信息 -->