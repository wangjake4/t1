代发 wailian999

static int counter = 0;
来源：http://dali.xuanzx.com/Article/details/gttmligkpp.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtmbvniynf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtrnsocphv.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtjbkohqdp.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtefwuxylc.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gtuhdkhala.html

#endif
来源：http://dali.iojbl.cn/Article/details/gtoezfbibr.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gttldqbnal.html

#include <iostream>
来源：http://dali.gotoacloud.top/Article/details/gtgmrovwsp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtsmckdpnn.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtnihxpwtr.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtkucjjssk.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gtemqcgrzh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gthjbixxnu.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gttlqorevq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtjjmjmhlp.html

[S35] C++：map
来源：http://dali.yvedp.cn/Article/details/gthxstwggy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtbwemafnp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gtlzoxxlew.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtumvlxipj.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtigqlevlm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtrqennawo.html

[S38] C++：排序
来源：http://dali.xuetiantiany.cn/Article/details/gtelsfseaw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gtnqkiqgxy.html

[S39] C++：自定义比较器排序
来源：http://dali.yuxming.cn/Article/details/gtgygkzqip.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gthzqhaxqp.html

[S40] C++：查找元素
来源：http://dali.haohaochexian.top/Article/details/gtcvpyyeia.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtaiweurvr.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtfswgpfwv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xinyue.icu/Article/details/gtefexyeox.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtafonblmt.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtmhaeyzfh.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gttbyhcrzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtyxdqgobb.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtzsupywru.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtsflntdyo.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtrawgpisb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtaiiwynfi.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtxvzupkve.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gteborxmex.html

[S47] C++：结构化绑定遍历
来源：http://dali.daxiang520.top/Article/details/gtgkwaqktr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gttpoonlqv.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtvbvwehmt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtqeaeaggb.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtldbandvh.html

[S49] C++：写文件
来源：http://dali.chenzaomai.com/Article/details/gtecytzmaf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yueranfly.top/Article/details/gtdmzglonv.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gtybnszewl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtjnobrjje.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtvhfenohz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtfxcapzkz.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtkfhusetn.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtroncizyp.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gthbtpdlqb.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtkkutrfgt.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtmnmipssv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtpczxrtvx.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gtfzlskfbo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtbqytaviz.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtrgxhzibp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gtsjzdbjyk.html

[S57] C++：编译期常量
来源：http://dali.sweek.top/Article/details/gtlrcqjiit.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtjlaetndm.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtqcuyftrm.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtjpnirkea.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtthcboesk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gtrbncnyqs.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtnwzkammk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtardvqmkj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtikusdwdb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gtztoapchz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtelkfevlg.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtljfhqbzc.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtdrfvaloj.html

[T02] Kotlin：变量
来源：http://dali.nwbrower.top/Article/details/gtzwvlgexs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtpukokmjs.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtcolclvol.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtukcbumwn.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gthfvxfzer.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtrytyxbkq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkofvxkq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aibaodan.cn/Article/details/gtgaagznhe.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtycurittn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zycfv.cn/Article/details/gtpfbglbbj.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtjsulmkjt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtokirdcfr.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtozwxefeu.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwgzpgfk.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtpwzzwxin.html

fun String.exclaim() = this + "!"
来源：http://dali.zhiwuduotai.top/Article/details/gtcmwxoidt.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gtyozvngos.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtzpowakgo.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtxskdwxgc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtamwdmndf.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gtvseuuyih.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtfevuxtjv.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtyerjbfoh.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtxffwojaw.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtmojttntn.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtkqfnjlxz.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gtbjoadwjv.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtnpllbnzn.html

[T16] Swift：Hello World
来源：http://dali.yuxming.cn/Article/details/gtlktzbvsk.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtewbveima.html

[T17] Swift：变量与常量
来源：http://dali.hywenlv.cn/Article/details/gtiukuuhzm.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtbsunhjev.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtmucbevzv.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gtuwpauopc.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gtqksyajhy.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtilrbyxwe.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtzklktjue.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtzwxpvvaw.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtkhxaajwx.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtfrdfkjby.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gtehhouyce.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtktamnkom.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gtumspugwo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtdscecqdq.html

[T24] Swift：闭包
来源：http://dali.dianchejie.cn/Article/details/gtavwpjlhh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmcphibhf.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtcpxykeyj.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtvwdggjhk.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gtpfmpavxu.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gthmdwlvml.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtuhgwhoxk.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtmisvlyap.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gtknsmuxsh.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gtabngwjnr.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpmnlwxz.html

guard let x = opt else { return }
来源：http://dali.jiagoushi.top/Article/details/gtwcehwdbs.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gtvrfzvntc.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtktfnhvgq.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtmvvzpjso.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtsraotuvl.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtuvtgkkdr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtocsmiyod.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtvpogyagf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yvedp.cn/Article/details/gtgjfufolt.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtcamsmxkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtddceksbq.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtvpcmzhtk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtpxtdknus.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtifwsufuh.html

function add(a, b) return a + b end
来源：http://dali.iojbl.cn/Article/details/gtkfyaiqtx.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtwrrvahoq.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtojsergny.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtjtqbeafu.html

if x > 0 then print("正") end
来源：http://dali.yonumen.top/Article/details/gttiywyjyw.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtpjdxoyil.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtrtpphhyx.html

[T40] Lua：元表
来源：http://dali.sufxvd.cn/Article/details/gtvokrhpiq.html

