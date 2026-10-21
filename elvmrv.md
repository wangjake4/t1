代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtujtomvfa.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gtyeefsoan.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gtbwiglatz.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkbowtdw.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gteqltpcyj.html

[S29] C：变参函数
来源：http://dali.cheryme.top/Article/details/gtzinyydkg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gtcnvlqknf.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtdzdhhjdp.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gttezzbzcu.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtnktcjdyt.html

#endif
来源：http://dali.yj20258.top/Article/details/gteyiinqfe.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtoxtatnyn.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtiwqytfit.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtbovpamxm.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtwwtabzgq.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtcndtwqep.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtuqlosfby.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.kuanghao11.cn/Article/details/gtdnazoqki.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtolapnqzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtijvtjmbz.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtnmlffvxy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtbpwrblpm.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtqxlyhexv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtglwdufvn.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gttxochqei.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhixingplan.top/Article/details/gtklyfknoz.html

[S38] C++：排序
来源：http://dali.pycfn.com/Article/details/gthgyjlbop.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtzmpblkvs.html

[S39] C++：自定义比较器排序
来源：http://dali.chenlongwang.top/Article/details/gtdmmtzbqt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtztqlphxz.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gttwtebsms.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtpwrfaacv.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyqulxwa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gtmjinuvkv.html

[S42] C++：继承与虚函数
来源：http://dali.nanxinkj.top/Article/details/gtsvdtpmqo.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gttdvmsigo.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtpeuiignl.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtxpqxqihj.html

[S44] C++：引用传参
来源：http://dali.zhoulong.xyz/Article/details/gtfmillqwg.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxhoiwwx.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gtjczulbyd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvdappho.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvuxjnwt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwwdjlfxm.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtukzhsfgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtrcxcywfi.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtaanqocpr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.feifeiyinyue.top/Article/details/gtfmgokdkz.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gtklesvnxt.html

[S49] C++：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxalsbuez.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtilwiwjsp.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtmjoqjsjn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtbsqqaqhl.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gtstfzkvjp.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gtnfdpccav.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtgtrjjhfo.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigfzy.top/Article/details/gtbgosaios.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtdwmtwcuz.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtdkslbqpg.html

[S54] C++：异常处理
来源：http://dali.aizwys.cn/Article/details/gtyyqvkaqa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtytqqeero.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtexwnnkhf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtfdzfttga.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gtbwxzteho.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtbwiptyqv.html

[S57] C++：编译期常量
来源：http://dali.wangshuangyany.cn/Article/details/gtjlojafcz.html

constexpr int N = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkycdtph.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtnpanekfx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtpmhgxbbf.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gtralamrmk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sysykeji.top/Article/details/gtyslmnoup.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtfmkkqbnt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gtasqeoyau.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtaldiigsv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtlgtxaset.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjuwhqusc.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtmwfpupvn.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gtgsfkswjb.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gtzoixnhco.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sufxvd.cn/Article/details/gtasybsjea.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gthqxbjrfg.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtevfdwgzy.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtumytftxk.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtjropltjz.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtqrndkpyg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtmslmzdtt.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtlivtwdiv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtuzrhnreq.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtoeyzvbkh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtakrdzegb.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtbpdlxcuq.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtbuklozgu.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtszuxmgql.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtltdkzspu.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtorpsuucv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtsoqtsjjt.html

[T11] Kotlin：协程
来源：http://dali.hnqzz.top/Article/details/gtjgzucser.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hongshengwenyu.top/Article/details/gtwiotekoo.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtqupylewb.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhczbmfj.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gttzsnppse.html

