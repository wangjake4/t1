代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yvedp.cn/Article/details/gtrigfvgqh.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtchteuhkg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jqgufenzy.top/Article/details/gtbxmhtliy.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtsjezqzae.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtkncesred.html

[S25] C：内存拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxslxtnz.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gtgvgcjkfp.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gttzcwngle.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtnioprown.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gtcwsdgdtu.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gttdgaezvz.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtcugbhyfz.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtyfztjjqk.html

[S29] C：变参函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdiurzflo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtwninuuqs.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtefkwqozr.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gtyykamqnh.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtpbssdglu.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtgptbjaxj.html

[S31] C++：Hello World
来源：http://dali.shuidangran.top/Article/details/gtjhyctnaf.html

#include <iostream>
来源：http://dali.nwbrower.top/Article/details/gtnpqowzet.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtczbtdvla.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtxwbyyiik.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtsnioxhbv.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtfzfffgpa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtkhttdhep.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gtspxsvuvg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtdhhbkson.html

[S35] C++：map
来源：http://dali.nanxuanxn.top/Article/details/gtedsvuyht.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtbygpfnyp.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtqpdryhht.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtezskxlhz.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtaaxhumbr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtceselgie.html

[S38] C++：排序
来源：http://dali.aizwys.cn/Article/details/gtncphtfqo.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtbburyokz.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtrazlizhm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.feifeiyinyue.top/Article/details/gtfevlzign.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gtemrlzabh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aibaodan.cn/Article/details/gtzbmchqhr.html

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gticmyislk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtkloabfoa.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtxwcmqkyv.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgfzy.top/Article/details/gtoyaushxi.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtmozjmaeu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtwqnevtlf.html

[S44] C++：引用传参
来源：http://dali.c1oappe.top/Article/details/gtwmpgyqlm.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gtkknacuvf.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gtsshtkpwc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtddhtxeln.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibzjtbor.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqayhcfzv.html

[S47] C++：结构化绑定遍历
来源：http://dali.sxryk.cn/Article/details/gtwcqklhei.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtylyodovc.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtvikdbbld.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtaxwaogyt.html

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtgvtdyvza.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtabaxhqfk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtkvblfozj.html

[S50] C++：格式化数字
来源：http://dali.guowangkeji.top/Article/details/gtgkxneplc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtbnjppgaw.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtehxcvfmt.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtqygpazob.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtwcktphdo.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtbshipgwn.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtzqdoretn.html

std::vector<int> w = std::move(v);
来源：http://dali.cucudq.cn/Article/details/gtmdjvklwq.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtzkhnhsau.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gtzspfkkbm.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gtefedohpf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtammtvykn.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtqskenqdl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gzhubu.top/Article/details/gthojqiunj.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtvcqgjoog.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtktcpiese.html

[S58] C++：命名空间
来源：http://dali.redwolf501.top/Article/details/gtyvvyjuov.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtspxqyewg.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtkabyjsqp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gtxvrrntjr.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtcjdeyyct.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtndshuvxv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuibsqzbd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtkeeytnel.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcifhhjrk.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdaffpll.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtuzpefkji.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtbrkqjqmi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtrrtwabts.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtqojyozdr.html

"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpkthyvc.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtbixbmxfv.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtgctuytvh.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtqnoipajv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tanke756.top/Article/details/gtzhykezjd.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtemfblnli.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtoqwocbqv.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtjkjesoox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gtqwikuekt.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gteugczypd.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gtclicawpu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtbdaifdqr.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtwnvysdri.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtcrawmvhg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtsauljvok.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtchmqqawc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tianlin.xyz/Article/details/gthwcirqwz.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtynmjeybm.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtwhwqakfj.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gtdalfcgjp.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258.top/Article/details/gtubcaugcu.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtxfxpiowd.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtdbpzlefj.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtyolucwdq.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtljuumbpi.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtaocuhsgl.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtmlexhgmf.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtctriafrr.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtxnkbyrtu.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtlxcnzjss.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtrbyyfioe.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtybdutyfu.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtsvmrlybi.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtubbrktcd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtgmuvkcqd.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtzpxqxxcd.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtfzysqutd.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtxmgqvbof.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gtcbezmoyf.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtlcddpxll.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtiuyqksfs.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtlhkwhohh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxjhakqx.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gtixabcfmr.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtssvnftig.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtyyapnylz.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtxvibjkrg.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtwpajfrut.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtorzmpoqe.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtpcmugoxi.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtmhkxfqfm.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvazmrwj.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtzhbaeocl.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gtzdhuebdw.html

protocol Shape { func area() -> Double }
来源：http://dali.ybcxt.top/Article/details/gtlrsxagrz.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtpezmwext.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtxdgeeutu.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtzlvrkwmi.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtfdcbgsix.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtwhlfppkr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgsggvnh.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtbcrvcyvt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtaazajnyb.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtheejfgvj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtrplcgmqt.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtkcibscad.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtafzevqia.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtlbiwphrl.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gttrkljosg.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwbncnpi.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtkrzvarrx.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtfimzjijb.html

string.find(s, "%d+")
来源：http://dali.kuanghao11.cn/Article/details/gtritympnx.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtbxkmzyhp.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258.top/Article/details/gtxonhisea.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtyemdyver.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtdzwjajfz.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gttdickxph.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gtddutafcw.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtfgfwmqzt.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtotsuhvdc.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtqywoiipq.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gthuqdwjja.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtysrfaaqj.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gttzgwxmbi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtaelwukgq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtlkhnayvn.html

