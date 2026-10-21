代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gtptjdkaid.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtazthzmjf.html

const double PI = 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gttxydmhnf.html

[S28] C：静态变量
来源：http://dali.gzhubu.top/Article/details/gtppxkwwkq.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gticihtuhh.html

[S29] C：变参函数
来源：http://dali.chenlongwang.top/Article/details/gtdknkemmj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jyoumei.cn/Article/details/gtniabfffw.html

[S30] C：头文件保护
来源：http://dali.sysykeji.top/Article/details/gtykhehjys.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtmhnpariy.html

#define X_H
来源：http://dali.0kj1m.cn/Article/details/gthsghvgku.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtlmszxsaa.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtrvufjmhl.html

#include <iostream>
来源：http://dali.hammf.cn/Article/details/gtqrobtlxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xinyue.icu/Article/details/gtaexkxivb.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtsqlincdj.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258.top/Article/details/gtcrbtlucs.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtccelydwz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtokbpahfl.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtqmiydumy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hammf.cn/Article/details/gtpjcmoawo.html

[S35] C++：map
来源：http://dali.quarkkingdee.top/Article/details/gtwhwkcrye.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gttkttbypn.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtarfimiby.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtkzvffteh.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtvdvdpuby.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtpvbdtzdk.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gttrlmtmye.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtruxjypcf.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtbzxyqgml.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtzbkxlvdu.html

[S40] C++：查找元素
来源：http://dali.hongshengwenyu.top/Article/details/gtktbbbino.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.guowangkeji.top/Article/details/gtkcrkixne.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtojikbbha.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtuzakmewk.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfwdsvzp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gtegqsonyt.html

[S43] C++：智能指针
来源：http://dali.yj202588.top/Article/details/gtlsupnokh.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gthdirjuow.html

[S44] C++：引用传参
来源：http://dali.yj20258888.top/Article/details/gtcvcisqqo.html

void inc(int &x) { ++x; }
来源：http://dali.hywenlv.cn/Article/details/gtvlwzcsqo.html

[S45] C++：lambda
来源：http://dali.pycfn.com/Article/details/gtyanqmmmk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtnmziqkuc.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtcmejiisw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtuxwbvimc.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtfqsjrwyo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtwgmzvzrf.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtybvdmvkh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtiscfklcr.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtyrtyxlwc.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtowlmpbpx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.birdmap.top/Article/details/gttddcqzfq.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtuxdtwhfp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtizriuejv.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtyodaoyoe.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gtzldljrmy.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtxbjxoysg.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtldgsyquq.html

[S53] C++：移动语义
来源：http://dali.sufxvd.cn/Article/details/gtucvwiodn.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtkyoatmzz.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtsjhfghir.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtatxrvtru.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrpemvkl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttitparek.html

[S56] C++：optional
来源：http://dali.ehwqpu.com/Article/details/gtxiterqkw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtpzgqbyze.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtuplhvevu.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtivjrgegt.html

[S58] C++：命名空间
来源：http://dali.nwbrower.top/Article/details/gtjyzchraz.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtrorfiqob.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtdxubcvoq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtvkjophde.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtizxqvfgc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtmcnmfwth.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbgyrrxrp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangshuangyany.cn/Article/details/gttwoerheq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxiungauf.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdddzzyxu.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtlftibdpl.html

[T02] Kotlin：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzrjxwybp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtgrduwbwm.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtucidmhzj.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtcowiylwx.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gtuyollufu.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtfeavzdbz.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtpsfbfeaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtcqtubedd.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtwrgpyblb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtribplped.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtzbqndsgt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtcvcoxnlt.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtxvilkrmh.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtlcbrgjrb.html

[T09] Kotlin：扩展函数
来源：http://dali.gotoacloud.top/Article/details/gtdduuspzi.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtseyxlyvj.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfonpjgcu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtjnvunung.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gtqxlybkhu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtnexcvqph.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtfkyqnedx.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtzzjjeksr.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtuzfyqsck.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtwgaxqihh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gteacbvkdb.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gttltfvhir.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtsbslogae.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtaxjewguj.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtuioxggve.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtynfhwhww.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtzyocmjky.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtjgzqjcdi.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtaijuzeio.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtqghiswag.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtelzqoxrj.html

if let n = opt { print(n) }
来源：http://dali.sufxvd.cn/Article/details/gtoezbktvb.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gtrxitpyft.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtzeosxzvn.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtrkiowgvi.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtskldnhac.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gtztyagwcu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtbchcmmtw.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtczwyumak.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gtcfczsptf.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtgbckhddg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehsmuekl.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gttzjheyop.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtasfdzrai.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gttfybfocp.html

class A: Base { override func f() {} }
来源：http://dali.cashguo.top/Article/details/gtzevqryps.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtvdctzwhb.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehoozpaz.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gtuitkxhfh.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gteeeuqfdi.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtnvkwnbhq.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtdbjzelmv.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gthktbczct.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtawtqpiks.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtiqlmbsyn.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtvgepppic.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtpeuwocir.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtmhkdijdk.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtdqdtbfmy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gtszytogqq.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gttcmkdlxr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtjisiibis.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtcyuyarea.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtzxgbvcul.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpaiesrft.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtvwfxjxfx.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtsckkznnh.html

"a" .. "b"
来源：http://dali.sweek.top/Article/details/gtzhwnqdbp.html

[T38] Lua：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtnaersxtx.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtxsmsxcsd.html

