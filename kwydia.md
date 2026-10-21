代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtwcmvnoqd.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtfiuyoyjz.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtjejlaiqm.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gtvnlbktty.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gtjyapckxh.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gttosdvqfc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cheryme.top/Article/details/gtwlcdimwx.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtqcgeajoi.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtpvhtqsjp.html

#define X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybrjkpcb.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtcopqnoxy.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gttjkedsdw.html

#include <iostream>
来源：http://dali.zdqjudy.top/Article/details/gtmocyavem.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shuidangran.top/Article/details/gtqflhqxtk.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gtahantegw.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtnwfsrbqc.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtsyzgumya.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gogol.net.cn/Article/details/gtjbmepqar.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gtywugvicv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtycpxhwup.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtgluhrdsb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtldfqzgrm.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtvdlukata.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtfdfmkmjm.html

[S37] C++：set
来源：http://dali.tanke756.top/Article/details/gturkpskkx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtmrrskhjd.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtxndxuzqr.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtpmyjirgx.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtubbacmua.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtvxsnouyw.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtdtjxrdun.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guannengcc.top/Article/details/gthwmzglce.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtohnbisoz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtcowyolbx.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtacjabtms.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtznoikpbe.html

[S43] C++：智能指针
来源：http://dali.316326.xyz/Article/details/gtuafjvdta.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtsgsvejxu.html

[S44] C++：引用传参
来源：http://dali.shzxlz.cn/Article/details/gtfccgwjib.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtulqwtcpt.html

[S45] C++：lambda
来源：http://dali.xziqi.cn/Article/details/gtvrjypihz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblbcgdas.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtgsjnrhjw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gtjijckwej.html

[S47] C++：结构化绑定遍历
来源：http://dali.tian-w.cn/Article/details/gtsaysxzcg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gtxwkymlhq.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtdrafjegb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtecnsohyn.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtfrzamhqs.html

[S49] C++：写文件
来源：http://dali.sxryk.cn/Article/details/gtmykcpzgi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtgydpuhmx.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtixfdgkut.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtggeobfdf.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtpohlviia.html

static_cast<double>(a) / b
来源：http://dali.hammf.cn/Article/details/gtkmfsvjru.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gttndqnmvs.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuigphdsa.html

[S53] C++：移动语义
来源：http://dali.cucudq.cn/Article/details/gtrgiruixz.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtpujfndhx.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtuajnjdeu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgarvoid.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbrdwzkn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsvcekbj.html

[S56] C++：optional
来源：http://dali.mhx1999.top/Article/details/gtbjsfgsto.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gtkqeumfqk.html

[S57] C++：编译期常量
来源：http://dali.316326.xyz/Article/details/gtamcmdymj.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtrmlgxyax.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtzuvhdgtx.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtvfzjdzrp.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtilatbska.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtkycvvoog.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtwgzaqmeu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtluypipar.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtzjeohrfd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtdchzrhug.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmdolutga.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtewdectkk.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtmkiwplhv.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtfianpyqj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtuclzfara.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtjxyfricc.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtqvuzttdz.html

[T04] Kotlin：空安全
来源：http://dali.tanke756.top/Article/details/gtenpipbcn.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gtosnjzwrh.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtmuljcexl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtpavgiwvm.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gttfenrble.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtlwpkdzmw.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjuuxwyi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yvedp.cn/Article/details/gtgrxnqvcc.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtqotfalfl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiajfvrf.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtcelauxqx.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtvtlskwwu.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gthovmxobb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtydxtnixj.html

[T11] Kotlin：协程
来源：http://dali.mhx1999.top/Article/details/gtrcegozsv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gtgvfuwlny.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtbjdwiumi.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtkkxitbev.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtinrpnqig.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtdijzeruw.html

[T14] Kotlin：循环
来源：http://dali.gaohongyu789.top/Article/details/gtcigctsca.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtexfamqrd.html

[T15] Kotlin：接口
来源：http://dali.birdmap.top/Article/details/gtmgnbsgjd.html

