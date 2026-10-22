代发 wailian999

static int counter = 0;
来源：http://dali.smart0.xyz/Article/details/gtajzdobpk.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmfchipog.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtrpwmoouw.html

[S30] C：头文件保护
来源：http://dali.shzxlz.cn/Article/details/gtuqaragty.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtgcwpuiil.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtnyrapmon.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmoxmppf.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtzdvihajs.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtwbpwamys.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gtlmhkdrqz.html

[S32] C++：字符串
来源：http://dali.redwolf501.top/Article/details/gtlvvpliki.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtwzmpafth.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gtqnelvkhn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtthjvmofj.html

[S34] C++：遍历 vector
来源：http://dali.redwolf501.top/Article/details/gtnhfpiyjx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtvepfmtyg.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtkdhjlggx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gturvlawee.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtqhnbmefq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtrjfukiwe.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gtpldvqplw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtadpwhsjf.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtpvczqqsa.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gtolfoorhm.html

[S39] C++：自定义比较器排序
来源：http://dali.cheryme.top/Article/details/gtwmamztpq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtnlgjddzh.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtcpipvhks.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtfqusqcct.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtziokmoqs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tianlin.xyz/Article/details/gtnbexezoz.html

[S42] C++：继承与虚函数
来源：http://dali.wangshuangyany.cn/Article/details/gtenkelerx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtmbpfzgqv.html

[S43] C++：智能指针
来源：http://dali.bjfxy.top/Article/details/gtpimxzxut.html

auto p = std::make_unique<int>(5);
来源：http://dali.yangfankeji.com/Article/details/gtlcsoqgtd.html

[S44] C++：引用传参
来源：http://dali.guowangkeji.top/Article/details/gtsudhaipw.html

void inc(int &x) { ++x; }
来源：http://dali.xziqi.cn/Article/details/gttkzghhkm.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcuvakyz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtcsmvwhkx.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gtwcirivaq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gttsaeqgoe.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtfrsbctcj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtpinqruyn.html

[S48] C++：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtjjrxmpuy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gtrtnhgwdj.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabhkncwt.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtfekrayhj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtccsrvqpa.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtkjawjubc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gteifovpte.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gthevfzhvg.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gtqlsiewri.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtqnjijmxi.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtupbrhiau.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gthuyqepuu.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtricycogh.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtuuzduyfm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gtkcqiqlog.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnockscp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtfgdoysam.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtaeoqwcgx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtyaezyiut.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtqglsexbx.html

constexpr int N = 10;
来源：http://dali.zhixingplan.top/Article/details/gtcijezbnw.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtnqeostcp.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gttetdcmhi.html

[S59] C++：静态断言
来源：http://dali.pycfn.com/Article/details/gtmzhdoxfw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gtfxiorcmw.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtczymogve.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gthwmhxnmf.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtzpmvbhrf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtxhmhyuns.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gttvvkccsm.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtaghzfefs.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gttjymyfmy.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtlpgxlgqp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenlongwang.top/Article/details/gtsdjuxebk.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtrkbrrika.html

"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuppdclzb.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtvtbfdxoe.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtidmyrzol.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtasoznisj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtteyfcdgt.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtdubkxmut.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtydsvsyjc.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtzyczwxwu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gtrglxxxfo.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtoynmziuq.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtpskaxhia.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gtjylduiab.html

fun String.exclaim() = this + "!"
来源：http://dali.ybcxt.top/Article/details/gtemmxmlmv.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtnavfnhew.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtkgrwahbe.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtmphfvzah.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtelmcjlpc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtlhqjboyv.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxuxvxexe.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtkzaqpwgs.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gtgdnzrujn.html

[T14] Kotlin：循环
来源：http://dali.dianchejie.cn/Article/details/gtrfjtltpl.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gthbmgjprz.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtitsbvalq.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtayryxfni.html

[T16] Swift：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtpdromlhp.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtxcyinqyr.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtdunzxlod.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtxnydywph.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtamzvyqcw.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gtlztxyyoj.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gtctgotcsx.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtxbkeiqzx.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gttqxwsfkb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtapymrgha.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtzqahmrsb.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gtsfqbigfg.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtzdixfzvv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtfellebde.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtelbawxbn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hywenlv.cn/Article/details/gtjlbsmdxf.html

