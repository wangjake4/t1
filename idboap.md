代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gttyunqguz.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtnurhmkxk.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtlfjzmtnw.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjippknvk.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtwxhcbxhj.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtumageesk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.pengpengdd.cyou/Article/details/gtvqbgbnqj.html

[S30] C：头文件保护
来源：http://dali.ehwqpu.com/Article/details/gtbkyvnvkg.html

#ifndef X_H
来源：http://dali.quarkkingdee.top/Article/details/gtaymlukci.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gthptsugdb.html

#endif
来源：http://dali.yonumen.top/Article/details/gtltqdhzun.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmcootrq.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtfjysebmx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gteppmpagf.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtyoxhwpyo.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gtqflpzcmq.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gtxwxilylz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtzdzixekr.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtcbzqxvng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtlisxfgco.html

[S35] C++：map
来源：http://dali.jlsjyb.cn/Article/details/gtcogydajn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtxejiilap.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtvazwhouz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtgjzdvvys.html

[S37] C++：set
来源：http://dali.ydzc1.top/Article/details/gtjcyjdpmz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtvbhalfaf.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtovftuodt.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwftwijhh.html

[S39] C++：自定义比较器排序
来源：http://dali.sweek.top/Article/details/gtswjfocoz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gthawtecda.html

[S40] C++：查找元素
来源：http://dali.aibaodan.cn/Article/details/gtczjnrjey.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtgpohhasl.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtaelqnkwd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtnziuxnur.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtzqpbishq.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtmqbwgqdh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtftzlgmgu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgliugri.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtybndkgmn.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtwqvqnpmy.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtsauhtwta.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gtchmbtuyg.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtjxheusvz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gtipdkyvbu.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtuahrbaon.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtmopqnepn.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtbrduwiba.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gttcirvwjf.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gtazdiqjqe.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gtnmktgmvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtwbhmvuoy.html

[S50] C++：格式化数字
来源：http://dali.sweek.top/Article/details/gtsfxbqqja.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtwxgtjtqm.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtwrbryitn.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqenmyqm.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gteobmljct.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtpsbkubja.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtpuglvaiq.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtunoyrymo.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtuivhiyrv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvsvwydr.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gtzrzyyohl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtwpghsocu.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtmbmmtxrh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtjbylutra.html

[S57] C++：编译期常量
来源：http://dali.xziqi.cn/Article/details/gtqavhnjxv.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtgymjpcup.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtrmfczwue.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtpekxflsm.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gttaatuqup.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmuqmgkn.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258888.top/Article/details/gtmgkaxdhx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtbhkthugq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtsulmnbpr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gthzcjereg.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gteydamzoz.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtuhvlfgdo.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtaltzkxkd.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtwxqdkmcc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtbjsjdnlh.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtosfytkoy.html

"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtzsloswat.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtzltkmjni.html

val n: String? = null;  n?.length
来源：http://dali.daria6918.cn/Article/details/gtddmxjdlj.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtpkfaukek.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtybeqbbkx.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjqffybh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtvsgsvkug.html

[T07] Kotlin：集合过滤
来源：http://dali.yongpay.top/Article/details/gtdggrmiom.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.havefunace.top/Article/details/gtklnkcfcf.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtkyhopeuw.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtbxkbqbom.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtrydrqgaj.html

fun String.exclaim() = this + "!"
来源：http://dali.aibaodan.cn/Article/details/gtmqwhcndr.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gttrjwqupk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtqajsavav.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtgfyyghvy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtnmfyshtj.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gtomzksqdj.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtnzgygfhl.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtblbkbmev.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtehdawrcn.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gtwdxwxupk.html

for (i in 1..10) println(i)
来源：http://dali.cdnleiting.top/Article/details/gtqayzcplg.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gtuvylbmbi.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtnxbnpvol.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gtbmdlmuor.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtuemwsfjy.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtnekqvipm.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gtddaoqsjx.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtilwfqsqb.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuudoofkg.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gtxeobpsit.html

