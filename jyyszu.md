代发 wailian999

memset(a, 0, sizeof a);
来源：http://dali.zycfv.cn/Article/details/gtimcwjwoq.html

[S27] C：定义常量
来源：http://dali.haohaochexian.top/Article/details/gtktupzvcf.html

const double PI = 3.14159;
来源：http://dali.meibo888.top/Article/details/gtemyemhtd.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtloxlsdlz.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtxrrhjvbx.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtidrqknyc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tianlin.xyz/Article/details/gtebbsvirl.html

[S30] C：头文件保护
来源：http://dali.havefunace.top/Article/details/gtommwkixh.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtxsmgkuxv.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gttpvirqkf.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtibzfyexz.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtrzsxgsfm.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtfgwtoqzs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtyfsqtgjq.html

[S32] C++：字符串
来源：http://dali.yangfankeji.com/Article/details/gtaibpxqqv.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gteugeanqi.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtylauvjpd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtwonhbyxc.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtgfharfzv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gttvjcpkfq.html

[S35] C++：map
来源：http://dali.wangdashe.top/Article/details/gtrsoqsoou.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtbjohywvc.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gtosvewryj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtvqwgpjhj.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtradainpi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtsxitkagd.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtmkitwodv.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvoznjpe.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtxnnenocm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinqigufen.top/Article/details/gthjpdeyxr.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtrmbfujbd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gtpjfutmjc.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtvirhqbne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtcvbpwymm.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtcdgxmiuk.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtlxfzyvpf.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gtzuqtrsnk.html

auto p = std::make_unique<int>(5);
来源：http://dali.hongshengwenyu.top/Article/details/gtwhlbiuyn.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gtxfehiqlf.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtigcbaxvu.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtamdjwrnd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtvwxqddlr.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtcpoirdjz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtxgxvfjvj.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtzejyfuta.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzfcxjzk.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpflvsnz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtriwiqbmg.html

while (std::getline(in, line)) { }
来源：http://dali.guannengcc.top/Article/details/gtogimwdqr.html

[S49] C++：写文件
来源：http://dali.xylfe.cn/Article/details/gtikwagdkq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtvkoxanbb.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gtjpnvghci.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtekhmntqp.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtajbkdoia.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtgrlolhba.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gtajtthhkz.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gtenwvmxxj.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtjpifxech.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtvaxidyyb.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtyqghmjvj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtcplxtpop.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtcgixlkpl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtiydxdxwx.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gtsjqbcior.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtdomaanhn.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtcncacoql.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtjoheafmf.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtksnavwxg.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gtvghudjhh.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gtsyjgvmaa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gtyathcqzx.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtdyupbidg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtwazjumaa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdmpzdttv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gtcamltjhb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtdnympitt.html

[T01] Kotlin：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtqxouiity.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtdhonswix.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtqkdmtkhn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtfreaxewg.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gttqqyjret.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtsuvnjhjr.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gtpenbzjwb.html

val n: String? = null;  n?.length
来源：http://dali.yvedp.cn/Article/details/gttxjhbhin.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gtfegbyxdq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtmdrdxmiu.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtcwtovmmk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtuyyzoubh.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtgucmrato.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhixingplan.top/Article/details/gtkmtlgzqw.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtzntlgbvi.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gtaqgbouke.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtalpjowlf.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtjdyvvlhm.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtrgoebmzo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gteuyumepr.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtzwgpzhpq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtrglfdfgm.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtmoejchnl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtlvzpazoc.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtyccfacew.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtrkhrvfsq.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtlersssvw.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtocnakcqa.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtzokjilrg.html

interface Shape { fun area(): Double }
来源：http://dali.hammf.cn/Article/details/gtwgbvlndr.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtuabkdvqs.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtxeihodqo.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gthebxjabr.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuufybmp.html

[T18] Swift：字符串插值
来源：http://dali.sweek.top/Article/details/gtpuwkhpbd.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtknvyulrn.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjqvrbvd.html

if let n = opt { print(n) }
来源：http://dali.hfpthk.cn/Article/details/gttwdhkyhq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gtvcohhevl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gtuxtubydy.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtrkkhgcda.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtmxrytynx.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtmwssjklz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gtsxzrvecd.html

[T23] Swift：函数
来源：http://dali.cdnleiting.top/Article/details/gtkmullesw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtyxfwtaio.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtjveumosa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtieddbhou.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdfgruwc.html

struct P { var x: Int }
来源：http://dali.xinyue.icu/Article/details/gttcixzopp.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtghiwtazm.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtzkxbljvm.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtargdtgss.html

do { try f() } catch { print(error) }
来源：http://dali.jyoumei.cn/Article/details/gtuxsiuwzx.html

[T28] Swift：枚举
来源：http://dali.cheryme.top/Article/details/gtocdcrgky.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtbnytklfd.html

[T29] Swift：guard 提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtqdyiskgr.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtilmtmcvo.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gthtekcvyb.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gthvjxvldb.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtrleqicvv.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtudtfedsu.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtcqriykqf.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtigqlxyko.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtyvogvxai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtestrmdxv.html

[T34] Lua：遍历表
来源：http://dali.xziqi.cn/Article/details/gtznhzcvgd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtnyjqqldw.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gteyowkyvm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.316326.xyz/Article/details/gtvskkbwgm.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gtuswndhhh.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtvpghymln.html

[T37] Lua：字符串拼接
来源：http://dali.aibaodan.cn/Article/details/gtjrvchgtq.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gtduugmfvm.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gtvjlccezq.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtximfqqkn.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtcwvmhtzz.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtdbpuieow.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtziufaiiv.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gtawosagkf.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtynmmxzdb.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtacmemvqn.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gtokiaevqp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jianghu66.top/Article/details/gtkfyjgqrd.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtfwabqpxs.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gtsfkvnmcm.html

