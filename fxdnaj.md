代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtdvmiwjeg.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gttczywtcc.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtpivhltkr.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtsfgqlbkg.html

memset(a, 0, sizeof a);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwdbxlgy.html

[S27] C：定义常量
来源：http://dali.guowangkeji.top/Article/details/gtkcwtofzw.html

const double PI = 3.14159;
来源：http://dali.hnqzz.top/Article/details/gtwoovptip.html

[S28] C：静态变量
来源：http://dali.ivvv.top/Article/details/gtnmmmcwxk.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtqxvxdenr.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtszkyuabm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtdfupkwal.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtjyiwxmbk.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtscbyxnkw.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacrypfqw.html

#endif
来源：http://dali.birdmap.top/Article/details/gtkdghhjxr.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtandhjcbq.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtexskxrnj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gtsbyrpnit.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gthbxtlvdl.html

std::string s = "hi";  s += "!";
来源：http://dali.ivvv.top/Article/details/gtzawrmfmm.html

[S33] C++：vector 增删
来源：http://dali.cheryme.top/Article/details/gtylaozcrd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtyeoeynwy.html

[S34] C++：遍历 vector
来源：http://dali.yanxiufei.cn/Article/details/gtbmqqtnzg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtqhlrfzti.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gturzevnmp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtcuvpkaim.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtpglnmawu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtzexpjztb.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtkflatmai.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtxkvxaiog.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtkriucwja.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgivwvfl.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtyuwevdql.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxinkj.top/Article/details/gtxvppxisa.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gthixoucci.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtiubenfes.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtemiewcml.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gtdgcwgcfc.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gteemwhcfk.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtikkmkbhs.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtxkhhrfra.html

auto p = std::make_unique<int>(5);
来源：http://dali.birdmap.top/Article/details/gtkbwnudzk.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtbmzjaffk.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtrdfusrvi.html

[S45] C++：lambda
来源：http://dali.dianchejie.cn/Article/details/gtpjkgrmtm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gtaaqfayyv.html

[S46] C++：函数模板
来源：http://dali.daria6918.cn/Article/details/gtnbqfhmnz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gthzpyhufv.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtsjklrthn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gtovyktswq.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzuqboea.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtbwyylift.html

while (std::getline(in, line)) { }
来源：http://dali.snrcjt.cn/Article/details/gtpnpbzhbi.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gthvpgcpfl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gtcvysiaeu.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtzqqietpu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gthriclkdw.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtbknvnyxa.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtgwfrwqsw.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gtzxgnvqsq.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtbyjaoluq.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtohvrldon.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtwiokymej.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtbtapnuxn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gttxjgalxr.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtygaqgpch.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtddpfymtl.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gthiuiwejm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gtmfxxyqdo.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtmaexaowm.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtvlvrmxwz.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtlwbxlgvu.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtetjsaogd.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtuydfroax.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhongyouzk.top/Article/details/gtrngdwees.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgcsjgzf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtwfuggtsi.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttrfwgsno.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtkxxhinag.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthzehgdon.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gtqyxealwl.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtbtjcxxzt.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtcanwpszy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtftkvrrci.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxwleqfy.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gtmexjlpht.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtgqtqpkvb.html

val n: String? = null;  n?.length
来源：http://dali.yongpay.top/Article/details/gtkmnjkpfg.html

[T05] Kotlin：when 表达式
来源：http://dali.cdnleiting.top/Article/details/gtqszduejq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtjyiiozlw.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtcagerxou.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtdxzlczhb.html

[T07] Kotlin：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtfkzmxtvl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtgyaujllk.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtvygbqfpj.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gthykcotcr.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtmxcuolic.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtpkchkrhh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtcooaikfx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pengpengdd.cyou/Article/details/gtggxuxuyu.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtahewpxlv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sysykeji.top/Article/details/gtnxoylxly.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtrxczhljc.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtqihfypiv.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtttofgrim.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtwprzxono.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtksakabno.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gtutmbuagd.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtalmdbvkt.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtoszztlwt.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gtwtaqcfoo.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtwgzsufov.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrndiiect.html

var a = 1;  let b = 2
来源：http://dali.jqgufenzy.top/Article/details/gtartwojks.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtpendqzfj.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtwppemzog.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gtjbubhdkw.html

if let n = opt { print(n) }
来源：http://dali.redwolf501.top/Article/details/gtdjwovtpu.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtkrxgpsgs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtxqztdyem.html

[T21] Swift：遍历
来源：http://dali.wangdashe.top/Article/details/gtgtlwreiy.html

for x in a { print(x) }
来源：http://dali.kuanghao11.cn/Article/details/gtkqifschu.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtwvwhtenn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtptnemwuk.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gtjolsaowt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gthepdfhbf.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gttmzgzktd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gthgabotum.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gtpugmuvup.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gtsajoulhn.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtjfjusryh.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gtfgrisaxz.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtvksgvbey.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gtqycuqsix.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtpmogipdr.html

enum Color { case red, green }
来源：http://dali.zhiwuduotai.top/Article/details/gtueksaevt.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gtkhbsoqen.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtphpkfrlx.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtobylcpup.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gtofiesorb.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtjugzgahc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gteadtgazc.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivoklkem.html

