代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtlsvqtcfx.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtzblkncgd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtoymvoknf.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtuzxhrspz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jyoumei.cn/Article/details/gtartzqtiy.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtdpuxwcuk.html

memcpy(dst, src, n);
来源：http://dali.sufxvd.cn/Article/details/gtkqtttbgi.html

[S26] C：内存清零
来源：http://dali.zhengqikj.top/Article/details/gtybhggccp.html

memset(a, 0, sizeof a);
来源：http://dali.smart0.xyz/Article/details/gtqaguuqdr.html

[S27] C：定义常量
来源：http://dali.yangfankeji.com/Article/details/gtwbupvswq.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtweyywotm.html

[S28] C：静态变量
来源：http://dali.ehwqpu.com/Article/details/gthnaktfep.html

static int counter = 0;
来源：http://dali.ehwqpu.com/Article/details/gtodswjjcs.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gtzqwjdtmt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ybcxt.top/Article/details/gtwszadzrt.html

[S30] C：头文件保护
来源：http://dali.zdqjudy.top/Article/details/gtrukwklny.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtqtapynha.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtmbjbtscy.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gtgptblnwb.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtximrwyzf.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtbacnnbfa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtwpsdwryp.html

[S32] C++：字符串
来源：http://dali.mhx1999.top/Article/details/gtbagsuakw.html

std::string s = "hi";  s += "!";
来源：http://dali.xuanzx.com/Article/details/gtyvckburt.html

[S33] C++：vector 增删
来源：http://dali.jlsjyb.cn/Article/details/gtcskroftq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtxvmxntct.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtyehqlwea.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtzirrahnw.html

[S35] C++：map
来源：http://dali.yueranfly.top/Article/details/gtrqhwoyuy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtngozagdp.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtrylazluu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtuadihaya.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtwuonszmu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtwpqfgqhe.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtirdcjpmf.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtevljpdmd.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtlrpigpqm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aibaodan.cn/Article/details/gtigfnowae.html

[S40] C++：查找元素
来源：http://dali.dashuyun.cn/Article/details/gtuwqohtnh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtomkeazru.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtywdmudwt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtjakudlvp.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtvliiqzrq.html

class B : public Base { public: void f() override {} };
来源：http://dali.yueranfly.top/Article/details/gtyibbavri.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtnoggfkvw.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gtollecazk.html

[S44] C++：引用传参
来源：http://dali.zhongyouzk.top/Article/details/gtjfybsdvh.html

void inc(int &x) { ++x; }
来源：http://dali.nwbrower.top/Article/details/gtrerobqkb.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtkxkqforg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtgrkkvwdz.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwozriod.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtovqkunpr.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtzkwxsjfm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gthuuozase.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtybfjcyeu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.bjfxy.top/Article/details/gtgthdbean.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gtejphujod.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtcicppejx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtomhredyi.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gtaqzdzxzb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtmkfsuuye.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtyygwmgah.html

static_cast<double>(a) / b
来源：http://dali.yj20258888.top/Article/details/gtcqsqaskz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gtywokytyp.html

int size() const noexcept { return n_; }
来源：http://dali.vqdsnc.cn/Article/details/gtdkjuxkcm.html

[S53] C++：移动语义
来源：http://dali.zhixingplan.top/Article/details/gtopzadclo.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtpktinxdt.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtyydhgwic.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtirkfppth.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtktlkzpmw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtztggfdzx.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtvowjgwkc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtvvyisnda.html

[S57] C++：编译期常量
来源：http://dali.ydzc1.top/Article/details/gttwatrwaz.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gtwlplmyau.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtvohvkymx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yanxiufei.cn/Article/details/gtxqwbyrdm.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyihpshu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtmnnxphtn.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtbnaqarwv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtvwwmnrwb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtglxcybvn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtlnusadfw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtjsfzejca.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtxmvttgkh.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gtjtgeyoty.html

