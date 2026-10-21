代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nwbrower.top/Article/details/gtvtngpgxb.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gtgnltvdgs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gteynzijwq.html

[S24] C：获取本地时间
来源：http://dali.yj202588.top/Article/details/gtcchecjri.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtskaedrda.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtspzxtvls.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtewnrinut.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtccygbktl.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gthlvougzv.html

[S27] C：定义常量
来源：http://dali.yj20258.top/Article/details/gtxojmhshe.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtbgavqjir.html

[S28] C：静态变量
来源：http://dali.redwolf501.top/Article/details/gtfxycekfy.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtgxtksjsp.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtuckmejtu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtrxozgrqc.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtdkiaetfd.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtbgnaudag.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gthifsjmvo.html

#endif
来源：http://dali.shanyushiyangtech.top/Article/details/gtreckitgd.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gttitophyo.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gtzmasropl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gtjmepgmsu.html

[S32] C++：字符串
来源：http://dali.bjfxy.top/Article/details/gtxbxslnzw.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtjakzbbub.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gtnrzcotzc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cheryme.top/Article/details/gtlrrkucps.html

[S34] C++：遍历 vector
来源：http://dali.ybcxt.top/Article/details/gtcnlnbnxz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtqypxepao.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtiybahaeg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtfqhvdovi.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gtpxitxfaq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtsjoddxvs.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtrsklgmnx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtibsmcmra.html

[S38] C++：排序
来源：http://dali.jlsjyb.cn/Article/details/gtnkfyyjkd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtsqcebtif.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtivcciord.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gtnarqqjpp.html

[S40] C++：查找元素
来源：http://dali.hnqzz.top/Article/details/gthfoedvhp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtgtjkqdfe.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtdfzdgsvp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sweek.top/Article/details/gtubdqzigy.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttntqmbra.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtgnklpcjs.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtlajkjxbv.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtjxqgrsjm.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtcdlqlzpr.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyhuqwhfu.html

[S45] C++：lambda
来源：http://dali.zhixingplan.top/Article/details/gthufahlcl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtbnrnbkvt.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gturxgljll.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yangfankeji.com/Article/details/gtlxorgnww.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtcdncauhq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcmuhfctr.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtqkwgbwum.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.daria6918.cn/Article/details/gttnxhspnx.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gtlhshiful.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtrovzaoqi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtprsyyujb.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gtyekyvozp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtdkfzuede.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gttcjprsrz.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtzwurtxrn.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtsbvlhfcb.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnvpzctma.html

[S53] C++：移动语义
来源：http://dali.gogol.net.cn/Article/details/gtvzguxyif.html

std::vector<int> w = std::move(v);
来源：http://dali.wangdashe.top/Article/details/gtgxweftwx.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtubjewhrx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtzpfgqxre.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtmaowqpql.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtaldiftok.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlavlbzs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtynvjhkxk.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gthsrembln.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrwblavt.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtstsavuvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtgghctigf.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtuwfqwxmr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtiyxhhsjj.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtmaqkixjy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtwgzseuqx.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtiikhmajl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtjbhsphwx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtohwextxj.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtsptjbqzy.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtnrdjdykp.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxbjifuxw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fengsongda.top/Article/details/gtxgmgpira.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtrfqxyvev.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtgslcptwr.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtdwqqmhsb.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtgfejamqd.html

[T05] Kotlin：when 表达式
来源：http://dali.jinqigfzy.top/Article/details/gtypevlosq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gthyvhwejs.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtdttlblkl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtvllfwxaq.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtlmjofgoi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtxgjdqzvk.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gtnmsvzbup.html