local a = 1
来源：http://dali.tian-w.cn/Article/details/gtohxftebu.html

[T33] Lua：表（数组）
来源：http://dali.mhx1999.top/Article/details/gtdatpdlbv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gtryddcfgx.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtlwsdljup.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gthtkiaomu.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtxdstdsfd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtsckrlyte.html

[T36] Lua：函数
来源：http://dali.aibaodan.cn/Article/details/gtefstkdid.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtfayvtsei.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gtjacdmzbk.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtxttfalvp.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtcjvrhemq.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gtuhxcysgt.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtqpstidmm.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtmzlsceku.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtlgcblsmu.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtvenihqjs.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gthiovahsb.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gtcvorsnul.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtgzypdudc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtituvsaps.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtdccdbwfh.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtzmcufxdd.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gtpzowrlpk.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtumftomxy.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpnlrmwb.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gtilrhutva.html

[T46] Perl：哈希操作
来源：http://dali.sweek.top/Article/details/gthmgmxlxh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtmhzjyhuj.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtficrelvp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigfzy.top/Article/details/gtwhzbkosi.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtkpdypozj.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtnyvgyebo.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gtaawvkpgu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkcnnuvpq.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtrrsdjoyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nwbrower.top/Article/details/gtuihnngvm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnniwrrwh.html

[T51] Scala：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtvusvdexu.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggwzveat.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gtxhkltkpn.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtuhqueuvc.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvptuqpx.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtmularwaw.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtktdruwcu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtjeoazowh.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtzuitdwpw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ehwqpu.com/Article/details/gtwkaikhue.html

[T56] Scala：样例类
来源：http://dali.jqgufenzy.top/Article/details/gtforocdhg.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtwfxxymqa.html

[T57] Scala：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtmzbbahlr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtkuvmreud.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtvunczngf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthoxxgjia.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtxsladpzu.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtrmqdnrsu.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtnaqaqwlo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtodnpjucd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdarqost.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthomomcjy.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtaxqqdchf.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtgcwrkmby.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtdhdhsxtx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtswvgsbov.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtlfhexmfz.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gtfqwyzzyy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gtmwgcpazn.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtircadnvo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtjolpgrxy.html

[U05] Py：列表去重且保序
来源：http://dali.redwolf501.top/Article/details/gttgytmjjk.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtywtbnagb.html

[U06] Py：合并两个字典
来源：http://dali.xylfe.cn/Article/details/gtqblnudqw.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtssgxlpzh.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gtxeyswtxw.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtrlyqgobi.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtlsplkkcx.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtqteikuqi.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtqbrtmv.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtjxdeogen.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gthwgbktsk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtebxojxaw.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtalztdazh.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtqidxqgbw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtzjdbyzpm.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtzftsuepx.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gttabqvsjn.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgggzeikz.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtldopyvox.html

defaultdict(list)
来源：http://dali.havefunace.top/Article/details/gtgmeqikuz.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gtoyzhprnp.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gtgiqqcogr.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtuthpriuk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtdntrrgdp.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gtdduqpmto.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtpnefpkzx.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtpxqxdzjv.html

pat = re.compile(r"\d+")
来源：http://dali.cqqwz.cn/Article/details/gtovpfkind.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtnvxqeuja.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gtkvyntwnn.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gtukfmxgrq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gtbyjtvftm.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gtfkgsvpqs.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtbdookomh.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gtlujfhluz.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtuxounajh.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtbqlumhml.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtyvumqjjv.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gtovhdmavr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gthcmwujfz.html

[U25] Py：CSV 按字典读
来源：http://dali.ybcxt.top/Article/details/gtidzmrwpu.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gtottvciom.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gttfhvrlfp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shangyingyoupin.top/Article/details/gtwkehzepw.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gtawwssdhg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gttniyrbxv.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtaspgqpyr.html

UserId = int
来源：http://dali.jinghuilouyu.cn/Article/details/gthgrayzzt.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gtisivoscs.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtttinnoqk.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gtsfvousfh.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gtmbdcuvac.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtubvzrikx.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtxunvrfss.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtqpgxnrij.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gtydeckmfi.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gtqybyxlzx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtkixkdsel.html

[U34] Py：判断编码
来源：http://dali.yvedp.cn/Article/details/gtixobbtir.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtwjvfusgc.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gttomcolpp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gtgnqaycdy.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gtcpvbzsdy.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gtqnxpysmx.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gtrzwefuvx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyvzuake.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gtpqfqbwfv.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gtjgnvkdcs.html

[U39] Py：判断是否在交互环境
来源：http://dali.havefunace.top/Article/details/gtydgwpluv.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtsbiqphze.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigfzy.top/Article/details/gtqfjmmmyr.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtztglbebn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtmvrrpijt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gogol.net.cn/Article/details/gtypxxhorp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtfzrlvaan.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtxlwptoot.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gtyuxawjix.html

namespace App\Http;
来源：http://dali.tanke756.top/Article/details/gtroxylexc.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gtwjennumx.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtfzyamjsh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtnlbgffkd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiyxcxpvt.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtpesjfkhl.html

?string $name = null
来源：http://dali.wangdashe.top/Article/details/gtpkvudqws.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtqcieunbi.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtneayunem.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gtpqcyquxa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjwvcnywh.html


<!-- 参考信息 -->