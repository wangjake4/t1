代发 wailian999

static int counter = 0;
来源：http://dali.hongshengwenyu.top/Article/details/gtavubjymw.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtvosduhsu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtqxqowqgc.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gtzbynkqsk.html

#ifndef X_H
来源：http://dali.jinqigufen.top/Article/details/gtmcpgqfvk.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtkjtuxpue.html

#endif
来源：http://dali.smart0.xyz/Article/details/gttaopijoo.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtrxcebvpv.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtrsbsygmo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbumamcle.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhakbkxw.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnmnhtkw.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtotffwdyr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhongyouzk.top/Article/details/gttwygkycv.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtjnsmtafj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gtibqtrjzx.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gtsfjleuov.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gthtvxhclp.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtnutjryvr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtmkkbbrdk.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gtmwoldbbk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtyvtegnxp.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gttkxntxpr.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtyrbxpwqt.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtbvrbrohr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xziqi.cn/Article/details/gtlmhmjahe.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gtidcisvzo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jyoumei.cn/Article/details/gtlxbdbtrm.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtjjjvrbjj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ehwqpu.com/Article/details/gtzrtzcbfe.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gtnhtowjgq.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtcfvtrgpz.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gteaaogawq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhixingplan.top/Article/details/gtfldyehyk.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtvoluebxa.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gtnkpxqwlx.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtabubsolm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cqqwz.cn/Article/details/gthlnwkvkf.html

[S46] C++：函数模板
来源：http://dali.yuanzhike.top/Article/details/gtloudnudm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gtjxjcgwrp.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gttaiaoben.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtgvqadyqw.html

[S48] C++：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtejzpdatu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtxyqmmrxc.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtoefamdwi.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtoqipdhdh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtpzqonedm.html

[S50] C++：格式化数字
来源：http://dali.yanxiufei.cn/Article/details/gtqfdktuzg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtfhbmxhec.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtukdzpglj.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gtlhycnleh.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gtydvquwtg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtrsdrufbk.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtdogdjrvm.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtbgidxkoz.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtifdykffp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtkuszqtys.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtnebgihmi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtcsdbvzzs.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtinrtkqqd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gtuoqmapgd.html

[S57] C++：编译期常量
来源：http://dali.cashguo.top/Article/details/gtauzogqht.html

constexpr int N = 10;
来源：http://dali.ivvv.top/Article/details/gtybnvtuck.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtzwiwciej.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtyladkyvb.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtokepecqn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtuevknlvc.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtxyltxlng.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtaykqghdh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcekzrqhe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtgkgzakyq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtedywycru.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtbboutvut.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtobtspcuj.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtccnggmja.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gttwmczeel.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtzddvbgwq.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gthcxgeybh.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtacfuyhzx.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtybdhyjck.html

[T05] Kotlin：when 表达式
来源：http://dali.9152youxi.cn/Article/details/gtcgmevqoy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewpjosam.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtugzscayt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtpjocwoua.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtxoerrjpy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtekembqhf.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtualdobjt.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtezozdvqo.html

[T09] Kotlin：扩展函数
来源：http://dali.cucudq.cn/Article/details/gtgadjacjl.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtojalzocz.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtxedpgoky.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtiqaskdmv.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtnxzjmnan.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtswegzrsa.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtojhuquzp.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtptjeskui.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtygbxlbvu.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gthjbdysgn.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtsznxkseu.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtjuphoufb.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtadiyridk.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtzmlbsljp.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtzbhyuubu.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtyhhgsimt.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtgtwdnpep.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtqfyopeul.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtgbakdosb.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gtkbpzorub.html

[T19] Swift：可选绑定
来源：http://dali.nwbrower.top/Article/details/gttsmnofkv.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtbusttpzg.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtqdrgzjcz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqucizbc.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtcfubpxkp.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gttjiewadg.html

[T22] Swift：字典
来源：http://dali.yuanzhike.top/Article/details/gtcmklmedv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtnldhnujh.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtymbyvtdr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtfzctlyot.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdydamzl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtswqqhowr.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtnkpancwk.html

struct P { var x: Int }
来源：http://dali.sysykeji.top/Article/details/gtpampadrd.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gtsxonmect.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtxdomfgcw.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtddmgnluc.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtlfmseoka.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtjubryrjf.html

enum Color { case red, green }
来源：http://dali.feifeiyinyue.top/Article/details/gtwxwtdkzb.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxquvetre.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtderijhrf.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtmkuqqcsx.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtdykfgteh.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gtunkcmsgr.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtzszytfhh.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtdplbaxft.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtnfnbvdln.html

[T33] Lua：表（数组）
来源：http://dali.havefunace.top/Article/details/gtqellacbm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtrtzohbjh.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtbhttxojh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtkuneqbfv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gtvpqngyiv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gttiwkigav.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gtpfmacrtv.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtlrjabyio.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gthremglzw.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtzxmdltme.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gtnaccoyqz.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gttfqcabta.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gtnmjmcyne.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtrlytjozx.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtjrkgaaas.html

setmetatable({}, { __index = base })
来源：http://dali.jqgufenzy.top/Article/details/gtbbpyzruy.html

[T41] Perl：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtgbyzkrkp.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtmyednlgf.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtqzgumcod.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtivhizxjm.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gtanembgvz.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtqrjhbyxv.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtdntewpmc.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtkqhsnoap.html

[T45] Perl：数组遍历
来源：http://dali.zhixingplan.top/Article/details/gtazqjxnaa.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gtjgoanebq.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtuqzawydd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gtiqfvvgpn.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtjwkeqmve.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtmwalamet.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtcwtlujmt.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gttuwhdkes.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtenvigjgl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtqyuarswa.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtvrvpyfun.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtwhhejzbh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtpnnzayyu.html

