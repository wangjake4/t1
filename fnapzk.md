代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtoqdkrlkw.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gtlnpicwwf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtcgajjdco.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtxprezmys.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gthxunrkqm.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdurpuxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtvofvisxx.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gtxsusixng.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtjzlhxiye.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtalrtnoky.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtotdyvwvo.html

[S26] C：内存清零
来源：http://dali.zhongyouzk.top/Article/details/gtikspsacw.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtgeejhkto.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtrqhyjrth.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtjkcxaxcu.html

[S28] C：静态变量
来源：http://dali.smart0.xyz/Article/details/gtghxmgfuo.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtbdckshmy.html

[S29] C：变参函数
来源：http://dali.fengsongda.top/Article/details/gtcqmwkplv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtufszlwqc.html

[S30] C：头文件保护
来源：http://dali.jiagoushi.top/Article/details/gtwgldsjkw.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtgsrqlbth.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtzgbcxnkb.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhgqzawy.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtgweidian.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtctwpxpcw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtperjjied.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtnrkqfuvf.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtfgnvlgie.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gtsbavqzdl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gtozkrhyzt.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gtoeemzwvb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtoajpajsu.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gtrsjocwnk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtuigrqzqj.html

[S36] C++：unordered_map
来源：http://dali.wangshuangyany.cn/Article/details/gtbzeleslo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gthiaqyfsk.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gteesrnegw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtsxblipkw.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtpboswnfn.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtvveshgrk.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gttlviqucc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtrqartgcb.html

[S40] C++：查找元素
来源：http://dali.cdnleiting.top/Article/details/gtldjmxuwq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtjtizpyqj.html

[S41] C++：类与构造函数
来源：http://dali.cheryme.top/Article/details/gtmbupadsx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gtynogptxi.html

[S42] C++：继承与虚函数
来源：http://dali.yvedp.cn/Article/details/gtajlbgbcj.html

class B : public Base { public: void f() override {} };
来源：http://dali.fzhhl.top/Article/details/gtchklemlp.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtazafmmpk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtthhqbjzf.html

[S44] C++：引用传参
来源：http://dali.gaohongyu789.top/Article/details/gtzlpimeec.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtazjwysub.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtgdhfufzt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdymmsik.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtzfiymoyw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sufxvd.cn/Article/details/gtyirfyqst.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtuysqgpfk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtkqmqylvu.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtyixzjyqu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ybcxt.top/Article/details/gtappdkcjs.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtvpejxwwg.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gtjparqxqx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gttaoqcsje.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtldfxaqtk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtzdxiwamy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtpcbiixcd.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtahaxidvx.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gtcjfktkcz.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpigpslek.html

[S53] C++：移动语义
来源：http://dali.shangyingyoupin.top/Article/details/gtjnqjcele.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtzqlyoahg.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpamyxrz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gteemdxilk.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtrdnxdmkd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gttyalccjh.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gtidmsijfj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtmgvrohzd.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtbecphrsn.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtmcpyymqn.html

[S58] C++：命名空间
来源：http://dali.xziqi.cn/Article/details/gtoxjiorqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtgsontmio.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjmlvgjx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gtfghgzdif.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkzrhfvi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtjcfmfccm.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtpqfzccut.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtgedebjgr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtpifriusl.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtbiqnwatf.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtdyegzexe.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtbphcbkkf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gtpnxxnrap.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtrfkikynd.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtfutavnis.html

[T04] Kotlin：空安全
来源：http://dali.chenzaomai.com/Article/details/gtwdwioltv.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtdxrycwgr.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtlrncvwdd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtnysbmnbk.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtultdvrkc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtanbynjhj.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtiwzdqvow.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtjsgpuodf.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gtsjtrjdbj.html

data class User(val name: String, val age: Int)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmspqigpr.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gtdjnxcfxk.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtflhwvphx.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtoklyaukb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtbbocoelt.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gtmchaspiw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtwjrnxvuf.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtedrlcxac.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gthasvpowt.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gthyrcgfia.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gtrpcpsdzn.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtlitqstsh.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtamlnvnyx.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtrtisymvn.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gtnbltjfkx.html

