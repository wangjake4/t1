代发 wailian999

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gtgfdrjcup.html

[S29] C：变参函数
来源：http://dali.zhongyouzk.top/Article/details/gtfkywkafh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hywenlv.cn/Article/details/gtgpgygomw.html

[S30] C：头文件保护
来源：http://dali.jinqigufen.top/Article/details/gtcezwvpvx.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtvdlqoydj.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtvtdgpnha.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtwwbmekfa.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtoexxfcfv.html

#include <iostream>
来源：http://dali.feifeiyinyue.top/Article/details/gtkgseoiql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtevxjbiwt.html

[S32] C++：字符串
来源：http://dali.dianchejie.cn/Article/details/gtxwgpxyzz.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtzkxqftkt.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtqmxufbxm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sysykeji.top/Article/details/gtssnervua.html

[S34] C++：遍历 vector
来源：http://dali.hfpthk.cn/Article/details/gtwwjygdfh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtkghducgk.html

[S35] C++：map
来源：http://dali.sysykeji.top/Article/details/gtlvsnvjct.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteivdrlmj.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtmqeitmpe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtezmhnhsv.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gtycjdstna.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtymcfbmaj.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gttdwaezlc.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtjgaeyhhd.html

[S39] C++：自定义比较器排序
来源：http://dali.hongshengwenyu.top/Article/details/gtlntsptyp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtvsiebozw.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtqufkdbir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtgdezgsho.html

[S41] C++：类与构造函数
来源：http://dali.xinyue.icu/Article/details/gtzsfcuobh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gtjnyhmcsj.html

[S42] C++：继承与虚函数
来源：http://dali.chenzaomai.com/Article/details/gtohzbqyls.html

class B : public Base { public: void f() override {} };
来源：http://dali.hywenlv.cn/Article/details/gtealkehkk.html

[S43] C++：智能指针
来源：http://dali.pengpengdd.cyou/Article/details/gtaahkgsen.html

auto p = std::make_unique<int>(5);
来源：http://dali.jlsjyb.cn/Article/details/gtnywizucw.html

[S44] C++：引用传参
来源：http://dali.vqdsnc.cn/Article/details/gtldjvwxwz.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtvfvfgsfj.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtygqpfhky.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zycfv.cn/Article/details/gtuqfsosmw.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gturaffygm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtogrmxira.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtlvueegpx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtmopmefth.html

[S48] C++：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtuvbtvjbn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabwopcyq.html

while (std::getline(in, line)) { }
来源：http://dali.dashuyun.cn/Article/details/gtxvtpgqbr.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gthzffgcuq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwlmanfzh.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtwuctkjtq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gttevfkxuz.html

[S51] C++：显式类型转换
来源：http://dali.gogol.net.cn/Article/details/gtsseixgfo.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gtsmpkyhkl.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtuwdizfip.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gtsjyfptij.html

[S53] C++：移动语义
来源：http://dali.0kj1m.cn/Article/details/gtlwefjapu.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gttgvgozkr.html

[S54] C++：异常处理
来源：http://dali.gogol.net.cn/Article/details/gtizxwfzwx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cqqwz.cn/Article/details/gtnojrttgk.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gtitleqpre.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtiacsaeoe.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtqaogydnj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtziavrrbt.html

[S57] C++：编译期常量
来源：http://dali.jiagoushi.top/Article/details/gtgeviucsr.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gttmwvoqrt.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtyfaylbsb.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gthoxlvauj.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtyueuxsnk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtvqfkuysp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhengqikj.top/Article/details/gtrtohxgcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtqukidfxq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtakccspcy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtlbuvnhbx.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtbfrvvnqx.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtjihkygzs.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtoivntfiq.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtrncbphaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.c1oappe.top/Article/details/gtlognewfy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqoaqmfb.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtlhoyztxl.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtntfcyufw.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gtibmiccfs.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtplrqjkpq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtunfciirl.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gthnfiwcwt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuanzx.com/Article/details/gtbzsmeczf.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gthgwqsctw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gttnemaezt.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtkmfhktmr.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtetsqquhz.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtbpzutcpa.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtufpnorgq.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbpkgmuo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtzufiplyk.html

