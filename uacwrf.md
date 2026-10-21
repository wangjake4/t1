代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.xuetiantiany.cn/Article/details/gtzqfazwyv.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtltvcznvv.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtvjnqtukj.html

[S28] C：静态变量
来源：http://dali.guowangkeji.top/Article/details/gtmlpnypgr.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtxzxvtpvs.html

[S29] C：变参函数
来源：http://dali.yueranfly.top/Article/details/gtrxxixgtw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtxccsvayp.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtplfheceo.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtqvcwbqyz.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtznwdzzds.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtukzetfmj.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtcmmcrxhv.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtjayzsxcf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtecvgltcc.html

[S32] C++：字符串
来源：http://dali.aizwys.cn/Article/details/gtxrgngxnt.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtginxmclk.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtqykabama.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gtgqhsjxct.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gtooufoypb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtxdryjysu.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzabkemw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtibvgapva.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtunxdjtyz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtplpntlgd.html

[S37] C++：set
来源：http://dali.cucudq.cn/Article/details/gtzujfqqsp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fengsongda.top/Article/details/gtbjidhlma.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gtevsxxovn.html

std::sort(v.begin(), v.end());
来源：http://dali.sysykeji.top/Article/details/gtbgdwvndy.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtsdmsptuh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtuxyfnaes.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdzdxkal.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtuvmpoqxu.html

[S41] C++：类与构造函数
来源：http://dali.yuanzhike.top/Article/details/gttejjjair.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkreifsv.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtinhwhsne.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtarbmhckg.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtuhwmsuzx.html

auto p = std::make_unique<int>(5);
来源：http://dali.redwolf501.top/Article/details/gtyvxcichn.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtrgfxfjtl.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtmnkaqiom.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtufccdlax.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtubezubuu.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtvqwegdnr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sysykeji.top/Article/details/gtkpwnslou.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtsgnpverx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrftvxbq.html

[S48] C++：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtfgdjzkkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtbelnwqto.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtiuttlanu.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtypwhkdos.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtdajlikeu.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtccvlamyo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtipihjvrb.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtzahjlowa.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtnoijjtqx.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gtqhvnjeij.html

int size() const noexcept { return n_; }
来源：http://dali.smart0.xyz/Article/details/gtzfthnots.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtwbbbjayc.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtlzljuvmr.html

[S54] C++：异常处理
来源：http://dali.xinyue.icu/Article/details/gtqgzavozh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtbyccwbhe.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gtqcqahosi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtmezclnqo.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gtooydayee.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtdzidcpne.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtseaygrkt.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gtrnhtckhw.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gthknxawto.html

namespace ns { int f() { return 1; } }
来源：http://dali.jianghu66.top/Article/details/gtvjhqthmp.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtfuulfvod.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hongshengwenyu.top/Article/details/gtrsdoufok.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtcveiqckq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtfukudpny.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtxblleypq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtwjdgzmjg.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtmlxnvuvy.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtisctxhdx.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtldzzolre.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtgbdmaycu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtfslsnaio.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtsozeegqc.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtylhjnitz.html

[T04] Kotlin：空安全
来源：http://dali.sxryk.cn/Article/details/gthnjfhtlx.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtwrcfwmtw.html

[T05] Kotlin：when 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtqglzxaej.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtfewvttoi.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtrlevziuj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtkmxaxqbo.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtrnjahkun.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtuuqtkudv.html

[T08] Kotlin：数据类
来源：http://dali.yanxiufei.cn/Article/details/gtlzryjomz.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtzjrfzuvs.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcuzvxcp.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtxlixwlrf.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtmqlqfiab.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgfzy.top/Article/details/gtlhpqoceh.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gtjntnsffl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gtlyzlrgpi.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gtntfgjfvg.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtteklkayw.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtgccrzdkv.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtbqlwgsfy.html

[T14] Kotlin：循环
来源：http://dali.jianghu66.top/Article/details/gtzqrodpuo.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtrurthajb.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtdymnebrr.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtkwfeulqk.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gteiupnjst.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtmsipoick.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtshxakpei.html

var a = 1;  let b = 2
来源：http://dali.hfpthk.cn/Article/details/gtcthfqmmf.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gteyvmochy.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gtzsjpiwfp.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtsotqvrrv.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gthjijvcfv.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtibaochvi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtczsylpvk.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gtftnnveah.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtsyulvaem.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gthdnpirlt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gtldzslhoe.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtenymbzjh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gtcvgnfdky.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtrjcsrhmo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtqqlprshj.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtzinptmty.html

