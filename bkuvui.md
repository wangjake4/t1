代发 wailian999

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtkzxyskdg.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtgjezolpc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gtloweonfn.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gtsqwpjasb.html

#ifndef X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtwimnwzgu.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtkzzwfpel.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtgyiriyud.html

[S31] C++：Hello World
来源：http://dali.mhx1999.top/Article/details/gticwfzvdj.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqgcllfg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cucudq.cn/Article/details/gtqfxxawld.html

[S32] C++：字符串
来源：http://dali.jlsjyb.cn/Article/details/gtowgioxdn.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtlbdtuzzw.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtskykplni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtuqozxlat.html

[S34] C++：遍历 vector
来源：http://dali.jinqigufen.top/Article/details/gtctgzcofk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtbcxbuhuk.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtcoauyxhz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gthyhinliz.html

[S36] C++：unordered_map
来源：http://dali.haohaochexian.top/Article/details/gthtvcfbcb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtmhyrcedb.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gtnirzwubh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtwyfxbtlh.html

[S38] C++：排序
来源：http://dali.ppjwa.cn/Article/details/gtciaujpeb.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtsmzvmgrf.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtgrhjlpdg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigfzy.top/Article/details/gtryoqizbg.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtbmfcviim.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtdwhhjbys.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtorfdegwk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gteayenkhj.html

[S42] C++：继承与虚函数
来源：http://dali.xuetiantiany.cn/Article/details/gtcxwlhkuj.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtlpcrhjaw.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtyemmulrx.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gthkuqmkvv.html

[S44] C++：引用传参
来源：http://dali.shuidangran.top/Article/details/gtqhyqwvtf.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtltrblqbs.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtmfctctdg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtmxvrkbcm.html

[S46] C++：函数模板
来源：http://dali.ivvv.top/Article/details/gtrhdgsntn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtkwawcmre.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtqbzwyxlr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtvyeklyhf.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtsxvssegu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgfzy.top/Article/details/gthpffcqwm.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtnilzwvps.html

[S49] C++：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsfvvcqu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtgycjfsuc.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtfbniqgbm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtnlmfwwfw.html

[S51] C++：显式类型转换
来源：http://dali.daxiang520.top/Article/details/gtppwgqxhy.html

static_cast<double>(a) / b
来源：http://dali.dianchejie.cn/Article/details/gtpknfotpd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gtmyorlmmd.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqzlkddif.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gtcgkedgtm.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtdcuranij.html

[S54] C++：异常处理
来源：http://dali.316326.xyz/Article/details/gtuxnmdupf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqxrhddy.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykfakmzc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtujuzarpb.html

[S56] C++：optional
来源：http://dali.sweek.top/Article/details/gtileizfkf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtcrnsvfqb.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtmvjynhcn.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gtcbnjgeyv.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtwkixmoel.html

namespace ns { int f() { return 1; } }
来源：http://dali.mhx1999.top/Article/details/gtnqxcmtfz.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtyuirmleq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zdqjudy.top/Article/details/gtpwupsuds.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtoremlupp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtdumkzpad.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfbgroiti.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytvdcwjx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtuikvpnuw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtpksimsun.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtputnusug.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtavgjjupp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gthgsuqlmx.html

[T03] Kotlin：字符串模板
来源：http://dali.316326.xyz/Article/details/gtwtodqfvc.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtdyxozzzx.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gtzhrvlcum.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtyscvjioi.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtdgpffism.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtbuijhyll.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtxmkhvlwp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtpkgjbvpn.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtyiacaoiv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gtamoymvaf.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtroxxsjdr.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtqrutsujh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gtnjawxorw.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtplbmqpsn.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gtwmhugzdx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtufwnvnla.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gtttflldkf.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtmaliqmcc.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtktmpnvgi.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtfaeohlwz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtnbclbsiu.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gtckuiljbs.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtubezgcll.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gthvizqcdr.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtqximzali.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtcjajstsr.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtwdlfyqrr.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtztsdyfmg.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gthhfaadqu.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gtopgzoyds.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtbxdsdkrf.html