val m = mapOf("a" to 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxozohqyt.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gtqoyhxmqz.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtgiktvfdj.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtxzmttwvw.html

interface Shape { fun area(): Double }
来源：http://dali.316326.xyz/Article/details/gtfpirvzze.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtwxerkkfo.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtrnhioeve.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gtkljiavap.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtfjjonmoq.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gttncfbzgo.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtetrmhdxe.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtjswnfffx.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gtibbpfgxb.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtecfexjve.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtfgiqbegg.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtnukbjpli.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtzjuatdbi.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtdmpqbrmt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtrbkuglny.html

[T23] Swift：函数
来源：http://dali.shzxlz.cn/Article/details/gtefvhezpp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gtgmvsvzzh.html

[T24] Swift：闭包
来源：http://dali.haohaochexian.top/Article/details/gtuckuoeak.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yongpay.top/Article/details/gtlombkups.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtogmizdbw.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtemiztpnl.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrstqpktv.html

class A: Base { override func f() {} }
来源：http://dali.dashuyun.cn/Article/details/gtpotmylri.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtmbpqafhm.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtyspmmxrz.html

[T28] Swift：枚举
来源：http://dali.zhengqikj.top/Article/details/gtfdnylwtp.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtfktrfvab.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtjbefcfku.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gtxwwbrdib.html

[T30] Swift：协议
来源：http://dali.shuidangran.top/Article/details/gtzwaucbcc.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtqrjyulhu.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtkhnbcyoo.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtgnsuyaft.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtkvwmmupn.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtikudbunt.html

[T33] Lua：表（数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtagynjcvn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtmxbjgcye.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtowokdzxw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gttmjrnmej.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtfmmhumbx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gtvrzvgfhh.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtbtavmgad.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtzqfixkqi.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtkvaasnad.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtsalfpkuj.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gtoyvzintf.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtjttiikuy.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtnxdomgop.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtndfryesb.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gthmunnjxp.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtrhxjrtdk.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtjgbfzabj.html

print "Hello\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtnfldjpov.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gtudbheezn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtgzvbqhyi.html

[T43] Perl：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtzpeuxyle.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtimldvesn.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gtmzlpbmzh.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtwwhndbro.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaznnrdy.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gttttifsgc.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtaytnvjlf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwptysuvj.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtdhmyafta.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sweek.top/Article/details/gtkzllckwx.html

[T48] Perl：正则替换
来源：http://dali.aizwys.cn/Article/details/gtkktraksk.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtzwbeqwkx.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtkmmebdde.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtiomwfhpc.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtahemoxrb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtwslociwc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jyoumei.cn/Article/details/gtbdowpqyj.html

[T51] Scala：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtwoxszbou.html

println("Hello")
来源：http://dali.nwbrower.top/Article/details/gtldhikhnu.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtpvdgiafo.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtqphnemqd.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjihgzkr.html

s"值: $b"
来源：http://dali.xuanzx.com/Article/details/gtbhxknxgc.html

[T54] Scala：集合映射
来源：http://dali.c1oappe.top/Article/details/gtqibqtpld.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtjppsermz.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtovvgxexa.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtkuhjvpli.html

[T56] Scala：样例类
来源：http://dali.guowangkeji.top/Article/details/gtsuwwtfgr.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gthodbjlrg.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtxksihgql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gtpzlbxkfs.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtkqhuopad.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtxmdzktfb.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gtibieqrpg.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfluunhe.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtqqoixhbj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrxqaprj.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtaccowrce.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtyedipavs.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhplxhha.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtlokpbqpm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gtzkayvdgx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtannvlzrr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtmazothbc.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gthlpblqoq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtycrruuoa.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtntyqewgz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jyoumei.cn/Article/details/gtbqegddht.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gttfcbxkhn.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtdpjfgipl.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrumbmmo.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gtnvnmtzbo.html

[U07] Py：反转字典键值
来源：http://dali.svipenyu.cn/Article/details/gttitcryks.html

{v: k for k, v in d.items()}
来源：http://dali.cdnleiting.top/Article/details/gtnghqbynl.html

[U08] Py：展平二维列表
来源：http://dali.yj20258.top/Article/details/gtnwaabofx.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtwmvdkbmk.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gttjsddvzi.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtqmqsmlpv.html

[U10] Py：按值排序字典
来源：http://dali.dashuyun.cn/Article/details/gtnidhxxkh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtjrlajzrw.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gtetjzdxyw.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtxeyhpviq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gthucllfva.html

Counter(arr).most_common(3)
来源：http://dali.hfpthk.cn/Article/details/gtxwcfzsbc.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtgfulnfwu.html

deque(maxlen=10)
来源：http://dali.fengsongda.top/Article/details/gtjkksgfum.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gtqjdfcsjy.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gtckoojxaj.html

[U15] Py：高精度计时
来源：http://dali.chenzaomai.com/Article/details/gtajyoboav.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gtkilttrnw.html

[U16] Py：命令行参数解析
来源：http://dali.fengsongda.top/Article/details/gtobbmfxou.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlvztnmto.html

[U17] Py：初始化日志
来源：http://dali.yuanzhike.top/Article/details/gtpaosxgki.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fzhhl.top/Article/details/gttnennctw.html

[U18] Py：预编译正则
来源：http://dali.yueranfly.top/Article/details/gtqubcrvwo.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtviehcgml.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtqlhodktt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtzmywmole.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gttwffrxtj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtvwmprnmo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsissqnxj.html

@contextlib.contextmanager
来源：http://dali.birdmap.top/Article/details/gteexhbmxl.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtqbuxfgkl.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtcgxmvpld.html

[U23] Py：分块读取大文件
来源：http://dali.feifeiyinyue.top/Article/details/gtkgjlhggn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtdobfrxbs.html

[U24] Py：路径操作
来源：http://dali.9152youxi.cn/Article/details/gtaytbhzim.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtoquqskbg.html

[U25] Py：CSV 按字典读
来源：http://dali.zycfv.cn/Article/details/gtrzbqlocj.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gtcyjdsfma.html

[U26] Py：并发下载
来源：http://dali.chenjidiqi.icu/Article/details/gtheryrwva.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnujdrihe.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gtnwmzdksc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtobypaxup.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gtybsqtkwi.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtgahqzbzw.html

[U29] Py：属性校验
来源：http://dali.snrcjt.cn/Article/details/gtdsspuvlr.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtqwliypka.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gtjgmslelv.html

@dataclass(slots=True)
来源：http://dali.shzxlz.cn/Article/details/gtxmyzidat.html

[U31] Py：单测
来源：http://dali.gaohongyu789.top/Article/details/gttohgyzvh.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gtuggpsdvz.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtaxfydjkp.html

ruff format . && ruff check --fix .
来源：http://dali.vqdsnc.cn/Article/details/gtsuxvmgnk.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gtnywxlbpk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtluinyrru.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtqwudxnij.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtntxcwxjk.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gtjhqroats.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgufenzy.top/Article/details/gtiqlmlgnd.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gtfaxodhvq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gtgcaxzfke.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gtegbiygqb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtgevojseq.html

[U38] Py：获取脚本所在目录
来源：http://dali.gogol.net.cn/Article/details/gtoxilrsnl.html

Path(__file__).resolve().parent
来源：http://dali.nanxinkj.top/Article/details/gtfsvarrlf.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gtuobuqcsz.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gtcdxnjxyg.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtvvncblql.html

print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gtirjhcstn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gtilujyygt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhongyouzk.top/Article/details/gtlztxbkny.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgfzy.top/Article/details/gtqyfwoopp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtskbcpxay.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtmlskdzwl.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtzcsbpiwd.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gtowibwmrs.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gttdwkhukr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtbnxojbyz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtmnfjefmb.html

[U46] PHP：可空类型
来源：http://dali.zhoulong.xyz/Article/details/gtugwxkvto.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtrdxjvkat.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtzqxnupfp.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtvstllaqq.html

[U48] PHP：纯枚举
来源：http://dali.c1oappe.top/Article/details/gtkhbbjkdv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcclurmx.html

[U49] PHP：只读属性
来源：http://dali.cqqwz.cn/Article/details/gtmtorhuyz.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphczrhwd.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtjeafkwkg.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtvdwcbijx.html


<!-- 参考信息 -->