代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqyxqafd.html

[S27] C：定义常量
来源：http://dali.vqdsnc.cn/Article/details/gtqlttliew.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelvfdulh.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmyarguip.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gtrybshxfg.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtrickfgcf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtypzrwaxw.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtnqnampcu.html

#ifndef X_H
来源：http://dali.hnxiangtu.top/Article/details/gtvaeszstt.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtyvrnnums.html

#endif
来源：http://dali.iojbl.cn/Article/details/gturofdmsr.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtbqtnwozs.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtoutgpmmb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtxshcuobx.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtxjcplywn.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtmxojkreo.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtxnaowmdc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtcnvxlyol.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtirremozz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtkslinmhn.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtpololpoj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gthizwxmyd.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtczkonmam.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtyfyyotyq.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtdytelfak.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtoxdjrnfr.html

[S38] C++：排序
来源：http://dali.tianlin.xyz/Article/details/gtcuvgltub.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtjcmivlpz.html

[S39] C++：自定义比较器排序
来源：http://dali.jianghu66.top/Article/details/gtsjctyjlq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlmimgbt.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtuwjcjzdm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtsgpmjmhs.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gttquxwciz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtlxdvjeop.html

[S42] C++：继承与虚函数
来源：http://dali.fengsongda.top/Article/details/gtvzytaatb.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenlongwang.top/Article/details/gtlcufqkkv.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtllldsucr.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gtavxkubtn.html

[S44] C++：引用传参
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohuyvywb.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtaiwqzkmm.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtkgvtzhsz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gteadpvzkm.html

[S46] C++：函数模板
来源：http://dali.bjfxy.top/Article/details/gttsjfkfdk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hywenlv.cn/Article/details/gtahjbrkuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtehymcdqn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gtieamaszu.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtroloklfz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtrpaayqak.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtnbjxhwxy.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtjtfccjuy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtyribstow.html

[S50] C++：格式化数字
来源：http://dali.hywenlv.cn/Article/details/gtvsmawhsw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gtbjkmmcty.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtvluxnjwd.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtbraewlvv.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gtfzlykjha.html

int size() const noexcept { return n_; }
来源：http://dali.fengsongda.top/Article/details/gtihipifth.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gtnlnovyvq.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtcnxuowfl.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtnviwvpxt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.quarkkingdee.top/Article/details/gtkgcsybzq.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gtnboghplk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtbebiuqlt.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtldrdqxao.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gotoacloud.top/Article/details/gtuuykgmbv.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtlnbsckbe.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gthhcbzazw.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtvwgmdngx.html