[T02] Kotlin：变量
来源：http://dali.nanxuanxn.top/Article/details/gtlhworrbb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsiuplrt.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258888.top/Article/details/gtjzfiaezx.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gthumqnfxa.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtysyuegpv.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtjawedeuz.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtxohcvtxg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtwioqbwkb.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtmfuxxdqm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtilknmpgq.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtauagfcuu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtywgecknp.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtcpoptikf.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtephjilnb.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gthkpnnduq.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtwptmewow.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtttvwrncr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtcjthkgpe.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtnqkydvel.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtjtgoyhzx.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtyurprfcd.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenzaomai.com/Article/details/gtfiycgzwz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtlxtpofch.html

val m = mapOf("a" to 1)
来源：http://dali.xuanzx.com/Article/details/gtjlrjkgig.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtasjxcsbi.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gtbxdncxos.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtqlkvpyie.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtbrurkggp.html

[T16] Swift：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtdcnravsq.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtyomvxnov.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtksfvibzv.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gtqhcfydmn.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtclyarqud.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtwyzjlrut.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtvkjktcxf.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtclflzjxq.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhkrqtcu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtzyagsfvl.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtnhmfnvmp.html

for x in a { print(x) }
来源：http://dali.zhiwuduotai.top/Article/details/gtchprbtbt.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtnbjmihky.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gtzwsqpsat.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtcydazada.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtqtvgscrt.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtofcyhmsd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtvroxqwqo.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtycpuekak.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gtjhvlcczz.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtthuhvlcp.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtzxwmchme.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gtjerownaq.html

do { try f() } catch { print(error) }
来源：http://dali.pengpengdd.cyou/Article/details/gtxswylghw.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtefciehis.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtprwqkjfc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtxoavlaze.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gtkanwkxwm.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtymsflrik.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gteihukhuc.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtrafzcyyw.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gthceybarz.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtnoaaotwg.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtohhpwc.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtjjigdefn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtvmpvlxtr.html

[T34] Lua：遍历表
来源：http://dali.sxryk.cn/Article/details/gteuntkzin.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymcrmmfk.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtwvqchizv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tianlin.xyz/Article/details/gtohslxdkz.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gtdefiwlus.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtfongnfzq.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gttzftmqoi.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtxwktgabe.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtlevalclp.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtftqbwtlb.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqustybp.html

string.find(s, "%d+")
来源：http://dali.jianghu66.top/Article/details/gtnijljnht.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gttqundimw.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gthkheujtw.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtxlxvdcrb.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtszrtwopo.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtqnkrqhba.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtqmhxtdiq.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtdtkcbwzc.html

"值: $a"
来源：http://dali.chenzaomai.com/Article/details/gtvtcqadxw.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtxdidbgbz.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gtledkaknt.html

[T45] Perl：数组遍历
来源：http://dali.cdnleiting.top/Article/details/gtofhazfet.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtnuiaczrf.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtmzdyyekd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.kuanghao11.cn/Article/details/gtspfiemkq.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gtiperhxnl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xinyue.icu/Article/details/gtvhbsgyjg.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gttygfkpbh.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gtzgoendwy.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtfktlhmya.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtffposaja.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtwbcgbscj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtdyyykwpr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrtfkzixu.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtudxlezbq.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtugkurdyy.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtdblaqqbh.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtgteritat.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gttqfltbxx.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtdxqfwhlh.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gtgbegodsu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtqjrqxyqb.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gthtxewjbz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gticgzdwni.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtansnljhx.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gtsqjjgrul.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtdscjmgtx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gthfgroeaf.html

[T58] Scala：函数定义
来源：http://dali.jqgufenzy.top/Article/details/gtqvfwwnum.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gtvdoccotq.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtuftlvteb.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtqzrqbeio.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gtdxfhturd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtoujoqvau.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmyusnhsm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtmugylqpf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlafeuqpp.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gthmacultw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkonszlf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtausnbjnq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daria6918.cn/Article/details/gtypbgfbbv.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gtwbdvazae.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtotpckcnx.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gthcyeiraj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gtmvdijtvb.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtiilndqvs.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gttjwsdsgm.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gtswoifwpm.html

{**a, **b}
来源：http://dali.316326.xyz/Article/details/gtzqcokxbi.html

[U07] Py：反转字典键值
来源：http://dali.yvedp.cn/Article/details/gtvjippqge.html

{v: k for k, v in d.items()}
来源：http://dali.hnqzz.top/Article/details/gthfslviiz.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtfiyorqrg.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtbktzmleh.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gtkueujvcd.html

