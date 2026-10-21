代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtqlwcfgjz.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtaleblxnl.html

memcpy(dst, src, n);
来源：http://dali.jqgufenzy.top/Article/details/gttrluxrqi.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtacottxiu.html

memset(a, 0, sizeof a);
来源：http://dali.pengpengdd.cyou/Article/details/gtejhsjqri.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtpxbfblgx.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtvmnosijl.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtvsbqpofd.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gtjjdvvqbk.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtixrplbpq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntkcmwzj.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gttuokmuim.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gtuvqfzryc.html

#define X_H
来源：http://dali.xziqi.cn/Article/details/gtpvsgpeer.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtdoofifth.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtquzlufvj.html

#include <iostream>
来源：http://dali.hnqzz.top/Article/details/gtpvrnxcrw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtdaiyaeqz.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gttddviels.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtwnbhimje.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtqticgyhs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtlufnyfsh.html

[S34] C++：遍历 vector
来源：http://dali.ehwqpu.com/Article/details/gtmqbzdrvn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtjvsqmzjs.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtuglpjrzf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gthitbbyyj.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjegkfvc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoikqilxa.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtbhapzxpx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtwcvltajp.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtamyhewky.html

std::sort(v.begin(), v.end());
来源：http://dali.zdqjudy.top/Article/details/gtyocgheop.html

[S39] C++：自定义比较器排序
来源：http://dali.cashguo.top/Article/details/gtsvmdmvmk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhztiaev.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtfbrgerye.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtaevnpcrr.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtpdokyilq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtbtdfmbet.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gthvsauabx.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gterejemjd.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtcdtqrbeb.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gtzrmnuxcv.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gteaahhgxq.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvynemmnu.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtqgmkwvjj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhengqikj.top/Article/details/gtlcvyearj.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gtdshzhirm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gttmhsaelr.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtfcgujbmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtmcrgksks.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtduvkfkka.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tianlin.xyz/Article/details/gtmrkaumgp.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtnaevfvur.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtlpcgdwaq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtparyffxy.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtnmihidkk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtaytklepf.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gteorpvfbb.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtdzfzlszp.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gtukpkmmus.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtmbehyinw.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtwpfaqyxz.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtszzethsg.html

[S54] C++：异常处理
来源：http://dali.yanxiufei.cn/Article/details/gtkjkrtcsn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gtibcibtjs.html

[S55] C++：结构化绑定
来源：http://dali.mhx1999.top/Article/details/gtykzcvfrr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gtxsjyacyw.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdqamkml.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtwcqddyua.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtklntvaea.html

constexpr int N = 10;
来源：http://dali.gzhubu.top/Article/details/gtgcaqufcr.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtcsgipxus.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtxpxqtyee.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtbeceutwx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtjkicblsa.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gthwpdqwwp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtmyeufsbz.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvuxvymm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gtgmmkqjty.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtxrilscds.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtkqxbfvhf.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtsunntmho.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gthdeijjng.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guowangkeji.top/Article/details/gtkuvxfary.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtaenbgxoc.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gthyboudfk.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gtxsdbruru.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtggwabfun.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtirhcebhd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtcibwfgde.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdfxjvzxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtbqyyskui.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtpihozwpd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtumwvydkr.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtrchiuewu.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtnkvjbodp.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtgpjieaqg.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gtihuawmrn.html

[T10] Kotlin：默认参数
来源：http://dali.316326.xyz/Article/details/gteprvxhvc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtxnggvnti.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtccvdycvc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.dashuyun.cn/Article/details/gtshmioepz.html

[T12] Kotlin：解构声明
来源：http://dali.zhixingplan.top/Article/details/gtrgzyqyek.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtqeoujdmh.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtzgnxezys.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtuxfbktah.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtrhtxyooo.html