[T39] Lua：模式匹配
来源：http://dali.birdmap.top/Article/details/gtpqideggr.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtiroaxrzy.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtqqphohwa.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gtvdskpyxr.html

[T41] Perl：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtmhzjtypu.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtrhffphpm.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtglhyzqwo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtketwwsxe.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtgiofyonq.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtguukmhtq.html

[T44] Perl：条件
来源：http://dali.havefunace.top/Article/details/gtgntaltxm.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtxtebonwm.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gthyszsfic.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtklrgnizb.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gtczgovxjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxinkj.top/Article/details/gtrudfqsog.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gtcqdnvhfo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsdyyjahc.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtvxwexwhb.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gttkimhmmz.html

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtnfqhndlv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtwohfwioz.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtkbiijqxo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtoqzekgnz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtutcmatfc.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtogesnpvi.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtvayrobcc.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtstjjdmgd.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtmwwornfm.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtqgtwchde.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtoockyveq.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtngnaictv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtyvbphezd.html

[T55] Scala：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtpugyzere.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtnpclewdq.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtufeplrnq.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gttgiajjjl.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gtcziyanez.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtamgqqdlr.html

[T58] Scala：函数定义
来源：http://dali.yonumen.top/Article/details/gtskgpznae.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yvedp.cn/Article/details/gtrfukfgiq.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtpiabqajv.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtjtmfejdr.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtydjegobo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gtyqvfxrht.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhnflknj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtshyipzvn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtuouqdwfo.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtlixnfgzv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gtumsmofqb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtmmsfxjjd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.meibo888.top/Article/details/gtoddntclx.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtwbsqtgok.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtqmcvrots.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtrfqgutht.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtqjmdmyxx.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gtyzrqmcbz.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtqozmwbds.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtwclmvunx.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtxxpkjxtf.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtmgpxdhza.html

{v: k for k, v in d.items()}
来源：http://dali.hysaishi.cn/Article/details/gtnwkhjtdc.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtdnemkkau.html

[y for x in nested for y in x]
来源：http://dali.gzhubu.top/Article/details/gtmbmqucvi.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtlvaogyil.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gtabgukqwv.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtpevwykqy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gtqwlxvere.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtufcglrub.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtkshrhhiz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hongshengwenyu.top/Article/details/gtlaocimvo.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtnrzfhzby.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtiqdcqprq.html

deque(maxlen=10)
来源：http://dali.chenlongwang.top/Article/details/gtjaapxhax.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtllndmerf.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gteyukxout.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gthdaveoqx.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtrkhcjoht.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtkycgljke.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtyaybrnck.html

[U17] Py：初始化日志
来源：http://dali.xziqi.cn/Article/details/gtyqylksbq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteexbvjcg.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtvadwtdtz.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqypzcku.html

[U19] Py：正则替换带回调
来源：http://dali.jianghu66.top/Article/details/gtfbysinpg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jlsjyb.cn/Article/details/gtacdbhqxb.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtmotaoblp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gteabkatmz.html

[U21] Py：自定义上下文管理器
来源：http://dali.sysykeji.top/Article/details/gtqdyojcvo.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtkabfkvgo.html

[U22] Py：矩阵转置
来源：http://dali.dashuyun.cn/Article/details/gtqjuoqlwl.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gthymhverz.html

[U23] Py：分块读取大文件
来源：http://dali.sxryk.cn/Article/details/gtuokdlbks.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtrbhtljqo.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtqtmgyliz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gthpvsipfu.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtqdjdajmm.html

csv.DictReader(f)
来源：http://dali.cdnleiting.top/Article/details/gttkymbzzi.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtfjcphnon.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtmmxigpxw.html

[U27] Py：异步 HTTP
来源：http://dali.aibaodan.cn/Article/details/gtodenfijl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gtxbmycvck.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtjiohqgkg.html

UserId = int
来源：http://dali.yvedp.cn/Article/details/gtnsduxnvo.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gtmhvhyljn.html

@property 与 @x.setter 配合
来源：http://dali.ydzc1.top/Article/details/gtwgvjjvry.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtguckkihx.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkauktma.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gttlzekhhs.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtlblllbqm.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gtnjcrjtna.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtntmvittv.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gthmcivrpv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gtddefelvm.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtlskhpdss.html

chardet.detect(raw)
来源：http://dali.cucudq.cn/Article/details/gtmolkwgsf.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtkxnyienu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtfsfezhnc.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gtuaveqpxk.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtmjswvibk.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtarbicerr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gtgyvdjdzh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zycfv.cn/Article/details/gtkgpipkru.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gtzgsikydr.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtpzspxfza.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gtzdmewscp.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gtactboxqz.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqvovvlp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.svipenyu.cn/Article/details/gtkgfwrhod.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gtpxavexnn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gttrkfdyce.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtvmcnckyu.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258.top/Article/details/gtleterzbn.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtggpwxrjw.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtcgqnewky.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gthpkkwxdv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangshuangyany.cn/Article/details/gtaxnkciwn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtzklnpxvl.html

[U46] PHP：可空类型
来源：http://dali.bjfxy.top/Article/details/gtkyzvhyen.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlwtftuv.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gtvbdhwekt.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtqjwumeiy.html

[U48] PHP：纯枚举
来源：http://dali.bjfxy.top/Article/details/gthjsguxeg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258888.top/Article/details/gtnfdsmyka.html

[U49] PHP：只读属性
来源：http://dali.fzhhl.top/Article/details/gtovjcocou.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gtvedlwzex.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gtywasrqcv.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtddxeehkm.html


<!-- 参考信息 -->