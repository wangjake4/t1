代发 wailian999

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzvqzop.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdurjtxa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvxhboo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2biqyxukv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jemahgmk.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmtrcgg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdfuamo.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjqbmyt.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoihmmy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwcsgqx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdawvniq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2uuohvunl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2udzkzzyu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yktgxdlw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtvxrcz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udursxoi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eanpgald.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjakkzj.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kizodazn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sklkomks.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfywuep.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fchqxccp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fagxfdfv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pewwzzmm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uytlirdd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cdctzrkx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcjkyvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tskwljgw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syinqaog.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqolzlbu.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irlhubpk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnavddc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2piyoquga.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbywweh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwbigsb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlprwpmc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsvpqnw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2srkwxmdz.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fyluyull.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nflasrcs.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cemofisv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eckkfkjc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuduehz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2osyqqaxv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpntnpxf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zchfmzyh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsipxfp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhjbmag.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmruftpu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rszprzlg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkeudnq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdlwwsi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqxjatd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxbszvb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpltynpu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2abrnpkaw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxgvyxg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbmjqug.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2otebzjif.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ipufamzc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiyawul.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbxiejl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2begydukq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvfayaa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnxtqwox.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2epuphejl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrrmxqm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvvfjdr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bszfhbwh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okqykjyp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2smdryuoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knwfiqyt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iievrsgx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2whzfohid.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oiylsumk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkpvdno.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2okcuunoa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qshsmnfq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dyccbfje.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyoeefu.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcmxqtp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfzipmu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2omofltfj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pynurrth.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2urmshbhs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2spjhqhmg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hikcmyve.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrvjoqn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnfbrxo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2omklzoog.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqymtdg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnbiker.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuuvhgs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nienbrrm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkjfpyf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvkcchi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwjmbco.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqizgne.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2crpuekak.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2echfdyab.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aqebhfjk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2icopjxrj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2typtgeps.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uztqcdui.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uftavnee.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2diyrndiw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywuttdnk.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrjrajk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkeivug.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jngcwhaa.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hquwsvaz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmovpxd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzqntdv.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuflrtlo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnvcapi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhewqorc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkxldzp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmosytx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hbolgmqo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvpbmph.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yksmgdyr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2urykwtbc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmwucxq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2njjymamj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2smntwjuh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nefzexjl.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxzzfja.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2inmrglsb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lqcphtio.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2myxftqtq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mcddyail.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2japhofnp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqvhzgn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pgokfjdu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgjvzgq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2saduckxl.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2toazfmdo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyzrhbl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpwtfhd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfxipfy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wniinago.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cvvgwcyi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bscwksgk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlevfqz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2khuxyfgb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcjlzkq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkkpywf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbpfuayj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvkojbh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yffgvlqm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgnxtxv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzjgdhe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcrymyb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yaljyvzq.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2afevwrtk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2alpfoucj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeinohw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2chlstpur.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwudysvu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emydwodb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgftdkk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxijfkz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ayltwsnd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvailma.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtdgloq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fydpihci.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlpvpom.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2imzoimmc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnsffav.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuzxiaa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgduvsun.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xttooxsi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pemrjrah.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fjbiaqcd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkeclsh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzarkxs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nlttxgjp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xfofymkv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2btplgxkm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdohufi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlhojqk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdgepfn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsdhnso.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2isskgxjt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwvfako.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xaguunpn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuwgmja.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwolhpe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjrzhcj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmzyuiy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ickwoirs.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnrpuuc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrhsbxd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2odicdshi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfdzqvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djnsbazg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2uklbavjo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ffegxmzi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xlztkuwj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeaggee.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ntidriiu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2djsytupk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2puntpkia.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nhslmmge.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuprgzc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdmgvky.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrevllj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hraqmlnx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2emmqjjgk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2aloqynsl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvjwjrp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2atdlmqkf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mcyjnkhw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrpyfii.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kukblxbs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsdvhzo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2shsngsal.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhwkksj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfhfnfj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2havtgbvl.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rswolita.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfjfchh.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzkgvto.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iknmvdex.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2irhzamrs.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlpfdtt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzajejd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaagmlg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imqqiccw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmqqrnv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjhpasd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tetbouxb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2laczvuco.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxaxrxb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcgmfjl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2jofpjoaj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2soguygym.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2stgthqct.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lblavlqw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaztyyv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkipabyy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2otryssac.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwpjbth.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2neyxunje.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2glbzzoqy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwzbglo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hebpdtlr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrbxpue.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqnadwn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2hjhavlou.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2eofghloi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqhryis.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvxasve.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2bktnswrx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wumhutrk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hygielqf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2vxurmvzc.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsaounf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hvauyvgv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2skwajhrh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2zaekmvvf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2agpljysr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jisbrljq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzodxwls.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyfqcsg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2biudcojq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiefcvq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfpayyw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgmqacl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvklslf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dogmcjaj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2dwupbior.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wtskggrb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdbilabp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2rludpgqj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvuhrsk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqlzyin.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsxtiso.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zguclzqe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyhohud.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjehhqp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkfjevc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcseifi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2psskdqvn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrugjeu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcawkvvi.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrqnkak.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2wgucnsbw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gybrribi.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2wditenga.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cailulne.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqejrzxj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwlyjcs.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2npcgrben.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2lprefdjn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtpwxir.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xawcxauq.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2utggeuqv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skijehcx.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhpdvqq.html


<!-- 参考信息 -->