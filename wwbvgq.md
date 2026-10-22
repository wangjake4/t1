代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2zhcozhem.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gt2ailqyqya.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gt2vvspomtf.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gt2jmwckhlo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gt2abqggltv.html

[S25] C：内存拷贝
来源：http://dali.yvedp.cn/Article/details/gt2wipayzpf.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gt2fnnoljtc.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gt2atwbovie.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gt2bqhbwauv.html

[S27] C：定义常量
来源：http://dali.wangdashe.top/Article/details/gt2holvrkmf.html

const double PI = 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2qbrcvabs.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gt2nbvklril.html

static int counter = 0;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rmfnxdni.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gt2ipotnohq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2ozelzmaf.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gt2zepgowzk.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2qbstabtc.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gt2gbixydxp.html

#endif
来源：http://dali.nwbrower.top/Article/details/gt2vaxsshdo.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2fnvtpvlp.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gt2hadhcmrt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gt2gfrlvnee.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gt2qwafbydq.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gt2ycwmifyt.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gt2wlvvpuef.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gt2mlnfvftr.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gt2odcwstlj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yvedp.cn/Article/details/gt2whgpctva.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2afjenxjq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gt2fdeevdgs.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gt2nephohet.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2eofdfxys.html

[S37] C++：set
来源：http://dali.yvedp.cn/Article/details/gt2wihlzrag.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gt2zqaaixav.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gt2mwafzzex.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gt2zzjyloyy.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gt2mxtiigey.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gt2wuuufgjn.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gt2duqzoubg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gt2vzkvwzur.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gt2tsscutti.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gt2gzbbrdlh.html

[S42] C++：继承与虚函数
来源：http://dali.sxryk.cn/Article/details/gt2cxozhgsx.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gt2uduxnfau.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gt2dobiuxan.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gt2hnyzuwmz.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gt2ldcbnonj.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gt2zigvlrlo.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gt2tlnukuyr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gt2huvobghe.html

[S46] C++：函数模板
来源：http://dali.jyoumei.cn/Article/details/gt2uismkbmo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sxryk.cn/Article/details/gt2kwqeozbs.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gt2laqhdffa.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gt2xpspelfe.html

[S48] C++：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2ebkffjkc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2istmixen.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2faqsgvaz.html

[S49] C++：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2ekrctjzp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gt2wdgavtpf.html

[S50] C++：格式化数字
来源：http://dali.gzhubu.top/Article/details/gt2vctrzzmp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gt2eurotngx.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnruqqhu.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gt2pxuqbedm.html

[S52] C++：const 与 noexcept
来源：http://dali.chenlongwang.top/Article/details/gt2kyjzdgfz.html

int size() const noexcept { return n_; }
来源：http://dali.guannengcc.top/Article/details/gt2sfaigvry.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdspfbdo.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gt2dudkjzwr.html

[S54] C++：异常处理
来源：http://dali.nwbrower.top/Article/details/gt2tbvybtsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gt2dqupwzkv.html

[S55] C++：结构化绑定
来源：http://dali.zhoulong.xyz/Article/details/gt2gnjmvyjf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2byzhfcyl.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gt2stofaifz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gt2spcdwriz.html

[S57] C++：编译期常量
来源：http://dali.zycfv.cn/Article/details/gt2xsgzmdrw.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gt2xwcksacb.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2necclguz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cprihsrs.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2jtunrvwx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuanzhike.top/Article/details/gt2hikxbtuv.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2wfzpmqtq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gt2gyyxljxd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2jqtpldhp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gt2gorzgrbm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2xqjbtcyf.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2apwcksrx.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2ksqsunrs.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gt2sctjwljj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gt2qloaeygf.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2ehmzamuy.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gt2jnriemln.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2dpqppbmm.html

val n: String? = null;  n?.length
来源：http://dali.smart0.xyz/Article/details/gt2zvzpxbir.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gt2dzlpdnag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2tpvkxzvk.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2afyqxykl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2lbketkpm.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2kbguyeax.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gt2aivspowp.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nzixxzpx.html

