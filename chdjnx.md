代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdbltwn.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oitvykxi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfjwhoh.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cqumoeub.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2nronarhh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfrofkb.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2apamiysi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sdksgkji.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpsryuw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2obxmqgfk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuchqml.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pphwkbee.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fuxkwkmq.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnchvqf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlskjuo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xdokzjln.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvsowxk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgdcaqu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ipptaszj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxgwjoz.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxlaqnz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuavfxq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eytbfsfs.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2htdlhrsa.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2nsybpztm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkavrte.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtkhwnx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wteagflq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2fmdudnwn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnwenyj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wemmgrsg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlnjnmb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2adapetrf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxldntz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ofefnbtk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2brgjvomt.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ghytaqfs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkrybea.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yuynxkit.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvaazjl.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwewlwtz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdjgxqy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oojjwgbz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wppcmspg.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbwmgxx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2juozcyta.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeqcios.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjifwea.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhyesyc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmyszzo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2idvbtrde.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvszzjz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2netxbyoj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nykmwzma.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oojkyrsn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kumfauyp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvydeuu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbsnapc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhcrdtj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kukclxba.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icqcupkj.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwzlsde.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhkxrrb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdtxvah.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfwklvb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyihcsr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqmdbzv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eijtecgx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qitvodgc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvnpyet.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsoyvai.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hctfdwsz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqplboh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2quuayupw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcehijxg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2csophkdh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2whnqxucs.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxgdrfr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xilmkkkd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jutzsifj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlarclc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fwelgsep.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqdbqoq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhjehfc.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsptbhvl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyjprqq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkxqakk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2savvlqkz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2cklucmaf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfzxucy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bioqocya.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrcyuuu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhnrrdz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrbxhna.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dontqqbs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2awhmcmoh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtwvijz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2etgvmgkx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkjlkys.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2olwpaccj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2urpqhnhe.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvfvjcl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2foapnwbr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kfghjhnh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yeefmewu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmoiphm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zazhhoxv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuzxoub.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsahvwg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zexeuzzt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2onqzvvyz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlstkbks.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnmvsak.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfietdti.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfdwiel.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yppvsfaz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgabmog.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hidnidjb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nbigyfii.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2epsrdtpo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2idusxjfu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2whfweidh.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2idcbgduw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfhetts.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kuscpktl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gecigcjh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrwsjxw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpvjjsn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsjooqn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2niasbkje.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bwpgwhni.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkkwyjc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtclfyp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnntfytg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xglemisv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qztjflgn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfkxpmc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsshqssd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jcljauan.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdczifim.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2snofkodh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmrrvuc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mipvjhde.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaaxpcna.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ngffmzxp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jubmjbtb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2znlqergj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dctnrtsv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rcowbnct.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rktqxjnj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oymbqomm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzneouz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2tctkkpjo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtvhslv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqnejgx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mftwwooe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nogrkywk.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xunagrke.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ictjdvne.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjwwccj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqeqasn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmmqfjz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2apmmxlho.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jznrvmmr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2luqlpsim.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgjiqui.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaccknm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2umjgczqj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pauyxeze.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgjzilf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyeobkh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmoqwrx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oizvgbai.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vosbfugr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrdkmln.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcizijc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmgeesi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdgnske.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mpoivmox.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2clnxjlqz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzidadc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjcghqg.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tytxmflr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkkjczk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otukyjhv.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcbxbzm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsolxbl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnrvulb.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdfgvgw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hivsgaan.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvigzpq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2paeiabxc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sejidqcw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cxopowbd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhlbizz.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wvukzxqz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwryrqj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvftskm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzklogi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pobveycg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvtnwxt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jncawgme.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzcxjot.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqzkwfj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2siebfxei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rexqadnd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abgekzok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afgqhqrs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dpzatalj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyabctr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hagdtufr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tufjppdf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjjvnkk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyqbdzg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2iikfqgpu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqipccb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuopsjzb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgogvdpm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsxoodc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2chueoulq.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbdkvqf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdljxbbi.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnbkzal.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lugizxnt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kblpolxt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kezjxxxw.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mssxzirr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2csstuvuq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2itwaxrzy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2teqpyylc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxyyfmx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmirynu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zepuqlqi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2plhumtmc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2utwojmsr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmgabfe.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmeqesl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzujeqrq.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxxgzce.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2csjxfgjt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2avvwaoaj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvisvcqz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2monhhuer.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fydatnds.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jubczjti.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuganzg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjnajzb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdydpvey.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfpcsro.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wauidthn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2kkselffz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cxropwod.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrvhwkz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuyebve.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ykptadgx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zckudznn.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtsrpyd.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nounxnmw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mealezea.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmzyknn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2npkrttaw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbngbpp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2oufedgwp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvzzkzh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uglupdnj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrxyqej.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qjngoely.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnsatle.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2btkulivd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqcmrmi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jkivqomk.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbawzva.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjofyuz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2geviyjpb.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pevxrefj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdccjnhi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrkhjxa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zndfyzxl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffiozadw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfokeiyf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hoboofxh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zjviinjk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bejagfbc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2yftgzpri.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lydhzhvm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2swwmdkgi.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjukash.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtrquit.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zbnbxkhc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2jaubbaxx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2igxwejln.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgucoks.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbsngro.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmcarhz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzlqjtx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2poujgjlc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sueoegbk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hactysfj.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2szlonokz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2uidcpkge.html


<!-- 参考信息 -->