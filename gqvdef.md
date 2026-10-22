代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gtizzrafgj.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gtlupegcuw.html

memcpy(dst, src, n);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqjrrxvi.html

[S26] C：内存清零
来源：http://dali.xinyue.icu/Article/details/gtmvphenkq.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtaxmrgsug.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtsqbqarjx.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtqbqitwue.html

[S28] C：静态变量
来源：http://dali.jqgufenzy.top/Article/details/gtxyqtreml.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtuxhmzrbx.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtddrpzhju.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gttpuqwnqh.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtjullkqjb.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtwcvzxaox.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtwxwywtry.html

#endif
来源：http://dali.chenzaomai.com/Article/details/gthfdvoowx.html

[S31] C++：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtkrktfjoj.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzkfllnm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxcxnqtjf.html

[S32] C++：字符串
来源：http://dali.ppjwa.cn/Article/details/gtuncfdzqc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtbnrpckgu.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtqzzknrhe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gtpnaxsebs.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtisfofuai.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtmphigyju.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtnzplcvbb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtamqultod.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqbbadbp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtomlmjhqq.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gtkueqwahy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cashguo.top/Article/details/gtpsihhxyq.html

[S38] C++：排序
来源：http://dali.yj20258.top/Article/details/gtqvywxots.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtbltjomww.html

[S39] C++：自定义比较器排序
来源：http://dali.aibaodan.cn/Article/details/gtjdxrovbz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtgdfqdqqa.html

[S40] C++：查找元素
来源：http://dali.jqgufenzy.top/Article/details/gtxbnforpd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtupdcpynu.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gtfjcbaeqf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtaazulekv.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gtzlcoihsx.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gtsgjfcszr.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gtzaozluic.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtkrjysvap.html

[S44] C++：引用传参
来源：http://dali.hysaishi.cn/Article/details/gtoyqampla.html

void inc(int &x) { ++x; }
来源：http://dali.yuxming.cn/Article/details/gtmsrkjqvv.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtqfzpujxu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtwswmudam.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gtvdzhrwjj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtvkucsclv.html

[S47] C++：结构化绑定遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqlzhafzv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtkneoxxgl.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtzyzmwpyy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gthuzsvarl.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtjhevhulm.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjrilshwh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gteesowkon.html

[S50] C++：格式化数字
来源：http://dali.hnxiangtu.top/Article/details/gtwbvhffae.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtcrogdfwq.html

[S51] C++：显式类型转换
来源：http://dali.zdqjudy.top/Article/details/gtcgxlhebg.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtilocnxcg.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtuyktdudv.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtmxipekee.html

[S53] C++：移动语义
来源：http://dali.hnqzz.top/Article/details/gtqflfbuno.html

std::vector<int> w = std::move(v);
来源：http://dali.gogol.net.cn/Article/details/gtoyxokxpj.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtvjcvwxlv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtuzqpkrym.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtyrcdkfui.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtsnbadfld.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtuipuczpk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtjrmdyhht.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtxrtiukqi.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtetbncxom.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtehdkjurs.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gterwhvtcv.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtsvcmhkej.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtunbkfroy.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtguwtepum.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtxtzoteml.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxbtwwxn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtafuurcuc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttrjrtvnu.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtostlxvwq.html