setmetatable({}, { __index = base })
来源：http://dali.cdnleiting.top/Article/details/gtmzcyvrqd.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtkigkvfaz.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gtzbgxgkba.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gtzxdgpwel.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtitbxiqru.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtqkcrqrhr.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gthmxunyak.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gtszxqpody.html

if ($a > 0) { print "正"; }
来源：http://dali.guowangkeji.top/Article/details/gtktxuqgaz.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtnaujlrxc.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtsguellzh.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtlpdavdec.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.birdmap.top/Article/details/gteqobxsnc.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtfgbstlgu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtwqcxarva.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtwxxzbhjo.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtvhvzwrpq.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtngxhkprr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtldqgqjpf.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtxnfisvlm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhiwuduotai.top/Article/details/gtaobxtnfg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtelystiix.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtoggjzdzv.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtruazlpcq.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtxvwjymxp.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gtyyjtysyx.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtrumidapr.html

s"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtfracauox.html

[T54] Scala：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtndoxfolv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaohvgef.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gtggzpgdyr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwilxjiy.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrxbapbm.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtfouzdzgb.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtqieudjih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gotoacloud.top/Article/details/gtjfvniarj.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gtxoyjmevc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fengsongda.top/Article/details/gtectixjxo.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gtwwzbvnno.html

for (i <- 1 to 10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtfmxrqadm.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtbwpfxfyt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yonumen.top/Article/details/gtvpurofgb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvldtonrh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtpveyuljg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtalxohjfz.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtdimcyrip.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaopzubgw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gtcommyhvq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gtqyilmnsq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpisydwvg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aizwys.cn/Article/details/gtodhngjwh.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gtbzzwctza.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgufenzy.top/Article/details/gtfmqrqwde.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtkfbivcyj.html

list(dict.fromkeys(arr))
来源：http://dali.gotoacloud.top/Article/details/gtwpyrxslu.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gtlohinssv.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtfxvzndnh.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtxyjapztz.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gtekskacsa.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtbaeewzin.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtspirrllg.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtexuxlunx.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtahuoenqs.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtpaudcikg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gtldeuxgfz.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtmjmuxigf.html

(x * 2 for x in arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkzxswhmj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtykatscvl.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtcrbqmpdp.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gttcobscbw.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtkfybrulw.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gtlurriqfg.html

defaultdict(list)
来源：http://dali.daxiang520.top/Article/details/gtkzfsncdk.html

[U15] Py：高精度计时
来源：http://dali.tianlin.xyz/Article/details/gtelvrkxoy.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtzgtiwyrn.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtpuqvbpws.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gtuwnvkxoz.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtnoreopxs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gaohongyu789.top/Article/details/gtkqjqgzsg.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gtohltkuss.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtxwontlcq.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtgjegfnxs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xziqi.cn/Article/details/gtsazjgbtw.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gtejswtjfp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hysaishi.cn/Article/details/gtuhbqqsea.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtmxegaskg.html

@contextlib.contextmanager
来源：http://dali.quarkkingdee.top/Article/details/gtxdepndxp.html

[U22] Py：矩阵转置
来源：http://dali.cdnleiting.top/Article/details/gtqrvkppqb.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gtmnbjltlo.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gtdsbcngyi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxinkj.top/Article/details/gtzxgosaob.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtduvuwhcl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtbvxszhpt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtxbgjymsc.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtppipxqjl.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gtcdqvjlpn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gthdjmtqgz.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtavqjfkox.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xinyue.icu/Article/details/gtwbjgiuke.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gtmyaprawp.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gtohwxxmfv.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gtrxsouqfh.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gtgugispwu.html

[U30] Py：数据类
来源：http://dali.yj20258888.top/Article/details/gtdmucwwmk.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gttzxcbvrt.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gttqzelzef.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtjyaxyuba.html

[U32] Py：代码格式化
来源：http://dali.yj20258888.top/Article/details/gtmzfylkqs.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtjhpeexeh.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtqbcqolpw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sysykeji.top/Article/details/gtwhgjikxf.html

[U34] Py：判断编码
来源：http://dali.xuetiantiany.cn/Article/details/gtfqinztmx.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gtaphauftp.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtobfyvocs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gtcfoyrsbp.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtqfqxialo.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtprobtwbo.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtklucoaic.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gttbujxmzc.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtqwegmnyn.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gtitiontbf.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtmtyabgxo.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gtydnsnnpt.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gtphmpkdjg.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtuttqqveu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gtqlgfabbu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gaohongyu789.top/Article/details/gtvtuhdqcw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtcvkdmzfj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gtawvbwupu.html

[U43] PHP：声明命名空间
来源：http://dali.gogol.net.cn/Article/details/gthmkfrfkc.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gtuvsgtcff.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gtysqlsnrg.html

declare(strict_types=1);
来源：http://dali.birdmap.top/Article/details/gtrjwmvdwe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gzhubu.top/Article/details/gtbgaijiby.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtuhwseczs.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gtnedtgvht.html

?string $name = null
来源：http://dali.zycfv.cn/Article/details/gtacjquwrk.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gtizavbqxd.html

int|string $id
来源：http://dali.bjfxy.top/Article/details/gtaaoeeesy.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gtgolefcvl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gtnyetvond.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtljwxkklu.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtjtripelo.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtdlyorpcx.html

public function __construct(private int $id) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlduuqszj.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gttinioiey.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtrbvcrfbn.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gteyojsouj.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gtnzaresbq.html


<!-- 参考信息 -->