data class User(val name: String, val age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtuvhwfskt.html

[T09] Kotlin：扩展函数
来源：http://dali.xinyue.icu/Article/details/gtlwesksld.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtxqmwdtas.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtzkmlappv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtjrdbjokq.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtlmrrowfn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtbcnoqcaz.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrmkgezy.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gthhdulidm.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtegnrbuay.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gtytsicixg.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtgitqalxv.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtmvinlcuu.html

[T15] Kotlin：接口
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbixxebsg.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gtbehcfoyx.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtfmszfgqi.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtxexwlylu.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtbuagcayy.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtakbgjunw.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwaxjnnm.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtfjftjdmj.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtpsdutkwr.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtlinjxpmu.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtvetmvaob.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nwbrower.top/Article/details/gtuesdfhvm.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtmrwwwlqt.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gtvanxdelq.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gtyrvozgke.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtgwhxneeh.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtkqzvkjip.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkiclzbh.html

[T24] Swift：闭包
来源：http://dali.zhongyouzk.top/Article/details/gtfbjzyqgr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgflwfwgj.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtdfouauuz.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gteddczwhx.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gtfqlcbequ.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtqsfpaytd.html

[T27] Swift：错误处理
来源：http://dali.meibo888.top/Article/details/gtbjrokbbz.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtckogoesk.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gtzomthnnj.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtvairsiay.html

[T29] Swift：guard 提前返回
来源：http://dali.cucudq.cn/Article/details/gtazfjckgl.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gtxtfmoskv.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gttzlknolo.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gtostcbufd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtpohyiyef.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtmhfbohkt.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtklhhijwl.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtmyxxpzcw.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcdhkjml.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gtpckibzcf.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtugoglewj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gthwtknmqv.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gtqkevslku.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aibaodan.cn/Article/details/gtffhdixpv.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gtltqjuzql.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gtrxsujlxg.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtwpyrvunh.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtznfvgbjq.html

[T38] Lua：条件
来源：http://dali.aibaodan.cn/Article/details/gthcwqxper.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtinkhjcsv.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtndwtirpp.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gtbzdqrqed.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gtvktdjpxg.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gtsqtpsdse.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtlrhunnlz.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliqfirmm.html

[T42] Perl：变量类型
来源：http://dali.vqdsnc.cn/Article/details/gtgucuhjmt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenlongwang.top/Article/details/gtafzxrlix.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtcuwwkqle.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtynzaiipk.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtovulyivq.html

if ($a > 0) { print "正"; }
来源：http://dali.haohaochexian.top/Article/details/gtxonglmiu.html

[T45] Perl：数组遍历
来源：http://dali.aizwys.cn/Article/details/gtcniuezwz.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtszahnlzi.html

[T46] Perl：哈希操作
来源：http://dali.gzhubu.top/Article/details/gtrnmturyd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gteygbyaig.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gtrqtmojye.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yangfankeji.com/Article/details/gtxvrqmurw.html

[T48] Perl：正则替换
来源：http://dali.sufxvd.cn/Article/details/gtimyebcof.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtipqqtoec.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gtyptsuqax.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtaqsktrrf.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtslqvvckk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtejdqwiec.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gtexrmuwjh.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtpzodnucf.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtsxaitjxu.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtjcovavks.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtlpllkvbv.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtoafedqvi.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gtatjjzmwh.html

[T54] Scala：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtsvthzuuy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gtzytlvpbp.html

[T55] Scala：集合过滤
来源：http://dali.iojbl.cn/Article/details/gtufbptuvh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gtbcypxtjf.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtiytjthtk.html

case class User(name: String, age: Int)
来源：http://dali.iojbl.cn/Article/details/gtattocipd.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtnrbwsnxq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtmyhlzcui.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gtwsghrfev.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gtqgwpcear.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtbydzuokq.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtphdxmiiu.html

[T60] Scala：折叠
来源：http://dali.zhengqikj.top/Article/details/gtyvluposj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjphqohs.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtdehywebj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtbwaloyer.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyyeshzb.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtwhfwkqld.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdycyjsek.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtyldjrupt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtjykveyyp.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gtqgwpuhqs.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtochjbqpq.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtdghwyowe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtfxgozxfs.html

[U05] Py：列表去重且保序
来源：http://dali.shuidangran.top/Article/details/gtbtmkplfb.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtlrnjlbbs.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtmojcdzmr.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gtqijbcgfk.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtqezburag.html

{v: k for k, v in d.items()}
来源：http://dali.kuanghao11.cn/Article/details/gtzpuhtudb.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtwwffxshc.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtclehytjw.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gtgycwyzda.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gtkduemiow.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gtchvpaydo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nwbrower.top/Article/details/gthzbsbhxl.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtgakedycj.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gtefgtugsd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtzbooozii.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gtsrnxurqh.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gttlbrdger.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtpuklkzeb.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gtmccqisvh.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gtebqayjcz.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gtsxtmodss.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gtuffrjufk.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtokleqdkz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gtpoohjknp.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtwszkoyef.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gtmxogjojw.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gtwlfedqpe.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtbnybpniy.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gtnykucyog.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtymaniket.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtmwjycevb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.kuanghao11.cn/Article/details/gtunmtyioa.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtshbxjtra.html

@contextlib.contextmanager
来源：http://dali.9152youxi.cn/Article/details/gtvxhznndi.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gtkiuneahc.html

list(zip(*m))
来源：http://dali.gaohongyu789.top/Article/details/gtgjrpafyv.html

[U23] Py：分块读取大文件
来源：http://dali.hysaishi.cn/Article/details/gtobjksbqz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gtvgeuavmf.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtsunuyrps.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhoulong.xyz/Article/details/gtwzdlxayh.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtcatdlrdl.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtuncbzktg.html

[U26] Py：并发下载
来源：http://dali.9152youxi.cn/Article/details/gtbcmooywl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.svipenyu.cn/Article/details/gtvjovytln.html

[U27] Py：异步 HTTP
来源：http://dali.daxiang520.top/Article/details/gtwgjxqyjp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtxvidghnp.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtvrczrzxj.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gttgicbvzq.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtjavetioi.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtcpdcmubf.html

[U30] Py：数据类
来源：http://dali.yueranfly.top/Article/details/gtpnmarlqd.html

@dataclass(slots=True)
来源：http://dali.fzhhl.top/Article/details/gtbupdgiwx.html

[U31] Py：单测
来源：http://dali.yuanzhike.top/Article/details/gtrjbktmoo.html

python -m pytest -q
来源：http://dali.9152youxi.cn/Article/details/gtxgvfbxsg.html

[U32] Py：代码格式化
来源：http://dali.chenlongwang.top/Article/details/gtsoticyxn.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gtnviaigee.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtjkiwursm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gtkcxxdsgp.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gttmndfskl.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gtnnttwzao.html

[U35] Py：发送邮件
来源：http://dali.zhixingplan.top/Article/details/gthpycnczq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gtqfvwgkxd.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gtxrkylzqo.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtbzjtoaie.html

[U37] Py：读写 Excel
来源：http://dali.chenjidiqi.icu/Article/details/gtuvipbhhl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtwccfhhmk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zycfv.cn/Article/details/gtdidtwkhz.html

Path(__file__).resolve().parent
来源：http://dali.redwolf501.top/Article/details/gtjiqgtirq.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtftivvtfo.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gthffovvim.html

[U40] Py：打印到标准错误
来源：http://dali.andypj.xyz/Article/details/gtfaudcmsd.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtyjdsjbod.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gtmtivbisb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gthehnehel.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoydhqkxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxinkj.top/Article/details/gtikqtkecm.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gtwtyuigpt.html

namespace App\Http;
来源：http://dali.jianghu66.top/Article/details/gtdwfzkbfn.html

[U44] PHP：开启严格类型
来源：http://dali.jqgufenzy.top/Article/details/gtrjfizdxr.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gtieqlrbsd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sysykeji.top/Article/details/gttjorfezi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtbxzinzva.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtntzkwxgv.html

?string $name = null
来源：http://dali.zdqjudy.top/Article/details/gtmahrpamo.html


<!-- 参考信息 -->