interface Shape { fun area(): Double }
来源：http://dali.daria6918.cn/Article/details/gtlwlcubzw.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtvwpkejlz.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmfnapbo.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtstrhggoc.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtdymzlelp.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtnkfmyszs.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxztdbpz.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtxznzfjvm.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gttwbgxxrc.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtakzzqbxk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gthzepdszj.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gtpvrtaevx.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gterbyzpab.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gtmeexatfu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.daria6918.cn/Article/details/gtqjiskrrk.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuodnhzft.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnqzz.top/Article/details/gtdhyxqqow.html

[T24] Swift：闭包
来源：http://dali.yj202588.top/Article/details/gtqrjmfnzs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtydoisszq.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtfiuhpnlh.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gtqsbsrtlo.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtszqhisik.html

class A: Base { override func f() {} }
来源：http://dali.ppjwa.cn/Article/details/gtivqrkljm.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtamvbccpu.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtjqjkbhiu.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtrgnkoqef.html

enum Color { case red, green }
来源：http://dali.yongpay.top/Article/details/gttrhjyzxe.html

[T29] Swift：guard 提前返回
来源：http://dali.sxryk.cn/Article/details/gtnlknrdrr.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gtbwttoqlt.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gtsyabwiip.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtksoztxnd.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtlknbpzak.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtcrxsmdpw.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtigewobut.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmnjdgrdj.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtxroxrzmg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gtyfzzpmli.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gtpgklmkvt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtlzopcmck.html

[T35] Lua：字典表
来源：http://dali.haohaochexian.top/Article/details/gtrkggeklx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ehwqpu.com/Article/details/gtgrcavopm.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtaupsfjig.html

function add(a, b) return a + b end
来源：http://dali.ybcxt.top/Article/details/gtmveopztw.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtvlwnzgqq.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gtotazyifz.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtgzjkhovk.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtogsxyqzd.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtjvskwqqn.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtyeoytskh.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gttawxvbys.html

setmetatable({}, { __index = base })
来源：http://dali.shuidangran.top/Article/details/gtbdcarxtb.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtqegcisfc.html

print "Hello\n";
来源：http://dali.yj202588.top/Article/details/gtyykxdpdp.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gtxwsjjboh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtuqpepoqg.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtcvoxtmde.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtvqiposse.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gtlncahlbo.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtkwzgnndu.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gttojdmtlr.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gtqrzftbol.html

[T46] Perl：哈希操作
来源：http://dali.c1oappe.top/Article/details/gtrteejfzu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtlfunjvfv.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtrxazqqbj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gttyxlidgc.html

[T48] Perl：正则替换
来源：http://dali.yueranfly.top/Article/details/gtbrmuywey.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtvbxnfxsa.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gtsnjboebu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtyxzjtwbr.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtgewobmzg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gttiaznjya.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gzhubu.top/Article/details/gtjzywjxnh.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtszqpvikt.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gttrogyiwu.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gttsvnikhv.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtofyupfsx.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gtliwgdbix.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtvkrmlqgw.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtjfwuqrbk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aizwys.cn/Article/details/gtqqcyahqr.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtvqysobui.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gtndlmqrvh.html

[T56] Scala：样例类
来源：http://dali.cucudq.cn/Article/details/gtwiojsyoh.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtfrqtayun.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtecnnpqwm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fzhhl.top/Article/details/gtczbashwe.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gttnceuxko.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtxluflyfc.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtbyivndut.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gtilrdvhtr.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gtbofafxcp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gthkdgcrai.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvwfwdevn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtxzdjcyhr.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmfebqfdy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gtvwiuuohr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gtqoxchdov.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtdrxcsmge.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtwusygtfh.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gtipbijcmq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gturbjhvtm.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gtmjkkrxfp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gtoattlipg.html

[U05] Py：列表去重且保序
来源：http://dali.jlsjyb.cn/Article/details/gtkeqqxupo.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbalhwzss.html

[U06] Py：合并两个字典
来源：http://dali.xuetiantiany.cn/Article/details/gttrznjjul.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtazcqkosc.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtbhknwphj.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gtidmxpejz.html

[U08] Py：展平二维列表
来源：http://dali.snrcjt.cn/Article/details/gtmucesxhd.html

[y for x in nested for y in x]
来源：http://dali.hysaishi.cn/Article/details/gttoljyfrs.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gtyajddrcp.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gtcdzzfcuq.html

[U10] Py：按值排序字典
来源：http://dali.yongpay.top/Article/details/gtipsuknen.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtlvkmivts.html

