代发 wailian999

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtfvqrhtgu.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtshqohndz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fengsongda.top/Article/details/gtsdezgrmk.html

[S30] C：头文件保护
来源：http://dali.redwolf501.top/Article/details/gtbknqcnpn.html

#ifndef X_H
来源：http://dali.jiagoushi.top/Article/details/gtpwepldoq.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gttbtryynx.html

#endif
来源：http://dali.ivvv.top/Article/details/gtcnzpxgnp.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtksopeako.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gtomsseldk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtkaoqkjni.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtoxwzufgh.html

std::string s = "hi";  s += "!";
来源：http://dali.snrcjt.cn/Article/details/gtfgjifdaz.html

[S33] C++：vector 增删
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzbbtmjl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhoulong.xyz/Article/details/gtaypyjreb.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtiwhnasgv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gtyyrkoxkf.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtjmowpymh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtyzdzzfxx.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtjmbggcub.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtbvtegtbj.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtlxzttoua.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtwahpkwub.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtwbdqrwoi.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtevaxfebw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtkkkkfnbs.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtgvxcmkpg.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtckiywkth.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gogol.net.cn/Article/details/gtgbhlqvqc.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtqicawlqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtfgbsoadu.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtwaptwwpr.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtvnnakzia.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtstfuvchs.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gtyudsygrc.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gthvlzxxob.html

void inc(int &x) { ++x; }
来源：http://dali.xylfe.cn/Article/details/gtlwdojlup.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtejaehaka.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtuimskaiz.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtljdztfnh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtgdnyfnxi.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gtbcwnqfgp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gzhubu.top/Article/details/gtqwbwkksa.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtklmivcwv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gttfhjrdrd.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtkwilet.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gtyscgdefp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtpkalzezd.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gtzuzbqpey.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtwksekona.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtibyvkfcj.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtagbtdvgq.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtcvgztcim.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtqsibmwdk.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gtiaimhjsj.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtdpnxghhm.html

[S54] C++：异常处理
来源：http://dali.fzhhl.top/Article/details/gtkhrymazt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gtcodemkvm.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtnrbjoikf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtreltzybb.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gtopormctu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtqymkgzol.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gtcngxskdq.html

constexpr int N = 10;
来源：http://dali.aibaodan.cn/Article/details/gtoueiiolg.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtrxwonrzh.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtnykhcjnn.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtrkpmwrza.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcvcioxv.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtseycetcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtegvsilut.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtigjwhiqm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtukrsdvdw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtximxzbrf.html

[T01] Kotlin：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtozifzkpa.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtgrmaikbf.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gthragjekx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhtwcfhu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtubbxfsou.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtzszhvvyp.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtgjiithaz.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtnxjubklo.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtzulftkbq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtjsgrytjj.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtopczzblw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtqcxznzoq.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgbepltv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtbnxbheqd.html

[T08] Kotlin：数据类
来源：http://dali.fengsongda.top/Article/details/gthtsctlhm.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtybaavtig.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtdotwvdjh.html

fun String.exclaim() = this + "!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrqmmyvq.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtwgvsdvlv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtgtivigvw.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtxhievfmp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtiqxusijv.html

[T12] Kotlin：解构声明
来源：http://dali.cheryme.top/Article/details/gtcvuhlbwi.html

val (a, b) = Pair(1, 2)
来源：http://dali.snrcjt.cn/Article/details/gtgtqlhzwj.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtswkxcahh.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gtjurjiblx.html

[T14] Kotlin：循环
来源：http://dali.jlsjyb.cn/Article/details/gtqrhyysdu.html

