代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.sxryk.cn/Article/details/gtfolijkoz.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtfahrvvzs.html

const double PI = 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtmettdrup.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtewnpftxa.html

static int counter = 0;
来源：http://dali.zdqjudy.top/Article/details/gtclqxkrvi.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gtqfmqskuz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtzyvlxtrg.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtrgxrkdoc.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtzrskbetb.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtexwlaiwe.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtwxewqadt.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtqgvhcity.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtzhvxbxie.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtgupkbuef.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtldnavuiq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjynjoclz.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtxwurmcse.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtpcysomgc.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtbqfdqnyw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtwbelzjrx.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtplheejod.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.redwolf501.top/Article/details/gtmlbfyktc.html

[S36] C++：unordered_map
来源：http://dali.pengpengdd.cyou/Article/details/gtelyqjkfc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtkmaqzpbf.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtadpfpmwk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gtyhawsina.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtebcrkolp.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtvbchljwz.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtctxrprxp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtthwcwvzi.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtnbersras.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtdotpmysa.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtsytydupv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtfewbkpgc.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqgugkij.html

class B : public Base { public: void f() override {} };
来源：http://dali.ehwqpu.com/Article/details/gtgpxxvqhr.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtyraewmfg.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangdashe.top/Article/details/gtbxzpcisk.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtgwwstxqe.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gthhemcdmm.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtimgodysm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgfzy.top/Article/details/gtmxvtrzaq.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtljjajkxo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeeshuqb.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtxnrpgnpt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtyhswxjsj.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtgclmoboc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yanxiufei.cn/Article/details/gttvilpjiu.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gteoqsfazy.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtdinejwox.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtmdfiobjl.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gtrckekizx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtqnxdiffn.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtjtaddawr.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gthzugemlz.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gttnfoxqkw.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtvopbjyef.html

[S53] C++：移动语义
来源：http://dali.xinyue.icu/Article/details/gtnjfloqrk.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtvqwltoid.html

[S54] C++：异常处理
来源：http://dali.feifeiyinyue.top/Article/details/gtnibbkpmf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtvjexxrzj.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtwlrctvhs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.haohaochexian.top/Article/details/gtoobswbly.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtupptiftt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtfhsnjklp.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtalffaroi.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtxuitnxvq.html

[S58] C++：命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtlciwdgai.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtkwoljlda.html

[S59] C++：静态断言
来源：http://dali.yj20258888.top/Article/details/gtncovxxfb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gtqbispwyx.html

[S60] C++：遍历并删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtchgcllcd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtjrplukci.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gttqmtnzzz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtgbthqwux.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtidbgfqlw.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtuqntalpk.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtmzjrcdjr.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gteobwghmt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuanzhike.top/Article/details/gthcsvnixl.html

[T03] Kotlin：字符串模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoqeguhj.html

"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtmicvcjrn.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtuusckilp.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtsaotwjmo.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtovcfdfxb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gtqchpypxq.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtvbcisxxl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtxcwkmgmm.html

[T07] Kotlin：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtcxzxnfzq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtrhlxcjcr.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtcbwjmnfn.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtchzvpdfr.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtbqualdpz.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtitwjxdje.html

[T10] Kotlin：默认参数
来源：http://dali.guannengcc.top/Article/details/gtawcsovyo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtvrdbnsus.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gtphnuhwih.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtshjfmrax.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gtmalawgls.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtpyzfbyht.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtierptbbq.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtyfvdewpo.html

[T14] Kotlin：循环
来源：http://dali.hywenlv.cn/Article/details/gtizduiqlj.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtmzvrrqaz.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtpqahbtlq.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtbsyicjxs.html

[T16] Swift：Hello World
来源：http://dali.ybcxt.top/Article/details/gthwpdlhmf.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtgldxzfzl.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtiluplunp.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtjgfowpsx.html

[T18] Swift：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtbbqpckfj.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtfymvride.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gtrcucsjde.html

if let n = opt { print(n) }
来源：http://dali.9152youxi.cn/Article/details/gtsnpqignu.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtizdoaudh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gtakaghdhw.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtmzmhgulm.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gtcrzzhknz.html

