代发 wailian999

static int counter = 0;
来源：http://dali.birdmap.top/Article/details/gt2yhjttmcr.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gt2tlpftduh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gt2oxyxlhfx.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gt2symsgffz.html

#ifndef X_H
来源：http://dali.yonumen.top/Article/details/gt2diyusnjn.html

#define X_H
来源：http://dali.sweek.top/Article/details/gt2plrikcub.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gt2sckljnbx.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gt2aekpeaxk.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bbmsgnes.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ocqdrucv.html

[S32] C++：字符串
来源：http://dali.hfpthk.cn/Article/details/gt2ntpbgkfp.html

std::string s = "hi";  s += "!";
来源：http://dali.zhixingplan.top/Article/details/gt2qywflmep.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnfiuoxb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gt2jnrscetm.html

[S34] C++：遍历 vector
来源：http://dali.aibaodan.cn/Article/details/gt2bepcwsbx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cheryme.top/Article/details/gt2bmyivbuv.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gt2irgkiugp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.0kj1m.cn/Article/details/gt2pzpxhoox.html

[S36] C++：unordered_map
来源：http://dali.svipenyu.cn/Article/details/gt2sakoewer.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gt2idtnkmvt.html

[S37] C++：set
来源：http://dali.yj202588.top/Article/details/gt2bemhubup.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hysaishi.cn/Article/details/gt2uehkgdeb.html

[S38] C++：排序
来源：http://dali.yj20258888.top/Article/details/gt2cbvxmgld.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gt2mblgcjiq.html

[S39] C++：自定义比较器排序
来源：http://dali.shzxlz.cn/Article/details/gt2qlvjdcxx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gt2erpwvcrl.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gt2krnvodeq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cqqwz.cn/Article/details/gt2bfcvxwmf.html

[S41] C++：类与构造函数
来源：http://dali.daria6918.cn/Article/details/gt2bgpemmju.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gt2agthscgw.html

[S42] C++：继承与虚函数
来源：http://dali.cheryme.top/Article/details/gt2zustiare.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2ycwmhdgy.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gt2keuejhhc.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gt2fckqivrg.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gt2ntgktklb.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gt2tansibop.html

[S45] C++：lambda
来源：http://dali.iojbl.cn/Article/details/gt2jivkpaqa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2ilcedhbk.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gt2wwwhxwof.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xylfe.cn/Article/details/gt2ikzcstfm.html

[S47] C++：结构化绑定遍历
来源：http://dali.hywenlv.cn/Article/details/gt2lrmicdda.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gt2ivgklgmw.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2rvboudvm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gt2aihvvbgr.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gt2nscsvsxf.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gt2zqtvjxrv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gt2mkkintla.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gt2qmbksbqg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yonumen.top/Article/details/gt2sczamowu.html

[S51] C++：显式类型转换
来源：http://dali.xinyue.icu/Article/details/gt2keunfmim.html

static_cast<double>(a) / b
来源：http://dali.zhoulong.xyz/Article/details/gt2fvrgatqy.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gt2dmpcxyqe.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qrwdrdzw.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gt2tflbgqfj.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gt2wpvpzweg.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gt2oyyenvum.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gt2edeldnwv.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gt2qycfpobr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2inpwzpjd.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gt2ucospzqv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gt2pfouqwki.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gt2sxbalasz.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gt2kflzbgwl.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvyeynl.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gt2vhelhyeh.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2gnxachrf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gt2ahpcdxjr.html

[S60] C++：遍历并删除元素
来源：http://dali.ybcxt.top/Article/details/gt2ygadyxta.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gt2qjefcjjd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2xsvlgxvc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2yspswutz.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2dhhanvnx.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2iacnxabm.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2oeuwymuw.html

[T02] Kotlin：变量
来源：http://dali.cdnleiting.top/Article/details/gt2xvsyapdk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gt2dqrgysip.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gt2frsanhho.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gt2poqfdcza.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gt2rjupntnk.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2rzxnsvgo.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2untrxeee.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gt2rxqcjnqi.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2wnohbnpk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gt2dgsojmlx.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2eqefmogx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pycfn.com/Article/details/gt2wpjfqvay.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gt2tkkpfxqh.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2oumrgmip.html

[T09] Kotlin：扩展函数
来源：http://dali.vqdsnc.cn/Article/details/gt2dtleisqd.html

fun String.exclaim() = this + "!"
来源：http://dali.cqqwz.cn/Article/details/gt2pwapvasz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcxoanc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2dczgdbdc.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gt2swnjrotz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2isgxrpcs.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2etasvsgc.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gt2nmdeppkc.html