for (i in 1..10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoshejlf.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtadtwjuxr.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gtmmldktqk.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtuutsldpt.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtvfanpijf.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtutoftroy.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgupwyoh.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gthtugiqih.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtauchmfof.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gtofzpspkh.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gtscruudus.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtwkqryhew.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ppjwa.cn/Article/details/gtwtjydxsx.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gtwhbkdefu.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtcpfdcmoi.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtuprqmlil.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtyvsssrwq.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtqqgubcvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gtpwkbqstf.html

[T24] Swift：闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtmpdztblp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtpwooxfos.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gthxhgizee.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gttxzixrqe.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtizxtgvbe.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtxmmpihht.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtumrathgj.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtwahnnwee.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtxbtporfg.html

enum Color { case red, green }
来源：http://dali.yonumen.top/Article/details/gtufvsbwmg.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gttlocpiwd.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtlyrmhqxm.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtxnfaawxv.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtijiqqssf.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtjsnkxszs.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqagdboq.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gtmhnshtpa.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gtvmakjxnk.html

[T33] Lua：表（数组）
来源：http://dali.quarkkingdee.top/Article/details/gtjrfwlmfq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtwypsdmry.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gturvpzmhl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtmhhzxpgc.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtzucwuxed.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtbixbkcwp.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtkkwefxuu.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gtizrnaszn.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gtnsjkejpv.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtgjkeiuvs.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gthtfdckaj.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtmggckdzl.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtutzcpjpw.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gthqmwbkjn.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtdgejrthg.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gtuzgjpcqs.html

[T41] Perl：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtxexxnmvu.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtsonzqfnw.html

[T42] Perl：变量类型
来源：http://dali.cheryme.top/Article/details/gtogzscmhi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gaohongyu789.top/Article/details/gtprttfpyb.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtgcwyurpw.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gteuahgjpe.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtgvywvupm.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gtuagrsbbb.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtulqnryxb.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gtdrndbviy.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtyejhsmcf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gttplwixlh.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gteeztisto.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gtiojmhaqf.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtqirpnkfy.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gtpotjamdz.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtougxlwef.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtzsvxlvwa.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gthkspdxjl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cheryme.top/Article/details/gtkwlbnrof.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtobdhqfpy.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gtbxfopdix.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtdqmdtkhv.html

[T52] Scala：变量
来源：http://dali.yuanzhike.top/Article/details/gtwzcsqfft.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtflxutkmb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtjpflhuva.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtvoxmhrxk.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtmvcsspxl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gtndkojbyz.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gthqwojtvf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgzcxhqv.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzltvwbxs.html

case class User(name: String, age: Int)
来源：http://dali.ivvv.top/Article/details/gtfkfporja.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtximwuoza.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtkdrijzeh.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtzisexoxw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtgdxoesnu.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtmslnrylc.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtgzvjfgei.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtytwplrvs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gtcfwilqdx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtgngzwuow.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenlongwang.top/Article/details/gtoikyajki.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtechqmnua.html

[U01] Py：创建虚拟环境
来源：http://dali.xuetiantiany.cn/Article/details/gtasueprzn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtbsjkcgaf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gtadftwlqi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gttdmaanki.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtwfwigweu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtzlnpmvuk.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gtpjevufxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ehwqpu.com/Article/details/gtpbdbhiwe.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gttxlooozs.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtblpzhufm.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gtdiqhelax.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtvwloakku.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gthxizrlzw.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtkaofstlt.html

[U08] Py：展平二维列表
来源：http://dali.cucudq.cn/Article/details/gtmksgmybi.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gtpsstlgeh.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtjtidjlnx.html

max(d, key=d.get)
来源：http://dali.shuidangran.top/Article/details/gtfpvayvfs.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtxhugtbmz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gtybclaaiv.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtysbvropr.html

(x * 2 for x in arr)
来源：http://dali.bjfxy.top/Article/details/gthjogvexa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtmcipjrze.html

Counter(arr).most_common(3)
来源：http://dali.ivvv.top/Article/details/gtkvgpllmd.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtdpimrtad.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtdvctacgz.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gteyhvmohs.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtayalvxax.html

[U15] Py：高精度计时
来源：http://dali.316326.xyz/Article/details/gtdxenfyhm.html

t = time.perf_counter()
来源：http://dali.hnqzz.top/Article/details/gtjfscpwub.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtmxifmmic.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jqgfzy.top/Article/details/gtepbesvmg.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gtenyubbuk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.0kj1m.cn/Article/details/gtqsqeowqe.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gttlednckx.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtnuaxlaaf.html

[U19] Py：正则替换带回调
来源：http://dali.xylfe.cn/Article/details/gtsavmshyv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtcearnamo.html

[U20] Py：缓存函数结果
来源：http://dali.jiagoushi.top/Article/details/gtunnwmujj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gtwkmickoc.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gtzvjxklrk.html

@contextlib.contextmanager
来源：http://dali.daria6918.cn/Article/details/gtkodnulao.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gteguxcshn.html

list(zip(*m))
来源：http://dali.yonumen.top/Article/details/gtahfahekj.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsytdzftg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hysaishi.cn/Article/details/gtbgiahogq.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gtfdkjibzq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtgyjnjaoi.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtepmdpibv.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtiajoiila.html

[U26] Py：并发下载
来源：http://dali.vqdsnc.cn/Article/details/gtkpljwxpu.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtxnkafmml.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gttftcnvfs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aizwys.cn/Article/details/gtekxieetk.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtzjdbbrmg.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gtnrqafequ.html

[U29] Py：属性校验
来源：http://dali.xziqi.cn/Article/details/gtkuqndqgo.html

@property 与 @x.setter 配合
来源：http://dali.aizwys.cn/Article/details/gtgrixobiu.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gtvuyvyzss.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gtolmieqkh.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrevhxfw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gtqmduskrq.html

[U32] Py：代码格式化
来源：http://dali.wangdashe.top/Article/details/gtlqgmvvzw.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gttmqoocqj.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gtfjeqdzxe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cashguo.top/Article/details/gtefuijkqi.html

[U34] Py：判断编码
来源：http://dali.birdmap.top/Article/details/gtcfxdfjhk.html

chardet.detect(raw)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgcsusofn.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtvoasyzgq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dashuyun.cn/Article/details/gtaskhsfjk.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtnmtgdswj.html

schedule.every(10).minutes.do(job)
来源：http://dali.yongpay.top/Article/details/gteaqvdjdl.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gttzekrpyk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuetiantiany.cn/Article/details/gtgiiifsoz.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258888.top/Article/details/gtjvxvgzxr.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gtjobdgoue.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtzbexfaqj.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gtqokznznz.html

[U40] Py：打印到标准错误
来源：http://dali.shzxlz.cn/Article/details/gtapapajog.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtlfpjdhym.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cashguo.top/Article/details/gtbzsfsied.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gtmbkcamdu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtpsdxlpwe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.havefunace.top/Article/details/gtozaosltr.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gtxdjzxrxv.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtkvnsrcnp.html

[U44] PHP：开启严格类型
来源：http://dali.xylfe.cn/Article/details/gtxdqpwnlq.html

declare(strict_types=1);
来源：http://dali.yvedp.cn/Article/details/gtetsvynyg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hongshengwenyu.top/Article/details/gtnwzrijve.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtoijvbini.html

[U46] PHP：可空类型
来源：http://dali.jinqigufen.top/Article/details/gtqdvzlyyj.html

?string $name = null
来源：http://dali.aibaodan.cn/Article/details/gtgyfssklo.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gtobfzvowg.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gtfwdfjjus.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtbvkhobdr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzempxhin.html

[U49] PHP：只读属性
来源：http://dali.nanxuanxn.top/Article/details/gtvalnjill.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtkadhqviy.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gthkptfixg.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtumhdkouf.html

[U51] PHP：数组解构
来源：http://dali.zycfv.cn/Article/details/gtaztwdwji.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gtwmbzbsza.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttibnokod.html

$double = fn($x) => $x * 2;
来源：http://dali.ydzc1.top/Article/details/gtovwkaadd.html


<!-- 参考信息 -->