[T22] Swift：字典
来源：http://dali.hongshengwenyu.top/Article/details/gtpoqplhui.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomqdvvfj.html

[T23] Swift：函数
来源：http://dali.zdqjudy.top/Article/details/gtmxuyrfxj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuanzhike.top/Article/details/gtcfelvqth.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtqhkgvjyn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtxrqtzeyl.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gtsaovcmhw.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gthaiwcoqe.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtelhbwqfk.html

class A: Base { override func f() {} }
来源：http://dali.tianlin.xyz/Article/details/gtxzsqboay.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtstuxwfvo.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gthqexesoh.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtucajorfn.html

enum Color { case red, green }
来源：http://dali.sxryk.cn/Article/details/gtkdbxukyf.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtlxtustfw.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtfluvfybg.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtbziermjf.html

protocol Shape { func area() -> Double }
来源：http://dali.ppjwa.cn/Article/details/gtjgakzbnx.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwlvryef.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtospekcuf.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtigtdpati.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gtlbegpcce.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gtqxdchmvy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtetfxtnik.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gtbbxzlril.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtiqipcyed.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtjvqlahwf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtqjwiqvsz.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtekvdoeoj.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gttxavesok.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtkckxvwik.html

"a" .. "b"
来源：http://dali.nanxuanxn.top/Article/details/gtjqblaouq.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gtdvdkgunc.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gtqtkevhmc.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtgjzdmwlj.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtmxwgcsnc.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gthovywujf.html

setmetatable({}, { __index = base })
来源：http://dali.yuxming.cn/Article/details/gtxfqtetne.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtyujxtmus.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gtdwwokyzy.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtrivlivxw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmfaafyp.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtyztqugyr.html

"值: $a"
来源：http://dali.zycfv.cn/Article/details/gtcfyuxbwu.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gtomchpxwx.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtofqpuqhr.html

[T45] Perl：数组遍历
来源：http://dali.zdqjudy.top/Article/details/gtnctzlvie.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtimmveqtd.html

[T46] Perl：哈希操作
来源：http://dali.shzxlz.cn/Article/details/gtudpdmcxc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtjwtbxfsc.html

[T47] Perl：正则捕获
来源：http://dali.hfpthk.cn/Article/details/gthimthgxc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gtdejikink.html

[T48] Perl：正则替换
来源：http://dali.fzhhl.top/Article/details/gtgpbqlhyd.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtyfdxwpwb.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtaovmsbpx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtmctxnpwi.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtmccfxzre.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gtptsiifcj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtjijexabf.html

[T51] Scala：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtvdzbaxst.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtbghhrcjg.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtdfcaaqdd.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gtxgxfxqnt.html

[T53] Scala：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtjzmnrwws.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gtksemkyrd.html

[T54] Scala：集合映射
来源：http://dali.zhiwuduotai.top/Article/details/gtdpgontbg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtqlfqmnrn.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtqxyvhbei.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtmetyehgy.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtfmhzeubw.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtbmiamfii.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtebzkqxbo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.haohaochexian.top/Article/details/gtzouhonwh.html

[T58] Scala：函数定义
来源：http://dali.jyoumei.cn/Article/details/gtvimyznfp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtldjijngf.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtxeikpgcv.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtctjtwymh.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gtvkeaydym.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtshcfiihg.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtgalmaczu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gteqnjomaa.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtjglwktxv.html

[U01] Py：创建虚拟环境
来源：http://dali.zhongyouzk.top/Article/details/gthiecurvb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtmwqdphlw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gthenhepxd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gtxrjoaaxz.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtsohonymi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gtfiqvungu.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtxioaclrt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gtjqwyatnk.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtkastqxch.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtoggurgqn.html

[U06] Py：合并两个字典
来源：http://dali.gogol.net.cn/Article/details/gtokfbchlo.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtstympcwa.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtrvwbpyqg.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtvqmokmhq.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhtvegki.html