if let n = opt { print(n) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmatlxyvn.html

[T20] Swift：数组操作
来源：http://dali.cqqwz.cn/Article/details/gtihivxiru.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gtcmftxqje.html

[T21] Swift：遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtrrefbytg.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gtqcaloqko.html

[T22] Swift：字典
来源：http://dali.hnqzz.top/Article/details/gtduoznvgq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gtobfjrhmn.html

[T23] Swift：函数
来源：http://dali.hnqzz.top/Article/details/gtwlrrbbxq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gtcwcuuyka.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtcmyysaks.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtucwwffha.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtvtdezvpm.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtqzjvulbc.html

[T26] Swift：类与重写
来源：http://dali.zycfv.cn/Article/details/gtmdmifyzf.html

class A: Base { override func f() {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtwaefbimj.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtohckumgo.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtrdldqtmq.html

[T28] Swift：枚举
来源：http://dali.jqgfzy.top/Article/details/gtbjuchgaf.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtgozajxkz.html

[T29] Swift：guard 提前返回
来源：http://dali.cqqwz.cn/Article/details/gtbohmwptt.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gtwbptyrtn.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtaqzkduks.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gtqietjljg.html

[T31] Lua：Hello World
来源：http://dali.hammf.cn/Article/details/gtgtfgxfbx.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtwiwpfiom.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtalszrffm.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtpbhreatw.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllsajkdb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtdkvumuus.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtofmvawfc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtflfjnrvx.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gthtdkhfye.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zdqjudy.top/Article/details/gtwfcztbjy.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gtrqvutpbl.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtqwucwocx.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtdmocvsli.html

"a" .. "b"
来源：http://dali.aibaodan.cn/Article/details/gthlotzwhp.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtaudjdoep.html

if x > 0 then print("正") end
来源：http://dali.sxryk.cn/Article/details/gtadlhbosy.html

[T39] Lua：模式匹配
来源：http://dali.fzhhl.top/Article/details/gtanfcattd.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtwbaomtwk.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtgyvxgxmy.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtiqvzpibj.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtpgjahcqa.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gtetwnetws.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtqbwbzsdq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtrsrzaelo.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtunnzujnp.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gtbvjnpppg.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gtgzjgczqd.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gthszsumqa.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtkfdnmihp.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtmxbrkrtk.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gteiputbnr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gtoumnytuu.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gtgsrnqizz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guowangkeji.top/Article/details/gtctokooeo.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtonjxxzsl.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gtvqtapyvb.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtwphytotv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtlczakkdm.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gttdhatkbg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpizkisto.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gtqptktpea.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtmmyebdzo.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhhmmgxq.html

[T52] Scala：变量
来源：http://dali.mhx1999.top/Article/details/gtlvrhadtp.html

val a = 1;  var b = 2
来源：http://dali.hywenlv.cn/Article/details/gtdsqwnwoe.html

[T53] Scala：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtoiwwfjgv.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtqbprlfeq.html

[T54] Scala：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcscavof.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtzwaktbhm.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtfiapdgiz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtncxtxkuf.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gteybtnbyw.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtmsmgqtaj.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtfsjecwcd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtglpewesx.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtvfrmnlnx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gttqcpytxs.html

[T59] Scala：循环
来源：http://dali.shzxlz.cn/Article/details/gtudpyolvi.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbvecfne.html

[T60] Scala：折叠
来源：http://dali.kuanghao11.cn/Article/details/gtzgbbkvyg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtzpushgkx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtxdbakjxp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtfthabdbp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtyvbcpwox.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtkmyqycwd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtamarvzmd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtlzlxbrdp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.wangdashe.top/Article/details/gtkzpdyqrh.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gtmrpbidbg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gtftkhsnsj.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtluuqjxqz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gthcerqote.html

[U05] Py：列表去重且保序
来源：http://dali.dianchejie.cn/Article/details/gtrkccdnvg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtxumwfdsq.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gtgvyfsokh.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtmdhceaxb.html

[U07] Py：反转字典键值
来源：http://dali.gaohongyu789.top/Article/details/gthnifwuqv.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtrfwfuobb.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gttnkzhndu.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtpnbtdhsv.html

[U09] Py：字典取最大值的键
来源：http://dali.sxryk.cn/Article/details/gtlsqategd.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtegndnyuz.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gtyyramnel.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gtvmhnotyq.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtyxcnctfk.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtklqexrxk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.9152youxi.cn/Article/details/gtadmgybby.html

Counter(arr).most_common(3)
来源：http://dali.yonumen.top/Article/details/gtxxhyowhd.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gtvrfpraup.html

deque(maxlen=10)
来源：http://dali.shzxlz.cn/Article/details/gtpulgddar.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gtsmyilvuz.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gtydixncqt.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtdszorzjr.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbfavcxw.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gthtjczkky.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtnohygpch.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gtldtudgqs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj202588.top/Article/details/gtwzcpuruk.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtrrwhlmzh.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtnpjtntcn.html

[U19] Py：正则替换带回调
来源：http://dali.mhx1999.top/Article/details/gtnqvlyuni.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gtmmszztzb.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtliefmtkm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gtmdxequag.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuxming.cn/Article/details/gtwanbpjyr.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gtwjfamhqg.html

[U22] Py：矩阵转置
来源：http://dali.zdqjudy.top/Article/details/gtogbhfkot.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gtuwpvmqfj.html

[U23] Py：分块读取大文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrscnbsdl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtwebttyqr.html

[U24] Py：路径操作
来源：http://dali.c1oappe.top/Article/details/gtcpdocexx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtczokvjei.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gtxeohhjff.html

csv.DictReader(f)
来源：http://dali.nanxuanxn.top/Article/details/gtzjtqgofi.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrhihpnx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shuidangran.top/Article/details/gtiunmkokx.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtrdilcrby.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtcydotjic.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuyuzjyl.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gtweevwien.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gtrnukefun.html

@property 与 @x.setter 配合
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlkxdbjr.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtiofjnhsp.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gtedxwcycq.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtowvcsdpe.html

python -m pytest -q
来源：http://dali.andypj.xyz/Article/details/gtpdvkpxuj.html

[U32] Py：代码格式化
来源：http://dali.ydzc1.top/Article/details/gtqcputwcg.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtzebdijvc.html

[U33] Py：打包发布
来源：http://dali.pycfn.com/Article/details/gtdqbbztct.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gtywzgjvpl.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gtmlayhbiw.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gtulxvkhye.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gtgugzkmny.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtrmhxvvar.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gttiyrznti.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gtyzljwhmt.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gtlcwzntpv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gtcscscfrp.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhoulong.xyz/Article/details/gtwjuvanel.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gtzalexyll.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gtfnfqtxtp.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gtzbsovxeq.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtsgeopxgx.html

print("err", file=sys.stderr)
来源：http://dali.shangyingyoupin.top/Article/details/gtfljdamqk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gtwousmoid.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gthvwcsxty.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gttcnewwwa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ivvv.top/Article/details/gtspcamdvj.html

[U43] PHP：声明命名空间
来源：http://dali.316326.xyz/Article/details/gthljsfucf.html

namespace App\Http;
来源：http://dali.snrcjt.cn/Article/details/gtakyilywr.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gtugaqgqoy.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtattfzggp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gtuyulopus.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthavefst.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtumtfvdqg.html

?string $name = null
来源：http://dali.jinqigufen.top/Article/details/gtwzsmeahr.html

[U47] PHP：联合类型
来源：http://dali.guannengcc.top/Article/details/gtzckfuvql.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gtndhykutz.html

[U48] PHP：纯枚举
来源：http://dali.aizwys.cn/Article/details/gtfllsockd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gtussuluny.html

[U49] PHP：只读属性
来源：http://dali.pengpengdd.cyou/Article/details/gtsozeyffp.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gtsssscxmd.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtznnohaqh.html

public function __construct(private int $id) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzzupfllr.html


<!-- 参考信息 -->