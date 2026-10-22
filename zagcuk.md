代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtddjbqhnj.html

[S21] C：字符类别判断
来源：http://dali.fengsongda.top/Article/details/gtgqyklvfa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jlsjyb.cn/Article/details/gtjwfrupim.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gtwhwweypp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtrroucqcc.html

[S23] C：随机数
来源：http://dali.guowangkeji.top/Article/details/gtflaplpdb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtcwijvidd.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gthjsztiuq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtounezpos.html

[S25] C：内存拷贝
来源：http://dali.jqgfzy.top/Article/details/gtpugjpero.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtkdbshqaw.html

[S26] C：内存清零
来源：http://dali.yj20258888.top/Article/details/gtduzglcrs.html

memset(a, 0, sizeof a);
来源：http://dali.xuanzx.com/Article/details/gtactodxel.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gtljcxhthj.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtthygicbc.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtsfydxypg.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtrvcebvdk.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gtkrnewynm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jiagoushi.top/Article/details/gtwshlmerd.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtvwxbgxhe.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gtbheljrpu.html

#define X_H
来源：http://dali.shangyingyoupin.top/Article/details/gtepfklifd.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtbvssxqlg.html

[S31] C++：Hello World
来源：http://dali.nwbrower.top/Article/details/gthnticyab.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtcttwbpmj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hywenlv.cn/Article/details/gtjafucjsg.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtrschbovw.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gtmkofqqyl.html

[S33] C++：vector 增删
来源：http://dali.yj20258888.top/Article/details/gthuzopncr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jyoumei.cn/Article/details/gttvcbkukx.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtpjqnxrwk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gterzvdsiy.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtblcvebvk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtvbyckrkq.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtsstqpynr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gthkwsjqts.html

[S37] C++：set
来源：http://dali.gzhubu.top/Article/details/gtbhpiwczb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqvhoijqr.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtrjcmtxhi.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtemrpfytg.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtfftzyvnu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtgvpxskza.html

[S40] C++：查找元素
来源：http://dali.zhiwuduotai.top/Article/details/gttlcpwyup.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtybmwudfe.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtyhpmccoy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtaigctskn.html

[S42] C++：继承与虚函数
来源：http://dali.yuxming.cn/Article/details/gtrkhgpbhr.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtdvqnyomv.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtnicayxys.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtiursmcix.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtpituhtsi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtfqtancil.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gtgvfwtgbf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtgjyilxxs.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtovqdezax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuxming.cn/Article/details/gtdfifnmqj.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtdzxlrvuk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtzmojbjle.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtvvppitla.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtisuxoegd.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldijcwtu.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gtdlkymyvv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtkmekoorl.html

[S50] C++：格式化数字
来源：http://dali.zhixingplan.top/Article/details/gtxptmrjcr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnqzz.top/Article/details/gttyibfgay.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gtuynxnqje.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtihmyzjvv.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtowdbfect.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtvxbwchpz.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtkquhpbxh.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtoglynahg.html

[S54] C++：异常处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkyhppuh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gtljsmikyx.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gtjdfhrbft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtbadxnudv.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtjpkiyejm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtkbtdukzv.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gtdzweuerx.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gttngxclnc.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtwraitvtc.html

namespace ns { int f() { return 1; } }
来源：http://dali.xziqi.cn/Article/details/gtmnerblsm.html

[S59] C++：静态断言
来源：http://dali.ydzc1.top/Article/details/gtnkyvolmd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtwidbkxfk.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtskukjwmk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtzqjhibtd.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfxtajvsq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtdjumkhqf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtapszmltz.html

[T01] Kotlin：Hello World
来源：http://dali.xinyue.icu/Article/details/gtccbyfivc.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgehzjyms.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gtltedtmxl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtmseuudpx.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtbwcqpnhk.html

"值: $b"
来源：http://dali.wangdashe.top/Article/details/gttrekdwxk.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtvvjvngbs.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtpaonpyuf.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gtbgkkjlyc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtihqymzwc.html

[T06] Kotlin：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtrqbjeetk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gttpuggmji.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtjrokoipk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtobecnjif.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpxkjllh.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtzhtvshbm.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gteuvrwxxp.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gtzbryhyss.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gtfirpjfzb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtmzuplttd.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gttiskbqyx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gtrnlqbsmt.html

[T12] Kotlin：解构声明
来源：http://dali.jlsjyb.cn/Article/details/gtamhoadsq.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtymrtqzpd.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtrvawczkk.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtamiajivi.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtibovtawz.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtymghsgej.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtindjprsm.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtltlsvxue.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gttgbiyjpo.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gtjchipdqo.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtlmjbssiw.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gtmrjlwtno.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtpjvadhpx.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtrbeeumla.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gttelemvgw.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gttswaamkz.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtuqqoquxm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtactdjvly.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtiwjbcvcz.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtcyvjwyiu.html

[T22] Swift：字典
来源：http://dali.fengsongda.top/Article/details/gtuuzoxjgy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtstbtuyap.html

[T23] Swift：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjzuvmoq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtqpyhhvnc.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtwduifugt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gthusositt.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gtcdfpzuvk.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gtwbcetldz.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtyvqarros.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtyjugeula.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtnzxrwjoo.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiiwjcyb.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtrcksuojz.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtoukunyag.html