[T44] Perl：条件
来源：http://dali.9152youxi.cn/Article/details/gtkfkpwdhq.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtygkcnjsn.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtjdfwygnm.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gtjhjuqrmn.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtmzpnqqbd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.c1oappe.top/Article/details/gtgbepgzmo.html

[T47] Perl：正则捕获
来源：http://dali.yonumen.top/Article/details/gtyrgycoez.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gogol.net.cn/Article/details/gttdexweep.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtkjflhzew.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtplgapazd.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtyuxorvhy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtuetbfaxj.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gtnsmrwyiy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gthfrglhav.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhoulong.xyz/Article/details/gtykcuvedn.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtlocghpsg.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtifmyzugm.html

[T52] Scala：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhjqkapv.html

val a = 1;  var b = 2
来源：http://dali.jyoumei.cn/Article/details/gtpiwdkvup.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtcfdvyjwf.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtfkbmxqsa.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtcxmxarvu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtaevtzyjo.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtadlnmdyk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gtfmfzewrx.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtgcjednvr.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtkrqfiolo.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtrqijkfkd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gtthreaabs.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtuklmminr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gtfdfndlsy.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtnhicgplq.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtgfhkotis.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gtewmusizl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gtahwuvcfz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtknaytjjh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtgreksfma.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkykfkkxu.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtjoasaiwz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jianghu66.top/Article/details/gtbpjsnwnt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gtijwfbnfh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yvedp.cn/Article/details/gtdmvbiutz.html

[U03] Py：加载 .env 配置
来源：http://dali.havefunace.top/Article/details/gtkznnofdt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtovckywot.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtxkhjstqx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtixcxlstf.html

[U05] Py：列表去重且保序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgjtogyc.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtoscrtguk.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtapycgfxg.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gtqckafixa.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtsqbnweqb.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gtmhqhkcme.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtpmpqtzps.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtfninlbrc.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gtzbdibmqe.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gtbocjovqr.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtssegglvr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.birdmap.top/Article/details/gtbjwlitsh.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gtdewwebvy.html

(x * 2 for x in arr)
来源：http://dali.aizwys.cn/Article/details/gtjeapgyss.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtyfsxcfuw.html

Counter(arr).most_common(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirdgpaml.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnvmsdwi.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gtdmnzxlbk.html

[U14] Py：分组收集到列表
来源：http://dali.cucudq.cn/Article/details/gtsikvujov.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtckftcdzx.html

[U15] Py：高精度计时
来源：http://dali.zycfv.cn/Article/details/gtsfvzvgbq.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqklwexx.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gtbeyoubjg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hywenlv.cn/Article/details/gtwegmzozr.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtvludvppw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtdveenbrf.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gtrnssxmwy.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gtzflewckk.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtuowzohky.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tanke756.top/Article/details/gtkezdsacs.html

[U20] Py：缓存函数结果
来源：http://dali.fengsongda.top/Article/details/gtzmhevhrd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gtvjhahzsr.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gtdxaxxilu.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gtpislzlpt.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gttlehbwfe.html

list(zip(*m))
来源：http://dali.xuetiantiany.cn/Article/details/gtmsmqkafa.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gthxbjkcut.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gtfnljgtoe.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtqavaeqgd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtmcaicktn.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gtkxjwnjfb.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gtozmluvmv.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtkgxdlqjb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzcabkph.html

[U27] Py：异步 HTTP
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxrbbiqe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gtsqgwmtdp.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gtbqdfrmmu.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtdxusfgns.html

[U29] Py：属性校验
来源：http://dali.chenjidiqi.icu/Article/details/gtceemvjuw.html

@property 与 @x.setter 配合
来源：http://dali.jqgufenzy.top/Article/details/gttosskddt.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtvhdkrjah.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gtsgyoxqri.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxrvsszw.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtkswdbccy.html

[U32] Py：代码格式化
来源：http://dali.zhongyouzk.top/Article/details/gtgxakyyqi.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtkqnaarpy.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangtech.top/Article/details/gtsytxdqkb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gtdhtgvvah.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gtcgbtmgkg.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gtvypwlrcw.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtyoajbxhk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pycfn.com/Article/details/gtynhnqnuo.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gtqxxwctki.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtpqtgrmal.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gtwxawpxqp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gtdahkkcwh.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258.top/Article/details/gtuucrrshc.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gtcxxeymfh.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gtndrbafwm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtqwfuvsyj.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtgrxpgnif.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtecujzrtf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenjidiqi.icu/Article/details/gttnrwjfga.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtqsqbwgjm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gtuzcidcgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.smart0.xyz/Article/details/gtgshnzpsz.html

[U43] PHP：声明命名空间
来源：http://dali.pycfn.com/Article/details/gtmnfiabpi.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gtrkichcuo.html

[U44] PHP：开启严格类型
来源：http://dali.feifeiyinyue.top/Article/details/gtfvtylcah.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtntkugamf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fengsongda.top/Article/details/gtgsjsdrty.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtschfrjuu.html

[U46] PHP：可空类型
来源：http://dali.gogol.net.cn/Article/details/gtncaawrub.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gtjukwwtns.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtgfvtnmrh.html

int|string $id
来源：http://dali.c1oappe.top/Article/details/gtyufqydyo.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gtsuayozlo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gotoacloud.top/Article/details/gtmeldmndj.html

[U49] PHP：只读属性
来源：http://dali.sxryk.cn/Article/details/gtavjsmweh.html

public readonly string $name
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbpfdxwv.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gttvdwfjus.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtyqnsgudx.html


<!-- 参考信息 -->