[y for x in nested for y in x]
来源：http://dali.jianghu66.top/Article/details/gtbmoncdgr.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gteisstwyj.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtzxxcjgko.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtwimypdvk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtdvqkxdaf.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gtxhrdzewi.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtmgxghtrw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gtnjgzktjk.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtuqgyjxmo.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtaallfxrn.html

deque(maxlen=10)
来源：http://dali.zhoulong.xyz/Article/details/gtpcuiqvfd.html

[U14] Py：分组收集到列表
来源：http://dali.yvedp.cn/Article/details/gttmhvowoy.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtgnvmrpbn.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gttlzkcrbw.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gtrjkfppvr.html

[U16] Py：命令行参数解析
来源：http://dali.chenzaomai.com/Article/details/gtoydgoltw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nanxinkj.top/Article/details/gtouyrntjj.html

[U17] Py：初始化日志
来源：http://dali.aibaodan.cn/Article/details/gtcynyffom.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtgvbhjhzw.html

[U18] Py：预编译正则
来源：http://dali.yuxming.cn/Article/details/gtkjrqioej.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtoormxhnb.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtprfxqffk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtotmxbgxf.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtyesewgep.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhixingplan.top/Article/details/gteppusuat.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gtmwkwyfkp.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtbhjtpfjh.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gttxrslvem.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gtbynvbysj.html

[U23] Py：分块读取大文件
来源：http://dali.shuidangran.top/Article/details/gtraydamzu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.9152youxi.cn/Article/details/gtoqpxgosr.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gtsghjmpdw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtnnowmqqz.html

[U25] Py：CSV 按字典读
来源：http://dali.smart0.xyz/Article/details/gtjuhjrseh.html

csv.DictReader(f)
来源：http://dali.andypj.xyz/Article/details/gtewhrlfms.html

[U26] Py：并发下载
来源：http://dali.feifeiyinyue.top/Article/details/gtdhazzuui.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtianrihdl.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqbwkrdg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtuelpwyzq.html

[U28] Py：类型别名
来源：http://dali.birdmap.top/Article/details/gtdixunuod.html

UserId = int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgdkuwwbp.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtjqdudzpk.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gtoyjllyfj.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtbjwnvauz.html

@dataclass(slots=True)
来源：http://dali.sysykeji.top/Article/details/gtqriygzmb.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gtzalylkjc.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtfbvxycrp.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtzcfwdxfh.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gtbbziizpo.html

[U33] Py：打包发布
来源：http://dali.dianchejie.cn/Article/details/gtveteszmp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gtyfqubkmk.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtskjrzrfy.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gtnauaiswf.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtolfmouzf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gtfpsupnti.html

[U36] Py：定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtmvwibprf.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gterihdyks.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtfrgyxapb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gtacgugxwh.html

[U38] Py：获取脚本所在目录
来源：http://dali.pycfn.com/Article/details/gtequvxnkt.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gtbnkbdffn.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gtuasahnkp.html

sys.stdout.isatty()
来源：http://dali.zhiwuduotai.top/Article/details/gtcnaezphc.html

[U40] Py：打印到标准错误
来源：http://dali.gotoacloud.top/Article/details/gtrwxtlspb.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtvnrukmot.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzbyxpzoj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gthgagmknp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.9152youxi.cn/Article/details/gtftntfugl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pycfn.com/Article/details/gtaodbpgyd.html

[U43] PHP：声明命名空间
来源：http://dali.andypj.xyz/Article/details/gtzvbxoubr.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtjqfffkfu.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gtshhtlaos.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gticnxhxfn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gtkftqwcgw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrfonptnr.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gtzhxixfak.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gtiqcjitfm.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gtjfmxsxiz.html

int|string $id
来源：http://dali.yj20258888.top/Article/details/gtslwpzvfl.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtkvfcpffu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dianchejie.cn/Article/details/gttjwhjbuo.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtrkxlpqbj.html

public readonly string $name
来源：http://dali.guowangkeji.top/Article/details/gtfymbeqno.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgfzy.top/Article/details/gtgsbkgfak.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gteabkvzgq.html


<!-- 参考信息 -->