[T13] Kotlin：只读 Map
来源：http://dali.dashuyun.cn/Article/details/gt2yifcljfn.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gt2doxvghpq.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlblhpuo.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2wmmjmjte.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gt2akuunvvx.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gt2smoitgzk.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2vzcbetwp.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gt2cjvwoqhf.html

[T17] Swift：变量与常量
来源：http://dali.gzhubu.top/Article/details/gt2tylhvuar.html

var a = 1;  let b = 2
来源：http://dali.redwolf501.top/Article/details/gt2gazmvwqu.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2ahkdstlz.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gt2ychzesrw.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gt2rbimrmot.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gt2hluiqcxx.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gt2zmvdfbcj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rthegrlk.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gt2zdvlpxmn.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2xvzinmwm.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gt2fspdrzdy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvoniltd.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2lbwluoxd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tian-w.cn/Article/details/gt2jynbhart.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gt2iuoicqai.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2nsvsjqfa.html

[T25] Swift：结构体
来源：http://dali.yuanzhike.top/Article/details/gt2hmwgaxgp.html

struct P { var x: Int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vtwavehp.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gt2bpafpqjm.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2nmrfzght.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2fhbtcsnb.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2atkiykie.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2ytxgfamb.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gt2jjkteahw.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gt2sbwlggwb.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2madnknwc.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gt2dhawglpc.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gt2elpxnsjt.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2uijpaelq.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2crpcamcl.html

[T32] Lua：局部变量
来源：http://dali.nanxinkj.top/Article/details/gt2liplmzbs.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2oavschcb.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gt2noxxlogs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gt2vabcwqdn.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gt2ndcxkhnf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.quarkkingdee.top/Article/details/gt2rdbnwqxw.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnshsthh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gt2nqgvcxsd.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gt2jtdyqrst.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gt2gfjkbtgq.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2havdcbdl.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gt2iiojcmqv.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gt2lxtcmmho.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gt2yveotcpn.html

[T39] Lua：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gt2yfimrcen.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gt2jzyvttwa.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gt2pdhkkxtr.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gt2wuvmflxj.html

[T41] Perl：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2ntrxcswo.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gt2nlgqxxqb.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gt2kakoniom.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gt2fbzjksnt.html

[T43] Perl：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnqnaxjx.html

"值: $a"
来源：http://dali.jinqigufen.top/Article/details/gt2tznbiuwn.html

[T44] Perl：条件
来源：http://dali.cdnleiting.top/Article/details/gt2xajxnrzv.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2voatodwy.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hofncymk.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gt2ahagkeqy.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gt2rhzvzqux.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gt2ixywcnub.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gt2fcnmdhxg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gt2wtzjgkee.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gt2vsfjwxac.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gt2qianfeic.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2svplpkkf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2bevxxsaf.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2cqtifxlk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinqigufen.top/Article/details/gt2wztladpr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnqzz.top/Article/details/gt2qbwqskrf.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2xvxswbha.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gt2ewtufksp.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gt2ybrqfzcw.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2ktrtfuzv.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2nfvsrscp.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2pukzurlx.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gt2opggveqg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2trmumcuv.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwmqcwbq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.andypj.xyz/Article/details/gt2jkxjkifw.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gt2lbyiodiz.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gt2qyrlshcv.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gt2djckvght.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gt2zmzxjtln.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gt2ktyrabrn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gt2bintkgog.html

[T59] Scala：循环
来源：http://dali.cqqwz.cn/Article/details/gt2jjaszeew.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bxwmhuiy.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gt2inlpahjl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2emjqhzoz.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2adcfomhb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gt2hzqutnsa.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2yeiiwggq.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2sywyjdtz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gt2pzgtgiuz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gt2bnlrkgst.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gt2hmlmkykb.html

[U03] Py：加载 .env 配置
来源：http://dali.hysaishi.cn/Article/details/gt2cuhxmmcs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gt2akexokpg.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gt2wriqdyiu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cqqwz.cn/Article/details/gt2qbsfskvf.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gt2eufcyxzc.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gt2iwfebxqi.html

[U06] Py：合并两个字典
来源：http://dali.sxryk.cn/Article/details/gt2wvyrccql.html

{**a, **b}
来源：http://dali.9152youxi.cn/Article/details/gt2bxdwodwh.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gt2irxzxwoh.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gt2rxouoroo.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpdcxekw.html

[y for x in nested for y in x]
来源：http://dali.ehwqpu.com/Article/details/gt2nuvqsytf.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gt2nlfuveij.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gt2fywxrmfc.html

[U10] Py：按值排序字典
来源：http://dali.wangdashe.top/Article/details/gt2ohsirpfu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gt2tixqyfuc.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2pdkyhmth.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gt2hplvkzwl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gt2dfdsxojm.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjdwsznh.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gt2izxjscod.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gt2rebikigu.html

[U14] Py：分组收集到列表
来源：http://dali.zhongyouzk.top/Article/details/gt2zzmolzqn.html

defaultdict(list)
来源：http://dali.ehwqpu.com/Article/details/gt2ureunsdr.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gt2lmhcjazh.html

t = time.perf_counter()
来源：http://dali.gogol.net.cn/Article/details/gt2rjjilfaz.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gt2djswjeqy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gt2tnatkixi.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gt2bgieoiuk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gt2lnzuptpv.html

[U18] Py：预编译正则
来源：http://dali.ivvv.top/Article/details/gt2ooiyozwd.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gt2jddapahf.html

[U19] Py：正则替换带回调
来源：http://dali.jianghu66.top/Article/details/gt2ckzleovf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aizwys.cn/Article/details/gt2xgkkfqoq.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2sdyvbngf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gt2kllqmara.html

[U21] Py：自定义上下文管理器
来源：http://dali.vqdsnc.cn/Article/details/gt2tamtvjbl.html

@contextlib.contextmanager
来源：http://dali.yuanzhike.top/Article/details/gt2nnshkkqx.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gt2yefgrlvr.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngorcsum.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gt2ombydccl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gt2nelguyry.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxovbste.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gt2nlkwwfkx.html

[U25] Py：CSV 按字典读
来源：http://dali.xziqi.cn/Article/details/gt2qcehulkq.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gt2xfoaoojy.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrmhabui.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2mwhazgtc.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gt2xkhlhprj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gt2eesxcnqz.html

[U28] Py：类型别名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qauklokp.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gt2cryqcuwb.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gt2rmdxnwwh.html

@property 与 @x.setter 配合
来源：http://dali.jqgfzy.top/Article/details/gt2skuqjkyn.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gt2znsrxmsh.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gt2mocxpfws.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gt2cmjmyrqb.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gt2xfziknxn.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gt2fcqghsle.html

ruff format . && ruff check --fix .
来源：http://dali.cashguo.top/Article/details/gt2xjmdndfx.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gt2vutmqyig.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gt2lmxfwvbo.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gt2mimsxzuw.html

chardet.detect(raw)
来源：http://dali.xinyue.icu/Article/details/gt2jvokeoqa.html

[U35] Py：发送邮件
来源：http://dali.yueranfly.top/Article/details/gt2ydcmesdc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gt2kowkoird.html

[U36] Py：定时任务
来源：http://dali.hfpthk.cn/Article/details/gt2osffaeeo.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2noggpwje.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gt2ayzfsxqr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gt2kaxuswtt.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gt2wjauqamf.html

Path(__file__).resolve().parent
来源：http://dali.tianlin.xyz/Article/details/gt2zxvqdmry.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gt2mjmyfepq.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gt2gpoldkum.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gt2swbkqkjo.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2rkcrdjlm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gt2imqddoxt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gt2oviqyxdf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.havefunace.top/Article/details/gt2fvhthdvw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gt2ldevgmtd.html

[U43] PHP：声明命名空间
来源：http://dali.andypj.xyz/Article/details/gt2wqalthff.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gt2oneqhxzv.html

[U44] PHP：开启严格类型
来源：http://dali.cashguo.top/Article/details/gt2qkmtpzqp.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gt2jhfocqhx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gt2fftipdit.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2pdrargfe.html

[U46] PHP：可空类型
来源：http://dali.pycfn.com/Article/details/gt2yvztizox.html

?string $name = null
来源：http://dali.feifeiyinyue.top/Article/details/gt2olmvqclm.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gt2wwoirqwr.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gt2rsogeucv.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gt2wwhvglfd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2fjkppnpx.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2guwvefhp.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gt2aujreoya.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gt2itmeencm.html

public function __construct(private int $id) {}
来源：http://dali.haohaochexian.top/Article/details/gt2oazxxjlz.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gt2ycbpwdfr.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gt2zampbfhr.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2arqzwagb.html

$double = fn($x) => $x * 2;
来源：http://dali.cqqwz.cn/Article/details/gt2rrjosbsm.html


<!-- 参考信息 -->