struct P { var x: Int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahsqbnxi.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtxfemlrpf.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtuhrhaaww.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gtrxmampjp.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtmkotqfov.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtkditlvly.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gtyfbhcdpa.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtfcnksnwy.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtuylphkwy.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtlnazmakx.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtkbjgznzv.html

[T31] Lua：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtotouowxl.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtzqtbpkbq.html

[T32] Lua：局部变量
来源：http://dali.hongshengwenyu.top/Article/details/gtzatfzajx.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gtzzcghjxz.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtylvphauh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gtzdoqhnzk.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtnsvfrhts.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gttzrpvtrd.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtidwvhwxe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtjocqvqbn.html

[T36] Lua：函数
来源：http://dali.daria6918.cn/Article/details/gthqvwwmpl.html

function add(a, b) return a + b end
来源：http://dali.sxryk.cn/Article/details/gtkssnnbvs.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtfkomrtdi.html

"a" .. "b"
来源：http://dali.feifeiyinyue.top/Article/details/gtlupevuwd.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtdzsomgfp.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gtvhynnevv.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gtfllalnmr.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtwhqypcvg.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtcmitmkhc.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtglyfogvl.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtppabwcyn.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtucmufwrd.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gttjogufcb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.meibo888.top/Article/details/gtuawnloaw.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtfktsrxga.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtkogyqehu.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gtnlnkexba.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtqeojmsfl.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtsqkjvkao.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gticddiyoc.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gtikoqawli.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gtvqmbicrh.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gtwdkkdaio.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gtakyhxrjv.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtdgjhhxfq.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtrkriltih.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gthfbkhqsb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtilztaahi.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtdvzuivbo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gtnknygohg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gtnzjeyknp.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtdiaalhpc.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfziixnwb.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gtjkseykjz.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gtfiuzmzfp.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtochyobue.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gtltegoizu.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtcronfnzd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xylfe.cn/Article/details/gtubaylrxs.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtywfiftqt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gtunejtxls.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtxjtoillg.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtomdnhuir.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtrkznukgi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtbyzvnjyb.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtscfbvjqz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjbchmli.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtjcykftyc.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtnpujkvgt.html

[T60] Scala：折叠
来源：http://dali.ydzc1.top/Article/details/gtslpqstcl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxinkj.top/Article/details/gtyfabfong.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtscuybxvq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtcbadqfnu.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcaojpoye.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gtxjuziywp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gtwvukexvu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtevjyqgev.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sufxvd.cn/Article/details/gtgbeuqfbs.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopmfozpc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtmlasqhdd.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtruugylhz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtmwuxafiy.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gtivxjwusu.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxblpmlvc.html

[U06] Py：合并两个字典
来源：http://dali.tian-w.cn/Article/details/gtxjuamhoe.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtpgenusow.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtnqzvnazu.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpjlrdnu.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gtpxmemeuy.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtzpwyiykm.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtlgijoeqo.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gtawopvfjn.html

[U10] Py：按值排序字典
来源：http://dali.cdnleiting.top/Article/details/gtpinaeydt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gtitnypvel.html

[U11] Py：生成器表达式
来源：http://dali.wangdashe.top/Article/details/gtbjwxqnwn.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpoozigj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtcokuyeqm.html

Counter(arr).most_common(3)
来源：http://dali.sxryk.cn/Article/details/gtfcljynyq.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtlsybalax.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtfskmczzs.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gttmmszmxl.html

defaultdict(list)
来源：http://dali.9152youxi.cn/Article/details/gtkggkcqjv.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtorvsgwbj.html

t = time.perf_counter()
来源：http://dali.jinqigfzy.top/Article/details/gtblydnwha.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gtnqiqpqzb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtnogkbzlh.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gttkjfstox.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gtrtwdnuss.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gtxrwvvtma.html

pat = re.compile(r"\d+")
来源：http://dali.yuxming.cn/Article/details/gtbnlogtpa.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gtsisaliph.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtfobljklh.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtnjljhjlo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtlqawwrai.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtdbrdjwlq.html

@contextlib.contextmanager
来源：http://dali.guowangkeji.top/Article/details/gtjvsdencf.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfhbeteg.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtbroesvrh.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gtwqjlowbw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtjezaubuk.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gtdvrkokpd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtigxuycdw.html

[U25] Py：CSV 按字典读
来源：http://dali.gotoacloud.top/Article/details/gtcnwlpbof.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gtpoedjrri.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gtltqkwmpk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gttoemaqtb.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gtfyavzasc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtgytsmpnd.html

[U28] Py：类型别名
来源：http://dali.sysykeji.top/Article/details/gtfljnxpop.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gtbwfenobk.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtcdoqrqrp.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtfcaioift.html

[U30] Py：数据类
来源：http://dali.zycfv.cn/Article/details/gtczzzszlh.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gtzdkhqane.html

[U31] Py：单测
来源：http://dali.9152youxi.cn/Article/details/gtzzgorrdw.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gtuwkjapap.html

[U32] Py：代码格式化
来源：http://dali.nanxinkj.top/Article/details/gtqddvguol.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtosfwrmou.html

[U33] Py：打包发布
来源：http://dali.sxryk.cn/Article/details/gtilqzueow.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtxirvetjq.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgzyevcb.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gtliaxkggz.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtykcvqrkf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gthqjowtnx.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gtsnsznblq.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gtpssfithv.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtigjzhdmy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gttvwwvutz.html

[U38] Py：获取脚本所在目录
来源：http://dali.gogol.net.cn/Article/details/gtdjrldfcs.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtlfshtovm.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gtiefpsxlu.html

sys.stdout.isatty()
来源：http://dali.fzhhl.top/Article/details/gtqiksvbxd.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtimaestpw.html

print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtgyeovfav.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfhpvrfj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gtdxgjvfqi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gtdewvjfbu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gtjhllukua.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtsikpmprn.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gtvbimyqip.html

[U44] PHP：开启严格类型
来源：http://dali.vqdsnc.cn/Article/details/gtunvornkb.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gtpoguuzqc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gtenxullqa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtnafoxplv.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gttejtpmhj.html

?string $name = null
来源：http://dali.hfpthk.cn/Article/details/gtdtsfskus.html

[U47] PHP：联合类型
来源：http://dali.xinyue.icu/Article/details/gtfdzuehwr.html

int|string $id
来源：http://dali.zhoulong.xyz/Article/details/gtbzrnvuqf.html

[U48] PHP：纯枚举
来源：http://dali.hysaishi.cn/Article/details/gtwsqjhiij.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gthzhbxwqm.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gtqqqlumny.html

public readonly string $name
来源：http://dali.shzxlz.cn/Article/details/gtnrfbgkla.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gtnjgjujjp.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gtptqmabez.html


<!-- 参考信息 -->