[T24] Swift：闭包
来源：http://dali.chenlongwang.top/Article/details/gtfzpqptre.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthnttscsf.html

[T25] Swift：结构体
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteriwlfh.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtcexnpeae.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtbukszjog.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtgcwawaak.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpygtxdh.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtlazbdzpp.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtxaiuwpox.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtdyzxmhri.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtspnxapmb.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtzdgxedax.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtjpzqtlyb.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gtezokovkk.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtivomqspl.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtkrwgclrf.html

[T32] Lua：局部变量
来源：http://dali.yj20258888.top/Article/details/gtmagwxbwg.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtstpsiwoy.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtrvwlwlru.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gtklzkrmfu.html

[T34] Lua：遍历表
来源：http://dali.yueranfly.top/Article/details/gtopnraumm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtngkbzuuj.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtvxgaifkn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtvqjxvtqd.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtkxeoyniz.html

function add(a, b) return a + b end
来源：http://dali.gotoacloud.top/Article/details/gtvazqbeka.html

[T37] Lua：字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtdvgaxmka.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gtjnfwhrby.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtoikuytoc.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtlseygzbx.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtqopayxzy.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtzivsrkny.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gtrcfeqxbl.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gthtvfxjnu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtdxoduuym.html

print "Hello\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtgkhjeznt.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpjzvvoqn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtleleumht.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtdsecnqln.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtvsdgkvhu.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtxptwjnpn.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtrkzcvuvx.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtiqzktihh.html

for my $x (@arr) { print $x; }
来源：http://dali.zdqjudy.top/Article/details/gtnkxekyft.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gtnbwbpdkx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangshuangyany.cn/Article/details/gthxpopabl.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtgjfbhrmb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gticybjyku.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gtwxvfxxib.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnhdklyx.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtfxwauyzc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtmxkqqenx.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtrrthlbww.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtddoyqfdn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtyrzyjoen.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtnedxsmak.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtinyzuwwl.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtxjcjwzgi.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtkpirqdwk.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtsaawyylo.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnjrqykg.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gtoigiebak.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtkbdcjvep.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtlirwjmcj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnelvxyy.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtusopzduk.html

case class User(name: String, age: Int)
来源：http://dali.ehwqpu.com/Article/details/gtwyluinno.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtfctpsadj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtjclojhen.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtresypvad.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtvvhbdmzb.html

[T59] Scala：循环
来源：http://dali.birdmap.top/Article/details/gtglmmhkqu.html

