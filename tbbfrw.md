代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtgazvlmfw.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtklmvivfz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtnjlicbpk.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtdkswljqs.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yanxiufei.cn/Article/details/gttqeewyoz.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtmqoxsvcy.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtlcfsftjo.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtczojugkw.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtqpocrwhy.html

[S27] C：定义常量
来源：http://dali.jqgfzy.top/Article/details/gtiwjbnltv.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtyfqvspgq.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzohgxzsc.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gtvvhfqvdp.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbcsjcqyc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtzhyagksc.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gtbkkekyzb.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtmtbojcob.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtlmtikpuu.html

#endif
来源：http://dali.yuanzhike.top/Article/details/gtrgmfjmxb.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gttnjvjqxs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gteuxvdhct.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtflhfufjm.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtdemwygsg.html

std::string s = "hi";  s += "!";
来源：http://dali.hywenlv.cn/Article/details/gtymdsjsdw.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gthsymytxo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtoxxvfmzh.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtmmmvdufg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqedrvvze.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtinkfysgu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtlpolqomc.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gtzuanfxks.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtlrttzlch.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtsqxdfhej.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtulzbmffx.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtdrkmnqju.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtrmilwgge.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gtbupbyvmb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtmolnqmku.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtkolczxjs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtelvjucmd.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gtlhvvzgnu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtiqfkqlca.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtodejusyj.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtfgpmpipl.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtplgkmjyg.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtrwihehoa.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gthtlhmijq.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtsewelyll.html

[S45] C++：lambda
来源：http://dali.haohaochexian.top/Article/details/gtqlukqxxy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yuanzhike.top/Article/details/gtzdkmhvef.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtebxauilx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gttublqyuo.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtnpujweaz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtoiudlgcc.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtrqwbmmsk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gttfctmecf.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtvybsunqi.html

[S49] C++：写文件
来源：http://dali.tianlin.xyz/Article/details/gtnjkihtok.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtfxyqzprm.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtrtwckkto.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtsooerfzr.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gtswvndlvi.html

static_cast<double>(a) / b
来源：http://dali.ivvv.top/Article/details/gtbxbinmuu.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtbeblfkhb.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtdhclkjux.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtzbiflixa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtxcsiiysc.html

[S54] C++：异常处理
来源：http://dali.chenzaomai.com/Article/details/gtnlrpzccr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gtqtzkwkys.html

[S55] C++：结构化绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtknmbknmm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gogol.net.cn/Article/details/gtkzetorys.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gtotmmvrlp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzzdmhqb.html

[S57] C++：编译期常量
来源：http://dali.cheryme.top/Article/details/gtwxgfgcoe.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdubximdr.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtzdzpanjq.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtjwjzxekz.html

[S59] C++：静态断言
来源：http://dali.xuanzx.com/Article/details/gtgtavwnrt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.quarkkingdee.top/Article/details/gtetmqcydq.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdogbjyxa.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gttekbsjht.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfmjupqwe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvhlfvui.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtzypjowrj.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtudhfitxp.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtgmbcybrs.html

[T02] Kotlin：变量
来源：http://dali.haohaochexian.top/Article/details/gtzmszsbmu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtealeoupx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhiwuduotai.top/Article/details/gtzlbvukfm.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtcsyxsajg.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtvqbhfgxq.html

val n: String? = null;  n?.length
来源：http://dali.xziqi.cn/Article/details/gtdejffzci.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gtrnuqeyzz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtnoabwdbe.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtclaskqzi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtyvfgexvl.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtlhfkjepe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtnzjcplxv.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtlzjmxzoi.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtsuqosxef.html

[T09] Kotlin：扩展函数
来源：http://dali.jqgufenzy.top/Article/details/gtknsctonq.html

fun String.exclaim() = this + "!"
来源：http://dali.hnqzz.top/Article/details/gtywnfykrg.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gtzfnreepr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtxtabrtmt.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtfovddutw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gttjkdcmoh.html

[T12] Kotlin：解构声明
来源：http://dali.fzhhl.top/Article/details/gthbxxfqrc.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtvcvmmiwq.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gtosdtgdvy.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtvwxzxuxr.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gthhrqvane.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtdfwjshcj.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gtqhtetmka.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gtxumrplup.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtireuyisk.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtfbvcgsdd.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdavlfdis.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtbvirvkgt.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtkzfkzfym.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtjelabmqi.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtbifzaays.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gttqzlodqz.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtulvyuozn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtpvpuatnq.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtoeujmuhp.html

for x in a { print(x) }
来源：http://dali.zhoulong.xyz/Article/details/gtbrazjhpa.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtbzhdlmry.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gtpeeqgoll.html

[T23] Swift：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrhhievk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtklkopfes.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtguckbjpl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtqsdiltfq.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtqoifhubc.html

struct P { var x: Int }
来源：http://dali.tanke756.top/Article/details/gtcedhnphw.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gtvkunwlkf.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtqypbodov.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtipxuqpxt.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gtfnlilyya.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtlvvnwvqn.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtilieasnd.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtaxwzzgeh.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnohhnges.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtwcgjamdh.html

protocol Shape { func area() -> Double }
来源：http://dali.wangdashe.top/Article/details/gthlnvypfk.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtrexgqmtm.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtscorqpai.html

[T32] Lua：局部变量
来源：http://dali.gogol.net.cn/Article/details/gtsfedrshh.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdsdofsql.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtwjgnfwdz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtdhhuxaqa.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtuqjzdbio.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtwdvsxcnl.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtbhaouhei.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtfjezdfnq.html

[T36] Lua：函数
来源：http://dali.andypj.xyz/Article/details/gtwljnpeur.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtzeermhcf.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtyvvfafrx.html