[T16] Swift：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gttrsdhxao.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtdinafzud.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtuhjkcpbm.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtoschekll.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtgnxfvmxl.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtpysgxrdm.html

[T19] Swift：可选绑定
来源：http://dali.ppjwa.cn/Article/details/gteapjanjk.html

if let n = opt { print(n) }
来源：http://dali.xinyue.icu/Article/details/gtglfahmpv.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtblvcpqxk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhengqikj.top/Article/details/gtvehgwayx.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtagtfyaoh.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtmkfkyetw.html

[T22] Swift：字典
来源：http://dali.zhiwuduotai.top/Article/details/gtynqdvhkk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.bjfxy.top/Article/details/gtnmlremuo.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gtnyikhkrx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gturjtaste.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtcfdmagcy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtwyubjyag.html

[T25] Swift：结构体
来源：http://dali.ehwqpu.com/Article/details/gtdeykordl.html

struct P { var x: Int }
来源：http://dali.pycfn.com/Article/details/gtnalwiewr.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtzhugfeno.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtrqyxkwot.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gttrmncxub.html

do { try f() } catch { print(error) }
来源：http://dali.yj202588.top/Article/details/gthhvziver.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtchivyvzl.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gteakemkfm.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtveardyfp.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gthrnefmug.html

[T30] Swift：协议
来源：http://dali.jqgfzy.top/Article/details/gtlwfnanjy.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gttvkhdmdj.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtahqqqvmq.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtoylknrkl.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gtujoayecw.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtqvzxnafk.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gttscvwhim.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtyskuocdh.html

[T34] Lua：遍历表
来源：http://dali.aizwys.cn/Article/details/gtpgfeedqj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yueranfly.top/Article/details/gtxwvpthfb.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gthvjavfkd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabipbure.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtwbderqdm.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtkfihvobe.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gtrhwkobhw.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gtczrrgsac.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtskwyrdny.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gtwgpprflz.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtcmixlrvg.html

string.find(s, "%d+")
来源：http://dali.c1oappe.top/Article/details/gtsiafjvhh.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gtmipfnlus.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtoborabaa.html

[T41] Perl：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtjkjukpyv.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtqeglyzzq.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gtipegxggm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtactkeylf.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtfijhzkqa.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gtsmvkkyag.html

[T44] Perl：条件
来源：http://dali.yanxiufei.cn/Article/details/gtkbkddxqc.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gtmuiqzdkn.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gtrnrcguvu.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtwssyznmo.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gtjkytbeut.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtriihyvjg.html

[T47] Perl：正则捕获
来源：http://dali.yuanzhike.top/Article/details/gtupbixmtg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtnaffwdjf.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtndjteesf.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtgbogozod.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtlxktpqfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtasgjgmsd.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtdcgqlxlp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yueranfly.top/Article/details/gtqydevkxk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtocjilhpg.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwhdqftq.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmodwpfpu.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtfbizfwkw.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gthevcgvoi.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmitqwaw.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gtuxirgeem.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gtifakbjjq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gthypfntwb.html

[T55] Scala：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtfjvbvmgw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pycfn.com/Article/details/gtzdqlnynv.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtujjaoeak.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtwrejdojl.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtqovmesxw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinqigufen.top/Article/details/gtlcbwiywx.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtsvyheapg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gtuaqpunan.html

[T59] Scala：循环
来源：http://dali.dashuyun.cn/Article/details/gtlcxjaicv.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtpfnimtfl.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtnnphpebt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gtqbcwzmsl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtupwhbbor.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gtqetjpmgr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttwfqngox.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgfzy.top/Article/details/gtpgkdpjpy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gtatfaaztu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gtjjhlxnfx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gthzmpmcjy.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrptrudsb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gtozasqxjk.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtnwcftmam.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtwqbbksad.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtsrbcspnv.html