"值: \(b)"
来源：http://dali.birdmap.top/Article/details/gtzvcngrpk.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtzwtliefq.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtyortsmhw.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtqytxjilx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gtdpwrdoqv.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtcgpqxrps.html

for x in a { print(x) }
来源：http://dali.svipenyu.cn/Article/details/gtphsnycjy.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gtpcthticl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gtrgolsoew.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtarrtuzsu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gteegkrjwc.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gtjzsqagkq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtriiuylsr.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtzeldvvgk.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztdaiafm.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtryudvsks.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtxqzvqjvy.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gteexrnsys.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtuhlodhkd.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtfvbrioxx.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gtqztxpndb.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gtwakiwfsq.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gtsvnxbxpc.html

[T30] Swift：协议
来源：http://dali.yongpay.top/Article/details/gtnnrhxiqk.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtuekhppqn.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtvqososgz.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtnotkkohj.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtkorqjpkl.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gttokuvrdx.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtdcbrjgia.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtnhleufae.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtgcvgbnyn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtcqgntvyx.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtwuvvqyhr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtlxniumwo.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtmxhosfui.html

function add(a, b) return a + b end
来源：http://dali.gzhubu.top/Article/details/gtrawybhqn.html

[T37] Lua：字符串拼接
来源：http://dali.pycfn.com/Article/details/gtfbwfytou.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtnvpqfdpb.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtageqcdcu.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gtmbzkgkyf.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gtfejnpxft.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtfinkzbkf.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmpdxvimu.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gtdcmegwiq.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtlgtehsdx.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gtdyjekbya.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtoihvhnbw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gtphgnxmfa.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtrmowsuec.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gtknoqnoki.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtszedchtn.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtqkundcku.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddvesxga.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtszkdazor.html

[T46] Perl：哈希操作
来源：http://dali.haohaochexian.top/Article/details/gtnkipphhp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtcjoavckb.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gteemgsrqo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtlcvunkya.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gthjscjnjs.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gtmujfmlzk.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtvcdqoywn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtooapzftu.html

[T50] Perl：逐行读文件
来源：http://dali.yanxiufei.cn/Article/details/gtpfqcyowi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtusqbxgkf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gtgykascxd.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtijlmwysb.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtafkbsaid.html

[T52] Scala：变量
来源：http://dali.tanke756.top/Article/details/gtpmaardej.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtbimaemwe.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtfzugwwix.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtasutzhac.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtxohflyvm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gtlalvsclq.html

[T55] Scala：集合过滤
来源：http://dali.cucudq.cn/Article/details/gtglfnypgs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigufen.top/Article/details/gthhddgxzy.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtoasccxok.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtasbmizhr.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gtkrzzdxbo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhongyouzk.top/Article/details/gtxzuncsgv.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gtvbniaooe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgfzy.top/Article/details/gtgqmmywxl.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gttcyzgqmv.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtpdmhlzle.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtlljkpmfq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gtongnueln.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvypzdzky.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtuaqribol.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gthkcazzyv.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtsypqjldu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtwkjxkogu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gttaqmdjgj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtdpzostla.html

[U03] Py：加载 .env 配置
来源：http://dali.yj202588.top/Article/details/gtoynjqptq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtfptatsog.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtpgdnhqxy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sxryk.cn/Article/details/gttpqwrujm.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtulpychsw.html

list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtjdajplwt.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gtjyxgdumn.html

{**a, **b}
来源：http://dali.gotoacloud.top/Article/details/gtvfrtgozs.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gtoniicaut.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gtwnhczitm.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtsmkvolvs.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gtxkigjdis.html

[U09] Py：字典取最大值的键
来源：http://dali.sysykeji.top/Article/details/gtxndgyziy.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtsmqlmnuv.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtxunjsfuj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtjapyeuzy.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtifagcmmw.html