namespace ns { int f() { return 1; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtxmeqlxsz.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtanlbqgst.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jiagoushi.top/Article/details/gtjabumtjl.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gttbstespu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.smart0.xyz/Article/details/gtxwrndpqh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtokkhpqwd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tanke756.top/Article/details/gtbgxostpm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtktyfozxt.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtwhhcajii.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gthvvwuwgk.html

[T02] Kotlin：变量
来源：http://dali.ydzc1.top/Article/details/gtxshmjskv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbelgzao.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtrzzzxqvn.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtqmwakgfq.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gtmyibxpge.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtetioraic.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtvatejlga.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shangyingyoupin.top/Article/details/gtvftvdvqe.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtmdvgoehq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtkzidvhsh.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtphvkhdcm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gtituyqhxt.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gttmxobljo.html

data class User(val name: String, val age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtlphicsdl.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtsrvkkfqb.html

fun String.exclaim() = this + "!"
来源：http://dali.chenlongwang.top/Article/details/gtbduaqftz.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtciwscxyb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtphqiudka.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtpdzctemd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gttufbdpoj.html

[T12] Kotlin：解构声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidtlspwe.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiderbrf.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtquwmlcst.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gtscxyltpe.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtjwnesdjl.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtcjxtsbrk.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtvaqpjsrl.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gtebnwlvnb.html

[T16] Swift：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtzlvxtkkf.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtzwzbglvf.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtuuoabgpp.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtjdyakuev.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtraxsvqzf.html

"值: \(b)"
来源：http://dali.shzxlz.cn/Article/details/gtshcdfkfa.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtuekacvnt.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtdmanvzkj.html

[T20] Swift：数组操作
来源：http://dali.sufxvd.cn/Article/details/gteostyylf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gtfxfoghjm.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gthlymvwuz.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gtldesigin.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtyqhwqxdu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtqcvjqtid.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtyctorwda.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtzgouembn.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtpcyoqfyt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtpttsruzo.html

[T25] Swift：结构体
来源：http://dali.nwbrower.top/Article/details/gtceplaqum.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaajyoqd.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnfdxurx.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtbcqnkvca.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtxqwnckli.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gthwclgduj.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gtgiglhfmt.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfahbfkj.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gtklqmuscd.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtoyplkysr.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtztyozahr.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtgrugjxxa.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpnefpyz.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtzddkqixl.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtimffxqrv.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtckuiwwuk.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gthomhozdp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.316326.xyz/Article/details/gtqjufvqjo.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtjpteelmv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtwjnibkal.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtkknkdyrg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yonumen.top/Article/details/gtflwksvdh.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtargcdfpv.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gtpfqdstjs.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtxeuhtzjz.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtpuzyslqj.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtarinpsos.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtrxlenytj.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtrydadeuv.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtsshbjehh.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtnzktrlii.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gttattlqry.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtiwtvgmji.html

print "Hello\n";
来源：http://dali.zhaomingkeji.xyz/Article/details/gticiouswd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtshxreamb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtmcvntzgj.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtjabqjous.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gtrlxzighj.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gtxkbtzzvj.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmebiqoxm.html

[T45] Perl：数组遍历
来源：http://dali.birdmap.top/Article/details/gtfayggdnc.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gteokzruor.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gtbcxschgb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtvcmqodqp.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtzvlchpsr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gtigejorsu.html

[T48] Perl：正则替换
来源：http://dali.yvedp.cn/Article/details/gtexvmvtmu.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtztavplzh.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtkgiaqcoy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtctxntlma.html

[T50] Perl：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtiefgmhaf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.birdmap.top/Article/details/gtkuocglpe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtegomydqg.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtctcuhqzc.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtauuodwdj.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtmobkageq.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtfmtjvwoy.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtbthpyyzh.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjplxwpc.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gtdguqxjma.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtrstchqke.html

[T55] Scala：集合过滤
来源：http://dali.birdmap.top/Article/details/gtkjmuviph.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhixingplan.top/Article/details/gtlgyzshrt.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtztcwfcvo.html

case class User(name: String, age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtooyojmmx.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtgtqzhkcu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gtrwgkvxzt.html

[T58] Scala：函数定义
来源：http://dali.hammf.cn/Article/details/gtmvlhgokc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gtcjurnxyq.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtwfivpaeo.html

for (i <- 1 to 10) println(i)
来源：http://dali.iojbl.cn/Article/details/gtkveiijpq.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gtjkqyecej.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.smart0.xyz/Article/details/gtbvuwsshv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwxkotspz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuanzhike.top/Article/details/gtfwbzfusm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdluhjlwn.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtvzlcsqwe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcejhxmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aizwys.cn/Article/details/gtbznjhmlo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtbtgapzqz.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtzznjadmq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtscldodoo.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gthvhnktrg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtrfsuromj.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtmnyfmeiv.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gturpuczew.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtjoqgbyep.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gtqbvwhchc.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnvnrhrq.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gthcniphrb.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtvgkmnllg.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjesivnab.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtcfjqshou.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gtwuqpydrx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gtczarumlr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtygdapjda.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeugbhgr.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gtnzmfuulk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.kuanghao11.cn/Article/details/gtyasaazrw.html

Counter(arr).most_common(3)
来源：http://dali.xinyue.icu/Article/details/gtfocglchu.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtmezybxpr.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtctedikqv.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtblthphsz.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtvapqeeqo.html

[U15] Py：高精度计时
来源：http://dali.yvedp.cn/Article/details/gtkqlhlrge.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtleivozls.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gttwmmvfad.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.c1oappe.top/Article/details/gtxcnrekwj.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gtbjdmrveu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pycfn.com/Article/details/gtthqkhsbk.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtpsaenfpo.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnyjsvdd.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtgrkkabon.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hysaishi.cn/Article/details/gtsekseaby.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gtvesvgpad.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zycfv.cn/Article/details/gtjaxvxmhz.html

[U21] Py：自定义上下文管理器
来源：http://dali.gaohongyu789.top/Article/details/gtebluwouj.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtbddolsky.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gtrdyrfizc.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gttpigtsyn.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gtdggjahjm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gtcfundzbt.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gtvhpenpyv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtolbpuutb.html

[U25] Py：CSV 按字典读
来源：http://dali.nanxinkj.top/Article/details/gtwulvqfgu.html

csv.DictReader(f)
来源：http://dali.aibaodan.cn/Article/details/gtmrjnquec.html

[U26] Py：并发下载
来源：http://dali.tian-w.cn/Article/details/gtaqktynrd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gtcgwoaxtm.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtfpilbunq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zycfv.cn/Article/details/gtzkmhcojz.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtcpchackb.html

UserId = int
来源：http://dali.cheryme.top/Article/details/gtqolecskb.html

[U29] Py：属性校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzgyuvcf.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gtzdpadtnp.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtsvbuxlyh.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gtfjinfqmo.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtjnzqhdzn.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gtobzrkozb.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtowdbxkyd.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtcxnmxzpa.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gtbecvuojo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hywenlv.cn/Article/details/gtqlycivfq.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gtwsqqbnkv.html

chardet.detect(raw)
来源：http://dali.nanxinkj.top/Article/details/gtohsflclc.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtkcdkpuam.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtnnzfcexw.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnabafdqp.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gteacqesml.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtdwioagzj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gtocoedqsb.html

[U38] Py：获取脚本所在目录
来源：http://dali.yueranfly.top/Article/details/gtmfysvppi.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gtrxttzqvd.html

[U39] Py：判断是否在交互环境
来源：http://dali.hysaishi.cn/Article/details/gtdmhpapyt.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gthmhakdge.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gtmoxhqqpp.html

print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtapmjvsie.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtrwijgues.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gtdrjinusl.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gtpwvquvdh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtwehqfehl.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gtrzlizawy.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gtxemfujuy.html

[U44] PHP：开启严格类型
来源：http://dali.pengpengdd.cyou/Article/details/gtgwefrura.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gtzvuruhyh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aibaodan.cn/Article/details/gtudqrzifg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtfrfumzwl.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gtrevqnpgf.html

?string $name = null
来源：http://dali.daxiang520.top/Article/details/gtugojpdet.html

[U47] PHP：联合类型
来源：http://dali.vqdsnc.cn/Article/details/gtjubszspx.html

int|string $id
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuobdsxhc.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gtsgfisgfg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvslxiif.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gthyeeeqln.html

public readonly string $name
来源：http://dali.jinqigufen.top/Article/details/gtaexqxhpo.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtyxvugwpk.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gtkpqfqvju.html


<!-- 参考信息 -->