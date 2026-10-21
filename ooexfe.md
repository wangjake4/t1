代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzoifbxkb.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqgfuwha.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aibaodan.cn/Article/details/gtgvhfazdc.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtrhvnejpl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtriaqpshc.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtgtafwsge.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtjynnypcv.html

[S26] C：内存清零
来源：http://dali.sweek.top/Article/details/gtweszeozt.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtwxbjmnvf.html

[S27] C：定义常量
来源：http://dali.cdnleiting.top/Article/details/gtwyrvqlhv.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtobloiinf.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gtwgxebucn.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtutkubxeb.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gtibuwrlkd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daria6918.cn/Article/details/gtvncxplgp.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtomorfolg.html

#ifndef X_H
来源：http://dali.yuanzhike.top/Article/details/gtmspzqusm.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gtgevljqet.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtkytttqpt.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtpghvjdxx.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtpoebarxa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jyoumei.cn/Article/details/gtmwfsjyjh.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtotodsqfy.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gtcjfdlfwi.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtadxdncai.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gtoybmfrld.html

[S34] C++：遍历 vector
来源：http://dali.ivvv.top/Article/details/gtazmdcotl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtncbekcbn.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbvaqdin.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtdnrymuna.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtkzjhkpoq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtbbtqumqa.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtvfdgvyzb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtlufcuyte.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtzdtyyqul.html

