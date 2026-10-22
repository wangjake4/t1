代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwtypkw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2giarilqd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuidbdjn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kipusubm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyzftqu.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzdlevo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpbaxnju.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxksspf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbdgpws.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2znizdgjc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsyauhw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fexqbpsi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2seselniy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2akvfibve.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyhtxyz.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnivfkk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsmxufrg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2odigvgsl.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubedjmqu.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yflznhmi.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqnhgbyu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmyqoaa.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2uygyujfp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpztzwy.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsieqod.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2axrkcydn.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzpkibu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsotbta.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwcupbn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqygycos.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvyxrau.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qhooraaf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2asfkhujy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcxasip.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oehxufwj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhesrsyd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjtyhnc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qktiwxce.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2faowlqqb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smapmwra.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrhqtbg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyjhriz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2krakrtgu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2myjgfjuo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fysdivzn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2quznldzq.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2agcekgul.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2twgntaht.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qijkdhla.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gulcukgs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okxwyfkr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2aucvnxvt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ouoyoefk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwfpoxp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2omgiztnd.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smcqtobb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsuddsy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzijkyl.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmtbqog.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvipdjkv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uygpjzqy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfcvksg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dizgvmwa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtmmknr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyoydcr.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vijrixln.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuomvau.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oshucdgc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxltbzla.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cbclsjql.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmgdbes.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoxhwac.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkkrgki.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeycmps.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvenbeek.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tfraxzok.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzrfzde.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcdiqvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyfyfsl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2plifbmmb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vslelaza.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kowppmca.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2szzvdtmk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2egmexeox.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrimedsx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmzyysp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tucnbdwh.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cidrbxpe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhprxboe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2quacgsgn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xllmehvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxdzekp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmfwelg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsazkkxx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlgcujma.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnvedka.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2navmlqek.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2erutguvr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwzjugw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2edgepsst.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2doufwuxy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2kupnrspl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkmuexx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbitqhnr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2untryddt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpqfmqz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqtxcxj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwikkvpw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwcoqpz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdhtbcl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzsbnfy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrlfgmn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xwejtoic.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvlixkc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxssegf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtaghov.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2uvngpsdg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnvgvod.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2forbmfbi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsrelvm.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vmvchtgx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2aczbmctk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npzqtufn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlsbncc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ienugqgd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaptkve.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiosyax.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoxvhdx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ltunliad.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zychrpzq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgzlxgg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2unemcymd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmeitbw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zopihwkx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uscmtvov.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zepgxehw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzolpovz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrfeoib.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2oepynuhl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2olvufaxy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkrpvtp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvznstiz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnpnmae.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaltsuni.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xubgckhp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuedcti.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcnzwnt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpryzktn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2xaebguxq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkxqptt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2evbkvjcv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2etqdhnmp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fopwcoqc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmoamcm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsvsuhv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nmssroga.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrnwlum.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gsctmhbs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyucuzms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tpounzvk.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpxndqx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzftamc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iegucqsu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpjfwzh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmxrake.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yygcnqnn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2upiigysg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpkimce.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcycxri.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zewgreov.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwbgwhq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxqjybo.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpwxjnq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jnakhmhw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wozvmmof.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcwakai.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2igzksibb.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2mifznzmp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2liolzexf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdhlmtm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpduhch.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkffcddt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjznhch.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svnnyouc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrixxuh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzfyzid.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dhraxgkp.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtbjemp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idpuatai.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxrgblj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmefeqyg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lloawraq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wugtqduy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lriirwsy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhofkxij.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qlykrelr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2clgxxpxb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2htsvemdu.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2brmwtnbq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kgoalogx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpszorbr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrtbtaw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvwnjve.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbuffor.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdloogr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dyepqnum.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylduwcob.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gafyrthk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrmkskv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ujenlhgm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2obahitja.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcsufri.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqmtjws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwzjvyw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2skebfzzs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxslqpp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eeszxewk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgfkxpc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2egimourd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgitlly.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2plrpkyyh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cekmbeqo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ykepssas.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgmxdrv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ruziohjj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zscwjbvk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rglbpjni.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmctfuj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2roakudho.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2callmoub.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdmcgsi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cosktyuh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxrafld.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkqriqwk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lyptflgw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpslrcoi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaopaoo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2swezmjfa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2viweezic.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtlvkie.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhbtern.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpxusmt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2siflcqfa.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyyqntw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2adapgbai.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgosxkbs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2quufqljg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjtczmq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnwauen.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2rseadnzp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2doblbkpz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tytxjxxz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxzigtt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkzlqrp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcasanx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgihtgl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2clhvsqpe.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2dvegmjax.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nhykhwte.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rffjjxfn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqywvxkq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgxcxry.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gfivuycc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dchsvpkg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlkmgyj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2aahfsmrz.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuwqrxh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bskbpulq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvckzei.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkqnwhc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kaowebdl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcznvtm.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2otocdlty.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfdumxd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2snwuqbsd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2julobnec.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzwwzeo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2xstmkovq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbaxhgm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nrimhwux.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2urztcwnt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfquwlv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrrpcuy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdhvydl.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhhtxlh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2umjkfxiy.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kuyvoada.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nakgsqrs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmxxknx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbpudov.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkkcdya.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zyogsngs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqjpneb.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjyervr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhrkgl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdadrytb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yheyibbm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2goymtdcw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qdpnecqo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbmpfqt.html


<!-- 参考信息 -->