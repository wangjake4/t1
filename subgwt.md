代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiwbunq.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2myhiktmj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoiwmxj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dwiirmws.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtniuxm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pudbfast.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yqisqazn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjtdxcu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2fprkdwfp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yroowskm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjvlcku.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jybifzub.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmudiba.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyekqktz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dluncwxl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcupbhhj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2lnczifgm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvbxkbf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qipnrivq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdaeawp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgxmmuz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmqvjxs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2unimgokk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmtcboe.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxfxwxm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxxuamq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yexwvauq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvthermp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vaetawqi.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbnwssj.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgmlnea.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhhlfge.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbzzbit.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwhdqjm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2crvccpfk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywibzfcz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xugrahpx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjdaews.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzfnlqaw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2recixiqj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqbfeid.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cackbfxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vwyhtdjt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhrwcsq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjkmpzh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgglnzc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kadyznon.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2csoijkui.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnuibjj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2eswiebyb.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oupyixnz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgqtwru.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vezowefk.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2opsdjmip.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxgwxds.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pzafvqzf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkvabff.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwwypoj.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrlhxgj.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vlklgauf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2haqrilrm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmiezov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtiruch.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fhpvvrkc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ngewutoo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqzqncd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vynmpdpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgulwzy.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lyovyhyx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqxtmsw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krajoffc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgythrs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vvckefae.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hexbchkk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjpxjao.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qinctesm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yjveeyjn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvjxhhs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hlypnorz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mofzailg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nemrpijg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujbeur.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgnrcgo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyreceq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhkrwph.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwaiegg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsyrwtfj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2roocshws.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgewisl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfsacbb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zhljnaev.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zclwbmpr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bonvpled.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxjiklp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rihpnwjl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2epcdjhzl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfcjbwe.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zliukawd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrzbkow.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmudvifm.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2whjnwiaw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aopvinur.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaeebtm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oumycjdb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgtwloe.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmlgqsg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2numbdkrb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcqxgvt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mmywumqu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbelpvl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dqydzhhj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzshfnb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2udderwqg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxjkowe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bowtfucx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdvqvwsj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuxflhb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2naixljob.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pncqcrqs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeudmss.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpwjzhf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzxkxbr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2siyfxmcg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnllcum.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcckljh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfrkarc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2gslfsraa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaqivsz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfxwhul.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeupfwwm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fginpqgr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2twfmcmsv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tphdkzwt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2sbaoqsrx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtqiavp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qeytrohg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2txaeykzb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdrsnju.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmgmxiq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2clggacai.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvjnhqz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxyaemv.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmwsole.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwzwqom.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nobghwzc.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2omczvmxx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2oelipbcq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nxivdhcv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axrnawth.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgudatc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erufrsac.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxfnlck.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zuspvnxp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsptakuk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbwkyul.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnwilfd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ikijmndv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlkmuuz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhcyuva.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbyfawx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sxodkllx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gahteiql.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dluqwxoi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mikdionn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwwxcun.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akgfftcx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmxvavb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rukbqivz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzphwyk.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2prnbtkqw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqkjjlh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2joalyeoa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2becetnsk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtvwqun.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwwjghy.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqbodgx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpawpvxx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxwmeik.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuyacqp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqbxshd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2miuwnmdn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xnythrzs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjftnq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxuzxfq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjfqjpl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ykynwodz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zggeavsl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2anjklgpy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsnnbns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpegavpt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udyjalop.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgpbdbv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2myuuvefo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2itafwumu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eaykopvc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fomwomir.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2glbjqmyt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgirdjpm.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2blfqfgys.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvwkkwy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnkfhsc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcrypck.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tazwccrs.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgabaxip.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qeqsfjgi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rieplshx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyxcxuh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2zabodcaq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sxflggve.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrijhqmj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhmrgkl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrcgrba.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hztodlor.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpubiwv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpnmwnd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rntmsldd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsnkcin.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjwpllm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zudefhgg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiutdqru.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2yztocfxh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcriprpi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsolwkd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uamgfgjj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2pudcwepi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbymxdjn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwobuak.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kpucvkwy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2eziwhiod.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfeezvnw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwppppt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwkxkmo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxmkezk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtbrav.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2urdncqrc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoconhv.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmibwtj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcjpnjf.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luybbgea.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2agbnjdhz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbtslnf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldelfddk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2scqojlmc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgknzze.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qohnezig.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcrdspp.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kefcefme.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkbpspi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqiluxe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2uveybrex.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uchmwxke.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnsijtq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iwocpnmg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2baatqlar.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2aduwdngr.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2eaesyirw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqzcnru.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2saybrbrl.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtacdiy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgazuvet.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqgldvt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqxeafh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxlawsj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnehtfd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2drlhkeft.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnteyei.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gzldiibw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2joomaxky.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2igbeyryf.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvmflek.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwmggvm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwgwove.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qdtyvfeb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2owiplqzx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2prcknwdf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvwkyoo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lqavqgjo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnyxjrq.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2htcjuzgg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkkokfs.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iimnyrth.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzuteaa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyqsybk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zavixfli.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yymsemop.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2azyuyfxt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmhideg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzvjpkp.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2narxakcd.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2apucouof.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2uaddmpac.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cshlopyp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxvfuhz.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2crvokqxm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhqibna.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeciqxb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2suvobdci.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsnzbye.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdzrjmk.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbthzhlz.html


<!-- 参考信息 -->