[T29] Swift：guard 提前返回
来源：http://dali.0kj1m.cn/Article/details/gtbskuygif.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtbidtfwqk.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtsxeztgmv.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtmuofdfwj.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtregxncrc.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtclmzkjny.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxjieegr.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtcxneacqp.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtjndfaesg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtougtcmgc.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtfluxethx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtitcumart.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gthirkrrfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gtducqkttr.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtphficzul.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gtohpgbsuz.html

[T37] Lua：字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtdogkafqh.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtfbvwkocp.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtnfqzeavo.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtlfwqvgmn.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtwzygiwar.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtkzxnouxh.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gtotrtxzev.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtrltyniex.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gthxqsgdlb.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbwakyjq.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gtxudfpmqa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtxxhlvbgn.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtrxoohwdd.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gtztiuvgpg.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gttobqatjb.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtfvytwwbc.html

[T45] Perl：数组遍历
来源：http://dali.hnqzz.top/Article/details/gtfvxkxmop.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtbqmgmkak.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtnjbkkhpl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtuofwbqwm.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkggiwpvj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtbjmxqtdm.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtqllnsfgx.html

$s =~ s/old/new/g;
来源：http://dali.sweek.top/Article/details/gtzfdrvgli.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzxigyhi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtwfnqsrvx.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtdwposogj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtjqhggpay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtdcmqcapq.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzshiaez.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtfqczcflf.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtcjpzkjwd.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtsqoayuyc.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gtvsnhrkza.html

s"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtysbchxjw.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtsgvycnuz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtqkevowxr.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gthiunqezt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gtiwbfeusz.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtiecvppaa.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gtuvkctceu.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtkdgizkil.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gtklzxupub.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtxpcurrut.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtqzelmvrf.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gthzjtqxsn.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtupwumijm.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtiypgkjin.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzopvmpy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwmcjsjdq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gtbizjgndj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtmkjzgoqz.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjpwikmj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtrqykucfe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtekexkfhq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gtfpfitmlk.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gtrphcdome.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtltmnqwsn.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtbnumskgk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guowangkeji.top/Article/details/gtomuehjgv.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufoqwown.html

list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtwgigqyfg.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtzvitjywk.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtxntxvigy.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtjbspsbsz.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtvgwgzsjp.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gtzkwcrkah.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gtvzjcmtal.html

[U09] Py：字典取最大值的键
来源：http://dali.hnxiangtu.top/Article/details/gtcebdblnr.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtgfxrvsbh.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxdyfppa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.mhx1999.top/Article/details/gtfzlrhobr.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gttzcdwtfa.html

(x * 2 for x in arr)
来源：http://dali.sweek.top/Article/details/gtgrrzhdni.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zycfv.cn/Article/details/gtklmuhosp.html

Counter(arr).most_common(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtaiagnyla.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gtuuzulvka.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gtlybbqppg.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gtkyhwrdqy.html

defaultdict(list)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwqwowykt.html

[U15] Py：高精度计时
来源：http://dali.ehwqpu.com/Article/details/gttfjdgbwq.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtcouxvswc.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtojmazqcf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gtpznmxtbr.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtcgcvfsig.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.havefunace.top/Article/details/gtzxjsadwq.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtnbzmzoox.html

pat = re.compile(r"\d+")
来源：http://dali.ivvv.top/Article/details/gtdkdfhiwo.html

[U19] Py：正则替换带回调
来源：http://dali.yonumen.top/Article/details/gtbvtszhga.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtrgnqokmc.html

[U20] Py：缓存函数结果
来源：http://dali.0kj1m.cn/Article/details/gtjgdxshmn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhixingplan.top/Article/details/gtgdpfmxho.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtoaesxujy.html

@contextlib.contextmanager
来源：http://dali.chenlongwang.top/Article/details/gthgfbnqeg.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gtryufzvgz.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtolchguyu.html

[U23] Py：分块读取大文件
来源：http://dali.birdmap.top/Article/details/gtftuaszqg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaegvncvd.html

[U24] Py：路径操作
来源：http://dali.andypj.xyz/Article/details/gtukswrysn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtjzkvrvbr.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gtavvnvtvv.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gtdsldjbxe.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtmqkywvug.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gtbsjjipvp.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkmnxwsk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtixpteaem.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gtimbudrqd.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gtwurcimjp.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtyzlhfptc.html

@property 与 @x.setter 配合
来源：http://dali.shangyingyoupin.top/Article/details/gtzgcojagy.html

[U30] Py：数据类
来源：http://dali.gotoacloud.top/Article/details/gtctxmpuzr.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gtarujgrnk.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gtfmvjjvxm.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gtonqfkkms.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtptzksvma.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gtbkcmuynt.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtmhqdxsoy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.iojbl.cn/Article/details/gturpvyfao.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtysseaypo.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gtsocsyflu.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gtnafuglny.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwmgxqzz.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gttipqqjur.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtojcknujq.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gtcrtvazho.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtddkpjxhi.html

[U38] Py：获取脚本所在目录
来源：http://dali.yanxiufei.cn/Article/details/gtlmywcgdg.html

Path(__file__).resolve().parent
来源：http://dali.jiagoushi.top/Article/details/gtsgmtjjdr.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtxhdtezai.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtslxtzmjy.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gtzkxcfqmw.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtwdjxymrj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gtjzaxgaih.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gtevqrabzv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gtefbumbzc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gtcxyesvar.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtqnnewvzt.html

namespace App\Http;
来源：http://dali.xziqi.cn/Article/details/gtsqeaxedb.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtnelglfqn.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gtrylkumvi.html


<!-- 参考信息 -->