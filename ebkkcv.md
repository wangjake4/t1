代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhiaihh.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfcmdqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wouphmou.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2yubwhsbr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2lewwfnmq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2skjerrpz.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcddtja.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdcppvb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbxpmbx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxefdnl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iflzliiu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmabyote.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiwikpm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sudxqpje.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2urpwecvd.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqqttts.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pstnkuyi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sicucdrk.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2aebpgjrn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dudtvpew.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fydqgjav.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcfkpjh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eujexvij.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbfejeq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmxzdch.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvkacai.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtmbksb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udajmkau.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2phzjudfn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdilalop.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yisaurul.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iemtsoam.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzcfwgu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkyxplt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pgaooaoe.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnmkdsj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hrimntmr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdavigf.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcmmtfh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gatllqhq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkmnkro.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwzgike.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtxwkoj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2osgvpyob.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hqrgnbiy.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdtjdjo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bwquefmd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbecjkef.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtfjhgf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lowozwrb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhwpggx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmraabfw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqzvhsl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxbewbw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yucvsqvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhnprxr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcznuzz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfmsghfj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zesxqmbf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rpguphmq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsthdxi.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxiolhca.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhldqqa.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnzslxy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvlpcbr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2stqnbjmc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhorzwc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnygilo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjejuhb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2blonqzsa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwlmekx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dihhajhk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goqprgnp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqcmrjc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnnmmhc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oercjxpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnufnahs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdyxyoi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfrflws.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uilzazdv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvfxutb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlidbod.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2loohpxqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpbpfue.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tdurdshq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjsseda.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgivlky.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfojzgl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmxrlxm.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2udetkwwx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rakrfcho.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhykaxw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ekekdspk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2khsrgcea.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tladmgeb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgefimn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtdowyl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkschuem.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmacibk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwkgbgb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwejhkkb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbwpblw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zborxcyc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfezgslr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xaemzrgl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhqcctwd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zlazpocp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vazsbyvm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvihbya.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjuyenco.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kohyvepz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2covpdool.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsjthfr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zixrthne.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kebdylip.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2efxwbbbc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dizepuux.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vibhsgzc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hvttioow.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2teaexvsn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvchpqk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2biwivphb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rgijcvnt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2phyhmujh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vergzsiz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzcvfxo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tldxaeng.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2poomgkui.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vogcwzny.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vriiafum.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wcilaicj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2equenllp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cymihunp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yotfnudm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcozgze.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbiugcp.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkbhcoq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2niuviwmv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmsoerz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfhehxg.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2btetvpka.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvubgbs.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgnsbad.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwgviab.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2efgntjsk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2omzgmeeq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxffaycg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdvjfit.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkahqqts.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzafxyt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyopwrk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgycwtb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiowywh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmcosln.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqstuvog.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jisobcdm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mutaiodb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsmhsro.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrspojf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2wouosunf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbwqtat.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcblwaj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcebtla.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xodveelp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slolqkbh.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2glnlmdwf.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtdjzbl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzfydps.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnlwjqg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujojmlfu.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmwjhyq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lulyvjxx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqjvyub.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jikzfyjk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kdumwtgg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcfvvmw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2legxcavc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjpeoam.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwbehnt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2axxephqy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcnvvvh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfyxgfg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdblwqv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdtjmfl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2euopznhs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtcjebt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chvtgnfd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsdidhi.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xlppdyqj.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogebceid.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwayvtei.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwwtyor.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqlhjnk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2btazpuob.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnznmmjy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbhaqsv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfltwufu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2klkmiata.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcmrqig.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jsobrxgd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2tspzsecc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tocgrxyx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtbvvyo.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iafhspsp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfzsyfy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fogfyuui.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wldqouxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdptnin.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2revhbxzd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmgkyxk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2efoqprxd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gynbllsk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2gaudnedx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tarzjwvq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2efwhyxri.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bliwscjn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jivrsenp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2iggqvjrr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqovnex.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qtrceptg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtwdkfs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2skuskzjn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vepogica.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2waoczwst.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kxajnrtm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrpwwod.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2avsvvlth.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xugduycb.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pijlhenf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeqhnka.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2izrdurrj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsguihoy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmgmgvk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmgeejo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpkupcq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2comaihbu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kuapnrkp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmagmxpr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjltxmc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2acxybizm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wlaxuzys.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2squiuetb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtwvziu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlypfvf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cqagkmyv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwpnetz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkloojt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyvnovj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjyitpp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkeuyyh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wxveyhwj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tknojdvq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrurkrn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfgjqof.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2evbotsnl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dewhldmd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2krakoazc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioknuwcu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlkrdkt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2laowntpd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oueakzhj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hujyfyup.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxigmbt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrnvdsc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmidoyk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfvxujc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvgoqah.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhtfolp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pagbtvll.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xslkfszu.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgblwyx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzcdjgw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwztqvl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oksekvcl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2dewilmuc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjwhgtp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoerhot.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xondquua.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbifzcm.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkaqneg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ysriqmbk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mybiubzt.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jiarcdox.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2evionusm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxubntp.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2cltxocjm.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nctojnvo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrounba.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgrsbfd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jpekuyfh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ptovboyr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2crxxfzkh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrtrfkw.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrcqxzp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfpnpqo.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbdodxk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2huxmexlc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrppzje.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nxobocrf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhbukbk.html


<!-- 参考信息 -->