[U11] Py：生成器表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgqhgrzw.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gtrkmglbuj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtswpxvsyt.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gtzrastgwd.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gthwgsvurv.html

deque(maxlen=10)
来源：http://dali.yanxiufei.cn/Article/details/gtrsovjtdx.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gtbalvtohv.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtuijyship.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gthpefgcxp.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtjxhfqubj.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtuzpmdojw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aizwys.cn/Article/details/gtceyhkenf.html

[U17] Py：初始化日志
来源：http://dali.jiagoushi.top/Article/details/gtaedmxpib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yonumen.top/Article/details/gtrjmptxij.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gtmmbaxpra.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gtjesmgogj.html

[U19] Py：正则替换带回调
来源：http://dali.jinyuanbaomall.cn/Article/details/gttscjacrh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gtpvxxugag.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtbznhokag.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xinyue.icu/Article/details/gtdecfnztv.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtcamulcvq.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtbraoxdlz.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtaxrbucxu.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gtfzaqduqu.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtpxyjgbar.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gtmdsjcwqa.html

[U24] Py：路径操作
来源：http://dali.hnxiangtu.top/Article/details/gtyefzgshe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtmlcufbxn.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gtqebmgcid.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gtpgcjtpge.html

[U26] Py：并发下载
来源：http://dali.mhx1999.top/Article/details/gtksazeggo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gtttjbkbux.html

[U27] Py：异步 HTTP
来源：http://dali.bjfxy.top/Article/details/gtxeqlfycp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteejbkbwt.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtiglfprun.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtqxtyshol.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gtqazitjtq.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtgdloiswd.html

[U30] Py：数据类
来源：http://dali.jyoumei.cn/Article/details/gtfcefsebc.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtnnmesquu.html

[U31] Py：单测
来源：http://dali.shangyingyoupin.top/Article/details/gtwqqmmtek.html

python -m pytest -q
来源：http://dali.chenjidiqi.icu/Article/details/gtaccgdopz.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcphgiecq.html

ruff format . && ruff check --fix .
来源：http://dali.jinqigufen.top/Article/details/gtyzhenexk.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtzzghyfnt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtupipfasu.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtysmwjwia.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gtgoicykqa.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gtmsaffabt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gttvoscpmm.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtpgxjtsmn.html

schedule.every(10).minutes.do(job)
来源：http://dali.daxiang520.top/Article/details/gtyzmhahcs.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gtrowwdqod.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenjidiqi.icu/Article/details/gtezyxkvsc.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuanzhike.top/Article/details/gtdzzegbly.html

Path(__file__).resolve().parent
来源：http://dali.jiagoushi.top/Article/details/gtvulqptrd.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtijmatule.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gtqowpuahy.html

[U40] Py：打印到标准错误
来源：http://dali.hysaishi.cn/Article/details/gtckrrrzsx.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtembartam.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtaolnmhds.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gtrlguruuh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zycfv.cn/Article/details/gttarousgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gthjhryczr.html

[U43] PHP：声明命名空间
来源：http://dali.0kj1m.cn/Article/details/gtyeguflur.html

namespace App\Http;
来源：http://dali.hnxiangtu.top/Article/details/gtmrddpczj.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtwvfespyg.html

declare(strict_types=1);
来源：http://dali.jinqigufen.top/Article/details/gttffysozz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.birdmap.top/Article/details/gtjdjcwsof.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtndtecicl.html

[U46] PHP：可空类型
来源：http://dali.svipenyu.cn/Article/details/gtouvjvrcu.html

?string $name = null
来源：http://dali.yanxiufei.cn/Article/details/gtvoncxzdw.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gttitpzlul.html

int|string $id
来源：http://dali.cdnleiting.top/Article/details/gtfjiokymh.html

[U48] PHP：纯枚举
来源：http://dali.bjfxy.top/Article/details/gtjsvdklbp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tian-w.cn/Article/details/gtzrikvnop.html

[U49] PHP：只读属性
来源：http://dali.zdqjudy.top/Article/details/gtqgszikxf.html

public readonly string $name
来源：http://dali.tanke756.top/Article/details/gtdlzjgqsg.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gtiznuzpwh.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gtfogjszlg.html


<!-- 参考信息 -->