for (i <- 1 to 10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gtklyefbha.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtkkcrqchh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtojhjzsfh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtabbbtybj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtbodwynhu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjnywuius.html

[U01] Py：创建虚拟环境
来源：http://dali.9152youxi.cn/Article/details/gtubquyznv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.c1oappe.top/Article/details/gttxhtnkdu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangdashe.top/Article/details/gthztcnrgk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtvzjencvd.html

[U03] Py：加载 .env 配置
来源：http://dali.sufxvd.cn/Article/details/gtfokcmpky.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtfdfvsvkt.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gtuwunoarn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtmivrhvfs.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gtijashftr.html

list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtkhnzrlqm.html

[U06] Py：合并两个字典
来源：http://dali.zhiwuduotai.top/Article/details/gtedgfjpdn.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gteedwxvud.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gtgibfxtdd.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gtxiretisp.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gttncjdslv.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtqkjygjdh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhongyouzk.top/Article/details/gtdjzkvgpq.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtorrmbimj.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrospdex.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gtldtrpbil.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtlriksspj.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gtudzzqdlp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtxrgiozbd.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpvzmibx.html

[U13] Py：固定长度队列
来源：http://dali.ehwqpu.com/Article/details/gtztbhcrdt.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gtnfooalmf.html

[U14] Py：分组收集到列表
来源：http://dali.hnqzz.top/Article/details/gtarrwppmd.html

defaultdict(list)
来源：http://dali.zycfv.cn/Article/details/gtabucuyik.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtitmqrzhg.html

t = time.perf_counter()
来源：http://dali.tanke756.top/Article/details/gtlkksrpdi.html

[U16] Py：命令行参数解析
来源：http://dali.meibo888.top/Article/details/gtkugbotfr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gtudxbwgdp.html

[U17] Py：初始化日志
来源：http://dali.zhoulong.xyz/Article/details/gtupysakce.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gteoakwlgd.html

[U18] Py：预编译正则
来源：http://dali.yuanzhike.top/Article/details/gtwdxzijcl.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtqlslxnwz.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqwkgcpcr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gtgxwjzism.html

[U20] Py：缓存函数结果
来源：http://dali.yonumen.top/Article/details/gthjtqajon.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtrkcyegee.html

[U21] Py：自定义上下文管理器
来源：http://dali.hfpthk.cn/Article/details/gtwwvtrpnv.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtziylaenb.html

[U22] Py：矩阵转置
来源：http://dali.zhoulong.xyz/Article/details/gtvqxemsmo.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gtyeylkaeb.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtzcjbtsmb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtsypkvquv.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gtqkpckjej.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtydxcyfrq.html

[U25] Py：CSV 按字典读
来源：http://dali.hfpthk.cn/Article/details/gtndowiccm.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtycfuufyc.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gtwptcrgal.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtvyywldvl.html

[U27] Py：异步 HTTP
来源：http://dali.c1oappe.top/Article/details/gtziotropp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxgbbmox.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gtjbtbkzwn.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtdwoqwydw.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtxqvofwml.html

@property 与 @x.setter 配合
来源：http://dali.havefunace.top/Article/details/gtbxgrvsok.html

[U30] Py：数据类
来源：http://dali.guowangkeji.top/Article/details/gtufopwrjg.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gthihyrmfd.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gteezoxdcx.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtgzvvuadm.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcfwolpw.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtibdbgbfv.html

[U33] Py：打包发布
来源：http://dali.jyoumei.cn/Article/details/gtzaggroox.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxmlcxwi.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtqatqbrok.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gtzcjjfbdg.html

[U35] Py：发送邮件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudtirfxa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daria6918.cn/Article/details/gtixfmhfcx.html

[U36] Py：定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtgdhrqmwl.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gtywrlohdj.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gtdmnelaea.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagllyrbw.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtutrzklvf.html

Path(__file__).resolve().parent
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrrhxxfu.html

[U39] Py：判断是否在交互环境
来源：http://dali.hongshengwenyu.top/Article/details/gtbqolyfrm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtmmtfkzyz.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gthekbmjta.html

print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtshhiruzn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ehwqpu.com/Article/details/gtqmumawai.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtdwrwjpsi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gtvcbrflga.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtrylswxqz.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtgvczvjdr.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gtlfozgglp.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gtrwybmxmn.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gttowdzryd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszlplshv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtmcdpveiw.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gtdjtjgmuz.html

?string $name = null
来源：http://dali.chenzaomai.com/Article/details/gtutdyhcab.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gtgosrdfzs.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gtifjccfod.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gtdzyjcaff.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gtvgfzexyg.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gtnsvjzuxx.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtelnuubbi.html

[U50] PHP：构造器属性提升
来源：http://dali.hongshengwenyu.top/Article/details/gtntkacppr.html

public function __construct(private int $id) {}
来源：http://dali.sysykeji.top/Article/details/gtdfuoabii.html

[U51] PHP：数组解构
来源：http://dali.gotoacloud.top/Article/details/gtrsupaybb.html

[$a, $b] = $arr;
来源：http://dali.jinqigfzy.top/Article/details/gtlljwdbxe.html

[U52] PHP：箭头函数
来源：http://dali.fengsongda.top/Article/details/gtyhegcpvb.html

$double = fn($x) => $x * 2;
来源：http://dali.zdqjudy.top/Article/details/gtlqdgzawp.html


<!-- 参考信息 -->