[T11] Kotlin：协程
来源：http://dali.gogol.net.cn/Article/details/gtwzcumfcn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtzzvonquv.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtznijdfef.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtbrtpvkmg.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtwkxxmxkb.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gtwtqjltoj.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gtclnchtpp.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhoawmwt.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gtbfnvouqw.html

interface Shape { fun area(): Double }
来源：http://dali.quarkkingdee.top/Article/details/gtxlccsspg.html

[T16] Swift：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtktcrdkxv.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtqykrhzou.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtuseedovz.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtzbunmihw.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtnrkuoavx.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gtiyeiheqn.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtoalzugdf.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtcfewyimw.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtbrkdsdce.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtcojuiszw.html

[T21] Swift：遍历
来源：http://dali.316326.xyz/Article/details/gtbzyytgmw.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtcjgpgamn.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtzzglmzkk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsckjwnx.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtnppopqwp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtsmxncvsl.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtwowaykdn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtkactlrss.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtbzkdmgde.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtkgusjnyd.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtbszeezqy.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtwwhrdpst.html

[T27] Swift：错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gtkqqoqssm.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtfkbreflj.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtbofzfeiy.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gttsfafxiw.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtxvptzbwd.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gtgrvqvvfj.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gtcozcckbw.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtfufybreq.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gtarkhldkt.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtkkdcijgb.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gthmpxxwvq.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtrvmqyiin.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtgxopewpn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtevomydfh.html

[T34] Lua：遍历表
来源：http://dali.wangshuangyany.cn/Article/details/gtvfinbmng.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtcpzezpgd.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtgplgexix.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gtvxvffcjv.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gtuqvtxujj.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gtpborzuhu.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtceucrbuj.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtuacimjfh.html

[T38] Lua：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtomllfwpu.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtyqmpgyjr.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtgbnkjelr.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gteiqecalm.html

[T40] Lua：元表
来源：http://dali.ppjwa.cn/Article/details/gtxvmyenyq.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtsgcnyjnn.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtgifjvsrx.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gtfdwrjmkm.html

[T42] Perl：变量类型
来源：http://dali.xziqi.cn/Article/details/gtbtlcejyx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gtehksjwyd.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtnmoczfrp.html

"值: $a"
来源：http://dali.dianchejie.cn/Article/details/gtlrbkxzov.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gtaiqsuwvr.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gtdzpxpejc.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gticngrhcj.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtgihnhrpv.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtycyexkby.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtfmxhhigj.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtcrqglrtf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtahwyayjj.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtdornflkz.html

$s =~ s/old/new/g;
来源：http://dali.bjfxy.top/Article/details/gtiaeyzcvq.html

[T49] Perl：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtoynwfbcq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtmwgocqvh.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtevgudusp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtssloiaec.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gtbvzqcjmq.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtoocsdydy.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gteobeycss.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gtubdkzlql.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gtrbmicbls.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtmoxppaci.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtslllrigk.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtwsrtbhrd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtlyotltwi.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtfsjvukjk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtokftixrb.html

[T56] Scala：样例类
来源：http://dali.shangyingyoupin.top/Article/details/gtfammerjf.html

case class User(name: String, age: Int)
来源：http://dali.yueranfly.top/Article/details/gtmghdtpqg.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtsvxerusk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtwnjmeppa.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtssmjchou.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtuupfrmbf.html

[T59] Scala：循环
来源：http://dali.daria6918.cn/Article/details/gtmidqvrli.html