println("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtxqbmzyti.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtzwftwlpp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gzhubu.top/Article/details/gtaxwrpizc.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtvamoubks.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtbwdocpjj.html

[T04] Kotlin：空安全
来源：http://dali.hongshengwenyu.top/Article/details/gtgqblzlzp.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gtjzzhhlte.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtlakwvocg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtiptpzpmu.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtfkinqwjl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtrgscnzaf.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gtucgphehv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtgyclysla.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtxuffvjol.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gtahwinzej.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtoyjurqqy.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtwkcsmskc.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gthwqpdoet.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtidnxdkwn.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtsulredjo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.iojbl.cn/Article/details/gtirfsohlo.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynnkgsej.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtymmqiytp.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtnswqjjty.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmwsurgg.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtzelmvwpb.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtuxgxeodn.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtlxmfxxcv.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtwkoqsggq.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtkiftihde.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtndqkjncp.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gtcvwcisbe.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gtqcfsoffz.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtrwvjftzm.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtuupwangn.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gtaohuhkiu.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtafykbcll.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtjgpbkalf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtzjnnasbg.html

[T21] Swift：遍历
来源：http://dali.dashuyun.cn/Article/details/gtfkmwylzo.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtztzrkyuf.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtcoufcsgx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtfchfpedt.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtadfvjdag.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtxumcpxie.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtjfihabnv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtzsmfjpoa.html

[T25] Swift：结构体
来源：http://dali.feifeiyinyue.top/Article/details/gthlexofjm.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtenynuoby.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gtnpbpywyz.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gteopdgmwr.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtekkygjqn.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtgpjkyfeq.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtpxwpglex.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtzfqacboi.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtylftdkyj.html

guard let x = opt else { return }
来源：http://dali.xziqi.cn/Article/details/gtvvcyydog.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gtygmqecyy.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtyjbesfzr.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlysgdjdp.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtdwkaflyr.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gtcnzlcabh.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtyuhadnob.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gttlloatun.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtsipmyzmu.html

[T34] Lua：遍历表
来源：http://dali.pycfn.com/Article/details/gtejgknipz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtlbrivdig.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtlmtoxsql.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtohbdsdap.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gtvwwczspf.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtfpppjjid.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtfhugkxcm.html

"a" .. "b"
来源：http://dali.dianchejie.cn/Article/details/gtzpjwbiff.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtsdmwdomw.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtthctruyn.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtqaljbwzs.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gterggsqyn.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtqmnzxbhb.html

setmetatable({}, { __index = base })
来源：http://dali.jqgfzy.top/Article/details/gtupofwqvf.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtukearqqb.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtwxpfrgfx.html

[T42] Perl：变量类型
来源：http://dali.chenjidiqi.icu/Article/details/gtwhsynsse.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dianchejie.cn/Article/details/gtutwghlip.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtdasipwer.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtgglijoxl.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gticqvogai.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gttxhifwdh.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtbsaardpl.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtpisevszo.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtkinilkds.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gtzcyunxwj.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtdzahmbmp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hfpthk.cn/Article/details/gtzvwjjfjy.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtgxhvhlpq.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gtbzjxpmbz.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtzebnzoou.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtclshuyny.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtsofqjpki.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gttfijcsbm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtebnejizw.html

[T51] Scala：Hello World
来源：http://dali.yuxming.cn/Article/details/gtcemiezxx.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtqgkrwlrh.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gtgrhajkdn.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtihogckum.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwfyexdc.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtgmuvffvv.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gttdurmwjl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tanke756.top/Article/details/gttievwgcv.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtfovgoige.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtztvyijsv.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtxasjgshj.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtmskszogh.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtnsghqula.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtrsthjgze.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtrrbzrqlo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtugugmror.html

[T59] Scala：循环
来源：http://dali.jqgfzy.top/Article/details/gtyngkeyde.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtjbsnkgxo.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtlxmxxvdx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtwdauddch.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtahdbefxb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtdewdpprd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttehhjwny.html

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gtcogruvlh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtstynmgre.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gthngzzxqy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnxiangtu.top/Article/details/gtumrafgse.html

[U03] Py：加载 .env 配置
来源：http://dali.xziqi.cn/Article/details/gtwsjwgyll.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtcuzpqmzb.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtonorznpn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtsyyvnzvf.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtwlrpubuh.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtjgblvxnj.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gtnkomefed.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtnkhcehcw.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtddzdoptz.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtxmgvazki.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gtkooharfq.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtzeipdxby.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gtvbhnzets.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gtjamakahu.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gticvwvyva.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.quarkkingdee.top/Article/details/gtevzyhdha.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtlvbbyphj.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gtomcovbrh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtvpqsrdyk.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxhxuyqw.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gtlathpmmq.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtmiujmjmk.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gtpxxvzwcr.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtogvqhavg.html

[U15] Py：高精度计时
来源：http://dali.jlsjyb.cn/Article/details/gtghfjtfew.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gtkxfgymge.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gtltacypfe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqgecvcn.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gtuavgrech.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yongpay.top/Article/details/gtpagbnmoh.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtggbkbdkf.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gtzmbsyuce.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gtafhquden.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtwvqdmyed.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gtjnqivqwj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gtmocuaiqy.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gtvihgsmjy.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtdrjmwvxn.html

[U22] Py：矩阵转置
来源：http://dali.quarkkingdee.top/Article/details/gtiitvzvmq.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtpylajcwz.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gtjlqqobhz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtphyjsldo.html

[U24] Py：路径操作
来源：http://dali.cheryme.top/Article/details/gtxsldojun.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtsmrxohgq.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gtnbyygwfq.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtunayighg.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtabvulrow.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gtsrhvgkqw.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtdjzcnbgd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtjgqldlpg.html

[U28] Py：类型别名
来源：http://dali.zycfv.cn/Article/details/gtoykjkpxn.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gtfjfpoolg.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gtlexousev.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtxapvpleu.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gtutfkfbli.html

@dataclass(slots=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtogzfyhfh.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gttkealcur.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtcnkbxlta.html

[U32] Py：代码格式化
来源：http://dali.aizwys.cn/Article/details/gtkttpqpky.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtjkuckaqa.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtqtcarbsa.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtztfnmglj.html

[U34] Py：判断编码
来源：http://dali.hammf.cn/Article/details/gtrstlvfex.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtulesstmr.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gtcczsvzfk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.9152youxi.cn/Article/details/gtvbmzgdzd.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gtitdsdhzt.html

schedule.every(10).minutes.do(job)
来源：http://dali.yueranfly.top/Article/details/gtvbsqkuju.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtmbfnrizv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gtlveuvnlf.html

[U38] Py：获取脚本所在目录
来源：http://dali.guannengcc.top/Article/details/gtpbdmadex.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gtzckqtsjk.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gtbqjhevsm.html

sys.stdout.isatty()
来源：http://dali.jqgfzy.top/Article/details/gtfaakurgl.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gticvfftit.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynihorcz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gtqplaaeiy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sysykeji.top/Article/details/gtwhusxcsl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoqrpmfs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xuanzx.com/Article/details/gtzszzxhgr.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtmzytjaho.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtplwvjanl.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtchuridiz.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwhibjds.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yongpay.top/Article/details/gtiucthybt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtzqmihmvz.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gtmxbreytp.html

?string $name = null
来源：http://dali.zhoulong.xyz/Article/details/gtirqheiia.html

[U47] PHP：联合类型
来源：http://dali.jinqigfzy.top/Article/details/gtfrhmcxga.html

int|string $id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemcfjfbq.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gtkxkvhxkr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtyozadnzv.html


<!-- 参考信息 -->