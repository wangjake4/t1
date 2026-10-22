代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvqkhoq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmieoavd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlilpof.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2iohotrnu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2fehkllyw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnqrwka.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwkmpir.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmtnojl.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2iipntpaa.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbehtgs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2goqavyxh.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeddcal.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmithqgf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdfjckz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2chrwmfox.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2nhudwmrk.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwvogqc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxjquzb.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fntopdmi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwclmkjo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2imvbvbxg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jetjtxij.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyprmxw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2odadlxsy.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmgsiey.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfftdfmb.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zommawlw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxlxzpv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cabckqxa.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mocnbqiw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqcvzmu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdfokdj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvhhlus.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2eemkkzgo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nmteuusb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vixnlufx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kohooihw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bffnowre.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqbksox.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmserary.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkzjfky.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjilhudm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsrhqhc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wdckrapf.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2attspksw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsileiv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2prycpubt.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsfumbc.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmbqdqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2irssiisn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoblggo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtzrasn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhereze.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnounhp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txksppep.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cirvbwsh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhoymxuu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cmymsiry.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mkygviev.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pkitfbwm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkzqrbu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzudjyl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2mazkucxd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aenvgriz.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhswdwdj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rajtpvdm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2trmtoxrg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2utyaljld.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpoadtp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqiyfbv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvjnrnz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxpecvr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbacvewn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxdpbmo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpvbtue.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bjfqjbap.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eorwiiup.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2gitghvxz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2eloeodcd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pfklifug.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxztvrx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ayluvxqz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbxjjji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iudhzbad.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iebbiwrc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbwiuyq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghubwceo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgehpzy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vehlgdwv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hntthmgm.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcifftw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2unhjirgw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkiczoe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxogpxt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoeulwg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2igpwqdsw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fziuvtsu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfndoqk.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cessyfdt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjbjzie.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zghbrsev.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2pfehtsee.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqetgosj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubojbpsw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnjwgku.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vopcxspk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2dmetajbi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsblbco.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zleolodd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2icypotky.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gobappcc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpsleqt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvgbrqs.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpuvyygc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cjztnmov.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgoppmbe.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhusrko.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mqygtjbv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2moyyghpy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfxabcn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2myescxoh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mivobfyq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgrhryx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2smyordkr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wcscljjp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsacsrk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmihfhm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2owwfxbze.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kginrpql.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhvwuoa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcfvcxr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwkxvsc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fpatovgo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2yivzluyd.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwrscmk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dofvfrai.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ueahdzcl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmhuwvk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lnllvsty.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qihidysj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrrrxjd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwmuowgi.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2dphgzldc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2szstgeea.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2irfryzhd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjepljj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjougxxj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2equmjsta.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lukyrvrs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgsroxo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2axrwwtrb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvkxitx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnnmcap.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2grscmdzp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2giyvtaxv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fjosoqwg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2sqakzdzq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwdkuzy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2dievvxim.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2tgnmftbl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wkmwidyr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqtnesh.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuyfwmn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuprsox.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smibrmnv.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvscbae.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtuustr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2izknkrys.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjjhqmmp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nojbraat.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvsjztg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnabgsrf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2elugtpeb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmawysz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twkpujzh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtllsupe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2areftnsg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brxgjfyo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrkrctw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2utznclrx.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rprtivlv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kifruuza.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdalomm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2grsoebmz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxvikjq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsocplg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoggcjt.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxbvzbs.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfhmago.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxbgiah.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2timpnawk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wypdsmom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykohzrir.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtbxbli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeffwwt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqmkcsc.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnaiigyu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdoewyd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsxdbmn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhlhllv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mlacftsy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjbtsek.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmabazis.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqdshxu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fssrbmvz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqtltzuj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rbglcsva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhvujpr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjauhtt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxdmebc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2dggkyvoz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvptipob.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eebmualj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmfapsi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2aymhhnlk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zetyegwi.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2rebqkxgg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqovrsqb.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgyvmez.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oupvspyt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbxjmbj.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2omrwiwvp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwcoili.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2kveuksqb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yamjktjc.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpletejg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2icgbbogo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2expxzkqx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtbfiik.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwgdxxg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yoqrhcjv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gclipqtj.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzxpaom.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxvugnz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lumoekok.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcuqzzp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2nystookw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmpxvqt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2opnqmatp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2msmsetkb.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbnwfpb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvmexfh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2npfuuqbj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiclvgn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwklxcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zejxeegm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fvlnwevr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuarajw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fqwedbgc.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsrqcvu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhnarov.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnebeap.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhutjjr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuimxrl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwrkaaw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gezzzknd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jnqqgoqf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtnecle.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtpwpju.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2trshddku.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2aoukxivb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yskzdcfa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnsmggy.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrgcaax.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkatiuk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yuprczpa.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2butemaew.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjacbjh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2hqijchqd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzcfisa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfhmfgp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2mekwkznv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wwdurvet.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfntayg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2quyimcmq.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgqskxj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sulpwmyr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfhtbac.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2dotdihhy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmorzkv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuqiwui.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fnohnkjz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbzolms.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2qyncjnlt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpawfzq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rnksgqba.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnvqxvg.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjruijvy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqeflnk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjvcjjv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwnctyf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwhqtuq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lishvrrc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fetehplc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ryaqydrg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkiqbqm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiqlnfp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gybfuykg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqtqjjt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2nznpyizl.html


<!-- 参考信息 -->