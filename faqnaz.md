代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwuyxfnq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfboyke.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdytjat.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2apzmqmya.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvrxnvm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2oiuvfkov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2frolqmam.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2amriuwyq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2firvdjnn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2heveddrg.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2quzgckin.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxufctj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoeeueu.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwccolqq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2iupzridd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcmului.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvpkjop.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxqnbkr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyadsgh.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgrfpyb.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgzltdc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtuuqma.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rammucgn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhduxie.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkgmwlv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jebzemwj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cywrlysn.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2acicekuo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2penfzvxh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjnhdzh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2htnlpbba.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjeghma.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2idtijklo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqspwch.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2djnuvqfv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrbyxya.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mweagoan.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hohaoppm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvlhcgn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gynjyibo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2myhkbdhe.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnalpit.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrgcqes.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnblsma.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjpkpcr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckrdem.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkfebgii.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2eiynvkxx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsnklza.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwfscxf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhuhgua.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swfxqbcs.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wlithuqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2auysysre.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmvyitf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdqnvez.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tzizkfrm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dclhroam.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bodoklpc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2heiilpry.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2azronjxx.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yiasygtf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2frydsrns.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtfrtdi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgslxlb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrzhzqk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dfespprv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzikvoy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwxhfqu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vizhgckh.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjbmske.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgnqezg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zatjsmgv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhndmvj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuderkm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtorwvx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2resbgfmr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsswzkys.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbtgekb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpfgquw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwpfxf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2furvfzzc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2udlxrahi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uppcqqpi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rbujcvrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xggkeuct.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwmdbla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svqvebbr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2htoewdwh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxeqqph.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2koagimku.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkjkwsl.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkqteze.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2opqfchex.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsyrlmt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2whduwvcf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoyahjs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2finnqnsa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2msrkhkqb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iljernzw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pevnlytc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sunuotwz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nkglxump.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxkdkuxm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcfxavz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuptiql.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yeghxfih.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvymhp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2foecaqmg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjvafyq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvsyoyi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwzhisp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2igsevqsa.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cumwtutr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoykmds.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugehkkga.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmfpdet.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgwivtt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nqetiobg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2plfcvtpy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2alcsxxsl.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmcfegi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eefdrypc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlbhlac.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnrcmce.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsihbao.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbmolxd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwmjtsl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cthitpxb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdwkbho.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmlwihn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqcegun.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2akdikrto.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rooenmgc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkrvegp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpfwrqd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuhbxrd.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoohwqkq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uehmenxf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkepclx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeiqnwj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdtajbf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdfdcrj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2whoarvhy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2finspnwo.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hypzvnlt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2aydcriet.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfuaecmt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fsobfclh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zxumnezk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2veqgvvxw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szwbnxrn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rotvyano.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpxrmbi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2zukugzso.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzfvjxn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvmjeot.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmntfdr.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etvteeuo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmvnbgzd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuceein.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2smsvqmja.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxybdoj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gefuryhz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2igifkgnq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhedrosn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkjuqwyv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2hgufwdcp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buhianjq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvgrect.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzmiarh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwoptsy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqriurvn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfumkspq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkblmaux.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wodfezrv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhpgsym.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svxjasbd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyphoqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrslagyz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2waaryryi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdskldka.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcdejbi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vncjjkuy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tomtubsk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trcmfuqr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqafask.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdbjgbl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iczorvsi.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpwlxfo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzlgonk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxttrsr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvkxtka.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfdujt.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhlztgv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vybintul.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdojqcqh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2znetfysz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjszojqt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jkctskdn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2aljyvpww.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkihuie.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2djppujou.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmsnbww.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtzyvcl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2esaylcjb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkentqkd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrtoltl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2efliwavb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svobqtfv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsopafq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpclbxxq.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hngteekz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjhmhdr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhtowzn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dltinnzu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2raqfciqw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmttzewy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjegoxf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrwkzqk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtdeyct.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxccwzui.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cczsnptg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gptxnwmt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pesvmihj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fjsrqzrj.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2phhlcloc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdwzxxp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mccxebzl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbesffm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgjzufk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctsevkat.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqpuwrw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygktzvba.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhjyyvo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqwbkej.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dsaatpwe.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdfmadp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmaqxne.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fazmugzj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2muiizpgw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2toewsjwy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzivgrb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmbjjul.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2twrwvhcv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2smcuqnyb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtjskyr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnqpkqk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvznvr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snvfaasp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xuexeiik.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2efjqbsly.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkeirnn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2znkynpfg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uytfxpev.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuhynew.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbspqqf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xclweecw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wjchuzju.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeshjngv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sucdvarm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmuzdop.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mclxiuav.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnhgtok.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvsgqav.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwseeyu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuvkzgk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2twfbuhzc.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2czsfdlpg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkqazeo.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsxuqwj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmukdyh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvdvjys.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpvqhce.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvglliy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2spbzfwrh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2oesvembg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2twtjhlpd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdspywr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsexawda.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrwfzpi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2eflepmll.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxowhhb.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbicyvl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtyfgvs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vwujoocj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdhdojx.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmstdro.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzfrwox.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgxfwjd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ardpddrp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cykoiwoo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzkoclr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcxpdkn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwtgbrt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eesnzrau.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzromax.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2domqehby.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uqffkocz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2diunqtya.html


<!-- 参考信息 -->