data class User(val name: String, val age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2sfrhxppc.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2mtwxjdfj.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2ogrmptag.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gt2ucascfym.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gt2nlvxexip.html

[T11] Kotlin：协程
来源：http://dali.hfpthk.cn/Article/details/gt2qnyjouyp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gt2ctowtvbq.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2lhftoabq.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gt2sxminvnd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gt2vqzdjxpn.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2iilsqfvj.html

[T14] Kotlin：循环
来源：http://dali.smart0.xyz/Article/details/gt2czenbhwz.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2grtnfciz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbmblbo.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rctgkvxn.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2zznhfrwt.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2oshzjjxt.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gt2mulrkfce.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gt2tghtmqvc.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gt2vxmiwdtr.html

"值: \(b)"
来源：http://dali.chenzaomai.com/Article/details/gt2ocbpnfdl.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gt2vrjdlfml.html

if let n = opt { print(n) }
来源：http://dali.zdqjudy.top/Article/details/gt2ahhyoemx.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gt2vgbdqptc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2jwzpxmfn.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gt2klirqrvc.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gt2spapcugf.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gt2ejumwqwr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2uszkubfz.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gt2gdmwcapw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2uityghbc.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2tusfbnhm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2mekywdxi.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gt2jbjyevwf.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gt2fefrsnjz.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gt2jbqsirei.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gt2sporvegf.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gt2xaltqwmy.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dyesttql.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gt2ebezsfai.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gt2yxxtxmfc.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gt2ubnpfdop.html

guard let x = opt else { return }
来源：http://dali.ydzc1.top/Article/details/gt2lfzaxiac.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsikapfy.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gt2pktibcuq.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2zfjgyqqo.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2iwuzvyow.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gt2cpcpnuag.html

local a = 1
来源：http://dali.yj20258.top/Article/details/gt2fekexdid.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gt2qdkrzism.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gt2htbyudco.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gt2fvvrufiz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gt2edtmmaco.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2uzuhsfqt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gt2fhlyfmqh.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gt2figbgjot.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gt2blnaklui.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gt2arwscdkw.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gt2bgeftnaj.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2vcsyteal.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dloxknby.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2msholgly.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gt2dswkpwta.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gt2osxajwsc.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ohzdgbnk.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2tjljcjrd.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gt2simqlnxd.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gt2giwcajhg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2tjqsgejr.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gt2zabpvqqu.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gt2tzhxeqvd.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gt2bgwmmjit.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gt2tnaqxjig.html

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gt2yjpmcujq.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yacsyeeo.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gt2gljhfqjm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gt2fqeqnlvb.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gt2dssweanl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daxiang520.top/Article/details/gt2zblqhyay.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gt2mjmfhkdb.html

$s =~ s/old/new/g;
来源：http://dali.yongpay.top/Article/details/gt2wxlfdqkb.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gt2huwgurbm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjzykiff.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2fhzktexb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gt2rslwcwwn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gt2vzjaeuoy.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smrszfcb.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2kaknhixx.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2echganwu.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2ukmvvgoj.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gt2veijnkql.html

s"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2djzbrznk.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gt2ogfbnxhw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2uryztlng.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2fuqrposv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sweek.top/Article/details/gt2kpbniljn.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gt2bcayndvd.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gt2lfijxvye.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2pgzcviff.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nwbrower.top/Article/details/gt2mdndzwvt.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gt2ncohimxs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gt2ruanuxuk.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gt2cnuztihv.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gt2eyntvray.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gt2pnbnphip.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.9152youxi.cn/Article/details/gt2xnpjibjj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2wsimftwb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gt2toblchzm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kacykmtx.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gt2absoetjf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gt2wvfkyhui.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yvedp.cn/Article/details/gt2lrgdjyia.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gt2dhpvynlu.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gt2ydbnvfdq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gt2pdzbnjrs.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gt2hsdysiou.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nwbrower.top/Article/details/gt2ufxazhby.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gt2lzpedoyc.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gt2npbgcwpm.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gt2fcfhrwqb.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gt2svuyavgm.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gt2lweolnjo.html

{v: k for k, v in d.items()}
来源：http://dali.guowangkeji.top/Article/details/gt2qxzywdve.html

[U08] Py：展平二维列表
来源：http://dali.zhoulong.xyz/Article/details/gt2uaxffhzx.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gt2tdlncaba.html

[U09] Py：字典取最大值的键
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtcglila.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gt2tvdvvvgl.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gt2caltukly.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puulxkbe.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gt2sskihbsi.html

(x * 2 for x in arr)
来源：http://dali.daria6918.cn/Article/details/gt2xoclqdmp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gt2davdtlup.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gt2nisncgqp.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gt2fyfhekky.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gt2chjhszot.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gt2llfcbpjz.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gt2nvyiaxid.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2mvfdfgjj.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gt2nypvcgzq.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2bhbleljs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gt2fogsmzjp.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gt2zoywfixn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gt2gmbqyzpp.html

[U18] Py：预编译正则
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bbcaymqb.html

pat = re.compile(r"\d+")
来源：http://dali.haohaochexian.top/Article/details/gt2owqbfejc.html

[U19] Py：正则替换带回调
来源：http://dali.zycfv.cn/Article/details/gt2sragakyp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gotoacloud.top/Article/details/gt2qgofdpqs.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gt2kgouacil.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gt2bjwjosgr.html

[U21] Py：自定义上下文管理器
来源：http://dali.pycfn.com/Article/details/gt2agxvojtc.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2tlwezeto.html

[U22] Py：矩阵转置
来源：http://dali.birdmap.top/Article/details/gt2jrpnzelf.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gt2wkxwiqqm.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwtfxvck.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gt2vmnejudw.html

[U24] Py：路径操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2ixtqobva.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bxqkfqhc.html

[U25] Py：CSV 按字典读
来源：http://dali.cashguo.top/Article/details/gt2ryaeovxk.html

csv.DictReader(f)
来源：http://dali.tian-w.cn/Article/details/gt2jgpwxkjx.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gt2hlbnknow.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gt2cuwxypsw.html

[U27] Py：异步 HTTP
来源：http://dali.ybcxt.top/Article/details/gt2smfutalf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gt2ohxfnbmp.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gt2fxghwbcm.html

UserId = int
来源：http://dali.zhixingplan.top/Article/details/gt2uanjeqnl.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vchcyvqb.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gt2uoqgjmkv.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2jtxmotei.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2yhkgnacx.html

[U31] Py：单测
来源：http://dali.jyoumei.cn/Article/details/gt2oemgdvzw.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gt2yaptznru.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2smsfmwsc.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gt2stszstuj.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gt2itfosuas.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gt2qifngqwh.html

[U34] Py：判断编码
来源：http://dali.nanxuanxn.top/Article/details/gt2npgyunkw.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gt2ymncmckj.html

[U35] Py：发送邮件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ridygcfd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gt2ykypdkce.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2anvfzcxs.html

schedule.every(10).minutes.do(job)
来源：http://dali.meibo888.top/Article/details/gt2eyeyizfg.html

[U37] Py：读写 Excel
来源：http://dali.yuanzhike.top/Article/details/gt2mdjkcznj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gt2gxzkogvh.html

[U38] Py：获取脚本所在目录
来源：http://dali.jiagoushi.top/Article/details/gt2zerhpnwn.html

Path(__file__).resolve().parent
来源：http://dali.aizwys.cn/Article/details/gt2hglrntei.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gt2qvnxwbrs.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gt2rhqbijvh.html

[U40] Py：打印到标准错误
来源：http://dali.gotoacloud.top/Article/details/gt2xexrofpd.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2hgjveqic.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gt2ciegljwf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ydzc1.top/Article/details/gt2upuraded.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gt2ujqmnyyk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gt2hihfhezi.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gt2bbwnalxs.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpkgvxky.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gt2jcotqtjj.html

declare(strict_types=1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwdyrudc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gt2esvmktuu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2sfsawjnj.html

[U46] PHP：可空类型
来源：http://dali.smart0.xyz/Article/details/gt2idftwmkl.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gt2gdnmqxml.html


<!-- 参考信息 -->