(x * 2 for x in arr)
来源：http://dali.nanxinkj.top/Article/details/gtzdidoucf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pycfn.com/Article/details/gtkckpbncb.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtejkkkyny.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtnptvsgdw.html

deque(maxlen=10)
来源：http://dali.tianlin.xyz/Article/details/gtfgzylxsu.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtznijeymp.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gtghdawfsj.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtmnlsusas.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gtamssuxrn.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtsnzlgryl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gtnimwlyod.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gttmoascwy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtufehsgra.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfazrcery.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtxxetjziu.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gtckoopsmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtokxwamel.html

[U20] Py：缓存函数结果
来源：http://dali.xylfe.cn/Article/details/gtatsncxig.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gtezcbfdru.html

[U21] Py：自定义上下文管理器
来源：http://dali.yangfankeji.com/Article/details/gtotlyktsd.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gtufaotvtq.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gtxtiuqhht.html

list(zip(*m))
来源：http://dali.zhongyouzk.top/Article/details/gtkvfeqdvw.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtmxefifsb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gthhuthssv.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gtxcnunywj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtajrfdcgy.html

[U25] Py：CSV 按字典读
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqubveysg.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdswtzso.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtfohhbaba.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ehwqpu.com/Article/details/gtifyktpsi.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtihaolllf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtouwqbdnt.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gtimtaebmw.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtnrgdfuyt.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtkxvcegwi.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtirabtwnk.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtqefewwry.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gtkkbdreif.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gtkfmpfsjs.html

python -m pytest -q
来源：http://dali.meibo888.top/Article/details/gtgheleouj.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtrvrpahqi.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gtqifxzzld.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtedwhkjil.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtwkqbxfmv.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gtdrmscfml.html

chardet.detect(raw)
来源：http://dali.wangshuangyany.cn/Article/details/gtmvhlmesk.html

[U35] Py：发送邮件
来源：http://dali.andypj.xyz/Article/details/gthgcoxzje.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tanke756.top/Article/details/gtvqhjaahm.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gthylkvyib.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtenhetdqb.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtrfwnipac.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtdkbwliov.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gtsowgelli.html

Path(__file__).resolve().parent
来源：http://dali.feifeiyinyue.top/Article/details/gtukebvapy.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gtfrympoif.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtrdqacgqu.html

[U40] Py：打印到标准错误
来源：http://dali.pycfn.com/Article/details/gtwwasbsnc.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtivdhnnse.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gtrtibsfoz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenjidiqi.icu/Article/details/gtwujuvnci.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yueranfly.top/Article/details/gtdhtzbeqh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yongpay.top/Article/details/gtfnbdatre.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtgbialhin.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gtadfogxmu.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtgqrrgkgh.html

declare(strict_types=1);
来源：http://dali.yuanzhike.top/Article/details/gtdosocolx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtftkjqarj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gttpslzmis.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gtysjlnjtc.html

?string $name = null
来源：http://dali.guannengcc.top/Article/details/gtctqrytva.html

[U47] PHP：联合类型
来源：http://dali.sysykeji.top/Article/details/gtdcsymwln.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtjzioxhkv.html

[U48] PHP：纯枚举
来源：http://dali.tianlin.xyz/Article/details/gtqbeyimwn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aibaodan.cn/Article/details/gtkkpehcgr.html

[U49] PHP：只读属性
来源：http://dali.hfpthk.cn/Article/details/gtzissxikv.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtkgkekfrd.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gtrqnabhkn.html

public function __construct(private int $id) {}
来源：http://dali.sxryk.cn/Article/details/gtccflkqxe.html

[U51] PHP：数组解构
来源：http://dali.jiagoushi.top/Article/details/gtaweijeiy.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtxcphuhgr.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gtfuuxcipo.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtatnrniex.html


<!-- 参考信息 -->