list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpqssbghn.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gtmwmprcco.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gtatvbwevn.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtuagghsby.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gthljsedyo.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtmbqksnio.html

[y for x in nested for y in x]
来源：http://dali.pengpengdd.cyou/Article/details/gtlyinbegn.html

[U09] Py：字典取最大值的键
来源：http://dali.316326.xyz/Article/details/gtukgbwudm.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtnzhrbhbn.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtquyrhgqi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gtnqtnyaeg.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gttpwlhxus.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtgjpdzxov.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gtaxmqkuxu.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtiryrgrtb.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtjjfnqvid.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtqmagnleb.html

[U14] Py：分组收集到列表
来源：http://dali.birdmap.top/Article/details/gtuwhoftte.html

defaultdict(list)
来源：http://dali.cheryme.top/Article/details/gtcmrgyzrf.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtkwtgukvt.html

t = time.perf_counter()
来源：http://dali.zycfv.cn/Article/details/gteqcjouwh.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gttxvrtrnf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenzaomai.com/Article/details/gtpllhlfgd.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtbmpmdxfn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gtyvlvgyal.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtizokdkpg.html

pat = re.compile(r"\d+")
来源：http://dali.yanxiufei.cn/Article/details/gtktmspzhb.html

[U19] Py：正则替换带回调
来源：http://dali.zhoulong.xyz/Article/details/gtjpalwycb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtjwdlmrfp.html

[U20] Py：缓存函数结果
来源：http://dali.nanxuanxn.top/Article/details/gtlnjrljug.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gttigpnlsu.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gtetoimgbg.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtrdvhzjle.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmtztylp.html

list(zip(*m))
来源：http://dali.daria6918.cn/Article/details/gtmgnxutbg.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gtsylmkxxj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jyoumei.cn/Article/details/gtelbayifw.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gteuwibeud.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbgesxvg.html

[U25] Py：CSV 按字典读
来源：http://dali.yvedp.cn/Article/details/gtzoraqcdf.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gtujvqwpqq.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gtkoqktibw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gtapksewwr.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtboggvrmw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.meibo888.top/Article/details/gtovuqioqc.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtazxfpwph.html

UserId = int
来源：http://dali.hnqzz.top/Article/details/gtunddfvvi.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtycxhjdjg.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtbqptsqna.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gtkpmknqqk.html

@dataclass(slots=True)
来源：http://dali.daria6918.cn/Article/details/gtxcmsajqr.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtcgbiqfyx.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtejwsmjfy.html

[U32] Py：代码格式化
来源：http://dali.yvedp.cn/Article/details/gtaoampxxu.html

ruff format . && ruff check --fix .
来源：http://dali.yonumen.top/Article/details/gtyshqymew.html

[U33] Py：打包发布
来源：http://dali.yj202588.top/Article/details/gtqzlcuzzn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gtizmvjdji.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gttwrciudj.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtobscinms.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtcdxdtibz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gtqudddgeo.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtctaprnoz.html

schedule.every(10).minutes.do(job)
来源：http://dali.tian-w.cn/Article/details/gtguywriie.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtflorrwmi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cdnleiting.top/Article/details/gtsdtobnrq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtzyppkuvq.html

Path(__file__).resolve().parent
来源：http://dali.sysykeji.top/Article/details/gtgysgthuo.html

[U39] Py：判断是否在交互环境
来源：http://dali.dianchejie.cn/Article/details/gtdceitzgm.html

sys.stdout.isatty()
来源：http://dali.hongshengwenyu.top/Article/details/gtpljkylxm.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gtejudyuky.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtvrnbrdhi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gtdivxmnig.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenzaomai.com/Article/details/gtvkgntuyr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtmhcqsjmp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtnuwbbbze.html

[U43] PHP：声明命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopnrpvsw.html

namespace App\Http;
来源：http://dali.birdmap.top/Article/details/gtucnnoziy.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gtkfnqiahs.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gtacmvmkrf.html


<!-- 参考信息 -->