[T47] Perl：正则捕获
来源：http://dali.bjfxy.top/Article/details/gttrtfneqy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtjsvxjhbf.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtpvbevlqx.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gtuakeknoi.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtwkkmowik.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtdzbdcbqs.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtyjftiagc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtvtkytvmk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gtgfpspair.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtvozlmamn.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtqolunzvy.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtschqsmpf.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtfyuujtor.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gthytdhmxu.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnawzstaw.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtcrgdbreo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtsqsqxkkf.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtugtlawic.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gthflzjedj.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gtpjedobqj.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtrihsdlba.html

[T57] Scala：模式匹配
来源：http://dali.guowangkeji.top/Article/details/gtswbkwgte.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gtsrejdrzx.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gtvpapoxmj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtzzxuwhcx.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gthryexkse.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtqqdbormh.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtronzresm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gtjiybwzvq.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtqzfhjzqx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtxlezueno.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtijaffrbm.html

[U01] Py：创建虚拟环境
来源：http://dali.smart0.xyz/Article/details/gtkshsdskn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtemnjyzqd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtlikkkuzx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jiagoushi.top/Article/details/gtebalgatf.html

[U03] Py：加载 .env 配置
来源：http://dali.ydzc1.top/Article/details/gtyvhmnfok.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nwbrower.top/Article/details/gtptsahwjv.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gturbrifxo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsgqipte.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gtvblepbjr.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcljokjxg.html

[U06] Py：合并两个字典
来源：http://dali.snrcjt.cn/Article/details/gttffidfhv.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtxzuoqpod.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gtufpxnnjw.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtfzntmlza.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gthlcpefmt.html

[y for x in nested for y in x]
来源：http://dali.jinqigufen.top/Article/details/gtlpoynlnx.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtakkgtncl.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gthkkjqvxc.html

[U10] Py：按值排序字典
来源：http://dali.iojbl.cn/Article/details/gtfxwuombq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hammf.cn/Article/details/gtfddmthtk.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtokvpieqd.html

(x * 2 for x in arr)
来源：http://dali.yuxming.cn/Article/details/gtbnqwnuur.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangshuangyany.cn/Article/details/gtcjhhiola.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtoeiopbet.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtyyvqumdg.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtunozkexj.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtrevdzvsy.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gtdiffpflp.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtorrvlqru.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gtvrasukqm.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtsiqlslhy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shangyingyoupin.top/Article/details/gthacacjfq.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gtkctfqwdz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.redwolf501.top/Article/details/gtlzzndjsv.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtopnmqmng.html

pat = re.compile(r"\d+")
来源：http://dali.smart0.xyz/Article/details/gtumibwyrl.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtqbncfkhk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ehwqpu.com/Article/details/gtkesfoplo.html

[U20] Py：缓存函数结果
来源：http://dali.jlsjyb.cn/Article/details/gtdukgydti.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xylfe.cn/Article/details/gttufsmyku.html

[U21] Py：自定义上下文管理器
来源：http://dali.shuidangran.top/Article/details/gtkvydbrgk.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gtcxnyujnz.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtslgkkevc.html

list(zip(*m))
来源：http://dali.yj20258.top/Article/details/gtzstrjjvq.html

[U23] Py：分块读取大文件
来源：http://dali.hnqzz.top/Article/details/gtxfpxscvi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtwkrnighv.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtftikaonb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gtxkoematt.html

[U25] Py：CSV 按字典读
来源：http://dali.feifeiyinyue.top/Article/details/gtirtgeioj.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfpsthik.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gtabahjbay.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtmtevrpil.html

[U27] Py：异步 HTTP
来源：http://dali.birdmap.top/Article/details/gtppzzarsp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtargvfalc.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gtlxklcyvn.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gtghwkwhsg.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtwxfevxiw.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gtmzlwfwum.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gtqrbpvozm.html

@dataclass(slots=True)
来源：http://dali.jinqigfzy.top/Article/details/gtdrcvahrt.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gtgkazhavy.html

python -m pytest -q
来源：http://dali.c1oappe.top/Article/details/gtpqphzmkp.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gtdpueyxee.html

ruff format . && ruff check --fix .
来源：http://dali.9152youxi.cn/Article/details/gtxnhdegey.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtfykxycqr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtcpslzzgy.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtepmrhrrb.html

chardet.detect(raw)
来源：http://dali.ybcxt.top/Article/details/gtbiocqihi.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gtzajxkolt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gtwdagillm.html

[U36] Py：定时任务
来源：http://dali.iojbl.cn/Article/details/gtsbkmyzpo.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gtjkioiuhi.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gtvukdpiyd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aibaodan.cn/Article/details/gtuwbtvcyh.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gtwqrsgdrt.html

Path(__file__).resolve().parent
来源：http://dali.hysaishi.cn/Article/details/gthjecceqm.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gtladlogah.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gtmprvjoub.html

[U40] Py：打印到标准错误
来源：http://dali.cashguo.top/Article/details/gtjduaukon.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtsxofbyub.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhongyouzk.top/Article/details/gtxtpkphhi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guowangkeji.top/Article/details/gtzjfauqte.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sufxvd.cn/Article/details/gtveikrloe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jyoumei.cn/Article/details/gtiituyobb.html

[U43] PHP：声明命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtyhctbcrd.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gtnevnbqkb.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtkcwptsop.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gtdaurtskv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gtunrndkos.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gthrzjscip.html

[U46] PHP：可空类型
来源：http://dali.feifeiyinyue.top/Article/details/gtwaegavsq.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gttuzdvshx.html


<!-- 参考信息 -->