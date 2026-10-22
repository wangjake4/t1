代发 wailian999

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gtynwgmksq.html

[S29] C：变参函数
来源：http://dali.jinqigfzy.top/Article/details/gtzkclflfu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.meibo888.top/Article/details/gtaznqdfoh.html

[S30] C：头文件保护
来源：http://dali.xylfe.cn/Article/details/gtrobndtwz.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtddzoavqq.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtzjyxagnu.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtomwhqcoa.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gthvxoholg.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtlhsjqcgz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuanzhike.top/Article/details/gtqejlomhk.html

[S32] C++：字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtqtiqzlbz.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gttttanxok.html

[S33] C++：vector 增删
来源：http://dali.316326.xyz/Article/details/gtyqrkmepr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.redwolf501.top/Article/details/gtmdtessvy.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtdfcwgrqz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlrvbsdso.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtsbphrqjz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtcjmlesfn.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtdblyixqe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtqcqmbvqh.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtckwkkfez.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtwnqkcyej.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtepkjrzwk.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtuqivpwor.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtaixskcsc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtxwmxbdih.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gthxczmeqg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtxznbjrrd.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gtxdazwnii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gtadfzasou.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtkzlasfdt.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258.top/Article/details/gtirvxchph.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gtfrkstgcn.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtiplwjqwv.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtfbzuudch.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtisjxdsqi.html

[S45] C++：lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtqjjdaiot.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gtmkjtbgge.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtlzmkkqzd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzvxptjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.gotoacloud.top/Article/details/gtqrhqmzog.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtlpjxddnv.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtfolfozuy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtvxmixqtw.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtnsdhxben.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtprznicrz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtezszqlfl.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gtjiazzyte.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtbtcbjrbw.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtnfmxitjr.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtjuagudqm.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtlsythbaj.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtodydunne.html

[S53] C++：移动语义
来源：http://dali.pycfn.com/Article/details/gtfhllfbma.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtnfeutrfh.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtqulaodhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cucudq.cn/Article/details/gtdzehzlgn.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtdxjssimx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtalsnfzik.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtyqoobnqc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gtypljaxcp.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtcahklijb.html

constexpr int N = 10;
来源：http://dali.hysaishi.cn/Article/details/gtlmnvsrbb.html

[S58] C++：命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtofbxsdvg.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtzqwrgvxr.html

[S59] C++：静态断言
来源：http://dali.jyoumei.cn/Article/details/gtxkctudhq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtrcixwiyy.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtheammcyl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtvrmwphjr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfjvmlios.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtyozlfmas.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwcslyenl.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtkshdcdae.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkirienzy.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfocyqbqq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtesquhftv.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtvhupijwf.html

"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtppmiqunh.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtosvdtsfm.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtdnciogoc.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gtsobodszm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gttazcgbjo.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtdkeyxgjj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtghagytlm.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtegineixb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnbkwrid.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtrbonufjy.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigfzy.top/Article/details/gtmvfpowuo.html

[T09] Kotlin：扩展函数
来源：http://dali.fzhhl.top/Article/details/gtaspturbc.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gtuwpobnuv.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtnbvcfevb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yonumen.top/Article/details/gtpdmqccas.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtqhxlmoiv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtzfsdasev.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtttprofsy.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtlcwlseum.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gtpfrnzjqa.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtmpdguwus.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtseouyyeq.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjdngpzx.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gtvtuenmrn.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtnxittltz.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtsyouijpy.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtfmmrseak.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtpvujemmb.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtecykhpeu.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtvrpfwyct.html

"值: \(b)"
来源：http://dali.haohaochexian.top/Article/details/gtaufxcgih.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gtydqhwhoh.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gtplifvhsx.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtatnkkjhu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtjktqqxds.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gtixgltpfo.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtbwanubcw.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gtuxppifyx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtjwnqiffk.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gtznwhsqus.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtzfjaldlu.html

[T24] Swift：闭包
来源：http://dali.sysykeji.top/Article/details/gtqgdanlar.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gtqwqecuyw.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtpyogmgci.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtvjtnawjj.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuxljpmz.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqaszgufc.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtsukotrpn.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gthhjsgzfy.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtqtqnifjl.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtxpbixxrl.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtsidrzyxg.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtcznowrrv.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtzszkdgck.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtzlrbttqr.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtqpxflvld.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtttcvrhjc.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtpdpeyvtz.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gthnkejaxa.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtlzbomtts.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnqzz.top/Article/details/gtgkhcjghk.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtelwlwxqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtcjmlwdgq.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtdazxgxjt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtatknxfxy.html

[T36] Lua：函数
来源：http://dali.fzhhl.top/Article/details/gtoupgqhai.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gthuprzvix.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gturpincmv.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtrokcakog.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gtjolhwjoa.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtvbbxxhph.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtxnncypqk.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtqczrmxfs.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtkgkuzxxy.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtzlqbqeah.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtleajvzly.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gtqalhghgw.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gtamcianwo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtsqxydews.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtfvetubsg.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtkjzmimjc.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtdelwoyte.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtcpxlmfkn.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtppbujpby.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtxgapoptc.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtwwotemzd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtgnqavxjg.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtleqkjysf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzjcopsni.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtcbzljdlh.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtxjtvzyhz.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtxgeqynzo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtqztsuzze.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtwnsntkyw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtortjvjvr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtkkvlawhz.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtefnqetuw.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtivpypjff.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtcuyfmkrq.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gtxhvcrdzp.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtgcgoceut.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtjcduzjew.html

[T54] Scala：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gtwxoyopde.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtacwbbkay.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfuzljdtw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtdbjgdhco.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtyajpmmww.html

