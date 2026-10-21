代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtmjtpdyxd.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtqogfqujs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gthdneposk.html

[S22] C：字符串转数字
来源：http://dali.hammf.cn/Article/details/gtpouzlxto.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gthxnauzwg.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gttlvnensd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtbxagafvo.html

[S24] C：获取本地时间
来源：http://dali.quarkkingdee.top/Article/details/gtjjplwwtt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtylglsxqa.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtrrgfiykp.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtqarqfpeo.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtxvphwmzu.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtqzaxaqnd.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gteozypwfk.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtfqqvgtkm.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtplmhhbff.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtqkvgagev.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gtefiqirsv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gttqemqxbv.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtqruceuhe.html

#ifndef X_H
来源：http://dali.jinqigfzy.top/Article/details/gtdcyrfuel.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtcbmwyovh.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweyofupw.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gtjlgpamru.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtoxjlbjjl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtwhldymda.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gticuijwwb.html

std::string s = "hi";  s += "!";
来源：http://dali.xylfe.cn/Article/details/gtqtimqotf.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkrjioebg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigfzy.top/Article/details/gtbtsfoatw.html

[S34] C++：遍历 vector
来源：http://dali.jyoumei.cn/Article/details/gtaaiunwol.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtjipokpec.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtyqsjsnga.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnxiangtu.top/Article/details/gtnxjmxjov.html

[S36] C++：unordered_map
来源：http://dali.vqdsnc.cn/Article/details/gtjjamstkm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtlsydkziy.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtuuiqiuvr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtecrwhkfn.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtqsamxjaj.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtlhcomlom.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtismogkkk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtghmlkuuc.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gtcjkzneyk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtsbztjzuh.html

[S41] C++：类与构造函数
来源：http://dali.havefunace.top/Article/details/gtmeyfdbqz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuetiantiany.cn/Article/details/gtbwayqcdh.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gteokmshfy.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtrlypgqcw.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtqbukrjvo.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtnfydxrqq.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtgokcbfuf.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtlyqunojn.html

[S45] C++：lambda
来源：http://dali.mhx1999.top/Article/details/gtlkmipeuw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtiibjitmu.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtqhleyjtb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtyrqpgunm.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gticeiivsu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtkfpbgbqs.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtazpbfxxq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.mhx1999.top/Article/details/gtomgbhpwq.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtzyeeymjp.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtwhynqlmd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gtglrwpiif.html

[S50] C++：格式化数字
来源：http://dali.shangyingyoupin.top/Article/details/gtvczrwwia.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtytfgngql.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gttbptqbbj.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtsybksofe.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gtalccruhz.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtnhlxrsbh.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtcbhkjcjh.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsnjmaum.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gtwzlsznuz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hfpthk.cn/Article/details/gtihnetsjv.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gttbrxrxso.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtmbmkkfrf.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtzhzomtab.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjreujwug.html

[S57] C++：编译期常量
来源：http://dali.yj20258888.top/Article/details/gtlgywqqpv.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtwemmtzjn.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gttfjjbxrn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtlhuhensa.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtxokitwzf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gteuawvdip.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtstsgfrzw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258.top/Article/details/gtrlzkomph.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtyxmyhjtg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtnpamcrxn.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtubitrzcg.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtnnvoxbdr.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gtxnxxctzp.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtondhbwmj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zycfv.cn/Article/details/gtzfdrncie.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtzesmbjve.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtymircbdv.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtmsndhtwr.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gtbdzmjufd.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtriykkfjc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuxming.cn/Article/details/gtixtmhdxu.html

[T06] Kotlin：集合映射
来源：http://dali.meibo888.top/Article/details/gtoibngquk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gtbwiwybfo.html

[T07] Kotlin：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtwyhkhnya.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.iojbl.cn/Article/details/gtndcdbgfq.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtotlqlmbh.html