std::sort(v.begin(), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmhbnujb.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxvsfdfw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtdxltssbk.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtelveyrjb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sxryk.cn/Article/details/gthukzcovz.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtfovendjv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtawwzcwro.html

[S42] C++：继承与虚函数
来源：http://dali.aizwys.cn/Article/details/gtrjcknrjc.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtwvfdkyuh.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gttcqgrmwn.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtmymorrds.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtkzxclxby.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gtogztdbaz.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtaythrgru.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtfeuzshhm.html

[S46] C++：函数模板
来源：http://dali.hywenlv.cn/Article/details/gtkkkkenxq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ydzc1.top/Article/details/gtrhkmjeim.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtngimwkoi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtltwpzosi.html

[S48] C++：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtvnownbjq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gtjxvuijnr.html

while (std::getline(in, line)) { }
来源：http://dali.bjfxy.top/Article/details/gtswfzkpjl.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtjuvmoxpt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtqbaltnxh.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtkanlssoh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtshifjzld.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttypdhfqr.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gttowmeabb.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gtqblfxcfq.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtfmcwyxro.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtnzozuhvx.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvhrzzbz.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtumtvpkjh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtwneiukwe.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gtafpnrwzp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hammf.cn/Article/details/gtrdrqfywu.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtsqqihdvk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtnzwyjecd.html

[S57] C++：编译期常量
来源：http://dali.chenjidiqi.icu/Article/details/gtnfnvjyvu.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gthprbbqqe.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtjxxglytn.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gtsnuqvpfz.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtklvcfgha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbbzijjd.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtpfkmtnlu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gteudrzpes.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtfxpwol.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtxixnvnih.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gthzmcxxwh.html

[T01] Kotlin：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtawbkdfpq.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtpxbbbpyp.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtbwnpokek.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gtuxklokyl.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gttgyptbuj.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtxppbwcfo.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtkrzfzlbi.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtrmiwnoml.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtnkvwecxf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gteriajghe.html

[T06] Kotlin：集合映射
来源：http://dali.0kj1m.cn/Article/details/gtvzhtapae.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtwuwwvsij.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtxasdnjjw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnywliruy.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtqlpivebk.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtlilsfipk.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gthmhgaptp.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyevuaxhm.html

[T10] Kotlin：默认参数
来源：http://dali.gogol.net.cn/Article/details/gtfltutdrv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gtakkpumcb.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gthzcqkmxk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtzwghctlq.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gtbscmkgsx.html

val (a, b) = Pair(1, 2)
来源：http://dali.cqqwz.cn/Article/details/gtvlofwwua.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtxlgriaib.html

val m = mapOf("a" to 1)
来源：http://dali.guowangkeji.top/Article/details/gtapwyqjne.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtswhxpuhh.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtlcukhhme.html

[T15] Kotlin：接口
来源：http://dali.redwolf501.top/Article/details/gtovetwuqf.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtclcitnbp.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtghcjwiqn.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtknbnloyw.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtmupleafb.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtymihzogw.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtgjnpigbd.html

"值: \(b)"
来源：http://dali.yonumen.top/Article/details/gtkxmcajzf.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtibhtdkgp.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gtkkogptab.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtaimqepej.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gtmcnjdmql.html

[T21] Swift：遍历
来源：http://dali.jqgufenzy.top/Article/details/gtsiwujlky.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvbjqzpu.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtpqqcsbju.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtbpqrvckc.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjfbjmya.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.haohaochexian.top/Article/details/gtqpsvfoql.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtcyqtovsj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtmpbxfpxf.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gtnhdqlosn.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyxlqaqs.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtozatmdad.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtyyebtppm.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtfxduwnhv.html

do { try f() } catch { print(error) }
来源：http://dali.sweek.top/Article/details/gtfatkmuwh.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtrnkwxjmp.html

enum Color { case red, green }
来源：http://dali.guannengcc.top/Article/details/gtvhoalpvo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtloopjaau.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrpfozuq.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gtdctpplvr.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtwdnpyfhg.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtsnsqmkwc.html

print("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtlxagaqxe.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtrdfzqqqa.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtcvdjuwcg.html

[T33] Lua：表（数组）
来源：http://dali.gogol.net.cn/Article/details/gtxpzaxtur.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtijkuzewo.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtefmovmtn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtadampzvx.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtoghxlbrn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtgbzmowlc.html

[T36] Lua：函数
来源：http://dali.jianghu66.top/Article/details/gtzfldkqls.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtkwgakcfo.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtwodoohmb.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtmixlyogx.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gtnsdhrkbv.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtygwatqar.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gttpqfoigx.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtyyekabji.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtqizrpbtk.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtsfnfhkmz.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtrybezvmu.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtrvnnahiu.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gtclbsedzu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtxfcnsdji.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtgidbrzhk.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gthfiyszqz.html

[T44] Perl：条件
来源：http://dali.tanke756.top/Article/details/gtjxmqknum.html

if ($a > 0) { print "正"; }
来源：http://dali.meibo888.top/Article/details/gtisfqtmes.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtkxlpwrvu.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gtdqfrrugo.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtxryawlvb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtajsckslf.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gtmweoortn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gttqlvysci.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gtqobuadvz.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtiotuizxd.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtwhbkxsta.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gteszpxoww.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtioklzand.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gtuwmrvzml.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtvhxqbpns.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaadvaelr.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtldeompxq.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtnbafkzgt.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtchcoblou.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtwaoonlsp.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gtrvijebzu.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtdbemlwdm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gttmyfkhsy.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtjmjwfhdl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuanzx.com/Article/details/gtuxibnewg.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtverkwabu.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtuoowczgz.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtprpfsmau.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxkcaifn.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gturbwceut.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtiqcjhffn.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gtvdcdwtmb.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtxrwjydvd.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gttfayffoq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtpchijfau.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtpewczkqx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gtyzxeibqh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtzfeoxuba.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gtbzytzaqm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtsvahcmyk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtgmuppgmn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhbmgqxl.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtukereoib.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.snrcjt.cn/Article/details/gtzbuqtxig.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gttrqleynl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtrzqwimqg.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtkgdzpcls.html

list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtvewnmrkk.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gtloibmemm.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtwkipbtkv.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gttcxslgsz.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtqbruyhmo.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwdytmlx.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gtvapudqwy.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtgfzxhobs.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtskmreowz.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gtkbadcpqy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtrhwrabsa.html

[U11] Py：生成器表达式
来源：http://dali.havefunace.top/Article/details/gtujkbvhxn.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gthtfhbxvf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gtlsvxwyuk.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtozucnqzo.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtyipkpxhv.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtbrdapwxr.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gtrherqjrr.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtwtwmxmhn.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtmombtsam.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gtpqkgepkc.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gtdnembbui.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cashguo.top/Article/details/gtptpdgpul.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtdvpudukh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigfzy.top/Article/details/gtfquyzhde.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtfkewbllw.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gtvhmjfijx.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gtzduqcsty.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gtmvdaxvgj.html

[U20] Py：缓存函数结果
来源：http://dali.guannengcc.top/Article/details/gtknwlooqn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzqpiyjyx.html

[U21] Py：自定义上下文管理器
来源：http://dali.meibo888.top/Article/details/gtooryvcah.html

@contextlib.contextmanager
来源：http://dali.andypj.xyz/Article/details/gtbbvonacp.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtonykfvkx.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gttgckwril.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gthxxepbmt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gtrwuiwvun.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gtnwqnyszf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtveagjywa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gtxcclipzp.html

csv.DictReader(f)
来源：http://dali.yj202588.top/Article/details/gtglzstikx.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtjnfctcty.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtwetnlsqf.html

[U27] Py：异步 HTTP
来源：http://dali.xinyue.icu/Article/details/gtvtorpczp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gtrvnyxffa.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gteekilqfs.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gtpupgcybd.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtnoyutuap.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtbdnndoii.html

[U30] Py：数据类
来源：http://dali.iojbl.cn/Article/details/gtkesjwykq.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtqdwscooq.html

[U31] Py：单测
来源：http://dali.wangdashe.top/Article/details/gtabqozrza.html

python -m pytest -q
来源：http://dali.tian-w.cn/Article/details/gtkwttboeh.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtuutnqzat.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtkdhsvdoa.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gtdviqytll.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvubmbnjd.html

[U34] Py：判断编码
来源：http://dali.xuanzx.com/Article/details/gtfwoupuzn.html

chardet.detect(raw)
来源：http://dali.shzxlz.cn/Article/details/gtuwkusyvp.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtbvsjlfey.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jyoumei.cn/Article/details/gtqubhzsjc.html

[U36] Py：定时任务
来源：http://dali.jyoumei.cn/Article/details/gtjbvexcbx.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtawpvwawb.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gtiartmyka.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtltkbodiq.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gtjhmuwobu.html

Path(__file__).resolve().parent
来源：http://dali.xylfe.cn/Article/details/gtpaikxyjv.html

[U39] Py：判断是否在交互环境
来源：http://dali.cashguo.top/Article/details/gtvwyvpvua.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtdbtwxyka.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtqwwuhipw.html

print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtkpmiocfd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhongyouzk.top/Article/details/gtuhjyjdmy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtaewpjlyp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtmcvvzigj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gtkeqqezub.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtsnebekqi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gthlbmtelf.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gtakurawhj.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtfeveztkq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guannengcc.top/Article/details/gtiwhkeanx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtjhmnxhpk.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlacsihpk.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gtnglkioka.html


<!-- 参考信息 -->