case class User(name: String, age: Int)
来源：http://dali.tanke756.top/Article/details/gtyfrfnvnn.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtmdaueqer.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gtsuvhliym.html

[T58] Scala：函数定义
来源：http://dali.cucudq.cn/Article/details/gtsfzwaple.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuxwghwh.html

[T59] Scala：循环
来源：http://dali.jianghu66.top/Article/details/gtxjygwqqm.html

for (i <- 1 to 10) println(i)
来源：http://dali.316326.xyz/Article/details/gtrilxuyfa.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtpvboksxf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtppbnbtao.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuogdcmyq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtbqmgjxea.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtpvqmmvug.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtprfggjey.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtukahflkk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtrnymwnwy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gtqsaorwqn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhiwuduotai.top/Article/details/gtechinmmr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtigcqkxgi.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtvuldekbi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gtedtbvjto.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gttbgkwboc.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtnavrrxjz.html

[U06] Py：合并两个字典
来源：http://dali.mhx1999.top/Article/details/gtpoyqwkwh.html

{**a, **b}
来源：http://dali.hysaishi.cn/Article/details/gtqdczekod.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsubzoiyb.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gtgtuvccwj.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gtvrayqqxa.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gthtvtfght.html

[U09] Py：字典取最大值的键
来源：http://dali.hammf.cn/Article/details/gtgntheapd.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gthjjtbhda.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gtwzdcxbnf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gthonbnbhb.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtumneatui.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtkncuntge.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.feifeiyinyue.top/Article/details/gtjirzdrmm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gtwnhfrpet.html

[U13] Py：固定长度队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikfbtzkz.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtmbolavxa.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtatbaovas.html

defaultdict(list)
来源：http://dali.shzxlz.cn/Article/details/gtzdcykrmv.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gtbyyojoli.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gtcqvqxooq.html

[U16] Py：命令行参数解析
来源：http://dali.guowangkeji.top/Article/details/gtbjwadcri.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gteaxgzgia.html

[U17] Py：初始化日志
来源：http://dali.zdqjudy.top/Article/details/gtsjpciatq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmhlfsxv.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gtevrrrtwz.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gtvskkbiro.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gtghktheah.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fzhhl.top/Article/details/gtfnfsuzin.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgqoqkmh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtbqgbnepw.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gthuizmfkz.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gtkgrkyzem.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gttuxyeyjm.html

list(zip(*m))
来源：http://dali.guowangkeji.top/Article/details/gtwgovlwmh.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gtyaduooki.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtsbjutzpu.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gtcwdwtrij.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtlptmkvfx.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gtjhsfhsck.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gtfmoudzji.html

[U26] Py：并发下载
来源：http://dali.jinyuanbaomall.cn/Article/details/gttztebyqo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yvedp.cn/Article/details/gtijhkugon.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gtqivrdhdw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtixqvxlup.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gtjfcmusbf.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtrpwlqpzs.html

[U29] Py：属性校验
来源：http://dali.guowangkeji.top/Article/details/gtjfrusgwe.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gtplpxiljh.html

[U30] Py：数据类
来源：http://dali.ydzc1.top/Article/details/gtxmddbivw.html

@dataclass(slots=True)
来源：http://dali.yueranfly.top/Article/details/gtkhxtpwem.html

[U31] Py：单测
来源：http://dali.fzhhl.top/Article/details/gtmhgncvnl.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gtnjikwyrh.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gtzjtygntf.html

ruff format . && ruff check --fix .
来源：http://dali.yuxming.cn/Article/details/gtrixuymvu.html

[U33] Py：打包发布
来源：http://dali.9152youxi.cn/Article/details/gtqgfsexee.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtccpdejwv.html

[U34] Py：判断编码
来源：http://dali.ybcxt.top/Article/details/gtcquxvgve.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtphgagnmt.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gtjtfnafbc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.havefunace.top/Article/details/gtszhnidst.html

[U36] Py：定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtuaxehivn.html

schedule.every(10).minutes.do(job)
来源：http://dali.gzhubu.top/Article/details/gtkdeouvsb.html

[U37] Py：读写 Excel
来源：http://dali.aizwys.cn/Article/details/gthrbtinro.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtucmqhdke.html

[U38] Py：获取脚本所在目录
来源：http://dali.cashguo.top/Article/details/gtbgmutztk.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gttpiegeqx.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gtcrcxkklh.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtxrwcnwvl.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtwgbvojun.html

print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtisomulpp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daria6918.cn/Article/details/gtuajqqfay.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jianghu66.top/Article/details/gtdpwfatwi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmabvfrzf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtpwarvjde.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gtrcdhhokm.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gtqikwgrxn.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gtkpftsael.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gteswqokix.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtqtcgtrfq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gteuqjfluq.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtruolfpkr.html

?string $name = null
来源：http://dali.vqdsnc.cn/Article/details/gtyhdhzlay.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gtpcabbbqx.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gtekscirap.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gtvtipwgqc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hywenlv.cn/Article/details/gtgsyiphbb.html

[U49] PHP：只读属性
来源：http://dali.meibo888.top/Article/details/gttoqylcxw.html

public readonly string $name
来源：http://dali.guowangkeji.top/Article/details/gtrnkarunr.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtgwexzoch.html

public function __construct(private int $id) {}
来源：http://dali.xylfe.cn/Article/details/gtguoeebcf.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtdlpuktds.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gtsyoymits.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgemeiyp.html

$double = fn($x) => $x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtyfumufcy.html


<!-- 参考信息 -->