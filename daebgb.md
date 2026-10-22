代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2usiklkeo.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsvqzmq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdcatni.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxjmoxy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2obahydbl.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfhclak.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2lafsizob.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2oayxuahg.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2breexdgw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqawjln.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2faibmval.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnojmry.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2azywqhqf.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wixxavyp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jscjiqhu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgmumyq.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vwialtte.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhesxoy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbevznb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2umimpwge.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxtorjv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onqfniio.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2reujepyz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lzghcqbk.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xupxqugg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwacryfk.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrpfpbp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwpbmjg.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiuiqix.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2toykdeid.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pacaijqs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uygkjvgg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2admellba.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2buzellpe.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhbirou.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkhbman.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfmmgak.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ccorszmb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxjudoc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2exltmlnz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzipzso.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gyssfjin.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwvjhty.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2clwwxafp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2wylltyiu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wocpilim.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsxpxcp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgawpxsi.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2soojzkui.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zhrwwxek.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuexwmf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuejdum.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyiarcu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnlvssr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgjhcuc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzsivkq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqdmedm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbelkwg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pelxiutq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kndfbfjm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmscrlr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2iumlkjuw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lytgvczf.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqsnpxu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yupigvhv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjuajyr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fysyqhud.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dklzygwy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kudvruav.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zjeeiumc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxfikxd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bicnehsz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjzkapn.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rejakudv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qprtnkct.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sfedmsce.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnruuxk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2urcrqrti.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2sysliydm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpydqdmw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zilbadwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tskbhnjm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2makgwzui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqmhgoib.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsecrnd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qswjrflr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aypwgixc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2akxmcfeq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vcporxrp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgwhvgo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2bipjxhey.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfczsals.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfuhcsc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2crfspame.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwjmgdp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2luiuwaxd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2plppjyxs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmwvcjx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2upbqwtbd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qteoichf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyzicnk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mascblij.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkxwycb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyfohey.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjvfbei.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xitvbpsl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2arctqgpn.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zepdaaei.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2clydrccj.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzleuhx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxepxt.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xesnxyrl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkjpqdw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyiupfqy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqmjzgp.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpkvlex.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2paghkzpz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uomaribe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uznltual.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cfayzvdu.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtefbxu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2objgyqmr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwmakvn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqiyxhi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbgtahd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvutsary.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pnltciun.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2btryomrh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkkqwwx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwydyiio.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrmxmba.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmcidcj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wzetqwep.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpvuryt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhjcbvc.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkunnhtl.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ekmpokai.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wixgbqwe.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2odxhcctl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zezflmrz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aihbnuaz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2irinycks.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdzexiu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhenthmh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqsgwzv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mktkcijo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyzfrpj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lukkhnrh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxgiswq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cawkkwql.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjxzsve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaizfke.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2afdazzgg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utkpqhrk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhydhqv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuofltw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkrqunz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2auvtnsbr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2adsminme.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdngic.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vullkfyh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2taoadmxy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2eicaried.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fuowkthd.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeyexpq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aldqhgfe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2urutommc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2satmqaas.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfqwtm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dydxbnny.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qicatzbr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdqyfzs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ravppmtk.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvcohpt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvvnuvl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhxsrbr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iesmsrcj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxwhsbd.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcxggtl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppanupva.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccgkuxod.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqdzelh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vutzjvxb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2oajfkreh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqxsiot.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqdeplp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2suzwbbqc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2valdcmop.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2avovcwjg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhgcnei.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqhokmt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oghgmmtd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ticmnukq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yzfxixia.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dasdrysm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zztdocrk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmujauj.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dpleaewq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdkltwh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2toaeegjc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2raaibkug.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2btishorl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdjeruu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2oymxxorz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2efpzaehb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyqycdm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2abjndljw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2egmesron.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gttfvgfh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2swdizasm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfufhqw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxxjjvh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kxemtbnv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkovurii.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mexgfrym.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2izysahul.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tefzsxzi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2msybcckx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnvykml.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dztzwjpc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqicgnnc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2onnqrdif.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmsxayd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfwbwba.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xezrwqbe.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wezzotce.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vaynvbtc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ymggkvhj.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2owggbung.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lczgqftc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kwoakpdj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfoayve.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbpanzz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnkhxmy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjejcpy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvkxfejv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaonvpd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbxwnvj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkupjrv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2egfueoyy.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gwboyfyk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfeznxa.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pzywutev.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fiikvucs.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyirnjm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnzavbd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlobffl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulewmtc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2snenmilb.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxorely.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoxjavr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjoukbo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmtydzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gjfeasee.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhkcenk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2csvrxmvw.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qvibxpfg.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjgnzvd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wkviwfoz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxghycya.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2edsflqnq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bpihrnfb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxwfnx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbtwzwk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zynzyoun.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gxogvers.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlshkjx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvyruaf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2atlkyqdz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdvcoev.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uecojfsg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2lerfzwpc.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkmmwdl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2reyhomqr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjcotzn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtfmimk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgebttnx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzkbsvi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zskybiyk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2louzeshl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnpcndf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vubaykqh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2gabuuvgc.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2rkagsddv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2inoveshd.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2vccuduvw.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aoegfeoy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uftwfqka.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rymexmad.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwdrjll.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2obozmead.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeojefft.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvjshou.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2usrqasyh.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2elmuowsc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyymbymn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfetcnb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mykazrnb.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgkezog.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ysknlpoj.html


<!-- 参考信息 -->