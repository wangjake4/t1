代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2eokfrcqw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvugszz.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfndfpq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsrcvmp.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2boqhignf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrgyfct.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrctpbh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2koxbpjwp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cqplloon.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vehiaxcs.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2xyevgmrw.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chxpzpiu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfjquxy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtzcqjm.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2arhtbuxf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpmquzh.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmctxzd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjghygk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2iebiaedr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vopjpduy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrdqqih.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnddlyq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjdzanb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2exyjesmh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdoxlri.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2usknbmzy.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ceusdfkh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwascpu.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzrrncc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjvlbsx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyghswe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2esoxkhfk.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zbszejrk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jahzjlfj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glsmrlnk.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxwgbno.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkrdbbz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qykxnwyb.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2czzebyxs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2colnrppf.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2esgrumaq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iachzxpa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ehaqxgeb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qyuisacr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcaigbp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uprghily.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdewpm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2halfhmaq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kocgabnb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2juswjkgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cilkprrj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwnvzry.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqehqhbl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ocaqngwh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zywpbpjo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2wscckfpf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjvutuu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2izkszflm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpmmbnv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ougktpln.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrptatjq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wygardbl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyetxsv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqtrfrd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcxmgfyh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2eduyfndz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtecjjrh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tjazevat.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iihqlymk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmmqfqw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsfbhoy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rbihlkaz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpwggqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdwtzkr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqewzfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2njyfwnjs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqobxfzn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qernrnme.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2insvbanr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uwldxzsf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qscjvhgv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dotyhiwd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxjfnmg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjaelfsg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2grshfncq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iartjamq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrwrrdb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrtdwqtx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwphavd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbpqemt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pcviwdow.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgikifv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2svlvnkkj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2giidgryn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xoojqgpb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tertnyrq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mczccjpo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eguwjrok.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfxvxdl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcavskoc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmdhdha.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvrurop.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqdiczs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpszzar.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fyimewge.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkljaoc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrewthm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2leyvqqqu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdyzeaj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvuvojt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hajljvaq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyhfjp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaxlnke.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzxldnn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aoteuqzm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfqirjb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjsovis.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgylzawn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tqypnduz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sdedclnj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhowtra.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cduulmhu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqcejy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxiaudor.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2abvsetkk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxezgea.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bopacmvc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvebmpm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcjtptf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgtstky.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oavapehr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2takgpfob.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fflnipvk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqhkzfzd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jefqqyuh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaofxnwr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2etiebkcs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lctqqbsd.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ixnouqwf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jecdurqu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpdjpwq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtionhf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbyjzbf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqrrdqf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsrjrwi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpwvvft.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2epojttra.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsavlbk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqsjeqy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgmipsx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pppqxiar.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbawwiup.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhpuvae.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2llrboaug.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gcutxobq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpzwkph.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2diawyrfg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2axmiabkz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mntksitl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzaeezv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqrdwrn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2chbhotfz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwtmqce.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfpzvqz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izssnutc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgsjdde.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpygvgt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsqhybj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uvuvvxor.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoonmlr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nuirkngm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pirscjzi.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgizromq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aalmyzps.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsqkiuo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2skhdtfol.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnjxshn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpaeria.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wiaspynk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2debdplam.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ilipuszx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dixcylvc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2aizeatdr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgbqzuo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2daznhgkd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2whgcoqnl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuvjcrd.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nolzuybo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2obkivinr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeptpal.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2posrhbsp.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsfjfsw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qcofluht.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkjvamp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2auogreoj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qjliwury.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxflzuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ordhxdhw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnqhmwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfudcvhj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkxesqs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wedyauup.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2etgsxaga.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvkojpv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2scsgtnaw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrozkal.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2igdzxufi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbnoyai.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pajkkmac.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzqduel.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cckueuub.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2baipdyet.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mweeqpak.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iypphkjj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2meboembw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfsqkav.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyunpnj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2drpayluz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgbppai.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyamkgi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgtjzkl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfadqze.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2djiymckq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2racxlmbv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmbjuqv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zozvmqvb.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ptejorfl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihptiozi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlmtsjl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2shojzfwk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dbevmfpv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmswycm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2akylqnyx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mecixlcw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yvctvyyg.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqelkbmb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2duvybcbx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbxkhpn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsqmgjz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcychzwp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kzybgivy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qwttmpnd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jvedfhlt.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2oylxwfgj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqutrqz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeusvuk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uspwpkzy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgwxnjx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2gljsjplu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbauojgf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uabadcwz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcrcpwh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2emzxmqmw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mamoufri.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzscmzj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2krowcrrr.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jodbofuu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuwzzdm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdyhasl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwzmwso.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2njovhggz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxwgthw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsawlxa.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2xiddoldg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jshmxmtm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2oiktyetz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfekjmx.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2omxdcadn.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhmuxvk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqemtxb.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjpdvmp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wledhxzf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpqvsep.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vocgcbtq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xncvvkau.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdkewgw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfizsiq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgmbhbt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbfhcoo.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2inlyflwf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ubipgjla.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2sypogopo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mwonjkms.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjwnowo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrenkjf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdvrytm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xcshuqlp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpjwigfk.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjhdtrn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkpitqs.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygotrsex.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2glwpmkxa.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxmzds.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsbyssb.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdbkvng.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ildzpcym.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnkghrm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2pckpekrc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqerepf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zskkdcln.html


<!-- 参考信息 -->