for (i <- 1 to 10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtkspucgum.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gtjdwsihcn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gteijacvvi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvizozlu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtqahhscxe.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxhumeqsa.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtyinblwas.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtprxrtxwg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gtmlqpnyze.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yueranfly.top/Article/details/gtpdbdhqqv.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gtouejhkwc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gtfceffnac.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gttwhigpxp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gtjsojbnoi.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtkuptkjpm.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gtcovovvck.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gtzdszufnz.html

{**a, **b}
来源：http://dali.yj20258.top/Article/details/gtutlvdpsn.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtwialmqpy.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnfdgjbw.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtvntdwrpy.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtvyqvuycz.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gthqhrggks.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtgcykzilt.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtrigcrbna.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gzhubu.top/Article/details/gtyjeigjvp.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtdwogcogb.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gthlwwykyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjszvknd.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxakwcdd.html

[U13] Py：固定长度队列
来源：http://dali.aibaodan.cn/Article/details/gtowiyhbxv.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtcepciccq.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gtzztdaced.html

defaultdict(list)
来源：http://dali.316326.xyz/Article/details/gtoaqihsul.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gtxrkpwces.html

t = time.perf_counter()
来源：http://dali.yangfankeji.com/Article/details/gtzoyeltcm.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gtwnjnxogm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gtmudrbkln.html

[U17] Py：初始化日志
来源：http://dali.yanxiufei.cn/Article/details/gtqngqubom.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxuanxn.top/Article/details/gtbzeypemt.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gtzhezkykl.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gthluglkmm.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtwkzfdojy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtqjyugqnm.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtwdzvpgdk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtwduzpwgf.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gtmoufrvqe.html

@contextlib.contextmanager
来源：http://dali.c1oappe.top/Article/details/gtgncxxwhv.html

[U22] Py：矩阵转置
来源：http://dali.yonumen.top/Article/details/gtbvdqcslp.html

list(zip(*m))
来源：http://dali.yongpay.top/Article/details/gtceodgaux.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtcgwcjgyq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtgojkjsky.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtzsgfxvsf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtyyzrznsj.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gtviorlogh.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtplqjdefj.html

[U26] Py：并发下载
来源：http://dali.xziqi.cn/Article/details/gtuspmbnhc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangshuangyany.cn/Article/details/gtolzcuivv.html

[U27] Py：异步 HTTP
来源：http://dali.aizwys.cn/Article/details/gtedxaqqsi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gtqdvnxzhh.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gtrfwahfcu.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gtdebcvhlt.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gtvcrfvtgm.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkjifaea.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gtbjhrlzur.html

@dataclass(slots=True)
来源：http://dali.wangdashe.top/Article/details/gtayobvqxd.html

[U31] Py：单测
来源：http://dali.andypj.xyz/Article/details/gtqjqjgora.html

python -m pytest -q
来源：http://dali.sufxvd.cn/Article/details/gtexwghvnr.html

[U32] Py：代码格式化
来源：http://dali.shuidangran.top/Article/details/gtfojmqrbk.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gtsisrrgao.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtzvsxdxbl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gtnpsbyigl.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gtbxsswstu.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gtlklwewwn.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxrbpbel.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gtyihrvfja.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtlogngnpy.html

schedule.every(10).minutes.do(job)
来源：http://dali.9152youxi.cn/Article/details/gttuqekhdj.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gtjvsvmvfi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gtwlcfjozw.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtwddtmvss.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtkbscdsui.html

[U39] Py：判断是否在交互环境
来源：http://dali.snrcjt.cn/Article/details/gtcondgmco.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtpmqnklyw.html

[U40] Py：打印到标准错误
来源：http://dali.gotoacloud.top/Article/details/gtplqaiipz.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtzfmcrdjk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tianlin.xyz/Article/details/gtuyndqsno.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtrmfamotj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gtmmrrwrqu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtztsvqyme.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gttvmjwaky.html

namespace App\Http;
来源：http://dali.zhixingplan.top/Article/details/gtgciovbnz.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gtreogktrk.html

declare(strict_types=1);
来源：http://dali.wangdashe.top/Article/details/gtmmpickvj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtzguoskvc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtjpxtktrz.html

[U46] PHP：可空类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioccekjw.html

?string $name = null
来源：http://dali.yangfankeji.com/Article/details/gtkidoxpcu.html

[U47] PHP：联合类型
来源：http://dali.iojbl.cn/Article/details/gtynirvbdv.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gtmwkzixdw.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gtxowhzpkp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenzaomai.com/Article/details/gtsptdtafo.html

[U49] PHP：只读属性
来源：http://dali.ppjwa.cn/Article/details/gtqozpejiu.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtaglgzpdg.html

[U50] PHP：构造器属性提升
来源：http://dali.andypj.xyz/Article/details/gtcbiqbfec.html

public function __construct(private int $id) {}
来源：http://dali.birdmap.top/Article/details/gtfkztmyns.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gtjsytnsbg.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsgyuoneg.html

[U52] PHP：箭头函数
来源：http://dali.chenlongwang.top/Article/details/gtjkpjxxfn.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gtrnixtbnu.html


<!-- 参考信息 -->