for (i in 1..10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtnedyzbxy.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqyjmikm.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtzqlaookw.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtjynhrmnb.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtzcpnxucl.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtryukiokm.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtvfvwcegl.html

[T18] Swift：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtuzlysbqa.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtunxwdmvu.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtghwsugvw.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtxmtmxrfl.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtueaxmvmu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jlsjyb.cn/Article/details/gtmnmepsyr.html

[T21] Swift：遍历
来源：http://dali.yj202588.top/Article/details/gtlmwpdlhy.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtlowfzizn.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gtcgxoasiz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gtduegtzax.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtzixoihgg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtdzujadne.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtqcxvywau.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtqligppdv.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtpkqqarqs.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtmgcdupvo.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtsjhyrjth.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gthrulywef.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtgzivokwx.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gtxeimuspu.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtmpargskw.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtbtdojvee.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gthburfdtl.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtmpwdgsus.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gtodtgkepd.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtplnoiwiy.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gthrrgqshv.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtwyhrpwcj.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtrwarzaab.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtxzicyfbk.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gteizgvyto.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtbucvyezr.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gtglmmbbkr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtrcyyhwlx.html

[T35] Lua：字典表
来源：http://dali.zdqjudy.top/Article/details/gtslqwfhlc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtyznennsp.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtqaadmiuy.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtxgdcxwqh.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtoqwzpnxo.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtranphiox.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtphtkzbsp.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtvrjyhcdh.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtutxdwvnw.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtldipljpz.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gtznsauvnm.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtmzvtwdvj.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtviqtmtqh.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtclcidxaz.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtyfsrxage.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtcedmaytj.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtccnslanu.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtloilvafa.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtvansbfjf.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gtuayfarde.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtecgbrevk.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtyanadkki.html

[T46] Perl：哈希操作
来源：http://dali.zhiwuduotai.top/Article/details/gtcwrhfjps.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gtatstrfwp.html

[T47] Perl：正则捕获
来源：http://dali.dianchejie.cn/Article/details/gtwlrunzkr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtbypypsyz.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gtwijfjayf.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtncyasian.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtfzawpjmr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtqhngottg.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtdtpfjyhp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtrpllpcjs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcfkwnhmf.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtrifwhdek.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtqancpqfu.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtrehizndn.html

val a = 1;  var b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtacxwtgat.html

[T53] Scala：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtlvnxegpr.html

s"值: $b"
来源：http://dali.xylfe.cn/Article/details/gtxwaybgqd.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtgjscbtrd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtfkuesbgr.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gttdhedipc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gtqcruzoxd.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gtcnxatczh.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtohgqlyyy.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtcqisuxgm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shzxlz.cn/Article/details/gtzpnsvcqe.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtvvpriwlx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gtidlbtgve.html

[T59] Scala：循环
来源：http://dali.wangshuangyany.cn/Article/details/gtrkkyhoaz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtpcmhoxxt.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtrjajujbq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtiwnvppdy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlffzjtai.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjqdvlfw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxgdpwghr.html

[U01] Py：创建虚拟环境
来源：http://dali.hammf.cn/Article/details/gthrtqutsk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtuiupycor.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtmaxgxqzt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtinsjecmh.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtexbxzbfk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtcbedcrek.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtxeifwpie.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gtlbfcebkd.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtlspmrpln.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtzwkdhdae.html

[U06] Py：合并两个字典
来源：http://dali.zhongyouzk.top/Article/details/gtjrnrrgnz.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtcfbkgfre.html

[U07] Py：反转字典键值
来源：http://dali.yanxiufei.cn/Article/details/gtgwflplsi.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtynbzsnzc.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtndbumnfo.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsforrjxd.html

[U09] Py：字典取最大值的键
来源：http://dali.chenlongwang.top/Article/details/gtfosdgiia.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gtctyiouhr.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshzijwhg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gtzbtcsphh.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtarbtirek.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtowckwhex.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gtqpwihbpa.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtetgoswqo.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gttcwvqqem.html

deque(maxlen=10)
来源：http://dali.zhengqikj.top/Article/details/gtffmpwurk.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtkdxsjcdo.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtublehfmq.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtvpbengmg.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gtfybfrltl.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gtzurhpntu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gtvhxspfnu.html

[U17] Py：初始化日志
来源：http://dali.pengpengdd.cyou/Article/details/gtiwkvjbxi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.vqdsnc.cn/Article/details/gtzxapngsm.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gtmnwfzkrx.html

pat = re.compile(r"\d+")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnxzwutp.html

[U19] Py：正则替换带回调
来源：http://dali.cucudq.cn/Article/details/gtwygupenx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gtambbrmca.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gtydknjjgm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtoukofltt.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtzsplrnzd.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gtjsdwbrwg.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtjysyfwpy.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gtmkefafqw.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gtbacdertg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtmqkzwdsa.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gthdkkjilu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.bjfxy.top/Article/details/gtyqrzntsf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gtyeqhrypj.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtsxexdwwc.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gttnrutoab.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gttngelboj.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gtfmfucqwe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gtejmfzson.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtrsudmlvw.html

UserId = int
来源：http://dali.hongshengwenyu.top/Article/details/gtgbssttxe.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtrzqlggjf.html

@property 与 @x.setter 配合
来源：http://dali.tian-w.cn/Article/details/gtwtunvsws.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtkjmjwyvt.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtjzgntgcs.html

[U31] Py：单测
来源：http://dali.316326.xyz/Article/details/gtljnbuero.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtkwelrmtw.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gtcxqiwuma.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gtncgdfqjy.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gthshyzkiv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gtpxjraoio.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtntllyrfq.html

chardet.detect(raw)
来源：http://dali.hammf.cn/Article/details/gtwjnkdcla.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmtelfzz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxinkj.top/Article/details/gtjpmenxze.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gtqmvfcbhi.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gtzionbhgp.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtdtogfxhy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gtgiywqfpq.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigufen.top/Article/details/gttwxaactk.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtipnlelof.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gtohuxvjar.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gtcwauglqe.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtrwstcxlx.html

print("err", file=sys.stderr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhqvltrc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tian-w.cn/Article/details/gtyxmlszxv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zdqjudy.top/Article/details/gtbiyakoyg.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtuzgmhyoq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gtsbzzlrtz.html

[U43] PHP：声明命名空间
来源：http://dali.nwbrower.top/Article/details/gtsahnvvih.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gtcczyxepy.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gtrsqruiiw.html

declare(strict_types=1);
来源：http://dali.snrcjt.cn/Article/details/gtyyqsfmnq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtyuoglwbx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtfcgwqdhv.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtlyxcemoe.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gtmhqnezqh.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtusmupkcw.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gttjlpuswv.html

[U48] PHP：纯枚举
来源：http://dali.tanke756.top/Article/details/gtooxeggce.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gotoacloud.top/Article/details/gtlgpcxbmm.html


<!-- 参考信息 -->