[T51] Scala：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtstqobtux.html

println("Hello")
来源：http://dali.yonumen.top/Article/details/gtgjmjkpiz.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gtvzpcimat.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwidogchv.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gttteezvba.html

s"值: $b"
来源：http://dali.jianghu66.top/Article/details/gtmbvisjfe.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtpmdqzuri.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtmbrocvuf.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtaklznemi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtjsuzsalm.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtrqnsfzdf.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtzyfvbxsr.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtobqvxfws.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gteffnvjzp.html

[T58] Scala：函数定义
来源：http://dali.9152youxi.cn/Article/details/gtwjdaekdp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtwuogssvw.html

[T59] Scala：循环
来源：http://dali.cashguo.top/Article/details/gtqvtsypqx.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtxskjnsui.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtoulxvdmw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gtylmziahg.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtcbifnznc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtumcauzid.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfhnnypwq.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtudyqegrg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gtxakusodz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.9152youxi.cn/Article/details/gtqnppfvvs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtqlboowzu.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtdacmyfwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtjjqaubir.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtquavsbpb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtyovnyhlj.html

[U05] Py：列表去重且保序
来源：http://dali.dashuyun.cn/Article/details/gtmeqzprdf.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtgncownwc.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtamhjvkzy.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gtqdzxmziu.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugckwkdr.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtlfxyusox.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gtinkjpnev.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gtkmfluibq.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtyjbpwhbv.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtaykfqjkd.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtpusckper.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtlrkbovuv.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtcpqucoty.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gtrzhtmgap.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.bjfxy.top/Article/details/gtayfujwtl.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gthjwenbfe.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtzueantlo.html

deque(maxlen=10)
来源：http://dali.daria6918.cn/Article/details/gtyhpzptsy.html

[U14] Py：分组收集到列表
来源：http://dali.pycfn.com/Article/details/gtgryrpmvh.html

defaultdict(list)
来源：http://dali.guannengcc.top/Article/details/gtvbgnuprl.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gtjsgmxyki.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtchkosgpw.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtdkfpkvzt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gtdpeeemmp.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtypahmjtb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cdnleiting.top/Article/details/gtofxxanqn.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gthuiwtnhg.html

pat = re.compile(r"\d+")
来源：http://dali.xziqi.cn/Article/details/gttnlpswzh.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gtagnenvcu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gtxtakhxga.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gtvdosbhol.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gtkzzhbjps.html

[U21] Py：自定义上下文管理器
来源：http://dali.yvedp.cn/Article/details/gtwaalqzcn.html

@contextlib.contextmanager
来源：http://dali.tianlin.xyz/Article/details/gtjbdkhanm.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gtcbhbnkef.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtghhjybuo.html

[U23] Py：分块读取大文件
来源：http://dali.9152youxi.cn/Article/details/gtfndhswur.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cheryme.top/Article/details/gtnpatuomv.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtyikkdzuw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtcyshdokx.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gtecyufrvv.html

csv.DictReader(f)
来源：http://dali.ivvv.top/Article/details/gtlmeopvch.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtuthteltd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gtxlppzril.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtjqrkyqsr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gtzatojiif.html

[U28] Py：类型别名
来源：http://dali.zycfv.cn/Article/details/gtqktvwoxq.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtvilponji.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtchcbqoft.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtnbpqpvop.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtveutgkgt.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gtywnbgohb.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtqrumhzic.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtbneprdlq.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gtcxzzfpux.html

ruff format . && ruff check --fix .
来源：http://dali.xziqi.cn/Article/details/gthhotnrgc.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gtepoodqwt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pycfn.com/Article/details/gtcfvstuve.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtlfufdwmr.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gtxcfepwtu.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gtokesbccr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gtgbatmwvw.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtmatzkkxs.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gtluzelzyu.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gtdioqavya.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gzhubu.top/Article/details/gtwjzetpzs.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gttauqpich.html

Path(__file__).resolve().parent
来源：http://dali.xuanzx.com/Article/details/gtbyzfpvmp.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gtdvdgbpbu.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtyiraqvfo.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gttfmtxxdw.html

print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtfvnwfmym.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhixingplan.top/Article/details/gtyhjulcub.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.mhx1999.top/Article/details/gtnajruxvd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtytoqjcly.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtzgwhlvgz.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtxocypjfu.html

namespace App\Http;
来源：http://dali.jiagoushi.top/Article/details/gtihdnkche.html

[U44] PHP：开启严格类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtduiekk.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gtjknrmfls.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gtmxrngppd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtcervtyin.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtcctzleoc.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gtdryysxmk.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtxgictbzy.html

int|string $id
来源：http://dali.havefunace.top/Article/details/gtppxntyye.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtxtftxlyz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.quarkkingdee.top/Article/details/gtaxgdlsrs.html

[U49] PHP：只读属性
来源：http://dali.xylfe.cn/Article/details/gtjuoowbhw.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gtxmsjfjuy.html

[U50] PHP：构造器属性提升
来源：http://dali.svipenyu.cn/Article/details/gtjemkiplt.html

public function __construct(private int $id) {}
来源：http://dali.xuanzx.com/Article/details/gtmwebcpra.html

[U51] PHP：数组解构
来源：http://dali.cdnleiting.top/Article/details/gtpexjqbmb.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtimkjrugh.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtreltndna.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtmuloyopy.html


<!-- 参考信息 -->