max(d, key=d.get)
来源：http://dali.aibaodan.cn/Article/details/gtpbfdkjcr.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gthtlggyni.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ydzc1.top/Article/details/gtpbdsmmgj.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtacpvcjtt.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gttqsxdcgh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtqskfuhat.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gtfudlgabo.html

[U13] Py：固定长度队列
来源：http://dali.jqgufenzy.top/Article/details/gtxsoerqge.html

deque(maxlen=10)
来源：http://dali.ehwqpu.com/Article/details/gtkytfhfvy.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtwvyewuny.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtqpdalpng.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gtswxjtzhy.html

t = time.perf_counter()
来源：http://dali.guowangkeji.top/Article/details/gtbragrpbn.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyaotqun.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gtyloqxoeq.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gtkjmgvzkq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpeavpbua.html

[U18] Py：预编译正则
来源：http://dali.nanxinkj.top/Article/details/gthafbuwnq.html

pat = re.compile(r"\d+")
来源：http://dali.ppjwa.cn/Article/details/gthdfrpvvr.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtfypmwode.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtynpnieuf.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gtpwehfhgn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gtfisodhxj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtolojpxch.html

@contextlib.contextmanager
来源：http://dali.hnxiangtu.top/Article/details/gtxhywwbxz.html

[U22] Py：矩阵转置
来源：http://dali.mhx1999.top/Article/details/gtbofbywjy.html

list(zip(*m))
来源：http://dali.pycfn.com/Article/details/gtthizpvfy.html

[U23] Py：分块读取大文件
来源：http://dali.zhixingplan.top/Article/details/gtfuteoogb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gtxrhqyzjv.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtwetpbwlx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtvpeatamn.html

[U25] Py：CSV 按字典读
来源：http://dali.mhx1999.top/Article/details/gtegxszlyl.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gtcyfqgobb.html

[U26] Py：并发下载
来源：http://dali.havefunace.top/Article/details/gtyquubqgz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnqzz.top/Article/details/gtqxvrrtxg.html

[U27] Py：异步 HTTP
来源：http://dali.yueranfly.top/Article/details/gtbtpqhcaj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.svipenyu.cn/Article/details/gtmhkueyst.html

[U28] Py：类型别名
来源：http://dali.xuetiantiany.cn/Article/details/gttxlchixd.html

UserId = int
来源：http://dali.aibaodan.cn/Article/details/gtwlwhcisp.html

[U29] Py：属性校验
来源：http://dali.redwolf501.top/Article/details/gtxcslkeuc.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gtfjtyfbyj.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gtmqbvvhdo.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gtzzycutqw.html

[U31] Py：单测
来源：http://dali.daxiang520.top/Article/details/gtvhvxjjtr.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtruqftrau.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gtkppezqxm.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtuystgtec.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gtlxoabryx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gthhhdkxnp.html

[U34] Py：判断编码
来源：http://dali.jlsjyb.cn/Article/details/gtoipjkqyp.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrszlzhnk.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gtvxvmyhwc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gtscuzvjkm.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gttymmsoxm.html

schedule.every(10).minutes.do(job)
来源：http://dali.xinyue.icu/Article/details/gtvfibdhwz.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gtcyrqldbx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtlyscdzaj.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gtnkyagmcx.html

Path(__file__).resolve().parent
来源：http://dali.meibo888.top/Article/details/gtasagqffm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zdqjudy.top/Article/details/gthisxpuiq.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtouhfrjuo.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtnijfkfcs.html

print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gtapulxgsd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gtkszkesoz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgecmwem.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gtcekzvvdd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gthujmnfym.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gtsrllnkvy.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gtpoeqxbyl.html

[U44] PHP：开启严格类型
来源：http://dali.cashguo.top/Article/details/gtmvopfwzd.html

declare(strict_types=1);
来源：http://dali.sysykeji.top/Article/details/gtpfkuolrx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gthwaetlck.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtokqjzsbk.html

[U46] PHP：可空类型
来源：http://dali.hysaishi.cn/Article/details/gtjpxtbtqc.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtlqvaxzfq.html


<!-- 参考信息 -->