"a" .. "b"
来源：http://dali.tanke756.top/Article/details/gtuesbndma.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtiowifjlr.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gttxczoitg.html

[T39] Lua：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtwkhuowjm.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtsmytzroa.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gtocuozwff.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gtwksdlrzo.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtvagztuzc.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtmstjgcdd.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnxbcxfx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtiyhklgwg.html

[T43] Perl：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtegslgltj.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtmsqhfagb.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbfzqcdk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtzsymwhqw.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gtjgbbrthz.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtdkatacly.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtujuokmsw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtdjabssyl.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtoolyfrxg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gtfatfldtk.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gtxcyietsv.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gttnjwcfnn.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtxgifjhtv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gthhrpudcv.html

[T50] Perl：逐行读文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtablsuuzh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtijlobdrr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtclyxiare.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gtpjfgsqdd.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtdqtqdznq.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtyhuqdvwk.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtqbhqqbro.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtnvlgtgxd.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtrtmoejpr.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiryabpjy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtlzsfardh.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtxygqnqgh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtvfmfluzc.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gtkivckjry.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtvaawbkll.html

[T57] Scala：模式匹配
来源：http://dali.sufxvd.cn/Article/details/gtmntgjxbk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtuttmwonl.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gtlhzdutzp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtcuyoqrlj.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gtihduteqd.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtghxopmur.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtisbwxmgb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtkgoxssna.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtebmmuqtz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtrqrgruok.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoiucuuvc.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gtsottplrj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gtvcoxppis.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gtlkmomugb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtvyypzebh.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gtfwtidiel.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.havefunace.top/Article/details/gtysgopnpn.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtahvrgsur.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtosrtwhul.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gtuumvlmvs.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtkawhvext.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtbanqjljr.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtzqiiuqwd.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtiifggbjq.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gtgipqlnks.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gtyekpzakx.html

[y for x in nested for y in x]
来源：http://dali.dianchejie.cn/Article/details/gttgokhkoj.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtocsaqldz.html

max(d, key=d.get)
来源：http://dali.smart0.xyz/Article/details/gtzgkmooob.html

[U10] Py：按值排序字典
来源：http://dali.bjfxy.top/Article/details/gttxcuwppc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gttpbcsubm.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtitmjvqag.html

(x * 2 for x in arr)
来源：http://dali.cashguo.top/Article/details/gtsmieldim.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtsphgipft.html

Counter(arr).most_common(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqocepxbj.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtegysbcom.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtezzsinpv.html

[U14] Py：分组收集到列表
来源：http://dali.zhixingplan.top/Article/details/gtxnymupwp.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgasruhgg.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gtkpouziyg.html

t = time.perf_counter()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspqeytyk.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gttlmaijjj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtycvviztm.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtjhbfrmhv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtpoxopere.html

[U18] Py：预编译正则
来源：http://dali.gzhubu.top/Article/details/gtropomcfo.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtnslhzvit.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gtiwnizond.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtbxjnezbx.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzmpqkvp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gtgccmauhb.html

[U21] Py：自定义上下文管理器
来源：http://dali.gzhubu.top/Article/details/gtdnotzred.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gtmgduzwle.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtcqgwvsqg.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtdwadzuco.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gtaoyynpei.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gtlhpbvhzu.html

[U24] Py：路径操作
来源：http://dali.hfpthk.cn/Article/details/gtmkswjpxk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtxfqmituy.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gtpzjezvjy.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtzzmwkrxu.html

[U26] Py：并发下载
来源：http://dali.yj202588.top/Article/details/gtczovnyuo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwjenkrk.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtrwwhujbi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtgdmkhint.html

[U28] Py：类型别名
来源：http://dali.shuidangran.top/Article/details/gtfvrexieb.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gtaqedwqhy.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtrefczeqp.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gtcazfrhbu.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtkkyvhpjb.html

@dataclass(slots=True)
来源：http://dali.dashuyun.cn/Article/details/gtblgoomsr.html

[U31] Py：单测
来源：http://dali.haohaochexian.top/Article/details/gtuuohlegx.html

python -m pytest -q
来源：http://dali.gotoacloud.top/Article/details/gtyzcedwbf.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtcohewjeu.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtlrkkniqy.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtggrueood.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.daxiang520.top/Article/details/gtipdrifom.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gtrjcdojbk.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gtzairndff.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gteivbhcvn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilhmmtjk.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtmydhwsoi.html

schedule.every(10).minutes.do(job)
来源：http://dali.aizwys.cn/Article/details/gtuxtpmygl.html

[U37] Py：读写 Excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuheqvrf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtkcdedppq.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gtqgkkkcfk.html

Path(__file__).resolve().parent
来源：http://dali.gogol.net.cn/Article/details/gtgjzrjhmm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinqigufen.top/Article/details/gttptflodb.html

sys.stdout.isatty()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejojdhnp.html

[U40] Py：打印到标准错误
来源：http://dali.zhiwuduotai.top/Article/details/gtxscggbfq.html

print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtcwusmzur.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtuugflanc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hnqzz.top/Article/details/gtrtmxmeeh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gtnwgyrzch.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gtekoqxfnn.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gtclgxvmzz.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhfncfkc.html

[U44] PHP：开启严格类型
来源：http://dali.ppjwa.cn/Article/details/gtvqaebrdz.html

declare(strict_types=1);
来源：http://dali.zdqjudy.top/Article/details/gtshiagctn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnzfuqha.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtxldmebtl.html

[U46] PHP：可空类型
来源：http://dali.hfpthk.cn/Article/details/gtjpahxyko.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtmtjkadzx.html


<!-- 参考信息 -->