data class User(val name: String, val age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtfxvmxijh.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gtgjaszlho.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtkbhrzjkj.html

[T10] Kotlin：默认参数
来源：http://dali.fzhhl.top/Article/details/gtkygaohsl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtxujgmbmg.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtitdeepdm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gthidhtaha.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtzzoyhacc.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtfbfqmjtd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtgwddbwnh.html

val m = mapOf("a" to 1)
来源：http://dali.dashuyun.cn/Article/details/gtphgjehvv.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbljovra.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmomspyd.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtsjhxbkjh.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtjobljnjs.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtbqpowrgd.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtjkbicmce.html

[T17] Swift：变量与常量
来源：http://dali.xinyue.icu/Article/details/gtzwubhfqf.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtcxvfakri.html

[T18] Swift：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtegsajcbw.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gttmqfklbv.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtcdzbhzgh.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gtsoeambyh.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gtupbsqpue.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtatbiwqvp.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gtfoshmvof.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gtsrmtwqvs.html

[T22] Swift：字典
来源：http://dali.guannengcc.top/Article/details/gtjddrvefz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqgtmgfi.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gtfcewukyb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gtvussprsp.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtwhmlikau.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gtnmzrpfzj.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gtzvpafnpl.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtggbusoss.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtmnwjhhmt.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtkzeuckzd.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtybpetscp.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gtwgcowqid.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gtodtynqcx.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gtvajawmsf.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtahxbaewo.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtzlkinzad.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtfoxyulrz.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtoysqvdph.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtbmtzxtwb.html

print("Hello")
来源：http://dali.xuanzx.com/Article/details/gtlgtvnorw.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtqdschpwm.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtpdrdqhsk.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtdlpnvnvj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gthbczoatm.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdxfgcpg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtkddptyok.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtksprjomz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.9152youxi.cn/Article/details/gtjztcsljt.html

[T36] Lua：函数
来源：http://dali.yj202588.top/Article/details/gtogmnrtsj.html

function add(a, b) return a + b end
来源：http://dali.yueranfly.top/Article/details/gtocznqrcp.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtzotztuki.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtuntqelqm.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gtggkvbvaw.html

if x > 0 then print("正") end
来源：http://dali.aizwys.cn/Article/details/gtmlvaqinf.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtopdsohnh.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtmbdsivbd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gtvlqfgdfp.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgekxwry.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtgoddfzdu.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtghtgatzp.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzxzbuob.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtlykdkeyr.html

[T43] Perl：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtchbrajsl.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gtqhnwlfdh.html

[T44] Perl：条件
来源：http://dali.aizwys.cn/Article/details/gthrdgoaye.html

if ($a > 0) { print "正"; }
来源：http://dali.zhixingplan.top/Article/details/gtmeqowqrm.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtrdbqbcyc.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtsusntxck.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtyzzzobgq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeqbdlfh.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtclimtuod.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtyphbqxmg.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gtnyjpfzkt.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gtjbfoocwl.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtbikniaax.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gturcnkpzx.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtvicxvmdh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxinkj.top/Article/details/gtizaeormx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtvqsnucwt.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtzlpgphzs.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtwweuospx.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtybbqlsbp.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gthyzsrpqb.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gthfmhwjkc.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomiulcof.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtnljlzwxg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.iojbl.cn/Article/details/gtaihpovdx.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gtfnqtnfng.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtldmsbwew.html

[T56] Scala：样例类
来源：http://dali.meibo888.top/Article/details/gtlbsgdglr.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gttpwbvuwx.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtrwpwlduw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtqcjkjsnw.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtdwbxoicd.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtxssqsdhw.html

[T59] Scala：循环
来源：http://dali.havefunace.top/Article/details/gtlnltspnb.html

for (i <- 1 to 10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtkhjqzpfh.html

[T60] Scala：折叠
来源：http://dali.xinyue.icu/Article/details/gtvxjeyikh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sxryk.cn/Article/details/gtyuglvpoq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzwrtjyyn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtjzjpvbfd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtvrroezds.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gtiftrutzy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gteqfhbffm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gtfokbxvqj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtwkdyddhc.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtadktsgkg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtzhvsemic.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskqxympq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gtsnmkqdjz.html

[U05] Py：列表去重且保序
来源：http://dali.jyoumei.cn/Article/details/gtncityfpj.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtoscqcsdn.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gtaarvafpc.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gtmrknusbc.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gtwtgjltkm.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gtnuudtgyk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gtsvwuyxbr.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtmgqxsure.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtswdicpvj.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtoryxztvn.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gtcyymfysf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fengsongda.top/Article/details/gtnadsfyzp.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtzvdrevfn.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gtarsmnwiv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtiumyjzyb.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gtzcsgxpqj.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtnomivjxx.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtxypkqqoc.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gtdssxqalt.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtnxuejiol.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gttghplgni.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtbcmawgdz.html

[U16] Py：命令行参数解析
来源：http://dali.gogol.net.cn/Article/details/gteyzmebrg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gtxsxcydlh.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gtmwfytkeq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258888.top/Article/details/gtokzbfkhf.html

[U18] Py：预编译正则
来源：http://dali.shuidangran.top/Article/details/gtcgloerfs.html

pat = re.compile(r"\d+")
来源：http://dali.jinqigufen.top/Article/details/gtmrbjqkff.html

[U19] Py：正则替换带回调
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrggtofyf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjthqbeuc.html

[U20] Py：缓存函数结果
来源：http://dali.cashguo.top/Article/details/gtmyrxnzha.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtpjyfckic.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gtscowhgce.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtulazoosc.html

[U22] Py：矩阵转置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgdjupgr.html

list(zip(*m))
来源：http://dali.chenjidiqi.icu/Article/details/gtzxmbutuw.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gttzffvknb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gtfjdwaajk.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gtxqsprjgi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtcpdnhpoz.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gteremnlyf.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbodvhukb.html

[U26] Py：并发下载
来源：http://dali.shzxlz.cn/Article/details/gtjckrovxb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gtficoieyo.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtraydyiro.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhiwuduotai.top/Article/details/gtkgzfrdzk.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gtnilfwgig.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtdwpgzbxu.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gtfvelwhps.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtsgkjpocx.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gtpqxencdf.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gttfjbsflc.html

[U31] Py：单测
来源：http://dali.wangshuangyany.cn/Article/details/gtsuovghhm.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtxbnwsgzq.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtcovxjahc.html

ruff format . && ruff check --fix .
来源：http://dali.zdqjudy.top/Article/details/gtcblxxknn.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtyyfaixqz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gtuykvgxya.html

[U34] Py：判断编码
来源：http://dali.feifeiyinyue.top/Article/details/gtyzlmgtwf.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gtlwpvxoch.html

[U35] Py：发送邮件
来源：http://dali.aizwys.cn/Article/details/gtozphqwwi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhengqikj.top/Article/details/gtevdahdvp.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gthjawvwjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.ydzc1.top/Article/details/gthbyxwita.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtfhczmbgx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhengqikj.top/Article/details/gtgnibcdha.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gtmnteqwph.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtpdybkbfj.html

[U39] Py：判断是否在交互环境
来源：http://dali.cashguo.top/Article/details/gtururphwk.html

sys.stdout.isatty()
来源：http://dali.gzhubu.top/Article/details/gtbwimrpiw.html

[U40] Py：打印到标准错误
来源：http://dali.hammf.cn/Article/details/gtgfgkhdci.html

print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gttxfymfvl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxuanxn.top/Article/details/gtxevnxevg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fzhhl.top/Article/details/gtrhbkcemr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gttddymdye.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhiwuduotai.top/Article/details/gtsohdtsub.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gtgiyxqpji.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gtbcmpkjql.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtidmtzwtz.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gthlahzqiv.html


<!-- 参考信息 -->