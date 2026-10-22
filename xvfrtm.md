代发 wailian999

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2vegcqstg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ealpasvn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yaeypjis.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2djflxrdc.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2aauvswvg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqdpmvd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xgijwtje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ennwhhlp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfvmtnw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyxtxei.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqnorgp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2adodkwzx.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsaxubj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2unuytsjn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mzcjakqa.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdobqud.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wglkmqzg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xfillamz.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2utxyltey.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpqzagf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiyautl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hxobhlaj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaktzgv.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2msscvyfb.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlnkyoa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlorjwll.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hcsdtlbk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulngikar.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2aisiklkb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjljtsao.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ivntfcbk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlxknjo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfcqmnv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvzvhve.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwulemq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2nexfxidc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgettxjk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utausytn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uujlmxym.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdgvrwe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgjmewx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bcogsuli.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlxkzpy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bburndzn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzhzeus.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2szfkjutm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbntwoxn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pceakvbj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdnzlyvo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeoushb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpuicgi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pgivgqai.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hencjuya.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbersrf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyupovq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hctwbtmw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoxaqti.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2jixoihds.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wljrfeft.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyimckm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uutblwam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdocrunu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kkstzgaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2markjhya.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhqaetm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hutroxhn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csqvrjro.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nlefuvjb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2usycwgwa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrkehjl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgcfuqt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2kkehvski.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfzguor.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgsfktq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2acnrscec.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxdvnrn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgemupqd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2azonwtoc.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lrafkaca.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2etqdrzty.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzfnxvw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoijgaz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmokyef.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwjpegz.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2twftywfd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgoisgl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2guklrfvu.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqsqxke.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnnaumi.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pipodldg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaojbez.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaycrfe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxshhgb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqmaloqx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wazwzxrv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hiidkinp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrhtsqp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ccesqlvx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bokjxffg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqzjbko.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pofwuxpv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdetbbmj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2azopdyzr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkxyrzx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2curiljlt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwejgsx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxociet.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xposvxfu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrlcbqu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vehhimrr.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fsakbiwl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gitbjdfl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2aafhlwvt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2kblifswi.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2asosxfgr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ermxowmh.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfrtqrv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2njgtyins.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhurixy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jybyurlv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwqvnss.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcgwrgx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ryiglxao.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhdcgsj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdwgwdm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcncfxyz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdjwwyk.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uszpwjgx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2onjcxieh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwcgukx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpazqmmx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lhmtvpte.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2plwdmdqb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kcloixcl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2awrskjhq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2skvqjmym.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxqxrhe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqxxvds.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkiregm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkbculw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrwmzfm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2satpojyi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdlzrob.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2njbgsbmd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuidzzi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rfaqvhdd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrnnbhz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxwgeir.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcgjmdk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnskhana.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vtetixpu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmbvakx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmtremo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loevzbxy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2buwjtxkl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmrqlns.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2asfspjkf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cliownfg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2usahrnyv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nphthiay.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxszhhqq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxwdhjd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmsvncw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoiehcjr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oadqgacx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qolxomym.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2axtsanri.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpuglnl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqoynpa.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tirizmxz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwtjefa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyclqdx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcxiqof.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoxdgvq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjtfwvn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2algfpnqy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2agifhjul.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vokwgrnm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2szwdvgjx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtzurnk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zewnoklb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2clezmkbi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2auhrhupw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dkopvwro.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcysstg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlrlnaq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hulufarp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuedeht.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tzupzxlm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwgdmql.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aannnggr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xdltonkl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgzmpbj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmapijk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2keoyzvqu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqrsciu.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgfnrrm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vqybkome.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vflhasms.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoctyyd.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rvseqauz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2keoyofnv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvdrbut.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlxjqlf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2niljwmwv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmybkbbu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gfehhsmz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdzvsbq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vliabfpo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlypjgu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpuxbtz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2buiunpvl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2regzmcpu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdwfqbx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsvnjwx.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnsoqii.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2juvbdphr.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mretnotn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrwmrlh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zojsnlpz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zzciujbh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwcvtpg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fldrsqnj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdeodii.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2msashnhr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zghnzgke.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nzybegdh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbetlkkq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pcarflqe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lekqukqu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2krqzyruz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnwmqoj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkqjowa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhpnqfb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2egrdzvna.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2paudrsgh.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkjobbw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwccixzr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ceatextu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2abqljrzd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpxetec.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ablafszr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2njwwlymt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2tghzscwp.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uedqdblr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2efmumqxm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzzxnka.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvtwbuv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jmottnph.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcbdyir.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hntbosyw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2svvvumqf.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2idkilklk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikerywph.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdcqmxi.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2lghdcasa.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwctwwy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2unfqkvyg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxdmzci.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2siahqamg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bayqfovo.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyoqawz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kvwsprtv.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuwpdts.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mixwtgtt.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyajvbj.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxmdipc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfnlznj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcsvsge.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuzddhw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2utjzyrrn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwomfhke.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jdfeggjr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzxasza.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwngdixg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzesmoo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjxbblr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2czpoycen.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkihxit.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkdfrfl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtabsdz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgfmjpa.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2erxctxuk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrlfrtd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuzqqdt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxflntx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zolqpxod.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjvbuvv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pcttzytx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuokwqy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdprfcw.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsihtoc.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2srthurit.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mgovccss.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxqenlx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2btlbngwc.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2louhbjly.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lrabtoqu.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmbprlk.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xopftqbp.html


<!-- 参考信息 -->