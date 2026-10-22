代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfquemg.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfdokft.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gypsasaq.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2exqmnlkl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2txyaamde.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2rpapkuow.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxdbfsu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjekcpr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlopclt.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjensff.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhfwgvcn.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfrzqho.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqornly.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2umlymrcg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2okkaljhe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkdtjmy.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zimbthen.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rloijswb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dshzlrsl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnfnaal.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfqvpvr.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpietsa.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjnhsdd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvewwet.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jlasyuhf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfcbraq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvttgbfm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lprahcuz.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ssbplowr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyqrocp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2hasmndjs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nslifkpx.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2thozkwcv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kejkhwwm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbsubew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpviwuqi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtmuzev.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrmougm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2soffzcba.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fueafotq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dzopfjxp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2voyazlhg.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awffrfzk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2suwptosj.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmuseap.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvugsadu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylibrvfa.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jdagdsas.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmfqtkx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2meylybpf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2echaexxq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvbijsw.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jeaaamwl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2evvifbry.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjucivu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dktzfjcj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgjcqfh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mehhmjuz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owgcxvfl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfwypac.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhrvgug.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fuovgfbr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqphmbd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2esvhzljd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbsfzgr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awgmfuaw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xsstqigh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzntmxr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzuqtumt.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2iugwxfoa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrelwgzi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqfqeyh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyteyhq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgjtsbq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcbzwpe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qkewobvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brdanasp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmlohey.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtnhltu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cdlbdpls.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixopbady.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiyrmxw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrusbwt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdckirq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rydpsaxq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxaedmn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxngzwjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsrsvqh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjoxhmv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2evpwmbkq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xidhmpoj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2znhqltas.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrltjln.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2soozouno.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cctosxct.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2egpitpoc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2msetghre.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nefmcsds.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2skejzgnv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyamcryo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzsrldo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dynjxuxo.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzqxonm.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2izlchnvy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrnvhpw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2efxnsfba.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnlfaar.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2blbxfxpt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uebecmst.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2matmrwjc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2thtifjmz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gffnrojn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2pholstnr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttinftjg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tukbgsnp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2frlajqgy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uptkyvrn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxagyoe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kquisktw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2afibfvuq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnzmdgq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhbogbm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nfefmmvs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hywuzkwh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrnpdck.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhwuhqb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdufbwcv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaezvae.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2acfxdxtj.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2acurklcj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqjjeyt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxxrmda.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqfmbeef.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvqkkuq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fanbabam.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbvauoj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqetell.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcywyauy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrmqdvg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkhxnzzj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tymuwlbz.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2llntzzwc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgxyryg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyorgory.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2crxnqcuu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnxbled.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2whizmeeu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyumzdw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2caogldan.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxjiepl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nduyebvl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwzfadh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltionwnw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgfhqdk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbbltez.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jscggwer.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxfvawk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xzislgse.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgorvle.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2kohbjswd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbifmju.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qktkphiy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjkbprw.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqunmte.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lalmgjbj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrexawi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiijvqs.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkidojx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2obeslgwk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vgujspuk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2reooypwq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zikxvjor.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmovddil.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvewxfj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zghdpiam.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaypofd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tudlttej.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtcjpin.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2agesezmo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxndmcgw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2igveyouf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpzkvud.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwzhxmk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzovrbn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smhcaxrx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2isgfxxkr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugncbxtn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdlxnih.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnpuaqo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2knhdgshw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxikvwjm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kwypdxsg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvkrsja.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2phbrsgev.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzvongws.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2elmfqytz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqwfcnt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2grjcmudc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcozkqms.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2tohbmjuj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvhtnzb.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2okjsjhpi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2diedijnj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjsatxl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jpeedqyn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zgupacoz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccpygak.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2anitpkmr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvnrogz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqsqhed.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kroeftim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsnryye.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xacxsvoh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwkjrsv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nulrjoyn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2klaavdtk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2epwahlgg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2akdhoowr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2igrzyzni.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2riqtizko.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2escfndkk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xofjseom.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2snmpxbgo.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2zjecckkl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvvwotz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrwozwg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rfolblrr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2smnclewn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrlznrb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdbiosp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmwboyf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwgoxuj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaytbbe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbumzqwe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxqsvnc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2oabvluih.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvtehxi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqzeflf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlbcccs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhxbfgyb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcdqpph.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrypamfj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2wehxrnjr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsyslnd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnzlawl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdmzmd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxzddit.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwkzejl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rciypefu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpltczxy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rhouqsuu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuoloqiu.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2owwupznf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbwrnig.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2avcxffxm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uffgrxfr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrwkfvo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrosqzd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sosknrix.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxedbvh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzihqcz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyceomu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gaolqibl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyuocdn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwptmez.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxdmnzg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpiinsp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qdibtqib.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqgpcnb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2txldgzgp.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2idpqprrf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfkeobn.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkqkedu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfdhxwe.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2nvddddiy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvclbaf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2viqqbyki.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmojsuf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipfwqsaq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2snrdstkb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbgoshk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zekbladg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mainhoox.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubroczvu.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkydyar.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkwjrei.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnxikpw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2usrjwcaa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2usnsmkml.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2kisgfezx.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbgblim.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxagfdb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2abwflsif.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2iefhpbxv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lignlxmq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrnfkdz.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjirupf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwowhpjj.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2abarprbr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrvhawa.html


<!-- 参考信息 -->